code of egui example: https://github.com/emilk/egui/blob/0.17.0/egui_glow/examples/pure_glow.rs

RUST_BACKTRACE=1 cargo run

Sometimes got error:

[xcb] Unknown sequence number while processing queue  
[xcb] Most likely this is a multi-threaded client and XInitThreads has not been called  
[xcb] Aborting, sorry about that.  
sequence_lost: xcb_io.c:269: poll_for_event: Assertion `!xcb_xlib_threads_sequence_lost' failed.  
Aborted (core dumped)
