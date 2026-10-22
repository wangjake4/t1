代发 wailian999

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gt2jdjtmezi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sweek.top/Article/details/gt2thrwidwu.html

PHP:  filesize("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2texyooyu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gt2aofsnwmo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2usrhomtu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gt2dtksebwp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ybcxt.top/Article/details/gt2chwzvizk.html

Ruby: File.size("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2puvyzftg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258.top/Article/details/gt2qbkhugmj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.svipenyu.cn/Article/details/gt2ulicsvdp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2pybcdjdt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2oipufglf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2sxgqouqz.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2oihmveix.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dianchejie.cn/Article/details/gt2ekejlsvc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2ieucahdo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2wbssmbhp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2vynhylaf.html

[F11] 复制与移动文件
来源：http://dali.kuanghao11.cn/Article/details/gt2gsrmgfym.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2luvtptol.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2vmttpapo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rkkdeaoz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uwffmdue.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.c1oappe.top/Article/details/gt2lhuunvxy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.svipenyu.cn/Article/details/gt2awmtzraf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gt2wkosqatm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dianchejie.cn/Article/details/gt2fzcbjras.html

[F12] CSV 读写
来源：http://dali.shuidangran.top/Article/details/gt2tosdanvd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hysaishi.cn/Article/details/gt2kqytvgja.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenjidiqi.icu/Article/details/gt2azbodjhe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yanxiufei.cn/Article/details/gt2zwluofcu.html

TS:   // 同上
来源：http://dali.zhixingplan.top/Article/details/gt2dhikmxgd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jiagoushi.top/Article/details/gt2lnvbmonl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cheryme.top/Article/details/gt2bzoviyig.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cashguo.top/Article/details/gt2dwfetxru.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guowangkeji.top/Article/details/gt2hbcqfmww.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2fqvkdyqg.html

G. 面向对象
来源：http://dali.chenjidiqi.icu/Article/details/gt2jjrqqeip.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ssecvgki.html

[G01] 定义类
来源：http://dali.yuanzhike.top/Article/details/gt2vijmofua.html

Py:   class User: pass
来源：http://dali.yuxming.cn/Article/details/gt2aykjvwhe.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfjsofyf.html

JS:   class User {}
来源：http://dali.shuidangran.top/Article/details/gt2tkbbpwkb.html

TS:   class User { name: string = ""; }
来源：http://dali.hnqzz.top/Article/details/gt2sixszhce.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xyowbbhv.html

Go:   type User struct { Name string }
来源：http://dali.fengsongda.top/Article/details/gt2aaypagzf.html

Ruby: class User; end
来源：http://dali.aibaodan.cn/Article/details/gt2dhgmhfxi.html

C#:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ossydbjg.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gt2cfqawzvb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hongshengwenyu.top/Article/details/gt2xcutkqiy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2eqakugdq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gt2kocusfjr.html

TS:   constructor(public name: string) {}
来源：http://dali.fengsongda.top/Article/details/gt2pphyccjo.html

Java: User(String name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2lofricpt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xylfe.cn/Article/details/gt2ilpjptgx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gt2mcurcjdb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gt2jstwmkix.html

[G03] 实例属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pgtcexvz.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evbevzgx.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2hjdoboul.html

JS:   this.name = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2jjtkcigr.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gt2hkrocnwz.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gt2hiqzanqp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hongshengwenyu.top/Article/details/gt2deoikxbe.html

Ruby: @name = "x"
来源：http://dali.nwbrower.top/Article/details/gt2khurabht.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.meibo888.top/Article/details/gt2clvwqkee.html

[G04] 定义方法
来源：http://dali.cdnleiting.top/Article/details/gt2ijcchori.html

Py:   def greet(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gt2xwmzeqsy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gt2nzwrfnvw.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gt2zftvwxgg.html

TS:   greet(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2xmtzcuyw.html

Java: String greet() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2pgxuehdm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2tpqmkdys.html

Ruby: def greet; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxntqwop.html

C#:   public string Greet() => Name;
来源：http://dali.haohaochexian.top/Article/details/gt2hzjbopir.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gt2ohdwxzer.html

Py:   class Admin(User): pass
来源：http://dali.cdnleiting.top/Article/details/gt2ixruwdjq.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2nptekvcr.html

JS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2vygwtaxp.html

TS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gt2uvfekbnf.html

Java: class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2zenpgvov.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgufenzy.top/Article/details/gt2zflsbato.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gt2zezlwuxk.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2djdtdrmd.html

[G06] 重写方法
来源：http://dali.ppjwa.cn/Article/details/gt2nopwfhmx.html

Py:   def greet(self): return "admin"
来源：http://dali.zdqjudy.top/Article/details/gt2zkbadmyt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2nzefmpag.html

JS:   greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2ppntytks.html

TS:   greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gt2ttljqjuk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gt2sbmdcrfu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.feifeiyinyue.top/Article/details/gt2cuiudnfv.html

Ruby: def greet; "admin"; end
来源：http://dali.cdnleiting.top/Article/details/gt2mubcgsyg.html

C#:   public override string Greet() => "admin";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aotnrwwi.html

[G07] 调用父类方法
来源：http://dali.xuanzx.com/Article/details/gt2rrecvlwb.html

Py:   super().greet()
来源：http://dali.birdmap.top/Article/details/gt2exoghnnc.html

PHP:  parent::greet();
来源：http://dali.sweek.top/Article/details/gt2afzotazz.html

JS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gt2afnbnmko.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2rocivllb.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gt2dahiynwe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pycfn.com/Article/details/gt2roxjonsa.html

Ruby: super
来源：http://dali.smart0.xyz/Article/details/gt2ynxbuguq.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gt2ikwcspsz.html

[G08] 静态方法与属性
来源：http://dali.mhx1999.top/Article/details/gt2qetjejoj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gt2wxdwexic.html

PHP:  public static function f() {}
来源：http://dali.jyoumei.cn/Article/details/gt2frgwxjhv.html

JS:   static f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2mfdkzndh.html

TS:   static f(): void {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2hnfnmayn.html

Java: static void f() {}
来源：http://dali.daria6918.cn/Article/details/gt2jwmfijno.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhongyouzk.top/Article/details/gt2hcuzsbnn.html

Ruby: def self.f; end
来源：http://dali.316326.xyz/Article/details/gt2ybtowzym.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gt2frwdbvxl.html

[G09] 接口 / 抽象类
来源：http://dali.daria6918.cn/Article/details/gt2utqqexbi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sufxvd.cn/Article/details/gt2kbsdwdmm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jianghu66.top/Article/details/gt2oymlvqdr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktcmbmyd.html

TS:   interface Shape { area(): number; }
来源：http://dali.birdmap.top/Article/details/gt2fcyhcylb.html

Java: interface Shape { double area(); }
来源：http://dali.hfpthk.cn/Article/details/gt2ubflodpq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tian-w.cn/Article/details/gt2kdaqtpve.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gogol.net.cn/Article/details/gt2bdkflpca.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2iplzkpfr.html

[G10] 访问控制
来源：http://dali.gogol.net.cn/Article/details/gt2wlxgmoja.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ybcxt.top/Article/details/gt2dwjdehoz.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gt2ikpbufrx.html

JS:   #private 字段；其余公开
来源：http://dali.tanke756.top/Article/details/gt2uewmjrzc.html

TS:   public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gt2vmjhutna.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gt2kgirzsdj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangdashe.top/Article/details/gt2tyoeyxfo.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2sdeqabow.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gt2pnxcette.html

[G11] getter / setter
来源：http://dali.yueranfly.top/Article/details/gt2rxpuibwi.html

Py:   @property 与 @x.setter
来源：http://dali.hysaishi.cn/Article/details/gt2nkjjjmxo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gt2ynpaxptw.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fzqsoeon.html

TS:   get name(): string { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gt2scosniwv.html

Java: public String getName() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2jeahvkwj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gt2cakijdup.html

Ruby: attr_accessor :name
来源：http://dali.yj20258.top/Article/details/gt2avlrvqzn.html

C#:   public string Name { get; set; }
来源：http://dali.smart0.xyz/Article/details/gt2lvcnorzd.html

[G12] 对象转字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2debratjw.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gt2sjqwwwzz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gt2mtndaktv.html

JS:   toString() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2edhmjqjh.html

TS:   toString(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2vtgxcexp.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2odbbkjsm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gt2cqpxhkhb.html

Ruby: def to_s; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2pyxnbvon.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wdgiempr.html

[G13] 判断对象类型
来源：http://dali.yongpay.top/Article/details/gt2dracjxmc.html

Py:   isinstance(u, User)
来源：http://dali.pycfn.com/Article/details/gt2zrhjtech.html

PHP:  $u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gt2vhxnpgmw.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2kohlebgt.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2tsbidvsd.html

Java: u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2tinuvpei.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cdnleiting.top/Article/details/gt2maqbkxsl.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gt2ffaijyom.html

C#:   u is User
来源：http://dali.xylfe.cn/Article/details/gt2mgashsnh.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gt2dzoaqpns.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gt2vlmgvsom.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cashguo.top/Article/details/gt2tyjjluex.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pengpengdd.cyou/Article/details/gt2emkbnrrl.html

TS:   type User = { name: string; age: number };
来源：http://dali.jlsjyb.cn/Article/details/gt2vsnevgaj.html

Java: record User(String name, int age) {}
来源：http://dali.jianghu66.top/Article/details/gt2dpyrirgu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gt2xonrkyzv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2crigulqn.html

C#:   record User(string Name, int Age);
来源：http://dali.316326.xyz/Article/details/gt2eqwtkurl.html

[G15] 枚举
来源：http://dali.daxiang520.top/Article/details/gt2izbeiyfd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2stpzdxwu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenzaomai.com/Article/details/gt2wqbryrxd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenzaomai.com/Article/details/gt2gyzzdtli.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gt2clnjntto.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgufenzy.top/Article/details/gt2wrubzyqj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hysaishi.cn/Article/details/gt2giwjjjfh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nwbrower.top/Article/details/gt2jxajucam.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2filsgvcs.html

[G16] 对象转数组 / 字典
来源：http://dali.cdnleiting.top/Article/details/gt2yhpupgfd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgufenzy.top/Article/details/gt2vwgozkdt.html

PHP:  get_object_vars($obj);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sorxrkbg.html

JS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fttmijoc.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gt2sbxqujdj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hongshengwenyu.top/Article/details/gt2krypvhmh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gt2gzuuliys.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gt2sbxuxzei.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gt2wuzuwxnu.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2apxwydcb.html

H. 异常与错误处理
来源：http://dali.cucudq.cn/Article/details/gt2upwsppbs.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jlsvlapu.html

[H01] try / catch 基础
来源：http://dali.meibo888.top/Article/details/gt2wgmllcad.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gt2pupjvawm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cmvfjkza.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gt2njsyrrqz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gt2elxgurjt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gt2twisolil.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yonumen.top/Article/details/gt2pfcpxbap.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jyoumei.cn/Article/details/gt2rkhljeuk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gt2cjxpkuxt.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gt2rbwlxccu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxuanxn.top/Article/details/gt2asdluhlh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2sasrnmia.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xfycyzrj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2ijxssetv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2zpfuzrek.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tianlin.xyz/Article/details/gt2ikkguuwk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnqzz.top/Article/details/gt2czuadtmv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2hjksxyth.html

[H03] 主动抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2wooiazje.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgfzy.top/Article/details/gt2mzdwxqtr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2ngmfwjkh.html

JS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2miyzygfd.html

TS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2lqpkzqal.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2ilnvcotc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnqzz.top/Article/details/gt2jvjrjzkb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fzhhl.top/Article/details/gt2jvtjbscg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2ndewqzvo.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gt2esbvnfie.html

Py:   class MyError(Exception): pass
来源：http://dali.redwolf501.top/Article/details/gt2hpexlsdf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gt2skenbkrt.html

JS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcfcarid.html

TS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2vifibdgi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gt2inuklzah.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gt2ahwczfzo.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gt2zpabjucd.html

C#:   class MyException : Exception {}
来源：http://dali.sweek.top/Article/details/gt2dkcyljkz.html

[H05] 捕获特定类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rneaxstk.html

Py:   except ValueError as e:
来源：http://dali.kuanghao11.cn/Article/details/gt2bvaesxkj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shzxlz.cn/Article/details/gt2zerowrfv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gt2mnaomiwf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gt2vbgmmtqp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tanke756.top/Article/details/gt2annhrrdc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.0kj1m.cn/Article/details/gt2elwqtyme.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gt2znhbrovu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mnahglpt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yanxiufei.cn/Article/details/gt2juftrqfh.html

Py:   value = d.get("k") or default
来源：http://dali.yj20258888.top/Article/details/gt2nvufbtwg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gt2yhxtestl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gt2wesmbwlk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gt2uerjzska.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.quarkkingdee.top/Article/details/gt2ctgxkjsq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.kuanghao11.cn/Article/details/gt2ygaguwwv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hwbkdvjw.html

C#:   obj?.A?.B ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jkldngqm.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gt2mpkkpvtm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yvedp.cn/Article/details/gt2jhxqrtjk.html

PHP:  assert($x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2nhfntjuy.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2ytwedlql.html

TS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ikdqmwbe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.meibo888.top/Article/details/gt2uheaggxm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xylfe.cn/Article/details/gt2uffxdnhc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gt2vcyrgtli.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nfyswcfw.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnqzz.top/Article/details/gt2snfwchig.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hammf.cn/Article/details/gt2bjsrbbkx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhiwuduotai.top/Article/details/gt2fufmpjhi.html

JS:   e.message;  e.stack
来源：http://dali.yj202588.top/Article/details/gt2lfftnhez.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eokhkvrt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258.top/Article/details/gt2euomvhys.html

Go:   err.Error()
来源：http://dali.pycfn.com/Article/details/gt2kzozajdq.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gt2plfwkmwn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sxryk.cn/Article/details/gt2kcvzorle.html

[H09] 带错误码的异常
来源：http://dali.sxryk.cn/Article/details/gt2nzolyjnf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cucudq.cn/Article/details/gt2zqaporra.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nwbrower.top/Article/details/gt2muvfokmg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258888.top/Article/details/gt2kylscaen.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dashuyun.cn/Article/details/gt2jdghphqh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gt2fuwcxlar.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guowangkeji.top/Article/details/gt2buzvzbyf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuxming.cn/Article/details/gt2qfcwwfpy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gt2rsiklika.html

[H10] 资源自动释放
来源：http://dali.xuanzx.com/Article/details/gt2spcuikpw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gt2ozufwqnk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jyoumei.cn/Article/details/gt2erttdtfy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gt2avnkgiir.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gt2xrexcyjx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ybcxt.top/Article/details/gt2qtalrdlt.html

Go:   defer f.Close()
来源：http://dali.jqgufenzy.top/Article/details/gt2cbetvkbh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvfwognk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2lzttncwb.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2auvgaqpb.html

I. 正则表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wynwkpar.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2kqtyvmep.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xebnukdx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gt2qmevieeb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vqdqwcdw.html

JS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gt2lhnxknws.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gt2ejocaqnr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dashuyun.cn/Article/details/gt2tvchucsr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2rfyqfqwl.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sxbmaabl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.daxiang520.top/Article/details/gt2iepdmbmh.html

[I02] 提取所有匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2unjglurr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gt2mbjzvfgy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gt2dhcmlobq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.andypj.xyz/Article/details/gt2rsrabdor.html

TS:   s.match(/\d+/g)
来源：http://dali.0kj1m.cn/Article/details/gt2molbhubq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258888.top/Article/details/gt2vjfwprtn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2okpaqoay.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gt2hhlmxjjb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2dcaugvpc.html

[I03] 提取捕获分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sixbeuzw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.svipenyu.cn/Article/details/gt2cmadwjmx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj202588.top/Article/details/gt2xtjkcxvj.html


<!-- 参考信息 -->