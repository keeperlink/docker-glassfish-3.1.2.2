Docker Glassfish-3.1.2.2
==================================

Usage
------

	docker run -d -p 4848:4848 -p 8080:8080 -p 8181:8181 -e GLASSFISH_PASS="password" --name glassfish keeperlink/glassfish-3.1.2.2

Memory limit, i.e. 3GB:

	docker run -d -m 3GB-p 4848:4848 -p 8080:8080 -p 8181:8181 -e GLASSFISH_PASS="password" --name glassfish keeperlink/glassfish-3.1.2.2