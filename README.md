function changeCharCase(char) {
   return (/[a-z]/).test(char) ? char.toUpperCase() : char.toLowerCase();
}
var str = "kannada,felight.io,hI gOOD mORNING,Have a grate day",
    str1 = "";
for (var i = 0; i < str.length; i++) {
   str1 += changeCharCase(str[i]);
}
console.log(str1);

