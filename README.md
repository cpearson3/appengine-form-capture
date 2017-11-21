# Form Capture Service for Google App Engine

A simple web service and admin for capturing form data.

Built with Python and Flask on the backend and Materialize on the frontend.

## Features include:

* API to capture, store, and retrieve form data using Google App Engine and the Cloud Datastore
* Segment data into namespaces to accomodate for multiple data sources
* Export captured data as a CSV file
* Email Notification Service (Disabled by default. Can be enabled in config)
* API key and field validation
* Google Charts to show submissions by namespace to the dashboard 

## Changelog

### 0.1

* Forked from [Thousandblurbs](https://github.com/cpearson3/thousandblurbs) Project.
