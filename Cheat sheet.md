# Rust cheat sheet
| Description | Syntax |
| -------- | ----------- |
| variable (with type inference) | let x = 10; |
| mutable variable  | let mut x = 5; |
| variables with difrent types | let sx: i32 = -1;<br>let ux: i32 = 2<br>let f: f32 = 1.5<br>let b: bool = false<br> |
| array | let a: [i32; 5] = [1, 3, 2, 0] |
| tuple | let t: (i32, f64, u8) = (-5, 1.5, 1) |
| print with new row | println!("Hello!"); |
| print | print!("Hello!"); |
| if | if x < 5 {<br>&emsp;println!("true");<br>&emsp;} else {<br>&emsp;println!("false")<br>} |
| instantiating with if | let y = if x < 5 { 2 } else { 5 }; |
| function | fn function (x: i32) -> i32 |
| structure | struct Rectangle {<br>&emsp; width: u32,<br>&emsp; height: u32,<br>} |
| initiate structure | let r = Rectangle {<br>&emsp;width: 4<br>&emsp;height: 5<br>} |
| implement function on struct | impl Rectangle {<br>&emsp;fn area(&self) -> u32 {<br>&emsp;&emsp;self.width * self.height<br>&emsp;}<br>} |
| refrence | let x = &s; |
| mutable refrence| let x = &mut s; |
| enum | enum Message {<br>&emsp;Quit,<br>&emsp;Move { x: i32, y: i32 },<br>&emsp;Write(String),<br>&emsp;ChangeColor(i32, i32, i32),<br>}|
| match | match message {<br>&emsp;Message::Quit => {}<br>&emsp;Message::Move { x, y } => {}<br>&emsp;Message::Write(text) => {}<br>&emsp;Message::ChangeColor(r, g, b)=> {}<br>} |
| closure (no parameters or return) | let closure = \|\| {<br>&emsp; //do stuf <br>}; |
| closure (parameters and return) | let closure = \|num: u32\| -> u32 {<br>&emsp; //do stuf <br>}; |
| open tread | let handle = thread::spawn(\|\| {<br>&emsp;// do stuf<br>}) |
| close tread | handle.join().unrawp() |
