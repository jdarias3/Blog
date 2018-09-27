#json-ld version
```js
<script type="application/ld+json">
"@context": "http://schema.org/",
"@type": "Recipe",
"name": "Nombre de la receta",
"author": "Nombre del autor",
"image": "Ruta de la imagen que queremos que se vea en la tarjeta"
"aggregateRating": {
    "@type": "AggregateRating",
    "ratingValue": "4.5",
    "reviewCount": "276",
    "bestRating": "5",
    "worstRating": "1"
  },
  "prepTime": "PT30M",
  "totalTime": "PT3H",
  "recipeYield": "8",
  "nutrition": {
    "@type": "NutritionInformation",
    "servingSize": "1 medium slice",
    "calories": "230 calories",
    "fatContent": "1 g",
    "carbohydrateContent": "43 g",
    "cholesterolContent": "0 mg",
    "fiberContent": "1 g",
    "proteinContent": "1 g",
    "saturatedFatContent": "2 ½ g",
    "servingSize": "1 Serving",
    "sodiumContent": "200 mg",
    "sugarContent": "27 g",
    "transFatContent": "0 g"
  },
  "recipeIngredient": [
    "1 box Pillsbury™ refrigerated pie crusts, softened as directed on box",
    "6 cups thinly sliced, peeled apples (6 medium)",
    "3/4 cup sugar",


<script type="application/ld+json">
{
  "@context": "http://schema.org",
  "@type": "Event", //declarando una tarjeta enriquecida tipo evento
  "name": "Concierto ACDC", //nombre del evento
  "startDate" : "2013-09-14T21:30", //fecha del evento
  "url" : "http://example.com/tourdates.html", //URL con información del evento
  "location" : {
    "@type" : "Place", //declarando datos tipo lugar
    "sameAs" : "http://www.hi-dive.com", //URL lugar del evento
    "name" : "The Hi-Dive", //nombre del lugar
    "address" : "7 S. Broadway, Denver, CO 80209" //dirección del lugar
  }
}
</script>
```
