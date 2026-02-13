<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Class 10 Computer - C Language Introduction | Important Questions</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            overflow: hidden;
        }

        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 30px;
            text-align: center;
        }

        header h1 {
            font-size: 2em;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.1em;
            opacity: 0.9;
        }

        .content {
            padding: 30px;
        }

        .section {
            margin-bottom: 30px;
        }

        .section-title {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 15px 20px;
            border-radius: 10px;
            font-size: 1.3em;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .question-card {
            background: #f8f9fa;
            border-left: 4px solid #667eea;
            padding: 20px;
            margin-bottom: 15px;
            border-radius: 8px;
            transition: all 0.3s ease;
            cursor: pointer;
        }

        .question-card:hover {
            background: #e9ecef;
            transform: translateX(5px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }

        .question {
            font-weight: 600;
            color: #333;
            margin-bottom: 10px;
            font-size: 1.05em;
        }

        .marks {
            display: inline-block;
            background: #764ba2;
            color: white;
            padding: 3px 10px;
            border-radius: 15px;
            font-size: 0.85em;
            margin-left: 10px;
        }

        .answer {
            display: none;
            margin-top: 15px;
            padding: 15px;
            background: white;
            border-radius: 5px;
            color: #555;
            line-height: 1.6;
        }

        .answer.show {
            display: block;
            animation: slideDown 0.3s ease;
        }

        @keyframes slideDown {
            from {
                opacity: 0;
                transform: translateY(-10px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .toggle-btn {
            background: #667eea;
            color: white;
            border: none;
            padding: 8px 15px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 0.9em;
            margin-top: 10px;
            transition: background 0.3s ease;
        }

        .toggle-btn:hover {
            background: #5568d3;
        }

        code {
            background: #f4f4f4;
            padding: 2px 6px;
            border-radius: 3px;
            font-family: 'Courier New', monospace;
            color: #d63384;
        }

        .code-block {
            background: #2d2d2d;
            color: #f8f8f2;
            padding: 15px;
            border-radius: 5px;
            overflow-x: auto;
            margin: 10px 0;
            font-family: 'Courier New', monospace;
        }

        .note {
            background: #fff3cd;
            border-left: 4px solid #ffc107;
            padding: 15px;
            margin: 20px 0;
            border-radius: 5px;
        }

        .note strong {
            color: #856404;
        }

        ul, ol {
            margin-left: 20px;
            margin-top: 10px;
        }

        li {
            margin-bottom: 8px;
        }

        footer {
            background: #2d3436;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 30px;
        }

        .expand-all {
            text-align: center;
            margin: 20px 0;
        }

        .expand-all button {
            background: #28a745;
            color: white;
            border: none;
            padding: 12px 30px;
            border-radius: 25px;
            cursor: pointer;
            font-size: 1em;
            font-weight: 600;
            transition: all 0.3s ease;
        }

        .expand-all button:hover {
            background: #218838;
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>📚 Class 10 Computer Science</h1>
            <p>Chapter 1: Introduction to C Language</p>
            <p style="font-size: 0.9em; margin-top: 10px;">Important Questions & Answers</p>
        </header>

        <div class="content">
            <div class="expand-all">
                <button onclick="toggleAll()">Show All Answers</button>
            </div>

            <!-- Very Short Answer Questions -->
            <div class="section">
                <div class="section-title">
                    📝 Very Short Answer Questions (1 Mark)
                </div>

                <div class="question-card" onclick="toggleAnswer(this)">
                    <div class="question">
                        Q1. What is C language?
                        <span class="marks">1 Mark</span>
                    </div>
                    <div class="answer">
                        C is a general-purpose, high-level programming language developed by Dennis Ritchie at AT&T Bell Laboratories in 1972. It is a structured programming language widely used for system programming and application development.
                    </div>
                </div>

                <div class="question-card" onclick="toggleAnswer(this)">
                    <div class="question">
                        Q2. Who developed C language and when?
                        <span class="marks">1 Mark</span>
                    </div>
                    <div class="answer">
                        C language was developed by <strong>Dennis Ritchie</strong> in <strong>1972</strong> at AT&T Bell Laboratories, USA.
                    </div>
                </div>

                <div class="question-card" onclick="toggleAnswer(this)">
                    <div class="question">
                        Q3. What is a compiler?
                        <span class="marks">1 Mark</span>
                    </div>
                    <div class="answer">
                        A compiler is a software program that translates the entire source code written in a high-level language into machine language (object code) before execution.
                    </div>
                </div>

                <div class="question-card" onclick="toggleAnswer(this)">
                    <div class="question">
                        Q4. What is the extension of a C program file?
                        <span class="marks">1 Mark</span>
                    </div>
                    <div class="answer">
                        The extension of a C program file is <code>.c</code> (e.g., program.c)
                    </div>
                </div>

                <div class="question-card" onclick="toggleAnswer(this)">
                    <div class="question">
                        Q5. What is an algorithm?
                        <span class="marks">1 Mark</span>
                    </div>
                    <div class="answer">
                        An algorithm is a step-by-step procedure or set of instructions written in simple English to solve a specific problem.
                    </div>
                </div>

                <div class="question-card" onclick="toggleAnswer(this)">
                    <div class="question">
                        Q6. What is a flowchart?
                        <span class="marks">1 Mark</span>
                    </div>
                    <div class="answer">
                        A flowchart is a pictorial or graphical representation of an algorithm using standard symbols to show the flow of control in a program.
                    </div>
                </div>

                <div class="question-card" onclick="toggleAnswer(this)">
                    <div class="question">
                        Q7. Name any two C compilers.
                        <span class="marks">1 Mark</span>
                    </div>
                    <div class="answer">
                        <ul>
                            <li>Turbo C/C++</li>
                            <li>GCC (GNU Compiler Collection)</li>
                        </ul>
                    </div>
                </div>

                <div class="question-card" onclick="toggleAnswer(this)">
                    <div class="question">
                        Q8. What is source code?
                        <span class="marks">1 Mark</span>
                    </div>
                    <div class="answer">
                        Source code is the original program written by a programmer in a high-level language like C, which needs to be compiled before execution.
                    </div>
                </div>
            </div>

            <!-- Short Answer Questions -->
            <div class="section">
                <div class="section-title">
                    ✍️ Short Answer Questions (2-3 Marks)
                </div>

                <div class="question-card" onclick="toggleAnswer(this)">
                    <div class="question">
                        Q9. Write the basic structure of a C program.
                        <span class="marks">3 Marks</span>
                    </div>
                    <div class="answer">
                        The basic structure of a C program consists of:
                        <div class="code-block">
/* Documentation Section */
/* Preprocessor Directives */
#include &lt;stdio.h&gt;

/* Global Declaration Section */
int global_variable;

/* main() function */
int main()
{
    /* Local Declaration Section */
    int local_variable;
    
    /* Executable Statements */
    printf("Hello World");
    
    return 0;
}

/* User-defined Functions */
                        </div>
                    </div>
                </div>

                <div class="question-card" onclick="toggleAnswer(this)">
                    <div class="question">
                        Q10. Differentiate between compiler and interpreter.
                        <span class="marks">3 Marks</span>
                    </div>
                    <div class="answer">
                        <table style="width: 100%; border-collapse: collapse; margin-top: 10px;">
                            <tr style="background: #667eea; color: white;">
                                <th style="border: 1px solid #ddd; padding: 10px;">Compiler</th>
                                <th style="border: 1px solid #ddd; padding: 10px;">Interpreter</th>
                            </tr>
                            <tr>
                                <td style="border: 1px solid #ddd; padding: 10px;">Translates entire program at once</td>
                                <td style="border: 1px solid #ddd; padding: 10px;">Translates line by line</td>
                            </tr>
                            <tr>
                                <td style="border: 1px solid #ddd; padding: 10px;">Execution is faster</td>
                                <td style="border: 1px solid #ddd; padding: 10px;">Execution is slower</td>
                            </tr>
                            <tr>
                                <td style="border: 1px solid #ddd; padding: 10px;">Displays all errors after compilation</td>
                                <td style="border: 1px solid #ddd; padding: 10px;">Displays errors line by line</td>
                            </tr>
                            <tr>
                                <td style="border: 1px solid #ddd; padding: 10px;">Requires more memory</td>
                                <td style="border: 1px solid #ddd; padding: 10px;">Requires less memory</td>
                            </tr>
                            <tr>
                                <td style="border: 1px solid #ddd; padding: 10px;">Example: C, C++</td>
                                <td style="border: 1px solid #ddd; padding: 10px;">Example: Python, BASIC</td>
                            </tr>
                        </table>
                    </div>
                </div>

                <div class="question-card" onclick="toggleAnswer(this)">
                    <div class="question">
                        Q11. List the features of C language.
                        <span class="marks">3 Marks</span>
                    </div>
                    <div class="answer">
                        <strong>Features of C Language:</strong>
                        <ul>
                            <li><strong>Simple:</strong> Easy to learn and understand</li>
                            <li><strong>Portable:</strong> Programs can run on different machines</li>
                            <li><strong>Structured:</strong> Follows structured programming approach</li>
                            <li><strong>Fast:</strong> Compiled language, executes quickly</li>
                            <li><strong>Rich Library:</strong> Large collection of built-in functions</li>
                            <li><strong>Middle-level language:</strong> Combines features of high and low level languages</li>
                            <li><strong>Case Sensitive:</strong> Differentiates between uppercase and lowercase</li>
                        </ul>
                    </div>
                </div>

                <div class="question-card" onclick="toggleAnswer(this)">
                    <div class="question">
                        Q12. What are keywords in C? Give examples.
                        <span class="marks">2 Marks</span>
                    </div>
                    <div class="answer">
                        <strong>Keywords</strong> are reserved words in C language that have predefined meanings and cannot be used as identifiers (variable names, function names, etc.).
                        <br><br>
                        <strong>Examples:</strong> <code>int</code>, <code>float</code>, <code>char</code>, <code>if</code>, <code>else</code>, <code>while</code>, <code>for</code>, <code>return</code>, <code>void</code>, <code>break</code>, <code>continue</code>, <code>switch</code>
                        <br><br>
                        C has 32 keywords in total.
                    </div>
                </div>

                <div class="question-card" onclick="toggleAnswer(this)">
                    <div class="question">
                        Q13. Explain the steps involved in program execution.
                        <span class="marks">3 Marks</span>
                    </div>
                    <div class="answer">
                        <strong>Steps in Program Execution:</strong>
                        <ol>
                            <li><strong>Writing the Program:</strong> Write source code in a text editor and save with .c extension</li>
                            <li><strong>Compilation:</strong> Compiler translates source code into object code (.obj file)</li>
                            <li><strong>Linking:</strong> Linker combines object code with library functions to create executable file (.exe)</li>
                            <li><strong>Loading:</strong> Loader loads the executable file into memory</li>
                            <li><strong>Execution:</strong> CPU executes the program and produces output</li>
                        </ol>
                    </div>
                </div>

                <div class="question-card" onclick="toggleAnswer(this)">
                    <div class="question">
                        Q14. What are identifiers? Write rules for naming identifiers.
                        <span class="marks">3 Marks</span>
                    </div>
                    <div class="answer">
                        <strong>Identifiers</strong> are names given to variables, functions, arrays, etc. in a program.
                        <br><br>
                        <strong>Rules for Naming Identifiers:</strong>
                        <ul>
                            <li>Must begin with a letter (A-Z, a-z) or underscore (_)</li>
                            <li>Can contain letters, digits (0-9), and underscores</li>
                            <li>No special characters or spaces are allowed</li>
                            <li>Keywords cannot be used as identifiers</li>
                            <li>Case sensitive (Sum and sum are different)</li>
                            <li>Maximum length is 31 characters</li>
                        </ul>
                        <strong>Valid Examples:</strong> total, _sum, marks1, Student_Name<br>
                        <strong>Invalid Examples:</strong> 1total, student name, int, sum@total
                    </div>
                </div>

                <div class="question-card" onclick="toggleAnswer(this)">
                    <div class="question">
                        Q15. Draw flowchart symbols and their uses.
                        <span class="marks">3 Marks</span>
                    </div>
                    <div class="answer">
                        <strong>Flowchart Symbols:</strong>
                        <ul>
                            <li><strong>Oval/Terminal:</strong> Start/Stop of program</li>
                            <li><strong>Parallelogram:</strong> Input/Output operations</li>
                            <li><strong>Rectangle:</strong> Process/Assignment statements</li>
                            <li><strong>Diamond:</strong> Decision making (conditions)</li>
                            <li><strong>Arrow:</strong> Flow of control</li>
                            <li><strong>Circle:</strong> Connector to connect flowchart parts</li>
                        </ul>
                    </div>
                </div>
            </div>

            <!-- Long Answer Questions -->
            <div class="section">
                <div class="section-title">
                    📖 Long Answer Questions (5 Marks)
                </div>

                <div class="question-card" onclick="toggleAnswer(this)">
                    <div class="question">
                        Q16. Write a C program to print "Hello World".
                        <span class="marks">5 Marks</span>
                    </div>
                    <div class="answer">
                        <div class="code-block">
/* Program to print Hello World */
#include &lt;stdio.h&gt;

int main()
{
    printf("Hello World");
    return 0;
}
                        </div>
                        <strong>Explanation:</strong>
                        <ul>
                            <li><code>#include &lt;stdio.h&gt;</code> - Preprocessor directive to include standard input/output library</li>
                            <li><code>int main()</code> - Main function where execution begins</li>
                            <li><code>printf()</code> - Function to display output on screen</li>
                            <li><code>return 0;</code> - Returns 0 to indicate successful execution</li>
                        </ul>
                    </div>
                </div>

                <div class="question-card" onclick="toggleAnswer(this)">
                    <div class="question">
                        Q17. Write an algorithm and draw flowchart to find the sum of two numbers.
                        <span class="marks">5 Marks</span>
                    </div>
                    <div class="answer">
                        <strong>Algorithm:</strong>
                        <ol>
                            <li>Start</li>
                            <li>Declare variables a, b, sum</li>
                            <li>Read values of a and b</li>
                            <li>Calculate sum = a + b</li>
                            <li>Display sum</li>
                            <li>Stop</li>
                        </ol>
                        <br>
                        <strong>Flowchart Steps:</strong>
                        <ol>
                            <li>Start (Oval)</li>
                            <li>Input a, b (Parallelogram)</li>
                            <li>sum = a + b (Rectangle)</li>
                            <li>Output sum (Parallelogram)</li>
                            <li>Stop (Oval)</li>
                        </ol>
                    </div>
                </div>

                <div class="question-card" onclick="toggleAnswer(this)">
                    <div class="question">
                        Q18. Explain the advantages and disadvantages of C language.
                        <span class="marks">5 Marks</span>
                    </div>
                    <div class="answer">
                        <strong>Advantages of C Language:</strong>
                        <ul>
                            <li>Simple and easy to learn</li>
                            <li>Portable - programs can run on different platforms</li>
                            <li>Fast execution due to compilation</li>
                            <li>Rich set of built-in functions and operators</li>
                            <li>Supports structured programming</li>
                            <li>Can be used for system programming</li>
                            <li>Provides low-level access to memory</li>
                            <li>Case sensitive language</li>
                        </ul>
                        <br>
                        <strong>Disadvantages of C Language:</strong>
                        <ul>
                            <li>No strict type checking</li>
                            <li>No concept of OOP (Object Oriented Programming)</li>
                            <li>No runtime checking</li>
                            <li>Difficult to detect errors</li>
                            <li>No namespace concept</li>
                            <li>Not suitable for modern programming paradigms</li>
                        </ul>
                    </div>
                </div>

                <div class="question-card" onclick="toggleAnswer(this)">
                    <div class="question">
                        Q19. Write a C program to add two numbers.
                        <span class="marks">5 Marks</span>
                    </div>
                    <div class="answer">
                        <div class="code-block">
/* Program to add two numbers */
#include &lt;stdio.h&gt;

int main()
{
    int a, b, sum;
    
    printf("Enter first number: ");
    scanf("%d", &a);
    
    printf("Enter second number: ");
    scanf("%d", &b);
    
    sum = a + b;
    
    printf("Sum = %d", sum);
    
    return 0;
}
                        </div>
                        <strong>Output:</strong>
                        <div class="code-block">
Enter first number: 5
Enter second number: 10
Sum = 15
                        </div>
                    </div>
                </div>

                <div class="question-card" onclick="toggleAnswer(this)">
                    <div class="question">
                        Q20. Differentiate between algorithm and flowchart.
                        <span class="marks">3 Marks</span>
                    </div>
                    <div class="answer">
                        <table style="width: 100%; border-collapse: collapse; margin-top: 10px;">
                            <tr style="background: #667eea; color: white;">
                                <th style="border: 1px solid #ddd; padding: 10px;">Algorithm</th>
                                <th style="border: 1px solid #ddd; padding: 10px;">Flowchart</th>
                            </tr>
                            <tr>
                                <td style="border: 1px solid #ddd; padding: 10px;">Step-by-step written procedure</td>
                                <td style="border: 1px solid #ddd; padding: 10px;">Graphical/pictorial representation</td>
                            </tr>
                            <tr>
                                <td style="border: 1px solid #ddd; padding: 10px;">Easy to write and understand</td>
                                <td style="border: 1px solid #ddd; padding: 10px;">Requires knowledge of symbols</td>
                            </tr>
                            <tr>
                                <td style="border: 1px solid #ddd; padding: 10px;">No standard rules</td>
                                <td style="border: 1px solid #ddd; padding: 10px;">Uses standard symbols</td>
                            </tr>
                            <tr>
                                <td style="border: 1px solid #ddd; padding: 10px;">Difficult to debug</td>
                                <td style="border: 1px solid #ddd; padding: 10px;">Easy to debug and understand flow</td>
                            </tr>
                            <tr>
                                <td style="border: 1px solid #ddd; padding: 10px;">Easier for complex problems</td>
                                <td style="border: 1px solid #ddd; padding: 10px;">Difficult for complex problems</td>
                            </tr>
                        </table>
                    </div>
                </div>
            </div>

            <div class="note">
                <strong>💡 Study Tips:</strong>
                <ul>
                    <li>Practice writing basic C programs regularly</li>
                    <li>Understand the difference between compiler and interpreter</li>
                    <li>Memorize flowchart symbols and their uses</li>
                    <li>Learn the basic structure of C programs</li>
                    <li>Practice drawing flowcharts for simple problems</li>
                </ul>
            </div>
        </div>

        <footer>
            <p>📚 Best of luck for your exams! Keep practicing! 💪</p>
            <p style="margin-top: 10px; font-size: 0.9em;">Class 10 Computer Science - Chapter 1: C Language Introduction</p>
        </footer>
    </div>

    <script>
        function toggleAnswer(element) {
            const answer = element.querySelector('.answer');
            answer.classList.toggle('show');
        }

        let allExpanded = false;
        function toggleAll() {
            const answers = document.querySelectorAll('.answer');
            const button = document.querySelector('.expand-all button');
            
            if (!allExpanded) {
                answers.forEach(answer => answer.classList.add('show'));
                button.textContent = 'Hide All Answers';
                allExpanded = true;
            } else {
                answers.forEach(answer => answer.classList.remove('show'));
                button.textContent = 'Show All Answers';
                allExpanded = false;
            }
        }
    </script>
</body>
</html>
