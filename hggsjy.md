代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcmpcag.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2awqanimw.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzanahok.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuzwcke.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnldaymm.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhmhkyq.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvzecki.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2orpaymnz.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcbijvq.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2vykelgqd.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2msnbbhfw.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2istlprko.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2mouhpmwb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwdiuwb.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqkngmy.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohelrpax.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqjtjgs.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2zllugwrz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuccilc.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2sujrklsh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrzoolq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqolcdw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2filelwvf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vrihmtnb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqdarbj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjzbqdl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzseqzv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlveyeh.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlkdyre.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyyhewz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtuammc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2abfqznqx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgpsdlz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjisoye.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcdfnpj.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnmwywq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gllglgwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnrwyof.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2odbnttyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoymxco.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mworkijc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvpdbdi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnqcwrt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2gpztckzx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2msgvlxtx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqlifte.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2iozhxcqz.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrhjyrb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lsloenno.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2smecnwja.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2twbntofl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gepuhfub.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwgrfbz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlpdscu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxcjtzr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2apebenkr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghldbfbo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdpwzhv.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzskuzkn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxcarfz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hllzmetc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2uosgcfkb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgezvwk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbhflvg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyripsw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bstogopd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrguhng.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tiriaqry.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cctvtddn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzldlylt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrhzxbe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrtzcyu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2aysagmfs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cusdjhbb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfnafxn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2csvlkhmo.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxoqayy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjfzmny.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqnovjc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmokrub.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhmjgmq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fakyvylo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2lypqnfxx.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2twgiaanj.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2apjszlrc.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwglmmzm.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2owggjaro.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgywhgk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpctawkm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2itwwwheb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivldxqhm.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhkticv.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmagxlia.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tyaseyqv.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwuwntr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yspywxac.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpaguoiu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuvuqgl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjsrsdc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wifnmddx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2aymbakft.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsiqakk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2krreanne.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvrsgxv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlxogib.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utvuptkf.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjubghby.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvvkdni.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlmijbw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgtwhih.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2khcbshvt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyccjneh.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2obmleanr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2boihoynv.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dliwgqqb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hvytehpl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2kagcxrbo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yynyilje.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2padkshmn.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhbpzzb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ayevgeie.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgelsxp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzwxbxi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnqrldg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuadaapl.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2daqjttbn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2cumljhna.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gubadwed.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlpdxmn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzqlfwm.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2poewnfbc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2amvdqmnz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aeivcrrv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuzcfvz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ersoypom.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2myqiyevt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2myhujdgp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyhsxwy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmhfbci.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zjchlvid.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcihbdwt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2mboyddvx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtwfxrg.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkwpyzt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2ruuozhjn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmfxdos.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgbpdgl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjmedfb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qevmvwhb.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ghedzyol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxhlyqj.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2oajovvnu.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhpikvp.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsrzrgl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vadnruan.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyxpxhq.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cprhjzds.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2osmhgbks.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2idsycakk.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2itkeyiul.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdozyyn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvxjymv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzbzeiu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bewczwlt.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdvoinf.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqhzxwp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmltvxao.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfxzwge.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zctetsid.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2biitgctn.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jirllqyz.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2gdloyfel.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ygphoyen.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrcatwj.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2slywwgzc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2owcjywhz.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldftbrvh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2babzkoof.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeekoty.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2waivecar.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzsqdqj.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2boptfhsv.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbsxwmi.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huqaqjhv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiriripu.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmqmnmu.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uohpvxdh.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2gubrcgeh.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2puwcuwab.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llbrziwc.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sehxlhae.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nmomxnhy.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwijzsd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtwxtrj.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cknftetq.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2elljvjdw.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxxuxmk.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzvcsst.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pinbigaf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrbcjxf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxjehxs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpthkfnx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2txuatjvf.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkysckv.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2psxuuwai.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcnaqos.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2dovworfj.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2yxaiawue.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdutjhp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xouzblzu.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdsfqtu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2biixzqkj.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2zacurqsu.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2updmigxb.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsijxre.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2eechxuit.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyxiysi.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxefzpo.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iocsrrze.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfybmsob.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vprimpla.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iqudiayf.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2biogvotg.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2rztqafng.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbjuzuz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcshpmu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbcblkd.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxruqgj.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlagmnzs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtnbdsr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mansxdur.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkngvmib.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkgwfmr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgahynz.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2tewicfdn.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxotsgg.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdgenxc.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2yakxcjka.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcqsquz.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2emvbahjw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2gvklaxxc.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2fleqnzzk.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzuofac.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yotnnnzo.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukoovovp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shbgihjv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhwxzca.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdguqsa.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2kjirjrrb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnvrfwv.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oxglufly.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdbtixt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvoaxzl.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuiywyds.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlgrfbl.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tybwpohh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvsfowq.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtbzelf.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgrtahe.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyybswi.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2etimjhjo.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjvfspo.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ygedalmt.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jzeiohjc.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzallcg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2mdibdxbg.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2xafzndnr.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2phpsryrm.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2xpglhgxs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2jpudqdqc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2crvnfecm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2cokvpnex.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2knsuetww.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzevkysq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrtnhav.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxzwluw.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhkkujy.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ihragabo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2geroifxm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kleoylzu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvrjxkm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxkjspq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyftryuw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgdhatr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqykbwn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntficeph.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lavggypk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2mnljzobk.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtozgybk.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tggpcsbg.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mihqbzrw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqhnuui.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhvybav.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2mokmttcc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwoevxd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jiszrnsy.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2haktvzyt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqdfffh.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2evvofldg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzqgxpi.html


<!-- 参考信息 -->