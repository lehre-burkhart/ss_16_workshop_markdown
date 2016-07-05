    first_colour <- "#684F91"

    cars <- read.csv("data/cars.csv", sep = ",")

    ggplot(cars, aes(x = speed, y = dist)) +
      geom_point(size = 2) +
      geom_smooth(method = lm, se = TRUE, colour = first_colour)

![](README_files/figure-markdown_strict/Display%20relationship-1.png)
