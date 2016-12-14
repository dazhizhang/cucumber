# cucumber
cucumber rails
運行cucumber使用 rake features
会启动 bundle exec cucumber --profile default

在 Gemfile 中的 test 区域添加：

group :test do
  gem 'cucumber-rails', :require => false
end
然后执行 bundle install。

接下来执行 rails generate cucumber:install （可以先在后面加 --help 查看可用的选项）。

参考：

http://xhh.me/post/2013/03/10/acceptance-test-with-cucumber-in-rails#main

http://l404.blogspot.com/


http://www.w3ii.com/cucumber/cucumber_useful_resources.html
http://tauntaunslayer13.me/blog/2014/03/12/cucumberxiao-huang-gua-ye-mian-ji-zi-dong-hua-ce-shi-ru-men-jiao-cheng/
