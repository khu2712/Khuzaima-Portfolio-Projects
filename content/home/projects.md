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
    }
  """
+++