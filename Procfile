web: java $JAVA_OPTS -jar target/*.war --spring.profiles.active=prod,native,heroku --server.port=$PORT --spring.security.user.password=${SIMLIFE_PASSWORD:-"password"} --eureka.password=${SIMLIFE_PASSWORD:-"password"}