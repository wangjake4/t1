代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwtyhmx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjxodtu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2jozkdthr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnfgbxl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvdkqjs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2itzmqxie.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2woktxuxn.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyrfvhf.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2dawzmaqv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2htrcdifh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pocjbrpe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgsrtpy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sacbjbyk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqpvezh.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2uvudumbm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2abbictdb.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiskbxa.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyphxwlr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlkhoqw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyhzmyi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwnhspw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2amoooffi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvurgzx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2maqjdyel.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2afvmmxap.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxteczy.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkyqysw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2shlteguz.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyeznij.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kazsbyjn.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2udgzegfg.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjjnaei.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2nowvtsqr.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuqpmij.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2kywxofae.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2wytpbrjm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdqqfpw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfwtevj.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwznlfg.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkwxegs.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwtfxnh.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2prznpght.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukusaiyy.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2uecfpmky.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjknott.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tdabkror.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2loljgdha.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzjofki.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2adoztgej.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2endhktqi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dodqjoof.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqcbkzp.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2afdbphug.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2giyebsgr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvkgnwk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tctmsdwc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvnxmkh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vayxnzos.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmgahec.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnldbff.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cupjufks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2clfbupmd.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2geoezsll.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jccvgemu.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2frjctmip.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2zanqvxiw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zyntvcal.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2vpablktn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2okhgbcal.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hciyeyqn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdfscod.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovirqnwr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjrgica.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrqhasr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrmvzjf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vndaqxqv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtzztis.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbpgjep.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnmgjli.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwzygbp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2arqigpcn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkybtzqa.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2yeapmuys.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjlhwhk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjakkbau.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbvmcxg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmwpvxn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgzaxzl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpbevke.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycoslagh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkomgcqr.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rotqjfyn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtnpvnf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnzvkiz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nytrympl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlonoye.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqwdgkt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmantod.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjjsknw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbpamgs.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xzadgxcg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrrijae.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqvwhcw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfarjtm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ganovega.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sayrzfpe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2huwomldg.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrcpnok.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hskmswmi.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oomyiiew.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgoxrskq.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xdztcvoy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2difuulvb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxozkmmq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dfajfjkj.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqntlun.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpekvtb.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjbnhph.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqurhhcj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2poudzhei.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmobfvta.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2htbzhpmn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtafyis.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cyayyfdn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjlnncr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwavkjte.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2rnaafhuc.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2selvqjru.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoyjkci.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2reyhctui.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvmijrl.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2omujezrv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtzpbgc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqonljnc.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnlnawt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfqzefk.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2awmphuaq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2siqyhdlj.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnoleoa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hijcuond.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2txdmvqwq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ruaayvrr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2awnatwzn.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2afxxzukq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lapbgqfz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbrafqb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmjjfdk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2frttkdhe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2crpgjmyc.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqcdmur.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvacohdn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2heizfisl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bojhpodm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wokgjebf.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2epzxlhkp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxukhlw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2atsrgtmr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjssbmk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrisfhkw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tupmqmee.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2idfmbnxw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzknqngh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwzfgsh.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwykize.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2odsgockc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqhjinn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2znrpaedz.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsetsig.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfrusnt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuysrwo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgzihsw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vamxeixd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsdzoij.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fmejgimu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amjkyniu.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qaunqsdd.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yptkhimo.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yywoygft.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhlydak.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfuggui.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gadtzxnq.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtvzoht.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iqaxegxj.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2euafzxlt.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkfqiqr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdbiuez.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjhmgdt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgikvyn.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djqnscyt.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mprsilwv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfypfibu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2azxxdrig.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpntcwjo.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtnxbjg.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2imjzoxfq.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2doiyheaj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrrjuqw.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gmivfzvv.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfxzvxw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtjidbi.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxsgbpz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmaubjd.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2alvazewm.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2awjgftnw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzaoryph.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmhgsfc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxommkrj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slxwtxkd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jypvdmym.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfqnyap.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrwigwt.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kokhaoab.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkcjgrq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2memuqpeq.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icopjrap.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfxyfbw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwzavdq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjeuzia.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuvthoh.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lpudufgq.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2eyflsxog.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnebfrtv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbdxekt.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsaonhb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vutpiuvj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewotdrtf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2lsivbmye.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pimhhodm.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2afyzrjrz.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbbecny.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymppkhby.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2krfoxdsp.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcyjbty.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvacjef.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pgoimtyp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxbqugi.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2newodhxs.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpgidwz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fotsgdwr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2uyauvozg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuylyao.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rihtuyam.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgpghbm.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2htvomkyn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiadpfq.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wwygabwa.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrjsdjh.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgbhqtg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2yxemvnvh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2siehljye.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrbhhfn.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uynwzjvk.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbhcwyi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2icehcwqp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2osnajwsi.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqglkwgo.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2tewadbco.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqheqlh.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2obrzonig.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2talvkgft.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzbyren.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlxbbri.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpeezay.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zkoqxisa.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdabnpo.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cryerpps.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gotbkyku.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2styabzpt.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsqutjx.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvjtxig.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dboezigu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdsxkyc.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2eebkolim.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llaeazqq.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhszxnf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpvkirb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcibgrxi.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arrizmjw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znltwucl.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdijqacx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyynxgi.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2diapqatq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zluslips.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mktgzlgu.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2teykxjqr.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ukunbfcs.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ozscanmy.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qexddygy.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgtgcdp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlufxav.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjmrgzu.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzjquul.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmpccav.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfmqjdw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2crndedub.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrjufxb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrfmejn.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptteqkis.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivukljuj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfzfvwj.html


<!-- 参考信息 -->