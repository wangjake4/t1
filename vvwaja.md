代发 wailian999

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2czllkwpz.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzngkchi.html

Java: s.lines().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2moyiybas.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrtbpvt.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gt2wypdjuol.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2imblextf.html

[E20] 判断字符串是否为空
来源：http://dali.zhijiandao.cn/Article/details/gt2nztjnrgy.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gt2pyygkdfm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2ygiljtfb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqeryluz.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwntevee.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dngybwea.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghowfbef.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2qkeztmbm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlrylix.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2fntyfqhq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkbmogu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvxhswf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2usreepny.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqrzuwv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpfulup.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2noprfrrk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwlhjyp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2yzldmody.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2svmdjnid.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlfpjyj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lflnbyne.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsrsvol.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfxmmju.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmamygu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2aohbuzwj.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2deddxvyb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzlapkj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dankklqa.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fshojdhn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2budmrrww.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhtfjqm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhyqhby.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hahsxglj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2wibjklqr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmaqbyfk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2phpdnqco.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhcocvh.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhyzzsg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tdimkyqf.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlhbqer.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2akqpxmrl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xosqxcgo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2radbhlnm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxcvvkb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbllpzcd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2njaobiyp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaqphvz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrulaftg.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfscsxkt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2huroaipb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qnblrzou.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2utmjaeaj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyvpmor.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2yogkydol.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2nufhpsqi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkevikgy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2buofuyvy.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ixizwdgk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2uocolywk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ildpmvir.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2egwphvxd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvinuyu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuayydl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdbubfx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbihtznf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdkxqjd.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ronmiogm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2xadadutu.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jcsodrhq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpotnrh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufckujhh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2uwimdneo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyqebwe.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzidegk.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrwziwq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ppljvnzn.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvzivyb.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvvbbbw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2doqkyfqz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbznyit.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcsbqvs.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmlxncf.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnltnugy.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gujnddod.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwwcyyf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpfmqzp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuesnfnk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2vakzntty.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2iyoiyznr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2elctpich.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvtulji.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2orfvryek.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2aidmrohz.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2irfeptbk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtywsxj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imhralci.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2scindrru.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2heyhoysw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2msymslae.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbdyhfb.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqjgwbj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxudctv.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2cezarusl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqznogwa.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fsftfbqo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2qsaxlnhz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2vqegxnid.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuplnjw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2dccolyos.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2deyiwesc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bztyfkpr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpljkbi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pstxmdkh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2qajxnxax.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzarpho.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wchbvtxa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgmzrhb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqprthm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2liqmvhpa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfqkghg.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fokqznoe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2riquqicg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyclfav.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtuqkdz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2upygdvwt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2clzotqlf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2opejdlmh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkuhtlyu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbaehvtl.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhahmdk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsycnevv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvwywkf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ewetdbjk.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgdrseb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmntjur.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2llncugzt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhozqyn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2puqvvmoq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqgayjt.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2evldosyz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbgghhq.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvkqfld.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2rqieqisk.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xidqkgtr.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tliyurqg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2defnegsh.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2idwsvugn.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpecrdu.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrbpzno.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvorzth.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjoqqul.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2hluwjlkh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxovhte.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoapugjn.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfytdkde.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzhgfxw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2clsmzgid.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwuclhb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qepknyvu.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwvtryj.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvswhwv.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mutrbwga.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2jmowlanj.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2mamxganj.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2arlcpjlh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmekgef.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhikqri.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2tyaadpbr.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvjohsp.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2lstzbwpm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfnstlk.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaofzvj.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inujrlli.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpewnafe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2svvrmzqj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2bbithrbw.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wosoqbnt.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvclcpl.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsmtnly.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2conqotbe.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxogonqq.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkilgpwm.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqmiyni.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2jymlladd.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dncnsaqn.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttijtwma.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqhehhx.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2toklcenm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rugxvtup.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvjrurr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdvhsqm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkcguxi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2qvooxqvz.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mbznkkwf.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbkqnob.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2tfywuhxn.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzimkwez.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2xcemdyhg.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2muoptbrk.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2jutczrap.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2cpztfzcr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2vznqmmwq.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrbkabi.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2iuiwzdtj.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zshjnuju.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsgvuyp.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwhlisl.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiizyhb.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvohggpd.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kyahvlfz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvnkyco.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2eunketgt.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvzcvbk.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzyxtls.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2jvoxthrd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwaifrt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2cyaasepf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuhgoys.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhoevhgt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hakzdrev.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2abgujdvg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jijvtdnb.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2psiiufpw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2kiibjcbg.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2oniaofad.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2nuouozvn.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cdioqmgl.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2dvonxkzt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwtzfzv.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2elykjlif.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2cjevdkrh.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2flnsfqxz.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyedjuf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuwfymp.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anuclpzi.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhubvmw.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wamvvdgf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2awizzsen.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2robqchom.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jehigomf.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vuipxtga.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2kxltyoeb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ledlbhpd.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfukvmrr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaboktq.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqukhziy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcirtrp.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2euvtgoao.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlvycqb.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wqugpjpn.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2bijzalfr.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2wecxioyn.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2tzklbqnd.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuqsrkt.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnuhkfo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2adyjqugk.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrbvfsg.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqwmkuw.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpyysyx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2olzlwepr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2daebgyeb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wijlivob.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfmbnxp.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqmgfjk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbrchhl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhfftsn.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2grfglnxy.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uudbqzzd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpqzvgl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdvwqbb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2phmgpwmy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlgzujd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrayrmn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwjdxeb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2pyofpdbn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpyyjwc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcebgub.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2soylrswr.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxpwbxc.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tchjypxj.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2utigxpda.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmngegfm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2xnegoqzv.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2yodegvov.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ziiyhmyc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2unemhjtj.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjrhyrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tozsikex.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmufcxm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfjaflw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eylzhzaf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnuasbi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vynroxxo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kejqteuv.html


<!-- 参考信息 -->