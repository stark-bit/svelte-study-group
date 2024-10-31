<h1>Models</h1>
<a target="_blank" href="https://huggingface.co/models"><h2>🤗 HuggingFace.co/models</h2></a>
<h2>Model Types</h2>
<ul>
	<li>Multimodal</li>
	<li>Computer Vision</li>
	<li>Natural Language Processing</li>
	<li>Audio</li>
	<li>Tabluar</li>
	<li>Reinforcment Learning</li>
</ul>

<h2>Parameters</h2>
<h3>
	Size does matter, but it's <a
		target="_blank"
		href="https://notebooklm.google.com/notebook/e6982cd5-30c5-4dd2-8fad-3aeb7624a4bd/audio"
		>debatable</a
	>
	based on this paper - <a target="_blank" href="https://arxiv.org/pdf/2410.05229">paper</a>
</h3>
<ul>
	<li><strong>GPT-4</strong> rumored to have 170 trillion</li>
	<li><strong>Bard</strong> 1.6 trillion</li>
	<h4>Open sourced*</h4>
	<li>Llama 3.1 1B - 420B</li>
	<h4>Sweet spot</h4>
	<li>13B - 32B</li>
</ul>

<h2>Quantisation</h2>
<ul>
	<li>It's a compression technique</li>
	<h3>
		Why e.g. <a target="_blank" href="https://huggingface.co/meta-llama/Llama-3.1-8B/tree/main"
			>Llama-3.1.8B</a
		>
	</h3>
	<li>8B parameters ~ 15GB of memory needed</li>
	<li>
		<a
			target="_blank"
			href="https://www.reddit.com/r/LocalLLaMA/comments/178el7j/comment/k50vs5v/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button"
			>Safetensor vs GGUF vs GGML vs Other</a
		>
	</li>
	<li>
		<a href="https://huggingface.co/bartowski/Meta-Llama-3.1-8B-Instruct-GGUF">Q2 vs Q5 vs f32</a>
	</li>
</ul>

<h2>
	<a href="https://www.gpu-mart.com/blog/custom-llm-models-with-ollama-modelfile" target="_blank">
		Modelfiles
	</a>
</h2>
<pre>ollama show --modelfile llama3.2:1B</pre>
or send it to txt file
<pre>ollama show --modelfile llama3.2:1B > ~/Downloads/llama3.2.txt </pre>

<h2>How small can you go?</h2>
<ul><li><a href="https://apps.apple.com/us/app/pocketpal-ai/id6502579498">Apple PocketPal</a>
  </li><li><a href="https://play.google.com/store/apps/details?id=com.pocketpalai&hl=en" target="_blank">Android PocketPal</a></li></ul>

