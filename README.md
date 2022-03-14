# AMWA NMOS CI Dashboard

<a href="https://github.com/AMWA-TV/nmos/actions?query=workflow%3ALint"><img src="https://github.com/AMWA-TV/nmos/workflows/Lint/badge.svg"/></a> 
<a href="https://github.com/AMWA-TV/nmos/actions?query=workflow%3ARender"><img src="https://github.com/AMWA-TV/nmos/workflows/Render/badge.svg"/></a> 

<!-- INTRO-START -->

### What does it do?

- Renders a Dashboard for AMWA NMOS Specifications
- Shows state of lint and render
- Gives a summary of issues and pull requests

### Why does it matter?

- Helps us with maintaining the specifications

### How does it work?

- Gets list of specs from <https://specs.amwa.tv/nmos/spec_list.json> 
- Uses GitHub badges and API

<!-- INTRO-END -->

{% include dashboard_table.html %}
