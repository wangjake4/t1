代发 wailian999

[F09] 获取文件大小
来源：http://dali.yonumen.top/Article/details/gt2isberheh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ykaejbmy.html

PHP:  filesize("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2rxkzcvmk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gt2qjikoktr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gt2kbthqtdf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2jhmzyrww.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqsygbws.html

Ruby: File.size("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2wvtgjubi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oojwsxbv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sweek.top/Article/details/gt2flkwcenp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2ndrbzpoe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2lviasdns.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2gcwzchvg.html

TS:   path.extname("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2muxuydwm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gt2hdjwyvam.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2cljndigv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2mkszhkhn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2hasvkcqe.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gt2shcpbpiy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2mfozpmuk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2vefvmoqd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2kpxoyolq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2glczlxuh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mvaxsysc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ydzc1.top/Article/details/gt2moibodva.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2tkwtobhj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ltbtcuno.html

[F12] CSV 读写
来源：http://dali.cucudq.cn/Article/details/gt2cjrcyigm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigfzy.top/Article/details/gt2hpqykwak.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj202588.top/Article/details/gt2qbcwodpq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxuanxn.top/Article/details/gt2faaaduex.html

TS:   // 同上
来源：http://dali.shuidangran.top/Article/details/gt2fjxhmprb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangshuangyany.cn/Article/details/gt2rdncnhkx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gt2vkrfttrj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.meibo888.top/Article/details/gt2gmgtrpii.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gt2owidhclh.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2jeedczjr.html

G. 面向对象
来源：http://dali.zhongyouzk.top/Article/details/gt2ijrcvcfo.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fumrvtrd.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gt2hetpxyjf.html

Py:   class User: pass
来源：http://dali.chenjidiqi.icu/Article/details/gt2wgbfnrjo.html

PHP:  class User {}
来源：http://dali.gzhubu.top/Article/details/gt2ufabucrq.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2gfdznckv.html

TS:   class User { name: string = ""; }
来源：http://dali.jiagoushi.top/Article/details/gt2lfmdpfks.html

Java: class User {}
来源：http://dali.shuidangran.top/Article/details/gt2eelpozbb.html

Go:   type User struct { Name string }
来源：http://dali.jinqigufen.top/Article/details/gt2yxmtjfrt.html

Ruby: class User; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2ncvzwadu.html

C#:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2zndqqeqr.html

[G02] 构造函数
来源：http://dali.kuanghao11.cn/Article/details/gt2pauuixrc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangdashe.top/Article/details/gt2scusnzqn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangdashe.top/Article/details/gt2mkhfdezo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gt2vjoqvlvp.html

TS:   constructor(public name: string) {}
来源：http://dali.wangdashe.top/Article/details/gt2jhgzdety.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pniynnvi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yvedp.cn/Article/details/gt2upfqlsdw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jiagoushi.top/Article/details/gt2vthozisa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vycabtdt.html

[G03] 实例属性
来源：http://dali.cdnleiting.top/Article/details/gt2locccwcj.html

Py:   self.name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zdxlbibn.html

PHP:  public string $name = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2uyaufetl.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kigjulnm.html

TS:   name: string = "x";
来源：http://dali.wangdashe.top/Article/details/gt2mykkghpe.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gt2uyysqkje.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gaohongyu789.top/Article/details/gt2uvotaqqt.html

Ruby: @name = "x"
来源：http://dali.tianlin.xyz/Article/details/gt2gawehecr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2yncvewux.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gt2rtvahqlo.html

Py:   def greet(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gt2wdugufnc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2muejflqk.html

JS:   greet() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2pbokaeel.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2mumvkokd.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2arxgwuzo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gt2rmkksxdv.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gt2vjwuehiw.html

C#:   public string Greet() => Name;
来源：http://dali.dianchejie.cn/Article/details/gt2tnnmeonu.html

[G05] 继承
来源：http://dali.vqdsnc.cn/Article/details/gt2foceiyhu.html

Py:   class Admin(User): pass
来源：http://dali.cdnleiting.top/Article/details/gt2ckugsnxe.html

PHP:  class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gt2pzovbhsb.html

JS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gt2pbrxftyt.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gt2eczpwxqf.html

Java: class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gt2rbjlwquh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhixingplan.top/Article/details/gt2hwhcqqee.html

Ruby: class Admin < User; end
来源：http://dali.haohaochexian.top/Article/details/gt2ovfedemr.html

C#:   class Admin : User {}
来源：http://dali.hysaishi.cn/Article/details/gt2ujqerzxk.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gt2sspymfyb.html

Py:   def greet(self): return "admin"
来源：http://dali.cashguo.top/Article/details/gt2wdbwvkmk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2etooljuy.html

JS:   greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2iwggkoln.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2yhvwfzoh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lgzlqzge.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gt2vxuvqqgq.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gt2jsgfuxpm.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxinkj.top/Article/details/gt2arfvaglx.html

[G07] 调用父类方法
来源：http://dali.nwbrower.top/Article/details/gt2foxlkxpv.html

Py:   super().greet()
来源：http://dali.dianchejie.cn/Article/details/gt2zvmwkknl.html

PHP:  parent::greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2mbreboug.html

JS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zwpnxhic.html

TS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gt2oalfbuxu.html

Java: super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2zsgzofur.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhongyouzk.top/Article/details/gt2wjgqpoxc.html

Ruby: super
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnqwglxv.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gt2dwxerfsq.html

[G08] 静态方法与属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2ndoxyizj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yonumen.top/Article/details/gt2nqauweht.html

PHP:  public static function f() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2dqvzvgaz.html

JS:   static f() {}
来源：http://dali.yvedp.cn/Article/details/gt2avklszud.html

TS:   static f(): void {}
来源：http://dali.cdnleiting.top/Article/details/gt2vgnmodll.html

Java: static void f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2tnvcgcqx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gt2tawwessd.html

Ruby: def self.f; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2qbpitcrm.html

C#:   public static void F() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2hhkekurb.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigfzy.top/Article/details/gt2vjvchwbe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dashuyun.cn/Article/details/gt2hxlkgwfv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ftritker.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pengpengdd.cyou/Article/details/gt2mvjwlhcj.html

TS:   interface Shape { area(): number; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wkpgocdp.html

Java: interface Shape { double area(); }
来源：http://dali.xinyue.icu/Article/details/gt2hifydigl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigufen.top/Article/details/gt2rwormrmq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tianlin.xyz/Article/details/gt2pvggrqyo.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj202588.top/Article/details/gt2yqusuzxn.html

[G10] 访问控制
来源：http://dali.sxryk.cn/Article/details/gt2flrorcsy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tianlin.xyz/Article/details/gt2btgetytm.html

PHP:  public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2edxmkvnw.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigufen.top/Article/details/gt2lmwhmpwy.html

TS:   public / protected / private
来源：http://dali.fengsongda.top/Article/details/gt2xevhuegt.html

Java: public / protected / private / 默认包级
来源：http://dali.cdnleiting.top/Article/details/gt2jyvwmytj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gt2mefhktzc.html

Ruby: public / protected / private
来源：http://dali.redwolf501.top/Article/details/gt2vxouyivs.html

C#:   public / protected / private / internal
来源：http://dali.hnqzz.top/Article/details/gt2ibmwmdao.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gt2zpvzczqz.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gt2bnyicaad.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gt2hzvpelrv.html

JS:   get name() { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gt2svlivnpq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gt2ffvlrszv.html

Java: public String getName() { return name; }
来源：http://dali.meibo888.top/Article/details/gt2qlazobxv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gt2qnoenmis.html

Ruby: attr_accessor :name
来源：http://dali.zhixingplan.top/Article/details/gt2kqgnssoq.html

C#:   public string Name { get; set; }
来源：http://dali.redwolf501.top/Article/details/gt2phlivhmf.html

[G12] 对象转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2vokywiyk.html

Py:   def __str__(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gt2xjqgprar.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gt2rgupqozg.html

JS:   toString() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2bnsftfen.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gt2ialeebsx.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2arlpexxr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gt2aclsvdzm.html

Ruby: def to_s; @name; end
来源：http://dali.dashuyun.cn/Article/details/gt2xpligllx.html

C#:   public override string ToString() => Name;
来源：http://dali.meibo888.top/Article/details/gt2hwchlpsq.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gt2akpqetio.html

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gt2twlospba.html

PHP:  $u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2bhiepbpz.html

JS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2thiowekm.html

TS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2qmltuqak.html

Java: u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2biddjenh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuetiantiany.cn/Article/details/gt2pemklhyf.html

Ruby: u.is_a?(User)
来源：http://dali.gaohongyu789.top/Article/details/gt2pezmumib.html

C#:   u is User
来源：http://dali.kuanghao11.cn/Article/details/gt2fgnnfhqu.html

[G14] 数据类 / record
来源：http://dali.guowangkeji.top/Article/details/gt2ovbtcycq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hammf.cn/Article/details/gt2gykgtonk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258888.top/Article/details/gt2edtvyrjn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.svipenyu.cn/Article/details/gt2ceamamxu.html

TS:   type User = { name: string; age: number };
来源：http://dali.hammf.cn/Article/details/gt2nygmeryu.html

Java: record User(String name, int age) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2tbkcpvui.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ehwqpu.com/Article/details/gt2dwobyvuq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gt2egktswgz.html

C#:   record User(string Name, int Age);
来源：http://dali.hnqzz.top/Article/details/gt2irjskyre.html

[G15] 枚举
来源：http://dali.jianghu66.top/Article/details/gt2knyxuenl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gt2uubvalkq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.iojbl.cn/Article/details/gt2tahpkqjh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pengpengdd.cyou/Article/details/gt2ahzjdnjd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gt2bwvdohil.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnxiangtu.top/Article/details/gt2wtkqbhhz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aibaodan.cn/Article/details/gt2glsamwlg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhengqikj.top/Article/details/gt2prxmihll.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.mhx1999.top/Article/details/gt2udftbdqk.html

[G16] 对象转数组 / 字典
来源：http://dali.svipenyu.cn/Article/details/gt2dhorucrm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aibaodan.cn/Article/details/gt2uhkhxstc.html

PHP:  get_object_vars($obj);
来源：http://dali.gogol.net.cn/Article/details/gt2tutksjdy.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gt2itqsosvw.html

TS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2ovxqqofd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gt2qqzzsgnj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cucudq.cn/Article/details/gt2gclflsxt.html

Ruby: obj.instance_variables
来源：http://dali.aizwys.cn/Article/details/gt2yezxxeie.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gt2lultjotx.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2dnalspwj.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gt2xzhboefp.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2gmxdzocu.html

[H01] try / catch 基础
来源：http://dali.hongshengwenyu.top/Article/details/gt2ahegmxrx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gt2alhtrozc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.9152youxi.cn/Article/details/gt2toghsjfa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gt2pndkbsxh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gt2jdaetkkk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuanzx.com/Article/details/gt2fyjwpinc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xinyue.icu/Article/details/gt2ltgwkwcm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2ibyoirtc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gt2ihbwbgpd.html

[H02] finally / ensure 收尾
来源：http://dali.cucudq.cn/Article/details/gt2aqnznlwg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mdafjkjp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nxneqgvd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2yczvzorc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2cxlalame.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2ckcrzjpy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guowangkeji.top/Article/details/gt2qyacwypm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gt2alvgnuju.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2dgjxopht.html

[H03] 主动抛出异常
来源：http://dali.sweek.top/Article/details/gt2spfvmjkn.html

Py:   raise ValueError("错误信息")
来源：http://dali.xziqi.cn/Article/details/gt2amvoyoof.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2amfqyhpx.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2hnxltgsy.html

TS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2bcnfcajr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2adjinakn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gt2tarrlxkn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daxiang520.top/Article/details/gt2vizendvr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2dmbztmtr.html

[H04] 自定义异常类型
来源：http://dali.chenlongwang.top/Article/details/gt2hzqcyore.html

Py:   class MyError(Exception): pass
来源：http://dali.yj202588.top/Article/details/gt2xzmvybmd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gt2cggwvref.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2nodekwkl.html

TS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gt2hlwuniry.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gt2wfqdfawl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hammf.cn/Article/details/gt2msxlnxba.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj202588.top/Article/details/gt2vypymntq.html

C#:   class MyException : Exception {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oplpnbfm.html

[H05] 捕获特定类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2mumgqfbz.html

Py:   except ValueError as e:
来源：http://dali.yj20258888.top/Article/details/gt2jhgqcyox.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqbciej.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gt2fnvqgquq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gt2ivdaytii.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gt2uazljpqo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daria6918.cn/Article/details/gt2hfhostza.html

Ruby: rescue ArgumentError => e
来源：http://dali.hysaishi.cn/Article/details/gt2erdtqomx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigufen.top/Article/details/gt2ryvxaxyf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.kuanghao11.cn/Article/details/gt2kqqugxvj.html

Py:   value = d.get("k") or default
来源：http://dali.fengsongda.top/Article/details/gt2bhpesnda.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xtyvlthq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gt2wxgbkbif.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gt2xutpljwx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnqzz.top/Article/details/gt2uyasqqwi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hfttfeke.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gotoacloud.top/Article/details/gt2uvqrvpug.html

C#:   obj?.A?.B ?? default
来源：http://dali.meibo888.top/Article/details/gt2gwyookmo.html

[H07] 断言
来源：http://dali.hysaishi.cn/Article/details/gt2rrqvvwji.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yvedp.cn/Article/details/gt2cdfdekaf.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2ydgrjilp.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2gwqjyjok.html

TS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2aymqoeyv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.quarkkingdee.top/Article/details/gt2vyvufqwq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenlongwang.top/Article/details/gt2dtjjvmve.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnxiangtu.top/Article/details/gt2xjsrpqzj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2rmhduhlq.html

[H08] 获取错误信息与堆栈
来源：http://dali.daria6918.cn/Article/details/gt2oahrpdec.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gt2jckghynp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cqqwz.cn/Article/details/gt2ynzurskz.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gt2plptyyha.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258888.top/Article/details/gt2tmrhteqj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.quarkkingdee.top/Article/details/gt2ahyfufei.html

Go:   err.Error()
来源：http://dali.iojbl.cn/Article/details/gt2ephdeeoe.html

Ruby: e.message;  e.backtrace
来源：http://dali.shuidangran.top/Article/details/gt2kiglicdq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.quarkkingdee.top/Article/details/gt2qsvmjbsx.html

[H09] 带错误码的异常
来源：http://dali.yj20258888.top/Article/details/gt2jiophkwg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yonumen.top/Article/details/gt2svhwvgqm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhiwuduotai.top/Article/details/gt2urwcihvf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gzhubu.top/Article/details/gt2gitttvqy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gt2zsxotbek.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yonumen.top/Article/details/gt2sxuumgmi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guowangkeji.top/Article/details/gt2scmyndjt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.birdmap.top/Article/details/gt2tueevrvh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.mhx1999.top/Article/details/gt2lvckcrpd.html

[H10] 资源自动释放
来源：http://dali.cheryme.top/Article/details/gt2pchoyxas.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dashuyun.cn/Article/details/gt2ynekobkh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuanzx.com/Article/details/gt2gjwgpefs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gt2hjrbmzti.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gt2ltajkvfp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pycfn.com/Article/details/gt2tphxqpqw.html

Go:   defer f.Close()
来源：http://dali.nwbrower.top/Article/details/gt2rngqklkb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jblmicbw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2ztbpqzax.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2hltuwhoz.html

I. 正则表达式
来源：http://dali.nanxinkj.top/Article/details/gt2svaqlqsl.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2idkvirgc.html

[I01] 判断是否匹配
来源：http://dali.gotoacloud.top/Article/details/gt2ysebatib.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cetfegbd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xziqi.cn/Article/details/gt2myoxrtqu.html

JS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdudaem.html

TS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gt2yzwanjhh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenzaomai.com/Article/details/gt2zsulhvel.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2glkuhktx.html

Ruby: s.match?(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gt2hxnkwrxg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.andypj.xyz/Article/details/gt2zfcmpqdx.html

[I02] 提取所有匹配
来源：http://dali.ybcxt.top/Article/details/gt2sjzabziv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.0kj1m.cn/Article/details/gt2lpeyrzlg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hongshengwenyu.top/Article/details/gt2rsdeqinp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tevartur.html

TS:   s.match(/\d+/g)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uoqnvxuv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dsvqpole.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gxmrlmxs.html

Ruby: s.scan(/\d+/)
来源：http://dali.cheryme.top/Article/details/gt2ksyrrsrs.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jiagoushi.top/Article/details/gt2jwcwytvp.html

[I03] 提取捕获分组
来源：http://dali.shuidangran.top/Article/details/gt2pnralzbc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenlongwang.top/Article/details/gt2apcwkgiw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dashuyun.cn/Article/details/gt2awatodku.html


<!-- 参考信息 -->