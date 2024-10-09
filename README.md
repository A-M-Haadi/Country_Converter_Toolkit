# Country-Converter-Toolkit
The Country Converter Toolkit is a collection of modules that provide various functions for converting and retrieving country-related information.

from Modul.modul1 import search_country_code

print(search_country_code("Palestine"))
search_country_code(country_name): Returns the ISO 3166-1 alpha-2 country code for the given country name

from Modul.modul2 import get_country_info
print(get_country_info("indonesia"))

from Modul.modul3 import get_country_language

print(get_country_language("Palestine"))

from Modul.modul4 import get_info_by_country_code

print(get_info_by_country_code("ID"))

from Modul.modul5 import currency_conversion

print(currency_conversion(10, "USD", "IDR"))


from Modul.modul6 import convert_city_time
from Modul.modul6 import convert_time

print(convert_city_time("Indonesia", "Dubai", "08-10-2024 21:57:00"))
