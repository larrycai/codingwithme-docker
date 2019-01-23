# codingwithme-docker

some codes in CodingWithMe : Docker

* slides online: http://larrycai.github.io/codingwithme-docker/
* slides@slideshare: https://www.slideshare.net/larrycai/learn-docker-in-90-minutes (it cannot be updated since 2017.10 due to silly slideshare)

# preparation in playground

https://labs.play-with-docker.com is recommended to use
    
# slides

try to use markdown slides [remark](https://github.com/gnab/remark)

## browse locally

Just open the local `index.html`

## generate pdf

     docker run --rm --net=host -v `pwd`:/slides \
        astefanutti/decktape http://larrycai.gitlab.io/codingwithme-docker slides.pdf

# Errata



