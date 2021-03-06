# ANCHOR-Locator: Ground Truth Datasets

The ground truth of two datasets: 

1. Empirical dataset; 2. [Fan et al](https://dl.acm.org/doi/pdf/10.1145/3180155.3180222)'s dataset are included.

These two dataset files contain the ground truth, you are encouraged to try out your own locators with them. For apk files (they are very large) downloading/transmission, contact anchor-locator@gmail.com.

Essential Key-value pairs:

{

"exception": the exception type (Java class) thrown,

"buggyApi": the (incorrectly used) framework API that is the root cause of the crash, 

"msg": the message composed by Signaler,

"identifier": app package identifier,

"postURL": the url for the issue track (only Fan et al's dataset),

"fileName": the apk that crashed (contact anchor-locator.gmail.com for apk files or download from app repo),

"trace": stack trace,

"year": year of issue (only Fan et al's dataset),

"crashLog": raw crash message,

"real": the real buggy method or buggy sub-category.

"category": detailed category,

"realCate": A (in stack trace) B (outside stack trace, in code) C (outside code),

"tool": testing tool used for getting this crash (only apply for empirical dataset).

}
