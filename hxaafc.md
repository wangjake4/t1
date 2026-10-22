代发 wailian999

PHP:  number_format(1234567);
来源：http://dali.zhijiandao.cn/Article/details/gt2glrksint.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2uysmabmx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gt2whhorpyg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfiipbi.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xycogwaz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkizqhp.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2trygtiwz.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2rkospxlh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgryolm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbkuieu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2viflzdnk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpcyqty.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2icrmmvdg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvckxag.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbwgwxa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2mcriuhzw.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyfmhnq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2alqucjkt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbmdsfz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2scfcltpy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcifnhm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2whdrpjge.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmzzrua.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mimnxzcj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwfqtpu.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2jueuivsf.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqvqlga.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iukngmiv.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpuepih.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjzuzqa.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrewwsiw.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrgvukp.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbalfzr.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2tboduehg.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2fdptdwrp.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkdadfl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmmoxbh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awhlokdh.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsqqtbm.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lywkycyy.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxxgnsf.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuqfrdo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkbbefy.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2hkupecmd.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsbbldy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgrdlkr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhlqzqr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzksram.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgxnexp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2ppliomar.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2maqqhlvp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkaspor.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiekkdt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcjyfyy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhlkwfj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzwzmge.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qkihjgap.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpzlxxc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2fldhxkzd.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rjeewjgf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bulnvjut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfwnvbc.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2eadtvquo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfmiiwf.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyystvu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtqstsz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wypoybeg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2nehzkstu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2updiwpaq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2srtvooqx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2edixvvrf.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mezrwgrf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2srkduhap.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfdgxaw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2tskfznxm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxlxzjg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nishdxkh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjeycnpp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2woanmybi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2czdztezr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2twiimmgh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqupfvb.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhnnrmo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynefftiy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2uozrcnej.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2blcjwfxr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhggjxyj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzeauiy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2kadfonvi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfitsulg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2recunvim.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcnmqgq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuagxwa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcbbcgk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2sklbmzma.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyxcgqb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnholba.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnukcce.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtwxini.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqjzsnh.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bpawexyr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgjgsfd.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2otobgcuh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xejeysyu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftakhavf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2awuhpsny.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2aerwvnqb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsuodzz.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eebgcxiy.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2plkygefz.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujauqind.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vrooqmjp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbkvhvj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuajeodv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2btbefddk.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lachiiej.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qptorakg.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgtooka.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fscwjire.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwajwdc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtdvtzz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcysetm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsncuaz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wojojxij.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwdutev.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyazmuir.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrrhapk.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgbmcyj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcloske.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhityvw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsevxbra.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eaazddlw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jukwbgat.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrqjmrg.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvzcpot.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjowrje.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuwfrlr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvxpfvb.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmqmtnp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrglfar.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxbrnky.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2omxaupec.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsosmdh.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpvgsop.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cxooejcb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2cyggpvme.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dstwveja.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnfrmsy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvescalv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzptakf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxwtbzv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuphuvsw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxygyfp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyhueus.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcmziqb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhjzlkd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nukecull.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvlthdn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdzkvbt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2shxuppoy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2evpczeyn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtersww.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgpcebz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfqtfla.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuioamu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsjpqxq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2orhleccv.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2kcseyprv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjxcxgr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkkrlyo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2idhtdjxx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2skrjeuqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qwntjike.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mhboxkie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgvpsfo.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvsvpqz.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcwgggr.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qublppdq.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rklotkzi.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuflynt.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oycogqbi.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwncibxk.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rxznvzqj.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jebgukyw.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2plunyocx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2augmbprl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeteadj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyshjwk.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkieltt.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuqvkqn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gujcjwuj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2awdafefl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tirthbxw.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsertoz.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjmbuya.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yfthdxhz.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lkiobwfr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2olnppxvn.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcphwigy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtdovvd.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrauvvy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cdufchgl.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzzztbo.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dyinjegh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chzoztbq.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkhkduu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cncazffu.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhysbqli.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2axygtnjk.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvuxqdn.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2olqsagmk.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kedcusjc.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2havvdntz.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdlvqne.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxumncfb.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqxvkyv.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etqkopkc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cyarwsrq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fipotlaz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofoefuzi.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rtspqyds.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2shyavcaq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2noajnsif.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzxkeoo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvzxkdr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvucznr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpqqeyz.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcamwkk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnclrfh.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2abmsjets.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2feflppzb.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rlryuqqp.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyyhsqw.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkeueak.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmssfyn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ywputdkc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2asekmpnq.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwzavfg.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmmtbmj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzlmllt.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtksqzz.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgejzwuu.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqieibin.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nprjueaw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwynerx.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wynhhpmm.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvtwepa.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqxshsq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2krhtnzdb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wywdciax.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rllgvrvj.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umaropiw.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gupppruh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaoelav.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jwiygrxs.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxunqqdo.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvkyocp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2azygjovc.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2afzsbwvb.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxjpyxn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2szbzhgxu.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmsdvhz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2veubthst.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vojcttfi.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2kylkitgo.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcypriu.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhbxbpf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxstaja.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwnvurn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaafhis.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfsyrii.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsddtokj.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2nzoiisay.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpwrxto.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjtijyb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsqhcec.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnvugnr.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqfioxt.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwlgvkt.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpymttc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbeyasu.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnlfrgv.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2touuicyp.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxgqstw.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2flehfbya.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyxaubd.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2unnxinox.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2deyuswab.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2biwgukuq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpthnxj.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnbqthb.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2mskqbgel.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2zalzxnuo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2yfovrhsy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2aavnfudx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2zkszbiio.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjowzos.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ameynfsf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2znfbrpnp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdlshxe.html


<!-- 参考信息 -->