# Copyright (c) 2020 ARM Limited. All rights reserved.
# SPDX-License-Identifier: Apache-2.0

target_sources(mbed-core
    INTERFACE
        stm32f4xx_hal_can_legacy.c
)

target_include_directories(mbed-core
    INTERFACE
        .
)
