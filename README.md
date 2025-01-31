Windy - Wind Energy Assistant

Windy is a Streamlit based AI assistant designed to provide insights and solutions related to wind energy. It uses Groq AI model to answer questions about wind turbines, energy generation, environmental impact, maintenance, cost analysis, and global trends in the wind energy industry.

Features
- Wind Turbine Operation – Understand how wind turbines generate energy and factors affecting their efficiency.
- Energy Generation Calculations – Calculate potential energy output based on wind conditions and turbine specs.
- Environmental Impact – Learn about carbon emission reduction and sustainability benefits.
- System Maintenance – Get recommendations on maintaining wind turbines for optimal performance.
- Cost and Investment – Explore cost benefit analyses, subsidies, and ROI for wind energy.
- Global Wind Energy Trends – Stay updated on new technologies and industry developments.

Installation
To run Windy locally, follow these steps

1. Clone the repository
   git clone https github com yourusername windy git
   cd windy

2. Create a virtual environment and activate it
   python -m venv venv
   source venv bin activate   On Windows use venv Scripts activate

3. Install the required dependencies
   pip install -r requirements txt

4. Set up your API key for Groq
   - Update the initialize groq client function with your Groq API key

5. Run the Streamlit app
   streamlit run app py

Usage
1. Open the web interface provided by Streamlit
2. Enter your wind energy related query in the chat input box
3. Windy will provide concise informative responses based on reliable data

Technologies Used
- Streamlit – Interactive web UI
- Groq AI – AI powered responses
- Python 3 8 plus

Contributing
Feel free to fork the repository and submit pull requests to enhance Windy

Happy learning about wind energy
