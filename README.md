# alteryx-api-tools

The Alteryx API Tools are designed to allow users to interact with the Alteryx Gallery, via the use of the Alteryx Subscription and Admin APIs, in order to perform tasks that they may otherwise do within the interface. These tools may allow users to automate certain tasks, for example, administrators might want to download all workflows as packaged .zip files so that there contents can be  programmatically reviewed for best practices.

The tools can be downloaded using the single Alteryx installer file (.yxi) stored in this github repository. Tools will be added to their own 'Alteryx API Tools' tool pallette within your Alteryx Designer instance.

## Subscription

The macro's in this section require...

### List My Workflows

Allows you to get a list of workflows that exist within your private studio

### Get Worfklow Questions

Allows you to fetch the questions that create the interface for a given analytic application

### Get Workflow Jobs

Fetches jobs for a given workflow

### Download Workflow

Download a workflow from your private studio

### Execute Workflow

### Gallery Conditional Runner

Provides a method for running multiple workflows in a given order, depending on the status (success or fail) of the job.

### Publish Workflow

Allows you to publish a .yxzp to your private studio

### Get Job Status

Fetches the status of a given job

## Admin

The macro's in this section require...

### List Users

Retrieve a list of all users on the Alteryx Server

### List Collections

Get a list of all collections on the Alteryx Server

### List Schedules

Create a list of all schedules on the Alteryx Server

### List Workflows

Get a list of all workflows on the Alteryx Server

### Get Latest Job

Get the latest job for a given workflow or workflows

### List Future Jobs

Create a forecast of all future jobs that are expected to run

### List Insights

Get a list of all insights on the Alteryx Server

### List Subscriptions

Retrieve a list of all private studios on the Alteryx Server







