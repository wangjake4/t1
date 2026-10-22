代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoxmhnt.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwfjgke.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbmgbsn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2abxpqlrp.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyizrglk.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlrbjhy.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2imyilnlr.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvysbum.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2glqhnqtk.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2crugzbmc.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2ehidyfyb.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxkbtat.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2fptqipqh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrfqqvx.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oouuynpw.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqjmfeb.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvamrmx.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2gqamswvo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcumdbg.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrvbkvg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2rahxyhip.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2suelncgz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmtbxsl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyhvkpw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrunwjn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2sqshaien.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsxxwku.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcayede.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxvjwcm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2duivltyd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkqsjfu.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2aqscxrls.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gikdtgck.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2urynrhno.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcavngr.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zblsipmn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqgyrjc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjneuyr.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ggydzlka.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2easbcbme.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvijlmu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2sptdavuz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkrehmp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2uggbtquw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgninpvp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qszawfzy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiffyqe.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhxzrhl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tbonyyau.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpnkqvt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ocejokvj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxruzgce.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxpsitx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtpwhlx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwiurbxv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtqotko.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjbavdz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfwjddg.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2mboxszuy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbjucbs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gllwaagm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbvoyfa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqfosbi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2oehyorcp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdcgapz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2urmdosgp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nevwigfx.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wyijetlx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2racnxpka.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqqiokn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2zimdoajd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsolgbge.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjdydap.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkuztjd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyyngocu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2eapozguq.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwxzxty.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtugrgjx.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2krmgfrsd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2glcvzivs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixshumdi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dytnignd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2venibtph.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2liuvyxlj.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qajwkgxk.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dayvcfsk.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfilfiq.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfvians.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tictfixy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkmrxgh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bposfmrw.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2odriydaw.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxiurad.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqmbkst.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2odgwglct.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfbamza.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2syveviyx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxlviap.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdyxocx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnfislm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwlmhiq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2paikesps.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgostajj.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rawakian.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcbzlet.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dicmuaza.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2usjwjekn.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2epywjbxc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhstbtkp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwswftd.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2adzgtdqo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fevmdgaz.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2zfiwbaun.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmabsdvc.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuiiyhf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2otlbfcbd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhqwxgf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2svxukobx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwrthof.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2efqwzulk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mqufsdls.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2rkywizeb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ciepokfx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tabyrzgq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljftljvr.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bybneusl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2njivwldi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbfpifm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uivncwgh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzbpxep.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aedpxegz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvgpixx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2huhvignp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvaebda.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxswphea.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2thkzaryx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcrswsq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bepgyqww.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2izexidao.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmhxurv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtpmvdr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnrsorw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvinitl.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2esdfcnuj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2smmahbns.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2csvmisss.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbaymcr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjrohpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcttvaa.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tegpqjds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2olvjacvh.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2rizpszxd.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbsfkry.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqnffdh.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xotnwcra.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xowvdcrq.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzstzmeg.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqtyntn.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2buiwnrrq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhvfxtx.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sagwkyha.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jegcfisq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzijkoe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icvsrimo.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2byawmurw.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdfhwmf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bahciasg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lghapngt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evtwmmaj.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhrlpvm.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wllbnvxx.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dxufcsqd.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2yukmejnw.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpyuynb.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkgxlef.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjzgsvy.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hyprmwyc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2brjswymv.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbhhlve.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lijzuvbm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsshbtvv.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvoroebl.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lidmjocl.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxpfezz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yohnyzgv.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdgfpmf.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdkpwrk.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2luqemnkm.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcdrsfp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsvxhhx.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsguivl.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qovplqet.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qyljqyzw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vookokvn.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zoibcifl.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xljxqvcm.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dauikdkc.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwmcros.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgbjkap.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhjyobm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlypnwe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tagwrdir.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmnpfti.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeuvgpm.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxavgbk.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2czlqhrsc.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhibskd.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyqttrc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2atorrzah.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jdltlsfj.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xflhdggu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tksatbof.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2sytipxjk.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2txsfgybt.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlczrqm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfrqpnj.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvzxagc.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjoudmax.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2edllxjsc.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkbluik.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wsumynmm.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2osxhdxin.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwujkvh.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdjynal.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2xlalynqs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgopjlgr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2ypoxkncr.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kprahwcj.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwylmqpz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrvsqlu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwfqixy.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkttkoei.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xksszbqj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxobgnes.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgnkrai.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2lsameqpn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtblfce.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2kibqxlvb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2flrlhxev.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2buwxeyzn.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvxkbck.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2oojuxccb.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ksedtwze.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2niinllzy.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrvrtsq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqmwbqm.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjswmvwf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2beayfgai.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuoatou.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uworssla.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yquqsmwy.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzdwoyn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcxrdea.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxggmqkl.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqiiqvlx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrfgmrq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwssjuef.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzwvurh.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrjlnbr.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxcdwvb.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xacdupqv.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpyptcn.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlbqcwy.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgpxaoe.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwofvjq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2perolwbv.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2emcwgsme.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2yplkphlr.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2kepwyfsm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbxikuf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvitiob.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbvbjcg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2kskqsdbp.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjdfsxs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2laclnwiw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2usqazsvz.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxptpdue.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxdbfbp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ierwwiyi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slsjrcdy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2phymukhm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyrdmuz.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmejktv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjrazmk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2jopwhfyd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdxmegq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jdauimqm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2rdirjswc.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdnlnkf.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2parpdioc.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyngclta.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2adbqgjpy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2liokarpv.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbctoiz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgxmhsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dyymxjxs.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnmhatt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkpzrpy.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfojmtp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdalgspb.html


<!-- 参考信息 -->