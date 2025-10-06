+++
template = "landing.html"
title = "Goyo"

[extra]
version = "v0.1.0"

# Hero Section
# The main section at the top of the page.
[extra.hero]
title = "Welcome to Goyo!"
badge = "✨ Minimalist Documentation Theme"
description = "A simple and clean Zola theme for documentation."
image = "/images/landing.jpg" # Background image
cta_buttons = [
    { text = "Get Started", url = "/get-started/installation/", style = "primary" },
    { text = "View on GitHub", url = "https://github.com/your/repo", style = "secondary" },
]

# Features Section
# A grid to highlight key features.
[[extra.features]]
title = "Documentation Friendly"
desc = "Provides a clean writing experience for documentation."
icon = "fa-solid fa-book"

[[extra.features]]
title = "Simple Design"
desc = "A theme that pursues minimalism."
icon = "fa-solid fa-minimize"

# Trust Section
# Display logos of companies or projects that trust you.
[extra.trust_section]
title = "Trusted by the Best"
logos = [
    { src = "/images/logo1.svg", alt = "Company One" },
    { src = "/images/logo2.svg", alt = "Company Two" },
]

# Social Proof Section
# Showcase testimonials from your users.

# Final Call to Action Section
# A final prompt for users before the footer.
# You can also add an image field to show an image above the CTA text.
[extra.final_cta_section]
title = "Ready to Get Started?"
description = "Begin your journey with Goyo today and create beautiful documentation with ease."
button = { text = "Start Now", url = "/get-started/installation/" }
image = "/images/contribute.png" # (Optional) Image above the CTA section
+++
