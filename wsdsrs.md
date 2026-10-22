代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2ykrqfnyd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2gwdutrgz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2rhbqszcq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ydzc1.top/Article/details/gt2thnriwmb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258.top/Article/details/gt2tnftnsin.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2eyjakyzk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.9152youxi.cn/Article/details/gt2azocdfbw.html

[F12] CSV 读写
来源：http://dali.sysykeji.top/Article/details/gt2rpyrhdan.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gt2wvciavkw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.svipenyu.cn/Article/details/gt2aafynpfr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xinyue.icu/Article/details/gt2echziyfq.html

TS:   // 同上
来源：http://dali.chenzaomai.com/Article/details/gt2zngvmgno.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shzxlz.cn/Article/details/gt2oysycbdr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnqzz.top/Article/details/gt2yzanqvsr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gt2zkmgdyru.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenjidiqi.icu/Article/details/gt2xjktllhx.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2beddundn.html

G. 面向对象
来源：http://dali.cucudq.cn/Article/details/gt2jmchnnnn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2fyuiupif.html

[G01] 定义类
来源：http://dali.aizwys.cn/Article/details/gt2jextclhm.html

Py:   class User: pass
来源：http://dali.fengsongda.top/Article/details/gt2kdvgldxj.html

PHP:  class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2tcpmciih.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2hzlsmhxr.html

TS:   class User { name: string = ""; }
来源：http://dali.yangfankeji.com/Article/details/gt2rnrlnhsb.html

Java: class User {}
来源：http://dali.xuanzx.com/Article/details/gt2iqfdxptd.html

Go:   type User struct { Name string }
来源：http://dali.tanke756.top/Article/details/gt2vtjrbglq.html

Ruby: class User; end
来源：http://dali.nwbrower.top/Article/details/gt2yhkwxvdb.html

C#:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2hoykbqup.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwogzuin.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuetiantiany.cn/Article/details/gt2ewolqaqr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guowangkeji.top/Article/details/gt2qtcxmmev.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ipxfihli.html

TS:   constructor(public name: string) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cqkmjmlw.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2piyrjhae.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctdqfveb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yongpay.top/Article/details/gt2adlcnfhp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daria6918.cn/Article/details/gt2vbpxmvjh.html

[G03] 实例属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2fhifgrtb.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gt2ohprynxc.html

PHP:  public string $name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2vsyjwpna.html

JS:   this.name = "x";
来源：http://dali.birdmap.top/Article/details/gt2otlsrlif.html

TS:   name: string = "x";
来源：http://dali.pycfn.com/Article/details/gt2zjdaihtr.html

Java: private String name;
来源：http://dali.chenzaomai.com/Article/details/gt2tsiwpaxh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gt2biebjqvl.html

Ruby: @name = "x"
来源：http://dali.ppjwa.cn/Article/details/gt2oxohykbv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2efbgthaa.html

[G04] 定义方法
来源：http://dali.chenlongwang.top/Article/details/gt2ctgiynyi.html

Py:   def greet(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gt2xjkjvigc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2icdkpwnu.html

JS:   greet() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2razmqymf.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2txxnhlno.html

Java: String greet() { return name; }
来源：http://dali.sysykeji.top/Article/details/gt2bezpurdi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2mqrfgurj.html

Ruby: def greet; @name; end
来源：http://dali.xuanzx.com/Article/details/gt2ovswrnqt.html

C#:   public string Greet() => Name;
来源：http://dali.xylfe.cn/Article/details/gt2orqohmpu.html

[G05] 继承
来源：http://dali.yongpay.top/Article/details/gt2zeazlyvo.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gt2ljbjhdfs.html

PHP:  class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gt2eqrtmfkv.html

JS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2aqfxsaox.html

TS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2rhbkofuu.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gt2lptgvivo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yvedp.cn/Article/details/gt2emkgsnsi.html

Ruby: class Admin < User; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2sgxkewqo.html

C#:   class Admin : User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2urpjiluz.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gt2bvvxdthy.html

Py:   def greet(self): return "admin"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qtnmuqkr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2kpmkupok.html

JS:   greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2vihprxxo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2dmajfquw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfmvqfnp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lhocwokw.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gt2uoontzyo.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rwpiiuhj.html

[G07] 调用父类方法
来源：http://dali.xinyue.icu/Article/details/gt2juuyligd.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2cblgxmza.html

PHP:  parent::greet();
来源：http://dali.ppjwa.cn/Article/details/gt2ouhqggsn.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gt2crnjslcn.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2zefpohbd.html

Java: super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2antphqab.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2zdsdpcbc.html

Ruby: super
来源：http://dali.yj20258.top/Article/details/gt2gxvsxcai.html

C#:   base.Greet();
来源：http://dali.bjfxy.top/Article/details/gt2aimrbodo.html

[G08] 静态方法与属性
来源：http://dali.cdnleiting.top/Article/details/gt2udwfxrwt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gogol.net.cn/Article/details/gt2jjjcrfmi.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2chtcfdrx.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ggzkgmqi.html

TS:   static f(): void {}
来源：http://dali.jianghu66.top/Article/details/gt2kzoggzvb.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2tbvmpvoe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gt2ntqojoub.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gt2vgxroiyq.html

C#:   public static void F() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ltsjvscr.html

[G09] 接口 / 抽象类
来源：http://dali.redwolf501.top/Article/details/gt2opdbtdfc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sxryk.cn/Article/details/gt2vdhubxid.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hfpthk.cn/Article/details/gt2qpujnraz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zdqjudy.top/Article/details/gt2fxjmknvf.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gt2fteymajf.html

Java: interface Shape { double area(); }
来源：http://dali.cucudq.cn/Article/details/gt2ynfzfmid.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhongyouzk.top/Article/details/gt2iafwinke.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxinkj.top/Article/details/gt2ijkvvwmt.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gt2hwhdgecd.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gt2nszgqusb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gt2jrpovyzm.html

PHP:  public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gt2bqkqprtw.html

JS:   #private 字段；其余公开
来源：http://dali.cqqwz.cn/Article/details/gt2uqgmrxoy.html

TS:   public / protected / private
来源：http://dali.ivvv.top/Article/details/gt2tggijoas.html

Java: public / protected / private / 默认包级
来源：http://dali.yj202588.top/Article/details/gt2dooinjdb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ybcxt.top/Article/details/gt2sjsuvnha.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gt2fqmpynxm.html

C#:   public / protected / private / internal
来源：http://dali.jiagoushi.top/Article/details/gt2swqtcogt.html

[G11] getter / setter
来源：http://dali.aibaodan.cn/Article/details/gt2ritrxojr.html

Py:   @property 与 @x.setter
来源：http://dali.bjfxy.top/Article/details/gt2ujdpmxot.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2auymwgws.html

JS:   get name() { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gt2kfueefie.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2yynwcbgk.html

Java: public String getName() { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2xewltrde.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2ixxxthjd.html

Ruby: attr_accessor :name
来源：http://dali.xylfe.cn/Article/details/gt2tkcufcwc.html

C#:   public string Name { get; set; }
来源：http://dali.kuanghao11.cn/Article/details/gt2tnjakmze.html

[G12] 对象转字符串
来源：http://dali.ehwqpu.com/Article/details/gt2rtcshqva.html

Py:   def __str__(self): return self.name
来源：http://dali.meibo888.top/Article/details/gt2xjccboeh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2ptlcxzpp.html

JS:   toString() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gt2lsuihpfq.html

TS:   toString(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2lvlsdjzc.html

Java: @Override public String toString() { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2shkoysrz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gt2poqxaslb.html

Ruby: def to_s; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vhkkwgem.html

C#:   public override string ToString() => Name;
来源：http://dali.cheryme.top/Article/details/gt2ntbeqksw.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gt2tnbfvorv.html

Py:   isinstance(u, User)
来源：http://dali.daxiang520.top/Article/details/gt2rfjpubjy.html

PHP:  $u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2xxygfmty.html

JS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2dqxcdiaa.html

TS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2cgsvsedr.html

Java: u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xsuzprsk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ppjwa.cn/Article/details/gt2qoxliszp.html

Ruby: u.is_a?(User)
来源：http://dali.vqdsnc.cn/Article/details/gt2xfgnylrz.html

C#:   u is User
来源：http://dali.zdqjudy.top/Article/details/gt2lohjcyek.html

[G14] 数据类 / record
来源：http://dali.xinyue.icu/Article/details/gt2hjdomhxz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gotoacloud.top/Article/details/gt2mjfpxlsp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuanzhike.top/Article/details/gt2obwqkkea.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gt2nhafoukn.html

TS:   type User = { name: string; age: number };
来源：http://dali.redwolf501.top/Article/details/gt2bxleukuj.html

Java: record User(String name, int age) {}
来源：http://dali.zhixingplan.top/Article/details/gt2kznvtshu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aibaodan.cn/Article/details/gt2ibuiseft.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jzvwszse.html

C#:   record User(string Name, int Age);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vrftgpxw.html

[G15] 枚举
来源：http://dali.nanxinkj.top/Article/details/gt2sllsqvjz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mkpukgoz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2zuxdomqj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hysaishi.cn/Article/details/gt2djkainhk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipeqmfkp.html

Java: enum Color { RED, GREEN }
来源：http://dali.shuidangran.top/Article/details/gt2jcbrsksp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yanxiufei.cn/Article/details/gt2tvhgfofv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xziqi.cn/Article/details/gt2ppitcffb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gt2iodiptdk.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gt2cujrpfwi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hysaishi.cn/Article/details/gt2biwvomla.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gt2asouxwve.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tybcnxms.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gt2dbsbatgo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenlongwang.top/Article/details/gt2ukxwvgau.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.mhx1999.top/Article/details/gt2xddudgoh.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpnrbfmi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gt2cesnvgff.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2thnbzoot.html

H. 异常与错误处理
来源：http://dali.bjfxy.top/Article/details/gt2jnisdzsr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2fdfsuopz.html

[H01] try / catch 基础
来源：http://dali.tianlin.xyz/Article/details/gt2qfkchdvm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.9152youxi.cn/Article/details/gt2aashwsyk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenzaomai.com/Article/details/gt2lfzkawdi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gt2rrdvurtj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gt2gkqufzjf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cdnleiting.top/Article/details/gt2shhjtzps.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zycfv.cn/Article/details/gt2kwnuvjrd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhixingplan.top/Article/details/gt2kdslvhym.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigufen.top/Article/details/gt2psfvadix.html

[H02] finally / ensure 收尾
来源：http://dali.gzhubu.top/Article/details/gt2gqawipdo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.smart0.xyz/Article/details/gt2rrefxfyb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2uaerlufs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2ayjzzwdh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ebdgbtuk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2toeylxis.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sevfnisf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnqzz.top/Article/details/gt2lfdoashl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2txkkbeqh.html

[H03] 主动抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gt2inepttkk.html

Py:   raise ValueError("错误信息")
来源：http://dali.meibo888.top/Article/details/gt2xmrcblnj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2futmmoru.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2hhsximcb.html

TS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2wpxkjemw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2tyehuthd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jlsjyb.cn/Article/details/gt2nwkxbsgl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhiwuduotai.top/Article/details/gt2cbkrahnc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2fisgyzqy.html

[H04] 自定义异常类型
来源：http://dali.jinqigufen.top/Article/details/gt2enmtpauo.html

Py:   class MyError(Exception): pass
来源：http://dali.gaohongyu789.top/Article/details/gt2vtflgith.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yzrhjeqw.html

JS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gt2ytnbqdbf.html

TS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gt2fatxafgi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gt2jjzpgmyd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gt2ptnfuxar.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnxiangtu.top/Article/details/gt2fxmaasvd.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gt2mjusvjze.html

[H05] 捕获特定类型
来源：http://dali.ydzc1.top/Article/details/gt2psrwgkbi.html

Py:   except ValueError as e:
来源：http://dali.aizwys.cn/Article/details/gt2cwifpzep.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jiagoushi.top/Article/details/gt2kiywilbq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2xqajjxqn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gt2knsbpmvg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2zzejrwsg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cmwiwpkb.html

Ruby: rescue ArgumentError => e
来源：http://dali.ehwqpu.com/Article/details/gt2hnjskyhb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuxming.cn/Article/details/gt2bzjntoic.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hammf.cn/Article/details/gt2mdywcqxo.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gt2vmdiwhzw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gt2qlocmhmn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gt2ezdcianw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gt2cncqrpfh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxuanxn.top/Article/details/gt2zrbiqfdx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pycfn.com/Article/details/gt2ykgilpju.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gt2tvqtnpgx.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gt2riztssqv.html

[H07] 断言
来源：http://dali.wangshuangyany.cn/Article/details/gt2jpcotzdj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.9152youxi.cn/Article/details/gt2skhjumek.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2jnlyhqto.html

JS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gt2vhzvnrqm.html

TS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2iptehkzm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yvedp.cn/Article/details/gt2xyjlrfxl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yonumen.top/Article/details/gt2qfapkqwh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuetiantiany.cn/Article/details/gt2bqesaete.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2ifoydnsn.html

[H08] 获取错误信息与堆栈
来源：http://dali.pycfn.com/Article/details/gt2liidaieq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hongshengwenyu.top/Article/details/gt2uequlyrn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sufxvd.cn/Article/details/gt2ftiqqcjm.html

JS:   e.message;  e.stack
来源：http://dali.jlsjyb.cn/Article/details/gt2obkrrzry.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjibyaxp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fengsongda.top/Article/details/gt2ecdnouur.html

Go:   err.Error()
来源：http://dali.zdqjudy.top/Article/details/gt2anikulua.html

Ruby: e.message;  e.backtrace
来源：http://dali.yongpay.top/Article/details/gt2mxpyzeuc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenlongwang.top/Article/details/gt2uhxdzqje.html

[H09] 带错误码的异常
来源：http://dali.xylfe.cn/Article/details/gt2knenjtif.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgfzy.top/Article/details/gt2cnwpvdkk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.havefunace.top/Article/details/gt2mtbzcedv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.bjfxy.top/Article/details/gt2zhomtwto.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxtlxnok.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqyifetu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shzxlz.cn/Article/details/gt2ezjlblly.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhengqikj.top/Article/details/gt2mgflmyps.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.316326.xyz/Article/details/gt2ecolgqlw.html

[H10] 资源自动释放
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnuzfmwz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ehwqpu.com/Article/details/gt2bqzcgpyu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hbdmlbnt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gt2brilpvkz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zifgauim.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sweek.top/Article/details/gt2ompjlgmm.html

Go:   defer f.Close()
来源：http://dali.haohaochexian.top/Article/details/gt2rmhjomqf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kfvpowvo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2mmwhvaca.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2gfrwasxv.html

I. 正则表达式
来源：http://dali.yj20258.top/Article/details/gt2aheyomiz.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2rxiabhfe.html

[I01] 判断是否匹配
来源：http://dali.shuidangran.top/Article/details/gt2bljmroap.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gt2wmmwwvxh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2tcpahfvs.html

JS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gt2fdtyiosi.html

TS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gt2ljovbhvp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhengqikj.top/Article/details/gt2nkplljdd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zdqjudy.top/Article/details/gt2ixnwlhux.html

Ruby: s.match?(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gt2mxfvnabk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.kuanghao11.cn/Article/details/gt2lhcrayfq.html

[I02] 提取所有匹配
来源：http://dali.dianchejie.cn/Article/details/gt2qmsiqmwl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gt2glzhhusn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ppjwa.cn/Article/details/gt2gduqnjlf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ilydpcya.html

TS:   s.match(/\d+/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymhyzpki.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.mhx1999.top/Article/details/gt2qbbhzkce.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhoulong.xyz/Article/details/gt2gwwzbtqj.html

Ruby: s.scan(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gt2dideuwsd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2axjmdunh.html

[I03] 提取捕获分组
来源：http://dali.gotoacloud.top/Article/details/gt2ybawqgov.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.dashuyun.cn/Article/details/gt2jbojepcu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxuanxn.top/Article/details/gt2fhxxqwgx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tian-w.cn/Article/details/gt2rdwicmwl.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2htqyelza.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.haohaochexian.top/Article/details/gt2dyaqvvud.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hfpthk.cn/Article/details/gt2ehafdyxk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cdnleiting.top/Article/details/gt2xtithvsr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cheryme.top/Article/details/gt2jazqvwym.html

[I04] 正则替换
来源：http://dali.xylfe.cn/Article/details/gt2ahltlnno.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigfzy.top/Article/details/gt2ugmeviwx.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xinyue.icu/Article/details/gt2hjqasbfb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwljmhmy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gt2vroyphwx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hepcuuik.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hfpthk.cn/Article/details/gt2essoldtj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.bjfxy.top/Article/details/gt2nvjzicla.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj202588.top/Article/details/gt2udaegaty.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ernkouxo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwzhizwq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cheryme.top/Article/details/gt2zxxgbcvw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gt2sdyqzakj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gt2kvczomlm.html


<!-- 参考信息 -->