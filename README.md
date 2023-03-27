# openhsi-capture-and-processing
The jupyter notebooks used to capture, process, and classify data captured from an OpenHSI camera for my honours project at Flinders University.

The code contained here is not managed or kept up to date, it is a snapshot of what I used to complete my honours project.

`capture-datacube` will allow the user to capture and preview a datacube using an OpenHSI camera, note that different versions of this camera have different sensors, my version uses the Lucid Vision Labs [Pheonix 1.6MP](https://thinklucid.com/product/phoenix-16-mp-imx273/) model which has a specific SDK that is used to interact with it, including a custom python library.

`processing-radiative-transfer-calibration` and `proccess-to-reflectance` both contain code to assist in post-processing the captured datacubes into radiance and then reflectance. Note that this was a fairly manual procedure as my computer could not keep up with the memory requirements.

The remainder of the notebooks are fairly self explanatory. My work focussed on capturing images, extracting (where I could) ground truths from them, and classifying them. I was also interested in manual classification with matched filtering and the extraction of spectra.
