The two directories contain a spring boot project each. They are identical apart from the spring-boot version that is used.

To see how `StringUtils.stripAccents` behaves navigate to a project and run `mvn clean test`. The test will pass in 3.3.6
and will fail in 3.4.0. I also logged the result of each `stripAccent` call.