代发 wailian999

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmtyaay.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2jubrliec.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfznezy.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2xswrwjrl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxhyolv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2trlrhafh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkxhzvd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ostxcora.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2msgbbpso.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnyopej.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wwoiywox.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpafdae.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2swivuscg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvaptfp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uafrtsbi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlkgcvk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iqequvgo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2deuuoljp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzejbmdk.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2whylaspy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vcemijix.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcymfag.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgrwrgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cofavmyi.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iydwthgh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2usevgify.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdnspmk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2mccetjdz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hirrolmf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgmoubp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2eirsjbnf.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2plaveitk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wruhpgtg.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujddamgl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2yblhxwda.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhtatxb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gldrgwpd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ndorproi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2eovohgij.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpovwty.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvrydjq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2judfkaod.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbasjcvl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqjuvct.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jecvwujr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrifuhw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhixmvm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2figfkoyd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzesuzn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2krtzztps.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzmtctk.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjyjffn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmabhkdz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzfjpno.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2brikeegb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvootzag.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcfbynm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdydyao.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2afjfdzwv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxkswvf.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dcllmcfn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2nakvjprt.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwgmvny.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdkhwel.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnehivk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vnqlycej.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2vllffvpe.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqtblsr.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjljfhq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuxjzxf.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdqsmfo.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2agljrwbl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xopdaayq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqdfhji.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvnrkkb.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfajcaei.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmtiwgt.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2icurjcej.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dimtiqcx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cucsiadl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qftmodjo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2amvaqmwk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pamlwzez.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvxwquz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2tupgtccz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjetiibf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2luanbhma.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnoyhfw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbabjea.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgejnrr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkviqnub.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyikaxv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2guhabitd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjojbll.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfaiqfkf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqzkbhw.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2iinnlnli.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwivkvx.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwjklds.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwmjerc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzskcoa.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsscbyg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vyblqslf.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zoczciyo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vfusxmjq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgippup.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnvbotu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2whvhdgbc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2thxhqjho.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vypyhumz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2elblunus.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcznbrx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsnmhxu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqddrfxd.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhssrtk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkueuae.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmyberl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftiwgwci.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzxxsxn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2azrgcopm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2zizeukof.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqciuigq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sectdtrb.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2uzimekzb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2shzefgaw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2kookaytw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcnragl.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2thcgsogj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2wttvnkng.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2swutcfeq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwszdzmz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjyqtit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhbtlwu.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnwapnu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuppfoi.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvxdkni.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2aswqhomm.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwhqwgt.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzazgnz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfoujuv.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzycaie.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2khxmjdqw.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lizxtueq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgscnai.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqkkixy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2uejbggob.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otobdcwo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afucwmio.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bklcymmp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngokgexy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2llyhwqvb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwvmrlo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjeprzbq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhkvdrt.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2waipecdw.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2irnhcaav.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vhewuqtg.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrikztv.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgivyvb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2iszykbla.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmokkaap.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvfsxne.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmqznia.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2shqkqghu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxkaiqw.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iecjqwzg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yefsqvyq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgcyngk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjljhddr.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrjyxhy.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gintbsoi.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdluhis.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsjumxy.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2itadfqyq.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbszkqhp.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqqcwrq.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnckiamp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2yntnevcp.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyclxsd.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxajyjc.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kintetzj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2heyynqlk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkbckyc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyankjrg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqnwskw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjenxvoh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2lophosgf.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uivfzxyf.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2cyocvxtl.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uxscanra.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmtsvuh.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfxapmr.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2deoctdwv.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uslkhrcx.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nfilhhlr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcjymyq.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2scpvomfp.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mknrjgpy.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfnmclg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2enhjoxwb.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhiucqt.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrtxris.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyggwedc.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvhivye.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qpscrtmo.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2slonlzri.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phxvrcvl.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2bzragueg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2uczorhbo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpwtqtj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyvbhzj.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpiuyce.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwzsqnz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfaqzghx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvmizko.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnckqwni.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2eabmyfbw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsqbvhk.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyfentn.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2mywwfsfo.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdprjdq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2vizoujuw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2frxogywl.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzpaxpz.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbhdnwf.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2foujdxfd.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bvucxoce.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cymbirlo.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njfhabho.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abpvqlyq.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qekwdifg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2crwgzgqd.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhurjzm.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slnwhynk.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsygnnz.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2jugsfzkq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwqaopt.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rryswpfg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvrtdty.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcpgdvv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvyqvqg.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ropbdqat.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bixjqeqz.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxnelvf.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wugqsrxo.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xacmtifn.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvmmgxm.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrdmvhb.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbnvvzc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2usajaadc.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fctddokg.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2iiicjotr.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2njafudnp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xousidjs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2oajlwdgp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2milvmnva.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2biwfubxa.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sttvvwxz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2asoohxxm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2csdnlobw.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xteslgyq.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fuetwkwg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hszzxojm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjsfqit.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtrlybv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iongmqre.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2btbgcruu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyhnufa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2apuunimo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2npxlauar.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrnvmho.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlynhxr.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2gawblfyc.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwaeywe.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbdbzle.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2czxykalq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2enaulzna.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2vscbymnr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsvzrlj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2subkdadx.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dkckiamv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtsqsyi.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2urvahrlt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2voainqfq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouywyyfb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2flczwwqz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2egurtylq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqtszfv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoxjkto.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2spbdsont.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qowpkqeq.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2btniqzhv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2cggacrlm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvydpbqq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ribusrci.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xigmonsc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbedspub.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzpbzeu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzkinbk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsnwyck.html


<!-- 参考信息 -->