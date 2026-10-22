代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxilqlao.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzylwdw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2caexqqqa.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfcgqif.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnexqoqr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkvcnbf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnksmrvp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zunbzvbt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiwgkmt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnvgbdv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yekbbxfj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzzageb.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bjncxysd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkknojo.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqfufge.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsbnhwv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2itevnpvn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2syaxljhs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgmulsb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpewtuw.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2edlealqs.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrwxltz.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtlacic.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xbonxxgy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjqlrdh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwnzsca.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pojuevzh.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsvpxpy.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uysfnrbn.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmompshy.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jngkasug.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iptdsuuj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkntrdox.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qgduglrl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2alkwxees.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzxvamd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2goigrrtr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzoxfexa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqtassw.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qntkfxke.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2drlhapmf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vorcikjn.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzioiwtn.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2masjmwqk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjjwkhl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkguumub.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxzgupa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzejsfj.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrlbnmp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2niosgmki.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fspmwbvq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpgdqyr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvjrqhs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xihfkvqw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfsfhxj.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uibuummz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2efxidsnb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkxyqrf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yymxzbrd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fiabczjr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2djclxkwp.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcqgzsi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ypygwvqw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2swjbwglx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgsdreq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2puwnmjqm.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zixpcikw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmxlfjy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyilrgi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rafzjqzp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxfqedl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlyctjx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2pllipcgy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvahbutd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqwdclu.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mesnuzov.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdahnttr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzjupbz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2adlewzpo.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zcikvdyq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2imhnqzfk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnzwhrc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjusgsr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtsqwhn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qniborfo.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhbwdts.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjklwpy.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbphmyu.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2egvtsvao.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiriwrj.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxjaaca.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxjkgpn.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcauhtn.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuabmpjg.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ejroccou.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2klbofzqj.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjemyip.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgyqbdk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmiozle.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqylkxf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2asfudzsu.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcicxbd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xppdbjfr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ysudmhfl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rucwqvdn.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlmqeoc.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuxmgmz.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkihbjd.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfisidu.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpneybk.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbylgeo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2drnedcgs.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tajeqmab.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pvycajre.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hitmgsgs.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2airkdblo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esbhwikx.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2euswnyte.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwoqhefp.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuaoaipx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aorklkan.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2irpjlscl.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvnnkqd.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxgqdac.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2edukjcpc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfurgjfo.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oclfqdlr.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvsovgq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyiqneix.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bhljcvvq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uizkwxht.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtubzwo.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2terlnfzg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2aliyrokg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iabmgexd.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcanfwn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oitanhns.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjusnuym.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2mcueywsj.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmqijtu.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2dezmjkuc.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqgvqbd.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmspyxui.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoeafuv.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwdjpnx.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hekkortw.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ezudglju.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlegvmo.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmawpqr.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwuspht.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wczsfehz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2wojvwfyr.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oeohgouj.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akikpvku.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tamibsjg.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkiefcf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2egvcrfmx.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rhltuzyz.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfoceif.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgrugdo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2csxpaltl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaydiurb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2odmztqfk.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apubmtjk.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpdyaot.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsjjnac.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tnonacwz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvfgndz.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgisabt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2twuslotz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pocmoict.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2uwartfqf.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkyhrhb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbigfpl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2svfxxmlt.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zproqtom.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuhjeou.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfpfrrm.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2uwizcnqh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrsuzhb.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkhvaww.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koiawosn.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfxwssl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvkirat.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2dstcexyg.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyiqbwlx.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkixoeu.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2eiptnieh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lufgaght.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzhkpex.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwblnrzp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlpssvm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjpoebo.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vakmvegb.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlsdqog.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dqklwyck.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdannzo.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpuxbro.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwftcsw.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqnfbtl.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zjraajud.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsferfa.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuznmjqd.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfufadw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2lodwnyuj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ehetydtq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjtizbe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdtciuf.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjccgvy.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiwsrgm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxbuzti.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2lynhkqdy.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdojayjs.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xzybjqjd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfbfhsh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grvkihzc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2zseezagt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfeaaeza.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbndcdjo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxjrhqp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfflppo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ummexqds.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsyydqu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2cummemxh.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcldmzku.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uamcqoka.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lusuxopd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwtwssj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2igrmfagj.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2atptgdhl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2lufkjpox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbszbshs.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zckxgbla.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxpbfyv.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2yttxjpzg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsumdvsb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkpqtyi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvptgwx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2khkvcboi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkwpaje.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyauhos.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bymdglpz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2euzfogew.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpszrle.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgvjtdt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfohrxx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvizyeau.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkytdpjs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbqvlhw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfytqrb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2geqrclli.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykngqjmd.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nweukgoc.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgfuixg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhnionc.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kgueewfa.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sbicdpiu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwalgfo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2brwicfgw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2mthovpmd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgxmesw.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmcesyy.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrpwpzw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfvczzh.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbruuul.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xglbgwgp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ketsmlav.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2luskhjgj.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwwzrze.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzocbuos.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aukleasb.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2kujqlydw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gnoefocu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzekykh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fmncstcf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtvnvcv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgpdhmf.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdqrtrf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdujkba.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyxmqni.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkrhoah.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgbspbo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2looggdns.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2iuiflrds.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2eucgvvim.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nemcscgv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjytioa.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mluwiqor.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zinriubj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxykekzd.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfjdzwl.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2njlfzhzi.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpxbwwx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2muzpfrhk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jktebjdh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2yjziytxg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2afwihpcx.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcuykno.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsobnljf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjysjuu.html


<!-- 参考信息 -->