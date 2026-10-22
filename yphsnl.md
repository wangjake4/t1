代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgufenzy.top/Article/details/gt2uvmjbkcx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ivvv.top/Article/details/gt2aazszppf.html

[F03] 写入文件（覆盖）
来源：http://dali.tian-w.cn/Article/details/gt2emzbseiz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.smart0.xyz/Article/details/gt2kyazrusj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gt2cwsuvixr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gt2jhyfsfxs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gt2fgwcfycf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenlongwang.top/Article/details/gt2rnlyiany.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hkyvqjzr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gt2hohpiwig.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gt2ozanurjl.html

[F04] 追加写入文件
来源：http://dali.yueranfly.top/Article/details/gt2ttryeudq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gotoacloud.top/Article/details/gt2ciudwugf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gqyzcvxn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gt2srpuxedv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gt2jbukqfux.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rkpeztjj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258.top/Article/details/gt2teapcppo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gt2sykrvevl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fjamzmxm.html

[F05] 判断文件或目录是否存在
来源：http://dali.yongpay.top/Article/details/gt2jrqazrny.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxuanxn.top/Article/details/gt2nekghoxv.html

PHP:  file_exists("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2kmewqtxq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2xgejtmyq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmayeelq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gt2xhtcjzgv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.meibo888.top/Article/details/gt2vlbgbskm.html

Ruby: File.exist?("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2zkmrwxit.html

C#:   File.Exists("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2sjahuaxf.html

[F06] 删除文件
来源：http://dali.jinqigfzy.top/Article/details/gt2jwzbqagt.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2lvuvpvav.html

PHP:  unlink("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2tjidqzfm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2gfyuraxe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2klxubxer.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gt2vwtmwjcn.html

Go:   os.Remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2afgjgxoi.html

Ruby: File.delete("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwgcucsr.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2gzjmiddq.html

[F07] 创建目录（含多级）
来源：http://dali.havefunace.top/Article/details/gt2ycpcaltj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gt2vxblwqta.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gt2cigcspsv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gt2hxcslazl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gt2zsrmfeta.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wcdbzzkx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.havefunace.top/Article/details/gt2pkynddof.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhengqikj.top/Article/details/gt2incrxjps.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ypmkpugq.html

[F08] 遍历目录
来源：http://dali.xuanzx.com/Article/details/gt2fujnuqun.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ppjwa.cn/Article/details/gt2ahlgkrpl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvicgfxo.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2jxrzokvh.html

TS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gt2yqdszjfa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gt2sgvenclx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2wtshromy.html

Ruby: Dir.children("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qrxcstno.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuanzx.com/Article/details/gt2ywqmeeam.html

[F09] 获取文件大小
来源：http://dali.zhoulong.xyz/Article/details/gt2lwqcydet.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2mbxolvha.html

PHP:  filesize("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2njxzxrqp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gt2qyhkvixj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hkylvbpv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2buqoxtwr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shuidangran.top/Article/details/gt2stxrgjeo.html

Ruby: File.size("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2mgrxihpx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guannengcc.top/Article/details/gt2icaexpoi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cashguo.top/Article/details/gt2dvxvflvn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2lpxsqadk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2pvegdugd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2ubpewaad.html

TS:   path.extname("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2yyaypiba.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hfpthk.cn/Article/details/gt2yxoihfho.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2xwceocxa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2bzcsayqv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2cupqijhc.html

[F11] 复制与移动文件
来源：http://dali.gaohongyu789.top/Article/details/gt2huqafvvw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2whycxiei.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gt2hzhwmwno.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vehyngky.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2xgdysbsr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigufen.top/Article/details/gt2cwoycqzj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gt2nzmunyhn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gt2syspcpww.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuxming.cn/Article/details/gt2wwokcseq.html

[F12] CSV 读写
来源：http://dali.tianlin.xyz/Article/details/gt2leoajxyo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gt2fmxwbjcg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gt2pubksfxy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jyoumei.cn/Article/details/gt2hzvrhovr.html

TS:   // 同上
来源：http://dali.nanxinkj.top/Article/details/gt2znkhsiwt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gt2yjfnjemo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.birdmap.top/Article/details/gt2tlawqqgh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gt2ugothytp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jianghu66.top/Article/details/gt2zrzxtmyg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2kxvfheju.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gt2kegyvmrj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2pmfmikwl.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gt2lslqoxbn.html

Py:   class User: pass
来源：http://dali.sysykeji.top/Article/details/gt2slwunugi.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2hbikcidx.html

JS:   class User {}
来源：http://dali.redwolf501.top/Article/details/gt2yixwkiuh.html

TS:   class User { name: string = ""; }
来源：http://dali.snrcjt.cn/Article/details/gt2sagfgczc.html

Java: class User {}
来源：http://dali.xinyue.icu/Article/details/gt2hqquxzbd.html

Go:   type User struct { Name string }
来源：http://dali.aibaodan.cn/Article/details/gt2uujjuhys.html

Ruby: class User; end
来源：http://dali.jinqigufen.top/Article/details/gt2ptpubooc.html

C#:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gt2mungsbbc.html

[G02] 构造函数
来源：http://dali.shzxlz.cn/Article/details/gt2uarkbfgs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.316326.xyz/Article/details/gt2mzkelzwl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gt2iknxqptr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gt2gybzyfbu.html

TS:   constructor(public name: string) {}
来源：http://dali.yuxming.cn/Article/details/gt2lbwkpikk.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gt2sltsoqgt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfqsxzhj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenzaomai.com/Article/details/gt2yvacbmeo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zdqjudy.top/Article/details/gt2uztekzdy.html

[G03] 实例属性
来源：http://dali.xuanzx.com/Article/details/gt2fztdhggg.html

Py:   self.name = "x"
来源：http://dali.cucudq.cn/Article/details/gt2buwzrloi.html

PHP:  public string $name = "x";
来源：http://dali.redwolf501.top/Article/details/gt2ddpmtghx.html

JS:   this.name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2pmkqydfs.html

TS:   name: string = "x";
来源：http://dali.xziqi.cn/Article/details/gt2lbdunbvl.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gt2lpisywjn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.c1oappe.top/Article/details/gt2vzokuhcb.html

Ruby: @name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ndkqxryb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2rpoevoqk.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gt2xcwnvpll.html

Py:   def greet(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gt2sslhxzxw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gt2zwmkgahs.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ursmhtek.html

TS:   greet(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2tfathtbz.html

Java: String greet() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2newrucpd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekuorjvm.html

Ruby: def greet; @name; end
来源：http://dali.dashuyun.cn/Article/details/gt2adddkqsk.html

C#:   public string Greet() => Name;
来源：http://dali.yueranfly.top/Article/details/gt2qicafdrq.html

[G05] 继承
来源：http://dali.nanxinkj.top/Article/details/gt2uzglbmen.html

Py:   class Admin(User): pass
来源：http://dali.sufxvd.cn/Article/details/gt2gymxmdxj.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2hifvrxmi.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2rjwzmyvt.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2yipmooga.html

Java: class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2vluvnpaf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgufenzy.top/Article/details/gt2wcvvdmxl.html

Ruby: class Admin < User; end
来源：http://dali.ivvv.top/Article/details/gt2nbyptiaw.html

C#:   class Admin : User {}
来源：http://dali.yangfankeji.com/Article/details/gt2rahxynur.html

[G06] 重写方法
来源：http://dali.yj20258.top/Article/details/gt2ugvapsug.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gt2vklwsnng.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gt2vixnkfse.html

JS:   greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gt2jpltrxoh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2mjaresdy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2mqgyhueg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gt2zunktjnl.html

Ruby: def greet; "admin"; end
来源：http://dali.shzxlz.cn/Article/details/gt2jenfrfqs.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gt2jlegryyu.html

[G07] 调用父类方法
来源：http://dali.smart0.xyz/Article/details/gt2xcvwtxbh.html

Py:   super().greet()
来源：http://dali.yuxming.cn/Article/details/gt2bubzvhip.html

PHP:  parent::greet();
来源：http://dali.yuanzhike.top/Article/details/gt2duayqpuk.html

JS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gt2qjqpvxyp.html

TS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gt2ouxsnucw.html

Java: super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2ykvylngx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tian-w.cn/Article/details/gt2erbzfgzt.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gt2smorjedt.html

C#:   base.Greet();
来源：http://dali.hysaishi.cn/Article/details/gt2dbdfnxpn.html

[G08] 静态方法与属性
来源：http://dali.yuxming.cn/Article/details/gt2rcwsdukb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhoulong.xyz/Article/details/gt2iiguqxnd.html

PHP:  public static function f() {}
来源：http://dali.daria6918.cn/Article/details/gt2rngsfxmp.html

JS:   static f() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ocuaqoda.html

TS:   static f(): void {}
来源：http://dali.yueranfly.top/Article/details/gt2brxzrmov.html

Java: static void f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2nzslqpio.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shzxlz.cn/Article/details/gt2tdphlsnd.html

Ruby: def self.f; end
来源：http://dali.nwbrower.top/Article/details/gt2toclpecb.html

C#:   public static void F() {}
来源：http://dali.hammf.cn/Article/details/gt2efjhomdl.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigfzy.top/Article/details/gt2mjswkoml.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2gnixpijc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gt2iqakafhk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuxming.cn/Article/details/gt2asbtmrzf.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gt2gnvoeura.html

Java: interface Shape { double area(); }
来源：http://dali.gogol.net.cn/Article/details/gt2pvnepubc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yvedp.cn/Article/details/gt2rtxxdcis.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sweek.top/Article/details/gt2ylxzuuns.html

C#:   interface IShape { double Area(); }
来源：http://dali.yangfankeji.com/Article/details/gt2oolozuic.html

[G10] 访问控制
来源：http://dali.nanxinkj.top/Article/details/gt2afubquwi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.c1oappe.top/Article/details/gt2atulxwkl.html

PHP:  public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gt2krxhbuer.html

JS:   #private 字段；其余公开
来源：http://dali.ehwqpu.com/Article/details/gt2mvcohawt.html

TS:   public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gt2skgrtqru.html

Java: public / protected / private / 默认包级
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aoxkmhir.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aizwys.cn/Article/details/gt2vcfhpzvn.html

Ruby: public / protected / private
来源：http://dali.sweek.top/Article/details/gt2pvwbvxgk.html

C#:   public / protected / private / internal
来源：http://dali.zycfv.cn/Article/details/gt2agsqhiru.html

[G11] getter / setter
来源：http://dali.nanxinkj.top/Article/details/gt2xuijrcdl.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gt2tvnbnmei.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gt2yhneeeqr.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gt2ojjxldwj.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gt2lxromvid.html

Java: public String getName() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2oaxkfqys.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2axfukidd.html

Ruby: attr_accessor :name
来源：http://dali.sysykeji.top/Article/details/gt2edoqjfwi.html

C#:   public string Name { get; set; }
来源：http://dali.cheryme.top/Article/details/gt2dfpnuhwq.html

[G12] 对象转字符串
来源：http://dali.316326.xyz/Article/details/gt2fkergnrh.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abcnxtkj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rkfieoya.html

JS:   toString() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xbcgbznm.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pawlxwjw.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwthgwpr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gt2zhvozbdn.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pfcoqgvq.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gt2wvqxbwqb.html

[G13] 判断对象类型
来源：http://dali.sysykeji.top/Article/details/gt2yfdridak.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gt2iixgwpnl.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2fsikodqi.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2fifphntw.html

TS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2jpnobvnl.html

Java: u instanceof User
来源：http://dali.xylfe.cn/Article/details/gt2ebmcuwpd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.svipenyu.cn/Article/details/gt2ibgzmrlz.html

Ruby: u.is_a?(User)
来源：http://dali.ehwqpu.com/Article/details/gt2wzpttnxx.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gt2muyqqxdg.html

[G14] 数据类 / record
来源：http://dali.nanxuanxn.top/Article/details/gt2vhanpjkx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sufxvd.cn/Article/details/gt2unkjtpnc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gzhubu.top/Article/details/gt2bgriyozb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gt2ytganqcu.html

TS:   type User = { name: string; age: number };
来源：http://dali.9152youxi.cn/Article/details/gt2ybnbtqth.html

Java: record User(String name, int age) {}
来源：http://dali.snrcjt.cn/Article/details/gt2wivuioeh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgufenzy.top/Article/details/gt2xtvesbhf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.smart0.xyz/Article/details/gt2immtuuqr.html

C#:   record User(string Name, int Age);
来源：http://dali.zhixingplan.top/Article/details/gt2evklokey.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gt2xylrynpv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.bjfxy.top/Article/details/gt2rnnyftke.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tianlin.xyz/Article/details/gt2eitzbnrn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yueranfly.top/Article/details/gt2jilnmhmt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cyivtdux.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gt2vpaxrgxb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jianghu66.top/Article/details/gt2gzdtezcj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cucudq.cn/Article/details/gt2gfkqghdq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2grgqojiy.html

[G16] 对象转数组 / 字典
来源：http://dali.daria6918.cn/Article/details/gt2whwigrxo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gaohongyu789.top/Article/details/gt2rihadeed.html

PHP:  get_object_vars($obj);
来源：http://dali.hnqzz.top/Article/details/gt2fzxfzsfj.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2izoffqyu.html

TS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2khpmeilj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gt2pjwzpngm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.meibo888.top/Article/details/gt2oalikfqe.html

Ruby: obj.instance_variables
来源：http://dali.yueranfly.top/Article/details/gt2zzkonakd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gt2qnmeyire.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2qtgnoijn.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gt2jelbblhd.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2lqfssemq.html

[H01] try / catch 基础
来源：http://dali.pycfn.com/Article/details/gt2dxqygail.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wsbjowoy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2gltcybit.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gt2jewoimku.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gt2tmrpxdya.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.quarkkingdee.top/Article/details/gt2lqfqzsrf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2usgrslab.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cdnleiting.top/Article/details/gt2fhmdiurh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.316326.xyz/Article/details/gt2jrrnlrgt.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gt2btaskfzr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgufenzy.top/Article/details/gt2nrqbuotj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2uvnnivhb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2opzwayus.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2mcjtrtce.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2zprpkfnv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cqqwz.cn/Article/details/gt2rdjonixc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gt2fxepeyrc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vrhgxfje.html

[H03] 主动抛出异常
来源：http://dali.shuidangran.top/Article/details/gt2caklfirc.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258888.top/Article/details/gt2ujkmjgrm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2rtvoidlq.html

JS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2fkmulkfc.html

TS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2iwvwndyd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2gldeqont.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yangfankeji.com/Article/details/gt2cdcnpmed.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gt2mxznlbfo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2vpevxaxt.html

[H04] 自定义异常类型
来源：http://dali.yanxiufei.cn/Article/details/gt2oiqsiger.html

Py:   class MyError(Exception): pass
来源：http://dali.ivvv.top/Article/details/gt2fntjaabq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gt2twemnned.html

JS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gt2vudeuupk.html

TS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gt2shrgjavj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gt2epouxesg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zdqjudy.top/Article/details/gt2pfnykaqa.html

Ruby: class MyError < StandardError; end
来源：http://dali.yanxiufei.cn/Article/details/gt2syvycmzq.html

C#:   class MyException : Exception {}
来源：http://dali.jqgufenzy.top/Article/details/gt2oewrkjls.html

[H05] 捕获特定类型
来源：http://dali.sufxvd.cn/Article/details/gt2gvmcncsj.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwpjlsvt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cdnleiting.top/Article/details/gt2isjwztki.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2pkgpsweh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gt2yjxzsrki.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gotoacloud.top/Article/details/gt2eccjzfvz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gt2zneeueud.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenlongwang.top/Article/details/gt2yiplkshv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2pmohfavr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tvbkiqlf.html

Py:   value = d.get("k") or default
来源：http://dali.xziqi.cn/Article/details/gt2ydlztcap.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.meibo888.top/Article/details/gt2fprggnyo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gt2rnduvktd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2andzajlh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenzaomai.com/Article/details/gt2wygdjxwf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.snrcjt.cn/Article/details/gt2nmocjbxv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cqqwz.cn/Article/details/gt2gnmwrnnd.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gt2rlpauplx.html

[H07] 断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nbcjgkxv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fzhhl.top/Article/details/gt2bheyhmmu.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2obkxbwfo.html

JS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2fjbrxyji.html


<!-- 参考信息 -->