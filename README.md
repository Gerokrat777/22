class Vehicle:

    vehicle_type = None

class Car:

    price = 1000000

    def horse_powers(self):
        return 150



class Nissan(Car, Vehicle):
    price = '500 000 у.е.'
    vehicle_type = 'Nissan Taxi'

    def horse_powers(self):
        return 120


car = Nissan()
print(car.vehicle_type)
print(car.price)
car.horse_powers()

print()

car_ = Car()
print(car_.price)
car_.horse_powers()
