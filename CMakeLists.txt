cmake_minimum_required(VERSION 3.27)
project(QuanLyThuVien)

set(CMAKE_CXX_STANDARD 17)

add_executable(QuanLyThuVien main.cpp
        Macro.h
        mylib.h
        GlobalVariable.h
        mylib.cpp
        N17DCCN095_NPNMinh.cpp
        Xu_Ly.h
        Xu_Ly.cpp
        DSDocGia.h
        DSDocGia.cpp
        DauSach.h
        DauSach.cpp
        Ve_Hinh.h
        Ve_Hinh.cpp
        XuLyTam.h
        XuLyTam.cpp
        Muon_Tra.h
        Muon_Tra.cpp
        Ngay_Thang.h
        Ngay_Thang.cpp
        Check_Nhap.h
        Check_Nhap.cpp
        stdafx.h
        stdafx.cpp
        targetver.h)
