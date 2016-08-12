---
layout: post
title:  " Reading and writing to HIVE using Java "
categories: [Hadoop]
tags: [Hadoop,Java,JDBC]
icon: icon-hadoop
---

Hey and welcome back to my blog.

Since I'm new to the blogging game I've decided to start with a simple yet useful tutorial.



``` java
public class HiveTest {

    private static String driverName = "org.apache.hive.jdbc.HiveDriver";
    private static String tableName = "nameage";

    public static void main(String[] args) throws SQLException, ClassNotFoundException, IOException, URISyntaxException {

        // Register driver and create driver instance
        Class.forName(driverName);

```
