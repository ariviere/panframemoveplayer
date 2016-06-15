# PanFrame Move Player

Playing a 4K video doesn't work on LG G4, Samsung Note 3 and Samsung Galaxy S6 phones (all different versions of the OS). Working well on Nexus 6P and Moto G3. 

Here is the stacktrace on Samsung Note 3 :

E/PanframeNovaPlayerImpl: Internal runtime error. java.lang.IndexOutOfBoundsException: Invalid index 0, size is 0 at java.util.ArrayList.throwIndexOutOfBoundsException(ArrayList.java:255) at java.util.ArrayList.get(ArrayList.java:308) at com.a.a.a.f.u.b(Unknown Source) at com.a.a.a.f.u.b(Unknown Source) at com.a.a.a.f.n.a(Unknown Source) at com.a.a.a.X.a(Unknown Source) at com.a.a.a.m.c(Unknown Source) at com.a.a.a.p.g(Unknown Source) at com.a.a.a.p.handleMessage(Unknown Source) at android.os.Handler.dispatchMessage(Handler.java:98) at android.os.Looper.loop(Looper.java:157) at android.os.HandlerThread.run(HandlerThread.java:61) at com.a.a.a.k.x.run(Unknown Source)
