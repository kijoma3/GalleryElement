1. Am ende des Bodys gat.Element.js mit type=module einbinden.

2. <my-gallery>-Tag Verwenden und im Attribut "imgs" die Bildnamen mit Komma getrennt schreiben.

Das my-gallery Element sollte in einem Container sein der die Größe festlegt.

EINBINDUNG
<body>
…
<script src="[PFAD]/galElement.js" type="module" />
</body>

NUTZUNG
<div>
<my-gallery imgs="bild1.jpg, bild2.jpeg, bild3.png, ...">
</div>