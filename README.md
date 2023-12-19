# the-ultimate
    print("Menu :\n" "1.area of square\n" "2.area of rectanangle\n" "3.area of triangle\n" "4.area of circle\n")

    opt = int(input("enter the option:  "))

    print()

    if opt == 1 :
        side = int(input("enter the side: "))
        unit = input("enter the unit: ")
        print(side * side,unit,"²")

    if opt == 2 :
        length = int(input("enter the length: ")) 
        bredth = int(input("enter the bredth: "))
        unit = input("enter the unit: ")
        print(length * bredth,unit,"²")

    if opt == 3 :
        base = int(input("enter the base: ")) 
        height = int(input("enter the height: "))
        unit = input("enter the unit: ")
        print(1/2 * base * height,unit,"²")

    if opt == 4 : 
        radius = int(input("enter the radius: "))
        pie = 3.14
        unit = input("enter the unit: ")
        print(2*pie*radius,unit,"²")

    if opt == 1234 :
        unit = input("enter the unit: ")

        side = int(input("enter the side of square: "))
    
    

        length = int(input("enter the length of rectangle: ")) 
        bredth = int(input("enter the bredth of rectangle: "))
    

       base = int(input("enter the base of triangle: ")) 
       height = int(input("enter the height of triangle: "))
    
    
        radius = int(input("enter the radius of circle: "))
    
    

    print("area of square is",side * side,unit,"²")
    print("area of rectangle is",length * bredth,unit,"²")
    print("area of triangle is",1/2 * base * height,unit,"²")
    print("area of circle is",2*3.14*radius,unit,"²")

#aarav ahluwalia

