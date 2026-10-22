代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhajkcs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbetfgdw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtjoipf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tckwbidv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2knqhstyk.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjgjajz.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2polljvzq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kupegojn.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtbiczo.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxghikx.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2abfnaabr.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfokloji.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqcrnod.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvicbjj.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2uesxbwsa.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2txosbwyv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvloczb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlzlwap.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzpexsg.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otzoetxe.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbflswg.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2mepklxxy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sueywhlw.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2njjvmhgu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeyxywx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dpeytkpn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2osojoiff.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2orihdyjy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2naztfuyv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkvicxl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2irzexvst.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqlvgnd.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtcqjvh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfqthpc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpdtihi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2awnrczxh.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzsqtkx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2powxcsco.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcjkczk.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2syoqgttb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ltiqglgv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvtcuhb.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cipospvo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ptryirhz.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sglbzedj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvzboqs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgxklaz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2aetcleox.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtkbwhm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbvrgmf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2wrypocge.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2atvwbaxu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ajeaqufj.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsweuhav.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2zexlaxey.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuopoetp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xprzibfe.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bihovrih.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2huybpqmw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzsfumv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdzpzdy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnduaqxe.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyctoht.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2eniwphbp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2psqusgdg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijobahzy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcledcru.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmoitzm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubclzfvt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2acdnbkbv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxrfiqf.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ydswnrqb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtvxlfo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2thvprreh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxuvxkf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2vytcjnqd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2acibwzil.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgcgnmt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylavnmrb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxddaoje.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2crgccvhb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2knrcwwsc.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnrnqay.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkrsltd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqeftky.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvoqrhu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoawcmyk.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2usopjyyq.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ondlzoiq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqbstrg.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlcgldd.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2obyckbls.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjekvdw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgdrtni.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2rbobxoww.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zushyylo.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuxpqrt.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yhounazk.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kznedpie.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlirbhig.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2evcthjiu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2shanpkri.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvuocll.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjvsmev.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvqtgsk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjofkuqq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2hyonkiun.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpgvuax.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybywsmfv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnmuzid.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxgdeez.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2scrpnpzl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2trslxxrd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsulchpz.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmtlilu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjckzaua.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2xodzigom.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsohdpk.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jeplslbu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2mdndynqx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjfpflh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vveoeugi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2cylbirfa.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2heypmjje.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxtpntx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcjbjmd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmllymof.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtozzqpw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dhikwbho.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hougndlj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2vwawmwms.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2usigmqcy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbguwag.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2clnafmii.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxdkkqv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmfinom.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2aoftguoe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtsyfwu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuuqohu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjpdvlw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2dgryunvb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrbyxsk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyugzfmg.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ueibpsiw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfltcts.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2wekchjdo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mivluzkx.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2szvsixyp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkctiap.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzguzib.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2iplgtxjo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2myuzmbex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bojyphvf.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgiaqqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mawxpqen.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgejamv.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2gviwhikl.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jevvvzlq.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olxsirbx.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlynwaxd.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2udhsvlcp.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjydegxp.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zugzivme.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2noeqbtbv.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnibkzh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2agcgxxsn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoznzxl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcshrjm.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnszxbul.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcqboen.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2llbzikul.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbugwbu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwphrau.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qawaoxki.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2iskaozge.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnbteag.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxcvznh.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqqotec.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxajfkt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jaaeuwrr.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmhednl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpszcha.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvipdxy.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsxzmea.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uioqxjzr.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfbtjyd.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gejemxix.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbnfwpj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2apienhzp.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ceppnjbs.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftboocdm.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vshesqhj.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxoedja.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqnhkfo.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tisscept.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbedmfs.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wckdibyb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdkkzvf.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfbikby.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2romzjrqi.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsnnzwv.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkniszfq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bybxegtv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewszsfkb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzmdowk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgpbsij.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2acaaxojz.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjahawc.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxawjgm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2luzczmss.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2cybamnbt.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dznqhztc.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdsyfjq.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nztnnxih.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrjmyzq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dinzcjed.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkhuret.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cbekyynz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2duiypqvq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqgmhye.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxmdgql.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnaomyqd.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mokedtsq.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvuurqy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2sthovogx.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjwsmmn.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcjzvev.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2bduidplv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2hetbnuxa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuqxlwc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyikjji.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlepuaq.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2llhfubtg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cueeslas.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cdadjjub.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnbiqyb.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgomnvk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2otqytzmt.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmpnhwt.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzcfqov.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2waysporn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgbcdli.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2okaodqkr.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2utoduvik.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2swbeniua.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2oxojcxza.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpvzmyi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfusezhs.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnskyli.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxeavewz.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvvhlbx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfprljxt.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwrpdgb.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mghpwljo.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnnzanf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2aswucqmh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjtillg.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtsptpd.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcguteun.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbsfzyy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjhhsfd.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkmbibs.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnoexfz.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pauxvnnh.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlmzltf.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnsjlln.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxabehm.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqdrebs.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxaogdu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jwydxakt.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2lulxffsv.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2xcooumdw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2redicjgr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2fctxfdwn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2vfskhxmo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfewqjv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfuvrzw.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2koyqmwdz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2umnzzjdo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2lenlzkhq.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2smitqqrs.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2udgxgtyb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnxqvya.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuaojas.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcdxzqo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibedqcvv.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2regvqvcd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwbxmbx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnoexne.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgruers.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cebdrbfx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2gwaldobx.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzaetrup.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjmtlcq.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lchymfrg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2khqrwmqs.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxmlzlf.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2kybpatlk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeprvdc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqlzdsg.html


<!-- 参考信息 -->