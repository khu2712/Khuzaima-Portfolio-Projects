+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 65  # Order that this section will appear.

title = "Published and Accepted Research Work"
subtitle = ""

[content]
  # Page type to display.
  page_type = "project"  # We use "project" as the widget expects it for portfolio display

  # Directory where the papers are stored
  folder = "papers"

  # How many entries to show per page
  count = 5

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
  color = "#f0f0f0"

  # Text color (true=light or false=dark).
  text_color_light = false

[advanced]
 # Custom CSS. 
 css_style = """
   .portfolio {
     padding: 30px;
     background-color: #f0f0f0;
   }
   .portfolio-item {
     display: flex;
     align-items: center;
     border: 1px solid #ccc;
     border-radius: 8px;
     padding: 20px;
     background-color: #ffffff;
     box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
     margin-bottom: 20px;
   }
   .portfolio-item img {
     max-width: 100px;
     height: auto;
     border-radius: 4px;
     margin-right: 20px;
   }
   .portfolio-item h3 {
     margin: 0;
     font-size: 1.2em;
   }
   .portfolio-item a {
     text-decoration: none;
     color: #007bff;
   }
   .portfolio-item a:hover {
     text-decoration: underline;
   }
 """

 # CSS class.
 css_class = ""
+++
