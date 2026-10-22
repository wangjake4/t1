代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2zudoglzc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmarskes.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwmlxwq.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbjbllz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtzdzam.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwajlzis.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2twguwxis.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2buqrhsls.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkijdvqt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvgovvv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqsecyb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2erbfxiwd.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjnqepi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhowauh.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2swcrdldg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pomrluzr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlmozmd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjexszd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2yevnxkty.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmxeunp.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdcnlxq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkakodp.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfrknml.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqygfjy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcktzdmq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2luiotuof.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2utqvpdde.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eeikxckt.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbowjbhd.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbaonpu.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tblrnssa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2opvdhgcu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttisesot.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2daghvgdg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2eatzeseu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmcqvaf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmoboqu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrfhott.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgctiktp.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxyxbri.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoifdvs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zypxckhm.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cskinwor.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyejlhtx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtypkrje.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdfgzal.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eimotqgs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tanhhddb.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdnquex.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymexyroq.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeidzea.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnktjxi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtrbzyt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwlvstn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkhtrwd.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2miwpuegl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ciosbdhj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2idwnsmbx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyelfaq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjbkyuc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfphetim.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpxvdbj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjdjdkh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrisgcg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmkllsr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgizbejg.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ryaybgit.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlujqkjv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmsruhj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2plaizapm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzofukf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewujrchu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2bziuqvhk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrbsupc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjekfjte.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmnpbfc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnasknr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2heaqxlgg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdesfqb.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ngypcmhm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnshtmb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcbxwkq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2vafsdzje.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjcfjhx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmzakfm.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwjjlug.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2spnjifbd.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpeeanr.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2avkcgazs.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruajzomw.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2msisildg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvgykmh.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkbifpv.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwtaxhv.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2csjoxrxc.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmrdpnx.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2knxuhxrd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzsoipy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxjbdvr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmpmxeh.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skbzcnsl.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omavtuei.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2krpghqez.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vqakqpto.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cysxusjw.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fygeuiim.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yambggcq.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2krqmiooo.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kefcvqko.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mukmpltk.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxxlpju.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhwrsug.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgdiugf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjkgpkw.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cluxfgnq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kldhbsxk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfqlavp.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adtttaox.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mosdrnpk.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbdvybl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yooyisho.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yccxauqg.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2agxatxao.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjebouc.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfjtvnm.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsdtlkl.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qinqokjg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hqeozbmo.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2limbrbjl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkeidnr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fsszttpd.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tswohvcl.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bhktvreq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlwkrtn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anlpaqmo.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vekjtydv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwoktikb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2saikfrjp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jjasabzo.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzqhktl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2maxxlayr.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dpiidhbb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvanoue.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dskpczqq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdwjsyx.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2boboqzul.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ueisfqeh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2edhdvqrc.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2fquqawng.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2msypewup.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbexufn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjkagxd.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nukuujyc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbirygy.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmdssjf.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqlclpx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2aovmguul.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vajbujgz.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgybnxk.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpgssoo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrhwfto.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svhzonva.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpleqoe.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msajxina.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdimgfc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bigwxqhz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyhbxlb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2surhwykh.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbrbxyd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2tggzandv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxntbjr.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2mkiiqnpq.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2sryxyght.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcrqpry.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgljjyq.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvsimnk.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlxlams.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhimhgq.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kjykxoin.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbduiaci.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlapiwbd.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vifshnhc.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeegstaw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxiqkuc.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkveiaa.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fazyaqkw.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzzzras.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqiawmn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrrtnbv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwgqivw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxbvnew.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhaebbcl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhpprqb.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iudivsiq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2exohtlmx.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcwvmfe.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pltghwgn.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvhawvl.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zunqjifu.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qfchjpeb.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmaincy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yjveydqg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2koyydgpl.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvjayzu.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2kfijnsue.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2decyvvkn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2kixxzbtw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ribwczvy.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2exvskdue.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmyvlnj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqehznzf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrxbokj.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlinabqg.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bdarvmky.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2foaborsv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxaxkapy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2knsxxftq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cliorpov.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuhytny.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywososgk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ffooqlxg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ualkpcwc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tpoamtxu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2tungmdin.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkecvele.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgnbkaa.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2arpzahfr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygewoxqs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbnqgzv.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjflrnn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbpywnu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nogincob.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kxokwqee.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2orstfjgn.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcdardb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoefdbpn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yukwxaxg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiamjsht.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjqnomq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztscgffm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uqixxzqx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kstfuequ.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tywatmcm.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmqsnzf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2yaywjdkg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pusxxyle.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2miygnmst.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbiadjp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdldbwi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvbgvly.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yavmpwbn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2heuzbteo.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2abpassgr.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuebgxgq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfblwps.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2skxsrkkc.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgqxjbe.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hyefwnwg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2srttlmrr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvoxkdqe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2liqqlhyn.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqlzlnr.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wqirqmxi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2adwrkjli.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2coiqtkkv.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kikvgnqy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxefirkr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpixzyj.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2svfdxwep.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvjvvit.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2voouqwpf.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2kdizconk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrktrcc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tptvrvdw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uilinfdz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgiiucr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqwaebz.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkcgtja.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2snvwsyoh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2iibsxern.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2wptjtoxd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2bieembjg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2odndhdha.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ckclhyup.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2stkahtzp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyheukg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2skxvmwiv.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnspjqb.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wyeogfrw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2evyzwlzs.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnamurcj.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwyczhg.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfxzbbj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2axhhqxkv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zllgxcgr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmfkaqn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxbvllb.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbhnimd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2beposemr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2acnoyzvi.html


<!-- 参考信息 -->