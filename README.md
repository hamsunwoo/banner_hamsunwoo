# **askii art_hamsunwoo**
```
.........::.........
......=##%#%*=......
....:##%%%%%#%+.....
....=#%##%%#%%#*:...
..:*##%%%%%%#%%#*...
...+#*##%%%#%%%#....
...:*-***+#*%%+*-...
....-=:.:%:-+=......
.........+..........
.........+..........
....................
```

## **Synopsis**
   이미지를 아스키 아트로 바꾸고 로또번호가 출력되는 기능 추가

## **test**
   ```py
   pip install hamsunwoo-pic
   pip install hamsunwoo-lotto
   ```

## **사용법**
   ```py
   from pyfiglet import Figlet
   
   def show():
       f = Figlet(font='slant')
       print(f.renderText('Hamburger'))
   
   def pic():
       p = """
           .........::.........
......=##%#%*=......
....:##%%%%%#%+.....
....=#%##%%#%%#*:...
..:*##%%%%%%#%%#*...
...+#*##%%%#%%%#....
...:*-***+#*%%+*-...
....-=:.:%:-+=......
.........+..........
.........+..........
....................
"""
       print(p)
 
   def lotto():
       import random
       l = random.sample(range(1,46), 6)
       print(l)
   ```

## **Thanks**
   ham

## **License**
   hamsunwoo

## **urls**
   [Repository](https://github.com/hamsunwoo/banner_hamsunwoo)
   [Issues](https://github.com/hamsunwoo/banner_hamsunwoo/issues)
