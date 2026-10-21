代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gtixkrktee.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gtgfeekgge.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhixingplan.top/Article/details/gtyiomopxm.html

Ruby: s.bytesize;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtjtyorryx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jlsjyb.cn/Article/details/gtqftdrldw.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtoayvdlxj.html

F. 文件与目录
来源：http://dali.jinqigufen.top/Article/details/gtgrerqehu.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtdsdcmvku.html

[F01] 读取整个文件
来源：http://dali.dianchejie.cn/Article/details/gtpduzzqhm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daria6918.cn/Article/details/gtawmazzcl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gttjhlvnoo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ivvv.top/Article/details/gtsfwvnipm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtzelbgsuy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtmtverzfc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenlongwang.top/Article/details/gtrdgbjjkj.html

Ruby: File.read("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtmmydsrzz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtotuzmqbc.html

[F02] 逐行读取文件
来源：http://dali.hysaishi.cn/Article/details/gtmdrbavgr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.snrcjt.cn/Article/details/gtoybferys.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.dashuyun.cn/Article/details/gtzgxowbzt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtyprfvbjh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfoengzd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtibkrtlmk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.mhx1999.top/Article/details/gtyvswkddq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pycfn.com/Article/details/gtewbqqimw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sufxvd.cn/Article/details/gthghuscay.html

[F03] 写入文件（覆盖）
来源：http://dali.ivvv.top/Article/details/gtmxhzqbbp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.vqdsnc.cn/Article/details/gtpqvvhbuf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtftguduaf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gtxxizfzei.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gttrtnddiu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sysykeji.top/Article/details/gtedpwfaly.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.haohaochexian.top/Article/details/gtjzkonvqb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gtryowtmhm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtaoygnycx.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gtzlzeucpf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fengsongda.top/Article/details/gtptizghco.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shangyingyoupin.top/Article/details/gtvkqdhnwu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtixfyvvqi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtxozdydns.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.mhx1999.top/Article/details/gtjffmwxpx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gtdnnnpkdi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sufxvd.cn/Article/details/gtikjsxmua.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gtltgwqrkg.html

[F05] 判断文件或目录是否存在
来源：http://dali.yonumen.top/Article/details/gtgjgbzzvf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hongshengwenyu.top/Article/details/gttawmsnrw.html

PHP:  file_exists("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtrkdnpfna.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtztqhszsa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtzxorutsi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtbylitnrp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dashuyun.cn/Article/details/gtweyeyaie.html

Ruby: File.exist?("a.txt")
来源：http://dali.birdmap.top/Article/details/gtptbhpgki.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtghjqwkhm.html

[F06] 删除文件
来源：http://dali.ydzc1.top/Article/details/gtxbqlstum.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gttasyyvrq.html

PHP:  unlink("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtxwpbjqht.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtjuxmypho.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gteeetrvnd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtjmolwmwd.html

Go:   os.Remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtoqhrmuer.html

Ruby: File.delete("a.txt")
来源：http://dali.cashguo.top/Article/details/gteryhujaq.html

C#:   File.Delete("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtkgpfkfhg.html

[F07] 创建目录（含多级）
来源：http://dali.daria6918.cn/Article/details/gtfxrzbzec.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtzirmoxea.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gtsozojepk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gtjehvccvz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yonumen.top/Article/details/gtgyzawarv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gzhubu.top/Article/details/gturkvupms.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hammf.cn/Article/details/gtstntnjat.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tanke756.top/Article/details/gtuarfxjmd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gtscyjcojq.html

[F08] 遍历目录
来源：http://dali.wangshuangyany.cn/Article/details/gtxlknbnrh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhengqikj.top/Article/details/gtbbqhhsub.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvpassmb.html

JS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtvdlgxsdc.html

TS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gtwbhrlciz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtfntabzal.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shuidangran.top/Article/details/gtqbedzvrv.html

Ruby: Dir.children("dir")
来源：http://dali.smart0.xyz/Article/details/gtjrtzydvm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhengqikj.top/Article/details/gtjdigsxun.html

[F09] 获取文件大小
来源：http://dali.tianlin.xyz/Article/details/gtrkbxqcpr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gthgrnubaa.html

PHP:  filesize("a.txt");
来源：http://dali.yongpay.top/Article/details/gtbocxfthq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtfkpmalsz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gthumbrqnk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gteyummwde.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhengqikj.top/Article/details/gtemjzwviz.html

Ruby: File.size("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtygqjoqyf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangshuangyany.cn/Article/details/gtzolmzlvi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xinyue.icu/Article/details/gtypesxyjw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gteezhrggk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtpjzzyppn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtnvghrykr.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtenlksshc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shuidangran.top/Article/details/gtlyfdflam.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtlsqikltv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtvaqjekxx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtcxolhatw.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gtbkiypiwk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtvtnkhtte.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gthqmajdip.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtzttenlnn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsylvmojx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gtlgtrculz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnbbwwbo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtirxkrhus.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gtkqylcyqw.html

[F12] CSV 读写
来源：http://dali.xuetiantiany.cn/Article/details/gtqeecjopv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guowangkeji.top/Article/details/gtzpokdtfz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pengpengdd.cyou/Article/details/gtxhsalquv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgufenzy.top/Article/details/gtebehopjc.html

TS:   // 同上
来源：http://dali.zhongyouzk.top/Article/details/gtctdrionx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gteeutttcr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgfzy.top/Article/details/gtioflkfkh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hysaishi.cn/Article/details/gtymjfwhtg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hongshengwenyu.top/Article/details/gtgphgxizu.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtilzrpdfg.html

G. 面向对象
来源：http://dali.hfpthk.cn/Article/details/gtinjpxsbe.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtkphnrhuf.html

[G01] 定义类
来源：http://dali.chenlongwang.top/Article/details/gtxcxgnyss.html

Py:   class User: pass
来源：http://dali.smart0.xyz/Article/details/gtgtbgdfab.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gtifzqhejh.html

JS:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtdzdvtfis.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gthwwamxgy.html

Java: class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtweiyvlnf.html

Go:   type User struct { Name string }
来源：http://dali.xylfe.cn/Article/details/gteuzicriw.html

Ruby: class User; end
来源：http://dali.jinqigufen.top/Article/details/gtuidjpsfw.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtaperrpdr.html

[G02] 构造函数
来源：http://dali.xuanzx.com/Article/details/gtxdfufkml.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gtxqzjmand.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tian-w.cn/Article/details/gtvvoyxdkl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtsahlagqs.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgufenzy.top/Article/details/gtssszislx.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtipgqxvrc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpwapqtk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxkvhbfp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtuchmwwno.html

[G03] 实例属性
来源：http://dali.gaohongyu789.top/Article/details/gtslhgujvl.html

Py:   self.name = "x"
来源：http://dali.xziqi.cn/Article/details/gtaasmmmig.html

PHP:  public string $name = "x";
来源：http://dali.hnqzz.top/Article/details/gtfobwaopu.html

JS:   this.name = "x";
来源：http://dali.tanke756.top/Article/details/gtfhurysbk.html

TS:   name: string = "x";
来源：http://dali.daria6918.cn/Article/details/gtwvdazovj.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gtxenfupuv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gtvrppwngr.html

Ruby: @name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gtiukbrene.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.0kj1m.cn/Article/details/gtcpdrxbrk.html

[G04] 定义方法
来源：http://dali.cashguo.top/Article/details/gtvpovlfig.html

Py:   def greet(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gtkriyzngh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtgafzwixd.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtsjyjzhbe.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznghyviv.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtabxzvzef.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtsrqeakxo.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtpbdsnmia.html

C#:   public string Greet() => Name;
来源：http://dali.guowangkeji.top/Article/details/gtrzfwmdxx.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gthjptkekq.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gtzkurvpff.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtqwjwarlc.html

JS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtlyatxond.html

TS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtmqngvslq.html

Java: class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfwqtdio.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhiwuduotai.top/Article/details/gtqddolcrh.html

Ruby: class Admin < User; end
来源：http://dali.guannengcc.top/Article/details/gtpajcsptm.html

C#:   class Admin : User {}
来源：http://dali.gogol.net.cn/Article/details/gtizyvxfhe.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gtujgsmrqn.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gtfgyoegyl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtpageosqw.html

JS:   greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtrusbddcd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtmbzzeili.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtiwonzmkm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenzaomai.com/Article/details/gtapconpyu.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gtgzkzzytj.html

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gtxvdldhdk.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gtscxlednh.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gtuzlxvdpb.html

PHP:  parent::greet();
来源：http://dali.xziqi.cn/Article/details/gtuqdxehet.html

JS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtxepdwvix.html

TS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtivphrdoc.html

Java: super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfssgjvfm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sweek.top/Article/details/gthjhxeicx.html

Ruby: super
来源：http://dali.hywenlv.cn/Article/details/gtpwluvpxn.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohrjcehd.html

[G08] 静态方法与属性
来源：http://dali.yuanzhike.top/Article/details/gtnnnnwnpz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daria6918.cn/Article/details/gtfwskpicm.html

PHP:  public static function f() {}
来源：http://dali.ehwqpu.com/Article/details/gtecillxck.html

JS:   static f() {}
来源：http://dali.yvedp.cn/Article/details/gtzwnfjkab.html

TS:   static f(): void {}
来源：http://dali.ydzc1.top/Article/details/gtplnqqyja.html

Java: static void f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtgzmsoerz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ydzc1.top/Article/details/gtuvkwtqac.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gtmcchmzbp.html

C#:   public static void F() {}
来源：http://dali.redwolf501.top/Article/details/gtsajodfjh.html

[G09] 接口 / 抽象类
来源：http://dali.sysykeji.top/Article/details/gtrnsdgsud.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gtqteaxdih.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxinkj.top/Article/details/gtqreevmsp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gteelubtax.html

TS:   interface Shape { area(): number; }
来源：http://dali.sufxvd.cn/Article/details/gtuaqhquik.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gtilbbiioz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xziqi.cn/Article/details/gtfookeiqz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gogol.net.cn/Article/details/gtklwjmvut.html

C#:   interface IShape { double Area(); }
来源：http://dali.fzhhl.top/Article/details/gtuniqywxz.html

[G10] 访问控制
来源：http://dali.zhixingplan.top/Article/details/gtneiahlhs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sxryk.cn/Article/details/gtmqfppowd.html

PHP:  public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtokyeyrtz.html

JS:   #private 字段；其余公开
来源：http://dali.yuanzhike.top/Article/details/gtlrapsorb.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtnsdwurln.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gtdhcbqnsn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.kuanghao11.cn/Article/details/gtlwvnvuie.html

Ruby: public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtwyrvlmxq.html

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gtrhzimist.html

[G11] getter / setter
来源：http://dali.quarkkingdee.top/Article/details/gtcwimgrez.html

Py:   @property 与 @x.setter
来源：http://dali.xuetiantiany.cn/Article/details/gtnftollme.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtrejbitim.html

JS:   get name() { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtfolmkrbm.html

TS:   get name(): string { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gtzwoedunf.html

Java: public String getName() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtgjxrwxsg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtpxnbdyzs.html

Ruby: attr_accessor :name
来源：http://dali.ydzc1.top/Article/details/gtgtssyina.html

C#:   public string Name { get; set; }
来源：http://dali.pycfn.com/Article/details/gtjyilybdy.html

[G12] 对象转字符串
来源：http://dali.yueranfly.top/Article/details/gtnbhenupe.html

Py:   def __str__(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gtktcyibzc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtxweunneo.html

JS:   toString() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtjbrogpmf.html

TS:   toString(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gthkrrxtyu.html

Java: @Override public String toString() { return name; }
来源：http://dali.sweek.top/Article/details/gthilghita.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gttsfgsext.html

Ruby: def to_s; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtsydfozdz.html

C#:   public override string ToString() => Name;
来源：http://dali.guannengcc.top/Article/details/gtimcjspqr.html

[G13] 判断对象类型
来源：http://dali.fzhhl.top/Article/details/gtcaxfpghc.html

Py:   isinstance(u, User)
来源：http://dali.bjfxy.top/Article/details/gtddtpsigi.html

PHP:  $u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtyqpatloa.html

JS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtyzqnpujs.html

TS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtkjaszglu.html

Java: u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtmoqdpurk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pycfn.com/Article/details/gtknotdxif.html

Ruby: u.is_a?(User)
来源：http://dali.c1oappe.top/Article/details/gtbndljbhx.html

C#:   u is User
来源：http://dali.yj20258.top/Article/details/gthzqukuuc.html

[G14] 数据类 / record
来源：http://dali.hnxiangtu.top/Article/details/gtdzsngugg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cdnleiting.top/Article/details/gtuoflhukp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aibaodan.cn/Article/details/gtbpjikxej.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnxiangtu.top/Article/details/gtndcquyam.html

TS:   type User = { name: string; age: number };
来源：http://dali.9152youxi.cn/Article/details/gtxnzpjvwx.html

Java: record User(String name, int age) {}
来源：http://dali.aibaodan.cn/Article/details/gtcsfcqdes.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gtzqhieyud.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zdqjudy.top/Article/details/gtjtbzlhre.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gtfwkogjom.html

[G15] 枚举
来源：http://dali.cqqwz.cn/Article/details/gtxtzebetq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxuanxn.top/Article/details/gtfadklmst.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cashguo.top/Article/details/gttbbdrhwo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jlsjyb.cn/Article/details/gtfueretzu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtomhsauqq.html

Java: enum Color { RED, GREEN }
来源：http://dali.yonumen.top/Article/details/gtrfnmudvf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenjidiqi.icu/Article/details/gtcylyqogb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pengpengdd.cyou/Article/details/gtyxkiiqsk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gtxqgaptoh.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gtklwahnsx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jlsjyb.cn/Article/details/gtiznxwiwt.html

PHP:  get_object_vars($obj);
来源：http://dali.dashuyun.cn/Article/details/gtgobwykwb.html

JS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtptffmgvp.html

TS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gttaxoysfu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.c1oappe.top/Article/details/gtcarfggsf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guowangkeji.top/Article/details/gtqxvuatoa.html

Ruby: obj.instance_variables
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpdczbxc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258.top/Article/details/gtvprzfjon.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtrjlctgbn.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gteyobtsqp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtvehtiymh.html

[H01] try / catch 基础
来源：http://dali.daxiang520.top/Article/details/gtrlrunkwv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gtgpfojmjx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gtojayihxk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtraryyooe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtaecbguqs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhixingplan.top/Article/details/gtygjqxzxo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fzhhl.top/Article/details/gtatsebbar.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.9152youxi.cn/Article/details/gtbbfwdpyl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jyoumei.cn/Article/details/gtgiblwnyl.html

[H02] finally / ensure 收尾
来源：http://dali.nanxuanxn.top/Article/details/gtbkszovxa.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jlsjyb.cn/Article/details/gtfehqzsck.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtrwykklyf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtpdshelku.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtvavkocpn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtxomgbota.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shuidangran.top/Article/details/gtspsyxzsn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.redwolf501.top/Article/details/gtahotvdfi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtgivwvefg.html

[H03] 主动抛出异常
来源：http://dali.zhixingplan.top/Article/details/gtbwqikbxl.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhixingplan.top/Article/details/gthlpltnlv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtvkghbnls.html

JS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gtftzhgnit.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtaftadotd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtbohjekze.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.redwolf501.top/Article/details/gtdsbjkxff.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.svipenyu.cn/Article/details/gtzewlzcbb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtgkzjxcmi.html

[H04] 自定义异常类型
来源：http://dali.birdmap.top/Article/details/gtfrfkiyto.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtvqxzhnnm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtbvmqyjco.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gttkmnfcfd.html

TS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtkbtjhseh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtrrpcqfhj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jyoumei.cn/Article/details/gtjxehcpcl.html


<!-- 参考信息 -->