## AngularJS objectForm 
Direktiva umožňující jednoduché úpravy a vytváření JS objektů pomocí HTML formuláře
![Alt objectForm](http://obrazky.auto-makler.cz/obrazky/objectform.png)

#### Paremetry direktivy
object - reference na objekt v nějakém scopu (direktiva sama sleduje zmeny, lze tedy asynchronne doplnit i dele)
onSave - callback pro uložení dat
protected-property - vlsatnost nebo vlastnosti (oddělené čárkou), které v objektu nebude možné měnit (ani mazat).

#### Příklad
    <object-form object="editingObject" on-save="save('mountain',data)" protected-property="_id,provider"></object-form>