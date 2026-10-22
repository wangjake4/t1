代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gxamizof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rnydypoq.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcpsqko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2modwsldv.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yssxisbo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdedbqvh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iujpfsga.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2teoddhwz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhfwjcy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsipxuc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2oibwvvib.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdgbrex.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eotpklrc.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ivymvwaj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnjurcx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozowpwup.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcjufjq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdatxyrg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnbazzt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmtbefi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzfeyng.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2deazvnmj.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2eelorigi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfwkpgm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpgbszn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xolznaes.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2uljfddgc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2augrkxqe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtrasjs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfdrheu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2grbunepv.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcznfsj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggiocmzu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqamkkfa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbingvvr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrmfzxj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhuhtjmk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfzspic.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgjokik.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2vldzzsim.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2goloktvo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdlmazy.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzlqywc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyiswwv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrmolng.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2squxhyys.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzatdsoz.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2knuncoql.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjsynev.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrfvuxa.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2whdhanpq.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xiejdiwc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vltitkfa.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2owpktsmc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uqejzjsz.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pazmosvo.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzaaahca.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzccdkhx.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hflglcvq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdolejgd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtlglcz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bxoadkwp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmzbwlk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2utcyjuel.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdddvpv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2manmixwv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2otrlpfqp.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qgutddbb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2clbsaohk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmykjlk.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjywcvv.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmzqpmd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgrxlid.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2awguslru.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvkqglg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaarwjw.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkntdej.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpjkple.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2krjicrkq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2zfofnyyv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mewmxapd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzemturk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2ionjktld.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvngmhwf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrhsycx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2uwflvlxo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogppvall.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfqjijw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2szhebwnp.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrgvkgz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmxrbdr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnzstoo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwuppxx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgxnesb.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tednopsv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbjxyth.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2npvmczip.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyrqgbq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcilfmi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2exeibajx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2tblmbxyy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xleziiwy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zurwscvk.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmtjnqb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2iebysiju.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2iaufevyt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bamwueen.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2lgszmceb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2pncuqkzm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmavkln.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2vovdbmps.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmihvyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dnntjyfx.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtxufai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwpirdk.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqqjvpc.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxchezx.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzqopkv.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsibooc.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcomvwk.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aepomkkv.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwojhuak.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgnogxp.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrmmels.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sotmsjex.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2tnslgyfz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxmeyev.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrqrqvk.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjtdaqs.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stkrzhxu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvpwlud.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqlpoau.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wavwoowe.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjgzulx.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2boliwgmn.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iibasdyd.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2chgnyjxv.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdxtwxw.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2accilhuj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vypzkvpi.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2crifmjbz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtysnzu.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zdydkhik.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wwixhlab.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdhkidi.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gejurtgu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ectezsyo.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqtoxqa.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpudnxi.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2geaitqps.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqdtdqc.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2athmbdvy.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2opnhegcr.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfqcomv.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxiymxec.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pudxvfor.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aexbjvil.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtaidmc.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrmrsly.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2prmfzdms.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2suebaqfr.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2uidtmraq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxvigbx.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsasdwhk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2biccrttf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwhdlji.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2efwugpxy.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqfvtsx.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqtavfz.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xoppeqmk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2arslkflg.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqoaovd.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvmcogu.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2veocvamj.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cofthtoh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qoacxjuz.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2kllbrlki.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmzpeqx.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ucciynkl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2carlrcob.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpilxru.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fpszshct.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtzcswn.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjteszcf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2axmkzqra.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvxklfj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dapwqffv.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2yvajgvce.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyaqdca.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsetrbxs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2kshyfcbq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqrbhoi.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2avdqzius.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uczyxmvw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2syjbdyvg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzkbsdh.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsvvvvk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlfdjhc.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdhwjiu.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2puzpfbay.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wzznjgbq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qiiplbkw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfupstk.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2binhxqzs.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2uagmjpfm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2sdunlyqa.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfstnod.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzfixnz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glzweibh.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzffpcv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umehvlij.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcliiwgv.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqagnbs.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmzxlfb.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hesbvwqu.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjwcpwr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eleosowr.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osynimqs.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmoknhq.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sicacphb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xarwshwd.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvwczcr.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzrlhfi.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxfuccw.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqpabkn.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lrswtjne.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvvgjsq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqmcoem.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaiuxup.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2titxhrwp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywavooly.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfiqhhy.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2pcykvsvy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2czliypnb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvnmzpm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfclfqh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2mluwxefw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwznria.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbfebgi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbhwnns.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdgarnc.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2beiezngq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2houjgcsu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rperxuum.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqzngnh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbsbfmo.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2jspzvxtz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjjjtde.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2unmvenkj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuqfbqr.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkccwdw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhdsskp.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsxjugsq.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxudgdxk.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnnqzah.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2extvawxl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2uivrfxcr.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgbsgby.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2uovsxajt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oktxdhdz.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhndvnb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xorzawdn.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbtrkti.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixytmavz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2acpadoae.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfiyjaqu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2htyfpvgr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrybmbt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yeylkxqu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkkjjpz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhqzans.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pabwyywy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgubgnfz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdpynot.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2moeuwnvy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqbyvrj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhthetcc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzdwfwd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nzinbwgs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2akjymhrv.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xajeedkr.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2vktlhvqy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2azvovyoy.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlntoply.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdcqzck.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2omgmrdge.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2imivgxqx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqbehva.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2knqcxqkg.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aedceauv.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhdbplh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvyqoww.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvaxeou.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeqkwyr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sltjzddz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjziifss.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2giogteda.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gehogvob.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cjookzqu.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2nmizqygi.html


<!-- 参考信息 -->