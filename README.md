# Copy-All-Listview-Data-By-Clicking-One-Button-SketchWare-Pro
This is Simple Example Of Copy Total List Data In One Click 


![Screenshot_20220121-190119_Sketchware Pro](https://user-images.githubusercontent.com/59394255/150540084-a35364ef-8b71-4702-ae6c-289e2d96a60b.jpg)


**Steps**
you need to create list string(listdata) where you can put your list data.

**Note**
maximum steps will be skipped
i am showing you only main steps

**1.** Paste This Code In Add Source Directly Block
**2.** add string variable name is **result**


```String result = "";
int n = 0;
for (String str : listdata) {
  result += "" + (n++) + ". " + str + "\n";
}
// created by virkato/androidbulb
```


 **for more details watch video**
