# mrg_sort_projec
Merge Sort Projec
# ***Merge Sort Projec***
## [16,21,11,8,12,22]
- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

                        [16,21,11,8,12,22]   ---> Burada dizinin tam ortasından parçalama işlemi 
                         /              \            gerçeleştirildi. Bu parçalama işlemi diğer
                  [16,21,11]           [8,12,22]     adımlarda da devam etti.
                    /     \               /   \
               [16,21]   [11]          [8,12] [22]    ----> Parçalamış  dizileri kendi 
                                                        aralarında sıralama işlemi gerçekleşti.
                [11,16] [21]           [8,12] [22] 
                       |                     |
                   [11,16,21]             [8,12,22] 
                          \                 /
                           [8,11,12,16,21,22] ----> Kendi aralarında sıralanan dizileri
                                                     birleştiriyoruz.
- Big-O gösterimini yazınız.

**Time complexity o(nlogn)** formülü ile hesaplanır. Bunu dikkate aldığımızda  **o(6log6)** dır.   

[PatikaDev profilim](https://app.patika.dev/mrvalgi)

[https://app.patika.dev]
                   
