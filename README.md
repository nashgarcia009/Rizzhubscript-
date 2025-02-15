local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
    Name = "Rizz Hub",
    LoadingTitle = "Welcome to Rizz Hub!",
    LoadingSubtitle = "By Drake make the girls fall",
    Discord = {
        Enabled = true,
        Invite = "WgAcTZzStB",
        RememberJoins = true
    },
    KeySystem = false
})

local mainTab = Window:CreateTab("MAIN", 4483345998)

function chat(msg)
    if game:GetService("TextChatService").ChatVersion == Enum.ChatVersion.TextChatService then
        game:GetService("TextChatService").TextChannels.RBXGeneral:SendAsync(msg)
    else
        game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest:FireServer(msg, "All")
    end
end

Rayfield:Notify({
    Title = "Hello!",
    Content = "Hello " .. game.Players.LocalPlayer.Name .. " and thank you for using Rizz Hub!",
    Duration = 5,
    Image = 4483345998
})

mainTab:CreateButton({
    Name = "1. Can I be your snowflake?...",
    Callback = function()
        chat("Can I be your snowflake? I promise to never melt away from your heart.")
    end
})

mainTab:CreateButton({
    Name = "2. Are you a Wi-Fi signal?...",
    Callback = function()
        chat("Are you a Wi-Fi signal? Because I’m feeling a strong connection.")
    end
})

mainTab:CreateButton({
    Name = "3. Are you a heart?...",
    Callback = function()
        chat("Are you a heart? Because I'd never stop beating for you.")
    end
})

mainTab:CreateButton({
    Name = "4. I believe in following my dreams...",
    Callback = function()
        chat("I believe in following my dreams, so you lead the way.")
    end
})

mainTab:CreateButton({
    Name = "5. If being beautiful was a crime...",
    Callback = function()
        chat("If being beautiful was a crime, you’d be on the most wanted list.")
    end
})

mainTab:CreateButton({
    Name = "6. Are you iron?...",
    Callback = function()
        chat("Are you iron? Because I don’t get enough of you.")
    end
})

mainTab:CreateButton({
    Name = "7. You should be Jasmine...",
    Callback = function()
        chat("You should be Jasmine, 'cause you're absolutely royal.")
    end
})

mainTab:CreateButton({
    Name = "8. Are you a Disney ride?...",
    Callback = function()
        chat("Are you a Disney ride? Because I’d wait forever for you.")
    end
})

mainTab:CreateButton({
    Name = "9. Hey, I’m sorry to bother you...",
    Callback = function()
        chat("Hey, I’m sorry to bother you, but my phone must be broken because it doesn’t seem to have your number in it.")
    end
})

mainTab:CreateButton({
    Name = "10. Are you good at math?...",
    Callback = function()
        chat("Are you good at math? Me neither, the only number I care about is yours.")
    end
})

mainTab:CreateButton({
    Name = "11. Is your name Elsa?...",
    Callback = function()
        chat("Is your name Elsa? Because I can't let you go.")
    end
})

mainTab:CreateButton({
    Name = "12. Do you know the difference between history and you?...",
    Callback = function()
        chat("Do you know the difference between history and you? History is the past, and you are my future.")
    end
})

mainTab:CreateButton({
    Name = "13. Do you work for NASA?...",
    Callback = function()
        chat("Do you work for NASA? Because your beauty is out of this world.")
    end
})

mainTab:CreateButton({
    Name = "14. Math is so confusing...",
    Callback = function()
        chat("Math is so confusing. It always talks about x and y, but never you and I.")
    end
})

mainTab:CreateButton({
    Name = "15. Are you Christmas morning?...",
    Callback = function()
        chat("Are you Christmas morning? Because I’ve been waiting all year for you to arrive.")
    end
})

mainTab:CreateButton({
    Name = "16. Are you from Tennessee?...",
    Callback = function()
        chat("Are you from Tennessee? Because you're the only ten I see.")
    end
})

mainTab:CreateButton({
    Name = "17. Are you Nemo?...",
    Callback = function()
        chat("Are you Nemo? Because I've been trying to find you.")
    end
})

mainTab:CreateButton({
    Name = "18. Are you a bank loan?...",
    Callback = function()
        chat("Are you a bank loan? Because you have my interest.")
    end
})

mainTab:CreateButton({
    Name = "19. I hope you know CPR...",
    Callback = function()
        chat("I hope you know CPR, because you just took my breath away.")
    end
})

mainTab:CreateButton({
    Name = "20. Are you the sun?...",
    Callback = function()
        chat("Are you the sun? Because I could stare at you all day, and it’d be worth the risk.")
    end
})

mainTab:CreateButton({
    Name = "21. Are you a keyboard?...",
    Callback = function()
        chat("Are you a keyboard? Because you're just my type.")
    end
})

mainTab:CreateButton({
    Name = "22. My mom said sharing is caring...",
    Callback = function()
        chat("My mom said sharing is caring... but you're all mine!")
    end
})

mainTab:CreateButton({
    Name = "23. It's time to pay up...",
    Callback = function()
        chat("It's time to pay up. It's the first of the month, and you've been living in my mind rent-free.")
    end
})

mainTab:CreateButton({
    Name = "24. Are you a light?...",
    Callback = function()
        chat("Are you a light? Because you always make me feel bright.")
    end
})

mainTab:CreateButton({
    Name = "25. Do you have a bandaid?...",
    Callback = function()
        chat("Do you have a bandaid? My knees hurt from falling for you.")
    end
})

mainTab:CreateButton({
    Name = "26. We may not be pants, but...",
    Callback = function()
        chat("We may not be pants, but we'd make a great pair.")
    end
})

mainTab:CreateButton({
    Name = "27. You know what's beautiful?...",
    Callback = function()
        chat("You know what's beautiful? Repeat the first word.")
    end
})

mainTab:CreateButton({
    Name = "28. Your eyes remind me of Ikea...",
    Callback = function()
        chat("Your eyes remind me of Ikea: easy to get lost in.")
    end
})

mainTab:CreateButton({
    Name = "29. If you were a Transformer...",
    Callback = function()
        chat("If you were a Transformer, you'd be Optimus Fine.")
    end
})

mainTab:CreateButton({
    Name = "30. I must be a time traveler...",
    Callback = function()
        chat("I must be a time traveler, because I can't imagine my future without you.")
    end
})

mainTab:CreateButton({
    Name = "31. Are you a light switch?...",
    Callback = function()
        chat("Are you a light switch? Because you turn me on.")
    end
})

mainTab:CreateButton({
    Name = "32. Are you a doctor? Because...",
    Callback = function()
        chat("Are you a doctor? Because you instantly make me feel better.")
    end
})

mainTab:CreateButton({
    Name = "33. You must be a masterpiece...",
    Callback = function()
        chat("You must be a masterpiece, because I can't take my eyes off of you.")
    end
})

mainTab:CreateButton({
    Name = "34. Are you my favorite song?...",
    Callback = function()
        chat("Are you my favorite song? Because I can't get you out of my head.")
    end
})

mainTab:CreateButton({
    Name = "35. I'm no photographer, but...",
    Callback = function()
        chat("I'm no photographer, but I can picture us together.")
    end
})

-- New fun additions
mainTab:CreateButton({
    Name = "36. Are you a magician?...",
    Callback = function()
        chat("Are you a magician? Because whenever I look at you, everyone else disappears.")
    end
})

mainTab:CreateButton({
    Name = "37. Do you have a map?...",
    Callback = function()
        chat("Do you have a map? Because I keep getting lost in your eyes.")
    end
})

mainTab:CreateButton({
    Name = "38. You must be French...",
    Callback = function()
        chat("You must be French, because Eiffel for you.")
    end
})

mainTab:CreateButton({
    Name = "39. Are you a time traveler?...",
    Callback = function()
        chat("Are you a time traveler? Because I see you in my future.")
    end
})

mainTab:CreateButton({
    Name = "40. Is your name Google?...",
    Callback = function()
        chat("Is your name Google? Because you’ve got everything I’ve been searching for.")
    end
})

mainTab:CreateButton({
    Name = "Destroy UI",
    Callback = function()
        Rayfield:Destroy()
    end
})
mainTab:CreateButton({
    Name = "41. Are you French?...",
    Callback = function()
        chat("Are you French? Because Eiffel for you.")
    end
})

mainTab:CreateButton({
    Name = "42. Are you an angel?...",
    Callback = function()
        chat("Are you an angel? Because heaven is missing one.")
    end
})

mainTab:CreateButton({
    Name = "43. Do you have a Band-Aid?...",
    Callback = function()
        chat("Do you have a Band-Aid? Because I just scraped my knee falling for you.")
    end
})

mainTab:CreateButton({
    Name = "44. Are you a star?...",
    Callback = function()
        chat("Are you a star? Because your beauty lights up my world.")
    end
})

mainTab:CreateButton({
    Name = "45. If you were a vegetable...",
    Callback = function()
        chat("If you were a vegetable, you’d be a cutecumber.")
    end
})

mainTab:CreateButton({
    Name = "46. Are you a time machine?...",
    Callback = function()
        chat("Are you a time machine? Because every time I look at you, I see my future.")
    end
})

mainTab:CreateButton({
    Name = "47. Is there a spark between us?...",
    Callback = function()
        chat("Is there a spark between us? Because you just lit up my life.")
    end
})

mainTab:CreateButton({
    Name = "48. Are you a firework?...",
    Callback = function()
        chat("Are you a firework? Because you light up my night sky.")
    end
})

mainTab:CreateButton({
    Name = "49. Do you like raisins?...",
    Callback = function()
        chat("Do you like raisins? No? How about a date?")
    end
})

mainTab:CreateButton({
    Name = "50. Are you a camera?...",
    Callback = function()
        chat("Are you a camera? Because every time I look at you, I smile.")
    end
})

mainTab:CreateButton({
    Name = "51. Do you believe in love at first sight?...",
    Callback = function()
        chat("Do you believe in love at first sight, or should I walk by again?")
    end
})

mainTab:CreateButton({
    Name = "52. You must be tired...",
    Callback = function()
        chat("You must be tired because you've been running through my mind all day.")
    end
})

mainTab:CreateButton({
    Name = "53. Do you have a pencil?...",
    Callback = function()
        chat("Do you have a pencil? Because I want to draw a smile on your face.")
    end
})

mainTab:CreateButton({
    Name = "54. If I were a cat...",
    Callback = function()
        chat("If I were a cat, I'd spend all 9 lives with you.")
    end
})

mainTab:CreateButton({
    Name = "55. Do you have a mirror?...",
    Callback = function()
        chat("Do you have a mirror in your pocket? Because I see myself in your pants.")
    end
})

mainTab:CreateButton({
    Name = "56. Are you a bakery?...",
    Callback = function()
        chat("Are you a bakery? Because you’re making my heart rise.")
    end
})

mainTab:CreateButton({
    Name = "57. Are you a bank?...",
    Callback = function()
        chat("Are you a bank? Because you have my interest.")
    end
})

mainTab:CreateButton({
    Name = "58. Is your dad a boxer?...",
    Callback = function()
        chat("Is your dad a boxer? Because you're a knockout.")
    end
})

mainTab:CreateButton({
    Name = "59. Are you made of copper and tellurium?...",
    Callback = function()
        chat("Are you made of copper and tellurium? Because you're Cu-Te.")
    end
})

mainTab:CreateButton({
    Name = "60. Is your name Chapstick?...",
    Callback = function()
        chat("Is your name Chapstick? Because you’re da balm.")
    end
})

mainTab:CreateButton({
    Name = "61. Are you a loan?...",
    Callback = function()
        chat("Are you a loan? Because you have my interest.")
    end
})

mainTab:CreateButton({
    Name = "62. Do you know karate?...",
    Callback = function()
        chat("Do you know karate? Because your beauty is kicking me.")
    end
})

mainTab:CreateButton({
    Name = "63. Are you a GPS?...",
    Callback = function()
        chat("Are you a GPS? Because I’m lost in your eyes.")
    end
})

mainTab:CreateButton({
    Name = "64. Are you a snowstorm?...",
    Callback = function()
        chat("Are you a snowstorm? Because you're making my heart race.")
    end
})

mainTab:CreateButton({
    Name = "65. Are you a dictionary?...",
    Callback = function()
        chat("Are you a dictionary? Because you add meaning to my life.")
    end
})

mainTab:CreateButton({
    Name = "66. Are you a light bulb?...",
    Callback = function()
        chat("Are you a light bulb? Because you light up my world.")
    end
})

mainTab:CreateButton({
    Name = "67. Is your name Pepsi?...",
    Callback = function()
        chat("Is your name Pepsi? Because you're so-da-licious.")
    end
})

mainTab:CreateButton({
    Name = "68. You must be a parking ticket...",
    Callback = function()
        chat("You must be a parking ticket because you've got 'fine' written all over you.")
    end
})

mainTab:CreateButton({
    Name = "69. Are you a magician?...",
    Callback = function()
        chat("Are you a magician? Because whenever I look at you, everyone else disappears.")
    end
})

mainTab:CreateButton({
    Name = "70. Are you Cinderella?...",
    Callback = function()
        chat("Are you Cinderella? Because when I look at you, time stands still.")
    end
})

mainTab:CreateButton({
    Name = "71. You must be a magician...",
    Callback = function()
        chat("You must be a magician, because whenever I look at you, you make my heart skip a beat.")
    end
})

mainTab:CreateButton({
    Name = "72. Are you a camera?",
    Callback = function()
        chat("Are you a camera? Because every time I look at you, I smile.")
    end
})

mainTab:CreateButton({
    Name = "73. Are you a dictionary?",
    Callback = function()
        chat("Are you a dictionary? Because you give meaning to my life.")
    end
})

mainTab:CreateButton({
    Name = "74. Do you have a compass?",
    Callback = function()
        chat("Do you have a compass? Because I’m lost in your eyes.")
    end
})

mainTab:CreateButton({
    Name = "75. Are you a star?",
    Callback = function()
        chat("Are you a star? Because your beauty lights up my world.")
    end
})

mainTab:CreateButton({
    Name = "76. If you were a vegetable",
    Callback = function()
        chat("If you were a vegetable, you'd be a cutecumber.")
    end
})

mainTab:CreateButton({
    Name = "77. You must be tired",
    Callback = function()
        chat("You must be tired because you’ve been running through my mind all day.")
    end
})

mainTab:CreateButton({
    Name = "78. If you were a fruit",
    Callback = function()
        chat("If you were a fruit, you'd be a fineapple.")
    end
})

mainTab:CreateButton({
    Name = "79. Are you a time machine?",
    Callback = function()
        chat("Are you a time machine? Because I see you in my future.")
    end
})

mainTab:CreateButton({
    Name = "80. Are you the ocean?",
    Callback = function()
        chat("Are you the ocean? Because I’m lost at sea.")
    end
})

mainTab:CreateButton({
    Name = "81. Do you believe in love at first sight?",
    Callback = function()
        chat("Do you believe in love at first sight, or should I walk by again?")
    end
})

mainTab:CreateButton({
    Name = "82. Are you a dictionary?",
    Callback = function()
        chat("Are you a dictionary? Because you add meaning to my life.")
    end
})

mainTab:CreateButton({
    Name = "83. If I were a cat",
    Callback = function()
        chat("If I were a cat, I'd spend all 9 lives with you.")
    end
})

mainTab:CreateButton({
    Name = "84. Are you an angel?",
    Callback = function()
        chat("Are you an angel? Because heaven is missing one.")
    end
})

mainTab:CreateButton({
    Name = "85. Are you a Wi-Fi signal?",
    Callback = function()
        chat("Are you a Wi-Fi signal? Because I’m feeling a connection.")
    end
})

mainTab:CreateButton({
    Name = "86. Do you have a map?",
    Callback = function()
        chat("Do you have a map? Because I keep getting lost in your eyes.")
    end
})

mainTab:CreateButton({
    Name = "87. You must be tired",
    Callback = function()
        chat("You must be tired because you’ve been running through my mind all day.")
    end
})

mainTab:CreateButton({
    Name = "88. Do you have a pencil?",
    Callback = function()
        chat("Do you have a pencil? Because I want to draw a smile on your face.")
    end
})

mainTab:CreateButton({
    Name = "89. Are you a vampire?",
    Callback = function()
        chat("Are you a vampire? Because my heart beats for you.")
    end
})

mainTab:CreateButton({
    Name = "90. Are you a parking ticket?",
    Callback = function()
        chat("Are you a parking ticket? Because you've got 'fine' written all over you.")
    end
})

mainTab:CreateButton({
    Name = "91. Is your dad a boxer?",
    Callback = function()
        chat("Is your dad a boxer? Because you're a knockout.")
    end
})

mainTab:CreateButton({
    Name = "92. Are you a mirror?",
    Callback = function()
        chat("Are you a mirror? Because I can see myself in your future.")
    end
})

mainTab:CreateButton({
    Name = "93. Are you an angel?",
    Callback = function()
        chat("Are you an angel? Because I think I've finally found heaven on earth.")
    end
})

mainTab:CreateButton({
    Name = "94. If beauty were a crime",
    Callback = function()
        chat("If beauty were a crime, you'd be serving a life sentence.")
    end
})

mainTab:CreateButton({
    Name = "95. Is your name Google?",
    Callback = function()
        chat("Is your name Google? Because you’ve got everything I’ve been searching for.")
    end
})

mainTab:CreateButton({
    Name = "96. Are you a wizard?",
    Callback = function()
        chat("Are you a wizard? Because every time I look at you, everyone else disappears.")
    end
})

mainTab:CreateButton({
    Name = "97. If kisses were snowflakes",
    Callback = function()
        chat("If kisses were snowflakes, I’d send you a blizzard.")
    end
})

mainTab:CreateButton({
    Name = "98. Do you have a sunburn?",
    Callback = function()
        chat("Do you have a sunburn? Or are you always this hot?")
    end
})

mainTab:CreateButton({
    Name = "99. Are you a time traveler?",
    Callback = function()
        chat("Are you a time traveler? Because I see you in my future.")
    end
})

mainTab:CreateButton({
    Name = "100. If you were a fruit",
    Callback = function()
        chat("If you were a fruit, you'd be a fineapple.")
    end
})

