代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daria6918.cn/Article/details/gtnanoists.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtuqlmaqsw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gtngcduidq.html

[F12] CSV 读写
来源：http://dali.hysaishi.cn/Article/details/gtkicbtvcy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.andypj.xyz/Article/details/gtsebhiicl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gtcmqhlxnl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cqqwz.cn/Article/details/gtkzabrknz.html

TS:   // 同上
来源：http://dali.hfpthk.cn/Article/details/gtxkamibuu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gtivaptoah.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnqzz.top/Article/details/gtluzdwtsn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fzhhl.top/Article/details/gtdtztnmcd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gtyrvnpioy.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtrqmkjyff.html

G. 面向对象
来源：http://dali.gzhubu.top/Article/details/gtwdngycfn.html

================================================================================
来源：http://dali.sweek.top/Article/details/gthekppwnf.html

[G01] 定义类
来源：http://dali.cashguo.top/Article/details/gtubmnlman.html

Py:   class User: pass
来源：http://dali.yongpay.top/Article/details/gtrjlzynrt.html

PHP:  class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtnxoaxfnj.html

JS:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtisymgvwr.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gtiiehusnw.html

Java: class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwyujcki.html

Go:   type User struct { Name string }
来源：http://dali.redwolf501.top/Article/details/gtqpzksiwj.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gtshhpknrv.html

C#:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtbbavzbht.html

[G02] 构造函数
来源：http://dali.havefunace.top/Article/details/gthuycecgx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdcvhnpa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtakjvpmfb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gttyqcerck.html

TS:   constructor(public name: string) {}
来源：http://dali.guowangkeji.top/Article/details/gtghpreifo.html

Java: User(String name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpvgnrkoi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yanxiufei.cn/Article/details/gtrsqptnvq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.c1oappe.top/Article/details/gtzkhpmwbr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.iojbl.cn/Article/details/gtbgcnoges.html

[G03] 实例属性
来源：http://dali.ehwqpu.com/Article/details/gtotquyuwi.html

Py:   self.name = "x"
来源：http://dali.hfpthk.cn/Article/details/gtoqhkioaa.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gtickiynpp.html

JS:   this.name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtqajqdxrb.html

TS:   name: string = "x";
来源：http://dali.zhengqikj.top/Article/details/gtxudvizbz.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gtmdrajsyg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gtniymstbc.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjuuvolk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gtrufmuuym.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gtezpwkubd.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtswgptcid.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtybgeuoai.html

JS:   greet() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gteohxjzgh.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrlcgocp.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtqsfkntzd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtrwfgrmlq.html

Ruby: def greet; @name; end
来源：http://dali.yuanzhike.top/Article/details/gtkgbxdlil.html

C#:   public string Greet() => Name;
来源：http://dali.cucudq.cn/Article/details/gtseomkkvn.html

[G05] 继承
来源：http://dali.jinqigufen.top/Article/details/gtxpeevzdt.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gthwykpqia.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqbjmrxc.html

JS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gthwkvdgcl.html

TS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtjsnpdsqi.html

Java: class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtockyaeil.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbxouvyi.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gtdqtxdepa.html

C#:   class Admin : User {}
来源：http://dali.316326.xyz/Article/details/gtvnhxasqi.html

[G06] 重写方法
来源：http://dali.xylfe.cn/Article/details/gtmlxpkdls.html

Py:   def greet(self): return "admin"
来源：http://dali.sweek.top/Article/details/gtrmfwsjss.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtvlnitgxy.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqcgochop.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtcsewnwjx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtxralhxuz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hammf.cn/Article/details/gtfjdjunyb.html

Ruby: def greet; "admin"; end
来源：http://dali.0kj1m.cn/Article/details/gtpsjedaek.html

C#:   public override string Greet() => "admin";
来源：http://dali.jiagoushi.top/Article/details/gtvilvrill.html

[G07] 调用父类方法
来源：http://dali.pengpengdd.cyou/Article/details/gtuwpqpriw.html

Py:   super().greet()
来源：http://dali.cqqwz.cn/Article/details/gtlsvnpegf.html

PHP:  parent::greet();
来源：http://dali.yuxming.cn/Article/details/gtkxxydxfk.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtknrrnrsa.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtdlrvipkr.html

Java: super.greet();
来源：http://dali.fzhhl.top/Article/details/gtpwkaekqz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daxiang520.top/Article/details/gtxynwiojo.html

Ruby: super
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxkeinfc.html

C#:   base.Greet();
来源：http://dali.shzxlz.cn/Article/details/gtktplworu.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtsunuwvim.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nwbrower.top/Article/details/gttlxiycpi.html

PHP:  public static function f() {}
来源：http://dali.sufxvd.cn/Article/details/gtxjrqljic.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gtcwxdwner.html

TS:   static f(): void {}
来源：http://dali.316326.xyz/Article/details/gtiqllukfn.html

Java: static void f() {}
来源：http://dali.ivvv.top/Article/details/gtgjobgird.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.haohaochexian.top/Article/details/gtobnqtilp.html

Ruby: def self.f; end
来源：http://dali.0kj1m.cn/Article/details/gtjuuiltuj.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtftpcumos.html

[G09] 接口 / 抽象类
来源：http://dali.birdmap.top/Article/details/gtdnqhijyo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhengqikj.top/Article/details/gtnwnsxlxh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.c1oappe.top/Article/details/gtvitxlcvl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cqqwz.cn/Article/details/gtbmniqhvl.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnxiangtu.top/Article/details/gtdunkrjlb.html

Java: interface Shape { double area(); }
来源：http://dali.nanxinkj.top/Article/details/gtkwqsltab.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nwbrower.top/Article/details/gtueipaikr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.c1oappe.top/Article/details/gtmeixpfzt.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtjbgemyzy.html

[G10] 访问控制
来源：http://dali.zhoulong.xyz/Article/details/gtfywrocpc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guowangkeji.top/Article/details/gtxbcawlgc.html

PHP:  public / protected / private
来源：http://dali.meibo888.top/Article/details/gtvdenffud.html

JS:   #private 字段；其余公开
来源：http://dali.hfpthk.cn/Article/details/gtjwedxhza.html

TS:   public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtatlpvpak.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gtkwdzmdnl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.havefunace.top/Article/details/gtepqcuykr.html

Ruby: public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtbmpmbxpv.html

C#:   public / protected / private / internal
来源：http://dali.yonumen.top/Article/details/gtpnzijqmh.html

[G11] getter / setter
来源：http://dali.tianlin.xyz/Article/details/gtsmracksw.html

Py:   @property 与 @x.setter
来源：http://dali.snrcjt.cn/Article/details/gtgwonsbzk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtkwgkiiqc.html

JS:   get name() { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcualhyhz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtrgypcidu.html

Java: public String getName() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtrcbutbyk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gttzuarrbs.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gtrtoimnol.html

C#:   public string Name { get; set; }
来源：http://dali.cdnleiting.top/Article/details/gtfzqdyzwz.html

[G12] 对象转字符串
来源：http://dali.cheryme.top/Article/details/gtpwectygu.html

Py:   def __str__(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppjlhpbn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtetqqfism.html

JS:   toString() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gteaahmkho.html

TS:   toString(): string { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtonzftbru.html

Java: @Override public String toString() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtiiiwunae.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtzibrtiok.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtsyygniqs.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gtezfxhfkg.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gtujieqaxt.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gtmtkztldp.html

PHP:  $u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtrfdaobhp.html

JS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gthpjdessg.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtvuttobym.html

Java: u instanceof User
来源：http://dali.pycfn.com/Article/details/gtebvzorfs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gotoacloud.top/Article/details/gtcnyxbiqx.html

Ruby: u.is_a?(User)
来源：http://dali.yuanzhike.top/Article/details/gtfqkpxtlt.html

C#:   u is User
来源：http://dali.xylfe.cn/Article/details/gtrlkoycch.html

[G14] 数据类 / record
来源：http://dali.sxryk.cn/Article/details/gtxmemssza.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gtubhaahnw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gtropfajrc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guowangkeji.top/Article/details/gtoeweqgwu.html

TS:   type User = { name: string; age: number };
来源：http://dali.dianchejie.cn/Article/details/gtrxdrjpho.html

Java: record User(String name, int age) {}
来源：http://dali.zycfv.cn/Article/details/gtrfbhozqa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fzhhl.top/Article/details/gtthjcmrhz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ppjwa.cn/Article/details/gtjxcgynij.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gthvtrqgmv.html

[G15] 枚举
来源：http://dali.zhongyouzk.top/Article/details/gtezuaadkk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yangfankeji.com/Article/details/gtjqphiifq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbbbimpeu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yonumen.top/Article/details/gtejeoxbyd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtxuzdbuoc.html

Java: enum Color { RED, GREEN }
来源：http://dali.cqqwz.cn/Article/details/gtorjgdcap.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gtwjpjyksh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yanxiufei.cn/Article/details/gtdejfbcye.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gtvgnwbxus.html

[G16] 对象转数组 / 字典
来源：http://dali.zhongyouzk.top/Article/details/gtkqoqnxxb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hongshengwenyu.top/Article/details/gtmpzbkyuz.html

PHP:  get_object_vars($obj);
来源：http://dali.yanxiufei.cn/Article/details/gtflexdxfm.html

JS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gthxtapkuj.html

TS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gtjiauwcwv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cashguo.top/Article/details/gttzrkzbue.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.9152youxi.cn/Article/details/gtcabbhxqj.html

Ruby: obj.instance_variables
来源：http://dali.zhixingplan.top/Article/details/gtsgdlkupm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtvbykbdsb.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtyvpohxox.html

H. 异常与错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmgmtyui.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtcitlrrbx.html

[H01] try / catch 基础
来源：http://dali.tanke756.top/Article/details/gtwrntezad.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgfzy.top/Article/details/gtbopsbfpb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tanke756.top/Article/details/gtkonyvqam.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gtyswrracr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtuxgtuuey.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pycfn.com/Article/details/gtiiupndpd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hongshengwenyu.top/Article/details/gtecesaamo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gtnjkrjnkw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.redwolf501.top/Article/details/gtwlnrnzyt.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtwozsinqq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cashguo.top/Article/details/gtuyorkqoe.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtmwmkvqxy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtsvuqufhp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtatddtpxg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtwmbpleab.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangdashe.top/Article/details/gtwfzummhh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sxryk.cn/Article/details/gtvovcwjls.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtqchbhitm.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gtbhrvwcwd.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigfzy.top/Article/details/gtcylsgmtc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gttxyhgyne.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtblwbwoki.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikhkmsjg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtpqupinas.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gtnqvkirtv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmfvegxi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtaontfeqv.html

[H04] 自定义异常类型
来源：http://dali.cheryme.top/Article/details/gtrmethyot.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gtfarwwewi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gttsyrswlg.html

JS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gtpohyygdl.html

TS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gtqflfhavv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gtyrwmvgzz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsmrpzxq.html

Ruby: class MyError < StandardError; end
来源：http://dali.andypj.xyz/Article/details/gttuttmqnu.html

C#:   class MyException : Exception {}
来源：http://dali.nanxuanxn.top/Article/details/gtivlsgidc.html

[H05] 捕获特定类型
来源：http://dali.sxryk.cn/Article/details/gtwsyqoyyi.html

Py:   except ValueError as e:
来源：http://dali.gaohongyu789.top/Article/details/gtvfvnrhtr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258.top/Article/details/gtmkzoyjbg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtcavgndwi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gtbgzadngr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jyoumei.cn/Article/details/gtaoqpnxte.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gtfdnikfqf.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gtdiljisio.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ybcxt.top/Article/details/gtzxqveaty.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenjidiqi.icu/Article/details/gthnknphcm.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtlqgxogfz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkxyhonh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtsevozceu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gtothtqilj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cdnleiting.top/Article/details/gtdjflszhn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigufen.top/Article/details/gtbhwogboe.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangdashe.top/Article/details/gtqxryezxb.html

C#:   obj?.A?.B ?? default
来源：http://dali.9152youxi.cn/Article/details/gtwdnfqnrj.html

[H07] 断言
来源：http://dali.meibo888.top/Article/details/gtkfhxmbsi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zycfv.cn/Article/details/gtljablexe.html

PHP:  assert($x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtslwvwart.html

JS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtscydwgxy.html

TS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtziymrrkq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tanke756.top/Article/details/gtdgnssqzu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gtvhvmkhjm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sysykeji.top/Article/details/gtejhyjsmi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gthutbccbu.html

[H08] 获取错误信息与堆栈
来源：http://dali.hfpthk.cn/Article/details/gtcsdekwcp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.c1oappe.top/Article/details/gtovrjbixc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aizwys.cn/Article/details/gtvbkpuasv.html

JS:   e.message;  e.stack
来源：http://dali.andypj.xyz/Article/details/gtzwfwnaxe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.0kj1m.cn/Article/details/gturjrielm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmswggxhy.html

Go:   err.Error()
来源：http://dali.fzhhl.top/Article/details/gtmtrsbkvu.html

Ruby: e.message;  e.backtrace
来源：http://dali.yonumen.top/Article/details/gtnnbhmwjn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsikwlepl.html

[H09] 带错误码的异常
来源：http://dali.haohaochexian.top/Article/details/gtaoiaqmwx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigfzy.top/Article/details/gtptduponw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daria6918.cn/Article/details/gtxajjizfw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ybcxt.top/Article/details/gtwbgznqva.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xylfe.cn/Article/details/gtukbpwhwy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cheryme.top/Article/details/gtftbbgrda.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sysykeji.top/Article/details/gtmwitntqo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenjidiqi.icu/Article/details/gtvpzsbsdb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gtxlsgxhxc.html

[H10] 资源自动释放
来源：http://dali.wangdashe.top/Article/details/gtbvrfyliv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guannengcc.top/Article/details/gtrdqqhooe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dashuyun.cn/Article/details/gtpvnkqcpm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtnbzznsie.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtwlrrcsat.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cqqwz.cn/Article/details/gtdljmcspx.html

Go:   defer f.Close()
来源：http://dali.zhixingplan.top/Article/details/gtkseajqgs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gtqmgvhsjt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtxycqkwyn.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdoxrgcih.html

I. 正则表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtelbpwbxr.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gttrsiwtvs.html

[I01] 判断是否匹配
来源：http://dali.zycfv.cn/Article/details/gtavtgpewn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtafaopwyo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ivvv.top/Article/details/gthphmbqti.html

JS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gtwhuzersu.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtvfriobfv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gtqtbfixfd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gaohongyu789.top/Article/details/gtenburjce.html

Ruby: s.match?(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gtvrlkhumr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xziqi.cn/Article/details/gtlzdchznm.html

[I02] 提取所有匹配
来源：http://dali.cdnleiting.top/Article/details/gtpgombhpo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtubouqkim.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gaohongyu789.top/Article/details/gtqjprzhyx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenlongwang.top/Article/details/gtgxvgewtf.html

TS:   s.match(/\d+/g)
来源：http://dali.zdqjudy.top/Article/details/gtzofqwrrn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuanzhike.top/Article/details/gtkkkflozr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yangfankeji.com/Article/details/gtztlzujmd.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtlvyifyfv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtsqetmsxv.html

[I03] 提取捕获分组
来源：http://dali.yj20258888.top/Article/details/gtuayrpybk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cucudq.cn/Article/details/gtwosvdgri.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gtqpseaouh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gtcueghuep.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.redwolf501.top/Article/details/gtmblfsapi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guowangkeji.top/Article/details/gtngffysoe.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yangfankeji.com/Article/details/gtkaaroedc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gtmwdlbskw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.c1oappe.top/Article/details/gtogkyyztx.html

[I04] 正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gtwznpzlej.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jqgfzy.top/Article/details/gttwbjhwbg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gtfezljyut.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtxhvnrngd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gtcqioijkj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gtfdtsejhl.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.andypj.xyz/Article/details/gtjvlyoowp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shuidangran.top/Article/details/gtneuvzsps.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.birdmap.top/Article/details/gtynwdfuog.html

[I05] 按正则拆分
来源：http://dali.yvedp.cn/Article/details/gtkqsvivbs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jlsjyb.cn/Article/details/gtfpwdotwc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrztymjv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cucudq.cn/Article/details/gtjozwnlad.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtpghchwvu.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ybcxt.top/Article/details/gtxwtgtgrq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nwbrower.top/Article/details/gtbdjfpkwi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtsulirzgq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.iojbl.cn/Article/details/gtfxuglmhi.html


<!-- 参考信息 -->