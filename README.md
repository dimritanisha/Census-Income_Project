# Census Income Project

## 🧠 Problem Statement

This project uses data extracted from the 1994 Census Bureau database by Ronny Kohavi and Barry Becker (Data Mining and Visualization, Silicon Graphics). 

The dataset includes clean records filtered using the following conditions:



The goal is to predict whether a person earns more than $50K per year.

---

## 📊 Description of `fnlwgt` (Final Weight)

The `fnlwgt` attribute stands for "final weight" and is used by the Census Bureau to produce population estimates. It reflects how many people in the U.S. population a single record represents, based on various controls.

### The weights are adjusted using:
- A single cell estimate of the population 16+ for each state.
- Controls for Hispanic origin by age and sex.
- Controls by race, age, and sex.

Weights are raked through all control categories multiple times to ensure accurate representation. These weighted tallies help model real-world demographic characteristics.

---

## 📁 Project Structure

