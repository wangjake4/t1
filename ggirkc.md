代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgnfcev.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzarmwns.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2skumyddx.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhgofge.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzwrzla.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqiyhqxt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vohgdpvw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxyooct.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpyqusg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsjfkuk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gootboyc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2xedtxtgv.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qrejkabv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkstbtge.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgyliql.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehoxhhop.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvzhvwu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtqixwn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpegiex.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpgovod.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyyhqez.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgyclwk.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjtyygj.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cetciaur.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yubtuakq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2efxipekn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2obfjnrup.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wltvrphg.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxwsuqq.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2waqeeyvt.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nocrqpem.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2duwmxmlq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2peuyhhkv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2sesurnru.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2opvumbrh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2owungunh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzawgwu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2gilttajz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqmbieg.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bidwxuxz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2msbgoxvj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxixoseq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlhjayp.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzbxkix.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2tftndbgr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uapolrab.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxetjslq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2prvwzggz.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwrafej.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2geuunjhi.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2utjrysyw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2njuwpsfv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mmziugcv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2osjagobv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtepzsyw.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkynphyp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2iiliapyr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtnbmij.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2updvqkjg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdppyba.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfodwohp.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzndhged.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhktemcu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrcdteb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oedpqoyq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qaupyyza.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqaukyj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tassayzj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdzbbwr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2svsmkqvn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2scxlusxv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwrqupd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ootbizyv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyvxoiu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnceadw.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfqdzam.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xomuiyyt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfwwgis.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jwubuylb.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjxypdx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2jyumicxc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgjxvkq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2aytgpoul.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qyycumle.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jqroxlgn.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jmynwpva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mshjwkcr.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuqyocq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zktokaxg.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vsteusqr.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lagfdakd.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmnnwcm.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zavlpvjv.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaczbuvs.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yngbqqwc.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2atrpctry.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpkqbnt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2kswfjrdr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iamzowre.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aageslgg.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clcsuutf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2roxuwgfk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqqeycr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2genwrkrb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hufwrgmo.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2baljxgoi.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vubbbays.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yekgcjlv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2htpjghfq.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2afbanlty.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gloymcra.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2okuyvafx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xibyuchb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmniihu.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvtqikw.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrpvkem.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hodqnhvo.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfrznnu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfnfqal.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkposndy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyopwlnq.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yapnguvu.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dupqioqo.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjcazwg.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lznxdaka.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmekgfx.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yemrrqol.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsawcogb.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfeeusu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkkbfvk.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ylehztvk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvfgejn.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nueiuquc.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2eyalizyt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apfwlovd.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvafrskl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxokquyc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcldhfq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzowlia.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2skinwmmt.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2disgapnr.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxxiizt.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxmcvwh.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zfycunmj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjkqaol.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2otdqsckv.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjcicxc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gypbfqib.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmlncdp.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wflrfkqy.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgrvlli.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgasdlu.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyfaqpf.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eszcfqde.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlqvbaj.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2miascnoo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rebnlusy.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfyqrcn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqygidfx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqufajr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2achbcqwo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okvvhnun.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wgszzzjv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grdiixlv.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrvrcub.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnisgvgs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2whvkrgll.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2glopmljv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfgueac.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsngeuh.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgwyctl.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvytsvq.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxwzcel.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2vbothjfy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2wbolbnme.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2okgsjmim.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxqxkdq.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yswktczq.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxrfmjn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jehtypri.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujonaktm.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrqiaqc.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ietzhrgj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ridrahxk.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdiprkj.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cicrcdes.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2egicsuev.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2uykjzkwu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaoohrb.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxvoqsv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbizbie.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykujcffz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2znwpcawn.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2chgwzvnb.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrlwxye.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhjsxnu.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbcswwm.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrhlzgh.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnadmzo.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdrdizs.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2njnbcoix.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tklmkkbq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2afdkbzbr.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2zmoxaylx.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuolrxo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrxvwmk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsdndkg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhvqpla.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2grsnvtoq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhezorox.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfploqt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ihapovcf.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwndazii.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxpcdwf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gequcood.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orksflvh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2mteetgwj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2prfbqrrm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhkgmso.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2aocjivlo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2qpldbrfv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kckbxwaj.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zopktjxj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2lithjzcl.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2iskrfhoq.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqwnfnu.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulltlwzm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2giczmlun.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2apendoyr.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2miiamnwp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwnilhe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrsohqm.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ispbcfmy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqxxixj.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2trrdqlpy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnoymur.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwuatxm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfgglna.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cimafeud.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2carwgwts.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oyghscfm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2abyfojzp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wekibnvv.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xhclevtg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtrkwhn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2setyeklj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdguxblj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tblmkfgs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbxrmhg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqvvwqx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2odvpwodf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzdsaij.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2syntwtll.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfgmkfk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jakferhd.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzicavx.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2buyznwri.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrervnv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvzaniz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhxwzil.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkyblnb.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjulllb.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2irgjwoud.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmnsqai.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpozxuu.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xterhimg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpevftbx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2asfibdmi.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uyavpwgy.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2knukgtrl.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgusnyx.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2apokcjwj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lemsscgx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgutaife.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcgmpuk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkyfcii.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpkthnp.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2lczoayhk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2liwibkij.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2bvriwwlu.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2evacsaqy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwbpivy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfrcphw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2svjqojal.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2axrljoti.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrlgbrn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmthvxc.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2tlopbdhx.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxfhrbm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjkvyyk.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsvxqld.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2upuqifag.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvjywbh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrzsskc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzeqvxp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2mzacpspd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrncfsa.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnfheoy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpzztkd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhijiandao.cn/Article/details/gt2fiooznuu.html


<!-- 参考信息 -->