代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ykiozyjs.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zchcxaat.html

C#:   1234567.ToString("N0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyozdisf.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbqxgpc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxspyjmf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmojijov.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyujfdl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uigxoque.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzkhzwx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsdmprr.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2hlydrjdu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2iuidlqfi.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xkneovyt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2soelxknh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhxnard.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpvrhgh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfnwhke.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpepymi.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2urptclgo.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uftzksvx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzphdqv.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgamyrq.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsdwbsx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ossfpwjx.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2febacnur.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2sahtlfpc.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfozkab.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcoycty.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2flbsjthx.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2abzcroxc.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkkzfat.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpquapw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqxsljq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2knlshcgy.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uifejpid.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmaiarq.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zoutsvxg.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2wnepuxql.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vqaeeihf.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2trboplul.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtswist.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnjjrec.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2alzvfcca.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cddmcjsc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ahinfgta.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2tlekpanl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcyyzpr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2eserberf.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kkheswzv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzmgsdm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lawifkix.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtvtqds.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uvaaslis.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rylrfwhu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2eappshsm.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oxiwmpol.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwktptr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwyjwqn.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrcgsaz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crwavkzz.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hltqsjky.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhvjluc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2suoohdve.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2svcgamrl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nclgevbm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfxnmwy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2sysnmvco.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsfrhnh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wthiqfud.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fyipacpq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ugaqmcle.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfcrrvm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enhblvha.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpznyso.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwcefpq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyhyfxl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnxssdl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbrzypw.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqeztmot.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nimwbnoo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbietfm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbuwszf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzstdqz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jadejurq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgdwmuc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hysijxrh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2npzdskqu.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zonwcpub.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2axelkczo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzkpuxq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaorbfo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgbxztf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2tejycbcr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqeezktx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2twuagfxi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2upvyjvcy.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyedruy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdagpggv.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ophqdmoi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlwpjiy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2doufgykl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2htzchdbl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjeufxid.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvajadbw.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yucrokyp.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rejvjpzf.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjnsuxp.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqptevm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrsnmnb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfshppt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcfkwhy.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjncmzap.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhtjncc.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ongixvuu.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysembtmw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwadybn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhvufvm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fijvfycx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ihsecevx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zubwvbbv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfqnhch.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlsckbs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwhgbit.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ueooalpf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2eajjwoby.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxpiomc.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmmiats.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2efordlcu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebeicfrk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjfyhfm.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfaqrmy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbtltwb.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2dbizgzri.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrfonsh.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xaopzetu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsljqrx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rbiuthhm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2acimtlah.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfhuaix.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zddpywlm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrcfxxs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhvibrj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqfmqho.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvlxlyr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmxtugb.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aejxxbar.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2yommjkmj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wctzzwkg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sespddfx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikncnivd.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xyahmimq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2thdlkbsh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tudvfacq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2djufdmux.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsaukqk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnudjril.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdtvgai.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fiigqzpv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hstxwenn.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfbrtzs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2djjmlsef.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2wamhrfkx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2izjfhrac.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvfxrbu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqzkiyt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ritardbf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2utspluqq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hrghhgyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnnyejg.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdnqbaz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drsmryux.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgottqn.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmwbhuq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpmgesz.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhdingp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdntazc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lapuvkrn.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfbkdpf.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wagovccp.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trxpcgmz.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlffdit.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2evxyptch.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcdkrbk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvtudzq.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gewjyrhw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osiezaok.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vybpixlu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2epoazokv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mquoyzpk.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xkylrcib.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlzyhxf.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzxxpof.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2chsnideg.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxxwpdp.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2msfjgvjr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qkipocur.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlaqnrd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsggbfa.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lmalnyca.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2tupwqoyq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzzgrpz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rinxovtv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hodlxutr.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdnapuz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vixfbhzy.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aumcbtxl.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2soconvdm.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2acmymuoq.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2euuneevy.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivztiwiz.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzuwdmg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdtugrt.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxhcrrm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuioxsz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgrfkan.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfhaxse.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjoosnd.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfahrxc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imvqvcjt.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrebtfr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgtjnbu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjykdfvq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2tiriedaj.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhxamii.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2kaokfsxu.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjxgrrd.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfehhuuf.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfirxan.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfdlxdx.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lbywaoma.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qomggsjf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lbklbtac.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2uyptywoa.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2whrezgii.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqkzxba.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbsdnes.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbemltm.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nainueqk.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iyverffm.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzflbavm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2omjcuukv.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ywltjhsl.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwgvdfn.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzugsab.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2wtirpxjd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsblimry.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mojimkev.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbqqpyq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djvgfofp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaqhkdi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfzlxcj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yciknfwd.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2stztafcj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2grshbgwi.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2baopdlmd.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfhrrmc.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbjroye.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2nggljast.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnfjbob.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2vovcyula.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2etaeublk.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dvityxoy.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mglbjcac.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pptztaov.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqoxewe.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoezskqk.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnaxwviw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfynsutf.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnnwpca.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxptjlj.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dqucrnan.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jyehzhwu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2botluwlf.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zduyeadg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2audzjouv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cttyfngb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2byqwogph.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wmioivhn.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkqrlvb.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnuozky.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zahrcnqe.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mttcdeau.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2aaujhunc.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2idvqjdzx.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vsupjxxg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxvpesk.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhxugij.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2dajppqox.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxgekyi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2megxepth.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzetcyc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2iseowvko.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2swghekbn.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhxooxf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvezzkot.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2vttufkyr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkfsbum.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnqydsl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mytvjjrt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cijukkqh.html


<!-- 参考信息 -->