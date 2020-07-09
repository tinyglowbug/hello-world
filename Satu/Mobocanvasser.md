---
title: "Initiative - Mobocanvaser"
date: "2019-07-09"
Access: "Private"
---


# Summary

Mobo merupakan sebuah chip yang digunakan outlet/konter pulsa untuk
mengisi ulang nomor pembeli dengan menggunakan sistem Dial. Chip ini
selain bisa mengisi pulsa reguler juga digunakan untuk melakukan top up
paket data / internet dan pulsa sms Canvasser adalah orang yang
melakukan proses penjualan dengan melakukan kontak langsung dengan
pelanggannya.

## Background

Traditional Channel Canvaser Platform

## Business Requirements

In Q2 2017, Sepulsa get the opportunity to cooperate with one of MPC
(Mitra Penyelenggara Cluster) for Indosat Operator, which is PT. Akses
Komunikasi Indonesia. PT. AKI as a Indosat Authorised Distributor has a
traditional way to distribute “PULSA” & “PAKET DATA” to their customer
(Reseller).

Sepulsa makes a platform that digitalize that process of distribution.
Sepulsa make a platform to receive order from Field Canvasser (Sales
Person) via Android Apps. and make platform that collect the data from
Indosat MOBO website and build the report that used for Reporting
progress of KPI per canvasser per month

## List of System

| No.  | System                                          | Description                                                  |
| ---- | ----------------------------------------------- | ------------------------------------------------------------ |
| 1    | [KrakenDist](System/KrakenDist "wikilink")      | Backend that has function to receive request from apps, then forwarded to modem and modem will refill top up mobo deposit to device / mobile phone with indosat chip |
| 2    | [Flamingo](System/Apps_\(Flamingo\) "wikilink") | Frontend Canvaser                                            |

## High Level Architecture

