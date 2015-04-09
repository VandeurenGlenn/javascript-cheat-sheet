    <script> 
        var user = {name: "hi", function: "demo", date: "9/04/2015"};
        var data;
        var userData = "";
        
        for (data in user) {
            userData += user[data] + "<br>";
        }
        console.log("currentUser: name=" + user.name + ", function=" + user.function + ", date=" + user.date);
    </script>
