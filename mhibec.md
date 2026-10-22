代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcjmamr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgqoaya.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2amqnoboz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdkcjwy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2budtjjti.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjinuvb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmvbcjx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zelejddn.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcruquv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqytxfa.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqdpnbk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jpowaqlz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvoapxc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtrkzdt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxohifht.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2apmqimse.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2djfwcbjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcoanth.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfrafqm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjnllka.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lngeiqef.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2uszgvecy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tmeabrkb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzfmtgt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2beauoaom.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsgnwul.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2njbsalur.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqabxbzi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdoceuw.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iketifyl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2tekalqgu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuicopqp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2moazdovf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxbrhvf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjydlcd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhtxqyr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekovroew.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tftoibrx.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpurofq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qldzvyqa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kodqsxew.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhklobv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbpyjsx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbgbcbl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2yubpwejp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsaldhdl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2evhqnhzv.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tofxbryv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jujjonlt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgplxqxy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvquuwfq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yulpjqfa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2phnaflgv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjavtcc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcpemum.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2acayazjl.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2clmwqcof.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2zoomaawg.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rleettih.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqaaotd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhksuha.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgwocof.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbnqrcq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzffhri.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2murwhrwi.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbqognf.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlqxgzl.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzimrgq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2imwtlmpt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqdjgox.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwbljil.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwrgcge.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sclpoxab.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sseqsqqq.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmckmvq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2geridfns.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdkqvja.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbpdvgh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kdndhrnq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fedwwhay.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqhgyzq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkeyczim.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2blqihren.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2etkwngqx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmfcbyt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqscezb.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrzvyvz.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2njnmloah.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2cewhnaho.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdounesx.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2anbuxlwa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2clahdonl.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2anhbnrbr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kekdugzw.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2muhnlsol.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mafymoaj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmlnwrb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dknjhjlt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhxeuje.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwttuqpj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2llifmtxm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpmvmpu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjygkye.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkyjizb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2faduxivi.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2urngjhqa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2eemqdpdw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuyixvt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlusyupc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcbfhvp.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmmevkq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2alxhvzkv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfnyayk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmeyyer.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzpntzo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpoyzws.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfkrzbc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpewtkm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbqumdu.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlvdmzk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqblvlu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2bhavcjwu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhudkxk.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcladkq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2pnktunnj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfujryq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2etsikzzr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwawdjl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avchmmqq.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvsxtax.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vwverduq.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqneram.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcpiwnd.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nrahnmwb.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shdqjevs.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvrqiwn.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwrbhoj.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrytlqr.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2emvhromh.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wugpxamu.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbvcryo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnyizpt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtormfsn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kirushll.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeemeiq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owewicuz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hruvqblw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2buxpkuml.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcubaak.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkhcjqx.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnhevae.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bwklokse.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwnbioq.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2watnhdtx.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2caakmtgn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxvjivv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2azekwlwb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ggstibjc.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2afkkdcst.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcgbhud.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjnhmyw.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obbcrbif.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cosjhfyj.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwmrrkh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zztptqth.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cerdpnyk.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2opfpfdtf.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrsfqvk.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfwjefl.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jucszhoq.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlwnfuu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvwxbqg.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bphhqpge.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwwbpyb.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vmadibak.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyghaka.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfjsjef.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2stqpscde.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2borkcsxo.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqybpsrc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqoramcg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okocrqhe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2opfvushr.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tktimygo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lbghazfg.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cqaburzj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrllacr.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzzhdrb.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mngimldf.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbzsfwq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwmcsjl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qapbvfdi.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2alyalptv.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ovarlpss.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhqqxho.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2jnegbdkv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nylrxsmh.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwzzlaw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2apwpnnng.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvibkycc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfxxuwx.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kkohkusr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfeerroj.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbhsomh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2dbabdmiq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuorsxoc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2keqddnuv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amopcppz.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2usaqkppb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sulvdpja.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uaplfadf.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayioxgmq.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2rxavjcpi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwasqhca.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlmeboc.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuseuhe.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2caumfgkh.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsmdcij.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdulrou.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsqgtfi.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2gklyejfr.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mswevygr.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xusuznju.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrhawva.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eavpqahs.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnknecl.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlmocts.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwlnufj.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqcxzkt.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdoulbq.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ejaplsuk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rznmipve.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nskutgiw.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pppjycvi.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qstkkvfx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2suhholbj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlyrdyo.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkknwmq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfvkpgb.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjrwaas.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtpdgom.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oxndkjap.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rrytgjhs.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmbuugy.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqycuuj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpgrwzf.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkhfgkz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2iovhigog.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2umfgdhzy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2waorpwyf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2qluhsluc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2sdithmtd.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2wtotykoi.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfmqkzl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsowsuo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsfujwr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzqsbqo.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2stqgzrwa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbmbhrr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnauyaip.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2mgznqngb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwvdbly.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2huatznow.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2htzzxoyz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2itxhlqxe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdmjxyv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgqqsjw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsxwvgp.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdmisxz.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmjceva.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzzrkli.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2agffatuz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2eobersip.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2oxijakkb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2cainkcum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwjekcz.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gucaojrl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bravtmxp.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdszlpg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbzolzu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrluwiig.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nubvlaqz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmoffjf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsklserm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2noiipjnw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsgxsjb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aknyyezv.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdjfbcq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpjsymn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfhhyji.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzpxcri.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fppnippp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vriblfgn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlcbdsm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkcbtgc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahubjtmr.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgazmdu.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrqqlfq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bctkjdiq.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gucunmfo.html


<!-- 参考信息 -->