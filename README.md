<h1 align="center"><b>GITHUB PROFILE </b></h1><br>
<img src="https://telegra.ph/file/9142e8ab1f494dc7f082d.png" />
<a href="https://www.reddit.com/user">
  <img align="right" alt="XNewbie Reddit" width="20px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/reddit.svg" />
</a>
<a href="https://www.youtube.com">
  <img align="right" alt="XNewbie Youtube Channel" width="20px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/youtube.svg" />
</a>
<a href="https://pinterest.com">
  <img align="right" alt="XNewbie Pinterest" width="20px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/pinterest.svg" />
</a>
<a href="https://t.me/X_Newbie">
  <img align="left" alt="XNewbie Telegram" width="20px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/telegram.svg" />
</a>
<a href="https://twitter.com">
  <img align="left" alt="XNewbie Twitter" width="20px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />
</a>
<a href="https://www.instagram.com/">
  <img align="left" alt="XNewbie Instagram" width="20px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />
</a>
<a href="https://www.facebook.com">
  <img align="center" alt="XNewbie Facebook" width="20px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/facebook.svg" />
</a>
<br>
<br><p align="center"><a href="https://github.com/X-Newbie"><img src="https://img.shields.io/badge/dynamic/json?logo=github&label=GitHub+Followers&labelColor=282c34&color=181717&query=%24.data.totalSubs&url=https%3A%2F%2Fapi.spencerwoo.com%2Fsubstats%2F%3Fsource%3Dgithub%26queryKey%3DX-Newbie&longCache=true"></a></p>
<p align="center"><a href="https://github.com/X-Newbie"><img src="https://github-readme-stats.vercel.app/api?username=X-Newbie&show_icons=true&theme=radical"></a></p>
<p align="center"><a href="https://github.com/X-Newbie"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=X-Newbie&theme=radical&layout=compact"></a></p>
<img src="https://camo.githubusercontent.com/992babdffd8c74a1502de375fbdf7e4d54773242/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f53576f536b4e36447854737a71494b4571762f67697068792e676966" width="495px">

```python3

from dataclasses import dataclass
from typing import Tuple


class Meta(type):
    def __new__(cls, name, bases, attrs):
        for attr in attrs:
            if not attr.startswith("_"):
                __annotations__[attr] = Tuple[str, ...]
        attrs["__annotations__"] = __annotations__
        new_cls = super().__new__(cls, name, bases, attrs)
        new_cls = dataclass(new_cls)
        return new_cls


class Stack(metaclass=Meta):
    languages   = ("Python", "Bash")
    ongoing     = ("C")


print("A little more about me")

xnewbie = {
    'pronouns': 'he' or 'him' or 'his',
    'fullname': 'X NEWBIE',
    'nationality': ['Indonesia', 'ID'],
    'location': 'ID',
    'contact': {
        'email': 'sxnewbie@gmail.com',
        'website': 'https://gmail.com',
    },
    'about': [
        'A student',
        'A fan of python',
        'I\'m considering myself as a runner. (even tho rarely do it) xd',
        'Love gaming',
        'Human.',
        'Still don\'t know how to feel about Last of Us 2 ending'
    ],
    'game': ['Granado Espada', 'Blade & Soul Revolution']
}
```


<p align="center"><a href="https://t.me/XBOT_SUPPORT">   <img src="https://img.shields.io/badge/JOIN%20CHANNEL-red?style=flat&logo" width="210" height="34.45" /></a>
