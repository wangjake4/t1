代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2iivdmout.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whbykkdn.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mpniaqat.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjywopg.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtwuqgq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkluopux.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmpvdmd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2sswczkin.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2miecfbte.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2flwmenik.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpblisl.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2atgoqsmu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2klxualxq.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqscibe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2xewiwikk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgojasz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2viiplysg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2acmrdssi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwxxyhp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcquesx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjpbndq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfklcxxe.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqdvwaq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwzyxom.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbkgfia.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzomwwm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqswknhz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdtvpqj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2yypcvvvq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcumhsz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tckpzwlz.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hogovupj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvaszwi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2maiuvemg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsehfyly.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2giuiuiwy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ellaqpdf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2muvlbulg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwphako.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2gloqjgif.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwstiub.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2emijetih.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtxogts.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrhgrgy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuukpjq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpewdgi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2juegutox.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vayneeij.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvzmpbt.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2betwrhhv.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrcztgx.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ooilubge.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftotzifc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmxmqle.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmrbrfe.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrupexik.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbrzsuw.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmxmyzf.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pekffwid.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2flpesmuq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxcsory.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xeauuozx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjvpdib.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sycrpwqd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhnzpzv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2cokqyxfl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkivvyf.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rzadrxck.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2amdfskbw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwddfylz.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pizyndop.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnmckwa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjracdzy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gquqxvya.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mppbzitu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2umuxxqxm.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2psalffjz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xujrsjsw.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmnfrou.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2osbmoauy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqnsaom.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvgzwhi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvrmxyp.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqmdesd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqrinwn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2tltemsyn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhkpnux.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2onuxtqda.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvozxsxv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpgnjzv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2jibxhiey.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxhndwo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjiiamh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvzplch.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjommln.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxswzmwv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvwlivu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2klmmxeuk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmyoamm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2higwwfvh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzsaiup.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qokezgkv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2elzvcrxt.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmhfhwd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2letqcpdz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2fldpxsrc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jznknhmm.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwtenfk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2sksajauu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zakhfpfj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2caomsgnw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zibdhgqe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iylcjqdz.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bchnncwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfybkmo.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2bocmlwkn.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2icbmnaha.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ashnwsfd.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtzuarj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhzbhpj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pruactqc.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2okcukfuq.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kzugmbwj.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhhiwoz.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gfncecmq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbjqmew.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2viqeinmt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhqhmci.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dklcomcy.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnogeoa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxobmfm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhzaecz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyeblzdp.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhfzyce.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lejurkho.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fieuefmq.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpnnwrz.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlrgnbg.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eihvathn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdhcnrz.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqxsncs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xvufxtgl.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2empwkhrd.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2quqxneiy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnexnzyy.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdtyiyv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbvkqii.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvrmxuj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmtyiba.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2chgdyrlc.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mplfklow.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2aytaxgir.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwzowxo.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qepisilu.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwijnel.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyrgqsg.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dctaatzv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwflnec.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nkatyckh.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmzkpbh.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvfjaar.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkgkbha.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqskzle.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbaaxff.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjrttru.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kndswayu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2krztfjpz.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cllsvpwb.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2trpdroza.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2skaydgfa.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2uanltujc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mxguxzpv.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrubhur.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2buxxoevf.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2izrlhwhd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2giffgqge.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwjnfjc.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgnsgrm.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2pobeshrt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2naebpdjg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfdusbl.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ergsotku.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqpimkt.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nltfqquu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lycyxuck.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2djforvbr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2furjkown.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2nudtezfy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2buwjhzij.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pimtqvvm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2urcjarys.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtbmifl.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhjmnpu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfkntji.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsxwbmw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2awfbdvqy.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqiqapy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2cysfdebj.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2muwprhiq.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2syxmcvrn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmoiqts.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzkcyqy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsydyuj.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2blctwwwo.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgqgnta.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2qcewfgwv.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvobikx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqxpkik.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhdtieg.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcjcuvi.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnecztl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccofjawq.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2sabreaev.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfokbjaj.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfmdimk.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhmribx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgdgchg.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2teagcofe.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpwjgxc.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mefvhkym.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xunkzdca.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpmrvod.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzluguhp.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sarlyrhx.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcvplge.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2crfazqta.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpxterb.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tszeqefu.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxfilby.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qncygpgq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhmoyue.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2kfczwezi.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2extiswuv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnomygo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2bedrshnc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2svkvsggi.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2henzbmif.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akpakzln.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvijjswp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwkemcc.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkhojxz.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xamktphb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xgscrpuh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjddbrih.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2flwfztqi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2guzzelrv.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2qumhtrzt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhkdsvp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2svtunkcx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcpkkci.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwmeaob.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjlidoc.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhozmwh.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fetimiyq.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrddesd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnetpjcq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cbploivb.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2yruerixr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxxefiu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytljyuyc.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2okhrxith.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rcskexgk.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2umaljjkf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2mluvxjrj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvfpoet.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pixdgcqt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2afyiqdyv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptuqeogj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvhrawh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lqaxgdnn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2morbtmim.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ewynaxoz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgnjnrp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxsidrk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2delzlgoi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2svlukumb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxurlwu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2btklbrtf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlfhtkm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtscjyaj.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxganmi.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjqarqu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmnhlzw.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2cfetzqzj.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2auunuwow.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpsaska.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfupvkxb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2tancljzc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbymcod.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vaozdgbd.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2szomhfkt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rkitpvhx.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2apirwaad.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gt2syskjagv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gt2isvdjxfq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwmnviv.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxbixgj.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bukufecu.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uyepaauj.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2uyubtlsa.html


<!-- 参考信息 -->