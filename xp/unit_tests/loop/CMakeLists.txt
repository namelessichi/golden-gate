# Copyright 2017-2020 Fitbit, Inc
# SPDX-License-Identifier: Apache-2.0

gg_add_test(test_gg_loop.cpp "gg-loop;gg-utils")
if (GG_PORTS_ENABLE_POSIX_THREADS)
    gg_add_test(test_gg_loop_with_threads.cpp "gg-loop")
endif()
