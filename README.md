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


  <p> On a quest to bring fun back to tech!
      <br>
      <br>
I'm a tech enthusiast straight out of the Netherlands. I have a genuine curiosity for the world of tech, which has led me to become a jack of all trades in various domains: Hardware, Software, API, Artificial Intelligence, Security, Gadgets, a bit of tweaking -- you name it!
<br>
<br>
But forget about labels; the best way to really get to know me is by reaching out and getting in <a href="https://www.ginogit.com/contact">touch</a>.
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
        "Creative", "Fullstack", "Hardware", "Software", "Artificial Intelligence", 
        "Security", "Gadgets", "a bit of tweaking",
    ]);

    println!("{}", gino.introduction());
    println!("{:?}", gino.skills);
    println!("{}", gino.qoute());
}

```

<!-- GitHub Stats -->
<div align="center">
  <br>
  <h2>GitHub Stats</h2>
  <br>
 <a href="https://github.com/GinoGits">
      <img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=GinoGits&theme=dracula" />
    </a>
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
│  IDE      │   Zed                                    │
│  Theme    │   Dracula Pro                            │
│  Font     │   Berkeley Mono                          │
└───────────┴──────────────────────────────────────────┘
`);
```

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
