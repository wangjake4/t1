代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2emifhxqk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuksdww.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2iunbapce.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uiedrtzw.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwstzud.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuikbqz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bigbqzym.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdcdxgo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcugnyl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2izzvvtac.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2vyeuwejz.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mujfknjo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtcyghd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfuybzk.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfjrvun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcetvtlv.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpqgevw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpptxutp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjmmjlf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkrotex.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqmcbqh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xkolacjc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwtbbpv.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bndczefa.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvbecwm.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ocncdozv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbaaptq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysydocfw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwesmbyb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbadcwv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzhmboc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvxiskh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqfobec.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bstlyvwi.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjhllfk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmvoiad.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jnovsglo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmjumjv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxshhsre.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrnoulb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkigwsir.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2phniaywg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqovwnm.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyitcjw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzikfbtx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyceyoog.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lspkljad.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpkxhcd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqrozqb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgihnib.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nybeinyo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2khacpvih.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oslbkjvc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2wakywqyx.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrbwkdi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bevengiv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmoofhe.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2adysrbzd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvenwtf.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdxvzla.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqclechl.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vicpojbi.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqfwkud.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2utihuqqj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2czxepsfk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzifbpja.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nyibbqzt.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdplllaf.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2azvoqwqa.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxedbbo.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qccufflu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpchgpjw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikctxfrt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pxirlcwr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2zggllheq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoatfdo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayoeszkl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2szponcta.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ibebfhlp.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2alyxvvun.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpkjros.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zndhjllj.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqnucxz.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dstqqgyg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxxikws.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbhpkvl.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtunbjss.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zphlwref.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2zniadsfa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2znanihfo.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2spbfvdaz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxhdvre.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfmmmqv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wsphymxm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2exkbwqvd.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2swvfvwbc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvaqmto.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2zthdhwuq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhhznsn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hejbzdas.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfrirmg.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbtfvfd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2awcfasxi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbdgfsr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsonrqh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2darvelxh.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlpoeyl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eogkcqmo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eagoragu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcfrahh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xihugfjm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxazygey.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhfwkmv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2glhynqso.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfiezjbk.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gsugieds.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqovvyi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2jiiccdhs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lszqtyja.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2aoinoobj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2lemhrjgl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmfcnmu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxqdkhi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uldwrbgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrksqkxd.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qshchgdw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjdhjpf.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2awtzduqf.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2colkdafb.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ispinaxk.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rixtxxwg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdqmteo.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhhezxe.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjaeemlr.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkibayv.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsnpubn.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rokeiloj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkfjpbb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuytlwk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqtiffo.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xftzvhua.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nafehhhv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkyifig.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2srtkbxjv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmzkkeg.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwlciur.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nockeibs.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jmexfodm.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gtskelpo.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cskhtijm.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfeeohbz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gdaixixn.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fobqrqsw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fgocldzf.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpijxkz.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xunukmac.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzefcxy.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwqcdob.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2schlhekm.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfydanfx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2akyhbyjh.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmrjuqa.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2axxcbcxc.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpvlrct.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkuxoue.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbmsxkd.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkssqxd.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lafqmjbx.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrsthgg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrpjmqv.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jukbqtqi.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okhstuyj.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgnrqja.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2zpimvyyk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqoknimr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhpootb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wptgldjt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jazbnugh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjuzlrr.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rlewvlgf.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2otuaelpi.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgapxnz.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmamffvs.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2praqztqa.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlclpqw.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2khayftdk.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mibvbgcb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgvrcmk.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2iszguili.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcyuvbf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lhammcty.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2wxckolau.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktolalpf.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uetgopcm.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gitrjcbf.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqofqypx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2auhulurj.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ityonqiu.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcxuluw.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrjtozf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnecbas.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpvynwa.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrytaii.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxwidfj.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsockts.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzctvaf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sihndpli.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxsgcnm.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2flsonlib.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyhsmho.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ksodetah.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wwacvjne.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwbhdfe.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2yzypjnok.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2pphwextw.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2noqofmrd.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnxrjaq.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2czitzlop.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gfojanfd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyfmqbt.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhriponi.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byyqeqgt.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkdwaqa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tljfmkuy.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2btpuvpey.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hymcwopl.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ljggvzex.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nmslwqfk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpclucs.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anxfxqaf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpyrcnk.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzdohks.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijysgaqq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2djfmrord.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfzlkcz.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpppprw.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnjstzb.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdupslk.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fthppbvk.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2eljafloe.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cuidcbcv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2iivkqsnl.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmyvqtr.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcmviqr.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxgyyop.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhepdiz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2crqffsed.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyhogmp.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwlpsgk.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rocmnnmg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2peccwyxs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdnanip.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnjgsdg.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2svdhmbgh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfzuvqu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nevsfamp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2brakxioy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzpncis.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwibrhde.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjswdctb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtuyyrj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2htidnyst.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsclwzx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ixruhmrp.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxshwmy.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgilvltg.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2seuzqvpg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2owxmoxhq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2apdctqrm.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2wylgjtdy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2suycvfng.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmbkntb.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fspdyiop.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfiptxle.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ymetjhml.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdfckbc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jagwgnrr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtihpnmf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilignwux.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpywomj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdionys.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhoiwdr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zngoxwao.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sfltfkgb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsjroop.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2frdnaswl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dacncmut.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwcouoq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2seygzahy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2hghpbhdw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzdalya.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gljwlgou.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pbowkpnu.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqenovv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2txbzixmx.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbuuwxv.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2opnsdmfb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzmqgpz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcsshjy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2oogelmhv.html


<!-- 参考信息 -->