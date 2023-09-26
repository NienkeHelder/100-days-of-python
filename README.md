# 100-days-of-python
Exploring Turtle graphics by making a Hirst inspired dotted painting with colors extracted from an image.

I first used the following to extract colors from an image. Copied the result into color_list.

    colors = colorgram.extract('image.jpeg', 30)
    rgb_colors = []
    for color in colors:
        r = color.rgb.r
        g = color.rgb.g
        b = color.rgb.b
        new_color = (r, g, b)
        rgb_colors.append(new_color)
