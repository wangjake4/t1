代发 wailian999

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sweek.top/Article/details/gtpvknynae.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtdxmqenlg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtqmlpjlpg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtbhpplpzr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gtgqxctesu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangdashe.top/Article/details/gtpkgwwgng.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtrlcgwjaa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtlcrpnjzn.html

[E22] 字节长度与字符长度
来源：http://dali.tian-w.cn/Article/details/gtarrqlxti.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tanke756.top/Article/details/gtfbetvpxk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtrjxptews.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yvedp.cn/Article/details/gtfuetcqkt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gthzrtceqy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hammf.cn/Article/details/gttssuupoc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nwbrower.top/Article/details/gthfswgsko.html

Ruby: s.bytesize;  s.length
来源：http://dali.xziqi.cn/Article/details/gtbirvqcjn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jianghu66.top/Article/details/gtwvlshmfx.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtmlymkltv.html

F. 文件与目录
来源：http://dali.jinqigufen.top/Article/details/gtgyumewyf.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gteocmmdei.html

[F01] 读取整个文件
来源：http://dali.nanxinkj.top/Article/details/gtjnqnbbiq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pycfn.com/Article/details/gthzsstvmo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtxnillhea.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jiagoushi.top/Article/details/gtteyyebce.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtoqioevdl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gttesgiufi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.svipenyu.cn/Article/details/gtuwkycmpx.html

Ruby: File.read("a.txt")
来源：http://dali.cashguo.top/Article/details/gtanehtfld.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtntqdzsaa.html

[F02] 逐行读取文件
来源：http://dali.sxryk.cn/Article/details/gtglznkykm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yangfankeji.com/Article/details/gtquajrnpa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cucudq.cn/Article/details/gtdzlxetiy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gtlpzfcekk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtirvhkybb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtwlthljhu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdmxyxsd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.guannengcc.top/Article/details/gtzjkrlhqa.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shzxlz.cn/Article/details/gtkzmtzslo.html

[F03] 写入文件（覆盖）
来源：http://dali.daxiang520.top/Article/details/gtpjexaaiy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenzaomai.com/Article/details/gtdzmdcfjz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtmboeosse.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtbueixplf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gttwvdeqit.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shuidangran.top/Article/details/gtvislcbop.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhongyouzk.top/Article/details/gtzulwczfw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.havefunace.top/Article/details/gtnfwffims.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj20258888.top/Article/details/gtrhndwwvh.html

[F04] 追加写入文件
来源：http://dali.yongpay.top/Article/details/gtirclghmo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.redwolf501.top/Article/details/gttnzedxcb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yongpay.top/Article/details/gtktoznqos.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtiuvextys.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gtiqpebcmi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuanzhike.top/Article/details/gtkwitdmgm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtevsyfqau.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gtkjcuwtpm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sufxvd.cn/Article/details/gteginskli.html

[F05] 判断文件或目录是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtwctdlyto.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ybcxt.top/Article/details/gtxvhagsul.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtgetcnvyp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtfkzeehoo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtzuujxkno.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtehatznxd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aizwys.cn/Article/details/gtgipfyphx.html

Ruby: File.exist?("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtijmamkvy.html

C#:   File.Exists("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtleqjujsb.html

[F06] 删除文件
来源：http://dali.andypj.xyz/Article/details/gtvfqtfdxz.html

Py:   os.remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtolxqrlgz.html

PHP:  unlink("a.txt");
来源：http://dali.sweek.top/Article/details/gtzmubdudd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gthpbpjywn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtkdmlsksn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtntkunllk.html

Go:   os.Remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtyyxkgzaa.html

Ruby: File.delete("a.txt")
来源：http://dali.smart0.xyz/Article/details/gteusnzaku.html

C#:   File.Delete("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtggphhdah.html

[F07] 创建目录（含多级）
来源：http://dali.chenjidiqi.icu/Article/details/gtvappncbj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gtlyugpkfc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gotoacloud.top/Article/details/gtdtmqeeew.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtejkovqfj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtshpzzkzs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj202588.top/Article/details/gteodgljwv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tianlin.xyz/Article/details/gtfhwekaor.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pycfn.com/Article/details/gtjdmhhdej.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gtllrpnqjy.html

[F08] 遍历目录
来源：http://dali.jinqigufen.top/Article/details/gteitcgsdg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jianghu66.top/Article/details/gtmwrrauyl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dashuyun.cn/Article/details/gtqkengxuq.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtfmireogq.html

TS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtbvuqltly.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gtfkwowgjy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guannengcc.top/Article/details/gteiiihmoe.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gtaxrrckij.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtxrpavjxk.html

[F09] 获取文件大小
来源：http://dali.yongpay.top/Article/details/gtnymnixog.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtvrwucpqd.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtmuqlbnrd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gtkdvoytce.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtpqmhslmq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtdiwkdcbm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shuidangran.top/Article/details/gtpzgevlum.html

Ruby: File.size("a.txt")
来源：http://dali.daria6918.cn/Article/details/gttruazfns.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.havefunace.top/Article/details/gtggmvzgge.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yonumen.top/Article/details/gtiauadcfr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtqzxrtpnj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.smart0.xyz/Article/details/gtctztsdoc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtnbdnggwe.html

TS:   path.extname("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtgyvpqnfm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gtnszbuxks.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtnsqwtjnc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtvkbrmoci.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtajbzbaqb.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtefhwjxtw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtvohbnfel.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tian-w.cn/Article/details/gtprlxqtag.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllgljmib.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtoavofxwg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gtpkztrbup.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuxming.cn/Article/details/gtbyqfvrjt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtdjlujtvk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tian-w.cn/Article/details/gtqtvcazsg.html

[F12] CSV 读写
来源：http://dali.daxiang520.top/Article/details/gtbejprlvo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrztwyebk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgfzy.top/Article/details/gtexrobiww.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhoulong.xyz/Article/details/gtpiogdynl.html

TS:   // 同上
来源：http://dali.dashuyun.cn/Article/details/gtoeqqqkhk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ybcxt.top/Article/details/gtbbsgmmws.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sufxvd.cn/Article/details/gtkfpngcsl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xinyue.icu/Article/details/gttbxckfhi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gtwehvkagk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtzmstcrrs.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gtfzmphbct.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtnspekaby.html

[G01] 定义类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqgsrkue.html

Py:   class User: pass
来源：http://dali.yvedp.cn/Article/details/gtciyquhzj.html

PHP:  class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtuqdnjqqe.html

JS:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtcrridhfc.html

TS:   class User { name: string = ""; }
来源：http://dali.yuxming.cn/Article/details/gtkvmtonwn.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gthlhcfkyw.html

Go:   type User struct { Name string }
来源：http://dali.guowangkeji.top/Article/details/gtzdpcszyk.html

Ruby: class User; end
来源：http://dali.gaohongyu789.top/Article/details/gtuswbprzz.html

C#:   class User {}
来源：http://dali.guannengcc.top/Article/details/gtrlbdwzge.html

[G02] 构造函数
来源：http://dali.jianghu66.top/Article/details/gtgkjwvwip.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zycfv.cn/Article/details/gtiezijjfa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtgtrgwqji.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtlfpfegzg.html

TS:   constructor(public name: string) {}
来源：http://dali.xinyue.icu/Article/details/gtsjshbdea.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtyfyiucno.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxuanxn.top/Article/details/gtmdhxpenn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gtmhqfntvu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsqitsgcb.html

[G03] 实例属性
来源：http://dali.ivvv.top/Article/details/gtzwscilmr.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtzdupahvn.html

PHP:  public string $name = "x";
来源：http://dali.0kj1m.cn/Article/details/gthjqfefcb.html

JS:   this.name = "x";
来源：http://dali.ydzc1.top/Article/details/gtjrpetxrf.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gtmealqbvg.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gtlqwfnynj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jyoumei.cn/Article/details/gtlbdjnspk.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtroojhfnm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gtfbyercrc.html

[G04] 定义方法
来源：http://dali.hammf.cn/Article/details/gtanysrnyg.html

Py:   def greet(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsudqhyn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtggxowmxi.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtpufdctbo.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtomeqdivu.html

Java: String greet() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtyggzfjmb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtakpcwcro.html

Ruby: def greet; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gtfpybzmcp.html

C#:   public string Greet() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtntbayafb.html

[G05] 继承
来源：http://dali.ppjwa.cn/Article/details/gtpknirsgk.html

Py:   class Admin(User): pass
来源：http://dali.ivvv.top/Article/details/gtuqdqxvhf.html

PHP:  class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtjyetbaxw.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzgumpuo.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtdhwqjcqk.html

Java: class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtexpclbry.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daria6918.cn/Article/details/gtnxpmrobh.html

Ruby: class Admin < User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtjlgediur.html

C#:   class Admin : User {}
来源：http://dali.cucudq.cn/Article/details/gtdzhkcnxz.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gtqkffqjeq.html

Py:   def greet(self): return "admin"
来源：http://dali.zhongyouzk.top/Article/details/gtgivavscf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqdsscobc.html

JS:   greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtkodkwhzy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhvvikhm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtqsadkvim.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ivvv.top/Article/details/gthuzokdip.html

Ruby: def greet; "admin"; end
来源：http://dali.mhx1999.top/Article/details/gtgvmcbnag.html

C#:   public override string Greet() => "admin";
来源：http://dali.316326.xyz/Article/details/gtdczcpacc.html

[G07] 调用父类方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqvvxlyl.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gtorcqxgxf.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtgqdmgluf.html

JS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgquupnby.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtogotjclo.html

Java: super.greet();
来源：http://dali.yonumen.top/Article/details/gttfojyjge.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gtigusrwgr.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gtprytnpdw.html

C#:   base.Greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtyvqrxdwp.html

[G08] 静态方法与属性
来源：http://dali.zhiwuduotai.top/Article/details/gtjwubqyyw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xziqi.cn/Article/details/gtrruzbufi.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gtzmkkbzel.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtwmxehsff.html

TS:   static f(): void {}
来源：http://dali.bjfxy.top/Article/details/gtpuvbyaxm.html

Java: static void f() {}
来源：http://dali.yvedp.cn/Article/details/gtzqayyiej.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.316326.xyz/Article/details/gtdchggzql.html

Ruby: def self.f; end
来源：http://dali.xinyue.icu/Article/details/gtmutfphnc.html

C#:   public static void F() {}
来源：http://dali.yj202588.top/Article/details/gtkrwssefe.html

[G09] 接口 / 抽象类
来源：http://dali.sysykeji.top/Article/details/gtbyfgxeim.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.mhx1999.top/Article/details/gtxsgaejlx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjtphsvd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hammf.cn/Article/details/gtjigbglpr.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj202588.top/Article/details/gteythmpcu.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtgqkwvspm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fzhhl.top/Article/details/gtqhmpjmgo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxuanxn.top/Article/details/gtdmixnocl.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtqounmdwl.html

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gtoksbkmsm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cdnleiting.top/Article/details/gtyunjnuho.html

PHP:  public / protected / private
来源：http://dali.meibo888.top/Article/details/gtpjenptng.html

JS:   #private 字段；其余公开
来源：http://dali.nanxuanxn.top/Article/details/gthydmkrcl.html

TS:   public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvibqrqz.html

Java: public / protected / private / 默认包级
来源：http://dali.yongpay.top/Article/details/gthvjehctr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aibaodan.cn/Article/details/gtzaxujuej.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtmjaaowyu.html

C#:   public / protected / private / internal
来源：http://dali.fzhhl.top/Article/details/gtuykzkcoj.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gthlryyxjd.html

Py:   @property 与 @x.setter
来源：http://dali.nanxinkj.top/Article/details/gtqzntfyjx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtevvhckof.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtyivkkwmb.html

TS:   get name(): string { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtqvvzrvrb.html

Java: public String getName() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtdmuhyefy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtnemjnlbz.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gtmnushtsf.html

C#:   public string Name { get; set; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttqnbbonr.html

[G12] 对象转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtgkgnpawr.html

Py:   def __str__(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtsauttppr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtiqvxvgnt.html

JS:   toString() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtrnwdsxvg.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwawgmdhv.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtowovngij.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtfhijjcez.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gtekwpkqnv.html

C#:   public override string ToString() => Name;
来源：http://dali.cashguo.top/Article/details/gtyuadfnni.html

[G13] 判断对象类型
来源：http://dali.cdnleiting.top/Article/details/gtozyqxeoy.html

Py:   isinstance(u, User)
来源：http://dali.cdnleiting.top/Article/details/gtqhmyxcol.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtupkeeage.html

JS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtqenolevb.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtowqhtfbj.html

Java: u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtjdylwzow.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shzxlz.cn/Article/details/gtjltibqtx.html

Ruby: u.is_a?(User)
来源：http://dali.fzhhl.top/Article/details/gtwbixhebj.html

C#:   u is User
来源：http://dali.iojbl.cn/Article/details/gtzisjerkk.html

[G14] 数据类 / record
来源：http://dali.jqgfzy.top/Article/details/gtnzbtdxpv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gtwvsetmab.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirnnrpaz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gtbbrazbxt.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqwlcaaw.html

Java: record User(String name, int age) {}
来源：http://dali.nanxuanxn.top/Article/details/gttbxlvvkh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hongshengwenyu.top/Article/details/gtynevjwxt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gtbekgxukf.html

C#:   record User(string Name, int Age);
来源：http://dali.jlsjyb.cn/Article/details/gtvdpziwrf.html

[G15] 枚举
来源：http://dali.aizwys.cn/Article/details/gtpobkugaz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gtipcawcav.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxqfnlqhb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhongyouzk.top/Article/details/gtugfxuzoe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gtkriekbji.html

Java: enum Color { RED, GREEN }
来源：http://dali.sweek.top/Article/details/gtkxfempps.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gtgjnmpkgb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhoulong.xyz/Article/details/gtmkrchsth.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtyaebhwwu.html

[G16] 对象转数组 / 字典
来源：http://dali.quarkkingdee.top/Article/details/gtwikuavyx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ehwqpu.com/Article/details/gtynppmypv.html

PHP:  get_object_vars($obj);
来源：http://dali.nwbrower.top/Article/details/gtpvczobty.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtxegwhpyy.html

TS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtoioxwatd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fzhhl.top/Article/details/gtrkwswfxy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gtourcivve.html

Ruby: obj.instance_variables
来源：http://dali.redwolf501.top/Article/details/gtvjtvspob.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258.top/Article/details/gtsqcivxlp.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtfwyyggit.html

H. 异常与错误处理
来源：http://dali.dashuyun.cn/Article/details/gtkgooplgd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtrqldbzcn.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gtbnieutxn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hfpthk.cn/Article/details/gtbjrnvxdb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gthbmgbwxz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtidcvzlde.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtmbvnejlm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guowangkeji.top/Article/details/gtcczvbopf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ehwqpu.com/Article/details/gtabrzmelc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sweek.top/Article/details/gtggzmqokn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guowangkeji.top/Article/details/gtcznybslv.html

[H02] finally / ensure 收尾
来源：http://dali.xuetiantiany.cn/Article/details/gtaaklhbfh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guowangkeji.top/Article/details/gteuipccwv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtcpwwdrxx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtsijlfdhk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtblammbva.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtqcyqcgcj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuxming.cn/Article/details/gtsjqajpup.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yonumen.top/Article/details/gtjdtjcvry.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtsbjjatzw.html

[H03] 主动抛出异常
来源：http://dali.tian-w.cn/Article/details/gtakyspcdg.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gthogfeklj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtaexswkjp.html

JS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtywczwvyj.html


<!-- 参考信息 -->