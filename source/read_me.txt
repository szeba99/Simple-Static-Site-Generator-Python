HUN

Az eszköz a következő képpen működik:

Létrehozol egy templatet(egy komplett html oldalt), amibe variable-ket helyezel valahogy így:

<body>
    {{ CONTENT1 }}
</body>

Ez után létrehozol egy csak html formázású szöveget tartalmazó fájlt, amit kommentekkel látsz el.

<!-- |ELEMENT|IDE_ÍROD_A_VARIABLE_NEVÉT|BLOCK -->
<h1>Üdvözlet!</h1>
<p>Ez egy weboldal.\nEgy jó hely.<p>

<!-- |ELEMENT|CONTENT2|BLOCK -->

<p>

Egymás után több különböző blokkot létrehozhatsz, 
fel fogja ismerni a program, és behelyettesíti az adott helyre.


</p>

Ezek után csak belehúzod a szövegfájljaidat a .BAT fájlba, és az a PARENT mappában
generál neked statikus oldalt. voálá.

SZÓKÖZÖK HASZNÁLATA A FÁJLNÉVBEN BRUTÁLIS PUSZTÍTÁST OKOZHAT! FIGYELMEZTETTELEK!

-------------------------------------------------------------------------------------------------

EN

Create a template (A complete html site), and add variables in such fashion:
<body>
{{ VARIABLE1 }}
</body>

Then create html files you wish to use as content. Add such comments like in the examples, to indicate
what to fill those variables in with.

After this, just drag n' drop any html files onto the bat and it will generate your static site in the 
PARENT FOLDER.

DO NOT USE SPACES IN FILENAMES! IT CAUSES BRUTAL CATASTROPHES! I WARNED YOU!