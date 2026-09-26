# SurakshaNet

> **Privacy-Aware Early Warning Public Health Surveillance Platform**

SurakshaNet is a prototype that connects **health signals, weather, water conditions, environmental context, and citizen reports** to help authorities identify unusual health patterns earlier while preserving privacy.

Rather than waiting for outbreaks to become obvious, SurakshaNet helps transform scattered observations into connected public-health awareness.

---

## The Problem

Public health threats rarely begin with a dramatic event.

A rural Primary Health Centre may notice a few unusual cases.

A district hospital may see similar symptoms.

Citizens may report illness in their community.

Heavy rainfall or water-quality changes may also occur.

Individually these signals appear ordinary.

Together they may indicate something important.

SurakshaNet connects these signals into one regional surveillance picture.

---

## How SurakshaNet Works

Data Collection

↓

Privacy Protection

↓

Data Aggregation

↓

Historical Baseline Comparison

↓

Anomaly Detection

↓

Risk Assessment

↓

Early Warning

↓

Human Investigation & Response

---

## Key Features

* Rural PHC, CHC and Hospital Surveillance
* Weather Monitoring (Rainfall, Temperature, Humidity)
* Water Quality Monitoring
* Citizen Health Reporting
* Privacy-aware Data Processing
* Historical Baseline Comparison
* Surge Ratio & Z-Score Detection
* Medical Board Console
* Human-authorized Emergency Alerts

---

## Environmental Intelligence

SurakshaNet does more than count patients.

It considers:

* Heavy rainfall
* Flooding
* Waterlogging
* Water-quality indicators
* Temperature
* Humidity

These environmental signals are treated as **context**, helping authorities investigate unusual health patterns without assuming direct causation.

---

## Screenshots

| Dashboard              | Radar              |
| ---------------------- | ------------------ |
| `assets/dashboard.png` | `assets/radar.png` |

| Environmental Monitoring              | Medical Board              |
| ------------------------------------- | -------------------------- |
| `assets/environmental-monitoring.png` | `assets/medical-board.png` |

---

## Technology Stack

* Python
* Streamlit
* Pandas
* NumPy
* Plotly
* Statistical Analysis
* Privacy-aware Processing

---

## Running the Project

```bash
git clone https://github.com/CoolAnt001/SurakshaNet-3.0.git

cd SurakshaNet-3.0

pip install -r requirements.txt

streamlit run app.py
```

---

## Demo Flow

1. Open Dashboard
2. Select Waterborne Scenario
3. Observe PHC and Hospital signals
4. Watch Weather & Water indicators
5. Compare with Historical Baseline
6. View Z-Score anomaly
7. Submit Citizen Report
8. Open Medical Board Console
9. Authorize Early Warning

---

## Future Scope

* Real-time weather APIs
* Live water-quality feeds
* GIS mapping
* AI-assisted anomaly forecasting
* Mobile reporting app
* Government health-system integration

---

## License

This project is released under the MIT License.
