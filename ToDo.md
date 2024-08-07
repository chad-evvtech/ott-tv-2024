# OTT Live TV 2024 Roundup - To Do List

- [ ] Fix page jumping to top when clicking gallery links: a href="#"
	- side-effect of light lightbox's dynamic linking option
		- Can I just edit the script to replace "#/" instead?
		- Use JS to select all links inside the gallery element and apply e.preventDefault(); (disable default event handler)