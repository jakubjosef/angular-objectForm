## AngularJS objectForm 
Direktiva umožňující jednoduché úpravy a vytváření JS objektů pomocí HTML formuláře
![Alt objectForm](http://obrazky.auto-makler.cz/obrazky/objectform.png)

#### Paremetry direktivy
object - reference na objekt v nějakém scopu (direktiva sama sleduje zmeny, lze tedy asynchronne doplnit i dele)
onSave - callback pro ulozeni dat

#### Příklad
    <object-form object="editingObject" on-save="save('mountain',data)"></object-form>