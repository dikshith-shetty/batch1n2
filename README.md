package com.rc.Hello;

import java.util.HashMap;
import java.util.HashSet;
import java.util.TreeMap;

public class maptree {
    public static void main(String[] args) {
    TreeMap<Long,String> tm=new TreeMap<>();
    tm.put(1324567890l,"vikram");
    tm.put(123456789l,"tacchu");
    tm.put(1234567890l,"shubbu");
    tm.put(123434567890l,"mtr");
    System.out.println(tm);
        HashMap<Long,String> hm=new HashMap<>();
        hm.put(1324567890l,"vikram");
        hm.put(1234567890l,"tacchu");
        hm.put(1234567890l,"shubbu");
        hm.put(123434567890l,"mtr");
        System.out.println(hm);
        HashSet<Long> set=new HashSet<>();
    }
}
