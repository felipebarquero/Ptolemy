# Interactive Geographical Plotting PWA


## Overview


**Interactive Geographical Plotting PWA** is a Progressive Web App built with **Blazor** that enables users to create, customize, and share interactive plots of geographical data. It supports real-time rendering, data transformations, and multiple mapping layers to provide rich insights into spatial data.

## Features

- **Progressive Web App**: Installable and works offline.
- **Interactive Maps**: Utilize mapping libraries (e.g., Leaflet, OpenLayers) for dynamic plotting.
- **Data Integration**: Supports multiple data formats, including GeoJSON, CSV, and Shapefiles.
- **Customizable Visuals**: Adjust colors, scales, and layers to visualize data effectively.
- **Real-time Updates**: WebSocket support for live data streaming.
- **Export & Share**: Save plots as images or share via URL.

## Quickstart

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/felipebarquero/ptolemy.git
   cd your-project
   ```
2. Install dependencies:
   ```sh
   dotnet restore
   ```
3. Run the app:
   ```sh
   dotnet run
   ```
4. Open in a browser:
   ```
   http://localhost:5000
   ```

### PWA Installation
- Open the app in a supported browser (Chrome, Edge, etc.).
- Click the **Install** button in the address bar or use the PWA install prompt.
- Launch the app from your home screen or applications menu.

## Technologies Used

- **Blazor WebAssembly** - .NET-based front-end framework.
- **Leaflet / OpenLayers** - Mapping and visualization.
- **ASP.NET Core** - Backend services.
- **WebSockets / SignalR** - Real-time communication.
- **IndexedDB / LocalStorage** - Offline data caching.

## Deployment

To deploy the application to a production environment:

```sh
# Publish Blazor WebAssembly
 dotnet publish -c Release -o ./publish
```

Host the **wwwroot** folder in a static file server such as **Azure Static Web Apps, AWS S3, or GitHub Pages**.

## Contributing

1. Fork the repository.
2. Create a new branch:
   ```sh
   git checkout -b feature-new-plot
   ```
3. Commit changes and push:
   ```sh
   git commit -m "Added new plotting feature"
   git push origin feature-new-plot
   ```
4. Open a Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For issues or feature requests, please [open an issue](https://github.com/your-repo/your-project/issues) or contact us at [support@example.com](mailto:support@example.com).

