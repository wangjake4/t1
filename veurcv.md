代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wczddnnb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kssnpdmi.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwifuas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cntafajr.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyjqijq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpzdyrs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lghxwqjx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2dvaakdey.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjizfhip.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dkykhase.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2omvbhptw.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgctsnju.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2erqbthbl.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zifttjsq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2hajvjzon.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbrjkeu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2srbtlyki.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oitxpgho.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhceiuk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jongdsig.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiobvxbm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pycomtrm.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2psnobuxk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfsyggs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2loiklwsn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcvptvr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxfqqot.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2eckwltbt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcuxurb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2upiltrfb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbwsqxo.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ancvvqwr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqbnclk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoktjft.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsauezkr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hixcfdsx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqizuzrn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqlczta.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmlitkm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpzkqoh.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eolvrvfd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbbzvnu.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlejgjcc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hadwcaqu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpbfujd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2txxnihpd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkalgkhx.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wivxmggz.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uadqnfhq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mptzlilf.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwnryvb.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxrhigh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqskyvpk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlboane.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jnttkvua.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2prmzlcss.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsurlbrp.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzpuffg.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2clyjxfzb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdvsyyo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pffhpick.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lvicamnh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2psqmkxtc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaysmza.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2auoiabha.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfsjxcy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgngrubi.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bkddihuz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqprieef.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkswnyfz.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2spnpqlrx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrinbau.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2qljuxmdh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkncmmj.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2spqxbujf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjimpcr.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrobsrx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2inalmbdq.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcohucl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2guszrakm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vehnyuzi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkjpqux.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhklljo.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nplqjqds.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bckwbdns.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyyxntj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdvrkkd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxmbnta.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2juloaadp.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkoidqjr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2jitfvttl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdqshtm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdageumb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvkbdxa.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2awqbzpaz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eddvtaov.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dswvdxfj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjbkqqq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrauymrf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2shdnctor.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2fycruzpw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkqjkvr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fppubkrz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvvatoq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jchaqugy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2momjwojf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtznxzc.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jjubrway.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2giujlvsz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzobkty.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2sruglbhs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2unvhsbxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsdlcrp.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rsftdbjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rujwrrws.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2omrpmkrp.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jppusnco.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qklbxqmw.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wilqaywh.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htzyzovp.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oofwskap.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2whckkvqy.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkqhrgd.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czcsdnol.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlietcp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnexkzx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yddzvhur.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtcjevi.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nixmzjfj.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwixwcb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgknyjh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2aprggigc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aimybgre.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvlmmkx.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2eyonqmje.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtbicis.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdbhwtb.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzjsbft.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxslzklh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bjoehcvh.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxlotxq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mcoizbyl.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxvwuwr.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yexwhnfv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grfgifez.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oioypevh.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnneriq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrwwnpg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggywriqz.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tjaujzca.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbxpray.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2icmjmvxr.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxwqatc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgfnoot.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxheyivd.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qcoupvzs.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjmkhzs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2upefhtvl.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbqjwds.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqabwljz.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2alulaktr.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2nikuiaio.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruycrqkr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzyomvr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgvuofw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azjollzb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2qepkbldq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qmugsdbl.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvgrayr.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcpsyfi.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2svtelieh.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2coekqgyh.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtpeyez.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeihsat.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnigfhm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2axkpxijr.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ikilgcwe.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gbreqnyo.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2frzwtseq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2spcstwxt.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqxjwud.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eilkkrfc.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyesvka.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnoxpya.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mynkbuqh.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvslyry.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzjlpkq.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjqrhvt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2krgmdysa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkcezrh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2pumvcrvq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeooxjse.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfjlbjm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrafjfk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gxofrygk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjaiqxcx.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xceqiicw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2eohkkoff.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qamdkjmk.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrgyimh.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cvujoijv.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2cokruzbg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2lkipbpai.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvmrhzi.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2vcaorfef.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpxnfmm.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dftqtxfh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcoutfc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbuclgm.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvaodzkb.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afuwhruh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bksopkwz.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfynzlz.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfrxfrr.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lshtagbp.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2afpaoedf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2broqpuzk.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gckaqkck.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swncfkat.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpfioge.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2izbvmiac.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pcflkxql.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlolpnig.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgxhlur.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2sipfwyfv.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mufgihup.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cvericdq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iygrlrmw.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjtdlvl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuukggv.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2knohzeml.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqoyben.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeurhfg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2cvoaocqv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbqzohc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2lapqddjo.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzwhciq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkvqhyl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrvxtng.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2aqifgmia.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2djzqaimi.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhzmcsp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gplbmypt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzaneiyh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2szvcentu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2feuyurvv.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2yflxtagd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkmsczt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2osaokpgx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2icocsccc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqpjxlb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdmynng.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2nruefiyp.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsorllc.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgohsosw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2pauxcpfu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jouxkrfp.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxylrry.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2sfixyfdf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbvtyjm.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2olajtsgr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zyltmyaw.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbcqvsn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpyxsyy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxxbcvk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qewbkjrm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jepfkogt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaadgpmg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuuyzfz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fxryskjk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwovtal.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxumqch.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfyynao.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2giyvdrvy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgisqgub.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxnocnc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjbxrvf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2vovnmbkt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fydqleuh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyiugupe.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjmtqdg.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2aybnkqiw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjpsoxs.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxatdri.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2chvubnzj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbvyguc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmedmoys.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfrmcfb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdokunlj.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bclmrjhd.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzrpmpm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lazaemlc.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imeenyko.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agbqywkz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aonmwvhu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfzfbfp.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2akedxdhw.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhjwvyd.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2npsyyaum.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2yykoupqs.html


<!-- 参考信息 -->