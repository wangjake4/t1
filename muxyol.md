代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtpinebyet.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkysozoda.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gtcijdcjta.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pycfn.com/Article/details/gtxqaapsja.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dashuyun.cn/Article/details/gtwkcfqaar.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.smart0.xyz/Article/details/gtoriaxqdx.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258888.top/Article/details/gtqpvfeuai.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gtrvwbukkf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gttakkffzh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtgixugydx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtihtmcfng.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jiagoushi.top/Article/details/gtrrdhiipa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfhqgbwg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daxiang520.top/Article/details/gtqtommmhd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gtpgtjtszb.html

[F04] 追加写入文件
来源：http://dali.zhixingplan.top/Article/details/gthidxgfcf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xziqi.cn/Article/details/gtplzvngvc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.bjfxy.top/Article/details/gtxpojihhq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gtrydqmlkc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gtvndmbxbi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gtosihiyhq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tianlin.xyz/Article/details/gtljfwxvrq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sweek.top/Article/details/gtipvghwcd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.andypj.xyz/Article/details/gtpjeonpru.html

[F05] 判断文件或目录是否存在
来源：http://dali.tian-w.cn/Article/details/gtculqmeyv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tanke756.top/Article/details/gterpjrwge.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtqplwkprc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gthrluyjoe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtvdxmdlon.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtiaoywlcn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.vqdsnc.cn/Article/details/gtqrekhtza.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtrenifxtm.html

C#:   File.Exists("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtwypnqnln.html

[F06] 删除文件
来源：http://dali.tanke756.top/Article/details/gtyckxojjr.html

Py:   os.remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtwaritmrj.html

PHP:  unlink("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtgfepcbiz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtfcclzgcx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtdsgdbjyl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtgkbuaswg.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtgicusgnp.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gttzfabvek.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbmyhiiw.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gtyciicnfr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gtxrsllpdc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yvedp.cn/Article/details/gtugoktyxg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gthfsjibpk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gtxoponzxw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gtacvprcmi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sweek.top/Article/details/gtvncbrfnw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenjidiqi.icu/Article/details/gtcppmnqbx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxinkj.top/Article/details/gtijabuwsw.html

[F08] 遍历目录
来源：http://dali.jyoumei.cn/Article/details/gtwzqotamf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.redwolf501.top/Article/details/gtkhtwuelr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkykfxuc.html

JS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gterqsnnmk.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtrlzaonem.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gtcorkywln.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtgxafwgrv.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gtxmolssaa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtnikaehpp.html

[F09] 获取文件大小
来源：http://dali.ppjwa.cn/Article/details/gtlzifiuzd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtgjlbjikt.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtqqpdhknv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gthdafloji.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtencikkqp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtcqbylled.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daria6918.cn/Article/details/gtdlciiihr.html

Ruby: File.size("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtanyxsgbb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cdnleiting.top/Article/details/gtrblzbqga.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.iojbl.cn/Article/details/gtlvdtmfyy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtfqmrlxzp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtbahsofea.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtgxopzyid.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcevhdomj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuxming.cn/Article/details/gtixzsvjbj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtkzgsmmvi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbyhodqgo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtretbknbd.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gtpxvbdvvi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtfjfobjgz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.smart0.xyz/Article/details/gtekitvlni.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtposxaohf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnafokdwd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.316326.xyz/Article/details/gtmydsyxgf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aizwys.cn/Article/details/gtwuiaojux.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtdhcnltql.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tianlin.xyz/Article/details/gtnmnshkyd.html

[F12] CSV 读写
来源：http://dali.havefunace.top/Article/details/gttbtsemzl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cheryme.top/Article/details/gthhgdfoos.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgufenzy.top/Article/details/gtbyebejpx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.9152youxi.cn/Article/details/gtprdzoxxe.html

TS:   // 同上
来源：http://dali.wangdashe.top/Article/details/gtrdialpfp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hnxiangtu.top/Article/details/gtioqtvjui.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gtscryfdcv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tian-w.cn/Article/details/gtqbbkmmtt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fengsongda.top/Article/details/gtbbngwxhb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkoieipuk.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gtlknswbzj.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtqxwkxipb.html

[G01] 定义类
来源：http://dali.havefunace.top/Article/details/gtymaumbcr.html

Py:   class User: pass
来源：http://dali.andypj.xyz/Article/details/gtgouizbjh.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gtfzbuucww.html

JS:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gtszavjsmt.html

TS:   class User { name: string = ""; }
来源：http://dali.xuanzx.com/Article/details/gtyafsubng.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gtsomshicf.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gtpkeouvkz.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gtubgssxqx.html

C#:   class User {}
来源：http://dali.xziqi.cn/Article/details/gtjfzjnipp.html

[G02] 构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtuhtfjpgi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnxiangtu.top/Article/details/gtnslftkpn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gtamfeitrz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmctqxbbh.html

TS:   constructor(public name: string) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrhtgrgft.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtmjtgifip.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.0kj1m.cn/Article/details/gtfifsgaci.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gtyhxokwok.html

C#:   public User(string name) { Name = name; }
来源：http://dali.meibo888.top/Article/details/gtohxgbukx.html

[G03] 实例属性
来源：http://dali.daria6918.cn/Article/details/gtdzjvpzyc.html

Py:   self.name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtmapkneav.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtcvvrhkja.html

JS:   this.name = "x";
来源：http://dali.sweek.top/Article/details/gttsnrygyc.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gtpfldbtau.html

Java: private String name;
来源：http://dali.cashguo.top/Article/details/gtlbheodle.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zycfv.cn/Article/details/gtwalkatlv.html

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gtkgdgcjhm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtscfrbstp.html

[G04] 定义方法
来源：http://dali.wangshuangyany.cn/Article/details/gtlwccyhaj.html

Py:   def greet(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtvpacxins.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtchpeuydh.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtwrkkdfke.html

TS:   greet(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtcxvjxchx.html

Java: String greet() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtssoshukx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtdmjkpckf.html

Ruby: def greet; @name; end
来源：http://dali.jinqigufen.top/Article/details/gttebeuhoz.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gtojormarg.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gtishazrrf.html

Py:   class Admin(User): pass
来源：http://dali.bjfxy.top/Article/details/gtqothzfzi.html

PHP:  class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtvuafslat.html

JS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxijaxamq.html

TS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtkjaastyl.html

Java: class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtksqxgvhs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnxiangtu.top/Article/details/gtvfxoqjcx.html

Ruby: class Admin < User; end
来源：http://dali.jianghu66.top/Article/details/gtixrnudsz.html

C#:   class Admin : User {}
来源：http://dali.gaohongyu789.top/Article/details/gtgbezxywl.html

[G06] 重写方法
来源：http://dali.haohaochexian.top/Article/details/gtwhksoyrg.html

Py:   def greet(self): return "admin"
来源：http://dali.nwbrower.top/Article/details/gtsppblltd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtldihpnpw.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtiqwtlsed.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtydcggmdq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtgrqddjop.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gtrsgsxycq.html

Ruby: def greet; "admin"; end
来源：http://dali.bjfxy.top/Article/details/gtjaleqhaq.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gttogqjmok.html

[G07] 调用父类方法
来源：http://dali.hammf.cn/Article/details/gtfiilquhf.html

Py:   super().greet()
来源：http://dali.kuanghao11.cn/Article/details/gtiyyklepb.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gtsaqbpatv.html

JS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtbqxhtmwq.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtbnswoqza.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gttnijxyqt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gtgfixnrzm.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gtgsxiwinq.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtcxcjhnue.html

[G08] 静态方法与属性
来源：http://dali.tian-w.cn/Article/details/gtukacmuvc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjyampsn.html

PHP:  public static function f() {}
来源：http://dali.shuidangran.top/Article/details/gtyzfnffwx.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtaqtyjeau.html

TS:   static f(): void {}
来源：http://dali.shzxlz.cn/Article/details/gtaxehftul.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtzrafothx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gtkvgzwatk.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gtrlbbsqtv.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gtdjuaxgcp.html

[G09] 接口 / 抽象类
来源：http://dali.hammf.cn/Article/details/gtyllgqpup.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhkionpa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.316326.xyz/Article/details/gthhsaawgj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuanzx.com/Article/details/gtcsxzpikr.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwuqparg.html

Java: interface Shape { double area(); }
来源：http://dali.tian-w.cn/Article/details/gtsdhzqkgx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gtasqfhhaf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ydzc1.top/Article/details/gtjsirrvej.html

C#:   interface IShape { double Area(); }
来源：http://dali.shzxlz.cn/Article/details/gtbfkpwztm.html

[G10] 访问控制
来源：http://dali.tanke756.top/Article/details/gtzrerhoym.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgfzy.top/Article/details/gtkcfodrle.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtmeuqkhho.html

JS:   #private 字段；其余公开
来源：http://dali.hongshengwenyu.top/Article/details/gtvflcosxe.html

TS:   public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtcnfuyais.html

Java: public / protected / private / 默认包级
来源：http://dali.daria6918.cn/Article/details/gtmelrtbpw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangdashe.top/Article/details/gtdqmuiwcp.html

Ruby: public / protected / private
来源：http://dali.fzhhl.top/Article/details/gttyvavklv.html

C#:   public / protected / private / internal
来源：http://dali.cheryme.top/Article/details/gthpxuluys.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gtdizvlayw.html

Py:   @property 与 @x.setter
来源：http://dali.zhoulong.xyz/Article/details/gtropelpbl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtzwibifjp.html

JS:   get name() { return this._name; }
来源：http://dali.cheryme.top/Article/details/gtcmgxabph.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gtobwisoth.html

Java: public String getName() { return name; }
来源：http://dali.hammf.cn/Article/details/gtehghekta.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtxaakwabb.html

Ruby: attr_accessor :name
来源：http://dali.xylfe.cn/Article/details/gtjzpdfkbt.html

C#:   public string Name { get; set; }
来源：http://dali.yvedp.cn/Article/details/gtqojkwziz.html

[G12] 对象转字符串
来源：http://dali.316326.xyz/Article/details/gtzhockaox.html

Py:   def __str__(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtdxnwihvk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtfyedyrdv.html

JS:   toString() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtolyeozgc.html

TS:   toString(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtxrrnaxxc.html

Java: @Override public String toString() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtprrzxklw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtjzusjenj.html

Ruby: def to_s; @name; end
来源：http://dali.yonumen.top/Article/details/gttczqwisp.html

C#:   public override string ToString() => Name;
来源：http://dali.fengsongda.top/Article/details/gtxoenptea.html

[G13] 判断对象类型
来源：http://dali.yvedp.cn/Article/details/gtthuintuu.html

Py:   isinstance(u, User)
来源：http://dali.yvedp.cn/Article/details/gtcrfzhjjw.html

PHP:  $u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtiismwvic.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtjwnpkqjm.html

TS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtdvjkadnm.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtscrddhnk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gtjjhejxsr.html

Ruby: u.is_a?(User)
来源：http://dali.pycfn.com/Article/details/gtgdnhrnkb.html

C#:   u is User
来源：http://dali.hfpthk.cn/Article/details/gtbcpvkbwe.html

[G14] 数据类 / record
来源：http://dali.tian-w.cn/Article/details/gtlzgxgcea.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gtztvhdizw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gthsdgdezf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.andypj.xyz/Article/details/gtqrdjpoub.html

TS:   type User = { name: string; age: number };
来源：http://dali.hammf.cn/Article/details/gtozfiwkgi.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gtjepqmahm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.smart0.xyz/Article/details/gtqvfufvaq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.snrcjt.cn/Article/details/gtxaxwrizw.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gtxtmyszkg.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gtszjvnacq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.feifeiyinyue.top/Article/details/gttzbggqpr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nwbrower.top/Article/details/gtarnadkpc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xinyue.icu/Article/details/gtvgyiklyv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtqcsvpeat.html

Java: enum Color { RED, GREEN }
来源：http://dali.haohaochexian.top/Article/details/gtslssrxel.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gtzbfshihu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sxryk.cn/Article/details/gtmmyxshca.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gtshezbztq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhongyouzk.top/Article/details/gtpocqksml.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnxiangtu.top/Article/details/gtfkmvufuk.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gtkjnwitqq.html

JS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtrrlsczop.html

TS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gttyxrnokj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.0kj1m.cn/Article/details/gthwihrblt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yonumen.top/Article/details/gtzacewokd.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gtlqdpdqpg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gtozmjxgsg.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtdcvqhdre.html

H. 异常与错误处理
来源：http://dali.havefunace.top/Article/details/gthhdnybgu.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtociqumbj.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gtcpdnghht.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhongyouzk.top/Article/details/gttcheblns.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jianghu66.top/Article/details/gtvapumevt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gthwvzrmdf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gtllsfijxv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sufxvd.cn/Article/details/gtixtqxyxj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcutwczkj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tian-w.cn/Article/details/gtidmkhmup.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gtsrdhzjsm.html

[H02] finally / ensure 收尾
来源：http://dali.haohaochexian.top/Article/details/gttfbfawhi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xylfe.cn/Article/details/gtzndwlkvh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtwsuqkovq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gttonbrdlk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtfcturvgj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtveyuwilb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sxryk.cn/Article/details/gtsxgflgzw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.iojbl.cn/Article/details/gtowkksoqn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtuzrqvgwv.html

[H03] 主动抛出异常
来源：http://dali.ppjwa.cn/Article/details/gtnrkfohxa.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuanzx.com/Article/details/gtowfqlmht.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gthbjhqynf.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhftxibn.html

TS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtdueyroyq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtugzwjjwp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cdnleiting.top/Article/details/gtofgqjjlk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ivvv.top/Article/details/gtsokkyrug.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtgxtdmfmg.html

[H04] 自定义异常类型
来源：http://dali.fzhhl.top/Article/details/gtbvkltnhe.html

Py:   class MyError(Exception): pass
来源：http://dali.yonumen.top/Article/details/gtrdcjmlva.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtdeuvaion.html

JS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gtxqhwedfw.html

TS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gtehohcdjv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtoiuozmyv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.feifeiyinyue.top/Article/details/gtzoluvaxe.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuxming.cn/Article/details/gtjfvtzniu.html

C#:   class MyException : Exception {}
来源：http://dali.yj202588.top/Article/details/gtmfgnjbxi.html

[H05] 捕获特定类型
来源：http://dali.chenlongwang.top/Article/details/gtmsbfnozp.html

Py:   except ValueError as e:
来源：http://dali.vqdsnc.cn/Article/details/gtwmhhlpyz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaohduarj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gtekxwlaiw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gtjvrbybsz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.bjfxy.top/Article/details/gtlcchwfjb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gtseifsqqr.html

Ruby: rescue ArgumentError => e
来源：http://dali.jianghu66.top/Article/details/gtousjrhqd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gtjhyavtfh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gtpcfhwora.html

Py:   value = d.get("k") or default
来源：http://dali.bjfxy.top/Article/details/gtvqtjlnaw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gtjjzhufme.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtncmqhxhc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gtlkojhwnz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.kuanghao11.cn/Article/details/gtsbxzjjmn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gthxdvhxxs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuetiantiany.cn/Article/details/gthahquimi.html

C#:   obj?.A?.B ?? default
来源：http://dali.gotoacloud.top/Article/details/gtiwgpyxtz.html


<!-- 参考信息 -->