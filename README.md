# D Line Extension Corridor Survey

**[View the live map →](https://tedmccormick.github.io/D_Line_Extension_Vacant_Parcels/)**

A "before" picture of the neighborhoods along the Los Angeles Metro D Line (Purple Line) subway extension, documented by bicycle before the new stations change them.

What this is

The D Line extension is bringing new subway stations west along Wilshire Boulevard. New transit tends to reshape the blocks around it, so this project records what those blocks look like now: empty lots, abandoned buildings, and underused properties, many marked with "For Rent," "For Lease," or "For Sale" signs on residential and commercial buildings.

The site presents the survey as an interactive map with a sortable data table. Each parcel appears in both.

How the survey was done
Method: street-level field survey by bicycle, photographing properties from the public right-of-way
Fieldwork: six outings between March 13 and April 13, 2026
Photos: roughly 900
GIS work: mapped and analyzed in ArcGIS Pro / ArcGIS Online (UCLA Geography)

[Optional: one or two sentences on how you chose which properties to include, and what the status categories mean.]

What's in this repo
File	What it is
index.html	The whole website: map, table, and text in one file
parcels.csv	The survey data in spreadsheet form, also used for ArcGIS Online
README.md	This file

The map is built with Leaflet. Base map tiles come from OpenStreetMap.

Updating the data

Survey records live in the PARCELS list inside the <script> section of index.html. Look for the banner that says EDIT YOUR DATA HERE. One entry per parcel draws both the map marker and its table row. Keep parcels.csv in sync when you change it.

The site is hosted free on GitHub Pages and updates about a minute after each commit to main.

Data notes and caveats
Conditions were recorded on the survey dates and may have changed since.
Parcel details (use codes, size, zoning) come from public LA County Assessor and city records, which can lag behind what's on the ground. For example, a parking lot may be listed as "vacant land."
[Optional: any note on privacy, e.g. whether addresses or house numbers are generalized.]
Credits

Reporting, photography, and field survey by Ted McCormick. Built in Los Angeles, 2026. Base map © OpenStreetMap contributors.

[Optional: add a license line, e.g. "Photos © Ted McCormick, all rights reserved. Code available under the MIT License."]
