 # TODO:
 ---------------------

 - [ ] runtime
   - [ ] Rust
   - [ ] C 
 - [ ] language
   - [x] parser
     - [x] tests
     - [x] i32
     - [x] f32
     - [ ] explicit syntax eg `123f32`
 - [ ] compiler
   - [ ] i32
   - [ ] f32
  
 ## Questions
  
   - Explicit number notation xxxf32
   - Behaviour of - with regard to underflow - should `-` op always result in an int on uints? or keep the behaviour the same?
   - Should relations on ints return uints?
   - New syntax constract for casting eg `x as y`... seems undesirable use a built in constructor
     - Easy to cast from `u32 -> i32 -> f32` but obviously non trivial to cast `f32 -> i32 -> u32` 