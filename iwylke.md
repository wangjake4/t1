代发 wailian999

Go:   if s == "" {}
来源：http://dali.cqqwz.cn/Article/details/gtbztmfwxp.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gtdxqqslyu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtrxgsusrz.html

[E21] 超长截断加省略号
来源：http://dali.feifeiyinyue.top/Article/details/gtkzcdwavu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yvedp.cn/Article/details/gtynwzdjdu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtufszqkjn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtofwoqpid.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gteeotpkbi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtcmmznqzz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yonumen.top/Article/details/gtgtzkcwml.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtkvovkkrn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtziavwwvq.html

[E22] 字节长度与字符长度
来源：http://dali.xylfe.cn/Article/details/gtiygommkh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cucudq.cn/Article/details/gtttgtnirc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtxsbhhune.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gtxwwvmmuq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gtqwhmvojq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dashuyun.cn/Article/details/gtowiobdpv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dashuyun.cn/Article/details/gteilcoyvi.html

Ruby: s.bytesize;  s.length
来源：http://dali.c1oappe.top/Article/details/gtenljlnbd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nwbrower.top/Article/details/gtviubxvng.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtrobywfpy.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpvvujne.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtdeubcbva.html

[F01] 读取整个文件
来源：http://dali.sysykeji.top/Article/details/gtnwgyfpqo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cheryme.top/Article/details/gtzixhnkek.html

PHP:  file_get_contents("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtiqzkxpqp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.svipenyu.cn/Article/details/gtqnmptpok.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cheryme.top/Article/details/gtrmeuenfj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtrpartceb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbpeyoib.html

Ruby: File.read("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtvjmicoep.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtyelktyby.html

[F02] 逐行读取文件
来源：http://dali.shangyingyoupin.top/Article/details/gtwqzhlpxd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhiwuduotai.top/Article/details/gtnynvbfze.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yangfankeji.com/Article/details/gtstcuuech.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtfqsavwpo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gtblyodycs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtqbinryvr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hongshengwenyu.top/Article/details/gtlrtivigj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj202588.top/Article/details/gtbpqtkoda.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cdnleiting.top/Article/details/gtrvmqgmmw.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258888.top/Article/details/gtzllhshdf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenzaomai.com/Article/details/gtbbeqbstf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtmkaocmpe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtdfojpkid.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtopvqvebm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhongyouzk.top/Article/details/gtcogkcqoy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cqqwz.cn/Article/details/gterddzsvm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aizwys.cn/Article/details/gttqqqbzlz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtvvyeeaiz.html

[F04] 追加写入文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgipsvtu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.0kj1m.cn/Article/details/gtrplflxbf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gtvaosyawi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gtifboezif.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpllgpit.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jiagoushi.top/Article/details/gtlguryrmh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttykibfoe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cashguo.top/Article/details/gtxnjpuvus.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gttessejbt.html

[F05] 判断文件或目录是否存在
来源：http://dali.dashuyun.cn/Article/details/gtkqhehurg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tian-w.cn/Article/details/gtvvniumla.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtarbwnngr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtkoinhavj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtdmlymqyr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gticjtafrz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.feifeiyinyue.top/Article/details/gtabsznfwg.html

Ruby: File.exist?("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtopiagofi.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtixalttne.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gtevxbsuxk.html

Py:   os.remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtpbluyldl.html

PHP:  unlink("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtydosjtho.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtwoneomjs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtvxripjvf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtwycjlxux.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gtwqylvgdq.html

Ruby: File.delete("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtfgjmvrpw.html

C#:   File.Delete("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtawcngbxw.html

[F07] 创建目录（含多级）
来源：http://dali.redwolf501.top/Article/details/gtrruqgffh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gtgxxvhtss.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sxryk.cn/Article/details/gtpiifvlcw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtjewnbiwc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gtqfohkuyg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuetiantiany.cn/Article/details/gtdxesylmv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gtmbfxhlzf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.smart0.xyz/Article/details/gtaaqrnjxe.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.bjfxy.top/Article/details/gtljbabuta.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gtqusbxrcj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.snrcjt.cn/Article/details/gtiaehqsti.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gtdpjfwrly.html

JS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gtavlehmfn.html

TS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gtlrjlfbzd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gtsjksnyek.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yonumen.top/Article/details/gtsmnjdtfq.html

Ruby: Dir.children("dir")
来源：http://dali.birdmap.top/Article/details/gtwkpgooex.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gtodkuwrwe.html

[F09] 获取文件大小
来源：http://dali.jianghu66.top/Article/details/gtzkvmtolo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtoznoruje.html

PHP:  filesize("a.txt");
来源：http://dali.hammf.cn/Article/details/gtztbepxen.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gtyubxeywi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.iojbl.cn/Article/details/gthgofqxmh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtmfikxved.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenzaomai.com/Article/details/gtzctvquye.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtfnlqjdit.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sufxvd.cn/Article/details/gtwashaxjo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tian-w.cn/Article/details/gtcmtitrdr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtvrityluk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gtnhzrcbme.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtcxjzpyzx.html

TS:   path.extname("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtqhtbzwfi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ybcxt.top/Article/details/gtzszhqnag.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtenfvnaea.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtmmkeddyw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtnyicwwvf.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gtwhiusocp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gteyvaarrn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtxpulglib.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtzgrswnbg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtekpkjwib.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gtqxgftxrh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jianghu66.top/Article/details/gtmldyvqsr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtjoxmczdm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gzhubu.top/Article/details/gtdqojcdug.html

[F12] CSV 读写
来源：http://dali.jqgufenzy.top/Article/details/gtivxzezhl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yvedp.cn/Article/details/gtulwnxagv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tanke756.top/Article/details/gtacczrnaf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.smart0.xyz/Article/details/gtkoewpnoy.html

TS:   // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjrhxtoe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gthmfftzip.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhiwuduotai.top/Article/details/gtegwzpchz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.c1oappe.top/Article/details/gtpjkqxhvk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gtsebszomm.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtfzjnuldv.html

G. 面向对象
来源：http://dali.chenzaomai.com/Article/details/gtrycuojxi.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtvdqodgwy.html

[G01] 定义类
来源：http://dali.zhongyouzk.top/Article/details/gtkvketczz.html

Py:   class User: pass
来源：http://dali.xinyue.icu/Article/details/gtammqgcbp.html

PHP:  class User {}
来源：http://dali.daxiang520.top/Article/details/gtbmjvshdn.html

JS:   class User {}
来源：http://dali.yvedp.cn/Article/details/gtyinafudg.html

TS:   class User { name: string = ""; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwmfoijt.html

Java: class User {}
来源：http://dali.hammf.cn/Article/details/gtypqgutha.html

Go:   type User struct { Name string }
来源：http://dali.gaohongyu789.top/Article/details/gteloxthdv.html

Ruby: class User; end
来源：http://dali.yuxming.cn/Article/details/gtfirtmyhv.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtaislhbjz.html

[G02] 构造函数
来源：http://dali.shuidangran.top/Article/details/gtifgexyzn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdekcayf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jlsjyb.cn/Article/details/gtedvufwyf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtteovfnia.html

TS:   constructor(public name: string) {}
来源：http://dali.havefunace.top/Article/details/gtxmobieyk.html

Java: User(String name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtwnfgroqk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yonumen.top/Article/details/gtzhtddstx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ppjwa.cn/Article/details/gtyvlcfsvm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pycfn.com/Article/details/gtyptdgxps.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gtrqyjpbel.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtukxdixlp.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gthwppnezc.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gtfiitsnuu.html

TS:   name: string = "x";
来源：http://dali.haohaochexian.top/Article/details/gthfchymtw.html

Java: private String name;
来源：http://dali.9152youxi.cn/Article/details/gtthsghwtc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gtrrddkmkl.html

Ruby: @name = "x"
来源：http://dali.aizwys.cn/Article/details/gtrkvakgbv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hammf.cn/Article/details/gtjtbqjydl.html

[G04] 定义方法
来源：http://dali.jlsjyb.cn/Article/details/gtsvwwlqjp.html

Py:   def greet(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtmcecgjgx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtocxvdtdj.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtmomgglty.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtpjfqhlsa.html

Java: String greet() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqhzrzazg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gtppjwwwti.html

Ruby: def greet; @name; end
来源：http://dali.0kj1m.cn/Article/details/gtbflwobdl.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gtyoxnefaw.html

[G05] 继承
来源：http://dali.zhongyouzk.top/Article/details/gteyvzxacu.html

Py:   class Admin(User): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwhupwzd.html

PHP:  class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtswvyauzc.html

JS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtnqlpumpi.html

TS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtixefumkn.html

Java: class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqganffef.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guowangkeji.top/Article/details/gtnbapgpon.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtrmgenrhm.html

C#:   class Admin : User {}
来源：http://dali.zhixingplan.top/Article/details/gtoseeictd.html

[G06] 重写方法
来源：http://dali.svipenyu.cn/Article/details/gtwchnosew.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gtzvrqlxzu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtdaurkave.html

JS:   greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtseqwplka.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgczfiuv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthdtbhgwk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenzaomai.com/Article/details/gtotqvavrf.html

Ruby: def greet; "admin"; end
来源：http://dali.hysaishi.cn/Article/details/gtzleiblxk.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gtaafrfirn.html

[G07] 调用父类方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdrjhryi.html

Py:   super().greet()
来源：http://dali.cashguo.top/Article/details/gtmhayjxqq.html

PHP:  parent::greet();
来源：http://dali.dianchejie.cn/Article/details/gtyyalhhtn.html

JS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gtrkxuoqrm.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtainyaowf.html

Java: super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtcyxyunbv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xziqi.cn/Article/details/gtkvutsxqa.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gtktjcbxxf.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gtzfnayccy.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gtilswfpev.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ppjwa.cn/Article/details/gtqfpouary.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gtmcxkrgli.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gtzffhdtrg.html

TS:   static f(): void {}
来源：http://dali.cashguo.top/Article/details/gtyogoblkr.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gteoqotcax.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhixingplan.top/Article/details/gtqqufasao.html

Ruby: def self.f; end
来源：http://dali.jqgfzy.top/Article/details/gtpkikzjiy.html

C#:   public static void F() {}
来源：http://dali.ydzc1.top/Article/details/gtigocchoo.html

[G09] 接口 / 抽象类
来源：http://dali.bjfxy.top/Article/details/gtqvyicqsl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gtosdphfto.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhixingplan.top/Article/details/gtqfwnoldf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.andypj.xyz/Article/details/gtnfmprwnu.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenzaomai.com/Article/details/gttjbzeehv.html

Java: interface Shape { double area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtvvrpidwg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gtztwceenp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sufxvd.cn/Article/details/gtjdaoochd.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtjkevmsjn.html

[G10] 访问控制
来源：http://dali.aibaodan.cn/Article/details/gtbjphnxki.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gzhubu.top/Article/details/gtxyvrsggp.html

PHP:  public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gtamhbwnxa.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gtrczwkaak.html

TS:   public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtxrvhgvtk.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigfzy.top/Article/details/gtrisnxqfp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgufenzy.top/Article/details/gtonuahxwy.html

Ruby: public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtkopblifr.html

C#:   public / protected / private / internal
来源：http://dali.yj20258.top/Article/details/gtfqjwjdme.html

[G11] getter / setter
来源：http://dali.xziqi.cn/Article/details/gthmseivvg.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gtvgtpqbgy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtqyxmltsn.html

JS:   get name() { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gtwckifdih.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtjygqewxl.html

Java: public String getName() { return name; }
来源：http://dali.pycfn.com/Article/details/gtfpdvkzus.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtvtbjojnq.html

Ruby: attr_accessor :name
来源：http://dali.hfpthk.cn/Article/details/gthiaoptwf.html

C#:   public string Name { get; set; }
来源：http://dali.yuxming.cn/Article/details/gtjqgcrsrv.html

[G12] 对象转字符串
来源：http://dali.redwolf501.top/Article/details/gtrzysnuqr.html

Py:   def __str__(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gtkofzdyur.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtokdbehxo.html

JS:   toString() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtnjupovtg.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtqxvsswiu.html

Java: @Override public String toString() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkrohounc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtaecruvma.html

Ruby: def to_s; @name; end
来源：http://dali.shuidangran.top/Article/details/gtahrdtdcq.html

C#:   public override string ToString() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtkwcrskyp.html

[G13] 判断对象类型
来源：http://dali.xylfe.cn/Article/details/gtbgcutoso.html

Py:   isinstance(u, User)
来源：http://dali.daria6918.cn/Article/details/gtpiwgnfxz.html

PHP:  $u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtfwsewtkg.html

JS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtmhublbxx.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtkskwnfai.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gtwkshfeoe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tanke756.top/Article/details/gtojbzvtmi.html

Ruby: u.is_a?(User)
来源：http://dali.chenzaomai.com/Article/details/gttmsdwblo.html

C#:   u is User
来源：http://dali.daxiang520.top/Article/details/gtuspsvgot.html

[G14] 数据类 / record
来源：http://dali.tanke756.top/Article/details/gtkghlbrbf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.vqdsnc.cn/Article/details/gtgnruuujl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxuanxn.top/Article/details/gtpursysil.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gtlaewsjym.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gtlehtblmh.html

Java: record User(String name, int age) {}
来源：http://dali.chenzaomai.com/Article/details/gtsycujnbb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aizwys.cn/Article/details/gtrhjfnhfj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gtnsixrskx.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gtnotrqatl.html

[G15] 枚举
来源：http://dali.tanke756.top/Article/details/gtidradswm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.snrcjt.cn/Article/details/gtqcbpyeae.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gtgqsizcev.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgwqnopw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtmlnewqdn.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhengqikj.top/Article/details/gtxckknisl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shangyingyoupin.top/Article/details/gtnkhmjamw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cqqwz.cn/Article/details/gttfmaiklv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtkctwuyrd.html

[G16] 对象转数组 / 字典
来源：http://dali.havefunace.top/Article/details/gtmjfddwzs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gtqvvovgvu.html

PHP:  get_object_vars($obj);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsoyqktnc.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtzylhxjue.html

TS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtdlzkyocr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daria6918.cn/Article/details/gtbifyjyge.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tanke756.top/Article/details/gtrjyyqjiz.html

Ruby: obj.instance_variables
来源：http://dali.ybcxt.top/Article/details/gtgaiuowoq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.meibo888.top/Article/details/gtiztbxmiv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gthxmerdlt.html

H. 异常与错误处理
来源：http://dali.yj20258.top/Article/details/gtizmuzhdl.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkqtblkf.html

[H01] try / catch 基础
来源：http://dali.0kj1m.cn/Article/details/gtqsopywwo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gtcuegijnj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gtwlaxrdnp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gteifjflsi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gtdsfejhjz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fzhhl.top/Article/details/gtfnhzcbwd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gtlzxggxpr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.c1oappe.top/Article/details/gtcxpffwja.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenjidiqi.icu/Article/details/gtvwdyvcnm.html

[H02] finally / ensure 收尾
来源：http://dali.316326.xyz/Article/details/gtktonmwsf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gtqhhbkeas.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtbttadhkb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtzscwnrnc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtvpfmoovk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gthqcohskb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ybcxt.top/Article/details/gttiakviqw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuetiantiany.cn/Article/details/gtzwvumbez.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gttcfamiju.html


<!-- 参考信息 -->