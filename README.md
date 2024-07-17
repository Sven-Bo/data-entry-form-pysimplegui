
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


## 🤓 Check Out My Excel Add-ins
I've developed some handy Excel add-ins that you might find useful:

- 📊 **[Dashboard Add-in](https://pythonandvba.com/grafly)**: Easily create interactive and visually appealing dashboards.
- 🎨 **[Cartoon Charts Add-In](https://pythonandvba.com/cuteplots)**: Create engaging and fun cartoon-style charts.
- 🤪 **[Emoji Add-in](https://pythonandvba.com/emojify)**: Add a touch of fun to your spreadsheets with emojis.
- 🛠️ **[MyToolBelt Add-in](https://pythonandvba.com/mytoolbelt)**: A versatile toolbelt for Excel, featuring:
  - Creation of Pandas DataFrames and Jupyter Notebooks from Excel ranges
  - ChatGPT integration for advanced data analysis
  - And much more!



## 🤝 Connect with Me
- 📺 **YouTube:** [CodingIsFun](https://youtube.com/c/CodingIsFun)
- 🌐 **Website:** [PythonAndVBA](https://pythonandvba.com)
- 💬 **Discord:** [Join the Community](https://pythonandvba.com/discord)
- 💼 **LinkedIn:** [Sven Bosau](https://www.linkedin.com/in/sven-bosau/)
- 📸 **Instagram:** [sven_bosau](https://www.instagram.com/sven_bosau/)

## ☕ Support 
If you appreciate the project and wish to encourage its continued development, consider [supporting my work](https://pythonandvba.com/coffee-donation).
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://pythonandvba.com/coffee-donation)

## Feedback & Collaboration
For feedback, suggestions, or potential collaboration opportunities, reach out at contact@pythonandvba.com.
![Logo](https://www.pythonandvba.com/banner-img)

