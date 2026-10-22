代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xlaldkqx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzfkmsy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2axernyuq.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2naajqllb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlmckhj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vndokdab.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2srvewaxd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfedgktx.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqrsldn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcmwfdg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eknzcrsn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2snnevfvz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vafmhbwj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtxpcqa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnnuflu.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2heftddrl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsdexbw.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqpdfha.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2gfujraah.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eegssuze.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxaugwtd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pdamoyou.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfjyuky.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yajxtyjx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgwnsyl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwywsyv.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrytlos.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxtdktc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdowaqnn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuknwgk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtnkjlo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhhnkgl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzyhgtp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyndfsd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nppnswbz.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwbzhai.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcllumjk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgpdoph.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vttuzlob.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfoxmoc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2jopoiobh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxhglvn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lelgmaab.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2okyaxwpn.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbygfqi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2llqijqou.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qyadfzmo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjjhbuo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsndcwud.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2awxmujnm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsdbrth.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvciuywa.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbyrjuc.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jmczcnuh.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgtlqtb.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ngikfhvt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjvionl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqutvswq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tncrcyzb.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxliccj.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mixceboo.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmpiszd.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwvggzr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbaorkgw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrttybj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lyheuoez.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tmftbkdc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wctqlvnd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgffovfx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2noegsvzf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2dquwncwt.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2giwnyurs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtkhiea.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohotqpfm.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjoxdzg.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rusoigoo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrvkjde.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtnetgd.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvjfwav.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmybqtfr.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2xjykvexh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkarcal.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwkvdgw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbldbgu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcdfmln.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2glwaypui.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwneuid.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqfjsoz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmvftvi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkazwoh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttauftbt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kqehspqv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjrlguf.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iotbcxyr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxquola.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wonbjemv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbctilzu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2memtjhpg.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwbgtxh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pknhbteb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqzfnjx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2emqmlufh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tihntdok.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2waisdifh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2frjagedh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjgckgo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2estijmon.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvcvpca.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2slaxpyvq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgxrobq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qakhbvfk.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2yciujmba.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyprzvi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpnmshl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmsjomx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2snzgemqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjnxthj.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkulwbk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmemmsbr.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2yixbkyxd.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hhizmtyz.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtpazek.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2twxvjsbo.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wszcrrcj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrqmnxt.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2nllusrvg.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgfamib.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdhrwjw.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jemxcjyy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuvppkv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwlzjbn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijorlbya.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vzchckcl.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bykkvjtv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjamuctq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zmufqwnh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwnlwsl.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxqoido.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbuihtb.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ectsuylv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ropdioad.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ptskitlf.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jesibgkp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmenfiq.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihevwzyc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnlamog.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2reqhllgc.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjatgsz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sodpmido.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znczbewp.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbfaieg.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlwuxog.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzvwdkw.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2scrvlxfh.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvfmbqf.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nuremcbl.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jregepjp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efqtgzgp.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvrmpje.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2demjptaf.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnbkvly.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ensarrgd.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bstgfkid.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fcoqturo.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvembzf.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdxnsgt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgymfwqj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2piserzvp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcytohw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clpjyltt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkncxjb.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzcmzji.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2dufgbubb.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpvbjrz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2sysrcpcb.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzmxgbf.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qboviodo.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bphevyle.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zatxpbex.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqidkkp.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2dauorvjr.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzxkbef.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ezloeecq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2uohstcjn.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yehqzyoy.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqfgkmd.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkunftzb.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtibiwqp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnjkkvu.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsftlrs.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zharfntb.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbbiegr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2vsaceiiw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxfqjhy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmgvgwt.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdagceml.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtlqqzn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcmumxu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxvqzea.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhocqvw.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2qnotlhva.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2xuujtslk.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfwflxt.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2eowqfila.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qaczeicd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvfwrhd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdesxyo.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvuqgfk.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhtkoat.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vcymgcph.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2frprurzd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nixtsoay.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcoknjna.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhevkdki.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhuwyqh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcwvsax.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2mrchnnva.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgnlnog.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2afujqeff.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2posmioqy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jftcksha.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baskuccr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2celbezzi.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxodjwao.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjndgvgj.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qabmsxjd.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eomiwzpv.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bezlwdpl.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yknjgzuz.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfmxbau.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2sknvoidu.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqasdlm.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsuebfz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2umrkmklp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtstryw.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2otrhsjbw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpfqhpl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2josjantt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2djqydjgc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqnfjdd.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdkffgb.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oipnpima.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2shntlmuc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlpgbqt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2catqlttr.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2izidddbt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2anaopane.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klmiisqg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqqgsim.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oepvqnyv.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2reqgneum.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhdrzen.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2zuakrevg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2psumcupj.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2boiwrtao.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrtwklr.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2erarcdqr.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnskpzmj.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgguklzo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxcxaup.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmwkwph.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2caqevuqg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2lmplimbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iptglowb.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvjfvyt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztovjwgi.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdocber.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcsbhqd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nournhqy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqebsxh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lknpzntc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2spemqtvb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqewekj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzkodnt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbzjzkd.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsnmvpq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhatsnly.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppofaeqw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhnwriw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iffgezzr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bksrsnze.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2bddpsrtb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpnhxso.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvpvyci.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvfajtm.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsjarsr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvzgmrr.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rdupkvaj.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhanxug.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuswicu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2eturatye.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2faslymyv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2iennwjxf.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vokklray.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yscxtbtl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjclohc.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpicfqqm.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cplwoios.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvryuqnu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2deuzipqf.html


<!-- 参考信息 -->