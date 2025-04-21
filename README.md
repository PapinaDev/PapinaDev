import React from 'react';

const Profile = () => {
  return (
    <div className="container mx-auto p-4">
      <h1 className="text-center text-4xl font-bold">Hi there, I'm Papina 👋</h1>
      <h3 className="text-center text-2xl my-2">🚀 Computer Science Student & Full-Stack Developer from Algeria</h3>

      <div className="text-center my-4">
        <a href="https://discord.com/users/965714627918966845" target="blank">
          <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="Discord" className="inline-block h-8 w-10" />
        </a>
      </div>

      <hr className="my-6" />

      <section>
        <h2 className="text-xl font-semibold">👨‍💻 About Me</h2>
        <ul className="list-disc pl-6">
          <li>🌱 Currently diving deep into <strong>Networking, Cloud Computing, and Cybersecurity</strong></li>
          <li>🛠️ Building projects with <strong>Vue, Node.js, and modern web technologies</strong></li>
          <li>🔭 Interested in <strong>system architecture, server management, and open-source</strong></li>
          <li>💬 Ask me about <strong>web development, server configuration, or tech in general</strong></li>
          <li>⚡ Fun fact: I can probably fix your WiFi issues</li>
        </ul>
      </section>

      <hr className="my-6" />

      <section>
        <h2 className="text-xl font-semibold">🛠️ Tech Stack</h2>
        <div className="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 gap-4">
          {/* Frontend */}
          <div className="flex justify-center">
            <img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D" alt="Vue.js" />
          </div>
          <div className="flex justify-center">
            <img src="https://img.shields.io/badge/Nuxt-002E3B?style=for-the-badge&logo=nuxtdotjs&logoColor=#00DC82" alt="Nuxt.js" />
          </div>
          {/* Backend */}
          <div className="flex justify-center">
            <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
          </div>
          {/* Add other technologies here */}
        </div>
      </section>

      <hr className="my-6" />

      <section>
        <h2 className="text-xl font-semibold">📈 GitHub Stats</h2>
        <div className="text-center">
          <img src="https://github-readme-stats.vercel.app/api?username=papina&show_icons=true&theme=radical" alt="Papina's GitHub stats" className="mx-auto" />
          <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=papina&layout=compact&theme=radical" alt="Top Languages" className="mx-auto" />
        </div>
      </section>

      <hr className="my-6" />

      <section className="text-center">
        <img src="https://komarev.com/ghpvc/?username=papina&label=Profile%20views&color=0e75b6&style=flat" alt="papina" />
      </section>
    </div>
  );
};

export default Profile;
