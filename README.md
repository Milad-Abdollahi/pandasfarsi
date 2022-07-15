## pandasfarsi
working with a csv files that includes some farsi comments

choosing the right text encoder is important when reading farsi/arabic csv files

to use the pandas.read_csv() function do it like this:
data_frame = pd.read_csv('name_of_the_file.csv', encoding = "cp1256")

for the list of all encoders visit : https://docs.python.org/3/library/codecs.html#standard-encodings

the farsi letter (ی) sometimes creates problems when reading a csv file
to solve the problem use arabic (ي) ==>keyboard: [SHIFT] + [X]

using the read.excel function is better for preventing the problems mentioned above

# sourse of data : https://bigdata-ir.com/
