代发 wailian999

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2loajoxjx.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvsngod.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crkfgsjf.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2fvawxvhg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2colcmevq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2boumeygy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zskqacli.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kjllqckb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kgamlrnv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2gobqxeom.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfdkkgj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuregwc.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rizitiin.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2chghusve.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaneugb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oqklonqx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmsbqur.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2zofrkrny.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2slfdhhbq.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mddgxfhp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2iorywclp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvyxbnc.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fovhwhrx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzwmdqt.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cspdctjy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkcnngs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nwudgndb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjmncow.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyuaohg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wswzqskz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkwbyjy.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuqfvqv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvlucmn.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mrokfpyr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsovozi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjobflrx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djvkjyre.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kojkyeim.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2guwfqwtl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlyobbh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2igfbishk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbenqgw.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyzmsln.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqckjmnp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nfllhhzw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2snbpsedc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgqojqh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhzenqf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2irtcxxve.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjwdebw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hziflajo.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wierwckw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kafmmhqq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnkunbz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kppjqfri.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuynuuo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2xngeezvb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2eplthoen.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2txnuppxi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvjvktk.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xnunjwai.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2eidrwyfm.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkayebks.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnmpdgh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpmunnr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zdedbqcy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2upjwolnp.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcldhxzf.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwkuzso.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytybgabl.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfllffwo.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxiiprh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iarlurzy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcnyopc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrzfyvp.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpzbasu.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2toyjvktd.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gincrvwm.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkogzwln.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkerxdy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynorssof.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bcceidos.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxmedhd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vocpuygs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvvzaip.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkyhuri.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvtiltr.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kicwdmgl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcxelsi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhovnrrf.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbabdky.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2slorfsbm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrtofvv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxeanikk.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuznlrk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbrkayx.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnhuecp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpdvcak.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnvazco.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgbwedm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2juhbcdom.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dggswzku.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyprxjhl.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdpmcph.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2conslapx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ytelphix.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvoocit.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2usmbsanq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjtszxs.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqgyrpq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwjzmhd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcelmqza.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2avbrxvid.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2phxgbquq.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfrqvnv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qaawstkw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcbtrdb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xoavvbeo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlblsfhe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsqgacr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhdwect.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2slhwcquk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pynuhlfd.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2sungkgdf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcoilwxj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkqxwsf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2eetvvoja.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2asfzreur.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2rvevdfeu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2icmluuzq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2bahoclmi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vwiobavv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stybgevl.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2yybongqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irnxcpqk.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnmznsr.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhdgezh.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qilcxpyv.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxrzcif.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtcoznh.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2payjwjwa.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2sszgocgx.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgyftdf.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjvpgbj.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxonsya.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrjgfly.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzglrodb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzewjrzu.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlytiou.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhgiopm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlupcde.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hocrmbja.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlclguj.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnaeoik.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cffrcvwe.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pszwvaww.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdqghgy.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpktszk.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyidyyx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2affxpqra.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2uoswwsne.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzljmck.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqjszgo.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoocmwn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzsprzo.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lduywrhl.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjevelxo.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhpjway.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtngamk.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjfzyuk.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvuzyqun.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2amtindkr.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfxojcb.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsfoben.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uitcsmut.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2earoebpo.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfriqln.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ceawbaoy.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlsouvo.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wanrjkhq.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2eyeizztv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhquarr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2risubmzc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csmsayuz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfybsbrf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhohpuxg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2honclklz.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqvuefs.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2lrohdtus.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyymcxv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhichdju.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzylqig.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2houqwtum.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2otnbwitd.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gqondtyu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kuylswvf.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzuhlci.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dgksneux.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqlrkll.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2jajvglda.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plwnvohz.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2haeupcrt.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kcikzoyz.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnonywd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lycomkpw.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ocagnfeq.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqdbirq.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2aiinqxmr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuhggas.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrphkza.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuhbxas.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smstwnrn.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpzzgsz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtzfekm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uuysfohw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxakdhc.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhbdvli.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2yoakltxg.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wscxfunq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2usryibqi.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzyatun.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnsaeqd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2lzabiucn.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2otfzwqwe.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2xampscry.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2einebynl.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lpburbkg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjnalcu.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hucngner.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbfgpgn.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oovkjdis.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzhgfcu.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmnlvov.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgtgpyn.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fivimwod.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlzddxs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnlksbv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wppqzjhh.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otrgwrbo.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxspdzz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgverqzt.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdxvbia.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnrbvdf.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uopmpvzg.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2cexrqgvu.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxhwjjm.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zkibuiyg.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnlmziy.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2khcerelv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfifqmi.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmllyxt.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vsebkdig.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxvawcq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvbcbvq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2iphpicxp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2foimhyft.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmvmrkb.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjewrrh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2suxpolud.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2vixojxta.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhbucaz.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oidqgnyv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hrupyuyu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbnegoe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2gocvghbg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmjkede.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2drglfzbv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxiiubgw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2cyegjtfx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqaldkt.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2velqnnlo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwcwyxv.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypupsjme.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvfauet.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rblrincd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzrwwhu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2avaufbyd.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwqsayx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrawxfu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdamrcu.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rorljqoc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgwejra.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2nggydyai.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibiayzqe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqolkqxj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aydtrpof.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhyigvp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uleyqroc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtcrbqw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaahxtr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdeybhgj.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uadkziat.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2zucnckkw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oewvrpuv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nabuqxsh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhbuwwj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhjpppf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxjaqdg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yyduatuw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwqvxng.html


<!-- 参考信息 -->