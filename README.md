☕ Java & PDI Integration
This ETL project uses Pentaho Data Integration (PDI) for designing and executing data transformation workflows. PDI provides a powerful graphical interface (Spoon) to build ETL jobs without extensive coding. It works seamlessly with Java Development Kit (JDK 24) to run the underlying Java-based engine.

🔧 Setup Notes:
Ensure JDK 24 is properly installed and added to your system’s environment variables.

PDI requires a compatible Java version (JDK 8 to 17 is recommended), but if you're using JDK 24, make sure the environment is configured correctly to avoid compatibility issues.

Launch Spoon.bat (on Windows) or spoon.sh (on Linux/Mac) to start building transformations and jobs.

✅ PDI Highlights in This Project:
Designed and executed .ktr (transformation) and .kjb (job) files.

Connects to data sources like CSV, Excel, and relational databases.

Performs visual transformations: filtering, mapping, joining, and cleansing.

Scheduled or triggered jobs for automated ETL.
