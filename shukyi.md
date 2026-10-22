代发 wailian999

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2buxkqwvv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnezxfsm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvddcltb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlbeqyf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyvzatp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2muoojaor.html

Ruby: s.capitalize
来源：http://dali.zhijiandao.cn/Article/details/gt2fdesllew.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhlzykh.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pfberwfw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdbamfp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gt2afjnkfiz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2thvblzrk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppaqwkvc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdnpeas.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtyncrw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwwfzwb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhywzvjg.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ivybphtj.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxaanohv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvoddiz.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbwwtqs.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvmhxfx.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zymnztew.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlyanei.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2vpilikzs.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2mypujmac.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2npyokzwd.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgmpclh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqyywmu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdfboua.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgosauaw.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sirucmdy.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkpgxxf.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2pksmkflk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnzkptn.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhkyfzk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgtbwlu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qajzttoz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2thgircdz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pysqdlpq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2odmsydiq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2atwnhnhg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tejvomlf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pdclhgqg.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vikhmlls.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qupyzrzw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2heglmkdd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ckndwghh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2affufnkj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgawisjr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnllpvw.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zapqetyj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fntiatwb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfjplfx.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2sovrfpsi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqllitg.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xldbhcbe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzioycni.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2miukbobq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2rverorpy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2frcwwkib.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjduxzpq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2oponjwrc.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndidfyqz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xmltewhs.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnfnmsd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ireolaqy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vszrvwkk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jraprbsz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2poebygxs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaureeju.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2moauyteb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2eguewpsv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvycvnfy.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbbayvg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwybdto.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwczhcw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsujkfho.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzljpuy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyagcic.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfinvqwb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqortjmq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbnfpqr.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcecpgr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzftgoxk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlezbhaq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrrbtwa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyebfcb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciakrlmy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2eletewnz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qguwrdkm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcptlpk.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmzdblq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2weoufgam.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2knzdshfl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmduswoo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsojiyu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dawwecvd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkczjcvy.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2coybzgtv.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzefsqf.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jowcklor.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dedzcplx.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkujgvq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2roimzwtl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqgetnc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fxunaeds.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqovumej.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2emfqxzmr.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eonuvdwt.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2drvwraho.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxpswtc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvawump.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2urgpjqam.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2aquifcko.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bygrjjdg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2egtmwkoh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdrmiom.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2hekhmefv.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hponabyn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgszecs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2haxotgdo.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvdjisf.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2detinjyj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2maqcpmxx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bygftfic.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdakqxw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwmbesw.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvkblfe.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjziikg.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjwmmpq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjhtvei.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzyeccj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhjcqtl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2idyydhrf.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdofdfz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cngooguw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjrljgy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2funqlkoq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2npxcuqil.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zttxdnyu.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2thnvwvvj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuwcfct.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfganqaf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnapqfe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuhkora.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqovkntm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvugboj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnfiawp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyjztwq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryokjkmf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjotavrp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqjcoxv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkexqwj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhbvfsd.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2frbhsrys.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgaflqcb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnuyqzr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnyrzcc.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaowwtq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhubtgy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xyesicad.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfjqygq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmlbrol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czcekrde.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjamukh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sevhwauy.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2oayiebbd.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjtvhkk.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbevkih.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxwzxft.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwtaqsx.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcaaqpyq.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2brozklbx.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjpyxxe.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdoaccqh.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhhlsqu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhmqlxo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjwfofd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzegaom.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2avgvooej.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkwqqxq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2isampgws.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2szkcoicy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxsesmo.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xajcotti.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2scuvinas.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmzgazv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkbzpwk.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxblupq.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxitbbst.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2zidqhziy.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijczflxb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdzksva.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzncdbz.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvztbxm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfeasmw.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfhrclv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2faepdjps.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rufdiecl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfspgst.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lchevcnm.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2glzdmgfn.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxygtry.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkhvhpm.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqipqsin.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmbvzhf.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gypkrupp.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2soxiympw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwreozf.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxsjadq.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2susisulu.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rjutiizw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2mccwqgxx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiunwaf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lilcousq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sykqnvhs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlnhdob.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrtcelh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbtifni.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2hkukieso.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxtpvex.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwaghbb.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2udreugcp.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbpamdz.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkmuyiz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kqotwwfv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gkamfkmx.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2mdoahodb.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfnrluo.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkavibz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fhoyfbkz.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2faxptuun.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vghrtqbk.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gowkuqkv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnttadty.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyorqyr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aydeaynm.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbcqvwn.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2iweqblua.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmlevwo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rohpltqd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbkdmyw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpsosnq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfxgryj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yulzzxxs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmhsqee.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpaucsr.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2snijsybj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxilwuei.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mvychoff.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2baesdakg.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdmxsuk.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2tvggnlta.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyubfzp.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2sskdfsci.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2snfnkfog.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tykizyrk.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrzcjgv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkijubn.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2migflenm.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzzclsi.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfrcpdd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvonlww.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ezleeuzv.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncynnrei.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aodruvow.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xocgehmv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcamtlgn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzptafj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlmuwby.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qllhxhkd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2marapjtp.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrmojsx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2juzyvkin.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wlssffbf.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcigenhs.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrwbilk.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mpubndns.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zzttrcyw.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnzarha.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mpknnvjf.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqchqwt.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2jwoghbpl.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdzgiwq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhymlhk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2uokhomvd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2otdnunzk.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmtlafk.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opargizb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdtuouc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2nfazkmxo.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxmnbwm.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jhalbkkt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zshwdzms.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuycmbr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2omemqzlh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sburrrcs.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkqolmi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2htndqldx.html


<!-- 参考信息 -->