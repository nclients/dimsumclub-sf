---
layout: "ssg-theme-astro/layouts/main.astro" # This line of code should remain unchanged.
tag: ""
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
tableReservationLink: ""
tel: "415-579-3688"

# banner:
#   text:
#     - boldText: "🥳 新年快樂！"
#     - boldText: "本店於農曆初一（週二）10:00 AM – 3:00 PM 正常營業。"
#     # - text: " on xxx"
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
    - { text: "首頁", link: "/zh_TW" }
    - { text: "菜品展示", link: "#gallery" }
    - { text: "關於我們", link: "#about-us" }
    - { text: "聯繫我們", link: "#contact-us" }
    - { text: "English", link: "/" }

  addOrderOnlineBtn: false
  orderOnlineBtnInsteadText: ""
  addTableReservationBtn: false
  tableReservationBtnInsteadText: ""
  addTelBtn: true
  telTextColor: "#000000"

  otherBtn1InsteadText: "在線訂餐"
  otherBtn1Href: "https://www.bestfoodtodayus.com/ordering/?restaurant_uid=3a3ff07f-24b2-43f5-9bcb-9f60d2ca5e9b"
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
      - "歡迎光臨 Dim Sum Club 點心薈！在這裡，您可以享受傳統手工製作的粵式點心。"
      - "期待您的光臨，讓我們一起度過愉快的一天！"
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

    btn1Text: "在線訂餐"
    btn1Href: "https://www.bestfoodtodayus.com/ordering/restaurant/menu?restaurant_uid=3a3ff07f-24b2-43f5-9bcb-9f60d2ca5e9b"
    btn2Text: "電話: (415) 579-3688"
    btn2Href: "tel:415-579-3688"

    bannerImg: ""
    imgPosition: "imgLeft" # imgLeft | imgRight
    bannerMarginTopMobile: 20
    imgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

    bottomRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full
    # bottomInfo: "We offer Takeout"

  # Video
  - type: "video"
    id: ""
    title:
      - "Dim Sum Club 點心薈"
    description:
      - ""
      - ""
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
      - "美味點心"
    titleColor: "#000000"
    description:
      - "快来品尝我们精选的美味佳肴，甘香流沙包、水晶蝦餃皇、上海小籠包、百花釀茄子、豉汁排骨 ......"
    descriptionColor: "#333333"
    folderPath: "gallery1"
    showImgName: false # true | false
    imgNameColor: "#000000"
    menuItemImgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

  # Gallery - menu
  - type: "gallery"
    id: "gallery"
    mode: 4 # 1 - 4 # 1 - 3
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title:
      - "美味菜餚"
    titleColor: "#000000"
    description:
      - "快來開啟您的美味之旅！"
    descriptionColor: "#333333"
    folderPath: "gallery"
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
      - "關於我們"
    titleColor: "#000000"
    description:
      - "歡迎光臨 Dim Sum Club 點心薈！"
      - "在這裡，您可以享受傳統手工製作的粵式點心，如蝦餃、韭菜蝦餃、燒賣、叉燒包、潮州粉果、小籠包和腸粉。我們也提供傳統中式海鮮菜餚。點心俱樂部致力於以合理的價格為您奉上正宗美味。"
      - "期待您的光臨，讓我們一起度過美好的一天！"
    descriptionColor: ""

  # Gallery - Welcome To Dim Sum Club 點心薈
  - type: "gallery"
    id: ""
    mode: 4 # 1 - 4 # 1 - 3
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title:
      - "歡迎光臨"
    titleColor: ""
    description:
      - ""
    descriptionColor: "#333333"
    folderPath: "gallery2"
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

  # textBlock - Information
  - type: "textBlock"
    noMarginTop: false
    id: ""
    bgImg: "/Dim Sum Club 點心薈a.webp"
    bgImgAlt: "Dim Sum Club 點心薈.webp"
    bgColor: "#000"
    bgOpacity: "0.6" # 0~1
    title:
      - "新功能! 在線訂餐"
    titleColor: "#ffffff"
    description:
      - "現在支援線上訂單自取。只要告訴我們您想要的菜餚，我們會​​盡快準備好。所有訂單都由我們手動確認。您可以即時查看您的食物何時準備好。訂單狀態會即時更新，您可以在螢幕上查看您的食物何時可以取走。"
    descriptionColor: "#ffffff"

  # map
  - type: "map"
    noMarginTop: true
    id: "contact-us"
    mode: "fullWidth" # full-width | ...
    url: "https://maps.app.goo.gl/757AKRaYLAQ2aTb3A"
    iframeUrl: "https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3152.611833512855!2d-122.42643388796009!3d37.799135671862416!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808580e7fe35ab13%3A0x1bbee07675c9621b!2sDim%20Sum%20Club!5e0!3m2!1szh-CN!2sca!4v1731542744169!5m2!1szh-CN!2sca"
    addTelBtn: true
    tel: ""
    telInsteadText: "電話：415-579-3688"
    tel2: "" # if there are two phone numbers
    tel2InsteadText: ""
    getDirectionBtnInsteadText: "帶我去餐廳"

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
  mode: 1 # 1
  noMarginTop: true
  bgImg: "gallery2/001_Dim Sum Club interior.webp"
  bgColor: "#000"
  bgOpacity: "0.7" # 0~1
  textColor: "#fff" # default white

  openingHoursInsteadText: "營業時間"
  openingHours:
    - "週一、 週三～週五"
    - "10:30 AM - 3:00 PM, 5:00 PM - 9:00 PM"
    - "週六、週日"
    - "10:00 AM - 3:00 PM, 5:00 PM - 9:00 PM"
    - "週二  休息"

  isLogo: false
  logoSize: 120

  # menu:
  #   - { text: "首頁", link: "/zh_TW" }
  #   - { text: "菜品展示", link: "#gallery" }
  #   - { text: "關於我們", link: "#about-us" }
  #   - { text: "聯繫我們", link: "#contact-us" }
  #   - { text: "English", link: "/" }

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

  acceptedPaymentMethodsInsteadText: "付款方式"
  paymentMethod: "cash,visa,amex,alipay,mastercard" # alipay,applePay,cash,discover,googlePay,jcb,maestro,mastercard,stripe,unionPay,visa,weChatPay,payPal
  addressInsteadText: "地址"
  address:
    - address: "2237 Taraval St, San Francisco, CA 94116"
      url: "https://maps.app.goo.gl/8jTL3ZwV9JjpWQiQA"

  # at a minimum, please make sure to include the meta description.
seo:
  metaTitle: "Dim Sum Club 點心薈｜三藩市｜廣東菜｜粵菜"
  metaDescription: "探索三藩市的 Dim Sum Club 點心薈，享受傳統廣東菜，粵菜与卓越服務的完美结合。還提供外带或在線訂購服務！"
  img: "https://dimsumclub-sf.com/Dim%20Sum%20Club%20%E9%BB%9E%E5%BF%83%E8%96%88.webp"
  thisPageUrl: "https://dimsumclub-sf.com/"
  canonicalHref: "https://dimsumclub-sf.com/" # https://example.com/
  locale: "zh_TW" # zh_TW | zh_CN
---

<!-- hello world -->
