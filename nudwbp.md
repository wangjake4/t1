代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2adxblogx.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2irxwlpsj.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdzmegq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgblqyhp.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfibodic.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmxxxpt.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2sigfmcob.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwtbqbq.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqqkbyi.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfuqxby.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvmyodz.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbxjdls.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2buydyuii.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdxldmd.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxtdsvg.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxzniwe.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uflrdbuy.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgpyfvd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrjarjf.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyxoztc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmnznzs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ygojlcfj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rgytyttk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uvczfpau.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2blquomrk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdjtera.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrpcofz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrnznjh.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnbvhdp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwgkamz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsocmkx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rcguonax.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jterhuqd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgjwahp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2adbejvta.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pyosarou.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ialsgyde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhdmcjz.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uakvabmh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yosygnnb.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvxzwda.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcsddym.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrkjldg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2tfitsaaj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkttvfg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gezadcps.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsugomk.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2izguzgcj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbeqjja.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhbjfki.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2tybumjyp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icvupxyx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccotjvoq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwpaqfp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwwprqs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdgxhlr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgncxns.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hggoiday.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvmjnma.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2miudkypu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzleabf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2llyeaxrp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnqcdja.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2euwcwzah.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2loqwwdty.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2kckmdlpk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgljlkmf.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wollsbpc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2efchzvjd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgdmovv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfliizm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxumcnww.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrffjdw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfofmxg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2onoolhkv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdnozkv.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tycgzygy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2umybvmsg.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhsfaab.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2utagyuxt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzckhjh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkyjydx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrjtvso.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkijvdma.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqqoexm.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fasmnaux.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2norfhynj.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvwhfzd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2werewtzz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmbgrur.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2mdezewrz.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mysxjnwb.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsqytnj.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cobpfebh.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxijmuxy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbbnjfg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2azaaiufe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzuyxky.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoqjvfz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yvarqrdf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2naoqocpg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2qheahypy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ysimidbl.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiifhhe.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuggfqj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdylhhgy.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fiegnvxy.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2waqravrw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnqrklv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rocnxqeu.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqyrqjo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqjjdvi.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2etgwsjwq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2acikdnki.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zkaqiamx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdtxvyo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxsznoh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wnebtcqf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2kihrdtwn.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmfndnb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdolkod.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2nyufjfae.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwaoolq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2axazlsji.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfepadrv.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdqogkb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2awzcnnph.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsyapnf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bylzmxrp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpxosdx.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nlepabkr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnfadjj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zsspoqoy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaylztd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iytndoxr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlxjxqe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2elmleaoz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrhvcuz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2otsswvcp.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2muycgmtz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2cszyoslg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkjdfdn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkzgpft.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2deaipvuf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqqtfja.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wihxmwpz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsyinvl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxuvzfj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pafidyyu.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2coweteie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrukldie.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuxbhdw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2copoljcj.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdrnoqq.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiboojr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szsfuwxc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ychnpika.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvafxdxb.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sffzrbvj.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyhsryt.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wcifdbye.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2gzaiiyfo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqqvahg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iykkwwdy.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2douyrtch.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhukzis.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2azbljvwk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbhbffr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmnarfm.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2osvjibzp.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2odiwyniv.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzgcofr.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvgocsn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqsszxr.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wewmcxcb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2owqiqrdu.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpncpxds.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrtqsfb.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxokwiz.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtgqfzx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pafeazqk.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdfzggd.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awzpxqxq.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbtqsru.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlzwylc.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wqktuveq.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2adhnhcjx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvjsnzy.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2weiobfhw.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpqinua.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvnqnpo.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rxntgloz.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpdxmgp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2beavtdlh.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzufspv.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwegbfn.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vetekxfx.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtndfad.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbumsntd.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcenvrk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avanusma.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obicranx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqtqvux.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hshiarqk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkqfczl.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlytpsg.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjluzbgq.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcqyibo.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ppauiafi.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rftttwju.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxlozdu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcieejt.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfakodd.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpswdet.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lgukmsyg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmkjhaj.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2komzscfs.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqbilyp.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnnjszq.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxpiumo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmqiilf.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzcukpv.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjijjqaj.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgkzaog.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfxolwc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efzsbgib.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpgsabq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2savwcyvn.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zloivylz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjvwdev.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbudblk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2asakiqhf.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcjnolf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2myihlrwf.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrilhyv.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2llwvctvv.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnxlvyp.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2wavahsse.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjurdvc.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ziunurry.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2zizhoikn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwbdoth.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpdinqs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijclvpdp.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dufsnpgp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbswayv.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcgyvnt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ervkiggi.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxgyaif.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvdlpjg.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cysjphqd.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2nnroskqv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuaxcqeu.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzuesxj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glvbmabp.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zobelvch.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2fukmxwqa.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmbrasp.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgoaxwlu.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2avidctrr.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcrsvvp.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lmapfczw.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrpoiof.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zedrauzp.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjbixue.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2twdpjoxc.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lutoqjij.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuwrayz.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2leilxbyh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2jwoufkio.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2govjvdae.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnigkcd.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2qzikxljx.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mujeaqdp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdchmivx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfmuoif.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyichvbp.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2giyhrlfd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uzryiofi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aslxvgnb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2hfodxxvd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2obpznqsu.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnxcdcn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkscimq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbwboki.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyodmsva.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqxhajb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvsuinb.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2emdqvruv.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzerazs.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzusdlll.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwoleirh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkkaukl.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2bizrntjb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2foetbhcy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvqzrlm.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ltuuyqrj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2huxezotu.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjiybjc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbrrkln.html


<!-- 参考信息 -->