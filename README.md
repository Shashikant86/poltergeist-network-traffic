#Poltergeist 

Poltergeist is a headess capybara driver based on PhantomJS. This project is a demonstration of Poltergiest driver in your project. 



##Pre-requisite 

in order to use Poltergeist, You must have PhatomJs installed. It's very easy to install. 

On Mac : Use HomeBrew. Please note MacPort installtion is not recommended 

              $ brew install phantomjs

On Linux : Download PhantomJS from the official site and add binary to your PATH [ Note 64 bit and 32 bit ]
              
                $ wget https://phantomjs.googlecode.com/files/phantomjs-1.9.0-linux-x86_64.tar.bz2

And create symlink  phantomjs/bin to your /usr/local/bin and /usr/bin

On Ubuntu, you can use basic phantomjs package like this 

                $ sudo apt-get install phantomjs
              
              

#Usage 

Note: You need to have Ruby 1.9.3 and Capybara 2.1.0 for the latest Poltergeist version. Please make sure you have Ruby 1.9.3 and Capybara 2.1.0 for this Demo.

### Clone the repository 


        $ git clone https://github.com/Shashikant86/poltergeist-network-traffic.git
        $ cd poltergeist-network-traffic
        
        
You may widh to do bundle update before running cucumber 

        $ bundle update 

Now run cucumber to see all the scenario passes using Poltergiest. 

        $ cucumber  2> >(grep -v CoreText 1>&2)
