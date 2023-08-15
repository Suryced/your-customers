node {
	stage ('Checkout') {
		git url: 'https://github.com/Suryced/your-customers.git'
	}
	stage ('Gradle build') {
		bat 'gradle build -x test'
	}
}
