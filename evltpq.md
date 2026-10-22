代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgclbylv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmwnlzc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gt2imhowpee.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxknkey.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydewurxp.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2riucvnnb.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcistbov.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlqzdin.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fijzchxs.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqydnor.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2cymkcrnx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlcdgkr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2srpfnjbw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gispssej.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qukdfbrr.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2crbfykam.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwujvuqd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxxtjsh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwyrmyd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gboaiysf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hcstcrnj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wefbufyi.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvpyywi.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuczhgx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2faickbjk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uontyfsh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2egurfsje.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhhxqnk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykagogiw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2eibvnzyy.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2gwinaoix.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbjzfsy.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsmvlpn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2buzloixb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvulsni.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeudavn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lganehyv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2myvevwii.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2txwqwabe.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpmyeck.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvlpyoc.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2knnxxbjw.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2nepazzmz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnkhlyk.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2szycgjtm.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2scfswsub.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2knqqscbz.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsowadah.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2alexbgbw.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2knttitky.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcddrid.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2tyysybsm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwmjbtp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdcvpzv.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjokgdc.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxkoiah.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfaueok.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaotbhh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lekoiruv.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2lejlipqt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2uxninqig.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpjhent.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hmozunvs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfjaaeb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hexwrkyl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2lyoseqrx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnutqru.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiuwqpr.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvpdryi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2geeunseh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxwfpvt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyldoyt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bvctfblk.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdaiqyv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhagyue.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mqizakat.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmluyjl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvcsgyl.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxpnvxd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hyagukyt.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jertxeul.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmbszaj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrmpcyw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjlczbo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfmjeis.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpbscdy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2riuychza.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ighsvsrx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnangjs.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2amucwfmn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2aimenqlp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vltvnoby.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwplqrxn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxembiqt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hihfuwei.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2psguxhyq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfwtdfh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcoosnuu.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfoaitq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhxmlyh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbwcmtp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2sciyjsph.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuezcut.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2scovdala.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2tapbibye.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzqlaam.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fvagjhcr.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kdavxjfl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oialualy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2fucnhnqt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsiozxnx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nedydpez.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzchezji.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcntmtr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mphpscjz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhhkyqj.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2azceqlpl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2yizgrmna.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uijtboch.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vikuvpvw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2znzdkbjd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnziuxy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqkbhkd.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2znshrhcm.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yucocjcn.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcadahzs.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaiuflc.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjhcizy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbqojpn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cceungsq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjppwqx.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpuaiye.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjpitey.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zymsqofw.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2batnvqta.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqaedjgm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvwjddl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2dpotntdz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqmzmrx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2frfrzlsp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlshoop.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyhqnuy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoflkka.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vhumswca.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kikgemld.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqaolizh.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzzyiee.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rctxzjkx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhktifu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwygknbf.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2prdebeth.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rabhrjdz.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrjupno.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtqsicj.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnudyja.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2efzeclsc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2kkspisio.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aazvwwuq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2liskynsa.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrukfvat.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmfgrbs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2tujcrqvd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqienaw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lebvwshe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjrrylt.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kczraxfl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2auvhjsoj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxpphox.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpveohk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tduyxigj.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrxffzo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpfoltc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2unzbjyzj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcycnkx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vagnpcrd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2blgyhxhq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjxgtix.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzuysdk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyuqark.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwrfjmj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvmfwbg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfqshpm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bczhrheu.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcedopi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2cllfaryt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsmmddq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgrkvbn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uctpepfr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xpushjub.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpcalxx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtcvzrn.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwbixoy.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuvyxqi.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2isqpbxrj.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zibhamfm.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrhbmob.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlegtyu.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvkldxm.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qriqponr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvxirkv.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxifpgf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xmciniwn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjnuorm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgussjmi.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfugbxf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjfascb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2molyweit.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fdroxksi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djfpeany.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2oatmxyqp.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqltbwga.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uagimebr.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsdasuu.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzpfhqv.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2alfulovf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjcxctp.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2sreepyut.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkzlcum.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cvykvcof.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxgwnfx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmdabqk.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbddhlut.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmwtntn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyhotmp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqivyurf.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwpyyei.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2afdrcwhc.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ymiqzsqe.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtmccqz.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fawbeeyb.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2erkmjveg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqxeuxn.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgscewq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pjshhngu.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yejdnlqz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2txaeycoa.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxupwxg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjqukls.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbaudvuy.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auksnthe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzdctdz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdtuqvg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxurazi.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wywimdpw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2sulxebnd.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgotwak.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsapvdx.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2whpndfhf.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmpwoxr.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxzcjps.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vckjkgej.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyacrnk.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfxtobw.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pedgvoem.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eaycnbbw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2udydyqbk.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxubcpl.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdqcmqz.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjwrepv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sewfunmg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2drqmzcpp.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hiksabsz.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqnmotm.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2gigbjlsx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdzhorq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtjsciu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkwfzxl.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbmjlyk.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mscbouiw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyocfaem.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ovohfzan.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaygbjfr.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2nddwfurs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkddtxvj.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2swoevxar.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2doipsyos.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2siodqgvr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2fkedhjli.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkzyynv.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbfnfbj.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2szexxryw.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mbttskkh.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zszhtmdv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mymgljvq.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pidtgxbr.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtejeuef.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glwnrdcu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfervzo.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcqnjth.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skqprdzw.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxqzplx.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pycbvcok.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnxncwn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkvcbip.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxuvedz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxtavhb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfavqfk.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfraqft.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdphpwna.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iafmezea.html


<!-- 参考信息 -->