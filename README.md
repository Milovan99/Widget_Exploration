# Widget Exploration

## O aplikaciji 

<img src="https://user-images.githubusercontent.com/29107405/216350319-da81b2f7-5b2d-4bcb-84cf-627d1f827238.png">

Ova aplikacija sadrži Kotlin kod za glavnu aktivnost Android aplikacije. Aktivnost proširuje klasu AppCompatActivity i nadjačava metodu onCreate.

Kod postavlja prikaz sadržaja na R.layout.exploration_layout i implementira sljedeće ponašanje:

Polje za potvrdu "Transparentnost" menja alfa vrijednost imageViewa između 0,1 i 1.
CheckBox "Nijansa" menja filter boja za imageView između crvene sa alfa 150 i transparentne.
Polje za potvrdu "Promena veličine" menja skalu imageViewa između 2 i 1.
RadioGroup menja vremensku zonu tekstualnog sata na osnovu odabranog radio dugmeta između Londona, Pekinga, New Yorka i Evrope.
Dugme postavlja tekst textView na tekst unet u editText.
Switch čini textView vidljivim ili nevidljivim na osnovu njegovog stanja.
