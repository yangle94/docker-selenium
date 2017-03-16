# !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
# NOTE: DO *NOT* EDIT THIS FILE.  IT IS GENERATED.
# PLEASE UPDATE Dockerfile.txt INSTEAD OF THIS FILE
# !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
<<<<<<< HEAD
FROM angley/node-chrome:1.0
MAINTAINER Selenium <yangle@zs5s.com>
=======
FROM selenium/node-chrome:3.1.0-astatine
MAINTAINER Selenium <selenium-developers@googlegroups.com>
>>>>>>> 032b1873b5ddc758c2738c1fd3a16017d748024f

USER root

#====================================
# Scripts to run Selenium Standalone
#====================================
COPY entry_point.sh /opt/bin/entry_point.sh
RUN chmod +x /opt/bin/entry_point.sh

USER seluser

EXPOSE 4444
