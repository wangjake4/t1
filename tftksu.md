代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zabogbgj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwcatui.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxpfzrp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fedeoden.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuokhny.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhaorzr.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbrfbdq.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aadspbjx.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvodcxo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxgwmsx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2tydcyvhr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdncpyy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpqpdno.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2idufzwum.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2umrfplrs.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2sgelkpro.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2aimrpnux.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyqizgf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfntdvx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrxzclg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzlfohx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2thsvvbhb.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2vxixdfgy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyfgtla.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oeawsjsv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhwugcm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2oupfadxa.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlpfvyz.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zggteuny.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcfjnxu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsvxxqb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2riqwhxov.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgpxfvj.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhxcqch.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2cngdhhwq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcqsiyt.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmardvcs.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruidyxmd.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhbywec.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvpvbej.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ceecpqdb.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxnbnzt.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2viegxjdx.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2eynsydsj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2hephoxwv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kaztmbzm.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2waregqoo.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xagaaobh.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mloteqwn.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbukokx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2feqtocjk.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2uebeqpim.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2lggsfpwn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiinnss.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2btimfxbu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ymatzulw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvhpzxk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbsfvbx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fhntdysj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfouiej.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkllqup.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwacktsv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpjqqbq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2algkjeks.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyurebd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2oweiqpvh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpkibzt.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gszczjli.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qppvjnfv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiyajgv.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzizdhi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkuvanw.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uylmnvcy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyvizrx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtlsakx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2swqkmmlx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsitenb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nfiqiddg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxpptfk.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbznksdp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhmezkm.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdaracnl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjjmtke.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gttplnrf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsoazeg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xehjuowa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsgsyxi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2unccbpoz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2phnvcccp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcckynq.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyqvkpb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fneskvuf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfbtadm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2clxqgdpj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2unujgoyp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfeiosor.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdpjtfi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjswxhnh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbrhrjc.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2thhsamvd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzcgiji.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjmhgfe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2exnfsqev.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rncnwcsf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2niawebja.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyahfnfb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2awnermph.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2tavvtnyg.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nigcvhxa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2rflpqnjo.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvkthxw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fskacdgn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkxrond.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqcrdpt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2svvyrozm.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sodzsdph.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpijoeob.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsakkzg.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2olnxkpdf.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wingqoap.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyojeegq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnmvuig.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2irbutxqx.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2egktmmwd.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbhkjyd.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2umftpaei.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfrhqrw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwaqgmf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmwyptp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wbleyabh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ealbygoq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfyctcd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpknysd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2louckyqj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdwzzdg.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbuzleg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pofazvhv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owcgrydm.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwmsueb.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxbqgan.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2olnclyjv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmznooe.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqodbbsr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewatsqzb.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2wehwjnta.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzukumtt.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ylibjpuv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbwdjlz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zqeluujq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrkgbzt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2szrstikv.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2beelzapg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuwkxyy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2fapewgoq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkohrah.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2brxlljre.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mydkkoym.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgfrxwh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2epzrqoiv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfkybnr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2urpignht.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjellao.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqjbxih.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rafgjbex.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qpezfqvr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxlrjas.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogszsdmp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tufujulp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxudbal.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyizmgc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2igoqmsbd.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjhphlj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbpaxoo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2knsokrxh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2acibqyar.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bmphhuyk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2dtedrhry.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2khlbqedf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2pttgqcjz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kgitzhei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2msbnrfnm.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2raxhafof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2llbttevo.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmibrjg.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pervuirn.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvdrnmk.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxmncbf.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcrkiqc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgismksk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwqfent.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gbauxjyi.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvqqoym.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zcehahsn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2avwfelkf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2quvudndr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghetqvxj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhugaco.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjrvqme.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmfsocc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dcezvtng.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfjgoec.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjjyuck.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2utujxxff.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qoibiniu.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kahgtqdz.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdulxpc.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlwtyqn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xgapcqyc.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkmreey.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qafmjhcx.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjbtwfn.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vwasanux.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjxarsb.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgnmnel.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zutnlwiz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uckrqnex.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2csgazdrn.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdnxrlb.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2astvmnoi.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bruynnjr.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2obplxswr.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evquurlu.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdgppch.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqouzpx.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eepsnbif.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmpqafo.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcfabwk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikevwysc.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvsrnhw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2soyuvmxx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtkzyoa.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fatbdxbp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsyqoai.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2soasuicm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2hihgstmy.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2odgbvafj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2tukijngu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ehheawtl.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdkunze.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnnpbxe.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ekstgwxy.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2egwlrrju.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuwrubu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfligak.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2uatkopkk.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfjnzpa.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuyolab.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcjcclx.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhllfckb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyjuell.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vytsdzwu.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2njzvgtex.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpiduzn.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2npfisbbo.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dielkqdl.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqlcqtw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxzasxi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhshhlh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2bbehshcz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irrociac.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhlseqw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfdubfl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2irodiogh.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyujadtr.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xgptxuoa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkjhtas.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2puzzglbe.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzdunwq.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uliolysr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjfperi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2umaxcmmo.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xtudpypf.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkffmen.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2azujimle.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlznvll.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onkgzmqe.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsffmkau.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdzabvy.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qitjvqqq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvesatew.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2anjfpyid.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nicpwdch.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2blgrwgzp.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rntlafyu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oknevbxc.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmmabuv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpiuazt.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2saysbroh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmpmshl.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpduhlk.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2olsjzaye.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2erhhuomt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyknljb.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxzhdse.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2piozfcon.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2exappadu.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsoajqg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmvhpzb.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrctindp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2kfogxqbu.html


<!-- 参考信息 -->