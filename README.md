# Binary Search Tree Projesi

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

* Bu dizide root olarak 7'yi aldım. Rootun sağına 7'den büyükleri solunada 7'den küçükleri yazıyoruz. 
* Bu durum her dallanmada o daldaki sayıdan büyükleri sağına o daldaki sayının küçüklerini soluna yazıyoruz.

![çaşıma görseli](https://i.hizliresim.com/6g6dait.png)

- Root 7'dir, 5 solunda bulunur.
- 1, 5'ten küçüktür 5'in solunda bulunur.
- 8, root yani 7'den büyüktür, 7'nin sağında bulunur.
- 3, 7'den küçüktür, soluna bakılır, solunda 5 var, 5'ten de küçüktür 5'in soluna bakılır, 1 var, 1'in sağına eklenir.
- 6, 7'den küçüktür, soluna bakılır, solunda 5 var, 5'ten büyüktür, 5'in sağına eklenir.
- 0, 7'den küçüktür, soluna bakılır, solunda 5 var, 5'ten de küçüktür 5'in soluna bakılır 1 var, 1'in soluna eklenir.
- 9, 7'den büyüktür, sağına bakılır 8 görünür ve 8'in sağına eklenir.
- 4, 7'den küçüktür, soluna bakılır, solunda 5 var, 5'ten de küçüktür, 5'in soluna bakılır 1 var, 1'in sağına bakılır 3 var, 3'ün sağına eklenir.
- 2, 7'den küçüktür, soluna bakılır, solunda 5 var, 5'ten de küçüktür, 5'in soluna bakılır 1 var, 1'in sağına bakılır 3 var, 3'ün soluna eklenir.

### Patika.dev [FUAT BİŞİ](https://app.patika.dev/ftbs)