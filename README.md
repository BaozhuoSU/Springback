# Springback Error Optimization

> A comprehensive showcase of the mathematical models and codebase used to minimize springback error, developed during my internship at **LINKCONN Electronics**.

---

## 🧮 Theoretical Foundations
- **Bilevel Optimization**  
  - Formulated the springback minimization as a nested (upper–lower) decision problem.  
  - Derived optimal control variables at the lower level, subject to upper-level design constraints.
- **Stochastic Modeling**  
  - Modeled variability in material properties and process conditions with probabilistic distributions.  
  - Applied Monte Carlo sampling to estimate error distributions and robustify the solution.

---

## 💻 Implementation & Experiments
1. **Data Preprocessing**  
   - Cleaning and normalization of measurement datasets  
   - Feature extraction and augmentation scripts  
2. **Model Training & Hyperparameter Tuning**  
   - Automated pipelines using `scikit-learn` and `Optuna`  
   - Cross-validation and grid/random search for optimal parameters  
3. **Simulation & Results Analysis**  
   - Jupyter notebooks for running batch simulations  
   - Visualization of error reduction, convergence plots, and sensitivity analyses

---

> **📂 Repository Structure**  
> ```
> .
> ├── docs/                      # Detailed theory write-ups
> ├── data/                      # Raw and processed datasets
> ├── notebooks/                 # Experiment and visualization notebooks
> ├── src/                       # Core code (preprocessing, modeling, utils)
> └── README.md                  # Project overview
> ```

> **🔗 Quick Links**  
> - [Theoretical Derivations](docs/theoretical_foundations.md)  
> - [Getting Started Guide](docs/GETTING_STARTED.md)  
> - [Live Demo & Screenshots](docs/demo.md)


