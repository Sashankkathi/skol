alphabet = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z']
text_encode= input("Enter your text to be encoded\n").lower()
shift= int(input("Enter shift number\n"))
def encode(text_1, shift_1):
    string=""
    for letter in text_1:
        position = alphabet.index(letter)
        new_position = (position + shift_1)%26
        string = string + alphabet[new_position]
    print(string)
encode(text_encode,shift)
text_decode = input("Enter your text to be decoded\n").lower()
shift_decode = int(input("Enter shift number\n"))
def decode(text_2, shift_2):
    str=""
    for letter in text_2:
        de_position = alphabet.index(letter)
        new_de_position = (de_position - shift_2)%26
        str = str+alphabet[new_de_position]
    print(str)
decode(text_decode,shift_decode)

