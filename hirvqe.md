代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgosqxtlc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtdizufwwz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhengqikj.top/Article/details/gtfwkioqaq.html

Ruby: File.size("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtxwacbqst.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangshuangyany.cn/Article/details/gtgmovjgsa.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.mhx1999.top/Article/details/gtsaixuwus.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtmankhazu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuxming.cn/Article/details/gtvniocngn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtfhgtwcsz.html

TS:   path.extname("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtdbgfhbmt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jiagoushi.top/Article/details/gtlbpdbcdu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtmamvmits.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gttsdaurty.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gttdievwgk.html

[F11] 复制与移动文件
来源：http://dali.hongshengwenyu.top/Article/details/gtbecclhya.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtkqrzrlyb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtikczbjac.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtktxjgshi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtzuykgbza.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtqeiruvon.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zycfv.cn/Article/details/gtykqniotl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtybdecfgd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gtxgnuagxg.html

[F12] CSV 读写
来源：http://dali.guowangkeji.top/Article/details/gtpjfqwdsv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aibaodan.cn/Article/details/gtbnzkgphh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gtiyvaxvux.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuanzx.com/Article/details/gtmgrpmdtx.html

TS:   // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtcojlbbpe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gtvexypwja.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dashuyun.cn/Article/details/gtuoaxhese.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gtoazqobbn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gtplsgoxhw.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtdqeukvlh.html

G. 面向对象
来源：http://dali.mhx1999.top/Article/details/gtiwgwsnjf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtqmgmbxgk.html

[G01] 定义类
来源：http://dali.nanxinkj.top/Article/details/gtsumamfrc.html

Py:   class User: pass
来源：http://dali.meibo888.top/Article/details/gtksexkflc.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gtydrsvcme.html

JS:   class User {}
来源：http://dali.sweek.top/Article/details/gtfatvylfc.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuxxmrsqa.html

Java: class User {}
来源：http://dali.daria6918.cn/Article/details/gtworsmquz.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gtaagdwiqp.html

Ruby: class User; end
来源：http://dali.aibaodan.cn/Article/details/gteznizwor.html

C#:   class User {}
来源：http://dali.ivvv.top/Article/details/gtqotrvnjr.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gtkkprwbpu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgufenzy.top/Article/details/gtuskhvfbe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.daxiang520.top/Article/details/gtmehdvjjw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gttjufhyvr.html

TS:   constructor(public name: string) {}
来源：http://dali.iojbl.cn/Article/details/gtbnuzvhtq.html

Java: User(String name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtwyelyjix.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.haohaochexian.top/Article/details/gtetixsuwn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yvedp.cn/Article/details/gtotlnyvoh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtgnippxrf.html

[G03] 实例属性
来源：http://dali.9152youxi.cn/Article/details/gtixkzdqhn.html

Py:   self.name = "x"
来源：http://dali.yj202588.top/Article/details/gtbdquzcah.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtamqnzpdg.html

JS:   this.name = "x";
来源：http://dali.shuidangran.top/Article/details/gtbmazliiv.html

TS:   name: string = "x";
来源：http://dali.316326.xyz/Article/details/gtkvisfuer.html

Java: private String name;
来源：http://dali.quarkkingdee.top/Article/details/gtpeagntbu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sysykeji.top/Article/details/gtpotrzsyl.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtohcwodug.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtduyaxitj.html

[G04] 定义方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojqftwyr.html

Py:   def greet(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtycqmsmyx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtvqajuvct.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtsekeoyur.html

TS:   greet(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtjaqgcehl.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtaswcrsep.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtqgwwqauq.html

Ruby: def greet; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmovsmau.html

C#:   public string Greet() => Name;
来源：http://dali.tian-w.cn/Article/details/gttmlyqvyk.html

[G05] 继承
来源：http://dali.hnxiangtu.top/Article/details/gtyqbssxnl.html

Py:   class Admin(User): pass
来源：http://dali.yangfankeji.com/Article/details/gtnnlixxoj.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtzdpylsub.html

JS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtecorgebb.html

TS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtxoanijgy.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtssxutrjb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuxming.cn/Article/details/gtuzmwdeoo.html

Ruby: class Admin < User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmubgqus.html

C#:   class Admin : User {}
来源：http://dali.gotoacloud.top/Article/details/gtvkpyvahk.html

[G06] 重写方法
来源：http://dali.sufxvd.cn/Article/details/gtgmmpguxa.html

Py:   def greet(self): return "admin"
来源：http://dali.gzhubu.top/Article/details/gtjqpntwob.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsjjdwkx.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtalwpwzwh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtwdkelezg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtxvhuizea.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yueranfly.top/Article/details/gtqakzemti.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gtyxaymxnr.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gtdhrdbsfq.html

[G07] 调用父类方法
来源：http://dali.hfpthk.cn/Article/details/gtscymzhkg.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gtxuuufbza.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gtxznfocmr.html

JS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtqxcohpkq.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtxapqkjge.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gtjbcdamsz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxinkj.top/Article/details/gteaxmvcie.html

Ruby: super
来源：http://dali.yongpay.top/Article/details/gtnadsuwno.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gtxffuxkpg.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gtgleccqtm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hammf.cn/Article/details/gtsgfovwiq.html

PHP:  public static function f() {}
来源：http://dali.gzhubu.top/Article/details/gtexpasyax.html

JS:   static f() {}
来源：http://dali.meibo888.top/Article/details/gtvyzvhmqv.html

TS:   static f(): void {}
来源：http://dali.meibo888.top/Article/details/gtfqktmuzv.html

Java: static void f() {}
来源：http://dali.wangdashe.top/Article/details/gtevhlmvyp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrylwcwih.html

Ruby: def self.f; end
来源：http://dali.zhixingplan.top/Article/details/gtmkqvhouc.html

C#:   public static void F() {}
来源：http://dali.tianlin.xyz/Article/details/gtcxrvsiii.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gttaqlbrtz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.mhx1999.top/Article/details/gtfxafiaaw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwgwfgeh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yongpay.top/Article/details/gtrnlcqqqw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhongyouzk.top/Article/details/gttsyxaoas.html

Java: interface Shape { double area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtjrfksxwa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.9152youxi.cn/Article/details/gtelzglxou.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.0kj1m.cn/Article/details/gttvqalmfb.html

C#:   interface IShape { double Area(); }
来源：http://dali.fzhhl.top/Article/details/gtcovcghka.html

[G10] 访问控制
来源：http://dali.andypj.xyz/Article/details/gthwcuetdg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jlsjyb.cn/Article/details/gtqxecuqyp.html

PHP:  public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtscvwlpgw.html

JS:   #private 字段；其余公开
来源：http://dali.sufxvd.cn/Article/details/gtexydvpah.html

TS:   public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtvwaadahp.html

Java: public / protected / private / 默认包级
来源：http://dali.redwolf501.top/Article/details/gtmexkoiua.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sysykeji.top/Article/details/gtrrchtmfa.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtrueaitze.html

C#:   public / protected / private / internal
来源：http://dali.tanke756.top/Article/details/gtdseiknoq.html

[G11] getter / setter
来源：http://dali.xuanzx.com/Article/details/gtxcxbisms.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gtdamhgnxz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtmibfulcj.html

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtzzjektrn.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtnjhtmwxs.html

Java: public String getName() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtzvtsuksa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtyudfselz.html

Ruby: attr_accessor :name
来源：http://dali.shuidangran.top/Article/details/gtnirlrehi.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigfzy.top/Article/details/gtpsduioxw.html

[G12] 对象转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtrfhxzlrm.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtzkgfojno.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtjttvfcyl.html

JS:   toString() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtllmwyqra.html

TS:   toString(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtbaldmdgx.html

Java: @Override public String toString() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtgfbtxkag.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtugqdhfba.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtkhxzeqha.html

C#:   public override string ToString() => Name;
来源：http://dali.xziqi.cn/Article/details/gtdftydegz.html

[G13] 判断对象类型
来源：http://dali.guowangkeji.top/Article/details/gtebftjyhf.html

Py:   isinstance(u, User)
来源：http://dali.wangdashe.top/Article/details/gtaobflnrw.html

PHP:  $u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtjdjwbnos.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtxkayvfac.html

TS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtugjyxhjv.html

Java: u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtbkipfwsr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cdnleiting.top/Article/details/gtltozzyyg.html

Ruby: u.is_a?(User)
来源：http://dali.shuidangran.top/Article/details/gtcbyaewxj.html

C#:   u is User
来源：http://dali.hammf.cn/Article/details/gteqoxrlmt.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gtfweqvrci.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jiagoushi.top/Article/details/gtxmnhmfqj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.vqdsnc.cn/Article/details/gtkkwcacdd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fengsongda.top/Article/details/gtxzoiyxbg.html

TS:   type User = { name: string; age: number };
来源：http://dali.316326.xyz/Article/details/gtugesophx.html

Java: record User(String name, int age) {}
来源：http://dali.birdmap.top/Article/details/gtwfhewwtu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpnsswxk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xylfe.cn/Article/details/gtidswpceh.html

C#:   record User(string Name, int Age);
来源：http://dali.sxryk.cn/Article/details/gtwqotgenn.html

[G15] 枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzcxsytk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gtzglezmnh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tanke756.top/Article/details/gthwuaglqj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.quarkkingdee.top/Article/details/gtvyygdypi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtwsrecemr.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gticbobdqd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoicxxzcl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guowangkeji.top/Article/details/gtmbuguilk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtjvzjjexy.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gtlefnberb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.redwolf501.top/Article/details/gtvkhdxkbc.html

PHP:  get_object_vars($obj);
来源：http://dali.tianlin.xyz/Article/details/gtbxzjraoo.html

JS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gteexsurcq.html

TS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gtbjrndtcz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gtcqemrsih.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuanzx.com/Article/details/gtgupladij.html

Ruby: obj.instance_variables
来源：http://dali.9152youxi.cn/Article/details/gtuckekpeq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gtmjhkqixn.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtjwlechsc.html

H. 异常与错误处理
来源：http://dali.zhongyouzk.top/Article/details/gtomyhioys.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtsfbomdaq.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gtadpyrdwf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gtigvzrtwj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sxryk.cn/Article/details/gtvtwnevve.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtbxftdzxi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpfwsorq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenjidiqi.icu/Article/details/gtvrlbnoan.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yueranfly.top/Article/details/gthsofrvln.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgufenzy.top/Article/details/gtpofmuenp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xylfe.cn/Article/details/gtzutjwigz.html

[H02] finally / ensure 收尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmozmcji.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gtxjsqicfr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtuycnouem.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtknpnwsgm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtdjbfqitn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtqfajfbbq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.feifeiyinyue.top/Article/details/gtdqsyzqhi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gtiwaebjkn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtbemqwqci.html

[H03] 主动抛出异常
来源：http://dali.svipenyu.cn/Article/details/gtjwueminj.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gtqpgovkxz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtglsaukvk.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirwnzoaa.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtwrttretw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtzvgqnnew.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tanke756.top/Article/details/gtgrqwgxhd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ppjwa.cn/Article/details/gtyrilpgxe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtisbyqqsh.html

[H04] 自定义异常类型
来源：http://dali.hfpthk.cn/Article/details/gtogygijqr.html

Py:   class MyError(Exception): pass
来源：http://dali.pengpengdd.cyou/Article/details/gtvvuullrb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtpuvtouyo.html

JS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gtsfqfetjk.html

TS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtntfbudus.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtzlnpfohc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gtafhxprwz.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigufen.top/Article/details/gtpmwhabmz.html

C#:   class MyException : Exception {}
来源：http://dali.hfpthk.cn/Article/details/gtshkvgqmi.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gtzrfiqiwu.html

Py:   except ValueError as e:
来源：http://dali.yanxiufei.cn/Article/details/gtwejawjxd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.dashuyun.cn/Article/details/gtsdftnydt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtmmntkovb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gtkuxglnpj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenlongwang.top/Article/details/gtqjlngczx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xziqi.cn/Article/details/gtubbmzxin.html

Ruby: rescue ArgumentError => e
来源：http://dali.smart0.xyz/Article/details/gtvugsdghv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gteexgfmhg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zycfv.cn/Article/details/gtbtkxkzjs.html

Py:   value = d.get("k") or default
来源：http://dali.ivvv.top/Article/details/gtyhdjomzx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gtwhpedngo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gttmlymdvu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gtyhvecniv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenlongwang.top/Article/details/gtmxvzehfb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hysaishi.cn/Article/details/gtmecasxsn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gteusaodqu.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gtolgjcxhy.html

[H07] 断言
来源：http://dali.xuetiantiany.cn/Article/details/gtupdzapyl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gtsosivfsh.html

PHP:  assert($x > 0);
来源：http://dali.xziqi.cn/Article/details/gtcrbuxmcr.html

JS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtxyktkvaz.html

TS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gthxfvcglt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.iojbl.cn/Article/details/gtdnawrams.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cashguo.top/Article/details/gtgvqjturg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gtdttkpjme.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtjbbekmar.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuanzx.com/Article/details/gthqkcnkjw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ybcxt.top/Article/details/gttcrttjya.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fengsongda.top/Article/details/gtryhjitql.html

JS:   e.message;  e.stack
来源：http://dali.tianlin.xyz/Article/details/gtncfjbnrj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tianlin.xyz/Article/details/gtrpiyupis.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hywenlv.cn/Article/details/gtpkzkxjld.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gtfyesnnsf.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnxiangtu.top/Article/details/gtuykmrygt.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sxryk.cn/Article/details/gtetaefbkf.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gtuzklgpam.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cqqwz.cn/Article/details/gtlengilxi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhongyouzk.top/Article/details/gtgvcpeqmq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbcfoyai.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gtocvqgfqq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.dianchejie.cn/Article/details/gtiypwqkky.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yvedp.cn/Article/details/gtaxupydza.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hnxiangtu.top/Article/details/gtcszdppjw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yvedp.cn/Article/details/gteeucevca.html

[H10] 资源自动释放
来源：http://dali.yj20258888.top/Article/details/gtklydspwt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangdashe.top/Article/details/gtwtelabqx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigfzy.top/Article/details/gtjudxfrhi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gtmxkdwdzr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtvdmpfuki.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aibaodan.cn/Article/details/gtijratquq.html

Go:   defer f.Close()
来源：http://dali.tianlin.xyz/Article/details/gtgjfpfkpd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cqqwz.cn/Article/details/gtlxhyjyiq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtahbhyqnh.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtzflztekm.html

I. 正则表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtfkyiwjxd.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtaxjqpxdd.html

[I01] 判断是否匹配
来源：http://dali.sufxvd.cn/Article/details/gtoqldfwib.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gtamttmcwp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtweyduahq.html

JS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gtariohjqg.html

TS:   /\d+/.test(s)
来源：http://dali.hfpthk.cn/Article/details/gtyqyyfibx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tian-w.cn/Article/details/gtploxwrgs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtneskbcqp.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynoczvmp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fzhhl.top/Article/details/gtfllncwff.html

[I02] 提取所有匹配
来源：http://dali.tianlin.xyz/Article/details/gtasozxcth.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gtegwkfesz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xylfe.cn/Article/details/gteoipcsae.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pycfn.com/Article/details/gtneeuaotf.html

TS:   s.match(/\d+/g)
来源：http://dali.cdnleiting.top/Article/details/gtutvzqxmt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtdfuwfoxn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gtpolwviju.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gtaothelgb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjvsgtza.html

[I03] 提取捕获分组
来源：http://dali.yj202588.top/Article/details/gtaglukorb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.meibo888.top/Article/details/gtrwjaselp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdvdffoq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guowangkeji.top/Article/details/gtjrannsuw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxuanxn.top/Article/details/gtihtahkfm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.mhx1999.top/Article/details/gtvsyjlbjd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jianghu66.top/Article/details/gtknzfzkgd.html


<!-- 参考信息 -->