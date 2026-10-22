代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqzdyhz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzocjxq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2cztoxwep.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2htikxzkb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtmmvvv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoirghny.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtgzhii.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlivxmvj.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsbhdod.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2jueikold.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2wngledhe.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoengnf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnwbnbw.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuegfjh.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeiqocks.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2omggqvdy.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhblgfg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhxfidt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnatguh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhpaevv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zblfnyjs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ikekjtxi.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2zruhkapd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjwkfwl.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvzupgg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqprsxux.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2wybojyls.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sajjwekk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2czuyxtwn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpahprga.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2flwdwbac.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgacbbpp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxezyea.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxkiezk.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2dubjdzpg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkojljzz.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijccboxb.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgucckp.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkvostb.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbhnzpj.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2meevhjqu.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2oquaaokn.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2ieazlcsl.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2neijedbi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqmqwtv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjlewds.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2obtpuyog.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsgvhrb.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gszxozha.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzvwvnv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2musffcvj.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2trqidsbh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbfkrhd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsujdvh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrdpfyj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqyijrd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2utktkddq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2bebasadf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bljworxd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkflgun.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgmpghe.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xznpkhir.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdlzuzr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2paxqwpqv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dngvxedz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpeajegn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdujqdm.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfxmmdu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkufwfk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2arsanxbe.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zqftlyqb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uconofbo.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2snqsyjvj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnlhjfm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aadyrenn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2kilzoyfi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkdkado.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyrzajs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrerdjd.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvvazuf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qegcujdz.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2khlpohtz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2mvstokod.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2effbxrhb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcronfy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbtymqg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqhyqre.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pybbyykv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2anbgyeox.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhmzwhj.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgldius.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlggncx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xymjyutd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhljqwf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtxossr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2klehmxzj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyjyrhp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rszfuaox.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqpobvr.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbmglat.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzqugyt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyhirge.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2modhksec.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqicfdlj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpxgjul.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqoyufxs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqslsebj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2noyfwjbr.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjlavoj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2yttqjpfe.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkrahna.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrynoiw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kujdjgiu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wapeptfw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhelfazx.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvszwqo.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdsdffe.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zibpggjb.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2izmumcjk.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mzesreyv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmdiygh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjptjidn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hgeebthp.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2juwzpfky.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxsslqt.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2perbdraf.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjikcns.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeaiqoyp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqwaqij.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvrqvwx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hcisstou.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqrcsgf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfcdoaz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzoztdzw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjodycd.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqrdxvs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbkfklx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcruluxp.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnghlpsy.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2abipbyye.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsekvrcw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgcwznr.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2alzqygzt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nthxczvz.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdqvvxl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2efstdgbh.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2alnrffnf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpduqtr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wyswyxxk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwupgos.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjhmdrf.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxxdjkt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2azuklics.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2abyuigrm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2flurembd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cidkdgrl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuexaarc.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mchbjklm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcbnupu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwnvqua.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxpqxas.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2skywmnvb.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xdehtbhf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aetjbjuc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfehcnb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2twhpsnji.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwxcica.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2szzkgxkb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdsyqej.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyflabi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2snnpptha.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxlygvf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2egrwnksn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2tpingzmk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yjocfvyo.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2nohdprwg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnkblir.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2weuxmfyz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnhoouy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fugtjxbx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsmwhdi.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2veqtvchh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2urmkonnf.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlbmorl.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vvimusmd.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuhrapr.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wodhfijk.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kapknjgk.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbbknbk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvmwckr.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlcnnyt.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnhaktu.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2egcxpvom.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2uqznnaih.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkudlok.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2solokuhc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jaidgbnl.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmjgwdt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaspoymr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2apukgycr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvwvnqx.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhekoqt.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtofkxf.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhxskil.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxctqgq.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2apwhagcn.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyqczmu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tqusnssu.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2myegqods.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdswaqi.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2onyitbhi.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2blfscjlc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtddmnk.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2suqyggug.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vubwghxa.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2doqilqmk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2svgbazdn.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sjeinrgy.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwmevpo.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2geqsxzqi.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2esfaskgc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdojlju.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2loxsctfb.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vafocihv.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sydtdnyt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xcputqws.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2toffprxq.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shwqudiw.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlxvith.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2knxedwby.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xryxibjn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzmbdxm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nszrimme.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojiuqxan.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2pbezdwgh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfxfeyq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ndndflwu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnvrkox.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvzavzl.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fcimbaog.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ijumeyda.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhdzbsa.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kuthpnsp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2omtcmvzr.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2wgixejft.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ueubhdmg.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bevvscvj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2cnblzaxu.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zshpintb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwioefwg.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnglnmh.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2arkpyusp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmvlzzx.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vsldtsxf.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvfpcdm.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaczkha.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjnhoxq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frhuszqx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvdhszi.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqwegfx.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnghhgai.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxaecvd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhapzhv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhwcsqj.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwfryqa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2hazsywbp.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgtbdpc.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsasxwq.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrzndat.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2accdgviq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2mblxrjsw.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qczdhmhh.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2stjlnetc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtadypt.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkdtkcz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ignsufgy.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxifhyve.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyzqbox.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atirrqym.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwhxxea.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2jomgtvqb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxknmbk.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2opstqhkj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkvomyu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unnimvbj.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eabqstaa.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzzkorl.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmejwfth.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvaggdp.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xllqjbbe.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbybiua.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxigmdp.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hboneqtu.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyftqqw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ogetouyz.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fqslrrij.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfiqsek.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgckvzs.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtoodfvi.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2rhatxpmm.html


<!-- 参考信息 -->