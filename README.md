# Predicting Faults in Aircraft Turbofan Engines

text about the maintenance cost in aircrafts (2nd larger) and predictive maintenance

## C-MAPSS Dataset

Available at NASA's Prognostics Center of Execellence [Data Repository](https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/). The data generated were used as challenge data for the Prognostics and Health Management (PHM) data competition at PHM’08.

C-MAPSS simulates an engine model of the 90,000 lb thrust class and the package includes an atmospheric model capable of simulating operations at (i) altitudes ranging from sea level to 40,000 ft, (ii) Mach numbers from 0 to 0.90, and (iii) sea-level temperatures from –60 to 103 °F. The package also includes a powermanagement system that allows the engine to be operated over a wide range of thrust levels throughout the full range of flight conditions.

The data produced was divided into training and test sets. Each series in the train set runs until system failure while the test set was terminated some time before any faults.

The target of the regression was the number of remaining cycles before failure.

The training set had trajectories that ended at the failure threshold while the test and validation sets were pruned to stop some time prior to the failure threshold.

>*A purely data-driven approach takes no account of any prior system knowledge and therefore effective visualization of the data is a key first step in gaining an understanding of an unknown dataset.*

The outputs include various sensor response surfaces and operability margins. A total of 21 variables out of 58 different outputs available from the model were used in this study.

## Data Exploration

PCA analysis, clusterization

