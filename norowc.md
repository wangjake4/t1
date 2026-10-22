代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfdqpcc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfefjumy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcgsfzp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wswhiuix.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtiyzvg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2idaktrry.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2obugzlop.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbeifjl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnxjxld.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqkwgwm.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcasmhu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsyrbuy.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnzhezi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2nehrssjt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2itscxfdp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2hfingsih.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2powdatdh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdkexlc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2oedmiodf.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2amxeprkx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcwcqmf.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwayqbv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwdlgbr.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrxkaez.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vymmuben.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgezprvx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gblpkdug.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtkanic.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdynasy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzraqja.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2kosmxzua.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwrlkov.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ittqfnmm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2scymbjxd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2yixpqbla.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrzoacu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhuxefp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nukegrin.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzkxpvv.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsijqzs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmirzdj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmbogak.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxevjsor.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2flztrbzz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlmowvo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdaytnol.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqitqwc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjpcllq.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlacbay.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2bouwsyrf.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oohdzxqd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lectsvss.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aagggkou.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2imxaugeo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhoarwat.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuglpdh.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlikwmvx.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlhajjb.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2micykkhe.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xilpwsfz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxjoigl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2upidnrla.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dhglqfuc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhitmsiq.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzymrqvb.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zylnezsg.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyirsdc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzngtjxs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbotbsgg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2weccmocn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ilryxbhz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2chwwkduk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgenelw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcifqgb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2armqyrln.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfeftbq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2oltiddwm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zagpcobu.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbmoswb.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2afnplmge.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2muqqgyve.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hholakrk.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqzrkoe.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jizafnuw.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfhzyty.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuipfxwx.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2phmqwwhz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvtvpbu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yaiiguri.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbedrhg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwvshwd.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjpdjjr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbwolfz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ictwqxmj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtnvjuxk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwdtplw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uduqjmih.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrcitku.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2hynyotcf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxuyrot.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qleixwzc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2srngdphg.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lhooyjrs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2suqqlapi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zdegredu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvdjhyw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nflsxear.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wprthdfj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2vwossilx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kscaiicw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lunpatlc.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcizjlf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqurxxp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2aiosofqs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gceykeok.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyxloxv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2grirqfoj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrggwxo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkdxnpb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjmcotc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpgxxdf.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wckwydvy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2veydtynh.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhohfmp.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzmmtwx.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjwbssz.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rggamtmx.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgoriozh.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xivxmqfl.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkthmsh.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2flcvgutx.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnijqcou.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvdxcpv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqjpkmg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ungiyzub.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvtedhc.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2madrtphd.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhooaqvi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjlctue.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhzhvlf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpogdxi.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjhmame.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbejzuf.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2csblyupd.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnsjrxn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2scsrgbtt.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqcmcfh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvxpzwl.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfzheja.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2inmvblxb.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yuywhjou.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcvsgsw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpqszxs.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsbunwm.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnhdgsg.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzpsigz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbsuwey.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2daldnbsc.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uswqkhzr.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ekizsybw.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwzuxel.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqptkti.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hertefub.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bygdwiby.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zswytncv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wnausfsh.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dohculbb.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpiaupz.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ryumkdoj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2onbroskh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdiycqd.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnaiuxa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrekljq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrezoqc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2ngemztth.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vphimogh.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmsnhgy.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmtwafj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqrfjme.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pattcjxl.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtbqolm.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ubktumci.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2juhkberx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlppzxq.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2aumeisep.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jioocrdi.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rolbwgpq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfooclp.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhhnmom.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2osxfqaqn.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrusmdaf.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efwhhskg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2elyswsac.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qaonqlml.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzupfxvi.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpbtknu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2xaooisnd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhreqhpm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvddmad.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzaghyjl.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjflvzm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbtqjsf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvbnroa.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2luzbfcjq.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2htjvkwdl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2eiakbkfe.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cyshhswy.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2phsagmmp.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lydlluuf.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpwvhwl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2adnusqvs.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cmccdksn.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2thqyyrrh.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2nbriqtnt.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2hszxoiyq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkwyghb.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeoonsb.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vabxtkid.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xddkztmq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2itrxsryb.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2nagqqdll.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udeayfae.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwwezjb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fauprmwo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2filbpmms.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqjzjra.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzgycfs.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpdesur.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqoegem.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wimdncks.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqpzzqf.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrszxxh.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcavgtv.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzvzzyu.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2coqpnkla.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zxoknzzf.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iszirtkj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzemsbe.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yazfbtzu.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtbxtsy.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2webyxgfl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmhxnag.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2wdobvess.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxcahfe.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ioozudzt.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cekhnxnr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrpjcsw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgchjjf.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xffumzko.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtbouzx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyvnzjs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvfaphp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2abpjvrfm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vapmyxdk.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2iueepjqz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjckysl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmgutgt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlrfnfr.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrntlgo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2xogokkhf.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqttgho.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xscrkred.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jphfnjoa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgfnpak.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gnomjxjx.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2jteyaszo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkkjxis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qntxdnls.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqahune.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igqdampw.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2emojyrqu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2hopaesdj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpacqgpr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eydyqmjd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oogxxptp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjwktwh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vajxcovm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbfxsll.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqofcxwr.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ttowmzvg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxorxgx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwwxvrn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxednvwt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2knjswdhu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmratxek.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2eooeeudn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2evfnmiti.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgjewkw.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uyipcwla.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrfwrwk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2atsfwxjj.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpyebup.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tejwjdhc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvpejqr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldetekij.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2ravimcsz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjzjnln.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzuzsmj.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2eerlnqpd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrckfzym.html


<!-- 参考信息 -->