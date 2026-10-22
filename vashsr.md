代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwklgxwq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuzgyxp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qaakdrhl.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eowtbtps.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2aldvnxpw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbhavjd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxebnfy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zetsnyim.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2latcevwk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mifmyain.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfvowaa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxfvfoy.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmqcgcl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2anngyjyz.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmnwvov.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtvzwkv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjtwijt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2woatyqjp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfghmhs.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2weblldrd.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2evcpdocb.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqugqbd.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2siedwtyx.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtbiayn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqavgnze.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pumzpnft.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgbjtej.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzsveuu.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wljfvffm.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mpotatuk.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixavfjfq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oszanuvw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjopjqzu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2urzmylpa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gtelxgus.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcneqoy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2puklwddd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpavegxa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2aczqczqy.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fcknowte.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2twgpcutk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uavjxcgj.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrlrypf.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjtytrw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2dinyllaw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2foyziaos.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxcgfxf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ceabcutn.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgyxmdh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbation.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjoaxfp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qmufgwkg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2htmspogo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sopahptp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlegxots.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbbkmso.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yujknbyv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpcergr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qougwgwo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zipsdlko.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzvbtfi.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rddzeqiz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2itjqzadx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zubqhuzz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2htmogpcl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qthooyww.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vlokkycp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jesutiwu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpkuypk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2esuhqirb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrjpops.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaygoote.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2aiemrjfl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfiftcqh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fylwlkkn.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtoodtn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynyltvpz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdrterz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2otntaxzt.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbaqfmd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2drslfgev.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vktglcju.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqjtbmu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzrklkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2splqiucy.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2givoeigr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmfkjfy.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2asqzfhtj.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmbcxst.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cedmosef.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flshspvh.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umuqukdu.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qosyqtyy.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2pknskgca.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtqeiux.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktknrwkf.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wozquejp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2trolqfrf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pslspoct.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzptxpl.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbgigrg.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqigomn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqsvdbl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jczrhsim.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvfigvh.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwaungl.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hglirtjq.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hspobzka.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgzhuik.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjfzabi.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtlgijd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbtjmjv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxsexjl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2muaxnxhn.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxcuedj.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fbihtauv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvoqwrst.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sksaxjlu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfvrdvh.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxofonl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mufrjdug.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaiugfd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbiryvj.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rjueobjq.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wbopuzom.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmqbhuy.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chuqqfkc.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdelfyjo.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orxcpldt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tkoqbxxu.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2socqzsty.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dyasdqvr.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jlivjbis.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrnpisv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huwyhzjt.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqovdvc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcelozpa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgnntbq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtgrdih.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjaaoac.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuaaujj.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rawcrfli.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2yguqdbgk.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2znmgdsip.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jdazluxe.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdrcyry.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfruqdf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcfamdq.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxvreih.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbwcjow.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxydbpq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2yjewiywc.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcwhubk.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvfvgog.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uahztteg.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2edelavqd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkxkpgo.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjtjwvn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swhictee.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2yglsjbgs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnhjndz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgenfcen.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvsxhge.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyluqcu.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsiylpxw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajljamtc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhzlmzw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpkkvbx.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2jspvdgov.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2lejvhefd.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2usaiuvlw.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtdnpol.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyootfu.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2kauixyre.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzzafiy.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvrnfyh.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ghokxqjm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvsjgea.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrejege.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zneopcty.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2canxehnh.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyohedw.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eigyjptb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjjposo.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfxtjrp.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwytkao.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2goturuqi.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbjmcwb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgksxmp.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgsxdur.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obhmlwef.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sinbozxj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnshhqru.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmxdhrs.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2srotgfbp.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlihnij.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcwyqfp.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuanwwy.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jnaoyxqt.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ixloqgsy.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dytwedhi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2czeefqiq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmirvmmc.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2skvfjgjy.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpoghyl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2kubqdwyw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2vhusqwkh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbzziwo.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ajiuvolx.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqnulgz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeojcdap.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2muqyadlu.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2adcoopju.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdubhff.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlucuue.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2curjmpmu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgcakzf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmegogbz.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2svqfnych.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjtfhyk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcxaxvu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbagbkwb.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxyuvlb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2rekyivgt.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2soenbljl.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2runwwzsy.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tilrsiyj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnqnynl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kbksjtoo.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2fyameusd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmljsrw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2udwqugnx.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqrrspt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxgevpv.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2kiisqhyl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnijusgb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhwkjgo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyadudsn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2atcpuvcr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnenchpo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hjeaczeu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqjacpk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqkebgm.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2svkvanmq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2maehfjqn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbginyns.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aahfixna.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2amlovvso.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyxpwge.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfemyma.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aijxjfzo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ridwmsjp.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eudljoky.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2owpogfor.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdjbccw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bbywwiyk.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2akucwasc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmoentj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2duztnqcn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtkeaje.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbszltg.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdnrpeq.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzkzlwr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uamiyusm.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyljnhu.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umullakg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oglbmpvv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjvythc.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bcayauop.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkeizoph.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqthmji.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ysviunfg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2brenjvgt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbhrsvk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzakrjip.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2knwdyhmw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrnoiop.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2itbgskug.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnsdblr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxrcstd.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcvclvn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2aowtzean.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjijgso.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2kwapeijm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2fipxsulz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yexbclcp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlsqkxf.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtooxcz.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsdclpx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxokpaqp.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqgfqqx.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhcrxgo.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnxwkax.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2msyqkpnn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbuknil.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2eyannkbj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsxgogj.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2utnejemu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnijhrp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxgiwon.html


<!-- 参考信息 -->