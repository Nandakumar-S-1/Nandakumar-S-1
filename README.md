<h1 align="center">Hi 👋, I'm Nandakumar S</h1>
<h3 align="center">MERN Stack Developer & DSA Enthusiast</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=nandakumar-s-1&label=Profile%20views&color=0e75b6&style=flat" alt="nandakumar-s-1" />
</p>

```ts
const profile = {
  name: "Wiz Kid",
  title: "MERN Stack Developer & DSA Enthusiast",
  location: "Kerala, India",
  skills: [
    "JavaScript", "TypeScript", "Node.js", "Express.js", 
    "MongoDB", "PostgreSQL", "HTML", "CSS", "Bootstrap", "DSA"
  ],
  certifications: [
    "Diploma in Software Engineering - Govt. Polytechnic College Cherthala"
  ],
  interests: [
    "Building full-stack web apps",
    "Learning New Technologies"
    "Trying to Mastering DSA (LL, Tree, BST, Graph, Trie)",
    "Currently exploring React"
  ]
};

function introduce(profile: typeof profile) {
  console.log(`👋 Hi, I'm ${profile.name}! 💻 I'm passionate ${profile.title} from ${profile.location}.`);
  console.log("🛠 Skills:");
  console.log("  - " + profile.skills.join("\n  - "));
  console.log("📜 Certifications:");
  console.log("  - " + profile.certifications.join("\n  - "));
  console.log("🚀 Interests:");
  console.log("  - " + profile.interests.join("\n  - "));
}
