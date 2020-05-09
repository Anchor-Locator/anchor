# anchor

The ground truth of two datasets: 

1. Empirical dataset; 2. Fan et al's dataset are included.

These two dataset files contain the ground truth, you are encouraged to try out your own locators with them. For apk files downloading/transmission, contact anchor-locator@gmail.com.

Essential Key-value pairs:

{

"exception": the exception type (Java class) thrown,

"msg": the message composed by Signaler,

"identifier": app package identifier,

"postURL": the url for the issue track (only Fan et al's dataset),

"fileName": the apk that crashed (contact anchor-locator.gmail.com for apk files or download from app repo),

"trace": stack trace,

"year": year of issue,

"crashLog": raw crash message,

"real": the real buggy method or buggy sub-category.

"category": detailed category,

"realCate": A (in stack trace) B (outside stack trace, in code) C (outside code),

"tool": testing tool used for getting this crash (only apply for empirical dataset).

}
