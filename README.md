# week1-kotlinperusteet

# Datamalli
Sovellus käyttää Task data classia tehtävien kuvaamiseen. Tehtävällä on id, prioriteetti, kuvaus, määräpäivä ja tieto onko tehtävä tehty. Tehtävän prioriteetti määritellään prioriry enumilla jotka ovat LOW, MEDIUM, HIGH. Mocktasks on esimerkkilista jota käytetään sovelluksen testaamiseen.

# funktiot
addTask lisää uuden tehtävän
filterbydone suodattaa tehtävä tehtyihin ja tekemättömiin
sortbyduedate järjestää tehtävät määräpäivän mukaan
toggledone vaihtaa tehtävän done tilan
