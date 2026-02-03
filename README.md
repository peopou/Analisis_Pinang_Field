# Judul Project
Analisis Produksi Pinang Field

## Repository Outline
```
1. README.md - Penjelasan gambaran umum project
2. Analisis.ipynb - Notebook yang berisi pengolahan data dengan python
3. dATA.xlsx - berisi data yang akan dianalisis
4. production.xlsx - berisi data yang akan diinput ke tableu
dst.
```

## Problem Background
```
Analisis sebuah lapangan migas perlu dilakukan sebelum lapangan tersebut akan didevelopment untuk menentukan strategi yang akan dilakukan terhadap lapangan tersebut. Pada case ini akan dilakukan analisis terhadap lapangan pinang field guna mengumpulkan berbagai informasi atau insight dari lapangan ini, namun informasi dari lapangan ini sangat terbatas hanya berupa produksi minyak dan air harian tanpa ada data reservoir dan development apa saja yang telah dilakukan terhadap lapangan ini, sehingga analisis kali ini hanya berfokus pada trend dari produksi lapangan pinang
```

## Project Output
```
pada projek kali ini menghasilkan sebuah dashboard interaktif tablue 
link : https://public.tableau.com/views/P0M1_ahmadkurniawan/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
```

## Method
'''
pada projek ini dilakukan analisis untuk menjawab pertanyaan 
1. Berapa total produksi setiap sumur
2. Cek persebaran data (normal atau tidak normal)
3. Bagaimana hubungan produksi minyak dan air dari pinang field
4. Mengevaluasi efisiensi produksi minyak terhadap air (Oil–Water Ratio / OWR)
5. Bagaimana trend penurunan produksi minyak terhadap waktu
6. Menentukan sumur dengan potensi produksi terbaik berdasarkan watercut
'''
## Stack
- pandas
- scipy.stats
- matplotlib
