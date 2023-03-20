build-PullRequestStatsFunction:
	mvn clean package -Dpackaging=docker-native -Dmicronaut.runtime=lambda -Pgraalvm
	unzip ./target/function.zip
	cp func $(ARTIFACTS_DIR)
	cp bootstrap $(ARTIFACTS_DIR)