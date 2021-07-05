# Glossary
The following table lists the commonly used words while working with Jeeves.

<aside class="notice"> This is an evolving section of the document. Words can be added or deleted as Jeeves evolve. 
</aside>

| Word | Definition | See section(s) |
| ---- | ---------- | -------------- |
| **Alert Trigger** | The type of action that launches a Slack Alert in a Project channel. | [Integrate Slack Notifications to a Project Profile](#2-integrate-slack-notifications-to-a-project) |
| **API** | The acronym for Application Programming Interface. | [API Reference Documentation](#api-reference-documentation) |
| **AWS** | The acronym for Amazon Web Services. | [Version](#version) |
| | | [Run Agent](#run-agent) |
| **Bash Script** | A text file with an order of commands to run in a Terminal. | [Jobs](#jobs) |
| **Body** | The content of a POST API call. | [Dynamic Run Parameters](#dynamic-run-parameters) |
| **Config** | The Config section of the Run Parameters. Contains the testing variables for the Spot Instances. | [Run Parameters](#run-parameters) |
| | | [Config](#config) |
| **DJ** | The acronym for Dow Jones. | [Version](#version) |
| | | [Create a Project](#create-a-project) |
| **DJ Business Unit** | The Dow Jones Business Unit. An internal section of Dow Jones, such as The Wall Street Journal or Barron’s. | [Version](#version) |
| | | [Create a Project](#create-a-project) |
| **DJ Component** | The Dow Jones Component. An internal section of a DJ Business Unit, such as Shared Services or Data. | [Version](#version) |
| | | [Create a Project](#create-a-project) |
| **DJ Team** | The Dow Jones Team. An internal section of a DJ Component. DJ Teams focus on specific projects. | [Create a Project](#create-a-project) |
| **DJ VPN** | The Dow Jones Virtual Protected Network. Necessary to work with Jeeves and Dow Jones services and tools. | [Overview](#overview) |
| **EC2 Instance** | The acronym of Amazon Elastic Computing. Serves the computing services to run Test Cases in nonprod and stag environments. | [Run Agent](#run-agent) |
| **Engine** | The hardware and software behind an environment. Jeeves can use Local or AWS engines. | [Version](#version) |
| **Environment** | The state in which Jeeves runs. Jeeves can run in localhost, nonprod, and stag. | [Version](#version) |
| **Expected Status** | The HTTP status a request can receive. | [Expected Status](#expected-status) |
| **Fleet** | A group of Spot Instances that work together. | [Version](#version) |
| **Follow Redirect** | A web page configuration that allows web pages to redirect to a specified link. | [Config](#config) |
| **Header** | A variable that enables web clients and servers to pass information through a HTTP response or request. | [Headers](#headers) |
| | | [Header Parameters](#header-parameters) |
| **Health Check** | A tool to supervise the changes in requests results against expected results or previous results. | [Health Check](#health-checks) |
| | | [Test Case Insights](#test-case-insights) |
| **Home Page** | The principal page of a section. | [Home Page](#home-page) |
| | | [Project Home Page](#project-home-page) |
| | | [Test Case Home Page](#test-case-home-page) |
| **Host** | A server connected to the internet that offers services such as web pages. | [Dynamic Hosts](#dynamic-hosts) |
| | | [Run Agent](#run-agent) |
| **Job** | A task that groups Test Cases to run them sequentially. | [Jobs](#jobs) |
| **JSON** | The acronym for JavaScript Object Notation. A data-interchange file format. | [Run Parameters](#run-parameters) |
| **KO** | The indicator for failed requests. | [Charts and Indicators](#charts-and-indicators) |
| | | [Test Case Insights](#test-case-insights) |
| | | [Test Case Reports](#test-case-reports) |
| **Latest Report** | The report of the last Test Case run. | [Test Case Reports](#test-case-reports) |
| **Log** | A Terminal-like interface that lists the activities Jeeves does in real-time while running a Test Case or a Job. | [Test Case Logs](#test-case-logs) |
| | | [Jobs](#jobs) |
| **MDN Web Docs** | The acronym for Mozilla Developer Network Documentation Repository. A web page that contains information related to | [Dynamic Run Parameters](#dynamic-run-parameters) |
| **Mean** | The average of a sequence of results. It can be obtained by adding up results and dividing them by the total of results.| [Test Case Logs](#test-case-logs) |
| | | [Test Case Reports](#test-case-reports) |
| **Monitor** | The Jeeves section which enables users to check the progress of Test Cases running in the background. | [Monitor](#monitor) |
| **MS** | The acronym for microseconds, a time measure. | [Charts and Indicators](#charts-and-indicators) |
| | | [Test Case Insights](#test-case-insights) |
| | | [Test Case Reports](#test-case-reports) |
| **Notification Trigger** | The type of action that launches a Slack Notification in a Project channel. | [Integrate Slack Notifications to a Project Profile](#2-integrate-slack-notifications-to-a-project-profile) |
| **OK** | The indicator for successful requests. | [Charts and Indicators](#charts-and-indicators) |
| | | [Test Case Insights](#test-case-insights) |
| | | [Test Case Reports](#test-case-reports) |
| **Path** | The location of a resource in a web page folder structure. | [Dynamic Run Parameters](#dynamic-run-parameters) |
| | | [Path and Query Parameters](#path-and-query-parameters) |
| **Peer** | The Instance Spot in charge of running a Test Case. | [Run Agent](#run-agent) |
| | | [Config](#config) |
| | | [Test Case Logs](#test-case-logs) |
| **Percentile** | The score at or below which a given percentage falls. | [Charts and Indicators](#charts-and-indicators) |
| | | [Test Case Insights](#test-case-insights) |
| | | [Test Case Reports](#test-case-reports) |
| **Pool Status** | The status of tasks that have run from a group of tasks. | [Monitor](#monitor) |
| **Preset** | The prefabricated configuration of a Test Case. | [Create a Test Case](#create-a-test-case) |
| | | [Test Case Presets](#test-case-presets) |
| | | [Config](#config) |
| **Project** | The group of pages, team, or  to which the | [Projects](#projects) |
| **Query** | A parameter used to sort or search a specific item by subject or characteristic.  | [Dynamic Run Parameters](#dynamic-run-parameters) |
| | | [Path and Query Parameters](#path-and-query-parameters) |
| **Queue Status** | The status of tasks that are waiting to run from a group of tasks. | [Monitor](#monitor) |
| **Rampup** | The time a request takes to run. | [Config](#config) |
| **Report** | The presentation for the results obtained after a Test Case run. | [Test Case Logs](#test-case-logs) |
| | | [Test Case Reports](#test-case-reports) |
| **Repository** | The location of a web page code in GitHub. | [Create a Project](#create-a-project) |
| | | [Change a Project Detail](#change-a-project-detail) |
| **Response Time Higher Bound** | The highest time at which a request is allowed to receive a response. | [Charts and Indicators](#charts-and-indicators) |
| | | [Test Case Insights](#test-case-insights) |
| | |[Test Case Reports](#test-case-reports) |
| **Response Time Lower Bound** | The lowest time at which a request is allowed to receive a response. | [Charts and Indicators](#charts-and-indicators) |
| | | [Test Case Insights](#test-case-insights) |
| | | [Test Case Reports](#test-case-reports) |
| **RPS** | The acronym for Request Per Second. | [Config](#config) |
| **Run Agent** | The Amazon Spot Instance that runs the Test Case. | [Run Agent](#run-agent) |
| **Spot** | The Amazon Spot Instance that runs the Test Case. | [Version](#version) |
| | | [Run Agent](#run-agent) |
| **Standard Deviation** | The amount of variation or dispersion of a set of values. | [Charts and Indicators](#charts-and-indicators) |
| | | [Test Case Insights](#test-case-insights) |
| | | [Test Case Reports](#test-case-reports) |
| **Strategy** | The way a Test Case selects the data during a run. | [Config](#config) |
| **T** | The time. | [Charts and Indicators](#charts-and-indicators) |
| | | [Test Case Insights](#test-case-insights) |
| | | [Test Case Reports](#test-case-reports) |
| **Target Url** | The main URL for a Test Case. | [URL](#url) |
| | | [Dynamic Target URL](#dynamic-target-url) |
| **Test Case** | A simulation task that checks the availability and throughput of a web page or web application. | [Test Cases](#test-cases) |
| **URL** | The acronym for Uniform Resource Locator. | [URL](#url) |
| | | [Dynamic Target URL](#dynamic-target-url) |
| **Version** | The current state of Jeeves, labeled by a sequential number. | [Version](#version) |
| **VPC** | The acronym for Virtual Private Cloud. | [Version](#version) |
| **Warm Up URL** | The URL a Test Case uses to test connectivity to the Project Host, before starting a run. | [Run Agent](#run-agent) |
| **Web Availability** | The ability to use or access a web page service. | [Overview](#overview) |
| **Web Throughput** | The amount of transactions over time when using or accessing a web page service. | [Overview](#overview) |
| **Webhook** | A HTTP callback defined by the user, triggered by an event. Webhooks serve to launch a consequential activity derived from its trigger. | [Create a Slack Channel WebHook](#1-create-a-slack-channel-webhook) |




