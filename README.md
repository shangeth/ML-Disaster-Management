# Machine Learning in Disaster Management
This project is a part of Microsoft's [Codefundo Hackathon](https://codefundo.io/index.html)<br>
<pre>
Team Member :
              Shangeth Rajaa
              shangethrajaa@gmail.com | +91 7218540834
</pre>

## Problem Statement
During a disaster, victims panic and call the emergency service thousands at a time. There are two problems in this, 
1. The person behind the emergency **call can handle only one call at a time**.
2. The **victims were served on the basis of First-Come-First-Serve** as the person can't analyse who needed the help most at the time of disaster.So sometimes **victims who needed the help most may not be served first**.


## Machine Learning as the Solution
Machines can do any tasks faster and can analyse more data than a single human can do. Combining clusters of Machines for specific tasks can do any task at an impossible rate for the humans.

This project is to **automate the process of getting the details of victims in help** using calls from the victims in help and using social media. 
Social Media (Twitter, Facebook, Whatsapp) is widely used everywhere for fast passing of information about the disaster than news. It can be used for Mitigation, Responce and Recovery of a Disaster.

[Social Media is Helping save the world](https://www.techradar.com/news/internet/dealing-with-disaster-how-social-media-is-helping-save-the-world-1203809)
<br>
[Social Meida in Disaster Communication](https://www.fema.gov/pdf/about/regions/regionviii/risc_0711.pdf)
<br>
[Social Media in Disaster Management](https://aisel.aisnet.org/cgi/viewcontent.cgi?article=1267&context=icis2011)


## The Idea
1. To use Automated Machines to attend the calls from the victims, to get all the possible details about the type of disaster, location, damange level, current situation, specific help needed(if any). The Intelligence will analyse the data recieved through the calls and decide the action.
2. Use Social Media to analyse posts like these and decide what kind of help will be needed, location, etc and decide the action.
![picture](https://cdn-images-1.medium.com/max/800/1*tdlHy-40-F8I7OqbxB9xKg.png)
![pic2](https://cdn-images-1.medium.com/max/800/1*3l2w34KZqHpP5T9RU5ryOA.png)
<br>Image credits : google images

## Why Ml over Humans?
1. During a disaster , the emergency services gets thousands of calls at a time. It may **not be possible to have that much human resources to attend all the calls**, But a machine can do multiple tasks at a time given the enough computation power and thus none of the victims have to wait for the call to connect as the **machine can attend all the calls at a time**. And the human resources can be used for some other relief actions.
2. Humans can only get the information on pass it to the relief team, But a ML can analyse the call with 1000s of other call instantly (with enough computation power) and decide or **prioritize who needs help the most** at that time. Previously emergency services helps victims by First Come First Serve basis, but people who need help the most may not be served first. So a ML can analyse the details of 1000s of calls and **decide who is in need the most and decide the action** map.
3. People asking **helps in social media can be served better using ML** , which can analsye the posts automatically and get he information from it and deicide the action. It can also analyse the comments to analyse if the problem is solved or if help is still needed. 

## Feasibility
1. The task is to make an Intelligence to attend calls and get details from the call , analyse it and decide the action. There is an option to include a real time speaking bot which can get the details as it speaks( with the technologies like google assistant, cortana, siri it is clear that this can be done) . But due to lack of much computation power and datas , this project will not include that in the first prototype , but will try to include the feature if possible later. Tech giants like Google, Microsoft, IBM have the resources and knowledge to implement this idea easily.
2. This service **can be used even in remote locations as no internet is needed to place a call to the emergency service**.
3. In contries like India, where people speak different languages in different places, there may be a problem as we may want the **Machine to understand and respond in the language spoken by the victim**, which is hard but doable. In this project , english is going to be the language of conversation, which can still be used by many parts of the world.


## The technical part
This project will need intensive Natural Language Processing ,data and computation power.<br>
Microsoft's Azure is going to be used for the computation part, and GitHub for the version control.
