# Rim-Siwar-AMQP-OSGI-Project
STEP 1 — Download and extract Karaf:
Download the last Stable Version from https://karaf.apache.org/download.html
Extract the Zip to location
STEP 2 — Create a new project in Eclipse:
Click on New Project and select Maven Project
Step 3: Write some Code:
Generated project will have an Activator class. This class acts as an entry point to this bundle. Its start and stop methods will be invoked whenever this bundle would be started and stopped respectively.
Step 4 : INSTALL THE BUNDLE TO LOCAL MAVEN REPOSITORY:
You can do run as → maven install. It will create the OSGI bundle of the project and add to your local maven repo.
STEP 5 INSTALL THE BUNDLE TO KARAF:Start Karaf in Debugging Mode by typing ./karaf debug in your KARAF/bin Folder.
Step 6 : Create new bundle: Repeat all the steps of bundle creation and create bundle2. The activator class of bundle2 will consume the service exposed by the bundle1
Step 7 : Start the bundles
------------------------
Then Use RabbitMQ 







