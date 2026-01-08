# BrainLife Usage Statistics Dashboard

## 3.1 Goal 
- The overall goal of this project is to use BrainLife (BL) usage statistics to create plots and display them on the BL platform.
- Individual goals:  
 - Learn to use Tableau software for visualizing data
 - Create plots and dashboards for displaying BrainLife statistics
 - Connect the dashboards to BrainLife so that they are displayed on the website and automatically update based on current data

## 3.2 Methods 
- Before a dashboard can be constructed, each plot must be individually created based on a single dataset.
- Overall, 6 datasets were used to construct the dashboards.
  - The total_jobs_walltime dataset contains the amount of walltime used and jobs run per month since BrainLife started. It was used to construct 2 line graphs, one  representing the cumulative walltime used since the start of BrainLife and the other representing the cumultive job count since the start of BrainLife.
  - The jobs_walltime_per_app dataset contains the job count and walltime used per month, per app. It was used to construct 2 multiple lines graphs, one showing the cumulative walltime and the other showing cumulative job count, both separated by app. These plots allow us to determine the apps which were used most frequently, per month.
  - The jobs_walltime_per_user dataset contains the job count and walltime used per month, per user. It was used to construct 2 multiple lines graphs, one showing the cumulative walltime and the other showing cumulative job count, both separated by user. These plots allow us to determine the users which used the most walltime and ran the most jobs per month.
  - The jobs_walltime_per_resource dataset contains the job count and walltime used per month, per resource. It was used to construct 2 multiple lines graphs, one showing the cumulative walltime and the other showing cumulative job count, both separated by resource. These plots allow us to determine the resources which used the most walltime and ran the most jobs per month.
  - The jobs_walltime_per_project dataset contains the job count and walltime used per month, per project. It was used to construct 2 multiple lines graphs, one showing the cumulative walltime and the other showing cumulative job count, both separated by project. These plots allow us to determine the projects which used the most walltime and ran the most jobs per month.
  - The active_users_count_walltime dataset contains information the count of active users per month, as well as the jobs run and walltime used. It was used to constuct a line graph showing the amount of active users on BL per month.

## 3.3 Results 
- Once all of the individual plots were created, I combined them into a 3 dashboards based on their content.
- Figure 18 is intended to be the main page users are directed to when viewing BL statistics. It contains the trends of cumulative walltime, job count, and object count, as well as the total number of active users over time.

![image](https://github.com/catherinealeal/WhiteMatterTracking/assets/100166102/0bd6b71d-07e2-41ec-b5fd-253180274943)
Figure 18. The main page showing overall cumulative statistics, including walltime, object count, job count, and user count.

- These plots show that the overall usage of BL to run jobs and produce objects has increased over time. The active users plot also shows that the number of BL users has generally increased over time, with some month-to-month flucuations.
- Figure 19 is a dashboard containing data on cumulative walltime broken down by user, project, app, and resource.
- These plots allow us to see how walltime is broken down by many factors and which specific app or resource is most used.

![image](https://github.com/catherinealeal/WhiteMatterTracking/assets/100166102/513b0d5c-7f4a-435f-8460-a306f4aa7c19)
Figure 19. Walltime broken down by project, user, resource, and app.

- Figure 20 is a dashboard representing trends of cumulative job counts broken down by project, user, resource, and app.
- These plots allow us to see how job count is broken down by many factors and which specific app or resource ran the most jobs.

![image](https://github.com/catherinealeal/WhiteMatterTracking/assets/100166102/1ac38e5b-691e-4315-9f57-75267be2662e)
Figure 20. Jobs broken down by project, user, resource, and app.

## 3.4 Future Direction 
- These dashboards will allow Brainlife administrators and users to explore the usage of the BL platform over time.
- Now that the dashboards are created in Tableau, they need to be linked to the Brainlife website so that any BL user can see these visualizations.
- The datasets also need to be linked to current BL data so that the charts update automatically based on current data.

# Works Cited 
- Aydogan, Dogu Baran, and Yonggang Shi. 2021. “Parallel Transport Tractography.” IEEE Transactions on Medical Imaging 40 (2): 635.
- Çiçek, Özgün, Ahmed Abdulkadir, Soeren S. Lienkamp, Thomas Brox, and Olaf Ronneberger. 2016. “3D U-Net: Learning Dense Volumetric Segmentation from Sparse Annotation.” Medical Image Computing and Computer-Assisted Intervention: MICCAI ... International Conference on Medical Image Computing and Computer-Assisted Intervention, 424–32.
- Garyfallidis, Eleftherios, Matthew Brett, Marta Morgado Correia, Guy B. Williams, and Ian Nimmo-Smith. 2012. “QuickBundles, a Method for Tractography Simplification.” Frontiers in Neuroscience 6.
- Jeurissen, Ben, Maxime Descoteaux, Susumu Mori, and Alexander Leemans. 2019. “Diffusion MRI Fiber Tractography of the Brain.” NMR in Biomedicine 32 (4): e3785.
- Takemura, Hiromasa, Cesar F. Caiafa, Brian A. Wandell, and Franco Pestilli. 2016. “Ensemble Tractography.” PLoS Computational Biology 12 (2): e1004692.
- Takemura, Hiromasa, Franco Pestilli, Kevin S. Weiner, Georgios A. Keliris, Sofia M. Landi, Julia Sliwa, Frank Q. Ye, et al. 2017. “Occipital White Matter Tracts in Human and Macaque.” Cerebral Cortex  27 (6): 3346–59.
- Tournier, J-Donald, Fernando Calamante, and Alan Connelly. 2012. “MRtrix: Diffusion Tractography in Crossing Fiber Regions.” International Journal of Imaging Systems and Technology 22 (1): 53–66.
- “TractSeg - Fast and Accurate White Matter Tract Segmentation.” 2018. NeuroImage 183 (December): 239–53.

## View full notebook [here](https://github.com/catherinealeal/WhiteMatterTracking/blob/main/InternshipReport.ipynb)
