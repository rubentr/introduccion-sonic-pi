---
layout: presentation 
---

## Las notas hacen referencia a frecuencias...

```
use_synth :fm
print "Escala normal"
escala = [:c,:cs,:d,:ds,:e,:f,:fs,:g,:gs,:a,:as,:b,:c5]
escala.each do |nota|
  play nota
  print midi_to_hz(nota)
  sleep 0.5
end
```