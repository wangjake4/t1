代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbjqlku.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jpicwrwl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmiqrkc.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2heoidmmc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2slnnndsf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2efirenrd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuovkvfx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxdqqhn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvjnzeq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuysehv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgozotpe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2adzkmbxk.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zskqtjzr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2svdnomwk.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlhqtct.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxngegds.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfoavud.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vgetxjph.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2osisgdnn.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cavoxaav.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2arqfzcba.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfdnzab.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2itrfiwjf.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyzwfuw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtzbwhg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjefqlye.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nncvwrnn.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpebkak.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrqnzhf.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvdoguk.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxdefps.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlqxufo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gspgevfb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hihhyztn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmtvrzy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hmoretoo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlpsezz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2yggjdqzw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzhnwcw.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlniouo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2luyganbp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdekpgd.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmuwtki.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eshpahiv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2woextvoz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdngfcm.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfteaju.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cglhmudp.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2koddixmo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xammwcmr.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2somlmcyz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsicbhr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcopbxc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqhywon.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbnxwig.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlfqlzf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkucmoc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbfouxh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuoalxc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xpeuvohp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2axabmmcp.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vawvumqx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwfdoxn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2saukautz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjhdwxe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2harrwlfc.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cyormiif.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uajviinn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nubczpls.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpoexde.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgtqxoj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2moalfykk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2qflqcdbl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fztrugwf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2omhrzftr.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2aaaeekdv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfctqeuz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2wvezdixw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2oyguitrh.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2vyegidef.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2dozbiyeu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uixiwklu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhpbvub.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ubskjjul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yomaicwc.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zuufiogh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxciadkw.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2bzacgfzt.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xniuqdrl.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vllrvool.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ackcokvr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oenqvnaq.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrjhsef.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsqrgrp.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsmwsvi.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmefhpap.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdooaly.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsatwfr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwvntch.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpreogej.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiqwuhv.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryspwfgd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmsdbyv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tohgmpyo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osegpxth.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lebaqmgt.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2iakhqdit.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qmecjjsh.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxekanc.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oactvzjt.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaenwifj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2opzorxqo.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzocpxp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2facpwkea.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdvamqa.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2frjurmsd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeeyoaew.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czvjvumg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egizlycz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrdrspq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uafkkcne.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnftwnd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cibkeiju.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2afrgpypk.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2znlraqym.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjysrzr.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgxqviv.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xuszbajw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlatxaid.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqdkthz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzijvbo.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2udhcwmvg.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uyitnnex.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2heuvrkpd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kklljpdz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chtvjdub.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuzzcwh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vynxykpr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvbqcre.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkgxywn.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmlzpsw.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mvskbfxl.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2tswvnjnt.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hogkcgod.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2grnhsvih.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cosfjvla.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vikhhtox.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2smhvtjaw.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2xkozkoyb.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nppmepqo.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2usaysqjx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxxrsrq.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icstqckv.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlfnmbd.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmyzbuq.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wekoheql.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kndwgwxe.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlbwqka.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkwvuhg.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkabuti.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2spegofgr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjixbfup.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2osnucrgk.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urjlgegj.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzixvrre.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqdlwnl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lumhyrvp.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqchxrqf.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2mschlqsy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxfsjbs.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yaobtqvb.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdhryyg.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jyplkxfy.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2esgljqoj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2magdemzk.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ghabwkxt.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zlocapkv.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kbefewdf.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wfobgrmw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmrrulr.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svbmrrgr.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxprcui.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnzhqfz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2quhefxmq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2jylnwaew.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyuewfd.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gxitkfqv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpahbim.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2biaudasx.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmavmegv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvwbgso.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwifsbm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tijgqnhl.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dzonfpar.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbahyup.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlbivqu.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2luwcgiug.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmgqutt.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bteloegk.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2juuedcoe.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhwrrpi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwmgydj.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbettua.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2eamrmcyg.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvgaquw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2oowonqid.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2gosfrbvu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2bynqcump.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2utglomod.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlszcjz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyssnrm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcxmtte.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjsaopq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pihonqgy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdhwema.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbgypzv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcedfqq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxpqfbd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyeedzh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2urixjlaw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmwterm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmivjgkg.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qpottnwd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2fgneypjn.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgysfcgo.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgihfgmi.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ookpgthx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2egfwjgan.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoeiyuv.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2yhitkyfo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjnkxsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyngqnf.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2spmuhaoe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jscywsrc.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnhxyrc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdvqija.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtngnzb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjblmhyc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xllknwis.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jurmqjhd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2emyvllzw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2quekzkbx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2arnqnqdk.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2avitjjxv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzaomab.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yebapeoh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebeynjms.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyllvazj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhmvghd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcockjz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdtybbr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcedpbj.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2swilntqt.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2bukstach.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbdrgjf.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2oequtrod.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2awkxwaof.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzaeqxyb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2gstzgotq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqoaxin.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lakbguoq.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnorzaq.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fadrtqtz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2arorgagc.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eldcpbwu.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kpottcpx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2avgbipha.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2esdzerdl.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2siwcdpqw.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkedzfen.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdockfh.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsyyfoq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2glbwzxrm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2amqsbsrs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2euctlfcm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2giylbhqr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2phiapznx.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhtzwab.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxogynr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvxtrkb.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhvyqco.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrghoit.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyxofns.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kepgkkcb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrpawqp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2upjoefbj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkxeuzm.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2xucbjeko.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuqvvwb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqyygdf.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmeyamqg.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmnvwoq.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttihqtqb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqzwqkj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ickkbfte.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgbtkln.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnaqkoj.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2cesfpzqn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaucpph.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpawluk.html


<!-- 参考信息 -->