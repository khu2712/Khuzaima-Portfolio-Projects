+++
# A Papers section created with the Portfolio widget.
widget = "portfolio"
headless = true
active = true
weight = 65

title = "Published and Accepted Research Work"
subtitle = "ALL THINGS ARE DIFFICULT BEFORE THEY ARE EASY!"

[content]
  page_type = "papers"
  #folder = "papers"

[design]
  columns = "2"  # Two-column layout
  view = 3       # Card layout

[advanced]
  css_style = """
    .portfolio-item { 
      display: flex;                 /* Align image and text side by side */
      align-items: center;
      border: 1px solid #ddd;        /* Border for visibility */
      border-radius: 8px;            /* Rounded corners */
      padding: 15px;                 /* Inner padding */
      background-color: #fff;        /* Background color */
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1); /* Shadow for depth */
      margin-bottom: 20px;           /* Space between items */
    }
    .portfolio-item img {
      max-width: 150px;              /* Fixed width for image */
      height: auto;                  /* Maintain aspect ratio */
      border-radius: 4px;            /* Optional: Rounded corners for images */
      margin-right: 20px;            /* Space between image and text */
    }
    .portfolio-item h3 {
      margin: 0;                     /* Remove default margins */
      font-size: 1.25em;             /* Adjust font size */
    }
    .portfolio-item p {
      margin: 5px 0 0 0;             /* Minimal margin for subtitle */
      color: #555;                   /* Subtitle color */
    }
    .portfolio-item a {
      text-decoration: none;
      color: #007bff;
    }
    .portfolio-item a:hover {
      text-decoration: underline;
    }
  """
+++