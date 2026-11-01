---
layout: "ssg-theme-astro/layouts/main.astro" # This line of code should remain unchanged.
tag: "GTM-5X48JDV2"
title: "Dim Sum Club 點心薈 - Best Food Today"
favicon: "favicon.ico" #ico is best
logo: "點心薈LOGO-定.webp"
primaryColor: "#7E1C1D" # logo color
secondaryColor: "#EBB73D"
primaryColorScheme: "dark" # dark | light
secondaryColorScheme: "light"
cuid: ""
ruid: ""
orderOnlineLink: "https://www.bestfoodtodayus.com/ordering/restaurant/menu?restaurant_uid=3a3ff07f-24b2-43f5-9bcb-9f60d2ca5e9b"
# tableReservationLink: "https://www.bestfoodtodayus.com/ordering/restaurant/menu/reservation?restaurant_uid=3a3ff07f-24b2-43f5-9bcb-9f60d2ca5e9b&reservation=true&client_is_mobile=true"
tel: "415-592-8938"

# banner:
#   text:
#     - boldText: "🥳 Happy New Year!"
#     - boldText: "We will be open as usual on the first day of the Lunar New Year (Tuesday) from 10:00 AM to 3:00 PM."
#     - text: ""
#     - smText: ""
#   # add more text...
#   textColor: "#ffffff"
#   bgColor: "#E7383D"
#   bgOpacity: "1" # 0~1

# header
header:
  logoSize: 70
  logoSizeOnMobile: 50
  textAfterLogo:
    text: ""
    size: 20
    color: ""
  logoOnMobile: "點心薈LOGO-mobile.webp"
  bgColor: "#fff"
  bgOpacity: "0.9" # 0~1
  menuTextColor: "#000"
  menu:
    - { text: "Home", link: "/" }
    - { text: "Gallery", link: "/#gallery" }
    - { text: "About Us", link: "/#about-us" }
    - { text: "Contact Us", link: "/#contact-us" }
    - { text: "中文", link: "/zh_TW" }

  addOrderOnlineBtn: false
  orderOnlineBtnInsteadText: ""
  addTableReservationBtn: false
  tableReservationBtnInsteadText: ""
  telTextColor: "#000000"
  addTelBtn: true
  otherBtn1InsteadText: "Order Oline"
  otherBtn1Href: "https://www.bestfoodtodayus.com/ordering/restaurant/menu?restaurant_uid=3a3ff07f-24b2-43f5-9bcb-9f60d2ca5e9b"
  otherBtn2InsteadText: ""
  otherBtn2Href: ""

sections:
  # hero
  - type: "hero"
    id: ""
    height: "100" # Conditionally use only when sectionType is imgBg
    sectionType: "video" # video | imgWithText | imgBg
    bgVideoType: "gjw" # youtube | vimeo | gjw
    bgVideoId: "1gvlmtv3tum2JZzTBY29WfNi01rl1c"
    bgImg: "Dim Sum Club 點心薈.webp"
    bgColor: "#000000"
    bgOpacity: "0.5" # 0~1
    title:
      - "Dim Sum Club"
      - "點心薈"
    titleColor: "#ffffff"
    description:
      - "Welcome to Dim Sum Club, Come and enjoy your day with traditional handmade Cantonese style dim sums!"
    descriptionColor: "#ffffff"
    isTextAlignCenter: true
    # title2:
    #   - ""
    # title2Color: "#ffffff"
    # description2:
    #   - ""
    # description2Color: "#ffffff"

    addOrderOnlineBtn: false
    orderOnlineBtnInsteadText: ""
    addTableReservationBtn: false
    tableReservationBtnInsteadText: ""

    btn1Text: "See MENU & Order"
    btn1Href: "https://www.bestfoodtodayus.com/ordering/restaurant/menu?restaurant_uid=3a3ff07f-24b2-43f5-9bcb-9f60d2ca5e9b"
    btn2Text: "Tel: 415-592-8938"
    btn2Href: "tel:415-592-8938"

    bannerImg: ""
    imgPosition: "imgLeft" # imgLeft | imgRight
    bannerMarginTopMobile: 20
    imgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

    bottomRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full
    # bottomInfo: "We offer Takeout"

  # Video
  - type: "video"
    id: "video"
    title:
      - "Dim Sum Club 點心薈"
    description:
      - "Come and savor our delicious selections!"
    videoType: "gjw" # vimeo | gjw | youtube
    videoId:
      - "1gus30l309e3Pb9AhQptQPgTK1pv1c"
    isOnlyDisplayOnMobile: false

  # Gallery - menu
  - type: "gallery"
    id: "gallery"
    mode: 4 # 1 - 4 # 1 - 3
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title:
      - "Delicious Dim Sum"
    titleColor: "#000000"
    description:
      - ""
    descriptionColor: "#333333"
    folderPath: "gallery1"
    altOverrides:
      "001_Pan-Fried Turnip Cake Slices": "Pan-Fried Turnip Cake"
      "002_Green Vegetable Dumplings in Bowl": "Jade Vegetable Dumplings"
      "003_Fried Crab Rangoon": "Crab Rangoon"
      "004_Pan-Fried Pork Buns with Scallions": "Pan-Fried Pork Buns (Sheng Jian Bao)"
      "005_Steamed Soup Dumplings in Bamboo Steamer": "Xiaolongbao Soup Dumplings"
      "006_Steamed Shrimp Dumplings": "Shrimp Dumplings (Har Gow)"
      "007_Steamed Rice Wraps in Bamboo Steamer": "Sticky Rice Parcels (Lo Mai Gai)"
      "008_Steamed Crystal Dumplings with Greens": "Chive and Shrimp Dumplings"
      "009_Pork Shumai": "Pork Siu Mai"
      "010_Steamed White Buns in Bamboo Steamer": "BBQ Pork Buns (Char Siu Bao)"
      "011_Steamed Golden Custard Buns": "Steamed Custard Buns"
      "013_Braised Chicken Feet with Green Chili": "Braised Chicken Feet"
      "015_Pan-Fried Round Buns with Scallion and Sesame": "Pan-Fried Pork Buns (Sheng Jian Bao)"
      "018_Rice Noodle Rolls with Herbs and Choy Sum": "Rice Noodle Rolls with Cilantro and Choy Sum"
      "019_Plain Rice Noodle Rolls with Choy Sum": "Rice Noodle Rolls with Choy Sum"
    showImgName: false # true | false
    imgNameColor: "#000000"
    menuItemImgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

  # Gallery - menu
  - type: "gallery"
    id: "gallery-2"
    mode: 4 # 1 - 4 # 1 - 3
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title:
      - "Delicious Cuisine"
    titleColor: "#000000"
    description:
      - ""
    descriptionColor: "#333333"
    folderPath: "gallery"
    altOverrides:
      "001_Shrimp with Bean Sprouts in Red Pepper Ring": "Shrimp on Shredded Vegetables"
      "002_Walnut Shrimp on Square Plate": "Walnut Shrimp"
      "003_Sliced Beef with Peanuts and Sesame Seeds": "Beef and Tripe in Chili Oil (Fuqi Feipian)"
      "013_Roast Duck Platter": "Roast Duck"
      "015_Crispy Fried Chicken with Green Chilies": "Salt and Pepper Fried Chicken"
      "016_Walnut Shrimp Close-Up with Orchid Garnish": "Walnut Shrimp"
    showImgName: false # true | false
    imgNameColor: "#000000"
    menuItemImgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

  # textBlock - about us
  - type: "textBlock"
    id: "about-us"
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title:
      - "About Dim Sum Club"
      - "點心薈"
    titleColor: "#000000"
    description:
      - "Welcome to Dim Sum Club,  Come and enjoy your day with traditional handmade Cantonese style dim sums such as shrimp dumplings (Har Gow) , chives & shrimp dumplings, Pork dumpling (Siu Mai), BBQ Pork Bun, Techew dumpling, Shanghai dumpling & rice noodle rolls. We also serve traditional Chinese style seafood dishes. Dim Sum Club offers the authentic taste at reasonable price."
    descriptionColor: ""

  # Gallery - Welcome To Dim Sum Club 點心薈
  - type: "gallery"
    id: ""
    mode: 4 # 1 - 4 # 1 - 3
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title:
      - "Welcome To Dim Sum Club"
      - "點心薈"
    titleColor: ""
    description:
      - ""
    descriptionColor: "#333333"
    folderPath: "gallery2"
    altOverrides:
      "001_Dining Room with Round Banquet Table": "Dim Sum Club Dining Room"
      "002_Dining Room with Wall Mural and Tables": "Dim Sum Club Dining Room Near Entrance"
      "003_Storefront with Grand Opening Banner": "Dim Sum Club Storefront"
      "004_Entrance Door with Grand Opening Banner": "Dim Sum Club Storefront Entrance"
    showImgName: false # true | false
    imgNameColor: "#000000"
    menuItemImgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

  # # feature - imgWithText
  #   - type: "feature"
  #     noMarginTop: true
  #     id: ""
  #     height: "100" # Conditionally use only when sectionType is imgBg
  #     sectionType: "imgWithText" # video | imgWithText | imgBg
  #     title:
  #       - "Lorem ipsum dolor sit ame"
  #     titleColor: "#000000"
  #     description:
  #       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
  #     descriptionColor: "#000000"

  #     addOrderOnlineBtn: false
  #     orderOnlineBtnInsteadText: ""
  #     addTableReservationBtn: false
  #     tableReservationBtnInsteadText: ""

  #     btn1Text: ""
  #     btn1Href: ""
  #     btn2Text: ""
  #     btn2Href: ""

  #     bannerImg: "sample.webp"
  #     imgPosition: "imgLeft" # imgLeft | imgRight
  #     bannerMarginTopMobile: 20
  #     imgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

  # # feature - map
  #   - type: "feature"
  #     id: ""
  #     noMarginTop: false
  #     sectionType: "imgWithText" # video | imgWithText | imgBg
  #     title:
  #       - "Store 2 : Washington St"
  #     titleColor: "#000000"
  #     description:
  #       - "Opening Hours: "
  #       - "Mon-Fri 8:30 AM-8:00 PM, Sat-Sun 9:00 AM-8:30 PM"
  #     descriptionColor: "#000000"

  #     addOrderOnlineBtn: true
  #     orderOnlineBtnInsteadText: ""
  #     addTableReservationBtn: true
  #     tableReservationBtnInsteadText: ""
  #     showOtherBtn: true
  #     btn1Text: "Order online from Washington St Store"
  #     btn1Href: "#"
  #     btn2Text: ""
  #     btn2Href: ""

  #     map: true
  #     url: "https://maps.app.goo.gl/HDDb5yFih4S8TmDe7"
  #     iframeUrl: "https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d197.0491990412703!2d-122.4063506!3d37.7950269!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8085815e4be59617%3A0x87622e118f7e38a2!2sHon%E2%80%99s%20Wun-Tun%20House!5e0!3m2!1sen!2sjp!4v1722232541079!5m2!1sen!2sjp"
  #     addTelBtn: true
  #     tel: "12345678"
  #     telInsteadText: "Call: (123) 456-7890"
  #     tel2: "876543210" # if there are two phone numbers"
  #     tel2InsteadText: "Call: (876) 543-2100"
  #     getDirectionBtnInsteadText: ""
  #     imgPosition: "" # imgLeft | imgRight

  # # textBlock
  #   - type: "textBlock"
  #     id: "about-us"
  #     bgImg: ""
  #     bgColor: ""
  #     bgOpacity: "" # 0~1
  #     title:
  #       - "About Us"
  #     titleColor: "#000000"
  #     description:
  #       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit."
  #       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
  #     descriptionColor: "#000000"

  # textBlock - Information - NEW! Online Ordering
  - type: "textBlock"
    noMarginTop: false
    id: ""
    bgImg: "Dim Sum Club 點心薈a.webp"
    bgColor: "#000"
    bgOpacity: "0.6" # 0~1
    title:
      - "NEW! Online Ordering"
    titleColor: "#ffffff"
    description:
      - "Online ordering NOW enabled for pick-up. Just tell us what you want and we'll prepare it as fast as we can. All orders are manually confirmed by us directly. Find out in real-time when your food is ready. All orders are manually confirmed by us in real-time. Watch on-screen when your food is ready for pickup."
    descriptionColor: "#ffffff"

  # map
  - type: "map"
    noMarginTop: true
    id: "contact-us"
    mode: "fullWidth" # full-width | ...
    url: "https://maps.app.goo.gl/8jTL3ZwV9JjpWQiQA"
    iframeUrl: "https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d914.3236446052001!2d-122.49179671757695!3d37.742276930733766!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808f7d82ee0f4663%3A0xde21cc529fccf39d!2zRGltIFN1bSBDbHViIOm7nuW_g-iWiA!5e0!3m2!1sen!2sus!4v1723080951228!5m2!1sen!2sus"
    addTelBtn: true
    tel: ""
    telInsteadText: "Tel: 415-592-8938"
    tel2: "" # if there are two phone numbers
    tel2InsteadText: ""
    getDirectionBtnInsteadText: ""

#  # The modal will only appear once within 30 minutes."
#   - type: "modal"
#     bgColor: "#333"
#     bgOpacity: "0.1" # 0~1
#     title:
#       - "🎁 Special Offers"
#     titleColor: "#FF2D2F"
#     titleSize: 24
#     description:
#       - "20% off cash discount on frozen handmade dumplings. 10% off cash discount on family meal takeout. Free rice with lunch. Delivery available."
#     descriptionColor: ""
#     descriptionSize: 16
#     imgName: "special_offer.webp"
#     imgAlt: "20% off cash discount on frozen handmade dumplings. 10% off cash discount on family meal takeout. Free rice with lunch. Delivery available."
#     imgHref: ""
#     buttonText: ""

footer:
  cookie: true
  mode: 1 # 1
  noMarginTop: true
  bgImg: "gallery2/001_Dining Room with Round Banquet Table.webp"
  bgColor: "#000"
  bgOpacity: "0.7" # 0~1
  textColor: "#fff" # default white

  openingHoursInsteadText: ""
  openingHours:
    - "Mon, Wed ~ Fri"
    - "10:30 AM - 3:00 PM, 5:00 PM - 9:00 PM"
    - "Sat ~ Sun"
    - "10:00 AM - 3:00 PM, 5:00 PM - 9:00 PM"
    - "Tue Closed"

  isLogo: false
  logoSize: 120

  # menu:
  #   - { text: "Home", link: "/" }
  #   - { text: "Gallery", link: "#gallery" }
  #   - { text: "About Us", link: "/#about-us" }
  #   - { text: "Contact Us", link: "/#contact-us" }
  #   - { text: "中文", link: "/zh_TW" }

  FB: false
  FBLink: ""
  IG: false
  IGLink: ""
  X: false
  XLink: ""
  youtube: false
  youtubeLink: ""
  yelp: false
  yelpLink: ""
  doorDash: true
  doorDashLink: "https://www.doordash.com/store/dim-sum-club-san-francisco-1654701/"
  uberEats: true
  uberEatsLink: "https://www.ubereats.com/store/dim-sum-club/uaVtE5tHR3S6AipUh3-1ug"

  acceptedPaymentMethodsInsteadText: ""
  paymentMethod: "cash,visa,amex,alipay,mastercard" # alipay,applePay,cash,discover,googlePay,jcb,maestro,mastercard,stripe,unionPay,visa,weChatPay,payPal
  addressInsteadText: "Address"
  address:
    - address: "2237 Taraval St, San Francisco, CA 94116"
      url: "https://maps.app.goo.gl/8jTL3ZwV9JjpWQiQA"

  # at a minimum, please make sure to include the meta description.
seo:
  metaTitle: "Dim Sum Club 點心薈｜Cantonese Dim Sums｜SF"
  metaDescription: "Discover Dim Sum Club 點心薈 in San Francisco, CA, where traditional handmade Cantonese dim sums meet outstanding service. takeaway food or Order online now!"
  img: "https://dimsumclub-sf.com/Dim%20Sum%20Club%20%E9%BB%9E%E5%BF%83%E8%96%88.webp"
  thisPageUrl: "https://dimsumclub-sf.com/"
  locale: "en_US" # zh_TW | zh_CN
  canonicalHref: "https://dimsumclub-sf.com/" # https://example.com/
---

<!-- hello world -->
