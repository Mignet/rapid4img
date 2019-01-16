# rapid4img
```shell
mignet@Master:~/rust-projects/upfile$ cargo run
   Compiling upfile v0.1.0 (file:///home/mignet/rust-projects/upfile)
     Running `target/debug/upfile`
file load!start : 2016-04-17T16:00:49+08:00,end :2016-04-17T16:00:49+08:00,duration:PT0.000094890S
md5 load!start : 2016-04-17T16:00:49+08:00,end :2016-04-17T16:00:49+08:00,duration:PT0.023411631S
img load!start : 2016-04-17T16:00:49+08:00,end :2016-04-17T16:00:52+08:00,duration:PT2.621793752S
save file!start : 2016-04-17T16:00:52+08:00,end :2016-04-17T16:00:55+08:00,duration:PT3.651583434S
Field "userfile" is file "StarUml.png":
```

```shell
mignet@Master:~/rust-projects/upfile$ cargo run --release
   Compiling upfile v0.1.0 (file:///home/mignet/rust-projects/upfile)
     Running `target/release/upfile`
file load!start : 2016-04-17T16:02:28+08:00,end :2016-04-17T16:02:28+08:00,duration:PT0.000099016S
md5 load!start : 2016-04-17T16:02:28+08:00,end :2016-04-17T16:02:28+08:00,duration:PT0.001155275S
img load!start : 2016-04-17T16:02:28+08:00,end :2016-04-17T16:02:28+08:00,duration:PT0.055703035S
save file!start : 2016-04-17T16:02:28+08:00,end :2016-04-17T16:02:28+08:00,duration:PT0.375560153S
Field "userfile" is file "StarUml.png":
```
