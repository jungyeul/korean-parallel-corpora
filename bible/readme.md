# ==> bible-all.en.txt <==
* Genesis1.1  In the beginning God created the heavens and the earth.
* Genesis1.2  Now the earth was formless and empty, darkness was over the surface of the deep, and the Spirit of God was hovering over the waters.
* Genesis1.3  And God said, "Let there be light," and there was light.
* Genesis1.4  God saw that the light was good, and He separated the light from the darkness.
* Genesis1.5  God called the light "day," and the darkness he called "night." And there was evening, and there was morning--the first day.
* Genesis1.6  And God said, "Let there be an expanse between the waters to separate water from water."
* Genesis1.7  So God made the expanse and separated the water under the expanse from the water above it. And it was so.
* Genesis1.8  God called the expanse "sky." And there was evening, and there was morning--the second day.
* Genesis1.9  And God said, "Let the water under the sky be gathered to one place, and let dry ground appear." And it was so.
* Genesis1.10  God called the dry ground "land," and the gathered waters he called "seas." And God saw that it was good.

# ==> bible-all.kr.txt <==
* Genesis1.1  태초에 하나님이 천지를 창조하셨다.
* Genesis1.2  땅이 혼돈하고 공허하며, 어둠이 깊음 위에 있고, 하나님의 영은 물 위에 움직이고 계셨다.
* Genesis1.3  하나님이 말씀하시기를 "빛이 생겨라" 하시니, 빛이 생겼다.
* Genesis1.4  그 빛이 하나님 보시기에 좋았다. 하나님이 빛과 어둠을 나누셔서,
* Genesis1.5  빛을 낮이라고 하시고, 어둠을 밤이라고 하셨다. 저녁이 되고 아침이 되니, 하루가 지났다.
* Genesis1.6  하나님이 말씀하시기를 "물 한가운데 창공이 생겨, 물과 물 사이가 갈라져라" 하셨다.
* Genesis1.7  하나님이 이처럼 창공을 만드시고서, 물을 창공 아래에 있는 물과 창공 위에 있는 물로 나누시니, 그대로 되었다.
* Genesis1.8  하나님이 창공을 하늘이라고 하셨다. 저녁이 되고 아침이 되니, 이튿날이 지났다.
* Genesis1.9  하나님이 말씀하시기를 "하늘 아래에 있는 물은 한 곳으로 모이고, 뭍은 드러나거라" 하시니, 그대로 되었다.
* Genesis1.10  하나님이 뭍을 땅이라고 하시고, 모인 물을 바다라고 하셨다. 하나님 보시기에 좋았다.


```
>>> wc bible-all.*
   31103  756037 4235419 bible-all.en.txt
   31103  661648 5783870 bible-all.kr.txt
   62206 1417685 10019289 total
```

To remove identifiers at the beginning of the sentence
```
>>> cut -f2- -d" " bible-all.kr.txt | sed 's/^ //g' > bible-all.kr.clean.txt
```
