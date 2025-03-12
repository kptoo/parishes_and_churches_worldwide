# Catholic Churches Map

An interactive worldwide map of Catholic churches, basilicas, cathedrals, and parishes.

## Features

- Interactive visualization of over 143,000 Catholic churches worldwide
- Filter churches by:
  - Country (all countries with churches in the database)
  - Jurisdiction (Diocese, Archdiocese, etc.)
  - Type (Basilica, Cathedral, Parish Church, Church)
  - Rite (Roman/Latin, Ukrainian/Byzantine, Syro-Malabar)
- Visual differentiation for different church types:
  - Basilicas: Gold diamonds
  - Cathedrals: Purple triangles
  - Parish Churches: Blue squares
  - Churches: Gray circles
- Marker clustering for better performance
- Viewport filtering to efficiently display only visible churches
- Mobile-friendly responsive design
- Collapsible filter and legend panels

## Usage

### Basic Navigation

- Pan the map by clicking and dragging
- Zoom in/out using the buttons in the top-left or your mouse wheel
- Click on church markers to see detailed information
- Click on clusters to zoom in and see individual churches

### Filtering

1. Use the filter panel in the top-right corner
2. Select options from any of the dropdown menus:
   - Choose a country to see only churches in that nation
   - Select a jurisdiction to focus on a specific diocese or archdiocese
   - Filter by type to see only basilicas, cathedrals, etc.
   - Select a specific rite
3. Filters can be combined (e.g., select both a country and a type)
4. Use the "Reset Filters" button to clear all selections

## Data Source

This map uses data compiled from GCatholic Site. The database includes information about:
- Church names and titles
- Jurisdictions (dioceses, archdioceses)
- Types (basilicas, cathedrals, parishes, churches)
- Rites (Roman/Latin, Ukrainian/Byzantine, Syro-Malabar)
- Geographic locations
- Addresses

## Technical Implementation

- Built with Leaflet.js for mapping functionality
- Uses Leaflet.markercluster for clustering
- Custom styling for different church types
- Optimized for performance with large datasets
- Implements viewport filtering to handle the 143,000+ locations efficiently

## Future Enhancements

- Integration with additional church datasets
- Advanced search functionality
- Timeline visualization of church founding dates
- Historical information display
- Additional basemap options

## Contact

For questions, feedback, or inquiries about this project, please contact winermmanuel@gmail.com
