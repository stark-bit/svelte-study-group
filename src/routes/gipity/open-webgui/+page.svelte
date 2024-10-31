<h2>Open-WebGUI</h2>
<a target="_blank" href="https://github.com/open-webui/open-webui"
	><p>https://github.com/open-webui/open-webui</p></a
>

<h3>1. Docker</h3>
<pre>docker run -d -p 3013:8080 --add-host=host.docker.internal:host-gateway -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main</pre>
<p>
	<strong>-d</strong>: Runs the container in detached mode, allowing it to run in the background.
</p>
<p>
	<strong>-p 3013:8080:</strong> Maps port 8080 of the container to port 3013 on the host, enabling access
	to the container's service through localhost:3013.
</p>
<p>
	<strong>--add-host=host.docker.internal:host-gateway:</strong> Adds an entry to the container's /etc/hosts
	file, mapping host.docker.internal to the host's gateway IP, allowing the container to access services
	running on the host.
</p>
<strong>-v open-webui:/app/backend/data:</strong> Mounts the Docker volume open-webui to the
container's /app/backend/data directory, persisting data across container restarts.
<p>
	<strong>--name open-webui:</strong> Names the container open-webui, which makes it easier to manage
	and reference.
</p>
<p>
	<strong>--restart always:</strong> Ensures the container restarts automatically if it stops, useful
	for maintaining uptime.
</p>
<p>
	<strong>ghcr.io/open-webui/open-webui:main:</strong> Specifies the image to use for the container,
	including the repository and tag (in this case, main).
</p>

<h3>2. Confirm docker container is up and running</h3>
<pre>docker container ls</pre>

<h3>3. Open localhost:3013 and explore</h3>

<ul>
	<li>Models</li>
	<li>Workspace</li>
	<li>Inputs Files & websites</li>
	<li>Admin Panel</li>
	<li>Admin Panel > Settings > Connections</li>
</ul>

<a class="block text-right text-2xl font-bold underline" href="/gipity/models"
	>Next, models ->
</a>
