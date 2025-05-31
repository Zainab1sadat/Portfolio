# Portfolio
Design Decisions
Layout: 
A one-page scrolling layout was chosen to keep all content in a single flow, minimizing navigation friction.
Sections (Home, About, Portfolio, Contact) are clearly divided and anchor-linked for smooth user experience.
Responsiveness:
Media queries were used to ensure the site adapts seamlessly to mobile devices.
Elements like flexbox and fluid widths maintain consistent alignment and spacing on different screen sizes.
Theme Toggle (Light/Dark):
Implemented without JavaScript, using the modern :has() CSS selector for pure CSS interaction.
The switch is placed fixed at the top-right corner to remain accessible at all times.
Typography:
A mix of modern sans-serif and creative display fonts was used to balance professionalism with creativity.
Visual Identity:
The use of soft gradients and rounded images gives the site a gentle, inviting aesthetic.
Challenges Faced
Mobile Responsiveness:
Aligning flex layouts, especially in the about and portfolio sections, required careful tweaking to avoid overflow or stacking issues on smaller screens.
CSS-Only Theme Switcher:
Implementing a fully functioning dark mode toggle without JavaScript was challenging. It required deep knowledge of modern CSS capabilities, especially the :has() pseudo-class which isn't supported in all browsers.
