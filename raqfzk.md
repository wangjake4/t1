代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gtyyogdnac.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtgeyohpzr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gtcsvzpmdm.html

[F12] CSV 读写
来源：http://dali.guowangkeji.top/Article/details/gtawainhgo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gttycgyqti.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.feifeiyinyue.top/Article/details/gtikswwebs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xziqi.cn/Article/details/gtynayffme.html

TS:   // 同上
来源：http://dali.jqgufenzy.top/Article/details/gtqrwtpiar.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxuanxn.top/Article/details/gtpztytnvf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zycfv.cn/Article/details/gtumqihagk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnqzz.top/Article/details/gtfrtzqgvf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfacbbaf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtijsbzinp.html

G. 面向对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkfixghd.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtylgnlgsw.html

[G01] 定义类
来源：http://dali.chenlongwang.top/Article/details/gttvlbfvcs.html

Py:   class User: pass
来源：http://dali.hysaishi.cn/Article/details/gttcqkzkhq.html

PHP:  class User {}
来源：http://dali.xziqi.cn/Article/details/gtxahafeog.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtvnamybmd.html

TS:   class User { name: string = ""; }
来源：http://dali.hfpthk.cn/Article/details/gtgwaldswt.html

Java: class User {}
来源：http://dali.guannengcc.top/Article/details/gtihxxhevb.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gtkikpwlya.html

Ruby: class User; end
来源：http://dali.nwbrower.top/Article/details/gtnrxynckt.html

C#:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gticrjzhzy.html

[G02] 构造函数
来源：http://dali.mhx1999.top/Article/details/gtwggwlguh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.vqdsnc.cn/Article/details/gtcgwzjrhf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdkpyyur.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgoioefgn.html

TS:   constructor(public name: string) {}
来源：http://dali.pycfn.com/Article/details/gtmxqnxsjc.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtwrdtkzwc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.redwolf501.top/Article/details/gtvknhdrsh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gtknxhezol.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtwlchevql.html

[G03] 实例属性
来源：http://dali.cqqwz.cn/Article/details/gtqocmxjwd.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtvnoaneat.html

PHP:  public string $name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtpnlwtbzv.html

JS:   this.name = "x";
来源：http://dali.yvedp.cn/Article/details/gtqglchlob.html

TS:   name: string = "x";
来源：http://dali.nanxinkj.top/Article/details/gtfbghdzlp.html

Java: private String name;
来源：http://dali.zhengqikj.top/Article/details/gtpivmpeeh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgufenzy.top/Article/details/gtdsdtxnga.html

Ruby: @name = "x"
来源：http://dali.jianghu66.top/Article/details/gtsrrgyuli.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfrzqqdg.html

[G04] 定义方法
来源：http://dali.gaohongyu789.top/Article/details/gtuewrjhxq.html

Py:   def greet(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtufkmweua.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtipceapaa.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnniiouo.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrfybxjks.html

Java: String greet() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtrprhkbyz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtgpxidbjs.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gtysaaysog.html

C#:   public string Greet() => Name;
来源：http://dali.fzhhl.top/Article/details/gtnvdggjrl.html

[G05] 继承
来源：http://dali.bjfxy.top/Article/details/gtusqtbwvr.html

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gtcpiplrcp.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtxnefwkfd.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtnftvendy.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtvqdwajdr.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtlxzxxahp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gtitdsgdob.html

Ruby: class Admin < User; end
来源：http://dali.guowangkeji.top/Article/details/gtpezyhovz.html

C#:   class Admin : User {}
来源：http://dali.sxryk.cn/Article/details/gtddkbpioe.html

[G06] 重写方法
来源：http://dali.yuanzhike.top/Article/details/gtudgdtxbz.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gtyxzkohin.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtxynvevdy.html

JS:   greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtcxwujrdq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtsamvlkba.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtwrivlbts.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.snrcjt.cn/Article/details/gtuysekqku.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gtttstueuc.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gtmvjgrbhi.html

[G07] 调用父类方法
来源：http://dali.birdmap.top/Article/details/gtsuurlgcj.html

Py:   super().greet()
来源：http://dali.zhongyouzk.top/Article/details/gtrlmonetv.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gtjzuuyjbj.html

JS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtqcbqhtxb.html

TS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtxhioczsc.html

Java: super.greet();
来源：http://dali.tanke756.top/Article/details/gttalmgogf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gtnjwrbzzq.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gtrlgsiihx.html

C#:   base.Greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuedwmfit.html

[G08] 静态方法与属性
来源：http://dali.hywenlv.cn/Article/details/gtacsnizpo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gtmzrfqvdf.html

PHP:  public static function f() {}
来源：http://dali.svipenyu.cn/Article/details/gtofmjmjkl.html

JS:   static f() {}
来源：http://dali.jianghu66.top/Article/details/gthrthradr.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gtnqdpcgqf.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gtjblqwenb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuanzhike.top/Article/details/gtmhlthcex.html

Ruby: def self.f; end
来源：http://dali.yvedp.cn/Article/details/gtspxmvkbj.html

C#:   public static void F() {}
来源：http://dali.yuxming.cn/Article/details/gtmvzcdsyp.html

[G09] 接口 / 抽象类
来源：http://dali.jianghu66.top/Article/details/gtmwnkppew.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xziqi.cn/Article/details/gtnolgpcia.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pengpengdd.cyou/Article/details/gthivkruzq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zycfv.cn/Article/details/gtkhbomfgk.html

TS:   interface Shape { area(): number; }
来源：http://dali.0kj1m.cn/Article/details/gtrzuztwok.html

Java: interface Shape { double area(); }
来源：http://dali.svipenyu.cn/Article/details/gtpjxnwpof.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.kuanghao11.cn/Article/details/gtqvfavxql.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gtsxqdlxvn.html

C#:   interface IShape { double Area(); }
来源：http://dali.jyoumei.cn/Article/details/gtyzwpdgza.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gtlrayhptj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ybcxt.top/Article/details/gtcmlrygyd.html

PHP:  public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtnsrfbgsk.html

JS:   #private 字段；其余公开
来源：http://dali.tianlin.xyz/Article/details/gtgqqkvvws.html

TS:   public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtiivhjqlo.html

Java: public / protected / private / 默认包级
来源：http://dali.zhixingplan.top/Article/details/gtchofgoqj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jlsjyb.cn/Article/details/gtfbpumcci.html

Ruby: public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gthhupwulo.html

C#:   public / protected / private / internal
来源：http://dali.wangdashe.top/Article/details/gterkvlmji.html

[G11] getter / setter
来源：http://dali.tianlin.xyz/Article/details/gttzluwoij.html

Py:   @property 与 @x.setter
来源：http://dali.hfpthk.cn/Article/details/gtphonxzcm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtehnrhtkv.html

JS:   get name() { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtsrgwtvoc.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzubmxagu.html

Java: public String getName() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtsipbvrew.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gttulfyquz.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gttjevulqq.html

C#:   public string Name { get; set; }
来源：http://dali.sweek.top/Article/details/gtbgdvaqnq.html

[G12] 对象转字符串
来源：http://dali.daxiang520.top/Article/details/gtpcqfesib.html

Py:   def __str__(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gtpsszkuwi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtylenohzt.html

JS:   toString() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtfcmbclec.html

TS:   toString(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtssmwfnuw.html

Java: @Override public String toString() { return name; }
来源：http://dali.cheryme.top/Article/details/gtavqjnrvc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtyhhdfbiw.html

Ruby: def to_s; @name; end
来源：http://dali.havefunace.top/Article/details/gthlmmmmim.html

C#:   public override string ToString() => Name;
来源：http://dali.birdmap.top/Article/details/gthioqgtsp.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gtshsabscm.html

Py:   isinstance(u, User)
来源：http://dali.shangyingyoupin.top/Article/details/gtkfndijxo.html

PHP:  $u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtwpsptkxv.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtulehablq.html

TS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtqtkaopjq.html

Java: u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtftgqiatt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daxiang520.top/Article/details/gtkowhiypm.html

Ruby: u.is_a?(User)
来源：http://dali.ydzc1.top/Article/details/gtayjmswuw.html

C#:   u is User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjoozjuc.html

[G14] 数据类 / record
来源：http://dali.sufxvd.cn/Article/details/gtmunbxgyh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangtech.top/Article/details/gttrfpongs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gtoposqwxg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gtzjpwztpk.html

TS:   type User = { name: string; age: number };
来源：http://dali.jiagoushi.top/Article/details/gtmkubgbgn.html

Java: record User(String name, int age) {}
来源：http://dali.xylfe.cn/Article/details/gtvrimceiq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zycfv.cn/Article/details/gtknbxhonr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.smart0.xyz/Article/details/gtyyosndfa.html

C#:   record User(string Name, int Age);
来源：http://dali.iojbl.cn/Article/details/gtdwydjaao.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gtzquoqfpe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gtcjsjzzza.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tian-w.cn/Article/details/gtdlefssxi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daxiang520.top/Article/details/gtlieiyrtt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gtdqjmkeqe.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenzaomai.com/Article/details/gtswlsyvcy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhiwuduotai.top/Article/details/gtllptnigt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gotoacloud.top/Article/details/gtmyhoakqa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtfcznwtdk.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gtmipzwmhn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gogol.net.cn/Article/details/gtbgauwbrs.html

PHP:  get_object_vars($obj);
来源：http://dali.daxiang520.top/Article/details/gtxhoorszq.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtikfkjplw.html

TS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtavyzjmij.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zdqjudy.top/Article/details/gtlniwsblw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ehwqpu.com/Article/details/gtotwjysyv.html

Ruby: obj.instance_variables
来源：http://dali.chenjidiqi.icu/Article/details/gtvwcsusqp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gtnsrqgbkx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtqggvtmry.html

H. 异常与错误处理
来源：http://dali.yvedp.cn/Article/details/gtgyqpczrd.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtelglssbq.html

[H01] try / catch 基础
来源：http://dali.jiagoushi.top/Article/details/gtnkmytpoo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gthwpcanik.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gtbearynhk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjvmjils.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtnvefsbwn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuxming.cn/Article/details/gtvxprqizl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gtfvdnmkuv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shuidangran.top/Article/details/gtycwtdngd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gtwwflcsii.html

[H02] finally / ensure 收尾
来源：http://dali.tanke756.top/Article/details/gttpilrccj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ppjwa.cn/Article/details/gtckypitxm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtihhnlgok.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtrodiurzg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtzqbpzqyl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtjnwjuagf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.feifeiyinyue.top/Article/details/gthnqhltkq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gtfewmhsaw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtlkqireud.html

[H03] 主动抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtishczhpv.html

Py:   raise ValueError("错误信息")
来源：http://dali.yanxiufei.cn/Article/details/gtshsxenmr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtybcwyzpy.html

JS:   throw new Error("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gttxtbbujo.html

TS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtzvygayql.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtwiqftlyw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guannengcc.top/Article/details/gtqtdnezqd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yonumen.top/Article/details/gtcpkvojek.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtcipympgn.html

[H04] 自定义异常类型
来源：http://dali.ppjwa.cn/Article/details/gtzlojtqgn.html

Py:   class MyError(Exception): pass
来源：http://dali.mhx1999.top/Article/details/gtsnbggrih.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gttkqhyckv.html

JS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gtaoaicyrw.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtjytafpyk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gtirmcbvdd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxuanxn.top/Article/details/gtliczladq.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuanzx.com/Article/details/gtiiszqusn.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258888.top/Article/details/gtcpjvdidc.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gtyjphznwf.html

Py:   except ValueError as e:
来源：http://dali.guannengcc.top/Article/details/gtvejldlhi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guowangkeji.top/Article/details/gtanrueuhu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gtiieunxrf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtblemozgo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigfzy.top/Article/details/gtugcqhzvl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhongyouzk.top/Article/details/gtbbesokxw.html

Ruby: rescue ArgumentError => e
来源：http://dali.meibo888.top/Article/details/gtdybhptjr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gtvvmmsbqh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gtutabcwof.html

Py:   value = d.get("k") or default
来源：http://dali.jiagoushi.top/Article/details/gtfrvlbvsd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cheryme.top/Article/details/gtjdsqaxjv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtqlhfadlu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gtzrohovld.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gtocyopvcb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gtdqnminaf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cashguo.top/Article/details/gtxdkknlhm.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gtprhjdqqj.html

[H07] 断言
来源：http://dali.nanxuanxn.top/Article/details/gtljdmwlbs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jiagoushi.top/Article/details/gtxdxfeymk.html

PHP:  assert($x > 0);
来源：http://dali.fengsongda.top/Article/details/gtusrucxfz.html

JS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtnvlcsvrs.html

TS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtsemtlgal.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gtvpavvdby.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sweek.top/Article/details/gtxttzacsw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gotoacloud.top/Article/details/gtqjfptojj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtknhlwhgm.html

[H08] 获取错误信息与堆栈
来源：http://dali.zycfv.cn/Article/details/gtvcehxwyw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinghuilouyu.cn/Article/details/gtuypenglu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yueranfly.top/Article/details/gtopgmosai.html

JS:   e.message;  e.stack
来源：http://dali.sysykeji.top/Article/details/gtqnbwzpmp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gttveufhzd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gtkuttecnd.html

Go:   err.Error()
来源：http://dali.hfpthk.cn/Article/details/gtkjcnjprw.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuanzhike.top/Article/details/gtluxgwccf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xinyue.icu/Article/details/gtqwimneuc.html

[H09] 带错误码的异常
来源：http://dali.jinqigufen.top/Article/details/gtfywdfaeh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnxiangtu.top/Article/details/gtrglznden.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gtlmcoixiz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gtymlrvpyc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hywenlv.cn/Article/details/gtlokeszfa.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.316326.xyz/Article/details/gtttnqlpuq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yanxiufei.cn/Article/details/gtkwfeleqt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphxkbvre.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gtmombszwt.html

[H10] 资源自动释放
来源：http://dali.jinqigufen.top/Article/details/gtzybjoecw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shangyingyoupin.top/Article/details/gtpykvxewi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gaohongyu789.top/Article/details/gtfmnobxxa.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gtlaiyqiaj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gtrjgjnrdx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zycfv.cn/Article/details/gtmwoxrkgk.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gtlozmudix.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxinkj.top/Article/details/gtgcqoiieb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtnrebrfva.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtklizirgo.html

I. 正则表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtwhefjtiw.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkphpbhp.html

[I01] 判断是否匹配
来源：http://dali.snrcjt.cn/Article/details/gtaxweaesh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gtcndezlgq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtztgvihha.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gtrioychuk.html

TS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtqtljqadp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuupxvfcd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gzhubu.top/Article/details/gteiivxjgg.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtrzwrhdjx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jyoumei.cn/Article/details/gtquhsbenn.html

[I02] 提取所有匹配
来源：http://dali.svipenyu.cn/Article/details/gtgddslxgt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtxnwgfgrl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhongyouzk.top/Article/details/gtiovqjvdi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fzhhl.top/Article/details/gtmvgrmkxh.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gtsliiyvdj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.haohaochexian.top/Article/details/gtjfbfjzmi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gtiffnvfvo.html

Ruby: s.scan(/\d+/)
来源：http://dali.daxiang520.top/Article/details/gtszidjdrm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gtazpduanv.html

[I03] 提取捕获分组
来源：http://dali.gotoacloud.top/Article/details/gtpyqnxpqd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gtliibecxp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aibaodan.cn/Article/details/gtvdkgkwbm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yangfankeji.com/Article/details/gtnfazfdeh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqijhpvw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cucudq.cn/Article/details/gtlqxzrleb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.bjfxy.top/Article/details/gtubmpsywv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.snrcjt.cn/Article/details/gtkkwecxei.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ybcxt.top/Article/details/gtpkuhlvnh.html

[I04] 正则替换
来源：http://dali.yuxming.cn/Article/details/gtucgemlzj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbddmjlei.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sxryk.cn/Article/details/gtqxtdotio.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gtuffjsitd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtysxtnotz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtmawtsyjg.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.316326.xyz/Article/details/gtmpimmwbb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgfzy.top/Article/details/gtxldgxhfa.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtfsuhgfzf.html

[I05] 按正则拆分
来源：http://dali.cucudq.cn/Article/details/gtzvefdqwa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.cdnleiting.top/Article/details/gtwgjrmzfr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yonumen.top/Article/details/gtqskpaowe.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.snrcjt.cn/Article/details/gtrxggqeil.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtappmfnvx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nwbrower.top/Article/details/gtjcdewqsh.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gthakrjowd.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gtlwcrwlvo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tanke756.top/Article/details/gtfzzrejno.html


<!-- 参考信息 -->