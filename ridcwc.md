代发 wailian999

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqydkxb.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2rxoceftf.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2hphpygue.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcukhbb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2gofvgkgl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttoifqdr.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrrscqo.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dgocxlyg.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqenzylo.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2epphkxid.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clvtsvel.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzlzars.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2pecfrrsu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2swbrweto.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kedqmhrn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wnifoinw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2iddjwbpc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpteruu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ugeqvbnr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2udbluuzn.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2afnjlopt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfytlqjc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxvjhnh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzxrbrg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtbtsqi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxeetywo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmhrtfh.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pktmpjgl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2endjvskz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2esizbjqg.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mygqyqvv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2esasmxcn.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iasqnahj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvczosmo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rngiqyvj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2odaqcggc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkalhdyw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2soqihnfh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2kuudhxtw.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2stdavkrz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hehsgtrs.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiatkpl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2reyspppm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvevtnun.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdprqqsv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2conkujvc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrzzyvj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrqiszv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2swmyyfhf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2szvcbmnr.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2saizztrj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcxurqq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzvzrgu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nysuppvl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2vaajptln.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2whlnzror.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpxwznf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2znmwrjxu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhacidp.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyveeab.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2forhyczt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2irrxgkav.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxiokrj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2rookwwab.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2arlrpjix.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrbevbx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfsdvjox.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2skbngoph.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ennlbtys.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2oejmmizo.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xufczavi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlpkmvg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktescaap.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpawsdm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2myukctsj.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yplpjnkm.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2najrlsyk.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqmbpyu.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfphmjdu.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zktmnpir.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxmgixi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzochre.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxpqoqv.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhdwhdj.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtovckux.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyynhgf.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmedycbf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2khyulsja.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbsqpql.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2scvlketa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcruvtk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzwapws.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2trxiiyys.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjdkvrc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2oqczzmdm.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwhdssa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yywlfawz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgjphhj.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzefejd.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfgmrqh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhrhzir.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmkfkdd.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwexwiy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrmyjze.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwbslnu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwaqrig.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzsxxyp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2plofxwok.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2whtidyss.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gsidpaep.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdkqriu.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdgxnmm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqzstkh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2lzysurzh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iavsjyhd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhceampj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohddativ.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkqujbx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2splillys.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2awhgqwbm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbflhoh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jopojjsi.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vfejyuot.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jorevibu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2unkscghh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdqnfiw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2saaxsdvi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2apvflzsj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2sqopbdii.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfilqpt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2euokwjxq.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wbstyknk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlaqoxj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzryivq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zemejlpr.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqpreov.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2lwomvfkr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dghoojfz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2uessnima.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2acwndmlk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrhzjca.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsabhct.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfmzejj.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xhivjvln.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fkufwhye.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyaaosa.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeojgrx.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgulooot.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rayrhyla.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2oolhuham.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnlyavx.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkkdwpy.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzztariy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2okeibbsw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwxeqkx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzzfmae.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjsnucs.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blnmqkwq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aathiurd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xrglktst.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtcxrfr.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwummui.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtccoqi.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bziwdiqe.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnsxxnt.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fegbgplr.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccppmqxa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyhyizn.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yaigyzzw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfhurrp.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vwugzlzg.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2liaeuedt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lufzutby.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbdsnpn.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itzbiqbl.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ormgombg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhkykgn.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtqtztm.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqhlwhy.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkixxbx.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnnrjrq.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oebilqdo.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iavebkqy.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlocsfkh.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuppviz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmjjwgq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfqjrgo.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpqrkpt.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2waxfjavh.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkoprow.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvesvarw.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omsuudin.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spscthut.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzbimbv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjehwcq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rihgsifg.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ywevtvjl.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vljkohks.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2zucbihca.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqlvyru.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmelfyp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dotzfadz.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xowrjrru.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxxmkso.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2suufnnph.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzoujiw.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2icrgadjq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2nibjujar.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kzonuvkc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmukzzfy.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsigprc.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpizzkg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ycazbglw.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbgguxj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpmcnjr.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2lyujeung.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2grqfnpnz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bymvifzr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhfanay.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsyywkl.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbrpaby.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmjzbec.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2agmfifng.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewephhmn.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2cdepbjbf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncridpob.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mozjdfpk.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wycopeav.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmwmsoo.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvaiita.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2akgdqswh.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2hmspuqdl.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlwzwcg.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2uctxnubj.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2kziscehw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rykwqaoh.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpkieep.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hywututp.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjwqoco.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxhmgzr.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzkjxfo.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tumuvfqm.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjupkag.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkfidzr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omniuppi.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phwkyhjf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmnrmpp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikddaysi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcxbxij.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2utvhhpor.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2otdimqif.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvzjlie.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiqvdsv.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mqquwqck.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mfczcmqj.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvrefff.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2npdtfdrf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyvwpbj.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcmfsma.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2uoskzxoa.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzrudhx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2njmjgfep.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2pekgfung.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfkjuoo.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqyavjm.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tctkdqyv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2oglhploa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2hssojebn.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2lerjifxx.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpltemf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2knhmsplt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edgmhent.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqvrrge.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wclwnotd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxyrpyz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxjdvhj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2chlkhbht.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqxmubs.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmjrtpo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2kyavjbhm.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfjkfip.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwazvpy.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwmrvqb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2aonsacct.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpyjwkq.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ajobvpns.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2zoeiwewu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bliblawv.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfblrhx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xrilkrqe.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuagmqy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2wadvwusn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkcskqs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgbnabh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfeylnz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkfratu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sexmmhuq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjhcjcy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfldbtwn.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxkqvnq.html


<!-- 参考信息 -->