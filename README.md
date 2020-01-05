**!!New!!** <br />
SDK to detect and recognize MRZ/MRTD released at https://github.com/DoubangoTelecom/ultimateMRZ-SDK <br />
If you're looking for information on how to [parse](https://www.doubango.org/SDKs/mrz/docs/MRZ_parser.html) or [validate](https://www.doubango.org/SDKs/mrz/docs/Data_validation.html) MRZ data check [here](https://www.doubango.org/SDKs/mrz/docs/MRZ_parser.html) and [here](https://www.doubango.org/SDKs/mrz/docs/Data_validation.html).
<hr />

### The dataset ###

The dataset contains more than __#7 thousands__ images (__.tif__) with ground truth (__.gt.txt__) from Google image augmented with few synthetic data.

The dataset is ready to be used to train with Tesseract v4.

### The models ###

If you're lazy and don't want to train the model by yourself then, try the ones under __tessdata_best__ (*float-model*) or __tessdata_fast__ (*int-model*) folders.

### Testing the accuracy ###

You can check how accurate the MRZ model is at https://www.doubango.org/webapps/mrz/ <br /> <br />
You may also be interested in our **Magnetic ink character recognition (MICR E-13B & CMC-7)** implementation at https://github.com/DoubangoTelecom/tesseractMICR with online demo at https://www.doubango.org/webapps/micr/

### Getting help ###

To get help please check our [discussion group](https://groups.google.com/forum/#!forum/doubango-ai) or [twitter account](https://twitter.com/doubangotelecom?lang=en)
