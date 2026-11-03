# WASSAN Odisha -- Chitrakonda Block Village Visualization Map

An interactive web-based GIS visualization dashboard for **Chitrakonda
Block, Malkangiri District, Odisha**, developed for the **WASSAN
(Watershed Support Services and Activities Network)** initiative.

The application provides an interactive village-level map featuring
administrative boundaries, demographic analytics, dynamic filtering, and
multiple basemap options.

------------------------------------------------------------------------

## 🚀 How to Publish on GitHub Pages

You can publish this interactive map directly using GitHub Pages.

### 1. Create a GitHub Repository

Go to [GitHub -- Create Repository](https://github.com/new) and create a
public repository.

Example repository name: `odisha-chitrakonda-map`

### 2. Upload Project Files

Upload all project files to the repository, especially:

-   `index.html`
-   `geojson_data.js`
-   `wassan_logo.png` (or the exact logo filename used by the project)
-   `District.geojson`
-   `Chitrakonda_block.geojson`
-   `Village_Points.geojson`
-   `.nojekyll`

Also include the Excel and CSV source files if you want them available
in the repository.

### 3. Enable GitHub Pages

1.  Open your GitHub repository.
2.  Go to **Settings → Pages**.
3.  Under **Build and deployment**, select **Deploy from a branch**.
4.  Select the `main` branch.
5.  Select the `/ (root)` folder.
6.  Click **Save**.

### 4. Access Your Live Map

After GitHub Pages finishes publishing, your application will be
available at:

`https://YOUR-GITHUB-USERNAME.github.io/REPOSITORY-NAME/`

Replace `YOUR-GITHUB-USERNAME` and `REPOSITORY-NAME` with your actual
GitHub username and repository name.

------------------------------------------------------------------------

## 🗺️ Key Features

### Administrative Boundary Overlays

-   **Malkangiri District Boundary:** White dashed outline (`#ffffff`)
    with no fill.
-   **Chitrakonda Block Boundary:** Blue outline (`#0284c7`) with no
    fill.

### Village-Level Data Points

-   83 village records.
-   82 plotted village point markers.
-   Color-coded by implementation phase:
    -   🔵 **Phase 1:** Royal Blue
    -   🔷 **Phase 2:** Sky Blue
    -   🟢 **Phase 3:** Emerald Green

### Village Information Dashboard

Click a village point to view its detailed information:

-   Village name and Gram Panchayat (GP).
-   Serial number and implementation phase.
-   Total households and total population.
-   Male and female population.
-   Sex ratio with a visual percentage bar.
-   Geographic coordinates.
-   **Copy Coordinates** and **Google Maps** shortcuts.
-   Minimize and close controls.

### Basemap Switcher

Available basemaps:

1.  Google Satellite (default)
2.  Hybrid Satellite
3.  OpenStreetMap (OSM)
4.  Google Terrain

Additional controls include a **Reset View** button and layer visibility
options.

### WASSAN Branding

-   Official WASSAN logo in the sidebar header.
-   Floating top-left branding badge.
-   Responsive white-and-blue user interface.

### Interactive Sidebar and Filters

-   Search villages and Gram Panchayats.
-   Filter by Gram Panchayat:
    -   Badapada
    -   Papermetla
    -   Panasput
    -   Jodambo
    -   Badapadar
-   Filter by implementation phase (Phase 1, Phase 2, and Phase 3).
-   Interactive village directory.
-   Gram Panchayat distribution chart powered by Chart.js.
-   Layer visibility controls for District, Block, Village Points, and
    Labels.

------------------------------------------------------------------------

## 📁 Repository File Manifest

  -----------------------------------------------------------------------
  File                                Description
  ----------------------------------- -----------------------------------
  `index.html`                        Main responsive web GIS application

  `geojson_data.js`                   Precompiled GeoJSON layers and
                                      village database

  `wassan_logo.png`                   Official WASSAN branding logo (use
                                      the actual filename in the
                                      repository)

  `District.geojson`                  Malkangiri District boundary

  `Chitrakonda_block.geojson`         Chitrakonda Block boundary

  `Village_Points.geojson`            Village point features

  `Chitrakonda Village.xlsx`          Original Excel dataset

  `Chitrakonda Village_csv.csv`       Clean CSV dataset

  `.nojekyll`                         Prevents GitHub Pages from
                                      processing the repository using
                                      Jekyll
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## 💻 Local Testing

You can test the project locally.

### Option 1: Open Directly

Double-click `index.html` to open it in a web browser.

### Option 2: Run a Local Web Server

Using Python:

``` bash
python -m http.server 8000
```

Or using Node.js:

``` bash
npx serve .
```

Then open:

`http://localhost:8000`

------------------------------------------------------------------------

## 🧰 Technology Stack

-   HTML5
-   CSS3
-   JavaScript
-   Leaflet.js
-   GeoJSON
-   Chart.js
-   GitHub Pages

------------------------------------------------------------------------

## 🌐 Project Information

-   **Organization:** WASSAN -- Watershed Support Services and
    Activities Network
-   **Project Location:** Chitrakonda Block, Malkangiri District,
    Odisha, India
-   **Project Name:** Chitrakonda Village Visualization Map
-   **Application Type:** Interactive Web GIS Dashboard

------------------------------------------------------------------------

*Developed for village-level spatial visualization and demographic
information access under the WASSAN initiative.*
