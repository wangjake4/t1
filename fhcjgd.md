代发 wailian999

[F09] 获取文件大小
来源：http://dali.cheryme.top/Article/details/gt2jwtwiasw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2gvejithk.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2qphxemdi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gt2erzasmbg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gt2repubijb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gt2tynvarxr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xylfe.cn/Article/details/gt2ouxrjnda.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2xjvsrljs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xylfe.cn/Article/details/gt2uehtgpyt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxuanxn.top/Article/details/gt2ppwshmfb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2qfsqpzmi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2jnxmzain.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2bhgxhajr.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2eehmpggb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dibzqsuc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2pevxjxoz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2ibjwemno.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ksjyopvz.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qhunehsd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2owjvacui.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sxryk.cn/Article/details/gt2apyqlwys.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rvetxicl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2pxxduijr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.redwolf501.top/Article/details/gt2baaxwgby.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gt2mwakeloh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rbxyohjy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cashguo.top/Article/details/gt2asecgzus.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gt2cfwlldwj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangdashe.top/Article/details/gt2bycuwpxi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shuidangran.top/Article/details/gt2uwgzsncg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.vqdsnc.cn/Article/details/gt2phsyater.html

TS:   // 同上
来源：http://dali.bjfxy.top/Article/details/gt2rcqxdruo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ztpcnexm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxuanxn.top/Article/details/gt2doaznyjf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.0kj1m.cn/Article/details/gt2lbuxupvc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gt2imjkxoyj.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2knwpyptx.html

G. 面向对象
来源：http://dali.chenzaomai.com/Article/details/gt2yzmvkiyk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2masdtyqw.html

[G01] 定义类
来源：http://dali.snrcjt.cn/Article/details/gt2hmljwztm.html

Py:   class User: pass
来源：http://dali.xylfe.cn/Article/details/gt2ejjglagr.html

PHP:  class User {}
来源：http://dali.sweek.top/Article/details/gt2fbwnuwwa.html

JS:   class User {}
来源：http://dali.aizwys.cn/Article/details/gt2hxpkqsbg.html

TS:   class User { name: string = ""; }
来源：http://dali.cheryme.top/Article/details/gt2dyyhleqn.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2obkeetuk.html

Go:   type User struct { Name string }
来源：http://dali.xuetiantiany.cn/Article/details/gt2uizvxknv.html

Ruby: class User; end
来源：http://dali.0kj1m.cn/Article/details/gt2qjwnffer.html

C#:   class User {}
来源：http://dali.tanke756.top/Article/details/gt2zoqupqnv.html

[G02] 构造函数
来源：http://dali.svipenyu.cn/Article/details/gt2dsllibfy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jlsjyb.cn/Article/details/gt2yjuuawgv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.c1oappe.top/Article/details/gt2ryhsbjrc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gt2lohbieip.html

TS:   constructor(public name: string) {}
来源：http://dali.svipenyu.cn/Article/details/gt2usotwstn.html

Java: User(String name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2rgthwqrl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fzhhl.top/Article/details/gt2fgbitydn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sysykeji.top/Article/details/gt2vqvulkhs.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2oczcqulb.html

[G03] 实例属性
来源：http://dali.jinqigufen.top/Article/details/gt2dlptysnd.html

Py:   self.name = "x"
来源：http://dali.guowangkeji.top/Article/details/gt2xncjjbls.html

PHP:  public string $name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2dnrvtwca.html

JS:   this.name = "x";
来源：http://dali.ivvv.top/Article/details/gt2pxazldsj.html

TS:   name: string = "x";
来源：http://dali.ehwqpu.com/Article/details/gt2yalufpuc.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gt2pczqbunl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gaohongyu789.top/Article/details/gt2uzjumtiw.html

Ruby: @name = "x"
来源：http://dali.ehwqpu.com/Article/details/gt2olzatzfz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhengqikj.top/Article/details/gt2rrkgfgsl.html

[G04] 定义方法
来源：http://dali.jiagoushi.top/Article/details/gt2vizlclck.html

Py:   def greet(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gt2rjianrgu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2cjvxexsv.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2mtttimnt.html

TS:   greet(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2jweicokk.html

Java: String greet() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2lohxitze.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gt2ggzluurx.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gt2xiunruzs.html

C#:   public string Greet() => Name;
来源：http://dali.cheryme.top/Article/details/gt2usljrgio.html

[G05] 继承
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ycbnpguh.html

Py:   class Admin(User): pass
来源：http://dali.tianlin.xyz/Article/details/gt2rnesvbip.html

PHP:  class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gt2cavyegsu.html

JS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2rvjwirgq.html

TS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2ujchzldw.html

Java: class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2dgutgosq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cheryme.top/Article/details/gt2lwemaill.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gt2jzjqhxbw.html

C#:   class Admin : User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ccxokzdg.html

[G06] 重写方法
来源：http://dali.shuidangran.top/Article/details/gt2ywgcszyy.html

Py:   def greet(self): return "admin"
来源：http://dali.tianlin.xyz/Article/details/gt2mzvvsuuu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2bbsbdsua.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2lpnobigw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2yfnkpqcc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcorzfo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gt2sgjmfkzv.html

Ruby: def greet; "admin"; end
来源：http://dali.ybcxt.top/Article/details/gt2jsvakepf.html

C#:   public override string Greet() => "admin";
来源：http://dali.pycfn.com/Article/details/gt2ntwksooa.html

[G07] 调用父类方法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqbdxvjh.html

Py:   super().greet()
来源：http://dali.iojbl.cn/Article/details/gt2alclqzud.html

PHP:  parent::greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2fprumons.html

JS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gt2qentwpjx.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2ozlaatlo.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gt2xqzpjwtv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yvedp.cn/Article/details/gt2lszqiyrs.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gt2gvesygus.html

C#:   base.Greet();
来源：http://dali.xuanzx.com/Article/details/gt2cfuoneth.html

[G08] 静态方法与属性
来源：http://dali.snrcjt.cn/Article/details/gt2wqdsmoku.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jyoumei.cn/Article/details/gt2vqvrrvco.html

PHP:  public static function f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2puqhlroy.html

JS:   static f() {}
来源：http://dali.yuxming.cn/Article/details/gt2bgwipohl.html

TS:   static f(): void {}
来源：http://dali.cqqwz.cn/Article/details/gt2xwtoidxl.html

Java: static void f() {}
来源：http://dali.quarkkingdee.top/Article/details/gt2explxday.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pycfn.com/Article/details/gt2dxscxweo.html

Ruby: def self.f; end
来源：http://dali.yanxiufei.cn/Article/details/gt2mtvxmcik.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trxkxqrh.html

[G09] 接口 / 抽象类
来源：http://dali.feifeiyinyue.top/Article/details/gt2owluziby.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ubrzfqhl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yanxiufei.cn/Article/details/gt2yekecrhj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dianchejie.cn/Article/details/gt2mfjoqyya.html

TS:   interface Shape { area(): number; }
来源：http://dali.0kj1m.cn/Article/details/gt2rgpfkahu.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ilyligzj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daxiang520.top/Article/details/gt2lacvsfcx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yangfankeji.com/Article/details/gt2cwhtzqnc.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgfzy.top/Article/details/gt2pxlukiuc.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gt2rappigro.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zycfv.cn/Article/details/gt2eqeabibm.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2fgvcstxg.html

JS:   #private 字段；其余公开
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqascyuw.html

TS:   public / protected / private
来源：http://dali.aizwys.cn/Article/details/gt2xjsfbohk.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gt2yycmaubq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.feifeiyinyue.top/Article/details/gt2vgapketq.html

Ruby: public / protected / private
来源：http://dali.bjfxy.top/Article/details/gt2pqucjipn.html

C#:   public / protected / private / internal
来源：http://dali.fengsongda.top/Article/details/gt2hrobhmte.html

[G11] getter / setter
来源：http://dali.pengpengdd.cyou/Article/details/gt2smxqnoil.html

Py:   @property 与 @x.setter
来源：http://dali.quarkkingdee.top/Article/details/gt2spshbpgv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gt2chzlzeob.html

JS:   get name() { return this._name; }
来源：http://dali.yonumen.top/Article/details/gt2bcqepihb.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oibrsqar.html

Java: public String getName() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2sooxevtg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gt2ipfgnzwj.html

Ruby: attr_accessor :name
来源：http://dali.xziqi.cn/Article/details/gt2fwzhhtbc.html

C#:   public string Name { get; set; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhewzfta.html

[G12] 对象转字符串
来源：http://dali.aizwys.cn/Article/details/gt2geqmofks.html

Py:   def __str__(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gt2biiliuln.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2rsctqhxa.html

JS:   toString() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gt2cbnjezbq.html

TS:   toString(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ggsaaxph.html

Java: @Override public String toString() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ociednne.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gt2uwpcdtrb.html

Ruby: def to_s; @name; end
来源：http://dali.svipenyu.cn/Article/details/gt2mgluflxs.html

C#:   public override string ToString() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2moxcnifn.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2bgeqmayf.html

Py:   isinstance(u, User)
来源：http://dali.jqgfzy.top/Article/details/gt2xmxoexwl.html

PHP:  $u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2zrionojk.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2ybjccmlz.html

TS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2umkudmut.html

Java: u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2cavuvwbf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ivvv.top/Article/details/gt2tgfizjeu.html

Ruby: u.is_a?(User)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gmfkgqjz.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gt2xjgvycyz.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gt2nuurzawt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangdashe.top/Article/details/gt2ojoacdum.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuetiantiany.cn/Article/details/gt2btvegqkz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhongyouzk.top/Article/details/gt2ypqvhnes.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gt2jedhkudk.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gt2sgbnquaa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gt2xearjekb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.snrcjt.cn/Article/details/gt2ctqomljm.html

C#:   record User(string Name, int Age);
来源：http://dali.redwolf501.top/Article/details/gt2tauekbae.html

[G15] 枚举
来源：http://dali.havefunace.top/Article/details/gt2zpvcgsjh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zdqjudy.top/Article/details/gt2nrnoognd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ppjwa.cn/Article/details/gt2czjodnxh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gzhubu.top/Article/details/gt2dqcmuaok.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gt2xbygondl.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gt2odlserza.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cheryme.top/Article/details/gt2zkxtmbab.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pycfn.com/Article/details/gt2oiisdzuk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gt2qvgyullw.html

[G16] 对象转数组 / 字典
来源：http://dali.shzxlz.cn/Article/details/gt2wzsovlyh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhoulong.xyz/Article/details/gt2zuynafqn.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuovpca.html

JS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gt2ualnltti.html

TS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gt2kbawadji.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gt2ykutplxa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenzaomai.com/Article/details/gt2kuxoadmm.html

Ruby: obj.instance_variables
来源：http://dali.aibaodan.cn/Article/details/gt2csqyaegy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gt2agvnuyki.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2esfcukxi.html

H. 异常与错误处理
来源：http://dali.jianghu66.top/Article/details/gt2cxqudomm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2yepwsnjc.html

[H01] try / catch 基础
来源：http://dali.daxiang520.top/Article/details/gt2gryolnaj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2imemkscb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.andypj.xyz/Article/details/gt2odpaxybc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gt2zuxfgjxd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yummgfkg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gt2ftyzscbx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.c1oappe.top/Article/details/gt2rzycdsqf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gt2hrkprnka.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gaohongyu789.top/Article/details/gt2myuelabg.html

[H02] finally / ensure 收尾
来源：http://dali.shangyingyoupin.top/Article/details/gt2sshztqft.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yangfankeji.com/Article/details/gt2woaokdkl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2smzwqjfc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2qmkyreyj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2vpjjwltu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gt2zunweeeh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.bjfxy.top/Article/details/gt2seeqitxt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daxiang520.top/Article/details/gt2pnsdhdrf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2wvimmalt.html

[H03] 主动抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gt2bcowcikx.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpotlja.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2lzpelute.html

JS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2dxnuklpl.html

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2yezmnqhc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2qdswzwtv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rbpuajih.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yangfankeji.com/Article/details/gt2hrlhaqwb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2dvwjwkxd.html

[H04] 自定义异常类型
来源：http://dali.redwolf501.top/Article/details/gt2bifjhlzu.html

Py:   class MyError(Exception): pass
来源：http://dali.pycfn.com/Article/details/gt2xyfgfssr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2imyrzvdc.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gt2mjsxklxa.html

TS:   class MyError extends Error {}
来源：http://dali.shzxlz.cn/Article/details/gt2wghpfxna.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gt2updtibuu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aibaodan.cn/Article/details/gt2vouaivuu.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhoulong.xyz/Article/details/gt2ejbksqod.html

C#:   class MyException : Exception {}
来源：http://dali.wangdashe.top/Article/details/gt2sgvlfvvf.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gt2diuihrft.html

Py:   except ValueError as e:
来源：http://dali.chenjidiqi.icu/Article/details/gt2geevfcto.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258888.top/Article/details/gt2ndxfhdvw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gt2vowzkpvw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gt2nrwssprd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shzxlz.cn/Article/details/gt2wzivstjv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gt2xpsmldyz.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gt2oyzkrcjl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhengqikj.top/Article/details/gt2ciwtsxoi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pfyikbnb.html

Py:   value = d.get("k") or default
来源：http://dali.guannengcc.top/Article/details/gt2pprtoiww.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gt2zjhveutv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gt2ydtecfzf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gt2hqlplwcm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgufenzy.top/Article/details/gt2txqmaeyq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.0kj1m.cn/Article/details/gt2xtunnmtv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gt2jhovuojz.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gt2fqcmcunt.html

[H07] 断言
来源：http://dali.yvedp.cn/Article/details/gt2dkdwwbkj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.feifeiyinyue.top/Article/details/gt2typgequr.html

PHP:  assert($x > 0);
来源：http://dali.zycfv.cn/Article/details/gt2aobmezyh.html

JS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gt2dudfecqj.html

TS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2cburvtxy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.birdmap.top/Article/details/gt2wliqkpls.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daxiang520.top/Article/details/gt2rdkaqrxl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hywenlv.cn/Article/details/gt2mmovotwp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gt2oydgdyqv.html

[H08] 获取错误信息与堆栈
来源：http://dali.nanxuanxn.top/Article/details/gt2agxtvayd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.quarkkingdee.top/Article/details/gt2quqzmeps.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuanzhike.top/Article/details/gt2ynwgemqc.html

JS:   e.message;  e.stack
来源：http://dali.sweek.top/Article/details/gt2sekqofmz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shuidangran.top/Article/details/gt2jtdkpgaz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yongpay.top/Article/details/gt2cizhgdfr.html

Go:   err.Error()
来源：http://dali.cheryme.top/Article/details/gt2sprbudhh.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gt2mekshfih.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hfpthk.cn/Article/details/gt2cdhlmaue.html

[H09] 带错误码的异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2ojuhmbjt.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigfzy.top/Article/details/gt2jidrfouq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.316326.xyz/Article/details/gt2ulretsmk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ppjwa.cn/Article/details/gt2errijhip.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aizwys.cn/Article/details/gt2pvffpfxr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ppjwa.cn/Article/details/gt2knflgosd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2lsxbwqrg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tianlin.xyz/Article/details/gt2sbdrqfgq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.aizwys.cn/Article/details/gt2hzymsnql.html

[H10] 资源自动释放
来源：http://dali.cucudq.cn/Article/details/gt2vhublyws.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenlongwang.top/Article/details/gt2rsxgmnsl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zycfv.cn/Article/details/gt2lzdnrjrb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbsiasrm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gt2vseexolf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gt2toaaswjq.html

Go:   defer f.Close()
来源：http://dali.shangyingyoupin.top/Article/details/gt2heqxxslw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tanke756.top/Article/details/gt2ifyexwkk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2bpymltdl.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2htqugxhj.html

I. 正则表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2tpmuuqwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pqihllxn.html

[I01] 判断是否匹配
来源：http://dali.birdmap.top/Article/details/gt2ijdbrvrv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gt2iiviqseq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cheryme.top/Article/details/gt2dscxjvdc.html

JS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2bduoahss.html

TS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vbbbyutu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cucudq.cn/Article/details/gt2sieqhqjz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gt2wpowyzfe.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xqhhfnuz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xexpvynn.html

[I02] 提取所有匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2xafshoti.html

Py:   re.findall(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gt2lrfemeck.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258888.top/Article/details/gt2rvsyuxqe.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.fzhhl.top/Article/details/gt2fsoinitv.html

TS:   s.match(/\d+/g)
来源：http://dali.sysykeji.top/Article/details/gt2mdqqdnjc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2gyyrzzqh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hysaishi.cn/Article/details/gt2idvfyvsg.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gsvgrhhr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yonumen.top/Article/details/gt2vmkcjpsy.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gt2kshdjcrg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hammf.cn/Article/details/gt2txyhqmvo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenlongwang.top/Article/details/gt2llibeggb.html


<!-- 参考信息 -->