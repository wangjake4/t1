代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gt2xlwmoqxm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gt2rordjasl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2qcgbdlho.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guowangkeji.top/Article/details/gt2sllktwav.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jjeusxtb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2mjkdpgvx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2umfynjwb.html

[F12] CSV 读写
来源：http://dali.zhiwuduotai.top/Article/details/gt2ywjxnbgv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ehwqpu.com/Article/details/gt2loawujwv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.0kj1m.cn/Article/details/gt2rqusdkpq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tianlin.xyz/Article/details/gt2ybchbgoi.html

TS:   // 同上
来源：http://dali.jqgufenzy.top/Article/details/gt2cjhisndf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.smart0.xyz/Article/details/gt2ewaoweex.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gt2fhdrnnbc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sxryk.cn/Article/details/gt2tolhmaod.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yongpay.top/Article/details/gt2dveufnzg.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2tymusgea.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gt2atsgxunx.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2wkerkwtd.html

[G01] 定义类
来源：http://dali.jqgfzy.top/Article/details/gt2vvkvokaq.html

Py:   class User: pass
来源：http://dali.sysykeji.top/Article/details/gt2rowgjxmy.html

PHP:  class User {}
来源：http://dali.yvedp.cn/Article/details/gt2fuqvrvjh.html

JS:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2eaxonpdl.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gt2qmectbvh.html

Java: class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2auaydtkt.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gt2cmxttcnh.html

Ruby: class User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rswqkwyr.html

C#:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2tcpnuyky.html

[G02] 构造函数
来源：http://dali.shzxlz.cn/Article/details/gt2efvawfen.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxuanxn.top/Article/details/gt2bskdacoo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.svipenyu.cn/Article/details/gt2rkvvkgau.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gt2vcbrmfby.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258.top/Article/details/gt2uxxatxzq.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gt2qqukqaaq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gt2blyqfinf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yueranfly.top/Article/details/gt2zrgvapgf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgfzy.top/Article/details/gt2vwefaqeu.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gt2vowyssrq.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gt2lavwvuni.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvvmjqgh.html

JS:   this.name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2hplcqntw.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gt2iwdqiqjn.html

Java: private String name;
来源：http://dali.chenlongwang.top/Article/details/gt2ptslpddo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gt2tvekmejf.html

Ruby: @name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gt2rszygdbe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2inhcuflf.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gt2vtksqpkk.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gt2gpujtynh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2injjidcg.html

JS:   greet() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2acrzwmch.html

TS:   greet(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2vjukkbnx.html

Java: String greet() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rgttwvao.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2nwmisoea.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gt2mxltvket.html

C#:   public string Greet() => Name;
来源：http://dali.tanke756.top/Article/details/gt2xoeqwrhp.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2luifgrlh.html

Py:   class Admin(User): pass
来源：http://dali.shangyingyoupin.top/Article/details/gt2mzieboao.html

PHP:  class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gt2eszojsge.html

JS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2utjhokxa.html

TS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2jbzqtrob.html

Java: class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gt2axjlrftt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gaenlaxw.html

Ruby: class Admin < User; end
来源：http://dali.cheryme.top/Article/details/gt2rvtxrwdt.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gt2nllhidty.html

[G06] 重写方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmcyechq.html

Py:   def greet(self): return "admin"
来源：http://dali.andypj.xyz/Article/details/gt2hzlghafk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2xmxszcos.html

JS:   greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2oqbagain.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2gjkhkvtc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2zrbihcbc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.mhx1999.top/Article/details/gt2eiadvgqn.html

Ruby: def greet; "admin"; end
来源：http://dali.dashuyun.cn/Article/details/gt2orborleg.html

C#:   public override string Greet() => "admin";
来源：http://dali.sufxvd.cn/Article/details/gt2vmtmqbkb.html

[G07] 调用父类方法
来源：http://dali.gzhubu.top/Article/details/gt2rpvjrefk.html

Py:   super().greet()
来源：http://dali.jiagoushi.top/Article/details/gt2fwcbnjuj.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2mqsemafm.html

JS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gt2ytvwosru.html

TS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gt2oxljvnpu.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gt2ujfjrloq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gt2wxumyijq.html

Ruby: super
来源：http://dali.svipenyu.cn/Article/details/gt2onzggdhz.html

C#:   base.Greet();
来源：http://dali.shzxlz.cn/Article/details/gt2ugmvfpwg.html

[G08] 静态方法与属性
来源：http://dali.jqgfzy.top/Article/details/gt2cycowgds.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sweek.top/Article/details/gt2exkzwtjz.html

PHP:  public static function f() {}
来源：http://dali.birdmap.top/Article/details/gt2pbsigots.html

JS:   static f() {}
来源：http://dali.yj20258.top/Article/details/gt2lubhcccd.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gt2chwhktvx.html

Java: static void f() {}
来源：http://dali.zdqjudy.top/Article/details/gt2vkymglqg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gt2lhcyfdma.html

Ruby: def self.f; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2iezycmst.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gt2pwltpxju.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gt2blqbrxnd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ehwqpu.com/Article/details/gt2xariwwjz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gt2gvzdybcg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gt2jltlpzpt.html

TS:   interface Shape { area(): number; }
来源：http://dali.jianghu66.top/Article/details/gt2fsleyvth.html

Java: interface Shape { double area(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2axrniqkw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gt2atevroqv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gt2onrfowrs.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2piqxrszs.html

[G10] 访问控制
来源：http://dali.hfpthk.cn/Article/details/gt2bnezevah.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.andypj.xyz/Article/details/gt2bhnotium.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpxykefe.html

JS:   #private 字段；其余公开
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pzfzpoeq.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gt2tdgfvflu.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gt2hoyjbnxh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgufenzy.top/Article/details/gt2evsrcjyu.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gt2fbmdwxje.html

C#:   public / protected / private / internal
来源：http://dali.ppjwa.cn/Article/details/gt2zmhyvene.html

[G11] getter / setter
来源：http://dali.wangshuangyany.cn/Article/details/gt2mmswyxye.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gt2qhvxvxnp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2kdtmqfit.html

JS:   get name() { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gt2wiqmdtws.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gt2ibxhmlif.html

Java: public String getName() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvyuiljo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gt2wlqrcthj.html

Ruby: attr_accessor :name
来源：http://dali.sweek.top/Article/details/gt2flulfbrw.html

C#:   public string Name { get; set; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbxbylij.html

[G12] 对象转字符串
来源：http://dali.zhengqikj.top/Article/details/gt2kjlgodds.html

Py:   def __str__(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gt2fxzkctwa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gt2zcmaoxxu.html

JS:   toString() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gt2koddwajj.html

TS:   toString(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2hkatgmgq.html

Java: @Override public String toString() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2qxdfbqes.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gt2cnlaoqpd.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gt2fmhuselz.html

C#:   public override string ToString() => Name;
来源：http://dali.c1oappe.top/Article/details/gt2opnbtnhc.html

[G13] 判断对象类型
来源：http://dali.redwolf501.top/Article/details/gt2tcbcxwlw.html

Py:   isinstance(u, User)
来源：http://dali.cdnleiting.top/Article/details/gt2pcvbwlky.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2emthnjwn.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2vskgqata.html

TS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gt2izbqkeob.html

Java: u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2yprelowu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenlongwang.top/Article/details/gt2ruuhfjpv.html

Ruby: u.is_a?(User)
来源：http://dali.guowangkeji.top/Article/details/gt2ompbygae.html

C#:   u is User
来源：http://dali.c1oappe.top/Article/details/gt2pawexybv.html

[G14] 数据类 / record
来源：http://dali.ivvv.top/Article/details/gt2pvltdrsw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aibaodan.cn/Article/details/gt2hdxvjpwz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gt2siqwgkdo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guannengcc.top/Article/details/gt2ohdlgbjf.html

TS:   type User = { name: string; age: number };
来源：http://dali.0kj1m.cn/Article/details/gt2ljfoucnh.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gt2azgmbtpk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daria6918.cn/Article/details/gt2wrnbdxrf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangshuangyany.cn/Article/details/gt2qzpqkwkf.html

C#:   record User(string Name, int Age);
来源：http://dali.nwbrower.top/Article/details/gt2ekpygkbf.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uxasrmjj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dashuyun.cn/Article/details/gt2rtatlmnl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangdashe.top/Article/details/gt2swgyjgqp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xylfe.cn/Article/details/gt2uhcqwwma.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wpyhnzdh.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gt2wagzwwkx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gt2hifuqgjo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gt2hoibjzey.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fvathzao.html

[G16] 对象转数组 / 字典
来源：http://dali.hfpthk.cn/Article/details/gt2ebmydojb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhoulong.xyz/Article/details/gt2rmajchhi.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxuanxn.top/Article/details/gt2cwdsrbsj.html

JS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2toglxkhh.html

TS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2slbmqkcn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqenikkb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnxiangtu.top/Article/details/gt2atxncexb.html

Ruby: obj.instance_variables
来源：http://dali.hongshengwenyu.top/Article/details/gt2wbpykqks.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gt2kngyecdd.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2vexfvbea.html

H. 异常与错误处理
来源：http://dali.nanxinkj.top/Article/details/gt2zuhhesfs.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2rnzrxgpo.html

[H01] try / catch 基础
来源：http://dali.316326.xyz/Article/details/gt2fumxoxix.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gt2gkmwabor.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhixingplan.top/Article/details/gt2ilkwmtlk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gt2jvtrjrjs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gt2nyhuggxq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sxryk.cn/Article/details/gt2wutrihsu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gzhubu.top/Article/details/gt2tcbwcbgv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gt2chspytzy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gt2ydefyltr.html

[H02] finally / ensure 收尾
来源：http://dali.dashuyun.cn/Article/details/gt2lnnnyqpk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daxiang520.top/Article/details/gt2pmfpijqu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2lwauanoa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2nmpqusvt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2zrcuyarm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2coajtjhd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gt2wxsbbzjh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hywenlv.cn/Article/details/gt2hrmxfesw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2guwsjgiw.html

[H03] 主动抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gt2mmouuhpq.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gt2dfcezkir.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2tlgbiunx.html

JS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2jnaorzpv.html

TS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2bxezhgqv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrscsdjg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shuidangran.top/Article/details/gt2czvirrfe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cdnleiting.top/Article/details/gt2xfeagjkz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2urqxmfua.html

[H04] 自定义异常类型
来源：http://dali.dashuyun.cn/Article/details/gt2helxllid.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gt2ysdbcjjx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gt2tlppvnxi.html

JS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gt2xlntdjyh.html

TS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ndjblklk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gt2gfvvpdzl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gt2qpzwhvxm.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhixingplan.top/Article/details/gt2iisyoalx.html

C#:   class MyException : Exception {}
来源：http://dali.xylfe.cn/Article/details/gt2isuobcjd.html

[H05] 捕获特定类型
来源：http://dali.shzxlz.cn/Article/details/gt2qjvfzjez.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gt2sizyplxa.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hywenlv.cn/Article/details/gt2iftenunj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gt2oeqhaphy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gt2vuozfthy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2tauwczny.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxinkj.top/Article/details/gt2jpzuucff.html

Ruby: rescue ArgumentError => e
来源：http://dali.jianghu66.top/Article/details/gt2byjjzmcu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daria6918.cn/Article/details/gt2xcroqxxm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xylfe.cn/Article/details/gt2fznmmdav.html

Py:   value = d.get("k") or default
来源：http://dali.tian-w.cn/Article/details/gt2qxbksbkg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gt2jkfwpnqz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gt2hgarpaxk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gt2ojnxfvkm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.andypj.xyz/Article/details/gt2lboibuly.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2juevmbpv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuxming.cn/Article/details/gt2bsxdiudr.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgufenzy.top/Article/details/gt2omoknmvv.html

[H07] 断言
来源：http://dali.shzxlz.cn/Article/details/gt2vnmkkinb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yvedp.cn/Article/details/gt2yimkxlct.html

PHP:  assert($x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2caqqzdqu.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2ernqphcl.html

TS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2vukqlwug.html

Java: assert x > 0 : "必须为正";
来源：http://dali.daxiang520.top/Article/details/gt2wangwwfy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hammf.cn/Article/details/gt2jksvelxy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.316326.xyz/Article/details/gt2snhxrgeg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2huzaleqh.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bieqekam.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gzhubu.top/Article/details/gt2fsteaxsw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hywenlv.cn/Article/details/gt2kmtllkbs.html

JS:   e.message;  e.stack
来源：http://dali.mhx1999.top/Article/details/gt2xsugerrd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.9152youxi.cn/Article/details/gt2aehfdnth.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.iojbl.cn/Article/details/gt2ngkisybi.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gt2faymxiiu.html

Ruby: e.message;  e.backtrace
来源：http://dali.cdnleiting.top/Article/details/gt2oaprbjfe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sxryk.cn/Article/details/gt2ssgbaykw.html

[H09] 带错误码的异常
来源：http://dali.tianlin.xyz/Article/details/gt2ejlgqddv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gt2mfrzcjjw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.mhx1999.top/Article/details/gt2gmwrkbsx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.guannengcc.top/Article/details/gt2amtotfpb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mxirhznb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zbuoqooi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.0kj1m.cn/Article/details/gt2jrlxwbiy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gt2ywpkpjic.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cucudq.cn/Article/details/gt2ldyoinbe.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gt2pudbyzke.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yangfankeji.com/Article/details/gt2iwdmqxdf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gt2yylkkbts.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenzaomai.com/Article/details/gt2qzzllyyq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gt2uwaytujt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jlsjyb.cn/Article/details/gt2bopmrdcy.html

Go:   defer f.Close()
来源：http://dali.tianlin.xyz/Article/details/gt2wtlyfcbs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cqqwz.cn/Article/details/gt2zilbwjpu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2sdjptodr.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2cwbbgneu.html

I. 正则表达式
来源：http://dali.sysykeji.top/Article/details/gt2lvqzybhc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2kibjkpmb.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uuibqrtv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gt2gfyxyuid.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2sgjmyvxd.html

JS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2orjzpfkz.html

TS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gt2qhwnmsum.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cqqwz.cn/Article/details/gt2onlqvbsg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hysaishi.cn/Article/details/gt2hbxmpcyh.html

Ruby: s.match?(/\d+/)
来源：http://dali.hfpthk.cn/Article/details/gt2rczzxtkn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dashuyun.cn/Article/details/gt2qdqgczrl.html

[I02] 提取所有匹配
来源：http://dali.jqgfzy.top/Article/details/gt2mmvnrwej.html

Py:   re.findall(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2gwnwsucz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tian-w.cn/Article/details/gt2yxngyzuy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhongyouzk.top/Article/details/gt2adaleqik.html

TS:   s.match(/\d+/g)
来源：http://dali.yuanzhike.top/Article/details/gt2fomhyyag.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2knhpldij.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.daxiang520.top/Article/details/gt2loglbfxg.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wffwkbdp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ppjwa.cn/Article/details/gt2cezetfkn.html

[I03] 提取捕获分组
来源：http://dali.chenjidiqi.icu/Article/details/gt2snmdfewy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ehwqpu.com/Article/details/gt2ixjmjkvj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sweek.top/Article/details/gt2imefqrdg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xziqi.cn/Article/details/gt2rgnspmyb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hfpthk.cn/Article/details/gt2nlvnczxt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuanzx.com/Article/details/gt2kezxnjnu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhiwuduotai.top/Article/details/gt2ptyduueg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hammf.cn/Article/details/gt2zohokxaa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gotoacloud.top/Article/details/gt2mcndvmkq.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gt2lvjicodk.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenzaomai.com/Article/details/gt2jktvagll.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.mhx1999.top/Article/details/gt2wgqkszdd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.birdmap.top/Article/details/gt2ukntczmk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2btrnjzkh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gt2zdrmlvly.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.pycfn.com/Article/details/gt2jztkzijr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hfpthk.cn/Article/details/gt2pcstktrh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shzxlz.cn/Article/details/gt2lwkcriks.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gt2ykrgahnt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yj202588.top/Article/details/gt2rvxlvtec.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2jafvdqve.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gt2tbfjyszw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnimeerf.html


<!-- 参考信息 -->