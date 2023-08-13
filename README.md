# Camping-gear-webpage

Hosted Link:- https://lok-ii.github.io/Camping-gear-webpage/


![Screenshot 2023-08-13 152429](https://github.com/Lok-ii/Camping-gear-webpage/assets/129180844/541da929-febb-41c7-83c4-e9ff37c0b2ad)
    
    This is header section of the webpage that typically contains navigation and branding elements.
    This section was created using Header <header> tag, it represents the header section of the webpage. This header tag contains a <nav> tag which denotes the navigation bar. The navigation bar contains links to various sections of the webpage.
    
    <h2><a href="#home">LOGO</a></h2>: An <h2> heading containing a link with the text "LOGO".
    
    <div class="navbar">: A <div> element that wraps the navigation links. It contains the navigations links to the different parts of the webpage.

    CSS properties used in the header section:-

        CSS Properties for <nav>:

            position: fixed;: Positions the navigation bar as fixed so that it remains visible while scrolling.
            display: flex;: Uses the flexbox layout to arrange the navigation items horizontally.
            justify-content: center;: Centers the navigation items horizontally within the navigation bar.
            background-color: #333232;: Sets the background color of the navigation bar to a dark shade.
            width: 100%;: Makes the navigation bar span the entire width of its containing element.
            z-index: 6;: Specifies the stacking order of elements. This ensures the navigation bar is placed above other content.

        CSS Properties for <h2>:

            margin: 0;: Removes any default margin around the heading.
            line-height: 1;: Sets the line height to 1, ensuring the logo stays vertically centered.
            font-size: inherit;: Inherits the font size from its parent element.
        
        CSS Properties for <a> (Navigation Links):
            
            color: white;: Sets the text color of the navigation links to white.
            text-decoration: none;: Removes the default underlines from the navigation links.
            padding: 15px;: Adds padding around the navigation links to create space.
            font-size: 18px;: Sets the font size of the navigation links.
        
        CSS Properties for .navbar (Navigation Links Container):
            
            display: flex;: Uses the flexbox layout to arrange the navigation links in a row.
            gap: 40px;: Sets the gap (spacing) between each navigation link.
            align-items: center;: Centers the navigation links vertically within the container.



![Screenshot 2023-08-13 152440](https://github.com/Lok-ii/Camping-gear-webpage/assets/129180844/0a1ea64a-10b0-4df2-9e44-31054cda09f6)

    From this section starts the main content of the webpage. The main content is created inside the <main> tag.
    All the other important tags are used inside the main tag for various sections.
    Home Section (<section>, .home, .details, <h1>, <p>, <a>):

    The home section introduces the main content of the webpage.
    
    <section class="home" id="home">: Represents the home section of the webpage and includes the home class and id attribute.
    
    <div class="details">: A container for the main content of the home section.
    
    <h1>Camping Gear and Essentials</h1>: A heading that introduces the theme of the webpage.
    
    <p>: A paragraph that provides a brief description of the camping gear and its benefits.
    
    <a href="#services">OUR SERVICES</a>: A call-to-action link that directs users to the "services" section of the webpage.
    
    CSS Properties for .home (Home Section):
    
        background-image: Sets the background image of the home section.
        height: Defines the height of the home section.
        width: Defines the width of the home section.
        background-position: Sets the positioning of the background image.
        background-size: Specifies how the background image should be sized.
        background-attachment: Controls whether the background image scrolls with the content or remains fixed.
    
    CSS Properties for .details (Home Content Container):
    
        background-color: Sets the background color of the content container.
        height: Defines the height of the content container.
        text-align: Sets the alignment of the text within the container.
        padding-top: Adds padding to the top of the container to create spacing.
        color: Sets the text color within the container.
        text-shadow: Adds a subtle shadow effect to the text.
        
    CSS Properties for <h1> (Main Heading):
    
        font-size: Specifies the font size of the main heading.
        margin-bottom: Adds margin at the bottom of the heading to create spacing.
        
    CSS Properties for <p> (Paragraph):
    
        font-size: Specifies the font size of the paragraph.
        margin-bottom: Adds margin at the bottom of the paragraph to create spacing.
    
    CSS Properties for <a> (Call-to-Action Link):
    
        margin: Adds margin around the link to create spacing.
        padding: Adds padding around the link for better visual appearance.
        background-color: Sets the background color of the link.
        color: Sets the text color of the link.
        border: Adds a border to the link for visual distinction.
        border-radius: Adds rounded corners to the link.
        font-size: Specifies the font size of the link.
        box-shadow: Adds a subtle shadow effect to the link.

![Screenshot 2023-08-13 152454](https://github.com/Lok-ii/Camping-gear-webpage/assets/129180844/6e42ece1-b2f1-4e6e-ab70-3a6a9d34f329)
![Screenshot 2023-08-13 152504](https://github.com/Lok-ii/Camping-gear-webpage/assets/129180844/3326e05e-c979-4a8b-8878-e4de99b15513)

    This section highlights various camping gear services. It was created using a <section> tag and some other child elements were also used. Let me explain it in detail:

    <section class="services" id="services">: Represents the services section and includes the services class and id attribute.

    <h1>Our Services</h1>: A heading that introduces the services section.
    
    <p>: A paragraph that provides a brief description of the camping gear services.
    
    <div class="servicelist">: A container for displaying the list of services.
    
    <div class="list">: Represents an individual service list item.
    
    <img>: Displays an image associated with the service.
    
    <h3>: Represents the title of the service.
    
    <p>: Provides a description of the service.

        CSS Properties for .services (Services Section):

            height: Defines the height of the services section.
            text-align: Sets the alignment of the text within the section.
            padding-top: Adds padding to the top of the section to create spacing.
            
        CSS Properties for .servicelist (Services List Container):
            
            display: Uses the flexbox layout to arrange the service items.
            justify-content: Sets the alignment of service items horizontally.
            
        CSS Properties for .list (Service List Item):
            
            display: Uses the flexbox layout to arrange content vertically.
            flex-direction: Specifies the direction of the flex items.
            align-items: Aligns items within the container.
            
        CSS Properties for <img> (Service Image):
            
            margin-top: Adds margin at the top of the image to create spacing.
            margin-bottom: Adds margin at the bottom of the image to create spacing.
            width: Specifies the width of the image.
            height: Specifies the height of the image.
            object-fit: Controls how the image fits within its container.
            border-radius: Adds rounded corners to the image.
            
        CSS Properties for <h3> (Service Title):
            
            margin-top: Adds margin at the top of the title for spacing.
            
        CSS Properties for <p> (Service Description):
            
            width: Sets the width of the description for proper alignment.



![Screenshot 2023-08-13 152518](https://github.com/Lok-ii/Camping-gear-webpage/assets/129180844/9c85a476-bbe0-458d-9f7f-8784b2eeda50)

    The About Us section provides information about the company's story, mission, vision, and team.

         About Us Section (<section>, .about_us, .goals, <h3>, <p>, <ul>, <li>):
        
        <section class="about_us" id="about_us">: Represents the About Us section with the about_us class and id attribute.
        
        <h1>About Us</h1>: A heading introducing the About Us section.
        
        <p>: A paragraph providing a brief overview of the company.
        
        <div class="goals">: A container for the company's story, mission, vision, and team information.
        
        <h3>: Headings for different sections within the goals container.
        
        <p>: Paragraphs providing details for each section.
        
        <ul>: An unordered list for listing team members.
        
        <li>: List items representing individual team members.
        
        CSS Properties for .about_us (About Us Section):
        
            height: Defines the height of the About Us section.
            text-align: Sets the alignment of the text within the section.
            margin: Adds margin for proper spacing.
        
        CSS Properties for .goals (Goals Container):
        
            padding: Adds padding around the container for spacing.
            text-align: Aligns the text within the container.
        
        CSS Properties for <h3> (Section Headings):
        
            margin: Adds margin for proper spacing.
        
        CSS Properties for <p> (Section Paragraphs):
        
            margin-bottom: Adds margin at the bottom of paragraphs for spacing.
        
        CSS Properties for <ul> (Unordered List):
        
            padding-left: Adds left padding to the list for better indentation.
        
        CSS Properties for <li> (List Items):
        
            padding-left: Adds left padding to list items for better indentation.

![Screenshot 2023-08-13 152524](https://github.com/Lok-ii/Camping-gear-webpage/assets/129180844/cae03ab1-bb61-4a24-8b8f-b25d01de9454)

    The Contact Us section provides contact information and a contact form.

    Contact Us Section (<footer>, .contact_us, .contact, .address, .eachdetail, .material-icons, .fulldetails, form, input, textarea):
    
    <footer class="contact_us" id="contact_us">: Represents the Contact Us section with the contact_us class and id attribute.
    
    <h1>Contact Us</h1>: A heading introducing the Contact Us section.
    
    <p>: A paragraph providing a brief overview of contacting the company.
    
    <div class="contact">: A container for contact information and the contact form.
    
    <div class="address">: A container for displaying address details.
    
    <div class="eachdetail">: A container for each address detail.
    
    <span class="material-icons">: Utilizes Material Icons for icons.
    
    .fulldetails: A class for styling full contact details.
    
    <form>: A form element for user input.
    
    <input>: Input fields for name and email.
    
    <textarea>: A textarea for entering a message.
    
        CSS Properties for .contact_us (Contact Us Section):
            
            height: Defines the height of the Contact Us section.
            text-align: Sets the alignment of the text within the section.
            margin: Adds margin for proper spacing.
            max-width: Sets the maximum width of the section for responsive design.
            
        CSS Properties for .contact (Contact Container):
            
            display: Utilizes flex layout for arranging contact details and form.
            justify-content: Aligns items horizontally within the container.
            width: Sets the width of the container to 100%.
            
        CSS Properties for .address (Address Container):
            
            display: Uses flex layout for arranging address details vertically.
            align-items: Aligns items vertically within the container.
            gap: Adds space between each address detail.
            
        CSS Properties for .eachdetail (Each Address Detail):
            
            display: Utilizes flex layout for arranging icon and text.
            align-items: Aligns items vertically within the container.
            gap: Adds space between the icon and text.
            
        CSS Properties for .material-icons (Material Icons):
            
            color: Sets the color of the Material Icons.
            
        CSS Properties for .fulldetails (Full Contact Details):
            
            margin-bottom: Adds margin at the bottom of each contact detail.
            
        CSS Properties for form (Contact Form):
            
            display: Utilizes flex layout for arranging form elements vertically.
            flex-direction: Sets the direction of the flex items.
            font-family: Specifies the font family for the form.
            width: Sets the width of the form.
            
        CSS Properties for input (Input Fields):
            
            width: Sets the width of input fields.
            height: Sets the height of input fields.
            padding: Adds padding within the input fields.
            font-size: Specifies the font size of input text.
            border: Adds a border around input fields.
            outline: Removes the default outline of input fields.
            
        CSS Properties for textarea (Textarea):
            
            width: Sets the width of the textarea.
            padding: Adds padding within the textarea.
            font-size: Specifies the font size of textarea text.
            border: Adds a border around the textarea.
            outline: Removes the default outline of the textarea.
            
        CSS Properties for #submit (Submit Button):
            
            background-color: Sets the background color of the button.
            color: Sets the text color of the button.
            width: Sets the width of the button.
            height: Sets the height of the button.
            border-radius: Adds rounded corners to the button.
            cursor: Changes the cursor to a pointer on hover.
            
        CSS Properties for #submit:hover (Submit Button on Hover):
            
            Adjusts the background color of the button on hover.
