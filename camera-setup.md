# Animation Physical setup:

## FIRST: Set the lens focal length

The markings on the camera lense represent the focal length. Many DSLRs have an 18-55mm lens:

- 18mm = wide angle (avoid this for animation because of perspective distortion)
- 55mm = telephoto (good for up close photgraphy - this is what we want)

## SECOND: set your camera distance from the subject.

Setting the camera distance is a balancing act. You want the subject to fill the frame, but you also want to minimize lens distortion of the image. When you are closer, the lens has to be set to a wide-angle (see above), which distorts the image.

- closer to subject = more perspective distortion (fisheye)
- further away = less distortion, but images might not fill the frame

### How to set the camera distance:

- Set the Focal length to a high value (55mm)
- Place the subject in frame
- Move the camera away from the subject until it fills the frame correctly
- Check for perspective distortion using a straight edge near the edge of your camera frame
- Adjust as necessary

## THIRD: Set up lights

Make sure the lights are set up in a way that they will not get bumped, ruining your shoot.

### Light temperature:

- 1000 = Candlelight (orange)
- 3000 = Incandescant bulbs (yellow)
- 4500 = Electronic flash (pure white) **WHEN IN DOUBT, USE THIS ONE**
- 5000 = Bright sunlight (slightly bluish)
- 7000 = overcast daylight (light blue)
- 10000 = blue sky (blue, duh)

### Setting white balance or using a light meter

I have no idea how to do this

### Dragonframe Histogram

This can be used to make sure you have the right color profile. You generally don't want the graph clipped at the top or bottom range (unless you are trying to achieve a specific look).\
![Histogram](/images/cinema_histogram.jpg)

# Camera Setup in Dragonframe

To make these adjustments, the camera must be...

- Turned on (use a power supply, not a camera battery)
- Camera set to manual mode
- Lens set to manual focus
- Connected to laptop via USB cable
- Dragonframe is set to Cinematography mode (camera icon in upper right corner)\
  ![Cinematography Icon](/images/icon_cinematography.jpg)

Use the Camera Settings Window to set the following values. The **Test Shot** button will allow you to take test shots as you get this dialed in\
![Camera Settings](/images/cinema_camera_settings.jpg)

## FIRST: f-stop setting

f-stop sets your depth of field. Higher f-stop number = deeper field\
**examples:**

- f/32 = landscape (large depth of field) - everything will be in focus: foreground, background, subject. This give a more "realistic" feel to your film.
- f/5.6 = portrait (small depth of field) - emphasizes the "miniature" aspect of your film.

In most cases, depth of field should be high for animation, unless you are trying to achieve a special effect.

**TLDR; When in doubt, use f/8 - it will soften the background and foreground while allowing a reasonable depth of field**

## SECOND: ISO setting

ISO refers to how sensitive your camera is to light.

- High ISO = better in low light, but more grain in the image
- Lower ISO = better in brighter light with crisper (less grain) images

Generally, the lowest ISO you can get away with is best

**TLDR; Use ISO 100 and set the lock button in Dragonframe to prevent it from changing**\
![Dragonframe ISO Lock](/images/icon_iso_lock.jpg)

## THIRD: Shutter speed setting

After you have optimized for f-stop and ISO, set your shutter speed. The proper setting will be obvious based on how much light you need on the subject:

- washed out = go to faster shutter
- too dark = go to slower shutter

This assumes that you subject is completely still, so the shutter speed doesn't really matter. If shutter speed matters for some reason, you may need to do something different.

Note: Slower shutter speeds can help reduce light flicker. If you want to check for light flicker, shoot some video in slomo setting, then play it back to see if there is observable flickering.

## FOURTH: FOCUS

You should be doing a rough focus after each step in this process. Once you have all of the above settings dialed in, do a final focus with the **Focus Check** feature in Dragonframe.

- click the Focus Check button under the preview window\
  ![Focus Check](/images/cinema_focus_check.jpg)
- Move the window that appears to the part of your frame you want to check
- Double click in the frame to zoom in
- Adjust the camera focus manually until image is sharp
- Click Focus Check button again to dismiss
