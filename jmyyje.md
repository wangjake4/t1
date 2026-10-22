代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iudovgxd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlgrnjh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kflwjpkn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qlssqawk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2unflfwto.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2llrzxmvs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhktyyj.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kifyagam.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2sdscwfme.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2arqzfqxd.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhbwoht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvzifqh.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbfvinw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2vngiqpzr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qqeitvft.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkvermg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtungbp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bemszslw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2gmthuzkc.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygksoipc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aeztqirk.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyojhdi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2mseapzhm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uopjfzjp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzovfwvo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgusfoc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdrfqcc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2datejkri.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2xedefpav.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsovkokr.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpemafh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ruitddhw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hegfhcfq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2acmywipg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwyybszy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2grbxkdnw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2mogjgqxc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvqlfea.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2oswsudbh.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2moxplxmr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrolpzz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbtyyaa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2urckvtpt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2beoojezz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaxuskb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ausrbcou.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyzpyil.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyqkrhq.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2duxuothi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2iakkafst.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlxajoq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdycepp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxclksef.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wajwvhly.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvvmmrm.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmynnixn.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnykskwm.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oikvkerd.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2obzwaplt.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzjbswh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekebagak.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpzjptl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2eidkontb.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhkxdac.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrrbdwv.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2stnpmfii.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfcltba.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzyvsam.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yguaubik.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vuieevgz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqhgppq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ktygszkv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2harqrpmj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbrzwkd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2pogxwazt.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mltsthbl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2txissvou.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xipryogj.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnkeezu.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcodgbj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqpofht.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfnkvxl.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcufrxr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyifeguq.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2prsdvahv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrrfhqe.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jonpieyo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2razotjma.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpqkrhc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnlnviq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqycxuj.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2egzzmoem.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtfdkld.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtdjhbw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lajhsrrb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpgxeei.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvyqoup.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2reufoobm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkoypfs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnfrjnl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjsqvrf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2okcsdoyg.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfvzmgq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sziukrdt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmglovr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpxguiq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhlpoqk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2abajyrcn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlzpkit.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bizyatun.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiuweff.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2uljfvcey.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkjnorz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqqtvkn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2axmxufpf.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtgzcqj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxfjeew.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfrazkt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2spbautnp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpdshvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqumngq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gupeuqez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvxmxcr.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjethxa.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nmerphov.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwomsrtq.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkgdzzo.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nukavibe.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uidntvmb.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2zungxood.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbcfdyd.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuisgjm.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iitqtjmd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdfmhdo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tvftdcah.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbyqgnd.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vofpekyu.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fffjbnnp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmwhtne.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iakorrfx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rooamztx.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wvonkwac.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bedjpcxu.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcoxjbg.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kuteqenx.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kuagqrtf.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2shgcllfj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mcslkppa.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjeozkt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbuvtck.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2iwumztsw.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlkqbwk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdzitxu.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hizepiji.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqxybnf.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khliwcpj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkzztvb.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2reubaewa.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgajwyr.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xukhzlqo.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bajwtasi.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2typtxthp.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lurpmxdw.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dknrknee.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rggdbjag.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxqptzv.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgpezse.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkxifhe.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvlpfew.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2wumaxegj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vawosgyb.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyapjyr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffylvmxi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhvviik.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxuoirq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmlcekj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2smeahols.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2koaofpag.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjtirbl.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iymerezy.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rvglswmk.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2flbksygw.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmmffru.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuyknrs.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxnkdef.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oakhypzm.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzpxhbm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2umfzvvss.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsclzods.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmnzxgt.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mefbshhe.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plgftmpc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2adevwxte.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vomiujku.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jukveysy.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2etkjtqvf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2aqluaxka.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdqeheq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrlbcxs.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sejskexa.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aozrmafx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvareja.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcakwlt.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlucprb.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2cklksyay.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvetale.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnepgqn.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzfpsxl.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2eygrcohn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2pgemlwkj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ankvtmfa.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2prsxkbmo.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2pyewfkpw.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2drljxoxf.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gaogvrqq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbljbkjt.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdubqye.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhkveli.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oytroufd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hscvvdky.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2stgzhuba.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlxlrwz.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhgmazt.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbfmqam.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amazdkqv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzoclrwe.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnrvmuv.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2leqrijsl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vchsumlp.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2couzxzht.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2noeiouxi.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uflvxwvz.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxbgwfz.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwmtaim.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nguxckgb.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2snptrluj.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2unujvxiu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2opcencxw.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxfzndz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2byosvqyr.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ivadfqbs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwhzive.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2qfajozjq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2cujahcum.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2nunjotjp.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oksujbpi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqadzpl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2blilvplm.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2quixguzr.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gpylyxwx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmfwylu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwqrtsw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwnlnih.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2naoehqyh.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2eabudcoy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2bviooxbz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcqedxj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqyoifn.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmcncia.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2zilsnnsu.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzlhmug.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sayeqxrg.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2miosdllz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuukqsq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbegyvl.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjohjdc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2khrxemyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdequqv.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2karnkrkv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuyxtqw.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2vvupqeqd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rflauzls.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2flucijrn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hecrgvqz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tovilmdi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsaegpxa.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2egjwzidc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzsazwb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvddidym.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mepeylix.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdrfbkj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2majnfkbk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxrqeey.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghimwmqg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcxtaut.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2fagbduxw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qidhrtzp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyvwkxv.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2frusyylp.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjoiqsdo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2licqpbhl.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vdesbugq.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmjbafi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ghanxcce.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2lorankfd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2yshcmqrb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpkiabb.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zczgrazb.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2avsieefs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjyksjg.html


<!-- 参考信息 -->