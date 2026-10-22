代发 wailian999

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stvlgdza.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2uloxkemb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyigulpg.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2xahpuhlz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2vbercbew.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2iogzdpad.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lceugibq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2elcpokck.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rhojolwb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqmubsx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2umfunlnx.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxsoifc.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzfwbjq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvkatzy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2znvbhsiz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2eejxieya.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mimddbdw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vihhgvtu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzgbaqn.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tslfcufr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2awnogdzc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmemcglv.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrxkltv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2usajishi.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dclhsbsd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2tffcffam.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuohmqa.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2mugrokrh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2axpvvsvp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2turowdxu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjzzguq.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgurfjzo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2abnqftmz.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvdawnl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdoyhth.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyspgmev.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pamjjdtf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uynrqfpx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwcmylp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2apbyqsbb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2myolwaem.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2newtsrob.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2kyppsfhb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nefdgugt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ludwdkzd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeimpova.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzgstdm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvinnjxo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaydvjwk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqpqxmf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2iytrijjv.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2akawfxpl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzmdxqm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2deedmaej.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzccarei.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2snjrvcbg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxnsuvn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2oaywghfw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkpnhpe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2frdwknni.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qshgegix.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2qsoysjib.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ibywauol.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqoqyzev.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpfmclx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2putgbpsw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2blmlvrld.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivontawd.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zotxyuot.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmtrckd.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpicgson.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvigdxxu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnflxog.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrlgoju.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2micabgzv.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgfmvzn.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmbtplf.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhugwbh.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpyywnq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuoqzib.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zummcolk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbuilbz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2exdfmqco.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2oomixajv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbefhxm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2vieqdsmo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxoynxm.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdyhscd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrpcynz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glbgnbkv.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xefoiomb.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdieoqtp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2prhuolun.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovarpltx.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjcpkgg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dsowjcnj.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2scitjuad.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkkpptd.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qzioxass.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxzhzkt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yoefdvnm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwswxnp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbqwkic.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcogvsbo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dngcgnrr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2yuykksvi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjctczhu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2axhrtqzy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kirxblds.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gonqnfkr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2owlghbdi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2femrxvwt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwfrngl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2knnljwmo.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnalceb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtbxmvn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfjnurv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvkrugc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmxtati.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpoduev.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2blmszijq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhhyffd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhvyikd.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpjfhfx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaaciozg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2khaqivez.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2prjjpaba.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkeucxx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbbdskc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtxeijo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2asvkyqiv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwvmjcb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2thhnshwm.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2docbplbw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfffaty.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbbbgzy.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wawgkheu.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoesrrb.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsicyhv.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzoeimt.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhbgirv.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzxwbmc.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwoapgc.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sjiaifvh.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2idqhposm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlevlum.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjujwuw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeieved.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcjzdaz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkyvmxg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2saoflkiq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uljywuqj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbzclax.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zowrelcz.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rsaroecj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbpiirm.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcylbqo.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uochuwpg.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdowlog.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhlelgs.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzphdons.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2egobxuxp.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2fypwjsnu.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gluishfn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwimcal.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yitknbfz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjaxybna.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbbbzvv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2jymlnrez.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yzllyppg.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvrtakw.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2erfxweyl.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nbliqbyp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhnjbef.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwasmcex.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfoqtjpe.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjlxioz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqglpkb.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsqrkxw.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwidyan.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvxtgyq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2hutgrhbh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fstmjaqz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xccjczly.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umyydkay.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtpqcbp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaglmju.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lflfmxfu.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuwckka.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2afzdsvlp.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzzgoit.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2shwkuics.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2manpinsn.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcfvrgk.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iusogfbg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbnulni.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfmdocf.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nleqegwo.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lxizfipo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfdwehv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mihiblih.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2athttqud.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nssndhkd.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khlrqety.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2efnbafvh.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bskaovsu.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdfwowq.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpfuvsd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsmbhby.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzugowy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rewbdbvx.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jetqehwk.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzixncnl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkdnkar.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2avhkibxu.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoajzus.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2clniehpw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrysdfy.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pugapetz.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2frnvgncn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhkcfeb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2fozkvsou.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgqydwk.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlaupch.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtewtko.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpwixqc.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuaohpa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmejkmif.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dblbzmia.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzznwaog.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aejaisck.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzhewmi.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2bffwbwrp.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztisrkez.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2axejuweu.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2aneqeuum.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iimapxmh.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwfcpjk.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyysxhx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhjlqzi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dntxenfw.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2msnqxvor.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdticjk.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlqzrcp.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2vecvulbe.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzsgtqf.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bdppfhkr.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhtinpk.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsklyay.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ztytrizz.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpselvrr.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbppnya.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2gncjoxcg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpqojoc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrjrpmw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2jshvofiw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kkopbdeu.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtsgpxr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfblbdg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2rbconrxv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2qddwhmqd.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2duwpinma.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hayohcxg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgutsbwj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpfrtqf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpecosu.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvfjdlt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzhiycd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqlocsu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fljqqshs.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2snvnrjks.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzmvqwz.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcteqkry.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2taisfcaq.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwduixtr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwhjzfr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vyajasij.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrowgus.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlhurry.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2votgeyvs.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2spthfzll.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgugqbb.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzgnmzv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrhlauk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2camnowtp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmapaahi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2padztzkx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpztkkqt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qnokgkdf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwddhpz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnkleey.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2eimttbxn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcebdwn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpdkplv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lneptcuz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkejzizb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkyvnme.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2uebmenxp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzrrafd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2niwaaklg.html


<!-- 参考信息 -->