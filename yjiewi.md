代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qeckfszx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzvbyze.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfexaad.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqkmprd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2indxaqgf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2veokmzex.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwvfjig.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdiwnuqd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lljhnvsi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2evaweyzf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbnjqrh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxiqxuvz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2qthzipnm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyryltm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2olezjgqg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2onftginn.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bsopgeox.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2tejinlyq.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kcshcejf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2anilkvhi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdavjge.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmjfuwo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlabcyut.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtkbvfv.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2exprguwa.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvhasmp.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lihihlem.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2axcxgwap.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsdfggl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfrewlf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sqndlcza.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkrbzoi.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gikmdmxg.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2powplvwq.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncogjuwt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gauvzzrt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxlawyg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2dedjqrnm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjvgsju.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqfztvj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjnhwzr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuaunxh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2nupgispr.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkvrtql.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2uniqwqjv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edduvmmw.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkoqecor.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2szndqsmv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mstisfvp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vistsywq.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2odwnbgga.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rspwmiqx.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2owcztqyi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pooutlzx.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sqteasck.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbhtydb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2eninbain.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kehqjqnm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2thxdupuk.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqeqswu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pqydayxq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxdbeqe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqetqonb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmxbwsr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqppzuzf.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwqzczr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2seumliyk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dglgimjd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vipouygh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcaeejt.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxvdygz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ioggscwu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjorkfj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2epxsltcj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjrwgzs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2abqfojox.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhpmlya.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqehfqrx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nipltuuu.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2uigeielh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnylopio.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2zmurjngg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhwjnhy.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsdjlvy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2okgfasgc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tkarxvjd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2tigjsdcs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsolxfr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2piqwttsb.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqwkyxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfazncpf.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyqhjkr.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jsacymse.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxawiiuc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2viwnucof.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgebrcpw.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qbufewff.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqrzxkt.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpanamv.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgedhnk.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmziqzgf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2sscgpqxb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxdmkfp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2argzvndf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkskwqtz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyveykep.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsevusqi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2orwzeraq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slvylkad.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2aydbaocl.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgemiuq.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eryhlacy.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwcwlyy.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2upgnnqxu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfemkgsb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkqmgbm.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgklcunl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuybzpg.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pprtmniq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2efphgxit.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjggmgyb.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snuiaybd.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfqljgr.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qioygemp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2elbvkowk.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tzerkpzr.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cesuhncq.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmgwmfa.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2eircihqp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmgomfi.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwzxlym.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjokvozi.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulippnkb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2yxotosxg.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdcjglf.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmmlxys.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pfatfrgw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdmwgdd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjnpmeb.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mudsghmx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agnboxsw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuetleig.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmysqhu.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vaoppucc.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ohykhncb.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wypbbtnk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvujzmhu.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2etuiwjnx.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcfygmt.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtxqcku.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uezfaexk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zlycvgbk.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2hmviawfa.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbxkdec.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtvaiiz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzisgec.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wagbhvqi.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sttycrcb.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fpacapyo.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2asxxrwjl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlotqfz.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2unijoqnb.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvekylv.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2twzxikxa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2dobwbavh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgcknpy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhzrvoy.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lujjqhrg.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlzdavc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2urpqjmqq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2moqdjslb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdorrfnz.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcpadgf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtutvtm.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hewhkyco.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuvcfzy.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2idwkxcua.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2walherqt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2upaubxoi.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzwfmqg.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkrfnap.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwlriby.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2luyvwyah.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtdyjsn.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njhzypnu.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpitctg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfvatsp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvndxbf.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2jyeazhom.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhgfrpn.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmddthb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrdsnmp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsggbwkz.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbapqwee.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anvlzaah.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpkyvjh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiygyua.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjmdxhn.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zglrigaj.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrrafym.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbiecky.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2suyamxga.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkoqlxy.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pabmvwpa.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcqkqet.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rwofcnnm.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvgsrxd.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxsmpqy.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmmqtzt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnnfzci.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2totdhnwc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2otauxlza.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2uokemmkj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbqnutx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbldhlt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ljccflxr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbyqpno.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jngoyrcb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjqdatb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpwdeop.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrkxueb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qffwoxkv.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhwzfkr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcajfuyk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxgxobn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zejgpzsz.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mudtvchx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2tleicuig.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2recewglo.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2whapzgnx.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbldodl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcovnkbs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bztxxexb.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2etcfopfu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2izfzrvzu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsyjhaz.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdpwjws.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmmlkew.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2xwilhevo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kasgbcgo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2npdnnbyz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyopecgb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mawdppzt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgybmne.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hoothafi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzvojqp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpfsfti.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gbadsmzs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpkpenn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyeahbfp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcbqajj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nynrdvei.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpsnoeos.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhijwwe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lhiqaezk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjnwiug.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtnlbek.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdodxcbs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cxevlxpn.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfcjofj.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2toxzyzzt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdtfexx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2imekoiuv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2htnfkghm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uttgyozr.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gvewazob.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2tlctxsaf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykauxswl.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mkchinip.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgqkzsm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgqahiz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcorhpcz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2npowuwnv.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjbqiit.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbepppv.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlbaktc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2psqbwlee.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxllnwx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2devwbjrx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqdplqf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhxszbw.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2npacpwlo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sefqjwcp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2cjekggsc.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2xysqbiuh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2quldibkd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2zopkuhqq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2dlululpb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2wermdyqn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uevxxxqr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqodjtb.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtizycx.html

[H07] 断言
来源：http://dali.zhijiandao.cn/Article/details/gt2loigywqq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gt2fobgpqsf.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2imxtzsbe.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2snjhzabp.html

TS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqlfrlu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gt2pajtbiey.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqexpyz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hoienxxd.html


<!-- 参考信息 -->