# Combined.dates_project

  <body>
                <h1 id="res">                            
                        </h1>
                <button onclick="getDate()"> DATE </button>   
                <button onclick="Year()"> YEAR </button>  
                <button onclick="month()"> MONTH </button> 
                <button onclick="millisecond()"> MILLISECOND </button> 
                <button onclick="second()"> SECOND </button>        
                <button onclick="date()"> GETDATE </button>        
                <button onclick="hour()"> HOUR </button>        
                <button onclick="time()"> TIME </button>         
                <button onclick="day()"> DAY </button>   
                <button onclick="minute()"> MINUTE </button> 
                <script>
                        var x = new Date();                   // new Date is used for call date and time
                        function getDate()
                        {
                          document.getElementById("res").innerText = x;                        
                        }                       
                        function Year()
                            {
                                document.getElementById("res").innerText = x.getFullYear();
                            }                        
                        function month()
                        {
                                var y = ["January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December" ];
                               document.getElementById("res").innerText = y[x.getMonth()];
                        }
                        function millisecond()
                        {
                            document.getElementById("res").innerText = x.getMilliseconds();
                        }
                        function second()
                        {
                            document.getElementById("res").innerText = x.getSeconds();
                        }
                        function date()
                        {
                            document.getElementById("res").innerText = x.getDate();
                        }
                        function hour()
                        {
                            document.getElementById("res").innerText = x.getHours();
                        }
                        function time()
                        {
                            document.getElementById("res").innerText = x.getTime();         // time in millisecond since jan, 01 , 1970
                        }
                        function day()
                        {
                            document.getElementById("res").innerText = x.getDay();
                        }
                        function minute()
                        {
                            document.getElementById("res").innerText = x.getMinutes();
                        }                       
                </script>
</body>
