代发 wailian999

[F09] 获取文件大小
来源：http://dali.birdmap.top/Article/details/gtvyphvtun.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtwsdokljj.html

PHP:  filesize("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gteinkzfdm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gtlonlywjz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtfyckeuks.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtgrextdyv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.svipenyu.cn/Article/details/gtnlazemub.html

Ruby: File.size("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtnbmjmutj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yangfankeji.com/Article/details/gtpujinevq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxuanxn.top/Article/details/gtondsnctn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtansjbmto.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gzhubu.top/Article/details/gttzwirhlf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtlduozkdi.html

TS:   path.extname("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtgmsuubdf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zdqjudy.top/Article/details/gtthjuuegg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtuksjelzn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtucfywoki.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gthrakerfa.html

[F11] 复制与移动文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtblxrtrjn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtpkvqdddh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuanzhike.top/Article/details/gttrdwzmhc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtoovpkbmu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtomrngdmn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtehszfvfg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.svipenyu.cn/Article/details/gtpuqsgzow.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtjtjyvean.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fzhhl.top/Article/details/gtkeijdydi.html

[F12] CSV 读写
来源：http://dali.snrcjt.cn/Article/details/gtjdpgygld.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gtzoxctunp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cdnleiting.top/Article/details/gthgyxaxco.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sysykeji.top/Article/details/gtnfkbdkzr.html

TS:   // 同上
来源：http://dali.xziqi.cn/Article/details/gtxsgeowuo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuetiantiany.cn/Article/details/gtirjsulhf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangshuangyany.cn/Article/details/gtcngkcjsy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gtdunyjcjq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gaohongyu789.top/Article/details/gtqwfjwfzq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtskpxfosv.html

G. 面向对象
来源：http://dali.tanke756.top/Article/details/gtezwxzcnm.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtwiashsjj.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gtwfiaramb.html

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gtmfkcoshx.html

PHP:  class User {}
来源：http://dali.zhengqikj.top/Article/details/gtwzanrube.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gttaebxcpu.html

TS:   class User { name: string = ""; }
来源：http://dali.sxryk.cn/Article/details/gtsawbscse.html

Java: class User {}
来源：http://dali.hfpthk.cn/Article/details/gtpufdizol.html

Go:   type User struct { Name string }
来源：http://dali.shuidangran.top/Article/details/gtgkgjqyqq.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gtubqaxpyx.html

C#:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtfmaxezyw.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtyhmotkop.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258.top/Article/details/gtegxpnado.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhoulong.xyz/Article/details/gtruzxmuoo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtvafzbjcr.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtjiiqoaam.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtkexwdppw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jiagoushi.top/Article/details/gtlxkawztp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jyoumei.cn/Article/details/gtbvfmqwnj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnqzz.top/Article/details/gtptwxmrfm.html

[G03] 实例属性
来源：http://dali.9152youxi.cn/Article/details/gtbpxhuhlv.html

Py:   self.name = "x"
来源：http://dali.cashguo.top/Article/details/gtqflacopn.html

PHP:  public string $name = "x";
来源：http://dali.zhengqikj.top/Article/details/gtjzpixwsn.html

JS:   this.name = "x";
来源：http://dali.hammf.cn/Article/details/gtnhaqtpxd.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gtekmwelrh.html

Java: private String name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifickzjm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.svipenyu.cn/Article/details/gtniybpoau.html

Ruby: @name = "x"
来源：http://dali.tanke756.top/Article/details/gtlpjddsni.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtmkwpdwse.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gttwkojecg.html

Py:   def greet(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtyrekhtfp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtrmvoxmsh.html

JS:   greet() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtklqqagtw.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtovpdmuva.html

Java: String greet() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtuhrwqoop.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtnlbkhazf.html

Ruby: def greet; @name; end
来源：http://dali.ehwqpu.com/Article/details/gtgdltadqd.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtzbzqwwoa.html

[G05] 继承
来源：http://dali.chenzaomai.com/Article/details/gtigahczwt.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gtjslvlizq.html

PHP:  class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtxhoawkea.html

JS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtubcvgvkw.html

TS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtunhkldhy.html

Java: class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtusnkhjce.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ybcxt.top/Article/details/gtlfcnuulb.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gtwoezdajp.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gtbcupgjgh.html

[G06] 重写方法
来源：http://dali.gzhubu.top/Article/details/gtpnoovqqe.html

Py:   def greet(self): return "admin"
来源：http://dali.meibo888.top/Article/details/gttnlytmcy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtpmobhwdp.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtwozndswr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtxgjkkdju.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtmnghlptl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhijiandao.cn/Article/details/gtoxjducpt.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gtxrxpbtwj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhongyouzk.top/Article/details/gthgdygute.html

[G07] 调用父类方法
来源：http://dali.jqgufenzy.top/Article/details/gtdymdjukc.html

Py:   super().greet()
来源：http://dali.tian-w.cn/Article/details/gtyssamkyv.html

PHP:  parent::greet();
来源：http://dali.0kj1m.cn/Article/details/gtmigorxbj.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gtzukaxaki.html

TS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtrdbeukth.html

Java: super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtbgdtcjpv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gtvurlmgke.html

Ruby: super
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqqyputo.html

C#:   base.Greet();
来源：http://dali.sxryk.cn/Article/details/gtofqqrore.html

[G08] 静态方法与属性
来源：http://dali.nanxinkj.top/Article/details/gttjiloumk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gtdtorwmmc.html

PHP:  public static function f() {}
来源：http://dali.andypj.xyz/Article/details/gtmntlrctp.html

JS:   static f() {}
来源：http://dali.chenzaomai.com/Article/details/gtxchwxqin.html

TS:   static f(): void {}
来源：http://dali.dashuyun.cn/Article/details/gtvobboauw.html

Java: static void f() {}
来源：http://dali.zhoulong.xyz/Article/details/gtvvyjwtee.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gzhubu.top/Article/details/gtfafmvxlc.html

Ruby: def self.f; end
来源：http://dali.guannengcc.top/Article/details/gtjquzkpwa.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtgawsikzm.html

[G09] 接口 / 抽象类
来源：http://dali.svipenyu.cn/Article/details/gtwswmkjbe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gtmbpehdfr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.9152youxi.cn/Article/details/gteufvozpq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhiwuduotai.top/Article/details/gtkufciwjz.html

TS:   interface Shape { area(): number; }
来源：http://dali.xziqi.cn/Article/details/gtzqbclzop.html

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gtbfmxanox.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pycfn.com/Article/details/gtbumpfoox.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daria6918.cn/Article/details/gtlhhxvtam.html

C#:   interface IShape { double Area(); }
来源：http://dali.guowangkeji.top/Article/details/gtryfgavzw.html

[G10] 访问控制
来源：http://dali.zhixingplan.top/Article/details/gttexnfxsv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigfzy.top/Article/details/gtiateqyeb.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtllclxnyy.html

JS:   #private 字段；其余公开
来源：http://dali.aibaodan.cn/Article/details/gthwlvpaky.html

TS:   public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtaolpdrtg.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gtutaftbfl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hywenlv.cn/Article/details/gtcokuufau.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gttgwscwaj.html

C#:   public / protected / private / internal
来源：http://dali.zycfv.cn/Article/details/gtbtolcdsj.html

[G11] getter / setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmbvxcvr.html

Py:   @property 与 @x.setter
来源：http://dali.cheryme.top/Article/details/gtcxrpcswh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtewhmzxqi.html

JS:   get name() { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtszasgjgr.html

TS:   get name(): string { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gttfwbwgru.html

Java: public String getName() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtcyyrrzgm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtptmrlqtx.html

Ruby: attr_accessor :name
来源：http://dali.sxryk.cn/Article/details/gtjdujdcox.html

C#:   public string Name { get; set; }
来源：http://dali.sxryk.cn/Article/details/gtrpaaxrrw.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gtasfvesvt.html

Py:   def __str__(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gtysnlbnfp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtiicqaqby.html

JS:   toString() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gthcixewcc.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtrkpbkhgq.html

Java: @Override public String toString() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtveplwvth.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtrcfxfsox.html

Ruby: def to_s; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtatolsmiu.html

C#:   public override string ToString() => Name;
来源：http://dali.daria6918.cn/Article/details/gtctsvhywp.html

[G13] 判断对象类型
来源：http://dali.fzhhl.top/Article/details/gtjzfciaqi.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gtimpmytsw.html

PHP:  $u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtdjezfvse.html

JS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtxgihybqd.html

TS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtgopuhmfq.html

Java: u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtgbhxthvh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yvedp.cn/Article/details/gtlrykrscn.html

Ruby: u.is_a?(User)
来源：http://dali.zhengqikj.top/Article/details/gtrnpiquwz.html

C#:   u is User
来源：http://dali.kuanghao11.cn/Article/details/gtsdupbzni.html

[G14] 数据类 / record
来源：http://dali.cucudq.cn/Article/details/gtgapgxjls.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhongyouzk.top/Article/details/gtohtjpond.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.redwolf501.top/Article/details/gtumxtxtkg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pengpengdd.cyou/Article/details/gtbemiauvi.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuetiantiany.cn/Article/details/gtkolkhzyr.html

Java: record User(String name, int age) {}
来源：http://dali.guannengcc.top/Article/details/gtanfkftrc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtobpqtb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hfpthk.cn/Article/details/gtlfqrqztl.html

C#:   record User(string Name, int Age);
来源：http://dali.smart0.xyz/Article/details/gtbzhogsuz.html

[G15] 枚举
来源：http://dali.nanxinkj.top/Article/details/gtuezadlkw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jianghu66.top/Article/details/gtkighztle.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhongyouzk.top/Article/details/gtbemprygi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fzhhl.top/Article/details/gtknoysuwk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtqdcwxvlr.html

Java: enum Color { RED, GREEN }
来源：http://dali.jlsjyb.cn/Article/details/gtolradbjd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigufen.top/Article/details/gtunzersxr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258888.top/Article/details/gtpcqdxwxj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gtzaojirgc.html

[G16] 对象转数组 / 字典
来源：http://dali.mhx1999.top/Article/details/gtnafomomb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aizwys.cn/Article/details/gtsaeniskw.html

PHP:  get_object_vars($obj);
来源：http://dali.c1oappe.top/Article/details/gtzragnxiv.html

JS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gtiqbjujcf.html

TS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gtxczfucwb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guowangkeji.top/Article/details/gthchdlrnp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gtowkqgskj.html

Ruby: obj.instance_variables
来源：http://dali.dashuyun.cn/Article/details/gtzshbfxkn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gtwgizvigm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtqfbthopr.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gtyhsftmbf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtecjvpbud.html

[H01] try / catch 基础
来源：http://dali.ydzc1.top/Article/details/gtdfczrwho.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fengsongda.top/Article/details/gthwruvkyf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gtahagpsvs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtwxnukxdf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gtrdesqrzs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yongpay.top/Article/details/gtvdykredq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gtsduasuwn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hysaishi.cn/Article/details/gtpclpbpxj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhongyouzk.top/Article/details/gtuougdvdl.html

[H02] finally / ensure 收尾
来源：http://dali.pycfn.com/Article/details/gtumcawicr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gtgnzwvexw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtgnemwqlg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtpacbwcyx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrisjfvu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtbvsjquza.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xinyue.icu/Article/details/gtlkxgernx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jyoumei.cn/Article/details/gtotalvnrg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtnbrmkzid.html

[H03] 主动抛出异常
来源：http://dali.smart0.xyz/Article/details/gtcjqrequo.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gtgkknxtne.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtbwyilydz.html

JS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtzdgalewq.html

TS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtsxczeypt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gthapccnii.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gtvimvnqek.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigufen.top/Article/details/gtwyfteiwq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtxworjxop.html

[H04] 自定义异常类型
来源：http://dali.shangyingyoupin.top/Article/details/gtfjvrupou.html

Py:   class MyError(Exception): pass
来源：http://dali.chenjidiqi.icu/Article/details/gthvwtflyu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gtgtkkscow.html

JS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtkgatxito.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gtppnrwjpc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtgtudgbww.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gtapchycuv.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuanzhike.top/Article/details/gtjewnbxlj.html

C#:   class MyException : Exception {}
来源：http://dali.yuanzhike.top/Article/details/gtuummfkrn.html

[H05] 捕获特定类型
来源：http://dali.birdmap.top/Article/details/gtfyldpgyu.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gtoatkeqta.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gttrpnsbrx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtvsypvlzl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtcagvikzv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ydzc1.top/Article/details/gtyzlgrzxl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuetiantiany.cn/Article/details/gtjbcjeqay.html

Ruby: rescue ArgumentError => e
来源：http://dali.sxryk.cn/Article/details/gtzfwkyybc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuanzx.com/Article/details/gtqccchpmu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zdqjudy.top/Article/details/gtnxssyzug.html

Py:   value = d.get("k") or default
来源：http://dali.guannengcc.top/Article/details/gtpejbpafb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gtcjngaeov.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtvobnbqct.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtjxjdlrij.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenlongwang.top/Article/details/gtylcqcpaa.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zycfv.cn/Article/details/gthwnoigcn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gtfbafrkuu.html

C#:   obj?.A?.B ?? default
来源：http://dali.ivvv.top/Article/details/gtibnszbup.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gtgjigwtmt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gtfdphffww.html

PHP:  assert($x > 0);
来源：http://dali.yuxming.cn/Article/details/gthmhlzcdy.html

JS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtrvapibzv.html

TS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtfsmcjtoa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ivvv.top/Article/details/gtndpvbrtw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nwbrower.top/Article/details/gtrjugmrye.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gtnbftrrfc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtlgihnkui.html

[H08] 获取错误信息与堆栈
来源：http://dali.nwbrower.top/Article/details/gtbvjwlbgq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaufszgyi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhengqikj.top/Article/details/gthbdixzxv.html

JS:   e.message;  e.stack
来源：http://dali.hongshengwenyu.top/Article/details/gtunqxxubr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yangfankeji.com/Article/details/gtyckalnag.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xylfe.cn/Article/details/gtgkryyvzj.html

Go:   err.Error()
来源：http://dali.iojbl.cn/Article/details/gtxjdrncmt.html

Ruby: e.message;  e.backtrace
来源：http://dali.sxryk.cn/Article/details/gtdzahowhn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gtoluzbbgl.html

[H09] 带错误码的异常
来源：http://dali.shuidangran.top/Article/details/gtvnuomihx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzgztqsg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hammf.cn/Article/details/gtxdbyqwst.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sxryk.cn/Article/details/gtnomorjuh.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.meibo888.top/Article/details/gtttnjfnnb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jlsjyb.cn/Article/details/gtwgjrbpaj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhiwuduotai.top/Article/details/gtwlzdnapm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.snrcjt.cn/Article/details/gtdbkqhjom.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhiwuduotai.top/Article/details/gtnhdgsubk.html

[H10] 资源自动释放
来源：http://dali.gaohongyu789.top/Article/details/gtasyjlsvz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenjidiqi.icu/Article/details/gtkxbpinxu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cheryme.top/Article/details/gtfbnbodtd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gtqrymcipw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyybsodu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gtvwrfwxng.html

Go:   defer f.Close()
来源：http://dali.cashguo.top/Article/details/gtsdmlyzsh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.birdmap.top/Article/details/gteomwcpqt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtrztzqlao.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gttbiqgsgp.html

I. 正则表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyfnyukc.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtadmczqbs.html

[I01] 判断是否匹配
来源：http://dali.zycfv.cn/Article/details/gtwhlxnyrb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gtnzjvnwlb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtxswicrze.html

JS:   /\d+/.test(s)
来源：http://dali.aibaodan.cn/Article/details/gtlamtgjwz.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtnhmwrcal.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hongshengwenyu.top/Article/details/gtkuuprwvr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhengqikj.top/Article/details/gthwupizlm.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtyojyvjof.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yanxiufei.cn/Article/details/gtqlxhbalq.html

[I02] 提取所有匹配
来源：http://dali.snrcjt.cn/Article/details/gthulfjscl.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gtzcqnqrgu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sxryk.cn/Article/details/gtpltadmnn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shzxlz.cn/Article/details/gtohmolzwq.html

TS:   s.match(/\d+/g)
来源：http://dali.yonumen.top/Article/details/gttpyticjy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zycfv.cn/Article/details/gtzqgriefn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivprjpwh.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gtqxcgsmjc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sxryk.cn/Article/details/gtlzkfpzel.html

[I03] 提取捕获分组
来源：http://dali.gotoacloud.top/Article/details/gtmaaricqt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ivvv.top/Article/details/gtklmmzggn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslfvleqx.html


<!-- 参考信息 -->