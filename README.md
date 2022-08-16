# Object Oriented Programming

## University Management System

* There are classrooms, study offices and departments belonging to the university.

* There are offices belonging to the departments.

* There are university employees. These employees can be professors or officer.

* Every employee works in an office.

***Draw the Class diagram describing this system.***

**Note:** It is not necessary to specify the attributes and behaviors of the classes.

## Zoo Management

Bir hayvanat bahçesindeki hayvanlar hakkındaki bilgileri takip etmek için bir sistem tasarlıyorsunuz.

* Hayvanlar:
* Atlar (atlar, zebralar, eşekler vb.),
* Kedigiller (kaplanlar, aslanlar vb.),
* Kemirgenler (sıçanlar, kunduzlar vb.) gibi gruplardaki türlerle karakterize edilir.
* Hayvanlar hakkında depolanan bilgilerin çoğu tüm gruplamalar için aynıdır.
tür adı, ağırlığı, yaşı vb.
* Sistem ayrıca her hayvan için belirli ilaçların dozajını alabilmeli => getDosage ()
* Sistem Yem verme zamanlarını hesaplayabilmelidir => getFeedSchedule ()
* Sistemin bu işlevleri yerine getirme mantığı, her gruplama için farklı olacaktır. Örneğin, atlar için yem verme algoritması farklı olup, kaplanlar için farklı olacaktır.

Polimorfizm modelini kullanarak, yukarıda açıklanan durumu ele almak için bir sınıf diyagramı tasarlayın.
