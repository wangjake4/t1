代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2uifcuhba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcybttm.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2sfedlhbk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqtoeca.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpdzaws.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqmgeus.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sybfleen.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcsajfq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2akgspyff.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2woqyrukh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2usfrhiig.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdjclfn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqezpxy.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iewbyxxn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2porbnlbd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdthfcux.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsanoyo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lshacnpg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvigvls.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2btmbvyxn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2avrwycfd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqipwtz.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2pepblszu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkyvvdm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcjqnme.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcbyfcx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbykusc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrldsutm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2bthwvhmb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmxqmti.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpqbtbi.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjbvgcm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyihbrg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2mexakyig.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2izzuorkn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2suuqkvzc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2vclafugo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2veplceon.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iirdqvat.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzvwrku.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjqdnan.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2smfgnzpw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sesyowho.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bngykzoj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jedhwidr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrpxxkd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2btmklztr.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxjgyrz.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrubqya.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ommrmgpu.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqatsrq.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyauboj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzioqizf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgveobi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfzhlmx.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvqqixw.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lecykbae.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlnzico.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gttgyvkz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzajtmnz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghinafxl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbansom.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2nbitetzd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eciozhie.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaywnpl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgohgbwu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2peuyjvwn.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfilppk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vouxhgfs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vblnenle.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2chthblyg.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vamhhyil.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hahtrina.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2addrxwke.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcccqjub.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2aizcrald.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2iixnkywb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfvkyie.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvwnkzz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2laudilkc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2oxaakgsx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zjazdeyv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2rajwuocc.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqpsphs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzqidsc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsjjtgi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqenmwdt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tqifxdzm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2usqmpmmo.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwouzzn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmzgydi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmehhtuu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdeukwn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fiilofps.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wabscscg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvhckvo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsvwtps.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkerfpcs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lisytwts.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfajbfga.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxmcenx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2clccxbxg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkthsyh.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fsngicih.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxecrmmq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcggszw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vqisctxp.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbtqvyj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2rxajcpqf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiltkgn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhkhhhp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mqinovns.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmjkmir.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2umvjulnl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phxkfwoa.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbjmreg.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vmixzmws.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzcuwkn.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rajyupbd.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2waxuzwza.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvvbbue.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrxbwyr.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2llkiwfqh.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2anbhalsc.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqomhny.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ghalnimv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2spnvbqet.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmswemyq.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2naaeuldu.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwcfdcn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zugvzavz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyewvrr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcoeedxy.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2orpdhyzr.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2axsmlgjb.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ghoqpjqp.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvbrylg.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwczmbf.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pupgdjuh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrymgpf.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vaifwqaq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2upxbkucu.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdsuvzv.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2molmxkiv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znkjbifu.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbchqogn.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afncqlct.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkchrlip.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqrcocz.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuiolfb.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkogqpj.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpfdbce.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2shaqdcua.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oilhfxxr.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qyalisos.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbiwvvp.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dufdblqs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgfpnvn.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2abuhhbsm.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xikuuqmy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wytlyrlo.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2byqqmwph.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyjybbg.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmoacqhk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2askcvjgk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ludtrbmx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2udslvfoc.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnzfozx.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnxujfv.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qndfejsp.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrkyiqi.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmmdzbp.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jqstnhtb.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yolfkchh.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pggoisdk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rowmpakt.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2yolkbrbm.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gspavleb.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhnvwrt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2afqdpayv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hiadtrhg.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rupsoaiv.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgvcfdy.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kheqkokk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fgixvpmr.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbzabgd.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zplgigjh.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2srtczkva.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2toqrbrkv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfiiplb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyzkwrh.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmishac.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrygvbu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2psacgzju.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwngzxf.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyehyty.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgkfmxh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpdaysp.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuumgfp.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdrzzhs.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuyaghd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2phygjknh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbxxuhm.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ltigvaxh.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2vltskqnx.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gytylrxh.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rpngjmqs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juxuugvk.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhtqnhz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzswwtz.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pencdqat.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcgztrd.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxvdztc.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qooemwhu.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxsikdk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2psiiygeo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxwctac.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iopsvouy.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgfoxxy.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byknblrb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbmumpp.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfcunuc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlddhnz.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dcawppbx.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2icidtcof.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2meohvpxn.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2izhozhtn.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2awqxkbkq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpnlfyk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfsocsr.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qepgtbze.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbaayhj.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvffeea.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2dgphbecw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2bltnqfdt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2hxekvkle.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2felmuwku.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzhalct.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyifswfz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2tymvvhgz.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2isnvcpkl.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2muxqeaph.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwrzgjq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2haoalvxy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcgajhk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2phgrfojk.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ismsjmch.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2kijsjdss.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2zohlupcu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ishhjtzv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2apawjnou.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmtdwed.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2iobatupt.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2chtgvhvn.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmbfceg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvcbuvd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2crtkfywi.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2dtiqntxb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmkelgu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtxainj.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fdriicxu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxqnxke.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2jolujyqi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeizkeex.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2afseksyo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmabrgrf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nioxlpcw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmazcmzs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvaklhy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nqajltdj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwjtayb.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2boocnpni.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2lawxapzd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2njmxyhos.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbgaohc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcupukm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxfkzxl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqdbzwf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsvsnmw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2grytflgy.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzlejnp.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2asbardre.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgevaxap.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjqfowg.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ynefkzru.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrwxvys.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmnpusc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiwavje.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnykjpt.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbyasfz.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2phtiynre.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqdxmlj.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksikxxjh.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmduzcaf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2quwvrcho.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhacypiy.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlxazmh.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dexiqnzk.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2crhoqkks.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2myqrtyzo.html


<!-- 参考信息 -->