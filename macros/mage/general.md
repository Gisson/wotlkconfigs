```

```

#### Flamestrike rank rotation
```
#showtooltip
/castsequence [@cursor] reset=5 Flamestrike(rank 9), Flamestrike(rank 8)
```

#### Arcane blast nonstop AM
```
#showtooltip
/stopcasting [nochanneling, nocasting]
/use [nochanneling] Arcane Blast
```

#### Burst 
```
#showtooltip Arcane Power
/use 10
/cast Arcane Power
/cast Icy Veins
/use Global Thermal Sapper Charge 
/use 13
```

#### Quick IB
```
#showtooltip Ice Block
/stopcasting
/cancelaura Ice Block
/cast Ice Block
```

#### Util pot rotation
```
#showtooltip
/castsequence reset=120 Potion of Wild Magic, Potion of Speed
```

#### Saphire
```
#showtooltip
/use [nochanneling] Mana Sapphire
/cast Arcane Blast
/cqs
```

#### 1 button food
```
/use [group, modifier:alt] Ritual of Refreshment; [modifier:alt] Conjure Refreshment; item:43523
```