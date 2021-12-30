# Playing-Cat
This program checks wether cat is playing depending on the season and temperature given 

public class PlayingCat {

    public static boolean isCatPlaying(boolean summer, int temperature) {
        return ((summer && temperature >= 25 && temperature < 46) || (!summer && temperature < 36 && temperature >24));
    }



    public static void main(String[] args) {
        System.out.println(isCatPlaying(true, 46));
    }


}
