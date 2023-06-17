import phonenumbers
from phonenumbers import geocoder
phone_number1=phonenumbers.parse("+917075344945")
phone_number2=phonenumbers.parse("+916304289945")
phone_number3=phonenumbers.parse("+917981887507")
phone_number4=phonenumbers.parse("+918096692468")

print("\nphone Numbers Location\n")
print(geocoder.description_for_number(phone_number1,"en"));
print(geocoder.description_for_number(phone_number2,"en"));
print(geocoder.description_for_number(phone_number3,"en"));
print(geocoder.description_for_number(phone_number4,"en"));

