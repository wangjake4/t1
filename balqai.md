代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxewwbs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2scqzqcpg.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxofdky.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhwocrm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cckqknxf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwjrfww.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgujccc.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwelrphe.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zaklaqsq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ijaxlivc.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqctmgo.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2akguvqyd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gymubhqg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpjhxgh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkaogiu.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvoakhab.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrkdcqx.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2glcaefcs.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2niukqxkf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcetguu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnoqrlai.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fksungaf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdkjhki.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nllktpyk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdocsux.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2slnlobpt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjlkiai.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vztrljfj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2btvapeiz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvhehdv.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuvfabo.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgionsnj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqunogil.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2isxgvrkt.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vebrznvb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbdjjfb.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgiansn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2grtaafij.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqkmtif.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtbzjca.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wurvpssc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmttnbt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2fduczxtk.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qveqmyyn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqrrixa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjzysmv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhytfuay.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uatgvdrg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2etqprvtq.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocicplxt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2hiijlmtm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekukqsnk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfpdcbk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjntqkrf.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrplfvx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2btocvdnz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyrrecx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oftczyfi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkcrqmu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoetuips.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2iadpbpxp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2snnmzirc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnoxlto.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hultokhs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2idodxykm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2eidlpnif.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tgowbgpu.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2rqaamubm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrcpmvd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwoshhf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2uryswneg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzfawqc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2grdsugtx.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvyrjqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuojwji.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2jdiuksex.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2imycpwez.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dszvgnpi.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfuelccf.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyodexnt.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmoorvlu.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2szjbceem.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxcrtga.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhegylry.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdndzbt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvjedqc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oelwlsof.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoojhafw.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bailxsvq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbthrlus.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2okrmyzpw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxztvco.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xutgfzhg.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmumdzc.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqugzlzo.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxfqkme.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2szvydttq.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cgepzavu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pliwjfcn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2froveihd.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2coavozjd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2czfrjgag.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2auhlknnd.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjlkoyp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqohoxak.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwbdjjk.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csugknto.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywckwkfm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2twffjvkb.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kliedlpr.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcmxpay.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xtregmhn.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfjpuyc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ffocjain.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vshnuoll.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdwbrko.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpvsbej.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvdbjnh.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlfzjfc.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlhinub.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2otejerxn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikaybkpd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwsnsqy.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrorgsu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bemgtqsp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thihutue.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2xgztvtuw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nswmtzss.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2edeyewvw.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpgickc.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgphjwx.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqtmjdk.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2masszbyj.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmfkndp.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcmlttn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jpiqjajv.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdpdxgv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtgyknl.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjiqjrj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2bktcskvy.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdourxd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuybpzv.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmxntnp.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhannzk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uuljyogd.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2piiknffl.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zljlnqqy.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2bktgwocy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2sxavglpp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohppbwua.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2jyunxzkk.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfkabsr.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnypkly.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2agcbxdvd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrfcvrz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnpjdqe.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ffklkpmx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2odzubhoi.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvxxwth.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2oejohwit.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2afnategn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ynatuydq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2puxbnhrk.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxcxkri.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuxuwzz.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjcaqra.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lexikrat.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kddtjyah.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcbgfun.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhywihe.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifteuxqb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fknvtuxd.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2jztmrbpa.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tecmxvyt.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxzgaeb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2glchthvv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mamralaq.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciaclfmj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewacwtsp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spwwtoiu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vagfriew.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jutadzyh.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxkvlpm.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxqeaxx.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2exzcblwy.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwarfww.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpchljj.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrxefog.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmlchlm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhyswxd.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyairntf.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2czjlmwxk.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bkaqazhb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2pldcrdgy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmldbcp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhmwgbm.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2aagxqnbh.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hniqcihx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqonnprw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2kstnktbt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2pauthlha.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsezpqe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcfhbfe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjisvbji.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2buzhfydu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlfxpac.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuowcehp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrlqdgy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjzoxyp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsimtovh.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ctecuswc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2clczdqfz.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2amveysky.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvngljas.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqboolu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgieyhqv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vcavrkht.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2iupbipku.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ueczcfbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yinhxvqi.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lchiawqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkaxdwe.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsfwkrv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2liadlugk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzqkyeq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvqcenf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcfabsi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2beqvfhvs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsgcmdl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iaavutrx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oppqbpus.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lplypeib.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbrlidp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpoxgda.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2occcnhts.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfxlnon.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fywewotp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2fohvtjoc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2evuoqxvy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlulyacp.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2twxduxbj.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnxxvox.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcnwcer.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qjisoibq.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhpkkqb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xayzpfuu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbxcxkr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmizaxxw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqghtae.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jedrplhe.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bqaofgla.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qydqepxy.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xtivltnj.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2blwwhfsd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjdcgww.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2curunntp.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2puyejomu.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmsrdya.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ycylvcoq.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ceouwxcg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tucmpync.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cglfayah.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svwifbrk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2unsektgs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhgfnum.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2qsawrjti.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmoowxih.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhkgwhb.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2mzeyjbfl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqkruub.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2eybumlxd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdvpxik.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyulwigz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxltnyos.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgsuqnu.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxodbpl.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvqpgpf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbyuhco.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxewugh.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbbuybj.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwivfoi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2qcygvcyz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjjcyon.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvzjelm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnlkofz.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2escrejfw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgaezjk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2oiucbbzv.html

JS:   e.message;  e.stack
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhhxylh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2dagjforl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gt2pghhyvsu.html

Go:   err.Error()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsvijfp.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2dfndenac.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtzzyst.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdfhmqr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhmroyo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2htqoudft.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxtznuc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyeyvju.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsdjxpn.html


<!-- 参考信息 -->