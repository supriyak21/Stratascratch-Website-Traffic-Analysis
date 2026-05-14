### Project Overview: 
Exploratory data analysis of web traffic events from Linkfire music links over a 7-day period (Aug 19–25, 2021). Built using Python, Pandas, and SciPy. The dataset contains 226,278 web traffic events across 3,839 unique links, capturing three event types — pageviews, clicks, and previews — along with geographic and music content metadata.


### Goal:  
To understand traffic volume, distribution, and click engagement, and to identify patterns that could inform strategies to increase click rates.


### Dataset
| Column | Description |
|--------|-------------|
| `event` | Event type: `pageview`, `click`, or `preview` |
| `date` | Date of the event (7-day window) |
| `country` / `city` | Geographic origin of the traffic |
| `artist` / `album` / `track` | Music content metadata |
| `isrc` | International Standard Recording Code |
| `linkid` | Unique identifier for each link |


### Tech Stack:
- Python 3.12
- Pandas
- SciPy
- NumPy


### Key Takeaways:
- Preview engagement is a strong leading indicator of click activity — improving preview visibility could drive higher click rates
- A small subset of links (high-traffic artists like Tesher / Jalebi Baby) dominate total event volume
- Geographic diversity is high (200+ countries) but content metadata clusters tightly around a few top artists
