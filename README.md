# CebelcaBIZ-OpenCart

To je dodatek za najnovejši Opencart 3.0.3.7. Za razliko od prejšnjih dodatkov ne potrebuje vqMod, ampak uporablja ocMod, ki je že v osnovi dodan Opencart 3.x. To naj bi poenostavilo namestitev na vaš sistem.

### Kako namestiti

Pojdite na OpenCart administracijo:
* Pojdite na "Extensions > Installer" in izberite datoteko "invfox10.ocmod.zip" in dodatek se bo namestil
* Pojdite na "Extensions > Modifications" in kliknite "Refresh" ikono zgoraj desno
* Pojdite na "Extensions > Extensions" in izberite "Modules" iz izbirnega seznama
* Poiščite "Invoicefox Mod" ter na desni pritisnite "Install"
* Potem pritisnite "Edit" tipko, vnesite API ključ iz Čebelca BIZ dostopa ter npr. še DDV, ki naj se zaračuna pri poštnini

### Primer uporaba

* Ko prejmete naročilo ga odprete
* Odvisno od nastavitev, a ko mu nastavite status "Processed" se v Čebelci kreira Osnutek računa
* V zgodovini naročila boste videli tipko "Finalize invoice", ki izda račun (odvisno od nastvitev v čebelci in pluginu, ali se bo davčno potrdil ali ne)
* Ko naročilu določite status "Completed" se zabeleži plačilo

Če račun preko plugina izdajate prvič preverite kako se je prenesel v Čebelco in ga šele potem tam Izdajte. Še posebej če imate aktivirano davčno potrjevanje.
Predvsem bodite pozorni na davke in poštnino.

### Izjava

Moduli so na voljo kot so. Za namestitev na svoj strežnik morate poskrbeti sami, če najdete kakšne težave v dodatkih nas prosim obvestite o njih, še bolje pa če jih odpravite in nam pošljete spremembe preko Github sistema.

## English

This plugin works on newest OpenCart 3.0.3.7. It doesn't require vqMod, but uses ocMod, which is already included in opencart 3.x.

### How to install

Go to OpenCart admin. In the menu on the left click: 
 * Extensions > Installer
 * Select a invfox10.ocmod.zip file and extension is installed
 * Go to Extensions > Modifications and click Refresh icon on the right
 * Go to Extensions > Extensions and select Modules from drow-down list
 * Find Invoicefox mod and click green button "Install" on the right
 * Click the Edit button on the right and use the form to setup the plugin

More about settings can be seen here: https://www.cebelca.biz/help-integration-opencart.html
