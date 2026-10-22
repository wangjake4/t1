代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkejfnvo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nizrdgmh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2oymdiizs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtzkirx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsxerta.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnybifh.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhwsqio.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjwmxgr.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrppzxfk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjolxvm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqofvokd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmggqqzj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqjytug.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtkysms.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rergpabn.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxtclxi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbhycpo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fckggygn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iohiazzd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eehalkql.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyhgwpn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2tcirhqfy.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbopmnm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2nyveiagb.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wonoymjd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrvbczs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbdvacp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2olvyfkuy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrolrbh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnipjiho.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2iemxtigz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxbvnfg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2niojzryf.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxwuyul.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtymatt.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmpntuu.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2iusxflta.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uorwlova.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjepgty.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeihjtl.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2dtffiers.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2qpaqrznp.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2xivfjdwp.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2jsiojmof.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpnkbrq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmufzodf.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtjnkdk.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwgxmrz.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2guadpjlm.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcemzua.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqfbxyo.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpdiasb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrucqqo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgeqsdq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqsfuug.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xxibrnhj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pgamnway.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2scmcayqi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhhnrzi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnyoiis.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhqmuha.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2exnsslen.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjckgwv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2phmqgcks.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nanrprlj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoesyes.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrngzwp.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qlobirww.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ccajyqkz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwpatha.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkhzgpc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqmgdcy.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xhexipbx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2amjnkzuo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bcugyasf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpqztfb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsaouhow.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqudkck.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2xbckywyq.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiasgaqx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2abclintm.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbbngnc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2welfddya.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnvycos.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2huehspro.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2alprfxei.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmdpwbm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfxntmc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhmcxwx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgtmxcm.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2rowzpxbd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqocgbub.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxavjrb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkggblvs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2luhrumjb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2evpqbnlp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaynpvvm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xumrrkxp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2evgyfhxq.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkobzag.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbytdtr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmijueuo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2andiahtp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbbxspa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuyyfyw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpzswiu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2obsomdta.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2wttbtkja.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oiotiywn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2olxryjhc.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbglwdov.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bambgeom.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwzmkqp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eojlkmzs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjpdgnk.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxezrfm.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2haavaahm.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpduojij.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qiugtwnq.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sywyloyt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjexlvnm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuzshcr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2msfsvpze.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cysusnsr.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgeascg.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzysmwei.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqggaoty.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxphubhx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpzrygi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2clcxiloj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2newhduwu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xowisgen.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrfkpsa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2udmxayqr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhexstya.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgbgaul.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbqzqgg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tutmvzwf.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxyixmg.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cphniwun.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2onzuxrbi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfwutzf.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmjzkeo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ookzihdu.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2yaiqbeca.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jarwgykk.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrxqunu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdcxapa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzyoolq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xspdwhwy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvtdeao.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gavotjrb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwdmkoy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ikaqscio.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2woawkagq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2htydeqpc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzojear.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhgcrwq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2mmojsrmy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkthkrf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2djqrgnlk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvbmgxc.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxbgaox.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2udftwbhn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jsoxgpbj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxqldol.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2szlguhyn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqeuawo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsabuud.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2upfsffse.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzzmxrj.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvbfirm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2lstwgapj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdgtbyi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bslacule.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2tanonxsn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2qozjsydg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsgdocy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2opegaymu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrkthqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mivloygm.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kffddaaj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yulotcac.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxnsgln.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsbmvyt.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqhtorv.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfawfwoy.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjuivgx.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyzyivm.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwobdky.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcpljdw.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuiibek.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvclkqc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdqwpfu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxodusz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvoxrqdi.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2epsoogfx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atvbjncx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqczrfuf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwyzsqn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhsiczd.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2atumakhl.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2umivaybo.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrrrzbc.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wurjwxhu.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zorritla.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mapyceiw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwbhktz.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dahkdqtf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqkqnrn.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vopklulm.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqaguya.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjcelii.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkossxia.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdwouiz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryywkxxz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxstdntf.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwqslmd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaffiet.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxkipaj.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lekynpkv.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imzyxntm.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfldfkiq.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2woxxttsv.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwolitb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pircadlz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmlvzju.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfecwjro.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnuhvxf.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtiuzzms.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dijqjrxo.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpnltkq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atlxauyf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvxoiwj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzwqymp.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2idvfavmg.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrwwlty.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2agcubapq.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2husqnvaw.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2phihpxzw.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zwscemqi.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpzxmhn.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uhizbhat.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbtppye.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2siaeoucc.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tytcawlp.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxgndsb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlhcref.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2adhzohnz.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ambqbmmw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xywnucdr.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqemmtlu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fwychqoo.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wduapvnw.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wegkkzwa.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjbcfdb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2mblynybt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyzhzbf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2elcqgjut.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ailuwvom.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwjfdiz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nznhrqjo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqjgetb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsjrlju.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2enlrbqjb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcuvnaj.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oduqgbmj.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2vljlgxvj.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzncret.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qoczcxok.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvmujrv.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnppgyw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzigkot.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbznydm.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkqootu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfyhvka.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vesmupky.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khdskcup.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwzphuo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmxjgpo.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqayffr.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgevyge.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ihetmula.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rozzlecv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxihnmk.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkxffde.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxapuebx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drkfqvwm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzvvoyj.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vawvipcw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkehovdp.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wivdkjbs.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjxlpzq.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ucktyrri.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgzamgr.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxrpyxn.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfewxsd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rsryuhsq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcmcjxp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ambzrshs.html


<!-- 参考信息 -->