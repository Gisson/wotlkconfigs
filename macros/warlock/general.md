#### Spellstone apply/create
```
#showtooltip
/cast Create Spellstone
/use Grand Spellstone
/use 16
/click StaticPopup1Button1
```

#### Drain soul delete surplus
```
#showtooltip
/cast Drain Soul
/run i="Soul Shard"d=GetItemCount(i)-28 for x=0,4 do for y=1,GetContainerNumSlots(x)do if(d>0)then l=GetContainerItemLink(x,y)if l and GetItemInfo(l)==i then PickupContainerItem(x,y)DeleteCursorItem()d=d-1 end end end end
```

#### Shadowfire + cleave
```
#showtooltip Shadowflame
/cast Shadowflame
/cast Shadow Cleave(Demon)
```

#### Aoe + mana pot
```
#showtooltip
/cqs
/use Runic Mana Injector
/cast Seed of Corruption
```

#### Burst
```
#showttoltip
/cast Metamorphosis
/cast Demonic Empowerment
/cast Immolation Aura(Demon)
/cast Shadow Cleave(Demon)
/use 13
/use 10
/petattack
```

#### Pet attack + emp
```
#showtooltip
/cast Demonic Empowerment
/petattack
```

#### Prepot + pot
```
#showtooltip
/castsequence reset=200 Potion of Wild Magic, Potion of Speed
```