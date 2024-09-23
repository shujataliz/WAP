## Docker Deployment

1. Build the project:
   ```
   mvn clean package
   ```

2. Build the Docker image:
   ```
   docker compose build
   ```

3. Run the container:
   ```
   docker compose up
   ```

4. Access the application at `http://localhost:8080/ParsingJSON/index.jsp`

## Notes

This lab was simple and took about an hour to finish. 
It showed how JSP makes creating dynamic web content easier 
compared to putting all the logic directly in servlets. 
Knowing how JSP works is helpful for future web development projects.

