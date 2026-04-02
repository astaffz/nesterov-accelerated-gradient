# Nesterov Accelerated Gradient Minimization Method (NAG)

_(bs. Nesterovljev ubrzani gradijentni metod za minimizaciju)_

**Term paper conducted on the topic of the Nesterov Accelerated Gradient (NAG) minimization method.**

**Authors:** A. Mustafić (@astaffz) & Z. Ljutika (@Ljut)  
**Course:** Numerical Algorithms, Computer Science BSc., Prof. dr. Željko Jurić  
**Institution:** Faculty of Electrical Engineering, University of Sarajevo  
**Language:** Bosnian

**Practical Examples:** All examples are provided in the `src/` directory and are implemented in Julia

## Abstract

Accelerating the convergence rate of optimizations algorithms represents a key issue in modern applied mathematics and computer science.
This paper aims to showcase the Nesterov accelerated gradient minimazation method (or NAG for short), its implementation, as well as some of its modern practical applications.

First, the paper delves into the mathematical basis necessary for understanding the method, including a visual analysis and discussion of its theoretical convergence rate of $O(1/k^2)$.

Next, as an example, the method is implemented in the form of code, written in the **Julia programming language**, along with other, mathematically equvivalent forms,
such as those proposed by Sutskever and Bengio, which represent an important milestone in the development of modern deep learning and neural networks.

The validity and equivavalence of the presented formulations are tested and visualized using a few selected examples, including **Rosenbrock's function**, a standard benchmark in optimization theory.
Finally, the paper discusses some of the method's key present-day practical applications, primarily in deep learning, signal processing, and data analysis, and summarizes its main strengths and limitations.

## License

This repository contains both software code and written academic material:

- **Source code** (located in the `src/` directory) is licensed under the **MIT License**.
- **Textual content, figures, and the term paper** (located in the `paper/` directory) are licensed under **Creative Commons Attribution 4.0 (CC BY 4.0)**.

This separation follows common academic and open-source practices.
