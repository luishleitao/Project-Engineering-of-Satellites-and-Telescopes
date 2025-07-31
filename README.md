# 🛰️ PL Satellites Report – Ephem Orbit Propagation

This repository contains a Jupyter Notebook for a satellite observation and orbit analysis activity, using Python and the `ephem` library. It is based on a template developed by **Prof. André Moitinho**, and was completed by **Luís Leitão** as part of coursework at the University of Lisbon.

## 📄 Notebook Overview

The notebook guides the user through:

1. **Setting up Python libraries** for astronomical calculations and plotting.
2. **Defining an observation site** (e.g. Bissau, Guinea-Bissau).
3. **Loading and interpreting TLE data** for Earth-orbiting satellites (e.g. PoSAT-1).
4. **Using the `ephem` library** to propagate satellite orbits using the SGP4 model.
5. **Plotting and analyzing orbital parameters** visually.
6. **Understanding the structure and methods** of `ephem.Observer` and `ephem.EarthSatellite` objects.

## 🧰 Technologies Used

- Python 3
- [PyEphem](https://rhodesmill.org/pyephem/)
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## 📂 File Structure

```
.
├── PL_Satellites_ReportTemplate.ipynb   # Main notebook with code and answers
├── README.md                            # This file
└── data/                                # (Optional) Folder for TLE files or extended data
```

## 📌 Example Topics Covered

- TLE interpretation
- SGP4 orbit propagation
- Observer-satellite geometry
- Plotting satellite ground tracks
- Satellite visibility analysis

## 🧑‍🎓 Author

**Luís Leitão**  
Student number: 61424  
Physics & Astronomy enthusiast  
University of Lisbon

## 📝 License

This repository is for academic and educational purposes only. Attribution to the original template author (Prof. André Moitinho) is included.
