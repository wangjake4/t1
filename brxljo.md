代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gtyrrolcje.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtvggkkxqg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gttlblxuea.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258.top/Article/details/gteppuzqkq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigfzy.top/Article/details/gtuggnscnv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtkpkqtbgl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gtoyffeeve.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gtcifrsbtk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwaqhjunk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ivvv.top/Article/details/gtyopynbwf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.snrcjt.cn/Article/details/gtvrwhzwqc.html

TS:   // 同上
来源：http://dali.gotoacloud.top/Article/details/gtnyqaxlzh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.mhx1999.top/Article/details/gtjruyewry.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangshuangyany.cn/Article/details/gtraayuufq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gtditlhqkz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gtsaienjlt.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfswxcrf.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gtrcjjyzek.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtamalqgvj.html

[G01] 定义类
来源：http://dali.nanxuanxn.top/Article/details/gtupqxcvhu.html

Py:   class User: pass
来源：http://dali.chenzaomai.com/Article/details/gtbjrwxoah.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gtkfyyaush.html

JS:   class User {}
来源：http://dali.xziqi.cn/Article/details/gtgqpzgeyk.html

TS:   class User { name: string = ""; }
来源：http://dali.jlsjyb.cn/Article/details/gtdooopfsn.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gtxcpuojei.html

Go:   type User struct { Name string }
来源：http://dali.havefunace.top/Article/details/gtmafmikov.html

Ruby: class User; end
来源：http://dali.xylfe.cn/Article/details/gtnzirlpnt.html

C#:   class User {}
来源：http://dali.yonumen.top/Article/details/gtbuocstvf.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gtsqescehm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gtycitsayy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtgykggzcv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxekgejq.html

TS:   constructor(public name: string) {}
来源：http://dali.sweek.top/Article/details/gtdgttudjh.html

Java: User(String name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtmxgfvhcn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.kuanghao11.cn/Article/details/gttkgrsleb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtriqsmauz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jyoumei.cn/Article/details/gticvyblbj.html

[G03] 实例属性
来源：http://dali.quarkkingdee.top/Article/details/gthmtoflkd.html

Py:   self.name = "x"
来源：http://dali.gzhubu.top/Article/details/gtwjqrkwne.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtlsexkuuo.html

JS:   this.name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtxhxpegnc.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtydbuffnj.html

Java: private String name;
来源：http://dali.yuanzhike.top/Article/details/gtstplthlu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hfpthk.cn/Article/details/gtciwwtlhl.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtayhdiivi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.mhx1999.top/Article/details/gtzslntscc.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gtjxvyhade.html

Py:   def greet(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtjuiwgqvw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtvrfrqpny.html

JS:   greet() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gturjdqzpu.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtoqymptky.html

Java: String greet() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtujokfawi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtgjshlzwe.html

Ruby: def greet; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gteaxidjwp.html

C#:   public string Greet() => Name;
来源：http://dali.hnqzz.top/Article/details/gtnlbrevdp.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gtlgoaifxf.html

Py:   class Admin(User): pass
来源：http://dali.redwolf501.top/Article/details/gtrruuqdwq.html

PHP:  class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gttkixokqo.html

JS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtgcyacqce.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gttygxqfwb.html

Java: class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzctygqf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.c1oappe.top/Article/details/gtsomcsxxv.html

Ruby: class Admin < User; end
来源：http://dali.yonumen.top/Article/details/gtwfezvxxe.html

C#:   class Admin : User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtnqykiglg.html

[G06] 重写方法
来源：http://dali.tianlin.xyz/Article/details/gtgaqpmezg.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gtkltjkboj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtyotqwbnd.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtnqtscevq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxghizmyb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtharkvqch.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenjidiqi.icu/Article/details/gtuwsgmddm.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gtsjytbheb.html

C#:   public override string Greet() => "admin";
来源：http://dali.gaohongyu789.top/Article/details/gtjtvurvrf.html

[G07] 调用父类方法
来源：http://dali.birdmap.top/Article/details/gtlvdkpefn.html

Py:   super().greet()
来源：http://dali.wangshuangyany.cn/Article/details/gtomhtwrma.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtnbbxjufk.html

JS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtbeijwpnh.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtukdgqkke.html

Java: super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtxheacegn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gtdvlusaqa.html

Ruby: super
来源：http://dali.hongshengwenyu.top/Article/details/gtyjmdotcf.html

C#:   base.Greet();
来源：http://dali.dianchejie.cn/Article/details/gtyftaxilc.html

[G08] 静态方法与属性
来源：http://dali.cashguo.top/Article/details/gtxbtsicam.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gaohongyu789.top/Article/details/gtucvwktme.html

PHP:  public static function f() {}
来源：http://dali.dashuyun.cn/Article/details/gtyxwwgyaj.html

JS:   static f() {}
来源：http://dali.yj20258888.top/Article/details/gtkgridtap.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gtrhmyzmsl.html

Java: static void f() {}
来源：http://dali.jyoumei.cn/Article/details/gtippctlaf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.iojbl.cn/Article/details/gtablpqwcq.html

Ruby: def self.f; end
来源：http://dali.nwbrower.top/Article/details/gtzrobdxqp.html

C#:   public static void F() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtwoeokkgd.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gtpejudqjc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yongpay.top/Article/details/gtnywvdwlx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnigwhzph.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.havefunace.top/Article/details/gtkkffryoi.html

TS:   interface Shape { area(): number; }
来源：http://dali.ppjwa.cn/Article/details/gtcnzcsywa.html

Java: interface Shape { double area(); }
来源：http://dali.bjfxy.top/Article/details/gtyzodjnpi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.0kj1m.cn/Article/details/gtyqpupzjk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.feifeiyinyue.top/Article/details/gtjwwocpse.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gtpceoswye.html

[G10] 访问控制
来源：http://dali.guowangkeji.top/Article/details/gtnqinyseu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hywenlv.cn/Article/details/gtthfnsjim.html

PHP:  public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtaxgmplsu.html

JS:   #private 字段；其余公开
来源：http://dali.svipenyu.cn/Article/details/gtqwgrclfo.html

TS:   public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtpppfxnxw.html

Java: public / protected / private / 默认包级
来源：http://dali.tanke756.top/Article/details/gtfwtntgtn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.0kj1m.cn/Article/details/gtyuttjxiq.html

Ruby: public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtomwmlpqg.html

C#:   public / protected / private / internal
来源：http://dali.jlsjyb.cn/Article/details/gtnpshyepo.html

[G11] getter / setter
来源：http://dali.ydzc1.top/Article/details/gtamdiddss.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gthhokhlrs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtsxtcqfqw.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtsvarmdoa.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtvfdaoche.html

Java: public String getName() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtqeqmvpvu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnqmilvw.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gtxrvdvvcl.html

C#:   public string Name { get; set; }
来源：http://dali.hongshengwenyu.top/Article/details/gtjwffdwlo.html

[G12] 对象转字符串
来源：http://dali.ydzc1.top/Article/details/gtshvtmghg.html

Py:   def __str__(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gtdtpygmtq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtlanfqemd.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtpejevymp.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtzmbejwmr.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqnxsretj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtgcfdmibj.html

Ruby: def to_s; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gthngyqdph.html

C#:   public override string ToString() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gtrjuudwdp.html

[G13] 判断对象类型
来源：http://dali.hongshengwenyu.top/Article/details/gtmjxlqflh.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gtidaultjw.html

PHP:  $u instanceof User
来源：http://dali.daxiang520.top/Article/details/gthmwicytz.html

JS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtepankjsa.html

TS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtkjnhllpn.html

Java: u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtalzcbyur.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxuanxn.top/Article/details/gtvlijeufx.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258.top/Article/details/gttcjdeaol.html

C#:   u is User
来源：http://dali.jinqigfzy.top/Article/details/gtankrbszm.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gtufkndppc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gtdcleilhk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.vqdsnc.cn/Article/details/gtjtvnasej.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shangyingyoupin.top/Article/details/gtzqwepbrb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zycfv.cn/Article/details/gtehxoyeeb.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gtuldsfmqv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sweek.top/Article/details/gtrxpthhvu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daria6918.cn/Article/details/gtlfkjnfkv.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxinkj.top/Article/details/gtvrsejpyj.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gtzodkvhbm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj202588.top/Article/details/gtyalgiory.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedfapbpo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pengpengdd.cyou/Article/details/gtwxbecmia.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtuiyerygu.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gtmfvcligv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnqzz.top/Article/details/gtdkviegyp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gzhubu.top/Article/details/gticbuygqs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gthtpgwhtn.html

[G16] 对象转数组 / 字典
来源：http://dali.zhiwuduotai.top/Article/details/gtvnzytziz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnqxnigm.html

PHP:  get_object_vars($obj);
来源：http://dali.jianghu66.top/Article/details/gtenufpmyg.html

JS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtssbnpnjt.html

TS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gttgjyeyjs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.316326.xyz/Article/details/gtxkvoqswm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gtykqoejxx.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlpzjpry.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtkqdrhndh.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtsignklln.html

H. 异常与错误处理
来源：http://dali.fengsongda.top/Article/details/gthzijxvjb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gthdjeqave.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gtctwcerns.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dianchejie.cn/Article/details/gtjgidzbsu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daria6918.cn/Article/details/gtapmhjlug.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gttoaltnmn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtfeeycdch.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shuidangran.top/Article/details/gtmfqbslwl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigufen.top/Article/details/gtmrrgripq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daxiang520.top/Article/details/gtbqqynudp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gtoumpbqly.html

[H02] finally / ensure 收尾
来源：http://dali.guannengcc.top/Article/details/gtqmvxpnxs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dianchejie.cn/Article/details/gtwigslmxl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtjgjdfdql.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtgbgrjjsw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtzsfgroef.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtogtxestd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aizwys.cn/Article/details/gteyolhmeh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tanke756.top/Article/details/gtoaszctxg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtrbngihgn.html

[H03] 主动抛出异常
来源：http://dali.cheryme.top/Article/details/gttvuhiorc.html

Py:   raise ValueError("错误信息")
来源：http://dali.zdqjudy.top/Article/details/gtdyrmssti.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtwrkbkulj.html

JS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gthhgjwibt.html

TS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtzgirfsns.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtoordylac.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstzqhmfh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhoulong.xyz/Article/details/gtkmecqjoe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtasprmdij.html

[H04] 自定义异常类型
来源：http://dali.ydzc1.top/Article/details/gtuvnkztbh.html

Py:   class MyError(Exception): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphjcmgan.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtppwkagkd.html

JS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gtqwxxjxeg.html

TS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gtanyonehw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtoegtokvv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gtnhyietwd.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gttddznmtu.html

C#:   class MyException : Exception {}
来源：http://dali.gotoacloud.top/Article/details/gtdjygggcf.html

[H05] 捕获特定类型
来源：http://dali.jlsjyb.cn/Article/details/gtyvzjabmy.html

Py:   except ValueError as e:
来源：http://dali.sufxvd.cn/Article/details/gtxwzwtfqt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.kuanghao11.cn/Article/details/gtkfmimfjd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gthkfqxwsi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtuglynxwg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuanzx.com/Article/details/gtvskqxfrs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daria6918.cn/Article/details/gtrtlgdkcg.html

Ruby: rescue ArgumentError => e
来源：http://dali.gaohongyu789.top/Article/details/gtqqzqxjsq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pycfn.com/Article/details/gtfcpltjrh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuetiantiany.cn/Article/details/gtvasnsyzy.html

Py:   value = d.get("k") or default
来源：http://dali.meibo888.top/Article/details/gtvytdtmfu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvruhrrsa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gtahhhsbwd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtwrawnnrd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.havefunace.top/Article/details/gtdimdlsyo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yongpay.top/Article/details/gttjyglccg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sxryk.cn/Article/details/gtfvpmpldm.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenzaomai.com/Article/details/gtzuksdvpd.html

[H07] 断言
来源：http://dali.hysaishi.cn/Article/details/gtvhxfietp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenzaomai.com/Article/details/gtabfceqtm.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtsbspxgnu.html

JS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gttisskgzg.html

TS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtucdmqdpn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangdashe.top/Article/details/gthnuptgek.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj202588.top/Article/details/gtwkerfjfx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gtmvyjliuf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtfyzxdmvt.html

[H08] 获取错误信息与堆栈
来源：http://dali.fengsongda.top/Article/details/gtxrmlihkb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aizwys.cn/Article/details/gtrdmfssdt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shangyingyoupin.top/Article/details/gtxmbwecgo.html

JS:   e.message;  e.stack
来源：http://dali.tanke756.top/Article/details/gtxqytwsor.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.9152youxi.cn/Article/details/gtqvhhcatp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffqmzsir.html

Go:   err.Error()
来源：http://dali.jqgfzy.top/Article/details/gtimtnvezg.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gtkqglpcnj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gtctlzxrxe.html

[H09] 带错误码的异常
来源：http://dali.meibo888.top/Article/details/gtkpmivnku.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.havefunace.top/Article/details/gtjdnaaruf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuxming.cn/Article/details/gtwlldqrhb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.mhx1999.top/Article/details/gtlwlxvcbm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gthdcihgfk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tian-w.cn/Article/details/gtzjftlmej.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sufxvd.cn/Article/details/gtetvtbxdf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gtnhcthtrk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zycfv.cn/Article/details/gtrxmdxgvu.html

[H10] 资源自动释放
来源：http://dali.yonumen.top/Article/details/gtfxdbmrnz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhakjlsg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xylfe.cn/Article/details/gtooaxeuef.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtwuugixjt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtiusxwzyx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gtjucrkaxh.html

Go:   defer f.Close()
来源：http://dali.tanke756.top/Article/details/gtkpnzxvvj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnqzz.top/Article/details/gtuopoxujj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtkjfxnyqd.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtitwsuqie.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gtqqrwogre.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtraevqatj.html

[I01] 判断是否匹配
来源：http://dali.iojbl.cn/Article/details/gtpqyhtdcq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtcqlomook.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtcehjrpax.html

JS:   /\d+/.test(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzvmnrcr.html

TS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gteebwllzf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuxming.cn/Article/details/gtjjsjhkmd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tianlin.xyz/Article/details/gtdqbemfwf.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gtbvubstih.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aizwys.cn/Article/details/gtrgqrjcyq.html

[I02] 提取所有匹配
来源：http://dali.daxiang520.top/Article/details/gtnvhtqder.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtwfuiwbnz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hysaishi.cn/Article/details/gtcsfvfpdq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gtxsyqiyrz.html

TS:   s.match(/\d+/g)
来源：http://dali.ivvv.top/Article/details/gtgriyodex.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ivvv.top/Article/details/gtarkwdjcp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gthpbfhcia.html

Ruby: s.scan(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gttblxxcds.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtjrgdkyct.html

[I03] 提取捕获分组
来源：http://dali.pycfn.com/Article/details/gtnbwbdykg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nwbrower.top/Article/details/gtwgycrotp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ydzc1.top/Article/details/gtnghkeueq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.bjfxy.top/Article/details/gtteojzkpd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ivvv.top/Article/details/gtdqzluoka.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjcmrdtr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ydzc1.top/Article/details/gtsulzgazp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgfzy.top/Article/details/gtgqxhtste.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.iojbl.cn/Article/details/gtmnywwhas.html

[I04] 正则替换
来源：http://dali.ivvv.top/Article/details/gtewtiuwhl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jlsjyb.cn/Article/details/gtvfilndck.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gtqdqzndkv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gtbprrnkfl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtrertdtdx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtebrlptqv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigufen.top/Article/details/gthtcyuikv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.haohaochexian.top/Article/details/gtjkkkkvwd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.havefunace.top/Article/details/gtxikauzjh.html

[I05] 按正则拆分
来源：http://dali.yj20258.top/Article/details/gtujvdpbuw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnxiangtu.top/Article/details/gtigfevmab.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtxjhqrmpl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.aibaodan.cn/Article/details/gtfcufpvzo.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtfusnbgfd.html


<!-- 参考信息 -->