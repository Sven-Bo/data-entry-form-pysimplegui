
# How to Create an Excel Data Entry Form in 10 Minutes Using Python (No VBA) | Easy & Simple

Did you know you can use Python code to create an Excel Data Entry Form? This is a tutorial that will show you how to create one using the PySimpleGUI & Pandas library. No VBA or macros are required. At the end of the tutorial, we will also be converting the Python script to a standalone program. In doing so, we could share this data entry form with colleagues & friends, and they could use our program without having to install Python. The best part is that you could use this code as a starter template whenever you want to build a data entry form for Excel. If you want to add or remove columns, you only need to change one line of code. Additionally, you could also easily add more elements to the user form, like Multiline Input Fields, sliders, list boxes, a file dialogue box and much more.


## Video Tutorial

[![YouTube Video](https://img.youtube.com/vi/svcv8uub0D0/0.jpg)](https://youtu.be/svcv8uub0D0)

## Changes after releasing the video
With `pandas version 1.4.0` DataFrame.append() and Series.append() have been deprecated and will be removed in a future version
```diff
- df = df.append(values, ignore_index=True)
+ new_record = pd.DataFrame(values, index=[0])
+ df = pd.concat([df, new_record], ignore_index=True)
```

## Author

- Sven from Coding Is Fun
- YouTube: https://youtube.com/c/CodingIsFun
- Website: https://pythonandvba.com

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/X7X47Q0EG)

## Feedback

If you have any feedback, please reach out to me at contact@pythonandvba.com


![Logo](https://www.pythonandvba.com/banner-img)

