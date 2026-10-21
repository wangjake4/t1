代发 wailian999

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gtbgdmvtqv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ivvv.top/Article/details/gtfllsjesz.html

PHP:  filesize("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtjzdmojaa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtdissvgya.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gthkzxhkih.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtfkyerkjr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gogol.net.cn/Article/details/gtaivpxexf.html

Ruby: File.size("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtcnwollwh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.redwolf501.top/Article/details/gtorsbwiiq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ehwqpu.com/Article/details/gtigtewkhx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtawphfynf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xziqi.cn/Article/details/gtrazihona.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtlkzzpxsb.html

TS:   path.extname("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtixfwwzrd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gtigzzysyj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtlvtxoott.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gthztnkrtg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdammaema.html

[F11] 复制与移动文件
来源：http://dali.9152youxi.cn/Article/details/gtfcfrztbw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtfrhdjnsy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yongpay.top/Article/details/gtllimejnw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtksmkmwaw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtimeznuld.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtkvpgpnst.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.vqdsnc.cn/Article/details/gtvqxqgxje.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtipvkmpbk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tian-w.cn/Article/details/gtpbfmuomm.html

[F12] CSV 读写
来源：http://dali.redwolf501.top/Article/details/gtulinvujx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhixingplan.top/Article/details/gtpjfrvtbj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xylfe.cn/Article/details/gtheiawmmh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhoulong.xyz/Article/details/gtpwfbirkn.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtiiwjpprx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jlsjyb.cn/Article/details/gtidwgurcs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sxryk.cn/Article/details/gtebnmelue.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gtdvxmeypj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sxryk.cn/Article/details/gtcdqkkdmo.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtwgtdiued.html

G. 面向对象
来源：http://dali.cucudq.cn/Article/details/gtalixrwqd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtfilqpljz.html

[G01] 定义类
来源：http://dali.xylfe.cn/Article/details/gtnrxfkgls.html

Py:   class User: pass
来源：http://dali.yanxiufei.cn/Article/details/gthdiltfbj.html

PHP:  class User {}
来源：http://dali.yj202588.top/Article/details/gtnkfizfje.html

JS:   class User {}
来源：http://dali.cheryme.top/Article/details/gtsftjlyst.html

TS:   class User { name: string = ""; }
来源：http://dali.316326.xyz/Article/details/gtxeggsyrb.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gtgylpqrle.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gtopeauoex.html

Ruby: class User; end
来源：http://dali.birdmap.top/Article/details/gtkdekkktp.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtauprxjlc.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gtrylvhsxz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pycfn.com/Article/details/gtbsmzddsk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tianlin.xyz/Article/details/gtaagjvntw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtirmotdvv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhengqikj.top/Article/details/gtkgfikmvh.html

Java: User(String name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtqlrtmpzt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangdashe.top/Article/details/gtiglpsaiq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuakxztvf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guannengcc.top/Article/details/gtjswfmurj.html

[G03] 实例属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqikjjidd.html

Py:   self.name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtheqevuax.html

PHP:  public string $name = "x";
来源：http://dali.havefunace.top/Article/details/gtstwqxnmb.html

JS:   this.name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtgbqvjszl.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gtairepjtk.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gthudykolk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygfpqquo.html

Ruby: @name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtgjgrhgjy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljlhzrpn.html

[G04] 定义方法
来源：http://dali.cqqwz.cn/Article/details/gtlrlaelpr.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtkmztxjyx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydpzumpz.html

JS:   greet() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtqhovrwon.html

TS:   greet(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtsumcsgcq.html

Java: String greet() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtetetzppj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtwsjtjatb.html

Ruby: def greet; @name; end
来源：http://dali.fzhhl.top/Article/details/gtfnnmrmwx.html

C#:   public string Greet() => Name;
来源：http://dali.yangfankeji.com/Article/details/gtycsxzznd.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gtchysedae.html

Py:   class Admin(User): pass
来源：http://dali.yvedp.cn/Article/details/gtnggzezwb.html

PHP:  class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtkhrlucmj.html

JS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtkefqgxof.html

TS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtpbbxjvqy.html

Java: class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtrxsgguhs.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cqqwz.cn/Article/details/gtvibaaulw.html

Ruby: class Admin < User; end
来源：http://dali.cdnleiting.top/Article/details/gtxsvlovub.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gtcyfgzxxl.html

[G06] 重写方法
来源：http://dali.hywenlv.cn/Article/details/gtupccense.html

Py:   def greet(self): return "admin"
来源：http://dali.pengpengdd.cyou/Article/details/gtfvkjstho.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtbcqwdvhz.html

JS:   greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtydysagkd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtntvxjias.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvoovdkh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhengqikj.top/Article/details/gtilgsmouz.html

Ruby: def greet; "admin"; end
来源：http://dali.zhengqikj.top/Article/details/gtadqwetgp.html

C#:   public override string Greet() => "admin";
来源：http://dali.andypj.xyz/Article/details/gtafpnjkup.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gthdbdqods.html

Py:   super().greet()
来源：http://dali.nanxuanxn.top/Article/details/gtpcllhecc.html

PHP:  parent::greet();
来源：http://dali.smart0.xyz/Article/details/gtrrxmkkad.html

JS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gtluunxaxo.html

TS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtpglihqgw.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gtlyhopjhq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gtpyjphjzj.html

Ruby: super
来源：http://dali.fengsongda.top/Article/details/gteiwcjncj.html

C#:   base.Greet();
来源：http://dali.daxiang520.top/Article/details/gttfberbcn.html

[G08] 静态方法与属性
来源：http://dali.yj20258.top/Article/details/gtprsxyobk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dashuyun.cn/Article/details/gtdshexsmc.html

PHP:  public static function f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtudsrprcb.html

JS:   static f() {}
来源：http://dali.xuanzx.com/Article/details/gtbalpzgox.html

TS:   static f(): void {}
来源：http://dali.tanke756.top/Article/details/gtyddmceyk.html

Java: static void f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfpebxaq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gtikkkfaix.html

Ruby: def self.f; end
来源：http://dali.jinqigfzy.top/Article/details/gtmtnqoaui.html

C#:   public static void F() {}
来源：http://dali.chenzaomai.com/Article/details/gtzwjychmm.html

[G09] 接口 / 抽象类
来源：http://dali.gaohongyu789.top/Article/details/gtcshkpelm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.meibo888.top/Article/details/gtytotytze.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.316326.xyz/Article/details/gtigkvgjau.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gttocoaemg.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258.top/Article/details/gtjafdysih.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gtufafeuek.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gtzsdhzgdw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258888.top/Article/details/gtukhwyodg.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gtkkksrejq.html

[G10] 访问控制
来源：http://dali.quarkkingdee.top/Article/details/gtwhgoljvi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gtdflslarq.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtspehffsq.html

JS:   #private 字段；其余公开
来源：http://dali.zhongyouzk.top/Article/details/gtuiwukash.html

TS:   public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtugsmhwxo.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gtffbyctua.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gtzerzzzkp.html

Ruby: public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtkrysmduo.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gtrdghjqok.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gtokwlgupj.html

Py:   @property 与 @x.setter
来源：http://dali.yueranfly.top/Article/details/gtvftthnwu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtahkyiemm.html

JS:   get name() { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtppbojhde.html

TS:   get name(): string { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtslbtqvqi.html

Java: public String getName() { return name; }
来源：http://dali.yonumen.top/Article/details/gttqevkxac.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtiiejvqiu.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gttcqzpgop.html

C#:   public string Name { get; set; }
来源：http://dali.sweek.top/Article/details/gtvfvlkvin.html

[G12] 对象转字符串
来源：http://dali.zycfv.cn/Article/details/gtjefqzxtr.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gteihsgpwm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtkofigiwc.html

JS:   toString() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gthullvmki.html

TS:   toString(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtamurtxhl.html

Java: @Override public String toString() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtyipmeqqj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtutsdarlp.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtfqkyeydo.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gtcpridufk.html

[G13] 判断对象类型
来源：http://dali.ivvv.top/Article/details/gtmfgcqkay.html

Py:   isinstance(u, User)
来源：http://dali.c1oappe.top/Article/details/gthhzppich.html

PHP:  $u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtnhnemdrm.html

JS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtqmtxmjez.html

TS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtgzpjwaxx.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtxqtxdedy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadebirgy.html

Ruby: u.is_a?(User)
来源：http://dali.quarkkingdee.top/Article/details/gtqsuldkxi.html

C#:   u is User
来源：http://dali.yuanzhike.top/Article/details/gttvppsnmm.html

[G14] 数据类 / record
来源：http://dali.birdmap.top/Article/details/gtmqaalwni.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aizwys.cn/Article/details/gtyyvhhdrj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gtdzeoqjug.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shzxlz.cn/Article/details/gthzbjikua.html

TS:   type User = { name: string; age: number };
来源：http://dali.ydzc1.top/Article/details/gtzwwjcypj.html

Java: record User(String name, int age) {}
来源：http://dali.bjfxy.top/Article/details/gtulsftdut.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouderwid.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhongyouzk.top/Article/details/gtkgattesf.html

C#:   record User(string Name, int Age);
来源：http://dali.haohaochexian.top/Article/details/gtrsabunkm.html

[G15] 枚举
来源：http://dali.birdmap.top/Article/details/gtldkysgqy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj202588.top/Article/details/gtzjgwcfwl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.snrcjt.cn/Article/details/gtlmviixhi.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangdashe.top/Article/details/gtrudpyfwa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtqfdeklcp.html

Java: enum Color { RED, GREEN }
来源：http://dali.tanke756.top/Article/details/gttcrkvhzn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.feifeiyinyue.top/Article/details/gttqzeeuro.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gtshbscaxy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtqvyfhkkn.html

[G16] 对象转数组 / 字典
来源：http://dali.yuanzhike.top/Article/details/gtfbmpfnha.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gtsysjaoac.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gtswojgjrd.html

JS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gtwziwktjx.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gttbtxhuit.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yueranfly.top/Article/details/gtikwcvgob.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.316326.xyz/Article/details/gtttbehsux.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbemumuwx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtgqmxehdr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlojquzbf.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtcfsoad.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtrhbgbojf.html

[H01] try / catch 基础
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrlaagiq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gtddsggrig.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuanzx.com/Article/details/gtaisznevk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtkpzbsxew.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtzesatxeu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gtliupbcwq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pycfn.com/Article/details/gtymtynkqd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.kuanghao11.cn/Article/details/gtglilurze.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gtahkxgcmd.html

[H02] finally / ensure 收尾
来源：http://dali.hywenlv.cn/Article/details/gtejioltrx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gtiaxznibr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtquelwzul.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtvapzcfnl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtkiwpjhxh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtjumlukcw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gtddyzexju.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fzhhl.top/Article/details/gtjyrdcmda.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtywvhujtu.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtnlengjyd.html

Py:   raise ValueError("错误信息")
来源：http://dali.gaohongyu789.top/Article/details/gtdupykxsi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtzqxqcylo.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gthsucurue.html

TS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrpxtqne.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvyikosf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gtgvkhprds.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ivvv.top/Article/details/gtkscndfic.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gttcvnfeav.html

[H04] 自定义异常类型
来源：http://dali.shzxlz.cn/Article/details/gteucrgwuo.html

Py:   class MyError(Exception): pass
来源：http://dali.ehwqpu.com/Article/details/gtautqitct.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsrmjzxo.html

JS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gtulhbzcjh.html

TS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtciaknxhb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtczorzmvz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hfpthk.cn/Article/details/gtheuarool.html

Ruby: class MyError < StandardError; end
来源：http://dali.dianchejie.cn/Article/details/gturkebixo.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258888.top/Article/details/gtvzzndpnb.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gtykttbfve.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gtbnoksdch.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqobylpr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtcvrzvfld.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gttsypfwob.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtqfhxojuc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuxming.cn/Article/details/gtsiischma.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenlongwang.top/Article/details/gthtlbghsf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnanoygcc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgfzy.top/Article/details/gtkfjhvswa.html

Py:   value = d.get("k") or default
来源：http://dali.gzhubu.top/Article/details/gtqmqjrjix.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gtejuqppyk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gturxacxtb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gtqixnppfg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aizwys.cn/Article/details/gtlsisnobh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xylfe.cn/Article/details/gtpmbmipty.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gtorkqvqme.html

C#:   obj?.A?.B ?? default
来源：http://dali.pycfn.com/Article/details/gtrbldswav.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhtnqfwu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sxryk.cn/Article/details/gtcunkanut.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gtcriwmrgm.html

JS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtcprnyzfr.html

TS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtomdprzzd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrpehcir.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cqqwz.cn/Article/details/gtoxqiwmnz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aizwys.cn/Article/details/gtwovhwmdi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gthqzuckyf.html

[H08] 获取错误信息与堆栈
来源：http://dali.pycfn.com/Article/details/gtslzxgghq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shzxlz.cn/Article/details/gtxlwsjxzb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgufenzy.top/Article/details/gtbagoorjf.html

JS:   e.message;  e.stack
来源：http://dali.mhx1999.top/Article/details/gttfcmwpxf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgfzy.top/Article/details/gtflbjszhy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guowangkeji.top/Article/details/gtwwiilokr.html

Go:   err.Error()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwijmffzs.html

Ruby: e.message;  e.backtrace
来源：http://dali.yongpay.top/Article/details/gtncggbppp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangdashe.top/Article/details/gtbzfvnunh.html

[H09] 带错误码的异常
来源：http://dali.shuidangran.top/Article/details/gtgjcdnkxh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgufenzy.top/Article/details/gtiisxzqxw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkhidqlo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqptyfwg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nwbrower.top/Article/details/gtnugfdsua.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgfzy.top/Article/details/gtsombtvqk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtakopeuhb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gaohongyu789.top/Article/details/gtivwcbeff.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gtmrfxplsa.html

[H10] 资源自动释放
来源：http://dali.zhijiandao.cn/Article/details/gtnokffzkz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jiagoushi.top/Article/details/gtyiopggqu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guannengcc.top/Article/details/gtdfazicba.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtcknwxybg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gtppvlhpol.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxinkj.top/Article/details/gtfaocumqp.html

Go:   defer f.Close()
来源：http://dali.zycfv.cn/Article/details/gtrkwyazlh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnxiangtu.top/Article/details/gttetjnxbo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtxfikkxzu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtloqsafvz.html

I. 正则表达式
来源：http://dali.yangfankeji.com/Article/details/gtyimulxms.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtcudpgbki.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gtpgcwvrey.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtcjebhmmo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258.top/Article/details/gttoohovda.html

JS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gtniappwav.html

TS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gtvddvaypa.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.andypj.xyz/Article/details/gtjppjtxkr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sufxvd.cn/Article/details/gtsrstzcam.html

Ruby: s.match?(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gtkqljmmur.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivbjpwng.html

[I02] 提取所有匹配
来源：http://dali.shzxlz.cn/Article/details/gtivddsrup.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtutybrtsc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.birdmap.top/Article/details/gtucxhpkvj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yonumen.top/Article/details/gttxvzxvsc.html

TS:   s.match(/\d+/g)
来源：http://dali.gotoacloud.top/Article/details/gthwqsvdhl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yvedp.cn/Article/details/gtrejdqzkx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gtfhepmapq.html

Ruby: s.scan(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtvmmeuktv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guannengcc.top/Article/details/gtvdnqgbji.html

[I03] 提取捕获分组
来源：http://dali.redwolf501.top/Article/details/gtkxznltlk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.c1oappe.top/Article/details/gtliblfulz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtwznfhahl.html


<!-- 参考信息 -->