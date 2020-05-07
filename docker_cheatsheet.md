## Docker commands

### Build image:
(from the dir where there is dockerfile)

	docker build -t meetkrutik/spring-rest:3 .

### To run image:
	docker run -p 5000:5000 -t meetkrutik/spring-rest:3
	
### To push image 
-login first with: docker login 

-repo with same name must exist, so create that first (example: for following, create spring_rest repo first)

	docker push meetkrutik/spring_rest:1
	
