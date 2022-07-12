# OpenCV (python3)
![](https://upload.wikimedia.org/wikipedia/commons/5/53/OpenCV_Logo_with_text.png)
## Read
```python
cv2.imread('file_path', image_style)
```
image_style
- -1 (default), Color image **(transparacy will be ignored)**
- 0, Grayscale
- 1, Unchange
  
|Number |Meaning|FULL Command|
|-----|--------|-----------|
|-1|Color image|IMREAD_COLOR|
|0|Grayscale|IMREAD_GRAYSCALE|
|1|Unchange|IMREAD_UNCHANGED|

## Display
<pre><code>cv2.imshow('file_path', img)
</code></pre>
## Resize
1. Resize with pixel
   <pre><code>cv2.resize(img, (int, int))
</code></pre>

2. Resize with scale
    <pre><code>cv2.resize(img, (0,0), fx = 0.5, fy = 0.5)
</code></pre>

## Rotate
<pre><code>img = cv2.rotate(img, cv2.ROTATE...)
</code></pre>

## Write
<pre><code>cv2.imwrite('new_file_name', img)
</code></pre>

## test





