<div style="margin-bottom: 1%; padding-bottom: 2%;">
	<img align="right" width="100px" src="https://dx29.ai/assets/img/logo-Dx29.png">
</div>

Dx29 Pipelines Only deployment tasks
==============================================================================================================================================
### **Overview**

It will be the same as the [deployment all pipeline](https://github.com/foundation29org/Dx29.Pipelines_all) but only with the deploy stages. In this case only the selected images will be accessed with the input parameter tag/version and deployed to the cluster. The pipelines can be found in a container registry, yet compiled, build and tested. This pipeline will also not be executed automatically but must be launched manually.

For version control there is a variables yaml file with the tags of all images that the pipeline deploy on the environment.

It is used in the [Dx29 application](https://dx29.ai/) and therefore how to use and integrate it is described in the [Dx29 architecture guide](https://dx29-v2.readthedocs.io/en/latest/index.html).

<p>&nbsp;</p>

### **Getting Started**

####  1. Configuration: Pre-requisites

This project doesn’t need any dependency or secret.

You need an [Azure Pipelines](https://azure.microsoft.com/en-gb/services/devops/pipelines/) environment to run it. 

<p>&nbsp;</p>

####  2. Download and installation

Download the repository code with `git clone` or use download button.
You can use any text editor with this project.

You must work on a repository on Github and have it associated with this project and Azure Pipelines to run it.

You have to modify the "sample" projects with the real values of the environment where you want to automate the build and deploy tasks: AKS, container registry, etc.

<p>&nbsp;</p>

### **Contribute**

Please refer to each project's style and contribution guidelines for submitting patches and additions. 

In general, we follow the "fork-and-pull" Git workflow.

>1. Fork the repo on GitHub
>2. Clone the project to your own machine
>3. Commit changes to your own branch
>4. Push your work back up to your fork
>5. Submit a Pull request so that we can review your changes

The project is licenced under the **(TODO: LICENCE & LINK & Brief explanation)**

<p>&nbsp;</p>
<p>&nbsp;</p>

<div style="border-top: 1px solid !important;
	padding-top: 1% !important;
    padding-right: 1% !important;
    padding-bottom: 0.1% !important;">
	<div align="right">
		<img width="150px" src="https://dx29.ai/assets/img/logo-foundation-twentynine-footer.png">
	</div>
	<div align="right" style="padding-top: 0.5% !important">
		<p align="right">	
			Copyright © 2020
			<a style="color:#009DA0" href="https://www.foundation29.org/" target="_blank"> Foundation29</a>
		</p>
	</div>
<div>