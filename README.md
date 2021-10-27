27/10/2021
Am inceput studiul la SASS 2 ore
Ce am studiat

1. Variables
2. \_Partials
3. Libraria @use 'sass:math';

---

4. Maps
   maps: $colors: (
   "primary": $primary,
   "secondary": $secondary,
   "error": $error,
   "info": $info,
   );

background-color: map-get($colors, "purple");

---

5. Debugging
   @debug map-get($colors, "purple");
@debug map-has-key($colors, "secondary");
   @debug map-has-key($colors, "tertionary");
@debug map-remove($colors, "primary");
   @debug map-merge(
   $colors,
   (
   "pink": red,
   )
   );

---
