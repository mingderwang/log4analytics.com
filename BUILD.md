bundle exec Jekyll b
cd _site
s3cmd sync . s3://log4analytics.com
s3cmd sync . s3://www.log4analytics.com
on aws, select all files and make public
