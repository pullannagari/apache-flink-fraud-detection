# Fraud Detection with Apache Flink

This project implements a fraud detection system using Apache Flink. The system processes transaction data and generates alerts for potentially fraudulent activities.

## Project Structure

- `src/main/java/spendreport/FraudDetector.java`: Contains the `FraudDetector` class, which implements the logic for detecting fraudulent transactions.
- `src/main/java/spendreport/FraudDetectionJob.java`: Contains the `FraudDetectionJob` class, which sets up the Flink job to process transactions and generate alerts.
- `.gitignore`: Specifies files and directories to be ignored by Git.

## Prerequisites

- Java 8 or higher
- Apache Maven
- Apache Flink

## Building the Project

To build the project, run the following command:

```sh
mvn clean package