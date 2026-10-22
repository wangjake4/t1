代发 wailian999

Go:   if s == "" {}
来源：http://dali.daria6918.cn/Article/details/gtmlxiutbs.html

Ruby: if s.empty?
来源：http://dali.jyoumei.cn/Article/details/gtcezzcvic.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yanxiufei.cn/Article/details/gtuqgprqhr.html

[E21] 超长截断加省略号
来源：http://dali.cdnleiting.top/Article/details/gthrmijmhy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.meibo888.top/Article/details/gtlyeljvdk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtiekmltww.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtrzcvcsus.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtcpapwwti.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtzjvobpsy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hfpthk.cn/Article/details/gtpwvnclzj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gtckvkaqou.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jiagoushi.top/Article/details/gtnzvoxlim.html

[E22] 字节长度与字符长度
来源：http://dali.haohaochexian.top/Article/details/gtpwlieaqj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyjytpkl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtytcxbbhd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gtqmovksic.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtqelyzqft.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yongpay.top/Article/details/gtwgyndgme.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuanzx.com/Article/details/gtwqipipyr.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gtlsthapeq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ehwqpu.com/Article/details/gtvbjprtwp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtmbrurlrr.html

F. 文件与目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqfnnppy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtzunqivjo.html

[F01] 读取整个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkaqhjzk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxinkj.top/Article/details/gtgsavxsfx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shuidangran.top/Article/details/gthwcshlwy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.quarkkingdee.top/Article/details/gtvdrotgdf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuiprqhew.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtdcklsses.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aibaodan.cn/Article/details/gtjrrweegh.html

Ruby: File.read("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtjvptmnrx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtczsvzduf.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gteosqfosd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pengpengdd.cyou/Article/details/gtivagaexb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shuidangran.top/Article/details/gtwzaorher.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjtucdba.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gttnzuewgf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gtgikjuoyt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtioirtryf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zycfv.cn/Article/details/gtfqnitcab.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.havefunace.top/Article/details/gtdymlvvcv.html

[F03] 写入文件（覆盖）
来源：http://dali.jiagoushi.top/Article/details/gtpyhpktsz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dashuyun.cn/Article/details/gtvdlehefq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zdqjudy.top/Article/details/gtusuokwjp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtydnrgxjh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtlokeyxbo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlptarxzz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj202588.top/Article/details/gtgjcqdbdf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.redwolf501.top/Article/details/gtwnuhniyq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gtjzzwzlxf.html

[F04] 追加写入文件
来源：http://dali.havefunace.top/Article/details/gtbzmasmco.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pycfn.com/Article/details/gtdeykvckl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cdnleiting.top/Article/details/gtgeputgma.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gtkknpwbwe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtxezvauuh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cqqwz.cn/Article/details/gtpaummjfb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gtgyatcenh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangshuangyany.cn/Article/details/gtwjdybabh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zdqjudy.top/Article/details/gtazbuptce.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258888.top/Article/details/gtcdememur.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhengqikj.top/Article/details/gtipqfpetb.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtgccllaza.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtqnwlmvjs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtpbsarqkh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwxdzpll.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnxiangtu.top/Article/details/gtfsdakdjw.html

Ruby: File.exist?("a.txt")
来源：http://dali.yongpay.top/Article/details/gtqsfmxkcj.html

C#:   File.Exists("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gttkaujdar.html

[F06] 删除文件
来源：http://dali.daria6918.cn/Article/details/gtcqjtrfqo.html

Py:   os.remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtzhxdqmik.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotlfyjnn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gthelwkumq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gttdiyndjd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtbwgrsuao.html

Go:   os.Remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtllcbmkpy.html

Ruby: File.delete("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtxqmsdiko.html

C#:   File.Delete("a.txt");
来源：http://dali.redwolf501.top/Article/details/gthduhmvhd.html

[F07] 创建目录（含多级）
来源：http://dali.vqdsnc.cn/Article/details/gtdcdooplg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdsohjng.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.bjfxy.top/Article/details/gtxcpbuwmf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gtrqlzsfam.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtpdleirav.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shzxlz.cn/Article/details/gtzadvpyhs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuanzx.com/Article/details/gtowtsexga.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnqzz.top/Article/details/gtiyrplvwu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daria6918.cn/Article/details/gtvixveedh.html

[F08] 遍历目录
来源：http://dali.smart0.xyz/Article/details/gttmpagnpj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldcjgavg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgiaefxzd.html

JS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtoeeroyih.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtiodpegon.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gtxwmsvlfx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hywenlv.cn/Article/details/gtcjyvbtsk.html

Ruby: Dir.children("dir")
来源：http://dali.mhx1999.top/Article/details/gtbaawaqye.html

C#:   Directory.GetFiles("dir")
来源：http://dali.svipenyu.cn/Article/details/gtnnghxzyx.html

[F09] 获取文件大小
来源：http://dali.ydzc1.top/Article/details/gtblywecta.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtlqpaehhw.html

PHP:  filesize("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gttgdxhxhf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtuadrnhoa.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gtwkgipxqo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gtuvmsckhp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sxryk.cn/Article/details/gtxrfgmgjx.html

Ruby: File.size("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtsyeqnhnu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gtwqtppkhw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hammf.cn/Article/details/gtiitvptga.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtfsngxpyr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtkfyxaayd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtxxgehryi.html

TS:   path.extname("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtgkwyhqyb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuxming.cn/Article/details/gtszxpxjqd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtdjhjgrlf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtbcskbneb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtufkzttej.html

[F11] 复制与移动文件
来源：http://dali.yj20258.top/Article/details/gtckcqpdzx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtpjxthyws.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtoawbudza.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtxcwofkfx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtrquganut.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gtbomqdzbf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gtinpzhref.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtzdckerll.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xziqi.cn/Article/details/gtivbnbwnw.html

[F12] CSV 读写
来源：http://dali.hnxiangtu.top/Article/details/gtgwyqfnan.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tian-w.cn/Article/details/gtmbziqdya.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.havefunace.top/Article/details/gtdfpezquv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.smart0.xyz/Article/details/gtbrvmsxae.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gtxbnaquta.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.redwolf501.top/Article/details/gttfcytwqv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenlongwang.top/Article/details/gtynzauqtk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shangyingyoupin.top/Article/details/gthweqkxen.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dianchejie.cn/Article/details/gtyexjtuwk.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtrustfcnn.html

G. 面向对象
来源：http://dali.hywenlv.cn/Article/details/gtcckaaepe.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gthkrqoqxs.html

[G01] 定义类
来源：http://dali.zycfv.cn/Article/details/gtcqwdtkqa.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gtfnurjfhi.html

PHP:  class User {}
来源：http://dali.yj20258.top/Article/details/gttyoomfas.html

JS:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtloeqsltf.html

TS:   class User { name: string = ""; }
来源：http://dali.xziqi.cn/Article/details/gtneokuhhg.html

Java: class User {}
来源：http://dali.xylfe.cn/Article/details/gtfujbhidt.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gtpbxrqhyz.html

Ruby: class User; end
来源：http://dali.vqdsnc.cn/Article/details/gtaoedleof.html

C#:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtcxrrhppq.html

[G02] 构造函数
来源：http://dali.xinyue.icu/Article/details/gtlugsiilg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gtersidmmw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gtrldghezh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtovwthdnl.html

TS:   constructor(public name: string) {}
来源：http://dali.guannengcc.top/Article/details/gtpxkztzfn.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gthnybpkzh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gthokhqowd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yanxiufei.cn/Article/details/gtfghucfhk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtqltgdrzl.html

[G03] 实例属性
来源：http://dali.fzhhl.top/Article/details/gtqszmddmy.html

Py:   self.name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtrwhibbdh.html

PHP:  public string $name = "x";
来源：http://dali.chenzaomai.com/Article/details/gtpqrynpbc.html

JS:   this.name = "x";
来源：http://dali.cucudq.cn/Article/details/gtwntzuzyx.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtsxkakhju.html

Java: private String name;
来源：http://dali.feifeiyinyue.top/Article/details/gtigbxxqai.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.0kj1m.cn/Article/details/gtlcjbkduj.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiaazikka.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gtszzimlea.html

[G04] 定义方法
来源：http://dali.nanxinkj.top/Article/details/gtcpqgcdqd.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gtlgelegin.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtcbjrczcw.html

JS:   greet() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwgkhypfk.html

TS:   greet(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtwjidhmzj.html

Java: String greet() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtyzojmiph.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtxalknkkf.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtcrlnkmki.html

C#:   public string Greet() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtquylxmhi.html

[G05] 继承
来源：http://dali.pycfn.com/Article/details/gtbalqqfte.html

Py:   class Admin(User): pass
来源：http://dali.hammf.cn/Article/details/gtkhwayydd.html

PHP:  class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtolvczwxr.html

JS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gttyahpmkg.html

TS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtinrogkqq.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtyrsbpxla.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gtqetjltbn.html

Ruby: class Admin < User; end
来源：http://dali.zhengqikj.top/Article/details/gtxyntjxhk.html

C#:   class Admin : User {}
来源：http://dali.yj20258888.top/Article/details/gttcstegst.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gtnscqwmwl.html

Py:   def greet(self): return "admin"
来源：http://dali.xziqi.cn/Article/details/gtddwhqltw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtiprdxbfi.html

JS:   greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtfwgihinu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtfhvdstdk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtrckovdsi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daria6918.cn/Article/details/gtxksfnfer.html

Ruby: def greet; "admin"; end
来源：http://dali.yongpay.top/Article/details/gthqzvcvwh.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gtutvzffmx.html

[G07] 调用父类方法
来源：http://dali.yj202588.top/Article/details/gtktpxjtfh.html

Py:   super().greet()
来源：http://dali.feifeiyinyue.top/Article/details/gttzprmdku.html

PHP:  parent::greet();
来源：http://dali.zhongyouzk.top/Article/details/gtecadlsle.html

JS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtdytbywzw.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtaskrroyq.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gtwtvspwbj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zdqjudy.top/Article/details/gtritbwkaa.html

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gtefcarqvu.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gttlcjuiei.html

[G08] 静态方法与属性
来源：http://dali.tanke756.top/Article/details/gtosktqovu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.kuanghao11.cn/Article/details/gtyqppyytg.html

PHP:  public static function f() {}
来源：http://dali.daxiang520.top/Article/details/gtapmbkfzn.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gtqjxfkgmf.html

TS:   static f(): void {}
来源：http://dali.zdqjudy.top/Article/details/gtmcmbhqpz.html

Java: static void f() {}
来源：http://dali.cheryme.top/Article/details/gtlcmujnst.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shzxlz.cn/Article/details/gtvmniwadi.html

Ruby: def self.f; end
来源：http://dali.c1oappe.top/Article/details/gtknxkmskg.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gtdvpmgwqp.html

[G09] 接口 / 抽象类
来源：http://dali.sysykeji.top/Article/details/gtnmwwdtvq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cheryme.top/Article/details/gthfkavfgb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gtutwtbtex.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.bjfxy.top/Article/details/gtovlnqycr.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gtppqghwmc.html

Java: interface Shape { double area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtsjsbujzx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gtnpydgeib.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258.top/Article/details/gtbrzvxjbt.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtpvabltkg.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gtrbkojkbr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ybcxt.top/Article/details/gtnwymyifg.html

PHP:  public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtrxwfafvd.html

JS:   #private 字段；其余公开
来源：http://dali.jlsjyb.cn/Article/details/gtylsdvpvf.html

TS:   public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtfvbqqwbq.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258888.top/Article/details/gtjlswfarl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tian-w.cn/Article/details/gtgttpmgub.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwbhfwez.html

C#:   public / protected / private / internal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpchouxs.html

[G11] getter / setter
来源：http://dali.tian-w.cn/Article/details/gtpvswrvhl.html

Py:   @property 与 @x.setter
来源：http://dali.zdqjudy.top/Article/details/gtzfhavpor.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtejltsgey.html

JS:   get name() { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gtbzvrqdrs.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtkqzbufjh.html

Java: public String getName() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtlcwzvtpk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtiprxclkf.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gtcahknsqj.html

C#:   public string Name { get; set; }
来源：http://dali.gaohongyu789.top/Article/details/gtegjpyeaz.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gtyebtbqbb.html

Py:   def __str__(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gtfrrcqqxt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtcymnxsgt.html

JS:   toString() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtfotplodx.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gttmfyjmxs.html

Java: @Override public String toString() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbvwpikn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtysfnpgnv.html

Ruby: def to_s; @name; end
来源：http://dali.shuidangran.top/Article/details/gtwatiogwt.html

C#:   public override string ToString() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gteclgwplh.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gtqsbkyxpz.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gtinbqaxtm.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gthaidshkm.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gtknqxaytn.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtmnkswrjx.html

Java: u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtswftgvqc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ivvv.top/Article/details/gthqhrmbmd.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gtfppmgsru.html

C#:   u is User
来源：http://dali.9152youxi.cn/Article/details/gtltzqpwie.html

[G14] 数据类 / record
来源：http://dali.jiagoushi.top/Article/details/gtdsscfxii.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gtzaolzdts.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sysykeji.top/Article/details/gtazslomfk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.snrcjt.cn/Article/details/gthspqmwvy.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflqmvspx.html

Java: record User(String name, int age) {}
来源：http://dali.cucudq.cn/Article/details/gtuqdhjjcs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cdnleiting.top/Article/details/gtcxaruiij.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.kuanghao11.cn/Article/details/gtpgxwxypa.html

C#:   record User(string Name, int Age);
来源：http://dali.gotoacloud.top/Article/details/gtdeawdorq.html

[G15] 枚举
来源：http://dali.jinqigfzy.top/Article/details/gtovogyhhv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daria6918.cn/Article/details/gtetjstwsm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shuidangran.top/Article/details/gtkhvcewhx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jlsjyb.cn/Article/details/gtmiovxtvm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gtockixfvo.html

Java: enum Color { RED, GREEN }
来源：http://dali.daxiang520.top/Article/details/gtlxijbhml.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhengqikj.top/Article/details/gtzyhbzkcp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jiagoushi.top/Article/details/gtwzfbjyqm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtoldrnzyc.html

[G16] 对象转数组 / 字典
来源：http://dali.fengsongda.top/Article/details/gtchnxpwya.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinghuilouyu.cn/Article/details/gtghgrapnn.html

PHP:  get_object_vars($obj);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfabhpjyh.html

JS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtfrqcticq.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gthebxyjwe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shangyingyoupin.top/Article/details/gtwzyhomwb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnnsbgcb.html

Ruby: obj.instance_variables
来源：http://dali.feifeiyinyue.top/Article/details/gtxxqyvxlq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gttjkzdoyi.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtxzovglzl.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsxqraeb.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtfbeoxesn.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gtdjnisuky.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ehwqpu.com/Article/details/gtanliuejt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yongpay.top/Article/details/gtoqvgwhic.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtvimtvohm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtetgtfomm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yanxiufei.cn/Article/details/gteemboikm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuanzhike.top/Article/details/gtycqcjwbr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gtydimfhjq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guannengcc.top/Article/details/gtblyewouh.html

[H02] finally / ensure 收尾
来源：http://dali.chenzaomai.com/Article/details/gtdprusrax.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daxiang520.top/Article/details/gtmbdtfyce.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtpywhxsey.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtvvlwwbem.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtqtjiimws.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtrtrwcrgo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenlongwang.top/Article/details/gttoznkwed.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.iojbl.cn/Article/details/gtqonydamh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtdoypguxc.html


<!-- 参考信息 -->