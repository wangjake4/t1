代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2afuquanc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqvmvqx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ixachajm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rxycbkbe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bfghwvrg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2szpznnnp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yjznlkhk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzdyehs.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pfulhoyz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iloqdfgd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdxkhnh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lohsmzwn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fuscifyh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikujarla.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2usoiyxwa.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gezkrfdz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbpwxly.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mjggpojj.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2htowreef.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lciarlyj.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2psrlcyzn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnttmxgd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2unmrwjzo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2ufaipnqv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtntspb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsdgaht.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2nstdvjfh.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2frvqzmai.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuvrsfx.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjfnoxn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2imudgxbf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbycvuw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slnkmqwi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjfpiro.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrrvrco.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzshvczy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbdbnfm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iargugrb.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2htpstmkm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcprzueg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmksoxy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vglepkew.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zovzjzif.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezalzxrt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtpjeoq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nplctomg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgdgczq.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzlkyfq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqvbfje.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhuetjt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrhdiax.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtaojva.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwragehx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqeetgbd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2eidrukul.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2whcvkhqr.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qzaikukn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2insycbkz.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hdanhelq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqxxdax.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbscinn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdyvsqm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxaqzdq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hijikgrb.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkadsfgo.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwphziy.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzlrich.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bywdnbze.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nocblkzc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhbbofs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ypapmcmc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfgkjwi.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwtjlen.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlepigb.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbeuhaoz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxezhrc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfexjwwi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2upwisuil.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2esdwloti.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wztjzycs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcekeuge.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2lynneygr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2kujyxwke.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2znxpflfe.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfmuvgf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbseseqb.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuatroqn.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkcinvm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxjnyvk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyaxqwla.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnsrphe.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbmmdgr.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnouhkd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhnstaw.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2emjfdjzr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzpvviw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbviozz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuuvbud.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2giuvdqpl.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iawcwllg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fthdcslg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdhqmda.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkgukuj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjvffzj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrckvmb.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoufjlp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2xeczykgz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdxkzlx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhpchcr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvjsmeo.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnzeefs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rezinjec.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bygvxpkw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2koxszlsg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfkqhgg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpbqtti.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbphkrb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjbstff.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2esleodtc.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nyennqyt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2opunwkjt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxoornu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2yswtqffl.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtzdbah.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2gwphdhgu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2owvwoprq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2owsobday.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuutiol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czwpwuwr.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyromff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zioclyug.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2pjenlliq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2whhpyyfa.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsskdux.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ertrhxhr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhmeulc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrzryqw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2obstyqsr.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mzefwomd.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcvfueo.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmwwviz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2tyturdsp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ybolcftj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzszwzof.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mibhuyqh.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqntgrsz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxmvcmu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sahxsjck.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmifaedj.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbjqpfw.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfntvdzh.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbtuklu.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kfetlbyy.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2apstsfub.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pomkxmos.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2njbnrzlo.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwzzpmq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2psisttpv.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2urdrplnh.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hmznuvlx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxizdpbb.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzkfyxm.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gquhsban.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnzdtbz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwrjdro.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ublsoupu.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvrnxkh.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bwapiqtk.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ynajtycv.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2auefybvs.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olyndofl.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwghbbua.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btbeapkf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rieimoru.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2msadnywm.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlazlqav.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2drmrhxub.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2emadiuwx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqsaajz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqwvglo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2piflgkma.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwddrjka.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqjhbrd.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2syodwrzu.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2xbumxnsp.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwzbxhl.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtigdhi.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwwscir.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2njvqdgvy.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtchaxo.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2sjusvsrp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrnhqkf.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2abxmlqcv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2krnhnvfv.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xyeaopkn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2szzrpfut.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flkiynxv.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyustkn.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrndcmg.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fifkuipz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzkevyh.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gotuoqti.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdywyznj.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtekubp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgoyrgn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jostmlnm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpkdatn.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akvkxhmq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqtltcy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnvplpa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2znlwtxph.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjrazhj.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrzsntn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbpckjx.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2euegxfos.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2smaxjzhx.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgdukgu.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2locbfkhw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbzfzea.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kdirritj.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpqmxsb.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlrbdza.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wndonzzy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdakcgx.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etpmsnqh.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzeuqkbz.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2passrqdx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xldifdvp.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtbtcej.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awsscnrk.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mcptdidm.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxikazy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuketja.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jweqwleu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyrqspe.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgaifgv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2axbnuxjz.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wlubaboj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuxmmsa.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xakjjaem.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzkfdwk.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpzsbgn.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbgqlzw.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qmslwsgy.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qazjcuic.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdtkkaq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nikodkwh.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhuuirq.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtscbjl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxuqkfb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2frxlewus.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfdwave.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnkqizr.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oixdnlbp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbmhymn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2cklubdcn.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2gprxhlsl.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ffoxxdia.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyyxklv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmtgrzk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlrvnxq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvsonfs.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxppbjn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2eincxtgw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2ukodrvqo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxavwpt.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrsccsi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsbyzwm.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcemlzqs.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yumpclra.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouldbdoe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqphnql.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mespynat.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2emlsejyy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2znjpviez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kbilblnu.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgdyrua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwaarnb.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2xelzaddm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixajvcyi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tffdyibx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2irwgftvg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpekkhl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgahtdq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2irfgujsd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2narijmpu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqpenap.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsaessv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2abdfafzz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfdqjak.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgtspvd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sngiocsb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcaavlv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzbalit.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aspsxyuk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndilwlci.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2daiohcxr.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtbozhk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wafdjtmt.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmnfpbk.html


<!-- 参考信息 -->