type Profile = {
  name: string;
  title: string;
  location: string;
  skills: string[];
  certifications: string[];
  interests: string[];
};

const profile: Profile = {
  name: "Wiz Kid",
  title: "MERN Stack Developer & DSA Enthusiast",
  location: "Kerala, India",
  skills: [
    "JavaScript",
    "TypeScript",
    "Node.js",
    "Express.js",
    "MongoDB",
    "PostgreSQL",
    "HTML",
    "CSS",
    "Bootstrap",
    "EJS"
  ],
  certifications: [
    "Diploma in Software Engineering - Govt. Polytechnic College Cherthala"
  ],
  interests: [
    "Building full-stack web apps",
    "Creating clone projects for hands-on learning",
    "Mastering Data Structures & Algorithms (LL, Tree, BST, Graph, Trie)",
    "Currently exploring React"
  ]
};

function introduce(profile: Profile): void {
  console.log(`
👋 Hi, I'm ${profile.name}!
💻 I'm a passionate ${profile.title} from ${profile.location}.

🔧 Skills:
  - ${profile.skills.join("\n  - ")}

🎓 Education & Certifications:
  - ${profile.certifications.join("\n  - ")}

🚀 Interests:
  - ${profile.interests[0]}
  - ${profile.interests[1]}
  - ${profile.interests[2]}
  - ${profile.interests[3]}
`);
}

introduce(profile);
