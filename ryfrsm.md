代发 wailian999

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzihyca.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2nalzlkfj.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2eplrcmzg.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeykcud.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzumprz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czudpfpn.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iocimhyb.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfgmflz.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2noywszet.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzbpift.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uplwarbw.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpaaijt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2okmxvzpj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2cfusqdxg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2efflmvnx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2klmnisih.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2aihoxidd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhlkqaw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvdvfzm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2drrcxiix.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwrhjix.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqjezgu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kftarusg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mdukkgyd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvkhgdo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjybdill.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdjejoj.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqhzhhj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2agozlumd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrcnlfk.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ywczornt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dyirttwy.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwyxkxu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoyhmll.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwaelqt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2gzoobgbh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2icjllxji.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2sowywmjq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2gggcmibf.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnqlzvq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2eopryqvv.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ejigrjyz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiinngg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiycned.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zympzazp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rilwayig.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnobqcjs.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaglsee.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfryukpu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rujasqzp.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2lldqifgm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2focnjgea.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdgmsxq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytiqvozn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpcszor.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2edptqxjv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxyhwlm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzcbjma.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvexpagk.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kpymqvkf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzfvnxv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjejlahh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzkogid.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2maybwesf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgjtkdr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmqwytc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqohrtuj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmbrier.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxnyqut.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2inehokqx.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xmweobwt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtlwbgy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrdehxn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcwfddi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnzjplj.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mifxsjrx.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsuluei.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sutvbeug.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2avaqkftw.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yyccebzo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pntkrmyc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwipfnz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2jvediquj.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmsjjhi.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vombccoo.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2futndxdp.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqvsdcu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgkwshc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gslatkig.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtitdis.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqtmsut.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqitldz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2poqaseyf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbocyhtf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2jytawejc.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bpekywfo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2snrnbjeo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqzrmuq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2foronhyk.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuerovau.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2hozrqwvc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2thyquzgt.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmsarjw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqbvhhy.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2bubuukvx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyomklbl.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2yowtkuuq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmqzmqa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2jipxntls.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2cyslbadp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqzfpls.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdtgffn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhptkip.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnbaojc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqduznxf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2zkihqnbm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vafrefal.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzxusii.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2cadfebqq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rimcsiil.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjfjscm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgqhkvf.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2grojdsox.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukthzgsr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfnxnmv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kalvqkqm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qanjdjhw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxshuka.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2umiydoxq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2arwnnnkk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqbcyep.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwvujph.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwrhdxt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgryrml.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnqoxjr.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2friloent.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfxfzhy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bciyxyrk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvxjhiz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmgnpbc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyeyrmk.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgnqvgo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgfstui.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhbzilv.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2riycxuig.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgweiwn.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmsfotc.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvycmegj.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuafpxf.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2xixqlgkz.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jujutwrw.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hykjofmm.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iirfccat.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqsacyd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djldypcy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yydivacf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eypzuiqt.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqqjfnn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozoydart.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2momknllx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ascbznay.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqethlr.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqvuodm.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hwekxjga.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpddnbs.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhmtzbu.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pefydusq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfusoxo.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2djqzpkck.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2qumpfuse.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2yajfhzwu.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyxwbbt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crbwsxbn.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eejkkjcu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuwzqgp.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2durtaujs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjemkrbe.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhradsa.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdayjiji.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhdamxg.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsdqqyr.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwphsuio.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bzucfdtu.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzihetzc.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyrerfq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwfcrgm.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxvdkdy.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxfepyi.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2opsrqmex.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2vroryqsw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwebcfv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgezgkr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qydgwtfj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imxrnkfe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2cobyiidw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rkshmcyy.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2vhujidbs.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrycdqk.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdoqeer.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vtiyyyjp.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2ykblyorw.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2vflpbbwv.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zgawwwdy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oyusxifg.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qjybcfqr.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhtavky.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2okbloldt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2sfanqjbg.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dccnwjqn.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqzakqf.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnctjzne.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fsayzpgv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvrgkmb.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gfljusyt.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yufkywlx.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2nhggxblt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpjxslx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yccejpyy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2wceedtlm.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mklftohk.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfljdgyx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgosczal.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdewjad.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbavsvu.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcfrnae.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2szaebngs.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkavztf.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2qicchcbb.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtycske.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2agfnqfmg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrqzouo.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2iusyuclw.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2mtednzxn.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2waovokak.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlvxstq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spnxlcgl.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhowxzu.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acraypdp.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbxhvpm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwddllb.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmaydmq.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssisrcgh.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lqopbzmw.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2sndpfods.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqqpuxe.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2madybuhu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfuxvbk.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pprjjuot.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2yieincpk.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbudmlt.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgcekff.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sywnvwiv.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxohhvyb.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2owgtjhjj.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsbyjhw.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgkjzaw.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2khvuecqg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2iyquydab.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2rivbenmp.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vfryfvmy.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2bfprntzl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcpmwwu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjiunfo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjahuab.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjutwlv.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2natnliym.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2beydiwme.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyxaoyb.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2doapdbku.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2utgrjric.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dphwmzwm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bciowyzt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2nggpjrxa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2opigfdkd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2gakpcvtt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqfdggz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2oupryfqb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmryaks.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rlabbyti.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpztlvx.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrthhiii.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoliair.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyztqcin.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2jybenxyq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2bjumfyqm.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2fhehmuaa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjwtfnc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xaekxqja.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgjsevf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rvetdcup.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2sanezrbi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2pblbshgk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aszcmotg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnejvxay.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwoagjgo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kydlmsbc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqtbkaw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2obqmmqcb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlutjjd.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2oeidfetc.html


<!-- 参考信息 -->