# What is this?

tinyBundle is a bundler which compresses multiple python files into a single file!

This is similar to [pyz](https://github.com/BTOdell/pyz) and [zipfile](https://docs.python.org/3/library/zipapp.html) but doesn't require its own file type, hence it acts more like JavaScript's [rollup](https://rollupjs.org/).

# How do I install the project?

You can either click the 'Use this template' button in Github or using git you can perform a git clone

    git clone https://github.com/jakewdr/tinyBundle

# How do I build a bundle?

To build a bundle create a .py file and then import tinyBundle:

    import tinyBundle

Then you can build a bundle in the format:

    tinyBundle.bundle(listOfPythonFiles,outputPath,levelOfCompression)

# Example project

I've made a simple project which checks a image's file size here to give an example of what tinybundle can do, you can that [here](https://github.com/jakewdr/imageFileSizeChecker).

# Upcoming features

 - The ability to bundle other file types (like [webpack](https://webpack.js.org/) can).
 - The ability to bundle dependencies in the bundle.
 - A cli version?
 - Automatic requriments.txt creation
