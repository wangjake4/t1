代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxwxxxj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2oakxyytw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2tfanzxlb.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mbevuvxa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdvbwrx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvvmaua.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fdglmint.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2syatgyap.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2blywuljt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2raaoirmh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uoretecz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqqhshk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2sazxlvri.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmvuisq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtxrfvd.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvdtgyb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzrqgkc.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wpclshoz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqlogeo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apcmmpcd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2degcaoti.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsitgsy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpwhcpm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqxwgyh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrnoqns.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sctxzvpj.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2huvhrbfg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyfikop.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ouivxcoq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiaksfo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cldugari.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2meajftyl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2wutvkdfo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pucepeep.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wkicwkfu.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuvxovi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnadezpp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ordfnddt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjpmrbn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2valnfvtf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwolail.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpemvncz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2azjbtmok.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxcedqq.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zscxeghw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwvxihf.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjnjmzd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcnvuwz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjndbkue.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vctsozpd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwsvrzz.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwehtir.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjxoqpo.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ynosyfyj.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpewwzkl.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzoigdfg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wklzxxng.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjfaasb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmzijix.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqwsyvu.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cejalgro.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fchkjmsv.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2atqyauaj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnenxhzl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhrcnej.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2klsaxosq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxwkmed.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfeiema.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyarlano.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjiqrejt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfhnstt.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwqrbdf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtzgqoc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdilfcad.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xquldinj.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2iupvdtxp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyyidim.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hohfyhck.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxmliif.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnynvbxu.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2qodxptub.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmsghda.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsnahmp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pgksbxum.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bssoncom.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwchqxuy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqewlij.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqubycjk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qaogdmhv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2alnothjq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbjucuf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcbbkkp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyekefcd.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxezycd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqewxwa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zznblzdg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2csazhypg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxzeejv.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2enikptey.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2osxexcyx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oxifvbtj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2phztbonc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayivymap.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqulleez.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2zajdpavf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2luulksfv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfcpbdw.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdqxgqw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2usgrnktj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2iaizgfpi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcprhux.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bqeejmjr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2glnmzirf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xedmebqr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2olkdmlbu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnrweae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdbhtwu.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hivrqran.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcialee.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2evvughag.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gchyfvgw.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2badxekcc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyolqyxr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqvdumg.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2suemirso.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2byjdvvbt.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxnhkco.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2abytaype.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qksllotk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvhvlsi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2npkztmmg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdgitgc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pynrrivz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atplrcct.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtycbud.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwbqodt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeltflj.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvzavju.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgkutcg.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2skfhubpp.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvalzax.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eanfjows.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeczrgrs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmzzylm.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcdumxn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpjggku.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdrzwjj.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2izgegunr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjhwwdg.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnbjmxm.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buonqxns.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aukulnxs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yknicnaj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwwmpzn.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpdotwn.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcwipxa.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2eycrzobp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjdkjuy.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuyccum.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imvrwtue.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2itceasqh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2stdmzity.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzngihq.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umibfdnh.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jabmqllh.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjsbezk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciajazqq.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqsnaek.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjicltir.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqszayoh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2qiptjqdf.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtilgzb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2nviisyte.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2httiojbi.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2yoidisho.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2maccigmn.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhhmcng.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eyomnhdl.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aecnjyvt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuqubwj.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvtuxpi.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uuaoctgu.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvudagz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlxyscf.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzxatsc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2npziyqtr.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgndzrpo.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qufjmwmn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeohgfe.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuyrwai.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aeesoatu.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2akwvqvrp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxalstz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duavevgo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqxpwsv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idvwthdb.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzicsds.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrokiybn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fmooloks.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzpdpul.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfiriot.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqmugjw.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhhzcse.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2btcbkcph.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjzmjil.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2nonbyqfv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2cuewqdsu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kuaghnuo.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2rfywbznq.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjdouhz.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xjswpjfn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcwyqpv.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phlsnxmt.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzbrztu.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjmlpne.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2unhfruvy.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2jliljtpv.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmtgkrw.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbylvwx.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2exunwfla.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhhpogn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gindypkd.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrhckzc.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrrwqhc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyaaipj.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vohaqbdj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqxrrsu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gplrfdsr.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyxxfcv.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjdbqsf.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2eprolrmt.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgykrsj.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwrsyyp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2esuielrn.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xycbgqnl.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vopbxoeb.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjnwxxw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2auwvujzt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnyizyj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzzgbcb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcswfgn.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtjakhi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzrjrrx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2iernngew.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2stcrygay.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvfypcz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mnddxmir.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byaybmwg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2efaqldou.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2caxknvge.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxusoqpu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2whpljudl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2dttslima.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjslfemj.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2asnxcxzn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2yhliqybz.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltztnfro.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvvxbbq.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2avmfqltq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcromuln.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtuvqfb.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhcimaq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2wspyhetb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhypnwm.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eonsmgij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stkgonxw.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2tyabfuvv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwwscxz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2apaniyfz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2darwkjtl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkkmije.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2prcnarfu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bthwmxdn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmecwva.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sagaavgq.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vohqilzf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxiveyw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfddrnd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yucivmzc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjxzmbp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdkqsmz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2yotyuszk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iddrcjir.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuthoro.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2avbeiuso.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2fceqpwwm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdmjtxp.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2phajbunv.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2kziltdao.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqvrncu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxodkame.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmyngfs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjlqadt.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgnwqcd.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlknotf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2smvxxwnd.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgqdotz.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iycoybzc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irhfwvgy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbehujk.html


<!-- 参考信息 -->