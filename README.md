# Data from: Energetics and fear of humans constrain the spatial ecology of pumas

This repository contains the data used for the following paper:

Energetics and fear of humans constrain the spatial ecology of pumas  
Barry A. Nickel, Justin P. Suraci, Anna C. Nisi, Christopher C. Wilmers  
Center for Integrated Spatial Research, Environmental Studies Department, University of California - Santa Cruz, Santa Cruz, CA, 95064, USA

Abstract: Energetic demands and fear of predators are considered primary factors shaping animal behavior, and both are likely drivers of movement decisions that ultimately determine the spatial ecology of wildlife.  Yet energetic constraints on movement imposed by the physical landscape have only been considered separately from those imposed by risk avoidance, limiting our understanding of how short-term movement decisions scale up to affect long-term space use.  Here, we integrate the costs of both physical terrain and predation risk into a common currency, energy, and then quantify their effects on the short-term movement and long-term spatial ecology of a large carnivore living in a human-dominated landscape.  Using high-resolution GPS and accelerometer data from collared pumas (Puma concolor), we calculated the short-term (i.e., five-minute) energetic costs of navigating both rugged physical terrain and a landscape of risk from humans (major sources of both mortality and fear for our study population).  Both the physical and risk landscapes affected puma short-term movement costs, with risk having a relatively greater impact by inducing high energy but low efficiency movement behavior.  The cumulative effects of short-term movement costs lead to reductions of 29-68% in daily travel distances and total home range area.  For male pumas, long-term patterns of space use were predominantly driven by the energetic costs of human-induced risk.  This work demonstrates that, along with physical terrain, predation risk plays a primary role in shaping an animal's "energy landscape" and suggests that fear of humans may be a major factor affecting wildlife movements worldwide.

Details of how these data were collected can be found in the Methods and Supplementary Materials of Nickel et al. 2021, Energetics and fear of humans constrain the spatial ecology of pumas (Proceedings of the National Academy of Sciences). A brief summary of each dataset follows:

puma-step-data-mmr.csv - Columns: id=animal id; sex=animal sex; log_mmr=mean metabolic rate; tpi=mean topographic position; vrm=mean topographic ruggedness; slope=mean local slope; housing=mean housing density; daynight=day(0) or night(1).

puma-step-data-lcot.csv - Columns: id=animal id; sex=animal sex; log_lcot=landscape cost of transport; tpi=mean topographic position; vrm=mean topographic ruggedness; slope=mean local slope; housing=mean housing density; daynight=day(0) or night(1).

puma-hr-data.csv - Columns: id=animal id; sex=animal sex; lcot=daily mean landscape cost of transport; distance=daily mean travel distance (km); hr=home range area (km^2); tpi=mean topographic position; vrm=mean topographic ruggedness; slope=mean local slope; housing=mean housing density.

