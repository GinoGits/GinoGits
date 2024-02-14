<!-- Divider -->
<img src="https://raw.githubusercontent.com/GinoGits/GinoGits/main/Assets/Divider.gif">

<!-- Header -->
<div align="center">
    <a href="https://www.GinoGit.com">
  <img src="https://github.com/GinoGits/GinoGits/blob/main/Assets/GinoGit.png?raw=true" align="center" style="width: 40%; margin-bottom: 20px;">
    </a>
</div>

<!-- Name -->
<div align="center">
<h2 align="center">Hey there, I’m Gino de Graaff 
  <a href="https://www.GinoGit.com">
    <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="20px"></h2>
  </a>


  <p> While I prefer to tell folks i'm a {Software Artist}, I've been referred to as a {software engineer}, {indie developer} or {tattoo artist} as well. 
          Regardless of the labels, I invite you to join into my world, where art, technology, creativity, and an unwavering passion come together.
      <br>
      <br>
  For me, code is more than just a tool, it's a canvas where I can bring my ideas to life.
  </p>
    <br>
</div>

<!-- Bio -->
<div align="center">
  <br>
  <h2>Bio</h2>
  <br>
</div>

```rust
struct Me {
    name: String,
    username: String,
    skills: Vec<String>,
}

impl Me {
    fn new(name: &str, username: &str, skills: &[&str]) -> Me {
        Me {
            name: name.to_owned(),
            username: username.to_owned(),
            skills: skills.iter().map(|&skill| skill.to_owned()).collect(),
        }
    }

    fn introduction(&self) -> String {
        format!("Hi, my name is {} but also known as {}.", self.name, self.username)
    }

    fn quote(&self) -> String {
        "The only way to do great work is to love what you do.".to_owned()
    }
}

fn main() {
    let gino = Me::new("Gino de Graaff", "GinoGit", &[
        "Creative", "Fullstack", "Git", "Algorithms", "Terminal", "Collaboration",
    ]);

    println!("{}", gino.introduction());
    println!("{:?}", gino.skills);
    println!("{}", gino.qoute());
}

```

<!-- Learn more -->
<div align="center">
  <br>
  <h2>Curious to learn more about me?</h2>
  <br>
  <p>Please feel welcome to visit my <a href="https://www.ginogit.com">website</a> to explore my socials, works and more! I'm excited to connect with new people, exchange ideas, and potentially discover new opportunities. Whether you're a fellow software engineer or simply share my enthusiasm for technology, I'm eager to hear from you!
  </p>
<p>Or if you're an insatiably curious cat, feel free to sneak a peek at the secret stash of tools I've hoarded in my <a href="https://www.dockhunt.com/users/GinoGit">Dock of Wonders</a>. It's like a treasure chest, but for tech geeks!</p>
</div>

<!-- GitHub Stats -->
<div align="center">
  <br>
  <h2>GitHub Stats</h2>
  <br>
  <a href="https://github.com/GinoGits">
      <img align="center" src="https://github-readme-stats.vercel.app/api?username=GinoGits&theme=dracula&count_private=true" />
    </a>
    <br>
    <br>
    <a href="https://github.com/GinoGits">
      <img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=GinoGits&theme=dracula" />
    </a>
    <br>
    <br>
   <a href="https://github.com/GinoGits">
     <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=GinoGits&theme=dracula" />
   </a>
   <br>
   <br>
   </div>
   
<!-- Architecture -->
<div align="center">
  <br>
  <h2>Architecture</h2>
  <br>
</div>

```bash
> fetch

console.log(`
┌───────────┬──────────────────────────────────────────┐
│  OS       │   MacOS                                  │
│  Host     │   MacBook                                │
│  Terminal │   Ghostty                                │
│  Shell    │   Zsh                                    │
│  IDE      │   Nova                                   │
│  Theme    │   Dracula Pro                            │
│  Font     │   Berkeley Mono                          │
└───────────┴──────────────────────────────────────────┘
`);
```

<!-- Contact -->
<section>
  <div align="center">
    <br>
    <h2>Contact</h2>
    <p>Got queries? Need some tech advice? Let's talk!</p>
    <p>Email: <a href="mailto:contact@ginogit.com">contact@ginogit.com</a></p>
    <p>Twitter: <a href="https://twitter.com/ginogit">@GinoGit</a></p>
    <br>
  </div>
</section>


<!-- Bottom -->
<div align="center">
  <br>
  <img src="https://raw.githubusercontent.com/GinoGits/GinoGits/main/Assets/Bottom.svg"/>
  <img src="https://raw.githubusercontent.com/GinoGits/GinoGits/main/Assets/Divider.gif">
  <br>
</div>


<!-- Footer -->
<div align="center">
  <br>
  <p>© 2024 GinoGit. All rights reserved.</p>
  <p>Designed and developed by <a href="https://www.ginogit.com">GinoGit</a></p>
  <br>
</div>
