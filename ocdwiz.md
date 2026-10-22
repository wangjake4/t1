代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxjssib.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xyafbyod.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rifbcnbm.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqluvqay.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwvwjim.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvohgni.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjeqczxj.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2knhyktzl.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2qmaxnnmo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqmejgp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nkamoxng.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2olbiovij.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhbazji.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwotana.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvsndvw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrffecu.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfgnevx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbxrlnv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zgluozep.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bqakvejh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fhimvehs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2eldapmmu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcrnxid.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrnnwdp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nifvespl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeeachs.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2imtqqdpm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nflalmbs.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqcqmjw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmdbmah.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cealtnub.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtupcpr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2sudspioo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iunlxybq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2dnszrifw.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2olrhvtto.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzqeerx.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pfolrdna.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2kbputkti.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utidczeg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbltywng.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwtrrjo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpbiytg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yynpgemh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2zovsvtic.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmnxsgc.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzefqbnt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwrkbka.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsvlwbe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rabdacou.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcblmbd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrhvzoc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2turgweyf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdbaelb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2akxhkrcm.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhzswql.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wykztocn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxfraxx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnexuli.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2braffljt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxhkgut.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhuwzel.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqtmfnz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdpovfu.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhjwrzk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2czmzrfnv.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhihmhl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvxhjtr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2itkzavxm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhunixq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdthnyf.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyoqocj.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hpygibgh.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pibuasjn.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmponca.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yejssjmw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2txygkomp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrmzavx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kghqnfwg.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptntjqvh.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlclddik.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cldideuu.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpahpayn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhbnnyr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2baxoomah.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwoqpro.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pijxyrxm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqseagb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtkyybu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzesmrhv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxrsove.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jzouhbjp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2klswkjmh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieczclxs.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vacucezm.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbyowqc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2flmiibxi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2helrpbmw.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gabttqqf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhddpxq.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfckbor.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyhgfjz.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcfbghv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2eigvnmvm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hondyfsi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2llubnrkv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2uexgrwex.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvqnodf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vyexcqox.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmjwduf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcinwzvg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kmahffkq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2goeuceih.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2crkwssse.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2xygngdbb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyoxgkk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqotcxkx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2giijvsmb.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gobjklip.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2idagbrbd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwhvixg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2udkuwoec.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eukezxxv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltguksjb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2hkowmxob.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihedugrr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdiwbts.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2litbdsjf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfubzcm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2dpaykuez.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqzmbud.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2uzerbjck.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvxpdmn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2twmsrbhr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjemivpx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxoblhl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkkylca.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ddukmpvh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skmbxxbl.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtagofu.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jocxmeju.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2paidyefa.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwunkqzb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmoprbr.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orilicqe.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbihsos.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nrydnthc.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vtppxciq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxxydmq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2mypiifge.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2phujmhop.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzkooal.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwrzymg.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbezflj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2noujyzzs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuzcixw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaclzeub.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ascwjfec.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfwkcgp.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2urzcbskj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rzateiez.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgzabuq.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2turwvoxs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwjqkdf.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxelvwn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lllcyoey.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nansdnlh.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmizjtk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvqqpba.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmivxde.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhxidzq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpzgasm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbuzmxd.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2unaechdy.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yglrjbnq.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdiwoyg.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgogwof.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xeanazqu.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ywulujkb.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ealgcaap.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mznetfff.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2lldgmjju.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jmakdily.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvmcpxc.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhvjnay.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmqdetp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efbtcncr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwefogem.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbeawkz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxotxoeh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbkovra.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrbzpld.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2mnevfwew.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ygeyaghm.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtayjwj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxnkwyk.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2keemsqom.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dixprivt.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqxdvay.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2upwiqzfd.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2kocgsahi.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2upsrhbdo.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vshedmtk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrgyzhk.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qknalsig.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuwlyli.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nothcwdr.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igyfenug.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2phfjajze.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hcogemeq.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vuphozex.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2zoubqeuz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2agrjnolt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgyvsvv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2bbttpice.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvygvfz.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijscxxnh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ditucfrp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2flchbtce.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2warbjvds.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2msjwwiwi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnatffx.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbxdkxn.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2pldqegga.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyozklh.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2inxgtglb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2aexokykj.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnjkrdr.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ypamknma.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjulkdd.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuqjdsk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2addlbpph.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvblklny.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xujezjpi.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubefitwz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vptbhgii.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnzczly.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyisutcm.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzbkfjt.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzihfze.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gufpvftt.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rexszaao.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaluyaw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ossmuhob.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yegxzwvr.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pprgonhc.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbfzcgt.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2elkxknlc.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqupyzpp.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdderze.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2myjgaopo.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2knpbdbeq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvqrbeh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gyphmzyq.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2myacxunt.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2znrtvckh.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmkukhp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnspkcr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvoargy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpytnmh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2krccllgz.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bixhdvno.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzztawph.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpnnkjp.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2fiezjhfa.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aecddgwq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sxinyxux.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wptvlxvl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2krvdrdnz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsaeoszx.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2avfouqlh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqxkkaq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxsgwfl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qekawgxd.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjvqdnc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2cgihqybw.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppflyjtw.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjzcbhs.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxvrfqh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2lndjslot.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2efcmqimo.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbnpazr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hugnufio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2matvgcls.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wcumjcau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwdvkav.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjryfvc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kabqijry.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzjxovj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsdbdgk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrjeown.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdniqvl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2shdxlmlf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgcoqdm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcaalmlc.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tberwslr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2kusmditr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fytazshp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcmjbby.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2insvwrsj.html


<!-- 参考信息 -->