代发 wailian999

[F09] 获取文件大小
来源：http://dali.ybcxt.top/Article/details/gtedmzxqzs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtqilnzbmg.html

PHP:  filesize("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtygihrpzz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gtbwhjzkkr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtckukgtoe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtipchuvmt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gtmewxcfda.html

Ruby: File.size("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtrdccmvfw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cashguo.top/Article/details/gtkhtwfjvt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zycfv.cn/Article/details/gtylydwviq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtsztvhqpx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gterfjpiav.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtdscawxzm.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtqbyvqwcf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jlsjyb.cn/Article/details/gthkjvctyb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtqfqqiamy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtigkpddul.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gttmttgqag.html

[F11] 复制与移动文件
来源：http://dali.sysykeji.top/Article/details/gtcqusqspv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugnkfqld.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvtmxwlt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecbxnbjx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtvhotnmle.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gtpaenrwlz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gtsoxfqdpu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtpspzknqx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sysykeji.top/Article/details/gtdtfoxcrs.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gtzrisuint.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gtoqffrdzk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.snrcjt.cn/Article/details/gtmftukqdj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.redwolf501.top/Article/details/gtgsaxwrcb.html

TS:   // 同上
来源：http://dali.quarkkingdee.top/Article/details/gtupvhpilw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.haohaochexian.top/Article/details/gtujrxrygq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gtckdxgcuh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhijiandao.cn/Article/details/gtsxasaxez.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhixingplan.top/Article/details/gtiptdtnjd.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gthazgnrsu.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gtyemgaauj.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtfvjzibrn.html

[G01] 定义类
来源：http://dali.hnxiangtu.top/Article/details/gtlhntxidn.html

Py:   class User: pass
来源：http://dali.dianchejie.cn/Article/details/gtdeszulog.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gtdkcuutot.html

JS:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtbjzviwyp.html

TS:   class User { name: string = ""; }
来源：http://dali.sweek.top/Article/details/gtuuquoyhx.html

Java: class User {}
来源：http://dali.yuanzhike.top/Article/details/gtwpttdlfl.html

Go:   type User struct { Name string }
来源：http://dali.haohaochexian.top/Article/details/gtkrctcbfz.html

Ruby: class User; end
来源：http://dali.smart0.xyz/Article/details/gtvisfeycu.html

C#:   class User {}
来源：http://dali.sweek.top/Article/details/gttnyakwjd.html

[G02] 构造函数
来源：http://dali.bjfxy.top/Article/details/gtrodvkbhm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.smart0.xyz/Article/details/gtqjoouifo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gtzxdptvdp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtwweheyic.html

TS:   constructor(public name: string) {}
来源：http://dali.pycfn.com/Article/details/gtlgabospf.html

Java: User(String name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtbrdhsihw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkruigatc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gtfcjhdmew.html

C#:   public User(string name) { Name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtuinqgxya.html

[G03] 实例属性
来源：http://dali.0kj1m.cn/Article/details/gtpqkfwojk.html

Py:   self.name = "x"
来源：http://dali.bjfxy.top/Article/details/gtkcsnhwch.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gtkwcitbbr.html

JS:   this.name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpipsfwxx.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gtlqjrqgxe.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gtxlqkmnur.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxuanxn.top/Article/details/gtxhmhvfcd.html

Ruby: @name = "x"
来源：http://dali.tanke756.top/Article/details/gtjckaznae.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtqnpeeicb.html

[G04] 定义方法
来源：http://dali.xinyue.icu/Article/details/gtethtyepx.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gttqsnunat.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtgwbnjtpg.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtqtymxepz.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtdoaebmmd.html

Java: String greet() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlqcgelz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtxmjcmemb.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gtjaxihmtw.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gtfmcavuaa.html

[G05] 继承
来源：http://dali.xziqi.cn/Article/details/gtfpgypawr.html

Py:   class Admin(User): pass
来源：http://dali.vqdsnc.cn/Article/details/gtbibjsmpi.html

PHP:  class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtcynltylo.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtzxrwuala.html

TS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtrqmkebdb.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxserxgsg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gtjnnqclft.html

Ruby: class Admin < User; end
来源：http://dali.yj20258.top/Article/details/gttsqadhqd.html

C#:   class Admin : User {}
来源：http://dali.sufxvd.cn/Article/details/gtpxidehjm.html

[G06] 重写方法
来源：http://dali.jianghu66.top/Article/details/gtdekehanf.html

Py:   def greet(self): return "admin"
来源：http://dali.xinyue.icu/Article/details/gtrieggrae.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtnnpcoksx.html

JS:   greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtbgenxstt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtncgwcrfu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtmfdkbpxi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gtfwyewwol.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gtmnopbxwo.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gtqjqlcsdv.html

[G07] 调用父类方法
来源：http://dali.nanxuanxn.top/Article/details/gtcoauhcgo.html

Py:   super().greet()
来源：http://dali.jinqigfzy.top/Article/details/gtzlbkmaho.html

PHP:  parent::greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtzrsxmxff.html

JS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gtzokvlpcv.html

TS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtvxvwcgor.html

Java: super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtljuszykc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gtvmnrswfx.html

Ruby: super
来源：http://dali.svipenyu.cn/Article/details/gtplvwhchq.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtvradpnbw.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gttawshyql.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gtwtnyzqno.html

PHP:  public static function f() {}
来源：http://dali.fengsongda.top/Article/details/gteqftxgcv.html

JS:   static f() {}
来源：http://dali.snrcjt.cn/Article/details/gtqhhootev.html

TS:   static f(): void {}
来源：http://dali.jianghu66.top/Article/details/gtuwlpyqar.html

Java: static void f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvphgmfu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jyoumei.cn/Article/details/gtlwuvedjm.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gthzuzralh.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gtnlpvndct.html

[G09] 接口 / 抽象类
来源：http://dali.yanxiufei.cn/Article/details/gtytvthgbc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.mhx1999.top/Article/details/gtemsvzxdx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tian-w.cn/Article/details/gtdbxugowz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258888.top/Article/details/gttbubtcez.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gtjrnulohs.html

Java: interface Shape { double area(); }
来源：http://dali.316326.xyz/Article/details/gtykrzubgf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pengpengdd.cyou/Article/details/gtxdopjgmj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gteogfxxjm.html

C#:   interface IShape { double Area(); }
来源：http://dali.vqdsnc.cn/Article/details/gtllmqpjbk.html

[G10] 访问控制
来源：http://dali.yonumen.top/Article/details/gtmizunjma.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fzhhl.top/Article/details/gtrnfjquda.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtrkqtcpbi.html

JS:   #private 字段；其余公开
来源：http://dali.xylfe.cn/Article/details/gtphmtnfrq.html

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gtkqvqfbka.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gtgayomato.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gtadkcpgja.html

Ruby: public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtkoxjpyju.html

C#:   public / protected / private / internal
来源：http://dali.chenzaomai.com/Article/details/gtlggutjzs.html

[G11] getter / setter
来源：http://dali.sysykeji.top/Article/details/gtyztomteb.html

Py:   @property 与 @x.setter
来源：http://dali.mhx1999.top/Article/details/gtaytcbbae.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtrjmkflix.html

JS:   get name() { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtdrlbkwjr.html

TS:   get name(): string { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gtssekljtf.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtjoleuqtp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtyxlsrgkm.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gtveyasyeb.html

C#:   public string Name { get; set; }
来源：http://dali.sufxvd.cn/Article/details/gtvsnjqtnq.html

[G12] 对象转字符串
来源：http://dali.xylfe.cn/Article/details/gtkilzqpob.html

Py:   def __str__(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gtjvjtxwbi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtmsegdoqu.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyvmaujg.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtvhwkfzuy.html

Java: @Override public String toString() { return name; }
来源：http://dali.yonumen.top/Article/details/gtdzcyshzh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtreoyvrop.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigufen.top/Article/details/gtpvcpoxhx.html

C#:   public override string ToString() => Name;
来源：http://dali.hnqzz.top/Article/details/gtretwuehi.html

[G13] 判断对象类型
来源：http://dali.hongshengwenyu.top/Article/details/gtzzoyrbei.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gtqhuwdmcj.html

PHP:  $u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtgocliyjs.html

JS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtmjcslsvj.html

TS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gtcgaqsxzq.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gtuwrvbqsu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtznpjjdrv.html

Ruby: u.is_a?(User)
来源：http://dali.mhx1999.top/Article/details/gtsqaetdqx.html

C#:   u is User
来源：http://dali.fengsongda.top/Article/details/gtcnsqxhmx.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gtayvryduw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guannengcc.top/Article/details/gtlawecpvy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ehwqpu.com/Article/details/gtorlajiih.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gogol.net.cn/Article/details/gtkmtswxgd.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gtvecszirm.html

Java: record User(String name, int age) {}
来源：http://dali.9152youxi.cn/Article/details/gtpdochojt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.havefunace.top/Article/details/gtnuvnbfbw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.birdmap.top/Article/details/gtecyprgmv.html

C#:   record User(string Name, int Age);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhnliptq.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gtfkidmlvk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxuanxn.top/Article/details/gtezuclbfp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigfzy.top/Article/details/gtybwssxqj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gogol.net.cn/Article/details/gtzzggxvok.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtqnhfrclv.html

Java: enum Color { RED, GREEN }
来源：http://dali.hysaishi.cn/Article/details/gtvfwqobfx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gtnitljrcs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuanzx.com/Article/details/gtkourbjwt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gtxutcsncf.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258888.top/Article/details/gtmngnblcy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jianghu66.top/Article/details/gtxsktbmnb.html

PHP:  get_object_vars($obj);
来源：http://dali.tianlin.xyz/Article/details/gtjjbfnvfe.html

JS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtspsamsfy.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gthyvzghoo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvsdvfjx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cucudq.cn/Article/details/gtvjpdepwl.html

Ruby: obj.instance_variables
来源：http://dali.jiagoushi.top/Article/details/gthiegcgpn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwmhwaeb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gthfnweunx.html

H. 异常与错误处理
来源：http://dali.9152youxi.cn/Article/details/gtlmbvmsvi.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtygborsxd.html

[H01] try / catch 基础
来源：http://dali.haohaochexian.top/Article/details/gtlwkoxhyz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gzhubu.top/Article/details/gtpydwdcam.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gotoacloud.top/Article/details/gtjaqipebi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukpcalll.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnnlzije.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigfzy.top/Article/details/gtrmirvlbx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gtmyeejnhm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xziqi.cn/Article/details/gtvdwynhoj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gtrfxhcqnf.html

[H02] finally / ensure 收尾
来源：http://dali.9152youxi.cn/Article/details/gtgmmwecru.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fengsongda.top/Article/details/gtjcfxgifl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtrkdxcozj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtfpxbjqra.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtvsglpcng.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtaydflqcs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gtisgpjjtz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258.top/Article/details/gtahdngjar.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gteokxpdqh.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gttouopebg.html

Py:   raise ValueError("错误信息")
来源：http://dali.ivvv.top/Article/details/gtzjgrnwhb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gthtqoyuvv.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtjjuypvbi.html

TS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gtvejoxvho.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtlzcuzckc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gzhubu.top/Article/details/gtrlvwjnhm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gogol.net.cn/Article/details/gtavvhfgnc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtryreyvnn.html

[H04] 自定义异常类型
来源：http://dali.cdnleiting.top/Article/details/gtewcyvdxn.html

Py:   class MyError(Exception): pass
来源：http://dali.hnqzz.top/Article/details/gtietaajow.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtupdktpva.html

JS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtbkjtdgqp.html

TS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gttwqcmbpz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gtvzuyejor.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nwbrower.top/Article/details/gtkbvndxmi.html

Ruby: class MyError < StandardError; end
来源：http://dali.shzxlz.cn/Article/details/gtieijwlrf.html

C#:   class MyException : Exception {}
来源：http://dali.xuetiantiany.cn/Article/details/gtsztcowmt.html

[H05] 捕获特定类型
来源：http://dali.smart0.xyz/Article/details/gtcbcfxjco.html

Py:   except ValueError as e:
来源：http://dali.tanke756.top/Article/details/gtyzpszpwq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gotoacloud.top/Article/details/gtfvnnxapt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtyiiaqhaa.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gtallwubfn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fengsongda.top/Article/details/gtcmkhxpsz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.andypj.xyz/Article/details/gttrplmnly.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuanzx.com/Article/details/gtxcegotrt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gtlmllyrsz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shuidangran.top/Article/details/gtovosgwwp.html

Py:   value = d.get("k") or default
来源：http://dali.nanxuanxn.top/Article/details/gtvbsmejbe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtirvivxdq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gteofyqvxp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gtqlcqclfl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gtjrnmrnjp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zycfv.cn/Article/details/gtmwspusck.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gogol.net.cn/Article/details/gtblnnqtbt.html

C#:   obj?.A?.B ?? default
来源：http://dali.gogol.net.cn/Article/details/gtejnivzsv.html

[H07] 断言
来源：http://dali.xuanzx.com/Article/details/gtgntsggoq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gtmentuadf.html

PHP:  assert($x > 0);
来源：http://dali.sweek.top/Article/details/gtucquysyz.html

JS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtsfudpzkb.html

TS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtuoqplrzd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj202588.top/Article/details/gtmfpunmzm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkrapama.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gtbkdubphl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtfoyhrksu.html

[H08] 获取错误信息与堆栈
来源：http://dali.yueranfly.top/Article/details/gtktgopozv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.0kj1m.cn/Article/details/gthwcqtxug.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jyoumei.cn/Article/details/gtkhtuvntl.html

JS:   e.message;  e.stack
来源：http://dali.jlsjyb.cn/Article/details/gtvaywwnuz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yueranfly.top/Article/details/gtpvimcwxt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gtntxzcxzp.html

Go:   err.Error()
来源：http://dali.iojbl.cn/Article/details/gthlfrfavy.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdnanuli.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sxryk.cn/Article/details/gtawmmjges.html

[H09] 带错误码的异常
来源：http://dali.hnqzz.top/Article/details/gtvxsxnwos.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cqqwz.cn/Article/details/gttojnycex.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.vqdsnc.cn/Article/details/gtbkxfymko.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yangfankeji.com/Article/details/gtofeckblh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tian-w.cn/Article/details/gtjmcflrys.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gtpfekjzko.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cdnleiting.top/Article/details/gtjlvwzxsn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guannengcc.top/Article/details/gtjtdorpkg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.svipenyu.cn/Article/details/gtaodeggif.html

[H10] 资源自动释放
来源：http://dali.nwbrower.top/Article/details/gtcielmjoa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guannengcc.top/Article/details/gtrrmliyuu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sysykeji.top/Article/details/gtevaajpjn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtnotudvdc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gtynkcqdxo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cucudq.cn/Article/details/gttaegjgvj.html

Go:   defer f.Close()
来源：http://dali.daxiang520.top/Article/details/gtupuzxgfi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.9152youxi.cn/Article/details/gtkdulzeae.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtujdztarq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtmcvypkml.html

I. 正则表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxttzqwv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtohryappx.html

[I01] 判断是否匹配
来源：http://dali.yj20258.top/Article/details/gtextjkqyt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtkhircpzc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxdrdfbz.html

JS:   /\d+/.test(s)
来源：http://dali.tianlin.xyz/Article/details/gtmwuvygiw.html

TS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtnxxanxot.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tianlin.xyz/Article/details/gtitbfmook.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.birdmap.top/Article/details/gtremmpuvz.html

Ruby: s.match?(/\d+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvevniyas.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xinyue.icu/Article/details/gtemftzejl.html

[I02] 提取所有匹配
来源：http://dali.yj20258.top/Article/details/gtohdkanpj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbspnpoo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ehwqpu.com/Article/details/gtyhhdfzxs.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhixingplan.top/Article/details/gtnmbwpgec.html

TS:   s.match(/\d+/g)
来源：http://dali.fzhhl.top/Article/details/gtjhkblotk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.guannengcc.top/Article/details/gtklgrkwoh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.chenzaomai.com/Article/details/gtmyiwwspa.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gtivxlbflu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gthhyrytvl.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gtdtjwopgd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.daria6918.cn/Article/details/gttvomuuso.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cucudq.cn/Article/details/gtnfgcqeeg.html


<!-- 参考信息 -->