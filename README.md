<script>
    var nameArr = [
      "Nikel-jak",
      "Sam-al",
      "Shxy-jhu",
      "Shubke",
      "Bts-boy",
      "Narzo_in",
      "Mrs-shin",
      "Kaguyama",
      "Aligator_sho",
      "McYeter200",
      "Subadi382",
      "Dadi900",
      "Mikel62",
      "Jhon094",
      "Sam27",
      "Numkei35",
      "Shinkai",
      "Badsur7",
      "Shxy_bit",
      "xvy_ht5",
      "txf07",
      "Double63",
      "Birdas74",
      "Narzi84",
      "palyr41",
      "xoxox743",
      "zima97",
      "same85",
      "pop086"
    ];
    var phoneArr = [
      "8676 Tiktok Coins!",
      "$50 Fortnite Card!",
      "$75 Playstation Card!",
      "$10 Amazon Card!",
      "$20 Xbox Card!",
      "8.642 Robux Card!",
      "$100 Tiktok Followers!",
      "13.598 Tiktok Coins!",
      "$30 Playstation Card!",
      "$75 googleplay Card!",
      "$10 Robux Card!",
      "$100 Fortnite Card!",
      "$150 Robux Card!",
      "$100 Playstation Card!",
      "$15 Googleplay Card!",
      "$35 Amazon Card!",
      "9865 Tiktok Followers!",
      "$50 Googleplay Card!",
      "$100 Fortnite Card!",
      "$5 Playstation Card!",
      "$100 Amazon Card!",
      "$5 Xbox Card!",
      "$15 Robux Card!",
      "$100 Fortnite Card!",
      "$25 Fortnite Card!",
      "$100 Playstation Card!",
      "$50 amazon Card!",
      "112357 Tiktok Coins!",
      "$200 Googleplay Card!"
    ];
    setInterval(function() {
      var randomNumber = Math.floor(Math.random() * nameArr.length);
      $("#customer-name").text(nameArr[randomNumber] + " Has just claimed a ");
      $("#customer-phone").text("Claimed " + phoneArr[randomNumber]);
      $("#customer-time").text(randomNumber + 1 + " min ago");
      $("#notification-container").show();
      setTimeout(() => {
        $(".notification-bottom-left").stop().slideToggle("fast");
      }, 4000);
    }, 5000);
  </script>
