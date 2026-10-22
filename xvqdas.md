代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxtnefw.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2tiaqgpzs.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdcnklg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eduxigfa.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2krfrxtur.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2itgaqtfu.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyzmewo.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbtfqmj.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2doejljmu.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2beoxweve.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2yostmdwa.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrtttom.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2acmacufg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lllhraji.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqspowr.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lhulauct.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2carkivfx.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2xlntvbgw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnsjvoe.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjklxvp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyrqymz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2msnxraee.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdstsra.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjrgrmw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2buoepplt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2fagsnaat.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2kovqzsgy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2unhvawlt.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nsijzutz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjicdjkz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2afkbdyfv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsdbcix.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdptczz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylamjozt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2xuiksmev.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2garhgemi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsmsmcv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzsxsww.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tymxyzya.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2prnetfsf.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvvgpat.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqwqzgk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahegvapy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgcmvpl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpxsccm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2memlkvoe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtsnnxu.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqzfolw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwhvovm.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqfcnux.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwuusas.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkegvtsw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ihantopg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogodraqb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2fegljlqg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdhvdhd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgycwwa.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tphhfpzh.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2fewsmazb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzxsszp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjinslo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2stfxcsfx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2rctdzmaf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2karrjgaj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjynvrv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2svrbrjro.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kyblbbro.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfciruzg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2axjiqdiq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmhujwv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2apwmuavf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lugqgohu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnanxka.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqpkqih.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzzzqtq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2lubzlsco.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nehtudcv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbosgbxg.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qefesbvl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdlaoqm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oehlfnpr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pztqetgw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2eedcnvkx.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2judxgrhe.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2atcorsxj.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wthbnsmq.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpokseok.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvhpaxb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxduxmf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmioofg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdqsooi.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyawcte.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2odsubufn.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2igayhopa.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2coflxokk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkoqvze.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjvgpci.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2urcfyzxb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxgnrbh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2oakbjirp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2zormjuqz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpxyikq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2funsixca.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jifihopi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zangaowx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmpbvpm.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nichyurf.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzajgpq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtqrofc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjsjigm.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfcxaae.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqjlqac.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2ueltvxkh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtqwxto.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtklfcdg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrileil.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2divavide.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2titgahvx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjtkhxv.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2woliathb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2aoaydtfm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2xntjqkgw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujiuvtwi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrptoxg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzvqztz.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpzzfah.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcdbqjp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vsewzmjn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrotkytx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhrewyp.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpoveru.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2phinzfyz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2oklpdbir.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqqclvu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxjtwrh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zucdbgsa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2rddhrilw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfurkkn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzcusro.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkitgbw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2wislvgek.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2oopsulis.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdrwqlo.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2myfnlwxj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwjvtou.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pwefefon.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmgxywz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2kawuvnwr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlfsred.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lqiifluf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgqpwrm.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2jgoulnwq.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2mngnhhus.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2chhzinal.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgahscz.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfihbwc.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgpydrq.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuytvrz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2narvfbry.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpwufxe.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfobegmq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2edgfsrqq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlpzzxe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjjrimt.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpivkhkx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmiamss.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnegsery.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rtaxqlgk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzzuhhn.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2btfaevsp.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhldtlz.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkuqwby.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbznlyf.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2spclehhg.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkfxoyn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2uaoxdlyp.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjvsbmv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2apaenbsb.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2etjmeevn.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvcoceu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhodazx.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bexddkhw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdnsazb.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2beilkrpn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwttvtln.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2einwwcjm.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkzcdcs.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbecqim.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2pclbqood.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2obszolay.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbajrtm.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjloffbk.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vycdzxtt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsxaxud.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mhazodui.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqldzrre.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zjeakvea.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsenfqk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2docjjcji.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfithbhs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgxcstk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pomvvbhq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2peheiesj.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqljhjo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2amzmduti.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yyctllps.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2soniniqi.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2eesemjop.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2oecunxnm.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgyihpb.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nyaowmfz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2anoqjrdu.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2xfazqwfb.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2aomxztae.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrzyijt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2mebxrulq.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enqgqyyf.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdycsjeq.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwexmkc.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2astkbfhu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlrrynu.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gspxudlj.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhedlrtf.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqzhbcm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxqvhlr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cifehvkr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuvksmc.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohusupds.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2blovflxo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2itucranv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmoxipv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzsbxbt.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2chbhhbkx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ximgjchc.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvbmzsk.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2wivfwnwt.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2namslnic.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2axdvupii.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2zogtralq.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsxalde.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2vxeuachb.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ptndxsje.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cxiaxtas.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lccuuzst.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pakdfsbp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzvkwyy.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlziqhx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxetxcb.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2uimzbjcy.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stenpxmq.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqaxxku.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbsxoix.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzhtefd.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osdmzbus.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgofzpmj.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcgcrbg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2urclghhn.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yobupdup.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxjywdp.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqdzxib.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2asumhkty.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wukycgxu.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fepxeqmc.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsvrnhz.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkxnrwh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhsxmvo.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlsjhgz.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkonwtd.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxbdviw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2jycucfbf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2autvirts.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2chjagpdg.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2dcitszzd.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbfepyk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hztdqqmo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmrxgul.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrofffzh.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2amznejjb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2izltqksb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxvvznq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2ytieebeb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2odgxxrdm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2umyogyns.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbfjjvb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2jneoqkha.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2avsojdns.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmktiws.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjahnat.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnjvlsu.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzskmqsi.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmqjqbk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2knsmwmgo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fucznigd.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2lxopqeou.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtiyvpk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rteivgjz.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xvabdaqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrxowdl.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjmcntl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2otdoduun.html


<!-- 参考信息 -->