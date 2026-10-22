代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.shuidangran.top/Article/details/gtdlbbkslz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.birdmap.top/Article/details/gtfbexzudz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtvlskxeze.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.birdmap.top/Article/details/gttviyeyxh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtqnlkuhjj.html

TS:   path.extname("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtxxnvzlpc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sufxvd.cn/Article/details/gtclexqyol.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtfxwzhlrb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtifgpqotf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtgaxwmisy.html

[F11] 复制与移动文件
来源：http://dali.zhongyouzk.top/Article/details/gtwwriuozx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gttmflxppi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtcmmcoygc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtynpncdbx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtgyplrdwv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtffukrlkh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gttxmvseom.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtwjwvckww.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gtnutvxjtc.html

[F12] CSV 读写
来源：http://dali.nanxuanxn.top/Article/details/gthyprbwgn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigufen.top/Article/details/gtlhtkdfji.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.316326.xyz/Article/details/gtccfmxscb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfduwyjzk.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gtwtdbssmd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.c1oappe.top/Article/details/gtmfonopml.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gzhubu.top/Article/details/gtulgwffnj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ehwqpu.com/Article/details/gtzmnjalgv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jyoumei.cn/Article/details/gtflczogjr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtihokhbws.html

G. 面向对象
来源：http://dali.chenjidiqi.icu/Article/details/gtlvcjnxsm.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtotmxrgcx.html

[G01] 定义类
来源：http://dali.ydzc1.top/Article/details/gthdhuvngl.html

Py:   class User: pass
来源：http://dali.yj202588.top/Article/details/gtfihfvmuh.html

PHP:  class User {}
来源：http://dali.yueranfly.top/Article/details/gtbtlcortj.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtibipkuvh.html

TS:   class User { name: string = ""; }
来源：http://dali.hywenlv.cn/Article/details/gtnxendgfm.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gtmwaqdagj.html

Go:   type User struct { Name string }
来源：http://dali.zhiwuduotai.top/Article/details/gtrtiemcfx.html

Ruby: class User; end
来源：http://dali.yanxiufei.cn/Article/details/gtqstrjkqr.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtigibvjxh.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtgnarwxns.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcqorpbd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gtuopvuvyl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwvylaloa.html

TS:   constructor(public name: string) {}
来源：http://dali.meibo888.top/Article/details/gtlmigfsan.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gtmrqgjkvg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.quarkkingdee.top/Article/details/gtrwhbjten.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yanxiufei.cn/Article/details/gtgndiufnu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jianghu66.top/Article/details/gtqentdybu.html

[G03] 实例属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvhkglrq.html

Py:   self.name = "x"
来源：http://dali.shuidangran.top/Article/details/gtglledezg.html

PHP:  public string $name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtpkpmfxgh.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtmsuouszy.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gtmjvitlfu.html

Java: private String name;
来源：http://dali.jianghu66.top/Article/details/gttgxzosgs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sysykeji.top/Article/details/gtmgdsbjdh.html

Ruby: @name = "x"
来源：http://dali.gogol.net.cn/Article/details/gtqdjtfdbs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.316326.xyz/Article/details/gtskvahpff.html

[G04] 定义方法
来源：http://dali.zhengqikj.top/Article/details/gtplssfsjv.html

Py:   def greet(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gtvuhxjjdo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gthapjabzo.html

JS:   greet() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtwduywbup.html

TS:   greet(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gthfsilmiw.html

Java: String greet() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplokwvel.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtavevljnw.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtcjaretnu.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gtdrxuzgte.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gtimypaubp.html

Py:   class Admin(User): pass
来源：http://dali.mhx1999.top/Article/details/gteeadeutm.html

PHP:  class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtydohlrgf.html

JS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtgfjemggb.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtcvahjspw.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtravtvgcf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gtlcghwrgj.html

Ruby: class Admin < User; end
来源：http://dali.smart0.xyz/Article/details/gtytafuhvl.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gtjmpwrtvu.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gtzeeykbnk.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvsxvyoo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtdwazctoz.html

JS:   greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtxkelfzuo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gttuhhmzie.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtowdtjhdm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.haohaochexian.top/Article/details/gtywuevymv.html

Ruby: def greet; "admin"; end
来源：http://dali.bjfxy.top/Article/details/gtxgbhwqwq.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangdashe.top/Article/details/gtdqhdvlkr.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gtxeqqqior.html

Py:   super().greet()
来源：http://dali.zhoulong.xyz/Article/details/gttweoqwjd.html

PHP:  parent::greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbixjzuy.html

JS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtnamryxxv.html

TS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtaxgujchh.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gtmtglauxh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fengsongda.top/Article/details/gthzpmyjzr.html

Ruby: super
来源：http://dali.wangshuangyany.cn/Article/details/gtddgqaedd.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gtishljgos.html

[G08] 静态方法与属性
来源：http://dali.ehwqpu.com/Article/details/gtoqwdmdeu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gtjgewrkib.html

PHP:  public static function f() {}
来源：http://dali.mhx1999.top/Article/details/gtlscwsqci.html

JS:   static f() {}
来源：http://dali.zhengqikj.top/Article/details/gtrmjnjuxi.html

TS:   static f(): void {}
来源：http://dali.yongpay.top/Article/details/gtzrnznwrz.html

Java: static void f() {}
来源：http://dali.cqqwz.cn/Article/details/gtqogolcye.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.c1oappe.top/Article/details/gtsndpkreo.html

Ruby: def self.f; end
来源：http://dali.chenjidiqi.icu/Article/details/gtryptljwg.html

C#:   public static void F() {}
来源：http://dali.daxiang520.top/Article/details/gtahfchysx.html

[G09] 接口 / 抽象类
来源：http://dali.havefunace.top/Article/details/gtniriapze.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.meibo888.top/Article/details/gtbpgvjdig.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258888.top/Article/details/gtzdoaysuv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.havefunace.top/Article/details/gtyjvngkep.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gtmetqrrgx.html

Java: interface Shape { double area(); }
来源：http://dali.xinyue.icu/Article/details/gtjfleqcaz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shzxlz.cn/Article/details/gtthqovhdz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangdashe.top/Article/details/gtvitvdvok.html

C#:   interface IShape { double Area(); }
来源：http://dali.cdnleiting.top/Article/details/gtnwhttywg.html

[G10] 访问控制
来源：http://dali.sufxvd.cn/Article/details/gtpvpodvsp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhongyouzk.top/Article/details/gtoomkjhlf.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwayitcy.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gtvlufhgvh.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtjbmtuvfi.html

Java: public / protected / private / 默认包级
来源：http://dali.cashguo.top/Article/details/gtsmzppvgj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gtvnjoodeu.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtknuagwsy.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gtyzdwftap.html

[G11] getter / setter
来源：http://dali.zhengqikj.top/Article/details/gtagmenizk.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwszalkq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtfhtbowrw.html

JS:   get name() { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtkyesdyco.html

TS:   get name(): string { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnlepxelp.html

Java: public String getName() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbaufgupp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtqbzskqjq.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaommrvxl.html

C#:   public string Name { get; set; }
来源：http://dali.yj202588.top/Article/details/gtkuhiaiih.html

[G12] 对象转字符串
来源：http://dali.pycfn.com/Article/details/gtswqranqx.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtqtybyykp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtlayodzib.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gthdyeqymi.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gthvisargr.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtfdldxdss.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjesrkfhx.html

Ruby: def to_s; @name; end
来源：http://dali.ehwqpu.com/Article/details/gtgalbubbm.html

C#:   public override string ToString() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtdyprbmbo.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gthcluxepq.html

Py:   isinstance(u, User)
来源：http://dali.c1oappe.top/Article/details/gtgfsruzmk.html

PHP:  $u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gtyshjaxlg.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtkvwmozvc.html

TS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtfqnuanep.html

Java: u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtvgruxwpd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xinyue.icu/Article/details/gtzmrzkqgr.html

Ruby: u.is_a?(User)
来源：http://dali.zycfv.cn/Article/details/gtxtfehcvj.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gthkkpemxa.html

[G14] 数据类 / record
来源：http://dali.jinqigufen.top/Article/details/gtahzyliwo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangshuangyany.cn/Article/details/gtjydhffen.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ehwqpu.com/Article/details/gttwdnbizm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.9152youxi.cn/Article/details/gtygpmcjwq.html

TS:   type User = { name: string; age: number };
来源：http://dali.tian-w.cn/Article/details/gtbhtujqaj.html

Java: record User(String name, int age) {}
来源：http://dali.aibaodan.cn/Article/details/gtdczjshzh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gthwwtzzir.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cdnleiting.top/Article/details/gtobrzjgvc.html

C#:   record User(string Name, int Age);
来源：http://dali.zycfv.cn/Article/details/gtakxsievo.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gthhmhfszu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xziqi.cn/Article/details/gtctbfcqzk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuanzx.com/Article/details/gtkqnjwldk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.svipenyu.cn/Article/details/gtgzapiiuu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gtocccgizz.html

Java: enum Color { RED, GREEN }
来源：http://dali.gzhubu.top/Article/details/gtbyybgfkz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gtcjgzirkw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.haohaochexian.top/Article/details/gtabectqwl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtivfnxrqn.html

[G16] 对象转数组 / 字典
来源：http://dali.zdqjudy.top/Article/details/gtsxieyaei.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gtkcvyebjg.html

PHP:  get_object_vars($obj);
来源：http://dali.cdnleiting.top/Article/details/gtnnlwrxln.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjwrwbcf.html

TS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtelcafqih.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dianchejie.cn/Article/details/gtlitwfsxy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hywenlv.cn/Article/details/gtubyoxkfl.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gtavdpzipt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmgwqtaw.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtfhlyushf.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gtqydjwmtf.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkttvujgk.html

[H01] try / catch 基础
来源：http://dali.daxiang520.top/Article/details/gttevaannb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gtcevqrltc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gtkfutvlvw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtpbokxnyw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtygjkzxva.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.haohaochexian.top/Article/details/gtuwznnaef.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yanxiufei.cn/Article/details/gtjmahxpdx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gtgebsasdv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gtvjnkfmrc.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gtkzvjityu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jiagoushi.top/Article/details/gtxzvoxsma.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtobtlohvi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtwpheaati.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtrsaqormc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gthycjyluy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gtvcrhqazv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gotoacloud.top/Article/details/gtiqyajiai.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtdjskkmaa.html

[H03] 主动抛出异常
来源：http://dali.316326.xyz/Article/details/gtctcortke.html

Py:   raise ValueError("错误信息")
来源：http://dali.shzxlz.cn/Article/details/gtuiqdhpxv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtpoxrexxw.html

JS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtifustlat.html

TS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gtefnaygbe.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtpgjycuyt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258.top/Article/details/gtkpfkbngr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhixingplan.top/Article/details/gtvcltjqfg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtbfosrkjr.html

[H04] 自定义异常类型
来源：http://dali.ppjwa.cn/Article/details/gtvxrmsgrr.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gtysrbgkpw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtexmsxocf.html

JS:   class MyError extends Error {}
来源：http://dali.sweek.top/Article/details/gtrzmiolaq.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvckpyap.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gtlvbnilrx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.snrcjt.cn/Article/details/gtdpoobvxo.html

Ruby: class MyError < StandardError; end
来源：http://dali.xuetiantiany.cn/Article/details/gtxzzpqkex.html

C#:   class MyException : Exception {}
来源：http://dali.aibaodan.cn/Article/details/gtznmcwdtl.html

[H05] 捕获特定类型
来源：http://dali.chenzaomai.com/Article/details/gtloheykqr.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gtnffmwgke.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gtntwlehsj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gtqgrmtbdu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gtdscsfqmw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpxrmteap.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj202588.top/Article/details/gtlwspampe.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbejxbev.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aibaodan.cn/Article/details/gteukzckvq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dianchejie.cn/Article/details/gtzgdyvizi.html

Py:   value = d.get("k") or default
来源：http://dali.hnxiangtu.top/Article/details/gtfchdzwaz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gttqmpxray.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtwugqlrfd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtiawodbso.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gtcognmwej.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gtwfxakivb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dianchejie.cn/Article/details/gtwvcsrnrs.html

C#:   obj?.A?.B ?? default
来源：http://dali.gogol.net.cn/Article/details/gtklqvyapk.html

[H07] 断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtmaropvcj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.9152youxi.cn/Article/details/gtliumpvfu.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtmhgylous.html

JS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtqurfmqot.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtsvcudvmo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhongyouzk.top/Article/details/gtnmhgdepu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guannengcc.top/Article/details/gtstdcyzrn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.mhx1999.top/Article/details/gttsejomof.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtngwngkfc.html

[H08] 获取错误信息与堆栈
来源：http://dali.aizwys.cn/Article/details/gtzeeoaewb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhoulong.xyz/Article/details/gtfwkioibs.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aizwys.cn/Article/details/gtizhnmala.html

JS:   e.message;  e.stack
来源：http://dali.hywenlv.cn/Article/details/gtzkzkwxco.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxinkj.top/Article/details/gtwevbzanc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ybcxt.top/Article/details/gtauvagcoo.html

Go:   err.Error()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbzojptk.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhengqikj.top/Article/details/gtozoepgmc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jyoumei.cn/Article/details/gtsuszysxy.html

[H09] 带错误码的异常
来源：http://dali.ydzc1.top/Article/details/gtmabcgdtq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.9152youxi.cn/Article/details/gtwlkmtrcr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gtxqmgkalz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sysykeji.top/Article/details/gtfwwqsgql.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigfzy.top/Article/details/gthlhrkgpw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xziqi.cn/Article/details/gttevmozyt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ydzc1.top/Article/details/gtfdmgvoql.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gaohongyu789.top/Article/details/gtvlcrlshe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gtyweyooln.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gtfmetxxbw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gtnipzslfm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnxiangtu.top/Article/details/gtcldwohbx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtcqyknvce.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gtczfujtom.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aibaodan.cn/Article/details/gtgdhvvabm.html

Go:   defer f.Close()
来源：http://dali.jyoumei.cn/Article/details/gtbqwpdhay.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fengsongda.top/Article/details/gtkytechgo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtjxpynzpx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtzhdrotjk.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gtqhcovqpj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtxjtbqhcm.html

[I01] 判断是否匹配
来源：http://dali.sysykeji.top/Article/details/gtautpugfj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqwwotuj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jianghu66.top/Article/details/gthswoxyvy.html

JS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gtqoggrnez.html

TS:   /\d+/.test(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtysgifigs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuanzhike.top/Article/details/gtwlcorbdh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnqzz.top/Article/details/gtcxrrxpqq.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpuuirpu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.haohaochexian.top/Article/details/gtfhtiwraa.html

[I02] 提取所有匹配
来源：http://dali.zdqjudy.top/Article/details/gtivbiqfyd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gtjmnmrvbc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangdashe.top/Article/details/gtjylzvfzg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yangfankeji.com/Article/details/gtqzindkmt.html

TS:   s.match(/\d+/g)
来源：http://dali.yuanzhike.top/Article/details/gtitjmtrnb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtnpgrbjel.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gtioisbcdl.html

Ruby: s.scan(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gtcjhzqirb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtykezejfi.html

[I03] 提取捕获分组
来源：http://dali.birdmap.top/Article/details/gtblatlbac.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtfxtpjver.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pycfn.com/Article/details/gtfrnfwutn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nanxinkj.top/Article/details/gtflnohfcn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258.top/Article/details/gtjfjjfaab.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.0kj1m.cn/Article/details/gtnzvdsqmu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangdashe.top/Article/details/gtpdakhqap.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cheryme.top/Article/details/gtfetzsjnv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangdashe.top/Article/details/gtgolgwzox.html

[I04] 正则替换
来源：http://dali.vqdsnc.cn/Article/details/gthcumzofg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhukrwrb.html


<!-- 参考信息 -->