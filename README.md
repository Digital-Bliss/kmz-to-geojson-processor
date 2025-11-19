# KMZ to GeoJSON Processor

A web-based tool to convert KMZ files to GeoJSON format, specifically designed for wayleave application processing and fiber network conflict analysis.

## 🎯 Purpose

This tool helps convert KMZ files (from Google Earth) into GeoJSON format that can be used in:
- Fiber network conflict detection
- Wayleave application processing
- Spatial analysis workflows
- n8n automation workflows

## 🚀 Live Demo

Access the converter here:  
**https://yourusername.github.io/kmz-to-geojson-processor**

## 📁 How to Use

1. **Visit the live demo URL**
2. **Upload your KMZ file** (drag & drop or click to browse)
3. **Get GeoJSON output** that you can:
   - Copy to clipboard
   - Download as .geojson file
   - Use directly in n8n workflows

## 🔧 Integration with n8n

After converting your KMZ to GeoJSON:

1. Copy the GeoJSON output
2. Use it in your n8n "Wayleave-Network-Comparison2" node
3. The GeoJSON will be in the correct format for spatial analysis

## 🛠️ Technical Details

- **Client-side processing** - No data sent to servers
- **Uses toGeoJSON library** for KML conversion
- **Handles KMZ as ZIP archives** with JSZip
- **Outputs standard GeoJSON** format

## 📄 Supported Formats

- ✅ KMZ files (compressed KML)
- ✅ KML content with points, lines, polygons
- ✅ Google Earth export formats

## 🤝 Contributing

Feel free to submit issues and enhancement requests!
