(function (ext) {
    // Define the extension's name and blocks here

    // List of random facts
    var randomFacts = [
        "The Earth is approximately 4.5 billion years old.",
        "The cheetah is the fastest land animal, reaching speeds up to 70 mph (113 km/h).",
        "The Great Wall of China is visible from space.",
        "The average human body contains enough iron to make a small nail.",
        "Honey never spoils. Archaeologists have found pots of honey in ancient Egyptian tombs that are over 3,000 years old and still perfectly edible."
    ];

    // Block to get a random fact
    ext.getRandomFact = function () {
        var fact = randomFacts[Math.floor(Math.random() * randomFacts.length)];
        return fact;
    };

    // Block and descriptor for the "get random fact" block
    var descriptor = {
        blocks: [
            ['r', 'get random fact', 'getRandomFact']
        ]
    };

    // Register the extension
    ScratchExtensions.register('Random Facts', descriptor, ext);
})({});
