# 2021_viralTissueWorkshop

COVID-19 is a disease caused by the virus SARS-CoV-2. As you may already know, this virus has caused the current global pandemic and changed all of our lives. Computational biology (the study of biology using computers) has been an important tool for understanding how viruses hijack the body’s own cells to spread in a person and through human populations. In this workshop, you will focus on learning about the ways in which viruses such as SARS-CoV-2 spread in the body.  You will be using code that you will build and modify, just as computational biologists do. 

This activity take about 1 hour. It is aimed at high schoolers from beginer to expert level background in coding and biology.

Run python in browser: https://mybinder.org/v2/gh/jennifer-bio/2021_viralTissueWorkshop/HEAD 
Or download code and run on locally with jupyter notebooks.

## Worksheet questions

### Before you start running code in the jupyter notebook
* 1 Think about the parameter INFECT_PROB, which stands for ‘infection probability’:

  * 1a. If INFECT_PROB is set to 0, what would happen to the healthy cells next to a Viral Assembly (VA) cell? Or the healthy cells next to a Viral Release (VR) cell?

  * 1b. If INFECT_PROBis set to 1, what would happen to the healthy cells next to a Viral Assembly (VA) cell? Or the healthy cells next to a Viral Release (VR) cell?

### Run simulation and visualize
2. When you run the below code how many times do you run one_time_step(tissue, infect_prob)?

  n_time_steps = 30
 
  tissue_frames = t_time_step(n_time_steps, tissue, infect_prob = INFECT_PROB)

3. Once you have made your first movie, think about the image 

+ 3a. What do the legend colors represent?

3b. Describe what you see happen over time in the animation: what is the end state and how did it get there

4. Run the simulation again and change the value of INFECT_PROB

4a. What happens if INFECT_PROB = 0.05?

4b. What happens if INFECT_PROB = 0.95?

5. What would happen if you double the value of max_starting_infected? 
Note that the actual number of starting infected cells is a random number within the range 0 to max_starting_infected. So try running the simulation 3 or more times. 
5a. How does max_starting_infected influence the number of starting infected cells?

5b. How does the number of starting infected cells change the simulation?

### Plot infection with immune system over time
6. Before you run the final cell in this section to generate the simulation, what do you predict will happen? How will this be different than the previous simulation?

7. Re-run the simulation and change the n_immune_recruited value

7a. What happens when you change n_immune_recruited to 0? 

7b. What happens when you change n_immune_recruited to 10?

8. What do you think could be some reasons that different people have different immune response levels?

9. If you were to simulate the effect of the individual having had a vaccine, how would the immune system behavior change?

### Final questions
10. What is one biological feature/behavior that you learned about today, or already knew about, which was not represented in these simulations?

11. Do you think all viruses would behave the same as in our simulations? Can you think of any which might behave differently? 
