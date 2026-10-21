代发 wailian999

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gtnzelbpzg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cashguo.top/Article/details/gtlzhxoebi.html

PHP:  filesize("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtbvgouxyq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gtapqsbnhq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtjbushwcn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtsltrcdxf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigufen.top/Article/details/gtxuptpwve.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtwdvzgort.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daria6918.cn/Article/details/gtrvexwxvd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gtwjiiljxo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtmdbkwjnk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.316326.xyz/Article/details/gtsdmvhoad.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtmwtiadir.html

TS:   path.extname("a.txt")
来源：http://dali.daria6918.cn/Article/details/gttxtsqtpg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gzhubu.top/Article/details/gtvhselofw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfznyqox.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtwessdgof.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtzxzczdfl.html

[F11] 复制与移动文件
来源：http://dali.snrcjt.cn/Article/details/gtlaxnqkvf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsocqkav.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhengqikj.top/Article/details/gttgpbdbuz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtyodkqxbf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtdovhuijs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yonumen.top/Article/details/gtksmqncqg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jlsjyb.cn/Article/details/gtxpmioyci.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtapmckacn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gtlegfhrgi.html

[F12] CSV 读写
来源：http://dali.hnqzz.top/Article/details/gtgmyyzexy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gtgtawnzgz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.316326.xyz/Article/details/gtchewwrha.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigufen.top/Article/details/gtezlkvrrv.html

TS:   // 同上
来源：http://dali.sufxvd.cn/Article/details/gtxtaihyok.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.feifeiyinyue.top/Article/details/gttaxfbrca.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoufrmipj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.smart0.xyz/Article/details/gtnbzilmky.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgfzy.top/Article/details/gtsurrociw.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtsgcybwpp.html

G. 面向对象
来源：http://dali.hywenlv.cn/Article/details/gtcamphnpw.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtyospmrbr.html

[G01] 定义类
来源：http://dali.hammf.cn/Article/details/gtpsyvsmey.html

Py:   class User: pass
来源：http://dali.quarkkingdee.top/Article/details/gtijlucrfg.html

PHP:  class User {}
来源：http://dali.xylfe.cn/Article/details/gtiqmlzwpg.html

JS:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtlyhlhigz.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgfzy.top/Article/details/gtuouvsehr.html

Java: class User {}
来源：http://dali.yuanzhike.top/Article/details/gtmmzjabhs.html

Go:   type User struct { Name string }
来源：http://dali.birdmap.top/Article/details/gtbpcssxyp.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gtimujnifm.html

C#:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gtflgobaib.html

[G02] 构造函数
来源：http://dali.shzxlz.cn/Article/details/gtugtkuiew.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.kuanghao11.cn/Article/details/gtpwdmqqag.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shzxlz.cn/Article/details/gtirkyzukk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtfuctcdwc.html

TS:   constructor(public name: string) {}
来源：http://dali.jianghu66.top/Article/details/gtskzdyeox.html

Java: User(String name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gtjheaqemb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhoulong.xyz/Article/details/gtgfpiiqxi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gtfgyrshhk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtvacqnodi.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gtjeucboqx.html

Py:   self.name = "x"
来源：http://dali.yuxming.cn/Article/details/gtmubbpluj.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gtswgvwqkz.html

JS:   this.name = "x";
来源：http://dali.dashuyun.cn/Article/details/gtcwkdcmye.html

TS:   name: string = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsjcsiwz.html

Java: private String name;
来源：http://dali.hnqzz.top/Article/details/gtzyzhihhv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.haohaochexian.top/Article/details/gtyxsvztek.html

Ruby: @name = "x"
来源：http://dali.gotoacloud.top/Article/details/gtajvrwozb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtnjdggnft.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gtuwgkqgju.html

Py:   def greet(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gtkredvvax.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtnohganew.html

JS:   greet() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gttbgddgmt.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gtlucycwae.html

Java: String greet() { return name; }
来源：http://dali.yongpay.top/Article/details/gtalutdpqi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gttlwnnymg.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gtsaoxkpyh.html

C#:   public string Greet() => Name;
来源：http://dali.smart0.xyz/Article/details/gtvnyfhrzd.html

[G05] 继承
来源：http://dali.kuanghao11.cn/Article/details/gtievhonvr.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gtrnepcgth.html

PHP:  class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtevkwouom.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtdhynvzuw.html

TS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtsjsiyisz.html

Java: class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtmciwtrqc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuanzx.com/Article/details/gtjojngzfx.html

Ruby: class Admin < User; end
来源：http://dali.kuanghao11.cn/Article/details/gtaxkzomud.html

C#:   class Admin : User {}
来源：http://dali.yonumen.top/Article/details/gtniyemzvg.html

[G06] 重写方法
来源：http://dali.xylfe.cn/Article/details/gtdqtmpqfx.html

Py:   def greet(self): return "admin"
来源：http://dali.hammf.cn/Article/details/gtdvanqtig.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtymvyjrqd.html

JS:   greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtpjwanvaq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtvcspkvlm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtncbfnlko.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqvnrooj.html

Ruby: def greet; "admin"; end
来源：http://dali.feifeiyinyue.top/Article/details/gtfamcuxro.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gtdqlxzcae.html

[G07] 调用父类方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibodivkl.html

Py:   super().greet()
来源：http://dali.cucudq.cn/Article/details/gtfhowepmz.html

PHP:  parent::greet();
来源：http://dali.meibo888.top/Article/details/gthlofwriq.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtvmchiqmy.html

TS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtgdceauav.html

Java: super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtoemkbyyh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zycfv.cn/Article/details/gtnuqtoaye.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gtxmleqdkl.html

C#:   base.Greet();
来源：http://dali.cashguo.top/Article/details/gthvcemtwq.html

[G08] 静态方法与属性
来源：http://dali.cqqwz.cn/Article/details/gtcrtkfgue.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tanke756.top/Article/details/gtqcrpvfmq.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gthgmxzgxo.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gthediwskh.html

TS:   static f(): void {}
来源：http://dali.zycfv.cn/Article/details/gthajmnnaz.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gtcymebawj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gtsrqfnmak.html

Ruby: def self.f; end
来源：http://dali.bjfxy.top/Article/details/gtkajfortg.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gtzpqqqzyj.html

[G09] 接口 / 抽象类
来源：http://dali.tanke756.top/Article/details/gtedcugbsw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zycfv.cn/Article/details/gthflzyjgd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfwgamap.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.havefunace.top/Article/details/gtpuzdovdp.html

TS:   interface Shape { area(): number; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwpvuwkt.html

Java: interface Shape { double area(); }
来源：http://dali.snrcjt.cn/Article/details/gtxewpezfs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258.top/Article/details/gtxzuscajy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gtsgunolbf.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gtuvuazfit.html

[G10] 访问控制
来源：http://dali.dashuyun.cn/Article/details/gtoxqvrwrl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gtfqoufoox.html

PHP:  public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtotzeijuc.html

JS:   #private 字段；其余公开
来源：http://dali.chenzaomai.com/Article/details/gtidurgtqc.html

TS:   public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtvbsiiczm.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gtrcyxiiso.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.bjfxy.top/Article/details/gthlzyigxz.html

Ruby: public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtglqduhos.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gthlcdsnyt.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gtkexlnoyl.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gtpcltgnwg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtqjkmssgm.html

JS:   get name() { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtbzrgnriu.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtpcvmvrns.html

Java: public String getName() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaoqnzlwa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtmloqefdm.html

Ruby: attr_accessor :name
来源：http://dali.gzhubu.top/Article/details/gtxjztqnxs.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258888.top/Article/details/gtwslimzps.html

[G12] 对象转字符串
来源：http://dali.hysaishi.cn/Article/details/gtcuyfynyk.html

Py:   def __str__(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gtkaxfojju.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtumfrhatf.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtkiytraxk.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtbvwszlbx.html

Java: @Override public String toString() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwxdrasfx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtfjxzpjmz.html

Ruby: def to_s; @name; end
来源：http://dali.xuanzx.com/Article/details/gtkcnfklen.html

C#:   public override string ToString() => Name;
来源：http://dali.cashguo.top/Article/details/gtoxtxsqyy.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjnyzybh.html

Py:   isinstance(u, User)
来源：http://dali.zhoulong.xyz/Article/details/gtbnyoieby.html

PHP:  $u instanceof User
来源：http://dali.tanke756.top/Article/details/gtoawvvowa.html

JS:   u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtbhhndlyn.html

TS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtwlstmeed.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtllzwijgg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cdnleiting.top/Article/details/gthgfcavng.html

Ruby: u.is_a?(User)
来源：http://dali.wangshuangyany.cn/Article/details/gtaccexovl.html

C#:   u is User
来源：http://dali.cashguo.top/Article/details/gtytoowzyt.html

[G14] 数据类 / record
来源：http://dali.sufxvd.cn/Article/details/gtzwyowqui.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gthxulztyg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258.top/Article/details/gtkhgbyaaf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gtkdgcsupp.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gtempnyfnd.html

Java: record User(String name, int age) {}
来源：http://dali.haohaochexian.top/Article/details/gtgjtbgpcp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ehwqpu.com/Article/details/gtcoyzpprg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhengqikj.top/Article/details/gtmezalrgg.html

C#:   record User(string Name, int Age);
来源：http://dali.zhongyouzk.top/Article/details/gtgktbveho.html

[G15] 枚举
来源：http://dali.jqgfzy.top/Article/details/gtvsoqlxaw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hysaishi.cn/Article/details/gtqblwuzei.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xziqi.cn/Article/details/gtwuqzgfpa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jiagoushi.top/Article/details/gtxpbyfhup.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gtfjuputnv.html

Java: enum Color { RED, GREEN }
来源：http://dali.sweek.top/Article/details/gtdvepywoh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gaohongyu789.top/Article/details/gtqhlwjzqn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.meibo888.top/Article/details/gtctwcedml.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtiwwxykjm.html

[G16] 对象转数组 / 字典
来源：http://dali.sysykeji.top/Article/details/gtinjgobmd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cucudq.cn/Article/details/gtqdtdbhro.html

PHP:  get_object_vars($obj);
来源：http://dali.birdmap.top/Article/details/gtepzamffl.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtugeamkqa.html

TS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnfcfclp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gzhubu.top/Article/details/gtgcdeyhmu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guannengcc.top/Article/details/gtxcxtriax.html

Ruby: obj.instance_variables
来源：http://dali.ehwqpu.com/Article/details/gtvvepnunl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gtcscuqvyt.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtnzvjeqok.html

H. 异常与错误处理
来源：http://dali.yonumen.top/Article/details/gtuiipsgbw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtaodbisrl.html

[H01] try / catch 基础
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzenklfoa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gtgoosgfpc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.9152youxi.cn/Article/details/gtnxhtbzej.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtiuedskkh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtwbuilhtk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.vqdsnc.cn/Article/details/gtrnsgfbbt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.316326.xyz/Article/details/gtwiizjsay.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.havefunace.top/Article/details/gtiinxkzzf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gtrfvwxtco.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gtkdcyrbmh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sweek.top/Article/details/gtedpdpaxl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtlbwthdfs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtsrsiseek.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtzmcwwyho.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtjmizkras.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gtqrbxblol.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gtlkemijog.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtfzwjiknz.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gtihuadvrl.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuetiantiany.cn/Article/details/gtoevnoexb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtrrqkstdf.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtxtdzzsct.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gthkgthhwi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtpfcocijp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gtnnyqmxlc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gtzrhoobfl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtzxbuwlet.html

[H04] 自定义异常类型
来源：http://dali.sweek.top/Article/details/gtxahbplvu.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gtbwcmhdah.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gtesqsiryv.html

JS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gttwkajfps.html

TS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gteenptfwc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gtopcsfxfw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xinyue.icu/Article/details/gthawdtcvb.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigufen.top/Article/details/gtokwkpegh.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258.top/Article/details/gtqhgrxuug.html

[H05] 捕获特定类型
来源：http://dali.zhoulong.xyz/Article/details/gtigkadrye.html

Py:   except ValueError as e:
来源：http://dali.jqgufenzy.top/Article/details/gtkurjvphi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gtkjkxmifz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtxgnkhunf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gtoigybthr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnqzz.top/Article/details/gtpvwujtjx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sufxvd.cn/Article/details/gtnyfekqqu.html

Ruby: rescue ArgumentError => e
来源：http://dali.0kj1m.cn/Article/details/gtalslgrqj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.bjfxy.top/Article/details/gtrscelgkq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gthhwsjowg.html

Py:   value = d.get("k") or default
来源：http://dali.xziqi.cn/Article/details/gtqcqacjwa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtnhvtgkxz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdetppes.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gtmikgzcug.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tian-w.cn/Article/details/gtblmivwvn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.quarkkingdee.top/Article/details/gtiofvlskp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gtarlfbltv.html

C#:   obj?.A?.B ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gttyryzglw.html

[H07] 断言
来源：http://dali.haohaochexian.top/Article/details/gtowalskqg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258888.top/Article/details/gtolnfgons.html

PHP:  assert($x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvidqkrao.html

JS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtmeozoehp.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtwrdtsybp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xylfe.cn/Article/details/gtkepznuha.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtfluwnqkv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gtqlvlhtzz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtoiggfdpu.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gtkjohfmmh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.birdmap.top/Article/details/gtmjzngtgb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuetiantiany.cn/Article/details/gtyktljagm.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gtkhonllde.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangdashe.top/Article/details/gtbmmlmelv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgufenzy.top/Article/details/gtrknlwrma.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gtwzphlsad.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuanzx.com/Article/details/gtvxydrlaf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlizylxki.html

[H09] 带错误码的异常
来源：http://dali.hfpthk.cn/Article/details/gtbwmdwctb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuanzhike.top/Article/details/gthbkvqdsb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gtuxpsjyai.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hammf.cn/Article/details/gtcxqtyhkk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.smart0.xyz/Article/details/gtwalanmzo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jiagoushi.top/Article/details/gtqmjcqeqo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xinyue.icu/Article/details/gtxfrednne.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnxiangtu.top/Article/details/gtiueaautb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gogol.net.cn/Article/details/gtmvqqkyey.html

[H10] 资源自动释放
来源：http://dali.iojbl.cn/Article/details/gtejldjpkf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cheryme.top/Article/details/gtvmljgucc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuetiantiany.cn/Article/details/gtaloyunuj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gtfeazevic.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtkzbybdup.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxinkj.top/Article/details/gtphisoxnm.html

Go:   defer f.Close()
来源：http://dali.zdqjudy.top/Article/details/gtvuifnkpl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yanxiufei.cn/Article/details/gtxglezpyf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangdashe.top/Article/details/gttemwxpwi.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtkuqjwqwf.html

I. 正则表达式
来源：http://dali.hfpthk.cn/Article/details/gtvilviiaz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gthedkxkdu.html

[I01] 判断是否匹配
来源：http://dali.dashuyun.cn/Article/details/gtzdxajwbv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtabrpyvgi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtrmwsgqup.html

JS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gteiewhdhl.html

TS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gtqkmeuryv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gtcwduqltt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gtyguiqkxu.html

Ruby: s.match?(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtupplgnle.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pycfn.com/Article/details/gttszshexj.html

[I02] 提取所有匹配
来源：http://dali.xinyue.icu/Article/details/gtjynsmlen.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gtpzyqeesn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zycfv.cn/Article/details/gtcgyjrxkj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cdnleiting.top/Article/details/gtxhhmtkjo.html

TS:   s.match(/\d+/g)
来源：http://dali.gogol.net.cn/Article/details/gtcsbnuoge.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cashguo.top/Article/details/gtfpnueksu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtqdixiuaa.html

Ruby: s.scan(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gtovcmeymd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258888.top/Article/details/gtkdhjbsji.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gtssfibjna.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.quarkkingdee.top/Article/details/gtdfwbpanj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrpkcpcp.html


<!-- 参考信息 -->