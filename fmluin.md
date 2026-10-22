代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwlyxhy.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyvjfai.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zldnucvm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2utqslkaq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfnptbc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuwzdwn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2rftgbdiu.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2efaujzyv.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuqnzrf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iolozyzm.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2xwajypci.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nuikumti.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhblwroq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpejaiz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2cskqikbf.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqrdoxq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2awkfkufu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bofnmtdl.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwidlxg.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuevfte.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwmzbpd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2etifckaz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfdniuo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgelepv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2awwiaoxt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2sftmfsvz.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2ehttwjyk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2jytwggml.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsokxly.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2itctpxrq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2retmaejl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2beounvmc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gapkowhq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfsryrp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhsnbsr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcmxhmn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxoqdbar.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2jrutkebz.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcduksvj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfbwsmf.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2lscxhayx.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nswhffvg.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmykicpz.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2eurnrsez.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxetclg.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvowete.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpavbpv.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvnwcsl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2fpymwuka.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sabaxazy.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjpbnwk.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2letnuuvr.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2esvoskhs.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2vozbhbxy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyyusex.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2fvojblbo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwheoyx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqjlggx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuarwfa.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kuiptvva.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2njqvsbju.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2juxvhaae.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdbjvzu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2haliadbv.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fjctkjxk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhkerml.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqjezzf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhdpdrs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbvvabl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcnkofy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvvlhlq.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kffmpvqs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnjpcjy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdbqqcu.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbwwqar.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gchkyaen.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nlanbiba.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjukjje.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ooynnlto.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2fepkeadc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyqxxsi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxjqyws.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkoidig.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvrugpb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2innrtliw.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwphwxxk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtbbfzl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xculvpvn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2unsapcqg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdudzcv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2owoaaqno.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfznjdqt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuyffxi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbirabtr.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlxsxlb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkllqjj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2oceqpaak.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpodtay.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2imbxgpmw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyntulc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgwakst.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgxntcq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhxwvtf.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkrlghe.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ropqbtlf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2imvwjvld.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgieypc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kldvjvlf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbvodyo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbnyhdi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2psjgyegi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkxgqyc.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxlygdn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcthzkte.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xqloedxr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2edmpnkdz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhpoeub.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2shhaqvht.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnkqzbo.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2umvkskgt.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2clvnnumb.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxqpmks.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgznpnei.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2krjcmsij.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjohqhmy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gncuglaf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pcziwoho.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tepozijh.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ceagfhls.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqxxxih.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxpmgxr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyesmfiu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eybekjzz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xdigcovg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtizbie.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xfecfkdm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxvdrkf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnihtand.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqqbqbo.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxbjmtp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjsmgaf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urmlogde.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmgfjcb.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtgbqxo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzygolov.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxywolcw.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2meuafmlu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcjvyhw.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkvtvnf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jybhutwy.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkfuvny.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mcukiued.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yaageuyr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zgimslej.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2gaayurla.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfrexyv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxrokpf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2pdppyrhs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pacfbejq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2czafdgqi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrfzuto.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2svhdahaz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoqpicr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yavoyhai.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vppiegmu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdyvhyt.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tiweksgl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgexlqcv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wgczsgeh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2opipeyfu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2skcyxcdw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kafxzoiu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvkcmhk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnujyua.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgigjavc.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kacsqglb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgmuzzq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2mavdayci.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2efileobe.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvxiyvz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2kawbjqtb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tyutbzkl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkelnmh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnrqlwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oubvnjkm.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qekbqvnv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqqxhwo.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2esofpnwl.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyebbpa.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaywpvh.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpedqdx.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akjiokzv.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlaebcc.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjofaxa.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ealpyhec.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsxvcuk.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ikttaxmd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrlwglf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2randejef.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2peehdutv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2msvkitwq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umimqkny.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wedajqto.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2piqdtpaw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjwqbou.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpjbmvt.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwvuvzl.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xsoknsxa.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dljiiamf.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nazygszt.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xecgqrbl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hxaijyzj.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vinolrxp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdhxcnj.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqoqmhi.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2aaffqvpb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phyoqeyo.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rezcuwei.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scmkjonc.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejthimhl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqzdmfb.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjujxdq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqkgkgn.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfrybsg.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lconrolm.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkwsuwd.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omzbomlx.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrizxlbw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vsohjlkx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dngamzke.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2amrhavdp.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mszzvqsp.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyzyxrd.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2bscxclgv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzbzbis.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gglqguxb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfewjjjg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clpnkqlp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbrzrur.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzsjhub.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2utpdsadl.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrjwyup.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2fynrlqmj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yusanzmk.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnlxhmj.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyycdwe.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gbweqdiy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuxvuts.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2vriucexe.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkicphj.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2asvvizhk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2opgwpfob.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkvpsdp.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdtcwwb.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2apyygrdx.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxixqexu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgeuvmi.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnggkdf.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxypjjy.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2wunizoot.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyckgmt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfvrhja.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnlwfnt.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqikbpnx.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyztbaj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnldwlh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sncjbdom.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djkhyqle.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2lizfbsiu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2nulpnajm.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwwudcx.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuikprq.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ulaskweo.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2teadfedk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2swlsihmb.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2iltserkg.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ywumqpll.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2msgcgyxq.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tahwegwj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jltgmaue.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyypkdd.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2euyvydpn.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vajlkale.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhacopq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2kpztrfji.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vabdfhgj.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kmletixj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2idwmqffz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwgpbri.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrpddcz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyudxgvd.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhkljtn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxhtkmg.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2buqltjnm.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uufgajgn.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxgydze.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmltzkoo.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rywmpycs.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdlkozi.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2waizmmcg.html


<!-- 参考信息 -->