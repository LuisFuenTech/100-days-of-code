# 100 Days Of Code - Log

### Day 0: December 15, 2018
##### 

**Today's Progress**: Learned all about *regular expressions* on *regex* on javascript.

**Thoughts:** I really heard about regex as a neat way to match characters, special characters and substring inside a string. Even I can replace those matches.

**Link to work:** [Regular Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions)

### Day 1: December 16, 2018
#####

**Today's Progress:** I'm still learning about regex and today I found *Capturing groups*, a feature allows search for repeat substrings.
It often apply basically when need to check a valid username, email or password.
Example: Valid and email
```
let reg = /[-.\w]+@([\w-]+.)+[\w-]{2,20}/g;
console.log("my@mail.com @ his@site.com.uk".match(reg)) -> ['my@mail.com', 'his@site.com.uk']
```

**Thoughts:** I was wondering how hard will know about complex *regex*, but it also have an interesting and neat way to code as a master.

**Links to work:** 
* [Regular Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions)
* [JavaScript info](https://javascript.info/regular-expressions)
