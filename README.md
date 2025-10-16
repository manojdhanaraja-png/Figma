# Ex09 Event Registration Web Application
## Date:16.10.2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
```FIGMA

## CODE:
import React from "react";
import CREATE1 from "./CREATE-1.png";
import college1 from "./college-1.png";
import vector from "./vector.svg";

export const IphoneProMax = () => {
  return (
    <div className="bg-[#add8e6] w-full min-w-[534px] min-h-[1006px] relative">
      <img
        className="absolute top-[41px] left-[calc(50.00%_-_242px)] w-[483px] h-[118px] aspect-[4.1] object-cover"
        alt="College"
        src={college1}
      />

      <img
        className="absolute top-[703px] left-[calc(50.00%_-_152px)] w-[293px] h-[68px]"
        alt="Vector"
        src={vector}
      />

      <div className="absolute top-[803px] left-[calc(50.00%_-_147px)] w-[293px] h-[68px] bg-[#90ee90]" />

      <div className="absolute top-[811px] left-[184px] w-[266px] [font-family:'Inter-ExtraBold',Helvetica] font-extrabold text-black text-4xl tracking-[0] leading-[normal]">
        Register
      </div>

      <div className="absolute top-[718px] left-[212px] w-[173px] [font-family:'Inter-ExtraBold',Helvetica] font-extrabold text-black text-4xl tracking-[0] leading-[normal]">
        login
      </div>

      <div className="absolute top-[543px] left-[calc(50.00%_-_250px)] w-[500px] [font-family:'Inter-Italic',Helvetica] font-normal italic text-[#ff0000] text-[40px] tracking-[0] leading-[normal]">
        &nbsp;&nbsp;ART AND CRAFT EVENT
      </div>

      <img
        className="absolute top-[219px] left-[60px] w-[412px] h-[265px] aspect-[1.56] object-cover"
        alt="Create"
        src={CREATE1}
      />
    </div>
  );
};

import React from "react";
import ART1 from "./ART-1.png";

export const IphoneProMax = () => {
  return (
    <div className="bg-[#dda0dd] overflow-hidden w-full min-w-[957px] min-h-[1006px] relative">
      <div className="absolute top-8 left-[calc(50.00%_-_188px)] w-[535px] [font-family:'Inter-ExtraBold',Helvetica] font-extrabold text-black text-8xl tracking-[0] leading-[normal]">
        EVENTS
      </div>

      <img
        className="absolute top-[183px] left-[calc(50.00%_-_300px)] w-[583px] h-[583px] aspect-[1] object-cover"
        alt="Art"
        src={ART1}
      />

      <p className="absolute top-[783px] left-[calc(50.00%_-_260px)] w-[1506px] [font-family:'Inter-ExtraBold',Helvetica] font-extrabold text-transparent text-5xl tracking-[0] leading-[normal]">
        <span className="[font-family:'Inter-ExtraBold_Italic',Helvetica] italic text-black">
          &nbsp;&nbsp;&nbsp;&nbsp;
        </span>

        <span className="[font-family:'Inter-ExtraBold_Italic',Helvetica] italic text-[#ff0000]">
          “Art is not a thing,
          <br />
          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;it
          is a way.”
        </span>
      </p>
    </div>
  );
};

```
## OUTPUT:
![alt text](<Screenshot 2025-10-09 112813.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
