+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 65  # Order that this section will appear.

title = "Published and Accepted Research Work"
subtitle = ""

[content]
  # Page type to display. E.g. project.
  page_type = "papers"
  
[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   3 = Card
  #   5 = Showcase
  view = 5

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

[design.background]
  # Apply a background color, gradient, or image.

  # Background color for a formal aesthetic.
  color = "#f0f0f0"  # Light gray for a clean look

  # Optional background gradient for a more dynamic feel.
  # gradient_start = "#e0e0e0"  # Light gray
  # gradient_end = "#ffffff"    # White

  # Text color (true=light or false=dark).
  text_color_light = false  # Dark text for readability
  
[advanced]
 # Custom CSS. 
 css_style = """
   .portfolio-item {
     border: 1px solid #ddd;  # Add a subtle border around items
     border-radius: 8px;      # Rounded corners for a modern look
     padding: 15px;            # Add padding inside each item
     background-color: #ffffff;  # White background for items
   }
 """

 # CSS class.
 css_class = ""
+++
