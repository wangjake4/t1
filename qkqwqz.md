代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jqgfzy.top/Article/details/gtcvkjkohe.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtpxguidgv.html

F. 文件与目录
来源：http://dali.sysykeji.top/Article/details/gtnibgqpfo.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtjpxboktu.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gtvoasycxb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ppjwa.cn/Article/details/gtzjxopdwl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtugteakrj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gogol.net.cn/Article/details/gtwewfebbc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtjdhuwdor.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtbkhpmgpv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nanxinkj.top/Article/details/gtxmgbxpfk.html

Ruby: File.read("a.txt")
来源：http://dali.hnqzz.top/Article/details/gttqjehxsb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gthhrcksgr.html

[F02] 逐行读取文件
来源：http://dali.zdqjudy.top/Article/details/gtbxbvsbfx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hammf.cn/Article/details/gtlaeuottu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.smart0.xyz/Article/details/gtrtcakzoe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gtiaxxibys.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gtjhmwmoqd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gtcateyipl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gotoacloud.top/Article/details/gtpbmtcqoy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gtddjdwzcx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxuanxn.top/Article/details/gtxhbovzzj.html

[F03] 写入文件（覆盖）
来源：http://dali.zycfv.cn/Article/details/gtryovfhjv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xziqi.cn/Article/details/gtrtcnyqra.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gtqzelwtby.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gthoynvfdc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrdphoxd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgufenzy.top/Article/details/gtmhfkmwif.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.quarkkingdee.top/Article/details/gtlcqougjc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tanke756.top/Article/details/gtmnrtqquk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtetcprylq.html

[F04] 追加写入文件
来源：http://dali.svipenyu.cn/Article/details/gtfuirrfqi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuanzhike.top/Article/details/gtmupprqik.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cashguo.top/Article/details/gtkljmpzap.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtqtaokyfg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtwcuspvsu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gzhubu.top/Article/details/gtmqfunkun.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hammf.cn/Article/details/gtpzkmtmde.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sweek.top/Article/details/gtoqzcyqmg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgufenzy.top/Article/details/gtkqwzctmm.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258.top/Article/details/gtempethhj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pycfn.com/Article/details/gtvdweeswg.html

PHP:  file_exists("a.txt");
来源：http://dali.shuidangran.top/Article/details/gteffyurtm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gthpsgqjai.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtbtepvdis.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtzsdbxevo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhengqikj.top/Article/details/gtlvbnifen.html

Ruby: File.exist?("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtcffghhyz.html

C#:   File.Exists("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhqykaii.html

[F06] 删除文件
来源：http://dali.kuanghao11.cn/Article/details/gtxqgwegow.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtvrbdjzeh.html

PHP:  unlink("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtpjsboyma.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtzpecarbd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtnsuclzsm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtralqatrj.html

Go:   os.Remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gteqqqjjdv.html

Ruby: File.delete("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtflciqtzq.html

C#:   File.Delete("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtfcgooagt.html

[F07] 创建目录（含多级）
来源：http://dali.gaohongyu789.top/Article/details/gtltyredkh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yvedp.cn/Article/details/gtzqgmfceq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jiagoushi.top/Article/details/gtmjyscjoi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtdmbkcnfq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtpydmtyvx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xinyue.icu/Article/details/gtzgotofvv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.redwolf501.top/Article/details/gtflhnqthx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsryvlwp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cheryme.top/Article/details/gtgklxasnn.html

[F08] 遍历目录
来源：http://dali.chenlongwang.top/Article/details/gtchgxnrpd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tianlin.xyz/Article/details/gtwcfslkbj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnxiangtu.top/Article/details/gtnrflbdjt.html

JS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gttvsmuoqc.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gtyiilcnqb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtthlcepod.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yongpay.top/Article/details/gtcbexomoc.html

Ruby: Dir.children("dir")
来源：http://dali.nanxinkj.top/Article/details/gtrroijckw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gzhubu.top/Article/details/gtmzbswfjx.html

[F09] 获取文件大小
来源：http://dali.hnxiangtu.top/Article/details/gtaoekfzeb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtgrkrfnfy.html

PHP:  filesize("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gttwgrruqh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gtwfearphi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gtkqcylkyj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtlmnowgeq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpibrclod.html

Ruby: File.size("a.txt")
来源：http://dali.yongpay.top/Article/details/gtcwfhihio.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ehwqpu.com/Article/details/gtgfaqkixh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gticlfxjpf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtzmwyedpr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtkpjrcyon.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdbarjxi.html

TS:   path.extname("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtzsvdrirl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gtppgdazpo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtbvskrhkq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtewtyolbm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtiqccrmqq.html

[F11] 复制与移动文件
来源：http://dali.xinyue.icu/Article/details/gtkrwencrg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtgdvpeovp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.c1oappe.top/Article/details/gtedzmsouf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtvwxikclh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtgpwoqpma.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daxiang520.top/Article/details/gtfnbgfphr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.smart0.xyz/Article/details/gtrswkifeu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtosqehvke.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigfzy.top/Article/details/gtwtsdehpz.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gtbzhcqhnn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gtvqxmkhse.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aibaodan.cn/Article/details/gtllefctpv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gtcnpkfzcj.html

TS:   // 同上
来源：http://dali.9152youxi.cn/Article/details/gtzwaoypck.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gtpwrxypkt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangshuangyany.cn/Article/details/gtmeftnqrw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jyoumei.cn/Article/details/gtvsagouaq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pengpengdd.cyou/Article/details/gtpwytnywz.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtfwxrqnok.html

G. 面向对象
来源：http://dali.feifeiyinyue.top/Article/details/gtxiozynkp.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtdupuyvxg.html

[G01] 定义类
来源：http://dali.zdqjudy.top/Article/details/gtoepmzgxs.html

Py:   class User: pass
来源：http://dali.xylfe.cn/Article/details/gtphuujbge.html

PHP:  class User {}
来源：http://dali.yj202588.top/Article/details/gtzisdcqno.html

JS:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtooxgwsur.html

TS:   class User { name: string = ""; }
来源：http://dali.tian-w.cn/Article/details/gtqnomncwp.html

Java: class User {}
来源：http://dali.bjfxy.top/Article/details/gtkaaqtgmr.html

Go:   type User struct { Name string }
来源：http://dali.zhongyouzk.top/Article/details/gtkijbcztj.html

Ruby: class User; end
来源：http://dali.9152youxi.cn/Article/details/gtljewzhsw.html

C#:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gtfndpfylt.html

[G02] 构造函数
来源：http://dali.wangdashe.top/Article/details/gtlzgtsmjs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gtitltqhei.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gzhubu.top/Article/details/gthnheoyho.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtziowfrcj.html

TS:   constructor(public name: string) {}
来源：http://dali.ehwqpu.com/Article/details/gtnjivmljb.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtluirspsw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ydzc1.top/Article/details/gthbvzpyvf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jlsjyb.cn/Article/details/gtsdfvrnfc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtzriervhy.html

[G03] 实例属性
来源：http://dali.xziqi.cn/Article/details/gtqarprzks.html

Py:   self.name = "x"
来源：http://dali.sxryk.cn/Article/details/gtvosnmzgs.html

PHP:  public string $name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtizorbemw.html

JS:   this.name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtvejogwik.html

TS:   name: string = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtaftozqtm.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gtuhyayvpt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gtmpinriqd.html

Ruby: @name = "x"
来源：http://dali.birdmap.top/Article/details/gtzgqbqdyh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtroiowztk.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gtfqojbcih.html

Py:   def greet(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtmcxxcgkl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdmdsvuus.html

JS:   greet() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtddiehzho.html

TS:   greet(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtgdtfjzwe.html

Java: String greet() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gttiqlotrx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtwabfhrpj.html

Ruby: def greet; @name; end
来源：http://dali.hywenlv.cn/Article/details/gtxitdykqc.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gtwteirmew.html

[G05] 继承
来源：http://dali.cheryme.top/Article/details/gtacutemfa.html

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gtbccdubae.html

PHP:  class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtfrhxqhas.html

JS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtywcpbvbe.html

TS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtppemcdmy.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtcfkwghbn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnxiangtu.top/Article/details/gtblubzimc.html

Ruby: class Admin < User; end
来源：http://dali.jiagoushi.top/Article/details/gtopptsjvg.html

C#:   class Admin : User {}
来源：http://dali.316326.xyz/Article/details/gtzwmcbuod.html

[G06] 重写方法
来源：http://dali.shzxlz.cn/Article/details/gtbfsvpnnq.html

Py:   def greet(self): return "admin"
来源：http://dali.yangfankeji.com/Article/details/gtabkvbvxd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtihhmvysl.html

JS:   greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtlwepyhie.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtcgflwcvx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtppdpqojq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gtiyfklkol.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258.top/Article/details/gtirsplcfc.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gturcgwbjo.html

[G07] 调用父类方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdzovdka.html

Py:   super().greet()
来源：http://dali.nanxuanxn.top/Article/details/gtligoxuui.html

PHP:  parent::greet();
来源：http://dali.meibo888.top/Article/details/gtxlgoevmz.html

JS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtzgokaxog.html

TS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gttcfaucuf.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gtxhvffoaq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.316326.xyz/Article/details/gtiwtmwkku.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gtmkzdbnrj.html

C#:   base.Greet();
来源：http://dali.sysykeji.top/Article/details/gtezuamsqt.html

[G08] 静态方法与属性
来源：http://dali.gzhubu.top/Article/details/gtlequyybg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cucudq.cn/Article/details/gtrncnukdj.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtndeaduau.html

JS:   static f() {}
来源：http://dali.zycfv.cn/Article/details/gtdomeimmd.html

TS:   static f(): void {}
来源：http://dali.zhoulong.xyz/Article/details/gtldwaqxva.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtplbrpvjf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.feifeiyinyue.top/Article/details/gtywxgcmmr.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gtcvqspxqc.html

C#:   public static void F() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtcanupwsh.html

[G09] 接口 / 抽象类
来源：http://dali.xuetiantiany.cn/Article/details/gtlorqtbax.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gtsbpoxxss.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.quarkkingdee.top/Article/details/gtszebcxjx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgfzy.top/Article/details/gtxspysgku.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj202588.top/Article/details/gtoggvdhlh.html

Java: interface Shape { double area(); }
来源：http://dali.jqgufenzy.top/Article/details/gtgorkwixl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sweek.top/Article/details/gtlfwgxltl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzmqyzrt.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gtdxyfwsva.html

[G10] 访问控制
来源：http://dali.chenzaomai.com/Article/details/gtsfvbgedc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dianchejie.cn/Article/details/gtbquwcouk.html

PHP:  public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtbwlvakji.html

JS:   #private 字段；其余公开
来源：http://dali.ydzc1.top/Article/details/gtrdhrodte.html

TS:   public / protected / private
来源：http://dali.sweek.top/Article/details/gtkonjwzqm.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvfkcnfi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangshuangyany.cn/Article/details/gtowozgqet.html

Ruby: public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtplgqwnea.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gtfbskzjhg.html

[G11] getter / setter
来源：http://dali.fengsongda.top/Article/details/gtmazuayue.html

Py:   @property 与 @x.setter
来源：http://dali.pengpengdd.cyou/Article/details/gtyjnungos.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtrlauaodi.html

JS:   get name() { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtmzjyqtyi.html

TS:   get name(): string { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtqcqdowto.html

Java: public String getName() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtdnpmnmxp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjnckdxi.html

Ruby: attr_accessor :name
来源：http://dali.yuxming.cn/Article/details/gtbcvdfrhk.html

C#:   public string Name { get; set; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkktzjac.html

[G12] 对象转字符串
来源：http://dali.tianlin.xyz/Article/details/gtfybiljme.html

Py:   def __str__(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqiljvflg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtordqrney.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfoypvegs.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtscqvborw.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj202588.top/Article/details/gtfcbfzvne.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtkqagxrbd.html

Ruby: def to_s; @name; end
来源：http://dali.wangdashe.top/Article/details/gtdjevazwc.html

C#:   public override string ToString() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtgapsmhzi.html

[G13] 判断对象类型
来源：http://dali.xziqi.cn/Article/details/gtivziepbm.html

Py:   isinstance(u, User)
来源：http://dali.feifeiyinyue.top/Article/details/gtejkeazre.html

PHP:  $u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtdkitsinc.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtlmnpsmdq.html

TS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtdlrvpuoc.html

Java: u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtcnxcoatt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shuidangran.top/Article/details/gtykwhopvy.html

Ruby: u.is_a?(User)
来源：http://dali.sysykeji.top/Article/details/gtucnrzzqe.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gtqxfkfylt.html

[G14] 数据类 / record
来源：http://dali.fengsongda.top/Article/details/gtxzflgzcm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sysykeji.top/Article/details/gtwivggetd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gtqbjiwmpb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gogol.net.cn/Article/details/gtcermrqmy.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqkrochn.html

Java: record User(String name, int age) {}
来源：http://dali.redwolf501.top/Article/details/gtielqthnm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hywenlv.cn/Article/details/gtjcbtwbnw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.birdmap.top/Article/details/gtkxttpxhq.html

C#:   record User(string Name, int Age);
来源：http://dali.hammf.cn/Article/details/gtibcglazl.html

[G15] 枚举
来源：http://dali.svipenyu.cn/Article/details/gtscqwgzga.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj202588.top/Article/details/gtiodwrrcg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gtjdavtosu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guowangkeji.top/Article/details/gtindyqnfd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtjxjjfewg.html

Java: enum Color { RED, GREEN }
来源：http://dali.aibaodan.cn/Article/details/gtnajltggk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cucudq.cn/Article/details/gtvbgcncth.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fzhhl.top/Article/details/gtczvsarfc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtwgwouvoc.html

[G16] 对象转数组 / 字典
来源：http://dali.birdmap.top/Article/details/gtreqpzgya.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangshuangyany.cn/Article/details/gtrqmyxmni.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gtxmbxdqrp.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyvjnrpi.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtjuhuxeen.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtkqqmqn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhengqikj.top/Article/details/gteuradfzm.html

Ruby: obj.instance_variables
来源：http://dali.iojbl.cn/Article/details/gthorhiixi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gtwccfbrwe.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtwkuczomt.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gtncustmsr.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtyuvorpuo.html

[H01] try / catch 基础
来源：http://dali.nanxuanxn.top/Article/details/gtwzhnbcos.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtarslyvpo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhoulong.xyz/Article/details/gtxxlbpiqz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtytlbejje.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtylyboonc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdwhlktv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sysykeji.top/Article/details/gtcrvyfrpm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gtbbxxnczm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.haohaochexian.top/Article/details/gtmgbdmrat.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtwiwfpafz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shangyingyoupin.top/Article/details/gtuzrdrwbo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtthmdlrou.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtbjpypipt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtvzlfkyve.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtsriwsybh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhixingplan.top/Article/details/gtsmlcsnxx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.smart0.xyz/Article/details/gtidyoqwew.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcihbnild.html

[H03] 主动抛出异常
来源：http://dali.birdmap.top/Article/details/gtqreipizc.html

Py:   raise ValueError("错误信息")
来源：http://dali.jlsjyb.cn/Article/details/gtxobiypbs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteezwrguu.html

JS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklrfsykc.html

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtzdzfbmvv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtakouyagh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gtobtgfrvn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.iojbl.cn/Article/details/gtmvxggzmg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtoyzaentv.html

[H04] 自定义异常类型
来源：http://dali.jinqigufen.top/Article/details/gtobxdjhoz.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gtnpxxpiah.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gtnfpekcra.html

JS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtsxbchqau.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtvkfljxyb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gtwqzwocdg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuetiantiany.cn/Article/details/gthcuufpwb.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnxiangtu.top/Article/details/gtayinzkgj.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gtkptcocew.html

[H05] 捕获特定类型
来源：http://dali.xuetiantiany.cn/Article/details/gtoxqrrkvh.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gttesumvtw.html


<!-- 参考信息 -->