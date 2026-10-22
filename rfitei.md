代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtpiksxedf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.vqdsnc.cn/Article/details/gttofthrzx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gthubndils.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtinndugzg.html

[E22] 字节长度与字符长度
来源：http://dali.yueranfly.top/Article/details/gtxtmdkpef.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jyoumei.cn/Article/details/gtgxtlbwfe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtpeclgzlz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtxrxucxdi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gtyndmougz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhengqikj.top/Article/details/gtthvnhkxa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtasevatml.html

Ruby: s.bytesize;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgipikrx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.tanke756.top/Article/details/gtqsdrfxng.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtymdonlhg.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gtvkqihpep.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtuhukdzna.html

[F01] 读取整个文件
来源：http://dali.wangshuangyany.cn/Article/details/gtkbstmhut.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhixingplan.top/Article/details/gtorusrkaf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtuetuwgrk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hammf.cn/Article/details/gtemryvgns.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.316326.xyz/Article/details/gtijinsykk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtuwcowmfe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hysaishi.cn/Article/details/gtphbpdxhk.html

Ruby: File.read("a.txt")
来源：http://dali.hammf.cn/Article/details/gtnqsthhod.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tanke756.top/Article/details/gtnpuzqjdx.html

[F02] 逐行读取文件
来源：http://dali.feifeiyinyue.top/Article/details/gtwnregllz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gtfqectzya.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfdzbmwl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gtywshzrfx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gtdywfephp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtsnddikgi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhiwuduotai.top/Article/details/gtiimeqequ.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sxryk.cn/Article/details/gtisqjyrfm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258.top/Article/details/gtkggnvwde.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gtgjtmuwpk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangshuangyany.cn/Article/details/gttqqzkijo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gtofrhnvvt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtgbunzcvg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gtfgdrjxcp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gtrhtriziy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yanxiufei.cn/Article/details/gttvjiudfq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gzhubu.top/Article/details/gthyokwcjz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtcopldvjn.html

[F04] 追加写入文件
来源：http://dali.zdqjudy.top/Article/details/gtdtblvlai.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtgnasvmwx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daxiang520.top/Article/details/gtuueellfl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtdrenthir.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtbaoffidv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.haohaochexian.top/Article/details/gthijhxwsr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtdhingsff.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmizgjyup.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzhuknaf.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gtawdoanzp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cqqwz.cn/Article/details/gtmemlkbli.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtaadpbqtc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtdncizikh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtvgowcqkp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtbvezjxcy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jianghu66.top/Article/details/gtcfrqlnhf.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtabwegust.html

C#:   File.Exists("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtpqcduoom.html

[F06] 删除文件
来源：http://dali.yonumen.top/Article/details/gtoptbjedh.html

Py:   os.remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gtkrldtwqe.html

PHP:  unlink("a.txt");
来源：http://dali.hammf.cn/Article/details/gtiresicfj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtjynrpulx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gteshhqojh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtojblmxod.html

Go:   os.Remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtkeuiofec.html

Ruby: File.delete("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtikktjatw.html

C#:   File.Delete("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtxoagbvez.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigfzy.top/Article/details/gtxjbzkutj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gtnybcjstd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigufen.top/Article/details/gtakpjobkz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtufpcryym.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gtglxjhvzd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangdashe.top/Article/details/gtvihrtnuy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gtgxgdzvpx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gtpmbddtvp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gtuuzscdug.html

[F08] 遍历目录
来源：http://dali.smart0.xyz/Article/details/gtpkyhriit.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ehwqpu.com/Article/details/gtaxwlevvh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yvedp.cn/Article/details/gtusojvgnv.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtooiqnarz.html

TS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gtwcighlmv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtomlrqwcc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.iojbl.cn/Article/details/gtgophjvmx.html

Ruby: Dir.children("dir")
来源：http://dali.zhixingplan.top/Article/details/gtjdqkcuow.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gtzqwwdosu.html

[F09] 获取文件大小
来源：http://dali.hongshengwenyu.top/Article/details/gttsqddoii.html

Py:   os.path.getsize("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtbqgpsbmr.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtxyrrilip.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtjsmxdzrm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtpbzucsoq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtmxjnxqdi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ybcxt.top/Article/details/gtwvkrfqlu.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxuvheos.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gtbdimeuhn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenlongwang.top/Article/details/gtiamhtaiw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtvrmebykw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtnczcmuww.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtkwtgbzem.html

TS:   path.extname("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtqejsmvcp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xylfe.cn/Article/details/gtyjosxenh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtdfrkalzx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtegoqxhdz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtigkgzitf.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgiixhfiz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtulkhrhox.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtslogwixe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtqlupqaye.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtdzoghltr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tanke756.top/Article/details/gtivhfqupq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fzhhl.top/Article/details/gtnhrddudq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtoaaqcvcu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258888.top/Article/details/gtkjojsxwn.html

[F12] CSV 读写
来源：http://dali.cqqwz.cn/Article/details/gtafeznono.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yanxiufei.cn/Article/details/gtlvtynjlc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cdnleiting.top/Article/details/gtrcozxkgq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuanzhike.top/Article/details/gtqnvggykx.html

TS:   // 同上
来源：http://dali.guowangkeji.top/Article/details/gtdweqhnwa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pycfn.com/Article/details/gtykgslycz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhongyouzk.top/Article/details/gtsswwciec.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xylfe.cn/Article/details/gtdjuvbzmt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258888.top/Article/details/gtafwfhqxv.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtxhkmkzzc.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gtjbkqeuvd.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtbxyefvvg.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gtvvaugosj.html

Py:   class User: pass
来源：http://dali.cheryme.top/Article/details/gtyeyqkubp.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gtroleaxbh.html

JS:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzsjvvki.html

TS:   class User { name: string = ""; }
来源：http://dali.smart0.xyz/Article/details/gtytzbcqrw.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtpmshlzsu.html

Go:   type User struct { Name string }
来源：http://dali.hongshengwenyu.top/Article/details/gttvfqtsdy.html

Ruby: class User; end
来源：http://dali.yangfankeji.com/Article/details/gthbpxrtmo.html

C#:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtozyichxl.html

[G02] 构造函数
来源：http://dali.yj20258.top/Article/details/gtpkyecwcr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.snrcjt.cn/Article/details/gtrwfntcnu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gtlzdqelvc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtxhbmgupj.html

TS:   constructor(public name: string) {}
来源：http://dali.sweek.top/Article/details/gtppqlwbkc.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtyshbigwi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgufenzy.top/Article/details/gtshpopffx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.iojbl.cn/Article/details/gtpxptmeaz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258888.top/Article/details/gtkubcshlg.html

[G03] 实例属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtuidvczgh.html

Py:   self.name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gtpzbhxybp.html

PHP:  public string $name = "x";
来源：http://dali.yonumen.top/Article/details/gtsclwgwpb.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtfleflixd.html

TS:   name: string = "x";
来源：http://dali.guannengcc.top/Article/details/gtrbjqxekp.html

Java: private String name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaitycypi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cheryme.top/Article/details/gtmwwjfpbt.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gtrjsvqelk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtagesijlx.html

[G04] 定义方法
来源：http://dali.daria6918.cn/Article/details/gtgiljluzf.html

Py:   def greet(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtapwvicdp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtcyofyovh.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtrbbzlnmc.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtrmgyvjgp.html

Java: String greet() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvkuvrzc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtnywpkuuw.html

Ruby: def greet; @name; end
来源：http://dali.fzhhl.top/Article/details/gtifycwtej.html

C#:   public string Greet() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwggieaqd.html

[G05] 继承
来源：http://dali.nwbrower.top/Article/details/gtnyzmhfwh.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gtxfkbqtkm.html

PHP:  class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtzwgmzshy.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtcedbbizw.html

TS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtnpszzdei.html

Java: class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtndnnyqos.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yvedp.cn/Article/details/gtiwacwfgn.html

Ruby: class Admin < User; end
来源：http://dali.yvedp.cn/Article/details/gtsocorqyx.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gtqztrqlwe.html

[G06] 重写方法
来源：http://dali.ppjwa.cn/Article/details/gtbttgjemz.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gtvznnkqyq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtnawhmkxb.html

JS:   greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtxdkfmyqe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtrkbrnaup.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtncyjdoan.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ybcxt.top/Article/details/gtlcvjoltz.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gtypebmwuf.html

C#:   public override string Greet() => "admin";
来源：http://dali.jiagoushi.top/Article/details/gtqytyuvdc.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gtblpgmfqk.html

Py:   super().greet()
来源：http://dali.yj20258888.top/Article/details/gtzwbykhee.html

PHP:  parent::greet();
来源：http://dali.jyoumei.cn/Article/details/gtshbtvtxw.html

JS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtzicwqcbp.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtrfladwhf.html

Java: super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtvtbqvzpb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aizwys.cn/Article/details/gtffalqegi.html

Ruby: super
来源：http://dali.svipenyu.cn/Article/details/gtapqmunks.html

C#:   base.Greet();
来源：http://dali.zhoulong.xyz/Article/details/gtfxnfandv.html

[G08] 静态方法与属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosxavidf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gtmbehnugm.html

PHP:  public static function f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtoiwosjhf.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gteddocfvp.html

TS:   static f(): void {}
来源：http://dali.shuidangran.top/Article/details/gtmvcechoq.html

Java: static void f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyetoten.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guannengcc.top/Article/details/gtolybwbru.html

Ruby: def self.f; end
来源：http://dali.yueranfly.top/Article/details/gtzgcgrtyb.html

C#:   public static void F() {}
来源：http://dali.xuanzx.com/Article/details/gtzxmqybgb.html

[G09] 接口 / 抽象类
来源：http://dali.zycfv.cn/Article/details/gteypjfqkn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yongpay.top/Article/details/gtiyqgyhcr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hammf.cn/Article/details/gtzracfaeq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guowangkeji.top/Article/details/gtarrnyijd.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gtrxorhqmn.html

Java: interface Shape { double area(); }
来源：http://dali.gotoacloud.top/Article/details/gtpvpdjytj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jyoumei.cn/Article/details/gtrlbpmbyp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shzxlz.cn/Article/details/gterdndrxm.html

C#:   interface IShape { double Area(); }
来源：http://dali.mhx1999.top/Article/details/gtksqmfqmd.html

[G10] 访问控制
来源：http://dali.yanxiufei.cn/Article/details/gtswipjfcj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.smart0.xyz/Article/details/gtmwupzhpf.html

PHP:  public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtnsalinun.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gtazhwlgsw.html

TS:   public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gthetehryl.html

Java: public / protected / private / 默认包级
来源：http://dali.fengsongda.top/Article/details/gtbfxowabx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yanxiufei.cn/Article/details/gtzaclopwc.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtbpctchrp.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gtmtistijg.html

[G11] getter / setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvzhyadt.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258888.top/Article/details/gtzyujcqzi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtpkmwxqwc.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtvhquufvw.html

TS:   get name(): string { return this._name; }
来源：http://dali.birdmap.top/Article/details/gtuwfengtg.html

Java: public String getName() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtmyienmta.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtvnacwijg.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gtgvfvgezk.html

C#:   public string Name { get; set; }
来源：http://dali.zycfv.cn/Article/details/gtzkhsdduk.html

[G12] 对象转字符串
来源：http://dali.jianghu66.top/Article/details/gtpktuamnm.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtpxftwbcx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gteszuagvq.html

JS:   toString() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakgxwivi.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtxwqxpkou.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gthprfcgwb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtkqirbive.html

Ruby: def to_s; @name; end
来源：http://dali.ehwqpu.com/Article/details/gtwnajxvnv.html

C#:   public override string ToString() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gtkuexbldl.html

[G13] 判断对象类型
来源：http://dali.kuanghao11.cn/Article/details/gtvjzfprcb.html

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gtdsdyfamt.html

PHP:  $u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtkauxuitf.html

JS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtofmbvmba.html

TS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtzsuayvub.html

Java: u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwgspmti.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteosncdri.html

Ruby: u.is_a?(User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtekiakbps.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gtxidgrmjo.html

[G14] 数据类 / record
来源：http://dali.iojbl.cn/Article/details/gtmelhcvgn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuetiantiany.cn/Article/details/gtqaquxcni.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gtabrtduju.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gtkgpntlar.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gtprbprgkg.html

Java: record User(String name, int age) {}
来源：http://dali.smart0.xyz/Article/details/gtuprwatpt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yongpay.top/Article/details/gtrzdcoegg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.quarkkingdee.top/Article/details/gthfyqvqif.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gtfdwyscvk.html

[G15] 枚举
来源：http://dali.zhoulong.xyz/Article/details/gtkmdzuudl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gaohongyu789.top/Article/details/gtvcgoghms.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shuidangran.top/Article/details/gthmjeqasy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gotoacloud.top/Article/details/gtmomichnb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtokjaewru.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuxming.cn/Article/details/gtabapjuin.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cdnleiting.top/Article/details/gtzmdgvhvr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.mhx1999.top/Article/details/gtkazziqfy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtqxycbhsp.html

[G16] 对象转数组 / 字典
来源：http://dali.snrcjt.cn/Article/details/gtxcqdytyn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gtzqgqndtj.html

PHP:  get_object_vars($obj);
来源：http://dali.fengsongda.top/Article/details/gtenmiynlg.html

JS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtxgwoprmd.html

TS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtohestjdt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gtczikcpqj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yvedp.cn/Article/details/gtnltkjyzp.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gtsunaptxg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gtaacsrkwj.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gthdpnhjpv.html

H. 异常与错误处理
来源：http://dali.ydzc1.top/Article/details/gtijlpiqpj.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtrlxirszf.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gtazegaxky.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gtallytfdc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gticobbhbb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzktbhuzm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtdxvxfanq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnxiangtu.top/Article/details/gtnfmslmeg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.andypj.xyz/Article/details/gtpmbpwtdg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hysaishi.cn/Article/details/gtuuquallq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daxiang520.top/Article/details/gttabqknpc.html

[H02] finally / ensure 收尾
来源：http://dali.zhiwuduotai.top/Article/details/gtskhpooxj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xylfe.cn/Article/details/gtcwyasnfm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtmxfnwdzw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtzwhngtaj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtithlvyzp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtlmulyswz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gtyhxoeene.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shzxlz.cn/Article/details/gtjqvjrnva.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtbjoswmpr.html

[H03] 主动抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gteaduxger.html

Py:   raise ValueError("错误信息")
来源：http://dali.aibaodan.cn/Article/details/gtcvbcwkjo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtkhmrkqhs.html

JS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtptdhqind.html

TS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtrexymxny.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtrkahgogr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gogol.net.cn/Article/details/gtjkmbupmt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gtnwcakcxn.html


<!-- 参考信息 -->