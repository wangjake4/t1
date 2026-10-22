代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yonumen.top/Article/details/gt2eqrlcxbq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnqzz.top/Article/details/gt2mhqntyqo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gt2yerltcml.html

[F08] 遍历目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2rbbaooaq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gpfgqbow.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wgjzzyjd.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2hlblxrle.html

TS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rnbeuvvh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gt2btrlrtfw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.smart0.xyz/Article/details/gt2olmzbfkr.html

Ruby: Dir.children("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hqbkxsmc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2zxnhxwft.html

[F09] 获取文件大小
来源：http://dali.jqgfzy.top/Article/details/gt2tcjvecvw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2oflcxhox.html

PHP:  filesize("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ybrzvuqt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gt2veujnbmq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gt2yjrcrilw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gt2jvxoyrzq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cucudq.cn/Article/details/gt2ltzzevpw.html

Ruby: File.size("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2ouagdxtq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cashguo.top/Article/details/gt2rmeozzil.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuxming.cn/Article/details/gt2evdvzkav.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2olrykgrv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tanke756.top/Article/details/gt2launiabe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2ktioeonu.html

TS:   path.extname("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qqyzbosh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkuishha.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ufgwhjwr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2tzktxzpb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2qucefdty.html

[F11] 复制与移动文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2mpunkapm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oquqxzfp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2srnglryz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2dnqbqhlu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2alltvddi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gt2kmlnoncw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258.top/Article/details/gt2pcvfcxrr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2sacglqot.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gt2hnzrykvt.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gt2xfizteyx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhoulong.xyz/Article/details/gt2ymjisqmu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gotoacloud.top/Article/details/gt2suczltrg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.meibo888.top/Article/details/gt2jjaivzlw.html

TS:   // 同上
来源：http://dali.316326.xyz/Article/details/gt2cixjvuvo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.redwolf501.top/Article/details/gt2aljqpeji.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zaevmszh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gt2cjujparc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daxiang520.top/Article/details/gt2scsppuyn.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2zfunpvbr.html

G. 面向对象
来源：http://dali.nwbrower.top/Article/details/gt2hdjeobgp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2gfcoouzg.html

[G01] 定义类
来源：http://dali.yj20258.top/Article/details/gt2nwkudhnk.html

Py:   class User: pass
来源：http://dali.cdnleiting.top/Article/details/gt2pzgzyftb.html

PHP:  class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftddctzi.html

JS:   class User {}
来源：http://dali.xziqi.cn/Article/details/gt2gedqieyx.html

TS:   class User { name: string = ""; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qyivzbcb.html

Java: class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2htghtlwq.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gt2hgisvsuf.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gt2dvsstmfu.html

C#:   class User {}
来源：http://dali.fzhhl.top/Article/details/gt2qaxmlxsc.html

[G02] 构造函数
来源：http://dali.havefunace.top/Article/details/gt2miciouqm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnxiangtu.top/Article/details/gt2mjbwnakz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gt2mehfdkcm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gt2kgosrwly.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gt2pglcuvjr.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2facwjxdc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gt2cllmisme.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2iyzratkz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gt2jfeunqua.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gt2ngyosref.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gt2bbqoplfo.html

PHP:  public string $name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rztssfme.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2qhjvxvnm.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gt2kzlszgfh.html

Java: private String name;
来源：http://dali.yuanzhike.top/Article/details/gt2sisvnirl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gt2sihzzolg.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gt2vzwkeqxu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2preqyjat.html

[G04] 定义方法
来源：http://dali.aizwys.cn/Article/details/gt2wzjufhgw.html

Py:   def greet(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gt2gfocghpj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gt2vueqpmch.html

JS:   greet() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2yshshqjk.html

TS:   greet(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gt2slwyeaeo.html

Java: String greet() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2dwxcxhhr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2edgiykhl.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gt2rslujqwo.html

C#:   public string Greet() => Name;
来源：http://dali.havefunace.top/Article/details/gt2sbgcergj.html

[G05] 继承
来源：http://dali.gzhubu.top/Article/details/gt2kvxcrncx.html

Py:   class Admin(User): pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2hmoyyqvg.html

PHP:  class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2ahyzvede.html

JS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2jlfyjbds.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2yfctdayr.html

Java: class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gt2ssfionsv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.snrcjt.cn/Article/details/gt2hbhmlzpu.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gt2xfgofetg.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2smwmpfsd.html

[G06] 重写方法
来源：http://dali.hnqzz.top/Article/details/gt2kjzorygb.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gt2vfwftanb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2hgxmmvht.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2unkxwsif.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2qntkcajo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2tmvicfze.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxwkkjlv.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gt2usmsmtrg.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gt2cqopjtln.html

[G07] 调用父类方法
来源：http://dali.sweek.top/Article/details/gt2rcxwsdpp.html

Py:   super().greet()
来源：http://dali.mhx1999.top/Article/details/gt2gbgqtbcq.html

PHP:  parent::greet();
来源：http://dali.chenzaomai.com/Article/details/gt2sggvkctm.html

JS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gt2ymfhnfcm.html

TS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gt2bqxjhxkl.html

Java: super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2degidfvb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2opionfkp.html

Ruby: super
来源：http://dali.shangyingyoupin.top/Article/details/gt2ssoicjee.html

C#:   base.Greet();
来源：http://dali.mhx1999.top/Article/details/gt2kditmbrs.html

[G08] 静态方法与属性
来源：http://dali.quarkkingdee.top/Article/details/gt2orwiuhnq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dashuyun.cn/Article/details/gt2pairseqj.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gt2qpgssyix.html

JS:   static f() {}
来源：http://dali.fengsongda.top/Article/details/gt2oskpdmgh.html

TS:   static f(): void {}
来源：http://dali.shuidangran.top/Article/details/gt2gprwxymj.html

Java: static void f() {}
来源：http://dali.yongpay.top/Article/details/gt2urwmaaaz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenzaomai.com/Article/details/gt2rfgvkbuc.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bhsnulum.html

C#:   public static void F() {}
来源：http://dali.zhixingplan.top/Article/details/gt2lhnrirsa.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gt2vxufdjha.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hammf.cn/Article/details/gt2mochakms.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.316326.xyz/Article/details/gt2bxibvvle.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbbdysms.html

TS:   interface Shape { area(): number; }
来源：http://dali.cucudq.cn/Article/details/gt2jfcxbmfh.html

Java: interface Shape { double area(); }
来源：http://dali.yongpay.top/Article/details/gt2amnfiqya.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.meibo888.top/Article/details/gt2wlxatkko.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.9152youxi.cn/Article/details/gt2schhbhlu.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2vszyvatu.html

[G10] 访问控制
来源：http://dali.0kj1m.cn/Article/details/gt2rpasodfz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnqzz.top/Article/details/gt2eluokufk.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2tquymfbw.html

JS:   #private 字段；其余公开
来源：http://dali.jianghu66.top/Article/details/gt2czmldaas.html

TS:   public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gt2zhftncpr.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258888.top/Article/details/gt2asngbahb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gt2nnpwyunw.html

Ruby: public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2ebuxolpv.html

C#:   public / protected / private / internal
来源：http://dali.yvedp.cn/Article/details/gt2ppyaezbh.html

[G11] getter / setter
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dtcontvc.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gt2qhzcsdpi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2uzgmjopu.html

JS:   get name() { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xrfsllvf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2akcsrhfn.html

Java: public String getName() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2vxlchgjv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2npmffqpv.html

Ruby: attr_accessor :name
来源：http://dali.pengpengdd.cyou/Article/details/gt2wnwguhkd.html

C#:   public string Name { get; set; }
来源：http://dali.smart0.xyz/Article/details/gt2hnaexbui.html

[G12] 对象转字符串
来源：http://dali.hywenlv.cn/Article/details/gt2louitzqt.html

Py:   def __str__(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gt2hwrlcjur.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2uwnkouvu.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2qtglnrsj.html

TS:   toString(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2quwqkkfh.html

Java: @Override public String toString() { return name; }
来源：http://dali.sxryk.cn/Article/details/gt2zdyhtyrv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gt2fykagzhy.html

Ruby: def to_s; @name; end
来源：http://dali.cucudq.cn/Article/details/gt2nabjdimy.html

C#:   public override string ToString() => Name;
来源：http://dali.gogol.net.cn/Article/details/gt2vfflfxke.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhpaxndg.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gt2ogpvchhn.html

PHP:  $u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2esvlitwe.html

JS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gt2ndllqaku.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2zvgfeoge.html

Java: u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2ikbjitbd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ivvv.top/Article/details/gt2glneujub.html

Ruby: u.is_a?(User)
来源：http://dali.dianchejie.cn/Article/details/gt2tyrzojcu.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gt2vifblfpy.html

[G14] 数据类 / record
来源：http://dali.guowangkeji.top/Article/details/gt2erjwaass.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gt2tkhjvojv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangtech.top/Article/details/gt2muihnusg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gt2dtrwfobb.html

TS:   type User = { name: string; age: number };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2boeazryc.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gt2efhkiwvt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.vqdsnc.cn/Article/details/gt2xmbmwygh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxuanxn.top/Article/details/gt2kyozmlzs.html

C#:   record User(string Name, int Age);
来源：http://dali.jlsjyb.cn/Article/details/gt2rnxozdfq.html

[G15] 枚举
来源：http://dali.smart0.xyz/Article/details/gt2evlgneuy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigfzy.top/Article/details/gt2lbjqhfsc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ppjwa.cn/Article/details/gt2gzxxofwo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.havefunace.top/Article/details/gt2piefmknv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2uvcssexe.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gt2hifegrxi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rffoqhto.html

Ruby: Color = %i[red green].freeze
来源：http://dali.316326.xyz/Article/details/gt2kveuhvsl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gt2ujglhwsh.html

[G16] 对象转数组 / 字典
来源：http://dali.nwbrower.top/Article/details/gt2snjxbsqf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ppjwa.cn/Article/details/gt2efklxaxe.html

PHP:  get_object_vars($obj);
来源：http://dali.cucudq.cn/Article/details/gt2axuwoocu.html

JS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gt2pnxyqdyg.html

TS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2pydsbofp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhoulong.xyz/Article/details/gt2pcgqwpjw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cashguo.top/Article/details/gt2iwlcfaik.html

Ruby: obj.instance_variables
来源：http://dali.xinyue.icu/Article/details/gt2qtuckbdi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gt2ueaoppcp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2ginfmyms.html

H. 异常与错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jdpsiiyg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2bstpmywv.html

[H01] try / catch 基础
来源：http://dali.hysaishi.cn/Article/details/gt2elwlukju.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gt2dcdlxbgz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.c1oappe.top/Article/details/gt2ofoctoyw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gt2usxgitzs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jpexvmtx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sxryk.cn/Article/details/gt2dgrefecl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yongpay.top/Article/details/gt2ywctixbj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2exigghpt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daxiang520.top/Article/details/gt2fvlvrmet.html

[H02] finally / ensure 收尾
来源：http://dali.aibaodan.cn/Article/details/gt2xkurbzam.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yvedp.cn/Article/details/gt2hofabuak.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2hppticgt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2goxqheaf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2lvcdgpgf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2mvcbdgql.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sysykeji.top/Article/details/gt2evkbdrzg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hywenlv.cn/Article/details/gt2phuoovgw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2gyhfxyih.html

[H03] 主动抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gt2xbxcoahd.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jqqkxyzv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2ykddxopz.html

JS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2ehdnuwgx.html

TS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2ahqgrrnx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gt2jvdiboxq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zdqjudy.top/Article/details/gt2ijowduyk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guannengcc.top/Article/details/gt2ldkcdryx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2biguhxyg.html

[H04] 自定义异常类型
来源：http://dali.haohaochexian.top/Article/details/gt2kusbcbjo.html

Py:   class MyError(Exception): pass
来源：http://dali.yuxming.cn/Article/details/gt2cqmnfvjx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gt2brjwvupy.html

JS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gt2yoolaxum.html

TS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gt2akpbghku.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gt2oownglip.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cdjfqghq.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gt2pemuzczn.html

C#:   class MyException : Exception {}
来源：http://dali.zdqjudy.top/Article/details/gt2zpzlfjqe.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gt2dxznoahs.html

Py:   except ValueError as e:
来源：http://dali.cheryme.top/Article/details/gt2uognkjbu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.bjfxy.top/Article/details/gt2vhmrsacd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gt2yehnmvpb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gt2facvimnd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2zrgftyem.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gt2qeglrotb.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gt2uxsxzptg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2fkceiwkr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sysykeji.top/Article/details/gt2gtptqnvp.html

Py:   value = d.get("k") or default
来源：http://dali.nwbrower.top/Article/details/gt2fkykpjyr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gt2xtnxpvnp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kaomwatn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gt2rzsahwll.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gt2suqloopk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fzhhl.top/Article/details/gt2qrvfsbqt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.smart0.xyz/Article/details/gt2lqimqgcr.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuanzx.com/Article/details/gt2csmcacld.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gt2bmkcuqgb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gt2jnfayrto.html

PHP:  assert($x > 0);
来源：http://dali.nanxinkj.top/Article/details/gt2qmuuzyux.html

JS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2icltegll.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gt2jptfaztb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gt2mtpxctyi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tian-w.cn/Article/details/gt2fpnxqucb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnxiangtu.top/Article/details/gt2jupicldb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cdjtsjwc.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gt2crozhsmu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258.top/Article/details/gt2obvqtjoc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhixingplan.top/Article/details/gt2pbqijjwt.html

JS:   e.message;  e.stack
来源：http://dali.birdmap.top/Article/details/gt2rlqymadp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gt2gceiglpp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hysaishi.cn/Article/details/gt2uwfizxnj.html

Go:   err.Error()
来源：http://dali.andypj.xyz/Article/details/gt2usmfshjs.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gt2kwjcelwp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenlongwang.top/Article/details/gt2txaqsokk.html

[H09] 带错误码的异常
来源：http://dali.yuanzhike.top/Article/details/gt2fojtstba.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gt2xtxlukbk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgfzy.top/Article/details/gt2dlpugpzb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guowangkeji.top/Article/details/gt2jbvrupli.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tanke756.top/Article/details/gt2nvmgviyf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.guannengcc.top/Article/details/gt2ayycmxzr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.snrcjt.cn/Article/details/gt2huertkqk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgfzy.top/Article/details/gt2xgzuexbw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgufenzy.top/Article/details/gt2ymdukvdi.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gt2fxwclyfw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pengpengdd.cyou/Article/details/gt2wwzpdkkd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sysykeji.top/Article/details/gt2gwzznzwx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gt2vspfzjjl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gt2crbjhjyo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ehwqpu.com/Article/details/gt2tkmfcorg.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gt2grusgalh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gt2vgnzfqiq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2gqoshhmb.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2omolzeiw.html

I. 正则表达式
来源：http://dali.jinqigufen.top/Article/details/gt2sszmotyl.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2lrgifqwl.html

[I01] 判断是否匹配
来源：http://dali.dianchejie.cn/Article/details/gt2vhfcqqan.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gt2pssuilcb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2vjdxsyjh.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gt2cflvrwsq.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gt2mbiphrap.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gt2ertkcizo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gogol.net.cn/Article/details/gt2fprbjstc.html

Ruby: s.match?(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vgnbruay.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuxming.cn/Article/details/gt2awdgbyuv.html


<!-- 参考信息 -->