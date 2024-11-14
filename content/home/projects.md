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
  folder = "projects"  # Directory where the project markdown files are stored

[design]
  columns = "2"  # Ensure two-column layout
  view = 3       # Use Card layout for uniformity

[advanced]
  css_style = """
    .project-card { 
      height: 450px;     # Set a fixed height for cards
      display: flex;       # Use flexbox for alignment
      flex-direction: column; # Align content vertically
      justify-content: space-between; # Distribute space
      padding: 15px;     # Add padding for inner spacing
      border: 1px solid #ddd;  # Optional: Add border for better visibility
      border-radius: 8px;  # Optional: Rounded corners
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1); # Optional: Add shadow for depth
      background-color: #fff; # Optional: Set background color
    }
    .project-card img {
      max-width: 100%;    # Ensure images are responsive
      height: auto;       # Maintain aspect ratio
      flex-shrink: 0;     # Prevent images from shrinking
    }
    .project-card h3 {
      margin: 0;          # Remove default margins
      font-size: 1.25em;  # Adjust font size if necessary
    }
  """
+++

# Loop through the markdown files in the `projects` folder to create project cards.
{{ range .Site.GetPage "section" "projects" }}
  <div class="project-card">
    <img src="{{ .Params.image }}" alt="{{ .Title }}">
    <h3>{{ .Title }}</h3>
    <p>{{ .Params.short_description }}</p>
    <a href="{{ .Permalink }}">Learn more</a>
  </div>
{{ end }}