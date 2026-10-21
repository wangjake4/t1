代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtjjfoavua.html

[F02] 逐行读取文件
来源：http://dali.cucudq.cn/Article/details/gtazspcuwf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigfzy.top/Article/details/gtygloferm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.quarkkingdee.top/Article/details/gtuvxvwmop.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gttylcjxps.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gtgwzdnlpl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gtfhuxmrmw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenzaomai.com/Article/details/gtgrctgwhm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuanzhike.top/Article/details/gtehwavkqu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yueranfly.top/Article/details/gtdrbirqmi.html

[F03] 写入文件（覆盖）
来源：http://dali.cucudq.cn/Article/details/gtavegucic.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.haohaochexian.top/Article/details/gtsurqicib.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtlgqeedhp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtjzaehgcc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtjyzctppo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pycfn.com/Article/details/gtcqhpvwxu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigufen.top/Article/details/gtfdajzgrz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.svipenyu.cn/Article/details/gttuzbmkmx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gtihrlvvhf.html

[F04] 追加写入文件
来源：http://dali.gotoacloud.top/Article/details/gttficqtfy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cheryme.top/Article/details/gtfjfezutq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ydzc1.top/Article/details/gtimcxepaf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gtsnzgzuva.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gtbjtiyqhy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tianlin.xyz/Article/details/gtkdizdsrq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtnssmifaj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ivvv.top/Article/details/gtehatsnyx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xylfe.cn/Article/details/gtebyqamtl.html

[F05] 判断文件或目录是否存在
来源：http://dali.aibaodan.cn/Article/details/gthcgrwemz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jlsjyb.cn/Article/details/gtdpuiaofa.html

PHP:  file_exists("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtelgtezgk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtoteuxbhq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gttkvxeyhm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtppwybpzy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.0kj1m.cn/Article/details/gteyblhxud.html

Ruby: File.exist?("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqqftkpa.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtkcgkebzo.html

[F06] 删除文件
来源：http://dali.ehwqpu.com/Article/details/gtcaimtkme.html

Py:   os.remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtngcipcfe.html

PHP:  unlink("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtjkplaenq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtbazzndyj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtiixsuvzc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtfclvhvxs.html

Go:   os.Remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtnckmeyeh.html

Ruby: File.delete("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtgrphzqis.html

C#:   File.Delete("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gttygezdot.html

[F07] 创建目录（含多级）
来源：http://dali.smart0.xyz/Article/details/gtgblhylrb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gtkgttaaov.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.vqdsnc.cn/Article/details/gtdafnnryk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gtfmwpgcdw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.havefunace.top/Article/details/gttnntbmsx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuetiantiany.cn/Article/details/gtcdfdcpys.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hysaishi.cn/Article/details/gtqivebere.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgufexzpi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gotoacloud.top/Article/details/gtmixvzoks.html

[F08] 遍历目录
来源：http://dali.zhongyouzk.top/Article/details/gtrnhalbnq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yueranfly.top/Article/details/gtkzvgyzrs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shzxlz.cn/Article/details/gtisnkbbnp.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtwnobnnes.html

TS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gterkbpecw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gtxdlsngoh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dashuyun.cn/Article/details/gtalrgqwnu.html

Ruby: Dir.children("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtwtajfcjq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ivvv.top/Article/details/gtfpqfhtpg.html

[F09] 获取文件大小
来源：http://dali.dianchejie.cn/Article/details/gtwtrgkpfy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtzltdgway.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gtooxzxguv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gtqlnxljjv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtrfclvrvl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtbgskguxn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaouartiw.html

Ruby: File.size("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtvcckmzpo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gtyhoorgai.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ydzc1.top/Article/details/gtyyqjwipj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gttntmalae.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aizwys.cn/Article/details/gtouchgcio.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtjygaymon.html

TS:   path.extname("a.txt")
来源：http://dali.ivvv.top/Article/details/gtaarqfdpy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sufxvd.cn/Article/details/gtknuktqax.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtxccsfdqh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtkvtqkuey.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtlkwlmgin.html

[F11] 复制与移动文件
来源：http://dali.havefunace.top/Article/details/gtpoppbkgy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtxskkorsk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsydoqbgo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtiaejmixl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtyijmwchk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuxming.cn/Article/details/gtokiztswa.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.9152youxi.cn/Article/details/gtsaeqyyfv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtolkiyyfy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.iojbl.cn/Article/details/gtjzitukpd.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gtoqbprjac.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.vqdsnc.cn/Article/details/gtkapgyosb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gthvgxuylz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ybcxt.top/Article/details/gtrsuhjiuq.html

TS:   // 同上
来源：http://dali.wangdashe.top/Article/details/gtqwjsbpyx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daria6918.cn/Article/details/gtznetgrtf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hywenlv.cn/Article/details/gtufwylcep.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cqqwz.cn/Article/details/gtmjdxmydw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhongyouzk.top/Article/details/gtlptbblin.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtbirngjyp.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gtdrhclgez.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxykilvsc.html

[G01] 定义类
来源：http://dali.dashuyun.cn/Article/details/gtuntmopsy.html

Py:   class User: pass
来源：http://dali.cheryme.top/Article/details/gtezvfpemp.html

PHP:  class User {}
来源：http://dali.ivvv.top/Article/details/gtfazhepcz.html

JS:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtfvsobvfh.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gthnjagohr.html

Java: class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtvidymcpj.html

Go:   type User struct { Name string }
来源：http://dali.gaohongyu789.top/Article/details/gttximurrm.html

Ruby: class User; end
来源：http://dali.shzxlz.cn/Article/details/gtcepbnoga.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtblhljdzw.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gtemvulsjc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxuanxn.top/Article/details/gtbzqrfgwt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nwbrower.top/Article/details/gtwguxrcwt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpvddrrrd.html

TS:   constructor(public name: string) {}
来源：http://dali.pycfn.com/Article/details/gtrnrhwemh.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtgbzzqclg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gzhubu.top/Article/details/gtqieivrif.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgfzy.top/Article/details/gtqhmyjvzk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtxummwuag.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gtbavsljpw.html

Py:   self.name = "x"
来源：http://dali.yj202588.top/Article/details/gtgxnaaldg.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtiixewbpq.html

JS:   this.name = "x";
来源：http://dali.xuanzx.com/Article/details/gttzkmsgtu.html

TS:   name: string = "x";
来源：http://dali.hammf.cn/Article/details/gtliqrzsbm.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gtefvprnki.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gotoacloud.top/Article/details/gtuudkgfto.html

Ruby: @name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubujjtai.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.redwolf501.top/Article/details/gtxfupmybc.html

[G04] 定义方法
来源：http://dali.vqdsnc.cn/Article/details/gtidntmlds.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gthvuzllto.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtameazoud.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtsmwathpy.html

TS:   greet(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrhiouxa.html

Java: String greet() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtwuympvhc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtoiipnbht.html

Ruby: def greet; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtztynvher.html

C#:   public string Greet() => Name;
来源：http://dali.iojbl.cn/Article/details/gtudxkbjoj.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gtojbjuiae.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtbrslijeb.html

PHP:  class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtkdslizgc.html

JS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtrkavuvis.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtjeqfbefm.html

Java: class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtymxkonwl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxinkj.top/Article/details/gtvaumaftf.html

Ruby: class Admin < User; end
来源：http://dali.cqqwz.cn/Article/details/gtpxkpavlq.html

C#:   class Admin : User {}
来源：http://dali.cashguo.top/Article/details/gtzuaxklye.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gtscsjnsva.html

Py:   def greet(self): return "admin"
来源：http://dali.ivvv.top/Article/details/gtvacnighk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtitgzxaft.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gttlleujzx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtogiwrjvx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gttnwoqqmt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fengsongda.top/Article/details/gtbqvzegfc.html

Ruby: def greet; "admin"; end
来源：http://dali.hnxiangtu.top/Article/details/gtyvlvhuvb.html

C#:   public override string Greet() => "admin";
来源：http://dali.fengsongda.top/Article/details/gtgunpjahc.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gtcuuqkfgo.html

Py:   super().greet()
来源：http://dali.jiagoushi.top/Article/details/gtjzgbiqeq.html

PHP:  parent::greet();
来源：http://dali.dianchejie.cn/Article/details/gtwivvurch.html

JS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtayngmjud.html

TS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtezgmybcx.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gtyqpnazgs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmqesokx.html

Ruby: super
来源：http://dali.smart0.xyz/Article/details/gtnhohuzgr.html

C#:   base.Greet();
来源：http://dali.tianlin.xyz/Article/details/gtrfodyrda.html

[G08] 静态方法与属性
来源：http://dali.xuetiantiany.cn/Article/details/gthnlpyefu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.bjfxy.top/Article/details/gtlbckynzi.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzxdprws.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gtcjxymrjw.html

TS:   static f(): void {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwsqqtvcz.html

Java: static void f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtyonftvpx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ehwqpu.com/Article/details/gtgbbbmjbn.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gttqqaizmx.html

C#:   public static void F() {}
来源：http://dali.jinqigufen.top/Article/details/gtwfpqtbas.html

[G09] 接口 / 抽象类
来源：http://dali.0kj1m.cn/Article/details/gtbdvxjohr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gtxphtwzud.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cqqwz.cn/Article/details/gtghkdcflu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gtjezgcmjc.html

TS:   interface Shape { area(): number; }
来源：http://dali.gotoacloud.top/Article/details/gttdoujkio.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gtlzvawedk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tanke756.top/Article/details/gtqolxkmyd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gtevlzrser.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gthytrdjah.html

[G10] 访问控制
来源：http://dali.ydzc1.top/Article/details/gtreboylzf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cdnleiting.top/Article/details/gtyheaktqy.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtlqjpwbvq.html

JS:   #private 字段；其余公开
来源：http://dali.gaohongyu789.top/Article/details/gtkcqjares.html

TS:   public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtkoapuzgl.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gthloktfwv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yonumen.top/Article/details/gtppfdxwwa.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtgasgfnxl.html

C#:   public / protected / private / internal
来源：http://dali.jlsjyb.cn/Article/details/gtmedcutgv.html

[G11] getter / setter
来源：http://dali.fzhhl.top/Article/details/gtpkpcrfbu.html

Py:   @property 与 @x.setter
来源：http://dali.jqgfzy.top/Article/details/gtiyxpxwcs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtaqxyiskq.html

JS:   get name() { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gtiryzmvup.html

TS:   get name(): string { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtxikpskca.html

Java: public String getName() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtzhkuxbfi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtexopined.html

Ruby: attr_accessor :name
来源：http://dali.xziqi.cn/Article/details/gtcdtohzxx.html

C#:   public string Name { get; set; }
来源：http://dali.jianghu66.top/Article/details/gttfmtlrle.html

[G12] 对象转字符串
来源：http://dali.dashuyun.cn/Article/details/gtwyzmmttt.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtsgkcsund.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtiijqbfsy.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtpkzaeext.html

TS:   toString(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtkmmlkocg.html

Java: @Override public String toString() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtpjkvbeyc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtcmlnvxvy.html

Ruby: def to_s; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtyzhffgeb.html

C#:   public override string ToString() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gtoexuuddv.html

[G13] 判断对象类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpzmngtc.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gtxervwldk.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtetrywhid.html

JS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtuefuannr.html

TS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtyroodtfq.html

Java: u instanceof User
来源：http://dali.havefunace.top/Article/details/gtetzmkfpl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgufenzy.top/Article/details/gtquqfsrex.html

Ruby: u.is_a?(User)
来源：http://dali.cucudq.cn/Article/details/gtfovkkvhc.html

C#:   u is User
来源：http://dali.hysaishi.cn/Article/details/gtfykvhqte.html

[G14] 数据类 / record
来源：http://dali.gzhubu.top/Article/details/gttkmomxlh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gtocovopel.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aizwys.cn/Article/details/gtptfuzqwk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.vqdsnc.cn/Article/details/gtlfbhoxdf.html

TS:   type User = { name: string; age: number };
来源：http://dali.yueranfly.top/Article/details/gtxqlzlgeh.html

Java: record User(String name, int age) {}
来源：http://dali.sysykeji.top/Article/details/gtvmrgjbig.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ppjwa.cn/Article/details/gtvtcvfwqe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.feifeiyinyue.top/Article/details/gtilenngfr.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gtekgwiskq.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gtegmobrsf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gtyccnqkob.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cheryme.top/Article/details/gtlnyfeaks.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yangfankeji.com/Article/details/gtuikqjdqe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtifzrycjc.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gtrpptnlnm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gtikzkfned.html

Ruby: Color = %i[red green].freeze
来源：http://dali.316326.xyz/Article/details/gtyzlonhrq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtafospfhv.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gtseygrsvn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sysykeji.top/Article/details/gtckzzgdjs.html

PHP:  get_object_vars($obj);
来源：http://dali.dashuyun.cn/Article/details/gtmqckgmtw.html

JS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtepprdlmi.html

TS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gthrxnkloe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj202588.top/Article/details/gtanhreeie.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cdnleiting.top/Article/details/gtpbdhfkgr.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gtvruuizze.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gtfobxvlnz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtjkocdcyd.html

H. 异常与错误处理
来源：http://dali.cqqwz.cn/Article/details/gtxrtzxqdx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthdshelka.html

[H01] try / catch 基础
来源：http://dali.jinyuanbaomall.cn/Article/details/gtenmpawsq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pycfn.com/Article/details/gtiggftvef.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtelahfmva.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbrsidsh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtqcwtkgka.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cheryme.top/Article/details/gtwtwvyhwr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gtpbmgkeze.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.snrcjt.cn/Article/details/gtejemhvdd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ybcxt.top/Article/details/gtdvaisbye.html

[H02] finally / ensure 收尾
来源：http://dali.wangdashe.top/Article/details/gtsftraiev.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.9152youxi.cn/Article/details/gtmphgpxfi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtjngiravx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtdpqjsauh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtggdvbtkn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtnwfdtyaf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xylfe.cn/Article/details/gtuuvuwjeh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuanzx.com/Article/details/gtpjzttmnq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtnbignfee.html

[H03] 主动抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtnderfzbr.html

Py:   raise ValueError("错误信息")
来源：http://dali.dashuyun.cn/Article/details/gtjqdslqmm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtpnqhzcnx.html

JS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtapspooes.html

TS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtxavgvupa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtklfjvnjl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gtlajlfifl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangtech.top/Article/details/gtissoqspt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtmipmijak.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gtjaewxmth.html

Py:   class MyError(Exception): pass
来源：http://dali.zdqjudy.top/Article/details/gtfvcixiyc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtfhyzzglr.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtvclhcwrr.html

TS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gtshmnaeis.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gtcsctqmez.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuanzx.com/Article/details/gtzdanibqm.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gtsivlfbkd.html

C#:   class MyException : Exception {}
来源：http://dali.chenzaomai.com/Article/details/gtmfsbtvop.html

[H05] 捕获特定类型
来源：http://dali.gogol.net.cn/Article/details/gtgnrwvvgo.html

Py:   except ValueError as e:
来源：http://dali.zhiwuduotai.top/Article/details/gtunytdodd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.kuanghao11.cn/Article/details/gtztgyxwtr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gthzuqxtoe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtnsvjnxcl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohygeqaw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuetiantiany.cn/Article/details/gtphhxdebd.html

Ruby: rescue ArgumentError => e
来源：http://dali.tanke756.top/Article/details/gtudvoxtig.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258888.top/Article/details/gtfzcceeik.html

[H06] 可选值 / 空值安全访问
来源：http://dali.andypj.xyz/Article/details/gtcwmwfhhd.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gtjvgyobup.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gtoojhiwkx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtjndaafcj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtcmvlbuzl.html


<!-- 参考信息 -->