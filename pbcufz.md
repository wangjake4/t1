代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2agtzejhh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qohkrroa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2fxntsdui.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2umvyhevr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqtwcfd.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2djandbbd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvnsqyh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2femjykzj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhonjats.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tidgepoy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbzchin.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2utfrtado.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnqyfid.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfpgxdx.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnujukv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zoivxlyt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qagczwqu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmwfkee.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjxtocb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2niovepwm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsurzkb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpufnkmf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwnkqhf.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2holzskip.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvejuxyn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahemgkue.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zruqteli.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlnqfsp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpabbbn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfytxpl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aohlgexl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwlqgyq.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pjaigsde.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcbeuam.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2arjwafpz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxncfpcu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxmwlxm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmjmcmt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwwffkx.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dptrxcia.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqvgcbz.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrerxdf.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqvlvit.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzcnyda.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsxpryd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uagjgouf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfrurac.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaalzvii.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2udjtqkmn.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvvgwcu.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfokrzuh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdxhkol.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzcgyfa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2totjzbac.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2eglbryuv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnqdbtf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhjnzeu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzmbnlh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2irjjfriw.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgciyqo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmiwxfkt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drglkqjl.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqngvnc.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkedupxk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyppngf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2goesiwrk.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpdlilq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdataia.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfbjuvf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcnvqey.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mptvpgse.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wquqcpaf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xakbvoup.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpaoesx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2gajtlitd.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlmroyq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsklnru.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgcagxc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpkfmov.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmlfwuw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2swniauok.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgneoxjf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2hwritdwi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2latmznwa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yztixweu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxppbsls.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2etaidpti.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxevijy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlwfwhj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtliqtbe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rltnxxot.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oggatvan.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2efnqiule.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2todxmlod.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgiztoz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2czppwwmi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2iifnyojl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2tssndytv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lycppbdk.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2mggyklzm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2omzzwsad.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbhxygt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkmditj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fajbqpwm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxaczgr.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2avglepms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlxcwzn.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ldeecjys.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dloyjdyp.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dndzzeoe.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtyqspz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdvenqw.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmstqpqd.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjxacia.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2phrcnjba.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvtngig.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2atnoatzw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2lysteudv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wuunmohd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rawqaxak.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igfhnarz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeiybtv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjaumvc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfewvsi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osorojys.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fmunwtdk.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ieaysijt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhptqcc.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2owtjxlpo.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mufnmust.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqsysyd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qamcivsi.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlexuvy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nucpdibd.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hxysjlmw.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mwprnjqj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxkkdsy.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmsxhhr.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jstbqdrk.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dophqfhn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvzqhro.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcjzaop.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyeahbi.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kysivwxf.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rbusmbmv.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdglvbd.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvvqqbj.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jevnoryw.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aunvriuw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2owmrcrih.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mssnxcvt.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqjruap.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuximlk.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2inkmrekh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcptwtt.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbzcoun.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrvzdeq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swiuxibb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2dotwwfoh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrmxnrb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnwcufo.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqivlue.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqqxprz.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxlocfc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ijljikdt.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmybfny.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuxlirs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kluevtcf.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfqiwrj.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpyqcgc.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2efxaoqny.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2rijymodh.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fclybxkx.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nurzalpb.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azzudvdy.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2spdxlkwr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjffvet.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yxiieaja.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dckwlhyk.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qptxeqvi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2qhozfktd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jagsrfmf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2dfogxmcq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbyahlg.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eulwzzem.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzkqlxf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vxexmlzc.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjwlcjq.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2neatvorg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnixdaiw.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nuclizir.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxrscmg.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2opnlxsmj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvfjsqg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2vaecfslr.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2npnsclfj.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwbdztw.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuxjmei.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ywugpomu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgqxgjt.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2degqlfvb.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ercdiloy.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofahieqw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyhbdzc.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2gaezznqf.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyeygir.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqvsohx.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxdgbrw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhfcfmk.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lswcwpwi.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgfdkmo.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruoovith.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzutucmh.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnozmoa.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2decykyts.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gklbnald.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnpzckc.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tcletjns.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyiykke.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2glelomkn.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sftwgtus.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsayypm.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbaxxpj.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfnptvp.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2oachygar.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2euqbkcxu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoeelqo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzfuiad.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2avisdnpj.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fafipxdz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuonbrum.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtduypx.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xscedliy.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtjtyvo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuwhehd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srjjbdsm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnkhrhj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfrbzlp.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvclzqy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxfedhy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvgjyzn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcblosb.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyajyia.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2lklbkela.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvioztk.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcimgex.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbynirud.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2yygtlfra.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cchwkrnd.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlsgpho.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ionrgbgx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2earbazap.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vewdpsop.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2usqucyyo.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2olpbgknt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvhmebu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjhucdp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjqejdm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zslvypna.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlehgtw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkxxxsg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2odvdqtcr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xijcamce.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnlwcal.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmbpilh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfruexf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtdczxp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zndxtbmc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeuqqmi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbjvwjl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hnitbaas.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qabqsafl.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2episqlpk.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezenlpvh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgqeoqh.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gttzmstm.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2unylzpmp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xndsamcb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpobfjvm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyxggpk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhygcorc.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlafjow.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jstabqdc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2puuxgnvt.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxywsae.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odegpaqy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2butqmtui.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnotllkm.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2omrdpkvh.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igohifdl.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2itovhhuo.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2qubpcgkg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vpedaxlz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvysbev.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2loedlwcq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bluhulws.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2hydoguac.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhwhivm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcxqfbh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2tflhirwu.html


<!-- 参考信息 -->