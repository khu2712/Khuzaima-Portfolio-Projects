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
  color = "#f0f0f0"  # Light gray for a clean look

  # Text color (true=light or false=dark).
  text_color_light = false  # Dark text for readability
  
[advanced]
 # Custom CSS. 
 css_style = """
   .portfolio {
     padding: 30px;  # Add padding around the entire section
     background-color: #f0f0f0;  # Background for the section
   }
   .portfolio-item {
     display: flex;                 # Use flexbox for alignment
     align-items: center;           # Center items vertically
     border: 1px solid #ccc;        # Subtle border around items
     border-radius: 8px;            # Rounded corners for a modern look
     padding: 20px;                 # Add padding inside each item
     background-color: #ffffff;     # White background for items
     box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);  # Subtle shadow for depth
     margin-bottom: 20px;           # Space between cards
   }
   .portfolio-item img {
     max-width: 100px;              # Fixed width for images
     height: auto;                   # Maintain aspect ratio
     border-radius: 4px;            # Rounded corners for images
     margin-right: 20px;             # Space between image and text
   }
   .portfolio-item h3 {
     margin: 0;                      # Remove default margin from titles
     font-size: 1.2em;               # Adjust font size if necessary
   }
 """

 # CSS class.
 css_class = ""
