代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzncybq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2fasjohgo.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlbczgl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuwoqdi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmjyyhm.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2ipytcwoy.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2toosyeyv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjkuhrd.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2smxqhwsp.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyejkuew.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvazxbj.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mulwrxlt.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvuuyby.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfvjhbu.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcekctq.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhdkhnj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuptbly.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zqisvyco.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyxxhiu.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lutyicys.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifixztik.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2vafhjvrn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcoqdyb.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2tsegzsxe.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2ezslwypa.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqektet.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mchgjoss.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2lvglibzo.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2snnttblj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjqnwxj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtysnhr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kbblxwkq.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lfklicac.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rphoegwb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzqawss.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bmoljcfr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wehllsau.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsuvzaj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfntwopg.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyndurz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqxulgg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtiqyfzz.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwtcglw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmxpazo.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sazewpon.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2uozwrvwy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aghxskor.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2cetqhupl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjmyzuo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2noesqjex.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkgxesy.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2brtquzwe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbnwibs.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2umzixnjd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2wofwylsk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhqzsfu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2biovbyze.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckibmtib.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2guynqsfg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfniyxe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2izhboniq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2purfcnqt.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbqpnwh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2hevuufja.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2oyglrsvw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2alvbdqzn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2xporgcmv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjjwtjk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2khrymyzp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsanmozp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qlltfskz.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bvuxybod.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpjyqgr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhedckxx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaodpkt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfknazsh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2enwahxgj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vplmbfnq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2smjuwnqg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvztxdt.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bplddyks.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgttsgtk.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2arvxlrmn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypuchuqj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzagjkd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yffmleya.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuspjcy.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwpptve.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2imqimgwf.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2flaqkrqj.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnaidaoq.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gifitelj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcilelf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqrgjwu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2auzdgkov.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xidvlkdm.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrnlzfg.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjjgxzh.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvjujwx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdhfmfp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pavxgntx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2adkhzshk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxugrfq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsjunpt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnghrre.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2neigyjla.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpschdtl.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqkbise.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2udgnjfbt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2meygpfgh.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2yaccxxza.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqierbv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlklnfwg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvraiovz.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiseiymv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhimrbz.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnqqgxx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkoezwl.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaxdwxn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyzhnsg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qczbairo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkqafdp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2kttmqybc.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjiqxco.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fihtluhj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbpicbx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2apudgmgo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnbracc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oceepeza.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tncfduga.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2prthodfp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfnxcst.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vevrygnd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2veyyaojh.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2crbkzetm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbeyfygn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wrawwdjz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwfpmqt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyxzceb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyejqer.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgveqjz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqweilbv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2fracpeet.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzasygn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2kchlcrwo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2hndptenw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rhywnbrj.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ualftxwc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2gskflbei.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2srlpibtd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2gynvyako.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtxcxlu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vaipbcin.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2esmknjog.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2asehptfy.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxfnftj.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdnncko.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oaaattay.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ocirqehe.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olxeoxwu.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwijsrw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhogjxn.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbyujoe.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2twuzcuup.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xswolnay.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbwoibg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzrvaru.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcoxfmdo.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fanhnpgu.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnllkis.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvzwozf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2seccurql.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaxykwm.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vumzyloq.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwprqsgh.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxvsigc.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kviwbcjh.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gchauxxm.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyhwuqf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpyacyv.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnjugdc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjzdknh.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2uxihhrjm.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcepmdx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgezinh.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvklyfg.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmrcnbi.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfrdrlu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrahkcs.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgzyohk.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxugigb.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2wsokzchd.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jnembxko.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jteuihsv.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtclsky.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnmbzqv.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcsiovw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zykwclrr.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbgkdnu.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfxedxx.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqarnlv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2pempdurj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oumuueht.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smyfcqhv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbewplp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbbztrp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpltdyp.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdjxula.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsexkme.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tiamapeh.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmxggum.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnvkxyl.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kaobjukw.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqufhpq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpsthfd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2eumwfjks.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2sabzpyas.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmevydw.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtzqqhz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2tlntneqp.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2knprkbdl.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpebsha.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2osagmovh.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axrmfhjf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rjejtwsm.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvyymgv.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2osgmcxed.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvclzfm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2vlotrird.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbccmcz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2svszqijs.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnookshh.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivoqjofp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwydeyog.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ffikbque.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfkqwut.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2hyenndju.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2orqdzcsv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjvaobo.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhunolp.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqykytx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpomijb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmihpbo.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvrkyzq.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqduhhh.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2yitizthr.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzxqnqw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2giteariu.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytujyupi.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrquqzwh.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2embovpvm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvyhbcl.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqcghhl.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmedvlwf.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2efgkwbbm.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xihdcoox.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xswtrkqq.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqmpeks.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iipdehgm.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxeqslu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytckcwne.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhpdezu.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2klwxihwa.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzzcvlc.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozijfmrh.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2clkyrrtc.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpqtazr.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ctaftcpm.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2swdumrbk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2aethoshf.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhfadpc.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2anbtjomz.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ffobasqu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2htuyhpse.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxritmg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qogprhot.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2wtiqniqa.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfppvhlc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaihhoql.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2furomwui.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlnjnpb.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aiiixjyd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2krogrrya.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zebfbwua.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2djmifgla.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgadrgf.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2vadybjvt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2wheqrdeo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2jeflihaf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfpvxww.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ygallhbf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2gtufakzq.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2bppaxcww.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbsnmrh.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmfhelv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpbhpro.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrnkmik.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpxpvyb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2aeopegua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjtqthz.html


<!-- 参考信息 -->