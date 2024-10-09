+++
# Slider widget with enhanced animations
widget = "slider"
headless = true
active = false  # Activate this widget
weight = 1

# Slide interval for smooth transition
interval = 5000  # 5 seconds

# Slide height
height = "calc(100vh - 70px)"  # Full height minus header

# Slides
[[item]]
  title = "Welcome to My Portfolio"
  content = "Discover my journey and expertise in the field."
  align = "center"

  overlay_color = "#333"  # Dark overlay for readability
  overlay_filter = 0.5  # Darken the overlay

  cta_label = "Learn More"
  cta_url = "https://khuzaimaalikhan.netlify.app/"
  cta_icon_pack = "fas"
  cta_icon = "info-circle"

[[item]]
  title = "Innovative Solutions"
  content = "Committed to providing innovative and efficient solutions."
  align = "left"

  overlay_color = "#444"
  overlay_filter = 0.5

[[item]]
  title = "Get in Touch"
  content = "Let’s collaborate to create something extraordinary."
  align = "right"

  overlay_color = "#555"
  overlay_filter = 0.5
+++