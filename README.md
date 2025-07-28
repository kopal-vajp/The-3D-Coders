# Space Mission Control Dashboard 🚀

A comprehensive web-based dashboard that visualizes live and simulated space mission data, providing real-time insights into satellite telemetry, ISS location tracking, Mars weather conditions, and asteroid monitoring.

## 🌟 Features

### Real-time Data Visualization
- **Satellite Telemetry**: Live streaming of satellite data with real-time status updates
- **ISS Location Tracking**: Current International Space Station position and orbital data
- **Mars Weather Monitoring**: Atmospheric conditions and surface weather data from Mars
- **Asteroid Tracking**: Near-Earth object detection and trajectory visualization

### Interactive Dashboard Components
- **System Status Monitor**: Real-time system health indicators
- **Mission Log**: Timestamped mission events and telemetry updates
- **Live Earth Simulation**: 3D visualization of Earth with satellite tracking
- **Data Streams**: Multiple concurrent data feeds with filtering capabilities

### Space Agency Integration
- Support for multiple space agencies (NASA, SpaceX, ESA, ISRO, Roscosmos)
- Agency-specific mission data and branding
- Collaborative mission monitoring capabilities

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Custom CSS with animations and responsive design
- **Media**: MP4 video integration for dynamic backgrounds
- **Icons**: Boxicons for consistent UI elements
- **Animations**: AOS (Animate On Scroll) library

## 📁 Project Structure

```
Space-Data/
├── index.html              # Main dashboard interface
├── style.css              # Comprehensive styling and animations
├── app.js                 # JavaScript functionality
├── images/                # Space mission assets
│   ├── astronaut.png      # Logo and branding
│   ├── active.jpg         # Data stream indicators
│   ├── lines.png          # Mission log visualizations
│   ├── worldfulll.png     # Earth visualization
│   ├── nasaa.png          # NASA branding
│   ├── spaceX.png         # SpaceX integration
│   ├── esa.png            # European Space Agency
│   ├── isro.png           # Indian Space Research Organisation
│   ├── roscosmos.png      # Russian space agency
│   ├── satellite.png      # Satellite tracking
│   ├── iss.png            # International Space Station
│   ├── mars.png           # Mars mission data
│   └── Blue.png           # Blue Origin integration
├── videos/                # Dynamic mission content
│   ├── galaxy.mp4         # Background space visualization
│   ├── blackhole.mp4      # Astronomical phenomena
│   ├── hero-video.mp4     # Main dashboard animation
│   ├── glob.mp4           # Earth simulation
│   ├── Mars.mp4           # Mars atmospheric feed
│   ├── ISS.mp4            # ISS location tracking
│   └── Asteroid_Tracking_Video_Creation.mp4
└── README.md              # Project documentation
```

## 🚀 Quick Start

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, for development)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/kopal-vajp/Space-Data.git
   cd Space-Data
   ```

2. **Launch the dashboard**
   - Open `index.html` in your web browser
   - Or serve using a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   
   # Using Live Server (VS Code extension)
   Right-click index.html → Open with Live Server
   ```

3. **Access the dashboard**
   - Direct file: `file:///path/to/index.html`
   - Local server: `http://localhost:8000`

## 🎯 Dashboard Sections

### 1. Mission Control Header
- Real-time navigation with space mission links
- Social media integration for space agencies
- Responsive mobile-friendly design

### 2. Dashboard Overview Cards
- **System Status**: All systems nominal indicator
- **Active Data Streams**: Live telemetry feeds
- **Live Earth Simulation**: Real-time globe with ISS tracking
- **Mission Log**: Timestamped space mission events

### 3. Live Mission Feeds
- **Mars Atmospheric Feed**: CO2 levels and atmospheric data
- **Current ISS Location**: Orbital position and speed data
- **Asteroid Tracking API**: Near-Earth object monitoring

### 4. Space Data Visualization
- **Real-time Data Streaming**: Dynamic telemetry visualization
- **Trajectory Visualization**: 3D orbital path plotting
- **Agency Carousel**: Rotating display of space agencies

## 🌐 Live Data Sources

The dashboard is designed to integrate with various space data APIs:

- **NASA APIs**: Open data from NASA's extensive catalog
- **SpaceX API**: Launch schedules and vehicle telemetry
- **ISS Location API**: Real-time position tracking
- **Mars Weather API**: Surface conditions from rovers
- **Asteroid Database**: Near-Earth object tracking

## 📱 Responsive Design

- **Desktop**: Full dashboard with all features
- **Tablet**: Optimized layout with touch-friendly controls
- **Mobile**: Compact view with essential mission data
- **Breakpoints**: 1200px, 700px, 480px for optimal viewing

## 🎨 Visual Features

### Animations
- Smooth scroll animations with AOS library
- Auto-blur effects for immersive experience
- Gradient text animations for space theme
- Carousel animations for agency showcase

### Theme
- Dark space-inspired color scheme
- Glowing effects and neon accents
- Video backgrounds for dynamic experience
- Glassmorphism UI elements

## 🔧 Customization

### Adding New Data Sources
1. Extend the mission cards in `index.html`
2. Add corresponding video/image assets
3. Update CSS styling in `style.css`
4. Implement data fetching in `app.js`

### Modifying Agencies
- Add new agency logos to `/images/`
- Update the slider component in HTML
- Adjust carousel positions in CSS

### Theme Customization
- Modify CSS variables for color schemes
- Update gradient definitions
- Adjust animation timings and effects

## 🚀 Future Enhancements

- [ ] Real-time API integration for live data
- [ ] Interactive 3D Earth model with WebGL
- [ ] Mission planning and trajectory calculation tools
- [ ] Multi-language support for international agencies
- [ ] Advanced filtering and data export features
- [ ] WebSocket connections for real-time updates
- [ ] Augmented reality features for mobile devices

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **NASA**: For providing open space data and inspiration
- **SpaceX**: For revolutionizing space technology
- **ESA, ISRO, Roscosmos**: For international space collaboration
- **AOS Library**: For smooth scroll animations
- **Boxicons**: For consistent iconography

## 📞 Contact

**The 3D Coders Team**
- Repository: [The-3D-Coders](https://github.com/kopal-vajp/The-3D-Coders.git)
- Issues: [Report Bug](https://github.com/kopal-vajp/The-3D-Coders/issues)

---

*Made with ❤️ by The 3D Coders - Exploring the cosmos through code*
