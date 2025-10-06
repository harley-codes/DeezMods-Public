+++
template = "landing.html"
title = "DeezMods"

# Hero Section
# The main section at the top of the page.
[extra.hero]
title = "DeezModz"
badge = "Only for Minecraft Bedrock"
description = "An addon aimed to deliver fun and creative content."
image = "/images/landing-page/landing.png" # Background image
cta_buttons = [
	{ text = "View on CurseForge", url = "https://www.curseforge.com/members/harley_codes", style = "primary" },
    { text = "Wiki", url = "/introduction", style = "secondary" },
]

# Features Section
# A grid to highlight key features.
[[extra.features]]
title = "Documentation Friendly"
desc = "Don't be left in the dark - all features are well documented."
icon = "fa-solid fa-book"
[[extra.features]]
title = "Free Forever and Add Free"
desc = "Do it for the love of craft."
icon = "fa-solid fa-heart"

# Final Call to Action Section
# A final prompt for users before the footer.
# You can also add an image field to show an image above the CTA text.
[extra.final_cta_section]
title = "Ready to Get Started?"
description = "Begin your new adventure with DeezMods."
button = { text = "Get Addon", url = "https://www.curseforge.com/members/harley_codes/projects" }
image = "/images/landing-page/get-addon.png" # (Optional) Image above the CTA section
+++
