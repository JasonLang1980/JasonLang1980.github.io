{: .page-header} 
# Business tools for Engineers: Cost Benefit Analysis pt 2

![Which one?](./whichone.png)  

In the previous post, I explained how to build out the standard Cost Benefit Analysis for a single "widget". In this post, I will go into depth on how I compare two products against each other to choose the one I will be putting my support behind. 

In some cases, choosing a widget is clear cut. Cheaper overall cost or one has way more features and capabilities than any others available. Other times the clear winner is more difficult to spot. Lets compare two separate cost benefit analysis's for a moment: 

### **Widget 1:** 
> | Cost Element | Quantity | Amount per Item | Total | 
> | --- | --- | --- | --- | 
> | License | 1 | 2500 | 2500 | 
> | Data Transfer | 1 | 1.53 | 558.45 | 
> | Setup | 80 | 52 | 4160 | 
> | Upkeep | 104 | 52 | 5408 | 
> | --- | --- | --- | --- | 
> | Grand Total | | | 12626.45 | 
> {: .tablelines} 
> 
> * No more servers to maintain for the project
> * More storage at a cheaper cost
> * Better UI interface
> * Better Search capabilities
> * Machine Learning Assistance for anomaly detection
> * The Ability to build graphs from Log based data via common syntax
> * The Ability to Extend the interface with custom NodeJS additions using sdk 

### **Widget 2:** 
> | Cost Element | Quantity | Amount per Item | Total | 
> | --- | --- | --- | --- | 
> | License | 0 | 0 | 0 | 
> | Data Transfer | 1 | 1.53 | 558.45 | 
> | Setup | 80 | 52 | 4160 | 
> | Ongoing Server Costs | 2 | 1250 | 2500 |
> | Upkeep | 104 | 52 | 5408 | 
> | --- | --- | --- | --- | 
> | Grand Total | | | 12626.45 | 
> {: .tablelines} 
> 
> * Requires 2 servers and a database
> * Better UI interface
> * Open Source - Allows for customization and new features developed in house 
> * Machine Learning Assistance for anomaly detection
> * The Ability to build graphs from Log based data via common syntax
> * The Ability to Extend the interface with custom code.

In this case, the costs are the same, the features are also very similar. The choice becomes much more difficult to provide. 

Now comes the choice of **"What is best for the future of the Organization?"** So lets break down the questions that need answers before we can come to that final conclusion. 

**"What questions do I ask?"** It is important to ask the right questions if you want the result to be the best it can be. Lets take a list of the reasons we need to align the questions to. 
> 1. Future viability of the decision. IE: Will the widget still make sense in 5+ years, or even next year? 
> 1. Alignment with the future vision of the organization. IE: Is the widget something that will be used in the future or is it a "band-aid" to plug a problem right now rather than the permanent fix to it?
> 1. Build vs Buy. IE: Will someone else's widget fulfill the need or will our Organization be better served building our own solution so that it can be more aligned and upgradeable for future needs?
> 1. Finances. IE: If we buy the widget from another company, will we loose it in the future should we have to cut budget? 

Lets break down these reasons and delve deep into the business thoughts behind them so that as engineers, we can make a decision that will benefit the organization more closely in our choice.  

**Future viability.** This is something that will, quite frankly, be an opinion that differs from person to person. You are trying to guess weather the company that provides the widget will still be around in x+ years. You are also trying to guess as to the future states of your own organizations need for the widget lasting out that far. To make an informed choice here, make sure you are asking the right people in your organization their vision for the future of the organization. Understanding that is key. As to wether or not the company that provides widget, find out what other organizations are using it to get a ballpark idea of that aspect. Knowing who else uses a product will give you a better picture of their viability. For example, if google uses the product, what do you think the chances are that in a year or two google will be replacing the product with something developed in house to them. Where as if say several major insurance companies or finance organizations use it, there is a higher chance it will remain viable as these types or organization change their needs on that technology at a much slower rate.  

**Alignment with future vision.** As with future viability, to know this you need to align yourself with the vision of the organization or have a discussion with someone who is. If your organization is currently running everything in house, but has a 5 year plan to go global, buying a product that is only used on premise might not be the best option. Likewise, if your organization is currently using one cloud provider, but has plans to move to multiple cloud providers in the future, choosing a widget that locks you down to a single provider (vendor lock) is also not a good strategy.  

**Build vs buy.**  Touchy subject I know, but one that has to be broached for every widget we look at. This is the question that will have to be answered. With out example widgets, one requires us to put in a feature request and hope it gets picked up and implemented on the timeline our organization needs. While the other option allows us to build in our own new features and push them upstream to the open-source community at large for adoption. While it seems a no brain-er to some engineers that it's better to take the open-source solution and build on it, keep in mind the business has their own road-map of things, and this could clash. Talk to the business side and your management about the options carefully and provide your solid reasoning behind your choice.  

**Finances.** I mentally hear a groan from engineers around the world when I bring this up. It however is nonetheless a major deciding factor. And wether or not we want to admit it, engineer hours are a cost. It may be the same estimated cost either way, however there is always risk that if we go with our open-source widget, that we end up spending double or triple the engineer hours on improvements and upkeep that what we originally estimated. As such you will need to be able to present sound financial reasons why it is still best to go that route as opposed to the paid service. Likewise, if the company selling the paid service has a history of annual price increases, be prepared to justify continually paying those increases to keep the widget in service.

In summary, choosing the right widget for your organization will not be an easy decision. But with the knowledge above, I do hope I have better armed you for making that choice. As they say, knowledge is half the battle, so knowing what knowledge you need and how to get it provides you with the weapons you need and the ammo. Practicing these methods will give you the other half of the equation, the skill to stand before your leadership and speak with confidence as to what the best choices are and why.