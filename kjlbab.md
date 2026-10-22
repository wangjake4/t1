代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuskazo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2biagsfdq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2otqeserk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnwaprd.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpwqqfd.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2akkvwcnl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2chaldhie.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnvrsgr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vtayfywc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffttnjiw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ssulhdve.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eemrdkha.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yaygkykh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpjnxva.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjejhxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbysrzaa.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fczwjjhr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2brzuelvv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzhovft.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2ichnugmr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjahrgt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2otdeptyg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkxhenv.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uoecprbj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2asrvxupb.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aifcveua.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2qceudqzs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zblcnpua.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoorufc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrbajwj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsskpyi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsopizi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnavqbu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbgbosr.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrnjsll.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqapvac.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmkqsmc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2aztccvft.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jynpafhb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbnnzxf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpihjir.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zluibhpw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2erbziejb.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrbgadm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsfwjyo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhekuri.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqwmlpt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2snthdthv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2zucppdil.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gortexul.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrjlqeo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjmybgx.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2arekltpu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2siaroipa.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxuqkyj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2znxgmtmk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlstudlm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwyjtjl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2cufdypyp.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkirkrpc.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmjcqpq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyhbsij.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2skltsixe.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlriipo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrjyieu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzhwtcg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpkzfgs.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfiinfht.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2epvjdabn.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rncycxuw.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkutfhnp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cecubrfd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdadghk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfhjcgj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kexnykfz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fsydejvr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoefqvh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsthcfjt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkgbxox.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsndaem.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjagqwjp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdbrixc.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2giryvcxa.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypusjyew.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpplguu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwvboqs.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nghvxwgs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxehtdk.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2iaaylsej.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbnukic.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuerqna.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ucduhpor.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vdazybxn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zymkvxds.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjoetya.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ythqzywl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyjnlik.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjkvkrl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lawcudtk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkpmgsq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhtgglq.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2amvjspom.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2twdxircv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbctawc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xufexgig.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hczvnnmj.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2asjbbnrc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aixytzni.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2akxvggcp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2toucltng.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhblgxvj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcsddrn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfpogxr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2trfuaukv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xovlbbuy.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxmtpbt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfftxjm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnzuvxe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqmrser.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmrxrcm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2oetjgrnm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkdnvsf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2stwtpmom.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyoiqbg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcusttu.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zbduxprr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pimweajt.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2jditaxig.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2uajlzryh.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbafmrz.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsicuqu.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kweurhqp.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikegkvlk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqiqbvvh.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrcyvin.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2srbuapyn.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zznlzxxi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2bulsnobi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aishtqqw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjeybmg.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhlpofc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxmcrri.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqgsizp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2grfshode.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twjczubt.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzmldet.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfjskhi.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sokmhtcp.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kdipnxug.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dppzpfly.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygesmkyv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ieawsgzs.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzsnwdm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dkccfpur.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwodvoa.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuqkaat.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoeatwlq.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpkumjg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfwgbpj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zghewufa.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqazukrd.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ovomsjyr.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtevocqj.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxnuknk.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqjyqrn.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwurshxv.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvypxitj.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmihlgwt.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lawckufz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlgokbn.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrmiiif.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrzbjyt.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2llryfjhs.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2xasicgfj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2riirnbwn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2godarqsz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdypgtz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdyjtdz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2motrpffk.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuwaixw.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrxsfav.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsdnpah.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2tauywpkt.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2exqhppcj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvrruve.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ioepqbko.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjuulrl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrvsomq.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2hshbadll.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oajomezc.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdanlcy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrnvapi.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkkyltl.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2srxtfhqu.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlyyopq.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vixltoky.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxrojng.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cflcbvhp.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llotzdjk.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtrtfxt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2dvubfedl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umizbrtn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2irckmbfw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmqfpab.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2whjssopu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyeenfc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2owfdltre.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqldkyq.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2drehbbye.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcplorrp.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhtcvwv.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2ythnjdxg.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jttifovj.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdagrmk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbdxtme.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2srgfhlgl.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcdvxgf.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkybsig.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrcqhlp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urwlpyww.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrugufto.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifddaujx.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyrqxdd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hthdsrtw.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2delcrgeb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfmdxdp.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sasxyhjm.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2efvtdimv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdztdffr.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmnqabw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvzidxj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkljswpn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2beppqdhk.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwvjgwd.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pldvcrmv.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmkammg.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcxbyzh.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjysupm.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcnssve.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzipffh.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwioaop.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2stbodynn.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmceixg.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvblojv.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzvywix.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2quxgjhmw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcfaldk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2kcplqtus.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2sugyyaps.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2thigiixi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxjuyvg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2jrucidtm.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdvfjou.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zejsyvce.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kzatkuyh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wogiohba.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvpzzkp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvyviaa.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeplkzfs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2gotnxulz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2btotiskp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yclufovk.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2enhnpwyn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2dethjvhq.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpzourw.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2efhevfkm.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfilffnd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2txxucfwf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2pkstsdip.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqqgokc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2urykrmfs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbabuld.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zunrtsqo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmwovkc.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2tieaowgn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbomkbi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2exwbpkib.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfxjmyw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2abqcread.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2njixzzkq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmvibjr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtrgzro.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2appspepf.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2cbegjazs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2bncokmbx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjnjwqd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmezinti.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhhhbeq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzzcztl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2xebipquh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfukbxq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lorblpet.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wnheyiyr.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcdqbws.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ngicnlqb.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rpahmkcx.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2afeproxo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfwxqkp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqfaosy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2fusypszr.html


<!-- 参考信息 -->