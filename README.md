# testIng
// Print the container's standard output to golang's standard output
		container.SetPrintBuildOnStrOut()
		// Enables the use of the "cache:latest" image [optional].
		// To prevent an image from downloading the same dependency multiple times for each test, you can create an image 
		// named "cache:latest" and use this image as the basis for the test images.
		container.SetCacheEnable(true)
		// Determines the name of the image to be created during the test.
it is for research
