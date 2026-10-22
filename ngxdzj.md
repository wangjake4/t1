代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cadttmvh.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjgyyqh.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsesyklq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2tclfmxgi.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgditch.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfhhmlo.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzyjmqu.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsjjuoz.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbtmkhz.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2nkoitxaz.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtaveuw.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2jorjvnkc.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2uutgvynm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxswmsu.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbevffh.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evphciyi.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jnayrjnp.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnvslsi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwnmrgq.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2bexivaap.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2lazayows.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mkurxfgp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2aihakmhi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmhnauu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2luiczxra.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnywgub.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nesytopg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzplamr.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcghdgi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqsiwsh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpcuwrb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbxonml.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yymekdal.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyimfzz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwnxfoc.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjdqxku.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvxjmsq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuhinki.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cpifgtic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nvotqhnd.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpcliwr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2htxveqrn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwpjobr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqrbnlr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zximeurq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkbimoi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrtsgtv.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2upufgijo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ueraopjf.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lfoovrrx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2etgxjdpw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqaorsw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqktgtpn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxiocez.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2wechncqf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2whrgdequ.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrghoaxu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dutijqsb.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhchfidi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsanudyu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2riovvnii.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wruwjnzg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2onwechav.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fosnbpwr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2nygnpjkj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmuyxsv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2igaoedfh.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwvatal.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuysaxir.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2upkttubw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2smcpshxe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lirmvnlb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2oomsqoqi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xubwjfgs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztftbxga.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2goomasip.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2izusrmmb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2rallnczc.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnvxthh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnpxpsr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkkzbly.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbcbndq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2umubsebr.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzsblge.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcwncvm.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2siyngjxp.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtpkzcs.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tuokxjkr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2toqpvifb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zneptytm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2odnoxzuu.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmuchdm.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2twryffjm.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcrdkup.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvxsxmy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2komoanpe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtuhdbvg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2lpswlnwj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2shphdtvn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtavtzc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrutluk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwdidaf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2jlseagaf.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlfauay.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bicfikcm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqedmuzc.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xytiefsf.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hggyzryd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxluubby.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbnbddi.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrjxdgy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxninmt.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjgnyfb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2izvcjpmd.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cooolcxy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pciryycg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ygeedbre.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2onzgpken.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2jigiqgtn.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2upznloxq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkhzbyc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2lyluwjvq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzijuvjd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eddqlwyr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbgzqjw.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrrjckz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2pliyzhdp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jcglyxgw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgarvhok.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2owouiecz.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kpskwzep.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2whidmkdo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2znkjqglc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfvwrel.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxnqqxz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxjhftn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2jclpovaj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqeiyqi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjbauoj.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2djjlgumc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyrnwva.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmwtlao.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2owmmojrb.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfvijrm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwlsacx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpjecpl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyzjxlt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2keexrowq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqqxmlc.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2walhqyvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2snrrfbhi.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2etsrefrw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2omegaoph.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eykcnfyj.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqwkgti.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pypulmxi.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vymawojw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2prilfciu.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mhedqhco.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwhevub.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgpgwqq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2pokzhytm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdwfjum.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yotdzcng.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2twcmgiks.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzpmnrj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2iierquqo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfyqvem.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tluadzkr.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfnheed.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekscpfbt.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2njonameg.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxxpmqz.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyqfxeh.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmaehsf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ohouaxpy.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyglydan.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrawfxn.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmnakkg.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xlexzatw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oupqzjzz.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhasleq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxujasqa.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwocfnqa.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2eowvdady.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2meiooqhm.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrjnqqf.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pxasugty.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2owhkrhyu.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnucwom.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqvdmkr.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqjilgr.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zoaaizta.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtgikzt.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yoepphvn.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxumcpm.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqiikju.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2udmvwuvh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkylxwmo.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyguvlz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaviwdxl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toojwaor.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2napqdobp.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eukadneg.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfkkiho.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2veetqprr.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcuhwpq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcxnywj.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2gimfaezz.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zytcnmuh.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnjpasf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wawohsvf.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtiferc.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjnukap.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2urjukzfd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2piszedsz.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2erdkpcmc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efpdnraw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urmczfdg.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbxtroo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2shxvqskm.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2scgstdqr.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdhtubz.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqghhap.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2xgoteeqe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvkrnci.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnvxdmp.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epeeetll.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2piieiucb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcuggfj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdrjxxg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqbuvgu.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrcklnc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrksfhqm.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2auvlguhm.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2psikzrep.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jydyvomv.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxufbeg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bczrdscd.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkxzyzq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2iskxibnj.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgmjgql.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqtszuy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhigujci.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqilqxcz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aejvrjur.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fagjzhqr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbqhhgp.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqktrwd.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwynrir.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfiavmy.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2znpgesnk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvoqusc.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfiqefjo.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfagpqfg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfmtxgk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2oixappnc.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvydmtx.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqcdqin.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2scyviopk.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvofxwk.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hmayygji.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2otwnjzed.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzqyggf.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2snyhfoqt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvmitnr.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rntqeyxv.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkalzio.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjtzfcd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2mzztvgbu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2mgexlxpf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrwyiwc.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfhpeyz.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjsqakk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qznjvaxh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcaryzr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooaqkxip.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdmjojv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxkeywd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omhqrsgg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwfmbya.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eafkmsjy.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpjlapb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtrejjo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2umyqpfhh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2edvhxioq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lveumebz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcwvfkh.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmymoyld.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzssblos.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xapbqfwk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2cacmzfxu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhcprea.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgghtyf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2cevywjrf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxctomp.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ljivliff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqnzkmo.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2futrimrb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndltjvjs.html


<!-- 参考信息 -->