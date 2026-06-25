# project-management-analytics

I put this project together to solve a common headache: tracking project progress, resources, and budget health across different teams without jumping between five different tools. 

This dashboard is a clean, centralized view built directly in Excel. It bridges the gap between high-level management updates and daily task completions, making it easy to spot which projects are hitting roadblocks before things go off the rails.

##  Key Focus Areas

* **Health and Efficiency:** Tracks the Schedule Performance Index (SPI) across web, marketing, and infrastructure teams to ensure projects are actually moving forward.
* **Financial Oversight:** Keeps an eye on budget variances and total spend so we don't accidentally over-allocate capital.
* **Team Capacity Planning:** Includes a weekly breakdown of where engineering effort goes (Development vs. Testing vs. Planning) to avoid burnout.
* **Risk Triage:** Features a dedicated, color-coded "At-Risk" watch list so leadership instantly knows what needs immediate attention.

## 🗂️ Project Structure

* `project-management-analytics.xlsx` - The core workbook containing the live dashboard interface, lookup tables, and interactive visual data.
* `assets/` - Repository image files and dashboard layout previews for quick viewing.

## 🛠️ Thoughts on Building This
When designing the layout, my main goal was scannability. I positioned the critical KPIs right at the top so anyone opening the sheet gets an instant temperature check. The bottom half breaks the data down by project type and priority, relying heavily on conditional formatting and native stacked column charts to give depth to the raw data rows.

*Note: The datasets and project names used here are mock data designed to showcase the architecture and visual workflow.*
