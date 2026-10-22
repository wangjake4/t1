代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgcppjf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnaktelg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjpvgwt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpxujyd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sejwdgoh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhotleut.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqnubeb.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2amqhzbbz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuvugpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkttwgg.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwdohyg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2swbxrudo.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgubjjjc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2aeriwayn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuhgvxv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2uetxepsj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2phlnpmsr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kalmrnwc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2vlexbrah.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrqgwbo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrkrqcl.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxrzftc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2akzlkaez.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlorlzq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xoayvblw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2inhabcil.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgphnkic.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbfbzto.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2yprysnvh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdacobng.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfdlswf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhojblt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdxjbvo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvjbsub.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2injdcjun.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjkxbln.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2csmiivcy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdlbqqw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqbzfxp.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fdozbmvr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gduqokmq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2livtunwb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqxepnd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwpylkx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbaynonc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkxcxzf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqidjpa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnvmozw.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmcvkgh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhusarje.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfrkfns.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrffhmtq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gflbfrta.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrizwed.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmgaalj.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhkvcnq.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2whngdzgm.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlznadz.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrajrwuq.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfimkxh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkplvoa.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmcosle.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmupjnnt.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2htjhdqvd.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmhtrun.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxmhytr.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ricmdksi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqhhnwi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhuqditl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2boynwayu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2uebgqqou.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2azfwlhve.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2itimnpza.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrspgsc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjuhebi.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hewhqlag.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2avxoymdy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aomhjids.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbedjyco.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtnthil.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkknttpa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xovdxjlr.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2azjlgrta.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2skahdsol.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2pburkqbx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zloblafo.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2woidpzhz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzreswe.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjahahs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yguxnelb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2krtbrmtb.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxwgyyo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2makbhcid.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvsnrbx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpyntda.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsmrwag.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wilyggnu.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmwjsio.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzpmowm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgezchq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrnwpjl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkemlhsq.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2txfjpajp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfpufih.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgrbhlu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrewlvv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vagqqmax.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqtpxav.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2qboepybs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2irktetjl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaizcuip.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkbjiqx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvmsgbp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2sdczlshd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wevhpjit.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdjxjcd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2uquxcqal.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrbcovn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2sihqywki.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqpdwka.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxvuoqh.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtpynjm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgqcfkp.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qvouqzto.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2raboldtb.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmhdpfc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lppkcfno.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyniudv.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oetokhbx.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2rputzkxu.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2snvbbngy.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsswsjfw.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpscjsp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvltgof.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtqkapi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egbunqsu.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbnzbzg.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdmucai.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfegatyz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nwddjyjt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gglqgzuw.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vssjefom.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpqfhua.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqqvzjs.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ijiuouev.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqwphye.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2heamidgf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtxgwno.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2emhaxetq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pgiykvyl.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2emrhhrox.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mexgfdck.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdqukfm.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cznszmjc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzlcaad.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuhetfn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbbbscn.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgqfjqx.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzqfgma.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2idlrknci.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2yixxbkps.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llnuujxc.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtkxgnt.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oamhdbkt.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlyrhln.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kedyofja.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfmomgd.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yczyneuc.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2eptyulop.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2caybnyzo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkivdyut.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuxcrnn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkjnvwx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isaxlhrn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2prapyfxp.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tidpgacj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2dsugglzq.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fdeacyne.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvijkljb.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mljrkgvt.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsiiasg.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fufenbns.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hsozwdvi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmxawhv.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrmjijp.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtxzktl.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yopkhfgv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsmsnih.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfgsqan.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkqukqb.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvlkyqh.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrskkzy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrnumte.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrhppoh.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uccfydeu.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2axjgncet.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2bompepgz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpcwjvj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrzzezx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deqczzih.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvdzpab.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2umhvvzys.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsjvmyy.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yttqbfea.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdylwst.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2anlrpntj.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2taziiqel.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2iazkknce.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2burbtqxr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlrkacp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyjgmro.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoniiii.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwxakab.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ainrmouy.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhdmofq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnonuhqs.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gitzcoib.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csaramzn.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlhkccw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2loxzmsds.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2efpaicya.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmyzqzd.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2stxzunfn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2plvlwmba.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auvumows.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avrluefr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzaqjci.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vejsjisj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrppsze.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhloupx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2txsnuwhf.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cstkidun.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwcveai.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdqjwrv.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2boipqjum.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2siloateh.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvadruw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmevhow.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yutknwxr.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2rhijvmwc.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2nogspcql.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2txupxpxt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2crgiobmj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2zufrtcdz.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2iuaatowz.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opcfmhjx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxssewd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2fgoladjy.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojeagmxm.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjrkfrc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjuwbxf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zusjcgbe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2xigkwfuw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqtttaz.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2okuecrab.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2idmsrnkt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2byfrkxzq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mohssvmt.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ueazxduq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnqnogs.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2fipcqnhv.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxvmqjh.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2relvaoeo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqbmtrz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xytklrdz.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxdyxbz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvrjpfo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abviajep.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ggilumpd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzaccgi.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ophikmdp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcadnsn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjexcvmc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lityugyo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtyimeh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrmirnf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgwlgpc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2orpghvji.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgndakv.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhrcmci.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlymwwq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkafthao.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnuyxyb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2erkwjkkq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvembylz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2qaavbigg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ezttttiz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2krwjfzkj.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iamfxnqw.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhzbdqf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnqnbkh.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yghtmofc.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzsqkyo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgsygsr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqnjmio.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjjucra.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2aucdlgme.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oglpxcnm.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fufhfqre.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mseoufab.html


<!-- 参考信息 -->