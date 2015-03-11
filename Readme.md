It's 2015, You can code on Github, the editor is good enough, has everything you want for an editor, you need a guard / gulp plugin that lets you keep a github repo in sync, or do very long edits :) 
the full screen option is very cool, especially if you are prototyping and you actually don't need to switch file.

Ooooor! You need an app that has an editor and uses git/github  

```ruby

require 'profligacy'
# TODO: Take a look at github.com/makevoid/eptitheotherthingiwrote_with_profligacy (sorry, broken link) or better: github.com/makevoid/donacoin


## current state of ruby (from a js point of view)

# ruby is a functional language

class Actions
  def self.start
    # do stuff
  end
end

l = lambda

start = l{ |env| puts "env: #{env}"  }
start = -> { |env| } #... 

start.call
# start[]  # mmh 
# start.() # this is the best I think


### back to profligacy and stuff
```

```md
### Readme.md

# deltatime
### JRuby Profligacy app

## Ideas for the basic app:

Fan (spread) donations - time based
- BTC addresses
- level 1
  - onename
  - keybase
    - twitter
    - github username 
- telegram accounts


## Dreams (given the fact I'm now working full time and I can't hack all day on this):
## main actions of the ideal bombammano app!!

- wallet (web, similar to rushwallet)
- donations
- accounts
-- keybase
-- onename
-- twitter
-- facebook
-- telegram
-- NFC
-- channels
--- changetip
--- telegram
--- wallet_link_Bot


### Prerequisites

jruby+jre: <jruby.org/downloads>

### Install

    gem i warbler profligacy mechanize ftools zip

use jgem if gem is not available
 
### Run

    ruby bin/deltatime

### Develop

create jar

    rm deltatime.jar; warble

launch 

    java -jar .\deltatime.jar

see bin/deltatime, deltatime.rb, core.rb and ui.rb

enjoy!

notes: If you don't have java in your path on windows try referencing the java executable directly like:

    C:\jruby-1.7.3\jre\bin\java.exe -jar .\deltatime.jar
    
dev oneliners

    rm deltatime.jar; warble; java -jar deltatime.jar 

    rm deltatime.jar && warble && java -jar deltatime.jar 

    c:\jruby-1.7.3\bin\jruby.exe bin\eptidl

#######

```


### let your delta time be scandito by mbtcs

###  Flows of donations everywhere

###  Sets a pool of donations - notifies you when it's empty 

####  Java runs everything everywhere, it's easy to do a cross platform app
####  The web runs everywhere, it's easy to do a cross platform app :D


