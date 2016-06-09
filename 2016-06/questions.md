# Questions for participants

## Questions related to [Deliverable D2.3](https://seafile.idmt.de/seafhttp/files/23b6c4b0-7045-40da-8447-6b7029973e90/D2.3.pdf)

* The document mentions uncertainty on several occasions. What are some examples of uncertainties that you wish were possible
  to model in the DSL? (T4.2) - SM: there are many types of uncertainty that we can include, depending on the focus of the tool. For example, if planning in time is a focus, there is uncertainty about the timing of climate change impacts, as well as changing conditions in the city, such as socio-economic developments. If we do not look at time and stick only to spatial planning, there is uncertainty in the effects of different measures and what spatial needs will be in the future (e.g. do you develop a low-lying area or leave it as open space, when it is unknown whether its flood risk will increase under climate change)

* On page 16, under the "Data manipulation" column, it says:
  "Combining uncertainty ... with alternatives"
  Please elaborate on what the semantics of this combination are (T4.2, T4.3, T4.5) - SM: simply that there may be different types of uncertainties inherent in different alternatives and it would be useful for the tool to give an indication of what uncertainties they are accepting with different alternatives. This information could for example be used by decision makers to invest in research to reduce some uncertainties, or to pay more for an alternative that is more robust, etc.  

## Questions related to [Deliverable D2.2](https://seafile.idmt.de/seafhttp/files/57576c02-12ee-4484-b167-be22cabf7f46/D2.2.pdf)

* Page 8, bullet point 5, mentions setting up simulations to
  analyze alternatives. How do these simulations work? (T4.3, T4.5) - SM: there has been some confusion about this deliverable with people joining the project after the report was developed. The first two sections are not our proposal for GRACeFUL tools, but lay out the departure point from policy analysis and CRUD. The reason for covering this was to make our starting point and framing clear, but equally to communicate this to the other project partners, who are not familiar with the literature and practice in our field. Bullet point 5 refers to a generic policy analysis framework, so the simulations can be made accordingly. For our project, we imagine simulations will show some kind of effect of different alternatives, potentially for different future scenarios, so they can be compared.

## Questions on Causal Loop Diagrams (CLDs)

* What is an example of a minimal (no more than 4 nodes) CLD,
  and what are it's semantics (what would be the input parameters
  to a computer simulation modeling this CLD, how does the computer simulation
  work)? (T4.3, T4.5) - SM: this is a question for Linda.

* How important is time in modeling the behaviour of CLDs? (T4.3, T4.5) - SM: again, probably more appropriate for Linda, but it largely depends on how the tool is developed. If planning in time is a focus, then time will be very important (this is standard system dynamics modeling, if you are using pure CLDs). If planning in time is not a focus, then I think the CLDs will largely be used for system understanding/organization. Two notes though, first, for GRACeFUL the aim is to make "GRACeFUL Concept Maps" (or system diagrams) that include other relations than causal. Second, Linda can probably provide better response!

* Are actions subject to some temporal semantic. That is, should the system
  be able to model actions taken at varying times? (T4.3, T4.5) - SM: Again, it depends. It could be a very nice feature if we could plan actions in a timeline. That would be great! However, the functionalities of the tools should be in line with the type of decision making it is supporting. In preliminary design support (like the existing Adaptation Support Tool) time is nice, but not critical, because the discussion is really about priorities, values and possibilities. If the tool supports more strategic planning then the temporal semantic is critical. Personally, I favor the latter, but for various reasons, there is no consensus on this...  

## General questions on DSL-design

* Please rank the following by how important you think it is for the
  DSL to be able to model them: (T4.2) - SM: It really depends on the focus of the tool. I would say Action Application Options would be top in any scenario. Likewise I think Runoff flow networks would be low in any scenario. I am not sure what you mean by topo networks and geographic zones.
    * Causal Loop Diagrams
    * Geographic zones 
    * Topological networks
    * Runoff flow networks
    * Action application options 
