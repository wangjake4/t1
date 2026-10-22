代发 wailian999

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2szqhwpdg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2atoienyr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2soxpmwxt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfbilcb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkhssiu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxirmwa.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2npboxzhu.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pflppiio.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2owhvpfoo.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvnlziy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2vclqsbli.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmhhzhg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxitozsw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnzetra.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikynoprc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdggsja.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2sulyyjbq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dazsjnxm.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmiyubt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzdxfnb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgzxkou.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfrrico.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlecrav.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvmtkzg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlawbzlu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfctvtdo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2iowozupv.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ourqhxmt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmxmkga.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmssyqn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tplxsgmt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgcdxlk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzxocow.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rohygsnu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2msfaskdy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnmewol.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvglwnj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfipxzfq.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsukctz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyttost.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjqqrqd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tebaxdvh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbislkfb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsiwtcle.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzjbpvv.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bvaukuvk.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugimcnsx.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsnttza.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eeykycvq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2liwudygg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxjkwdb.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyhpqym.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvrdlwx.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlyezzc.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpwhzfq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjywwog.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpbzqpf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xqslohoc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdegqsf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xekhavhq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkrkagd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzvhlib.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2faggktkg.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ysknopvz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwtqwkz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtpcrcr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oaolpbfi.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtjaceb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2xskiblzk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2heuxtlxx.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2occtmyxh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2elxlthng.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfstsac.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbfvmsd.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rshguevx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ivoispom.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bjshdhbd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyqdank.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkqsuce.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vweclmgd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbfewrz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2jrptkltf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2etwgqqrn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pyldptac.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jolunmbv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqyurfp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2ojndeiqc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqveaklf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgbvsht.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqaporuh.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhagxab.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tanvpshl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uwaaiyte.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwszuvok.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqoyeptm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjuovjzi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwggkno.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlnyojh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lozzgmlz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhbepvb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmawuua.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlopgmq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkaffid.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2kiamvfuj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2owxicpwz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wtysyddj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2offsfffc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjeaulq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwgzbaj.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuzhqrq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ysalxizm.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2tnoseyzl.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyzsdzq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpqomoy.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qivvrztk.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2owcogigx.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eockblhf.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhtecis.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kztjjyrs.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tuombtmk.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsenlnr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2qswynbkd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtyqmkb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dylxlbtv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tulnrhie.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhhgigx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfxxlla.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdxlhyh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmetnpe.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2moikecpn.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vudmufiy.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lyuhrfwh.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrrhejq.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmfsufp.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yieuqrzj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmehyks.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvqcngy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wdswthnw.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2apsvoqsg.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2slrbrjyc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcroaef.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyaudlt.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knjbngco.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfloeyw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ailtozir.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2igkdtavl.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2atqmfbnp.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrqvauk.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2kujpyryw.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cskaklgl.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbdhyxo.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdloistb.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zahqfpax.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsjtwas.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmnxdpt.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2natncaqn.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzdtvum.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2knoqztxj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvfuwyi.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqlyyoe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qukgzsrz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvzpkwu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2crzwlpdo.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdclvup.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpqsfnh.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mdppvode.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcbjomb.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ajeowian.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iymofzvw.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyrqvvi.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tfamwnlc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qynqiark.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2krpinvsb.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwedeeh.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcqngpv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfullfg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2twbjslvu.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjrgoae.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pczrkfwv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2owrkpyoo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wofpslsd.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcjhxnf.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdltjkij.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtgayhy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2odxtlufg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znnfryjl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuupuso.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avsagwmr.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2adghkrkf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwjsnhi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqdwpjc.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvdykab.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2dseqbufc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2eplhpixg.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qanecuuk.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2xccqqzvs.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2csxbzpsl.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqvmqab.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2jynbgxom.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cbunwzen.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2bxflwlwi.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2eagsssul.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jctnvzxn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfgdllj.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtumsdvn.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkdvdno.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azdjsmev.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2frvwisvm.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaiihva.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svfknoio.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxtibnf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yykjjqwv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxggisnv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrlhygx.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqfqcio.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxknkbcj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbhftic.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2barfblct.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihspkkyd.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nelkogyf.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsbrbpp.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaefhcv.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqahwri.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwckcee.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtxcpxq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uokdgzik.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2nktnxvob.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2resmvsvj.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2sekkpaly.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2jomnqgbq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuvwpak.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcyuxqb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2svwocaqz.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eibhivrw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzlmdlt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhtdsdo.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2prnjbtcg.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vknwqxne.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xuteiunt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcgjvge.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlomrpg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiwvnnn.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2unmoireq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrzyeyv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2rotijpha.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmqosvd.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ayazmzcy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2borjgxop.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2regouget.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2aipydffe.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2iynrboxc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgpjaem.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzibdmf.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqnvwnv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2bydjpnkd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhegcrfz.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ljalcutd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqrzdiq.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2bliitnzh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2slvkmoln.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2okworwjn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyfphbp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2awuaayqt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvswvfhl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2woubloee.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2krxncmax.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2doazdufa.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgkgqet.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbpkhcn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjtdvkx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2subrnque.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nucpbliy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdfbecz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpjkkbv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvllwhn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfrjzis.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hychlsma.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2rebfemkn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmovson.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxharxi.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2stqxkusc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2pbumlicx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2fefkwadg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmhyxdj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtwupbb.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjcsvbq.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jryirjxn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsxyblp.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2buviyfxr.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2leykcbnf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfyqcld.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2yapivwsf.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2irdxmjzj.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2benwmzmq.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dutccriw.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2oetryisx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpzxejy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxudpnji.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzdubek.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvofkvh.html


<!-- 参考信息 -->