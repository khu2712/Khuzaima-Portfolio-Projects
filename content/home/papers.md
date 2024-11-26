+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"
headless = true
active = true
weight = 65

title = "Research Work"
#subtitle = "ALL THINGS ARE DIFFICULT BEFORE THEY ARE EASY!"

[content]
  page_type = "papers"
  folder = "papers"  # Directory where the project markdown files are stored

[design]
  columns = "2"  # Ensure two-column layout
  view = 1       # Use Card layout for uniformity

[advanced]
  css_style = """
    .project-card { 
      height: 500px;    # Set a fixed height for cards (adjustable)
      display: flex;    
      flex-direction: column; 
      justify-content: space-between;  # Distribute space evenly inside cards
      padding: 15px;
      border: 1px solid #ddd;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      background-color: #fff;
      overflow: hidden;   # Ensure content stays inside the card without overflowing
    }
    .project-card img {
      width: 100%;        # Make sure images fill the width of the card
      height: 200px;      # Fixed height for images (adjustable)
      object-fit: cover;  # Ensures images cover the area without distorting
    }
    .project-card h3 {
      margin: 0;
      font-size: 1.25em;
      overflow: hidden;   # Prevent long titles from breaking the layout
      text-overflow: ellipsis;  # Add "..." for overflowing text
      white-space: nowrap;  # Prevent text wrapping
    }
    .project-card p {
      flex-grow: 1;       # Allow text to fill available space
      overflow: hidden;   # Prevent content from overflowing
      text-overflow: ellipsis; # Add "..." for overflowed text
    }
    .project-card a {
      margin-top: 10px;
      text-decoration: none;
      color: #007bff;
      font-weight: bold;
    }
  """
+++