07-08 01:45:14.568 30758 30758 E AndroidRuntime: *** FATAL EXCEPTION IN SYSTEM PROCESS: main
07-08 01:45:14.568 30758 30758 E AndroidRuntime: java.lang.RuntimeException: Failed to boot service com.android.server.ethernet.EthernetService: onBootPhase threw an exception during phase 500
07-08 01:45:14.568 30758 30758 E AndroidRuntime: 	at com.android.server.SystemServiceManager.startBootPhase(SystemServiceManager.java:238)
07-08 01:45:14.568 30758 30758 E AndroidRuntime: 	at com.android.server.SystemServer.startOtherServices(SystemServer.java:2591)
07-08 01:45:14.568 30758 30758 E AndroidRuntime: 	at com.android.server.SystemServer.run(SystemServer.java:885)
07-08 01:45:14.568 30758 30758 E AndroidRuntime: 	at com.android.server.SystemServer.main(SystemServer.java:616)
07-08 01:45:14.568 30758 30758 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 01:45:14.568 30758 30758 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:548)
07-08 01:45:14.568 30758 30758 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:981)
07-08 01:45:14.568 30758 30758 E AndroidRuntime: Caused by: java.lang.NullPointerException: Attempt to invoke virtual method 'java.net.InetAddress android.net.LinkAddress.getAddress()' on a null object reference
07-08 01:45:14.568 30758 30758 E AndroidRuntime: 	at com.android.server.net.IpConfigStore.readIpConfigurations(IpConfigStore.java:326)
07-08 01:45:14.568 30758 30758 E AndroidRuntime: 	at com.android.server.net.IpConfigStore.readIpConfigurations(IpConfigStore.java:215)
07-08 01:45:14.568 30758 30758 E AndroidRuntime: 	at com.android.server.ethernet.EthernetConfigStore.read(EthernetConfigStore.java:46)
07-08 01:45:14.568 30758 30758 E AndroidRuntime: 	at com.android.server.ethernet.EthernetTracker.start(EthernetTracker.java:146)
07-08 01:45:14.568 30758 30758 E AndroidRuntime: 	at com.android.server.ethernet.EthernetServiceImpl.start(EthernetServiceImpl.java:83)
07-08 01:45:14.568 30758 30758 E AndroidRuntime: 	at com.android.server.ethernet.EthernetService.onBootPhase(EthernetService.java:42)
07-08 01:45:14.568 30758 30758 E AndroidRuntime: 	at com.android.server.SystemServiceManager.startBootPhase(SystemServiceManager.java:235)
07-08 01:45:14.568 30758 30758 E AndroidRuntime: 	... 6 more
07-08 01:45:16.775 30917 30917 D AndroidRuntime: >>>>>> START com.android.internal.os.ZygoteInit uid 0 <<<<<<
07-08 01:45:16.778 30917 30917 I AndroidRuntime: Using default boot image
07-08 01:45:16.778 30917 30917 I AndroidRuntime: Leaving lock profiling enabled
07-08 01:45:16.784 30918 30918 D AndroidRuntime: >>>>>> START com.android.internal.os.ZygoteInit uid 0 <<<<<<
07-08 01:45:16.788 30918 30918 I AndroidRuntime: Using default boot image
07-08 01:45:16.788 30918 30918 I AndroidRuntime: Leaving lock profiling enabled
07-08 01:45:16.821  6028  6028 I ExynosCameraInterface: DEBUG(HAL_getNumberOfCameras[607]):Number of cameras(6)
07-08 01:45:16.821  6028  7183 I ExynosCameraInterface: DEBUG(HAL_getNumberOfCameras[607]):Number of cameras(6)
07-08 01:45:16.821  6028  6028 I ExynosCameraInterface: DEBUG(HAL_getNumberOfCameras[607]):Number of cameras(6)
07-08 01:45:16.822  6028  7183 I ExynosCameraInterface: DEBUG(HAL_getNumberOfCameras[607]):Number of cameras(6)
07-08 01:45:16.822  6028  6028 I ExynosCameraInterface: DEBUG(HAL_getNumberOfCameras[607]):Number of cameras(6)
07-08 01:45:16.822  6028  6028 I ExynosCameraInterface: DEBUG(HAL_getNumberOfCameras[607]):Number of cameras(6)
07-08 01:45:16.823  6028  7183 I ExynosCameraInterface: DEBUG(HAL_getNumberOfCameras[607]):Number of cameras(6)
07-08 01:45:19.542 30991 30991 D AndroidRuntime: Shutting down VM
07-08 01:45:19.543 30991 30991 E AndroidRuntime: *** FATAL EXCEPTION IN SYSTEM PROCESS: main
07-08 01:45:19.543 30991 30991 E AndroidRuntime: java.lang.RuntimeException: Failed to boot service com.android.server.ethernet.EthernetService: onBootPhase threw an exception during phase 500
07-08 01:45:19.543 30991 30991 E AndroidRuntime: 	at com.android.server.SystemServiceManager.startBootPhase(SystemServiceManager.java:238)
07-08 01:45:19.543 30991 30991 E AndroidRuntime: 	at com.android.server.SystemServer.startOtherServices(SystemServer.java:2591)
07-08 01:45:19.543 30991 30991 E AndroidRuntime: 	at com.android.server.SystemServer.run(SystemServer.java:885)
07-08 01:45:19.543 30991 30991 E AndroidRuntime: 	at com.android.server.SystemServer.main(SystemServer.java:616)
07-08 01:45:19.543 30991 30991 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 01:45:19.543 30991 30991 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:548)
07-08 01:45:19.543 30991 30991 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:981)
07-08 01:45:19.543 30991 30991 E AndroidRuntime: Caused by: java.lang.NullPointerException: Attempt to invoke virtual method 'java.net.InetAddress android.net.LinkAddress.getAddress()' on a null object reference
07-08 01:45:19.543 30991 30991 E AndroidRuntime: 	at com.android.server.net.IpConfigStore.readIpConfigurations(IpConfigStore.java:326)
07-08 01:45:19.543 30991 30991 E AndroidRuntime: 	at com.android.server.net.IpConfigStore.readIpConfigurations(IpConfigStore.java:215)
07-08 01:45:19.543 30991 30991 E AndroidRuntime: 	at com.android.server.ethernet.EthernetConfigStore.read(EthernetConfigStore.java:46)
07-08 01:45:19.543 30991 30991 E AndroidRuntime: 	at com.android.server.ethernet.EthernetTracker.start(EthernetTracker.java:146)
07-08 01:45:19.543 30991 30991 E AndroidRuntime: 	at com.android.server.ethernet.EthernetServiceImpl.start(EthernetServiceImpl.java:83)
07-08 01:45:19.543 30991 30991 E AndroidRuntime: 	at com.android.server.ethernet.EthernetService.onBootPhase(EthernetService.java:42)
07-08 01:45:19.543 30991 30991 E AndroidRuntime: 	at com.android.server.SystemServiceManager.startBootPhase(SystemServiceManager.java:235)
07-08 01:45:19.543 30991 30991 E AndroidRuntime: 	... 6 more
07-08 01:45:21.773 31148 31148 D AndroidRuntime: >>>>>> START com.android.internal.os.ZygoteInit uid 0 <<<<<<
07-08 01:45:21.778 31148 31148 I AndroidRuntime: Using default boot image
07-08 01:45:21.778 31148 31148 I AndroidRuntime: Leaving lock profiling enabled
07-08 01:45:21.792 31149 31149 D AndroidRuntime: >>>>>> START com.android.internal.os.ZygoteInit uid 0 <<<<<<
07-08 01:45:21.796 31149 31149 I AndroidRuntime: Using default boot image
07-08 01:45:21.796 31149 31149 I AndroidRuntime: Leaving lock profiling enabled
07-08 01:45:21.825  6028  7183 I ExynosCameraInterface: DEBUG(HAL_getNumberOfCameras[607]):Number of cameras(6)
07-08 01:45:21.826  6028  7183 I ExynosCameraInterface: DEBUG(HAL_getNumberOfCameras[607]):Number of cameras(6)
07-08 01:45:21.826  6028  6296 I ExynosCameraInterface: DEBUG(HAL_getNumberOfCameras[607]):Number of cameras(6)
07-08 01:45:21.827  6028  7183 I ExynosCameraInterface: DEBUG(HAL_getNumberOfCameras[607]):Number of cameras(6)
07-08 01:45:21.827  6028  7183 I ExynosCameraInterface: DEBUG(HAL_getNumberOfCameras[607]):Number of cameras(6)
07-08 01:45:21.828  6028  7183 I ExynosCameraInterface: DEBUG(HAL_getNumberOfCameras[607]):Number of cameras(6)
07-08 01:45:21.828  6028  6296 I ExynosCameraInterface: DEBUG(HAL_getNumberOfCameras[607]):Number of cameras(6)
07-08 01:45:24.578 31221 31221 D AndroidRuntime: Shutting down VM
07-08 01:45:24.578 31221 31221 E AndroidRuntime: *** FATAL EXCEPTION IN SYSTEM PROCESS: main
07-08 01:45:24.578 31221 31221 E AndroidRuntime: java.lang.RuntimeException: Failed to boot service com.android.server.ethernet.EthernetService: onBootPhase threw an exception during phase 500
07-08 01:45:24.578 31221 31221 E AndroidRuntime: 	at com.android.server.SystemServiceManager.startBootPhase(SystemServiceManager.java:238)
07-08 01:45:24.578 31221 31221 E AndroidRuntime: 	at com.android.server.SystemServer.startOtherServices(SystemServer.java:2591)
07-08 01:45:24.578 31221 31221 E AndroidRuntime: 	at com.android.server.SystemServer.run(SystemServer.java:885)
07-08 01:45:24.578 31221 31221 E AndroidRuntime: 	at com.android.server.SystemServer.main(SystemServer.java:616)
07-08 01:45:24.578 31221 31221 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-08 01:45:24.578 31221 31221 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:548)
07-08 01:45:24.578 31221 31221 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:981)
07-08 01:45:24.578 31221 31221 E AndroidRuntime: Caused by: java.lang.NullPointerException: Attempt to invoke virtual method 'java.net.InetAddress android.net.LinkAddress.getAddress()' on a null object reference
07-08 01:45:24.578 31221 31221 E AndroidRuntime: 	at com.android.server.net.IpConfigStore.readIpConfigurations(IpConfigStore.java:326)
07-08 01:45:24.578 31221 31221 E AndroidRuntime: 	at com.android.server.net.IpConfigStore.readIpConfigurations(IpConfigStore.java:215)
07-08 01:45:24.578 31221 31221 E AndroidRuntime: 	at com.android.server.ethernet.EthernetConfigStore.read(EthernetConfigStore.java:46)
07-08 01:45:24.578 31221 31221 E AndroidRuntime: 	at com.android.server.ethernet.EthernetTracker.start(EthernetTracker.java:146)
07-08 01:45:24.578 31221 31221 E AndroidRuntime: 	at com.android.server.ethernet.EthernetServiceImpl.start(EthernetServiceImpl.java:83)
07-08 01:45:24.578 31221 31221 E AndroidRuntime: 	at com.android.server.ethernet.EthernetService.onBootPhase(EthernetService.java:42)
07-08 01:45:24.578 31221 31221 E AndroidRuntime: 	at com.android.server.SystemServiceManager.startBootPhase(SystemServiceManager.java:235)
