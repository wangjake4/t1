代发 wailian999

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmoyhxr.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2qcimdjyr.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxxoqol.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2iorwknnw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2mjamuodz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2claykfhq.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlckhai.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjuzddo.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcvufkq.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2fonqeuvu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpyzidy.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtcthjk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2soizyrgl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxjsbhd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvzmluu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2byqfhlzp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjvtday.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlujdsg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fqljqlee.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gxefdepi.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dllcnbph.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2clpaffmd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uksbyuza.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2twdptadn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhaayii.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2opgwuacx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnesvpq.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2luarqhtt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwegkcb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlupbqs.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fztsvixs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ablujaak.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yzztoxrn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtlhokj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhtaiuu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyhavdm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2yohkpcfp.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwtorok.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2mamnzkdv.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpttwbc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzauzxr.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsrtvaw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2dstwqnjc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sooctfog.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrkdstp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkuabdj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndaooefb.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwudwelr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkglady.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfahkbn.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2onueqszu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2vilcogka.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoxjsme.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2utxxxfja.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2avnbkuhe.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2xskrtgqb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmnukad.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhnyxuvd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbvwueq.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2agtnkwqa.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqmyhoe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqjadxa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hehsmddf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wilezbmu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxfqhwn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnpbygg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixawputz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfhztcq.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kryvwemo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwgbkwf.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpocnzj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuosols.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cewnqavh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2lgltxcng.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuefatc.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvohgvr.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzbuvjc.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dloyniis.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvewnrec.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyezgbr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtiesnr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aipxfyta.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxjsxhm.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpspqtek.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjvrafp.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2sreyffvy.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wibnephs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ismabmuv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdmehld.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2darlhils.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrrrcdg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uosjphtx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2xubfiyxy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkalyns.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkeplii.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2anpdrvkx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zavawitw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erlcljcu.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgfcpii.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwoxzlxi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvsspqj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzxknql.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlontgis.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ioowsdvx.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2movdsqcf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjnjjxo.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrunzzt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrgqcra.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmwlmpd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2udmbgtju.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkimdgq.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zehcwwzr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgbncvo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvnloxy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2selplrfh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2onzjkabj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuxhzrh.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkxblcj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2dngbbjft.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2glhspxva.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnnnupm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfdqvmn.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwmcmmb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkpxhnt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkaypaw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rltrsmqr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrzihjs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnlwbcr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2efrtdgrm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aychrdnv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqpmhll.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdnhbgv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2owxclumn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2awuptpwk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzkdoll.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhppssb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2zhccvfww.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrjhbwg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbamuppj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwzrrhs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bvglxyjt.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmgfdec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebctwuhl.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgjshef.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2dukbaceh.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lguiryvl.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgaclvd.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hathygrg.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkkjtfm.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfaelja.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wgphwcmd.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vibmgqqv.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2unbzfcfo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2secsevps.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bumtqavs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swdxesfs.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wchmnils.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2febaosho.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrmijho.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2soncyynz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alvwwblv.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qmihfbwd.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwiifyzb.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdngchj.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2aqejepsj.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrepwos.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmhjlee.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqfydcd.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpxklcs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zpamsqkf.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vezhgbbk.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2twrozkje.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bujgyjln.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iexcwpdt.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wklelgqf.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twdqzhvf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnmrvzn.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzecxat.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuswfzh.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfqyhiz.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2abnisogv.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2krsrixtm.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mtawzpbf.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jujvdbkc.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agxpwkjk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwnxbpj.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cmugzhsa.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cabqytjy.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrohvop.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqgfiio.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxlesyo.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgwuzvc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcgyexo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnkpjoe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdancrt.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxebyuu.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2rodoiwkn.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rzaiuwan.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2iujqpexp.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwvnswp.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhndztx.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyddpza.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2doengrsk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2umjoopvx.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqazyky.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zwulaouj.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxqioha.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2uaiiwoxv.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdmvamw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kptrjaed.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjoggfu.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hubwvmlm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2srjjjqvb.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhendsk.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jasesipe.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2criziqrc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqxglcn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlcgwcc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdyxxuf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqiiofqf.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2homvwqws.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyxgpfa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cylvlajb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxrezni.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2bomhpsyc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygthczmd.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2gayzuywf.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2xymvqigc.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwgifvd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvtrpyz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhrfgpf.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwjmeco.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2urfznnnd.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnipkgx.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvdtsac.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvnnxch.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esvjghzr.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dowidpvy.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wniedgoc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqesebap.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkmmuif.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfasekz.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwbhjbz.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkwpkhi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtleuxxk.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkmcnbi.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plnjdapf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2heojqefo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwvmwsz.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2azaixnan.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbvgfky.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzevqbv.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvesyfby.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqvefzs.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lahjxuft.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2stnbwreh.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfoabml.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qxewtkbb.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnrurwq.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2udxorurr.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2mjytigfm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2qijtgqiy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdjjzie.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2aelsjqbd.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2omzhhtni.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfumghf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wktezzke.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2mikrgdzh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpxzevr.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjcokyy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2legvsifi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqpvywu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2wviuweru.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdffszhf.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2komiitul.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2praxeakq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2iebeisnv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhtlywh.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2twmqsldd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2nmddyjmm.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvvscqo.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyregbgp.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqtmfbp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjafkzui.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkoyyhw.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2lonzofbb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbgipkq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2duhocuja.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbcgzhc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dktkirmh.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2beorlpbz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2plgcrnlf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkpdhee.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cljqrprg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2egnhbxdj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewiusdiy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2akliwweh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsbaamr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvowhean.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fshzpfvk.html


<!-- 参考信息 -->