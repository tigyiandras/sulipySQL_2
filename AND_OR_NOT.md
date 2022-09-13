# sulipySQL_2

1. Feladat
Írj SQL utasítást amely az online tesztadatbázis 'Suppliers' táblájából lekérdezi

a, azon beszállítók nevét (SupplierName) és országát, akiknek a székhelye az USA-ban vagy UK-ban van,

  SELECT SupplierName FROM Suppliers WHERE Country='USA' OR Country='UK';

b, azon beszállítók nevét (SupplierName) és városát, akiknek a székhelye az USA-ban Bostonban vagy New Orleansban van,

  SELECT SupplierName, City FROM Suppliers WHERE Country='USA' AND (City='Boston' OR City='New Orleans');
  
c, azon beszállítók nevét (SupplierName) és országát, akiknek a székhelye nem Japánban vagy Kanadában van!

   SELECT SupplierName, Country FROM Suppliers WHERE NOT Country='Japan' AND NOT Country='Canada';
   
 2. Feladat
Írj SQL utasítást amely az online tesztadatbázis 'Products' táblájából lekérdezi 

a, a termékek nevét és árát ár szerint növekvő sorrendben,

  SELECT Productname, Price FROM Products ORDER BY Price;
  
b, a termékek nevét és árát ár szerint csökkenő sorrendben,

  SELECT Productname, Price FROM Products ORDER BY Price DESC;
  
c, a termékek nevét és egységét név szerint növekvő, azon belül egység szerint csökkenő sorrendben!

  SELECT ProductName, Unit FROM Products ORDER BY Unit DESC;
  


  

  























































