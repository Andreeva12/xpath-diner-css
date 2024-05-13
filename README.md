# xpath-diner-css
## Xpath Diner Solutions:

Level 01 of 26:
//plate

Level 02 of 26:
//bento

Level 03 of 26:
//plate/apple

Level 04 of 26:
//*

Level 05 of 26:
//*/apple

Level 06 of 26:
//*[@id="fancy"]

Level 07 of 26:
//plate/apple

Level 08 of 26:
//*[@id="fancy"]/pickle

Level 09 of 26:
//*[contains(@Class,"small")]

Level 10 of 26:
//orange[contains(@Class,"small")]

Level 11 of 26:
//bento/orange[contains(@Class,"small")]

Level 12 of 26:
//plate|//bento

Level 13 of 26:
//plate/*

Level 14 of 26:
//plate/following-sibling::apple

Level 15 of 26:
//plate/preceding-sibling::pickle

Level 16 of 26:
(//pickle)[3]

Level 17 of 26:
//plate/apple

Level 18 of 26:
//plate/*[last()]

Level 19 of 26:
//plate/apple[last()]

Level 20 of 26:
//plate/apple[last()-1]

Level 21 of 26:
//*[@for]

Level 22 of 26:
//plate[@for]

Level 23 of 26:
//*[@for="Vitaly"]

Level 24 of 26:
//plate[@id="fancy" and @for="Hanna"]/apple

Level 25 of 26:
//*[starts-with(@for,"Sa")]

Level 26 of 26:
//*[substring(@for, string-length(@for) - string-length('o') +1) = 'o']


## css Diner Solutions:
01. plate
02. bento
03. #fancy
04. plate apple
05. #fancy pickle
06. .small
07. orange.small
08. bento orange.small
09. plate, bento
10. *
11. plate *
12. plate + apple
13. bento ~ pickle
14. plate > apple
15. orange:first-child
16. plate apple:only-child, plate pickle:only-child
17. .small:last-child
18. plate:nth-child(3)
19. bento:nth-last-child(3)
20. apple:first-of-type
21. plate:nth-of-type(even)
22. plate:nth-of-type(2n+3)
23. plate apple:only-of-type
24. orange:last-of-type, apple:last-of-type
25. bento:empty
26. apple:not(.small)
27. *[for]
28. plate[for]
29. bento[for="Vitaly"]
30. *[for^="Sa"]
31. *[for$="ato"]
32. bento[for*="obb"]
