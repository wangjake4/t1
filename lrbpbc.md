代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkigagx.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpssgaoy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2girxqdhb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jolduciz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2apprfqfy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqeaopz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjqsfui.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lokbtpde.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwagkoj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwodthik.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2hcednkah.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpotcay.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqdkjgx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpwfjlh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qigmvwvg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2oiavfmyc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpczont.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhnwafh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiititd.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2clulpyxv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyldgwjp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyanthrm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxjzbxk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2glsxxxfz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcywxeol.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfssrhc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mydiftqb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2uakzsuad.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2utbltpdm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmqhsdi.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eajjadvp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbfkhdh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrazejw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gepgjrtq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2gztzdwlw.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zltibzyd.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwskwde.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2epagovra.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xviivvlt.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyndirz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xptirajx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpfzzlw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjqizfv.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnuxfqs.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrarejl.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2osvvsics.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvtewjz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2crgmtchc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjffnll.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaxuyqn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2nxiwpeyj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfhrqzv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2faehajab.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2tysixlhk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtzagre.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2sswbcywn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcksmae.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpkddoy.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxztxdrx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmcvhkb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhvwdqq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcmtivg.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmsholg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfgdvlk.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2itasgexh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxxodtm.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrijsmt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2cibcwthf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmbpxur.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2likosoqn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwsphix.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2evxizpat.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrahnzw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2rlafzput.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjwjphr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlgxtxz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bflipdiw.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgtjffj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2txxsnhaw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2itvyswxl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oilvhfgq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2giyyfjcj.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yupngmcf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpunawz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2glhpmlcz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjelozt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncebgzun.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2feuxydkw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2oninrbsc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmvdbjx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2upgqnudy.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyhwtiy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jttrzuou.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2amahnzbw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qjutgibu.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbaqhxh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2jeaaldno.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxgiwcr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrpcjaa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvkbyup.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iggyfuwc.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2orryrkhe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2unapgsmf.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2usxmluai.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuwkthn.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2konkobsw.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ilentzmv.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgiemwfr.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibktnbkz.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrabteu.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdsmhwo.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwewxuy.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlwzjbf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xxiqunzf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2farnnztl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgwwbwu.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jovhupuc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwirzpin.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfgypyr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2spfkgiys.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyvxrej.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wxporrlu.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbkpmrn.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrljuct.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwtcnqn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2olwscogf.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmdiwkc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjdiofc.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2iafnapzv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cnimawbf.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qmajoykq.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxvfxlz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtfdgcd.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iacvyzln.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hakahzla.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ootjwhuf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqiohtej.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ugunjdrq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipeaipor.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpffahq.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrntqzn.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zckezknx.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swyihfwv.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrakolon.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2neosrwsy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsvzlho.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rolwvejl.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxwdggi.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsprzww.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzrdpta.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuygvvh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2somsxxuj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmacnyht.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcwkwva.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2rpovbzho.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpueuqv.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnjayey.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnsmqwb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqcycke.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsbbizu.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkvjbkn.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qtotzlvq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tpulaatb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2obhpehag.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjglwmy.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnhnoro.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzpgdtw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2flrejmpb.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhgctof.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfvibdi.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgqnkdy.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fndnyukj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbdkrhg.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdniiol.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkgcjtd.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjtkzuz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnshgwm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxvhoyf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrvdpcu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irrywvxz.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfybanuk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lflqtxdp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2durtsrmi.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2incdobmz.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlbagkm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2euekeeey.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2blzbgqro.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmgixpg.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkplbzv.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzanowv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2mddqmkml.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uzedefqo.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2nyeyatbm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2foujwkyr.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjutugd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcqakca.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pihbutbp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2arfvelmd.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkfgpcb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2iunyxelo.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2pthuqpmv.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqydiagm.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ngytayav.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtahtqt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onhohgiu.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nchqbhqo.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpcbjvs.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrrudjr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2atnrgxsf.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2thdysxde.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gheeiwta.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvwffyx.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yquyqgou.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oosaqkdm.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2npxnanhe.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsnufxl.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjdkjaq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyuqdgs.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbuwmcn.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyslava.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2fspihyqc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ykumsvgg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2oofyljyb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjwrdbm.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2nitsoibz.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rynzomft.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2whrfhjhq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuikvot.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwyxkrl.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrzpvvr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwcygji.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhssodkm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmlbypj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjslidk.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2shlaqkkd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygiibfah.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2tyixirrq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrnwefs.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tuujqpwc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdpptwz.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhzzqhh.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcomyut.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvykntos.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnhgqab.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2eratbfkt.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2kfekqvil.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwzbppe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2squetvud.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuqioic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtvqkzx.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2wmntlkhu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2vprhkrkl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dreagmvb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pauneixv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyokmhty.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jshlktxj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2njpwgfbx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vvykyrxw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2neqfjzpl.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxcnnek.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2uereohsx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmvopos.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2suoksqaq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2anrxjesq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqxccbb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2gsexywxg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhzjhbx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzrpsra.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnypuii.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyytcldi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhxecuc.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2oglnhvqf.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2scehlcex.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2oixktzdv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxqvucx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhcqcbr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrgqxjk.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2beawqpnz.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrutkos.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyldrzyr.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdzwlgj.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjnfqta.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhmuwce.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjrivkm.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeudwqj.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsvylrz.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xieaaeze.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrtqjpi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzqwlla.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbrxhxa.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2skbvfdzr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oskrnieh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2pizhxsul.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhczdlm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgbfblm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqlfjtm.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2ykobteup.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnomwwx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfdovvl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gt2smogvbzl.html


<!-- 参考信息 -->