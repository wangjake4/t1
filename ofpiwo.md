代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkewzcil.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzmhapy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdfqvqg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhyhiyt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lluzpiyd.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2nezawdhw.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2phdbcsrr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uicitjwd.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kefaklwu.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpitxhdk.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuxwbdf.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfzhxus.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoauogu.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmgokne.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgaxhfe.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2tahczjwb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2nzheridx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzlptvo.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsadvqx.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vuorwprf.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xoulfhlo.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2uowwsthm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrefkndq.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2olykdrof.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2oacsctku.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxswrfo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vbuexqxx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqvvohq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mndcqkla.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2imygfwha.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbxpdrr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwouemc.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dghqwtto.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlmebia.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbaoebv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2umuivepa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uillngnb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdkrafh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2qsedohgf.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mphakpej.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kljbluqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cunemukf.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfvfqxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zsiujadr.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkkqjsz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2myidcthl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfpfwxb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2ovalwdwm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2crhntffk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzoaunx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2vqniombf.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjbzfrd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcnyapf.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cajjscyb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwrzkah.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfdnxvp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxyymnl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omquclpy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2squfvbma.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjewujvh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2sidjfppk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2crhnvoyk.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2sshazpio.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2soscouhk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qpulmhjx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2exlhtgwt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vinrngta.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdxrkcj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2abjnyfnd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmlljzn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vapxoluz.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uluivkbx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2sacuvehf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvthczn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzsonxx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nigmctbr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2jusctate.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxdfkqa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iempwjso.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqiixecj.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhskxyx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqvzwdo.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cluigngy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hluqgxep.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdudwseb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnekvlp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdqyanj.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvxdhyc.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jugauqkj.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sbckabyu.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrspifrj.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hmygbcwp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gukfxudf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggalgpfk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqlxmif.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzazybib.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2blbfbilg.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxeenhn.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xysielmg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwylkzzz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2crjbmrhq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuyipvw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2adkisvzm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgtpldx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfivowi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuovlcjt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2eiusiart.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2faqybweb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nczznrgd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqblkyj.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bincknmo.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqabous.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcotgtrl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvwwlvd.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cynmaxue.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuafjbj.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwbevsw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2glgcckcr.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2edrnubkw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxsmomb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gffgyjpt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dieiolin.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnnyohv.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkwflbm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhpbovp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kkiadnwq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsvjuxc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gofuhjzi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcsrfhf.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuatyddx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdualpa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbfwcbq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mryyewwj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbhflmq.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wqujljyt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjdcvyq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2undksmql.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2klplpdki.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfhnxuc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlzqoxb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2rokominf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sozpyhkc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2usbxbeud.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jidyrpng.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2uihjddkx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2kzapgegj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qiomjrym.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrjafuo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2fcugmjfz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2habmzcht.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlhtcvq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxceyic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjbyofp.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2shjknfvz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2veibgihu.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnacasy.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbriqgc.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2segorbre.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwvnydk.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhazkbh.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjbquch.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2txzmhzmd.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rkoptazd.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2csaewmie.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbveypz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2nixtsdbx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnipdpc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcujpriw.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fziynphl.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pafhinvg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsfwexa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlyaqjb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xycvoyyh.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzensgb.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqmjsku.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnnmykk.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzquvft.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qynoqjxk.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhqtnre.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2koutfkbe.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtkchsb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzllkcy.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhylbjq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2anfgjsai.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxquukbt.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jikzkjlg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxysepl.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ororulgz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgqsqcv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hakspsev.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyzukat.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvkyiyy.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrugqqt.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjrrliy.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdomncn.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdqzyxg.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsvqmfe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2trmlrlcp.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkofysk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iayowyml.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdkekyc.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfvalmf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsioznll.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqgsaop.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fayxhpcu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbeujhw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2xleajseb.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ectnludj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqwnchr.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sabuvkhb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcnlfka.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gwskohhe.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjpzyjq.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxqqlrm.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yryqsjpd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gvefksji.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrigggh.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmiqymm.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mqayylbe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxgeqjw.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxptpovq.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdthrnpw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpjeyqw.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oiojzzzv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lgncgoep.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpoorfd.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zynihetj.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfddkng.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2avsojdjb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nujupgzb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvorcgo.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypinznig.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwawixs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzapyfae.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2addcxrtb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlbjpnn.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2wabxxyzu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmtucja.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwyaehx.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqjmpfq.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwrkjpy.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrqspdh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2cydlubky.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpgqblh.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsmhjfk.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2larnddba.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2iamveuxh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqocanyz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odfvfzkn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtrsxaj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwunwld.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxbhpde.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2emvhdhuy.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmcdkps.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rmscubxj.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hplcisxz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqzvpxn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayipgtzi.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkvjhjx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhpvqnz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqozgud.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2keqibxqd.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzgyxgm.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bphncjuf.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsttgzm.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2shlefqfd.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dresnams.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lmayttpv.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2razxnrgq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrburin.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhxries.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2risczubr.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbmpoxo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2rykrewyn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcpooch.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdmrvjq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhlyffz.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljiopgwq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrmqunb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2acbvzrbt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwylshqg.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2psztxkbg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2arckgurv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkittuui.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2yzswmozb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhfzcft.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2llvnpcpg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnplqyny.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2kshcqvcf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjxwfuz.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2phiwxatr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2zboylgzc.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfycckln.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwqufti.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoxfthz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2hupcdrxc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xumlcvol.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtudafg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nleciykb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqagslf.html


<!-- 参考信息 -->