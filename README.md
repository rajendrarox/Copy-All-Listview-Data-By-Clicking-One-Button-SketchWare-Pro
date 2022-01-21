# Copy-All-Listview-Data-By-Clicking-One-Button-SketchWare-Pro
This is Simple Example Of Copy Total List Data In One Click 

https://github.com/androidbulb/Copy-All-Listview-Data-By-Clicking-One-Button-SketchWare-Pro/blob/main/Screenshot_20220121-190119_Sketchware%20Pro.jpg

**Steps**
1. Paste This Code In Add Source Directly Block
2. add string variable name is **result**


```String result = "";
int n = 0;
for (String str : listdata) {
  result += "" + (n++) + ". " + str + "\n";
}
// created by virkato/androidbulb


 
