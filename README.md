# Country-Converter-Toolkit-
from Modul.modul1 import search_country_code
from Modul.modul2 import get_country_info
from Modul.modul3 import get_country_language
from Modul.modul4 import get_info_by_country_code
from Modul.modul5 import currency_conversion
from Modul.modul6 import convert_city_time
from Modul.modul6 import convert_time

print(search_country_code("Palestine"))
print(get_country_info("indonesia"))
print(get_country_language("Palestine"))
print(get_info_by_country_code("ID"))
print(currency_conversion(10, "USD", "IDR"))
print(convert_city_time("Indonesia", "Dubai", "08-10-2024 21:57:00"))
