代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ylswclqy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmcjfjg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2eapnnkny.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqiteys.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cemjhudc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwkighy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgumeyb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oirbzoxj.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rakxlqcm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2hutejnpp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqydiqlo.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgmfxmh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfpxtei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uinmajxm.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhisuiu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhcztkd.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zerbdkow.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlmpcmp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ekicooji.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqkibkd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdawhyrp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwxrmjd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2iocmhqkg.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sojzupbp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrbwtnf.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ceiydfsa.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2omsaiest.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2woshqpdq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvhrqmj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwaacjf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2woutvtiy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2soxfdzfh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2gywhkuaq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqjceko.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2xruwbqdr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnidaxgc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkaserc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2skcvvlih.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2owbfikze.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qplrxirq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2huclxeat.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhvxvpk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2onwolftx.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqwkksk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkdxbok.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2agsqcljk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxpeiya.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrhgowq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsgkgfe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdcjpbc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2glnfzfbx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2qenyhnzm.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qridixzh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruaoygdd.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rptmlfnf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqfphxq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgizjkra.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jlozorww.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnagnhvw.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqlttqs.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsjcnbx.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjbhtef.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhachhf.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dueuisqi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sudarrfk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sywjtgnu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwtclgc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnfeguk.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bddoxloy.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfoykuf.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2exggsihl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnghbco.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtgyspa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdjowmo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmfjeqt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdwddwi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2myheqawx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjyaiqk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmqfvzd.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fkeciazg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zombkfuc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwndjwup.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2agssyymx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mttxelvb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsfabki.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmdxbsi.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwevixcj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcyfdbq.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2abmvhmra.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2elhyzpuo.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dulnsifa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xstrhygo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2nnccwlko.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwopwxu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2dskzqjhb.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qykybbqd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2oucdurdx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2cidjlxeb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iejvxdri.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gwagzmqd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqplrake.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzggdrnr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2slaxmife.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2venzugvr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2izpfcwhp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhihrhac.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyemrlm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnllaflg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2flgimruo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gczsnfdp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqijdfrv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zorkjkoj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvyatrb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxyjmmz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zylsmytj.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2aypihaoo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2zebhpwdj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2zisefqfr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2eikzwznf.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2eijcajis.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcxlqwd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgzttgr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvytira.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yuoaoerg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2asaljypn.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xddpcsdu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifozrrai.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xoasdqxe.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2facumthr.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfrphot.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsgxhky.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpuriqk.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcfksep.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2baudqgev.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2svsoqieh.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oexghxhw.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnruetls.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvjywsa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wflvuaeu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmonvyev.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzlkdzf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyzbtaq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2llrrkpqt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgjlrmn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtpgrkm.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wsscrwrx.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgahwmvd.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpdccra.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2glcuepwd.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2svbsyrca.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrnrkgv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvvwumh.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2olkyuilm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjvrqxa.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oybprhgy.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwppvvl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxyndhd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbkqavo.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyswtnc.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxpzevz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxxxhtp.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2drygjhok.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2phimbwuk.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrrwqao.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2anjuivcs.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqsxhfw.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkkfyhw.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqiqqsh.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpggvqdf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzwlykh.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkbtcvz.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaixrqi.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2icnuahho.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkismbps.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keikmnuc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dngmhovq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hclsbgrw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsitqjqi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2seumehdt.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbbbcin.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnpozpb.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2esnsevxv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgbmszb.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjebgwn.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qdejbkpk.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vcypttvq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjvfiio.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2elibfurn.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2cembzhpb.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcncxfn.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hmakyywq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dyplingj.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxknfoe.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjfwice.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxvohfu.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvkzuyj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2tephdgiz.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vuofuymg.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2toclmnzu.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2foloorvo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuusqrk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfoyuiu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ocaexetv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgnhers.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtokefq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2elrnghix.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrpmsus.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksoukvuy.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2fatagivq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmnbdtu.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2duatnuyu.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkeltgx.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsliyrb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2pthpiplh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2xxotslpd.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2utxzohzh.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ztavrjyh.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2secmlgqp.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxnxqns.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmmlgmm.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrplgwi.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbmyfdd.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuholmo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2thetkwcw.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2yenwxwgt.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grzcsngj.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvfjpwq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiuaqlg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqarkvb.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyuhxml.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcjumaq.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drkyhqtj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkamfdmi.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zppikhep.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgmwpsr.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nkumuzga.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtzknba.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzdsofu.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lafsxjbf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdqeecf.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2avkkqxer.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhfsqtk.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcntxqmp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzuoqai.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2eufcizhd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2miqqwyfq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfccchp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2tzntehgg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqlhvbf.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iazifqss.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbrftlo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvnqmju.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdislrdn.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrifjak.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqvwixt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abnsbixn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2mteybjob.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqutfdi.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2oiikxnei.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeniymta.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuubpjb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tynynnqc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdcfgcu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2qmoxshyc.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2shlgqjor.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2knkrbgye.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2suskamaq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2xncliopv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2diuxywvs.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2oswqmwqq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2yerdssfc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pexpomxv.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wmudvfgh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vapvbmwb.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ezaqtoon.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2sobvuuch.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzogqnqk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvmhaje.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxspysc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iverahqx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wskyvvzu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wkclhlwf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sditagah.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqrmlxe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkphksaz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hokozckt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjsczod.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xodrtlsa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjzwfvp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfyrboz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wuauhovw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqayekzg.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uimudvme.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2uokclqwt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvcfcrz.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpkcknv.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdnmwjs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ejabxwrt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoihhtho.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcoodich.html


<!-- 参考信息 -->