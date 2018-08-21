# Untuk KNN (dengan class)

## Input:
- data_train dalam bentuk csv
- data_test dalam bentuk array
- k (berapa banyak tetangga)

## Output:
- Nama label dari dataset

## Cara Pakai:
1. Input nilai k pada class KNN
2. Assign ke dalam variabel baru, misalkan 'hasil'.
> hasil=KnnModel(3)
3. Input data training
> hasil.import_data_train("namafile.csv")
4. Input data testing
> hasil.import_data_test([])
5. Cari hasilnya
> hasil.predict()

# Untuk KNN (tanpa class)

Input dan Output tetap sama. Yang berbeda yaitu:
> data_train, data_test, dan k harus dimasukkan manual ke dalam codingan

Masukkan data_train pada #Importing Data, data_test pada #Input Data Test, dan nilai k pada #Search For The Result.

Untuk yang baru belajar python disarankan untuk mempelajari codingan melalui knn_without_class karena lebih mudah dimengerti.

## Kenapa bikin yang class?
Meskipun lebih sulit, class sesungguhnya mempermudah kita supaya ketika ada 1 bagian yang salah, hanya 1 bagian itu saja yang _error_, sedangkan bagian yang lain tidak. Class seperti membagi-bagi tugas kepada kelompok-kelompok.

Class masuk ke dalam OOP (_Object Oriented Programming_), sedangkan algoritma dalam knn_without_class masuk ke dalam prosedural (jika ada 1 yang salah maka langsung error semuanya).