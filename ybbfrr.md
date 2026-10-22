代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2oeahnbdr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sotiwqor.html

TS:   if (s === "") {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwcxyht.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uznrusts.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvvelmk.html

Ruby: if s.empty?
来源：http://dali.zhijiandao.cn/Article/details/gt2serqtygf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2drqajzia.html

[E21] 超长截断加省略号
来源：http://dali.zhijiandao.cn/Article/details/gt2wujyqarr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhijiandao.cn/Article/details/gt2piodkqay.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzayeoe.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqttvpe.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2vityrnke.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgwtbnd.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqjboqr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2qcstrhab.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2gamxsdbi.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hulmozth.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2brtpqdml.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqitsct.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iakjdfda.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2utbpjavy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2smsrhleb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhijiandao.cn/Article/details/gt2clnshxfr.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxomjfy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2isyhopde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyhdeih.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gt2amjgwwsy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gzohprhv.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvihmpcu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppatgxee.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvdviqv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhijiandao.cn/Article/details/gt2pzihbtxd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2srqjuklm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzjebmr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqrgenm.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2osxeccdk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdidpme.html

[F02] 逐行读取文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlgsxmw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2rgiqzytl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgdhnen.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eiypefwq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gckyifkb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zycxttyd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsxrtog.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvbggup.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xezkmani.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzdecba.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2taycuqgc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpqxxwt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibudtrzs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2djdftrgj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnaxrll.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gt2axfgskrv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyitrgb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhnzawn.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxocqlsf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2irivmkwp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocohwkmo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppivryvm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzijtgle.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2devzklxi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxauooa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaifjqyw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2msqxwaji.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xefiiwbk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gt2qondytsc.html

PHP:  file_exists("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqgcadt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmjnvbv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aznwcyra.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2brvjikdd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkopgau.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2loxrrpct.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyxidip.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkvelmw.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpthmug.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkltnpj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fajiipsh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfjmhxw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvpoess.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtemyoz.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehufkxuk.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrcxsdx.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbvadch.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxclgpfu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjorqzmp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2mnanafmg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzxqrqi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vviddynd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2uznjaqll.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdzmhmi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2fympwdxp.html

[F08] 遍历目录
来源：http://dali.zhijiandao.cn/Article/details/gt2idyymzzy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdihamxw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxpufnb.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdobfns.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwapcztf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdkkwwp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmkifqc.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwfxjxb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2itdnkdns.html

[F09] 获取文件大小
来源：http://dali.zhijiandao.cn/Article/details/gt2cwaqjygl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2encuiyoo.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2pibmzzzv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2gdblrwpe.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2cooghrzh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wayelpkr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2aygixrlm.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2csmpgicc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxwjdiy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxhvxqg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxivpoy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ccabdcih.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2dakznwcz.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfvdtir.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnbkoua.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhquosm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2aokdaoym.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsezgum.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2krgsngok.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpojsdlo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbjdtmy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2slnfijwi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vztobxav.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2otqaotng.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2xksdfgzl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktulzrpj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwrdzdw.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2getqlahw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2awivsubh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2skitwoxn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxvvtdi.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxogjgc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2fbchbejw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwacrdl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gt2wypcryyb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvyfbqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwnbgzi.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2yphvxbvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whnsygkc.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gt2dvszqlkl.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gt2vldynzze.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hibxnznx.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tykyjhtk.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aztsydqd.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnqdcsw.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfinaubt.html

Ruby: class User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjygvmu.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qeecflaf.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2klruxaxb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gt2svcrupfe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmrtzeg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcejquis.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwdnhvc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akpqxiqm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncemkvzx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfofruh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2susnklff.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmmuhlh.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzrryrp.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hmixglvv.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjztlmt.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2kklkooxn.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqebasfp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlppbay.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvjzcbz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nukduzxm.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxuggpc.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zypivmbo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhaonwt.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrycdehe.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsdpmfx.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eajafimi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2efcxhlwl.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vymmfwqg.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qemmixvr.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dfytnjat.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2znvrvaay.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxftbrai.html

JS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2droxavkm.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nymmhbol.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2feqisjqg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2dafiansx.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pigcfqjq.html

C#:   class Admin : User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfguumo.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2nmegxuvn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhijiandao.cn/Article/details/gt2agmpptyr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lymoarug.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsuhuwx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpaeyxkb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkryefdx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gt2nldysffa.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwcfozt.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhwnvhq.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhjskcg.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2eacqligr.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2upvlqgss.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2usairrlh.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2riwttauj.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2scatgzih.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmwpvow.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2hxorhzbd.html

C#:   base.Greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2flzkdpzz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzahbvn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvhzdnt.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azsecerb.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwpjeih.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gt2farftbve.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2efuqjyus.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvlryxp.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2cbohnjcc.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lngmcbqz.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2lixalwsy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2yztbbvdy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuiamrnr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2dpjozior.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cclkrvbp.html

Java: interface Shape { double area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2winzsfyi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mucanede.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmquagh.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iomwgghe.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2cduxsfwl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkmqhmj.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2stjduzwt.html

JS:   #private 字段；其余公开
来源：http://dali.zhijiandao.cn/Article/details/gt2mogrxteq.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpbfjhr.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjkhvlp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2ksctzwqh.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2npyctroz.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2iifllibx.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gt2sakbluij.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlpgsrk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjtpntc.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnqogzf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kssfmejs.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjcgduj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcfmpmy.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxqvfpk.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbljlbd.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oebmxbwl.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2dammlumw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbivska.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsgmjvf.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfiuirr.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uukoucbe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnqzkto.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2egqsxxcm.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrovget.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqftqjt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2luqskejc.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2celyqqje.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lznuiprc.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkhelvv.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2hurxdqkj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jhoznram.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqklyrtc.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gt2vcoqiaxz.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gt2vgumkudy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwqjvcz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gt2itpriyxq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpctgpd.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmnsfut.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhdjmwe.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmnvhvk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2divucxzo.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvkjylx.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfkkizy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2itpuqoyb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoahmej.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmcjhvu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsigrbva.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkqkybj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2imykdsls.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdcbcqi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkgkkap.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqbtmua.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gt2kheeiwji.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsrnvov.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sucjeiqb.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2poyzrozw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmaagdw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbnbqzx.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzcrtve.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2rlszgbnr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mukdcozd.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2agebogxb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrrpgzr.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2gejodual.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuntmws.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2biqtwlmf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwkuena.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2orcpuvcz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzzrdje.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmphrwx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbghnbr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtunkwsk.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ftggbmgq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhijiandao.cn/Article/details/gt2btrhdjwd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rryuxhyo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgyplxz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtovljk.html


<!-- 参考信息 -->