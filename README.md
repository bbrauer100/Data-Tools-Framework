# Data-Tools-Framework
This repository contains documents and other artifacts that explain Microsoft's Data Tools Framework that encompasses platform tools and technologies, ecosystem partner products and solutions, and system integrator services.


Landscape and Ecosystem of Microsoft’s Data Tools
April 24, 2018

Summary:
Partners and customers have been confused by Microsoft’s Data Tools strategy, as there hasn’t been an explicit framework describing free platform tools that Microsoft would build and others that partners would build as extensions or complete solutions.  This confusion has led to lost revenue opportunity and wasted investments on behalf of the partners, Microsoft and their joint customers.
Microsoft and its closest data tools partners need a standard taxonomy and framework to collaborate on product positioning, roadmaps, and GTM initiatives.  This paper is a proposal derived from joint collaboration among Microsoft and its partners to create this necessary framework.

The premise of the framework is a maturity model similar to ITIL, in that it describes levels of organizational maturity within customer environments and recommended tools and technologies that support those levels of maturity.  The paper also delves into the tools and processes leveraged by “Dev + Ops” movement, and ties into Microsoft’s overall DevOps vision and the notion that ITIL and DevOps both rely heavily on IT process standardization and automation.  Microsoft has developed a broad vision for its Dev+Ops strategy that includes developing simple, reliable solutions that can be used for any type of application on any stack.  The primary objective is allow enterprises to reach the ultimate goal of deploying a standardized set of ALM processes across the entire organization.  Plus, both Microsoft and ITIL/ALM have similar objectives for its users: 
•	Increase the speed of workflow completion 
•	Reduce errors 
•	Increase service reliability 
•	Assure process integrity 
•	Make infrastructure and operations (I&O) more cost-efficient 
•	Help ensure organizations are compliant with security and other compliance requirements 
•	Provide services that cannot be delivered manually
Focusing now on automating database administration and management makes sense, because it’s not well defined but our customers need solutions to incorporate into their overall DevOps initiatives.  Many customers are at varying levels of sophistication when it comes to adopting DevOps, especially when it comes to their data platforms.  By building tools that fit without holes or overlap will Microsoft’s ecosystem of data tools partners optimize value to their customers and ultimately serve Microsoft’s data platform businesses.
According to Gartner, DevOps toolchains will become critical to successful adoption of DevOps.  Current offerings for different phases of the lifecycle come from various vendors and typically do not integrate well.  Given that data tools are not typically integrated into the DevOps toolchains anyway, issues resulting from poor integration will dramatically impair adoption and introduce unnecessary risk into the application lifecycle.  
Gartner recommends customers understand each DevOps area of activity and how each tool supports others to ensure they provide the required interoperability to support tool-to-tool integration and toolchain automation. There is no single vendor that can provide holistic tool coverage to address all the needs in a DevOps pipeline and most organizations will require more than one toolchain to cover their needs (e.g., legacy applications, cloud applications, mobile applications, package applications).
However, tools do not create DevOps. They can enable automation and new practices, but the practices and culture of an organization must change for DevOps to have a positive effect.  Therefore we think it is critical to incorporate maturity levels in a similar fashion as ITIL has done.

Framework Overview
The framework consists of two dimensions that crisscross, forming the shape of a two dimensional matrix.  These two dimensions are critical capabilities and levels of an organization’s sophistication within each critical capability.  
  
DevOps sophistication relates to the level of knowledge and implementation of DevOps practices for database development and updates.  Organizations that have just started implemented DevOps and have relatively mundane use cases will be categorized into the lowest level, while highly sophisticated organizations will have deployed DevOps practices across their entire org in a standardized manner using source code management tools and DevOps Toolchains (according to Gartner’s Hype Cycle).  The middle ban will be in a state of transition, where some teams will have indoctrinated DevOps while others are still following waterfall approaches to application development, deployment and operations.
The chart below describes three different dimensions that frame the positioning of data tools provided by Microsoft and its partners.  “Level of Sophistication” refers to an organization’s current state of DevOps adoption at the time of tools evaluation.  The more sophisticated the organization’s DevOps environment, the more likely they are going to choose customized solutions.  The rationale behind this assumption is that DevOps can have standard practices but have highly customized implementations based on an organization’s specific needs.  
 

There are many categories and subcategories related to DevOps, but the primary ones related to DevOps for databases are “Database Updates”, “Monitoring/Admin”, and “Reporting/Compliance”.  These categories are based on customer research and partner discussions.  The chosen tools and technologies are illustrative examples per category and level.  These too have been vetted by research and partners.
The “Domain” refers to a general category in which tools will be offered to organizations.  Tools provided by the platform are considered commodity with little differentiated value beyond the platform.  Organizations just starting out with DevOps will most likely choose these tools, as they will not be interested in paying a premium until they get a better grasp on their processes and procedures.  Customers who have already developed DevOps practices will either choose value-added offerings that extend the platform tools or customized solutions that are specific to their needs, depending on their level of organization’s sophistication.  Those who have smaller environments will most likely choose value-added offerings, as they will not need (or want to pay for) custom and/or highly integrated offerings from an SI or boutique ISV.

MS bases its investments on the following principles:
-	 Commitment to cross-platform, OSS components
-	 Providing commodity building blocks to enable a cohesive ecosystem
-	 Providing rich experiences for key devops experiences
-	Relying on partners for enterprise systems integration and deep value-add solutions

We plan to define many of these dimensions with detailed scenarios backed by survey data furnished by RedGate and new qualified research from in-depth interviews of DevOps specialists.  The following questions will be addressed in this research:
Tell the story of DB development-deployment 
•	How does a change start and make it out to production?  Describe your cycle. (ie: one application cycle, where business/application requirements start the cycle and leads through the dev/test/deploy process and ‘ends’ in production users using it) 
o	How does database development fit in with other development they do? Is this how they want it to be?
o	What is the artifact you’re working on when making a database change?
•	How often do they deploy to production?
•	What problems is the current process guarding against? 
•	How long does your cycle take? 
•	Who is involved? (What skills are needed at each stage?) 
•	Is this standard across teams?  If not, why not?  How did you make it standard? How do you ensure compliance?
•	Is this cycle good enough? (i.e. what would be the business significance of the process being faster or easier) 
•	If so, will this process still be good in 5 years time? Why/Why not? What needs to evolve?
Could they describe what ‘great’ would look like for:
•	Development?
•	Collaboration?  (identify patterns that work ‘well’ versus those that need ‘help’)
•	Deployment?
•	Monitoring?

