代发 wailian999

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvgqhlo.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2zemitmhx.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlztbdu.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2tggpvgkt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2zqezofjf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdqtpcw.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nsodokwf.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmrjlgq.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zougnfrv.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2muidmqpb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtungds.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbvxxpt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsepzlf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2cssemzvp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gcazaxdh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jypvgmpg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyvmaee.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2arufqyub.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjclrkw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2coveqjfw.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iqchtugs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2etuiwrbf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pnywsuwt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wtigolve.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfnymvs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2muydsayl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvylrbs.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuvxbnv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vscvylht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsaniyj.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwumfik.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbxwhub.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwrhsqs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzjiimp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2abqmserh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdlnppf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzvfrun.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjkodyq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2zaswagzj.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvbvgkr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hoztjlin.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2guicltbx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqsasvs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvahqyft.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsnntlp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzdlrxh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrugnkfr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xacludtp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzopwgux.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nefaunbp.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnhnqzr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2okaqihli.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lfocubhm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2svrksaiw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrsjead.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmoxgfq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsvtovz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvidmvju.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpmtqvg.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqjcaph.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvefxvgu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2nskklmmq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkdobhr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfgdtbz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzagsvp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnamixtb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsccqwui.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxgcxpt.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xahrydmg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvejwpb.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzhjdpv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwldprcd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlkgoes.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aurpbzkv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhqmipl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdfmjxh.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdaxkofu.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tidsfcor.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tenagezi.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mweialry.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsninxck.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sshajwer.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqkfotd.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2riprtior.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbjxbcg.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hpifbhmc.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2envohfkp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsvwzqe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqlugsb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhjraxh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaxiuwe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gncecygg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzxtfhn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqidzxq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2lrttnztj.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2goqwmany.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wawoshxk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xycbuczt.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbyazla.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxjelxu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzosciik.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpgbywd.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2btejmlip.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuigepr.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmwpdkq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2efmzxooq.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2txglvxtz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpxujwc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmhejwr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuiupzq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyoqgsi.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkhmdye.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2sqphhlrj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyqclkb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbjhsrh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhhlxkj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xucaefqc.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwsgsls.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyrexnl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmvrxlw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmvsdfb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2exyrybiw.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xelqtgzk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgsmxlh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmcfnep.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzowrss.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2udxgseuo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqhgdco.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcfmzzg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2trcpksev.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2prtykbrh.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hlquujee.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtncnbd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvxcehd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2icfsemve.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2qyucksgs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2odkdwauy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2krapkbzb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2rysfmidf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2svgmrqhz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbsksyd.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxdebgp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2umxnfyhz.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbtpcae.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hypemoqk.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzghtrtu.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkqlhwd.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvvvdbk.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcpvczj.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuunfjs.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2csycnjzo.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwehazo.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjpsabr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2gijklflo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmmwrwj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqmrlub.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfzvwlg.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmfljxn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bivmiuyb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bulrzywx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pskezvwa.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ixildtmv.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtpjuur.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvqcndp.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bhywxrtl.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eycrdaxc.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnugjxi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2simisrdg.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkhqrzc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gzoajvdn.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzdwchb.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxwaoty.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfyoust.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrimbfv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amzmwfhw.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2illgszjd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtmsdzg.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2odljuxsx.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrdjqqo.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2znwwoxqc.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2swbdltbk.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymibdjan.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkibjju.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdildceb.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmugwger.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2veywgwnp.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ephugxvl.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrcrykg.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsumovy.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgpmzmf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svadkxfh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyosudo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gilfokml.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2domfelos.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhuefep.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlulgxm.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ppizogtm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yqeexhfq.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhkgsst.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eabqmvod.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2opprtaqd.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgqvyou.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzqhhlv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbkjqyt.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqiekdf.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2utvycehz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vlabzpol.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2nrckxqcz.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szrtdwaw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cskxnbur.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfoqvzf.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clazjovv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdpxeiz.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iarrjamh.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxivtcy.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2mywgeehm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qydjrzee.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuzwpgu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2odxiwwng.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tflivyli.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkacxlfa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxmwbia.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2swdwpwnw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2diocptyz.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmaxwey.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwdbtgt.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyzaglb.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpjoqsr.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2whzpteag.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvnrhxo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlceuen.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2luxzemow.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkgpscc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dteynoft.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdxiset.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzedkqyt.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvjjxfq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whjuteje.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjlgzfr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tihfejwn.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzzjoqc.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmhzose.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfnmzes.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsomkaq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unvrjsin.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdyullg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2noyggiar.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2togvcnpy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwmdojg.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhkeche.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwhuwdv.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgwkawo.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyycbsrm.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2osfrjota.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrzmrwk.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhammxb.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lykebnjz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqubtkb.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqptcgls.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmgokuw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmxavic.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2gysifnsz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2elamamrg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2mptdccht.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbccvko.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgdcdzf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjjeptf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdccvzt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjwoeyq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ddoakhcz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zjickmsd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auqxirvd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrtjbxs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qybilgbo.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2esytxbdd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpjdhjp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwljpxy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2srdngues.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtikchp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvsqpsw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2anuqcemd.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqysskd.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kogcptaq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2nadhvoxp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwmvvdw.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmlwuzz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2incocfry.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuvmzwp.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2quydxuvz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2okgzifvt.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2qblrfmil.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwlfxgq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eexamxgw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlwssgq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2htctqzvh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfaklqm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2syujzuml.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ergytuso.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwciwhm.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzpbxar.html


<!-- 参考信息 -->