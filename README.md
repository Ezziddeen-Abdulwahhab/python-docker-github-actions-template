<h2>Description</h2>
<p>
A template for creating Python based projects that run inside Docker containers and have some GitHub actions configured.
</p>

<h2>How to run the project</h2>
<p>
To run this project as it is, simply clone it and run the following command with the Docker daemon running in the background:
</p>

<ul>
<li>docker-compose up</li>
</ul>

<h2>Customization</h2>
<p>
These are the main areas you need to modify in order to make good use of this template:
</p>

<ul>
<li>Add your Python code to the app directory</li>
<li>Change the Docker base image to the version of your requirements (eg. Python 2.7, 3.6, 3.9 etc.)</li>
<li>Add your Python production dependencies to requirements.txt</li>
<li>Add your Python development dependencies to requirements.dev.txt</li>
<li>Add GitHub actions as needed (eg. Run tests, run linting etc.)</li>
<li>Add the main command that launches your application to the Docker compose file</li>
<li>Add two secrets to the repository configuration (The values must be generated on DockerHub)</li>
<ul>
<li>DOCKERHUB_USER: A DockerHub valid username</li>
<li>DOCKERHUB_TOKEN: An access token for the DockerHub user</li>
</ul>
</ul>
