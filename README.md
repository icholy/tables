My friend requested that I 3D print table numbers for her wedding. This ended up being more involved than I anticipated, so I’m documenting the process and sharing the models here in hopes that it will save someone a bit of time.

![](images/output.jpg)

### The Font

I assumed there would be many, readily available, fonts resembling the example in the image. This was not the case. A lot of time was wasted searching before I realized that I’d need hand-written calligraphy. I’m not very artistic, so my friend Sarah did this on her tablet using a brush tool. The `.png` files in this repository are the result of that work.

### Vectorization

The images needed to be converted to a format that a 3D modeling tool can import. Specifically, we need to convert the bitmap images into vector files. Inkscape has a **Trace Bitmap** tool for this exact purpose. In several cases, manual adjustments needed to be made. I then exported these in DXF format which OnShape supports.

![](images/inkscape.png)

## 3D Models

Once we have the DXF vector files, we can bring them into an OnShape sketch:

![](images/onshape_01.png)

I then used the dimension tool to scale it down to 3 inches tall:

![](images/onshape_02.png)

I then used the extrude tool to turn the sketch into a 6mm deep part:

![](images/onshape_03.png)

**Note:** It's been brought to my attention that OnShape is not the best tool for the job.

## Printing

After exporting the part from OnShape as an STL file, I printed it on my P1P using basic PLA with the default profile.

![](images/bambustudio.png)

I’m pretty happy with the results.

![](images/two.jpg)
