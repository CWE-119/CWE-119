### Improper Restriction of Operations within the Bounds of a Memory Buffer (aka. CWE-119)
- i am ghost becuz i am invisible for others 
- you call call me yotta-byte ttoo
- 
 [![Discord Presence](https://lanyard.cnrad.dev/api/449113066999775232)](https://discord.com/users/449113066999775232)

<p align="left">
  <img src="https://64.media.tumblr.com/92d2d43c3357c621fc3beec49b6c7850/tumblr_oi8o5utf9V1qfec8jo1_1280.gif">
</p> 

```rust
use std::io;

fn main(){

  every_wakey_wakey();
  
}

fn every_wakey_wakey(){
    
    let mut input = String::new();

    println!("your name here mate:");

    
    match io::stdin().read_line(&mut input) {
        Ok(_) => {
            println!(" {} Wakey Wakey!!! time for school ", input)
        },
        
        Err(e) => println!("{} , Ahh shit !!! Here we go again ", e)
    }
}
```

<p align="left"> 
  C4 timer<br>
  <img src="https://profile-counter.glitch.me/SamiulNahiyan/count.svg" />
</p>
<!--
**CWE-119/CWE-119** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->
