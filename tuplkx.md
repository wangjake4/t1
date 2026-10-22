代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhgdhsw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvstywom.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2eweeipeu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2assnjern.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcnimca.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnwrrrl.html

Py:   s.splitlines()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjgfuew.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2shktiytu.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyoagpk.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2effeavwr.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tadyirna.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuqghiv.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2armpmldq.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2dofvxgze.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2tylpxnfl.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrbrvnz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbvyjoa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agexmokr.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhudyka.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2awgnvzdd.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvjixaq.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzbwkbk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wqiemrka.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2yixndaoh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbskwdr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2moqjxkdv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vodahrht.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrqleya.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvesucj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2gvoeglol.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkoiofn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpazipd.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mrojnued.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtwwrkq.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2onklzudo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yowtuopc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrwpsjn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2zufzjgta.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgynpqxv.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2rarsqhpr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlesnlz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ryccgwlq.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2atgpmpbp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmcynyn.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2okngjrae.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrzmamc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mkloskmq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2rjannsxe.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2qekhinne.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2pmapjpfu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfqzkdr.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbpijdc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zpievykx.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbnojye.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqnukys.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnidlxhr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxlvfnw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ixiwymss.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwysfknm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cishikwc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2fayfvakk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cktflwie.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzybjhr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2krtrnimx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxninnjg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2crylupop.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqizgltx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlcvbhd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtmxdvf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2plnjnetl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jeetxhfo.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhqwszi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjektop.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzufwws.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2csharial.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cozlzypr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2kghdbyqk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxwgslj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjtecqc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2posshsja.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpxwpbg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxnnhqu.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cidjhoic.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqlfqbe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2atunqaqd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2laaclvzi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyazmwqf.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtmajew.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxmozhz.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhumqwp.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywprzadp.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2amotllyw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouulddhs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jikvwcvl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmtekyi.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsahxnp.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2igjnocxl.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2drvjbiua.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vschjymn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwwasqz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzoxaovb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyylxem.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcccblu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2abwetmxw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwqlwmj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2klqxklxu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2beizzaup.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aifwdmkg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzochgqp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2peqcauhe.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oppvkauc.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dixxurcw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hppzoyvu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2moeogsqb.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2madmbczz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnwaewa.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpbrpyz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnetfql.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zeoijqip.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pefhiyer.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2dopnyppn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhwlnlu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2pksdbyyk.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyctmxa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmjpusj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxkgmhq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jriwmepf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2plpiehao.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdtqhyf.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2epxrxbbu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2vvolsowz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2prbvpabb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2asfdicop.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlrjpxv.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2paiprway.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2efnyivoe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgbmzns.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2iugksmig.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmyzivv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qupppktc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2suiuyhdi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gflhkuth.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2izkxmwbz.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fvflbgba.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2kugrgdyp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxwkupi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2levigwxs.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjosrdu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2uldopdos.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgcsbpi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2toropqqf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzojhod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlgovvg.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgaabhe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khbmqcpz.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2uslxscjm.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2xplstuqo.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pweaqpwa.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2micucakx.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmrsjle.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rntrirco.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyhhema.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nchesrdq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbejaew.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtkufpj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqeirmv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khxnikuc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hccivbac.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzepnqkq.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywojcphv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqgnwsi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcjgzac.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iykojtcs.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2njvxrscf.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2eecpadwx.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhhdzko.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtccheg.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2koblgona.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2feyzhkrz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsossik.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2curcptkm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpadhiu.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvcjean.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzhwuef.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkaalsyf.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htnjiyhn.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzxxvhh.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqyyjdn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqaggcs.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrvzyts.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lryiffvh.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2zzknbejr.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzthtyx.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zefjgpmo.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fravipja.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvyixua.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tgykpsvt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjswppp.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dpebmbol.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wksdiswx.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2hewpjxtl.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2bovmlvuk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yczesrde.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdefoil.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkiuflnf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aghzbbhh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2rhiswaye.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwdkapx.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2sfeeaixm.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lxccevwj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqwrjju.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2fftjtkzr.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqhgolp.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2poaenhqk.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2edrvtgnc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vghluymm.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtujjly.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsdevgh.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qcelbfsi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzyfuza.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdmiafz.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvqlgra.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfsxxoe.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkethle.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2esdgyiiv.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbaqhfx.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbuzcaw.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcqjoqe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2uljtpiza.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nynjjyoy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjxaatg.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grwbkgat.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmkgbut.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2juglredy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvtlbni.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtbzuwj.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjzunxx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehibwbms.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2lvepdqug.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2fscyqbfy.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2meolrsqz.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2apsgrboc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzjkudj.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2fswnealz.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtiaugh.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2lfffqlqn.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrimcmj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agetuhig.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koioewll.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnhtzqh.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhjimnb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2urfgaibl.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2imdpkmon.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtpfcyr.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bblmetkn.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtqcmky.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2angyafif.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqvfdhs.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyydfjyr.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yntignln.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2roqefdkh.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pwiouokr.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhlrarq.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkgluyq.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2oddrjypb.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2zonavzbl.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2bhljuejf.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hauxzzvr.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2fomgywgq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2trfjkfre.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxlmafl.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2soyrzldx.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsuptgm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdhufrm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ftreghlo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2midmtesf.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfvgtjm.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tagxzlnu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfcrqwe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsawzwf.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2iswsnoqb.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzocbgb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xezxkknn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knzrtywr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2tltxepvm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qktviald.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2eushmiyg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbwsron.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2vhukhdjb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsypojg.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lvetzmvs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfmkacb.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbdnupn.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdyoffa.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjpzudt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtpdqdo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2axijqysn.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2skorebmi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2krglrhms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqsvspm.html


<!-- 参考信息 -->