# Date:25-11-2024
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
```
#1st page
        <div class="i-phone-13-14-1">
          <img class="saveetha-logo-1" src="saveetha-logo-10.png" />
          <img class="rectangle-1" src="rectangle-10.svg" />
          <div class="ellipse-1"></div>
          <div class="id-8">id8</div>
          <div class="welcome-to-id-8-event">
            <span>
              <span class="welcome-to-id-8-event-span">Welcome to</span>
              <span class="welcome-to-id-8-event-span2">id8 Event</span>
            </span>
          </div>
          <div class="create-an-account-with-us-enjoy-all-exciting-event">
            Create an account with us &amp; enjoy all
            <br />
            exciting event
          </div>
          <div class="full-name">Full Name</div>
          <img class="rectangle-2" src="rectangle-20.svg" />
          <div class="e-mail">E-mail</div>
          <div class="rectangle-3"></div>
          <div class="date-of-birth">Date of Birth</div>
          <div class="rectangle-4"></div>
          <div class="phone-number">Phone Number</div>
          <div class="rectangle-5"></div>
          <div class="college-name">College name</div>
          <div class="rectangle-6"></div>
          <div
            class="by-creating-your-account-you-can-confirm-that-you-accept-our-terms-of-use-privacy-policy"
          >
            <span>
              <span
                class="by-creating-your-account-you-can-confirm-that-you-accept-our-terms-of-use-privacy-policy-span"
              >
                By creating your account you can confirm
                <br />
                that you accept
              </span>
              <span
                class="by-creating-your-account-you-can-confirm-that-you-accept-our-terms-of-use-privacy-policy-span2"
              >
                our Terms of Use
              </span>
              <span
                class="by-creating-your-account-you-can-confirm-that-you-accept-our-terms-of-use-privacy-policy-span3"
              >
                &amp;
              </span>
              <span
                class="by-creating-your-account-you-can-confirm-that-you-accept-our-terms-of-use-privacy-policy-span4"
              >
                Privacy policy
              </span>
              <span
                class="by-creating-your-account-you-can-confirm-that-you-accept-our-terms-of-use-privacy-policy-span5"
              ></span>
            </span>
          </div>
          <img class="rectangle-7" src="rectangle-70.svg" />
          <div class="create-account">create Account</div>
          <div class="have-an-account-sign-in">
            <span>
              <span class="have-an-account-sign-in-span">Have an Account?</span>
              <span class="have-an-account-sign-in-span2">Sign in</span>
            </span>
          </div>
        </div>
        
        .i-phone-13-14-1,
        .i-phone-13-14-1 * {
          box-sizing: border-box;
        }
        .i-phone-13-14-1 {
          background: #fffef5;
          border-radius: 20px;
          height: 853px;
          position: relative;
          overflow: hidden;
        }
        .saveetha-logo-1 {
          border-radius: 5px;
          width: 387px;
          height: 58px;
          position: absolute;
          left: 0px;
          top: 35px;
          object-fit: cover;
        }
        .rectangle-1 {
          border-radius: 0px;
          width: 312px;
          height: 173px;
          position: absolute;
          left: 39px;
          top: 133px;
          overflow: visible;
        }
        .ellipse-1 {
          background: #b3b0b0;
          border-radius: 50%;
          width: 68px;
          height: 63px;
          position: absolute;
          left: 158px;
          top: 145px;
        }
        .id-8 {
          color: #000000;
          text-align: left;
          font-family: "Inter-Bold", sans-serif;
          font-size: 16px;
          font-weight: 700;
          position: absolute;
          left: 182px;
          top: 165px;
          width: 26px;
          height: 27px;
        }
        .welcome-to-id-8-event {
          text-align: left;
          font-family: "Inter-Bold", sans-serif;
          font-size: 20px;
          font-weight: 700;
          position: absolute;
          left: 50%;
          translate: -50%;
          top: 214px;
          width: 237px;
          height: 32px;
        }
        .welcome-to-id-8-event-span {
          color: #000000;
          font-family: "Inter-Bold", sans-serif;
          font-size: 20px;
          font-weight: 700;
        }
        .welcome-to-id-8-event-span2 {
          color: #ef8114;
          font-family: "Inter-Bold", sans-serif;
          font-size: 20px;
          font-weight: 700;
        }
        .create-an-account-with-us-enjoy-all-exciting-event {
          color: #9d9c9a;
          text-align: left;
          font-family: "Inter-Italic", sans-serif;
          font-size: 14px;
          font-weight: 400;
          font-style: italic;
          position: absolute;
          left: 66px;
          top: 246px;
          width: 251px;
          height: 38px;
        }
        .full-name {
          color: #b3b0b0;
          text-align: left;
          font-family: "Inter-Bold", sans-serif;
          font-size: 14px;
          font-weight: 700;
          position: absolute;
          left: 48px;
          top: 327px;
          width: 84px;
          height: 25px;
        }
        .rectangle-2 {
          border-radius: 0px;
          width: 312px;
          height: 50px;
          position: absolute;
          right: 30px;
          bottom: 441px;
          overflow: visible;
        }
        .e-mail {
          color: #b4afaf;
          text-align: left;
          font-family: "Inter-Bold", sans-serif;
          font-size: 16px;
          font-weight: 700;
          position: absolute;
          left: 48px;
          top: 422px;
          width: 88px;
          height: 25px;
        }
        .rectangle-3 {
          background: #d9d9d9;
          border-radius: 20px;
          width: 311px;
          height: 45px;
          position: absolute;
          left: 40px;
          top: 454px;
        }
        .date-of-birth {
          color: #a8a4a4;
          text-align: left;
          font-family: "Inter-Bold", sans-serif;
          font-size: 15px;
          font-weight: 700;
          position: absolute;
          left: 39px;
          top: 520px;
          width: 127px;
          height: 33px;
        }
        .rectangle-4 {
          background: #d9d9d9;
          border-radius: 20px;
          width: 135px;
          height: 45px;
          position: absolute;
          left: 40px;
          top: 549px;
        }
        .phone-number {
          color: #a8a6a6;
          text-align: left;
          font-family: "Inter-Bold", sans-serif;
          font-size: 15px;
          font-weight: 700;
          position: absolute;
          left: 227px;
          top: 520px;
          width: 124px;
          height: 31px;
        }
        .rectangle-5 {
          background: #d9d9d9;
          border-radius: 20px;
          width: 140px;
          height: 45px;
          position: absolute;
          left: 211px;
          top: 549px;
        }
        .college-name {
          color: #a6a3a3;
          text-align: left;
          font-family: "Inter-Bold", sans-serif;
          font-size: 15px;
          font-weight: 700;
          position: absolute;
          left: 44px;
          top: 609px;
          width: 114px;
          height: 28px;
        }
        .rectangle-6 {
          background: #d9d9d9;
          border-radius: 20px;
          width: 311px;
          height: 49px;
          position: absolute;
          left: 40px;
          top: 637px;
        }
        .by-creating-your-account-you-can-confirm-that-you-accept-our-terms-of-use-privacy-policy {
          text-align: left;
          font-family: "Inter-Medium", sans-serif;
          font-size: 14px;
          font-weight: 500;
          position: absolute;
          left: 40px;
          top: 698px;
          width: 311px;
          height: 52px;
        }
        .by-creating-your-account-you-can-confirm-that-you-accept-our-terms-of-use-privacy-policy-span {
          color: #a5a3a3;
          font-family: "Inter-Medium", sans-serif;
          font-size: 14px;
          font-weight: 500;
        }
        .by-creating-your-account-you-can-confirm-that-you-accept-our-terms-of-use-privacy-policy-span2 {
          color: #f39c10;
          font-family: "Inter-Medium", sans-serif;
          font-size: 14px;
          font-weight: 500;
        }
        .by-creating-your-account-you-can-confirm-that-you-accept-our-terms-of-use-privacy-policy-span3 {
          color: #a5a3a3;
          font-family: "Inter-Medium", sans-serif;
          font-size: 14px;
          font-weight: 500;
        }
        .by-creating-your-account-you-can-confirm-that-you-accept-our-terms-of-use-privacy-policy-span4 {
          color: #fd9915;
          font-family: "Inter-Medium", sans-serif;
          font-size: 14px;
          font-weight: 500;
        }
        .by-creating-your-account-you-can-confirm-that-you-accept-our-terms-of-use-privacy-policy-span5 {
          color: #a5a3a3;
          font-family: "Inter-Medium", sans-serif;
          font-size: 14px;
          font-weight: 500;
        }
        .rectangle-7 {
          border-radius: 0px;
          width: 311px;
          height: 48px;
          position: absolute;
          left: 40px;
          top: 759px;
          overflow: visible;
        }
        .create-account {
          color: #000000;
          text-align: left;
          font-family: "Inter-Bold", sans-serif;
          font-size: 15px;
          font-weight: 700;
          position: absolute;
          left: 132px;
          top: 776px;
          width: 144px;
          height: 22px;
        }
        .have-an-account-sign-in {
          text-align: left;
          font-family: "Inter-Bold", sans-serif;
          font-size: 15px;
          font-weight: 700;
          position: absolute;
          left: 82px;
          top: 820px;
          width: 199px;
          height: 30px;
        }
        .have-an-account-sign-in-span {
          color: #000000;
          font-family: "Inter-Bold", sans-serif;
          font-size: 15px;
          font-weight: 700;
        }
        .have-an-account-sign-in-span2 {
          color: #f39c10;
          font-family: "Inter-Bold", sans-serif;
          font-size: 15px;
          font-weight: 700;
        }

#2nd page
        <div class="i-phone-13-14-2">
          <img class="logo-s" src="logo-s0.png" />
          <div class="ellipse-3"></div>
          <div class="ellipse-4"></div>
          <img class="search-logo-1" src="search-logo-10.png" />
          <div class="ellipse-5"></div>
          <img class="screenshot-91-1" src="screenshot-91-10.png" />
          <div class="upcoming-event-in-october">
            <span>
              <span class="upcoming-event-in-october-span">Upcoming Event</span>
              <span class="upcoming-event-in-october-span2">in October</span>
            </span>
          </div>
          <img class="screenshot-93" src="screenshot-930.png" />
          <img class="screenshot-92" src="screenshot-920.svg" />
          <div class="dhaka-food-festival">Dhaka Food Festival</div>
          <div class="rectangle-8"></div>
          <div class="view-event">View Event</div>
          <img class="food-emojy" src="food-emojy0.png" />
          <div
            class="lot-of-events-are-are-conducting-from-our-college-come-and-join-us"
          >
            <span>
              <span
                class="lot-of-events-are-are-conducting-from-our-college-come-and-join-us-span"
              >
                Lot of Events are
                <br />
                are conducting
                <br />
                from our College
                <br />
                come and
              </span>
              <span
                class="lot-of-events-are-are-conducting-from-our-college-come-and-join-us-span2"
              >
                join us
              </span>
            </span>
          </div>
          <div class="registeration-fee-for-all-300">
            <span>
              <span class="registeration-fee-for-all-300-span">
                Registeration Fee
                <br />
              </span>
              <span class="registeration-fee-for-all-300-span2">For All : 300</span>
            </span>
          </div>
        </div>
        
        .i-phone-13-14-2,
        .i-phone-13-14-2 * {
          box-sizing: border-box;
        }
        .i-phone-13-14-2 {
          background: #fffef5;
          border-radius: 20px;
          height: 853px;
          position: relative;
          overflow: hidden;
        }
        .logo-s {
          border-radius: 50%;
          width: 85px;
          height: 79px;
          position: absolute;
          left: 157px;
          top: 17px;
          object-fit: cover;
        }
        .ellipse-3 {
          background: #fffef5;
          border-radius: 50%;
          width: 54px;
          height: 53px;
          position: absolute;
          left: 29px;
          top: 31px;
        }
        .ellipse-4 {
          background: #fffef5;
          border-radius: 50%;
          width: 34px;
          height: 34px;
          position: absolute;
          left: 49px;
          top: 50px;
        }
        .search-logo-1 {
          width: 41px;
          height: 45px;
          position: absolute;
          left: 36px;
          top: 39px;
          object-fit: cover;
        }
        .ellipse-5 {
          background: #fffef5;
          border-radius: 50%;
          width: 58px;
          height: 53px;
          position: absolute;
          left: 306px;
          top: 31px;
        }
        .screenshot-91-1 {
          width: 34px;
          height: 26px;
          position: absolute;
          left: 318px;
          top: 44px;
          object-fit: cover;
        }
        .upcoming-event-in-october {
          text-align: left;
          font-family: "Inter-ExtraBold", sans-serif;
          font-size: 24px;
          font-weight: 800;
          position: absolute;
          left: 31px;
          top: 127px;
          width: 302px;
          height: 80px;
        }
        .upcoming-event-in-october-span {
          color: #000000;
          font-family: "Inter-ExtraBold", sans-serif;
          font-size: 24px;
          font-weight: 800;
        }
        .upcoming-event-in-october-span2 {
          color: #fd9915;
          font-family: "Inter-ExtraBold", sans-serif;
          font-size: 24px;
          font-weight: 800;
        }
        .screenshot-93 {
          border-radius: 20px;
          width: 148px;
          height: 152px;
          position: absolute;
          left: 31px;
          top: 193px;
          object-fit: cover;
        }
        .screenshot-92 {
          border-radius: 0px;
          width: 150px;
          height: 152px;
          position: absolute;
          left: 214px;
          top: 193px;
          overflow: visible;
          object-fit: cover;
        }
        .dhaka-food-festival {
          color: #000000;
          text-align: left;
          font-family: "Inter-Bold", sans-serif;
          font-size: 20px;
          font-weight: 700;
          position: absolute;
          left: 83px;
          top: 376px;
          width: 223px;
          height: 38px;
        }
        .rectangle-8 {
          background: #fd9915;
          border-radius: 20px;
          width: 195px;
          height: 49px;
          position: absolute;
          left: 83px;
          top: 414px;
        }
        .view-event {
          color: #000000;
          text-align: left;
          font-family: "Inter-Bold", sans-serif;
          font-size: 20px;
          font-weight: 700;
          position: absolute;
          left: 117px;
          top: 427px;
          width: 141px;
          height: 25px;
        }
        .food-emojy {
          border-radius: 20px;
          width: 151px;
          height: 127px;
          position: absolute;
          left: 42px;
          top: 496px;
          object-fit: cover;
        }
        .lot-of-events-are-are-conducting-from-our-college-come-and-join-us {
          text-align: left;
          font-family: "Inter-Bold", sans-serif;
          font-size: 16px;
          font-weight: 700;
          position: absolute;
          left: 214px;
          top: 522px;
        }
        .lot-of-events-are-are-conducting-from-our-college-come-and-join-us-span {
          color: #000000;
          font-family: "Inter-Bold", sans-serif;
          font-size: 16px;
          font-weight: 700;
        }
        .lot-of-events-are-are-conducting-from-our-college-come-and-join-us-span2 {
          color: #f39c10;
          font-family: "Inter-Bold", sans-serif;
          font-size: 16px;
          font-weight: 700;
        }
        .registeration-fee-for-all-300 {
          text-align: left;
          font-family: "Inter-Bold", sans-serif;
          font-size: 20px;
          font-weight: 700;
          position: absolute;
          left: 49px;
          top: 681px;
          width: 192px;
          height: 64px;
        }
        .registeration-fee-for-all-300-span {
          color: #f39c10;
          font-family: "Inter-Bold", sans-serif;
          font-size: 20px;
          font-weight: 700;
        }
        .registeration-fee-for-all-300-span2 {
          color: #000000;
          font-family: "Inter-Bold", sans-serif;
          font-size: 20px;
          font-weight: 700;
        }
3rd page

        <div class="i-phone-13-14-3">
          <img class="food-2" src="food-20.png" />
          <img class="food-3" src="food-30.png" />
          <img class="food-7" src="food-70.png" />
          <div class="have-a-taste-and-enjoy-the-moment-with-your-friend">
            <span>
              <span class="have-a-taste-and-enjoy-the-moment-with-your-friend-span">
                Have a taste
                <br />
                and
              </span>
              <span class="have-a-taste-and-enjoy-the-moment-with-your-friend-span2">
                enjoy the
                <br />
                moment
              </span>
              <span class="have-a-taste-and-enjoy-the-moment-with-your-friend-span3">
                with
                <br />
                your friend
              </span>
            </span>
          </div>
          <div class="you-can-order-the-food-what-you-want">
            <span>
              <span class="you-can-order-the-food-what-you-want-span">
                You can
                <br />
              </span>
              <span class="you-can-order-the-food-what-you-want-span2">
                order the
                <br />
                food
              </span>
              <span class="you-can-order-the-food-what-you-want-span3">
                what
                <br />
                you want
              </span>
            </span>
          </div>
          <div class="we-are-providing-parcels-too">
            <span>
              <span class="we-are-providing-parcels-too-span">
                we are
                <br />
                providing
                <br />
              </span>
              <span class="we-are-providing-parcels-too-span2">parcels too!</span>
            </span>
          </div>
        </div>
        
        .i-phone-13-14-3,
        .i-phone-13-14-3 * {
          box-sizing: border-box;
        }
        .i-phone-13-14-3 {
          background: #fffef5;
          border-radius: 20px;
          height: 853px;
          position: relative;
          overflow: hidden;
        }
        .food-2 {
          border-radius: 20px;
          width: 168px;
          height: 198px;
          position: absolute;
          left: 28px;
          top: 57px;
          object-fit: cover;
        }
        .food-3 {
          border-radius: 20px;
          width: 173px;
          height: 212px;
          position: absolute;
          left: 186px;
          top: 294px;
          object-fit: cover;
        }
        .food-7 {
          border-radius: 20px;
          width: 180px;
          height: 213px;
          position: absolute;
          left: 28px;
          top: 554px;
          object-fit: cover;
        }
        .have-a-taste-and-enjoy-the-moment-with-your-friend {
          text-align: left;
          font-family: "Inter-Bold", sans-serif;
          font-size: 20px;
          font-weight: 700;
          position: absolute;
          left: 236px;
          top: 102px;
        }
        .have-a-taste-and-enjoy-the-moment-with-your-friend-span {
          color: #000000;
          font-family: "Inter-Bold", sans-serif;
          font-size: 20px;
          font-weight: 700;
        }
        .have-a-taste-and-enjoy-the-moment-with-your-friend-span2 {
          color: #f39c10;
          font-family: "Inter-Bold", sans-serif;
          font-size: 20px;
          font-weight: 700;
        }
        .have-a-taste-and-enjoy-the-moment-with-your-friend-span3 {
          color: #000000;
          font-family: "Inter-Bold", sans-serif;
          font-size: 20px;
          font-weight: 700;
        }
        .you-can-order-the-food-what-you-want {
          text-align: left;
          font-family: "Inter-Bold", sans-serif;
          font-size: 20px;
          font-weight: 700;
          position: absolute;
          left: 36px;
          top: 344px;
          width: 113px;
        }
        .you-can-order-the-food-what-you-want-span {
          color: #000000;
          font-family: "Inter-Bold", sans-serif;
          font-size: 20px;
          font-weight: 700;
        }
        .you-can-order-the-food-what-you-want-span2 {
          color: #f39c10;
          font-family: "Inter-Bold", sans-serif;
          font-size: 20px;
          font-weight: 700;
        }
        .you-can-order-the-food-what-you-want-span3 {
          color: #000000;
          font-family: "Inter-Bold", sans-serif;
          font-size: 20px;
          font-weight: 700;
        }
        .we-are-providing-parcels-too {
          text-align: left;
          font-family: "Inter-Bold", sans-serif;
          font-size: 20px;
          font-weight: 700;
          position: absolute;
          left: 247px;
          top: 600px;
        }
        .we-are-providing-parcels-too-span {
          color: #000000;
          font-family: "Inter-Bold", sans-serif;
          font-size: 20px;
          font-weight: 700;
        }
        .we-are-providing-parcels-too-span2 {
          color: #f39c10;
          font-family: "Inter-Bold", sans-serif;
          font-size: 20px;
          font-weight: 700;
        }
```
           

# OUTPUT:
![Screenshot (95)](https://github.com/user-attachments/assets/b8efd476-2649-4cb5-aa5f-59248cbd40cf)

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
