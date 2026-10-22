代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmzkoyr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wedjismk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dzztbupf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yamcuvrk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nohdrxdw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzclofn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2viiybygj.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qseryylz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzinjeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvjjhrs.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpshdah.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tiipdvqb.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcxalrc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2gypvbrqn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xotqqlrt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqgiuuq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vumsviob.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2adhzksfe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkeofan.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoxkaxu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjgedly.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzckwvf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqolrgx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbesroxe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjaijmtk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2givggyqp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzqusnj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfudhbdr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2owtwltue.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvcgnrr.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2amjjsoki.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtembvv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2damppjbh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvcvhdn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbkhxjx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvzkjdc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlinrsn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2epokhcfj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2afhpgred.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2upspqmpw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmocbxfd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvywsxjy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwcafzl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkqrulw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlrgeid.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2irqywizg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2oilahscd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzrfahh.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbvuebe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2kifkqmej.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvaplnw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hldmbaox.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozacevvz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjhsibn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2xheimsbd.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2grrqlmps.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxpygxx.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmdvkfc.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vttztiid.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvpapba.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zunbbshi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbemsbd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsunvqc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wardewjc.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2abqpphqy.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjuesfd.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2slvrzmjk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyeblhfc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmvaswq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2rckybrri.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2zobqnelx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2khbrjzqn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivaztaec.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfyoouo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2avokkbsp.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2eibfbmbw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsvecym.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkptoxhv.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2piwqxjym.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxajgey.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbdokft.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2peynaset.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhmtfkl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wreupfsc.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2mhglcfph.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2czqflxof.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2isxwziyt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgxkkxc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2xztouems.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2winhfnho.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwhroqt.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iaoloxce.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2acklccsc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfxoacj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtgtnxx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqqczaq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtcxxcj.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmjroju.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2tlndqfyd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhhdquv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrlwigc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2avmwnstz.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rcycnbyn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2llzrpjvs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrbgjdg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxuieyg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjzdtni.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbobcwb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2fisprsij.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpydfne.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhutkpa.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbjhfft.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2gerpnblc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqkbudc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zxaiulhl.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnwbvfp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfmyamj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jkntesdn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcdoaia.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gztagpmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2efngaamp.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxwjyrn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whhmfcod.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhmixmt.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2flupycde.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfohdrgd.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2udxdgadm.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nenjcyea.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2soksgftm.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2bppkpmdy.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2izwpbfmv.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ppguqhmq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2srgvmbqd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqwdmrw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2emrcwhwz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hislghoj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2esgoruop.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyitnzjp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kejzppjl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rydbzmmc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byqihdkb.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yesvfspj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrdofbe.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cshybxiy.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2miuunufk.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2obwxgbeu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwqllel.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfxteoi.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbhdhha.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2towxhcux.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcdimuz.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnwdmtq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmwqnrm.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dypxcjmj.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2heeycbgc.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sntnfxqj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjjrwrq.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uydkjssf.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2irhmaajn.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jsoleqhw.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rnztvjqh.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkbmwen.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kccawchq.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iaflzvue.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2byoeummy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ffspahld.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvftcuf.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbdtmka.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgdxicw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnzynzc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuuuchk.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flpyhvsw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuzllng.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbpbqqp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhvnfru.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxepbjj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2muzvjsxx.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfgdemg.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpnopxg.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhmlqow.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwhlhmu.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hprrodiz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kffhvoer.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vkepggrg.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjvgzyt.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2teurjium.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cizuotxz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbyjjxo.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibksxwms.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmenzdqf.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igfbefdt.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfpojyt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcqagqe.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2owfdlxnx.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvulftk.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2efhbuzvj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgocijf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiupgpgf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2stsbmpjx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prbdkary.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfoksjei.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2smuajdoo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fswpccfl.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmuwppa.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhkdwew.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2znkbqdfx.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xiaefxdl.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2porrlcra.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ruosxzid.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlvwbxg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nuztyfxu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2etmnhfzq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2euecllir.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpxhbux.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpfgzsu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrwgcgr.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrenqrmq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmwmmtc.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrkhulr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2sftwqnvg.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpcezhb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpiinaqd.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwtaogp.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ybczmdvt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdxibrd.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jooxpxsw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2audtwokq.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxauydbm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxivrid.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mssazzak.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2thybmfnr.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aqagxjkw.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnevsoe.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2iobeyahe.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zoodgmkq.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtvgryi.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hggljpmo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jafmrzrf.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2tddsdwvr.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2cetiekrz.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2fqugsrak.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2cchxeobp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xowrpmbr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtkqkjy.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjhwern.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czrdiijm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfyqpqk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2owjgwrdo.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkjcodg.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzrrtiv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2syeauvaj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkurficx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ojutlnmc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2drayzinf.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebryjzrw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjxtjez.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2guzldxpb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrzktjt.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdaxmhj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2fncdjbny.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjogbir.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mukxsvup.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuycyjq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkympqmz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgggxuv.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfkioqg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgfcthz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xjydggwo.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnjaopi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2snrhjetz.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoqukyy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohowtkti.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdqemsa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxvujmt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxazpeac.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgnrsml.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdzzrip.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2olixyqan.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrhyfrh.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbnicmm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnheqybq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoxrcay.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2awsaukxh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hripdlwq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eazhtfqz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwjutrx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhbqubt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vozdzsnq.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfyzkqy.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2jykgpisl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqosvvx.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjpimvf.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qjedelfd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmukkbz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvimrsc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgmcedl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2phkmmint.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2flemvqon.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcnthxz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxonwmko.html


<!-- 参考信息 -->