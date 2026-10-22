代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hongshengwenyu.top/Article/details/gt2pmwjljjr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenjidiqi.icu/Article/details/gt2vkgpkyll.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgufenzy.top/Article/details/gt2qsziojce.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gt2jqyjpvqv.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2lanaqjss.html

G. 面向对象
来源：http://dali.iojbl.cn/Article/details/gt2srtabjsp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2lnqxfwhv.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gt2prvbuwln.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gt2uecbxscd.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gt2golzqaok.html

JS:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2exgqtmzd.html

TS:   class User { name: string = ""; }
来源：http://dali.sxryk.cn/Article/details/gt2xomoyyck.html

Java: class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkpgoxzu.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gt2wdslrkfh.html

Ruby: class User; end
来源：http://dali.vqdsnc.cn/Article/details/gt2pcysoumb.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gt2xissuunj.html

[G02] 构造函数
来源：http://dali.sweek.top/Article/details/gt2gbegeohv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shzxlz.cn/Article/details/gt2skpyvggy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.0kj1m.cn/Article/details/gt2dxuhtexj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rgpxvatk.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gt2lxstysry.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gt2qoszgbqj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.kuanghao11.cn/Article/details/gt2sivbclog.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jlsjyb.cn/Article/details/gt2osrjpiat.html

C#:   public User(string name) { Name = name; }
来源：http://dali.redwolf501.top/Article/details/gt2byizgzcc.html

[G03] 实例属性
来源：http://dali.iojbl.cn/Article/details/gt2hymexfcx.html

Py:   self.name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gt2vvhpvvuv.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gt2kkvfhxpb.html

JS:   this.name = "x";
来源：http://dali.yuxming.cn/Article/details/gt2irarfpzv.html

TS:   name: string = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2mmdbhnax.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gt2kgeuxutr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmqmvnfh.html

Ruby: @name = "x"
来源：http://dali.gogol.net.cn/Article/details/gt2jmrjbcri.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2libulrma.html

[G04] 定义方法
来源：http://dali.nwbrower.top/Article/details/gt2bweczpko.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gt2pfuryokh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gt2oquydckk.html

JS:   greet() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2zhwpforc.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xtnggthv.html

Java: String greet() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2doormswc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gt2pcgxcdbb.html

Ruby: def greet; @name; end
来源：http://dali.aibaodan.cn/Article/details/gt2ygzvqavx.html

C#:   public string Greet() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gt2kofsjlvs.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gt2egchgykd.html

Py:   class Admin(User): pass
来源：http://dali.cdnleiting.top/Article/details/gt2glkmdofl.html

PHP:  class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2zjfndmmp.html

JS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gt2wtzeirco.html

TS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2iagcktas.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2hsplzegn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gt2cisljqny.html

Ruby: class Admin < User; end
来源：http://dali.zhengqikj.top/Article/details/gt2ujlnecva.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gt2vuswtyxu.html

[G06] 重写方法
来源：http://dali.zhengqikj.top/Article/details/gt2ryltsxkm.html

Py:   def greet(self): return "admin"
来源：http://dali.fengsongda.top/Article/details/gt2jspnumbi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2brehejuf.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2mwktwhya.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2dujogtqh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2simmwhso.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gt2oukkcdcd.html

Ruby: def greet; "admin"; end
来源：http://dali.meibo888.top/Article/details/gt2qmbyfsao.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gt2xmvkbnjy.html

[G07] 调用父类方法
来源：http://dali.cucudq.cn/Article/details/gt2bplxkiko.html

Py:   super().greet()
来源：http://dali.jlsjyb.cn/Article/details/gt2btyfauwx.html

PHP:  parent::greet();
来源：http://dali.fzhhl.top/Article/details/gt2azcoqhvs.html

JS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2ltipiprw.html

TS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gt2lmvndnqk.html

Java: super.greet();
来源：http://dali.yj202588.top/Article/details/gt2kpqhlcfl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangdashe.top/Article/details/gt2vfssvjzt.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gt2yvscieto.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gt2undsqdsl.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpenrug.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gt2rifeejbb.html

PHP:  public static function f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wzdokrtx.html

JS:   static f() {}
来源：http://dali.bjfxy.top/Article/details/gt2lifrkqus.html

TS:   static f(): void {}
来源：http://dali.ppjwa.cn/Article/details/gt2dkhiknan.html

Java: static void f() {}
来源：http://dali.yj20258888.top/Article/details/gt2gzxefivj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shzxlz.cn/Article/details/gt2cnhnskzf.html

Ruby: def self.f; end
来源：http://dali.jyoumei.cn/Article/details/gt2fvfnomzc.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gt2etxvptxz.html

[G09] 接口 / 抽象类
来源：http://dali.316326.xyz/Article/details/gt2affmzklu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnqzz.top/Article/details/gt2wojmmklt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shzxlz.cn/Article/details/gt2mcuctgiy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gt2lfslqkib.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gt2uwtsotcw.html

Java: interface Shape { double area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wzehogus.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yueranfly.top/Article/details/gt2qxrfrmhi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xziqi.cn/Article/details/gt2bazgcnht.html

C#:   interface IShape { double Area(); }
来源：http://dali.gzhubu.top/Article/details/gt2tfzukwbw.html

[G10] 访问控制
来源：http://dali.xinyue.icu/Article/details/gt2uidkkgdl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.iojbl.cn/Article/details/gt2slgkuhjw.html

PHP:  public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2ngtevwhd.html

JS:   #private 字段；其余公开
来源：http://dali.jqgufenzy.top/Article/details/gt2ylmnybwx.html

TS:   public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qigsuwnz.html

Java: public / protected / private / 默认包级
来源：http://dali.daxiang520.top/Article/details/gt2sjyrfgbu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.kuanghao11.cn/Article/details/gt2hwbzkbya.html

Ruby: public / protected / private
来源：http://dali.fengsongda.top/Article/details/gt2ababvtdf.html

C#:   public / protected / private / internal
来源：http://dali.zhoulong.xyz/Article/details/gt2ernggejm.html

[G11] getter / setter
来源：http://dali.chenjidiqi.icu/Article/details/gt2cuargwri.html

Py:   @property 与 @x.setter
来源：http://dali.chenlongwang.top/Article/details/gt2zhqhqsgs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gt2doftinza.html

JS:   get name() { return this._name; }
来源：http://dali.cashguo.top/Article/details/gt2ycklckct.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gt2mafgcpze.html

Java: public String getName() { return name; }
来源：http://dali.pycfn.com/Article/details/gt2rzmfxnlw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gt2bqcjggtg.html

Ruby: attr_accessor :name
来源：http://dali.daxiang520.top/Article/details/gt2hqvqlvpf.html

C#:   public string Name { get; set; }
来源：http://dali.fzhhl.top/Article/details/gt2ylyehghl.html

[G12] 对象转字符串
来源：http://dali.zhixingplan.top/Article/details/gt2ursnqfcp.html

Py:   def __str__(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gt2hjxqjfek.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gt2livzokda.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2gugvuhkm.html

TS:   toString(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2umbwhtoc.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2eyuoatxe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2gzsrngyf.html

Ruby: def to_s; @name; end
来源：http://dali.cheryme.top/Article/details/gt2jubxpufo.html

C#:   public override string ToString() => Name;
来源：http://dali.cqqwz.cn/Article/details/gt2kqdzidwp.html

[G13] 判断对象类型
来源：http://dali.zdqjudy.top/Article/details/gt2eyvvprhv.html

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gt2pzfyuatj.html

PHP:  $u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gt2yrpkhqrm.html

JS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2ffowdyhx.html

TS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gt2bbqzkqmp.html

Java: u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2cnayvgix.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gt2pxktnffx.html

Ruby: u.is_a?(User)
来源：http://dali.daria6918.cn/Article/details/gt2syaejprt.html

C#:   u is User
来源：http://dali.zhixingplan.top/Article/details/gt2tiiibfhe.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gt2rlvmance.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.meibo888.top/Article/details/gt2efgeitrj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tanke756.top/Article/details/gt2cbhblhoa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gt2mdkrulbp.html

TS:   type User = { name: string; age: number };
来源：http://dali.jyoumei.cn/Article/details/gt2ixnfnjjo.html

Java: record User(String name, int age) {}
来源：http://dali.gotoacloud.top/Article/details/gt2rzsjegjf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fzhhl.top/Article/details/gt2rjqvawnl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tian-w.cn/Article/details/gt2ncyriily.html

C#:   record User(string Name, int Age);
来源：http://dali.xziqi.cn/Article/details/gt2wgxkrsym.html

[G15] 枚举
来源：http://dali.zhoulong.xyz/Article/details/gt2cfxbuuyv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gaohongyu789.top/Article/details/gt2zoltngdn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hywenlv.cn/Article/details/gt2yppoyxjg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cashguo.top/Article/details/gt2amrftptp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2vbzzzzkn.html

Java: enum Color { RED, GREEN }
来源：http://dali.iojbl.cn/Article/details/gt2gkqhwmcb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ribqycpo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.0kj1m.cn/Article/details/gt2fygydzih.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gt2mwpztrmm.html

[G16] 对象转数组 / 字典
来源：http://dali.xylfe.cn/Article/details/gt2jzvackzc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gzhubu.top/Article/details/gt2gjaypbnd.html

PHP:  get_object_vars($obj);
来源：http://dali.ppjwa.cn/Article/details/gt2eksiggie.html

JS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gt2dckdluat.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gt2jxzkmlzu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oubbnwzu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sxryk.cn/Article/details/gt2ttgzfpgb.html

Ruby: obj.instance_variables
来源：http://dali.quarkkingdee.top/Article/details/gt2cxqlvehc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gt2knbphdls.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2iymofrpj.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gt2cbgbinhi.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2vdavobkn.html

[H01] try / catch 基础
来源：http://dali.zycfv.cn/Article/details/gt2ucvhraas.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tian-w.cn/Article/details/gt2ofbbfuqy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gt2danemuwm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gt2buerrqvu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hsmfbosj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gt2qgilsenf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ivvv.top/Article/details/gt2jmpcdwco.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ezimpgat.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jlsjyb.cn/Article/details/gt2pnabkxru.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gt2catzbpjm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.havefunace.top/Article/details/gt2qyyzitvv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2cbletvnr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjxtbwpg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2haowfnog.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gt2ptqphpnu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sxryk.cn/Article/details/gt2fysnbiqk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xinyue.icu/Article/details/gt2wrmuciym.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2otvaocsf.html

[H03] 主动抛出异常
来源：http://dali.birdmap.top/Article/details/gt2wvrztyey.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gt2oaxsypys.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hbogefhc.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2plxzdezn.html

TS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2ctebsuyw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2jajitvjn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gt2vecxyqvj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gt2jgekzaee.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2hueazbpa.html

[H04] 自定义异常类型
来源：http://dali.aibaodan.cn/Article/details/gt2jklwyebw.html

Py:   class MyError(Exception): pass
来源：http://dali.fengsongda.top/Article/details/gt2kqsljrip.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gt2uprehjkd.html

JS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ermxzmhr.html

TS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gt2vginiswp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gt2ngyilgog.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sefjsokv.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gt2spklewjc.html

C#:   class MyException : Exception {}
来源：http://dali.hammf.cn/Article/details/gt2baaqnxvr.html

[H05] 捕获特定类型
来源：http://dali.dianchejie.cn/Article/details/gt2whhldrbz.html

Py:   except ValueError as e:
来源：http://dali.guannengcc.top/Article/details/gt2vduhmnzo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gt2pjqrgadf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gt2xkzmuyhn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gt2cumojcbm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2qfapgzia.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gt2ljzkjdkm.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnqzz.top/Article/details/gt2hppbptbm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2cieecdqg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigufen.top/Article/details/gt2qggbazrz.html

Py:   value = d.get("k") or default
来源：http://dali.yangfankeji.com/Article/details/gt2njorhosr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bkmerhpi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2qhfxnjvi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gt2cynlxxnm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fnjawdcm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gt2zseqbway.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gt2uydppfqh.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fchrejhv.html

[H07] 断言
来源：http://dali.xuetiantiany.cn/Article/details/gt2jzzptfos.html

Py:   assert x > 0, "必须为正"
来源：http://dali.feifeiyinyue.top/Article/details/gt2qdlbnpdu.html

PHP:  assert($x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2rtawczxu.html

JS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2qsjhcshs.html

TS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2jadgtuar.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj202588.top/Article/details/gt2qaqugtly.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pdgjfvto.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ppjwa.cn/Article/details/gt2rczapwvn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gt2ygxnvbjc.html

[H08] 获取错误信息与堆栈
来源：http://dali.nwbrower.top/Article/details/gt2huctmwxj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuxming.cn/Article/details/gt2tvlirhrc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenjidiqi.icu/Article/details/gt2uyjtfeya.html

JS:   e.message;  e.stack
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wqwizgky.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258.top/Article/details/gt2wsakiucy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xylfe.cn/Article/details/gt2rfekuopm.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gt2ahxxhqrb.html

Ruby: e.message;  e.backtrace
来源：http://dali.cqqwz.cn/Article/details/gt2mwskybgd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jlsjyb.cn/Article/details/gt2zibglzvi.html

[H09] 带错误码的异常
来源：http://dali.fengsongda.top/Article/details/gt2jvoexuai.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gt2zczdzeog.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zdqjudy.top/Article/details/gt2hxwnkekx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ffqpqrda.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gt2ftrjmpop.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qbbntgoa.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gt2boqpqlnc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnqzz.top/Article/details/gt2aspycode.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2igdwcfur.html

[H10] 资源自动释放
来源：http://dali.nanxuanxn.top/Article/details/gt2nfismpzw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yonumen.top/Article/details/gt2ytskubbb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gaohongyu789.top/Article/details/gt2vvukmddr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gt2lhgbiukp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gt2ujyphfvv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jiagoushi.top/Article/details/gt2jpqucarm.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gt2oecabhxh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zycfv.cn/Article/details/gt2kmduiqjt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2klfrccps.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2eqrcofjf.html

I. 正则表达式
来源：http://dali.wangdashe.top/Article/details/gt2bylmqjjq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2uklwkdcz.html

[I01] 判断是否匹配
来源：http://dali.ivvv.top/Article/details/gt2mnvfvfdo.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gt2qlqmkykt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2vhdvxwal.html

JS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2nplpbuhi.html

TS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2hneczwbu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2euczuyrv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sweek.top/Article/details/gt2ijdwjuxd.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xndshrza.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cheryme.top/Article/details/gt2fyldvgde.html

[I02] 提取所有匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2haifrkdx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gt2ujvamvao.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gaohongyu789.top/Article/details/gt2ofocivhz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cucudq.cn/Article/details/gt2irqeawmo.html

TS:   s.match(/\d+/g)
来源：http://dali.yvedp.cn/Article/details/gt2mbrldxda.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jqgfzy.top/Article/details/gt2ifqlkyco.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258888.top/Article/details/gt2urgxcanq.html

Ruby: s.scan(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gt2faylwvww.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.bjfxy.top/Article/details/gt2gxsjeebj.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gt2nnedyrub.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cashguo.top/Article/details/gt2aandzudz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tianlin.xyz/Article/details/gt2hootvpsb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenzaomai.com/Article/details/gt2kgptdkkz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuxming.cn/Article/details/gt2xouibhga.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2mclsuauj.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xinyue.icu/Article/details/gt2yncfgybe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.havefunace.top/Article/details/gt2byilofuy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jianghu66.top/Article/details/gt2jerrqlpl.html

[I04] 正则替换
来源：http://dali.daria6918.cn/Article/details/gt2xdjtgurd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sufxvd.cn/Article/details/gt2jjrmahfc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gt2qriysqxi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2mdlhhddj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fkcrqkrk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258.top/Article/details/gt2yhpebfvx.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangdashe.top/Article/details/gt2ohzhzcba.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yueranfly.top/Article/details/gt2wpnajpnr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gt2vhnbxckv.html

[I05] 按正则拆分
来源：http://dali.gogol.net.cn/Article/details/gt2tnhgrjug.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2duogpiyh.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2jscpxrdi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gt2pxuauokp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gt2rkcqlkda.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xylfe.cn/Article/details/gt2bcobcfzp.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gt2yfsxqpbx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gt2dnzjbdot.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vaezwtzi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ppjwa.cn/Article/details/gt2hpnjaweu.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhiwuduotai.top/Article/details/gt2lyvflmle.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenzaomai.com/Article/details/gt2pxcowfjm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgufenzy.top/Article/details/gt2flspolls.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gt2kwstlvrj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jqgufenzy.top/Article/details/gt2udwweegf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktyvowoh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ehwqpu.com/Article/details/gt2gncbttmj.html


<!-- 参考信息 -->