These are the touch typing lessons optimized for Kinesis Advantage keyboard. You can load them into
free tutorial program TIPP10 : http://www.tipp10.com/en/index/

The Dvorak variant of the lessons was done by simply replacing the qwerty letters with their dvorak 
counterparts.
As a result the lessons that contained the words now contain jibberish, but it should still provide 
the same level of training.

The dvorak lessons were converted using a simple sed command that's documented here in case someone 
would benefit from applying it to other lessons or content.

```bash
sed 'y~-=qwertyuiop[]sdfghjkl;"zxcvbnm,./QWERTYUIOPSDFGHJKLZXCVBNM~[]'\'',.pyfgcrl/=oeuidhtns-;qjkxbmwvz'\'',.PYFGCRLOEUIDHTN;QJKXBM~' input.txt > output.txt
```
