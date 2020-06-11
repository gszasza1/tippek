# Értékadás
Előfodul, hogy valami szerint kell értéket beállítanod. Erre van több jó shorhand kifejezés, nem kell bonyolul if-ele ágat készíteni

## ?:
Ha a feltétel amit vizsgálsz értéke truthy, Akkor első, különben második értéket kapja.

```javascript
const almaExist=true;
const alma=almaExist ? ”Létezik” : ”Nem létezik”	//Alma értéke Létezik lesz
```

## ||
Ha a feltétel amit vizsgálsz értéke truthy, akkor azt az értéket kapja, különben második 
```javascript
let almaExist=”Van bennem string így truthy vagyok”
const alma=almaExist || ”Nem létezem” //alma értéke: ”Van bennem string így truthy vagyok”
almaExist=false
const korte=almaExist || ”Nem létezem”  //korte értéke: "Nem létezem"
  ```
## ??
Ha nem null vagy undefined akkor legyen az az értéke, különben a másik
```javascript
let almaExist=”Van bennem string így truthy vagyok”
const alma=almaExist ?? ”Nem létezem” //alma értéke: ”Van bennem string így truthy vagyok”
almaExist=false
const korte=almaExist ?? ”Nem létezem”  //korte értéke: false
  ```
