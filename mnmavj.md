代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kugaruua.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2bddtluxl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmnyize.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfivvsfv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2agdwhdhv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2spgtkkfl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2utnfkgey.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wpipqqwo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjpckof.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtepdeo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2imoswvrc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2atexvujz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2rymthxmx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxounpy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfvkncu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkbpqlk.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2obzrbqbc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgwfnll.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gbadoftq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgsrnsu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkybulqx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpqdbch.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqobxez.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2notoybss.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipoxgiil.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhdtxlg.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnrnsea.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqxuohk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzzrpyg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgcnxlv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbanmumo.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxylbqb.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfanomlv.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqgwfna.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtzzdab.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2crcojhtc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtbgigj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2stvktvxy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpotnzd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xlleafke.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcewxpy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2evejxqzt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2jeaopkbo.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsolvny.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qygyccip.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clvvmvtm.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqdazdv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbfuisx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2esnpmrnr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwvfjgz.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2egbldenu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaniqmm.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxsvkhe.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwycatsg.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsxlsph.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2aiflghlk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2oeeprriw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkagibh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrgywmd.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnszrxck.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrzkkbp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiydtqh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2femmpnax.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrbdvuh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zempjepd.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkgbcjq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbsywqo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgoajykr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gusjrwft.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvrvanu.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqlumza.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjvypyb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pisjsybb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2plwiqqzu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekatscme.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ainbxefo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2iigtamdf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdorirw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdipmylm.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bewizrwf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqggxtsu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2abvsnsnu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqdlcwf.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbajpth.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2usrpimog.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ootaakbf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wglikssv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rsypovwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mabqlsue.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzrlprr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2omjmacfz.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xzapmpfm.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdvhszy.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbhjapb.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwnexxt.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxerhrom.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trosalsk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2zitgoaud.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmdvcnt.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kumsjzwo.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2raukjwjx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqeekqy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aauhwugq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nngpvkmf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnatdrd.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2febugsyy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uslekgfq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjueayy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wklrlmmh.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eaneybza.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaiduwp.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2euckzwqk.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uohaydsd.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmhrokh.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2buiufdea.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ftebfvmf.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkflfed.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qihwthit.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlepuux.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gdanucqj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfcxjyt.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sebharsr.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfpmnjd.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xffhjsej.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2knoamvpj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuvzscr.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2epcitraj.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdecfhu.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tnatbzwy.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oalzzirb.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwghnpp.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyisvaa.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgefcsf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2avpndeeo.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2udmlutbh.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmbaujy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vftmatow.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2jltwbedg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toakddsk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbniymlf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjtfqbe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qplwlyjv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2hlckacdl.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxzblfm.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfcxwnq.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsybujf.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2atdnostm.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbeiflf.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eiaaubkm.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgnlmsi.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzhroal.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvpyibt.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2oilokwbr.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2soisytqt.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2derficwv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dspxlebk.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbzgdus.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhughlni.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kowasxup.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdxcgjl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcsbvby.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sccxfnpd.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdyjbzz.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2xbankfpq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2iiugktso.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cayujtvi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuinoiv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjetqwt.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxdhgxh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihotufif.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnxdgaa.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iotszozr.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlnegpk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2pplfznnn.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uiocdsvw.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wyynuxta.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2iihwxbjw.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlkpqav.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgswjjr.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2aaggvtal.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjnmktw.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bffoommt.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdtkygw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmgdaun.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqacpmks.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edupcrau.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbwtivc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqoavhm.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ciepgakd.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unzdgyis.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqawqqr.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2tigwfjdd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgtkveb.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyinpvvb.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tephtjsp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhrdwrg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhxacut.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmwcbiq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpejqzl.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2npclirty.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlycatmf.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhrpahb.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrbnhnk.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsdodhp.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxcynxl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2eotnhkhn.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvjtkxq.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2yoemkjxs.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvntjgf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcsifja.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2sjblueto.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2lfccxljq.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqfzmmg.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbeizhtc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2thyijojz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2djwflcqh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwbszgx.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oflkuifl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2omntavhc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpknylcr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ximssfnb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrjuqsk.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2uivhehja.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2oliaoutd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ytukorjw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxocdcx.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2csrsnowi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2jnekewdn.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzjtdag.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yblgzzlb.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyjlzdl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcutshon.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbudrah.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2hxupiilc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcheyyz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vryklctd.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzbgkmi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oiolszms.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2kifuwuhm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxaetbqc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvaqsvu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcogfnnw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzzbqis.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziymbpge.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbeupsz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrviauk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvixslk.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kczpbdkn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzjzhco.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eemafbsd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2smsfwvwe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdavkisp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlscgxyb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2frwgtifd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxxvzte.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tngxhjly.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2edvvkptu.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2axjolzjx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2eoszaqdu.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyjtrbl.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hocwqzpq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcdspwf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2tplpeqcn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnddkkai.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2exlwqbdr.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyshkri.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkqrnrb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynaxfurp.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzubzia.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrpdfxw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsstcjee.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqtynts.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eqipwxkv.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qslrergn.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtxiwuf.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuczrjc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcmxhzl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkggygik.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awixexah.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgsxmlh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2rchkcbco.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsfdtub.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iznfogds.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhvhbsu.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2xclnmrdy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvacbjt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dbeoznhw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2jofzfeuw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2nojqqsqr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkkldab.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzikiwwu.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2acwlaeyd.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2flgkvpsc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2anphulzj.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyaumzrv.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2epvvblzx.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hegfhecu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2nktwvbjm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2arvngmlm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2vjandrte.html


<!-- 参考信息 -->