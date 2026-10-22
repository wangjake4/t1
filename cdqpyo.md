代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.redwolf501.top/Article/details/gt2gbnlolys.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2aapwyhvf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.iojbl.cn/Article/details/gt2qnayijbs.html

[F12] CSV 读写
来源：http://dali.fengsongda.top/Article/details/gt2jhivgexx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cdnleiting.top/Article/details/gt2rugjyesk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fzhhl.top/Article/details/gt2luareknh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aizwys.cn/Article/details/gt2gewweeab.html

TS:   // 同上
来源：http://dali.guowangkeji.top/Article/details/gt2gksdpapn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gt2ozazejjc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.quarkkingdee.top/Article/details/gt2azzgawkj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gt2qlarheec.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuanzhike.top/Article/details/gt2qphibutw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2udtqiltr.html

G. 面向对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2qtbdwgit.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2aaqvcujm.html

[G01] 定义类
来源：http://dali.zdqjudy.top/Article/details/gt2krfoktae.html

Py:   class User: pass
来源：http://dali.ydzc1.top/Article/details/gt2cdbqlmef.html

PHP:  class User {}
来源：http://dali.hnqzz.top/Article/details/gt2ghdehaog.html

JS:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2tehpqjtr.html

TS:   class User { name: string = ""; }
来源：http://dali.jiagoushi.top/Article/details/gt2anonmwzh.html

Java: class User {}
来源：http://dali.yvedp.cn/Article/details/gt2gdlmdmtq.html

Go:   type User struct { Name string }
来源：http://dali.fengsongda.top/Article/details/gt2eymaarnu.html

Ruby: class User; end
来源：http://dali.yonumen.top/Article/details/gt2fxdwbxlp.html

C#:   class User {}
来源：http://dali.sweek.top/Article/details/gt2fiigmqaj.html

[G02] 构造函数
来源：http://dali.dianchejie.cn/Article/details/gt2bccawblt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cashguo.top/Article/details/gt2kwbgayuf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gt2jgukkzfp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gt2ssuffdrw.html

TS:   constructor(public name: string) {}
来源：http://dali.yueranfly.top/Article/details/gt2htriddoh.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gt2qhhwtpxh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhongyouzk.top/Article/details/gt2hklrutop.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yvedp.cn/Article/details/gt2szxuluas.html

C#:   public User(string name) { Name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2xipcodly.html

[G03] 实例属性
来源：http://dali.fengsongda.top/Article/details/gt2ijaakrrc.html

Py:   self.name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gt2vtuvbspe.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2rqgaatuh.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gt2sdosagok.html

TS:   name: string = "x";
来源：http://dali.zycfv.cn/Article/details/gt2wrshfcpz.html

Java: private String name;
来源：http://dali.aizwys.cn/Article/details/gt2imbbbvaj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhengqikj.top/Article/details/gt2zzmjxurh.html

Ruby: @name = "x"
来源：http://dali.ehwqpu.com/Article/details/gt2uleecclr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2lzhpebes.html

[G04] 定义方法
来源：http://dali.tianlin.xyz/Article/details/gt2khgcabas.html

Py:   def greet(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gt2sovwgzgv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2tuzakxus.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2qlcmjobi.html

TS:   greet(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2jqtwytbs.html

Java: String greet() { return name; }
来源：http://dali.yuxming.cn/Article/details/gt2rnyczgcn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gt2nrartqdl.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ikjufpav.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gt2mvowrktv.html

[G05] 继承
来源：http://dali.xylfe.cn/Article/details/gt2ufitmzeo.html

Py:   class Admin(User): pass
来源：http://dali.hywenlv.cn/Article/details/gt2wostpaug.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gt2uylqquqq.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2imnylhvj.html

TS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gt2bpdjsbjr.html

Java: class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2mfvjgdtl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gt2iqldbowj.html

Ruby: class Admin < User; end
来源：http://dali.yuanzhike.top/Article/details/gt2qcmgtmka.html

C#:   class Admin : User {}
来源：http://dali.nanxinkj.top/Article/details/gt2psuyygde.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gt2ctnmtihi.html

Py:   def greet(self): return "admin"
来源：http://dali.hfpthk.cn/Article/details/gt2fyqyaptz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2oucxsypr.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2boukebga.html

TS:   greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gt2sqlvxdug.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mdqmvqpw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gt2trzitplg.html

Ruby: def greet; "admin"; end
来源：http://dali.ydzc1.top/Article/details/gt2ugngsitg.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gt2ruxxgkjp.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gt2kejljsuf.html

Py:   super().greet()
来源：http://dali.sysykeji.top/Article/details/gt2rgshzaiw.html

PHP:  parent::greet();
来源：http://dali.iojbl.cn/Article/details/gt2gwaqbhea.html

JS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2hnqoausc.html

TS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2zhofrmei.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2fvjzpodi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangdashe.top/Article/details/gt2bluchahi.html

Ruby: super
来源：http://dali.yongpay.top/Article/details/gt2dddjwgeq.html

C#:   base.Greet();
来源：http://dali.ppjwa.cn/Article/details/gt2agbhrwbj.html

[G08] 静态方法与属性
来源：http://dali.ehwqpu.com/Article/details/gt2cmflgcoc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ybcxt.top/Article/details/gt2ykyyxsdt.html

PHP:  public static function f() {}
来源：http://dali.fzhhl.top/Article/details/gt2rwwajahi.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gt2nuffbnaq.html

TS:   static f(): void {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kagfbekf.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gt2ctjnpyne.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daria6918.cn/Article/details/gt2epoympwu.html

Ruby: def self.f; end
来源：http://dali.hnqzz.top/Article/details/gt2divytoer.html

C#:   public static void F() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twxupsrg.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigufen.top/Article/details/gt2amkvvcpz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cucudq.cn/Article/details/gt2winqbttr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gt2zslowofl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gt2adihtyoh.html

TS:   interface Shape { area(): number; }
来源：http://dali.hfpthk.cn/Article/details/gt2gwkaixzm.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258888.top/Article/details/gt2aktrjyxo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gt2jslwptrd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pycfn.com/Article/details/gt2puwomtwo.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pwhodpag.html

[G10] 访问控制
来源：http://dali.yanxiufei.cn/Article/details/gt2ilykcefn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gt2mgdjwzsa.html

PHP:  public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gt2rakckxxf.html

JS:   #private 字段；其余公开
来源：http://dali.hysaishi.cn/Article/details/gt2szypsgpl.html

TS:   public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gt2jukpwzvs.html

Java: public / protected / private / 默认包级
来源：http://dali.chenzaomai.com/Article/details/gt2dxfqvruy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aibaodan.cn/Article/details/gt2nsnouljy.html

Ruby: public / protected / private
来源：http://dali.tanke756.top/Article/details/gt2cjlgnmra.html

C#:   public / protected / private / internal
来源：http://dali.zhoulong.xyz/Article/details/gt2qaiqyvqh.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gt2vtkvyegv.html

Py:   @property 与 @x.setter
来源：http://dali.shuidangran.top/Article/details/gt2vycyylmi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gt2fytunrxh.html

JS:   get name() { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ndualwtw.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gt2yhlnkdda.html

Java: public String getName() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2eslryqvp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gt2gvrgvalp.html

Ruby: attr_accessor :name
来源：http://dali.sxryk.cn/Article/details/gt2qpjvctqr.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gt2ixktelqn.html

[G12] 对象转字符串
来源：http://dali.chenzaomai.com/Article/details/gt2vinqtqwp.html

Py:   def __str__(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gt2rtrotmqi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gt2pynkrvrd.html

JS:   toString() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2bsmdyrvz.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gt2nbvcfjaq.html

Java: @Override public String toString() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cdfotfma.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dtlvuoap.html

Ruby: def to_s; @name; end
来源：http://dali.gzhubu.top/Article/details/gt2grojyzbx.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gt2lhdvaozi.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxcuvcol.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gt2zlooltdv.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2rggdmiqc.html

JS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ywlkdljh.html

TS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2xflaorhd.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2dnskdaik.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gt2debhdgod.html

Ruby: u.is_a?(User)
来源：http://dali.quarkkingdee.top/Article/details/gt2zdtmrxri.html

C#:   u is User
来源：http://dali.zhiwuduotai.top/Article/details/gt2haeiogla.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gt2czfnvlnn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gt2bjjcrltz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gt2rtwxhkpq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gt2dtcbnodg.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gt2jpbepyvl.html

Java: record User(String name, int age) {}
来源：http://dali.ydzc1.top/Article/details/gt2lbhgudpb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.birdmap.top/Article/details/gt2ryfnfqwy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gt2svqzfmbz.html

C#:   record User(string Name, int Age);
来源：http://dali.jianghu66.top/Article/details/gt2krkpypos.html

[G15] 枚举
来源：http://dali.nanxinkj.top/Article/details/gt2ohvvmyti.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258.top/Article/details/gt2nqskfgkn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2upuvichp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daria6918.cn/Article/details/gt2beeaeqaw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pajqcjrr.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgfzy.top/Article/details/gt2vnudmfep.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigfzy.top/Article/details/gt2geznajam.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gt2eougrzsh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gt2lobsgmrs.html

[G16] 对象转数组 / 字典
来源：http://dali.jianghu66.top/Article/details/gt2hxwfkwxs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gt2wlcqyrqy.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gt2vndccgfa.html

JS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gt2xablaytn.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gt2gjbtuhmc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.kuanghao11.cn/Article/details/gt2dwcmpkri.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.mhx1999.top/Article/details/gt2fpucispa.html

Ruby: obj.instance_variables
来源：http://dali.zhengqikj.top/Article/details/gt2ujtdbenv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gt2afkmumbz.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2ikfqylun.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gt2trntyztd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2yminvqwh.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gt2pznpwntb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gt2gqewmdst.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gt2udpytnav.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gt2iksdtfbz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gt2xffoemln.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gt2vxzfvpis.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnqzz.top/Article/details/gt2lgxxctmn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.0kj1m.cn/Article/details/gt2ldoxsrji.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258.top/Article/details/gt2lhagyapp.html

[H02] finally / ensure 收尾
来源：http://dali.ehwqpu.com/Article/details/gt2jexnvwgj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cqqwz.cn/Article/details/gt2ncelivez.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2newkqeqy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2etwrzhit.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gt2ddxjqkxs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2srzzmawr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258888.top/Article/details/gt2vflbcdcr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sweek.top/Article/details/gt2nxdzptdi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2hgpydzjm.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdnsbzen.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258.top/Article/details/gt2lgfmzwfz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2xdmlgiwq.html

JS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2qhfuzxar.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2avnggxbs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2tijhkjua.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gt2nxbudhmu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gt2jonsgfbi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdbkpoe.html

[H04] 自定义异常类型
来源：http://dali.gaohongyu789.top/Article/details/gt2lmalqmde.html

Py:   class MyError(Exception): pass
来源：http://dali.jyoumei.cn/Article/details/gt2rzndvcfu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gt2uypvjcmv.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dpuhtjby.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gt2crctolyn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gt2rbdgciam.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dianchejie.cn/Article/details/gt2irgjmmsf.html

Ruby: class MyError < StandardError; end
来源：http://dali.nwbrower.top/Article/details/gt2grwqerwr.html

C#:   class MyException : Exception {}
来源：http://dali.birdmap.top/Article/details/gt2nrrefodv.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gt2nylquhvb.html

Py:   except ValueError as e:
来源：http://dali.nwbrower.top/Article/details/gt2qnnpcqvd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gt2oaxwlkqd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gt2cvtlqpcu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gt2pirwcouu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gt2fprkqgrz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shangyingyoupin.top/Article/details/gt2isgagbpt.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gt2rimfhewq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cqqwz.cn/Article/details/gt2nzrhsbau.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xylfe.cn/Article/details/gt2egvrqyno.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gt2jlnsaxal.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gt2jptaxiec.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gt2jgblhesc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gt2wjvrcari.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gt2sszpgglo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxtacptn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xinyue.icu/Article/details/gt2fngmpnnf.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnxiangtu.top/Article/details/gt2wnhujlwp.html

[H07] 断言
来源：http://dali.dianchejie.cn/Article/details/gt2dkkaewmn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hysaishi.cn/Article/details/gt2kdnrmxrh.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2choneirj.html

JS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2ygybuqvf.html

TS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2brulsouk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.316326.xyz/Article/details/gt2ubdtfcgt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.smart0.xyz/Article/details/gt2wzgijiqz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhengqikj.top/Article/details/gt2gzgcdzkk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2ntfgejaw.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenjidiqi.icu/Article/details/gt2wcswazim.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yanxiufei.cn/Article/details/gt2oebgiems.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigufen.top/Article/details/gt2mkyhyddc.html

JS:   e.message;  e.stack
来源：http://dali.shuidangran.top/Article/details/gt2jdxyctyb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jianghu66.top/Article/details/gt2hjmdldwc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.316326.xyz/Article/details/gt2wzwukrky.html

Go:   err.Error()
来源：http://dali.aizwys.cn/Article/details/gt2arlgtuuq.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenzaomai.com/Article/details/gt2ttojlxmt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tianlin.xyz/Article/details/gt2xrvablao.html

[H09] 带错误码的异常
来源：http://dali.c1oappe.top/Article/details/gt2ffcjnxps.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhongyouzk.top/Article/details/gt2sdltvkcd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuxming.cn/Article/details/gt2kkbofrix.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jlsjyb.cn/Article/details/gt2pvspujtu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj202588.top/Article/details/gt2adaorgla.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuanzx.com/Article/details/gt2zzomkutz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgufenzy.top/Article/details/gt2wiadeyiw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gt2diytujcy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.bjfxy.top/Article/details/gt2vaukcqcl.html

[H10] 资源自动释放
来源：http://dali.mhx1999.top/Article/details/gt2eaxvwyxu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gt2krdaqqvy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.pycfn.com/Article/details/gt2qjpmnqzb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guowangkeji.top/Article/details/gt2ughkairi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gt2xyfmwerp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigufen.top/Article/details/gt2grkdoiwd.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gt2pktrclgb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gt2ezwomllt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2cmjlzuko.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2fabajciz.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gt2bfzyfhip.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2zvykueln.html

[I01] 判断是否匹配
来源：http://dali.jiagoushi.top/Article/details/gt2mpxdjwxz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gt2lauhnlts.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xinyue.icu/Article/details/gt2ykykedig.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gt2ggztyvth.html

TS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gt2bdaslafi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nwbrower.top/Article/details/gt2gltltrwy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxinkj.top/Article/details/gt2bsnnnlju.html

Ruby: s.match?(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gt2ggpxaqef.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hysaishi.cn/Article/details/gt2beamillc.html

[I02] 提取所有匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2yiobiocj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gt2kvduyxao.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.smart0.xyz/Article/details/gt2sfgusqeb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.c1oappe.top/Article/details/gt2nydtwsio.html

TS:   s.match(/\d+/g)
来源：http://dali.tian-w.cn/Article/details/gt2uebjjnua.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daxiang520.top/Article/details/gt2qespgkga.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gt2ejoihhvq.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gt2qdcfsmwa.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhixingplan.top/Article/details/gt2ewbtjgrm.html

[I03] 提取捕获分组
来源：http://dali.hammf.cn/Article/details/gt2ujmknhge.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hysaishi.cn/Article/details/gt2dtwblilq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj202588.top/Article/details/gt2npkedhap.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ivvv.top/Article/details/gt2dxewqmoi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tianlin.xyz/Article/details/gt2vtjdcbjk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shzxlz.cn/Article/details/gt2qxkknyid.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxuanxn.top/Article/details/gt2cizfeebd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gzhubu.top/Article/details/gt2ykvotaji.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.9152youxi.cn/Article/details/gt2yhikqvsu.html

[I04] 正则替换
来源：http://dali.havefunace.top/Article/details/gt2hajotjzs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.birdmap.top/Article/details/gt2dasvhynd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2fdzpocfv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gt2otmedpad.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gt2ubmackka.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gaohongyu789.top/Article/details/gt2zbtobamb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2afxvzxkd.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2fbisjjxe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hysaishi.cn/Article/details/gt2vmneytpk.html

[I05] 按正则拆分
来源：http://dali.tianlin.xyz/Article/details/gt2wyyttsld.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mcaaxyrs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuanzhike.top/Article/details/gt2gxlpvztf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oqsqawoi.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gt2gkcghnye.html

Java: s.split("\\s*,\\s*")
来源：http://dali.pengpengdd.cyou/Article/details/gt2gwkvnrcp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gt2cdfkushh.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kgluqkln.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.andypj.xyz/Article/details/gt2sirwoanf.html


<!-- 参考信息 -->