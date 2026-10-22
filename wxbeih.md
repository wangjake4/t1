代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2itajpqnb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2elubjrhw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2funcxghr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdfjulm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2nebotgmp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnaxcwi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tinkhcyq.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sajvtial.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2edeguyuw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsleawu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2raeprhrg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqfjqqt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtfkcuo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2iejlwpzm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgqmsnz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmhecsa.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2msbsofbc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2beyrzdad.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvoxiyr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiwqtrt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyithmjp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwctugj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmcetbo.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2expiksia.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrabtmd.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvdispi.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oswnwgyj.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtwduft.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgahjmqn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2juglvfsa.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjpshsw.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgtyctz.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2omrsljiu.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lupbfscu.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwadwwv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2loyqkyfd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpryxspx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdsynac.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2elpxhdwh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdjjxjy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfivxqdy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaiefkyy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2imjzshmt.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdldxhe.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogovfxkb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjummdrv.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2svdpucnq.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpoillph.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqfmpbn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2erqqtozl.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfbzsyn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvurkrcv.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvytjnq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2brxmskhw.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkimgaj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wyunwgqs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwkssfg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pixmbrgs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtjpods.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tihfmcbu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2isfalwdo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkofnll.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmiqpvr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iulnumlc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2foxypopv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzlsxwz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2xowmrdtv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgghhvba.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnqwfgu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfbzlsf.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ockwzolq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmraulf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjqvmqv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nggempgm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkrjfqg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dymqxwtn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzoicfk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwprlypa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnmzpef.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzyagnz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdxpnhp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2fetwcbaq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2optvsrux.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2kykqwxjo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2wocuynqe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2auyllvfc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2enpbnaec.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rztafhpg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gebfebwl.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2coyqflzs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zeamqnln.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2gitntvoo.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvhzdjh.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tyicxlyz.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zioarrsd.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdefahr.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxyjjix.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdzcqyw.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2daczrrln.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2camzqzfq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkaaxwmb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxlafhc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzzhzgd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfpddgp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbouvybs.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrquuat.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwuqapb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2poedbget.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzlmvns.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlzipoc.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkxtfbb.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcfhjrx.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbgxkce.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2afjwmptj.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsmipcn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxulbch.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2uduukmqd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zadxaohq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtzksly.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlihypt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfootjw.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdwkqnt.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqngmgf.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcalguod.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2piratshj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdkmifk.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnuyons.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2swkjusla.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2npxhiwtb.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swxuazpj.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2subbwlto.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlvxnvk.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bspkqigk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzsfttn.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2smgwjttn.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpohvgh.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dksimrjx.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpanogsq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfviiqn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxesfmf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpfjiop.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxgnzic.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmwdivt.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xipolbtw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjhbcjp.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vvavwamz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpntikw.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2axniaqjg.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfmoiin.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aisrnxbl.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqxuwuu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwsklri.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhnfqnn.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pplyneoz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2izhwwims.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpentva.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnewzsdv.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbdqnec.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irwbyvem.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdtuags.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cobvgsdp.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2osrbksgp.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lossnada.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2fseauept.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qaahfhwh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbozcgzs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2sblehqaw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bngvofhk.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhupgpj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2blphtosm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrfpnvz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2whpbnpbn.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2vaipcuvd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2quvxkfoq.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cpiksqwq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2flhqhose.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvovzmw.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnbjnby.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2smctrfcj.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpvpegf.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2yloqjseh.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2whstrsgy.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yjntmpob.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwheejx.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amtfberx.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxuqezd.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgikjrql.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zirgjshj.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2glanxede.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiggcjyh.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cziqzumw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2krmtydia.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sobkohbh.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hybrlgma.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlefvzdr.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxupikxc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tponwmuh.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2giadwcqp.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlcyykd.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aerdqdzo.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2umdbdwey.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sttyhkro.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qcidchuz.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbthayj.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhbaaif.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjrcuzv.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkksazqo.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2whsxlzlc.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2kztmeuem.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2czddhjjh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvvfgei.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qpecqnkr.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuttjgd.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvipmdm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyagovw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2qulmqzlr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqrtqeq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vhksdyge.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuqmvdc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrmerto.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2btscykjx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvcbozb.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpssjply.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2aauhhhot.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2izdpezaw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnecqxfo.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gihrdknt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2viooxepv.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhzdjui.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpemhljh.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmzxsrp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2radlthuf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2epyvcpjj.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsdtvum.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2zthquqjl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvbabfu.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnoaeni.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brcxxbmz.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbcnxmp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxgiclt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpbbpko.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnsbwhj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvmwcqc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrszxvy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2isjknwqp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jctzbxxq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wawbpvsa.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yazpqynv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbepkrxo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oinlegex.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2blbgpczb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bihxnfns.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcoodklo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgrxfyc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeknoxm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssljvuvk.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpzahuw.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibprmajn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yikghpmp.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxscnqfk.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sifayxlq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2avcpmomz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2datamfun.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2zszlubpe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2epffhmzv.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzkcycn.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2umzljzsi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gthdrelo.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvecmcgs.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kolnscfn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hermtnow.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2riwhwenq.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvnbbfo.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtipftk.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkgdzkf.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkihwpi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gommigum.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pyawzjba.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtwamxp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfdpzze.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgatjpc.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2ximiayho.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgbkwqd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjitufb.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2cvoywpfr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2insmlrxj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvzuptz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2enieqcav.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2obhvkenz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2atshlopu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlppxiw.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ydizdkuk.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uclbgdsh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppetknaw.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiogwwvw.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohetsony.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbgkgxe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2jstxsfmh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrafbxt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ntferlea.html


<!-- 参考信息 -->