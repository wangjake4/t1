代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zycfv.cn/Article/details/gtkulpklxm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtotoqsngb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtgjrwmvkm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtvomtoonr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtokyqqoqn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hywenlv.cn/Article/details/gtcocpyhdi.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtbckatlwh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtuunisrcs.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258888.top/Article/details/gtnubdluni.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hysaishi.cn/Article/details/gthjelvglx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gthrnjzmab.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtvnkgmhar.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gtygcchedn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daxiang520.top/Article/details/gteeuvcbke.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yangfankeji.com/Article/details/gtmrihsgtn.html

Ruby: s.bytesize;  s.length
来源：http://dali.jiagoushi.top/Article/details/gtzmhjtbyp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gtpnolyukv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtatceawix.html

F. 文件与目录
来源：http://dali.smart0.xyz/Article/details/gtibcwrojn.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtaehcuejk.html

[F01] 读取整个文件
来源：http://dali.cheryme.top/Article/details/gtobusbaes.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.redwolf501.top/Article/details/gtupspicfi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ivvv.top/Article/details/gthkfzhnsj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cheryme.top/Article/details/gthtwaotro.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtfpxveamg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtdvpculwe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sxryk.cn/Article/details/gtinashzwn.html

Ruby: File.read("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gthscbyfng.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtmjruwqms.html

[F02] 逐行读取文件
来源：http://dali.bjfxy.top/Article/details/gtolzgavml.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj20258888.top/Article/details/gtcjichcpf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.iojbl.cn/Article/details/gtkoqejtpq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gtoltpfesp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gthxhcymmu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtsfeityou.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cucudq.cn/Article/details/gtbbopbnfz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jyoumei.cn/Article/details/gtfwazogpq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.c1oappe.top/Article/details/gtsiagyvtd.html

[F03] 写入文件（覆盖）
来源：http://dali.nanxinkj.top/Article/details/gtkqkyblhw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gtnckcfoxa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtxjzxmtlt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtjuegyvvv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbqfkrgc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gthipspzoi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.iojbl.cn/Article/details/gtfmrfzatt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gtmxipweew.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gtsvzlgqlp.html

[F04] 追加写入文件
来源：http://dali.jqgfzy.top/Article/details/gtpcefwnbv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.c1oappe.top/Article/details/gtyazjygko.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yueranfly.top/Article/details/gtahsgjuir.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtlvjhfwrm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtlsekggmx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jyoumei.cn/Article/details/gtaxihfehw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gtphtbilna.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gzhubu.top/Article/details/gtvyffrcol.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.smart0.xyz/Article/details/gtdjqqpcwy.html

[F05] 判断文件或目录是否存在
来源：http://dali.gotoacloud.top/Article/details/gtpvaepehv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gttbbnikta.html

PHP:  file_exists("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtdbkdownl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtwbcygdcp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtekdahqjo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtggqqvxpa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.redwolf501.top/Article/details/gtpmuwnlhj.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtoxogawcz.html

C#:   File.Exists("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtdvrnsoig.html

[F06] 删除文件
来源：http://dali.kuanghao11.cn/Article/details/gtiwtugvon.html

Py:   os.remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtygtdvamt.html

PHP:  unlink("a.txt");
来源：http://dali.yonumen.top/Article/details/gtemxzzpqr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtdocuuzfc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtwmzqaovn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtwkzvpqce.html

Go:   os.Remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtscpewmut.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtrblnehak.html

C#:   File.Delete("a.txt");
来源：http://dali.yongpay.top/Article/details/gtivnlhyhi.html

[F07] 创建目录（含多级）
来源：http://dali.jlsjyb.cn/Article/details/gtckefpwpq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gtqparolmj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gtkaiczufa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gttxqekujl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gtmwhbjkmb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gtiiknwhfd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.redwolf501.top/Article/details/gtbqdawuur.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqwmwvsp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jyoumei.cn/Article/details/gtafcfbaro.html

[F08] 遍历目录
来源：http://dali.yueranfly.top/Article/details/gtlmzpftwm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ybcxt.top/Article/details/gtgdmmbtnw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.andypj.xyz/Article/details/gtjzgntrba.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gtpgwqxwtd.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtcnydkmpg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gtzbdlllbo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gotoacloud.top/Article/details/gtjdlresnp.html

Ruby: Dir.children("dir")
来源：http://dali.9152youxi.cn/Article/details/gtxbfurjce.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sweek.top/Article/details/gtqtjomstm.html

[F09] 获取文件大小
来源：http://dali.jqgfzy.top/Article/details/gtkmozgikk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtojapmipv.html

PHP:  filesize("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumbnadhi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gtrfccclnk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtfahqchhn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtdxmwsldj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xinyue.icu/Article/details/gtgywntfxr.html

Ruby: File.size("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtwbxefowb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gtntrgrbbw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zycfv.cn/Article/details/gteuzzyfuj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtaobegbnv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtnwhtjyei.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnmbzuvp.html

TS:   path.extname("a.txt")
来源：http://dali.pycfn.com/Article/details/gtsngflwhi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ivvv.top/Article/details/gtdqktstxv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtqxooojbi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtjsqbpapq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gteswurbgi.html

[F11] 复制与移动文件
来源：http://dali.yj20258888.top/Article/details/gtnmsxdlbe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtjmzcnjlc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtzxilhufi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtdrpnmhfk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtzftginqq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtzpzwsurv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hysaishi.cn/Article/details/gtviazjzxh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtzojeiayb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ehwqpu.com/Article/details/gtbndvzbpm.html

[F12] CSV 读写
来源：http://dali.hongshengwenyu.top/Article/details/gtefxhpgar.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258.top/Article/details/gtsocaugrm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xylfe.cn/Article/details/gtesobrgnb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gtrdttyjod.html

TS:   // 同上
来源：http://dali.cucudq.cn/Article/details/gtelmtmotl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ybcxt.top/Article/details/gttyiausfs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.vqdsnc.cn/Article/details/gthaqnbspu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shzxlz.cn/Article/details/gtjrxqqmrk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ivvv.top/Article/details/gtlvqcibnl.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtrckcffym.html

G. 面向对象
来源：http://dali.yangfankeji.com/Article/details/gteosjfqiz.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gthpgeazjl.html

[G01] 定义类
来源：http://dali.chenzaomai.com/Article/details/gtneiryozi.html

Py:   class User: pass
来源：http://dali.xuetiantiany.cn/Article/details/gtayrrjjxd.html

PHP:  class User {}
来源：http://dali.hysaishi.cn/Article/details/gtghcspqja.html

JS:   class User {}
来源：http://dali.yvedp.cn/Article/details/gtvyiucisj.html

TS:   class User { name: string = ""; }
来源：http://dali.fengsongda.top/Article/details/gtnkjokoju.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gtrbtusdzo.html

Go:   type User struct { Name string }
来源：http://dali.yj20258.top/Article/details/gtwxbgqpyx.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gtyzofwjhh.html

C#:   class User {}
来源：http://dali.aizwys.cn/Article/details/gtgbkmvfwx.html

[G02] 构造函数
来源：http://dali.meibo888.top/Article/details/gtozopkpyb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gtccachngn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yangfankeji.com/Article/details/gtavhbiuru.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtmxzgnqvr.html

TS:   constructor(public name: string) {}
来源：http://dali.yongpay.top/Article/details/gtnomcjgsr.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtabbnbwkb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.feifeiyinyue.top/Article/details/gtjirvvqml.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtyvpscjth.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pycfn.com/Article/details/gthvykgnxe.html

[G03] 实例属性
来源：http://dali.xziqi.cn/Article/details/gtvnicuryy.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtnpxnciry.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtnzqhiuks.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtrmkojknc.html

TS:   name: string = "x";
来源：http://dali.havefunace.top/Article/details/gtwhjkfjgl.html

Java: private String name;
来源：http://dali.pengpengdd.cyou/Article/details/gtvvcyzmqb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.iojbl.cn/Article/details/gtpjqpxlyi.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdspqbnyx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gtrktayeti.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxqbnpnx.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtpvbrbwba.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtkuckvnsh.html

JS:   greet() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gteqvdxeay.html

TS:   greet(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtezqodpyv.html

Java: String greet() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtnmuxzicv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtxngxnncj.html

Ruby: def greet; @name; end
来源：http://dali.hywenlv.cn/Article/details/gtsrzddygo.html

C#:   public string Greet() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtnuvqnimv.html

[G05] 继承
来源：http://dali.xziqi.cn/Article/details/gtjucjcbav.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gtqpmwnapn.html

PHP:  class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtjaxdpscq.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtulimppwl.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtwfaigrtq.html

Java: class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtkopqdyqw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwndxyxt.html

Ruby: class Admin < User; end
来源：http://dali.cashguo.top/Article/details/gtshopexxa.html

C#:   class Admin : User {}
来源：http://dali.sweek.top/Article/details/gtvvcxvhfd.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gtmsyyakxv.html

Py:   def greet(self): return "admin"
来源：http://dali.fzhhl.top/Article/details/gtwsoduwie.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtzzymbslg.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtvhgqbjwj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsqeadtt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtgqyaukmi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgufenzy.top/Article/details/gtyvfmskzp.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gtajzhcxrz.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gtsuubmkvv.html

[G07] 调用父类方法
来源：http://dali.aizwys.cn/Article/details/gtiyqkztzo.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gtpeplgkqb.html

PHP:  parent::greet();
来源：http://dali.hnqzz.top/Article/details/gtitckqtyp.html

JS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtxpzwdtjq.html

TS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtekfooogs.html

Java: super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtqvipzxnd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sxryk.cn/Article/details/gtzqghhjsg.html

Ruby: super
来源：http://dali.xziqi.cn/Article/details/gtesfzurqr.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtvxsxwmpw.html

[G08] 静态方法与属性
来源：http://dali.hywenlv.cn/Article/details/gtefewqyqv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cashguo.top/Article/details/gtxeafaews.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gtuepdxnir.html

JS:   static f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtlefldzzz.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gtwzrahgvl.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gtincwiklh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gtbauhzbkf.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gtojgznhai.html

C#:   public static void F() {}
来源：http://dali.jinqigufen.top/Article/details/gtdycquplw.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258888.top/Article/details/gttiemhktp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gtbtmlwdyx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqcaahabl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guowangkeji.top/Article/details/gtxyochksx.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuanzhike.top/Article/details/gtckijyjto.html

Java: interface Shape { double area(); }
来源：http://dali.gogol.net.cn/Article/details/gtjdnllokc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ppjwa.cn/Article/details/gtwnjrmlyw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuetiantiany.cn/Article/details/gtgrsdilpi.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtltdkfqsj.html

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gtvvbfcdjo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuetiantiany.cn/Article/details/gtpxeevinz.html

PHP:  public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtaivqbedx.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gtfdaoegqj.html

TS:   public / protected / private
来源：http://dali.sweek.top/Article/details/gtnmyegfys.html

Java: public / protected / private / 默认包级
来源：http://dali.smart0.xyz/Article/details/gtvvgslysp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gaohongyu789.top/Article/details/gtumqqlgod.html

Ruby: public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtieoxrbqg.html

C#:   public / protected / private / internal
来源：http://dali.quarkkingdee.top/Article/details/gtopwebibq.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gtxojbwngx.html

Py:   @property 与 @x.setter
来源：http://dali.tian-w.cn/Article/details/gtsrsxynuu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtxtgpoict.html

JS:   get name() { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtujaonlow.html

TS:   get name(): string { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gtutjsysxp.html

Java: public String getName() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbjcnunh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtzolsdmdl.html

Ruby: attr_accessor :name
来源：http://dali.hfpthk.cn/Article/details/gtlylvxgsx.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gtyduzkrkj.html

[G12] 对象转字符串
来源：http://dali.chenzaomai.com/Article/details/gtmbveiohb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtcroeaptj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtdmyfhhbc.html

JS:   toString() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtaakmqlfi.html

TS:   toString(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtkrjhzypf.html

Java: @Override public String toString() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtcczhurkh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtoiqwfhwa.html

Ruby: def to_s; @name; end
来源：http://dali.nwbrower.top/Article/details/gtzqsaxcnc.html

C#:   public override string ToString() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtvxstguwe.html

[G13] 判断对象类型
来源：http://dali.yj20258.top/Article/details/gtpfdhnlrm.html

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gtsnbietis.html

PHP:  $u instanceof User
来源：http://dali.pycfn.com/Article/details/gtqauprapc.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtemhjljgu.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtrgkshhgk.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gteaypbkye.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtsbrxke.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpkngnzx.html

C#:   u is User
来源：http://dali.xylfe.cn/Article/details/gttdfshsny.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gtvyqcstvj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.iojbl.cn/Article/details/gtiejqrriu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gtoeqojdpj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcbkmdjn.html

TS:   type User = { name: string; age: number };
来源：http://dali.sweek.top/Article/details/gtjeeeiabr.html

Java: record User(String name, int age) {}
来源：http://dali.jqgufenzy.top/Article/details/gtsfafityq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cqqwz.cn/Article/details/gtxqzrfmer.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gtezlnwsbh.html

C#:   record User(string Name, int Age);
来源：http://dali.zhixingplan.top/Article/details/gthjhmdslc.html

[G15] 枚举
来源：http://dali.shzxlz.cn/Article/details/gtwrgfmxlw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcensbry.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cashguo.top/Article/details/gtxvhqkdsh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xziqi.cn/Article/details/gtzclazjkm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtnlfeiceu.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gtmilbaehp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.mhx1999.top/Article/details/gtgrxhueyf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gaohongyu789.top/Article/details/gtttzogxzs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtrlimpslr.html

[G16] 对象转数组 / 字典
来源：http://dali.quarkkingdee.top/Article/details/gtiniyijct.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xziqi.cn/Article/details/gtwsrblewa.html

PHP:  get_object_vars($obj);
来源：http://dali.meibo888.top/Article/details/gtzajeaxip.html

JS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtozsyprua.html

TS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtmbdrfcdi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gtgktyldqc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sxryk.cn/Article/details/gtroumvprs.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gtauisatge.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtsrtfibwq.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtpbopaame.html

H. 异常与错误处理
来源：http://dali.sxryk.cn/Article/details/gtumyhwxkl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtwqlnmfju.html

[H01] try / catch 基础
来源：http://dali.yj20258.top/Article/details/gtzxtdywhl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsfoykki.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cdnleiting.top/Article/details/gtmiopwixi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtnaiedxps.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtbdatrtso.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhiwuduotai.top/Article/details/gtikechdcb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gtjshgnndl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangshuangyany.cn/Article/details/gtmcdyclyv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sufxvd.cn/Article/details/gtpkrwgbzc.html

[H02] finally / ensure 收尾
来源：http://dali.ivvv.top/Article/details/gtdezhnhlp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sysykeji.top/Article/details/gtueabzngn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gteptdfxav.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtyklvjeqs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gthyzycaqm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtflbwijps.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zycfv.cn/Article/details/gttgpkadom.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gtaljusszq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtcyhaiscd.html

[H03] 主动抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtxdkdvnjx.html

Py:   raise ValueError("错误信息")
来源：http://dali.cucudq.cn/Article/details/gtyhalwqcm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhkxjmzx.html

JS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gteonjcdpy.html


<!-- 参考信息 -->