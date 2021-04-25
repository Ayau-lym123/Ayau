# Ayau
package com.company;

public class Main {

    public static void main(String[] args) {

        MyArrayList arrayList = new MyArrayList();

        arrayList.add(1);

        arrayList.add(2);

        arrayList.add(3);

        arrayList.add(4);

        arrayList.add(5);
        arrayList.add(6);
        arrayList.add(7);
        for(int i = 0; i < arrayList.getSize(); i++){
            System.out.print(arrayList.get(i) + " ");
        }

        System.out.println();

        arrayList.reverse();

        for(int i = 0; i < arrayList.getSize(); i++){
            System.out.print(arrayList.get(i) + " ");
        }
        System.out.println();
        System.out.println(arrayList.find(5));

        arrayList.remove(arrayList.find(5));

        for(int i = 0; i < arrayList.getSize(); i++){
            System.out.print(arrayList.get(i) + " ");
        }
        System.out.println();

        System.out.println(arrayList.find(5));




    }
}
