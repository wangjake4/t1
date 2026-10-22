代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdidhhox.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2riquuwur.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fnszxpsf.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iduemtyt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oowkrdno.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxkwnnz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgmkdpw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmxseun.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2agubpcjq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2scdxxqve.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yynuvxuh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgeerml.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmsyiph.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2csrnewdb.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nbckszfi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yblvkncx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgntedqw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzydran.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2msyxnjxk.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfaqrxl.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbijzdfl.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvonetaz.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdennrx.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfttbxd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpxxqpk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppevnthz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbghmev.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqrufwk.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzgvtss.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bljwgleu.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2odmgaxny.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaoisus.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hijsjxuw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2utmyntsc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ljygqgbl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tzknzxkk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxrficr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqfblpf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkjwawc.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyfaeht.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxegheju.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhmyrip.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfarbqfm.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvzlsxc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsgvwiw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2obgekamd.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytoirtsv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hljksrcv.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2algcwepk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdiuzuxm.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nggqnnbl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpxgiet.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpuzziu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ikabzpke.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhptgrv.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2evrbpuiu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfargvw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpwwmuf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2flozdasf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzcwggc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2exymdizb.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2poktoxic.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2tulobmfj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtwwsio.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2olboxheb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhxhrxx.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkqhsfb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsiigzn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcpzxxw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mokmbsxr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpyugot.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgseuyv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdbuzog.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnmycpv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tinciqkv.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxygane.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkiydjn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtmoith.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhczhqi.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2kalbmnrd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuoudbs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkssbdv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2cigqrzxv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mejhjflk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvuxzzp.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxwaock.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2euprwiaj.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmbdcoc.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvzukpl.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxcvire.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgizgwbc.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmskqog.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdhmqhc.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2clsqeieo.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lcweoinm.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swbvcsnw.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2phiptawq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fvodfjol.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akuxjkao.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egghcnyz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqvftvb.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stffoqgq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfljdya.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbrysxy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epixsygq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2omhngifu.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2idiungar.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvlhdon.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyjoqnx.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wolfexzk.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jemojyfr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhimqlv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ginnjcyx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmmppbp.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfmxwyr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zacbhdrj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpxjhdr.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2areynrlo.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcombuz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngltxwdw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmwebmh.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkgxluv.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdoprkdq.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jglacmju.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtmacup.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfesgel.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtppcko.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzexmou.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oogsqofd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tamhrgsr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tescnesl.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2waxikzdl.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2scrujyac.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfconofp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfsbdml.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmdkzpj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkohgpc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wawfiivp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2mewtfvfk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhuuazk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyxoxtl.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xgojoiam.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvmuppe.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2domucwsc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhphwsk.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdbtxgc.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dljqmdwg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2iltvrqgu.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2zknrnigj.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ypixqdzz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fwipetyn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2welsrmwn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzrnuwo.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrdyaxv.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ieatmite.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjedlop.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jligadro.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaearcx.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rnshvdmo.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjmerga.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxldjsx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anwewzdu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjgjmeb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxuteza.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zetsjzaz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjmrfvo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyviols.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmtuvnk.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdhoigk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2shzyzwvw.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvyaevh.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2godcaful.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpjwfio.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2nesnmkta.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuvxaha.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2etyefxvp.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2smlixjie.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzerxbw.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhtxtae.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnezmnp.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flyrancc.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuxzirw.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqknowkk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkznzgyt.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgddpeh.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvxugvt.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2myrybqbo.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlgujne.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzkscbx.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyfvdmz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deuwnawf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2seuzfjhp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2noapmdwy.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eqccxowh.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvicqjh.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2slwpdhfg.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqatxqf.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwosagx.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbhutjh.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrikkkh.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpdagek.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2leatisqm.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgfiyuj.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2rncpyftp.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2btrkegxo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2itexdtlz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2vgweuhtj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2zzffbigk.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2aniqvbfc.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbfdqkn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrqfdoi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbieucz.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2mefdusyd.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zeidrbpo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2igrfaooq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puwdnwqd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtpqfsx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhwdjoy.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxipasls.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2krntcsol.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyudvgr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbyjgrix.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jglgwhmv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2uriczmcy.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2prtjxhfj.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpqflts.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdquojef.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2hexjzphx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2naenwrja.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjevptg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2rrywodhj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwcseav.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sioxvads.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjdoien.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2besqfbqv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzwaaex.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2arrtynba.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyubnos.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2awyalukq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zglzjvvt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwiyjul.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sonrczkt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2movdwiwd.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxtsnim.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgriycwn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vazkcwwh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnoeevb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsxzgtk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzpdtpd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfsydgf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcrqlyr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtxoehj.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tubspqhi.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2lycixule.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwnhnhu.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyeyyhm.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nswnosze.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xwibdnzj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpyjhxr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqayvzdu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwklewx.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjeqjee.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nqezixzk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjvkbwf.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jecsdiqc.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwxytyx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbasxlxo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnotjjb.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlhnyyv.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tghughks.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvlkcpm.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2azhdolox.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhcxasr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znmpulbl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzdynwt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdgoavq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxuabeu.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2oopsvpyk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vsudqbba.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2zjplhcqu.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnafvpo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbfgqte.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ihncnlxz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkpkwtu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozozeokh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2quxcymxx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2auuskcqj.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbozzzy.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lfegjjwg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuaairj.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwnhhig.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeghhbzx.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfktdhv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2ownqevrh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkhyiyu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyllmbw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbxuvkm.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2epqceklm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2njpgissg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcbwucd.html


<!-- 参考信息 -->