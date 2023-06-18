# LIS2DW12-Driver-STM32

Usage:

    LIS2 lis; // declare driver struct
    LIS2_Init(&lis, &hi2c1); // init driver

    while (1){
        LIS2_Refresh(&lis);  // refresh data
    }
