# WP-comment-form-form-css


/* ===================== comments ===================== */ 

.comments {margin: 10px 0;}
.comments h3 {margin:50px 0 30px 0;font-size:24px;}
ol.commentlist { list-style:none; margin:0 0 1em; padding:0; text-indent:0; }
ol.commentlist li { }
ol.commentlist li.alt { }
ol.commentlist li.bypostauthor {}
ol.commentlist li.byuser {}
ol.commentlist li.comment-author-admin {}
ol.commentlist li.comment { border-bottom: 1px solid #ddd; padding:1em; margin-bottom: 10px; }
ol.commentlist li div.comment-author {}
ol.commentlist li div.vcard { font-size:20px;}
ol.commentlist li div.vcard cite.fn { font-style:normal; }
ol.commentlist li div.vcard cite.fn a.url {}
ol.commentlist li div.vcard img.avatar {float:left; margin:0 1em 1em 0; }
ol.commentlist li div.vcard img.avatar-32 {}
ol.commentlist li div.vcard img.photo {}
ol.commentlist li div.vcard span.says {}
ol.commentlist li div.commentmetadata {}
ol.commentlist li div.comment-meta { font-size:9px; margin-bottom: 10px;}
ol.commentlist li div.comment-meta a { color: #aaa; }
ol.commentlist li p { margin: 0; }
ol.commentlist li ul { list-style:square; margin:0 0 1em 2em; }
ol.commentlist li div.reply { font-size:11px; }
ol.commentlist li div.reply a { font-weight:bold; }
ol.commentlist li ul.children { list-style:none; margin:1em 0 0; text-indent:0; }
ol.commentlist li ul.children li {}
ol.commentlist li ul.children li.alt {}
ol.commentlist li ul.children li.bypostauthor {}
ol.commentlist li ul.children li.byuser {}
ol.commentlist li ul.children li.comment {}
ol.commentlist li ul.children li.comment-author-admin {}
ol.commentlist li ul.children li.depth-2 { margin:0 0 .25em .25em; }
ol.commentlist li ul.children li.depth-3 { margin:0 0 .25em .25em; }
ol.commentlist li ul.children li.depth-4 { margin:0 0 .25em .25em; }
ol.commentlist li ul.children li.depth-5 {}
ol.commentlist li ul.children li.odd {}
ol.commentlist li.even { background:#fff; }
ol.commentlist li.odd { background:#f6f6f6; }
ol.commentlist li.parent { }
ol.commentlist li.pingback { margin: 0 0 10px; padding: 1em; border: 1px dashed #ccc; }
ol.commentlist li.thread-alt { }
ol.commentlist li.thread-even { }
ol.commentlist li.thread-odd {}

/* ===================== comment form ===================== */ 

#respond {position: relative;}
#respond input[type="text"],#respond textarea {border:1px solid #ddd;padding:10px}
#respond input[type="text"] {padding:7px;width:300px}
#respond .comment-form-author,
#respond .comment-form-email,
#respond .comment-form-url,
#respond .comment-form-comment { position: relative; }
#respond .comment-form-author label,
#respond .comment-form-email label,
#respond .comment-form-url label,
#respond .comment-form-comment label { background: #eee; color: #555; display: inline-block; left: 4px; min-width: 60px; padding: 4px 10px; position: relative; top: 40px; z-index: 1; }
#respond input[type="text"]:focus,
#respond textarea:focus { text-indent: 0; z-index: 1; }
#respond textarea { resize: vertical; width: 95%; }
#respond .comment-form-author .required,
#respond .comment-form-email .required { color: #bd3500; font-size: 22px; font-weight: bold; left: 75%; position: absolute; top: 45px; z-index: 1; }
#respond .comment-notes,
#respond .logged-in-as { font-size: 13px; }
#respond p { margin: 10px 0; }
#respond .form-submit { float: right; margin: -20px 0 10px; }
#respond input#submit { background: #454545; border: none; -moz-border-radius: 3px; border-radius: 3px; -webkit-box-shadow: 0px 1px 2px rgba(0,0,0,0.3); -moz-box-shadow: 0px 1px 2px rgba(0,0,0,0.3); box-shadow: 0px 1px 2px rgba(0,0,0,0.3); color: #eee; cursor: pointer; padding: 5px 42px 5px 22px; }
#respond input#submit:active { background: #86222D; color: #fff; }
#respond #cancel-comment-reply-link { color: #666; margin-left: 10px; text-decoration: none; }
#respond .logged-in-as a:hover,
#respond #cancel-comment-reply-link:hover { text-decoration: underline; }
.commentlist #respond { margin: 1.625em 0 0; width: auto; }
#reply-title { color: #373737; font-size: 20px; }
#cancel-comment-reply-link { color: #888; display: block; position: absolute; right: 1.625em; text-decoration: none; text-transform: uppercase; top: 1.1em; }
#cancel-comment-reply-link:focus,
#cancel-comment-reply-link:active,
#cancel-comment-reply-link:hover { color: #ff4b33; }
#respond label {display: block; float: right; font-size: 16px; line-height: 2.2em; width: 280px;}
#respond input[type=text] {}
#respond p { font-size: 12px; }
p.comment-form-comment { margin: 0; }
.form-allowed-tags { display: none; }
.trackback { margin: 0 0 10px; padding: 1em; border: 1px dashed #ccc; }
