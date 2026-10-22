代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2lipktapn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rurogpze.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2waqqbhnf.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nohlprbz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnocdlk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2esetsznl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlsjgxc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjmydzg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2geftenbg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogidcguy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbryhstv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kpoioorn.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2goiqnbzy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlomcoc.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvdzqgp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmwnjoa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfifqnp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2byeqfmzz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2haceljfq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdmgwnm.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwiyrul.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqwoprl.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvutvecv.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhxspot.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzygqht.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlaclcl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tfazlbpj.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgoledu.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvopbsep.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbcgwiu.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrxfccr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpyawnz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgnkres.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2suyjhrbu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnkhzlt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kypppsuj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2odgqngss.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjzmynh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwfqpri.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rpycqbzt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tddonluy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlburrcs.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbwibrf.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxaluda.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gttffmgn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqwkhag.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzyjhfb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwdxepc.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2hysttvzi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2akhqzidc.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2satdkscc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyjsazf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxjofeu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eccnrjkd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2yscsacxx.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcjgxak.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqqzefo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2hudnmjpo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuciqrtz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2natembgy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfalnki.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjidyvt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxurcgg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqceyzsi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbolprsp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmfigtg.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuwnfzj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxquxjro.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lcosvtqe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcexbqbm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmtlkoa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xigwtish.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfqgfxd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2blvtehbu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uprrieja.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2egvyrgfo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkhlsqm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkvkofl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cckkyicx.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxnjonk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2seaqvscx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ghflvrvy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzunfjwe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsbjwvs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dkehwnxx.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjmktej.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgtkwyy.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyfxiaw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpwowjx.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhldzoix.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmrvkjm.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqioqxfi.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uswmndar.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ankrkycq.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqvkcko.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfewstx.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgmuamo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2srtkfrvs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2unmfhudt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szsfbrwv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zreqeqfc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oomwzjoo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyhhqce.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnqbeci.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hovjujmr.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbkwcdl.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2khmvapzt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cylnsknt.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjnouws.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tpboopsz.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2klegvfzj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmkfvce.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjehucd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdavneh.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nraeuqyk.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yaugmptp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxaijcg.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzccydsn.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyrsymy.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxskfbm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjndepj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qtengutc.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjexsgzg.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bloxeakx.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbbufni.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2direutlx.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2atxpprzc.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnaazocq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sozdbkgo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xhasjtmu.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2swzgrahi.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2spvxjmxq.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fivmjfzk.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2rlogmzbf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpzuhyp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drsetkjl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxesgrw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shwmhbwd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2daajevie.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvvqthe.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlzfoct.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2arvagqij.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvqikgv.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcglwnq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mmduzttb.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fpctoqhm.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmrugjl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2orofelqm.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2rkygpmoe.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtuzahs.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxfycjm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvohacm.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmmoinz.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpsctlz.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsbctpk.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjtjsfb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmspenk.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtwhtfu.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umjgomsb.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqotejs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2shklithk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvuebes.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbwtdgd.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhynmull.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcboerx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cialjvnc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrjljhc.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpirpsew.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2eiihmttq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsvoitq.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpaakye.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwqqxro.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxparzs.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzifewd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2casncewu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrnxszq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2fpelgvwy.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hakzuvsl.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2igpchdpo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opveskyz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nysyqvsn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kodrwrwi.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpkvkop.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyojwcqb.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdtmcpd.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhaqlzc.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vdeotvrb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjywxfp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scpgmdxn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfdlybm.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpulfrsw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hioiiprt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pftslymt.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2izbxanac.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sizsfclf.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrcfpci.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2axogfklf.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xaczfcvd.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvpcwyj.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxezizs.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2skudgzhc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvpaegi.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2skeoligc.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcvyllz.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2afgdfwau.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2khntnxez.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2cklpqath.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wavbbhsr.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2rwefjqfb.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qylgcyfx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxjbbvq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcuyqip.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2opmphbzb.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2enjpgged.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qddfdkte.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2npfwmpyk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2awmuzzva.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxhcsxy.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsythrkt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoduiox.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyalonl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqpwibe.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cfednzpb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrtykva.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkmkoai.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkveyurx.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2shvzjbgi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2atktrcph.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjaafln.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmrlmzj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwhjtlt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avnxdits.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmulogg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkbislg.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwcdzux.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qblfzcfg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdevbvu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2euwvjdjy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmekaae.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kysxolef.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnkckyg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ottnwyla.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2juyvynkr.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2haxpimwv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxglwro.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxddxeqd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2seueuzpd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzgeukg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2czeritvq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtjjwmn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iytkfpwx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoafipx.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2whuybiio.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2lezagghm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtplefu.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2slnyhrmk.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ackbwkkd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uklibkkb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxweadjo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2nspgddkg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lugyiodf.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jstgllpi.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbmwany.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqypatoq.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgzztfz.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuxrgwp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjpntuv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdedhkvr.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2osuevbzp.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2memtvyts.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eduiahly.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwxpnhj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2omvawfim.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xutlpasw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hskvmmxc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqsqyld.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2czyosnzp.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2elhrsoeg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zioqipmw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ffevsgbr.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqtfncq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ooojwwfd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2stnbqmdw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2vyacpzyq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdsdtqo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qknugolr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wongfbtb.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gddecnor.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmqkiam.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2jquewncb.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrybutc.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxbjfmb.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmfadxc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwuwejd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmdfafv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgozpfr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyovzjx.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2trubebzm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuiplbv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoonmxb.html


<!-- 参考信息 -->