# Bus Company Quotation Form
---
## Basic Structure
1. Home Page
2. Quotation Page
3. Contact Us Page

## Sections Maintained

* Header (Navigation and Logo)
* Newsletter
* Footer

## Home Page

The home page contains the basic details of the company. These include:
 * About
 * Company Mission
 * Company vision
 * Newsletter subscription section
 * Showcase Cover
 * Testimonial Section
 * Footer

## Quotation Page

The quotation page contains a form which allows page visitors to insert booking details for a bus. The form was seperated into different sections. 

### The table below shows the form sections and inputs that are in the sections
| Section | Inputs |
| ----------- | ----------- |
| Company Details | Company Name input box |
|  | Company Registration Number |
|  | Tax Number |
| Contact Details | Contact Name |
|  | Contact Surname |
|  | Contact Email |
|  | Contact Number |
| Trip Details | First Pickup Date |
|  | Second Pickup date |
|  | Pickup Time |
|  | Pickup Address |
|  | Drop-off Address |
| Bus Details | Bus Seats (e.g 30 seater) |
| Submit | Generate Quotation Button |

## Contact Us Page

The contact us page comprises of a form that allows users to insert their details and submit for them to be contacted.

The following are the inputs contained in the contact us form:
* Contact Name
* Contact Surname
* Contact Email Address
* Contact Number
* Text Area

## Hardest Sections & Lessons Learnt

The navbar was particularly difficult because i had not leartn flexbox yet therefore i relied on floats to move my navigation content. This seemed like a good resolution until the navigation links started getting kicked out of the header section. A fix to this was to make sure the nav links were structured before the logo in html. 

The following code shows html code of how i did it:
```
        <header>
            <div class="container">
                <nav class="navigation">
                    <ul>
                        <li class="currentPage"><a href="index.html">Home</a></li>
                        <li><a href="quotation.html">Quotation</a></li>
                        <li><a href="schedule.html">Schedule</a></li>
                    </ul>
                </nav>
                <div id="logo">
                    <h1>Buscorp</h1>
                </div>
            </div>
        </header>
```

#### Working Solution

The above solution was only temporary and it didn't work as well as i wanted it to so i went on to learn flexbox so i can find a fix for it. The best solution was found on [THIS](https://www.youtube.com/watch?v=PwWHL3RyQgk&t=494s) video. 

The following html code shows how i ended up fixing the navbar:
```
      <header>
            <a href="index.html"><h1 id="logo">S-Transit</h1></a>
            <nav class="navigation">
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li class="currentPage"><a href="quotation.html">Quotation</a></li>
                    <li><a href="schedule.html">Schedule</a></li>
                </ul>
            </nav>   
            <a class="contactButton" href="contact.html"><button>Contact Us</button></a>        
      </header>  
```

As you can see, the logo is now about the navigation links.

## Additional Challenges

Styling the forms has been very difficult because i had recently started learning flex. Therefore it took me long to learn the parent-child method in flex. I am still not an expert at flex, however, i can execute flex better than i did in this project. I will not try to fix or change the way i solved it in this project. The reason being i would like to look back at this code one day and see the growth i had.

## Final thoughts

This project was not easy at all and the longer i worked on it, the more it took out of me. I started strong and i burnt out 80% through. With that being said, it has also been my favourite project so far because i did not rely fully on tutorials to complete it. I only used tutorials to understand smaller concepts and not full sections. 

> *"If four things are followed - having a great aim, acquiring knowledge, hard work, and perseverance - then anything can be achieved."* - ***A.P.J Abdul Kalam***
