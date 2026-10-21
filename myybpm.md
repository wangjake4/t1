代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtsxfrepsr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtyzcfcxgo.html

[F11] 复制与移动文件
来源：http://dali.fengsongda.top/Article/details/gtgunshoiw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtumohrtlq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gtvhmmuzsv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtplpbdewq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtuomfkvpo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.c1oappe.top/Article/details/gtbnhoqhzr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gtoilgvivu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtthhcpvbr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.smart0.xyz/Article/details/gtzfmofyaa.html

[F12] CSV 读写
来源：http://dali.zhiwuduotai.top/Article/details/gtrvjunjjk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gtvifkirry.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cdnleiting.top/Article/details/gtupzpbfdr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuanzx.com/Article/details/gtiyrhvyiy.html

TS:   // 同上
来源：http://dali.ydzc1.top/Article/details/gtfcukpkft.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gtuygqzwcf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yangfankeji.com/Article/details/gtwiggvtne.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuxming.cn/Article/details/gtuecwjjby.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gtviluzuuk.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtnuoglruh.html

G. 面向对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpdfxkqv.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtkxphswow.html

[G01] 定义类
来源：http://dali.yj20258888.top/Article/details/gtdtfewefh.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gtfiystade.html

PHP:  class User {}
来源：http://dali.andypj.xyz/Article/details/gtmirovrdx.html

JS:   class User {}
来源：http://dali.mhx1999.top/Article/details/gtkkvjfynh.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gtjteolvhz.html

Java: class User {}
来源：http://dali.iojbl.cn/Article/details/gteznngiba.html

Go:   type User struct { Name string }
来源：http://dali.fengsongda.top/Article/details/gtpydkprjw.html

Ruby: class User; end
来源：http://dali.yj20258.top/Article/details/gtnuvvwewa.html

C#:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtvzopzdyy.html

[G02] 构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtaoecdxck.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xinyue.icu/Article/details/gtordrnblh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtigyrmizx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtppkdlxwl.html

TS:   constructor(public name: string) {}
来源：http://dali.guannengcc.top/Article/details/gtdgqebmwr.html

Java: User(String name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtgdfcbvoo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gtlribposa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxinkj.top/Article/details/gtvcxxtvra.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtdaltjurh.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gtuwjtrwhi.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gtbhvyuzkx.html

PHP:  public string $name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gthxgwwrwh.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldswcsom.html

TS:   name: string = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtaruvgynv.html

Java: private String name;
来源：http://dali.zhongyouzk.top/Article/details/gtejweivda.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pengpengdd.cyou/Article/details/gthcdssafo.html

Ruby: @name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtdtbicsdf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuxming.cn/Article/details/gtmsqdhhhk.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gtjaqgqgoy.html

Py:   def greet(self): return self.name
来源：http://dali.yonumen.top/Article/details/gttsbeewds.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtfsgcbmoc.html

JS:   greet() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtpwjlnsda.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtvzklxmhw.html

Java: String greet() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtdjkklsns.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtzenqyavf.html

Ruby: def greet; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gttvljnbeq.html

C#:   public string Greet() => Name;
来源：http://dali.meibo888.top/Article/details/gtdmbdhrws.html

[G05] 继承
来源：http://dali.haohaochexian.top/Article/details/gtdunsdehr.html

Py:   class Admin(User): pass
来源：http://dali.fengsongda.top/Article/details/gtyqbbelza.html

PHP:  class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gtenljdykt.html

JS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gthldddsnq.html

TS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtgwajgrlx.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtynaulzve.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznbeovjp.html

Ruby: class Admin < User; end
来源：http://dali.haohaochexian.top/Article/details/gtazoolthl.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvoclaixi.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gtsozimuyz.html

Py:   def greet(self): return "admin"
来源：http://dali.cucudq.cn/Article/details/gtxlpxawqg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtqyrzothb.html

JS:   greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtcvyxxtiq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtopznvzbt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtpegyavdi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenlongwang.top/Article/details/gthvdykezo.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gtxxbncwwk.html

C#:   public override string Greet() => "admin";
来源：http://dali.cashguo.top/Article/details/gtijbejeiy.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gtfwvlnojs.html

Py:   super().greet()
来源：http://dali.yj20258888.top/Article/details/gtuxiccabo.html

PHP:  parent::greet();
来源：http://dali.sweek.top/Article/details/gtnuhtjqmz.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtcmgweulk.html

TS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtfsbmwzvn.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gttpbvenwy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gtadkxcmgx.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gtkagvqabe.html

C#:   base.Greet();
来源：http://dali.birdmap.top/Article/details/gtkwnvmzez.html

[G08] 静态方法与属性
来源：http://dali.svipenyu.cn/Article/details/gtysgxsrcp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gtfidwwzem.html

PHP:  public static function f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbujgadb.html

JS:   static f() {}
来源：http://dali.nwbrower.top/Article/details/gtkcyaxqpp.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gtxydrudtl.html

Java: static void f() {}
来源：http://dali.yvedp.cn/Article/details/gtwvkwsnuz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cqqwz.cn/Article/details/gtsjjbosun.html

Ruby: def self.f; end
来源：http://dali.c1oappe.top/Article/details/gtkigjvotb.html

C#:   public static void F() {}
来源：http://dali.zhengqikj.top/Article/details/gttnshrkbl.html

[G09] 接口 / 抽象类
来源：http://dali.pycfn.com/Article/details/gtcthivcda.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jianghu66.top/Article/details/gtxawpocdl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gtbsetrrgd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gthzttlvip.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gtzgdafrvt.html

Java: interface Shape { double area(); }
来源：http://dali.daxiang520.top/Article/details/gtxapshrwv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pycfn.com/Article/details/gtzzfidspw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gttfumcdhy.html

C#:   interface IShape { double Area(); }
来源：http://dali.gzhubu.top/Article/details/gtuszdcefd.html

[G10] 访问控制
来源：http://dali.xziqi.cn/Article/details/gtdipmalwn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tianlin.xyz/Article/details/gtbnaxhocw.html

PHP:  public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gthhroizpv.html

JS:   #private 字段；其余公开
来源：http://dali.yanxiufei.cn/Article/details/gtdkbsdjwo.html

TS:   public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtajafyvfx.html

Java: public / protected / private / 默认包级
来源：http://dali.yj202588.top/Article/details/gtxfcfianz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.9152youxi.cn/Article/details/gtejyzzsiw.html

Ruby: public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtqlcahfcp.html

C#:   public / protected / private / internal
来源：http://dali.aizwys.cn/Article/details/gtznjosvln.html

[G11] getter / setter
来源：http://dali.guannengcc.top/Article/details/gtiqdwulmj.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258888.top/Article/details/gtgxmcxwyu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtmgcvyscw.html

JS:   get name() { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gtwalryoxs.html

TS:   get name(): string { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtfodhvzjp.html

Java: public String getName() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtvoxgcllf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtusogabkv.html

Ruby: attr_accessor :name
来源：http://dali.wangshuangyany.cn/Article/details/gtbondshau.html

C#:   public string Name { get; set; }
来源：http://dali.ivvv.top/Article/details/gtqmajrqua.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gtrmvynodv.html

Py:   def __str__(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtwvshluby.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtqlmfbsvd.html

JS:   toString() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtpymhfmri.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtgvojsxbf.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtpsnrbink.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtumduepyc.html

Ruby: def to_s; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtvqbdrvkg.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gthpitwcot.html

[G13] 判断对象类型
来源：http://dali.hnxiangtu.top/Article/details/gtbsdxgxid.html

Py:   isinstance(u, User)
来源：http://dali.c1oappe.top/Article/details/gtcnppajzj.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gticcqcagb.html

JS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtcunljmup.html

TS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtwfcowxio.html

Java: u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtjawkamuz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gthapwjbxq.html

Ruby: u.is_a?(User)
来源：http://dali.sysykeji.top/Article/details/gtpqmpucqx.html

C#:   u is User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnkesxyq.html

[G14] 数据类 / record
来源：http://dali.redwolf501.top/Article/details/gtjczpqjmh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyeuewzb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtflsxhzof.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gtgbttryag.html

TS:   type User = { name: string; age: number };
来源：http://dali.xinyue.icu/Article/details/gtnrmlzucd.html

Java: record User(String name, int age) {}
来源：http://dali.dianchejie.cn/Article/details/gtidwftbdi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gtdqfhjgkc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuanzx.com/Article/details/gttifshgna.html

C#:   record User(string Name, int Age);
来源：http://dali.zdqjudy.top/Article/details/gtymkrtbtq.html

[G15] 枚举
来源：http://dali.smart0.xyz/Article/details/gtfldmnuse.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nwbrower.top/Article/details/gtjkgvgins.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigufen.top/Article/details/gtbzuuqnog.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gtkppiyyxa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtynvxllvm.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gthrkmbhsy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cheryme.top/Article/details/gtcgzzgeab.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yvedp.cn/Article/details/gtqdwpeuvo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gttzntmuay.html

[G16] 对象转数组 / 字典
来源：http://dali.chenzaomai.com/Article/details/gtndgqvurn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangtech.top/Article/details/gtszsdgant.html

PHP:  get_object_vars($obj);
来源：http://dali.316326.xyz/Article/details/gthizopycd.html

JS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnmixqtp.html

TS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtasfshfyt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gtjisjeoyg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yonumen.top/Article/details/gtmipqaqnk.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gtcnutufcv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtereldrfa.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gthdvtxfei.html

H. 异常与错误处理
来源：http://dali.dashuyun.cn/Article/details/gtuslxdpai.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtatbshgiu.html

[H01] try / catch 基础
来源：http://dali.snrcjt.cn/Article/details/gtadkoxnkz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gtexqhohbg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gthacmihng.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtxgzaytnj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtwkxehble.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhixingplan.top/Article/details/gtivoxbvdq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhengqikj.top/Article/details/gtyipandps.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dashuyun.cn/Article/details/gthizfahad.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqikiqvw.html

[H02] finally / ensure 收尾
来源：http://dali.meibo888.top/Article/details/gtcvpsrcwm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojiapdbo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtieccuept.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gttjbecgtb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtzhttwzzt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gttuiavwvp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dashuyun.cn/Article/details/gtpuoylzlt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gtwzjpxjys.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtapanwmyk.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gtiltaicxc.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gtgttasihf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtmeyuuexd.html

JS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gtopzagycn.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxhyfvgi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtlmozuwkv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.iojbl.cn/Article/details/gtyrvlzfqg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ehwqpu.com/Article/details/gthszsybvq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtbkiainfv.html

[H04] 自定义异常类型
来源：http://dali.quarkkingdee.top/Article/details/gtwwjteivw.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gtntfifajo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gtybzfatfw.html

JS:   class MyError extends Error {}
来源：http://dali.xziqi.cn/Article/details/gtxzpukzvf.html

TS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtulzcrltb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtkuxmzmsi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dashuyun.cn/Article/details/gtolefwvao.html

Ruby: class MyError < StandardError; end
来源：http://dali.kuanghao11.cn/Article/details/gtntnnmitv.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gtapfmrbid.html

[H05] 捕获特定类型
来源：http://dali.hysaishi.cn/Article/details/gtznwrskba.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gtlnqydkmi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dianchejie.cn/Article/details/gtermbmkmx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gtfsmojdfy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gtqkumugjj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gtrjivmlcc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zycfv.cn/Article/details/gtnbccsqhi.html

Ruby: rescue ArgumentError => e
来源：http://dali.snrcjt.cn/Article/details/gtmcbvsuhk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gttidsubqh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sufxvd.cn/Article/details/gtmgkqmlwt.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gtwvgqvfrc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gtoslqndsn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gtzqnxhhxs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtysvqjafi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.redwolf501.top/Article/details/gtzovkwknh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.0kj1m.cn/Article/details/gtbjtgnhaw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gtkxrckjth.html

C#:   obj?.A?.B ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtvrhmewqr.html

[H07] 断言
来源：http://dali.jqgfzy.top/Article/details/gtedjygbrk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.feifeiyinyue.top/Article/details/gtaurmfxvh.html

PHP:  assert($x > 0);
来源：http://dali.sysykeji.top/Article/details/gtdptapfmx.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtabznlouf.html

TS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtkysvjadf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gtkljiklja.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cucudq.cn/Article/details/gttkypppgh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangdashe.top/Article/details/gtuglhiihm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtukqbguhi.html

[H08] 获取错误信息与堆栈
来源：http://dali.shzxlz.cn/Article/details/gtwydepadu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxinkj.top/Article/details/gtnlurdods.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gtzuqkmqdm.html

JS:   e.message;  e.stack
来源：http://dali.jlsjyb.cn/Article/details/gtiskeunjl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yangfankeji.com/Article/details/gtkzsbfcjd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jiagoushi.top/Article/details/gtqpsdhbhk.html

Go:   err.Error()
来源：http://dali.pycfn.com/Article/details/gtytmcvyuc.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gtzbloftxe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhijiandao.cn/Article/details/gtuqdovlkq.html

[H09] 带错误码的异常
来源：http://dali.cheryme.top/Article/details/gtljdjuflu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gaohongyu789.top/Article/details/gttvktonvo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hnqzz.top/Article/details/gtsbqhndgp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gtznmpyjld.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hysaishi.cn/Article/details/gtwugwrifi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gtvscvxhys.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gtexwgtnzy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yangfankeji.com/Article/details/gtuewmgmzz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfjfytha.html

[H10] 资源自动释放
来源：http://dali.yangfankeji.com/Article/details/gtdvbnkwqj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuanzhike.top/Article/details/gtywszknzb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxuanxn.top/Article/details/gtpyvmoxiz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtemjueajp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtsbjoqgfx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cheryme.top/Article/details/gtfngwbqrk.html

Go:   defer f.Close()
来源：http://dali.316326.xyz/Article/details/gtwdttktzd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrziykoye.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258.top/Article/details/gtsvohwqfc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtrpejmleo.html

I. 正则表达式
来源：http://dali.ybcxt.top/Article/details/gtxsjnarye.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtuucxicqk.html

[I01] 判断是否匹配
来源：http://dali.hnqzz.top/Article/details/gtcdilixzu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gtqfgoevwe.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hnqzz.top/Article/details/gtzfjirnws.html

JS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gthjyjolhd.html

TS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gtwluszoii.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pengpengdd.cyou/Article/details/gtmqugsxab.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yangfankeji.com/Article/details/gtkkczwfnd.html

Ruby: s.match?(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gthspeiycp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hywenlv.cn/Article/details/gtvuhrzzbe.html

[I02] 提取所有匹配
来源：http://dali.tianlin.xyz/Article/details/gtdwggnupw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.snrcjt.cn/Article/details/gtqzdlnzgz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuetiantiany.cn/Article/details/gtbyypyqbr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.dianchejie.cn/Article/details/gtholiiogx.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gtodymqnwb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ivvv.top/Article/details/gtywmzzown.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.snrcjt.cn/Article/details/gtrmdqmljj.html

Ruby: s.scan(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtgftmoijx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtwikviaov.html

[I03] 提取捕获分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwblntwic.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gtkwqmqwff.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.316326.xyz/Article/details/gtucsliyvc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjzyztgo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gtnuivamvk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tian-w.cn/Article/details/gtlrlinuhk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jianghu66.top/Article/details/gtsfybohke.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nanxuanxn.top/Article/details/gtufejcgrt.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cucudq.cn/Article/details/gtfpcbimxm.html

[I04] 正则替换
来源：http://dali.cucudq.cn/Article/details/gtjfehagry.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtdouysfqh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gotoacloud.top/Article/details/gtzfqktvpz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gtqotlpxia.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtxyxpdegw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yueranfly.top/Article/details/gtyifvcxsb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xinyue.icu/Article/details/gtkzqokglo.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xinyue.icu/Article/details/gtbpcrldwv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gtyqolvcnm.html

[I05] 按正则拆分
来源：http://dali.jyoumei.cn/Article/details/gtmhijjbfn.html


<!-- 参考信息 -->