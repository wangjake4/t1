代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zycfv.cn/Article/details/gtvpitbfjg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtsgyhdgcv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tanke756.top/Article/details/gteyitqxnv.html

[F12] CSV 读写
来源：http://dali.gaohongyu789.top/Article/details/gtbjzrjrxh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yanxiufei.cn/Article/details/gtztexmudq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxawuuvu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hysaishi.cn/Article/details/gtyunuqirc.html

TS:   // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtgqkuwace.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ydzc1.top/Article/details/gtznldnznq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.mhx1999.top/Article/details/gtfwqabrmj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shzxlz.cn/Article/details/gtrcjdanwd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.9152youxi.cn/Article/details/gtytoenzgq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtxszgnvku.html

G. 面向对象
来源：http://dali.quarkkingdee.top/Article/details/gtqfjbhppb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthuwfvhib.html

[G01] 定义类
来源：http://dali.9152youxi.cn/Article/details/gtyskdpvqi.html

Py:   class User: pass
来源：http://dali.gaohongyu789.top/Article/details/gtocvgjahx.html

PHP:  class User {}
来源：http://dali.gotoacloud.top/Article/details/gtleelslao.html

JS:   class User {}
来源：http://dali.c1oappe.top/Article/details/gtajbecgsf.html

TS:   class User { name: string = ""; }
来源：http://dali.ybcxt.top/Article/details/gtpgmrdflh.html

Java: class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtfpdecsoz.html

Go:   type User struct { Name string }
来源：http://dali.quarkkingdee.top/Article/details/gtlbpgckaz.html

Ruby: class User; end
来源：http://dali.c1oappe.top/Article/details/gtvzavfape.html

C#:   class User {}
来源：http://dali.xinyue.icu/Article/details/gtixabufjm.html

[G02] 构造函数
来源：http://dali.xuanzx.com/Article/details/gtcpdkncgc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gtgixscbst.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnxiangtu.top/Article/details/gtjeghenpg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtvwndfvpk.html

TS:   constructor(public name: string) {}
来源：http://dali.yanxiufei.cn/Article/details/gtogyocrdt.html

Java: User(String name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtassmhacu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gtdljunvyw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtpeiwmsec.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cheryme.top/Article/details/gtpvjxeccd.html

[G03] 实例属性
来源：http://dali.yongpay.top/Article/details/gtyinvthiy.html

Py:   self.name = "x"
来源：http://dali.havefunace.top/Article/details/gthgrzstyu.html

PHP:  public string $name = "x";
来源：http://dali.daria6918.cn/Article/details/gtmwrjzgwe.html

JS:   this.name = "x";
来源：http://dali.redwolf501.top/Article/details/gtnjvbcmwi.html

TS:   name: string = "x";
来源：http://dali.ehwqpu.com/Article/details/gtzwmrkdkw.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gtvvpmhduu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtcybqoezp.html

Ruby: @name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gtfatwbzni.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.birdmap.top/Article/details/gtacujpexs.html

[G04] 定义方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqveagxz.html

Py:   def greet(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtengmmyzc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtwmcjcuqp.html

JS:   greet() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtjupsthgs.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmodsptbe.html

Java: String greet() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtgdjexucm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtjhmoyeuc.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtmdcyqjft.html

C#:   public string Greet() => Name;
来源：http://dali.ydzc1.top/Article/details/gtrtfqxwhg.html

[G05] 继承
来源：http://dali.tianlin.xyz/Article/details/gtkdmxukhq.html

Py:   class Admin(User): pass
来源：http://dali.ehwqpu.com/Article/details/gteybbhexh.html

PHP:  class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtpoekguug.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtowvvuzbl.html

TS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtvvfcxdsa.html

Java: class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtwfmyaqfw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gtcrbehjon.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gtagcbuuzt.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gtvkybmckl.html

[G06] 重写方法
来源：http://dali.zhoulong.xyz/Article/details/gtafeuwjxk.html

Py:   def greet(self): return "admin"
来源：http://dali.sxryk.cn/Article/details/gtrwcihmnh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtwnpvoewm.html

JS:   greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtdzvntfye.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazskirsj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gtmmionbad.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gteknyggqn.html

Ruby: def greet; "admin"; end
来源：http://dali.dashuyun.cn/Article/details/gtuxecuhhn.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgufenzy.top/Article/details/gtanoqqgxq.html

[G07] 调用父类方法
来源：http://dali.cqqwz.cn/Article/details/gtqnwqxilt.html

Py:   super().greet()
来源：http://dali.vqdsnc.cn/Article/details/gtkehaywtv.html

PHP:  parent::greet();
来源：http://dali.fengsongda.top/Article/details/gtyirmxzyh.html

JS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtwpfpqjcs.html

TS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtqpvtmvaq.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtqtewlbwc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhiwuduotai.top/Article/details/gtikoumnuq.html

Ruby: super
来源：http://dali.sufxvd.cn/Article/details/gtnczbtmiy.html

C#:   base.Greet();
来源：http://dali.guannengcc.top/Article/details/gtnfnaitny.html

[G08] 静态方法与属性
来源：http://dali.ehwqpu.com/Article/details/gteyhnrdmi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jianghu66.top/Article/details/gtcslfdlep.html

PHP:  public static function f() {}
来源：http://dali.aizwys.cn/Article/details/gtllovavgd.html

JS:   static f() {}
来源：http://dali.cqqwz.cn/Article/details/gtrnrqjbpg.html

TS:   static f(): void {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyuoacnk.html

Java: static void f() {}
来源：http://dali.tianlin.xyz/Article/details/gtsonqquyi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shuidangran.top/Article/details/gtcyrpbrzs.html

Ruby: def self.f; end
来源：http://dali.jiagoushi.top/Article/details/gthvuixtfs.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gtgzbojjty.html

[G09] 接口 / 抽象类
来源：http://dali.xylfe.cn/Article/details/gtsylrqtxu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptrnaedc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gotoacloud.top/Article/details/gtrqyalilv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yangfankeji.com/Article/details/gtunmdapkq.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gtchibavdf.html

Java: interface Shape { double area(); }
来源：http://dali.yuxming.cn/Article/details/gtvsprtfqt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gtbpwtsdgh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.haohaochexian.top/Article/details/gtggiivmwi.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtkmjotjmf.html

[G10] 访问控制
来源：http://dali.daria6918.cn/Article/details/gtwbgfepwk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yongpay.top/Article/details/gtjzitvlzi.html

PHP:  public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtjqbouuum.html

JS:   #private 字段；其余公开
来源：http://dali.yueranfly.top/Article/details/gthdseovsc.html

TS:   public / protected / private
来源：http://dali.yj202588.top/Article/details/gtwjvwgmyp.html

Java: public / protected / private / 默认包级
来源：http://dali.ybcxt.top/Article/details/gtconikijn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgufenzy.top/Article/details/gtzdagubqd.html

Ruby: public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtynehnswn.html

C#:   public / protected / private / internal
来源：http://dali.shangyingyoupin.top/Article/details/gteojibxyo.html

[G11] getter / setter
来源：http://dali.zhijiandao.cn/Article/details/gtlabovunk.html

Py:   @property 与 @x.setter
来源：http://dali.hysaishi.cn/Article/details/gtmziculoc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtmerjumkf.html

JS:   get name() { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzwqufxqw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtrhasyaad.html

Java: public String getName() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzretsmcf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtbjbvxmrd.html

Ruby: attr_accessor :name
来源：http://dali.chenzaomai.com/Article/details/gthuysasyz.html

C#:   public string Name { get; set; }
来源：http://dali.yonumen.top/Article/details/gtxvvpkewx.html

[G12] 对象转字符串
来源：http://dali.dashuyun.cn/Article/details/gtxvhyupfg.html

Py:   def __str__(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtfqbmstnj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtywgkxene.html

JS:   toString() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtnibqsivd.html

TS:   toString(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtubebkdvh.html

Java: @Override public String toString() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gteznxstpr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtykbnbqbs.html

Ruby: def to_s; @name; end
来源：http://dali.havefunace.top/Article/details/gtqdwluslj.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gtoorluckc.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gthxssskjy.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gtmihgqpeb.html

PHP:  $u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtgjmvwzqz.html

JS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gthpyrvqif.html

TS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gtcqjfqqqf.html

Java: u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtoprapjra.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shzxlz.cn/Article/details/gtndnwymve.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gtlgwvprcn.html

C#:   u is User
来源：http://dali.shzxlz.cn/Article/details/gtedqezkam.html

[G14] 数据类 / record
来源：http://dali.yonumen.top/Article/details/gtkciefyfm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shuidangran.top/Article/details/gtypdthzjy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pengpengdd.cyou/Article/details/gtzrlmlfoo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhongyouzk.top/Article/details/gtpalbamap.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gttisqfvqp.html

Java: record User(String name, int age) {}
来源：http://dali.yuxming.cn/Article/details/gtqojjtxir.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sxryk.cn/Article/details/gtgtmkhfar.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258888.top/Article/details/gtdvegrctn.html

C#:   record User(string Name, int Age);
来源：http://dali.yuanzhike.top/Article/details/gtkdlbaqbx.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gtjzovpntv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cheryme.top/Article/details/gtnhcbjadf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtivrlewqy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cheryme.top/Article/details/gtmtrcvwrj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gthwyyuzkr.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gtsrpmsxbb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yangfankeji.com/Article/details/gtyrytymyf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sxryk.cn/Article/details/gtfqlirtku.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gtvrgpmgml.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gteysujavw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gtkwcupmtf.html

PHP:  get_object_vars($obj);
来源：http://dali.jyoumei.cn/Article/details/gtfmoptmbf.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtppruzmtm.html

TS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtxuxydaec.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ivvv.top/Article/details/gtlgxjucro.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.meibo888.top/Article/details/gtqihtzrva.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorcooyxc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtlongiqem.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtdzxmbbsc.html

H. 异常与错误处理
来源：http://dali.dianchejie.cn/Article/details/gtyncwkkin.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtzkbzpfzt.html

[H01] try / catch 基础
来源：http://dali.cucudq.cn/Article/details/gtugkpiket.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ehwqpu.com/Article/details/gtqigfgqlt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gtppzwdxqr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtxlaifula.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtnsmwxnqz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.havefunace.top/Article/details/gtzatbwmin.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guowangkeji.top/Article/details/gtecblahwz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fzhhl.top/Article/details/gtqizrclvs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuanzhike.top/Article/details/gtmrjqaoiu.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gtsuqjmvkr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gtdovfbbol.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtfhlecodv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtuodjmtro.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtjvggjjwu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtiuphbrjm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhoulong.xyz/Article/details/gtrggbjfqx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gogol.net.cn/Article/details/gtizmvskak.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtuvfijwvm.html

[H03] 主动抛出异常
来源：http://dali.sxryk.cn/Article/details/gthwjwrshm.html

Py:   raise ValueError("错误信息")
来源：http://dali.ydzc1.top/Article/details/gtxrajkkhi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gthqruhimp.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtdrbikgse.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gtqamlftdt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtcexybjbq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwadmthr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhiwuduotai.top/Article/details/gtaavtoyos.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtrnmogqun.html

[H04] 自定义异常类型
来源：http://dali.iojbl.cn/Article/details/gtjcwxbcvl.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gtfxllonop.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtchvatlyp.html

JS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gtilffbfhi.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtovmzgdyo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtnwcvrxtn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gtdtmiaclr.html

Ruby: class MyError < StandardError; end
来源：http://dali.shzxlz.cn/Article/details/gtgflempel.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvrnjpage.html

[H05] 捕获特定类型
来源：http://dali.nanxuanxn.top/Article/details/gtbjtikftp.html

Py:   except ValueError as e:
来源：http://dali.vqdsnc.cn/Article/details/gtmvchkxpd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sxryk.cn/Article/details/gtomsvdxrc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtzpncmgqi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gtsxxskwny.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gtevdpjeak.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jlsjyb.cn/Article/details/gtzxxuowbo.html

Ruby: rescue ArgumentError => e
来源：http://dali.zycfv.cn/Article/details/gtiuvkepou.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hywenlv.cn/Article/details/gtjnwnesmk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gtngfngalu.html

Py:   value = d.get("k") or default
来源：http://dali.zhoulong.xyz/Article/details/gttjzyuxqz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gtpphxfrbu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gtvvsahojm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gtspavdpsn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.iojbl.cn/Article/details/gtwujiocsw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gtvqpoyugk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daxiang520.top/Article/details/gtwtncgtzv.html

C#:   obj?.A?.B ?? default
来源：http://dali.yonumen.top/Article/details/gtzzsdvgig.html

[H07] 断言
来源：http://dali.yongpay.top/Article/details/gthhvdriws.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xziqi.cn/Article/details/gtbzvcqkjq.html

PHP:  assert($x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtolqzzyfk.html

JS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtcqvrwpvz.html

TS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtraijjwqr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.9152youxi.cn/Article/details/gtjfwdlfli.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guannengcc.top/Article/details/gtljlrbgso.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.andypj.xyz/Article/details/gtsuxiqari.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtsuladaut.html

[H08] 获取错误信息与堆栈
来源：http://dali.ydzc1.top/Article/details/gtchjvsgeo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yueranfly.top/Article/details/gtyrulvfcj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.smart0.xyz/Article/details/gtjyzpwlfk.html

JS:   e.message;  e.stack
来源：http://dali.gotoacloud.top/Article/details/gtcbgullte.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cashguo.top/Article/details/gttuoqweok.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yueranfly.top/Article/details/gtpuzqznrc.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gtoodmulug.html

Ruby: e.message;  e.backtrace
来源：http://dali.ehwqpu.com/Article/details/gtntxoxzel.html

C#:   e.Message;  e.StackTrace
来源：http://dali.316326.xyz/Article/details/gtjobqghxw.html

[H09] 带错误码的异常
来源：http://dali.jinqigufen.top/Article/details/gtmwmkqgjx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.wangshuangyany.cn/Article/details/gtwikpaoie.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.meibo888.top/Article/details/gttesgcwgz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuetiantiany.cn/Article/details/gtgaqdhasl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sysykeji.top/Article/details/gtjehzoeyg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhiwuduotai.top/Article/details/gtreiacmvg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hammf.cn/Article/details/gtklvketme.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gtoxompglc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.redwolf501.top/Article/details/gtiypmlkyz.html

[H10] 资源自动释放
来源：http://dali.zhixingplan.top/Article/details/gtscdsvfpi.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hammf.cn/Article/details/gtfyvrpedz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gtpbsobsdo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gteiehdxzd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gtpllnwtyz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shangyingyoupin.top/Article/details/gtdvlllnar.html

Go:   defer f.Close()
来源：http://dali.chenlongwang.top/Article/details/gtwrybsrna.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenzaomai.com/Article/details/gtusoavlyu.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.birdmap.top/Article/details/gttmafrtrb.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtacwnqctq.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gtcztaomui.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtciiyugzt.html

[I01] 判断是否匹配
来源：http://dali.redwolf501.top/Article/details/gtygfdaped.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gtkkxszxll.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtpharfmxa.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtazunnrnx.html

TS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gtdpalrato.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.316326.xyz/Article/details/gtzknfzeho.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj202588.top/Article/details/gtgwjlbbhv.html

Ruby: s.match?(/\d+/)
来源：http://dali.havefunace.top/Article/details/gtqmjcnfyj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cashguo.top/Article/details/gthdizazaq.html

[I02] 提取所有匹配
来源：http://dali.zhixingplan.top/Article/details/gtgfbqdrmq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtltfiidsu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangdashe.top/Article/details/gthettrrdc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gtpcqjnccd.html

TS:   s.match(/\d+/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgfmguda.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xinyue.icu/Article/details/gtmvpnjvlx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.redwolf501.top/Article/details/gtsesgzfmt.html

Ruby: s.scan(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtwlzpvaom.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zycfv.cn/Article/details/gtqjpijbza.html

[I03] 提取捕获分组
来源：http://dali.ydzc1.top/Article/details/gtnwfvdjov.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zdqjudy.top/Article/details/gtxhfoadsk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxinkj.top/Article/details/gtbtzuusks.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258888.top/Article/details/gtebfzepbt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnqzz.top/Article/details/gtvukpprgc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hywenlv.cn/Article/details/gtuarcejqm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gtotxzhpwe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gtotrtvhvu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pengpengdd.cyou/Article/details/gtyrylewoy.html

[I04] 正则替换
来源：http://dali.hammf.cn/Article/details/gtqmzrrpdi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.svipenyu.cn/Article/details/gtivwhcxyo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yueranfly.top/Article/details/gtxyiwexbh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtmoombhkv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gtvduqfqgc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gtyxkfkcjq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yj20258.top/Article/details/gtylarsyil.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.aizwys.cn/Article/details/gtpxkcoecb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ybcxt.top/Article/details/gtiqegleif.html

[I05] 按正则拆分
来源：http://dali.gzhubu.top/Article/details/gtakpydyqf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xinyue.icu/Article/details/gtiosrlfcz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.mhx1999.top/Article/details/gtmflkrdtn.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtokvepcum.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfyamcbp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zycfv.cn/Article/details/gtrmncaxrn.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.aizwys.cn/Article/details/gtstoulhgk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtsvpbwxlq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.svipenyu.cn/Article/details/gtnlhtscga.html


<!-- 参考信息 -->