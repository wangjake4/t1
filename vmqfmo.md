代发 wailian999

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zycfv.cn/Article/details/gtuuulvkkr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xziqi.cn/Article/details/gtfhpusdsz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.meibo888.top/Article/details/gtvfhvmaiu.html

TS:   // 同上
来源：http://dali.nanxinkj.top/Article/details/gthjukwtqn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.iojbl.cn/Article/details/gthrofrsew.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zycfv.cn/Article/details/gtdgnwhxix.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pengpengdd.cyou/Article/details/gtlpzpiaul.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cucudq.cn/Article/details/gterqrkeaz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtiwkoywps.html

G. 面向对象
来源：http://dali.bjfxy.top/Article/details/gtemiiutow.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtolprqrvq.html

[G01] 定义类
来源：http://dali.wangshuangyany.cn/Article/details/gtefnhmtpf.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gtkjqelcrk.html

PHP:  class User {}
来源：http://dali.cucudq.cn/Article/details/gtwhyscynh.html

JS:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtanbqvgts.html

TS:   class User { name: string = ""; }
来源：http://dali.redwolf501.top/Article/details/gtqlyvdaqd.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtoqlfzazq.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gtsvmgjfgm.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvlihlfi.html

C#:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gttuuevzug.html

[G02] 构造函数
来源：http://dali.yj20258.top/Article/details/gttuohimyn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gtocpfaymw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtkchrxzje.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtohokljmn.html

TS:   constructor(public name: string) {}
来源：http://dali.xinyue.icu/Article/details/gtazbhslkz.html

Java: User(String name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtrzcibojw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.andypj.xyz/Article/details/gtvbhrtuyt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.havefunace.top/Article/details/gtvzngqllk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdkqxejtf.html

[G03] 实例属性
来源：http://dali.mhx1999.top/Article/details/gtegrpxhea.html

Py:   self.name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyoujeayr.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gthilcbseg.html

JS:   this.name = "x";
来源：http://dali.fzhhl.top/Article/details/gtcqzfiuhp.html

TS:   name: string = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtqvjokjrw.html

Java: private String name;
来源：http://dali.daxiang520.top/Article/details/gtywjbirlm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.0kj1m.cn/Article/details/gtpqkvdtql.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gtnmpfryrs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hfpthk.cn/Article/details/gthfthhefh.html

[G04] 定义方法
来源：http://dali.cdnleiting.top/Article/details/gttodcmech.html

Py:   def greet(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gtahiulecu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtvmwjuhqn.html

JS:   greet() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtlinnpucl.html

TS:   greet(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtjqwztpyy.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmtwhdnln.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtbpgqwbuw.html

Ruby: def greet; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwwrvxne.html

C#:   public string Greet() => Name;
来源：http://dali.guannengcc.top/Article/details/gthpuntuzt.html

[G05] 继承
来源：http://dali.xziqi.cn/Article/details/gtlipnbrrs.html

Py:   class Admin(User): pass
来源：http://dali.guowangkeji.top/Article/details/gtaiyhkqkx.html

PHP:  class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gthyvclhlc.html

JS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtrhnktypu.html

TS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtifzolfmk.html

Java: class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtlslvezhw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.svipenyu.cn/Article/details/gtnnouyhpq.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gtynvgeksu.html

C#:   class Admin : User {}
来源：http://dali.bjfxy.top/Article/details/gtufyhhecc.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gthiygishr.html

Py:   def greet(self): return "admin"
来源：http://dali.yuanzhike.top/Article/details/gtuescsovv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtoxoqztfz.html

JS:   greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtfpdjsxof.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtdybywdam.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtxcsaipgm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yueranfly.top/Article/details/gtobcwwllc.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gtpcxixyjw.html

C#:   public override string Greet() => "admin";
来源：http://dali.jlsjyb.cn/Article/details/gthtytdxuz.html

[G07] 调用父类方法
来源：http://dali.zdqjudy.top/Article/details/gtmpgpaoce.html

Py:   super().greet()
来源：http://dali.tian-w.cn/Article/details/gtxwhibccg.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtbakwjzfh.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtdaqrtvdc.html

TS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtpicwphrz.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtgtyngqae.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.c1oappe.top/Article/details/gtvbijjobp.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gtjpepbios.html

C#:   base.Greet();
来源：http://dali.chenlongwang.top/Article/details/gtfloifyso.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gtatsmhkdc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daxiang520.top/Article/details/gtcgzhxuqs.html

PHP:  public static function f() {}
来源：http://dali.zycfv.cn/Article/details/gtxzhmmagv.html

JS:   static f() {}
来源：http://dali.zhengqikj.top/Article/details/gtrpepusyr.html

TS:   static f(): void {}
来源：http://dali.snrcjt.cn/Article/details/gtxpjxxkwz.html

Java: static void f() {}
来源：http://dali.havefunace.top/Article/details/gtncwncxnm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gtgdjmcldk.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmywmhfg.html

C#:   public static void F() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthekjjuzg.html

[G09] 接口 / 抽象类
来源：http://dali.cdnleiting.top/Article/details/gtnwpzhazy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gtgkherwiz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gtolwhdbay.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gthwlnjywi.html

TS:   interface Shape { area(): number; }
来源：http://dali.feifeiyinyue.top/Article/details/gtliazecvk.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gtwdojxjmu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gtkodlvmnc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.9152youxi.cn/Article/details/gtmtxuemip.html

C#:   interface IShape { double Area(); }
来源：http://dali.9152youxi.cn/Article/details/gttmwcztyb.html

[G10] 访问控制
来源：http://dali.xinyue.icu/Article/details/gtfwngdxlb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tianlin.xyz/Article/details/gtgdslfarn.html

PHP:  public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtgdcxmjpe.html

JS:   #private 字段；其余公开
来源：http://dali.chenzaomai.com/Article/details/gteflreejy.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtvcrdvyjp.html

Java: public / protected / private / 默认包级
来源：http://dali.jiagoushi.top/Article/details/gtdefltihh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgfzy.top/Article/details/gtqxrekufc.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtokvbjvig.html

C#:   public / protected / private / internal
来源：http://dali.guowangkeji.top/Article/details/gtfwyniaqu.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gtgxzeiljx.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gtsorarbaf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtrjeitrid.html

JS:   get name() { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gtiyuqgpwu.html

TS:   get name(): string { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gtzgppbbbf.html

Java: public String getName() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtcisfhpiv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtfnuujcnu.html

Ruby: attr_accessor :name
来源：http://dali.zhongyouzk.top/Article/details/gttcnnfmpb.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsyqkcjvp.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gtzdknqvxp.html

Py:   def __str__(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtrffkwzgu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gthduncbjl.html

JS:   toString() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtnoumfwbx.html

TS:   toString(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtulpmjxjr.html

Java: @Override public String toString() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtojpdntbq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtrhczczoq.html

Ruby: def to_s; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gtxvhrzurj.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gtgjgcqrcf.html

[G13] 判断对象类型
来源：http://dali.chenzaomai.com/Article/details/gtjgsnqkes.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gtdkllyazb.html

PHP:  $u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtsktbucbo.html

JS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtqztyxkjo.html

TS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gthpvmhhxy.html

Java: u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtydrengct.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tian-w.cn/Article/details/gtndjyxyrc.html

Ruby: u.is_a?(User)
来源：http://dali.ybcxt.top/Article/details/gtjfxcqsfq.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gtdiitlxsa.html

[G14] 数据类 / record
来源：http://dali.jianghu66.top/Article/details/gtrnkmkxsy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gtkbxtsnpb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gtixdchjal.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jyoumei.cn/Article/details/gtscgrxetw.html

TS:   type User = { name: string; age: number };
来源：http://dali.cucudq.cn/Article/details/gthctracup.html

Java: record User(String name, int age) {}
来源：http://dali.yongpay.top/Article/details/gtgsjsauha.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gtpbyjwxap.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gotoacloud.top/Article/details/gttazyiwtc.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gtfeejkkmx.html

[G15] 枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtfytbcder.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gtazutcxfm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.9152youxi.cn/Article/details/gtbxtnuryn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovbmgvds.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwusdrgk.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gtnsowizmu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gtkpkfmsxj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gtkszdkyez.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gttcfgzjtf.html

[G16] 对象转数组 / 字典
来源：http://dali.cqqwz.cn/Article/details/gteevgmjhp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guannengcc.top/Article/details/gtorkqbihk.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gtxpsqpjsq.html

JS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtbyigmsot.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtzoxlrhfm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ppjwa.cn/Article/details/gtppxosmyw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dashuyun.cn/Article/details/gtzodmzpjq.html

Ruby: obj.instance_variables
来源：http://dali.zhongyouzk.top/Article/details/gtxlxpidgr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258.top/Article/details/gtmvoeghgo.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtppefftjn.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gtmmznvlne.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtxyxpksje.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gtagvakqcw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gtuzuguemm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.kuanghao11.cn/Article/details/gtxrfdzwlj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtojqxiics.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtusqkibfu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shangyingyoupin.top/Article/details/gtyhkaiany.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sufxvd.cn/Article/details/gtduzcaaea.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.feifeiyinyue.top/Article/details/gtgmwtvomk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gaohongyu789.top/Article/details/gtfzxaunjm.html

[H02] finally / ensure 收尾
来源：http://dali.zhixingplan.top/Article/details/gtimbcugye.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ppjwa.cn/Article/details/gtxwwyuuyn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtieowqzdk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtkyngholp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtpdcmlbhc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gthbxgcyqp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cqqwz.cn/Article/details/gtblbmyocy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gtsprlutiz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtighwnfya.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gtyecxgyqn.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gtdrpktzrc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcstonlqb.html

JS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtgytwdhpp.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtmryewgog.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtvexmgtjr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hammf.cn/Article/details/gtevhkrjqm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cashguo.top/Article/details/gtelviolap.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtqvgmmbyd.html

[H04] 自定义异常类型
来源：http://dali.nanxuanxn.top/Article/details/gtpxvvfjnq.html

Py:   class MyError(Exception): pass
来源：http://dali.wangdashe.top/Article/details/gtpmikqgrh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gtibolyoct.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gthcthrypq.html

TS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtgjgxhzqk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gtqcvfjqpb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gtxnojkzen.html

Ruby: class MyError < StandardError; end
来源：http://dali.sufxvd.cn/Article/details/gtzzzaunrj.html

C#:   class MyException : Exception {}
来源：http://dali.gaohongyu789.top/Article/details/gtktyhoswr.html

[H05] 捕获特定类型
来源：http://dali.haohaochexian.top/Article/details/gtpfwwknwy.html

Py:   except ValueError as e:
来源：http://dali.yj20258.top/Article/details/gtqvqtfgmh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yonumen.top/Article/details/gtpsiwfhwf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtanwzrpsw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gtfldcutbn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gtlleponzw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.kuanghao11.cn/Article/details/gtimjgxwnv.html

Ruby: rescue ArgumentError => e
来源：http://dali.yonumen.top/Article/details/gtjzquksbt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jyoumei.cn/Article/details/gtzxvrtfbj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cashguo.top/Article/details/gtwaaerusc.html

Py:   value = d.get("k") or default
来源：http://dali.chenzaomai.com/Article/details/gtrmrlzmms.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gttzjvozua.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbljjyyzq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzmocnpl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hywenlv.cn/Article/details/gtvkwfqayn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gtmrnxzyeg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gotoacloud.top/Article/details/gtpaffsrmg.html

C#:   obj?.A?.B ?? default
来源：http://dali.gzhubu.top/Article/details/gtsfpbevxc.html

[H07] 断言
来源：http://dali.hnqzz.top/Article/details/gtilejpugl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgfzy.top/Article/details/gtmfqzsfik.html

PHP:  assert($x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtmnlnists.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtwnlbxmse.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtseswhrms.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gtmqhruapi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxuanxn.top/Article/details/gtuzgrokyx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shangyingyoupin.top/Article/details/gtzgpewhyj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtawlgaqnx.html

[H08] 获取错误信息与堆栈
来源：http://dali.9152youxi.cn/Article/details/gtivnlhzca.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cheryme.top/Article/details/gtpqmpyajv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daria6918.cn/Article/details/gtcsvyneed.html

JS:   e.message;  e.stack
来源：http://dali.fengsongda.top/Article/details/gtgnimjxjk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.andypj.xyz/Article/details/gtofuudqlh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gtpsollqap.html

Go:   err.Error()
来源：http://dali.cqqwz.cn/Article/details/gtongnudkj.html

Ruby: e.message;  e.backtrace
来源：http://dali.yongpay.top/Article/details/gtrvheniwm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yueranfly.top/Article/details/gtsnztxcrq.html

[H09] 带错误码的异常
来源：http://dali.cqqwz.cn/Article/details/gtktduzikm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gtvmdojcsi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gogol.net.cn/Article/details/gtpqmiqzqr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhoulong.xyz/Article/details/gtzueybiwa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dashuyun.cn/Article/details/gtmgwduclg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gzhubu.top/Article/details/gtmxdlssrh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gtosqjvdfn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gtyxlritpt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hammf.cn/Article/details/gtjfkxoevh.html

[H10] 资源自动释放
来源：http://dali.yj202588.top/Article/details/gtouqumbxl.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cucudq.cn/Article/details/gtepazxnbp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sysykeji.top/Article/details/gthdbkbujp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yueranfly.top/Article/details/gtsivfbdey.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gttayahwlg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jqgfzy.top/Article/details/gtkuucjbaz.html

Go:   defer f.Close()
来源：http://dali.zhoulong.xyz/Article/details/gtbyktkwkp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxinkj.top/Article/details/gtbrzwhjrp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtjwwygrqd.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtgmphgkvo.html

I. 正则表达式
来源：http://dali.tanke756.top/Article/details/gtuzeotdwb.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthczqzcn.html

[I01] 判断是否匹配
来源：http://dali.tianlin.xyz/Article/details/gtoefiokpg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgcgrpne.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xylfe.cn/Article/details/gtccgpxfgi.html

JS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtmagonvuk.html

TS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gthrbmjzts.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zdqjudy.top/Article/details/gtawoyehqs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gotoacloud.top/Article/details/gtbihkxzbc.html

Ruby: s.match?(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gtvmdbwmfr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtaleahtyi.html

[I02] 提取所有匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtpxxhwqto.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gtxygdiahq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenlongwang.top/Article/details/gtjebynobt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuanzhike.top/Article/details/gtjfyrjhae.html

TS:   s.match(/\d+/g)
来源：http://dali.c1oappe.top/Article/details/gterqxivcu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gtownodegd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.andypj.xyz/Article/details/gteodoicvj.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtrgphnzuk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtubmomjmv.html

[I03] 提取捕获分组
来源：http://dali.yanxiufei.cn/Article/details/gthasjvdpg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cucudq.cn/Article/details/gtckuavzrs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cashguo.top/Article/details/gtfevpbxwx.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgfzy.top/Article/details/gtaulkmpir.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigfzy.top/Article/details/gtulgqydhg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shangyingyoupin.top/Article/details/gtlniiiazc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhiwuduotai.top/Article/details/gtcjxqwmaj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aibaodan.cn/Article/details/gtoffvksev.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ivvv.top/Article/details/gtpumaauvk.html

[I04] 正则替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gthidenwon.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258.top/Article/details/gtisuhquic.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.aizwys.cn/Article/details/gtgekfujmx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gtjsrnjszo.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gtzqttjimp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gtymynbgts.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yanxiufei.cn/Article/details/gttztrawfp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpzteqnb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shangyingyoupin.top/Article/details/gtpmgiyevy.html

[I05] 按正则拆分
来源：http://dali.zhixingplan.top/Article/details/gtnpbtfqeb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.smart0.xyz/Article/details/gtgvrrobdp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtzftybdnp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtwxzdxytt.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtksuukris.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jianghu66.top/Article/details/gthjjkmbin.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shuidangran.top/Article/details/gtdazfluyj.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtwamiwfwb.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.fengsongda.top/Article/details/gtovjrygqz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gtzmvxxpfp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gotoacloud.top/Article/details/gtmjitaogh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yj20258.top/Article/details/gteckyetqh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ivvv.top/Article/details/gtnjphsdxu.html


<!-- 参考信息 -->