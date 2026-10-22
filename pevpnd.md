代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2musqbgot.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2gnojlrqu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2amsrisqg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gt2qnvwvbvt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gt2mygaonql.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gt2xqstcynk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shuidangran.top/Article/details/gt2yusorfvd.html

[F12] CSV 读写
来源：http://dali.daxiang520.top/Article/details/gt2akztkdbr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aibaodan.cn/Article/details/gt2rkpvypka.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tanke756.top/Article/details/gt2syobtqvn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2czjtycow.html

TS:   // 同上
来源：http://dali.yuxming.cn/Article/details/gt2stutxtlp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gt2vxvccqiv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gt2pcaepqzb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hywenlv.cn/Article/details/gt2ojhgsbrk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.iojbl.cn/Article/details/gt2gnddflgz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2gsiwkjfe.html

G. 面向对象
来源：http://dali.zhengqikj.top/Article/details/gt2plwfjral.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2lwvttcot.html

[G01] 定义类
来源：http://dali.cashguo.top/Article/details/gt2zvpqlerd.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gt2ltfjkgov.html

PHP:  class User {}
来源：http://dali.meibo888.top/Article/details/gt2ikvdexoe.html

JS:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gt2phcqjuwy.html

TS:   class User { name: string = ""; }
来源：http://dali.c1oappe.top/Article/details/gt2jsxttzps.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2sfpbexcb.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gt2ykusxjwd.html

Ruby: class User; end
来源：http://dali.aizwys.cn/Article/details/gt2hxquvluc.html

C#:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2ndiqasan.html

[G02] 构造函数
来源：http://dali.yvedp.cn/Article/details/gt2kxiltdkg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.havefunace.top/Article/details/gt2ocvlaitl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.svipenyu.cn/Article/details/gt2aohkewnt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gt2vwkffmxa.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2zddvdjgj.html

Java: User(String name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2oinliwzb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hywenlv.cn/Article/details/gt2cposlpxp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ybcxt.top/Article/details/gt2phiekmhb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cucudq.cn/Article/details/gt2tgupjhpt.html

[G03] 实例属性
来源：http://dali.kuanghao11.cn/Article/details/gt2twcuyyts.html

Py:   self.name = "x"
来源：http://dali.smart0.xyz/Article/details/gt2wxvgkfsj.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2bgzglqnd.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2uarrkgsp.html

TS:   name: string = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2jbnyhdcl.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gt2bswnnifg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhixingplan.top/Article/details/gt2valqrcgh.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gt2bjhmhjbb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnqzz.top/Article/details/gt2eedyiokz.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ughpozhr.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gt2qlfnppas.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gt2pjsiqqhq.html

JS:   greet() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2rdawcodb.html

TS:   greet(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2npwxogjg.html

Java: String greet() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ybsjserk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2awuwutfe.html

Ruby: def greet; @name; end
来源：http://dali.hywenlv.cn/Article/details/gt2uqyqquhf.html

C#:   public string Greet() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2woaeqnfb.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gt2exttcsde.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gt2ofyensif.html

PHP:  class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhuopurz.html

JS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2mtovwqmx.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2iuedcsyr.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2elwclkum.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gt2yjheeyvu.html

Ruby: class Admin < User; end
来源：http://dali.zhoulong.xyz/Article/details/gt2aqilgfcp.html

C#:   class Admin : User {}
来源：http://dali.yuanzhike.top/Article/details/gt2apinymdp.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2gomvafhe.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gt2tivbopki.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gt2eeigngle.html

JS:   greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gt2igaqpnkx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gt2pcqfeaul.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2oskucdrd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gt2zefjwkta.html

Ruby: def greet; "admin"; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kmswvwad.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gt2daspxfal.html

[G07] 调用父类方法
来源：http://dali.havefunace.top/Article/details/gt2abkwahtm.html

Py:   super().greet()
来源：http://dali.hammf.cn/Article/details/gt2fuoyifxj.html

PHP:  parent::greet();
来源：http://dali.nanxinkj.top/Article/details/gt2bqyxmimd.html

JS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2mcrgmwnu.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gt2cyxnyuya.html

Java: super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2kkfbadvf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.mhx1999.top/Article/details/gt2nupikyvq.html

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gt2lrqwpdhm.html

C#:   base.Greet();
来源：http://dali.yangfankeji.com/Article/details/gt2txksrnjq.html

[G08] 静态方法与属性
来源：http://dali.smart0.xyz/Article/details/gt2aqtkixqp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gt2nmxyvxed.html

PHP:  public static function f() {}
来源：http://dali.fengsongda.top/Article/details/gt2pcnkuujp.html

JS:   static f() {}
来源：http://dali.xziqi.cn/Article/details/gt2shwtigir.html

TS:   static f(): void {}
来源：http://dali.cdnleiting.top/Article/details/gt2ktlnrmrc.html

Java: static void f() {}
来源：http://dali.guowangkeji.top/Article/details/gt2alzwjecw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gt2zdvkpiyi.html

Ruby: def self.f; end
来源：http://dali.svipenyu.cn/Article/details/gt2quhrgcpw.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gt2fbfdeolo.html

[G09] 接口 / 抽象类
来源：http://dali.birdmap.top/Article/details/gt2bxnbhizv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.meibo888.top/Article/details/gt2xzwrobiq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.bjfxy.top/Article/details/gt2mpzktbun.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhongyouzk.top/Article/details/gt2wkkkimqe.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gt2idapwlpe.html

Java: interface Shape { double area(); }
来源：http://dali.yuxming.cn/Article/details/gt2vlbbgvks.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dianchejie.cn/Article/details/gt2mkrtxium.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gt2fczeniph.html

C#:   interface IShape { double Area(); }
来源：http://dali.mhx1999.top/Article/details/gt2ryhicttb.html

[G10] 访问控制
来源：http://dali.jqgufenzy.top/Article/details/gt2rfxrrnjm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vqdgqjpv.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwiurns.html

JS:   #private 字段；其余公开
来源：http://dali.tianlin.xyz/Article/details/gt2qvvcrcss.html

TS:   public / protected / private
来源：http://dali.cashguo.top/Article/details/gt2wiggzsgo.html

Java: public / protected / private / 默认包级
来源：http://dali.gaohongyu789.top/Article/details/gt2djlzuqgs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258888.top/Article/details/gt2eibnuzvx.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gt2ergyqamb.html

C#:   public / protected / private / internal
来源：http://dali.xziqi.cn/Article/details/gt2zkykpbtt.html

[G11] getter / setter
来源：http://dali.sxryk.cn/Article/details/gt2vhlioqle.html

Py:   @property 与 @x.setter
来源：http://dali.gogol.net.cn/Article/details/gt2jhoevtlk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gt2sqhbzlkq.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2aieaaowf.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2wkxxjbrt.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2rbvzpoja.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2lvsgbwiy.html

Ruby: attr_accessor :name
来源：http://dali.guannengcc.top/Article/details/gt2taolmfnc.html

C#:   public string Name { get; set; }
来源：http://dali.nanxinkj.top/Article/details/gt2yowqyusy.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gt2igajmpwp.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gt2ggwmibcg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gt2xvxczzpo.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gt2qtkxwmat.html

TS:   toString(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2yxcwuwfl.html

Java: @Override public String toString() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2trpcnpii.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gt2tzrmqvjd.html

Ruby: def to_s; @name; end
来源：http://dali.hnqzz.top/Article/details/gt2hmuvxioi.html

C#:   public override string ToString() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gt2aflbfykf.html

[G13] 判断对象类型
来源：http://dali.hammf.cn/Article/details/gt2nnwrvhux.html

Py:   isinstance(u, User)
来源：http://dali.hysaishi.cn/Article/details/gt2ibroymxo.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pmubnjza.html

JS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2ptimhaue.html

TS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gnlrksba.html

Java: u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2thidcrxm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dashuyun.cn/Article/details/gt2uvvpxegg.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ievhpiib.html

C#:   u is User
来源：http://dali.0kj1m.cn/Article/details/gt2ysogfltk.html

[G14] 数据类 / record
来源：http://dali.zhixingplan.top/Article/details/gt2bwfslnod.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xylfe.cn/Article/details/gt2dwudebzw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gt2ivkvbnbm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangshuangyany.cn/Article/details/gt2votyjywg.html

TS:   type User = { name: string; age: number };
来源：http://dali.daria6918.cn/Article/details/gt2hniljoao.html

Java: record User(String name, int age) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ctahxlab.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gt2fkgaofyc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gt2trapshfu.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gt2wahawzuf.html

[G15] 枚举
来源：http://dali.aizwys.cn/Article/details/gt2djtubdrq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2jmwxowzk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hywenlv.cn/Article/details/gt2mcnymxie.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigufen.top/Article/details/gt2vwbcfhdp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gt2kwsyyhno.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gt2uztzvtbr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guowangkeji.top/Article/details/gt2ufneokkn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gt2nijyrohe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2fpdrbgzx.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgfzy.top/Article/details/gt2hleruapc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258888.top/Article/details/gt2dpvilkdh.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gt2ljyqetxe.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vzvwlemf.html

TS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2tlzseoen.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xylfe.cn/Article/details/gt2tfifikzd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykmoxziz.html

Ruby: obj.instance_variables
来源：http://dali.hfpthk.cn/Article/details/gt2hjkemkbh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gt2wntzdzsr.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2iodzqrtz.html

H. 异常与错误处理
来源：http://dali.wangdashe.top/Article/details/gt2tajvafoi.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2ilmkzzyz.html

[H01] try / catch 基础
来源：http://dali.zhiwuduotai.top/Article/details/gt2jcrcdfyq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rchnhzbp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2mwfmmook.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gt2muttbvrw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gt2erszgxxa.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dashuyun.cn/Article/details/gt2nnromcig.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sweek.top/Article/details/gt2lhdeieuc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.0kj1m.cn/Article/details/gt2pevrhyyb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gt2doxkmiyq.html

[H02] finally / ensure 收尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fizkkqct.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yanxiufei.cn/Article/details/gt2mnfuzfdw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2gtohjicw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2wejcybpa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2exepepny.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wvqwueef.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenjidiqi.icu/Article/details/gt2qacqkeyv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nwbrower.top/Article/details/gt2anpjrbcy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2ujccwbqk.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzegjbx.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gt2eeltqnvr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2dqhnrtlu.html

JS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gt2lgisthaq.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2eproqbje.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2ucieoedr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gt2umdslysb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangshuangyany.cn/Article/details/gt2xduxfnec.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2febjvgyr.html

[H04] 自定义异常类型
来源：http://dali.dashuyun.cn/Article/details/gt2ddhakuim.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gt2gatoyrhd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ctroafad.html

JS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gt2qtnkymzd.html

TS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gt2hpbsyxyj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gt2iuwdcwnh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yongpay.top/Article/details/gt2tyetzlaq.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gt2birnjtkr.html

C#:   class MyException : Exception {}
来源：http://dali.haohaochexian.top/Article/details/gt2lrpdashq.html

[H05] 捕获特定类型
来源：http://dali.birdmap.top/Article/details/gt2smfgfmdr.html

Py:   except ValueError as e:
来源：http://dali.aizwys.cn/Article/details/gt2bfrjgpyd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zycfv.cn/Article/details/gt2tpbnzmfr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gt2pizssmqo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gt2xlnrzsfg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hywenlv.cn/Article/details/gt2olirlqrd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daria6918.cn/Article/details/gt2kbjfufqw.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigfzy.top/Article/details/gt2atbcmsae.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tianlin.xyz/Article/details/gt2cgdtilpi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhengqikj.top/Article/details/gt2vvappxri.html

Py:   value = d.get("k") or default
来源：http://dali.yvedp.cn/Article/details/gt2idcsltsr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gt2vczgxvos.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gt2jkxsmorg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gt2kykzpouc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258888.top/Article/details/gt2errwctmm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.kuanghao11.cn/Article/details/gt2oabfqxpt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qbzvjjqs.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uqnqvwcf.html

[H07] 断言
来源：http://dali.fengsongda.top/Article/details/gt2qlgzsmyr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenjidiqi.icu/Article/details/gt2nnohntzg.html

PHP:  assert($x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dspncizn.html

JS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2hbpiwaos.html

TS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2hnwsnjgl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgfzy.top/Article/details/gt2lmkzvyqr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daria6918.cn/Article/details/gt2gjtjgjim.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhoulong.xyz/Article/details/gt2tgjpfnlf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2jgtrpnct.html

[H08] 获取错误信息与堆栈
来源：http://dali.jyoumei.cn/Article/details/gt2ephimduf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.redwolf501.top/Article/details/gt2uoovihfe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.meibo888.top/Article/details/gt2gegdxuqn.html

JS:   e.message;  e.stack
来源：http://dali.ivvv.top/Article/details/gt2ensrnczu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cucudq.cn/Article/details/gt2mgpvzbne.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dianchejie.cn/Article/details/gt2vxynzwda.html

Go:   err.Error()
来源：http://dali.zhengqikj.top/Article/details/gt2aurivckj.html

Ruby: e.message;  e.backtrace
来源：http://dali.xziqi.cn/Article/details/gt2agausgyh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gt2ucbptkkt.html

[H09] 带错误码的异常
来源：http://dali.gotoacloud.top/Article/details/gt2bpbxaygl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gt2elyttmrh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cucudq.cn/Article/details/gt2ldxogzyh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.andypj.xyz/Article/details/gt2tceivhwz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zdqjudy.top/Article/details/gt2yaqguskr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yonumen.top/Article/details/gt2pmamggjv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zdqjudy.top/Article/details/gt2vcojsjnb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnxiangtu.top/Article/details/gt2jnrhdyys.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gt2hntborcr.html

[H10] 资源自动释放
来源：http://dali.yuxming.cn/Article/details/gt2wldufzbf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fnvhihrp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.snrcjt.cn/Article/details/gt2aooomlzh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gt2jszuxbzk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mbmcxfwh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ppjwa.cn/Article/details/gt2evgmolmv.html

Go:   defer f.Close()
来源：http://dali.yanxiufei.cn/Article/details/gt2uztrapbs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xziqi.cn/Article/details/gt2ykazjosl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2sypbuyie.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ttifegdu.html

I. 正则表达式
来源：http://dali.zhengqikj.top/Article/details/gt2wjlsbfpx.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2khfcnjst.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2uslrhpvs.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2xgvolqsy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2aucwilrn.html

JS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gt2ugglkjqn.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gt2cimsjpfg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.birdmap.top/Article/details/gt2siogiknx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yueranfly.top/Article/details/gt2oswxllvo.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gt2ddnpqids.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.c1oappe.top/Article/details/gt2gszofwri.html

[I02] 提取所有匹配
来源：http://dali.redwolf501.top/Article/details/gt2worsmpgo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gt2jppiojqq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.andypj.xyz/Article/details/gt2ojofpovj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shangyingyoupin.top/Article/details/gt2lewnnuex.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgfzy.top/Article/details/gt2ummhhaul.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangdashe.top/Article/details/gt2mrahalnh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gt2cqeifyzt.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gt2lhckuhcu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2pfdkviso.html

[I03] 提取捕获分组
来源：http://dali.jinqigfzy.top/Article/details/gt2mthhyzkk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.tanke756.top/Article/details/gt2saouwdop.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2fnjrjybi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.0kj1m.cn/Article/details/gt2mkorfxbs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fockzyxg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.redwolf501.top/Article/details/gt2ijivexhg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gotoacloud.top/Article/details/gt2wicpgrvd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenlongwang.top/Article/details/gt2xlyrtxpg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pqjvxdga.html

[I04] 正则替换
来源：http://dali.bjfxy.top/Article/details/gt2emgkgfzq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nwbrower.top/Article/details/gt2mcmtnvkz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.guannengcc.top/Article/details/gt2acgikxkb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qiezpgls.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gt2jdoxrzzl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gt2zuonaoqb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.0kj1m.cn/Article/details/gt2nwaefyqi.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.dashuyun.cn/Article/details/gt2ouhfcjfl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.aizwys.cn/Article/details/gt2eodxvbid.html

[I05] 按正则拆分
来源：http://dali.tanke756.top/Article/details/gt2mkjgpgiy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.dashuyun.cn/Article/details/gt2cmlibgkp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2ndgieunu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gt2qslileei.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pengpengdd.cyou/Article/details/gt2agtidvja.html


<!-- 参考信息 -->