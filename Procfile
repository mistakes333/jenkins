# Only listen on http; disable ajp and https
# web: java -jar jenkins.war --httpPort=$PORT --ajp13Port=-1 --httpsPort=-1
web: java -jar jenkins.war --httpPort=$PORT --ajp13Port=-1
lts: rm Jenkins.war && wget https://get.jenkins.io/war-stable/latest/jenkins.war
