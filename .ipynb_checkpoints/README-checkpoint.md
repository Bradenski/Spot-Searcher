# Skate Spot Finder 🛹

**AI-Powered Skateboarding Spot Discovery**

Built at the AI Tinkerers New York City Computer Vision Hackathon with Moondream - Automatically identify skateable features in street imagery using computer vision.

![Demo Map](demo_map.png) 

## 🎯 Problem Statement

Skateboarders spend countless hours "spot hunting" - driving or skating around cities to discover skateable features like ledges, stairs, and benches. This process is time-consuming and relies heavily on local knowledge. 

## 💡 Solution

Skate Spot Finder leverages Moondream's 1GB vision-language model to automatically detect skateable features in Google Street View imagery, creating an interactive map of discovered spots across NYC.

## 🚀 Features

- **Automated Feature Detection**: Identifies benches, ledges, and stair sets using Moonbeams 1GB VLM
- **Interactive Mapping**: Visual map interface with embedded street view images
- **Location Aggregation**: Clusters skateable features by geographic location
- **Visual Validation**: Click on map pins to see detected features in context
- **Scalable Pipeline**: Built to process any area with Street View coverage

## 🛠️ Technical Stack

- **AI Model**: Moondream 1GB vision-language model
- **Data Processing**: Python, Pandas, PIL
- **Mapping**: Folium with custom HTML popups
- **Development**: Jupyter Notebook
- **Image Encoding**: Base64 for embedded map images

## 📊 Results

- Successfully analyzed 9 NYC skateboarding locations
- Achieved strong performance in detecting architectural features, and challenged current definitions of spot nomenclature
- Visual validation confirmed correlation between AI detections and actual skateable infrastructure
- Demonstrated scalability for citywide analysis


## 📈 How It Works

1. **Data Collection**: Curate street view images of known skateboarding spots with GPS coordinates
2. **AI Processing**: Feed images through Moondream VLM with skateboarding-specific prompts
3. **Feature Extraction**: Parse model outputs to identify skateable features
4. **Geographic Mapping**: Aggregate detections by location and create interactive map
5. **Visual Validation**: Embed original images in map popups for verification

## 🎮 Demo

The interactive map shows:
- 📍 Precise GPS coordinates of detected spots
- 🖼️ Original street view imagery
- 🏷️ AI-detected features (bench, ledge, stairs, handrail)
- 📊 Comparison with ground truth labels

## 🏆 Hackathon Motivations

- **Theme Alignment**: Direct integration of Moondream VLM with NYC geographic data
- **Civic Impact**: Democratizes access to skateboarding infrastructure across diverse neighborhoods
- **Innovation**: First AI-powered solution for systematic skate spot discovery


## 🙏 Acknowledgments

- **Moondream** for providing the vision-language model and hackathon platform
- **OpenStreetMap & Google** for geographic data and street imagery


*"NBDs for everyone!"* 🛹