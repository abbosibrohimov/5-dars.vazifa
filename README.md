def myfunc(my_string):
    my_list=[]
    for index, letter in enumerate(my_string):
        if index %2==1:
            my_list.append(letter.upper())
        else:
            my_list.append(letter.lower())
    print(my_list)
        
myfunc('Anthropomorphism')
