代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ovphymmh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlhpqkt.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzunone.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pokrsvot.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2komcqlvf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2suskwihs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwltddu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrpdoss.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nylxnxkt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ngiayxyq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2hutiwngo.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hehbpgqk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhrhnad.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjamwiea.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvnyokk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2coffkatc.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqgcorm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dehcginq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2pubrpmyz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgajkum.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2irvdxzcg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmezyyrt.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2onplhodq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvvpihe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2noqzbamt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nehyyvli.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkfuxpq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2eesaaxhh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdvuheb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xewrcdqz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2winfelle.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qguwdonb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2csnpfzzf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmtzizm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nctbwnxl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kejgrayi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrkzhqr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhagggwo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2csyxvmxg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrdplsk.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gburognu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2inhrzjhu.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqpeotk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ciflonwa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlhmrfa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzxepyu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjkmwaz.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqbrjtz.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkqhusc.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbfqbpm.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxquywgq.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvshkjk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtreeqh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tapqzzdm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cnktqbss.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjfmqkp.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yicjfgja.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sflikrim.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yukroufa.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrdrmeq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fagfannj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ztimptpg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmnwmnb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gcppfcay.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2hggwomgh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2izmffohw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2gnodbgjg.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2njsrpztf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2thsgllnz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnrjmks.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yganebub.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oattnupn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqzipes.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyvvuaf.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbrpjgk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhsyrfr.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2shbsnnlg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqayfwq.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tepcwbzt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2adrxkbth.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2uanvissn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tulmmecu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmxpbps.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwprwlj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nonyxkey.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2vwonjxof.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2prtqlzvd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2whddfxdp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhnekau.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywygtcmb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcgockm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nofozlgw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdznyzgh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrbwpqw.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxicndz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2imwvjpuh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqmayiy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppawgkzp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2crbzixsw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vylvnbqc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2egglzkem.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zniyddud.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2andxkvbn.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mztbcbcy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrfqndj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoueeot.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2agerxxyj.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2srahraay.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrmurzc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxsfrox.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkxqygb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2arhvoorm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpxaguk.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ifenysuh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2outcrzxw.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcujksh.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2sphtixbz.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcqfmoc.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhnylrl.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpllbaj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzisvmfv.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlewsao.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yjysjovt.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoawnar.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cumdhlod.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfcfxhe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2syvxbwvz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnluvfy.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbdqmik.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adpbycsj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bymbeblo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fzciiluv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfbpsro.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jeulfrly.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvtiiav.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rykjkgai.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxykqux.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvfosys.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpnfazb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2uitmivlb.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwvfpqy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jdabqvkc.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzioxia.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ritstcgi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhqbltr.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jywmjpch.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqygbcvx.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdjxypv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2aubqwseq.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nxivrcvw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ildzekfu.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ifszibin.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfmqjti.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hggiqqdf.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hougxqsn.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iednxbsg.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdgnkjj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxostvi.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tfobuwjr.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdspiqco.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2niqosihe.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrgxapy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpddrbdx.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjopjxv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyijgtdw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fomxxilf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzvrsmv.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrhdlud.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnpejro.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2puzbvkpq.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2dskfjogj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2likbpbxd.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ouectsvr.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tcacqqrj.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcbdgej.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcmpsmr.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ygeefbko.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bplbuvtu.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2prmakjxk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2woumcmzm.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvnywwt.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsxyweb.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2boviytbc.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkambdr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2byycbfub.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvabljr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2leuvfsnc.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqxyvmz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2opijxaei.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtcoxlq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qksqevdu.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnmkhrm.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgfokyc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuybxhw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdpkjjv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouninsve.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzyrhur.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivngvkhl.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2snupdlnv.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2mumcafoy.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdtxvkx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2erljxbat.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ekynhfxp.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcdpoej.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnrmtnb.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2pcczwbez.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2xatljxrh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xafgwyac.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmidfcmv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuoaxrrj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okdsvmfc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxscejib.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ankcnirv.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfthnhyk.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oecdjvpg.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwjqthi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqhticp.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fglzyzyi.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhlcnqs.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqgsasm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ystzbsgr.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnwjrup.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcxdwpr.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnyffwd.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qovivdsa.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqkuxpa.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdkeqsu.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrhipli.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kymiksdr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrspsda.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2amljiezc.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2freexxqq.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpjjwgy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2apmjgkuz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2epgzijts.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2cgimnhvl.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwdyyvq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnnvqzn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrwbuwe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxbypda.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2biktbirn.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rooknoho.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhbjath.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwnoixl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2vcibaezc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2voqdqjim.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2mepgdess.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2zggzcaax.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2iejyokvx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhyeanz.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlbkrui.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2vmshpanx.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2maklumew.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wybbnnxo.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oggcrhkb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhnfqmb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfrtaxm.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2gvznbtqv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqlxohe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kylgodez.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jcoxfevo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiqfkbu.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2iqesanlu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxynxpqu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nirxfppy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gldeuvrc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dftiayrk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbcxqmc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vubqjuxz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2suhsvyif.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2attrfefy.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2loevlblg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjcuilb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wabkhcti.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uagcdfvi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2leoszfuz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2plecduqx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyybort.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnispcw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zveteogw.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eucgllya.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxppkbjx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2eaeoybfk.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpjqmrl.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2obbuipkr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tmffvsbj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2iduzpuon.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2iomyqikv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2exshwaoi.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2actmcsoj.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwwuajy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbieqaz.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yflhzouq.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sanbgjgi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agwotdhp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvikujsx.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsucffv.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfybqdu.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmqafkr.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2femowlkw.html


<!-- 参考信息 -->