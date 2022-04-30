import student.media.*;

//-------------------------------------------------------------------------
/**
 *  A picture that supports basic color transformations for Lab 06.
 *
 *  @author Aaron Whang (aaronw04)
 *  @version (2022.02.25)
 */
public class TransformablePicture
    extends Picture
{
    //~ Constructor ...........................................................

    // ----------------------------------------------------------
    /**
     * Initializes a newly created TransformablePicture object as a copy
     * of another image.
     * @param original is the picture to display.
     */
    public TransformablePicture(Picture original)
    {
        super(original);
    }


    //~ Methods ...............................................................

    // ----------------------------------------------------------
    /**
     * Turns the red intensity of every pixel in this image up to
     * the maximum value.
     */
    public void maxRed()
    {
        for (Pixel pix : this.getPixels())
        {
            pix.setRed(255);
        }
    }
    /**
     * Turns the green intensity of every pixel in this image up to
     * the maximum value.
     */
    public void maxGreen()
    {
        for (Pixel pix : this.getPixels())
        {
            pix.setGreen(255);
        }
    }
    /**
     * Turns the blue intensity of every pixel in this image up to
     * the maximum value.
     */
    public void maxBlue()
    {
        for (Pixel pix : this.getPixels())
        {
            pix.setBlue(255);
        }
    }
    /**
     * Turns the intensity of every pixel in this image up to
     * the specified value.
     * @param amount is value of rgb to add to brigten.
     */
    public void brighten(int amount)
    {
        for (Pixel pix : this.getPixels())
        {
            pix.setRed(pix.getRed() + amount);
            pix.setGreen(pix.getGreen() + amount);
            pix.setBlue(pix.getBlue() + amount);
        }
    }
}
