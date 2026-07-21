# MoMA Exhibitions Dashboard: 1929–1989

An interactive data visualization dashboard exploring exhibitions held at The Museum of Modern Art between 1929 and 1989.

## Live Dashboard

[Open the interactive dashboard](https://briseidasanchez.github.io/moma_exhibitions_dash/)

## Project Overview

This dashboard provides an interactive overview of MoMA exhibition records from 1929 through 1989. It is designed to make historical exhibition patterns easier to explore across time, topics, artists, institutions, nationalities, and gender representation.

The dashboard includes 34,558 records associated with 1,727 exhibitions.

## Features

Users can:

- Filter exhibitions by decade and topic.
- Explore the number and duration of exhibitions over time.
- Compare exhibitions across thematic categories.
- View the most frequently exhibited artists.
- Examine gender representation by decade.
- Explore the nationalities represented in the exhibition records.
- Select an artist to view the exhibitions in which they participated.
- Open artist and exhibition pages on the current MoMA website.

## Topic Classification

The original data does not include the thematic classification used in the dashboard. I created an additional topic field to organize exhibitions into broader subject categories and support interactive exploration.

The topic variable should be interpreted as a proxy classification rather than an official MoMA category.

## Data Source

The dashboard uses publicly available data from the Museum of Modern Art's GitHub repositories:

[The Museum of Modern Art on GitHub](https://github.com/MuseumofModernArt)

Artist and exhibition links direct users to their corresponding pages on the official MoMA website when available.

## Technology

The dashboard is implemented as a self-contained HTML file using embedded data, styles, and interactive visualization components.

Because the data is embedded directly in `index.html`, the published dashboard does not require a separate database, server, or data directory.

## Repository Structure

```text
moma_exhibitions_dash/
├── index.html
└── README.md
```

- `index.html`: Complete interactive dashboard and embedded data.
- `README.md`: Project documentation.

## Deployment

The dashboard is published with GitHub Pages from this repository:

[https://briseidasanchez.github.io/moma_exhibitions_dash/](https://briseidasanchez.github.io/moma_exhibitions_dash/)

## Author

Briseida Sanchez
