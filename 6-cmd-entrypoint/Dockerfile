FROM ubuntu:18.04

ENTRYPOINT ["sleep"]



# Eğer entrypoint'i sadece yalnız başına bu şekilde bırakırsak error vericek tabi cmd'de belli bir sayı girmezsek bunun önüne
# şu şekilde geçiyoruz eğer default bir değer vermek istiyorsak ENTRYPOINT'ten sonra bizlerinde bir CMD [""] komutu oluşturmamız gerekiyor.
# CMD ["sleep","4"]
# CMD sleep 4 diye de yazabiliriz.
# Eğer cmd komutunda ekstradan bir komut girersek eğer burdaki arrayi kaldırır ve bizim cmd'de yazdığımız komutu override eder
