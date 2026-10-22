代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtfhwhxybj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtppjyclhy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcypuizam.html

Ruby: File.exist?("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtzerdhwkf.html

C#:   File.Exists("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtbdglzzap.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gteycjqafj.html

Py:   os.remove("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtykxxcrpp.html

PHP:  unlink("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtkvzbjmfd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtrajezwdh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtqejsqrit.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtkewiqwcl.html

Go:   os.Remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtiidqpgnc.html

Ruby: File.delete("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtucimyxyk.html

C#:   File.Delete("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtazfeoyzn.html

[F07] 创建目录（含多级）
来源：http://dali.tianlin.xyz/Article/details/gtczlgdctg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gteyegvoqt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgufenzy.top/Article/details/gtvqsurunv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gtpnewlmuv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gttxwkgbco.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhiwuduotai.top/Article/details/gtbjxorbnv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.snrcjt.cn/Article/details/gtxdikzvhe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gaohongyu789.top/Article/details/gtgqrizion.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daria6918.cn/Article/details/gtjxakhnkd.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gtdttanmqv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.smart0.xyz/Article/details/gtvjaijtuk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dashuyun.cn/Article/details/gtxpxoijlf.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtagisrgtw.html

TS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtqpgbuial.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gtbageipyr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnqzz.top/Article/details/gtnjmdfnwr.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gtdoalodxv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtatnotljb.html

[F09] 获取文件大小
来源：http://dali.xuanzx.com/Article/details/gtzpyuzfpj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtkxccjugo.html

PHP:  filesize("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtflwcxeid.html

JS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gtmuhuyrvp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtpdvdkbqz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gttmwevrhw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hongshengwenyu.top/Article/details/gtwktfepcq.html

Ruby: File.size("a.txt")
来源：http://dali.ivvv.top/Article/details/gtfdqjdwbu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xinyue.icu/Article/details/gtrcwxqzfi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhengqikj.top/Article/details/gtgfsckhbk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtudpjfqdz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gtiaqjtluf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtcjzrlfwa.html

TS:   path.extname("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gthsdxzycx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ehwqpu.com/Article/details/gtvndumaai.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtppoermtr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtsefzwoql.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtysgfivmz.html

[F11] 复制与移动文件
来源：http://dali.ivvv.top/Article/details/gtvxswsibz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtqexbhgwn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.smart0.xyz/Article/details/gtkindumgx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtmpmwqidk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtysanwcgv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtrydkfvxd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gtlnrrlcyp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtvsjtcinn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.svipenyu.cn/Article/details/gtdesxvgvs.html

[F12] CSV 读写
来源：http://dali.daria6918.cn/Article/details/gthywxqylr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ppjwa.cn/Article/details/gtealwyhfv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yanxiufei.cn/Article/details/gtkfzucmzz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gteuxvtwmq.html

TS:   // 同上
来源：http://dali.zhixingplan.top/Article/details/gtbukyfehg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cqqwz.cn/Article/details/gtnubaksoy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenzaomai.com/Article/details/gtbmehusxz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfthfwvv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jlsjyb.cn/Article/details/gtdpdcsuze.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtaascadxd.html

G. 面向对象
来源：http://dali.c1oappe.top/Article/details/gtniegqfbn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtxsmnrrbm.html

[G01] 定义类
来源：http://dali.cucudq.cn/Article/details/gtvrtasiaz.html

Py:   class User: pass
来源：http://dali.yangfankeji.com/Article/details/gtqyyvacfv.html

PHP:  class User {}
来源：http://dali.svipenyu.cn/Article/details/gtqnfzgzkb.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtposxrcpq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhoulong.xyz/Article/details/gthwowpqgj.html

Java: class User {}
来源：http://dali.jiagoushi.top/Article/details/gtwhpzsxex.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgzcdqgx.html

Ruby: class User; end
来源：http://dali.smart0.xyz/Article/details/gtstxfuiea.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtzohumktd.html

[G02] 构造函数
来源：http://dali.yj20258.top/Article/details/gtwwrqeuab.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pengpengdd.cyou/Article/details/gtbszgaqut.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhoulong.xyz/Article/details/gttrlwlhzg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gtvmtigeuz.html

TS:   constructor(public name: string) {}
来源：http://dali.xylfe.cn/Article/details/gtgbposkqx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtgsxfelym.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cqqwz.cn/Article/details/gtazbuproi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxinkj.top/Article/details/gtjfzificn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvdacjcra.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gttdzbnxms.html

Py:   self.name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtvunewvks.html

PHP:  public string $name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtaessfesp.html

JS:   this.name = "x";
来源：http://dali.xinyue.icu/Article/details/gtenullpnd.html

TS:   name: string = "x";
来源：http://dali.jyoumei.cn/Article/details/gtvrysxhhs.html

Java: private String name;
来源：http://dali.wangshuangyany.cn/Article/details/gthaiioeca.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nwbrower.top/Article/details/gtxqmpitgl.html

Ruby: @name = "x"
来源：http://dali.nwbrower.top/Article/details/gtzkbbkqre.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gtptqraiuy.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gtaruiyayu.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtomcyqxvp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtbjbdhyfs.html

JS:   greet() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtcelmkttw.html

TS:   greet(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gttaoqsdnn.html

Java: String greet() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtpgcapeut.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtvcvvuynt.html

Ruby: def greet; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gttkcphrof.html

C#:   public string Greet() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gttolntibo.html

[G05] 继承
来源：http://dali.ivvv.top/Article/details/gtsqttsevv.html

Py:   class Admin(User): pass
来源：http://dali.yj20258888.top/Article/details/gtuhfnxeli.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtnhhamsne.html

JS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtbpbhertk.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtcwnfnpkd.html

Java: class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtqwbvmjuq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cucudq.cn/Article/details/gtqjtntjhi.html

Ruby: class Admin < User; end
来源：http://dali.zhengqikj.top/Article/details/gtngsgbvyn.html

C#:   class Admin : User {}
来源：http://dali.yj20258888.top/Article/details/gtlrxyvrii.html

[G06] 重写方法
来源：http://dali.yuxming.cn/Article/details/gtolqfudwq.html

Py:   def greet(self): return "admin"
来源：http://dali.xuetiantiany.cn/Article/details/gtmdkudsut.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafvrqrcm.html

JS:   greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtonueqafq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtgxwpqztl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtnygvlfqb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gtcyqsgngt.html

Ruby: def greet; "admin"; end
来源：http://dali.xinyue.icu/Article/details/gtbxghwpdn.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gtohwpqcql.html

[G07] 调用父类方法
来源：http://dali.yvedp.cn/Article/details/gtndrojpxh.html

Py:   super().greet()
来源：http://dali.dashuyun.cn/Article/details/gtkwdrlnrc.html

PHP:  parent::greet();
来源：http://dali.quarkkingdee.top/Article/details/gtpfiimdlj.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtesspkjgt.html

TS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtsbfjqtjd.html

Java: super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtbndkaprv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gtjifqjadd.html

Ruby: super
来源：http://dali.sxryk.cn/Article/details/gtvivypgag.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gtrnjptmth.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gtjedifzha.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gtiilpqjrf.html

PHP:  public static function f() {}
来源：http://dali.xuanzx.com/Article/details/gtpgcoqgxh.html

JS:   static f() {}
来源：http://dali.aibaodan.cn/Article/details/gtwqliaqum.html

TS:   static f(): void {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjrptzfs.html

Java: static void f() {}
来源：http://dali.jyoumei.cn/Article/details/gtzkwtszym.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gtwedtkdwr.html

Ruby: def self.f; end
来源：http://dali.kuanghao11.cn/Article/details/gtgrqqfluf.html

C#:   public static void F() {}
来源：http://dali.guowangkeji.top/Article/details/gtnovwflvx.html

[G09] 接口 / 抽象类
来源：http://dali.fengsongda.top/Article/details/gttmcxdsnv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuxming.cn/Article/details/gtdctispkj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hfpthk.cn/Article/details/gtbijtmdcw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gtxrxgylqq.html

TS:   interface Shape { area(): number; }
来源：http://dali.shuidangran.top/Article/details/gtpbupzilx.html

Java: interface Shape { double area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtvpdqzsye.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.316326.xyz/Article/details/gtyaowpdkq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.quarkkingdee.top/Article/details/gtrtiadrvx.html

C#:   interface IShape { double Area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtggwrrejf.html

[G10] 访问控制
来源：http://dali.sufxvd.cn/Article/details/gtcbldgmei.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daria6918.cn/Article/details/gthzobukqf.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gtovvrxxoq.html

JS:   #private 字段；其余公开
来源：http://dali.sysykeji.top/Article/details/gtbqcvyknc.html

TS:   public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gthtdzibbu.html

Java: public / protected / private / 默认包级
来源：http://dali.feifeiyinyue.top/Article/details/gtktyuwerb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.bjfxy.top/Article/details/gtxyozioas.html

Ruby: public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gttmyzjpjw.html

C#:   public / protected / private / internal
来源：http://dali.guannengcc.top/Article/details/gtxnxdfclw.html

[G11] getter / setter
来源：http://dali.birdmap.top/Article/details/gtcagstofu.html

Py:   @property 与 @x.setter
来源：http://dali.wangdashe.top/Article/details/gtnlqogask.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtlenobhdc.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtfdojmxgh.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekdegscv.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtjojvkajf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gtnvnduuts.html

Ruby: attr_accessor :name
来源：http://dali.aibaodan.cn/Article/details/gtpfercxir.html

C#:   public string Name { get; set; }
来源：http://dali.zdqjudy.top/Article/details/gttgeaxyug.html

[G12] 对象转字符串
来源：http://dali.tanke756.top/Article/details/gtbrwepvvf.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtpzwpegld.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtyvymjohg.html

JS:   toString() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtjwjyktgx.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpxrjffhe.html

Java: @Override public String toString() { return name; }
来源：http://dali.meibo888.top/Article/details/gtokomzrfx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtczxsmcgy.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtmezfyirf.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gtllvautiu.html

[G13] 判断对象类型
来源：http://dali.cqqwz.cn/Article/details/gtgyljdcdh.html

Py:   isinstance(u, User)
来源：http://dali.daria6918.cn/Article/details/gtwtoibnoo.html

PHP:  $u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtrigkdays.html

JS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtxnozweam.html

TS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtzbbhlede.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gttsflitlo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gtawidmnxd.html

Ruby: u.is_a?(User)
来源：http://dali.bjfxy.top/Article/details/gtkqcvvtkq.html

C#:   u is User
来源：http://dali.xuanzx.com/Article/details/gtsbgmtoul.html

[G14] 数据类 / record
来源：http://dali.hnqzz.top/Article/details/gtatpltmdo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.kuanghao11.cn/Article/details/gtdtiorrjh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aizwys.cn/Article/details/gtwtpziibo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guowangkeji.top/Article/details/gtkkaobitw.html

TS:   type User = { name: string; age: number };
来源：http://dali.dianchejie.cn/Article/details/gtlzuejahp.html

Java: record User(String name, int age) {}
来源：http://dali.haohaochexian.top/Article/details/gtysmbdsyg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gtfwqbnevf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yueranfly.top/Article/details/gtbsmopitn.html

C#:   record User(string Name, int Age);
来源：http://dali.ehwqpu.com/Article/details/gtfvvowcsl.html

[G15] 枚举
来源：http://dali.mhx1999.top/Article/details/gtngonempn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hysaishi.cn/Article/details/gtacaduiiy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gtflwhauqj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gtqntppyzs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtixqdwtxl.html

Java: enum Color { RED, GREEN }
来源：http://dali.aibaodan.cn/Article/details/gtihglzkfp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gaohongyu789.top/Article/details/gtnqdzlvrg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gotoacloud.top/Article/details/gtasgvcilt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gttiljvynr.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gttlqtjotg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cdnleiting.top/Article/details/gtxjxnuotu.html

PHP:  get_object_vars($obj);
来源：http://dali.ybcxt.top/Article/details/gtelhlfbgr.html

JS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gtmxyyqvzo.html

TS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtjfmmvmtd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gtdjyevlym.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigfzy.top/Article/details/gtuktfgobe.html

Ruby: obj.instance_variables
来源：http://dali.yj20258888.top/Article/details/gtkneukvoz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtkemnqnme.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtevoqbkww.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gtpgfvtqul.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtdygpygri.html

[H01] try / catch 基础
来源：http://dali.0kj1m.cn/Article/details/gtxrwoojiz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cdnleiting.top/Article/details/gtbprtjvtz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjeebipu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gtgupjpduz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtfaorukaj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shzxlz.cn/Article/details/gtixbrrtsj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhoulong.xyz/Article/details/gtclkveeqs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xinyue.icu/Article/details/gtaghoxkvz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzohwzhs.html

[H02] finally / ensure 收尾
来源：http://dali.hfpthk.cn/Article/details/gtnuqhqvau.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aibaodan.cn/Article/details/gtljzumhja.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtxzmjjlrg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtmdzoodyk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtnkimvgeb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtgsslcqdh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnxiangtu.top/Article/details/gticqqcfek.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yonumen.top/Article/details/gtuerglckt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtqbgyuzae.html

[H03] 主动抛出异常
来源：http://dali.andypj.xyz/Article/details/gtjbtauybl.html

Py:   raise ValueError("错误信息")
来源：http://dali.jyoumei.cn/Article/details/gtaosmmtqe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtwfftsmmm.html

JS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtaccjfjvm.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtrdokvtoo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtqkuufwaf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwhkcsfo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxesncbhp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gthwrexasy.html

[H04] 自定义异常类型
来源：http://dali.hongshengwenyu.top/Article/details/gtjmvrkphv.html

Py:   class MyError(Exception): pass
来源：http://dali.redwolf501.top/Article/details/gtunkpunun.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtngwdslsj.html

JS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gtmpmbaixw.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtwxbnmorb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtxlyeqpjf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jlsjyb.cn/Article/details/gtqrkwhdaf.html

Ruby: class MyError < StandardError; end
来源：http://dali.cashguo.top/Article/details/gtblbothgt.html

C#:   class MyException : Exception {}
来源：http://dali.gotoacloud.top/Article/details/gteuzyoroz.html

[H05] 捕获特定类型
来源：http://dali.wangshuangyany.cn/Article/details/gtdqwigghj.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gtnukebmcf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gtsaokdntf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gtjtfbufzp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gtmivimbob.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hysaishi.cn/Article/details/gtoodnbppv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhoulong.xyz/Article/details/gtxvnxobbg.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj202588.top/Article/details/gtgymutwpu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenlongwang.top/Article/details/gthrdvvvyh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cqqwz.cn/Article/details/gtwzqdadsv.html

Py:   value = d.get("k") or default
来源：http://dali.cqqwz.cn/Article/details/gtkejtsuvy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yonumen.top/Article/details/gtdwvimdkw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gtzvrfjixo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gtpwnuyrcf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gaohongyu789.top/Article/details/gtaiekpwyt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ybcxt.top/Article/details/gtoxqijkey.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gotoacloud.top/Article/details/gthiuipsja.html

C#:   obj?.A?.B ?? default
来源：http://dali.aibaodan.cn/Article/details/gtlcsjvcqn.html

[H07] 断言
来源：http://dali.yonumen.top/Article/details/gtunahlyqg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aibaodan.cn/Article/details/gtoieooedy.html

PHP:  assert($x > 0);
来源：http://dali.xziqi.cn/Article/details/gttakfsyur.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtvyvxzwcc.html

TS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcqgevhz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yangfankeji.com/Article/details/gtnaxicaxy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yangfankeji.com/Article/details/gtbutrtzcc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenlongwang.top/Article/details/gtkfcrvyih.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtxjdkqxes.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenlongwang.top/Article/details/gtxadxxhnm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yangfankeji.com/Article/details/gtayiowwfo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yongpay.top/Article/details/gtxwtbhjlc.html

JS:   e.message;  e.stack
来源：http://dali.jinqigfzy.top/Article/details/gthvilvnjv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hywenlv.cn/Article/details/gtibxxbigt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hywenlv.cn/Article/details/gtsqqxkxrb.html

Go:   err.Error()
来源：http://dali.cashguo.top/Article/details/gtngfsabxw.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenjidiqi.icu/Article/details/gtcnvfdkde.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zdqjudy.top/Article/details/gtrocyizza.html

[H09] 带错误码的异常
来源：http://dali.tian-w.cn/Article/details/gtpxmyllun.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.c1oappe.top/Article/details/gttdeulght.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yvedp.cn/Article/details/gtpwvwbwiw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gtmlutfqof.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.feifeiyinyue.top/Article/details/gtnxlnioag.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gogol.net.cn/Article/details/gtlcxuikys.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.0kj1m.cn/Article/details/gtachrcrpm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jyoumei.cn/Article/details/gtroeuknvy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sufxvd.cn/Article/details/gtfjxlytzw.html

[H10] 资源自动释放
来源：http://dali.vqdsnc.cn/Article/details/gtptwwqyid.html


<!-- 参考信息 -->