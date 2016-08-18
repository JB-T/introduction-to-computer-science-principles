<!--- REVISED -->
# Lesson 2.4: Boole in the House   <!-- Formerly 2.5 -->

## Learning Objectives

Students will be able to...

-   Define and identify Boolean expressions and operators
-   Evaluate Boolean expressions
-   Utilize Boolean operators (and/or/not) to create compound conditions

## Materials/Preparation

-   [Lab 2.4 handout (Triangles of All Kinds)](lab_24.md) ([Download in Word](Unit 2 Word/Lab 2.4 Triangles of All Kinds.docx)) ([Link to PDF](https://teals.sharepoint.com/curriculum/_layouts/15/guestaccess.aspx?guestaccesstoken=hxvo2nEHBhwdcjTXTK791hy01%2f8Fo5Z21cqgMR61PX8%3d&docid=04f343aec4d8141038dd482233763ef3c))

## Pacing Guide

| Duration   | Description                                   |
| ---------- | --------------------------------------------- |
| 5 minutes  | Welcome, attendance, bell work, announcements |
| 20 minutes | Review and lecture                            |
| 20 minutes | Triangles activity                            |
| 10 minutes | Debrief and wrap-up                           |

## Instructor's Notes

1.  Review
    -   Remind students about conditional statements, and ask what the blocks that can go in the holes in if blocks have in common
        -   Blocks are "pointy" and all  are "yes/no" or "true/false" questions
2.  Lecture
    -   Introduce and define "Boolean expressions" as expressions that evaluate to true or false
        -   If desired, explain that the term "Boolean" is derived from [George Boole](https://en.wikipedia.org/wiki/George_Boole)
        -   In SNAP, all Boolean expressions are pointy six-sided blocks
    -   Present the three Boolean operators: and, or and not
        -   Define the operators and describe when each will return true
        -   Show the truth tables for each operator and explain how to read them
            -   Describe that truth tables are read much like multiplication tables: find the two operands on the two edges, then find where the row and column meet to see the result
            -   Truth tables are simply one way of expressing how the Boolean operators work; if students are struggling, other depictions (such as an exhaustive list of all possible results) can be substituted
        -   Emphasize that since Boolean operators are themselves Boolean expressions, they can be nested
        -   Practice evaluating Boolean expressions, starting simple and moving to more complex nested operations
            -   Start with simple expressions: e.g. `5 < 7 AND 4 > 2`
            -   Introduce variables: e.g. `x = 7; x < 5 OR x > 10`
            -   Nest operations: e.g. `(x = 4; y = -3; x == y OR (x > 0 AND y < 0))`
        -   Discuss short-circuiting in evaluation of Boolean expressions
    -   Discuss situations in which the Boolean operators might be needed
        -   The lack of <= and >= operators in SNAP makes for a great example
        -   
3.  Activity
    -   Students should complete the ["Triangles of All Kinds"](lab_24.md) activity individually or in pairs
        -   A number of geometric concepts (Triangle Inequality Theorem, Pythagorean Theorem, etc.) are used in this lab, but students need not have a deep understanding of them.  The necessary points are explained in the lab.
        -   Encourage students to think about whether an "and" or an "or" is appropriate in each case.  Draw out truth tables if necessary.
4.  Debrief
    -   Walk through a student's response
        -   Point out uses of Boolean operators
        -   Discuss how nested or chained if blocks could potentially be used to obtain the same behavior, but would result in longer, less-readable code

## Accommodations/Differentiation

-   Students that have not taken Geometry made be intimidated by some of the concepts in the lab.  Deep understanding of the theorems is not necessary; encourage the students to simply focus on the equations and inequalities presented.
    -   If the students continue to struggle, help them build the necessary expressions, but encourage them to assemble them into the full condition on their own.
-   Advanced students, especially those who have taken higher levels of math, can be encouraged to add additional functionality, such as using [Heron's formula](https://en.wikipedia.org/wiki/Heron%27s_formula) to calculate the triangles area or using trigonometry to attempt to draw the triangle.
    -   Drawing the triangle is very challenging.
