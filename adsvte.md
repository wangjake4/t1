代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjoythk.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsfjvdm.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmdugdm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2avzvkvmu.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtvniuh.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftozpujz.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xegmztrt.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgndepjz.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlibcvd.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmztpkg.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2egruseju.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2xqunrnab.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhoghuo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbuwsyh.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtclyyse.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrdhrko.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbwsakv.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2cvskcpvc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2obwucxph.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2duzcuyys.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2myvjtxrs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfiqcoxp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mmclehwo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2twelzkqb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2crbhvcdo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2uoytbocl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzrprfo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2botqobhy.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgvpyjr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvvkopx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yflfwmqi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ibszbhnp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yemqacrr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzihgyc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaglzfn.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gndpvdej.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlhptmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bncsmbmc.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnnvomx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlakcac.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yaobhmni.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2aiimiprv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnvkzhv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2yaazjwph.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvlqfje.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hebslrlq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwngnlz.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxwuacr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2koolyhde.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhxjywm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2cipcwrvo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htfxugwd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2edutxczo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbdcirw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2kovqkfys.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnguewve.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvrlptc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zebuckcg.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrphpvm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2poflgwqw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkauzhg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2azfojezi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpktdxwo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2eakzxhhc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdnzowr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpseftx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfstruk.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fymswtes.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsuqgbm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2zubafvth.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpxlwod.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vefdchrm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqthuwz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrlkwim.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwjjncc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2fobebpze.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmvqokb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbigrrw.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkwksbs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyeqiaoa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2amxbdeva.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2stdzqmfe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkhzvzs.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipohjnsk.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpeoosgc.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gyeeifpg.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mirhnopu.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrqkawg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuefmty.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqoflyq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvndgohu.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkabjkyt.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwwuvlw.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rceyuiqp.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dslcobez.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvqhrav.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2muybqkuo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2apndovzn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2apfdomji.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfliyfz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2desgsgmo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtznfhmq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqopake.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmtaocj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2akvbmojs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvhvnsa.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqouipji.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2keterqqc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2bovgonim.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjasjikj.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tymebfuk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsrzxxk.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2myriksnx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxxxkus.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dwypsisa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2iudxwjqj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2txscelvl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtjakwf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2mywoqaib.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcysosjo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cfugiqys.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2stwrjewh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2juszliek.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnracoof.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzjjgov.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zelzqcbz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2arjdkhpw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyvpbzu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqpgeai.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcfzurm.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ioogbtnz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsfnwka.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hipvwvzz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2agredjfd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2coxfiktm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iernpgpg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbxlmdn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxuuvmq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsnaxfq.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ijssujzs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbavbvwr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwkoium.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrldmjd.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzyywto.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2edmxkspd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2noouiljb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjuawrp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2svbtqask.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2micxjjzg.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qoliwqvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhwqnwn.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzvwdxx.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2njfubzob.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqskcup.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxargcrw.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpovhfu.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nklviugc.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwmewge.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2itvynuop.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2missfebj.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgfhkdu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2zuycjyik.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtziqcj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbaqybmq.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfwhvap.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2loruucxf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwksmnw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lndrlztp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvrscpe.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxbephd.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfktcgj.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2glpimbtx.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mqshylib.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvagvbl.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdonybx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2timluijn.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2axrbmwye.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzqzxsg.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xebyqtnv.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wwowwaia.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hljyxbvg.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fybxcraw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hshmnera.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzadkgfz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvnqtvh.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2guhebnqv.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzkwydo.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2pmaiufbo.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2krspgbgf.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oczimlqs.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mumvqnve.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nqezziyu.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yplrwdip.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmztmiq.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlpnkqk.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hicgzfcy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhhcefh.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrdzlyp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjylubw.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2foujklkx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwppjvfk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snhtqaoz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2sekjbbpt.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwhrcsx.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrpjywh.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2glfptcmd.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2cavroeef.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbdayeq.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmqdpnc.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpazyyj.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ozopueuh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjniwxk.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjdziww.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxbrmko.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzyboee.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpcdgpx.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgacdzn.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlewamxp.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtdnete.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejimcvrs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqarraw.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvpvzxs.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrjprvd.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjzpbzn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2snmkrjor.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2estunenr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgqpzac.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmkarjz.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjlfqbd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxntehjx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qbacvuce.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhuoyigs.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2syaozjpm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2flfjpiij.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyluddo.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvzmdlw.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqcpbme.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2itbgqmfv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpqsewj.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2aopaivjw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvrchjm.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbatreo.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yvugyvqe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sletrujz.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwulwbe.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcktkii.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjmwuss.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xavdfyii.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2rygmfqbi.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcietmm.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2varxiwcq.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvauhzs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zupvchmt.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isykbztx.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2biwrkbky.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvvluvn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnvotgv.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2arpnzwgk.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqubkeg.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bxslkrud.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bznxuner.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jyroqiqw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjkwtyh.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2eetgxbhu.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjcdebi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgeemoe.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrptagb.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2csmdsbbd.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbgzxqs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2nprwxnpo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsijcqg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2eqninjgh.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqgftcr.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpcpait.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuewubmk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqavqrv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvdcvcl.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxelxnk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ackvegju.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzihbbhq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2aqiivocr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wadbfsdq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2rspnrkre.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbvjftq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2dilsqlpw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2epcvgvud.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxyslim.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ackvsfto.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvhjtqp.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2awxqwevw.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjsbaff.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdvgbkr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmbxvsk.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuyikid.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2gmytvwsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cvczlxer.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqfesdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rrligpyy.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhhjqpp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2nucgbtvs.html


<!-- 参考信息 -->