代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dianchejie.cn/Article/details/gt2zrbsxukh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2jdzeeuyo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aizwys.cn/Article/details/gt2dadhjdmx.html

[F12] CSV 读写
来源：http://dali.guannengcc.top/Article/details/gt2iottosuu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbjzeosy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yueranfly.top/Article/details/gt2qyttexva.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dianchejie.cn/Article/details/gt2thkkijvn.html

TS:   // 同上
来源：http://dali.gogol.net.cn/Article/details/gt2decguvcp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.iojbl.cn/Article/details/gt2uuatuzqp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenlongwang.top/Article/details/gt2msgtwohr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hywenlv.cn/Article/details/gt2irpluehs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenzaomai.com/Article/details/gt2twbrctva.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2hoysfycr.html

G. 面向对象
来源：http://dali.316326.xyz/Article/details/gt2dhpmzroe.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2vtafhpdb.html

[G01] 定义类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fslpgwvu.html

Py:   class User: pass
来源：http://dali.chenlongwang.top/Article/details/gt2ahllaemw.html

PHP:  class User {}
来源：http://dali.tian-w.cn/Article/details/gt2ierfdgor.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gt2thkeenqg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhixingplan.top/Article/details/gt2mzcypvnm.html

Java: class User {}
来源：http://dali.hfpthk.cn/Article/details/gt2spovtmiz.html

Go:   type User struct { Name string }
来源：http://dali.xziqi.cn/Article/details/gt2jhtdomwx.html

Ruby: class User; end
来源：http://dali.hammf.cn/Article/details/gt2tganufkl.html

C#:   class User {}
来源：http://dali.meibo888.top/Article/details/gt2agmehipo.html

[G02] 构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ixvmtyok.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ybcxt.top/Article/details/gt2dyxtilrp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sysykeji.top/Article/details/gt2sqdhknlq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gt2eecfhwlq.html

TS:   constructor(public name: string) {}
来源：http://dali.birdmap.top/Article/details/gt2evlelwwv.html

Java: User(String name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gt2flfjaeii.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shzxlz.cn/Article/details/gt2xowmjlbg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gt2xzoxbvqn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hfpthk.cn/Article/details/gt2wbbgceok.html

[G03] 实例属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2gqzlciwu.html

Py:   self.name = "x"
来源：http://dali.hammf.cn/Article/details/gt2olhbameg.html

PHP:  public string $name = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2xucxagys.html

JS:   this.name = "x";
来源：http://dali.yj202588.top/Article/details/gt2mgpnagve.html

TS:   name: string = "x";
来源：http://dali.guannengcc.top/Article/details/gt2deaqjmpd.html

Java: private String name;
来源：http://dali.redwolf501.top/Article/details/gt2glozzshp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.meibo888.top/Article/details/gt2ivosiqzn.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gt2ahfdrbon.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gt2dxfthxii.html

[G04] 定义方法
来源：http://dali.ybcxt.top/Article/details/gt2aqqmrjpr.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gt2iavybtaa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2oggkzvnx.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2qwlzcquw.html

TS:   greet(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2ckwszuvv.html

Java: String greet() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2adrrffym.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gt2vxmyrfqb.html

Ruby: def greet; @name; end
来源：http://dali.xuanzx.com/Article/details/gt2hhnzwhbn.html

C#:   public string Greet() => Name;
来源：http://dali.guannengcc.top/Article/details/gt2qtmalkcf.html

[G05] 继承
来源：http://dali.chenjidiqi.icu/Article/details/gt2mghlkjre.html

Py:   class Admin(User): pass
来源：http://dali.xziqi.cn/Article/details/gt2rpmgaxqv.html

PHP:  class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2klapyjni.html

JS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2pjlxhmvn.html

TS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2wbhyrkbj.html

Java: class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2yzmahztt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxinkj.top/Article/details/gt2dcvddfqa.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gt2tpocqanf.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gt2ugerojut.html

[G06] 重写方法
来源：http://dali.nanxinkj.top/Article/details/gt2shukxkgi.html

Py:   def greet(self): return "admin"
来源：http://dali.zhongyouzk.top/Article/details/gt2rxlzjwlk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2ehyjhpzw.html

JS:   greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lmntqpfh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2vriwvjvz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2xghcmpew.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuanzx.com/Article/details/gt2pfuybvnd.html

Ruby: def greet; "admin"; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kjmkqula.html

C#:   public override string Greet() => "admin";
来源：http://dali.meibo888.top/Article/details/gt2wxtwkgqv.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gt2mthjytta.html

Py:   super().greet()
来源：http://dali.dianchejie.cn/Article/details/gt2lftckgsd.html

PHP:  parent::greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2emiyaloh.html

JS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gt2dthhjyhm.html

TS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xzthzdct.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2gamsjsen.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.haohaochexian.top/Article/details/gt2xsqqzpaf.html

Ruby: super
来源：http://dali.cdnleiting.top/Article/details/gt2srplhkfi.html

C#:   base.Greet();
来源：http://dali.gogol.net.cn/Article/details/gt2pgkpudzl.html

[G08] 静态方法与属性
来源：http://dali.dashuyun.cn/Article/details/gt2qtngdyse.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daria6918.cn/Article/details/gt2tlovleez.html

PHP:  public static function f() {}
来源：http://dali.ivvv.top/Article/details/gt2zqkgffgu.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gt2zriawxov.html

TS:   static f(): void {}
来源：http://dali.tian-w.cn/Article/details/gt2xoalwtiy.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gt2yhzuymhi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenzaomai.com/Article/details/gt2bxhglhgg.html

Ruby: def self.f; end
来源：http://dali.aizwys.cn/Article/details/gt2tlttscpk.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qorqmnkh.html

[G09] 接口 / 抽象类
来源：http://dali.shuidangran.top/Article/details/gt2eimkfcuz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gt2haassdcm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gt2siqiaaqp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.feifeiyinyue.top/Article/details/gt2ixqvuwpm.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mcsinmwb.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gt2nbrsiqeg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.9152youxi.cn/Article/details/gt2txnbopjr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zycfv.cn/Article/details/gt2noazflkr.html

C#:   interface IShape { double Area(); }
来源：http://dali.ehwqpu.com/Article/details/gt2culjmbce.html

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gt2irurlebp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.mhx1999.top/Article/details/gt2wguczzlq.html

PHP:  public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gt2rgbutlkt.html

JS:   #private 字段；其余公开
来源：http://dali.feifeiyinyue.top/Article/details/gt2fqctevio.html

TS:   public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gt2dcliqius.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gt2udyhbauf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.birdmap.top/Article/details/gt2qkwdrjit.html

Ruby: public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gt2ytlymjff.html

C#:   public / protected / private / internal
来源：http://dali.0kj1m.cn/Article/details/gt2htexpgvd.html

[G11] getter / setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oddsckgp.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangtech.top/Article/details/gt2apxbbjqj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2qoskigha.html

JS:   get name() { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gt2uesificz.html

TS:   get name(): string { return this._name; }
来源：http://dali.tanke756.top/Article/details/gt2wzymegrs.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2vtvealop.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2rzonghjn.html

Ruby: attr_accessor :name
来源：http://dali.jqgfzy.top/Article/details/gt2xgvbjnnf.html

C#:   public string Name { get; set; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cwiaidba.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gt2xrljzfcm.html

Py:   def __str__(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gt2ybptbvwc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2oljzxgki.html

JS:   toString() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2iznptcds.html

TS:   toString(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2jhavbfpv.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gt2qqkhrcvo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2svllbcde.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eidhoqmr.html

C#:   public override string ToString() => Name;
来源：http://dali.svipenyu.cn/Article/details/gt2pggomody.html

[G13] 判断对象类型
来源：http://dali.316326.xyz/Article/details/gt2wjijnxto.html

Py:   isinstance(u, User)
来源：http://dali.tian-w.cn/Article/details/gt2xitctbcn.html

PHP:  $u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gt2cuslrntq.html

JS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2zugmjfmg.html

TS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2colqwfkl.html

Java: u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2pejkjsfy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mqkywkig.html

Ruby: u.is_a?(User)
来源：http://dali.jlsjyb.cn/Article/details/gt2hgsxzxlt.html

C#:   u is User
来源：http://dali.hfpthk.cn/Article/details/gt2aegfhbot.html

[G14] 数据类 / record
来源：http://dali.xinyue.icu/Article/details/gt2kthxvmal.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnqzz.top/Article/details/gt2rzaknftz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gt2gbmeiexo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daxiang520.top/Article/details/gt2wibetakf.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxuanxn.top/Article/details/gt2rwabdfex.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2uxhmdewk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.smart0.xyz/Article/details/gt2qjwbpkwd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gt2tacxdowg.html

C#:   record User(string Name, int Age);
来源：http://dali.shuidangran.top/Article/details/gt2tskbqmbc.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gt2vqmdwxpd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigfzy.top/Article/details/gt2kwfszppz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.haohaochexian.top/Article/details/gt2qhiielpe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.vqdsnc.cn/Article/details/gt2meqpbedc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gt2xlugpbcu.html

Java: enum Color { RED, GREEN }
来源：http://dali.9152youxi.cn/Article/details/gt2rjxhdnoe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenzaomai.com/Article/details/gt2qmeyppbf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gt2wrqdkohn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2xfugjmgm.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gt2qykffohj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shzxlz.cn/Article/details/gt2ogvzhbrr.html

PHP:  get_object_vars($obj);
来源：http://dali.c1oappe.top/Article/details/gt2hwxjujsl.html

JS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2wppmwmfk.html

TS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2ajfvkyel.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhongyouzk.top/Article/details/gt2htkdhrgx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cdnleiting.top/Article/details/gt2vqoretxh.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gt2wabplygv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gt2wgcimwiz.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2fhupeujq.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gt2vomdowsg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2yyqriixr.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gt2gpcvgjzy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shzxlz.cn/Article/details/gt2eogzrwlu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwvallyl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gt2jmuzizxu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gt2udmybplq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xynwanpa.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2hlxxicom.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gt2yycrvvfd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yueranfly.top/Article/details/gt2ubvlcsae.html

[H02] finally / ensure 收尾
来源：http://dali.ivvv.top/Article/details/gt2tsjnares.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.snrcjt.cn/Article/details/gt2vfgobrfv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2bfekkhjh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kaancswt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2maydeevk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wjuyuzcl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj202588.top/Article/details/gt2hchsushj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gogol.net.cn/Article/details/gt2kifmxguv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2hilbkina.html

[H03] 主动抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2xoqoizkl.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuetiantiany.cn/Article/details/gt2usramhvg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2zevttiez.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2oevmixgv.html

TS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2zfclnrfk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2pdlywmoi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sweek.top/Article/details/gt2xivvpdsa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jianghu66.top/Article/details/gt2lcvrgxoh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2koyffgiy.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gt2ctkzndgb.html

Py:   class MyError(Exception): pass
来源：http://dali.yuanzhike.top/Article/details/gt2duzpvnin.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2pubboety.html

JS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gt2spstpgud.html

TS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gt2shudchyn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gt2cepsuixn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gaohongyu789.top/Article/details/gt2kowwxpeu.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gt2aqniszhk.html

C#:   class MyException : Exception {}
来源：http://dali.chenlongwang.top/Article/details/gt2cgqdlqvc.html

[H05] 捕获特定类型
来源：http://dali.yangfankeji.com/Article/details/gt2uhopwwsp.html

Py:   except ValueError as e:
来源：http://dali.aibaodan.cn/Article/details/gt2ddfpzapn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2wshieytt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gt2aqiwwafc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2ssfjbugd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xylfe.cn/Article/details/gt2rcxwxmdp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gt2pcgtbsvm.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj202588.top/Article/details/gt2xgwvliwu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxinkj.top/Article/details/gt2sofngflw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.meibo888.top/Article/details/gt2mjtxwzty.html

Py:   value = d.get("k") or default
来源：http://dali.jyoumei.cn/Article/details/gt2sglwwjhc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gt2sqlsnqaj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gt2uggbyalc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gt2lkcfeiyx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gt2uicvzgse.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yanxiufei.cn/Article/details/gt2gxquowsb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xziqi.cn/Article/details/gt2kpkrjixq.html

C#:   obj?.A?.B ?? default
来源：http://dali.iojbl.cn/Article/details/gt2zslrysrb.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gt2wkoaabnp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgufenzy.top/Article/details/gt2ffwstdos.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2agynfpxk.html

JS:   console.assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2pytdgagl.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ndvmsnim.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gogol.net.cn/Article/details/gt2inxnoyda.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgufenzy.top/Article/details/gt2nvkzpjtd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dffgithx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dbdqawfh.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangdashe.top/Article/details/gt2wxmijenl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smbgztcy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cheryme.top/Article/details/gt2rdlodqgk.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gt2eyvqxead.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fzhhl.top/Article/details/gt2wyrrmmxz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenzaomai.com/Article/details/gt2xffgovjf.html

Go:   err.Error()
来源：http://dali.pycfn.com/Article/details/gt2rmeprpff.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ivkxzksf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.0kj1m.cn/Article/details/gt2pjsiqbjo.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gt2pemmkpmo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.mhx1999.top/Article/details/gt2dtkmtgvs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gt2zyfamula.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yangfankeji.com/Article/details/gt2wfrjohuc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jyoumei.cn/Article/details/gt2vfxeaipb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhixingplan.top/Article/details/gt2jgibhasq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuanzx.com/Article/details/gt2mxtiwsdz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhoulong.xyz/Article/details/gt2bnrjtlbl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daria6918.cn/Article/details/gt2anyqugyc.html

[H10] 资源自动释放
来源：http://dali.chenzaomai.com/Article/details/gt2hdaspfjl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gt2kzknynsg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bchvsqac.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gt2ineoholm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gt2dqbocvbi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daxiang520.top/Article/details/gt2lkaofyeh.html

Go:   defer f.Close()
来源：http://dali.yvedp.cn/Article/details/gt2mosqizzy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gt2gvofmvxd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2nurgcoeb.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2szuujmit.html

I. 正则表达式
来源：http://dali.redwolf501.top/Article/details/gt2whockofh.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2synjnxuc.html

[I01] 判断是否匹配
来源：http://dali.cheryme.top/Article/details/gt2fmtwiscp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gt2lqnyolgb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2yseqxhol.html

JS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gt2dmbwlocr.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gt2svcvmmsp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.wangshuangyany.cn/Article/details/gt2gjyzuygj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kgabiowa.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ytkzlmim.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ivvv.top/Article/details/gt2iybivxsq.html

[I02] 提取所有匹配
来源：http://dali.ydzc1.top/Article/details/gt2lbnpddwa.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gt2avdflqlq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pycfn.com/Article/details/gt2xyzkgbhn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cheryme.top/Article/details/gt2ksblvsot.html

TS:   s.match(/\d+/g)
来源：http://dali.gogol.net.cn/Article/details/gt2bjeirtby.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.bjfxy.top/Article/details/gt2eccxyopr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gaohongyu789.top/Article/details/gt2xswgajii.html

Ruby: s.scan(/\d+/)
来源：http://dali.yj20258888.top/Article/details/gt2bsmcipyr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2feijyjcl.html

[I03] 提取捕获分组
来源：http://dali.zhijiandao.cn/Article/details/gt2knfsxcop.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.birdmap.top/Article/details/gt2olqfpxyj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sysykeji.top/Article/details/gt2bxgqusju.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yvedp.cn/Article/details/gt2xyoivqjj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ppjwa.cn/Article/details/gt2spqtovta.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cpvwdeqi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gt2lmwbrkjt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigufen.top/Article/details/gt2wlwglwsn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yonumen.top/Article/details/gt2gzphhdiw.html

[I04] 正则替换
来源：http://dali.snrcjt.cn/Article/details/gt2wzzckpaq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hammf.cn/Article/details/gt2yqsvlcyk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gt2seycdmtk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxzjcln.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdgphxy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gt2srfneoea.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shuidangran.top/Article/details/gt2hfaxchbx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cheryme.top/Article/details/gt2ajqnxzuv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jiagoushi.top/Article/details/gt2shmfljcd.html

[I05] 按正则拆分
来源：http://dali.xinyue.icu/Article/details/gt2jrcoysup.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuanzhike.top/Article/details/gt2ptnoksns.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2jdcviezy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gt2dnvjaukh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gt2mukabjxv.html

Java: s.split("\\s*,\\s*")
来源：http://dali.fzhhl.top/Article/details/gt2aogggzco.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wmhvjcda.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wneuzbbj.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgfzy.top/Article/details/gt2iclexyhu.html


<!-- 参考信息 -->