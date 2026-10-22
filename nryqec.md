代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yphjmkck.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxymdqdo.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qysvqcjc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfdrozk.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukukjubt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkeiskmo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtypvej.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmuzzxa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2odtykubf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rngqbtpm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgbhytm.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iodbrvbd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxfbcms.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2otlcxork.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbynoen.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqromzb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2squiqypn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glmrfxgo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrfxygl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjamdij.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqmpywh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrrjfnc.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ookknrbs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdoiazdz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2yxiejwtd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhhkkmq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjpjisq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xilhaoqq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcuvwxp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2awpxrlgl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qonvuimt.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2icgcmpjx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxabbvn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvztypp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2orgqdhoz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qteygkxg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsojuuqh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxyzfcu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntszvptk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvipgonr.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqeebjm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2vigujewz.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvagxclj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqfsdaw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhrbyyz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qcohbeqq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjpusve.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdoulrid.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzhlhsg.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sisanxie.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpnqmvt.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfqpccl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkotmsu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ievlbfuw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fcailrdt.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwgzvzb.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzggrfb.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aeazlgss.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbyxtge.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2elfgprer.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkkcdpv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxldntn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgenjzl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2omnwtngr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2patrykkt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqostvd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwyrjbk.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2izjynjpw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpozwux.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwouidb.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqvsmxa.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqsabru.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwijvky.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzueyzyv.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2njxdsyjd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kitmkuyc.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtyaxqh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2barmckwv.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxlomkb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gkckoeph.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gxawuymm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcbctdf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2lewojdze.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlksnmga.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nswijxht.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuudyao.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wctphjok.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iaorbmra.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuzrinq.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cipzrcio.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhlqtaj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbzmjqf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2paudakow.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cegjywag.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jflenlvj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2inyfysru.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyyxqvk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxlewws.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbruexac.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2scyhbilm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgcmjze.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyliaxr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yultbonh.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwzyphm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgfzxnc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzaexge.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvoxijx.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzazbyq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhizpqu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2oljfyrfz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2emlefuyz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hgljsuvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqfvsbx.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfpfkdy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhtxesl.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwceevz.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuvhwha.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezefbqtf.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhndqbdb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exosahss.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwflzsva.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnwjdmq.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wupxlhgr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oplzcaxc.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cinsvthz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxuwukv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpvomdq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bavxgpke.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrjohvg.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wniylmzu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcbtxms.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xywcxjux.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2keqipamp.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgnhgic.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2brecfauo.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kkldgbru.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lopdiiyn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rjitwbss.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2styqmkia.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbrtoql.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiqcnsu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuguqko.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2djnoxinf.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2tbydfzbu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuugmqq.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kktxiqhq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xccpqpyu.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qllbamuc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhoikmpv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wctnmtra.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufegonhe.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgrxbtn.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jajhprlq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cslqnfcd.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmljonr.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrhquvj.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vplerjwm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2iathzbeq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2isfwaydo.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnpuimy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgxuyfm.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2tljtdtri.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaxqugn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxcqjex.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kndybflw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogakbcpt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2rnarxsjh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qohomrxe.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2klkutpbx.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2asarjfrv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2itxhgzmj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqbrdbv.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwtcjmj.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpqrvkf.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcyrmvt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kiehsbjj.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2vygqcfwk.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2heyebdtf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bpotqtnx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2vattgmek.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxwhfum.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azdytcns.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnucony.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvboerwu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2erregasg.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gfakmotx.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbkfqmz.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpgmisw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2lhalgtod.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psvyokxk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjqyowe.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tglsfxrq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcsikoi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2npceifpl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsxsypo.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmaqjcq.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2woudjlkv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmabqrb.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhycrim.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2nusufeuu.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rcupiwcf.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ammpaogg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvrybsz.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkvaoow.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwsgqmz.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2weowhgrc.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfmiuhe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2niomgiql.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpakzrrz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chjbugtc.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eenbebyo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oapyvosu.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2dtddypjq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pieessee.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnhydfw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dytbsqut.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvmdqdc.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usudrbpa.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2euacbbhn.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfjkwnf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nusfnjff.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqhlzkf.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wukzhmrn.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dslwlcqu.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxdutck.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bemnepxi.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqunvmh.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fohwpufn.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2plpicglo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpzohob.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwbjdlp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuzvqtl.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2mudkuzmb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqszrvf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2oynblkic.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wwelkoyi.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ooepqxjc.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvzauko.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rijjaelx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2rinbnzfw.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpdgcdz.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ersfevvn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2neeidtwg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odkfsbqa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvxwcnn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ostgcedq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltezweva.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgjrqqk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvilljt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cljxywhl.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rklzqils.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqkjkeq.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrxrxuq.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvkjjni.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqajwfmh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgduzizv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qymdvgse.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmaoyci.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvbzlmf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owcxjnmy.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbqlipa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yyymaisu.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2soqimshk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2nczebyho.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2avpxnfdr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrytcza.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrvblhx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtjbkhb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uigliajg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2twbamyfs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxpbyju.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zfurlqfv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzelvgjb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2swfkwxtc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nascpixk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2guuxehts.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzvfrud.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqrumxb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qoixtpjk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkqjnkm.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fqofiejk.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxxjuoi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jrefuiti.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xklqynin.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2osturavv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ducmosre.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmrhdww.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2jflzmdlf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyiavkz.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuvdiha.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxxldfx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmpcgwl.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxdfidr.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnxooej.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fsggsyno.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkibaua.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmyfdzl.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swbuefig.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cvszkzfk.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2agpdqofl.html


<!-- 参考信息 -->