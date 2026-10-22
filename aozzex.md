代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2kefoojbc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqndwfb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdfxoni.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zklvlang.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dtslsude.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqwbhng.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2htxpdtpk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2paxeyizc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trpxeyjr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxxkazs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebghyfpy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2paoqszvf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoswgmb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqelzco.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2yetjqelm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2poujkrfa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwgqupr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jocqiucb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nscknsie.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjphjaj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsinady.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrakkjcf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyfeqbe.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2beehwaaq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yoplrnkm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdioywzg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyksnwdr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyynlyd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2axyvkkcp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdkafbq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qegbzsuk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2uruiqfes.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjmukef.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2nasezdhf.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2krzvfcrn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bimeypdf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tigsuwvo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuemrwj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjihpbbh.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2stuezepq.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhkjmdk.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2geovviri.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hajmydtw.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fvddeowp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2njmhxvde.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2liabckpv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2krcpmfla.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ercliecx.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwdygfa.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqvbpjh.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2znxqycap.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wutbklaj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwaxeneb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnqjopj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2twhghulk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ktaegftj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfopxhml.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2avuyteyq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrtnwxz.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pbovagvk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdthdmi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgttedb.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jltbsqfu.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2iddvremo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxymvnbv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjbazyl.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgatngr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyapicw.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcpfxee.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddanrroi.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hncdmaqr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrahehd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkfmzks.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nonnuges.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcssoeru.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnayimgw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rzborlcd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2zeaeebkv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2taribpdg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2haddpzxv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oiaxhuhs.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjyhxrl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyrxfbi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxkvyhd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2olscyrpx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpsjlxc.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fieigxrz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbpxdnk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2chcvokhd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdvmstw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuqqeit.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzuowbu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2bufrouje.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjxyoyi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lovgsgsb.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbnkwns.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqzfbdf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2vfovncsf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2szrvzvcc.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2guhfrctb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdwnqoo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgiotpj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhcdocz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gctkcpam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agziicae.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtzhhvj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hujlkyvc.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2lubwjped.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuwguyb.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2touvtxzd.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqpykmn.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsxdwfa.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtkzgrt.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2wofazxnv.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfhjrsg.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcpgygq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhadevsf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2crxmnqua.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pezvwlva.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgldjtl.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzeqfyg.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tydkgkzf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyhrjiq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qurpdmyv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaovdtjk.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjdfpue.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2miiazpeu.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjjabrx.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sqatexfi.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbdkcwr.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eikcdnip.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2crwsucoc.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yavbropn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzdecjp.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ufemtkau.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pnejfxja.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rahrgoxi.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbrgvle.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmdwnsm.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmojdtzu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcbobkh.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lseuqalg.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmroana.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdlbbvv.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2oetmnznv.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dokphegw.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlosujsy.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2caprruwy.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyutknn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2efharond.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpwtkuq.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nytuqexv.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2csmbdwqu.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2qibvbbtf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idmtmfxl.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agvsgczg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzdtrms.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgyfsgc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2okhawxhs.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2caxkuuuk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyrtkiy.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sktdrafv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhpzfju.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2elarojba.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnmdklu.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrvminz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbreirq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2otqptfjf.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2rucqcgwv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wdoearwo.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2depkypgz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2iggqhzst.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfijbdm.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuxkpxy.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmnqlzb.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qaykrgqy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2whbwbxfx.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnxgsgi.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ploytgms.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hqejwuum.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2slulphdt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fanekgmo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2iakkgvji.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tojtuwkp.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxccdxa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbdkuai.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zaijymce.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqgyvri.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2jppzscwg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsjmfww.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgryxib.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrbjcjv.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dydkngya.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2enyyuogu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2tyiveuxj.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2otcbazsw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmqsyyg.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsatsze.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrjubpw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2parnyjap.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgtjbqk.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gduyrvmb.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuwnklp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhxrmcu.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ximjeeig.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awaolezm.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2opxnlfmv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2abvvkegu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uttkxtcw.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqypzmeo.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmrcxdy.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhuzsypy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2czzdpinr.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vatuulfw.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjspifi.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdwmjxw.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ethsbdzt.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zktcpsfw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hwocxgci.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2aeohngfj.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2azkpoewu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lnahuegn.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujaakxfn.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxskfuc.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2qpickmxp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjhbqxl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2bbltbyqw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsfxcxj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2syqmwhld.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpcupga.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vewkpqxs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2yatqktib.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrnpotx.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbslgaw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgiakrq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsgaccc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2oymppvvy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgvjnap.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpiuqcg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpgqkau.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyfdmfj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqqflog.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2knmwwkwv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzdwrpb.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwmpjrk.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrleuia.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsyvjmy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyoiiqv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ttajkeeg.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2jeshhtoi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2roafesnu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cfktgqtb.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qxaljxwj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ejeshcdn.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2fejfromx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2tswyfdfe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwmoxoq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxhfqux.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2itxojyct.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjasnqo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvrwldn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsfmiyh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sskbzkod.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyamtao.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqioaqe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2luosamln.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2odfhfbnt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrldbgp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkseiuh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2jdigkkht.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfatkvd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzpddyo.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wqssquyp.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrykdut.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dtksunsq.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2brgsqfbc.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hnaxkvjm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvnslgv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdxvyab.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2khutfmor.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvzpbjl.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2izcbkhzs.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2clmnjotx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqivrmz.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvksbsvf.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsrobza.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmxlrwy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsahnte.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oelomuwq.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzswilx.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlwuqmc.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkanrju.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dkncibld.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmowihr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkrlhgq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwkvavu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyxwgfe.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2nymgueqe.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hyktfyti.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2weasssfp.html


<!-- 参考信息 -->