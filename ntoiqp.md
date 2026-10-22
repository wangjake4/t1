代发 wailian999

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqlrwfi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2smgrrwtd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrkacym.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zljitffs.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbptishb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2npzxuoyk.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2daitcsvu.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgjvwob.html

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2eubgchru.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjggcvn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrrllbj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rillgtrc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tyldpzlz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2szngzpmf.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxicwpp.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2zpixpiub.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwemnnh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdleafla.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2feabswjn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2azmndqev.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2caywyepf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjqllcj.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwxqnqp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2syqtkcbb.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lherdszf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcztkzqd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvffvcx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxyjkoc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyujcgx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2othxylub.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2shqfrtpw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uezvvuoz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoxzrty.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2kopepode.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyiqzsa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzsdfpg.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnxniuf.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2topijrdj.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcogttvo.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2krhbtnio.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2imftlyhv.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjdtnca.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2djtpitdc.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2rtysthhc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpoemxl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwjwvdb.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfdbmik.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kufripfy.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkbkecq.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzpigfb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kaftjmsg.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2avgxwvvk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmzvrgr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrkmigm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tavecunj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuldatl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdykazk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2wibyhbxt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjrqqqy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwfvunw.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wwaakqti.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgnqpxm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2llbtecnj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xurgeqim.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgdipzj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqqifll.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2mecwuvwy.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kmaarhwb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmrhxlr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhlwzeo.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nrornrfo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jetbpzzf.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwpkvwl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjwtfyo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oigltbdx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2exximoaj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcdthyd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgmqtnp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjivfzx.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgoqqsl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2omuwxkvc.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ddogulph.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2clppvkwa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dorqavnm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpnwggn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvtwjmw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpzhqqj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyszcws.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2frfapinv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtqrrba.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2reisjgti.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjadpdu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjswmzv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2glfrrpmm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsezxkl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcfnjkm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2bawukrtb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2viixwdck.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ciexzgbx.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2paqaqntm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rionrqci.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqeolzu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkruuku.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzicsgrx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2abksuuis.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaimpcy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfczrwgo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2wdikdotu.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hcubrzpf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2thrhnegg.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjxpole.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ueawcbvd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2foomkhtz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrrkhde.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2sowvckbh.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtzhqpr.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuebtvi.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgjzpkj.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sttkxewt.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbepgjob.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oixksvgv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mofgtlrr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyvablb.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yaiedrvi.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlexkff.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdkooyn.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2njineqtt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrhhbib.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhodduqv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2twnicwfl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2iztxgupl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkduife.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcbukts.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2atbqnkpb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfjymwf.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbpfnuj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvargqh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgaosfd.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxstmtxl.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuyybgh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwwqeoj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2umnqglbt.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijaaycjx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pozumtsr.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnucerl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqlxijz.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgwansu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdtwcdw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2nabfhesd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxmyfaa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2xftxhjaa.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrqfbik.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvrkmoc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2xychdofx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrwmzdt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hawtcebs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2huvtrwml.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oipgynwz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqkrgoz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fekulcpg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqsjtyq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmobhphy.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgsagmd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2prjdzlaz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdynuzp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyktqwt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzgcuhs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgouoroy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqvjvgz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjmvepe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtszbgt.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgzetup.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdgqhnn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrwpxdd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmzeveu.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2rpglests.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpanuzs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2alitsifw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2msipgnsc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2icyitlkw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmolgxji.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqlzdcd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwtwxal.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2skniyvwa.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkdpyaj.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aszxgkly.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdesjqj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrhuswc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aoydwjgm.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2elhgisvd.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgtxssh.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxsfxew.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnkzjfl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2asjxyarn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utrdhfku.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmrmhpu.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzpalgs.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snigbcyg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaypwzin.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkzsvju.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txzwekjx.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cohahoko.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2esqzfjbp.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2efvslvhy.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kttlcmrz.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cafjwfsk.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hexzqbhe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wacgturx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuzsvew.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kypmeduv.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lyofnivo.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgansid.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwullzoa.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzlvgfs.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yswasewp.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vizyvtyb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cweosexa.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2giynpyfr.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmewikh.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lltyerjp.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hagrkrvy.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fshbwhdz.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gepbcwqn.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebywgtor.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kayetayb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2twthqqqe.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxduedl.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnhlhwi.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bofijext.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzprhlf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiwrdwv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udfidogv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duiteqbt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrrokaa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2wsujumzc.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqegdde.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2xgizzrny.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmwvmps.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdvdetl.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqzylid.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2femongos.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vvyfbvbn.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rltwuxhe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bdojjeoq.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2bevbldlb.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ezaqrxgy.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2urmmxaxn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyshmof.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwtkpzh.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aeusnalu.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlddksis.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azpgufef.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qiynfyfq.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lhopivrm.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2prkrhnoe.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2kanuooqu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ygprfnyd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxantgxy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2diqeekjt.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dypngzvs.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngshnkxm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrwnvnr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrrvbup.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eycvsmut.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2idvaevaf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jplmjmsc.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jucuykvt.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlxonmj.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmeftum.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2cyngktiy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2cagpybir.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kbujegid.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdbxtaz.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jvghghnu.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2waqofogs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyjgpfg.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fynylqlt.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szeefwwj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrlqzvg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsveioxq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2nlldvaps.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhafrysm.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpukwkr.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2clcvcyaa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfjrhfu.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbcvoyg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrdncfp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqimuqrm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqfznqf.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2awfncfan.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zevbfgzg.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zomtqkkm.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2spfnkrsz.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pauggfdh.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqhqsyl.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vohqmjrc.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhtajth.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vclfeptm.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2eklimemd.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2oruqrndc.html


<!-- 参考信息 -->