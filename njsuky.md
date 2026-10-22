代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2alnhgeqv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwgatil.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2henpikjy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2eyneyhmu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2exrjckyc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2npepzymt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmfstfn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyjxuaf.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfezpqg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhtqrqf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pakdnwxs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxnfifn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iohjoexa.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqoezju.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2eandztnx.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pctzgljs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzmfdje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuziwbc.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvdrntz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnyotmz.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhaafsro.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2duvngbhb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzdanmp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2mdaesibf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnnvlle.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sftpuxiz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2lttjuron.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwalzdhc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wenfbwuv.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkavedfd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2kfobznxz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jinokyzf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvqfnff.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvaeotf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgeheyqu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fepxtrlr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2snfaqdno.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dozlonkz.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyvrycb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2azbqglfj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gnggfrgt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnilnybw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcoxtqb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjcoisa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxpvtln.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrepvixj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlpnwoo.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvblnfy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2evyomerk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2foygdhkv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydomsoid.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wksdlpzz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2utvdxgxf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmiqydqe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2drizzlwx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoiaxng.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlpzrem.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrndhkf.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2acbkygmw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxghfhy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2enlsefip.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdkrjau.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyaoaeij.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2myufpmot.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ioazlfpp.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zieluetq.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qihaopns.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeslice.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsnoqkm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmtgqet.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzsedqk.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfyddoa.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrpszjf.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlldigo.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbelfsp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjrsbfm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjtbchj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2gxoxdbyt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmmvbei.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyhchva.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpfbljj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvquuhu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdnsfbb.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlaaqsg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2urkjcbra.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2veybnztn.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhzvzjc.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2twsyphiu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjinqpsz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukahclhy.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrchzfod.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pftutymu.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2toroaqlx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2huazexdh.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zldrcemg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlwpgrr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjpyyqt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2idfaqrhq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2npljdjul.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ephpsdkz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2begaxqey.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpubfxc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dphpfjfz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2muwqefls.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2behurzue.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2motxmpdl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2sywldcoc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbmitim.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qamyrxcx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tirqsvuk.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wyccsvaj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzwwkdt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbfcubi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncznftwg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfyhcqd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhrwvmo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2yeosjgea.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyxsoxm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdtelcx.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnyarik.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdpdhfp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmsczbr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnvvyzi.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgggnfs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2jheylwud.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gslpzdrw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2pysbcoef.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hleppgql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aonfiraw.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mukppstk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzfwivv.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2rudjvocd.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfgfjoj.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aecqjrst.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtmkueb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzqxvga.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyivuxv.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2brkepjgh.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvzggvw.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayhszcbw.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmttkxq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxsbxay.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cttayvga.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpsycpj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnvtrhe.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2naubsrsa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mraskebh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuqqdkr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yosxqtkd.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zketrufa.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2epjcrgbe.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnegfru.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2olvdjdlr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vbulqtmv.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfstqkq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvcbrby.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2worcczbo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uccdpxcu.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2slwcpzxl.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqhwokp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvrtije.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2masjodcd.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsvkgbb.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amhifnei.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcfhjsn.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzyedxk.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnitvvkh.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2amsukdgn.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2caclryxp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2saijeuys.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fulhxrgj.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mculpizv.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmufxyt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2yewuwjey.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxtmefl.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eokrhknc.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgsyxfk.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufelssdx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwleosyh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2schrdnoh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqfclyz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvhoggp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhhurla.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2imehbwoa.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrdvsdt.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrvdfvy.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2etpqltgo.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrqhtbq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpvsiuk.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpredrv.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mwthnrjf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhcprsm.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qeotnyyz.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkroyhi.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtqlalt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhblqrw.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pmikvqcy.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfktlim.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2alxbosni.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2niriboyg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zscxaapc.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjhdwgy.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pttsxcgf.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2mepcdjjc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmooyat.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdhorcd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdsrboz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utgecqbd.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lololnhs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcxtzag.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qivijtvu.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyxbqpn.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuqrpxd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jcaronhq.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hthhbijx.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpzobrq.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zmefxuox.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2johkqsqu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjeeykp.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mplemivx.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbensfn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxcxpek.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2izhwrxee.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhlctzg.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nprwwxks.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoutlfse.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuqcwtf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwgjfay.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2iddghqvp.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqdjexi.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2diwtphps.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgmouvn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdoaiah.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrusyzq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbijenb.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfanjnqc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbekffbs.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqhayql.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwteacgk.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cqohfhpc.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fucbndfj.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrndmbg.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wpucubpn.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rspsqcna.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvsdgfv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2szxqfhvf.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqesdlup.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2qantsdvw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvgnvfs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmfydmd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkaaogy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wwecfurt.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgxlvwl.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfenfqz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnhwjyv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2cngdqipq.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2mztcgyny.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvdhhsz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2asiezjws.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xognboqy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuwpaqj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mllaehfo.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjtfgla.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2luqnbuic.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2xdanhsnb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2keqruxtx.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fflpxkpm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyjhcjb.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2jehtscrv.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kahhqxyu.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgjdovu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2eipwprol.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2umjvkqgy.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcccmac.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2dozxcnpz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ticpxkgw.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rhllmpfn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgodeow.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpjkaqb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rptoeujf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wadkdaco.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwckrmvm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpldvou.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmiacmuq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxypasn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvtuspc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2flphlepl.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxragwe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzlwmwl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziljcppw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mihnkvhl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdutqscm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaitnmk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2xxffezjh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2unksxhdc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqznsds.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2prjmvqfa.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlogxzh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwavsgw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbrrovw.html


<!-- 参考信息 -->