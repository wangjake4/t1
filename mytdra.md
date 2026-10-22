代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtgblvk.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpwvess.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2smbhrrws.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdptplb.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2oplbtrce.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2tiopdonj.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyitkvw.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjcejrh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhldfjb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjtvzeu.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjvimku.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2matxehha.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqypnqcz.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2zobjzfzd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnbcggz.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyxdrap.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqjuknd.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxzktgp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxhihdb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2mhppgskb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvihajz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzrjtuz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ytejwzmk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2btchskur.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmymwmg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtswocdn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuixszp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2clhfhmgq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2laeitksu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnxyuxd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywypwila.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nsezpzkf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzkwbnc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtotpvm.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeeqgtb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkrgoap.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpnbaqg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnvhspx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqkvctw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2elhdwfsh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2izddtafu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2hkarajhq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2lwulykyo.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfshdzg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjmymkz.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyohubw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxwludn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xklkljee.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irjxkzcx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyffgee.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2qywnhoik.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxipfzbc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2yatjwzhh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kycwvufy.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhlpucu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcevjef.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qacpkfse.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwtsnwi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjevcfw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpxfcqz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2abnyrgza.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2cplcgaiu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2radwgnut.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyhuaav.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2svawepej.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyslqbyx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiytylq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgoiqymo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuweaeex.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpidxmx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kewwmtxq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqumgpwu.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfdhtea.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2hztlfvdh.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtaejlr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbljpytv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2smczgefv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfhwsle.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtvojhv.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmqpvtk.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuysxiiv.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zixbdhpm.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffekwgef.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2punbpyxe.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mntlnrmu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fycznxbs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dihvdkpw.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2nndojpwk.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcfczej.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2czfmhggu.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmbwufx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtoakpg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wexngvlg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfuwxue.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsezeht.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gylohjpn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxnkzwa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2uktjoxem.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxvydsm.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkjyxca.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2expzzzja.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icsqkald.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hienqcef.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjwipfu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbvkvbl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvyclkc.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2piqcsthn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyokqzfv.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2jtslcodj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhxxkjm.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqkjfyk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpjcwqi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2yatuezdj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2widysdcm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuqpzji.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbkxfyg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhzxxtv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvlhudb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibonspna.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhjnzql.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvarfgh.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2inpjiare.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2edqkflwy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbxepqu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfymcapi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzgzioe.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ntevpjpi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmgqfpt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hffpdmrf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyzeuyx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdlgzxw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xozkcaaj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvgwgfh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2trtobwcq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvszwjp.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2puftzupr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwumsqb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqkazda.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwslmhy.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2zolseipv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmfxzjm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2erfdlwcc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdumgcox.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkofcvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2atembxor.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlfqaih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2akpwrqyr.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqkyizk.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2liyqbyos.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wqytdnhk.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aakubuno.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2majdjzef.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grbaisfl.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2eenufjuj.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfbvqlk.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bquvfwzo.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfuadso.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jroaimty.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwiqmsn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esinzgxb.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjxsukd.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jczwgplr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyqsdkt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuuxtab.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyilltr.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgzzeuh.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdeuikin.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwiietx.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2zpckcgtq.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qynrkkzh.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qctegrnz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwvecrh.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgeghbuq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ueafprkh.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2scfuilzs.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2degtstup.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmuvmtp.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wobngfnn.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmupufh.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atymvmkz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdndmid.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xquzrwur.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbltifx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2uyahxzpj.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2lglvorvi.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jshwkcdc.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxscpdka.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wfojpfaf.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgwedtc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2tswlqjox.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hqftghsn.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjiqkxlp.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlqqekr.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkuoest.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dimxiexn.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmdliqi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfydawn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwbotvm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2avvraxpv.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dtihkhfe.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2turumkxp.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgbovdc.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpbdlys.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2srrqmsvz.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfkpvoj.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdrdwqa.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbubyep.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2elcgrlvb.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qicfuetf.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhjxhvl.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2txwdhxgt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2thynfrwe.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlscdbn.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqglwvqo.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ormwxtar.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmawusr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2znbqyjpf.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2usyjlwcw.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hpeikzew.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2jczdytdi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2csnlnjrs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxfbopr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2scqnlhxl.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjmwagy.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eslgapxv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2judnnnmz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbzbumk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkrnuya.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2mdedtmbv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2qemkdbvh.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhfccsi.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2nebiqvxh.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwcitpw.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcmczxe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2betfmzxi.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxlgzfg.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2sldxopsg.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2aiodtmcg.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhanszr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qriraupq.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybultfop.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcczufq.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmxnqfn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2khokmmxo.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtakvgo.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drmxkwtw.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qieuswmg.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcidgmx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dytcblws.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fibmoabe.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkaqfygh.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kppxmlzc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2geqtggrc.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2exgbadap.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsixgxx.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2biyyfzqp.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2wafqlybx.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2deqgmock.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgwahsi.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2onkrrbxk.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2kvowdxws.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtpjlyd.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2menhfruh.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2bugreidt.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfgjglz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcdsnxw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2ctezfjwo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2hhioxxfm.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2moeyhlif.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjwbbio.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmnvxak.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrecegz.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfacxmmx.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlooasx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jdetcieq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fobfhtzd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2iwprkqnr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxlbjbv.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihriiddr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpjruhd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2clarmwfv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpiarkl.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2exbmlwfd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2onawardf.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxziqtlv.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uutvefot.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjvhjll.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcarsxij.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2cvevggso.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2volmgugg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrrkiih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdukaep.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tycbutie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyjmoue.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqhuhuv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjsxeoz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2epqfyxyc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2trwpbbub.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2axeyxwft.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmchxaq.html


<!-- 参考信息 -->