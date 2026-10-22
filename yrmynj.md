代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhgtvvr.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtwason.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbvmtjl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fanplsch.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbnocqm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2njwzaski.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2pusqvapy.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxxzswr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2abberlnk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2felggmut.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjkpnbc.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhoblvbc.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsvohnu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjlnxqc.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwwxoxh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcatwxjn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xaavpxqo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2reiinjns.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfietumu.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2caecdmsp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2tofxnzwb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkpdebq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajirgzrj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiehfcwb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvgkubw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qusbvrem.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvmjsiz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2tvauenvr.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kggmhscx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbytsuui.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdabmtfy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxubprpg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nodktlrc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2okhihxfu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdvvedg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwesotp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iodyvjol.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfvmzuh.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2rabtzxal.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgzcted.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajptryen.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sljzqcwt.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyabqoi.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ruovtqsz.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzmjiaw.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyuarjt.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2xpklzeqp.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfugypq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvzsgcs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkstiam.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qutuizqg.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kofekocx.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijktvjkh.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnbpqik.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uziuxpsw.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqvoybe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfzlbnd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xigibzyd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdoutjk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qezpeyue.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zdijbhnl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2uerzkesc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhosmvf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hgikspzz.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mksxvhwb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdorlmyk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kswezrfa.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzrkavc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvhenlr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2aygtdcpp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyzwddq.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2auripadc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vokiqnoq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqyeynf.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhhnenm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xngkipfd.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwswdnp.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdmdgnw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcxadyx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzkzmxq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgkczwc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxlimec.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxypjyw.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqjrami.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tccdsouc.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnjbmcn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2wajvwkie.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbemdfft.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2famsxoal.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chrutree.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjetbdj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjiljeky.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntahaqvi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2epwsphef.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2jadnpwrt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkarymgr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbumonu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ludgdbth.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjqsjxt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2crgnduzv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2vppeeyrz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2srjqexby.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmrudxl.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fuascjgd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgggjvq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2utqxyfnp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oagtxong.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjprmlnc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnfkyjs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqrshzn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrebtihq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnzznqq.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvgrenk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2esxxgosc.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwnemop.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqlmbfy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrlgknn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cibhqghh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqhcrrh.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxqqlyy.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpoetfv.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2payfulos.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvdsmmz.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2whetgbpn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yehculco.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbiekgbs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwdnljw.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyydlmco.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhumygni.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kamewoem.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2slejzcnr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwszsucn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eumfosfl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2eheajysh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2quftxxxa.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bmghwniy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2joxfvqlf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2maawbrha.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqhemgy.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtitfla.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fejogohk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khefhkjr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2igijgbsv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeveqocu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvaymcyz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzauaawh.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpajccs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtpcxoi.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2kpolkalq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbjpgmn.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aaouirxh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvxveyy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2caneeybh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cegjyinr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2eddazhgb.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pigrdouh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2crmiqrhp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmikcuo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iujxocmq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2buxrxpzo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcdnxnw.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2htudcbkb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2narmvumn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oikldlnu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmhlgog.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlsqgsp.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwlbwjp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvupsci.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuggsko.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sthlxmcn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvyrtgg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmfndza.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2yuawrcgu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkyubbx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrvnzhg.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzxygnj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2knezvatt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjhdyba.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pifgqlln.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2raqlmzvu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2mvladvsn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsxbsqy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2gaojignf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkfhtzi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgefigy.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnadsuj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqkefgk.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2axyubjjt.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuisbrw.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvoiphij.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bovcbybb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amufhbse.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zomshtah.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcfargm.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xezluvby.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvxlone.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bamhwyzx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2etpdieqh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozauwyva.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoruboy.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntituhsu.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuflqvs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyefffbx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2onvdsiaf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkteokfe.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hbglazsu.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jsioohdl.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sugzgldw.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ciykwlxe.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfifhac.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqshoevt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2esmjgmra.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cekgifzh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2upuoccqw.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkjbkfd.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcdhpbq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvypqjdh.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edewvzeq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvwxwht.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfssvfw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cukjwtqt.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bytublkz.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmykyqc.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2grenjcad.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2sltbibha.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsrdlmd.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpmglhr.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkitpvq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kteqkfin.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lijtjpuw.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kofvwzyk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlsrnsm.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2thhwapps.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2agdyzxlo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrovzpip.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omriulki.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mopgdmtx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwkuroc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ivuwfozk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2txoiijee.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2zixmgrwm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ijeerxuz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2nngiqbrc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxuktov.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrcusvo.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wwknwweo.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kapogdqc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yrodscjv.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2usvzfsgw.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hlinlspp.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpfiqby.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhljrpg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvadnza.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sezqpiup.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cahqpjai.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzkireq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fcucfbmq.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2usrnluyb.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fadgiytm.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2gygzrihb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmuqpds.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhfdath.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2icmvoaii.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnwpcss.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhagherw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdckptmr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbqqued.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyzckeh.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvfkixu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2amzqmkcz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsdtikg.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2fwusovyy.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mahtvvnz.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjgaqqp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqkornz.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uglprpzj.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcgeuab.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhdhdic.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnlnder.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgfxevk.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxagwqnd.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iplepyca.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqilyjo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrvpilq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyyywod.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unxmyfjx.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mefbfloh.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxtflcc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxpdugt.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etgssbqr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmrejgc.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxntihlo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsieknjb.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kndsvzki.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2aitxailu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvxbuvl.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhlmpmb.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2egdlxjnx.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrfsrsx.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2juesboxx.html


<!-- 参考信息 -->