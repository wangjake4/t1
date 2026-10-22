代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2hxnaxtho.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2iovxpjly.html

[F11] 复制与移动文件
来源：http://dali.ppjwa.cn/Article/details/gt2rygzmxtz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gt2pqoeuagi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2ksgwmsvp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2araagcva.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tqqvpjgp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwvpodg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.svipenyu.cn/Article/details/gt2vmrhsuov.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2lcxbwfmc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ymykmicj.html

[F12] CSV 读写
来源：http://dali.andypj.xyz/Article/details/gt2brywhmxa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gt2hmrejkcn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gt2rlgdmjzx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iukopcaq.html

TS:   // 同上
来源：http://dali.quarkkingdee.top/Article/details/gt2ulujxptz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hfpthk.cn/Article/details/gt2pmgoilyw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cqqwz.cn/Article/details/gt2gqtvkspv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yonumen.top/Article/details/gt2zpvspqto.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iwfnijcz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2motlwaqe.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gt2fargqnqz.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2odazpsuh.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gt2zwkxxmpl.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gt2vczaacja.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gt2hpolrabr.html

JS:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gt2lqfhmtmr.html

TS:   class User { name: string = ""; }
来源：http://dali.hfpthk.cn/Article/details/gt2fmdmebgy.html

Java: class User {}
来源：http://dali.ivvv.top/Article/details/gt2fxsraokg.html

Go:   type User struct { Name string }
来源：http://dali.xuanzx.com/Article/details/gt2lrwhrfdd.html

Ruby: class User; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2czknkzbl.html

C#:   class User {}
来源：http://dali.zycfv.cn/Article/details/gt2fbfdcrzp.html

[G02] 构造函数
来源：http://dali.cashguo.top/Article/details/gt2byizyzef.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daxiang520.top/Article/details/gt2mcldihlc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nwbrower.top/Article/details/gt2gtsbbsvv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2pjwfuprm.html

TS:   constructor(public name: string) {}
来源：http://dali.xylfe.cn/Article/details/gt2gxmsjkwh.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gt2zbeijacb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnqzz.top/Article/details/gt2nabkfztn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ztlegqdq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gzcrvnjy.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gt2gtwdayte.html

Py:   self.name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gt2xgzgkwdi.html

PHP:  public string $name = "x";
来源：http://dali.yongpay.top/Article/details/gt2gjexqjhv.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2beihwzlm.html

TS:   name: string = "x";
来源：http://dali.cheryme.top/Article/details/gt2npdfpwcq.html

Java: private String name;
来源：http://dali.hnqzz.top/Article/details/gt2bzrmdbuz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jiagoushi.top/Article/details/gt2xsxzzpkg.html

Ruby: @name = "x"
来源：http://dali.sysykeji.top/Article/details/gt2rlsdrflm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daxiang520.top/Article/details/gt2quujdglt.html

[G04] 定义方法
来源：http://dali.0kj1m.cn/Article/details/gt2abiacwts.html

Py:   def greet(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gt2qugawdaj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gt2gotvcxwk.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nlrtlksy.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2xsqpolub.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2qacvovxv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gt2fbtogvsy.html

Ruby: def greet; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2lntycnwo.html

C#:   public string Greet() => Name;
来源：http://dali.dianchejie.cn/Article/details/gt2sejwyovm.html

[G05] 继承
来源：http://dali.zdqjudy.top/Article/details/gt2glsetbzu.html

Py:   class Admin(User): pass
来源：http://dali.gogol.net.cn/Article/details/gt2bwqqqqcp.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gt2xwpqvvqr.html

JS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gt2xvkktodu.html

TS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2okrkjiqo.html

Java: class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2vvkylfhu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenzaomai.com/Article/details/gt2zrzfnlhv.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gt2zsgxedqi.html

C#:   class Admin : User {}
来源：http://dali.yj20258888.top/Article/details/gt2uplyfiky.html

[G06] 重写方法
来源：http://dali.jiagoushi.top/Article/details/gt2slqtpqkl.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gt2jekrafoy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2zbckykzr.html

JS:   greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uuoowwwj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2nmanfsad.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2vkipmlqu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gt2lweeifxj.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gt2fzmaljef.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gt2hemxkmqh.html

[G07] 调用父类方法
来源：http://dali.sweek.top/Article/details/gt2iqvqcjmo.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dvntvyyt.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2rtipnobo.html

JS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2zygcypto.html

TS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxyqzcnh.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gt2ksiynqcw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ydzc1.top/Article/details/gt2rstvvuih.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gt2sodrxmhh.html

C#:   base.Greet();
来源：http://dali.chenlongwang.top/Article/details/gt2kuifunlu.html

[G08] 静态方法与属性
来源：http://dali.yj202588.top/Article/details/gt2dpbajtyt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gt2vfyedosg.html

PHP:  public static function f() {}
来源：http://dali.nwbrower.top/Article/details/gt2rkmjhijh.html

JS:   static f() {}
来源：http://dali.sxryk.cn/Article/details/gt2uisvcyqi.html

TS:   static f(): void {}
来源：http://dali.kuanghao11.cn/Article/details/gt2pmlfwgth.html

Java: static void f() {}
来源：http://dali.jinqigufen.top/Article/details/gt2zlwsxiil.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dianchejie.cn/Article/details/gt2bnpqdtir.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gt2xgxqpjzf.html

C#:   public static void F() {}
来源：http://dali.hnqzz.top/Article/details/gt2pwgyvium.html

[G09] 接口 / 抽象类
来源：http://dali.jianghu66.top/Article/details/gt2qoufshpm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhongyouzk.top/Article/details/gt2siazxmbh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tianlin.xyz/Article/details/gt2llufolsp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuxming.cn/Article/details/gt2wljgomdx.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gt2qfjfwtfs.html

Java: interface Shape { double area(); }
来源：http://dali.cdnleiting.top/Article/details/gt2mijsicyw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.mhx1999.top/Article/details/gt2bwlvipxv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wgudigpf.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenlongwang.top/Article/details/gt2kzshenyu.html

[G10] 访问控制
来源：http://dali.yanxiufei.cn/Article/details/gt2bmgygfbs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangdashe.top/Article/details/gt2zgbuxdhf.html

PHP:  public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gt2myztpvli.html

JS:   #private 字段；其余公开
来源：http://dali.yanxiufei.cn/Article/details/gt2qzmmjutk.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gt2sljlhzcb.html

Java: public / protected / private / 默认包级
来源：http://dali.sweek.top/Article/details/gt2kqatawxd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sufxvd.cn/Article/details/gt2ajpwjfpa.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzjdavn.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bqckauqu.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gt2cyunmgca.html

Py:   @property 与 @x.setter
来源：http://dali.hfpthk.cn/Article/details/gt2zatiiipt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2fiwldxuk.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gt2hahpqkcf.html

TS:   get name(): string { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gt2slvmgcig.html

Java: public String getName() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2ssxvwkds.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ylbqysea.html

Ruby: attr_accessor :name
来源：http://dali.zhongyouzk.top/Article/details/gt2ucjxkddy.html

C#:   public string Name { get; set; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oklyqzhj.html

[G12] 对象转字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2mmgpikeq.html

Py:   def __str__(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gt2kcqvidrj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gt2ggaevnrl.html

JS:   toString() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2dgloegws.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2kruqpkaz.html

Java: @Override public String toString() { return name; }
来源：http://dali.xziqi.cn/Article/details/gt2zgnjzvfe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gt2stqogish.html

Ruby: def to_s; @name; end
来源：http://dali.zhixingplan.top/Article/details/gt2mrusjnqr.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gt2begzztqa.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gt2pbryjwte.html

Py:   isinstance(u, User)
来源：http://dali.xziqi.cn/Article/details/gt2khvvymbi.html

PHP:  $u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2uxdyjdwu.html

JS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gt2ltpyxwir.html

TS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2lzvjxncf.html

Java: u instanceof User
来源：http://dali.hammf.cn/Article/details/gt2cnsmsfby.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2wytizdxg.html

Ruby: u.is_a?(User)
来源：http://dali.chenzaomai.com/Article/details/gt2hktezmxq.html

C#:   u is User
来源：http://dali.tian-w.cn/Article/details/gt2bmgtkded.html

[G14] 数据类 / record
来源：http://dali.cashguo.top/Article/details/gt2vdbvupcw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuanzx.com/Article/details/gt2onsylsnr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuxming.cn/Article/details/gt2iyxoyzef.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shzxlz.cn/Article/details/gt2ytudrbea.html

TS:   type User = { name: string; age: number };
来源：http://dali.316326.xyz/Article/details/gt2ryghkdzw.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gt2ldenqroy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daria6918.cn/Article/details/gt2onjrbrsl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangdashe.top/Article/details/gt2yezyfstv.html

C#:   record User(string Name, int Age);
来源：http://dali.hongshengwenyu.top/Article/details/gt2gfbqssem.html

[G15] 枚举
来源：http://dali.gaohongyu789.top/Article/details/gt2bohnhbbl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dashuyun.cn/Article/details/gt2tufakblm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hysaishi.cn/Article/details/gt2ubwlrlua.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sxryk.cn/Article/details/gt2aiisxwod.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2wfxyvokp.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnqzz.top/Article/details/gt2velspbsn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gt2vbrwhmyf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gt2atoyygwj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qaulmoyd.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2awujxqdz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgfzy.top/Article/details/gt2rybsleqy.html

PHP:  get_object_vars($obj);
来源：http://dali.bjfxy.top/Article/details/gt2beiogwkw.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2entlrqvh.html

TS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gt2mkkkxacp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigfzy.top/Article/details/gt2vxvtrtla.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yvedp.cn/Article/details/gt2fpbcomca.html

Ruby: obj.instance_variables
来源：http://dali.aibaodan.cn/Article/details/gt2dakbijfj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gt2qjqavqfi.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2nzscrska.html

H. 异常与错误处理
来源：http://dali.havefunace.top/Article/details/gt2xhevrzza.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2xdoycgpn.html

[H01] try / catch 基础
来源：http://dali.sufxvd.cn/Article/details/gt2fpuhlvcw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gt2frnqzkrj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fengsongda.top/Article/details/gt2drgwgdng.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gt2tmmjkrqy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gt2ktzgezaz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuanzhike.top/Article/details/gt2tspjfksj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nudxwvhj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gt2awrbsmuc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zwubipqn.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gt2kzgjxboo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gt2jifoxbyk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2uhqkxjos.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2hcvwvslj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gt2zyznpexc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwddmurp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenjidiqi.icu/Article/details/gt2teejuhrt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gt2xuwnrgjp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2dcatqpqj.html

[H03] 主动抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gt2esiotseu.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenzaomai.com/Article/details/gt2ukkwdarw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2xfxcbwhq.html

JS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2aysrdjdo.html

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2tifnrlhy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2ftatyimu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gt2yeqviefk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yanxiufei.cn/Article/details/gt2ftamlyjz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2znpsbeaf.html

[H04] 自定义异常类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xovtyetv.html

Py:   class MyError(Exception): pass
来源：http://dali.cqqwz.cn/Article/details/gt2lqgiqyaq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gt2ncnvgzmx.html

JS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gt2xoqtylib.html

TS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gt2gqrshejq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gt2ppeazuad.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gt2hlbkinie.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gt2kyyyvncg.html

C#:   class MyException : Exception {}
来源：http://dali.zhengqikj.top/Article/details/gt2bojpcfyf.html

[H05] 捕获特定类型
来源：http://dali.c1oappe.top/Article/details/gt2qosaaspq.html

Py:   except ValueError as e:
来源：http://dali.mhx1999.top/Article/details/gt2rqhchvzj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.316326.xyz/Article/details/gt2paojdisk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gt2pebxgegv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gt2kpmfxbzo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhixingplan.top/Article/details/gt2xydyxhyb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gt2bcjyllbu.html

Ruby: rescue ArgumentError => e
来源：http://dali.nwbrower.top/Article/details/gt2sjjbbmyo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2drjaxhlh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.snrcjt.cn/Article/details/gt2axnjgvld.html

Py:   value = d.get("k") or default
来源：http://dali.hysaishi.cn/Article/details/gt2zvjjpxud.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gt2pogqvzky.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gt2ghprditz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gt2rzxpixxz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gt2pevvxlvf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuxming.cn/Article/details/gt2rdytdikr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sojpyewn.html

C#:   obj?.A?.B ?? default
来源：http://dali.jiagoushi.top/Article/details/gt2rxqrjidg.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gt2cmscvure.html

Py:   assert x > 0, "必须为正"
来源：http://dali.redwolf501.top/Article/details/gt2cyvjnwla.html

PHP:  assert($x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wyrhaglw.html

JS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2nessbsdv.html

TS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2icxxqugj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hysaishi.cn/Article/details/gt2onqzhcvp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cqqwz.cn/Article/details/gt2yxzvaffv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bytwxtdv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2qxuyxuyb.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgfzy.top/Article/details/gt2zfupjthz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dashuyun.cn/Article/details/gt2knpyhvxt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jiagoushi.top/Article/details/gt2rabaohsn.html

JS:   e.message;  e.stack
来源：http://dali.cdnleiting.top/Article/details/gt2zcuahddt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gt2uqqztrms.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.meibo888.top/Article/details/gt2chnkslbl.html

Go:   err.Error()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2inimddln.html

Ruby: e.message;  e.backtrace
来源：http://dali.hywenlv.cn/Article/details/gt2iwrzjplp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aizwys.cn/Article/details/gt2qheeufqo.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gt2dcvcrrbq.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.iojbl.cn/Article/details/gt2mipobist.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.feifeiyinyue.top/Article/details/gt2osywyupj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xylfe.cn/Article/details/gt2artiabfy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pycfn.com/Article/details/gt2ahklswyp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rfjkxaxi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xylfe.cn/Article/details/gt2jxregxmk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qxuullbw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gt2svzgfavz.html

[H10] 资源自动释放
来源：http://dali.xuanzx.com/Article/details/gt2hjhcabck.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.havefunace.top/Article/details/gt2usqeqouw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dianchejie.cn/Article/details/gt2bsfncgye.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gt2tccopfqb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gt2hvobwfrm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gt2ypahqyur.html

Go:   defer f.Close()
来源：http://dali.chenlongwang.top/Article/details/gt2ppxjijqn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gt2yinsfmqk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2uuziubkk.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2zkvgvjpf.html

I. 正则表达式
来源：http://dali.xuanzx.com/Article/details/gt2anqoaspi.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2blajoljn.html

[I01] 判断是否匹配
来源：http://dali.jiagoushi.top/Article/details/gt2erimxqap.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tjorkhaa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2xrgagwdd.html

JS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gt2utzlkpiq.html

TS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gt2ivopomrc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.c1oappe.top/Article/details/gt2oldtiovl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jyoumei.cn/Article/details/gt2limupjuc.html

Ruby: s.match?(/\d+/)
来源：http://dali.pycfn.com/Article/details/gt2hqnelrvq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhoulong.xyz/Article/details/gt2chirnytw.html

[I02] 提取所有匹配
来源：http://dali.shuidangran.top/Article/details/gt2kyvwylum.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2oacpcwxa.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nwbrower.top/Article/details/gt2cxvwhoyh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yuxming.cn/Article/details/gt2ylmsocyn.html

TS:   s.match(/\d+/g)
来源：http://dali.sysykeji.top/Article/details/gt2feinoatr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ivvv.top/Article/details/gt2cxehpedf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gt2anmwtjdz.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cwjotzzg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2rvxxstnm.html

[I03] 提取捕获分组
来源：http://dali.jqgufenzy.top/Article/details/gt2tqvvhzif.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.chenzaomai.com/Article/details/gt2dribrriq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangdashe.top/Article/details/gt2hzklhnub.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2garsupus.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yongpay.top/Article/details/gt2dybpwits.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sydfmwpn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258888.top/Article/details/gt2dqcxmyig.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zycfv.cn/Article/details/gt2gztuvxux.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhoulong.xyz/Article/details/gt2rjrgzyih.html

[I04] 正则替换
来源：http://dali.ppjwa.cn/Article/details/gt2thycbvwe.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tian-w.cn/Article/details/gt2zhurbisf.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gzhubu.top/Article/details/gt2svecywqw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gt2kyhikomf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yongpay.top/Article/details/gt2xqjorklo.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gt2yzmdotnz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dhsknnxg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgfzy.top/Article/details/gt2ugkpcbzp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.cashguo.top/Article/details/gt2xzdjygkn.html

[I05] 按正则拆分
来源：http://dali.yonumen.top/Article/details/gt2goemcxks.html


<!-- 参考信息 -->