# content_gen

Generate HTML and sitemap.xml for ruu.lv news, videos and AMP using these templates and 
https://github.com/Janis-Rullis-IT/shell-scripts/blob/master/albums-for-web.sh

## Preparation before using `albums-for-web.sh`

```shell
sudo ln -s ~/Desktop/www/content_gen/news.header.tpl.html /usr/local/bin/news.header.tpl.html
sudo ln -s ~/Desktop/www/content_gen/news.header.tpl.xml /usr/local/bin/news.header.tpl.xml
sudo ln -s ~/Desktop/www/content_gen/news.footer.tpl.html /usr/local/bin/news.footer.tpl.html
sudo ln -s ~/Desktop/www/content_gen/news.footer.tpl.xml /usr/local/bin/news.footer.tpl.xml

sudo ln -s ~/Desktop/www/content_gen/img.tpl.html /usr/local/bin/img.tpl.html
sudo ln -s ~/Desktop/www/content_gen/img.tpl.xml /usr/local/bin/img.tpl.xml

sudo ln -s ~/Desktop/www/content_gen/video.amp.tpl.html /usr/local/bin/video.amp.tpl.html
sudo ln -s ~/Desktop/www/content_gen/video.tpl.html /usr/local/bin/video.tpl.html
sudo ln -s ~/Desktop/www/content_gen/video.tpl.xml /usr/local/bin/video.tpl.xml
```