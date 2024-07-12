
# multithread
class csi extends Thread{
public void run(){
    for(int i=1;i<=5;i++){
        System.out.println(i*5);
        try{
            Thread.sleep(2000);
        }
        catch(interrupted Exception e){

        }
    }
}
}
class nec extends Threads{
    public void run()
    {
        for(int i=0;i<5;i++){
            System.out.println("NEC");
            try{
                Thread.sleep(3000);
            }
            catch(IntereuptedException e){
                
            }
        }
    }
}
