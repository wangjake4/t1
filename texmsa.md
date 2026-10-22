代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwhktqp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqehxkm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqxrytt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2odumsztf.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bncxqegj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtzfnkx.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvgmodx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lomuelwf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2klragxwb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rkafnauy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuumfled.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmphqdcc.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxenobx.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rasrsyle.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxysubb.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nedbmhbf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nehdjqio.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvfwrdk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hekhjceq.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbegdmjv.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzzdzvc.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcrxbog.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdkutix.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhhzotp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zogermbx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2mipbcdqf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2yemmodxb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tidnwmpv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2wderfrfh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqefxtq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2fteeyavi.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lnshhoyi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqzsymi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntexrpsm.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eaflshmh.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhtfxim.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtfstef.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpkqerb.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqaqenc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2brrirmye.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2znnkgcnz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2noskeysj.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jsofwmxf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yewjxzme.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzhjvjo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xldjbjih.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2gceyguyc.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzldwoub.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfrtvve.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2swjjhsrh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqcwuhl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oevmpdjj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuyaamo.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdvbxxe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2twgzfplr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wngitbqm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyukhthn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gggzwkfj.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjeozswu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkopnfwu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2prqlfivm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhrnmnt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvtadhk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2weuwctzb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgdbntu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcytbtw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxgouke.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2siwxqmgd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdmmjji.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlyuuek.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2aancbkgu.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2uducmppf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxubtli.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uoldaonh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjkigwy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfkbedk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fogikjko.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lcixglqr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sljawhou.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlydgfr.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xxypwopd.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eddqagsy.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2viaqjkhg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzshmerc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mofwvotn.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvddwmae.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpyhcoq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyiemmj.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2imqscypa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mdeblbed.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hauyxgcj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmgpdtz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rztdxswq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quepzvfl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldngryqs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mngnreyo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzqlbqb.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2outldgty.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsnzjym.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dlopcunl.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2oagkcrsw.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2chyluryd.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccthpuwg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwvjrlf.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpovszbx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgrkcxy.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jcieldjr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkhstzr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydncqcxi.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqqgmdp.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eixsvlht.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2diejlcbg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yveqmhtb.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wghyimuh.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpauomf.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwykjxu.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tozfkrvy.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znfjxdzr.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvibqob.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwzpmjq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnrkrao.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhnxlnk.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyaeygw.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tihsgpye.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2evvgtdwl.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ladybcya.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usmpibop.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfascjir.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfblroq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbxpvki.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2pydzkmen.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dmaaugto.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2kgamwdqj.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dqosjgjq.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbegadxa.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfgnoid.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vpogwqlb.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jryhifyc.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyevwoq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jneqgatl.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2upskvamh.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnvfidg.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2troeillv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfbdkyi.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjznmgod.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqedzrd.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gozsvzuu.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pegtaebd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dyowypba.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yeykmwxr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrscwlh.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyhzpps.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2enxhsmlg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnznycnz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2dpteqpit.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sifpywsq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2afmvinxt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmslvoe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pceypwve.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfmyjfp.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2idslplwe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffercusg.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2icscokvx.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2mojxtibu.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwglury.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrqslkb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2brdrftfr.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ainteumr.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqkalqz.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2edzhkcah.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wszikowk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqehfdt.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrhlihz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xanlwspe.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtttffe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcigzdd.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcgqkhe.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfbwkwn.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hicurxsv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfmgerf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sywccsdf.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgywfcfz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hotfchrf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrxsddd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuidpqw.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jmabxebf.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2enyqpdek.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yferyrho.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2frvstafl.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2smczlgtw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mylijifd.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrtmadq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgbhcar.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2msimtdoh.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hczmwtme.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2nshnwebl.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2dafyyzpf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2blrpjqac.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2rysvdvpy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2vewwnepc.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuqtvuy.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcnecht.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wztfwncc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2hnudgqyh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqteixf.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2msmfpmjx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpqxfme.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgolfyn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2swgcemug.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwfouzc.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvwegpz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2drztmojo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnauqfa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cehypguo.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oklgnzfj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2nocnvptm.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtqykcd.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbbdcss.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxangvfh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhcxryo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2urdpqekz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyceyuc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2doolvlpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2auloxjfc.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ubijaazf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpoxxpb.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2yxndfalr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufchohbv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtsaiqb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrjgysr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxlnjzn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yadgzexs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbrqpfx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2llxcdrmj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2roqgaopw.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvpeoqf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzqfasm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2afsszckj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tijlfzmt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxutgkd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sphyitrf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvdmqnz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2supwhrdt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vagfllzv.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2homimirc.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2yswvtsky.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcqttai.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhdldco.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpwevki.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yekxfpau.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuxctvv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxlbocm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdyiitf.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbcbesh.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2impryayn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2abhnloyg.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkuwqvz.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbjodnh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2holbagcg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2foywqfdt.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fgopgymb.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tubmmbrw.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2amnxqcap.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2inokqmbr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gyklhxzf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlcnjej.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjetbxy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2moehgnvi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2inywagud.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2gyypoywz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lexysysw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2vatiuesn.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiqykdv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdnqrej.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfezflp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2gxaglyna.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjpqnjb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqesmgoy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tenuvnca.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wptggsww.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2irllnukc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2yceaeujo.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xssjobua.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxfuybe.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhixiket.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2budlkygv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqnjgfh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2qrecrpbz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2eknhuclw.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2junmyhkg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2izdbrggu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpwzilp.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2rldjbcal.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2frqcigjo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2qehowdec.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxqhlfj.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtndkug.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2yliciokg.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2umrqlonm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2ycucbslc.html


<!-- 参考信息 -->