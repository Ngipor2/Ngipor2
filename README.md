def myFunc(e): #Funkcijas ir atkārtoti lietojamas koda daļas, kas palīdz mums sakārtot koda struktūru.
    return e['year'] #Python atgriešanas priekšraksts ir galvenā funkciju un metožu sastāvdaļa
cars = [ 
{'car':'Volvo', 'year': 2015}, 
{'car': 'Toyota', 'year': 2020}, 
{'car': 'BMW', 'year': 2019}, 
{'car': 'VW', 'year': 2021} 
{'car': 'Hyundai', 'year': 2021}
] #saraksts

cars.sort(key=myFunc) #Metode sort() sakārto sarakstu augošā secībā pēc noklusējuma.
print(cars) #
