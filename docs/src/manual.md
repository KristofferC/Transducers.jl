# Transducers and Transducible processes

```@index
Pages = ["manual.md"]
Order = [:function, :type]
```

## Transducible processes

```@docs
transduce
foldl
foreach
reduce
dreduce
dtransduce
eduction
map!
copy!
copy
tcopy
dcopy
append!
Transducers.append!!
collect
tcollect
dcollect
Channel
```

### Experimental transducible processes

```@docs
Transducers.channel_unordered
Transducers.append_unordered!
```

## Transducers

```@autodocs
Modules = [Transducers]
Private = false
Filter = Transducers.is_transducer_type
```

### Experimental transducers

```@docs
Transducers.TeeZip
Transducers.GetIndex
Transducers.SetIndex
Transducers.Inject
```

## Early termination

```@docs
Reduced
reduced
unreduced
ifunreduced
```

## Miscellaneous

```@docs
Transducer(::Transducers.Comprehension)
Transducer(::OnlineStats.OnlineStat)
reducingfunction
Completing
OnInit
CopyInit
right
setinput
AdHocFoldable
withprogress
```

## Deprecated

```@docs
mapfoldl
mapreduce
```
