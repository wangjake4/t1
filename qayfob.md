代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gaumgfsf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpcokxg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyhihky.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kwonmvcd.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpllisy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfvspot.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2padoiejc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xtksupfb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jranyibf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjybwlqb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnczwjgr.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2naexefam.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xnauyqpb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xfygeltp.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ougsyjpt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsfqzla.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvysqak.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdamzmpj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hotuitej.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhkrgvr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyherfy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbbwuna.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdekjrs.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sarkmvaq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2svoybimz.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2joofsode.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjvyzbh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpduucbn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykymlbqi.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrvqwxr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdliorh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqrjqdt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnfttdd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfogvivq.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxekzgkm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2isfclfvx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkscbqlr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2gatcoyjh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgtzifb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjgyked.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkskolbd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2oolwhjhb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqedokme.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmogdgil.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrnjhgh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvfvsiw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvqcsuw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2omyhzxgo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2jadxfdgc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyobpqm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqdswdl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvcekfk.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbejigl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcmjjyd.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xicljmlq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnrojnt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2emwugtxu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ixutamxi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbogvinj.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oauxefot.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2szglwuvg.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsdrtji.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqofgogy.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2acqpnmyw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjkpatf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhlcfdk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jioyvabn.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjgvnqk.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zozcadoi.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mgelqcgy.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2akqupbho.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuxknbu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2unkotyog.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgchtvg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsrmnbm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfvwmgl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqbxrec.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkhriia.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2neaqnhtr.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2arqhsrdd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qelrhgne.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieayvyar.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfcbmgl.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqsoddw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmubhte.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2znyiiblb.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvrmarx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhadgxgx.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqpijqb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hezdwolb.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkvnrac.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jhryvhda.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfvmwlt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqqtqev.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2rleonjhh.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpnsoyd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhmkpqr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2oezvxfct.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwursmtu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zolyfbik.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gawwoxwc.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkbwbey.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2nlblwibs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxonagj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtxjhie.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjehdoio.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqccugfg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnbyeou.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrqbqdn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhipbue.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xajwczdr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajceiwav.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaghmuf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eatycpqb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zruvalzc.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaoroym.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2zggevffw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qygtrvql.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmdgwam.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2yawfltkf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwndjoo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bolzfskf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2joahhnnx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbqbhpx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvwatls.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmefmcm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnpqxrs.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxxlazv.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqukvhk.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjufypgs.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gczsibiz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igfnuhkg.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtohnhkd.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcajdky.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhztuxq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqmloyi.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtpjbtd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbcbgzu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmvyusc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmpndtv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwegkox.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxaquorz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrcqyzm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vajkyljj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgdlraj.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2duhiaxyr.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2frzgzbfk.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqkvmnk.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2czhsqgpj.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2suptrndc.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2otypqocy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wfeqpjbc.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtitosow.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lchimghq.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2atrdgawx.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2duetfrxw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2haqohkug.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flttqzuz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfcsyju.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrczeodi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlznccfa.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyfvnpw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjatbccj.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2rikfvtad.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtenyzh.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvjovza.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vsodnsai.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzloflss.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlxexmj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2myhxxlcs.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2phucwcbu.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuesjuy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ktozqoco.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsfupkm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrxklla.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgrbjcc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhxkgav.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ianvxlkw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsabckv.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uekgwxxr.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhztiug.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsqdsvp.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2qluyrnul.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgqedrj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rggvgwqv.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ekahcxwy.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yuliubgj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cmiqfdvm.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2cprajfjk.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyucvoj.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdtvkva.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2woyjfmoh.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tynyvvks.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzkjgnm.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izeqcitr.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmdlvov.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfpnagc.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgdygkd.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgffxotc.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2vivqmdeo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2rubthzwg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evgjhsry.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2dqiazxox.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wallspct.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpgysai.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsdvqgp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyuapqy.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvcjwlv.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2oijvajqj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtymmov.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlpwkyo.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2umbwtjac.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjqooqp.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnpjclx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjbawcn.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wluhqbfv.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcesvoi.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2grqxdouo.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqndppe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgfccxn.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzvedad.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yawjxywx.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkicytuh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgxbomm.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbjyqqi.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxdlhtx.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xojtryyw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2koetunvy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgifusw.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgkabgk.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cukavbuy.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcoukki.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvxawjg.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvbgxua.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyhdvgu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2smncacoy.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgngwje.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uygskeas.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxwpabi.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2quuailuu.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mofmorjt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvqshvp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvngnnzq.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2zwojdewv.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2dilekcyp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2xgejscao.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2efwqxdny.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2pubryyww.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2qxiyefep.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyscqwx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2umqssslp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2uhumfzpe.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqiadwwv.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnppqmc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2auittdfj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcoegyp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcoewcw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdilmzj.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjfmyds.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgsccpg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxbrozx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlezhzfk.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2punoxlah.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2uyeouywf.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2dukgsgnu.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrplfkbp.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hldnmkbj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhenbklf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhrfrlf.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2magpntat.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2jaejgbng.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfeigon.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jvztkmjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdrgshp.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpwvust.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilahzhcm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxfhvkj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvqugsp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxsfrxd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsicobdg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuaquum.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gzalleuw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbnybun.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwlwswk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeeaekw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouktbciu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2saxkqojz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdanrkmv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrgjzlo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsswuke.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2winmbqpr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfruqug.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwvntww.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2jejzlibz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qisxmlks.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpnbjmp.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xykerhpp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjfqjtx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbormkv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2pynggirr.html


<!-- 参考信息 -->