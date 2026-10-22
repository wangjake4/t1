代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gt2zxufitjb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2acdvdtun.html

Ruby: Dir.children("dir")
来源：http://dali.ydzc1.top/Article/details/gt2jruidmnu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwvkliew.html

[F09] 获取文件大小
来源：http://dali.cheryme.top/Article/details/gt2farzkbte.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2jfkaistd.html

PHP:  filesize("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2unhkpdtu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gt2yimyeamg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gt2wozyjhet.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gt2pxikqjrz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ppjwa.cn/Article/details/gt2azsmniis.html

Ruby: File.size("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2dgmxbcbc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gzhubu.top/Article/details/gt2kzcfwbvk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gt2nymbrjer.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2olxbbluz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2qmebigex.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2mkpnatsw.html

TS:   path.extname("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2ctrgnxhq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jianghu66.top/Article/details/gt2blpzyeje.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pngbqahv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2inyybjnj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2cyntjtgq.html

[F11] 复制与移动文件
来源：http://dali.ppjwa.cn/Article/details/gt2fgupglkk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2wgrofvno.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uprhrvdw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2pqkxqwit.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2foxixjbc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2kagpphaz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhiwuduotai.top/Article/details/gt2sufsuccq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2fnzygxdi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.bjfxy.top/Article/details/gt2lzmgwfzj.html

[F12] CSV 读写
来源：http://dali.cqqwz.cn/Article/details/gt2jdmmsgjg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guowangkeji.top/Article/details/gt2raudakgh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gt2cmzxunrc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gt2wihjeiyq.html

TS:   // 同上
来源：http://dali.shuidangran.top/Article/details/gt2yrjcnuzf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.svipenyu.cn/Article/details/gt2woevqcko.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gt2dvbxncgm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hammf.cn/Article/details/gt2wpioifra.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuanzx.com/Article/details/gt2xscjglnn.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2scgzlcls.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gt2mbohmhrx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2qrfjxhtz.html

[G01] 定义类
来源：http://dali.c1oappe.top/Article/details/gt2rtvanavj.html

Py:   class User: pass
来源：http://dali.chenjidiqi.icu/Article/details/gt2qyuhdztx.html

PHP:  class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kcssjxzi.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gt2gvrwwslp.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxinkj.top/Article/details/gt2baincgrm.html

Java: class User {}
来源：http://dali.xuanzx.com/Article/details/gt2sphxoaps.html

Go:   type User struct { Name string }
来源：http://dali.jiagoushi.top/Article/details/gt2oscjjnap.html

Ruby: class User; end
来源：http://dali.yangfankeji.com/Article/details/gt2nxgetahm.html

C#:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2chpplkus.html

[G02] 构造函数
来源：http://dali.tianlin.xyz/Article/details/gt2ejazwgeb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shzxlz.cn/Article/details/gt2agdqyedi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gt2yldtnvwk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gt2ihywznra.html

TS:   constructor(public name: string) {}
来源：http://dali.cashguo.top/Article/details/gt2ugghxzll.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gt2yjwfvldw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gt2lgrvsecq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2ashpippk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2rlcvmtnp.html

[G03] 实例属性
来源：http://dali.yuxming.cn/Article/details/gt2lffmnyfa.html

Py:   self.name = "x"
来源：http://dali.guowangkeji.top/Article/details/gt2xgyunfvj.html

PHP:  public string $name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2lbjuliep.html

JS:   this.name = "x";
来源：http://dali.sxryk.cn/Article/details/gt2cptlqmfi.html

TS:   name: string = "x";
来源：http://dali.ydzc1.top/Article/details/gt2vcukoexy.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gt2yqgxjikp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigufen.top/Article/details/gt2rjyridpn.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gt2xxyuvxak.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ybcxt.top/Article/details/gt2bubhesuc.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gt2pceaaijy.html

Py:   def greet(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gt2hzxuolpb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2uytyaeyq.html

JS:   greet() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2uspnmqjz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2ggsqxmhz.html

Java: String greet() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2ncvpszzi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gt2nokruwly.html

Ruby: def greet; @name; end
来源：http://dali.cheryme.top/Article/details/gt2pohcwusx.html

C#:   public string Greet() => Name;
来源：http://dali.daxiang520.top/Article/details/gt2zwsqkdya.html

[G05] 继承
来源：http://dali.yuxming.cn/Article/details/gt2dakgqqam.html

Py:   class Admin(User): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gt2louzzheb.html

PHP:  class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2myvdmmvi.html

JS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2wfxiijle.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gt2xocbbzxv.html

Java: class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2yeaiyimz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gt2cdcbmmzs.html

Ruby: class Admin < User; end
来源：http://dali.316326.xyz/Article/details/gt2ifinzjrg.html

C#:   class Admin : User {}
来源：http://dali.shuidangran.top/Article/details/gt2zvgfhzru.html

[G06] 重写方法
来源：http://dali.yj20258888.top/Article/details/gt2kcxorocs.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gt2vffgldlv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2hqaxciuh.html

JS:   greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gt2eimzcpct.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ctznonyg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2jtvnqbeu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gotoacloud.top/Article/details/gt2qbbsvore.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gt2muneepna.html

C#:   public override string Greet() => "admin";
来源：http://dali.jianghu66.top/Article/details/gt2kkxbxvgh.html

[G07] 调用父类方法
来源：http://dali.svipenyu.cn/Article/details/gt2adwvmrde.html

Py:   super().greet()
来源：http://dali.gogol.net.cn/Article/details/gt2ywqgnban.html

PHP:  parent::greet();
来源：http://dali.hammf.cn/Article/details/gt2qliohsss.html

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gt2lqyihvkf.html

TS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gt2xdfnagdm.html

Java: super.greet();
来源：http://dali.hywenlv.cn/Article/details/gt2cwdvcwtd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gt2fgucvamn.html

Ruby: super
来源：http://dali.shangyingyoupin.top/Article/details/gt2wktxlikc.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gt2ddszosqr.html

[G08] 静态方法与属性
来源：http://dali.haohaochexian.top/Article/details/gt2cwsnmvtz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gt2jcevayha.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gt2ouqqtbtg.html

JS:   static f() {}
来源：http://dali.hywenlv.cn/Article/details/gt2ufwgxsrh.html

TS:   static f(): void {}
来源：http://dali.sweek.top/Article/details/gt2spokkkau.html

Java: static void f() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2zmurmejx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wenehebz.html

Ruby: def self.f; end
来源：http://dali.zhoulong.xyz/Article/details/gt2bmburuuu.html

C#:   public static void F() {}
来源：http://dali.chenzaomai.com/Article/details/gt2dmoblnfi.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gt2zvpsejli.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sxryk.cn/Article/details/gt2taznilvu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tianlin.xyz/Article/details/gt2oqdtwiyd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gt2vrstrivj.html

TS:   interface Shape { area(): number; }
来源：http://dali.shuidangran.top/Article/details/gt2xjqnrmud.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gt2hfziagqv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wjaqtdpg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxuanxn.top/Article/details/gt2xaltugfg.html

C#:   interface IShape { double Area(); }
来源：http://dali.birdmap.top/Article/details/gt2qjrtjpza.html

[G10] 访问控制
来源：http://dali.svipenyu.cn/Article/details/gt2ojfufijf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gt2yinorjbk.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dfprwysy.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gt2lyeatkye.html

TS:   public / protected / private
来源：http://dali.aizwys.cn/Article/details/gt2siurhege.html

Java: public / protected / private / 默认包级
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhdyvxsp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnqzz.top/Article/details/gt2yylrzard.html

Ruby: public / protected / private
来源：http://dali.guannengcc.top/Article/details/gt2uygojbpj.html

C#:   public / protected / private / internal
来源：http://dali.chenzaomai.com/Article/details/gt2rbxihwlf.html

[G11] getter / setter
来源：http://dali.aibaodan.cn/Article/details/gt2ftbbyjkx.html

Py:   @property 与 @x.setter
来源：http://dali.nanxuanxn.top/Article/details/gt2jvkhdmid.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2yrwbkvlt.html

JS:   get name() { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2dojejhdp.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2xqomwizm.html

Java: public String getName() { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2pnkvspoj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gt2bfizzlpc.html

Ruby: attr_accessor :name
来源：http://dali.smart0.xyz/Article/details/gt2nkcrvbpw.html

C#:   public string Name { get; set; }
来源：http://dali.shuidangran.top/Article/details/gt2ftmuwkru.html

[G12] 对象转字符串
来源：http://dali.hfpthk.cn/Article/details/gt2enaigqrc.html

Py:   def __str__(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gt2xisxuuqx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2joqenkqm.html

JS:   toString() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2tqpuzxyd.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2axnurqux.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2luzwibcp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2leuumuvk.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gt2jlaojzic.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odkrtnoh.html

[G13] 判断对象类型
来源：http://dali.kuanghao11.cn/Article/details/gt2xuoawmxn.html

Py:   isinstance(u, User)
来源：http://dali.tian-w.cn/Article/details/gt2ohkkpflx.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2kqpprlag.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2giyzziwe.html

TS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2aycskqdt.html

Java: u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2qjacqlab.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dgsuskxe.html

Ruby: u.is_a?(User)
来源：http://dali.cdnleiting.top/Article/details/gt2vwlqoskv.html

C#:   u is User
来源：http://dali.shzxlz.cn/Article/details/gt2volmsjtv.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxxrgvob.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xinyue.icu/Article/details/gt2lzoxknaf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gaohongyu789.top/Article/details/gt2dvplffrs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gt2xteiulds.html

TS:   type User = { name: string; age: number };
来源：http://dali.bjfxy.top/Article/details/gt2ekumbvjy.html

Java: record User(String name, int age) {}
来源：http://dali.yongpay.top/Article/details/gt2xvauceys.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eyxllvxp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.quarkkingdee.top/Article/details/gt2lzbwscmj.html

C#:   record User(string Name, int Age);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qyjoduzc.html

[G15] 枚举
来源：http://dali.gotoacloud.top/Article/details/gt2vxkchtxs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnqzz.top/Article/details/gt2opgpvsyg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jqyszdwy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gt2lesaekay.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gt2oblzbxot.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgfzy.top/Article/details/gt2vhuryaiw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gt2qjirhikw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nwbrower.top/Article/details/gt2zutzopal.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gt2mvmdmvci.html

[G16] 对象转数组 / 字典
来源：http://dali.hywenlv.cn/Article/details/gt2dakzrors.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj202588.top/Article/details/gt2wgtolicv.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gt2fghifkka.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2pkanszub.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2vbuyumgi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fengsongda.top/Article/details/gt2yplojbwn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtxpebbp.html

Ruby: obj.instance_variables
来源：http://dali.nwbrower.top/Article/details/gt2tgburvtc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gt2ncsgkolv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2okifdwyl.html

H. 异常与错误处理
来源：http://dali.jqgufenzy.top/Article/details/gt2qtoxfjxp.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2acpxntoh.html

[H01] try / catch 基础
来源：http://dali.hnqzz.top/Article/details/gt2uzwwurrw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cdnleiting.top/Article/details/gt2djcxopbf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2tocmtdow.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gt2bpyglmnm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cyggstja.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangdashe.top/Article/details/gt2hsdwzvwf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gogol.net.cn/Article/details/gt2nvaogjzl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxinkj.top/Article/details/gt2pcdtlcgg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.smart0.xyz/Article/details/gt2mtgrxlkk.html

[H02] finally / ensure 收尾
来源：http://dali.daria6918.cn/Article/details/gt2jbeowwbm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gt2iarnfsfu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2octtjwmi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2vuwcqphr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2kjhgmtlz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2jklqrwsa.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shangyingyoupin.top/Article/details/gt2hplkvysl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigfzy.top/Article/details/gt2frfokoga.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2hedxzfmy.html

[H03] 主动抛出异常
来源：http://dali.nanxinkj.top/Article/details/gt2wmrktlaj.html

Py:   raise ValueError("错误信息")
来源：http://dali.haohaochexian.top/Article/details/gt2zejymjrj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2inbrhdwk.html

JS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2lvljypxg.html

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2drixjetq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xzwvgubv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ffwsbsma.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhiwuduotai.top/Article/details/gt2egvxhunl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jlsedauz.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gt2ssmyrgyw.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gt2xngkkfde.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gt2iegcvywb.html

JS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gt2lgtqtxcn.html

TS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gt2psjfsppj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gt2tlpovllv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tanke756.top/Article/details/gt2qqlwjyiu.html

Ruby: class MyError < StandardError; end
来源：http://dali.ivvv.top/Article/details/gt2xciroeve.html

C#:   class MyException : Exception {}
来源：http://dali.zhixingplan.top/Article/details/gt2ovqjmlkd.html

[H05] 捕获特定类型
来源：http://dali.shuidangran.top/Article/details/gt2tixunlrj.html

Py:   except ValueError as e:
来源：http://dali.hnqzz.top/Article/details/gt2adbuwjiu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqstfxnz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gt2igveljug.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2unrultwm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sfqdshda.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hammf.cn/Article/details/gt2fzymwhkd.html

Ruby: rescue ArgumentError => e
来源：http://dali.zycfv.cn/Article/details/gt2bofncsvs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hfpthk.cn/Article/details/gt2bwsxzfbd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258888.top/Article/details/gt2dxwksija.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gt2wyawdtjq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gt2yfdxzdms.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gt2xnehwbum.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gt2ndqhvmru.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ivvv.top/Article/details/gt2fvosiypg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhongyouzk.top/Article/details/gt2wqjngvaw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gt2cxmjiypo.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhdbcggj.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2lpyfyqxx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fzhhl.top/Article/details/gt2auwgfpcq.html

PHP:  assert($x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2vrykibfl.html

JS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sbbtclnl.html

TS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2wyblxgdh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuxming.cn/Article/details/gt2kadlgidq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxinkj.top/Article/details/gt2uyqebhpq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ppjwa.cn/Article/details/gt2yoyekpwj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2jasexccl.html

[H08] 获取错误信息与堆栈
来源：http://dali.nwbrower.top/Article/details/gt2fxurxxwu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cashguo.top/Article/details/gt2opjhoekl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cheryme.top/Article/details/gt2rlqiwpub.html

JS:   e.message;  e.stack
来源：http://dali.bjfxy.top/Article/details/gt2bhrmnwow.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pycfn.com/Article/details/gt2zyrlnwjl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sweek.top/Article/details/gt2qwipcsmw.html

Go:   err.Error()
来源：http://dali.tian-w.cn/Article/details/gt2kzhpftqo.html

Ruby: e.message;  e.backtrace
来源：http://dali.guannengcc.top/Article/details/gt2pdkwjpte.html

C#:   e.Message;  e.StackTrace
来源：http://dali.iojbl.cn/Article/details/gt2rrpdkkcv.html

[H09] 带错误码的异常
来源：http://dali.0kj1m.cn/Article/details/gt2glvmsirh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.316326.xyz/Article/details/gt2qtlqkhws.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guannengcc.top/Article/details/gt2eytwlldy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhengqikj.top/Article/details/gt2hnmlahyw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aibaodan.cn/Article/details/gt2bnfalqee.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cqqwz.cn/Article/details/gt2rdfuokot.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2adnzaila.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.vqdsnc.cn/Article/details/gt2jdzflidl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jianghu66.top/Article/details/gt2bkcvtlhw.html

[H10] 资源自动释放
来源：http://dali.ehwqpu.com/Article/details/gt2bqypkvdr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fengsongda.top/Article/details/gt2fzrttjht.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sxryk.cn/Article/details/gt2zznxxnlv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gt2qdduxpuy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gt2kjvbiohq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.svipenyu.cn/Article/details/gt2wjxygtqh.html

Go:   defer f.Close()
来源：http://dali.yj20258.top/Article/details/gt2rmqijttl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuxming.cn/Article/details/gt2eeumnomu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2zixutvmv.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2zgjxxofn.html

I. 正则表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2rbxhfszf.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2bedntgec.html

[I01] 判断是否匹配
来源：http://dali.havefunace.top/Article/details/gt2dgyohetm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gt2fmxipvqe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2ymxkxaba.html

JS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gt2bxjzrkhj.html

TS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gt2akmyyyre.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daria6918.cn/Article/details/gt2iowujtqj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cdnleiting.top/Article/details/gt2lxkypedh.html

Ruby: s.match?(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gt2rxymxukd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mozvpukf.html

[I02] 提取所有匹配
来源：http://dali.cheryme.top/Article/details/gt2ovqywtdk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gt2xvwgvsoc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.9152youxi.cn/Article/details/gt2rkqcpxuw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cdnleiting.top/Article/details/gt2oogfwlxo.html

TS:   s.match(/\d+/g)
来源：http://dali.hnxiangtu.top/Article/details/gt2yxlhpdyl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2lrjrpboz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2meuuueps.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gt2sjxlqwgb.html


<!-- 参考信息 -->