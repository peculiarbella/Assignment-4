# Assignment-4
(function () {
    var helloByeGreeter = {};

    var helloByeGreeter, names = "Yaakov, John, Jen, Jason, Paul, Frank, Larry, Paula, Laura, Jim";

    var j = 0; j < names.length; j++; {

        var firstLetter = names[j].charAt(0).toLowerCase();

        if (firstLetter === 'j') {
            byeSpeaker.speak(names[j]);
        } else {
            helloSpeaker.speak(names[j]);
        }
        console.log(greeting + helloByeGreeter.names)
    }

})();
