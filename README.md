# -to-check-leap-year
year = int(input("Enter a year: "))
if (year % 4) == 0:
    if (year % 100) == 0:
        if (year % 400) == 0:
            print(year, " is a leap year")
        else:
            print(year, " is not a leap year")
    else:
        print(year, " is a leap year")
else:
    print(year, " is not a leap year")
OUTPUT:
Enter a year: 2026[118, 69, 60, 0]
[117, 68, 50, 0]
[113, 62, 57, 0]
