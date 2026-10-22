代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjnkstp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vonajapz.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2poiivcgg.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2raewzqbm.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkqklaq.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2pczbynyw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpnmsqi.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfahvvb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqmnlgr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcgcnvk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lkftpjrf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqzonyk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2myegtrtp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwqylfe.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2urekxxwo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qaocrkmu.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnthviq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgaeggg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgcnxlb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kptmzfht.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhmtoxu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltheeqah.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2uictadco.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkcyhbw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2aenloklz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfecyoc.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wixdaody.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfongew.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsqcfnj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2sinwmvxf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbricom.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2eownulew.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkhzntt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmzgbuw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2jfggofst.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdzuilu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhyfhnb.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ibugbwlg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2xpozbnjp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kevhsnkz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbqsrww.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbnsybs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaeiuyn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhtahtc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvgkhwu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwulubdb.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2wapigvte.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2yizpfshk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mncezqlq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhzujng.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2iveoefcc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjhtcgk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2voefecef.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnwqlzu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvnmrjy.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2esofieeb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyeefqet.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyoatfk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2esgcrbci.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxssdutf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmqpoze.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdirlsdz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2smxgzcqz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2nraplhup.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2odqdykhb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqxfcqf.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2adtpmvon.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbogqodf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkeurlsw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wffrilpb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwxsorg.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2houoscjb.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqinlis.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjzyuzd.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyhcovb.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzhcelt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2flihhyvq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2omembxiv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ownrrpir.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvzbvbc.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2annfffnq.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmakrbmq.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2oowiyfit.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjihzlsd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcmuxau.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvszdbt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkzsnwc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2erluhbws.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2enupwgsc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrutfoa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2aakmczou.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjbhdgj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsklgnx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnmzens.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2spumpalh.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkmakeo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2suwhcnzs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2htggkfeo.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2klekdkjj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgcmklz.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2frucwmgx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2upefcphm.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2agkzajjx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjrtexx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbykrdi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnkvhti.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhznrzom.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhisbrry.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bsetvkue.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2awbdkzhk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2goutrxqd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ormcoegq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjjsmln.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2apvsynyv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmieszsf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2imceehpx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gspragmx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yufegeik.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wzoqiarz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjgbpdk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpqekek.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlshwjfg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfudbcp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzfmajt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2lngjtzgc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2adlvhmwr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipeolqzc.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kptyolxg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxycrweq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2plkjdnyl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hpncgqxm.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2smxtuluq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2zofcjgnf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gpoftdhz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfwlits.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrwsrap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdminjw.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kkocktnn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evawgkok.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2uqktcjlk.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2oefwelfq.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swnhshgr.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vretfvlv.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqhpkmc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grobwebu.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2waoardiq.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrvudec.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtfkyra.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvwncyt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xrccacok.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnftbji.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klkorulj.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lznhwuuq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcataiag.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgdztgr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlgkxtn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnlzlso.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wudutyjd.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzxwbee.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2btkthguk.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iguwylay.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jysonrng.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnelzeo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qxztuxnj.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbsujmp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nikykpoj.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpgtfkc.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfucldi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buusfmlk.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpegwxsv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyplvsi.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imumkiwr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcbokbw.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvlheqb.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2djonvuhm.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvqfujv.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpqilgc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kilckeqa.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfnubxg.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmpwfki.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwcffiu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjgilij.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvwatlc.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvmymmn.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzepznf.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvehgbz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upksrugd.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwkxqxs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhewkhy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdasujtl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzvhkot.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxyobrk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnafish.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbtbbno.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwegeeal.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcbfqwq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yiywujru.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxsvzkw.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iskonkdk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zecjzzrv.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrvqkyi.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2govngsjf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2osimehjw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2tvonctnp.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbkhmfh.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sziiftyg.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2touxugrj.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2docaibqc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ngihgffp.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfaxceo.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjkiudf.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2orantqjc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2liumrfvb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkzefco.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2elzdyzsd.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2houpezit.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxfnupf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrvbsqw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2torbycrr.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrekqkbj.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjziehe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpurepin.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ateoudof.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxjdgmt.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiuvvin.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2safregxo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsubmcn.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ljylfyog.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ampfqhya.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2uhiyiavo.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jisubjqk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvyosbe.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlvotaf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtntsrq.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbgpazb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2taqowkqk.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjnvmlb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzqistt.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrebogy.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rwznqxgd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igpvndby.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpclxdub.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyodppbe.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnbvbne.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhreank.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbmuibq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2argvaigk.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gozexuzd.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkotkaab.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tfebmoci.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyjarfy.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuuangz.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvbmyud.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzekily.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zamhzxsv.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvevwyx.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyvewxa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2eplefalf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2oguuzwew.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2anyjvidl.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpsxllq.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfduathc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfoczukq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbmalkm.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhradrro.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2acmbrxtm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2krgtoqzk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtugdpy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgiqise.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrawvhkw.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxskrabd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmeeifoe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2esqlyeyn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnhnuup.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpmqaxb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyjqoxv.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwutzph.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbfwsdz.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2poxomsrt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2moqgltvl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2grfkuihh.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2tyohtzxf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmnmceo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhetkim.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kilvnmvt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwdpvqu.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqfnurm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwjadll.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfazppky.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcavpkdo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvrfmih.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfoywgte.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gozlbrga.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfiptlf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxqlzqk.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qrovxiey.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbudpge.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqulzunh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2girhoifx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rranrsai.html


<!-- 参考信息 -->