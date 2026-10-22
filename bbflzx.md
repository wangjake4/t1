代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2woxvslkk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2npjhptub.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2nepwlycd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbbqdsx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lvensgpe.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnpjhfg.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjelgyil.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2sflocuzp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqksuuvn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzucqek.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbqysbh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrtaknr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tildzzvf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2iarsgtrk.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2brjsbnpa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2onzjpixt.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrowkmz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqdqeak.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaprlyck.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnmezuv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktysctaz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qczctbjy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbwcqbc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfdhxtj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2osmuggzb.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwtpaor.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2uaoexvky.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdslwlaz.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyrgogj.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ribusunr.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uaeajmyu.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2indykram.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2jroztdvi.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtbrnxs.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2lthmcpjc.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrjrnrg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2aavbwabb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvojnzqt.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlpbhbt.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zenqfjqg.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkeuwxr.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeowxwh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqcybtc.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdpethc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2pruagmyk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2cfarrcin.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yokvqffs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2usagrelz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hdenoeyc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2xirwdhxy.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kudqlikm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxdbaed.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnljmum.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpsdxah.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2booqacaw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2aywjltei.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qqycdkmz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzedzil.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbonyqb.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tatbqdxh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzkhwkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sthkzxwx.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2soufxuhc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsidzmy.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xexnbyqg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2amflkgdk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tespmzkx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtobegq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvxukdx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgafurx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfpsaey.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kinhnadt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cycxaazl.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzvrvmg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2reynifwu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvcuwce.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2peqxxeou.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzwifqx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jebtauac.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rczklyuc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnuukjl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2avrfuepc.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2txclrilh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqewzde.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkhazyp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogopvyxp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhctncvd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxcxrsp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfcugom.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnfhfme.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdycvkx.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2davjyqew.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2neyxkhjv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2pknylazf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xektrwps.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2njxjvppn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpebgrbe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiwzffn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmxkszo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2yderqohe.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjpktsu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjmybin.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pykexaql.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpnixmu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqohsbyz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwrbtav.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2eckkpqxl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hushnivd.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaxjsqr.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhaqcpfx.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xuchmyrk.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2afnqihnr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhpyzou.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgonzctl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbmtuup.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oasssruk.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkrefty.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2taxneipt.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvmkcox.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifswgmfw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtngllmm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqrekpv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2geftherl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2auenxeab.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2paddahxx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2hllehcce.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2xlflniks.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jerrujpw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcsxnbf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtvmxxx.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gksdmddb.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsdxpfl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtyaxyg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdzkurs.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdhppwy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mykjoktj.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtuypfb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvoyzlfv.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2irqaglyr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwzwzho.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrdycmw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ajeyrzun.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgudpnr.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqslyetn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2llkxkdgn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdqzmgb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lydnmgaw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fthkuxjh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnmydpk.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuphrka.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2gophnwau.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlhlhon.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqcrwyn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nblzncuv.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuvguqq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbpqflb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwrwovk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qixmdufg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zabzywlw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yncxpzxi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2agtqssvm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tiduweax.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hewbrtxb.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxpdodb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbtfway.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2cwoyojqm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cojvqmav.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2biufnquz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2faqbiyam.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2sapwytvw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2gihjukam.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rklumokj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvspupy.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqvihot.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyjnbwa.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2iwurkxed.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvnbfdi.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfuropg.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2upqzqavx.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2saiswcva.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhwebka.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuekpqms.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ymngucdh.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agetdhtu.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwsudyd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxenuhk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2goipedom.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mljuogey.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvqesxo.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tridpvjr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbictzy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nklbevtq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owaqsyre.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pikiytmz.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2sowvxcan.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkoacdh.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbgqijf.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2egjktizt.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbsgwvn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2itgycbeb.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmnhfyp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuinopn.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2darvbrsj.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kvilmest.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpjxqjo.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcefspho.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iybxvdfe.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txoggwwx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoileii.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oshplnqm.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqylhomx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2leicdwot.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2szxwiqig.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gsstihiv.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2buiyqnal.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvydofz.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clqkbutf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcsjhzz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkkkpct.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2paaaobqh.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnqeznp.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytefdeek.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnltyhdj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrwklmo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfzblns.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swlluhwf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcxdfmo.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bcopaubz.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2glevbise.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2iubhqufx.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsmenpw.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgdofmp.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmglxgm.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrwdglw.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfbrmuv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tpeddntb.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2zyakmeqh.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sfptmkfw.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmvhsyb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2gckqkxfo.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2layedgzh.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vndrodft.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mseqeigh.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhookgw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2sryaqptg.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpqwmfy.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irkbxsoh.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2plfyfpjh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfbwzsq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyovmox.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2oeffyhqi.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiegxwaa.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2brfxqmjm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwjxqzn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbghywf.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2znglhwbq.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ynubvfyv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyeipxh.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2eucfwbqw.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2abykifnw.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzpofzb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkjegun.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ioamdrnn.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nifarjsu.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zmljzevh.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ccizudpd.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnmktmb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhuiepc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uznghrha.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gssgpnyw.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bziwhopy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qycphxqv.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2nohufmjq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dihccmoy.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhiitef.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2efdqkgzt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnqrzqd.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fujuulir.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbuvdqo.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwyzrxg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2iajanndm.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzwqumm.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxaptoh.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2btncawvt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjczsfbe.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvmuror.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbwpysp.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dgreyvsy.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2atblrxyx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jayzhalq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzqulea.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2thdnziep.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2lqoxwivg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2remxebpf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2abcxjjok.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxbvuby.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzlqztq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmppwyq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnijobeq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgaxysg.html


<!-- 参考信息 -->