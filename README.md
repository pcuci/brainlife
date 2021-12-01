
# Free cloud platform for secure neuroscience data analysis.

![brainlife.io](https://user-images.githubusercontent.com/2119795/93723350-7fa3d980-fb63-11ea-9272-e9fb133356a4.png)

## What is Brainlife?

Brainlife promotes engagement and education in reproducible neuroscience. We do this by providing an online platform where users can publish code (Apps), Data, and make it "alive" by integragrate various HPC and cloud computing resources to run those Apps. 

Brainlife also provide mechanisms to publish all research assets associated with a scientific project (data and analyses) embedded in a cloud computing environment and referenced by a single digital-object-identifier (DOI). The platform is unique because of its focus on supporting scientific reproducibility beyond open code and open data, by providing fundamental smart mechanisms for what we refer to as “Open Services.” 

## Brainlife Apps

Brainlife uses Apps to analyze data. Apps are small programs, small modules or compute units, that can process data individually or be made part of a larger series of steps in a full data analysis workflow. Brainlife Apps are meant to do small but meaningful steps in a longer analysis pipeline. Apps are modules and the brainlife.io platform. The platform allows users to develop, use, combine, and reuse Apps to build complex pipelines for customized brain data analyses. Most Apps indeed do only one thing, they process data in a specific way and are meant to perform a small set of operations and handle small sets of data; they do one thing, they do it well.

Apps can be developed and published on the Brainlife platform by anyone. App developers can be computational neuroscientists, cognitive neuroscientists, but also computer scientists or engineers. Apps are snippets of code implementing algorithms or analyses. By following a few easy steps developers can publish their code for brain data analysis on the Brainlife platform as an App. Publishing code as Apps allows scientists to use the code in combination with the data and computational resources available through Brainlife. Apps published on Brainlife can be used privately or shared publicly with the platform users community.

## Brainlife Datatypes

Brainlife Apps communicate via Brainlife “Datatypes.” A Datatype defines the expected list of filenames or the directory structure that an Apps can use as input or generate as output. The same Datatype is ideally used by multiple Apps, this allows Apps to communicate by their input and output data sets and reuse the data to generate more data derivatives, useful for other Apps. Datatypes, in addition to allowing the various Apps developed by independent developers to communicate on the brainlife.io platform, also allow Apps to be joined together to form a pipeline or workflows. The Brainlife Datatypes are maintained by individual developers participating in a specific Datatype, and discussed and maintained at https://github.com/brain-life/datatypes, conveniently using the full versioning and management features of github.com.

## Brainlife Clouds (Compute Resource)

The fundamental architecture of Brainlife allows orchestration of data and computing across mix systems of Clouds and high-performance computing clusters (HPC). We refer to both HCP and Clouds as Brainlife Clouds, this is not meant to be a technical definition but a simple way to communicate the fact that compute resources can be registered on the platform. Brainlife orchestration allows platform users and compute resource providers to register a compute resource and make it available publicly to the full Brainlife users community or privately to a subset of users. Brainlife has smart mechanisms that allow Apps to run on different resources, privately or publicly. Whereas with the more traditional approach of running an entire workflow on a single resource or on a small set of resources, does not allow optimization of the workflow (or parts of it) on every resources. Brainlife approach instead allows App Developers to identify the best resources available for the App the develop. This mechanisms is provided by scoring the compute resources available on the Brainlife platform depending on how well they work with the App being develop. Brainlife automatically keeps track of statistics, such as success rate a time to compute so that the users can quickly glance how often and efficiently each App has been processing data and make an informed choice when choosing among similar Apps to process a dataset.

## Brainlife Viz (Cloud Visualization)

Brainlife provides mechanisms to perform data visualization on the Cloud side – without moving data to the web-browser of the users in location distal from the data. Data visualization is meant to provide users with an agile way to get feedback on the quality of the results generated by Apps and pipelines. Visualization is implemented with smart cloud-side methods, so that data are not moved from the Cloud to the users computer. This increases security and improves data management. Brainlife Viz allows running major software for data visualization familiar to the neuroscience community (e.g., FreeView, FSLview, MRview). We also developed an innovative method to run GPU rendered visualization on the cloud via Docker and VNC. Brainlife Viz as well as the Apps can be openly and conveniently contributed by developers to the Brainlife platform. 


# Funding

This research was supported by NSF OAC-1916518, NSF IIS-1912270, NSF, IIS-1636893, NSF BCS-1734853, NIH 1R01EB029272-01, a Microsoft Research Award, A Microsoft Investigator Fellowship.

