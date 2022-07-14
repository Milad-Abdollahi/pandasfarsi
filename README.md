# pandasfarsi
working with some csv files that include some farsi comments
choosing the right text encoder is importan when importing farsi comments

using the read_csv function shoud be like this:
# data_frame = pd.read_csv('farsi_comments 2.csv', encoding = "cp1256")

for the list of all encoders visit : https://docs.python.org/3/library/codecs.html#standard-encodings
