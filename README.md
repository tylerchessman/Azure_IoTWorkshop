# Azure_IoTWorkshop
Hands-On workshop: Using Azure Data Services to ingest and monitor IOT data for predictive maintenance

### Summary
In these hands-on labs, participants design/build an architecture to ingest, query, store and visualize asset (equipment) performance data.  You start by exploring historical run-to-failure data to understand general trends/patterns – and validate that the historical data can be used to build a machine learning model for predicting future failures (i.e. remaining useful life (RUL), mean-time to failure, etc.).

After the machine learning model is built and deployed, subsequent production data is collected in near real-time - to monitor performance across a fleet of assets.  A Power-BI dashboard, where historical, near real-time, and ML predictive data is combined, serves as the "single pane of glass".

These labs are based on a solution template available in the Azure Gallery (https://gallery.azure.ai/Solution/Predictive-Maintenance-10).  The original predictive maintenance machine learning models are also in the gallery - https://gallery.azure.ai/Collection/Predictive-Maintenance-Template-3. 

#### Notes
* This workshop is designed be instructor-led (over a ~1 day timespan); see the included PowerPoint for background material and a suggested flow.
* The labs were developed a few years ago; the cloud is a fast-paced environment, and there are opportunities to consider alternative/enhanced technlogies (e.g. a different ML platform).  The PowerPoint point deck was recently updated (Oct. 2020) but may still reference older platform options.
* The data simulator source code is available at https://github.com/RaviTella/SimulatorLight. 
