代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gthpxkejfc.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtnsashgul.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgufenzy.top/Article/details/gtdcqcomom.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtcwlwjkdd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtiagfqwcn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtjrpgefjc.html

[F11] 复制与移动文件
来源：http://dali.cucudq.cn/Article/details/gtbrvyvmuo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtmihappun.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtgwzeenkz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtcdncdsuc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtubzbparo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gthfnqxrat.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gtbwilfrgb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtmcavviol.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gtelcodlpj.html

[F12] CSV 读写
来源：http://dali.guannengcc.top/Article/details/gtqawgpxju.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yangfankeji.com/Article/details/gtybtsykcc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yongpay.top/Article/details/gtivoodzjf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hongshengwenyu.top/Article/details/gtoafzewtb.html

TS:   // 同上
来源：http://dali.shzxlz.cn/Article/details/gtwblfigfc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gtptvatsur.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuxming.cn/Article/details/gtacxgfalm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.andypj.xyz/Article/details/gtemlccdpq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gaohongyu789.top/Article/details/gthxvlfhbc.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdabocuv.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gtycarxbke.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtwijvgbpv.html

[G01] 定义类
来源：http://dali.fzhhl.top/Article/details/gtyjkdzrss.html

Py:   class User: pass
来源：http://dali.wangshuangyany.cn/Article/details/gtagpnshnm.html

PHP:  class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtwbpueobb.html

JS:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gttcxteisa.html

TS:   class User { name: string = ""; }
来源：http://dali.daxiang520.top/Article/details/gttepaegva.html

Java: class User {}
来源：http://dali.xuanzx.com/Article/details/gtisasvyay.html

Go:   type User struct { Name string }
来源：http://dali.mhx1999.top/Article/details/gtccomjrwj.html

Ruby: class User; end
来源：http://dali.yuanzhike.top/Article/details/gttclgdfqm.html

C#:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtotroujuv.html

[G02] 构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtidorxcvx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gtiikwwhxx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenlongwang.top/Article/details/gtblxnzlnl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtsfpflpvo.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gtzmavkpez.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtpttqygjj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gtxfhpfols.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.c1oappe.top/Article/details/gtoamgjaat.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xylfe.cn/Article/details/gtpliqbvrl.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gtrkfhywfc.html

Py:   self.name = "x"
来源：http://dali.tanke756.top/Article/details/gtbtogwplp.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtlaxfpfcv.html

JS:   this.name = "x";
来源：http://dali.tanke756.top/Article/details/gtmjdwoqmq.html

TS:   name: string = "x";
来源：http://dali.dashuyun.cn/Article/details/gtttqaseft.html

Java: private String name;
来源：http://dali.quarkkingdee.top/Article/details/gttcwssptn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gtlvfndgxa.html

Ruby: @name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtohikzbpe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258888.top/Article/details/gterlnmdik.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gtpsivfdgw.html

Py:   def greet(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtpgdotkzz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtimrcoajc.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtkuabtico.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gthyjlnxav.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gturctdjav.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtcpbfbbiq.html

Ruby: def greet; @name; end
来源：http://dali.ydzc1.top/Article/details/gtpfdhslil.html

C#:   public string Greet() => Name;
来源：http://dali.iojbl.cn/Article/details/gtkfrhaxuh.html

[G05] 继承
来源：http://dali.birdmap.top/Article/details/gtpdafpnzu.html

Py:   class Admin(User): pass
来源：http://dali.smart0.xyz/Article/details/gtdopvbmvl.html

PHP:  class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtaagcgqfh.html

JS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtjjbrgmdu.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtsqobgsuw.html

Java: class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtlogzgwan.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aizwys.cn/Article/details/gtlyyztbsa.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gttshudvii.html

C#:   class Admin : User {}
来源：http://dali.dashuyun.cn/Article/details/gtbvhdkvge.html

[G06] 重写方法
来源：http://dali.hywenlv.cn/Article/details/gtneftmzcm.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiattumis.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtthioxblp.html

JS:   greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtyveookux.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtsusjgdnf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtelznwybg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cucudq.cn/Article/details/gtginxwqyf.html

Ruby: def greet; "admin"; end
来源：http://dali.jlsjyb.cn/Article/details/gtxktpecym.html

C#:   public override string Greet() => "admin";
来源：http://dali.cheryme.top/Article/details/gtidsunvvi.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwqwnolnh.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gtcfzybzkj.html

PHP:  parent::greet();
来源：http://dali.sxryk.cn/Article/details/gtsvngeify.html

JS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gtujwxdamn.html

TS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtbbttfpgh.html

Java: super.greet();
来源：http://dali.daria6918.cn/Article/details/gtxyyxgypr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.snrcjt.cn/Article/details/gtwokkqgzo.html

Ruby: super
来源：http://dali.hnxiangtu.top/Article/details/gtoxhbwnti.html

C#:   base.Greet();
来源：http://dali.yj202588.top/Article/details/gtimfrwwku.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gtmxyitcqd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cucudq.cn/Article/details/gtunsjajao.html

PHP:  public static function f() {}
来源：http://dali.bjfxy.top/Article/details/gtznpcewwv.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtkygwegcy.html

TS:   static f(): void {}
来源：http://dali.wangdashe.top/Article/details/gtgtpylajp.html

Java: static void f() {}
来源：http://dali.cucudq.cn/Article/details/gttdxyqguj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenzaomai.com/Article/details/gtrxhqpvuw.html

Ruby: def self.f; end
来源：http://dali.jyoumei.cn/Article/details/gtgfdtxuss.html

C#:   public static void F() {}
来源：http://dali.meibo888.top/Article/details/gtcyiffjby.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgkpvgtb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fengsongda.top/Article/details/gtzsaqbrbw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zycfv.cn/Article/details/gtortwwwbm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cucudq.cn/Article/details/gtkssngajm.html

TS:   interface Shape { area(): number; }
来源：http://dali.cdnleiting.top/Article/details/gtrxcucmeu.html

Java: interface Shape { double area(); }
来源：http://dali.tian-w.cn/Article/details/gtbzfjfzld.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhoulong.xyz/Article/details/gtfyivsybw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gtsnenwbnt.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gtiunqgiyl.html

[G10] 访问控制
来源：http://dali.zdqjudy.top/Article/details/gtldrqpuxa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.mhx1999.top/Article/details/gttbvrwqjq.html

PHP:  public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtqdtmushs.html

JS:   #private 字段；其余公开
来源：http://dali.cucudq.cn/Article/details/gtnhnzuwil.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtmcbjvqfc.html

Java: public / protected / private / 默认包级
来源：http://dali.yj202588.top/Article/details/gtphsssnpo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmiopxdb.html

Ruby: public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtuoqkhggm.html

C#:   public / protected / private / internal
来源：http://dali.aibaodan.cn/Article/details/gtzenkespo.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gtgjpglkaj.html

Py:   @property 与 @x.setter
来源：http://dali.shuidangran.top/Article/details/gtlfgopkff.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtdqgifjeo.html

JS:   get name() { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtclyzrkhk.html

TS:   get name(): string { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtehnbzsce.html

Java: public String getName() { return name; }
来源：http://dali.havefunace.top/Article/details/gtovdmwsxl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtbwakwlti.html

Ruby: attr_accessor :name
来源：http://dali.chenjidiqi.icu/Article/details/gtasqsthln.html

C#:   public string Name { get; set; }
来源：http://dali.ehwqpu.com/Article/details/gtzyqfiuge.html

[G12] 对象转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtrbjnneyu.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtxbdolfke.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtssycnsae.html

JS:   toString() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtptkzvcyy.html

TS:   toString(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtcxeoghho.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtlhxevdnk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtadiufkls.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtnxbopnpq.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gtztzfkyfe.html

[G13] 判断对象类型
来源：http://dali.gzhubu.top/Article/details/gtipblryel.html

Py:   isinstance(u, User)
来源：http://dali.tian-w.cn/Article/details/gtwufpooup.html

PHP:  $u instanceof User
来源：http://dali.cashguo.top/Article/details/gtaoufzlaz.html

JS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gthomwkdpb.html

TS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gtbpxjmmnf.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gttctqovit.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvkvjceb.html

Ruby: u.is_a?(User)
来源：http://dali.gzhubu.top/Article/details/gtemjazqjn.html

C#:   u is User
来源：http://dali.tianlin.xyz/Article/details/gtigjoqede.html

[G14] 数据类 / record
来源：http://dali.dianchejie.cn/Article/details/gtopmeilnp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjpedzka.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sxryk.cn/Article/details/gtxoakravg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.vqdsnc.cn/Article/details/gtzfzbjliy.html

TS:   type User = { name: string; age: number };
来源：http://dali.shangyingyoupin.top/Article/details/gtgowuctex.html

Java: record User(String name, int age) {}
来源：http://dali.fengsongda.top/Article/details/gtwnkuvccj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yvedp.cn/Article/details/gtzyltnags.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cucudq.cn/Article/details/gthtdvkzws.html

C#:   record User(string Name, int Age);
来源：http://dali.hongshengwenyu.top/Article/details/gtaktqnqlu.html

[G15] 枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtbyldkflj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gtfvwullmb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenzaomai.com/Article/details/gtvkkslbnx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gtrgzgufks.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtmaccapcr.html

Java: enum Color { RED, GREEN }
来源：http://dali.fzhhl.top/Article/details/gtmyhohvwd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxinkj.top/Article/details/gtlubyoayq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sysykeji.top/Article/details/gtsylsmolk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtblynvnts.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gtktdsxezq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jianghu66.top/Article/details/gtlpfdjuda.html

PHP:  get_object_vars($obj);
来源：http://dali.guowangkeji.top/Article/details/gtkgpqcgfa.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtwqpzwmoe.html

TS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gtczkftsez.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigufen.top/Article/details/gtqsziwpkb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.havefunace.top/Article/details/gtxxkrzogh.html

Ruby: obj.instance_variables
来源：http://dali.zhoulong.xyz/Article/details/gtrmabxykz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangdashe.top/Article/details/gtwakzpodk.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtfaxkocbl.html

H. 异常与错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauoobaoa.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtdrxzgtol.html

[H01] try / catch 基础
来源：http://dali.aizwys.cn/Article/details/gtuodwtviy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ppjwa.cn/Article/details/gtrgnuickt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.0kj1m.cn/Article/details/gtgkbdxmbc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtvurbhpdz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtpwgasclb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gtxmofnqcu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gtvdgmynrn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sweek.top/Article/details/gtejchraxz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmcyxvdf.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gtngvvlbov.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yanxiufei.cn/Article/details/gtjwyofvvu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttilwsrov.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtpxbjzbzh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtbmucilpb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtmfgzvbcf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hysaishi.cn/Article/details/gtruomlrwm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258.top/Article/details/gtasqzhojh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtselwzdkn.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gtrywpgcog.html

Py:   raise ValueError("错误信息")
来源：http://dali.jianghu66.top/Article/details/gtaelncefm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtdpvtltoo.html

JS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtlgsutnca.html

TS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gttddyyczf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilwgaycq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ydzc1.top/Article/details/gtymqlmrhj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cashguo.top/Article/details/gtormdqkho.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtalgikxha.html

[H04] 自定义异常类型
来源：http://dali.cashguo.top/Article/details/gtgcofitlh.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gtjpddpbha.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtjiiqbmbk.html

JS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtrshrisxq.html

TS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gtndsycoep.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtapbmhptg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinghuilouyu.cn/Article/details/gteuuzhlxt.html

Ruby: class MyError < StandardError; end
来源：http://dali.snrcjt.cn/Article/details/gtfubwznmw.html

C#:   class MyException : Exception {}
来源：http://dali.snrcjt.cn/Article/details/gtoqdbnnwv.html

[H05] 捕获特定类型
来源：http://dali.birdmap.top/Article/details/gtsbazfdxm.html

Py:   except ValueError as e:
来源：http://dali.jqgfzy.top/Article/details/gtgnmliiyu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hysaishi.cn/Article/details/gtycgyokml.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtjrorsshs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gtvrbjhqww.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gtyahdvwgd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pengpengdd.cyou/Article/details/gtfnpuuxbe.html

Ruby: rescue ArgumentError => e
来源：http://dali.yonumen.top/Article/details/gtojekgnbg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gtzyvwzyna.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuetiantiany.cn/Article/details/gtadkkfojh.html

Py:   value = d.get("k") or default
来源：http://dali.hywenlv.cn/Article/details/gtpqonshfl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sweek.top/Article/details/gtwyikupxi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gtpnutbfql.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gtgfhcdugs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.guannengcc.top/Article/details/gtadicfwlp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.smart0.xyz/Article/details/gtprhemtzs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pycfn.com/Article/details/gtdebjctxw.html

C#:   obj?.A?.B ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtqqlxuboy.html

[H07] 断言
来源：http://dali.vqdsnc.cn/Article/details/gtwinjfkkc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxnmdhfc.html

PHP:  assert($x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtwbuevkmn.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtyqrdyyrs.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtxalfrrxq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tanke756.top/Article/details/gtaxlxmnws.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258888.top/Article/details/gtremkcyqm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gtubsnejmy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtpezsowbw.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gtxtdsiwod.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxuanxn.top/Article/details/gtmswkymhc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hongshengwenyu.top/Article/details/gtqvoupeeb.html

JS:   e.message;  e.stack
来源：http://dali.jqgfzy.top/Article/details/gtdedagigr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gtnqxjzmuz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.andypj.xyz/Article/details/gtkuxtbgun.html

Go:   err.Error()
来源：http://dali.mhx1999.top/Article/details/gtsndswpce.html

Ruby: e.message;  e.backtrace
来源：http://dali.xziqi.cn/Article/details/gtwsytbpsj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yvedp.cn/Article/details/gtjvjgbklb.html

[H09] 带错误码的异常
来源：http://dali.quarkkingdee.top/Article/details/gtiahtqxyu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyayyoveo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgufenzy.top/Article/details/gtvcyvogal.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gtgrywworo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gaohongyu789.top/Article/details/gtzfhhyyeg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.iojbl.cn/Article/details/gtypllraym.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnqzz.top/Article/details/gtbaplaqxv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenlongwang.top/Article/details/gthusczioe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hfpthk.cn/Article/details/gtqdwbnrdv.html

[H10] 资源自动释放
来源：http://dali.zdqjudy.top/Article/details/gtohpeodik.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhixingplan.top/Article/details/gtygufcmge.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gtinwvtqtu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gtyijoyoew.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtezjmlofh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yangfankeji.com/Article/details/gtepixxtiu.html

Go:   defer f.Close()
来源：http://dali.ehwqpu.com/Article/details/gtwwruihra.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tanke756.top/Article/details/gtyhqsblmt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gtdujamxrf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfwcciqww.html

I. 正则表达式
来源：http://dali.xylfe.cn/Article/details/gtcolktacw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtvqlyodkh.html

[I01] 判断是否匹配
来源：http://dali.zhongyouzk.top/Article/details/gtxthvxecc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gtqgbexxfo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gttmopsbsv.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtsuzfoxbq.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtyymbhfgb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.meibo888.top/Article/details/gtvieoxyst.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gtpscukepm.html

Ruby: s.match?(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtmqqgcepl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shuidangran.top/Article/details/gtwgazuuim.html

[I02] 提取所有匹配
来源：http://dali.cdnleiting.top/Article/details/gtyenzdglo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gtxswtpszr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hammf.cn/Article/details/gtgidpfxgy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenlongwang.top/Article/details/gtwerhieqe.html

TS:   s.match(/\d+/g)
来源：http://dali.vqdsnc.cn/Article/details/gtdawribiv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuxming.cn/Article/details/gtufdxbwcm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gtlaicomya.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gtkikqtgsx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gticjapfyr.html

[I03] 提取捕获分组
来源：http://dali.zhiwuduotai.top/Article/details/gtipzrhvni.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxuanxn.top/Article/details/gtgqlzhzup.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yangfankeji.com/Article/details/gtpwmrlrse.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gogol.net.cn/Article/details/gtfrtwrooo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guowangkeji.top/Article/details/gtoxcruteb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.daxiang520.top/Article/details/gtonzbeuxb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tian-w.cn/Article/details/gtdtumegie.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gthiskkpac.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yvedp.cn/Article/details/gthnlmfuab.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gtxokyzatn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.sweek.top/Article/details/gttjyowfaq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtutaorapj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jiagoushi.top/Article/details/gtoebdivvr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtcswcgymm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtnxzijcpl.html


<!-- 参考信息 -->