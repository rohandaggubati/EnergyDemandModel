### What it does

- Forecasts electricity demand for power grid planning
- Spots peak demand events before they happen
- Shows how accurate different models are
- Calculates how much $ you could save with better predictions

### How I built it
Used 3 different prediction methods:
- XGBoost
- LightGBM
- LSTM neural net

Then combined them all to get better results than any single model.
### Results

- The combo model was better than any individual model
- Found most peak events with fewer false alarms
- Could save $ in energy costs compared to basic methods

### Next steps

- Add weather data to improve predictions
- Make alerts better for grid operators
- Create a dashboard for real-time monitoring
