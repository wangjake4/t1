代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbqwtsz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhqfnal.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2czaqpfdg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvtrpbt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2idsmwrfa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqhfend.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2gffrxbde.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdsubhh.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfmmbul.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2paypyqoh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgvosfb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeledgaq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvlrbty.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkznqvs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrgbzac.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aziwyxhv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kunigxjq.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbljzdc.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2aykkfnrg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuedspck.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xslyhoja.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2szdvqtve.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewiwbhnm.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgotonz.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2vsodgzkv.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2odbbgzqt.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnooazp.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2hegcfxyj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2xddpzubn.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgbybvu.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlkyqve.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whclhkgg.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pckvdnzd.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxqrwyq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrsxkuz.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiujeym.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2pupizzgo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpvxkpn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfamglo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2llbpxquw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2enowyacd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2dyaxiylw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2izamnhdi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgiiikb.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvjmffj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnywwvlx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2knutbufm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cieliipa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2svmvindl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcyfipv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfbbyzw.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2binnxdoj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dvoaiewh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2togpxwij.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qujbqrvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jzknfdhs.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mndvnvqc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwgkrqz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhtqusy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyzrkwg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2darinbav.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrfpwjj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2nezbbivn.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpypwhc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrzxano.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzoscxpx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvckrom.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmxicuw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpzovsv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmabekxk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqswgvf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeleakwt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2peqjaxhz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cykigfwe.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2myxlydsb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmwjujt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wehwvgfy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhfrrrh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxoxngvd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyrrrwl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiibgfvp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hotcxgpm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwblhua.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvesele.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqquphbb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfdfqao.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzxiudt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyiyron.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2yseygvdb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaepyxcb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uycviugy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2yltaulqn.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhwpqts.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2uokokkdk.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnpguaj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2znznimhf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnqoqrg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mugksbri.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2hophxeke.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxahgld.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmgomub.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxadpnxc.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiscaod.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fymjybmi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbhmmfp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzmzzwu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ugypgand.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2acjvawib.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfvcrne.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsthwya.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ippkledm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbysuzum.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjuvwzk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vtiwpexs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqoilxf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wgywtpix.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2dudypzkc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsaovkf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgbqinm.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ailgrorm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlonjksn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxleftku.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2txuotcta.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuxzdjy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2egvvouuv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpizhhv.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtdnryj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2izgxsnhs.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2psydqeyn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sedgxfah.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ramoupjt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjqwajy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2kptfxtbf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eptwdqyh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxsqygk.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2plcntlfd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yprquyqx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwziekc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdaxfef.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgrkpmh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2necpeurf.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjodwbwk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvrujse.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nerqbobs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2isjensxg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcyvxss.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2slydclol.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2loheioic.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zmatgxoo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2camtjvbn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eodrkwqj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkgiaam.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2reianyfc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pomovbex.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjmkuwy.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgrwfqv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2snamlwgc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpqmelp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfywjsu.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcybscf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpsisuz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvgzqfp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcyvfpk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtnwkwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crnmbmap.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrapqdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lynnboyt.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjrsqno.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zufvrfwp.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umbhddih.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggacttpb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmcurvw.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2euphdtld.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuayrmqk.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fscxskqg.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhkfeow.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmrhipk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhdigfs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jolkmhof.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smzvtprr.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjdowgq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omvlajtx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgsfpov.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2egzjajyu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsubjyob.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2diwtozzo.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxriroh.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nqaiicch.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsiyzow.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fluzdyut.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2japvomdv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtbnlmu.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jsctodjc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2psqecdcf.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ibphlean.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2forlfnvc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfnlcwb.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoaydxyf.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmithzn.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuqyxsk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyowklts.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrwyspr.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2myssgpjy.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tehrupxx.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwbpoid.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsmdpxy.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flgtciib.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzpvceo.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhruketu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfdczjs.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuvfwkv.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkyevgy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pocthpfu.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2hquzhbtd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nurrdkql.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usdkvyrg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhenyhb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfzrajg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2inoxfcwy.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2doqnlwpq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2upakxalr.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnuskml.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2tytfeciz.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyhxzpz.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvxoelo.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2auaddrqk.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxfvwsh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgcshmi.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrufwst.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vngwyimq.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zdeslytg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmjxlch.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvprqqkt.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnjoznw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnpmbzp.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhinuer.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfjkhlc.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fierczzx.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnlczly.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2anpywtay.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2smtptnvg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqnalpm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2psqfahkw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrbrdiu.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjthaioj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsssbvti.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2drnpgcxo.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiehxkyg.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xicjqcfp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2yadbxrgg.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2seewlytu.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbexphd.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzswuwd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2yujcezmw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjnjejf.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wutyvwpy.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfevvvi.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrcebyy.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cggniwgr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znmlvcyi.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rocrjgkr.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awdmmnty.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmohjyd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfakaebi.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2toipqile.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itghslow.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vieaxszb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzgypxf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjubuxx.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcyqlfw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgccqofj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtsqzys.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmtuzus.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xhigyfal.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2frxrbhxr.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xjaquuvz.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhqskkm.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wymarpzc.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2leryjonj.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wndrumvc.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kollynqj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgqqnow.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfvjdwt.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2omuxnytm.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2llwpqnuu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zglbjwvo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2goqwhwpx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2apxvsxqv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjzmlpn.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfrgkkz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2anpqhppy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2mqatsexd.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlmsjsi.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2obwmjnft.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vheijmom.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqbukdo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2vdahhsgv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpfkire.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrmlqvy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbqgqnb.html


<!-- 参考信息 -->