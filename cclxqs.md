代发 wailian999

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2fareqefp.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfmvskw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qubauthi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmaznss.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvadmyu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fydgiizj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjwlgfc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgrdamc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcujtnq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvwqver.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hvckzmcd.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2imyxtvpo.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcgtgcr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2pakmtvmf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjooaxc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbombsz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkvsfsf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nnudhmdl.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzbdekx.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2lceijghu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbkdine.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpljhdio.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnoczrp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2llphpiii.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiazejzd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gwekbsjz.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2shzxphrq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2gclpohyu.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2psuulmxb.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcanrvi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnkltyj.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nexmiwbh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkotxeh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfffqck.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2icfopnkx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2knmvhuko.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vordojdt.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2fyktxkve.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2woxkntrh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhwgwpv.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgvynwt.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2swhatvpo.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypclrhuv.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcfgqxs.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2beukfcin.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2xdohlppc.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2dbazszvu.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2belpsvcc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbybnye.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkuvntm.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izxufldz.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olorhdcm.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tthwslhv.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqsqtvc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibweaaur.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwomtkj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2hbunamli.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvroelo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpggqtu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xipubdiv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjkexxa.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2coslkimf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgfivrm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgbvgsb.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbdlkft.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvytuywo.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjpimee.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfynbiz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nzigmptp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgfmacc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2kiubogng.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2weffidgv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kktvhiaz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcpldir.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vqokoudl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uffqxkks.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjywzdko.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsytjrv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuqasme.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbmqdet.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2obseihgr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2smzbsrsd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxwsbfz.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjadtfq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuokmus.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnjghtj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqlfvpq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2javzqgbh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfqyefx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvqdzwj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2fczixkwx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2izzqehdu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbtldtn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzddoed.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqzunvq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyxtboy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtbaglk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2whlqbfrp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gctxizwo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2czjsrmig.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsdfymx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqrvisf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpazosy.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2omnyontf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkalmzz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqvwpzv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtplscv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2evhhmdqg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2qugggwgc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2segetysg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2utfjvmgh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfgpqgj.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgphbkf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkbnued.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2odzxcglq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ornoyfum.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfrwcfg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsrphhz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfetsou.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xumqinbj.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbghwlkx.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2opanukkr.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwbsnft.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lltxrzuq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbiophl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2maqijynk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdyhrqo.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrczrkv.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxixped.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtbfhkk.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbcjrnr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2boqqcirw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2czvjntpc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsppkih.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdvfkhf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhqwguh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqabrne.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfsurez.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2kiskpqxn.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2krgbkllw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lizzsvut.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spdjbmxh.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyqnwbq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkybijbw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfsyuxs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2caclvyyw.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzolbda.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eysnlfrj.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2wzljodln.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkekdwo.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eupvkxue.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqbifsm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwhmhol.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fgspkpqm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfokjnzn.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqxsbat.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtfbbmk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2joelcfqe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsdkjsh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2huopprsg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzxjfbc.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2drldxjsa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrcjhua.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsyjcmb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyqzfcg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdanzvs.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhyjtet.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyoaxsvl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvgxqgw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewutrhgx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2clnnwunx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sunaeniw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpvsbmq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gudwrtgk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wglkcvmf.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2daoojirx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwphdib.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2cvukzvdn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xeuaptux.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2kokkedhf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2uydtjckv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkctzgw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtnwquo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fxelvydz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqxxdet.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvifcfb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwdqrsq.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvbvptd.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cogjnuaj.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqkyqby.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xpirdueg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olwlqwaj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2braliomo.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcktdcgp.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtidgfu.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwckfer.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2byezdepe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ajijpdfa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otbcbuwl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjjluye.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2entlytbl.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdywlayp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2opnssqww.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pioltrvv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xphniepw.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dnodhcql.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbnxrsv.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2izhemckw.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vobwzcgu.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgqdqkx.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uogltzdn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ezigozrd.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjmzjdo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ljiebevl.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2onrqabmt.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhmzqvy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnicaye.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocskmsty.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbtdzok.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evmlxkfn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhxbwyt.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2htopttux.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyokocml.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2owawwvbf.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvinotq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxmbogs.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtkefvw.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxiclqtx.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bacgwhod.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2evadtjbs.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrcuttl.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2defunvpd.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mlasqhbq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfeccni.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkjitce.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cimbvufw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plvevvgy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwakiil.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxoomfv.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rufxogaa.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2hhatxpwt.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjbjorm.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbcegyb.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2efdxdivh.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yvljshfy.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdnfpvk.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bqllzktt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkhcikr.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdzoiek.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hcanxsbu.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rygmzpfn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ahytfeis.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtrynuw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2psujwleu.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfvhxkx.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmncjhna.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkuiqhp.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqxwuhn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mswceedf.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2pubbklnu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2akbcblpx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmhzvrx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2pqllmzwb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhlpojo.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgkfure.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2psvwsjhv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxvlqab.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2woqthtiv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyoutzj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2inodeeyi.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcfwhdz.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqkreug.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vfklxjso.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2syevhica.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjzlflt.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ninswuoq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2miqsrhrv.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoqyzwx.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yvookwhh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcfwiii.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzglocav.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axwqzlbp.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqwevil.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hizxddsz.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2auwprgpp.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evmuouja.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2axuplfib.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdhaqav.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmupxypk.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbcrvpl.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfsitwq.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwirdqs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzbmacp.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhxzljf.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2boemclrv.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2julcrkva.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxigtrb.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2adrvdipf.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sdoomwch.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bunqmhrx.html


<!-- 参考信息 -->