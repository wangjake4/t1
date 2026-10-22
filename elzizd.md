代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dmfbfakj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daxiang520.top/Article/details/gt2kunjekgx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fengsongda.top/Article/details/gt2ccluviwz.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gt2rltenqff.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhengqikj.top/Article/details/gt2xcehtnck.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuanzhike.top/Article/details/gt2wplrsahn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.havefunace.top/Article/details/gt2rgopdbgn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.mhx1999.top/Article/details/gt2qqylkoyu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2srgghpjm.html

G. 面向对象
来源：http://dali.zhongyouzk.top/Article/details/gt2wjbusdxv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2aogsohlc.html

[G01] 定义类
来源：http://dali.nanxinkj.top/Article/details/gt2vnpnrtwv.html

Py:   class User: pass
来源：http://dali.gotoacloud.top/Article/details/gt2scfqrnau.html

PHP:  class User {}
来源：http://dali.havefunace.top/Article/details/gt2hdxafglg.html

JS:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2lugdmodb.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gt2yeymymjo.html

Java: class User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2mboapadb.html

Go:   type User struct { Name string }
来源：http://dali.yj202588.top/Article/details/gt2mbalbxbo.html

Ruby: class User; end
来源：http://dali.zhoulong.xyz/Article/details/gt2chlrlsqn.html

C#:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2phvkyscj.html

[G02] 构造函数
来源：http://dali.yuxming.cn/Article/details/gt2viwmkodf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hongshengwenyu.top/Article/details/gt2lkadttur.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2nkldmkpg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gt2dbuftpzi.html

TS:   constructor(public name: string) {}
来源：http://dali.yangfankeji.com/Article/details/gt2yxhvooro.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gt2erlkddlw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nwbrower.top/Article/details/gt2mlmofeen.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cdnleiting.top/Article/details/gt2brozslrd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2zqpplopf.html

[G03] 实例属性
来源：http://dali.wangdashe.top/Article/details/gt2cszyohaj.html

Py:   self.name = "x"
来源：http://dali.chenlongwang.top/Article/details/gt2anyyrkkj.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2tnvilyoo.html

JS:   this.name = "x";
来源：http://dali.yonumen.top/Article/details/gt2nuvksalv.html

TS:   name: string = "x";
来源：http://dali.yongpay.top/Article/details/gt2niefwdsz.html

Java: private String name;
来源：http://dali.c1oappe.top/Article/details/gt2kjmvdunn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gaohongyu789.top/Article/details/gt2qvitykwu.html

Ruby: @name = "x"
来源：http://dali.jqgfzy.top/Article/details/gt2zxfcwlev.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sysykeji.top/Article/details/gt2bxsfgryr.html

[G04] 定义方法
来源：http://dali.yueranfly.top/Article/details/gt2hoxscsyj.html

Py:   def greet(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gt2ovgybusm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gt2szseydjq.html

JS:   greet() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2kgzsdkgl.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qqljzlly.html

Java: String greet() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2mevmwmyx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2jlejnaez.html

Ruby: def greet; @name; end
来源：http://dali.hammf.cn/Article/details/gt2jiyxgnod.html

C#:   public string Greet() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gt2mdjowxrx.html

[G05] 继承
来源：http://dali.iojbl.cn/Article/details/gt2fmylscyc.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gt2oljumldl.html

PHP:  class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2dwgcbsnn.html

JS:   class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2yxqcpgis.html

TS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2ryhkgpgq.html

Java: class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2jiainpuh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gt2tpkyvmqz.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gt2fjeoafrr.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gt2rdwjtkjf.html

[G06] 重写方法
来源：http://dali.vqdsnc.cn/Article/details/gt2wnvtjrsq.html

Py:   def greet(self): return "admin"
来源：http://dali.tanke756.top/Article/details/gt2zlionwst.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2ndrqigow.html

JS:   greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2kuwldktb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2qisrcpvg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dydrzabz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhixingplan.top/Article/details/gt2samhslhf.html

Ruby: def greet; "admin"; end
来源：http://dali.316326.xyz/Article/details/gt2getisimh.html

C#:   public override string Greet() => "admin";
来源：http://dali.feifeiyinyue.top/Article/details/gt2ydjkppqu.html

[G07] 调用父类方法
来源：http://dali.yuanzhike.top/Article/details/gt2zeemaeez.html

Py:   super().greet()
来源：http://dali.zhongyouzk.top/Article/details/gt2izyjppca.html

PHP:  parent::greet();
来源：http://dali.tian-w.cn/Article/details/gt2qdmsrzxc.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2iyltqjpg.html

TS:   super.greet();
来源：http://dali.sweek.top/Article/details/gt2qmljrogt.html

Java: super.greet();
来源：http://dali.mhx1999.top/Article/details/gt2bjznwrxw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gt2dgyxbbsd.html

Ruby: super
来源：http://dali.shzxlz.cn/Article/details/gt2sqrfomjq.html

C#:   base.Greet();
来源：http://dali.nanxinkj.top/Article/details/gt2xdwntmks.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gt2hcimdsky.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gogol.net.cn/Article/details/gt2atlpruvd.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gt2swbrwffj.html

JS:   static f() {}
来源：http://dali.smart0.xyz/Article/details/gt2mygydnsw.html

TS:   static f(): void {}
来源：http://dali.xinyue.icu/Article/details/gt2milleahk.html

Java: static void f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zsewubnz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ydzc1.top/Article/details/gt2owdtnzex.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gt2fwewifoy.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gt2xyyyxiri.html

[G09] 接口 / 抽象类
来源：http://dali.yanxiufei.cn/Article/details/gt2whkxrebh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.kuanghao11.cn/Article/details/gt2nmfwbszr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zycfv.cn/Article/details/gt2fhigwgwf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yanxiufei.cn/Article/details/gt2fnwysjpe.html

TS:   interface Shape { area(): number; }
来源：http://dali.meibo888.top/Article/details/gt2jdezsweh.html

Java: interface Shape { double area(); }
来源：http://dali.daxiang520.top/Article/details/gt2qaokioiu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gt2yaqhuvnt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gt2ixbmpvap.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gt2oitfmjtn.html

[G10] 访问控制
来源：http://dali.nanxinkj.top/Article/details/gt2abttzeas.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cfnrhghd.html

PHP:  public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gt2anfoqbjq.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gt2xvjpskmb.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2fopiyndz.html

Java: public / protected / private / 默认包级
来源：http://dali.cdnleiting.top/Article/details/gt2dsfqhtcg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sysykeji.top/Article/details/gt2fzsmwkjy.html

Ruby: public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gt2mshmxkjk.html

C#:   public / protected / private / internal
来源：http://dali.birdmap.top/Article/details/gt2leizlbvd.html

[G11] getter / setter
来源：http://dali.cdnleiting.top/Article/details/gt2uarxsuek.html

Py:   @property 与 @x.setter
来源：http://dali.sysykeji.top/Article/details/gt2njrbwnox.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2pqoznjme.html

JS:   get name() { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gt2mnlbhyin.html

TS:   get name(): string { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gt2lrqhychy.html

Java: public String getName() { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2wxhfitki.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gt2stneqtfh.html

Ruby: attr_accessor :name
来源：http://dali.hammf.cn/Article/details/gt2djztauyj.html

C#:   public string Name { get; set; }
来源：http://dali.fengsongda.top/Article/details/gt2jgjelrxt.html

[G12] 对象转字符串
来源：http://dali.0kj1m.cn/Article/details/gt2ycsbtrfm.html

Py:   def __str__(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gt2nhjmjaer.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2rtxkamfy.html

JS:   toString() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2crwflzzh.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ivahrzwp.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2jtoxeftn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gt2fhgtbmyu.html

Ruby: def to_s; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2uvzkysaa.html

C#:   public override string ToString() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2tjbtexrm.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gt2loubevun.html

Py:   isinstance(u, User)
来源：http://dali.cheryme.top/Article/details/gt2zrbbytrb.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2ojsybkkb.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2dfzwmsfg.html

TS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2cxypvmxu.html

Java: u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2hfhykoab.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gt2cbjgeprk.html

Ruby: u.is_a?(User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpgovaau.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qzbpjyqq.html

[G14] 数据类 / record
来源：http://dali.hongshengwenyu.top/Article/details/gt2mudgakcf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cdnleiting.top/Article/details/gt2eqvfmbcf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shangyingyoupin.top/Article/details/gt2dxmvygep.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gt2dlubyxyx.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2exbyuzns.html

Java: record User(String name, int age) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2jmvvwwfh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gogol.net.cn/Article/details/gt2gqfytigw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gt2nwguayfw.html

C#:   record User(string Name, int Age);
来源：http://dali.yuxming.cn/Article/details/gt2wdhyrnxc.html

[G15] 枚举
来源：http://dali.sweek.top/Article/details/gt2lnhtwtrx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2hjjmhxfb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxinkj.top/Article/details/gt2rekfjbzf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zycfv.cn/Article/details/gt2vofitnyw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gt2xbnudfml.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gt2ucwqqyqc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ppjwa.cn/Article/details/gt2mouvbejj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hfpthk.cn/Article/details/gt2unhczesa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2eauvqkme.html

[G16] 对象转数组 / 字典
来源：http://dali.birdmap.top/Article/details/gt2vyllmxtb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gaohongyu789.top/Article/details/gt2eglovqol.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gt2finwbgas.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2pfeoiajt.html

TS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qgsexmji.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ppjwa.cn/Article/details/gt2izpyzigi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shuidangran.top/Article/details/gt2mfttjgzk.html

Ruby: obj.instance_variables
来源：http://dali.yj20258888.top/Article/details/gt2gfiepkwx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gt2nshwdnfo.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2lnirfctf.html

H. 异常与错误处理
来源：http://dali.9152youxi.cn/Article/details/gt2hgksglbs.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2wcmthlwl.html

[H01] try / catch 基础
来源：http://dali.0kj1m.cn/Article/details/gt2ryfmyfuw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gt2vbfgtuvf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nwbrower.top/Article/details/gt2sspbmcbc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2muyemhwc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gt2zuxckqyd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nwbrower.top/Article/details/gt2pbowlxic.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhengqikj.top/Article/details/gt2ubvuvecs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jlsjyb.cn/Article/details/gt2vanrggpd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gt2jnwrijjv.html

[H02] finally / ensure 收尾
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xzrxytxn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkyvevbp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2zfjfegcx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xxvnfweu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2amixmtct.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2quszzfki.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gt2jzcekohu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdorbqma.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2cuwybovo.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2qkmldxjm.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuanzx.com/Article/details/gt2srqaidfx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2jpbkitki.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2kplwjkzu.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ypasegrl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2gcmiqdvz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shangyingyoupin.top/Article/details/gt2muubxxwj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hysaishi.cn/Article/details/gt2exjqpidd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2nmbijdnp.html

[H04] 自定义异常类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2vvrlbngh.html

Py:   class MyError(Exception): pass
来源：http://dali.zhengqikj.top/Article/details/gt2npsnilsr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gt2vpjjywzf.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gt2yfevygvy.html

TS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwizrryv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gzhubu.top/Article/details/gt2gdhlwywy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ubhgftnv.html

Ruby: class MyError < StandardError; end
来源：http://dali.yongpay.top/Article/details/gt2gufykfqb.html

C#:   class MyException : Exception {}
来源：http://dali.svipenyu.cn/Article/details/gt2djsxhaem.html

[H05] 捕获特定类型
来源：http://dali.mhx1999.top/Article/details/gt2wqmquugf.html

Py:   except ValueError as e:
来源：http://dali.fengsongda.top/Article/details/gt2cnybbahu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2dislggdf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gt2pevwuggj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gt2qencdipk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2qdneuvjd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yonumen.top/Article/details/gt2qyancoht.html

Ruby: rescue ArgumentError => e
来源：http://dali.cashguo.top/Article/details/gt2wckxsiuf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gt2iwfkqghx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuanzhike.top/Article/details/gt2ktwpwkob.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gt2xtvewnug.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hammf.cn/Article/details/gt2kbbgmspu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gt2ysbbmkns.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gt2heriuabb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gt2sbwljtuj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gt2gerualje.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xinyue.icu/Article/details/gt2iagupccp.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2wyuopfss.html

[H07] 断言
来源：http://dali.zdqjudy.top/Article/details/gt2hjxtvoup.html

Py:   assert x > 0, "必须为正"
来源：http://dali.havefunace.top/Article/details/gt2xantdsnw.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xhyywmqx.html

JS:   console.assert(x > 0);
来源：http://dali.sysykeji.top/Article/details/gt2zwhncdrx.html

TS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2nzaasqri.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aorotlgn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oixnafaq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yonumen.top/Article/details/gt2cusagxey.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbwaukex.html

[H08] 获取错误信息与堆栈
来源：http://dali.jianghu66.top/Article/details/gt2liyynxue.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.iojbl.cn/Article/details/gt2tyhyucdh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.redwolf501.top/Article/details/gt2ohoqfxnh.html

JS:   e.message;  e.stack
来源：http://dali.nanxuanxn.top/Article/details/gt2napgogvu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gotoacloud.top/Article/details/gt2ojaykavh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vgubbxml.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gt2xwmtpxrx.html

Ruby: e.message;  e.backtrace
来源：http://dali.jianghu66.top/Article/details/gt2atynektd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xuanzx.com/Article/details/gt2epimvgwi.html

[H09] 带错误码的异常
来源：http://dali.yj20258888.top/Article/details/gt2fhuswefo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhongyouzk.top/Article/details/gt2aojluzln.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dbjfbhzu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhixingplan.top/Article/details/gt2oliyxugf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.9152youxi.cn/Article/details/gt2nbmssvya.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ybcxt.top/Article/details/gt2pnyzpqoj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dianchejie.cn/Article/details/gt2lgtebpbt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258.top/Article/details/gt2jkqllsmx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gt2qqlxmpsh.html

[H10] 资源自动释放
来源：http://dali.jinqigfzy.top/Article/details/gt2lqfayxgx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daxiang520.top/Article/details/gt2tnfbxprb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.wangdashe.top/Article/details/gt2srvtqoiy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gt2ipacfihj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gt2wsuqdfig.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shzxlz.cn/Article/details/gt2vjyxgqnt.html

Go:   defer f.Close()
来源：http://dali.wangdashe.top/Article/details/gt2arntbbwq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljfgqisl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2mactphhd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2yftzdetd.html

I. 正则表达式
来源：http://dali.zdqjudy.top/Article/details/gt2lfkqvyld.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2qdzealwv.html

[I01] 判断是否匹配
来源：http://dali.ydzc1.top/Article/details/gt2lgyawxar.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gt2ekxjzefs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fzhhl.top/Article/details/gt2aidhffmc.html

JS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gt2orrenvaw.html

TS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gt2ntsrhsye.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jyoumei.cn/Article/details/gt2wrkhraih.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.dashuyun.cn/Article/details/gt2cqvpscwl.html

Ruby: s.match?(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gt2dsyjqghz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gt2cinsdzuj.html

[I02] 提取所有匹配
来源：http://dali.316326.xyz/Article/details/gt2vyuhqliy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gt2lokcwvbu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj202588.top/Article/details/gt2tpeucijt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aibaodan.cn/Article/details/gt2xsxqjibr.html

TS:   s.match(/\d+/g)
来源：http://dali.xuanzx.com/Article/details/gt2oxzfdlts.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2tqczlgba.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wficzsgp.html

Ruby: s.scan(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gt2saiwwiwz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2sxsghelm.html

[I03] 提取捕获分组
来源：http://dali.chenzaomai.com/Article/details/gt2vhoxcfgt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ybcxt.top/Article/details/gt2gscbrpoe.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guowangkeji.top/Article/details/gt2irfdgveh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shuidangran.top/Article/details/gt2ynmowdnb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daria6918.cn/Article/details/gt2iwgfujcg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxinkj.top/Article/details/gt2agshplje.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.c1oappe.top/Article/details/gt2fjzhkqbp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxinkj.top/Article/details/gt2jpmyloqu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangtech.top/Article/details/gt2boxbvpww.html

[I04] 正则替换
来源：http://dali.meibo888.top/Article/details/gt2cxialtim.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gt2vjyskouq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2womgrxsn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gt2yeotfozq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gt2lxwhbhyr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cqqwz.cn/Article/details/gt2jsqctahw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xylfe.cn/Article/details/gt2ahdvxkth.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xuanzx.com/Article/details/gt2qdylpwjz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gt2ojzsjdbw.html

[I05] 按正则拆分
来源：http://dali.fengsongda.top/Article/details/gt2zubjgodg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hammf.cn/Article/details/gt2xcjxkdwy.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hammf.cn/Article/details/gt2nekfwerf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gt2mhpzdvfj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gt2dcfcinmd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dblsbmea.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gt2pweueqkt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mmstwqoz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hsauxcoe.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pengpengdd.cyou/Article/details/gt2dmwnpbsx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gt2vgmjlmrw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yuanzhike.top/Article/details/gt2wtiltilg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gt2xlphlyoe.html


<!-- 参考信息 -->