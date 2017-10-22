# raupjc-hw0

# Pitanje 1:
Bin/Debug folder ima u ovom slučaju više file-ova, odnosno pojavili su se ClassLibrary.dll i .pdb file-ovi.
Ukoliko obrišemo .dll file i potom pokrenemo .exe file dolazi do Unhandled Exceptiona. Po tome zaključujemo da ukoliko želimo poslati upotrebljivu aplikaciju, moramo poslati .exe file i .dll class library projekta.

# Pitanje 2:
Konzolna je aplikacija koristila novu verziju class library asemblija, odnosno pokazala novi string jer konzolna aplikacija ovisi o class libraryju pa kad pokrećemo nju, builda se automatski i class library projekt.

# Pitanje 3:
Build proces je prošao najnormalnije, a nakon njega direktorij NodaTime se opet pojavio unutar packages direktorija
