# Olympics Analysis Dashboard

This project is a Streamlit-based web application that provides comprehensive analysis of Olympic Games data. It offers various insights and visualizations about medal tallies, overall statistics, country-wise performance, and athlete-specific analysis.

## Features

1. **Medal Tally**: 
   - View medal counts by year and country
   - Filter results for specific years or countries

2. **Overall Analysis**:
   - Display key statistics (editions, hosts, sports, events, nations, athletes)
   - Visualize trends over time for participating nations, events, and athletes
   - Heat map of events per sport over the years
   - List of most successful athletes (overall or by sport)

3. **Country-wise Analysis**:
   - Medal tally over the years for a selected country
   - Heat map of a country's performance in different sports
   - Top 10 athletes for a selected country

4. **Athlete-wise Analysis**:
   - Age distribution of athletes (overall and medal winners)
   - Age distribution of gold medalists by sport
   - Height vs Weight scatter plot for athletes
   - Men vs Women participation trends over the years

## Technologies Used

- Python
- Streamlit
- Pandas
- Plotly
- Matplotlib
- Seaborn

## Setup and Installation

1. Clone this repository
2. Install the required packages:
3. ``pip install -r requirements.txt``
4. Run the Streamlit app:
5. ``streamlit run app.py``
## Data Sources

This project uses two main data files:
- `athlete_events.csv`: Contains details about athletes, events, and medals
- `noc_regions.csv`: Mapping of NOC (National Olympic Committee) codes to regions

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check [issues page](link-to-your-issues-page) if you want to contribute.

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Contact

Your Name - [your-email@example.com](mailto:your-email@example.com)

Project Link: https://olymicsanalysis.streamlit.app/
