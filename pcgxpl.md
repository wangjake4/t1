代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gtpvakiqtj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gzhubu.top/Article/details/gtwtbalmzw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dashuyun.cn/Article/details/gtehdwifhh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yangfankeji.com/Article/details/gtczyxpwzr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxefpxdmt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hywenlv.cn/Article/details/gtxtynhmip.html

[E16] 数字千分位
来源：http://dali.chenlongwang.top/Article/details/gtbayhbjxu.html

Py:   f"{1234567:,}"
来源：http://dali.yangfankeji.com/Article/details/gtarclhgcl.html

PHP:  number_format(1234567);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrqyohyf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daria6918.cn/Article/details/gtyczqzxqw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gtufratrma.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqgstcwi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.mhx1999.top/Article/details/gtwaevhifi.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkiandgrl.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gtvynahynk.html

[E17] 首字母大写
来源：http://dali.jinqigfzy.top/Article/details/gtyawtfscl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.haohaochexian.top/Article/details/gtdqhmdffu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnqzz.top/Article/details/gtzqsormnu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.redwolf501.top/Article/details/gtewwmvsdz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkxfhuna.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yongpay.top/Article/details/gttlukbhbx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuanzhike.top/Article/details/gtrceplnvr.html

Ruby: s.capitalize
来源：http://dali.zhongyouzk.top/Article/details/gtgpnsdntw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cdnleiting.top/Article/details/gtuymzahrh.html

[E18] 模板占位符替换
来源：http://dali.daria6918.cn/Article/details/gttkrjuobr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj20258888.top/Article/details/gtgmdqgbld.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guowangkeji.top/Article/details/gtbokajcuv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtzajsbads.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gtqdoaqjiw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtlzujujek.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtpxbarnbc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.meibo888.top/Article/details/gtdukzwjmo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenzaomai.com/Article/details/gtxrtmoukm.html

[E19] 多行文本按行拆分
来源：http://dali.zhixingplan.top/Article/details/gtgfzzxpti.html

Py:   s.splitlines()
来源：http://dali.vqdsnc.cn/Article/details/gtkruutxgp.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangdashe.top/Article/details/gtdztvqnqz.html

JS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gtmshqsnrn.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxuanxn.top/Article/details/gtgzpcnhhl.html

Java: s.lines().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtwltzaagx.html

Go:   strings.Split(s, "\n")
来源：http://dali.pycfn.com/Article/details/gtxhxeblvt.html

Ruby: s.lines
来源：http://dali.zhixingplan.top/Article/details/gtyvgadjqd.html

C#:   s.Split('\n')
来源：http://dali.aizwys.cn/Article/details/gtmdnpmevx.html

[E20] 判断字符串是否为空
来源：http://dali.dashuyun.cn/Article/details/gtkxnquiqm.html

Py:   if not s:
来源：http://dali.guannengcc.top/Article/details/gtrvgmwdam.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sxryk.cn/Article/details/gthmgyymxm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.iojbl.cn/Article/details/gtqanvpfvn.html

TS:   if (s === "") {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdraugyf.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtivkzjrex.html

Go:   if s == "" {}
来源：http://dali.sweek.top/Article/details/gtpbwpqtmv.html

Ruby: if s.empty?
来源：http://dali.jinghuilouyu.cn/Article/details/gtuyjgffgg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtkkvfvuxr.html

[E21] 超长截断加省略号
来源：http://dali.sufxvd.cn/Article/details/gthognhbys.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhongyouzk.top/Article/details/gtvrpifwsi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtalgxamix.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtvkvembof.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtoaomxbyw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gtraqybmva.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.birdmap.top/Article/details/gtuitgeazj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtmotmoxve.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gtjcoqllmh.html

[E22] 字节长度与字符长度
来源：http://dali.zhiwuduotai.top/Article/details/gtswgyuiae.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yangfankeji.com/Article/details/gtiryvwmza.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtqntzchjg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtsyrirjpx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gtpeayrwpa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangdashe.top/Article/details/gtcmxalgdl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgufenzy.top/Article/details/gtkopcfkfr.html

Ruby: s.bytesize;  s.length
来源：http://dali.aizwys.cn/Article/details/gtihxfatuw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zdqjudy.top/Article/details/gtrnlliitz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtknlmugkw.html

F. 文件与目录
来源：http://dali.yj20258.top/Article/details/gtapmobnvp.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtdsqagbac.html

[F01] 读取整个文件
来源：http://dali.dashuyun.cn/Article/details/gtsdrsnjbq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aibaodan.cn/Article/details/gtehkmcsjd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtzavlujtl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuanzx.com/Article/details/gteneovjsr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtukulkcfd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtrlbbufgm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sweek.top/Article/details/gtnpbdzvhx.html

Ruby: File.read("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfmhgeib.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtgsvajhdp.html

[F02] 逐行读取文件
来源：http://dali.ppjwa.cn/Article/details/gtqsoviiow.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.svipenyu.cn/Article/details/gtcfyqnqkr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jyoumei.cn/Article/details/gtvhzvtdjl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtfwrbxagj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gtwaopapln.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtaiplnskf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.mhx1999.top/Article/details/gtsvwejhez.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhengqikj.top/Article/details/gtmsbcpkxj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.smart0.xyz/Article/details/gtjfnqupdw.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gtwzvieola.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxinkj.top/Article/details/gttecwzeuk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtptffyrwq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtqelopfhs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtsyhldbpw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.andypj.xyz/Article/details/gtpgrxcyxz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jlsjyb.cn/Article/details/gtsxmvvsns.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gtvlfpysor.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gtywmbllgi.html

[F04] 追加写入文件
来源：http://dali.shangyingyoupin.top/Article/details/gtnalnbmxh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dianchejie.cn/Article/details/gtpxxwmrma.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aibaodan.cn/Article/details/gtpkvsgpqo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtwcqokhzj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtlqppnnol.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shuidangran.top/Article/details/gtixljpsod.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fzhhl.top/Article/details/gtucoyqxtz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.snrcjt.cn/Article/details/gtfzhgibii.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xinyue.icu/Article/details/gttlkelgkb.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtialpwjyi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daria6918.cn/Article/details/gteebkjuwn.html

PHP:  file_exists("a.txt");
来源：http://dali.ivvv.top/Article/details/gtycgjnymd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtzztxipdi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtuwddcovo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtprusylwy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.andypj.xyz/Article/details/gttwkorfvw.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfqmgjkv.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtbaplrguf.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoiiffkdk.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtbvlpmqoj.html

PHP:  unlink("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtlfwfoqhf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtsqwortuj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gteplatntw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtgjclxluz.html

Go:   os.Remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtbnsfwaij.html

Ruby: File.delete("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtphxbjkfe.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtsroekqeo.html

[F07] 创建目录（含多级）
来源：http://dali.daxiang520.top/Article/details/gtbsfxttix.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gtaqdbztwh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.dashuyun.cn/Article/details/gttwgprdqh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtxgaromzr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtkxepjedl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aizwys.cn/Article/details/gthmbyctwk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xinyue.icu/Article/details/gtxilpqxre.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yanxiufei.cn/Article/details/gtwmqupsfo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangdashe.top/Article/details/gtzkyaudmo.html

[F08] 遍历目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigglcvio.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.bjfxy.top/Article/details/gtfhphfpsz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gtzehksrjm.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnslaoshw.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gtztnefwro.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gtmxjvjmpp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gtxpthmrvp.html

Ruby: Dir.children("dir")
来源：http://dali.daria6918.cn/Article/details/gtmpzrotib.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hysaishi.cn/Article/details/gtqiuftssy.html

[F09] 获取文件大小
来源：http://dali.xuetiantiany.cn/Article/details/gtawwklupx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtpyyifdbv.html

PHP:  filesize("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtzzbfwkvv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtpbvnulgn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtaxjpolkg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtafzvkpfs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gtoydasoan.html

Ruby: File.size("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtvldwojvm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tian-w.cn/Article/details/gtjbzgnhyv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuanzhike.top/Article/details/gtiidabcxd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtrsalnsot.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guannengcc.top/Article/details/gtsnwhmmmv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtviyckaio.html

TS:   path.extname("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitbkkhtq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ehwqpu.com/Article/details/gtvtwwibjs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtsxhholnl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtqjqykwnh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtrnguavmh.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gtdwblycwx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtbgnjqbib.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtrgmllptm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtuinstcil.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtrqtphgku.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtzcwdiwwe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhongyouzk.top/Article/details/gtulpxknxc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtxolomsgh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gtdiipcgvw.html

[F12] CSV 读写
来源：http://dali.nanxinkj.top/Article/details/gtanjkjwhl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aibaodan.cn/Article/details/gtnxfrjhvk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guowangkeji.top/Article/details/gtzqugeuab.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tanke756.top/Article/details/gtbacuoltv.html

TS:   // 同上
来源：http://dali.nanxinkj.top/Article/details/gtymncwqpq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvemyzws.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nwbrower.top/Article/details/gtccnhxxcm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuxming.cn/Article/details/gtctkezuel.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dianchejie.cn/Article/details/gtnhwcjbgc.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtnzsfhwug.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gtogksfzhv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtqtkcshiw.html

[G01] 定义类
来源：http://dali.zhoulong.xyz/Article/details/gtvgujxkyl.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gtlzmxzvqz.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gtbpkmdgvp.html

JS:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlrxhkux.html

TS:   class User { name: string = ""; }
来源：http://dali.nwbrower.top/Article/details/gtsvgafwha.html

Java: class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlybvqgem.html

Go:   type User struct { Name string }
来源：http://dali.jiagoushi.top/Article/details/gtkachfeki.html

Ruby: class User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpdfakdy.html

C#:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtnovqqaum.html

[G02] 构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtqavvqkuu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hammf.cn/Article/details/gtiwyoxwyn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigufen.top/Article/details/gtvxfjekcc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtdtmmkxlh.html

TS:   constructor(public name: string) {}
来源：http://dali.hfpthk.cn/Article/details/gtfyluwxtj.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtwvqswpzz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shangyingyoupin.top/Article/details/gtqfyauowj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gtjwkpghnp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtlqzfysrc.html

[G03] 实例属性
来源：http://dali.zycfv.cn/Article/details/gtaulteawx.html

Py:   self.name = "x"
来源：http://dali.tanke756.top/Article/details/gtbukjxiuy.html

PHP:  public string $name = "x";
来源：http://dali.xylfe.cn/Article/details/gtsqlmkyis.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtpowltkso.html

TS:   name: string = "x";
来源：http://dali.hnqzz.top/Article/details/gtampkeqro.html

Java: private String name;
来源：http://dali.chenlongwang.top/Article/details/gtwqilkiza.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gtvjmbmttb.html

Ruby: @name = "x"
来源：http://dali.mhx1999.top/Article/details/gthkntexav.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sxryk.cn/Article/details/gtciucunfg.html

[G04] 定义方法
来源：http://dali.aizwys.cn/Article/details/gtpcawsjdx.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtfckclbrl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtkanyofjd.html

JS:   greet() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtumywzesk.html

TS:   greet(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtjibxiomk.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtdgqcuppi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtdhpyvtro.html

Ruby: def greet; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gtknlvtltz.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gticjcrljj.html

[G05] 继承
来源：http://dali.zycfv.cn/Article/details/gttkebdawe.html

Py:   class Admin(User): pass
来源：http://dali.jyoumei.cn/Article/details/gthsnudqcm.html

PHP:  class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtbiqplhyb.html

JS:   class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtezijsqkl.html

TS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtmaylvnoa.html

Java: class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtwuhqphwh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gtumuunktq.html

Ruby: class Admin < User; end
来源：http://dali.kuanghao11.cn/Article/details/gtaxndgxjz.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gtimtgsgxq.html

[G06] 重写方法
来源：http://dali.gotoacloud.top/Article/details/gtegjfdaao.html

Py:   def greet(self): return "admin"
来源：http://dali.iojbl.cn/Article/details/gtjwicuxte.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtgkhqhufj.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtfwzeizpz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtkrzkmypd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtyogopnst.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ivvv.top/Article/details/gtnxcvdjwf.html

Ruby: def greet; "admin"; end
来源：http://dali.jyoumei.cn/Article/details/gtzyqytdyc.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgufenzy.top/Article/details/gtvhwdigsm.html

[G07] 调用父类方法
来源：http://dali.xuetiantiany.cn/Article/details/gtcbbrgabo.html

Py:   super().greet()
来源：http://dali.guowangkeji.top/Article/details/gtzmtxehwf.html

PHP:  parent::greet();
来源：http://dali.hnqzz.top/Article/details/gtxzqjlwzr.html

JS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gtlddknutj.html

TS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtbopfdhfp.html

Java: super.greet();
来源：http://dali.tanke756.top/Article/details/gtgkenepfj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.smart0.xyz/Article/details/gtdkjpxbkn.html

Ruby: super
来源：http://dali.yuanzhike.top/Article/details/gtbtgpamdp.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gtmjmjgevn.html

[G08] 静态方法与属性
来源：http://dali.zdqjudy.top/Article/details/gtcuopgblr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuanzhike.top/Article/details/gtzkprvehn.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gthojpsbsm.html

JS:   static f() {}
来源：http://dali.0kj1m.cn/Article/details/gtwamrbgxg.html

TS:   static f(): void {}
来源：http://dali.guannengcc.top/Article/details/gtadybiwwo.html

Java: static void f() {}
来源：http://dali.c1oappe.top/Article/details/gtstvbfyrf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.redwolf501.top/Article/details/gtjaaefpvn.html

Ruby: def self.f; end
来源：http://dali.xuanzx.com/Article/details/gtndralklk.html

C#:   public static void F() {}
来源：http://dali.yuxming.cn/Article/details/gtjbcxeuob.html

[G09] 接口 / 抽象类
来源：http://dali.xuetiantiany.cn/Article/details/gtguhfaoat.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuetiantiany.cn/Article/details/gtzfjwqbuw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gttysrwjom.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuanzhike.top/Article/details/gtvnyouwte.html

TS:   interface Shape { area(): number; }
来源：http://dali.jlsjyb.cn/Article/details/gtyefvrvlo.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtnsrymvzv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shangyingyoupin.top/Article/details/gtbmcwskgx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258.top/Article/details/gtgktdrgtr.html

C#:   interface IShape { double Area(); }
来源：http://dali.9152youxi.cn/Article/details/gtpravclhh.html

[G10] 访问控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamjpilbx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.birdmap.top/Article/details/gtuzovcpxk.html

PHP:  public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtkraraoki.html

JS:   #private 字段；其余公开
来源：http://dali.aizwys.cn/Article/details/gtfpqqhjrd.html

TS:   public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtxorcfwup.html

Java: public / protected / private / 默认包级
来源：http://dali.zycfv.cn/Article/details/gtdfdredgt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yangfankeji.com/Article/details/gtbpwensrn.html

Ruby: public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtxipxdsib.html

C#:   public / protected / private / internal
来源：http://dali.wangshuangyany.cn/Article/details/gtnuhstrzw.html

[G11] getter / setter
来源：http://dali.guowangkeji.top/Article/details/gtqcdqnrzh.html

Py:   @property 与 @x.setter
来源：http://dali.yuanzhike.top/Article/details/gtxvilvybw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtwvojmgam.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtokfnujpq.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gtqcoezfyb.html

Java: public String getName() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtnuyckijt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtiqoeiltv.html

Ruby: attr_accessor :name
来源：http://dali.guannengcc.top/Article/details/gtkiksxltz.html

C#:   public string Name { get; set; }
来源：http://dali.smart0.xyz/Article/details/gtyydfllxu.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gtpqkhapuk.html

Py:   def __str__(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtakrkfiid.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gthfoxvrod.html

JS:   toString() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbnllfpr.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgumbbtw.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttevlgdq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtfnuoatso.html

Ruby: def to_s; @name; end
来源：http://dali.guowangkeji.top/Article/details/gtlrsfvzlz.html

C#:   public override string ToString() => Name;
来源：http://dali.xuetiantiany.cn/Article/details/gtfkslegxo.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gtqdovejru.html

Py:   isinstance(u, User)
来源：http://dali.xuanzx.com/Article/details/gtyzwqwxfv.html

PHP:  $u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtlocjljla.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtjhyzfudg.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtvxvwoxdt.html

Java: u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtirtgolzg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sysykeji.top/Article/details/gtnwjaqgho.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gthjbffkfc.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gtokwboizs.html


<!-- 参考信息 -->