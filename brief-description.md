If you look at science-oriented IDEs, they all work like this. Scientific programmers are no longer strictly writing programs. We do everything with data and visualization. Consequently, IDEs have turned into dashboards with this kind of drag-and-drop capability. A science-oriented IDE will have source panes, a command line, a terminal, a file explorer, a help panel, a plot panel, a history panel, etc., etc. And the user wants to arrange these to their liking.

I think the _dashboard_ is becoming an extremely common and versatile application paradigm which has led to a multitude of libraries that each provide _some_ of the toolset needed to make them. In fact, I believe that all modern data science IDEs are essentially already dashboards or, in the case of VS Code, a set of plugins to turn a code editor into a dashboard.

Consider the following images of RStudio, Spyder, Matlab, and VS Code:

The basis of these applications are a grid of _panels_ which may further contain sub-panels or tabs. Generally, these panels have header bars and can be placed within the application window with some amount of freedom. Likewise for the sub-panels and tabs. In most cases these can be minimized, maximized, closed, dragged and dropped, and even popped-out and re-docked.

These panels can contain many different widget types such as editors, data tables, file explorers, command terminals, plots, help documentation, and others. There are great widget libraries that can be used for these. But for the basic dashboard/IDE functionality, I haven't found a single library with all the needed features/properties.

I want to build a pure javascript IDE like that.

# Matlab

![image](https://user-images.githubusercontent.com/5349876/205551369-b9005b86-736e-495a-863f-0b1b0025b46a.png)

![image](https://user-images.githubusercontent.com/5349876/205552131-f31d9dab-3b95-46ad-9a08-7ccfdc5ce873.png)

![image](https://user-images.githubusercontent.com/5349876/205552870-e98f267b-8aca-4e82-9482-028c020ee492.png)

# Scilab
![image](https://user-images.githubusercontent.com/5349876/205553081-6df03ad7-ccb7-4a4e-b02f-db33cc7ab805.png)

![image](https://user-images.githubusercontent.com/5349876/205553184-9db6289b-7eb6-4148-9d57-c15cd1b599f1.png)

# RStudio

![image](https://user-images.githubusercontent.com/5349876/205553672-8bcf9b25-1dc8-49fe-9671-2eec32ca477b.png)

![image](https://user-images.githubusercontent.com/5349876/205553750-3d903439-da69-48b4-bf06-d51df34706ff.png)

![image](https://user-images.githubusercontent.com/5349876/205554204-97ce7c08-20a8-49b8-9d96-f71c69e75e71.png)

![image](https://user-images.githubusercontent.com/5349876/205554252-9eb319b6-ef90-4392-8cb2-9b0be2bb36e7.png)


# Spyder

![image](https://user-images.githubusercontent.com/5349876/205553324-63003d01-7467-480c-bc96-ddbefd73265d.png)

![image](https://user-images.githubusercontent.com/5349876/205553470-d87a5ae3-601c-4153-abd1-712eb10b450f.png)

# Octave

![image](https://user-images.githubusercontent.com/5349876/205553625-254c368b-291b-40aa-852f-0dd224afe10d.png)

# Jupyterlab

![image](https://user-images.githubusercontent.com/5349876/205554353-2f39c963-60a9-46c1-a85e-6d73d31a484e.png)

![image](https://user-images.githubusercontent.com/5349876/205554525-85609b47-559e-427d-9ed6-0653699e92f7.png)

![image](https://user-images.githubusercontent.com/5349876/205554586-c4aa8b7f-6be1-498b-b1ef-879baf2cfed8.png)

