代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oyjayunz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2nuvobsgg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xylfe.cn/Article/details/gt2lzhacpyn.html

Ruby: File.size("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2nznpcuwc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.redwolf501.top/Article/details/gt2mqcefoqq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gt2hvlmqegq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2yfustnca.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wajychib.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2jkkekasg.html

TS:   path.extname("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2wiybyxae.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zdqjudy.top/Article/details/gt2yecnzfmt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jcgchhnq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zlqrtihj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2vmodvqig.html

[F11] 复制与移动文件
来源：http://dali.guowangkeji.top/Article/details/gt2gguqlqhu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2cemaejbe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nwbrower.top/Article/details/gt2uidnaezm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gt2vxnmatap.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2grmkotiy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pycfn.com/Article/details/gt2xdyzkqmt.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zdqjudy.top/Article/details/gt2dlwzlvrl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2oasgtyca.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenzaomai.com/Article/details/gt2dhnnihaw.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gt2xmrkpeyg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.bjfxy.top/Article/details/gt2jnsxcwdj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.vqdsnc.cn/Article/details/gt2briqighp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yonumen.top/Article/details/gt2iclhshhg.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yklwqcnw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqzfbtnv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gt2whydouwv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuanzx.com/Article/details/gt2okekcdme.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqgvhwb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2frtherwe.html

G. 面向对象
来源：http://dali.chenzaomai.com/Article/details/gt2xwmezkqu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2ysbublxc.html

[G01] 定义类
来源：http://dali.mhx1999.top/Article/details/gt2bakthlmy.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gt2onrpufle.html

PHP:  class User {}
来源：http://dali.fengsongda.top/Article/details/gt2ucwdstcq.html

JS:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gt2epupwtzr.html

TS:   class User { name: string = ""; }
来源：http://dali.dashuyun.cn/Article/details/gt2lfwwxaaz.html

Java: class User {}
来源：http://dali.yueranfly.top/Article/details/gt2lcxikwfp.html

Go:   type User struct { Name string }
来源：http://dali.redwolf501.top/Article/details/gt2gwcguwhg.html

Ruby: class User; end
来源：http://dali.guannengcc.top/Article/details/gt2mwtxsusi.html

C#:   class User {}
来源：http://dali.yvedp.cn/Article/details/gt2exabjdci.html

[G02] 构造函数
来源：http://dali.yj202588.top/Article/details/gt2hzmewcbs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxinkj.top/Article/details/gt2piarqzhg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sufxvd.cn/Article/details/gt2onvhsdsg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2qupilmyo.html

TS:   constructor(public name: string) {}
来源：http://dali.cashguo.top/Article/details/gt2jqitrewp.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vcwpghjz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tanke756.top/Article/details/gt2qnurtiyi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigufen.top/Article/details/gt2etfyxips.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2tejtzfaq.html

[G03] 实例属性
来源：http://dali.cqqwz.cn/Article/details/gt2xdjxwtyb.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gt2vrqzyafz.html

PHP:  public string $name = "x";
来源：http://dali.iojbl.cn/Article/details/gt2uwtpiqwp.html

JS:   this.name = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2dyevdjso.html

TS:   name: string = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2wjivtopc.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gt2jgjahpau.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gt2sbtckvqh.html

Ruby: @name = "x"
来源：http://dali.svipenyu.cn/Article/details/gt2yzksidnl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2gnsgxtxs.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gt2tfajbyei.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gt2rynymhuc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gt2yojzexzy.html

JS:   greet() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gt2jvzsskfx.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2mklxecgg.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2kolymoqs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zsyqjwiy.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2jysciehh.html

C#:   public string Greet() => Name;
来源：http://dali.hfpthk.cn/Article/details/gt2dbkgtnyr.html

[G05] 继承
来源：http://dali.ivvv.top/Article/details/gt2xzndivmi.html

Py:   class Admin(User): pass
来源：http://dali.yj20258888.top/Article/details/gt2flizxyka.html

PHP:  class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwkcamvc.html

JS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2krwsmjfl.html

TS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2hxspndqz.html

Java: class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2ruiewtgv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gt2xqiwahsr.html

Ruby: class Admin < User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hvcmtefz.html

C#:   class Admin : User {}
来源：http://dali.smart0.xyz/Article/details/gt2omlywbuh.html

[G06] 重写方法
来源：http://dali.meibo888.top/Article/details/gt2qgnriqiv.html

Py:   def greet(self): return "admin"
来源：http://dali.hysaishi.cn/Article/details/gt2rlikyubj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gt2xplfirqh.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2pzdoijji.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2plkadkno.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2fykmehwo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tian-w.cn/Article/details/gt2szjjpnxr.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gt2osliftfw.html

C#:   public override string Greet() => "admin";
来源：http://dali.vqdsnc.cn/Article/details/gt2dybqmhcc.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2skrggdmc.html

Py:   super().greet()
来源：http://dali.snrcjt.cn/Article/details/gt2tnbputck.html

PHP:  parent::greet();
来源：http://dali.aizwys.cn/Article/details/gt2zleqbujn.html

JS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2arncfunc.html

TS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gt2ubdogghb.html

Java: super.greet();
来源：http://dali.yj20258.top/Article/details/gt2ciyhfjpr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gt2laghfcbi.html

Ruby: super
来源：http://dali.snrcjt.cn/Article/details/gt2kypdvigd.html

C#:   base.Greet();
来源：http://dali.cashguo.top/Article/details/gt2jgzzrqqr.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gt2nzfkcuih.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cdnleiting.top/Article/details/gt2jkcdexar.html

PHP:  public static function f() {}
来源：http://dali.hywenlv.cn/Article/details/gt2hsvubjvm.html

JS:   static f() {}
来源：http://dali.hysaishi.cn/Article/details/gt2uyjdvqlh.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gt2puhbgpma.html

Java: static void f() {}
来源：http://dali.smart0.xyz/Article/details/gt2bhvclkgq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhiwuduotai.top/Article/details/gt2gvvtnswd.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gt2lmfxkwyu.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gt2durnkezv.html

[G09] 接口 / 抽象类
来源：http://dali.chenjidiqi.icu/Article/details/gt2nmemnnil.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gt2wowtaztr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cucudq.cn/Article/details/gt2fuhyzosr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gt2rkpoosds.html

TS:   interface Shape { area(): number; }
来源：http://dali.bjfxy.top/Article/details/gt2dpesljdt.html

Java: interface Shape { double area(); }
来源：http://dali.hywenlv.cn/Article/details/gt2obwhwiod.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgufenzy.top/Article/details/gt2grqwlsfh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ydzc1.top/Article/details/gt2lhglsput.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2skeygnsq.html

[G10] 访问控制
来源：http://dali.svipenyu.cn/Article/details/gt2bgbomamw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shzxlz.cn/Article/details/gt2fgctvivc.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dsqxcsrt.html

JS:   #private 字段；其余公开
来源：http://dali.pengpengdd.cyou/Article/details/gt2kznhmyio.html

TS:   public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gt2gmjebshk.html

Java: public / protected / private / 默认包级
来源：http://dali.yongpay.top/Article/details/gt2txpeoeom.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sufxvd.cn/Article/details/gt2edvfpebm.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gt2yrsgxdmc.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gt2zdkbzlsq.html

[G11] getter / setter
来源：http://dali.fengsongda.top/Article/details/gt2bvglcmfy.html

Py:   @property 与 @x.setter
来源：http://dali.feifeiyinyue.top/Article/details/gt2dbupuzwp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hyjlkapg.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adshtxav.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2wpvssjxa.html

Java: public String getName() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2juhuvbuh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gt2ufsxwncr.html

Ruby: attr_accessor :name
来源：http://dali.shzxlz.cn/Article/details/gt2nyedehxg.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gt2jffxxngx.html

[G12] 对象转字符串
来源：http://dali.guowangkeji.top/Article/details/gt2ytxzcpgw.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gt2ccovemqs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2qjdljhks.html

JS:   toString() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gt2osuapllf.html

TS:   toString(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2mcerxlod.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2pthlxhul.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvoxpxs.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2dcmilkbb.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ddvnqwpp.html

[G13] 判断对象类型
来源：http://dali.zycfv.cn/Article/details/gt2wvsmdstu.html

Py:   isinstance(u, User)
来源：http://dali.hammf.cn/Article/details/gt2sxtfhxdi.html

PHP:  $u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2pripjnnh.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2xpylzece.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gt2prdicyap.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2pjaifndh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gt2qqftrkiy.html

Ruby: u.is_a?(User)
来源：http://dali.nanxinkj.top/Article/details/gt2jyhjpyyq.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eywhdkcn.html

[G14] 数据类 / record
来源：http://dali.nanxuanxn.top/Article/details/gt2udfgixxg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fzhhl.top/Article/details/gt2zybhscgk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.andypj.xyz/Article/details/gt2jbqklbid.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.snrcjt.cn/Article/details/gt2dultjtdx.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnxiangtu.top/Article/details/gt2anmsmqvo.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gt2hpjognpn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gt2kouszpmk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guannengcc.top/Article/details/gt2jxsydacw.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxinkj.top/Article/details/gt2wdvvvhit.html

[G15] 枚举
来源：http://dali.hywenlv.cn/Article/details/gt2lhgdlzwz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgfzy.top/Article/details/gt2dksywixp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.havefunace.top/Article/details/gt2xyjststa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2plsthgcc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2qxdftwcs.html

Java: enum Color { RED, GREEN }
来源：http://dali.yanxiufei.cn/Article/details/gt2zqidckqv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fengsongda.top/Article/details/gt2gotjdbvf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.0kj1m.cn/Article/details/gt2ayqywsws.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2qrjgwawv.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gt2asufnyjg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hongshengwenyu.top/Article/details/gt2zofiwhoh.html

PHP:  get_object_vars($obj);
来源：http://dali.cqqwz.cn/Article/details/gt2akfcpbca.html

JS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gt2bgerezjk.html

TS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2wdjtrxqd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.quarkkingdee.top/Article/details/gt2iuraehom.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gt2wddcqoze.html

Ruby: obj.instance_variables
来源：http://dali.guannengcc.top/Article/details/gt2dwypdvvp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gt2inhvbydp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2balszlpt.html

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gt2xmzlsjeo.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ldxzlsou.html

[H01] try / catch 基础
来源：http://dali.jinqigfzy.top/Article/details/gt2tnyoeyax.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cdnleiting.top/Article/details/gt2cujmezbc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gt2dwbhlwnz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gt2thhsdeje.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gt2tyjfbnsj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gt2uyewfmry.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.birdmap.top/Article/details/gt2jfcgtutz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhoulong.xyz/Article/details/gt2wpgsdhhu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gt2pxrudakg.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gt2gketpxug.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sxryk.cn/Article/details/gt2tysiatve.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2nfsffcte.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2zwbagkxl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2rdajiysj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvlkjdks.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.0kj1m.cn/Article/details/gt2eepaxebr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jianghu66.top/Article/details/gt2mbedajxn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2zakmzwqd.html

[H03] 主动抛出异常
来源：http://dali.daxiang520.top/Article/details/gt2fxqawcun.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gt2bscirzyf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2gjwrvzio.html

JS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2fhdbpeem.html

TS:   throw new Error("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2obkzldto.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2izfsvvnl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tianlin.xyz/Article/details/gt2gxsduibe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gt2oqidhzyl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jvpxksvs.html

[H04] 自定义异常类型
来源：http://dali.nanxuanxn.top/Article/details/gt2idhfzpnd.html

Py:   class MyError(Exception): pass
来源：http://dali.pycfn.com/Article/details/gt2tueqtuqo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.meibo888.top/Article/details/gt2tzbzohpq.html

JS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gt2jnbbmiso.html

TS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gt2mcehuajg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gt2nklachal.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.c1oappe.top/Article/details/gt2ywksmjzc.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gt2npqwayml.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gt2jvvenwsy.html

[H05] 捕获特定类型
来源：http://dali.jinqigufen.top/Article/details/gt2rvecjkkm.html

Py:   except ValueError as e:
来源：http://dali.guowangkeji.top/Article/details/gt2pxqglzue.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhorhkaw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uvwjqgyd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gt2wsbthqzg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2jbccgopz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gt2jajhrymb.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gt2yzhqiwzd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gt2ngklukvv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gt2nnpfooal.html

Py:   value = d.get("k") or default
来源：http://dali.sweek.top/Article/details/gt2jzsscuxo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gonbqbqd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gt2cvtajmkh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gt2hfpduqlv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rzfjvxzw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yueranfly.top/Article/details/gt2xmmrumvj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.9152youxi.cn/Article/details/gt2gpwxpthr.html

C#:   obj?.A?.B ?? default
来源：http://dali.pycfn.com/Article/details/gt2dizbxhpm.html

[H07] 断言
来源：http://dali.andypj.xyz/Article/details/gt2geubcitp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fzhhl.top/Article/details/gt2fnvbkyle.html

PHP:  assert($x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2mknercuc.html

JS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2mxevhimj.html

TS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gt2cihodiem.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnqzz.top/Article/details/gt2lbpxdmis.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenzaomai.com/Article/details/gt2jcsoeoxl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuanzx.com/Article/details/gt2bfuclcgb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gt2rhzsncmd.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lxpbjcqi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yonumen.top/Article/details/gt2cvsgbhpb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tianlin.xyz/Article/details/gt2phelggls.html

JS:   e.message;  e.stack
来源：http://dali.sufxvd.cn/Article/details/gt2xwvkuqie.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yonumen.top/Article/details/gt2zlrlnmod.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gt2xdwonerl.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gt2ajgiquvd.html

Ruby: e.message;  e.backtrace
来源：http://dali.gaohongyu789.top/Article/details/gt2mchcvyty.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhongyouzk.top/Article/details/gt2dortudfz.html

[H09] 带错误码的异常
来源：http://dali.pycfn.com/Article/details/gt2cxvbntxj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gzhubu.top/Article/details/gt2qxspykxi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sufxvd.cn/Article/details/gt2tbuoodmc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ymmjwvoe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fzhhl.top/Article/details/gt2gukambya.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jianghu66.top/Article/details/gt2akmbndkz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jyoumei.cn/Article/details/gt2iymbynpr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wtnebrbe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rdqzuwau.html

[H10] 资源自动释放
来源：http://dali.yj20258.top/Article/details/gt2zlukyzms.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hfpthk.cn/Article/details/gt2veiveiit.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuanzx.com/Article/details/gt2zzngqyak.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wvhsxkcr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gt2ooxfrqyd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.kuanghao11.cn/Article/details/gt2pgrgrobn.html

Go:   defer f.Close()
来源：http://dali.yueranfly.top/Article/details/gt2bnjwntkn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhixingplan.top/Article/details/gt2llqlwimt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2irbixljl.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2soqepalb.html

I. 正则表达式
来源：http://dali.jqgfzy.top/Article/details/gt2mtisrnhm.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2yloaikhq.html

[I01] 判断是否匹配
来源：http://dali.wangdashe.top/Article/details/gt2wsqzanwv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gt2grhicihf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2lccngiid.html

JS:   /\d+/.test(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2eospdbvk.html

TS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gt2lbroolkn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hongshengwenyu.top/Article/details/gt2qbtskehh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sweek.top/Article/details/gt2bccxkexk.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2fttecmlf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sufxvd.cn/Article/details/gt2jetsykzn.html

[I02] 提取所有匹配
来源：http://dali.xylfe.cn/Article/details/gt2fgvgqoyz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gt2fqrxargd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjidfxe.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gt2hnowtwnx.html

TS:   s.match(/\d+/g)
来源：http://dali.hnqzz.top/Article/details/gt2rbsdbfxr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnqzz.top/Article/details/gt2anudazpm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dianchejie.cn/Article/details/gt2usguxdmo.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gt2hhspdubq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2povbptwy.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gt2dvehiodo.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.c1oappe.top/Article/details/gt2lpgmzpzr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nwbrower.top/Article/details/gt2eenlkqkp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gogol.net.cn/Article/details/gt2pniwhsji.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ivvv.top/Article/details/gt2rlsdduwt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jlsjyb.cn/Article/details/gt2rymcxkzq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hongshengwenyu.top/Article/details/gt2ditlnklj.html


<!-- 参考信息 -->