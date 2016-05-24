#web: jekyll serve --detach --port $PORT
web: jekyll build && bundle exec puma -t 8:32 -w 3 -p $PORT
