---
default: 'USD'
type: String
---
---
##### shortDescription
The default currency. Accepts a 3-letter [ISO 4217](https://www.currency-iso.org/en/home/tables/table-a1.html) code.

---
[note] [Reference Globalize or Intl](/concepts/Common/33%20Localization/05%20Localize%20Dates,%20Numbers,%20and%20Currencies '/Documentation/Guide/Common/Localization/#Localize_Dates_Numbers_and_Currencies/') if you specify a currency other than "USD".

Assign the currency code to this field if you use Intl, or do the following if you use Globalize: 

1. Get the *currencies.json* file that corresponds to your culture from a folder [here](https://github.com/unicode-cldr/cldr-numbers-modern/tree/master/main).
2. Load this file's contents in your app using a method described [here](https://github.com/jquery/globalize/blob/master/doc/cldr.md#how-do-i-load-cldr-data-into-globalize).
3. Assign the currency's 3-letter code to this field.


    <!--JavaScript-->DevExpress.config({ defaultCurrency: 'EUR' });

#####See Also#####
- [Localization](/concepts/Common/33%20Localization '/Documentation/Guide/Common/Localization/')