def rot13(x):
    def transform(y):
        index = 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz'.find(y)
        if index != -1:
            return 'NOPQRSTUVWXYZABCDEFGHIJKLMnopqrstuvwxyzabcdefghijklm'[index]
        else:
            return y

    return "".join(map(transform, x))

my_file = open("some.txt", "r")
my_string = my_file.read()
my_file.close()

my_file1 = open("some1.txt", "x+") #если такого еще нет то он будет создан 
a = (rot13(my_string))
my_file1.write(x)
my_file1.write("\n")
my_file1.close()
