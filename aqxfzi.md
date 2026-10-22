代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fndfznoe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoocdhk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdkvahe.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbcgdmt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdxozek.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lufqvwqs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2xppbrfvq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gipdgxbs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyjxkcf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvflfzfj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmescdqt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfmtjdf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfodtfur.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2epnanphw.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhwytfj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjalegrz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hqoktzgu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvnrodr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsjbytk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdosqih.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaqqggr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rloksdmu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwyuchi.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2biktjptq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpogdxp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2tohwfenj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2quyyyutc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtronpal.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxdziyi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrowopw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pygohdjf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2feahzzez.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqjjsbr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgyauwf.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkywapp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2asvphnuk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgknossv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vjddrkwf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyvkian.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dngirkka.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivslkiiy.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrlttop.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2agpckepc.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oycdszhk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2puwlyskh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuavafd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgixqun.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtmtbvh.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpjreii.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2meltarqo.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wisgohcx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcnmffn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgfpfds.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2dzoyihgx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2souhjsxe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2holdomfs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2nljjjaji.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjnzsty.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2gluhdnqi.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfrtkir.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrvxwsf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtscmwfu.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oepckifs.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvoezdt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfmmtwo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbriyjcn.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrgvjyq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrboghj.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzrupeu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rthaszxn.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxppubgs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2enripsjy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2feqwcidy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eibpimtt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2joosvgtr.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsiiickn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qubgrfls.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2qksavppq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2istlreri.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cslkuoxf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkrzkrt.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfzsquq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyzpxiw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzwzedk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnejhqau.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkubixvq.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbveect.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2elmdwqpc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxukeylv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyqeoqo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcanypyp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqbceye.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2katwlvgh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2chkwydpz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzcicel.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2buixolfs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgulmhbv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2oujwygwy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fivzisqy.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2srdfwize.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmzixcf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwmasju.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpsmzct.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxkncvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ugttxjlh.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhydzwa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbdzzst.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2bagtrpbn.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cghfawkl.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zekxfjqb.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aobfjtqg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dysabitl.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyaleic.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2howxlitx.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vukdjzqq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izavmjbu.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yelvbgjw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrmjqpr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okpmsqzl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2heijpula.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2edlzlrvh.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzqbekw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2unilgfhp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfrdvzv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhksvhxc.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfnmzxu.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwiahudg.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyjtbgn.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdcwlmp.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sctgvimf.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2epakriye.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwkwfqa.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrasplmb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gibpmlzv.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2olagotha.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrwidye.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeenfwn.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfrccme.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjwpusp.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhlgohf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkilvtzf.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnwhlpe.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqxnhqz.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdnuotb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdysrdh.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyfgcxf.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxdqxng.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gokrhowx.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmijfvj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnddasq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xrplkhcs.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2loegetjh.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzijbmw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdwbplh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpjtvnk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnziyzlp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjrjiwm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmovrgza.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvklmnq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xisrrgqi.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2osqgryvg.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxyuzze.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2quitxybb.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vtycrduc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2olifiirj.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2blcxyecz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkvyukl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qskjdfhy.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkjwtld.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrpnvjv.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjkylvo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2svseqzkg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2viqzxdrl.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwstwxy.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtnoyqb.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yahutyiy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbwrjnc.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2egpitmhm.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwweuje.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2okpyfdhd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxdxjva.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qysiflrw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2uanfgblp.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hstyopwy.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrdyjdm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hadaooiu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cruhsvql.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2idgbhpgo.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjelrag.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsswyst.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2shftcrap.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2dejwjank.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxctchw.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2jnuzfmam.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmtkvva.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2chjdtjai.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwblxbt.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gerjpbrx.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbpwdwv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msquxvao.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyngjia.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsymvvag.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkiufwcb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqxigjf.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2hpidfeqe.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpczgii.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2skaoykxv.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lexbqynw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cciyaylp.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruccvqxx.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmunfyeg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vusregxh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kixvfawa.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjwdeyj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iltikfpk.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjthkea.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2shvuzfic.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iibaxamd.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxjofdh.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnkjjsw.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2saijgtql.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaccftr.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2akbqscgy.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2spidanul.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2zhadgndd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqkpnhi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2kygsckyz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcpvyhy.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfezubh.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmmolzb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zujfixsw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlrdkii.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvqhcqr.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2modxfhdb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fukmmzrn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnbfrtc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqzgzml.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuggakr.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuzpffn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxfvavp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2dflrxkpi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qefvvfbx.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2asskyeya.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjignaa.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2avevyrbz.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2eepazscs.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqykcaeo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtfumzu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyszbhl.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmrovjb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2zxygoopc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dslqpvez.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2inzfmkfm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bcryeata.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2wnviubgz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzsnebm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrnjllo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmqaeir.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbalrie.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcfydwu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnewcjn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2foyqjepn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmyozke.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uexccoyj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuxwebz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdmnyrb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2imbmuxbs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuillps.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tinvgiyy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2prixwfwn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zaeduxje.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkjyblk.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dncpfisk.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2mivlehux.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wjglzzax.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmgcrfa.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fnucdnxy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dhymldyj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyktmpnf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2oczxoafd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmwcdij.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwpjvks.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2npsgmxnf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slwenjmk.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfonvwv.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sejdvvgq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2twzvyqyg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2bddhfeam.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2neadctds.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2henfgdvu.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnbewxq.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2ctufmqee.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrrmwvs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsidfox.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvihngdo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfukaphb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfylctf.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2appmbilh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tioulrgq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2pgoqomqr.html


<!-- 参考信息 -->