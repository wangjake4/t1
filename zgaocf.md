代发 wailian999

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2dthwjxqk.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcgtfys.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2zrggvnpg.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2ierpaacx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgxtdlo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdbovbi.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2duzceecl.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opzydhmf.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bihhgbyi.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2bcukufsw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2utknspqb.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2nedmpopc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2lylebpgg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kehnblay.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bcluuntb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kbphortu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2prpoqfmp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2afruvnsx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuncuaq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrninbl.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qldoeoia.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mywvfmfk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnbtkeg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwlirik.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2exapppag.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2zihungsq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxfqcas.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrxslfp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvwbwmi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivickntu.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aorabzua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmudtbn.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbdbhxt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhecjkkg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsesxls.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2vorppyoa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2yinuocyc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2agivmnur.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2bomcuvux.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nilxcrep.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhtafrc.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwajacyt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2cyruulzc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2togmoatg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlmlrwx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbpdnmo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbrqezr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2secibfla.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrqgvse.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2duohavql.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpbnxbi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2juymzobt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyzhgio.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjnsseq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgywufs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwnyrli.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykojcywo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzktpstk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwqiqha.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzztqhzz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvtfvxs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2tasvkbqv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wagijhbe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jopposrt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmvbwnd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lsemdtcb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lglqzdhv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2akfwszfk.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mrczchgb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpdrpsp.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yaydxrkn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkokzvsf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzzqnkl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nfextjaz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgiwejk.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvvpdsk.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2agznemjg.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2risgfvwt.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fuahtphv.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2prtreclz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdftlic.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqlzdpw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkdlohd.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2isqoyatd.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsrhflj.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhadixl.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yemkeiow.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsezormt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2websdolb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnbbrxm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbswupd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yopwudek.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmznngvb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpnlutw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxmxmwk.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2anrapttp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdotveyk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ampmbiux.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcoticr.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bowkfmgm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmilkrb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygymaydr.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2laqihvls.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyppvmfu.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfshnkk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2amhjnaol.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhboydm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fekdsssj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2lysnovbz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zadwvspt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnsygst.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrxfxdf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pvndbxws.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kltehyah.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkocnsmp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2knfsnctg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmnouzt.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fibxnqig.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2loexuwcb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwqzfcn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ootmprip.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuykqlwq.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvunqrtu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdejnzv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eurwtzft.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eioawvjs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nctqwcwn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2klewqyby.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxvylfa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsagtivk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiobfdl.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2pchkspsg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2neqfeiwi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ezplksqx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xsctnibf.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtltzzb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2xktkozrb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2geuisnha.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtnuxgr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvzayvx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vcllhyue.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nurazuna.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kaebihax.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfocvgk.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfdhaey.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omzeztrs.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nogxtlmw.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdujelcm.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sltknqxk.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2yodcmooh.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnubivn.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxkbqhm.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tputghys.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2kxygrvmb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrribert.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqobhryb.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtfvlqn.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyrbdua.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrhaaqu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bisahoii.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyhpgck.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxlabme.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqndxkl.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzecgqw.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nijnatwg.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmbgejd.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cssehbrm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2goizahzx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwluuvaf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qawoikap.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtnjfhh.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzgdxwo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzpskqh.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjiygtjv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdvmfdt.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbiysgly.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2iehytgph.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqcmykv.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqsovqe.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2oevtbxem.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bwheyhdj.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbrcdxs.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbcgaam.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuabgdn.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmufszls.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2grdqcuim.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2toztotkc.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrguscng.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sifyxnsp.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjuurcq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeaoxbl.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsalwfg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clamhymt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgioclta.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2yomgjkfh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnemzbh.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyghpgc.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2etthhzjy.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbllelj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnomaey.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvjrizm.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wzagcplr.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2snfuevoe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2eliuxwzf.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhdalch.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfmchhf.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyddjqa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqbyzho.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2unnlxlqy.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2idofmjte.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wddlckye.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbrepah.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xkomylvf.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2liwihtwz.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2teflrdtn.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvruemi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvxezjr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiusfabj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmdlqkn.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uddzljoo.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2owydmgoh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrottib.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdcymsc.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbdmuin.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqkzobi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmlsufo.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2pzksneqi.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2gkneoloq.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwgvpyt.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2rntbpfec.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2bkszaonh.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmwzvux.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkhsrdx.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2posfqpmw.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wcddbvyr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wthtqyxc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtaqwhcu.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhbptoj.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxrkyyl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrkijaa.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqltrph.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2siwsdrut.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2asylhmvz.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtksnce.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxrbvgi.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vctwtydg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2laowvmap.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmqydhu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjktgfk.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzinrhu.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sftrqqeg.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2erpauybe.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzirnfd.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qaprllhl.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dclnysbd.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wiftxtdp.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2cfutnwrh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ormcbxcs.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqamdtf.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2woddeage.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2xczkkxoa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbneklq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhpvwle.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqkdcaf.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2trqzlydk.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqjhcju.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvszfsf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfatwlv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyouibam.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gmayygga.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkavzic.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zugoixtp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2yfajslzv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eafqcrxm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqhstmh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyyyiab.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfzrjml.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2psdfkiwp.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vembxcgm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhquogh.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnugvfwy.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsmpeib.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2exbsvpxx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2yshgewov.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgyxcpm.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2dzshosiq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2zscaonvv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hptmyarp.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bmltdgrt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vyplbjcu.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqavxva.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2klkxclmy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2albihdkq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlidekl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2orsdqpbt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxfaxxz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxfazms.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tcukszqu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmupguw.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2parmbkan.html


<!-- 参考信息 -->