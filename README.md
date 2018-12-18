# Vidooly_Assignment_solution_comment-analysis
Use nlp to find comments similar to subtitles in youtube.

<h3>File details</h3><br>
comment_subtitle_similarity.ipynb : jupyter notebook for finding similar subtitles.<br>
subtitle.txt : subtitles of video.<br>
comments.txt : comments of video.<br>
downloader.py : code to download comments of video without using API.<br>

<h3>Steps performed</h3>:
<h4>1.Downloading Subtitles and Comments </h4>:<br> 

Youtube video link : https://www.youtube.com/watch?v=l1ZawWcya0Q<br>
Video name :  Ellen Looks Back at When Things Didn't Go As Planned<br>
Subtitles File : Subtitles.txt<br>
Comments file : comments .txt<br>

To download subtitles :<br>
>>>pip install youtube-dl<br>
>>>youtube-dl --all-subs --skip-download https://www.youtube.com/watch?v=l1ZawWcya0Q (video link)<br>

To download comments : <br>
>>>python downloader.py -y l1ZawWcya0Q -o subtitles.txt<br>
l1ZawWcya0Q = 'video id'<br>
subtitles.txt = file in which you want to save output to.<br>

<h4>2.Preprocessing subtitles and comments.</h4><br>
<h4>3.Word2vec embedding of subtitles and comments.</h4><br>
<h4>4.Matrix of euclidean distance beteen each subtitle and comment embedding.</h4><br>
<h4>5.Select least distance subtitles.</h4><br>
 
