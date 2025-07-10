<a href="https://www.buymeacoffee.com/kratkyt" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>
# Tapo-T315-csv-to-docx
![IMG_0004](https://github.com/user-attachments/assets/af25eea2-9c39-4952-a632-00d158b1b5bc)
![VakrT315](https://github.com/user-attachments/assets/a15744f8-b3a0-426a-a1b0-a77945d1d901)


Aplikace pro zpracování .csv dat z TAPO T315 a uložení do Word dokumentu (.docx). Využití je pro zachování naměřených hodnot v tiskové podobě. Aplikace zobrazuje případné teplotní alarmy. Před prvním spuštěním aplikace upravte soubor 'nastaveni.xml':

\<UPPERLIMIT>35</UPPERLIMIT\> - horní limit teploty

\<LOWLIMIT>20\</LOWLIMIT\> - nejnižší limit teploty

\<place0> - \<place4\> - Zde si můžete předvolit umístění teplotního senzoru - je uvedeno v protokolu
Je možné volitelně upravit 'sablona.docx'. POZOR, neupravujte umístění placeholderů (\#) v šabloně  !
Aplikace podporuje Drag and Drop (pouze přetáhnout .csv soubor do okna aplikace)

(EN)

Application for processing .csv data from TAPO T315 and saving it to a Word document (.docx). It is used to preserve measured values in print form. The application displays any temperature alarms. Before running the application for the first time, edit the 'nastaveni.xml' file:

\<UPPERLIMIT>35</UPPERLIMIT\> - upper temperature limit

\<LOWLIMIT>20\</LOWLIMIT\> - lower temperature limit

\<place0> - \<place4\> - Here you can preselect the location of the temperature sensor - it is specified in the protocol
You can optionally edit 'template.docx'. CAUTION, do not edit the location of placeholders (\#) in the template  !
The application supports Drag and Drop (just drag the .csv file into the application window)

