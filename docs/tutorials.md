### unsplash.com
Unsplash is one of my favorite which has more artistic content and I personally contribute many pitures to the community.
I have slitely different methods for unplash.
- Find - for search image by terms
- filter_by_tag - find images using tags

````
pip install git+http://github.com/manojap/wallspyder.git

from wallspyder import unsplash

unsplash.search().filter_by_tag('travel')
unsplash.search().filter_by_tag('women')

```` 
### Not working ?
If the above steps don't make it for just clone the repo use it or use a lite version from PYPI 
```python
git clone http://github.com/manojap/unsplashbot.git
pip install -r requirements.txt
```
### pip and unsplashbot
 Do you know , can directly install a working version of this package from PYPI using
 
 ```python
pip install unsplashbot
```

