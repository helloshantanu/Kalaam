<p align="center"><a href="kalaam.io" target="_blank" rel="noopener noreferrer"><img width="300" src="https://i.ibb.co/Dg3jzC5/Logo.png" alt="Kalaam logo"></a></p>

<h2 align="center">Contribute to Kalaam</h2>

## परिचय

कलाम हिंदी में प्रोग्रामिंग भाषा है और इसमें आधुनिक प्रोग्रामिंग भाषा के सभी बुनियादी कार्य हैं। लूप्स से लेकर लूप्स तक और फंक्शन्स से लेकर कंडीशनल स्टेटमेंट्स तक। कलाम का अपना पार्सर, दुभाषिया है और पार्सर द्वारा उत्पन्न पार्स ट्री से स्रोत कोड निष्पादित करता है।


## Branch Guide

`v1.0.0`

- The first version of Kalaam. You can explore it to see how first version came out to be. 
- No development work happens here anymore.




`v1.1.0`

- The latest version of Kalaam with improvments over v1.0.O. 
- contains latest stable Kalaam code. 
- No new functionality added but more flexible code, testcases, error handling and a lot of functional programming.

Goals

- [x] Refactoring, Better Code structure and Improved code readability
- [x] Improve primitive Datatypes parsing
- [x] Commenting majority of codebase
- [x] modularise codebase as per functionalities
- [x] 15+ testcases




`v1.2.0-dev` 

- As the name suggests, this is where devlopment work happens for next version of Kalaam. 
- If you want to contrubute, submit PR's to this branch only.

Goals

- [] NPM package initialization
- [] IDesigning an E2E package
- [] Separate repo for npm package and frontend
- [] Standalone Documentation
- [] guidelines on further contributions



## Contributions

- You can work on either Frontend, Backend or Documentation, whatever you think you can be best at with your current level of experience.
- This is a complete Kalaam.io application. The compiler will be made available as a standalone npm package called Kalaam-core.
- Fork the repo and create PR's on current dev branch. For now, it is #`v1.2.0-dev`#.
- Feel free to play with project. Creative ideas are most welcome.
- Use Kalaam Discord sever to connect with fellow contributors. (https://discord.gg/vpezZjQQSQ)

`NOTE: MAKE SURE TO CREATE A PULL REQUEST ON 'v1.2.0-dev' and NOT DIRECTLY ON THE MASTER BRANCH.`


## Steps to follow 

1. Fork the repo
2. create branch with the name of issue you want to fix. for e.g ```fixes whitespace issue while cleaning sourcecode```
3. Run necessary tests using ```npm run test```. Add more test cases if you need to.
4. Make sure your code is not breaking anything.
5. Comment each line of your code. Write down why you are doing it instead of how you are doing it. Tell a story!
6. Once you are ready, create a PR on current dev branch. DO NOT CREATE PR'S DIRECTLY ON MASTER BRANCH.
7. Your code will be reviewed and if good, PR will be merged.
8. Happy Contributing ⚙️


## Future plans

- Right now, Kalaam is in it's early stage. Many programming languages took decades of team work to reach their God level. We go step by step.
- Kalaam needs to have a usecase so that people can start building stuff with it. The use-case can be unique that suits well to the Indian ecosystem. This will help us to move in a straight direction. Right now it's best for learning purposes.
- Consider Kalaam as your project, explore it and feel free to try out new ideas.

## Documentation

To check out documentation visit [Documentation](https://www.kalaam.io/documentation).

- Documentation needs a lot of work. I think short video tuts will really help instead of just the overload of texts.

## Examples

To check out examples visit [live examples](https://www.kalaam.io/examples).

Feel free to add more examples. We have three categories for examples. Basic, Intermediate, and advanced. Add according to context.

## Questions

For questions and support please use [the discord server](https://discord.com/invite/EMyA8TA).

## NPM

- Kalaam compiler package is available at https://www.npmjs.com/package/kalaam-core as "Kalaam-core".

P.S- The package is not setup for named exports yet like import 'Compile' from 'Kalaam-core'.
Instead, use the node_modules path like import 'Compile' from '../node_modules/src/lib/Compiler/main.js'

## Where is the compiler code?:

Visit 'src/lib/Compiler/main.js' in repo structure to access Kalaam compile engine and learn about how Kalaam works.

## To test kalaam.io locally

The setups for recreating the project have been given in the [SETUP.md](SETUP.md) file.

## Issues

Found an issue in Kalaam? Please use [submit issue](https://github.com/Kalaam-Programming-Language/Kalaam/issues).

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2020-present, Swanand Kadam
