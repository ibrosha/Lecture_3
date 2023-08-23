# Lecture_3
Abdusattorov Sh, [8/22/2023 4:01 PM]
"# lectures3" 
# Table of Contents
## STRING
## NAMBER
## Array
## Destructuring
## Spread & Rest




## What is a Method in java script?

## String in java script
### Create string in java script 

## JAVA SCRIPT STRING METHODS

## avaScript String method charAt()
### The charAt() method returns the character at a specified index (position) in a string.The index of the first character is 0, the second 1, ...The index of the last character is string length - 1 .

## JavaScript String method at()
### The at() method takes an integer value and returns a new String.This method allows for positive and negative integers. Negative integers count back from the last string character.
### Усули at() арзиши бутунро мегирад ва Сатри навро бармегардонад.Ин усул имкон медиҳад, ки ададҳои мусбат ва манфӣ дошта бошанд. Шумораи бутуни манфӣ ҳисоб карда мешавадбозгашт аз аломати сатри охирин

## JavaScript String method concat()
### The concat() method joins two or more strings.The concat() method does not change the existing strings.The concat() method returns a new string.
### Усули concat() ду ё зиёда сатрҳоро мепайвандад.Усули concat() сатрҳои мавҷударо тағир намедиҳад.Усули concat() сатри навро бармегардонад.

## JavaScript String method replace()
### The replace() method searches a string for a value or a regular expression.The replace() method returns a new string with the value(s) replaced.The replace() method does not change the original string.
### Усули replace() сатрро барои арзиш ё ифодаи муқаррарӣ ҷустуҷӯ мекунад.Усули replace() сатри навро бо арзиш(ҳо) иваз мекунад.Усули иваз () сатри аслиро тағир намедиҳад.

## JavaScript String method replaceAll()
### //The replaceAll() method returns a new string with all matches of a pattern replaced by a replacement.                      
### //Усули replaceAll() сатри навро бо ҳамаи мувофиқати намунае, ки бо он иваз карда шудааст, бармегардонад ивазкунанда.

## //JavaScript String method split()
### //The split() method splits a string into an array of substrings. The split() method returns the new array. The split() method does not change the original string. If (" ") is used as separator, the string is split between words.
### //Усули split() сатрро ба массиви зерсатрҳо тақсим мекунад. Усули split() навро бармегардонад массив. Усули split () сатри аслиро тағир намедиҳад. Агар (" ") ҳамчун ҷудокунанда истифода шавад, сатр байни калимаҳо тақсим карда мешавад.

## //JavaScript String method substring(start,end)
### //The substring() method extracts characters, between two indices (positions), from a string, and returns the substring. The substring() method extracts characters from start to end (exclusive). The substring() method does not change the original string. If start is greater than end, arguments are swapped: (4, 1) = (1, 4). Start or end values less than 0, are treated as 0.
### //Усули substring() аломатҳоро дар байни ду индекс (мавқеъ), аз сатр ва зерхатро бармегардонад. Усули substring() аломатҳоро аз аввал то ба охир истихроҷ мекунад (истисноӣ). Усули substring() сатри аслиро тағир намедиҳад. Агар оғоз аз интиҳо бузургтар бошад, аргументҳо иваз карда мешаванд: (4, 1) = (1, 4). Қиматҳои оғоз ё анҷоми камтар аз 0 ҳамчун 0 ҳисоб карда мешаванд.

## //JavaScript String method slice(start, end)
### //The slice() method returns a shallow copy of a portion of an array into a new array object selected from start to end ( end not included) where start and end represent the index of items in that array.

Abdusattorov Sh, [8/22/2023 4:01 PM]
### //Усули slice() нусхаи ками як қисми массивро ба объекти массиви нав бармегардонад аз аввал то ба охир интихоб карда мешавад (охираш дохил карда нашудааст), ки дар он оғоз ва охири он шохиси ашёро ифода мекунад дар он массив.

## JavaScript String method toLowerCase()
### //The toLowerCase() method converts a string to lowercase letters. The toLowerCase() method does not change the original string.
### //Усули toLowerCase () сатрро ба ҳарфҳои хурд табдил медиҳад. Усули toLowerCase () сатри аслиро тағир намедиҳад.

## //JavaScript String method toUpperCase()
### //The toUpperCase() method converts a string to uppercase letters, using current locale. The toUpperCase() method does not change the original string.
### //Усули toUpperCase() бо истифода аз маҳалли ҷорӣ сатрро ба ҳарфҳои калон табдил медиҳад. Усули toUpperCase () сатри аслиро тағир намедиҳад.

## //JavaScript String method trim()
### //Method trim() removes whitespace from both sides of a string. The trim() method does not change the original string.
### //Усули trim() холигии ҳар ду тарафи сатрро нест мекунад. Усули trim () сатри аслиро тағир намедиҳад.

## //JavaScript String method includes()
### //The includes() method returns true if a string contains a specified string.Otherwise it returns false. The includes() method is case sensitive.
### //Усули дохил () ҳақиқиро бармегардонад, агар сатр дорои сатри муайяншуда бошад. Дар акси ҳол он бардурӯғ бармегардад. Усули дохил () ба ҳарфҳои хурд ҳассос аст.

## //JavaScript String method toString()
### //The toString() method returns a string representing the object. By default toString() takes no parameters.
### //Усули toString() сатри намояндагии объектро бармегардонад. Бо нобаёнӣ toString() ягон параметр намегирад.

## //JavaScript String method indexOf()
### //The indexOf() method returns the position of the first occurrence of a value in a string. The indexOf() method returns -1 if the value is not found. The indexOf() method is case sensitive
### //Усули indexOf() мавқеъи пайдоиши аввалини арзишро дар сатр бармегардонад. Усули indexOf () -1-ро бармегардонад, агар арзиш ёфт нашавад. Усули indexOf() ба ҳарфҳои хурд ҳассос аст

## //JavaScript String method repeat()
### //The repeat() method creates a new string by repeating the given string a specified number of times and returns it.
### //Усули такрор () як сатри навро бо такрори сатри додашуда шумораи муайяншуда месозад маротиба ва онро бармегардонад.

# //JavaScript Number methods
## //JavaScript Number methods Math.round(),ceil(),floor()
### //The Math.floor() function rounds down a number to the next smallest integer.
### //Функсияи Math.floor() ададро ба бутуни хурдтарини оянда яклухт мекунад.

### //The Math.round() function returns the number rounded to the nearest integer.
### //Функсияи Math.round() адади мудавваршударо ба бутуни наздиктарин бармегардонад.

### //The ceil() method rounds a decimal number up to the next largest integer and returns it.
### //Усули ceil() адади даҳиро то адади бузургтарини навбатӣ мудаввар мекунад ва онро бармегардонад.

## //JavaScript Number methods Math.max() and Math.min()
### //The max() method finds the maximum value among the specified values and returns it.
### //Усули max() арзиши максималиро дар байни арзишҳои муайяншуда пайдо мекунад ва онро бармегардонад.

### //The min() method finds the minimum value among the specified values and returns it.
### //Усули min() арзиши ҳадди ақалро дар байни арзишҳои муайяншуда пайдо мекунад ва онро бармегардонад.

Abdusattorov Sh, [8/22/2023 4:01 PM]

## //JavaScript Number methods Math.pow() and Math.sqrt()
### //The pow() method computes the power of a number by raising the second argument to the power of the first argument. 
### //Усули pow() қудрати ададро тавассути баланд бардоштани далели дуюм ба қудрати аргументи аввал ҳисоб мекунад.

### //The sqrt() method computes the square root of a specified number and returns it
### //Усули sqrt() решаи квадратии адади муайяншударо ҳисоб мекунад ва онро бармегардонад

## //JavaScript String method Math.abs() and Math.random()
### //The abs() method finds the absolute value of the specified number (without any sign) and returns it.
### //Усули abs() арзиши мутлақи адади зикршударо (бе ягон аломат) ёфта, онро бармегардонад.

### //The Math.random() function returns a floating-point, pseudo-random number between 0 (inclusive)  and 1 (exclusive).
### //Функсияи Math.random() рақами шинокунандаи нуқтаи шинокунанда ва псевдо-тасодуфӣ байни 0 (бо назардошти) бар мегардонад ва 1 (истисноӣ).

## //JavaScript Number method isNaN()
### //The isNaN() function checks if a value is NaN (Not-a-Number) or not.
### //Функсияи isNaN() тафтиш мекунад, ки оё арзиш NaN (Не рақам) аст ё не.

# Lecture_3





# Array in JavaScript

- An array is an object that holds values (of any type) not particularly in named properties/keys, 
but rather in numerically indexed position
In JavaScript, an array is an ordered list of values. Each value is called an element specified by 
an index. ... First, an array can hold values of mixed types.
An array is a special variable, which can hold more than one value:



# CHANGE ELEMENTS IN ARRAY

- You can also add elements or change the elements by accessing the index value
Suppose, an array has two elements. If you try to add an element at index 3 (fourth 
element), the third element will be undefined. For example,


# array method push
 - The push() method adds one or more elements to the end of an array and returns the
new length of the array. 
The element(s) to add to the end of the array.
Syntax: push(element0, element1, /* … ,*/ elementN)


# POP
- The pop() method removes the last element from an array and returns that element. 
This method changes the length of the array.
# unshift
- The unshift() method adds one or more elements to the beginning of an array and
returns the new length of the array. 

# shift 
- The pop() method removes the last element from an array and returns that element. 
This method changes the length of the array. 

# toString

- The toString() method returns a string representing the specified array and its
elements. 
A string representing the elements of the array.

# 