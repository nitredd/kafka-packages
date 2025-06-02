# kafka-packages

I packaged Kafka into DEB (for Ubuntu and Debian) & RPM packages (for RedHat Linux and its derivatives) that reduce the effort of setting up Kafka to a "yum install -y kafka<version>.rpm" or an "apt install -y ./kafka<version>.deb". Go to:
[https://www.pockettheories.com/ref_kafka.html](https://www.pockettheories.com/ref_kafka.html)

These packages have OpenJDK 21 as a dependency (yum/apt will auto-install the JDK) and the server is configured to use kRAFT (instead of ZooKeeper, which is deprecated from Kafka 4).
