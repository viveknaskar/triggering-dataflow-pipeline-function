# triggering-dataflow-pipeline-function

## About Google Cloud Function
Google Cloud Functions is a serverless execution environment for building and connecting cloud services. With Cloud Functions, you write simple, single-purpose functions that are attached to events emitted from your cloud infrastructure and services. Your function is triggered when an event being watched is fired. Your code executes in a fully managed environment. There is no need to provision any infrastructure or worry about managing any servers.

## What does it do here?
This cloud function is created to trigger cloud-dataflow pipeline when a file is uploaded into a cloud storage bucket. The function has been written in Node.js while the dataflow is worked on Java.

## Cloud Dataflow pipeline code
https://github.com/viveknaskar/google-dataflow-redis-example 

## How does a google cloud function trigger work?
Though in this code I have used nodejs as my main runtime language but just to get the gist of it, below link can clear a lot.

https://thedeveloperstory.com/2020/07/23/triggering-cloud-storage-with-cloud-functions-in-java/







