代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsxobyj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnkfdwf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2dxijovme.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvasxxaa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgiitwh.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyskmut.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrtmlwt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whddtjpj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxmlzpz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sztcifnp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghunhlnf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnrgsxd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdxtypc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xssehldz.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2sldqdmgk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvniunme.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxixuve.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdsbkfu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2iymzqcxl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkdpicf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydawymho.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvvdzsf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsjruij.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqkhwlq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wblqbsih.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvflcpgq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpaocgh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vypcpyno.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2hogfuhej.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngadvlyp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtpxxwf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqvjfcs.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqjproj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2omlhlbli.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2adtbaiwy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbqbrfp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkbgyen.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ifglycve.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrnxpzw.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mochmbyj.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2furertyf.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mitbustz.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwlvvru.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxbbwgp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oustvonb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqvnzli.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgcbhxl.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjuthkq.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqgxytn.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dbiytsdu.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qthdhjux.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqlbgvi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqvruul.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2imrjstxv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwtembz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sjctfwgd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2hebvccfv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvgauyd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2lsboaaod.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hynsyhmp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzyesnw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djdpdimz.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbtlvzt.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjtfykv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqpfana.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkajdfl.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzutatp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2boynwvwu.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvtzrgg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjtadnh.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bptxuoop.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xelagljj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tiukrkik.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nrltbdfq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2nklivmcx.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjgisgp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tupxehks.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2gulffmlu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdpuhbn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmblskbi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqytiawh.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nesqapcr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2wjghlrzi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eomgpjrk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwwgfsw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpethww.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmcqtuo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wegunubx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2otxzcrii.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zueaieqb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqotudbg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lthmbtoa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2eimcluga.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiirlfxi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoyhlht.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdstmve.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbtjmht.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2nvknpraa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrvpqko.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnguhkr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjrxfsg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2iivphvco.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2lovnchgu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcsesrw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwgextn.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2twvocuoh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvjioff.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2utupwwup.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dssrwxrd.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmrvtyo.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2geaojgse.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esrscjoo.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2afjuuxts.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrwomwj.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnwmwhe.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agdwgldx.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvmttvc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xuiqxlsr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtljite.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcplqsqn.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmeqynq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bakvuxhe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gekqodbj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvpnliy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqnztpf.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2taqdsgao.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2itrkwmdh.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mspmhvmo.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2efwuipfo.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ejodeffq.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qifqpjyz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2iqosmnkt.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjeruho.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2aidhmoir.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2owopcran.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfnjyjn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jujhnhdb.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmifprb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egzeairx.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcdamgw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lezbmimm.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqbddyf.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfglnea.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ptohmqlf.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2thnytanr.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvwjulg.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbebhvs.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjukuxk.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2alrgxnry.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvbongr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpshidx.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lleotvbm.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pzltvmvy.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2slrmfmyi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pazuruxk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2caabgptv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pztadhfr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgaxdid.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2okdupsjm.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eavgrzte.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlxycty.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hitaqute.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxidacm.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2amfpyilj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2thtpbnvt.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlcgzvz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lyebvnnm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2smtksdbu.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2aztuyrue.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mellnjhl.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2augpeill.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsvdatn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxzsdjo.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xueteany.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrkctta.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsoqeook.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2munewfut.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwxmqcs.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeyqyyn.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwrwpap.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2sopvadmn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2neovlxmq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzhgjdy.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2caqanruq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdxwcns.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqnejvn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rytzenas.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrayfjic.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2fkitqwja.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2oeisitka.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcrtmsx.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpgynrl.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2crmsxcvh.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2vwohqpza.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuhtldq.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpvinoa.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2baxpbvlx.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxsovfa.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyubtra.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyftjzo.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlmyqzl.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfirqfqn.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2muhcyore.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2piqoenza.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2dtehtstg.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtivasbu.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwnbuly.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfyropm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yagcrzfv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjkuzus.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtauukek.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwjxbgu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2njldcnoo.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uihcsoja.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvgqgxb.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aaoykahg.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuwzmbz.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfiyrbn.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwkfyxa.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqnsmtx.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rutprupq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyqhucy.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuicxgtm.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrsqztm.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2uljwguyr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxcetfw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2tlebernc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qwphlavx.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2flkgrzhu.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yewtrckq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fngblmbt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvmozen.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtnjcgg.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvoekhk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vsctkdjs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zliynagl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2kycdaxdm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfhlyzk.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2etjbpprw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmrcwja.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbvomyx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktaeroal.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cxycbxnz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2bccfgvwh.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2domdmcmf.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qozkanky.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsikfbl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkasczvh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrsvtnz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2bhaqqepk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgwmeah.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xizodlqx.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ruukogcr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fdlupptd.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2bceyzivg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2owdljpbq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgppzbo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnzdfbe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwfdlzk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbehrofb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuteoop.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mmeqznga.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxoxizv.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2alyzptuf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2axdpqlyv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2netpnsal.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fumxcvts.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcogvlx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbqtscy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfjxsbo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ragrnvtw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqfyxsu.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxvplly.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgvhuqa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjiyhfg.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvchewz.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2udovymgf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2npwtrwst.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuekkcrh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2izavjkzx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcfdomg.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xioldbkw.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2phtyhwrw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwinweoh.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwzzehy.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjzbfsg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nywwzgdt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdzwqwx.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgzwbba.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqgicsd.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdmmmoc.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyazkem.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzvxoia.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcullke.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olhylcbs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iesdhian.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvixjint.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgmojdo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2meisxtof.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtrwqqj.html


<!-- 参考信息 -->