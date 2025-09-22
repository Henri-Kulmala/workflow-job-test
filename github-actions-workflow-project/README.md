# GitHub Actions Workflow Project

This project demonstrates a GitHub Actions workflow that consists of 100 jobs. Each job is designed to run on an `ubuntu-latest` environment and executes a simple echo command to indicate that the job has been triggered. 

## Purpose

The primary purpose of this workflow is to showcase how to create and manage multiple jobs within a single GitHub Actions workflow file. This can be useful for testing, automation, and continuous integration processes.

## Workflow Overview

- **Jobs**: The workflow contains 100 jobs, named from `job1` to `job100`.
- **Environment**: All jobs run on the `ubuntu-latest` environment.
- **Execution**: Each job executes a command that outputs a message indicating that the job has been triggered.

## Triggering the Workflow

The workflow is triggered by a `push` event to the repository. To initiate the workflow, simply push any changes to the repository. The workflow will automatically run, executing all 100 jobs sequentially.

## Viewing Results

After the workflow runs, you can view the results of each job in the "Actions" tab of your GitHub repository. Each job's output will indicate whether it was successfully triggered and completed.