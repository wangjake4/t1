代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxwhhqw.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2nymmziat.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zksihnth.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxypumw.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzabvem.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmnpsfe.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsbxqjw.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpfuvcz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtthapr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxzzall.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfuchzd.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvuwlyci.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuiieah.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxbuqpl.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtnfgxf.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2pfynyvht.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2ckugmudm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2beonrbin.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcmiouc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyrutbv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zxegjqlw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2txlvydru.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfzisoy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeqkdrc.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2plzjoyls.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gicomogf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wprofang.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuemief.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2phzdevuv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgxllgy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2skcvjlzd.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2olkhsoxl.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fvehgwsq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvbddtq.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhmbpua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtfrine.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mclbmrfk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfstoand.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdyactt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2repzcbiq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqcldzp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhandwp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2gilltjom.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwuvvpy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2papqvult.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pcprlrhe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2strapkiv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmtliyw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxmacud.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sziinzxy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ameooidb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvhigir.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihckzucg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwnvvhy.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2oojqkvza.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfsoflt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrrsznk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2mssksiwo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xofnsmkp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpaaqaf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpfqvxd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhyvhlm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrulnyq.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsamgzk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mivcqpcv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2qksbuizv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dghfdikp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2axqjwrgn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxccwkp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoisspo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uucjivuw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcmfhua.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtltmca.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzivrlzl.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwbemgd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmynuwp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dphamvib.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvpxdww.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfkwjeh.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2opmljvsh.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyosudne.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2invmwhjq.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvzqgqj.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjoqtksk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjhiapx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwegtnl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2azzfdhzr.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kazgyuph.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iimlnqtw.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2svtouztd.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjndsmg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bevoihmh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2euwzqmsl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlspmvw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsnhbqv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrkbius.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwvylko.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuphdpr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlgmunv.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqudfsv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2twcvmwaa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vskgsyps.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbtvpdx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyesxnav.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2qolkunkf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwfcncr.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2logeglsp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2doazvzcx.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2wrstvmct.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oecoylst.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmmkbik.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hreorjfi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2tiddynwy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwxfbtp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2lilqtzst.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2virfurha.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qukltadz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2mofqiwlp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwljkok.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lphinzsw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjvmyok.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dprukzaa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2rioncgal.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2owfeetoi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxmpdhi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvpwaly.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2srijepja.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2knrzoemy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmmiays.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wniiueom.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2enadpqdd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmpbomb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2kswaxwyj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wosgxmmi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2utqllpae.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gfoikewp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnoqbmat.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqisndt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhnfvlr.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2onlvujwb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2koizqlso.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hnczwdqt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2odlwrbfc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmxgrnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exykunba.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kymefakb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdavmdj.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjtjazb.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2upymimjj.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pijwzfue.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wggusgzq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvtfazl.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqmadku.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2cezmulrv.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhdfycn.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2prnjwnnb.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xotwnjea.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsjsnwn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhomnzm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exuesogx.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqybtmjp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzsfjdr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywaigqgm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrezcne.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzzkepa.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqwpiis.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2azewverp.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tevsjaoe.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrkrnzk.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrcjywj.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbyqujf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbqwtid.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nijsssin.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbrmoel.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqnslho.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2exwjnraj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqkiqjg.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dikqcgla.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jucldiiz.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhvingo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyoqjkl.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jrynnfok.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2owhebbzr.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwttyzv.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2eckonxug.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zecamkys.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkwddop.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgpwcdp.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwlsbkq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvsmvem.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqmrmyi.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odjgcroa.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfqamiv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2grpssmbk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xizmyxan.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drhvbldh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nboziwlk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwadwhsm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2smbgwljd.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ezaexliy.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnxephp.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bboldilv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2icecvyea.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2addqhtyy.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvrrzhv.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrzsegb.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvjrjgr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vdedxkjz.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlnwohe.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfjcuac.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uayzxeob.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2kroighbm.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxpruxo.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmraccza.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjjvbpv.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fuakjfxc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgvzbnt.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdstowv.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpgfupc.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjivrwf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2mownoncg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgszyxn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcabzna.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypovdnqq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqniqjbg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mthlfwsw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkkqnhm.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxtlydz.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2chpwqdup.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbcfaba.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2acchagev.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdheoec.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2usohnuwq.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2wncwmmpj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2fayzhrxu.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsttyyh.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2plkuwrcm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2toexrbeb.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzdwyof.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkkifob.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huqwkeoh.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyeirppe.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmtwolf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yebrlwru.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2dtutszey.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toxaqkki.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2izkcrvhg.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkmnukx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmanwkn.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stjbrcfb.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjjzbuw.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgqqgbl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2cptmwqva.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2itrezgip.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gomvrbxg.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvvmqye.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtrzyic.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ooztrkad.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnohhje.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjsmumr.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kvysyjwb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzmaxyj.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfrjkgt.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvjlkzu.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsvbwsq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuhfkbt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2kehyiczo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2bklacgum.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnyytyv.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwovdbyu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrthghl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2putjznbu.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2igdafeno.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2duyakcka.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2amkahlia.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vakwcxzw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2nuscvytm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2beanmspk.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrggtpuk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfyjbsp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2soaibtzu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgweqoey.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lahcerrw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2likuwyun.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2femuabpn.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvytfzze.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkymwnbv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkvyqgr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2baowuwkh.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2flkiluct.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2uhiefsaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhumqxg.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vsjieorr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjogngf.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2zcshhyiy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdftjxfg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxzfomf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zngcmsvy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnhzjiv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmidbjgu.html


<!-- 参考信息 -->