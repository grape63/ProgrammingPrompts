# Leap Year Checker
----
For this prompt build a leap year checker that returns or prints whether or not a year is a leap year. The input will be an array of years.

```python
##Like This
years = ["2020","2000","1933","1880","2028","1944","2231","2400"]
```
def leapyearcheck(years=["2020","2000","1933","1880","2028","1944","2231","2400"]):
    checkedyears = []
    for year in years:
        if int(year)%4 != 0:
            checkedyears.append(False)
        else: checkedyears.append(True)
    return checkedyears
print(leapyearcheck())
