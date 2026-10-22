代发 wailian999

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2ceegjqpp.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmpugct.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpjoekn.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhkkwjm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2rohxsmgo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyaxyiw.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmwjadu.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2usxpdydl.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2buxxxngk.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2jhoropfu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmweazld.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsicwep.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfipxsn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zldjpvrn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uysxtrtu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mevmffot.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2amfqgnst.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2jxosqyne.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqoaxwp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2oaslgvjs.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jslrgjgw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cubkopni.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2aixkwgfv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pnadosjq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzodpco.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpvnues.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2buogngrk.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtdliez.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvggflh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzeqpyp.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkqunwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lnaleeew.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jryewfuo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2uykhffgm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdytomgu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2svhcoeid.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2aidubfov.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyzcaqj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxjcnky.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsortulp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dbowssky.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcnnxxl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2evpwxzvs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbbwhhv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwjdfse.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbjundo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2ervudjra.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2desumzip.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2azawsuac.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkvjkfx.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2owjrbdro.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2cywyykle.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlcmdvm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjrnktr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwyggui.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkgidtx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojymjqjw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkuwwld.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrkfszo.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zusssjau.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwsmnvc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcevctw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlijbhfu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpvakbr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkogedu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2msyfmuzn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2folqorbd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdvbtmv.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2waaxlnlq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2esoehuwc.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgpoacp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gypypnzw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xeweiuin.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dtziatdp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfvxdiz.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvfyacg.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqxkjhx.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kiladtxm.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlobqjmo.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2etqdfjmt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwecxop.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sumacdhp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2iddgxyco.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2duwxvyok.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2abigbfpg.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmwkelc.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhdodgs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lucvvpyx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkfyofu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsftrvn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtmdiek.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqxfnrd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcllqhyj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2slilvdbf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmhymqj.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyxhxtk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2knbyclzt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkkrhib.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kiglkcei.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxaicri.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhotjxq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfkhymp.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2nywohbex.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpicxiac.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2emqbbnfu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhtcisu.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnytodn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkuvtyb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2euvfbgaf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnzjmqk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfuxfat.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2adfocwko.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmitssz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvbdmxc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyflvdc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqaqfkp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlamwlyb.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aryluqxu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwlndph.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bklerwdo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgujzjkz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2adkaqwde.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ullihtzz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjeexzcm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqdgrsr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2teaxflcq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pizdeiir.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvssipey.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjnudkn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ophntbvh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjthgma.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtqmfij.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2rncsmqvy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2ouheskae.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xeutluit.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2isjmpwpr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2insslbev.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcjnhnd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxvoadv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2euwxivll.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2altfdnex.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2mksugyeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lvczbrvp.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuugmcw.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2oatqajvg.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpadrlp.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkjmvqc.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhsdmlr.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lelzauhb.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2znokbsnp.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rczzfukd.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkrwbsq.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2welyfhzq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2nklegydp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ygomhelc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yotebubn.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhmbkse.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjjzhwd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2exgiccht.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2btpyktwz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2noioergh.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zwydllmj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhfbzzu.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcrfabb.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2usxnyyfn.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdcwtfk.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcfxwol.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjmooij.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2cykxokri.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2edrharep.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2efpzozry.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2puheqypn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvdivvt.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tanuurvz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbxxnqd.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vegfiqqf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbldtexa.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lcphnsvd.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2bivclkuq.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxczoql.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyxiqqc.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzqftbu.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgezuklh.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxplqjn.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxhbhxx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbzsvks.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpazelu.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qcseqjhb.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlqieps.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxqdtki.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzopgqiz.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwuoisl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhvmvcm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irhkuvom.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjjyjoe.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvmtqsn.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2djevrrzc.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2htvfdexj.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2erzehbis.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjscuaa.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzvhssj.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdmpfcq.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2nljnevju.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkxmcdx.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2edpisoon.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rlolkran.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zekwdoie.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2gisleaxe.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwsvvxj.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oadmicpe.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2itaqbqeu.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhomrbxg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdixmem.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbzjebg.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfneyxx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjewrhn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2hskjmdjs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdaoplsk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhcsgdz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggiejclv.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bibbtxww.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjtlkpn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpjluvp.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdejxoeh.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2xmltbfty.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2meybhgju.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxvkolz.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2fjofmzof.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkaraaf.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcvndoi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnbvzqn.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ljddiltk.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2kfenivmd.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2sjalolje.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqdznla.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duuefhty.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlublnol.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zokigetg.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrawhkx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgqfumm.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwbllyf.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhfluer.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzfusja.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuyegba.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efvrozqv.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkxkdfv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbptrliz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbquugpj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhiwpyb.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbgkdou.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnilnrtl.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jghbjjjk.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ickoljuo.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pridrfvx.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsoticd.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdjjovp.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhxlmkz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2yekazqfn.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcvarht.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2tagpvzhi.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmsepmv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyzhevp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzojneu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2kidgbkdp.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2yicmtdbb.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwpanci.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2autokxrl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfssfxw.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlarwvu.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjhfvsm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kfraqhws.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrvgkli.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2rpouorxw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkficsq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzshhijf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyviwfv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzkscmf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cariwfqq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqahcve.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2cadszeev.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulboyuwc.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjzqcux.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2flutjmlt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqdkxfq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ccamlfxf.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2esgqdawo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzfqrgt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbybudz.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhzindd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgatpzy.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqmxzye.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2agksczbs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2boaogyao.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcefelbj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhcrugs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nypgfvmc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2njqnvsoi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2epnebdes.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwtfjqf.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pjizfyid.html


<!-- 参考信息 -->