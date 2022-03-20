# fseek-
&lt;?php $file = fopen("test.txt","r"); // Read first line echo fgets($file); // Move back to beginning of file fseek($file,0); fclose($file); ?>
