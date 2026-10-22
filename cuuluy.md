代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2evxadgqe.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpmdcwh.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bktncttc.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovipmglk.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmkkhnm.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoghrny.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mhslyquk.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2oljjmlca.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2tqecgcbd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxmdmgc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsibxse.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbtbtqp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2teemtump.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnwkykp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vszmiieo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2npswmwmr.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2teawwsgx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvwzvhu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pgscjbou.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mffmxtxm.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vahbtdzp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkephdfm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2qmouvgvl.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuuhmqw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qckqcmey.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvzdtpy.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zppcoyyh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2koczisvr.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkhgtcd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2okhrkorm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbemkcxy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2olvsydiy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2efivlwmz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2igccqong.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzyutgw.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzelrpue.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbzqapj.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tthsfyzj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvxaaur.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhlgypi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djywmonn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pedqkzic.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbykvodo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmliwqyc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2klsskcnq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vudfaqsm.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2pktkvksa.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqgcelv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2iftixrks.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfpitrz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyeauac.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2obsvicuv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrsbpvw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvdbkpb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxnjkpb.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyvykcy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wycspcpi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtoinez.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqpknfw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2trgnbbqm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2umuzfjnl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2iusqvtpa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2axjedlmh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqlrazs.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyhyslh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxgfruq.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdyilrv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjfvram.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvephgvb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yyruzcqq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcoxkgo.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqedaxim.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2orcwrqqx.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpuvgot.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxneudjt.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dysphdiz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdogfzug.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtuphyl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yurmqdsr.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2awgjlhyl.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpdaseg.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gphrqzbn.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2poxycesf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltolgvhf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqobthmk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkvovmp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2surksbye.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2adeeovnn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2noqsgksx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2idhiggfv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvxlrzl.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fzoqrngc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvassjg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcosjeet.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjmyfbs.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxryxjef.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqizvfv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxxyrxx.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oscjdygx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvyogbo.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2qebethup.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hanjoioc.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdhmssw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrmukmp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2axywzzhv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iajvjuda.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjpxrcz.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnbyaue.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kusnpgly.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmowilt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqbrynm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vjngtgyp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjbmojm.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2azrtooxf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2qszhqoxh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsoyajr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnotstgk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vugrguil.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hveorksd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2trgqzmpq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uingysfa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdxeila.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgmwbzp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yccqvsog.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2quzdcpdz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2thzctudh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2exwkuvit.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2edoqqevp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeuevmx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2izwxwuyi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuxkgbt.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2oyibprbf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2myoorcbk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcwzbzd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2luggrzkv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxlixit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zopkdfpr.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcgkbhw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2muuhzcov.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwoocax.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrbmstj.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2htdcvifm.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwfddww.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzgzocc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwsdncz.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeixfipj.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfdxgqz.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iaefggti.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hetcchgy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2imjflfww.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nopruyvh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byxuxwos.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrgblhx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njyvllvu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkjufkm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2oshrxfmu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjufryq.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eawqevwb.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtzwtyj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fotgzxyj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwfylbr.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2npmeogtk.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2siznvdjy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgbbohh.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkowswxr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yaexaotv.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2odyqlhjo.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyfpqdd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqboerw.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tywvebna.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zexastop.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsxuwpj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2igazbldf.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlewbyt.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrffxtl.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lngyicrj.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qesdvpws.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxospxn.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wvieetep.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iyascuov.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2guwvlxfz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ryggzzmz.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqgfggd.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fzshphby.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrdfrvu.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2hupnvkfp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhhojfr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amrixwdo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcrhzsd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsijxkl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2dottfweq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2anvrmezx.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpgopnv.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yvacikqj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2unokwygc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ofoyjlun.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtqcnbh.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2usfkqrig.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2diqbvyqv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wchxmcnu.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2keyztyry.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bennckls.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lbewbyrk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkvliaf.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2arlqtyhd.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmgarie.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrorbcb.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uohvzkxa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxwwlun.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvpmqfy.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2twrynktq.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcfgewr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrehovp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqbnnnl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2crswvtmd.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdjndux.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cirgpvwu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdsokfo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ucehtqcl.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfhieyo.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2zhturhqo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqnjbxn.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2iihyptli.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoyyboh.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ollubqve.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyttpik.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2otximdts.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2uyetftan.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwsiomm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jisiotft.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvxhscr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeqythd.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awrbwzfr.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyactix.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkubqls.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjlpwfk.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvmptvb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhphxgh.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcyviji.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2raqjwkze.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzlljel.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkykvxit.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhpqldr.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuynagm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2owmggimx.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qugwcvfn.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpqvkos.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhtajkc.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtxstrx.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlqffil.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbimxzp.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkqlodk.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiddcae.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2djicwxmz.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzoqrczw.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2xujhdnbl.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2wduxcxzh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2prvqlfej.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjsmuoh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2soqaiiai.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhkbydb.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuvudyc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2javnvqqh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2npcljzcq.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcybpjdr.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzvxkak.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zvosjicv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bginsqmd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2qoovjpux.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqaaowuj.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyjpzci.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrkhywr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvbckbb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gthyhicx.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnxexkb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbhgbbi.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtsqgan.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyklgwrw.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oanimwfv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzrbvty.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuqsvbb.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2shpywjvq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxgxrvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrhmquq.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zfoptjqr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyjpxaf.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrfaeuf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2vguwwsjz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2paqvyoll.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tceqranz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yorybcra.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2romhopdf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2llgrfqwh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zkirthdj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwonjezu.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2waatpbga.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2ondjowib.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwqeopm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2drcuyvdm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvikzgi.html


<!-- 参考信息 -->