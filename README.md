# Gas_Flaring_Prediction
## 1. Introduction
Gas flaring is the controlled burning of natural gas associated with oil extraction. It has persisted since the dawn of the oil industry over 160 years ago. Despite its long history, the practice remains a pervasive global challenge. The gas is wastefully flared for a variety of reasons, ranging from market and economic constraints, to a lack of capture infrastructure, to the absence of effective and enforced regulations, and a lack of operational priority by field operators.

The environmental and economic consequences are staggering. Flaring represents a squandering of a valuable natural resource that should either be used for productive purposes such as generating electricity or for conservation. To put the scale into perspective, the amount of gas currently flared each year is approximately **167 billion cubic meters (bcm)**.This is equivalent to Africa's entire annual gas consumption. This waste translates directly into millions of tons of CO₂ and black carbon emissions, accelerating climate change while simultaneously depleting a potential energy source for developing nations.

## 2. Problem Statement
While flaring is broadly categorized by intensity (Low, Medium, High), these qualitative labels are insufficient for precise environmental accounting, carbon tax calculations, or engineering diagnostics. Regulators, environmental agencies, and energy companies require **exact, continuous estimates** of flaring volume (in million m³) to:

- Accurately calculate greenhouse gas emissions for compliance and carbon markets.
- Identify operational inefficiencies or equipment failures that cause sudden deviations in flaring.
- Prioritize investments in gas-capture infrastructure based on expected recovery volumes.

The primary objective of this project is to develop a robust **supervised machine learning regression model** capable of predicting the precise annual flaring volume (in million m³) at individual oil and gas extraction sites.

## 3. Methodology
Using a comprehensive dataset sourced from the World Bank, containing field-specific attributes including geographic location (latitude/longitude), production metrics ('bcm' and 'MMscfd'), field type (Oil/Gas/LNG), operator identity, and onshore/offshore designation, we will train and evaluate multiple regression algorithms to achieve the following:

1.  **Minimize Prediction Error**: Achieve a low Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE) to ensure predictions are reliable for real-world decision-making.
2.  **Maximize Explained Variance**: Obtain a high R² score to confirm that the chosen features effectively capture the drivers of flaring behavior.
3.  **Provide Actionable Insights**: Identify which features (e.g., production rate, geographic region, operator) most strongly influence flaring volume, offering stakeholders clear levers for reduction.

**Target Variable**: 'flaringvolume(mm3)'  
**Evaluation Metrics**: R² Score, RMSE, MAE

## 4. Results

## 5. Key Insights

## 6. Recommendations


