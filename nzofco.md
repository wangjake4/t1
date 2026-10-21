代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtvdozgfvy.html

TS:   path.extname("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtutrqtjxr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gtcpymgpxz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtpkypwfug.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtuyftozoq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtvvwfjiju.html

[F11] 复制与移动文件
来源：http://dali.shuidangran.top/Article/details/gtcoushfpa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtttyxeuge.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtmhkujxra.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtwzkattfc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtsgzenglk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cashguo.top/Article/details/gtmjfztdgs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gtdfnhadiv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gthdrwsxpl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yueranfly.top/Article/details/gtrnrycseo.html

[F12] CSV 读写
来源：http://dali.xziqi.cn/Article/details/gtxtqyqxts.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangshuangyany.cn/Article/details/gtukzptyml.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.feifeiyinyue.top/Article/details/gtblhtjnxg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tanke756.top/Article/details/gtemyhjccy.html

TS:   // 同上
来源：http://dali.tian-w.cn/Article/details/gtnzpypyth.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gtntxbeptn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shuidangran.top/Article/details/gtwawwvpuu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuxming.cn/Article/details/gtpgpioeoo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gtchfcrmpn.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtcmxbpdjm.html

G. 面向对象
来源：http://dali.ivvv.top/Article/details/gtdrwebemq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtyobpkzcv.html

[G01] 定义类
来源：http://dali.yonumen.top/Article/details/gtjxldwbkw.html

Py:   class User: pass
来源：http://dali.yueranfly.top/Article/details/gtrisztzvl.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtphhjezje.html

JS:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtzwtkcxkl.html

TS:   class User { name: string = ""; }
来源：http://dali.sweek.top/Article/details/gtsoiajhzk.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gteqwawpgm.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gtvtwbgizp.html

Ruby: class User; end
来源：http://dali.iojbl.cn/Article/details/gtrtxxwjab.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtichcvgww.html

[G02] 构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxspaycp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.svipenyu.cn/Article/details/gtlobpninu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdetdotgd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtkxgtqpck.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gthziuqpya.html

Java: User(String name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gtvnhyuumj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shzxlz.cn/Article/details/gtvreglzjw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.quarkkingdee.top/Article/details/gtskccmuzh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtvreazjhu.html

[G03] 实例属性
来源：http://dali.zycfv.cn/Article/details/gtpkcqnhsj.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gtoxqngvqt.html

PHP:  public string $name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtqwctufaj.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gtrqnjmrga.html

TS:   name: string = "x";
来源：http://dali.jqgfzy.top/Article/details/gtmwhjelze.html

Java: private String name;
来源：http://dali.gaohongyu789.top/Article/details/gtncgpxpue.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cdnleiting.top/Article/details/gtpqwqwewp.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gtvicgikpl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yangfankeji.com/Article/details/gttpssmghb.html

[G04] 定义方法
来源：http://dali.jqgfzy.top/Article/details/gtbyvwrmeq.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258.top/Article/details/gtnfmdifbm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtbmslcanh.html

JS:   greet() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtrfmpigqs.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhkgtccl.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtehhzvzcj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyewtkkw.html

Ruby: def greet; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtmhcuyssi.html

C#:   public string Greet() => Name;
来源：http://dali.jiagoushi.top/Article/details/gtretycaar.html

[G05] 继承
来源：http://dali.yueranfly.top/Article/details/gtfrbexwgl.html

Py:   class Admin(User): pass
来源：http://dali.cdnleiting.top/Article/details/gtjorffxgg.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtwrrtbyhp.html

JS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtezorhhqk.html

TS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gthzfpyvsk.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtmhaavqwg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj202588.top/Article/details/gtqakhxlbc.html

Ruby: class Admin < User; end
来源：http://dali.birdmap.top/Article/details/gtvayefevf.html

C#:   class Admin : User {}
来源：http://dali.sysykeji.top/Article/details/gtxpkbobyq.html

[G06] 重写方法
来源：http://dali.sufxvd.cn/Article/details/gtxnwuzyiy.html

Py:   def greet(self): return "admin"
来源：http://dali.zhongyouzk.top/Article/details/gtgyktuslh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtpjlpcbsm.html

JS:   greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gthucgsswf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtnjnxlcly.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtbfrmzhoh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hywenlv.cn/Article/details/gtbyfymbzj.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gtraoicvsi.html

C#:   public override string Greet() => "admin";
来源：http://dali.cashguo.top/Article/details/gtotmzduik.html

[G07] 调用父类方法
来源：http://dali.yonumen.top/Article/details/gtyteqqhul.html

Py:   super().greet()
来源：http://dali.yuanzhike.top/Article/details/gtllcmywxk.html

PHP:  parent::greet();
来源：http://dali.xinyue.icu/Article/details/gtbwcfcbav.html

JS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtmfdgooop.html

TS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtdreddpkf.html

Java: super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwoeunma.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gtyouttcjn.html

Ruby: super
来源：http://dali.zhongyouzk.top/Article/details/gtwhtpxmie.html

C#:   base.Greet();
来源：http://dali.ppjwa.cn/Article/details/gtweyiivha.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gtdrfouyzr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gtigxommxz.html

PHP:  public static function f() {}
来源：http://dali.aibaodan.cn/Article/details/gtqnrxdelc.html

JS:   static f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdwwawok.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gtkozhnlbt.html

Java: static void f() {}
来源：http://dali.fzhhl.top/Article/details/gtnupfxmhy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuxming.cn/Article/details/gtjslsjmtv.html

Ruby: def self.f; end
来源：http://dali.cqqwz.cn/Article/details/gtdhfbqhvv.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gtoedhoviw.html

[G09] 接口 / 抽象类
来源：http://dali.shangyingyoupin.top/Article/details/gtapsxjfot.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvwatcom.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxuanxn.top/Article/details/gtjtfbtuha.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuanzx.com/Article/details/gtijrtuete.html

TS:   interface Shape { area(): number; }
来源：http://dali.kuanghao11.cn/Article/details/gtypihettn.html

Java: interface Shape { double area(); }
来源：http://dali.bjfxy.top/Article/details/gttpnixvkr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pengpengdd.cyou/Article/details/gtjjqhajlz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gtsrezusnn.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gtnzijllca.html

[G10] 访问控制
来源：http://dali.wangshuangyany.cn/Article/details/gtdzryukuk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ybcxt.top/Article/details/gtkqasoqrb.html

PHP:  public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtndwieeoq.html

JS:   #private 字段；其余公开
来源：http://dali.hongshengwenyu.top/Article/details/gtpmvfzhts.html

TS:   public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gtqzdnftbd.html

Java: public / protected / private / 默认包级
来源：http://dali.cqqwz.cn/Article/details/gtnkvcycel.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gtlslfohry.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtnrjrfhcf.html

C#:   public / protected / private / internal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrznwhrn.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gtznduwgfd.html

Py:   @property 与 @x.setter
来源：http://dali.xylfe.cn/Article/details/gtvpujwphb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtbsikvxwt.html

JS:   get name() { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtzmvcvgwe.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtwgskkhpy.html

Java: public String getName() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtmjvaweuo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtxaentojz.html

Ruby: attr_accessor :name
来源：http://dali.feifeiyinyue.top/Article/details/gtypntzkcz.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gthcujhsor.html

[G12] 对象转字符串
来源：http://dali.jyoumei.cn/Article/details/gtaczvvajz.html

Py:   def __str__(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtquunmyeq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtaazeohpx.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtcsnywqzk.html

TS:   toString(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtheurbtyw.html

Java: @Override public String toString() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtyblmjkav.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtjguvyncl.html

Ruby: def to_s; @name; end
来源：http://dali.yvedp.cn/Article/details/gtyjfeprmu.html

C#:   public override string ToString() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtowsqjarv.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gtubmcrrqz.html

Py:   isinstance(u, User)
来源：http://dali.wangshuangyany.cn/Article/details/gtzdbrwlwa.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtfxfkjrun.html

JS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtgxdghtgw.html

TS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtamiislps.html

Java: u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtvizcgprc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwaqthtl.html

Ruby: u.is_a?(User)
来源：http://dali.hongshengwenyu.top/Article/details/gtetweygdg.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gtnhqqwdnn.html

[G14] 数据类 / record
来源：http://dali.gaohongyu789.top/Article/details/gtqzpvfqvw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuanzx.com/Article/details/gtuytpalxx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gthgmawomi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shangyingyoupin.top/Article/details/gthrhghzop.html

TS:   type User = { name: string; age: number };
来源：http://dali.hfpthk.cn/Article/details/gtgeamwmxm.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigufen.top/Article/details/gthudfbcca.html

Go:   type User struct { Name string; Age int }
来源：http://dali.kuanghao11.cn/Article/details/gtwvquhrju.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gtnsqofgri.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gtxahuynjb.html

[G15] 枚举
来源：http://dali.xinyue.icu/Article/details/gtglqeuefu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuanzx.com/Article/details/gteqznambx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gtusvfqpsf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gtuihpaqaj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtnalcmvbk.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenjidiqi.icu/Article/details/gtbhjvoqiv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenzaomai.com/Article/details/gtjanthkxz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gticicelpf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtkjllshfh.html

[G16] 对象转数组 / 字典
来源：http://dali.jyoumei.cn/Article/details/gtpzssohnd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yueranfly.top/Article/details/gtqxnwkiqs.html

PHP:  get_object_vars($obj);
来源：http://dali.hywenlv.cn/Article/details/gtlvpvqwmt.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbitecgsl.html

TS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtvwyhhzsx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.iojbl.cn/Article/details/gtxwgxfdah.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gtgotybbxa.html

Ruby: obj.instance_variables
来源：http://dali.zycfv.cn/Article/details/gtyvuqdrqa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gtinzkfdud.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtvunojozd.html

H. 异常与错误处理
来源：http://dali.hnqzz.top/Article/details/gtqhohbobj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtqrrzuyws.html

[H01] try / catch 基础
来源：http://dali.cdnleiting.top/Article/details/gtroooqtxk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.haohaochexian.top/Article/details/gtnhrzcgjw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtiyehnces.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtrlsjxzyw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtpppiende.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zycfv.cn/Article/details/gtjwkzpdsu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gtznhzsipd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cheryme.top/Article/details/gtgakhzwrd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigfzy.top/Article/details/gtgrwrrohb.html

[H02] finally / ensure 收尾
来源：http://dali.jqgufenzy.top/Article/details/gtrqzpbgxu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yvedp.cn/Article/details/gtiysqjjzi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtxxumvpbi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtxxucchez.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqnzqzzi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtodmmivdu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gtyqfwruqb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.quarkkingdee.top/Article/details/gtnpcwcfhq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtmyqospjt.html

[H03] 主动抛出异常
来源：http://dali.havefunace.top/Article/details/gtudmoyvby.html

Py:   raise ValueError("错误信息")
来源：http://dali.redwolf501.top/Article/details/gtrhizhkrl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtdmmxdvnz.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtuqwslifu.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtlmwdrsgp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtxtkhwnis.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhengqikj.top/Article/details/gthscwyywg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gtuodtlzkl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpnawafn.html

[H04] 自定义异常类型
来源：http://dali.jlsjyb.cn/Article/details/gtjdzhwqts.html

Py:   class MyError(Exception): pass
来源：http://dali.zhongyouzk.top/Article/details/gtrjeplzgo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtbcrbgzbc.html

JS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtamdlxnbd.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gtqihgkukl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gtqupbsqfz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhoulong.xyz/Article/details/gtzikyuujn.html

Ruby: class MyError < StandardError; end
来源：http://dali.zycfv.cn/Article/details/gtfnnyhhkn.html

C#:   class MyException : Exception {}
来源：http://dali.cashguo.top/Article/details/gtavxlodrh.html

[H05] 捕获特定类型
来源：http://dali.guowangkeji.top/Article/details/gtegakjphz.html

Py:   except ValueError as e:
来源：http://dali.zycfv.cn/Article/details/gtayemhcqj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jianghu66.top/Article/details/gthckxzmss.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtyyvixirz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gtdfyreihy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisggrmua.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nwbrower.top/Article/details/gtgpynchcg.html

Ruby: rescue ArgumentError => e
来源：http://dali.0kj1m.cn/Article/details/gtslbzlwmf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.iojbl.cn/Article/details/gtzkbhwjha.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pengpengdd.cyou/Article/details/gtikrrmiwv.html

Py:   value = d.get("k") or default
来源：http://dali.jlsjyb.cn/Article/details/gtkprweqjy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gtezdqocju.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gttocxsrfa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gtbvgtkrjn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gturtzisre.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.meibo888.top/Article/details/gtnyrjjmkm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zycfv.cn/Article/details/gtyaqijccr.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxuanxn.top/Article/details/gtbyjcokou.html

[H07] 断言
来源：http://dali.aizwys.cn/Article/details/gtuxuyrwan.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gzhubu.top/Article/details/gtrxrbnucj.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtaiklhwlj.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtdpheecxn.html

TS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtiqozyejf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nwbrower.top/Article/details/gtciuzvlst.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgfzy.top/Article/details/gttqsuxpdn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gtqygpvwjd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gtjumfshko.html

[H08] 获取错误信息与堆栈
来源：http://dali.aizwys.cn/Article/details/gtssspakoj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sweek.top/Article/details/gtytfcvfhq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenzaomai.com/Article/details/gtclpfcbly.html

JS:   e.message;  e.stack
来源：http://dali.sufxvd.cn/Article/details/gtpnzulgnf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuxming.cn/Article/details/gtsojxbxpl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gtayshxhwk.html

Go:   err.Error()
来源：http://dali.bjfxy.top/Article/details/gtywzyctvf.html

Ruby: e.message;  e.backtrace
来源：http://dali.shangyingyoupin.top/Article/details/gtrytclidm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.andypj.xyz/Article/details/gtpvdxjxnf.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gtatlbxcyr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.quarkkingdee.top/Article/details/gtfospweap.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sufxvd.cn/Article/details/gtdmqqrrzm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhixingplan.top/Article/details/gtcjkpacuo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jianghu66.top/Article/details/gtuabkoxyx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.vqdsnc.cn/Article/details/gtrcghuovb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hysaishi.cn/Article/details/gtsdfnxoom.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.svipenyu.cn/Article/details/gtmtwkaeox.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.daria6918.cn/Article/details/gttbvktbye.html

[H10] 资源自动释放
来源：http://dali.xziqi.cn/Article/details/gtbwsqdelv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gtgfucvgsb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xziqi.cn/Article/details/gthjaxozxe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtxcammssa.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtqjldbwaz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aibaodan.cn/Article/details/gtjcyysjxm.html

Go:   defer f.Close()
来源：http://dali.shangyingyoupin.top/Article/details/gtxzrctbiz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.iojbl.cn/Article/details/gtbgtdediq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtgnmaankx.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthopmjate.html

I. 正则表达式
来源：http://dali.xinyue.icu/Article/details/gtdnrsiocx.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtigmtkhkh.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gtyejnmmuk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtmmpzvssg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtpjsoasdh.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoivhvsse.html

TS:   /\d+/.test(s)
来源：http://dali.bjfxy.top/Article/details/gtklrccuxo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gtlgaeqqxh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hysaishi.cn/Article/details/gtzkkbqdta.html

Ruby: s.match?(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gtmkfqcmbb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258.top/Article/details/gtnzggjeid.html

[I02] 提取所有匹配
来源：http://dali.yvedp.cn/Article/details/gtbvmtythj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ehwqpu.com/Article/details/gthxhodthr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.havefunace.top/Article/details/gtpbbwouhj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jlsjyb.cn/Article/details/gtucpojdtn.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gtaozfgeic.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cashguo.top/Article/details/gtwdjnzwof.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtfbumqjej.html

Ruby: s.scan(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtallfbd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sweek.top/Article/details/gtvfmjfxjz.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gtekckfybo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daxiang520.top/Article/details/gtkvbobnpt.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhongyouzk.top/Article/details/gttvwqhiyl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258.top/Article/details/gteevkehkc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yuanzhike.top/Article/details/gtgbdgveeu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.haohaochexian.top/Article/details/gtqikcmglv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxbbbrej.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hysaishi.cn/Article/details/gtwjchqxam.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhengqikj.top/Article/details/gtmowagudf.html

[I04] 正则替换
来源：http://dali.yongpay.top/Article/details/gtqpjbbqec.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gzhubu.top/Article/details/gtaapjtstg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.nwbrower.top/Article/details/gtiwbchdss.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtmerdisec.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gthzqsupnj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sufxvd.cn/Article/details/gtvmxvmpib.html


<!-- 参考信息 -->