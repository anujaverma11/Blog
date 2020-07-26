#### Using Environment Variables in ReactJS

In a ReactJS application defining and using environment variables is a little different implementation then usual. Follow the steps

1. Go to the root folder of the application and create a text file naming it ".env", this will give the following warning, which you should accept as, Click on " Use "." "

![.env Warning Image](/Images/envWarningImage.png)

2. Once the file is created, create the environment variables with prefix "REACT_APP" as shown in the example below:

![Defining Variables](/Images/defineVariables.png)


3. Define the keys so that they start from the prefix but has meaning to the name of which API and if it is a Client id or if it is a key.

4. Now, these environment variables can easily be assigned to other variables or print them to the screen etc. They are read-only to other Javascript files.

![Defining Variables](/Images/UsingVariables.png)



