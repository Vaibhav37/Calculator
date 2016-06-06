# Calculator
Basic and advanced calculator build in html,css,javascript with ajax request to switch between these two versions.

Calculator: Contains two seperate(.php) files.
            First is the basic version of calculator which operates on simply addition and subtraction operators.
            Second version is the advanced version which perform additional functions of multiplication,division,modulation.

Readme of calculator:-
1.click numerical buttons to enter numbers displayed in wooden color using css
2.click on corresponding operator followed by third operand.
3.We can also enter full string of calculation which will be parsed on the backend to generate the output.
4.Click on advanced button to generate ajax request for advanced page to load without page refresh.
5.Clicking on "CE" button will refresh the page and new entries can be added.(for advanced page , ajax request will be fired so that it doesn't reaches to basic)
6.Operator precedence not taken into account as it would have increased the complexity of parsing input data.
7.Eternal .css and .js files used ,which are referred to in the head tag .
