# Genetic Algorithm for University Course Scheduling

Developed a genetic algorithm-based system to address the NP-hard problem of university course scheduling, ensuring efficient and conflict-free timetabling.

The system aims to optimize scheduling by considering both hard and soft constraints to meet the needs of students and faculty.

Collected and processed data for course schedules, including student enrollments, faculty assignments, and room availability.

Utilized genetic algorithms for optimization, leveraging the principles of natural selection and genetics to generate high-quality solutions.
    o Employed binary encoding to represent chromosomes, which encapsulate scheduling information.
    o Initialized the population randomly to ensure a diverse set of potential solutions.

Genetic Algorithm Operators:
    o Implemented rank-based selection to prioritize high-fitness individuals, ensuring diversity and avoiding premature convergence.
    o Used uniform crossover to combine genetic information from parent chromosomes, enhancing solution quality.
    o Applied bit-flipping mutation to maintain genetic diversity and prevent local optima.

Conducted convergence tests and termination conditions to determine the optimal solution, ensuring the algorithm stopped when no better solutions were found.

Constraints Management:
    o Ensured no two courses were scheduled in the same room at the same time, no faculty member was assigned to two rooms simultaneously, and room assignments did not overlap.
    o Minimized student fatigue by limiting consecutive courses and total daily teaching hours, while considering preferred course timings.

Demonstrated the superiority of the genetic algorithm over traditional methods through comparative studies, achieving a high optimality rate of 93% in scheduling.

Collected and integrated feedback from students and faculty to refine constraints and improve the scheduling system dynamically.
