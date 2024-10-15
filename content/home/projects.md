+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"
headless = true
active = true
weight = 65

title = "Projects"
subtitle = "ALL THINGS ARE DIFFICULT BEFORE THEY ARE EASY!"

[content]
  page_type = "project"

[design]
  columns = "2"  # Ensure two-column layout
  view = 3       # Use Card layout for uniformity

[advanced]
  css_style = """
    .project-card { 
      min-height: 400px;  # Set a minimum height for cards
      display: flex;       # Use flexbox for alignment
      flex-direction: column; # Align content vertically
      justify-content: space-between; # Distribute space
    }
    .project-card img {
      max-width: 100%;    # Ensure images are responsive
      height: auto;       # Maintain aspect ratio
    }
    .project-card h3 {
      margin: 0;          # Remove default margins
      font-size: 1.25em;  # Adjust font size if necessary
    }
  """
+++
