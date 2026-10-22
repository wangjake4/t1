代发 wailian999

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vqtxjafd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shuidangran.top/Article/details/gt2sihtjnxl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gt2gwznhpak.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.mhx1999.top/Article/details/gt2tmnwbwom.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2vxztksjy.html

G. 面向对象
来源：http://dali.andypj.xyz/Article/details/gt2rwwriqon.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2vdjlxqow.html

[G01] 定义类
来源：http://dali.meibo888.top/Article/details/gt2mbtyioik.html

Py:   class User: pass
来源：http://dali.xuanzx.com/Article/details/gt2ckupalbm.html

PHP:  class User {}
来源：http://dali.cheryme.top/Article/details/gt2mqolghkm.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gt2bxcsarsx.html

TS:   class User { name: string = ""; }
来源：http://dali.tianlin.xyz/Article/details/gt2krojysht.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gt2cnpmrafw.html

Go:   type User struct { Name string }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qkgjnbfx.html

Ruby: class User; end
来源：http://dali.andypj.xyz/Article/details/gt2dakabcto.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2djwocqrb.html

[G02] 构造函数
来源：http://dali.xuanzx.com/Article/details/gt2ipiirpen.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gt2jyislnfw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gt2ptmmiqdf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gt2xmftdsei.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gt2pxfdtclr.html

Java: User(String name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gt2cfkupgbl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gt2odbzfnta.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gt2vugcbynb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2pqeonqhi.html

[G03] 实例属性
来源：http://dali.chenzaomai.com/Article/details/gt2efgtuhii.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gt2ofadrzeo.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ehigkttf.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2vnotkgkh.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2lvdzrprn.html

Java: private String name;
来源：http://dali.ivvv.top/Article/details/gt2xjvgcbkd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gt2olhgmqjs.html

Ruby: @name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gt2afsyixzt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2pghqqfwj.html

[G04] 定义方法
来源：http://dali.gzhubu.top/Article/details/gt2zzxwyzvc.html

Py:   def greet(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gt2uscxevvh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2hhfefnts.html

JS:   greet() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2hewrneep.html

TS:   greet(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2vbxcdwhw.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2psncsudq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2aauipmqj.html

Ruby: def greet; @name; end
来源：http://dali.haohaochexian.top/Article/details/gt2vvencxqr.html

C#:   public string Greet() => Name;
来源：http://dali.yueranfly.top/Article/details/gt2unxnwpaa.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gt2zkgrizso.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gt2mtyxqwdg.html

PHP:  class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2zinffwsd.html

JS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2qwwivwla.html

TS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2dlzejoyh.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zszzwwzc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cqqwz.cn/Article/details/gt2uerjaoyc.html

Ruby: class Admin < User; end
来源：http://dali.shzxlz.cn/Article/details/gt2bodtmbrl.html

C#:   class Admin : User {}
来源：http://dali.gzhubu.top/Article/details/gt2ehjgqnrk.html

[G06] 重写方法
来源：http://dali.jiagoushi.top/Article/details/gt2sieiqqiq.html

Py:   def greet(self): return "admin"
来源：http://dali.xziqi.cn/Article/details/gt2tuyionhn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vuxbngeo.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2rsdgdfkw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2stovqbuf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nugljkps.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjygrugy.html

Ruby: def greet; "admin"; end
来源：http://dali.xinyue.icu/Article/details/gt2hyjkqpvq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gt2soxytszn.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gt2bgybkmdq.html

Py:   super().greet()
来源：http://dali.9152youxi.cn/Article/details/gt2dvxpjrzl.html

PHP:  parent::greet();
来源：http://dali.xuanzx.com/Article/details/gt2nrposxto.html

JS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gt2xpevmlwk.html

TS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gt2kgiwlndd.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gt2odlqpbyx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2aurbnsgi.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gt2njrdhiob.html

C#:   base.Greet();
来源：http://dali.xuanzx.com/Article/details/gt2rzdfiiou.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gt2gxprfqjm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj20258888.top/Article/details/gt2hafiknxm.html

PHP:  public static function f() {}
来源：http://dali.fzhhl.top/Article/details/gt2dtdsigsd.html

JS:   static f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ofjqhhph.html

TS:   static f(): void {}
来源：http://dali.dashuyun.cn/Article/details/gt2gabjflwt.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2zeibjnvm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigufen.top/Article/details/gt2agzyqqrj.html

Ruby: def self.f; end
来源：http://dali.nanxuanxn.top/Article/details/gt2ehqqulye.html

C#:   public static void F() {}
来源：http://dali.hysaishi.cn/Article/details/gt2suymdzsp.html

[G09] 接口 / 抽象类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxekurzp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gt2aqdnqkyz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gotoacloud.top/Article/details/gt2ihdpngmb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yonumen.top/Article/details/gt2wnstdysc.html

TS:   interface Shape { area(): number; }
来源：http://dali.cucudq.cn/Article/details/gt2kkfskoqe.html

Java: interface Shape { double area(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2esbxxqxy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhongyouzk.top/Article/details/gt2zykrmowp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenzaomai.com/Article/details/gt2vyzkdzoy.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gt2acpxjnuu.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gt2xhasnywa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cucudq.cn/Article/details/gt2ekrhzbcd.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kudolxkh.html

JS:   #private 字段；其余公开
来源：http://dali.shzxlz.cn/Article/details/gt2nivtcybo.html

TS:   public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gt2kkzgjmct.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gt2vyjeiufg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gt2tqnptjxa.html

Ruby: public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gt2oktwubsh.html

C#:   public / protected / private / internal
来源：http://dali.dianchejie.cn/Article/details/gt2scdeuelm.html

[G11] getter / setter
来源：http://dali.dashuyun.cn/Article/details/gt2pnkotukw.html

Py:   @property 与 @x.setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2szkqfqur.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gt2agpjaaev.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2lejctngb.html

TS:   get name(): string { return this._name; }
来源：http://dali.hammf.cn/Article/details/gt2nqqduabd.html

Java: public String getName() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2qkilsekw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gt2olcoxwla.html

Ruby: attr_accessor :name
来源：http://dali.snrcjt.cn/Article/details/gt2uacsxtbc.html

C#:   public string Name { get; set; }
来源：http://dali.zhixingplan.top/Article/details/gt2bjkpgcia.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gt2avzaasde.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gt2ojivbklo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gt2jpyqpjum.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2wbcjosgl.html

TS:   toString(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gt2vjayzqgc.html

Java: @Override public String toString() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2hdzbgfcv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gt2yaibutbn.html

Ruby: def to_s; @name; end
来源：http://dali.hammf.cn/Article/details/gt2mfxfeqto.html

C#:   public override string ToString() => Name;
来源：http://dali.smart0.xyz/Article/details/gt2jizimrzn.html

[G13] 判断对象类型
来源：http://dali.jyoumei.cn/Article/details/gt2fcjxnine.html

Py:   isinstance(u, User)
来源：http://dali.guannengcc.top/Article/details/gt2tcirfvho.html

PHP:  $u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gt2hyefvfwf.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2aaablrpb.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2msykdodt.html

Java: u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2iejohygc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangshuangyany.cn/Article/details/gt2zhqmhtkg.html

Ruby: u.is_a?(User)
来源：http://dali.yueranfly.top/Article/details/gt2gyhjxhyr.html

C#:   u is User
来源：http://dali.aizwys.cn/Article/details/gt2jzqhiibm.html

[G14] 数据类 / record
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2genkgtdk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gt2osebxkxk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.redwolf501.top/Article/details/gt2dsauqebq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.andypj.xyz/Article/details/gt2dahavgmf.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gt2gqkdfjag.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2torwbtne.html

Go:   type User struct { Name string; Age int }
来源：http://dali.quarkkingdee.top/Article/details/gt2vygfpfnj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.vqdsnc.cn/Article/details/gt2gbxmgpyp.html

C#:   record User(string Name, int Age);
来源：http://dali.hnxiangtu.top/Article/details/gt2uazfsnlm.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2hplfpbuw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hfpthk.cn/Article/details/gt2cewupmpg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yvedp.cn/Article/details/gt2hfrclvkm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gt2wcbvdsmn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2skkhrziq.html

Java: enum Color { RED, GREEN }
来源：http://dali.cdnleiting.top/Article/details/gt2zvfeuakw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gt2setxkdvu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gt2zubesuri.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gt2tejngjkv.html

[G16] 对象转数组 / 字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dzqhtfug.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dianchejie.cn/Article/details/gt2flsfaodi.html

PHP:  get_object_vars($obj);
来源：http://dali.dashuyun.cn/Article/details/gt2caczjvep.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umncgstm.html

TS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2bvojodjr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cheryme.top/Article/details/gt2huyvftiq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cheryme.top/Article/details/gt2wcdahdeo.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gt2zsjiaisw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cheryme.top/Article/details/gt2mqxehdvz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2qlzqvqcm.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gt2rthrotne.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2bftlhdhq.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gt2aawavxcv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rutoyfps.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uhwacfju.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gt2tmusbizz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gt2zsotlckp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2sjfzrvgl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gt2fudndwww.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2ocgrgdtu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gogol.net.cn/Article/details/gt2ludavxed.html

[H02] finally / ensure 收尾
来源：http://dali.jianghu66.top/Article/details/gt2kweweqrs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.vqdsnc.cn/Article/details/gt2tlquocvh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2qqpupnrd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2icruqvvu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2ljryqgit.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gt2pbqoowfu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sufxvd.cn/Article/details/gt2pdiipitj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hammf.cn/Article/details/gt2gfnqmyoe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2phtvtmap.html

[H03] 主动抛出异常
来源：http://dali.cheryme.top/Article/details/gt2iasprxeh.html

Py:   raise ValueError("错误信息")
来源：http://dali.sxryk.cn/Article/details/gt2mtdhzcnn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gt2nsrzkyhm.html

JS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2nmoymqqx.html

TS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2dweqejhn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2xrgyoves.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenzaomai.com/Article/details/gt2etgwymbh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sweek.top/Article/details/gt2vbzbmltc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2txufwikh.html

[H04] 自定义异常类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2htjbiuzp.html

Py:   class MyError(Exception): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wpjjdgpk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2jikatlhu.html

JS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zupdxype.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gt2fjtlxxup.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gt2lphxqnsd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dzmckllf.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenlongwang.top/Article/details/gt2aahjzpbb.html

C#:   class MyException : Exception {}
来源：http://dali.yueranfly.top/Article/details/gt2khsbasyo.html

[H05] 捕获特定类型
来源：http://dali.yongpay.top/Article/details/gt2cxpnnonu.html

Py:   except ValueError as e:
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bzjanzcs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmftjkpx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gt2lzqixqgl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2duemrjex.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuxming.cn/Article/details/gt2sxhgzjul.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2elrrlfsx.html

Ruby: rescue ArgumentError => e
来源：http://dali.mhx1999.top/Article/details/gt2xfknvbfs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuanzhike.top/Article/details/gt2efcscxwj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gt2mtnduxbg.html

Py:   value = d.get("k") or default
来源：http://dali.yanxiufei.cn/Article/details/gt2igdapukt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gt2pkqhqysm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gt2kravsnwk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gt2onxlwbre.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ihaopkko.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jlsjyb.cn/Article/details/gt2kmgxuacv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuxming.cn/Article/details/gt2yvxfyrys.html

C#:   obj?.A?.B ?? default
来源：http://dali.yanxiufei.cn/Article/details/gt2bzvluihd.html

[H07] 断言
来源：http://dali.gotoacloud.top/Article/details/gt2bpcnuyfu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xinyue.icu/Article/details/gt2gyjkkwvp.html

PHP:  assert($x > 0);
来源：http://dali.yj20258.top/Article/details/gt2lnzuelmo.html

JS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2ayqiftxh.html

TS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2vvkywqfm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.c1oappe.top/Article/details/gt2bfadbaaa.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhongyouzk.top/Article/details/gt2kknfefhb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xylfe.cn/Article/details/gt2tzbuummg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gt2wygqembu.html

[H08] 获取错误信息与堆栈
来源：http://dali.kuanghao11.cn/Article/details/gt2ijstzaka.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnxiangtu.top/Article/details/gt2fjuggulj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yongpay.top/Article/details/gt2zmmovgvz.html

JS:   e.message;  e.stack
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgpegwcf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gt2jxkfdaok.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.quarkkingdee.top/Article/details/gt2byvktxht.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gt2bxgymari.html

Ruby: e.message;  e.backtrace
来源：http://dali.havefunace.top/Article/details/gt2lbepvtjv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hywenlv.cn/Article/details/gt2csqgcpli.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xaaxwiwd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangdashe.top/Article/details/gt2jrdrzhok.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cheryme.top/Article/details/gt2uyirrpds.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtuohly.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gt2cxyrrtjj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ddcmvevo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgufenzy.top/Article/details/gt2ewukzvij.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.snrcjt.cn/Article/details/gt2zivrrrpu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gt2wvfxerjv.html

[H10] 资源自动释放
来源：http://dali.zhiwuduotai.top/Article/details/gt2vesnckhf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shuidangran.top/Article/details/gt2eahcdgfh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigfzy.top/Article/details/gt2iiioilzf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gt2lspfjuuo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gt2mtvhxska.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pycfn.com/Article/details/gt2wllmzpjb.html

Go:   defer f.Close()
来源：http://dali.dashuyun.cn/Article/details/gt2jlzbendl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnqzz.top/Article/details/gt2diezvlti.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2tszazjxh.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2pspfvulz.html

I. 正则表达式
来源：http://dali.cdnleiting.top/Article/details/gt2yxrhvgee.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2cvossyve.html

[I01] 判断是否匹配
来源：http://dali.cqqwz.cn/Article/details/gt2lbmahrle.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gt2qgxkukgn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gt2owioyjcd.html

JS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2wwgudkfk.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gt2xrbpvspu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gt2twoebqiz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nhfpcave.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gt2iusdyged.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gt2utsgkucd.html

[I02] 提取所有匹配
来源：http://dali.yuanzhike.top/Article/details/gt2azyxtnsb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gt2punukrks.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258.top/Article/details/gt2qcjxdbjb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gt2kuxauiaa.html

TS:   s.match(/\d+/g)
来源：http://dali.andypj.xyz/Article/details/gt2jjsjxmvh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqcqkfbv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cucudq.cn/Article/details/gt2cwjlfqoi.html

Ruby: s.scan(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gt2wyyyqhdi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2nqztdouk.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gt2biawvyko.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2ofjxdqrb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shzxlz.cn/Article/details/gt2gfdvjhkt.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.svipenyu.cn/Article/details/gt2pmhqojny.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxqhcndr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cghcuhwx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shuidangran.top/Article/details/gt2orwhkujm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.snrcjt.cn/Article/details/gt2aukncght.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.meibo888.top/Article/details/gt2evvdyxmk.html

[I04] 正则替换
来源：http://dali.yanxiufei.cn/Article/details/gt2vqghktei.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenlongwang.top/Article/details/gt2txahbfrv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gt2wyqhbxya.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gt2hrlmicat.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gt2nhdlvwjz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gt2whqpqxsd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jianghu66.top/Article/details/gt2hpmxrbvm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xziqi.cn/Article/details/gt2xzypbuky.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zhixingplan.top/Article/details/gt2gahqeljy.html

[I05] 按正则拆分
来源：http://dali.jlsjyb.cn/Article/details/gt2vjmpehdl.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjdmsles.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2hwzropjh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wtegtzda.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tccavvbe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnqzz.top/Article/details/gt2octjrvii.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.yuanzhike.top/Article/details/gt2oefunqws.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gt2depxwbac.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shangyingyoupin.top/Article/details/gt2adlncime.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.andypj.xyz/Article/details/gt2bumhuyou.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gogol.net.cn/Article/details/gt2lmmajout.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hysaishi.cn/Article/details/gt2lwbylujx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gotoacloud.top/Article/details/gt2dpnztixd.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gt2zjwhlqof.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gt2ncgvtabt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.kuanghao11.cn/Article/details/gt2mqtsrkrd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jiagoushi.top/Article/details/gt2sndgoycr.html


<!-- 参考信息 -->