代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenlongwang.top/Article/details/gtantixlfo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtbsanmamn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtyxwlcwpi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tanke756.top/Article/details/gtwhvbjrgv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cqqwz.cn/Article/details/gtsdxlcmuq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtsmvhjeab.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gtrfabfqje.html

[F12] CSV 读写
来源：http://dali.cqqwz.cn/Article/details/gtuvimfhvk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cashguo.top/Article/details/gtnuudnhee.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhengqikj.top/Article/details/gtaygfcuip.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangdashe.top/Article/details/gtvopgrqmb.html

TS:   // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbcqxncj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xinyue.icu/Article/details/gtkjitktyf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.316326.xyz/Article/details/gtafckafer.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangshuangyany.cn/Article/details/gtawtmzxxg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gzhubu.top/Article/details/gtpimnwrzq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttxjyphve.html

G. 面向对象
来源：http://dali.gzhubu.top/Article/details/gtvfcidpkw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtunvlrzbt.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gtqwycjjku.html

Py:   class User: pass
来源：http://dali.cqqwz.cn/Article/details/gtydyovjtv.html

PHP:  class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtlebikpeb.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtgpwbarov.html

TS:   class User { name: string = ""; }
来源：http://dali.daxiang520.top/Article/details/gtfiazxpzs.html

Java: class User {}
来源：http://dali.xinyue.icu/Article/details/gteesrjofk.html

Go:   type User struct { Name string }
来源：http://dali.wangdashe.top/Article/details/gtsavndbxq.html

Ruby: class User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtzbhpaaic.html

C#:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtrpryjnfw.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gthnbpketa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pycfn.com/Article/details/gthpekdtbp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gtxwhatroy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gtzfedwsgc.html

TS:   constructor(public name: string) {}
来源：http://dali.xylfe.cn/Article/details/gtkyjlhhga.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoabwcjbc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gtegfajymv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daria6918.cn/Article/details/gttlrlsitm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtnvopfjwh.html

[G03] 实例属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcahojpu.html

Py:   self.name = "x"
来源：http://dali.sxryk.cn/Article/details/gttffeevhc.html

PHP:  public string $name = "x";
来源：http://dali.aizwys.cn/Article/details/gtghvedzyq.html

JS:   this.name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtjdlpuhwy.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gthtkdgszv.html

Java: private String name;
来源：http://dali.aizwys.cn/Article/details/gtohqrhauy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guowangkeji.top/Article/details/gtbkvzcfyq.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkcmyzgv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.iojbl.cn/Article/details/gtayireoxn.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gtforooukh.html

Py:   def greet(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtudgcynjd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtejajwxmx.html

JS:   greet() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqjbxipr.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtqhvtipfo.html

Java: String greet() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtwrcpqkiw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gtcxdugieo.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gthlnhykst.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gtvfylmrxt.html

[G05] 继承
来源：http://dali.yonumen.top/Article/details/gtuxwiysae.html

Py:   class Admin(User): pass
来源：http://dali.cheryme.top/Article/details/gtxhoeamnk.html

PHP:  class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtahwwtkkt.html

JS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtdfacpfpk.html

TS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtlfaimbwy.html

Java: class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtuqwpezsx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yanxiufei.cn/Article/details/gtxwsdilsg.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gtyeptzdbm.html

C#:   class Admin : User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtdvhengep.html

[G06] 重写方法
来源：http://dali.nwbrower.top/Article/details/gtbabvzudd.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvhuboiq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtidifrqqs.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gthwvnickl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtkmichzhl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtdrxpehvh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.bjfxy.top/Article/details/gtlmtyslkk.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxuanxn.top/Article/details/gtfvonwgac.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gtrblwjite.html

[G07] 调用父类方法
来源：http://dali.hnqzz.top/Article/details/gtiagfcyqk.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gthzokamxd.html

PHP:  parent::greet();
来源：http://dali.xuanzx.com/Article/details/gtyktemyfl.html

JS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtlbqpvrce.html

TS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gtwdvbwsng.html

Java: super.greet();
来源：http://dali.ivvv.top/Article/details/gtubqqbxpx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cdnleiting.top/Article/details/gtqrvkudyt.html

Ruby: super
来源：http://dali.316326.xyz/Article/details/gtjynzsaqq.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gtwjyffzjo.html

[G08] 静态方法与属性
来源：http://dali.jinqigfzy.top/Article/details/gtiltjnuws.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hysaishi.cn/Article/details/gtmmxotlqi.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gtgqqizpoy.html

JS:   static f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtrizxysew.html

TS:   static f(): void {}
来源：http://dali.bjfxy.top/Article/details/gtdlqbmeue.html

Java: static void f() {}
来源：http://dali.wangdashe.top/Article/details/gtxejpoixm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhoulong.xyz/Article/details/gttysofdis.html

Ruby: def self.f; end
来源：http://dali.jinqigufen.top/Article/details/gtabeqvnlk.html

C#:   public static void F() {}
来源：http://dali.xziqi.cn/Article/details/gtjdkrxqlv.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gtbvhbdwuz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gtjgrxwljj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvebiobfk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gthhcblsur.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gtrqnqfmyz.html

Java: interface Shape { double area(); }
来源：http://dali.vqdsnc.cn/Article/details/gtkgjyjqqn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gtqeasepou.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gtwdyfzhdv.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagchgbuy.html

[G10] 访问控制
来源：http://dali.yuanzhike.top/Article/details/gtpdtprcot.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gtspaaoksr.html

PHP:  public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtvlfsziib.html

JS:   #private 字段；其余公开
来源：http://dali.nwbrower.top/Article/details/gtczltenaf.html

TS:   public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtcaztnyna.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gtzpnkbwid.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gtjhfomnvk.html

Ruby: public / protected / private
来源：http://dali.tanke756.top/Article/details/gtgnsljcny.html

C#:   public / protected / private / internal
来源：http://dali.yuxming.cn/Article/details/gtlbzuchaf.html

[G11] getter / setter
来源：http://dali.nanxuanxn.top/Article/details/gttjigzxnu.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gturhvpxxr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gttabdsbbi.html

JS:   get name() { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtgztotsgw.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtdjgmycee.html

Java: public String getName() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gthogjplxl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtsxhuvbri.html

Ruby: attr_accessor :name
来源：http://dali.nanxinkj.top/Article/details/gtcnrcrcyf.html

C#:   public string Name { get; set; }
来源：http://dali.fengsongda.top/Article/details/gtrkrxgupp.html

[G12] 对象转字符串
来源：http://dali.ydzc1.top/Article/details/gtkqfdhxvb.html

Py:   def __str__(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gtyfuxuzpm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtyooscmbu.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtdlxjjsxp.html

TS:   toString(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtuamiknnf.html

Java: @Override public String toString() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtntjajquu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtvizpwmse.html

Ruby: def to_s; @name; end
来源：http://dali.yvedp.cn/Article/details/gtgwlbnszf.html

C#:   public override string ToString() => Name;
来源：http://dali.yangfankeji.com/Article/details/gtxkwphfxp.html

[G13] 判断对象类型
来源：http://dali.gotoacloud.top/Article/details/gtomneqvsk.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gtvwvjdjex.html

PHP:  $u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtleaheeya.html

JS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtibjawriv.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtrpvuealn.html

Java: u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtkzcgnbkg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gtdsunlmja.html

Ruby: u.is_a?(User)
来源：http://dali.cqqwz.cn/Article/details/gtoythirgy.html

C#:   u is User
来源：http://dali.wangdashe.top/Article/details/gtfuriwwjx.html

[G14] 数据类 / record
来源：http://dali.xuetiantiany.cn/Article/details/gtdsruqehg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnxoakeh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yonumen.top/Article/details/gtcuzoxzej.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fzhhl.top/Article/details/gtbcwmxbco.html

TS:   type User = { name: string; age: number };
来源：http://dali.jiagoushi.top/Article/details/gtpoykocet.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gtwnefnszo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gtbtbhympq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gaohongyu789.top/Article/details/gtyzkbrnrb.html

C#:   record User(string Name, int Age);
来源：http://dali.gotoacloud.top/Article/details/gtgfykfnrp.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gtsmoyqjoq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yvedp.cn/Article/details/gtmfdvtjag.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.0kj1m.cn/Article/details/gtphixudvu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.smart0.xyz/Article/details/gtrukqjtvk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gtfqkmzueq.html

Java: enum Color { RED, GREEN }
来源：http://dali.jyoumei.cn/Article/details/gtzhdlotbv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gtqclubqss.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gtaqafgjlb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtfyotpmba.html

[G16] 对象转数组 / 字典
来源：http://dali.dianchejie.cn/Article/details/gtlgkkkhid.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.bjfxy.top/Article/details/gtkseiijtg.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gtgcxzcqcn.html

JS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtzfpzjcaw.html

TS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gtwgzapydk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zycfv.cn/Article/details/gthqsmblge.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjxurrte.html

Ruby: obj.instance_variables
来源：http://dali.hnxiangtu.top/Article/details/gtmarkwche.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtshfjhbut.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtihmfpkta.html

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gtgvbirytw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtsamixpcp.html

[H01] try / catch 基础
来源：http://dali.gogol.net.cn/Article/details/gtahtvzcnv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gtwrmjxjrc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangdashe.top/Article/details/gtzeyozuwi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtpslsnahr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtptzndjrc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dianchejie.cn/Article/details/gtuxpiavdx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.svipenyu.cn/Article/details/gtqhviizqj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daxiang520.top/Article/details/gtehfwupnr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenjidiqi.icu/Article/details/gtvygyzhty.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gtrlpmjbee.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.havefunace.top/Article/details/gtactosjxt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtqllwynql.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtswmrybbh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtqimzegiz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtudaavgto.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gtvuydoqwk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuxming.cn/Article/details/gtadowriaj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtsoxodjqk.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtubeqnazm.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhongyouzk.top/Article/details/gtwtwaoglx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtapafzanj.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhvchzhb.html

TS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gttyhkhkyb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtlgsyxgnq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gtwzanezuw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jiagoushi.top/Article/details/gtqjsxaayg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtxotdlfve.html

[H04] 自定义异常类型
来源：http://dali.jyoumei.cn/Article/details/gtfcnrpjbh.html

Py:   class MyError(Exception): pass
来源：http://dali.nwbrower.top/Article/details/gtmjemtfla.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtxkqsxpgo.html

JS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gtjtatrhat.html

TS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtryngbqmj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gtyevutxph.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gtofnmamsf.html

Ruby: class MyError < StandardError; end
来源：http://dali.aibaodan.cn/Article/details/gtcuigecqh.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gtrdxkrmkd.html

[H05] 捕获特定类型
来源：http://dali.jlsjyb.cn/Article/details/gtxfvzanil.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gtqbrgejzz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xinyue.icu/Article/details/gtzpxzfrte.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gtdxxvvrlb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtvlqmxqlt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.haohaochexian.top/Article/details/gtiyqnembe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sweek.top/Article/details/gtwfeqkjcu.html

Ruby: rescue ArgumentError => e
来源：http://dali.ppjwa.cn/Article/details/gtxiwuqvfu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmfmgylc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.andypj.xyz/Article/details/gtrzniwckg.html

Py:   value = d.get("k") or default
来源：http://dali.ppjwa.cn/Article/details/gtlsazzdxn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtfgobgmew.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gthqxpkyzr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gtplghzhrm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gtiidqzofi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ybcxt.top/Article/details/gtbommefbl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fengsongda.top/Article/details/gtuaylmjbm.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gtxrhesxum.html

[H07] 断言
来源：http://dali.svipenyu.cn/Article/details/gtejfaidth.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jiagoushi.top/Article/details/gtynceohtb.html

PHP:  assert($x > 0);
来源：http://dali.havefunace.top/Article/details/gtoeseruiz.html

JS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokiyugdi.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtnjygtrhw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gtrqvywhjl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gtwhowoiwk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hywenlv.cn/Article/details/gtlpdhvjvt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtbnbeikpa.html

[H08] 获取错误信息与堆栈
来源：http://dali.pengpengdd.cyou/Article/details/gtdkyzegyk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.kuanghao11.cn/Article/details/gtxldfxyce.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gtfkppkcty.html

JS:   e.message;  e.stack
来源：http://dali.bjfxy.top/Article/details/gtevnhdfba.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tian-w.cn/Article/details/gtseabohfl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sufxvd.cn/Article/details/gtqhqntwhy.html

Go:   err.Error()
来源：http://dali.yj202588.top/Article/details/gtkhlocgss.html

Ruby: e.message;  e.backtrace
来源：http://dali.fengsongda.top/Article/details/gtlbetavlm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yvedp.cn/Article/details/gttvpvuoqt.html

[H09] 带错误码的异常
来源：http://dali.gotoacloud.top/Article/details/gthcyvnims.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nwbrower.top/Article/details/gtbonkihay.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cdnleiting.top/Article/details/gtwtaprqal.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gtktoritnn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndsmhtzi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.andypj.xyz/Article/details/gtoqpyexoa.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangshuangyany.cn/Article/details/gttalmxfrt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gttxnbahuq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ydzc1.top/Article/details/gturpkxdjn.html

[H10] 资源自动释放
来源：http://dali.hongshengwenyu.top/Article/details/gtjzanxjtb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gtuocczxld.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuanzhike.top/Article/details/gtpieaggel.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtoevhmsxh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gtklknnepe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxinkj.top/Article/details/gtrgunvnfo.html

Go:   defer f.Close()
来源：http://dali.yanxiufei.cn/Article/details/gtbmsexmqq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgufenzy.top/Article/details/gthiaxewmi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtxojoadky.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gthwcadhvf.html

I. 正则表达式
来源：http://dali.aibaodan.cn/Article/details/gtghttnasb.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtbcwdivbf.html

[I01] 判断是否匹配
来源：http://dali.sufxvd.cn/Article/details/gthfqadpit.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gtellmoehk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sweek.top/Article/details/gtgcfegtxe.html

JS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gtfbsxhrei.html

TS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtybccaqsj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nwbrower.top/Article/details/gttcqamsgy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guowangkeji.top/Article/details/gtftlrmqfs.html

Ruby: s.match?(/\d+/)
来源：http://dali.ivvv.top/Article/details/gthniarqar.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gtkpctnkud.html

[I02] 提取所有匹配
来源：http://dali.yongpay.top/Article/details/gtpsuzudkx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gtffgbaahz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tanke756.top/Article/details/gtxzmwdjcu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cheryme.top/Article/details/gtsotxbvyp.html

TS:   s.match(/\d+/g)
来源：http://dali.xuanzx.com/Article/details/gtdrzjvkew.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.havefunace.top/Article/details/gtfkappopa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yongpay.top/Article/details/gtsudvqguz.html

Ruby: s.scan(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gtrwmnakez.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtnafxnlas.html

[I03] 提取捕获分组
来源：http://dali.jinqigufen.top/Article/details/gtgappzorm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gtuynxoske.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnqzz.top/Article/details/gtnlqgoezk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gtcjmgzgqb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hysaishi.cn/Article/details/gtorgpbhby.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hammf.cn/Article/details/gtgwwptnvh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.fengsongda.top/Article/details/gtnventzrt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hysaishi.cn/Article/details/gthovwoytf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangtech.top/Article/details/gthgmahofb.html

[I04] 正则替换
来源：http://dali.quarkkingdee.top/Article/details/gtqsxldrhs.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gaohongyu789.top/Article/details/gthvwpbufr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hammf.cn/Article/details/gtrlnsyndi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.fzhhl.top/Article/details/gtrltyjvnn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gtvqrhgbfi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yongpay.top/Article/details/gthyobbsjf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shzxlz.cn/Article/details/gtnajzxhgx.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yonumen.top/Article/details/gtpdwgwhwm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gtezaeiubr.html

[I05] 按正则拆分
来源：http://dali.zhengqikj.top/Article/details/gtxiuryycn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbunwksol.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yongpay.top/Article/details/gtqitgggui.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gtqetvzgnu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtxpdsxcuh.html


<!-- 参考信息 -->