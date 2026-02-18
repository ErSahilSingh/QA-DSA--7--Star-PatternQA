# QA-DSA--7--Star-PatternQA

function Starpatten(n) {
    for (let i = 0; i < n; i++){
        let stat = ""
        for (let j = 0; j <= i; j++){
            stat=stat+ "*"
        }
        console.log(stat)
    }
    
}
Starpatten(5)
-------------------------------------------------
function Starpatten(n) {
    for (let i = 0; i < n; i++){
        let stat = ""
        for (let j = 0; j <= i; j++){
            stat=stat+ (j +1)
        }
        console.log(stat)
    }
    
}
Starpatten(6)



--------------------------------------------------

function Starpatten(n) {
    for (let i = 0; i < n; i++){
        let stat = ""
        for (let j = 0; j <n; j++){
            stat=stat+ j 
        }
        console.log(stat)
    }
    
}
Starpatten(6)
