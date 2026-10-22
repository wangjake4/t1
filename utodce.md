代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gt2jpxewpab.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2naoqfwqf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hywenlv.cn/Article/details/gt2urorbjtm.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2qecipixj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gt2oscwalsp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cheryme.top/Article/details/gt2zhzqaezi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2ylobnzcs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2oarbvlka.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2rwseaszf.html

TS:   path.extname("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xkcotrxy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guannengcc.top/Article/details/gt2wxglboxg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2vjfwmtgp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2lcjthjqw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2sjltmtyp.html

[F11] 复制与移动文件
来源：http://dali.zhoulong.xyz/Article/details/gt2jmabpdlm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gt2qesvqddk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuanzx.com/Article/details/gt2whuteatz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2gmloxpab.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2ljwgmqom.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gt2yakpintn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shuidangran.top/Article/details/gt2paluobrp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2uldsgblq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.quarkkingdee.top/Article/details/gt2nrjkolam.html

[F12] CSV 读写
来源：http://dali.yj20258.top/Article/details/gt2mbwkzwkv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.svipenyu.cn/Article/details/gt2eximxubr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.birdmap.top/Article/details/gt2tfcpbgkh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wpibvokj.html

TS:   // 同上
来源：http://dali.jyoumei.cn/Article/details/gt2kujskrpo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2manqdkcp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yangfankeji.com/Article/details/gt2dvndmqev.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.andypj.xyz/Article/details/gt2qzgepapp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gt2xfadkqev.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2ahekwfrj.html

G. 面向对象
来源：http://dali.sxryk.cn/Article/details/gt2qlurujvr.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2mlriegun.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gt2bpkjiixs.html

Py:   class User: pass
来源：http://dali.yvedp.cn/Article/details/gt2mcarscft.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gt2zynsfzny.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gt2ruunmoym.html

TS:   class User { name: string = ""; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jtbbzrfa.html

Java: class User {}
来源：http://dali.ivvv.top/Article/details/gt2wtkbvzkr.html

Go:   type User struct { Name string }
来源：http://dali.ydzc1.top/Article/details/gt2qtojmlsx.html

Ruby: class User; end
来源：http://dali.cdnleiting.top/Article/details/gt2ulaqqxae.html

C#:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gt2jbetcakv.html

[G02] 构造函数
来源：http://dali.jianghu66.top/Article/details/gt2arfykzxt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gt2kfpubenv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258888.top/Article/details/gt2jpvfjwso.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2ftmkperc.html

TS:   constructor(public name: string) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2drpbntet.html

Java: User(String name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gt2epihzset.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dashuyun.cn/Article/details/gt2rhoqkgbt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.quarkkingdee.top/Article/details/gt2flqdfzuy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2fhawlcro.html

[G03] 实例属性
来源：http://dali.smart0.xyz/Article/details/gt2jdokdnva.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gt2aqtnyrwb.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gt2ajazbdgf.html

JS:   this.name = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2ckoulaop.html

TS:   name: string = "x";
来源：http://dali.guannengcc.top/Article/details/gt2xmvsgoek.html

Java: private String name;
来源：http://dali.fengsongda.top/Article/details/gt2jcmmxwpa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gt2sbrihohg.html

Ruby: @name = "x"
来源：http://dali.cheryme.top/Article/details/gt2laxepkgj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2wxxuyrkk.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gt2poetcbww.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258.top/Article/details/gt2devjbdpy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gt2ofhqhfny.html

JS:   greet() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2sfngkygf.html

TS:   greet(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gt2eipvurne.html

Java: String greet() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2qcrfjvye.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gt2mkgqsybz.html

Ruby: def greet; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gt2atgvzgaa.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gt2umyrhuki.html

[G05] 继承
来源：http://dali.guannengcc.top/Article/details/gt2efnsjsjz.html

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gt2ikcbizuv.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2buvacymn.html

JS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2ahhiorjm.html

TS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2ixnnevrd.html

Java: class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2idzrhxtv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vedlrkmz.html

Ruby: class Admin < User; end
来源：http://dali.zhongyouzk.top/Article/details/gt2qxteexqy.html

C#:   class Admin : User {}
来源：http://dali.yueranfly.top/Article/details/gt2fisrltus.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gt2pcdqlkyb.html

Py:   def greet(self): return "admin"
来源：http://dali.wangdashe.top/Article/details/gt2edrtxkiw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2vxpuiijr.html

JS:   greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2glphrlqx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2vxbjfphg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2efobchlz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fzhhl.top/Article/details/gt2wolualxc.html

Ruby: def greet; "admin"; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2iqwobzzl.html

C#:   public override string Greet() => "admin";
来源：http://dali.jianghu66.top/Article/details/gt2hegtdzfa.html

[G07] 调用父类方法
来源：http://dali.zhiwuduotai.top/Article/details/gt2ssohwamv.html

Py:   super().greet()
来源：http://dali.c1oappe.top/Article/details/gt2kchxflvo.html

PHP:  parent::greet();
来源：http://dali.xziqi.cn/Article/details/gt2phqldztm.html

JS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gt2mugfhzcq.html

TS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gt2okydzmny.html

Java: super.greet();
来源：http://dali.zdqjudy.top/Article/details/gt2uynzmshj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.316326.xyz/Article/details/gt2enyfkiha.html

Ruby: super
来源：http://dali.cashguo.top/Article/details/gt2vrefsmrc.html

C#:   base.Greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2jctlingb.html

[G08] 静态方法与属性
来源：http://dali.yvedp.cn/Article/details/gt2pvftupnt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gt2coegyetr.html

PHP:  public static function f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2pxhouiib.html

JS:   static f() {}
来源：http://dali.c1oappe.top/Article/details/gt2ruucjsuv.html

TS:   static f(): void {}
来源：http://dali.0kj1m.cn/Article/details/gt2uomcbrjr.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2dyakyjyz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uqbjiaev.html

Ruby: def self.f; end
来源：http://dali.chenlongwang.top/Article/details/gt2ushapvue.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gt2qeblipyu.html

[G09] 接口 / 抽象类
来源：http://dali.chenzaomai.com/Article/details/gt2agngeepn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlskqyuy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gt2sewgmeic.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shangyingyoupin.top/Article/details/gt2eqkwljsa.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuanzx.com/Article/details/gt2qlhdguqb.html

Java: interface Shape { double area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zbrkpdir.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.smart0.xyz/Article/details/gt2enqnkjeu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aibaodan.cn/Article/details/gt2tqztagle.html

C#:   interface IShape { double Area(); }
来源：http://dali.0kj1m.cn/Article/details/gt2cidinhmm.html

[G10] 访问控制
来源：http://dali.daria6918.cn/Article/details/gt2emliwqce.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gt2gxvjuxff.html

PHP:  public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2rffbqsbc.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gt2rbzypqcn.html

TS:   public / protected / private
来源：http://dali.cashguo.top/Article/details/gt2lzmwzgnq.html

Java: public / protected / private / 默认包级
来源：http://dali.yueranfly.top/Article/details/gt2jxmgyqoq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnqzz.top/Article/details/gt2lcaswife.html

Ruby: public / protected / private
来源：http://dali.yj202588.top/Article/details/gt2fkygzokn.html

C#:   public / protected / private / internal
来源：http://dali.xylfe.cn/Article/details/gt2jhkcphxp.html

[G11] getter / setter
来源：http://dali.bjfxy.top/Article/details/gt2jgteyhym.html

Py:   @property 与 @x.setter
来源：http://dali.tian-w.cn/Article/details/gt2fpzelaou.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gt2rividfuo.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2uyqiduex.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2flfrlgxx.html

Java: public String getName() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2dfrnrjrg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gt2xuczftwa.html

Ruby: attr_accessor :name
来源：http://dali.pengpengdd.cyou/Article/details/gt2lcpxytgg.html

C#:   public string Name { get; set; }
来源：http://dali.ivvv.top/Article/details/gt2bkuchhwg.html

[G12] 对象转字符串
来源：http://dali.chenlongwang.top/Article/details/gt2qxfonxfc.html

Py:   def __str__(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gt2fcvgytpr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gt2flbbprxh.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2hwawcide.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gt2scofkmvz.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2yyglmbiu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2oabwfnpv.html

Ruby: def to_s; @name; end
来源：http://dali.jyoumei.cn/Article/details/gt2tzjqeutq.html

C#:   public override string ToString() => Name;
来源：http://dali.wangdashe.top/Article/details/gt2hjxznisv.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2hobojtxn.html

Py:   isinstance(u, User)
来源：http://dali.yvedp.cn/Article/details/gt2srcprakj.html

PHP:  $u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2aoaeghni.html

JS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2ewvyrpkd.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2xfktxwhx.html

Java: u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2yisscizv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yvedp.cn/Article/details/gt2atzeixwt.html

Ruby: u.is_a?(User)
来源：http://dali.sweek.top/Article/details/gt2phrjhjlk.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gt2bbxiwbok.html

[G14] 数据类 / record
来源：http://dali.tian-w.cn/Article/details/gt2btupyris.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yonumen.top/Article/details/gt2qrxmqhor.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.vqdsnc.cn/Article/details/gt2xaccvtbe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gt2nswhjhfx.html

TS:   type User = { name: string; age: number };
来源：http://dali.daria6918.cn/Article/details/gt2jpvgizxz.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gt2sxcmwseb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gt2ttbmeshs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gt2enydwnlb.html

C#:   record User(string Name, int Age);
来源：http://dali.gaohongyu789.top/Article/details/gt2xfzwheyl.html

[G15] 枚举
来源：http://dali.cashguo.top/Article/details/gt2ymoeaclt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258.top/Article/details/gt2xrurvaje.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2kgvjcbrm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwpazvyu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gt2vfrkeulj.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mrbtuilp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jyoumei.cn/Article/details/gt2pirtlwss.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gt2shtwpwxj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gt2lrwdivet.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gt2wkepuzsa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yangfankeji.com/Article/details/gt2ykmwojzv.html

PHP:  get_object_vars($obj);
来源：http://dali.316326.xyz/Article/details/gt2aimbxndx.html

JS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gt2irdkdtmt.html

TS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2uoircqcf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hongshengwenyu.top/Article/details/gt2pcxnqoxf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gt2akzfdrnw.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2onxwqriz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gt2bufkyngp.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2hgjruwae.html

H. 异常与错误处理
来源：http://dali.yvedp.cn/Article/details/gt2pgyxpmru.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2hjqwrgcu.html

[H01] try / catch 基础
来源：http://dali.andypj.xyz/Article/details/gt2akmxxtvs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gt2iaeckadq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gt2dwfylhdu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gt2lhrusxmw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gt2zgnbphgm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sysykeji.top/Article/details/gt2lnrphyom.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tian-w.cn/Article/details/gt2vbkffbsv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yonumen.top/Article/details/gt2qefrqckz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2yujemazp.html

[H02] finally / ensure 收尾
来源：http://dali.xylfe.cn/Article/details/gt2yejmgvhu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zgbpxnty.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2qmawmimo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2iqdwgkov.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2yehrxukw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2odupjngq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tanke756.top/Article/details/gt2vccpytsh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2xbllbmpi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2kvhwvoiw.html

[H03] 主动抛出异常
来源：http://dali.daria6918.cn/Article/details/gt2tqrdgukv.html

Py:   raise ValueError("错误信息")
来源：http://dali.jianghu66.top/Article/details/gt2ufuzllkm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2vxbkgfiu.html

JS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2wbenfrdt.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2yffslbky.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2zfiehfsr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gt2imgzhzfj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.birdmap.top/Article/details/gt2sioptmuo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2fdkobouo.html

[H04] 自定义异常类型
来源：http://dali.jianghu66.top/Article/details/gt2gkcrfeph.html

Py:   class MyError(Exception): pass
来源：http://dali.gotoacloud.top/Article/details/gt2chgkmfqn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gt2iitrdgfp.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wrfqgddc.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gt2qxljlhmi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gt2gdsjuepv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sufxvd.cn/Article/details/gt2oirxnrqs.html

Ruby: class MyError < StandardError; end
来源：http://dali.ybcxt.top/Article/details/gt2vlvymbww.html

C#:   class MyException : Exception {}
来源：http://dali.aibaodan.cn/Article/details/gt2mnpcjkxt.html

[H05] 捕获特定类型
来源：http://dali.havefunace.top/Article/details/gt2jqtybxus.html

Py:   except ValueError as e:
来源：http://dali.zhengqikj.top/Article/details/gt2ssvvumvk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qeeqdiqk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gt2rmlicrcf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2zfyyssjs.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hfpthk.cn/Article/details/gt2esbbcavx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gt2utjkbjgv.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gt2quagsebt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xylfe.cn/Article/details/gt2xoppaita.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jyoumei.cn/Article/details/gt2hxygimpm.html

Py:   value = d.get("k") or default
来源：http://dali.0kj1m.cn/Article/details/gt2nhuvegqr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gt2evqqpnxa.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2zxyyvjzf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gt2mgemffdn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fzhhl.top/Article/details/gt2dtimakja.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zdqjudy.top/Article/details/gt2gdskwmxb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifqobnpd.html

C#:   obj?.A?.B ?? default
来源：http://dali.vqdsnc.cn/Article/details/gt2krfekyss.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gt2gpivqzaf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xylfe.cn/Article/details/gt2snlxmzag.html

PHP:  assert($x > 0);
来源：http://dali.smart0.xyz/Article/details/gt2ujyuscjm.html

JS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdkkedmv.html

TS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gt2mwrsummz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shzxlz.cn/Article/details/gt2jbsitscl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gzhubu.top/Article/details/gt2ivdlexbk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gt2hbmvsqow.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lxrjzvfs.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhengqikj.top/Article/details/gt2pnebllir.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.smart0.xyz/Article/details/gt2abgkwvmp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ehwqpu.com/Article/details/gt2idiqiaog.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gt2udwjczmo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ybcxt.top/Article/details/gt2ohwlktyr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.bjfxy.top/Article/details/gt2xjuyppec.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gt2bpyplqhr.html

Ruby: e.message;  e.backtrace
来源：http://dali.svipenyu.cn/Article/details/gt2sxzbhtcl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xylfe.cn/Article/details/gt2zqxlhqfy.html

[H09] 带错误码的异常
来源：http://dali.xylfe.cn/Article/details/gt2pgllyrbj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shuidangran.top/Article/details/gt2jizfdbro.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.andypj.xyz/Article/details/gt2pqpbuetn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhixingplan.top/Article/details/gt2whtmpdom.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhixingplan.top/Article/details/gt2yqlsxsmt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2moiswlfc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gt2modaodle.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tianlin.xyz/Article/details/gt2lcnpxkyx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gt2jubpqufn.html

[H10] 资源自动释放
来源：http://dali.yangfankeji.com/Article/details/gt2tnvirlhg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangdashe.top/Article/details/gt2bxrfsyag.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wkrkobwt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gt2mpjfxemk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gt2mbrwpfmc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj202588.top/Article/details/gt2bsiscmnl.html

Go:   defer f.Close()
来源：http://dali.guannengcc.top/Article/details/gt2raaekikg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yanxiufei.cn/Article/details/gt2dmqtbjle.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2llhxondw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2pnhgoevx.html

I. 正则表达式
来源：http://dali.c1oappe.top/Article/details/gt2bmjfmloi.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2qrhdqzwm.html

[I01] 判断是否匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aazafuyj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.meibo888.top/Article/details/gt2jvewzlnx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gt2ubthgcux.html

JS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gt2xamljghd.html

TS:   /\d+/.test(s)
来源：http://dali.zycfv.cn/Article/details/gt2nbtouitr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.meibo888.top/Article/details/gt2xpbjeewu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2nrzspqvj.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gt2roarcszq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.havefunace.top/Article/details/gt2vsdbymxk.html

[I02] 提取所有匹配
来源：http://dali.jyoumei.cn/Article/details/gt2cpxdauco.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gt2zsybswgk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigufen.top/Article/details/gt2rwforrck.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aibaodan.cn/Article/details/gt2ypmtccqd.html

TS:   s.match(/\d+/g)
来源：http://dali.sxryk.cn/Article/details/gt2xtsvcnux.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2phxrsjfz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yonumen.top/Article/details/gt2zwcgerjk.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnqzz.top/Article/details/gt2zvmrghuo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2etnonqse.html

[I03] 提取捕获分组
来源：http://dali.guannengcc.top/Article/details/gt2ugzahmtj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ivvv.top/Article/details/gt2ijigctbh.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2duxhmrly.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sxryk.cn/Article/details/gt2eshqhskn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hywenlv.cn/Article/details/gt2oufatugn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nanxuanxn.top/Article/details/gt2fjkrsdtv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daria6918.cn/Article/details/gt2zerwgrdl.html


<!-- 参考信息 -->