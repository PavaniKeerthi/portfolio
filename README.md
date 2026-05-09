<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pavani Keerthi | Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background: #0f172a;
      color: white;
      scroll-behavior: smooth;
    }

    .glass {
      background: rgba(255,255,255,0.05);
      backdrop-filter: blur(12px);
      border: 1px solid rgba(255,255,255,0.08);
    }

    .gradient-text {
      background: linear-gradient(to right, #38bdf8, #8b5cf6);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    .card:hover {
      transform: translateY(-8px);
      transition: 0.3s ease;
    }
  </style>
</head>
<body>

  <!-- Hero Section -->
  <section class="min-h-screen flex flex-col justify-center items-center text-center px-6">
    <h1 class="text-5xl md:text-7xl font-bold mb-6">
      Hi, I'm <span class="gradient-text">Pavani Keerthi</span>
    </h1>

    <p class="text-xl md:text-2xl text-gray-300 max-w-3xl">
      🏆 National Runner-Up @ Amaravati Quantum Valley Hackathon 2025 | 
      GenAI Intern @ CloudKarya | Multi-Agent AI & Full-Stack Developer 🚀
    </p>

    <div class="mt-10 flex gap-4 flex-wrap justify-center">
      <a href="https://github.com/PavaniKeerthi" target="_blank"
        class="px-6 py-3 rounded-2xl bg-cyan-500 hover:bg-cyan-400 text-black font-semibold">
        GitHub
      </a>

      <a href="#projects"
        class="px-6 py-3 rounded-2xl border border-white hover:bg-white hover:text-black transition">
        View Projects
      </a>
    </div>
  </section>

  <!-- About -->
  <section class="py-20 px-6 max-w-6xl mx-auto">
    <h2 class="text-4xl font-bold mb-10 gradient-text">About Me</h2>

    <div class="glass rounded-3xl p-8 text-gray-300 text-lg leading-8">
      I am an AI Engineer and Full-Stack Developer passionate about building intelligent automation systems, multi-agent AI applications, and scalable web platforms.
      
      I specialize in LangChain, CrewAI, AutoGen, LangGraph, Next.js, and AI workflow automation.

      I love participating in hackathons and solving real-world problems through AI-driven innovation.
    </div>
  </section>

  <!-- Skills -->
  <section class="py-20 px-6 bg-slate-900">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-4xl font-bold mb-12 gradient-text">Tech Stack</h2>

      <div class="grid md:grid-cols-4 gap-6">
        <div class="glass rounded-3xl p-6">
          <h3 class="text-2xl font-semibold mb-4">🤖 AI</h3>
          <ul class="space-y-2 text-gray-300">
            <li>LangChain</li>
            <li>CrewAI</li>
            <li>AutoGen</li>
            <li>LangGraph</li>
          </ul>
        </div>

        <div class="glass rounded-3xl p-6">
          <h3 class="text-2xl font-semibold mb-4">💻 Frontend</h3>
          <ul class="space-y-2 text-gray-300">
            <li>Next.js</li>
            <li>React.js</li>
            <li>TypeScript</li>
            <li>Tailwind CSS</li>
          </ul>
        </div>

        <div class="glass rounded-3xl p-6">
          <h3 class="text-2xl font-semibold mb-4">⚡ Backend</h3>
          <ul class="space-y-2 text-gray-300">
            <li>FastAPI</li>
            <li>Node.js</li>
            <li>PostgreSQL</li>
            <li>Supabase</li>
          </ul>
        </div>

        <div class="glass rounded-3xl p-6">
          <h3 class="text-2xl font-semibold mb-4">🔗 APIs</h3>
          <ul class="space-y-2 text-gray-300">
            <li>Amadeus API</li>
            <li>Gmail API</li>
            <li>Google Calendar API</li>
            <li>Zapier</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects" class="py-20 px-6 max-w-6xl mx-auto">
    <h2 class="text-4xl font-bold mb-12 gradient-text">Featured Projects</h2>

    <div class="grid md:grid-cols-2 gap-8">

      <div class="glass rounded-3xl p-8 card">
        <h3 class="text-2xl font-bold mb-4">🤖 Agentic AI Workflow Automation Platform</h3>

        <p class="text-gray-300 leading-7">
          Built a scalable Multi-Agent Automation Platform using LangChain, CrewAI, AutoGen, and LangGraph for orchestrating intelligent AI workflows.
        </p>

        <ul class="mt-5 space-y-2 text-gray-400">
          <li>✅ 200+ monthly automated executions</li>
          <li>✅ 40% faster response time</li>
          <li>✅ Integrated Amadeus, Gmail & Google Calendar APIs</li>
        </ul>
      </div>

      <div class="glass rounded-3xl p-8 card">
        <h3 class="text-2xl font-bold mb-4">🌍 Click2Change</h3>

        <p class="text-gray-300 leading-7">
          A civic-tech issue reporting platform enabling users to upload geo-tagged issues and notify authorities in real time.
        </p>

        <ul class="mt-5 space-y-2 text-gray-400">
          <li>✅ Role-based dashboards</li>
          <li>✅ Real-time issue tracking</li>
          <li>✅ Analytics & workflow management</li>
        </ul>
      </div>

      <div class="glass rounded-3xl p-8 card">
        <h3 class="text-2xl font-bold mb-4">✈️ AI Travel Planner Assistant</h3>

        <p class="text-gray-300 leading-7">
          AI-powered travel assistant for flights, hotels, scheduling, itinerary generation, and workflow automation.
        </p>
      </div>

      <div class="glass rounded-3xl p-8 card">
        <h3 class="text-2xl font-bold mb-4">⚛️ Quantum Simulation Solution</h3>

        <p class="text-gray-300 leading-7">
          Developed a quantum simulation solution for molecular systems (H2 & LiH) during Amaravati Quantum Valley Hackathon 2025.
        </p>
      </div>

    </div>
  </section>

  <!-- Achievements -->
  <section class="py-20 px-6 bg-slate-900">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-4xl font-bold mb-12 gradient-text">Achievements</h2>

      <div class="space-y-6">

        <div class="glass rounded-3xl p-6">
          <h3 class="text-2xl font-semibold">🏆 Amaravati Quantum Valley Hackathon 2025</h3>
          <p class="text-gray-300 mt-3">
            National Runner-Up in Finals & 1st Place in Semi-Finals.
          </p>
        </div>

        <div class="glass rounded-3xl p-6">
          <h3 class="text-2xl font-semibold">🥇 DecodeX 2025</h3>
          <p class="text-gray-300 mt-3">
            Secured 1st Place in the “Create Your Own Design” competition.
          </p>
        </div>

        <div class="glass rounded-3xl p-6">
          <h3 class="text-2xl font-semibold">🥈 DTI Expo – IIC GVPCE(A)</h3>
          <p class="text-gray-300 mt-3">
            Secured 2nd Place for presenting Click2Change.
          </p>
        </div>

      </div>
    </div>
  </section>

  <!-- Contact -->
  <section class="py-20 px-6 text-center">
    <h2 class="text-4xl font-bold mb-8 gradient-text">Let's Connect</h2>

    <p class="text-gray-300 text-lg mb-8">
      Interested in collaborating on AI, Automation, or Full-Stack projects?
    </p>

    <div class="flex justify-center gap-4 flex-wrap">
      <a href="https://github.com/PavaniKeerthi" target="_blank"
        class="px-6 py-3 rounded-2xl bg-white text-black font-semibold hover:bg-gray-200">
        GitHub
      </a>

      <a href="#"
        class="px-6 py-3 rounded-2xl bg-cyan-500 text-black font-semibold hover:bg-cyan-400">
        LinkedIn
      </a>
    </div>
  </section>

</body>
</html>
