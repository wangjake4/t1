代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdnuoff.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pixrthyp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvmbdnn.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmftwntj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlagoqi.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2tosmfgxi.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmgbfos.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2aquvjtjv.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaththre.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2racdakth.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcrvidt.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxovovef.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2mdexgzev.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2mizyqely.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjnbgbl.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2vthmcokp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrvhwqc.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqhwjac.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrydbqon.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqdrntb.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2virxjtmx.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2afuhoiva.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyiwmptm.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2rjquuwxx.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfxkbls.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tumzbzlc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ievmbvmo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2bxasvmjl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yihoujci.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxrgazh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdjahkb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ewaghtwk.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xnycofex.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxehixj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwgsjyd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxlrwyt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbegiwm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qiclsxqf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2btruowmh.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oldrugwr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2sdblqhyu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aavboaay.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcjbexq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fawrgkof.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbpfihj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfvqrde.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdvlizv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvhxdob.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pioglrlc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzfkbxl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrqqbcw.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeezjpvo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qebgzdnm.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlzxdmk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2waubngsz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrdzysq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsmjuxh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwexxhdg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfztefps.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcohyext.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2kykhdrmn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2laddgtdl.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzjwsew.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjgkihx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mlieekcm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2pybftybi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuxdzdu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuloiaht.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2hftytxpq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2laipaslb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuvafru.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsxzgja.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyifruj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2demmspjc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxjoesy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnumfsk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxpxypl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2scsaauqi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2axtnyrja.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmabwsub.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfogawh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmeroli.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhgnngs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfkgmrc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhxpwbs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoqaeyo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpogdao.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqycaphp.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhswxjhp.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyfdras.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2stsnhrhn.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuzzqvu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2owovmcgs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2afyyurde.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2leuklwcr.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2urwzrbor.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjwxgjn.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpydgxg.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lowsakec.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhbcrsy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2okczersi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmntgss.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmueqpb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zlavmpdd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxsvooy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxffrpf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2esllzscf.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2oipzxpft.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwcjbfh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puehmdot.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufussrkh.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjdkxfe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2htsrilsr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzyguna.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2zifllxgy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2eeluriaw.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyuedew.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bywqrhvf.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyuyxpj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2ypesnmjz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fqayjztv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qorterdb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhvbjik.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrlboko.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ttskjdbt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgoxruv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxltyzx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2avloiovb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2okcfdafc.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nswcqwcp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2medpwewo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdebuduu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlahgmg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdillyg.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmixvnsh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdmanhq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2apaujtdd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2twoywyui.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztishtup.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrxvckq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjfdqop.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrgxdhr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ielicvri.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2urorwegd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2xstpmhrk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmxjsqt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2rkknyaey.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfahbph.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2cauorzfo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dwefohnj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdawkfn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vsizlnni.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oblhegex.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2njpuexrf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgpdcyu.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2wokcheha.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvaqedl.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgblpcb.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcdypks.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nerinctg.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxvixzw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrgnclo.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzqqwkd.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkruqwr.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqxtkoo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhocjtc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vecgzvgw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqeszff.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2acbvubth.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izctltba.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxznhvu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2esvaaudy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbzhblz.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vluwziib.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2yivotngk.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpewbcf.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtotxww.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2dpweuapl.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqqkuur.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2iozyengp.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpepiqag.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgmflil.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtdlyvu.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2njsxfmlr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmffjslk.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2squipilx.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azmmvyaa.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orqnyxbq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioaavsjw.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2peavreig.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gejgeeyr.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2mttxinlu.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnfgddt.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rknxvgym.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qotgteol.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2visoxgrk.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxdgdlt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfrrlar.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2svjfksat.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iemcnejp.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2otdasgbf.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlzkxpm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lekjkwsn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gctahctm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxvipzs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbgbitd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2fugqblod.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2shktqqbd.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2cdntpsav.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2guijxhwl.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2nunugvec.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ophiiktp.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fisntbxq.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rplmlush.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsgcuzf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjzusxh.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2kglarkok.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqjxzmq.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmdmsdi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2sklogwgs.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwasfli.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2csfbamrb.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kklfiiof.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlapjxu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjcyqzv.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhunzqt.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pffcslsn.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxvbzex.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2ongqiehj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqndurht.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyfsiih.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzximxcj.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmolavdd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrkypjd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2npbhmvqz.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oegudevz.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzlugqp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjmiyny.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbudnej.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxxntxa.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxvsjtd.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2axjuoohu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpxyecx.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsncsvj.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkibgso.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtcfksl.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpnfmkx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqcstci.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfjetat.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znspvjse.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lokmaqfz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtqwbqy.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2jdizoxke.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqstpljr.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnooeto.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2mqaegotj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwxndmh.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwqzlmf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvaqqpux.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvywbnfs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxxkwya.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2unpusejk.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dckglmpz.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2clspkkbc.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpngtqcd.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmgjibm.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2udjvfzbu.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2vxogbkbz.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwatbfb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rputobfb.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzpvifw.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzgkoca.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2nlitmwip.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2syowyadk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvgdxed.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2nirtuyaw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmkwzry.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gcumdhvy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhiczvfs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2djlfinmn.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2utfdhzly.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdlhser.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqqhdsv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfflcfe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2xivnmmtx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2johvtlop.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjtjopb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcrqjou.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2clnfbofv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cabzvkci.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tumhamkl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkdeuzv.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwjwnim.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uujhoarm.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbcjpiw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjcyfdn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zauhofpt.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxspyci.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjlvgdx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmpnkjb.html


<!-- 参考信息 -->