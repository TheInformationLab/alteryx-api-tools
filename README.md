# alteryx-api-tools

The Alteryx API Tools are designed to allow users to interact with the Alteryx Gallery, via the use of the Alteryx Subscription and Admin APIs, in order to perform tasks that they may otherwise do within the interface. These tools may allow users to automate certain tasks, for example, administrators might want to download all workflows as packaged .zip files so that there contents can be  programmatically reviewed for best practices.

The tools can be downloaded using the single Alteryx installer file (.yxi) stored in this github repository. Tools will be added to their own 'Alteryx API Tools' tool palette within your Alteryx Designer instance.

All tools have been designed to allow users to specify configuration parameters either dynamically from fields, or via fixed values entered in the configuration window.

## Subscription

The macro's in this section require...

#### List My Workflows - Beta

Allows you to get a list of workflows that exist within your private studio

#### Get Worfklow Questions - Beta

Allows you to fetch the questions that create the interface for a given analytic application

#### Download my Workflow - Beta

Download workflows from your private studio

#### Unzip and Read Packaged Workflow - Beta

From a list of packaged workflow paths, unzip and read the underlying XML into Alteryx

#### Execute Workflow - Beta

This macro allows users to execute a workflow or application stored on Alteryx Server

#### Gallery Conditional Runner - Beta

Provides a method for running multiple workflows in a given order, depending on the status (success or fail) of the previous job.

#### Get Workflow API Jobs - In Dev

Retrieves details of all jobs for a given workflow that were triggered via the Alteryx Subscription API

#### Publish Workflow - Beta

Allows you to publish a .yxzp to your private studio

Known Issues:

The 'Overwrite' functionality that this macro offers does not work, we have a support ticket open with Alteryx to understand where the issue lies.

#### Get Job Status - Beta

Fetches the status of a given job on Alteryx Server

## Admin

The macro's in this section require...

#### List Users - Beta

Retrieve a list of all users on the Alteryx Server

#### List Collections - Beta

Get a list of all collections on the Alteryx Server

#### List Schedules - Beta

Create a list of all schedules on the Alteryx Server

#### List Workflows - Beta

Get a list of all workflows on the Alteryx Server

#### Get Latest Job - Beta

Get the latest job for a given workflow or workflows

#### List Future Jobs - In Dev

Create a forecast of all future jobs that are expected to run

#### List Insights - Beta

Get a list of all insights on the Alteryx Server

#### List Subscriptions - Beta

Retrieve a list of all private studios on the Alteryx Server

#### List Data Connections - Testing

Retrieve a list of all data connections on the Alteryx Server

#### Download Workflow - Testing

Download any workflow on Alteryx Server
