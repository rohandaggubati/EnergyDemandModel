### Output Snapshots, TL;DR
![Energy Demand](https://github.com/user-attachments/assets/ac47fa9a-e33d-48fa-82a1-abb70a48a308)
![LTSM Model Loss](https://github.com/user-attachments/assets/d0b7e5b1-20fd-40f0-a5d1-3944862d9b72)
![Actual v Predicted Demand](https://github.com/user-attachments/assets/60b85931-aada-41b8-8c07-cfbbd3c8b508)
![Actual v Predicted Demand - One Week Detail](https://github.com/user-attachments/assets/ee2e01a3-d0a7-4cf0-ad0d-2fffacbcf403)
![Peak Event Detection](https://github.com/user-attachments/assets/f0a0470b-0b6e-49f3-81f1-05a1ee5294ac)
![Probabilistic Demand Forecast](https://github.com/user-attachments/assets/b4b40772-232d-4b0e-85a9-0238e137194d)
![Probabilistic Demand Forecast - One Week Detail](https://github.com/user-attachments/assets/4587a75b-a474-4baf-b194-a67dd8ec0ff0)
![Forecast and Exceedence](https://github.com/user-attachments/assets/fe26bc2e-0ace-4f2c-82e8-ac6e34843f8a)
![Summary](https://github.com/user-attachments/assets/53624f68-dcfa-4d6d-afbe-da9f0f661417)


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

*Dataset courtesy of Alex Kozlov https://www.kaggle.com/datasets/aramacus/electricity-demand-in-victoria-australia*
