library(tidyverse)

# ---------
  
mpg %>%
  ggplot() +
  geom_point(aes(displ, hwy))

mpg %>% 
  ggplot() +
  geom_point(aes(displ, hwy, color = class)) +
  geom_smooth(aes(displ, hwy))


mpg %>% 
  ggplot() +
  geom_point(aes(displ, hwy, shape = class, color = manufacturer)) +
  geom_smooth(aes(displ, hwy))
