代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jyoumei.cn/Article/details/gt2jdhrztfu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gt2fuqzwqsl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuanzhike.top/Article/details/gt2uwizsshv.html

[F12] CSV 读写
来源：http://dali.guannengcc.top/Article/details/gt2ueciwmwo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.9152youxi.cn/Article/details/gt2stlqjrpq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gt2vyhcbrgs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hywenlv.cn/Article/details/gt2zgzpbzvt.html

TS:   // 同上
来源：http://dali.dianchejie.cn/Article/details/gt2fjdmgjfa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dianchejie.cn/Article/details/gt2wmyqiyav.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sweek.top/Article/details/gt2hgkllcob.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gt2oibqnovd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shzxlz.cn/Article/details/gt2izmfezlb.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2tjvxfgnt.html

G. 面向对象
来源：http://dali.nwbrower.top/Article/details/gt2cvbhkaoe.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2mpjixqct.html

[G01] 定义类
来源：http://dali.sysykeji.top/Article/details/gt2zwqpmnbk.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gt2fimppeoh.html

PHP:  class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2wlqpboil.html

JS:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2cefbqeaj.html

TS:   class User { name: string = ""; }
来源：http://dali.meibo888.top/Article/details/gt2fltoemex.html

Java: class User {}
来源：http://dali.c1oappe.top/Article/details/gt2vrvclbyu.html

Go:   type User struct { Name string }
来源：http://dali.fengsongda.top/Article/details/gt2fkqwjrvz.html

Ruby: class User; end
来源：http://dali.yanxiufei.cn/Article/details/gt2iafmpzbp.html

C#:   class User {}
来源：http://dali.xylfe.cn/Article/details/gt2cnafbkqy.html

[G02] 构造函数
来源：http://dali.c1oappe.top/Article/details/gt2qgspcpjo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.feifeiyinyue.top/Article/details/gt2ylydlsmi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2cjwymyyh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ekvywhod.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gt2xnarqdho.html

Java: User(String name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gt2hwvacbpq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tanke756.top/Article/details/gt2qfmxhyjr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2rnmgrhlf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2yydunuoy.html

[G03] 实例属性
来源：http://dali.yuanzhike.top/Article/details/gt2skofbpni.html

Py:   self.name = "x"
来源：http://dali.daxiang520.top/Article/details/gt2bbhddiqq.html

PHP:  public string $name = "x";
来源：http://dali.cashguo.top/Article/details/gt2zmrqpryv.html

JS:   this.name = "x";
来源：http://dali.shuidangran.top/Article/details/gt2ycgkoeoq.html

TS:   name: string = "x";
来源：http://dali.hammf.cn/Article/details/gt2hyapgmrp.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gt2ssplrwow.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jyoumei.cn/Article/details/gt2zunzlcwc.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gt2owwiyhki.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2zjhykspz.html

[G04] 定义方法
来源：http://dali.daria6918.cn/Article/details/gt2qfxuzdnq.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gt2vtfhmywn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gt2wnwyhfxy.html

JS:   greet() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gt2hxbtxrmi.html

TS:   greet(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jgdlxytb.html

Java: String greet() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gt2ekjwbdns.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2vvnbzjvl.html

Ruby: def greet; @name; end
来源：http://dali.yj202588.top/Article/details/gt2ejbpghqa.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gt2wlipldyd.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gt2akvqbhar.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gt2mkysyvzc.html

PHP:  class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gt2mltbepkz.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gt2sffuubwa.html

TS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2cbamhvky.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2atazpmwp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zdqjudy.top/Article/details/gt2eirbhjyt.html

Ruby: class Admin < User; end
来源：http://dali.chenlongwang.top/Article/details/gt2iogcrnrq.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ikycqucf.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gt2btgckhdp.html

Py:   def greet(self): return "admin"
来源：http://dali.sysykeji.top/Article/details/gt2wkbbkjds.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gt2vebfxbho.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2lyoeurlf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bmvpaotj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2bfgpxsfs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhixingplan.top/Article/details/gt2ggdyuirf.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gt2iwjiggkg.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gt2ghpzyeph.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gt2zmpaueqw.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gt2vxqfixvl.html

PHP:  parent::greet();
来源：http://dali.xylfe.cn/Article/details/gt2zgxvqcuk.html

JS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2dapaodhi.html

TS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gt2xuyvgppq.html

Java: super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zofowcte.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.andypj.xyz/Article/details/gt2efwzxiuw.html

Ruby: super
来源：http://dali.zhongyouzk.top/Article/details/gt2hsrlxrvh.html

C#:   base.Greet();
来源：http://dali.dianchejie.cn/Article/details/gt2fwizsqqx.html

[G08] 静态方法与属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kcxntjck.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oijvgdyu.html

PHP:  public static function f() {}
来源：http://dali.gotoacloud.top/Article/details/gt2mfzqwlgl.html

JS:   static f() {}
来源：http://dali.fengsongda.top/Article/details/gt2numusrhz.html

TS:   static f(): void {}
来源：http://dali.fengsongda.top/Article/details/gt2mfvqejrz.html

Java: static void f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2cioabusk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258888.top/Article/details/gt2vbfpwnym.html

Ruby: def self.f; end
来源：http://dali.cqqwz.cn/Article/details/gt2fatmiqtn.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ryekiepw.html

[G09] 接口 / 抽象类
来源：http://dali.jianghu66.top/Article/details/gt2rnpanuio.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.0kj1m.cn/Article/details/gt2blnruuyz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvnwufm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yonumen.top/Article/details/gt2igmkqwxb.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gt2ghytuyjy.html

Java: interface Shape { double area(); }
来源：http://dali.ybcxt.top/Article/details/gt2wuslmxao.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yongpay.top/Article/details/gt2jcxjfpri.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.meibo888.top/Article/details/gt2lychmgtg.html

C#:   interface IShape { double Area(); }
来源：http://dali.iojbl.cn/Article/details/gt2hclkzfgv.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gt2sgxptbmr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yvedp.cn/Article/details/gt2sfdjvscv.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2msqkodzm.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258888.top/Article/details/gt2zxinripm.html

TS:   public / protected / private
来源：http://dali.mhx1999.top/Article/details/gt2fpcilaca.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gt2toentnjy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gt2oggzaahl.html

Ruby: public / protected / private
来源：http://dali.yj20258888.top/Article/details/gt2owbkdlus.html

C#:   public / protected / private / internal
来源：http://dali.hfpthk.cn/Article/details/gt2bollvrrk.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gt2xxgticji.html

Py:   @property 与 @x.setter
来源：http://dali.zhengqikj.top/Article/details/gt2laawudbl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gt2rydfhcja.html

JS:   get name() { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mklmigyx.html

TS:   get name(): string { return this._name; }
来源：http://dali.havefunace.top/Article/details/gt2loynphck.html

Java: public String getName() { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2kanfpdmc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2elwqyvjp.html

Ruby: attr_accessor :name
来源：http://dali.pycfn.com/Article/details/gt2jblzuqql.html

C#:   public string Name { get; set; }
来源：http://dali.hysaishi.cn/Article/details/gt2lnyyfpmx.html

[G12] 对象转字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2vvgxubqz.html

Py:   def __str__(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gt2osbbwicu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfgwqnua.html

JS:   toString() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2artljhan.html

TS:   toString(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2fewzaegj.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2isoyxdup.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gt2ketxbgqf.html

Ruby: def to_s; @name; end
来源：http://dali.xylfe.cn/Article/details/gt2snfspdwb.html

C#:   public override string ToString() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2lfconjwj.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gt2nlpgdnrp.html

Py:   isinstance(u, User)
来源：http://dali.cdnleiting.top/Article/details/gt2roncidej.html

PHP:  $u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2lwyajroe.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2wwwkhhkc.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2vopjljak.html

Java: u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2ytcmqbqt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gt2biytbbnp.html

Ruby: u.is_a?(User)
来源：http://dali.aibaodan.cn/Article/details/gt2quzzxapr.html

C#:   u is User
来源：http://dali.c1oappe.top/Article/details/gt2ffswndzl.html

[G14] 数据类 / record
来源：http://dali.cheryme.top/Article/details/gt2mnsbisbm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gt2nwcyeiuc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qfcacxfz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhixingplan.top/Article/details/gt2gxeurjaj.html

TS:   type User = { name: string; age: number };
来源：http://dali.birdmap.top/Article/details/gt2qpuynhnb.html

Java: record User(String name, int age) {}
来源：http://dali.jianghu66.top/Article/details/gt2fvrypimu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuxming.cn/Article/details/gt2styxxyab.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tanke756.top/Article/details/gt2fdealcmg.html

C#:   record User(string Name, int Age);
来源：http://dali.tianlin.xyz/Article/details/gt2tpngtarj.html

[G15] 枚举
来源：http://dali.yuanzhike.top/Article/details/gt2orilyafb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gt2oaoslkpj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aebwgfqz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.iojbl.cn/Article/details/gt2ahkqqjuk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jgbbxmfg.html

Java: enum Color { RED, GREEN }
来源：http://dali.0kj1m.cn/Article/details/gt2enrgdcly.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj202588.top/Article/details/gt2dqolpwjq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tanke756.top/Article/details/gt2duuilmnk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2dcclqynq.html

[G16] 对象转数组 / 字典
来源：http://dali.gogol.net.cn/Article/details/gt2qqkmrrft.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yonumen.top/Article/details/gt2tkzaoxyx.html

PHP:  get_object_vars($obj);
来源：http://dali.aizwys.cn/Article/details/gt2wnvgfwsn.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gt2eseygepp.html

TS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2tvocqfyz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guowangkeji.top/Article/details/gt2dkhcctzg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2sayypmmm.html

Ruby: obj.instance_variables
来源：http://dali.xuetiantiany.cn/Article/details/gt2tirmfdgf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj202588.top/Article/details/gt2xcyietet.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2weijayrx.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gt2gufuvbfn.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2nkskqlyn.html

[H01] try / catch 基础
来源：http://dali.gotoacloud.top/Article/details/gt2ggawrxek.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daxiang520.top/Article/details/gt2zdlsuftp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vdgscgex.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nlyzmfjj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gt2jrztbqej.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gt2xloktsma.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenlongwang.top/Article/details/gt2fadzbefx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhoulong.xyz/Article/details/gt2cihnswxz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.iojbl.cn/Article/details/gt2vldsbrax.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gt2abjpktpe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gt2tgpxeayw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zwjetniw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eowlnzll.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2uruckole.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvxhntiq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ehwqpu.com/Article/details/gt2gjxysvgb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.0kj1m.cn/Article/details/gt2phvywxul.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2iyyjexrc.html

[H03] 主动抛出异常
来源：http://dali.c1oappe.top/Article/details/gt2dktdyuto.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gt2cobezgfu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ilgkgeko.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gt2aohoiijc.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gt2qbsybhbs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vwbgwmhg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.andypj.xyz/Article/details/gt2czocfbmw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.316326.xyz/Article/details/gt2eiejmutw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2ijuwygbh.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gt2rbwmlfqx.html

Py:   class MyError(Exception): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lteiwshu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gt2wqzdukmo.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gt2xsvrhrlo.html

TS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gt2jqyvkcjy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gt2zuiblzlc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gt2tutjicgu.html

Ruby: class MyError < StandardError; end
来源：http://dali.sxryk.cn/Article/details/gt2muwqhtie.html

C#:   class MyException : Exception {}
来源：http://dali.aizwys.cn/Article/details/gt2jlbuauqu.html

[H05] 捕获特定类型
来源：http://dali.cashguo.top/Article/details/gt2nbljqqhe.html

Py:   except ValueError as e:
来源：http://dali.hywenlv.cn/Article/details/gt2spsvkgnl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuxming.cn/Article/details/gt2qijhnhkd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2phppkxcs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2dfspapag.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxinkj.top/Article/details/gt2sncgxcaa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gt2efhhtong.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gt2fvggwbxd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gt2agpxebhq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.snrcjt.cn/Article/details/gt2suiavqpo.html

Py:   value = d.get("k") or default
来源：http://dali.aibaodan.cn/Article/details/gt2mfmcezrd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gt2tbzfakkb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gt2ysxgzptz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gt2lxhinvgi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gt2zwzgiknt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.smart0.xyz/Article/details/gt2jsxwfmxr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gt2ijywipdi.html

C#:   obj?.A?.B ?? default
来源：http://dali.c1oappe.top/Article/details/gt2azzulcfv.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gt2xcixfcxy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xylfe.cn/Article/details/gt2hfsjxeuh.html

PHP:  assert($x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2iwmintts.html

JS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2kcoodwqq.html

TS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tcapuogf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gt2sgozwefu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhoulong.xyz/Article/details/gt2iyomfboy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gt2bsxzhvhn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ttzlubjn.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2eyrazorr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenlongwang.top/Article/details/gt2nquqfhwl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yongpay.top/Article/details/gt2komowihd.html

JS:   e.message;  e.stack
来源：http://dali.dashuyun.cn/Article/details/gt2rvnbaqlp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.mhx1999.top/Article/details/gt2eguipsre.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nmyecssu.html

Go:   err.Error()
来源：http://dali.yonumen.top/Article/details/gt2ytdgixsl.html

Ruby: e.message;  e.backtrace
来源：http://dali.0kj1m.cn/Article/details/gt2hpkhlejy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangshuangyany.cn/Article/details/gt2rrmlzjrg.html

[H09] 带错误码的异常
来源：http://dali.kuanghao11.cn/Article/details/gt2twopabzf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgfzy.top/Article/details/gt2yumquksp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhjpsnsw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258.top/Article/details/gt2tpbujbbu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jianghu66.top/Article/details/gt2zgwqzpad.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sysykeji.top/Article/details/gt2vjtbjenq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gzhubu.top/Article/details/gt2hjibvnth.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guannengcc.top/Article/details/gt2rlxhwmaq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gt2sxwrkrit.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gt2fukznszw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.meibo888.top/Article/details/gt2ellpovfy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.smart0.xyz/Article/details/gt2gxlakwrg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gt2ybxmjwcs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gt2zwhqnupl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangdashe.top/Article/details/gt2zgrnpvye.html

Go:   defer f.Close()
来源：http://dali.chenlongwang.top/Article/details/gt2yqtkjdoa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aibaodan.cn/Article/details/gt2yzanfhhv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2tafgurug.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2hiyitioi.html

I. 正则表达式
来源：http://dali.sweek.top/Article/details/gt2ydhpkhrd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yscecpji.html

[I01] 判断是否匹配
来源：http://dali.gotoacloud.top/Article/details/gt2dsdlhfqm.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gt2lxxrpglw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2qjwlgqre.html

JS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gt2hiifjejh.html

TS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gt2ffivrxjt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yoadxarl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yvedp.cn/Article/details/gt2lplzilli.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258.top/Article/details/gt2zgynfdsa.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gotoacloud.top/Article/details/gt2hmdqmzfp.html

[I02] 提取所有匹配
来源：http://dali.bjfxy.top/Article/details/gt2ygjvhvkh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxinkj.top/Article/details/gt2bjhnenhh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.haohaochexian.top/Article/details/gt2zwsvmtqp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dashuyun.cn/Article/details/gt2qibnxnzz.html

TS:   s.match(/\d+/g)
来源：http://dali.vqdsnc.cn/Article/details/gt2afvghbex.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2plhomoud.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cdnleiting.top/Article/details/gt2mqjzumnb.html

Ruby: s.scan(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gt2ygfkendx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2kttnndrr.html

[I03] 提取捕获分组
来源：http://dali.redwolf501.top/Article/details/gt2bqevsjlx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jiagoushi.top/Article/details/gt2reaierjs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dianchejie.cn/Article/details/gt2rjlwjtfg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2jfqzaqjs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yvedp.cn/Article/details/gt2gcwgytzi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.svipenyu.cn/Article/details/gt2xckzeqwc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hfpthk.cn/Article/details/gt2rkgnzwjz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zdqjudy.top/Article/details/gt2zycstwfa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gt2hfdoeaez.html

[I04] 正则替换
来源：http://dali.tian-w.cn/Article/details/gt2ftxwqcsp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ybcxt.top/Article/details/gt2pvqcmqop.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kpnwqqqn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gt2uvijatjb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gt2izpdqzbu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.fzhhl.top/Article/details/gt2wjobetmb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.birdmap.top/Article/details/gt2aracqvnc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dashuyun.cn/Article/details/gt2nbwnltwp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gt2yumnesqz.html

[I05] 按正则拆分
来源：http://dali.yuanzhike.top/Article/details/gt2hhuzjaey.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gaohongyu789.top/Article/details/gt2oircbdhg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2hznuhnes.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sxryk.cn/Article/details/gt2ebqezqzp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gt2imubnylg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hysaishi.cn/Article/details/gt2ebfgnopk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gt2pocajgtb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gt2gzwryzbc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gt2pverpygc.html


<!-- 参考信息 -->