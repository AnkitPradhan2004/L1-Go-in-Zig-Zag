let N =4;
let M = 4;
let arr =[[1,2,3,4,5],[6,7,8,9,10],[11,12,14,14,15],[16,17,18,19,20]];
for(let i=0; i<N;i++){
    if(i==0 ){
        for(let j=M;j>=0;j--){
            console.log(arr[i][j]);
        }
    }else if(i%2==0){
        for(let j=M;j>=0;j--){
            console.log(arr[i][j]);
        }

    }else{
        for(let j=0;j<M+1;j++){
            console.log(arr[i][j]);
        }
    }
}
