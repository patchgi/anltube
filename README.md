# anitube
某サイトの広告が某な上良い某は手元に某したいので色々某をするためのライブラリ
	
This is a library to live a comfortable anitube life without Advertisements

## Version
    Python==3.5.2
    beautifulsoup4==4.5.1
    
## Example
```python
import anitube

if __name__ == "__main__":
    soup = anitube.Anitube("{search word}")
    for idx in range(len(soup.movies)):
        print(soup.movies[idx]) # mp4file url
	    print(soup.titles[idx]) # movie's title
	    print(soup.thumnails[idx])# image url 
```
      
