# FitTrak food packs

Offline product packs for the [FitTrak](https://github.com/Kristiii101) app. Each pack is a SQLite
file with the food products sold in one country, so barcode scanning and food search work without
internet. The app downloads `packs.json` from the latest release and then the pack for the user's
country.

| Pack | Country |
| --- | --- |
| `ro.db` | România |

## Contents

- Product names (the country's language, English and the product's main language), brand, barcode,
  energy, protein, carbohydrates, fat, fiber, serving size, and vitamins and minerals when listed.
- `categories`: the median vitamin and mineral values of products in each Open Food Facts category,
  computed from products worldwide that list them. The app uses them to **estimate** values a
  product does not list, and marks them as estimated.

## Source and licence

Contains data from [Open Food Facts](https://world.openfoodfacts.org), available under the
[Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/). Individual
contents are under the [Database Contents License](https://opendatacommons.org/licenses/dbcl/1-0/).

The packs are an adapted version of the Open Food Facts database and are themselves made available
under the ODbL 1.0. You may use, share and adapt them under the same terms: keep this attribution
and licence notice, and share any adapted database under the ODbL.

Estimated values are typical values of similar products, not measurements. Data may be incomplete
or wrong; it is provided as is, without warranty. It is not medical or dietary advice.
