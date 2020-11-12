# Setup Process

* Using Docker container image with UBI 8.2 and microdnf
* Install yum
```
sudo microdnf install yum
```

* Install Ruby packages
```
sudo yum install ruby ruby-devel 
```

* Install development tools software package group
```
sudo yum groupinstall "Development Tools"
```

* Install Jekyll Ruby gem
```
sudo gem install jekyll bundler
```

* Edit Gemfile and add the following line
```
gem "jekyll"
```

* Initialize bundler
```
bundle init
```