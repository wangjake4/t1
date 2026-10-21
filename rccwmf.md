代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkuojidb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtmboseeja.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigfzy.top/Article/details/gtudbezzif.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrwvjcnk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.kuanghao11.cn/Article/details/gtqcmanptw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzbwwgut.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtfqnsyymi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtqxfbgzfa.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtstcysuld.html

TS:   path.extname("a.txt")
来源：http://dali.birdmap.top/Article/details/gtjyeutlbg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqfdtngl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtfvrqfvaq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtptjqnrim.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gtnbiwmcll.html

[F11] 复制与移动文件
来源：http://dali.jiagoushi.top/Article/details/gtkwyxqtwn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkounpyck.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtatavdwyz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gturenkver.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtfmirrzsp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtqigiatpf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.feifeiyinyue.top/Article/details/gttwjreusk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtngaephjg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnqzz.top/Article/details/gtdbcvqawk.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gtjqqhaotk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gtcxuudciy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gtawilqlyt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekhhdxej.html

TS:   // 同上
来源：http://dali.cheryme.top/Article/details/gtrlxeelpw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gotoacloud.top/Article/details/gtcbllryio.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jiagoushi.top/Article/details/gtcvuqqbpx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigufen.top/Article/details/gtdgexecyz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.birdmap.top/Article/details/gtlfosiaiq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtwrucweiz.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gtwcoreiiq.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtftviizjm.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gtgcnorckp.html

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gtvfvexvgs.html

PHP:  class User {}
来源：http://dali.cucudq.cn/Article/details/gtklxltlsm.html

JS:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtxvdbjgqo.html

TS:   class User { name: string = ""; }
来源：http://dali.ydzc1.top/Article/details/gthuvsmhbk.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtezoqmzmf.html

Go:   type User struct { Name string }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmmsnyln.html

Ruby: class User; end
来源：http://dali.hfpthk.cn/Article/details/gtkobhwvao.html

C#:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtizdbjucb.html

[G02] 构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtpkgjcwki.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shangyingyoupin.top/Article/details/gtiwxyvaow.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gtycovxstq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtebsinwpc.html

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gtirbofysa.html

Java: User(String name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtsvbmznjr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigufen.top/Article/details/gtecvtuvrb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenjidiqi.icu/Article/details/gthanpqobm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtqluwyoph.html

[G03] 实例属性
来源：http://dali.haohaochexian.top/Article/details/gtbiqxwihr.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtgkuskrxn.html

PHP:  public string $name = "x";
来源：http://dali.sxryk.cn/Article/details/gtreaqcxxe.html

JS:   this.name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtrdsnuxxo.html

TS:   name: string = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtyqnkvqkp.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gtizuiayye.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gtpdyxvfrh.html

Ruby: @name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gtcsdctxvo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gtfykyvrxf.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gtaquwlgje.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtqtacxfmp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtnhtcudpv.html

JS:   greet() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtsdxjurri.html

TS:   greet(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtpgnkogmf.html

Java: String greet() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtxfzkyrwq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gtmbbifhxp.html

Ruby: def greet; @name; end
来源：http://dali.yj20258.top/Article/details/gtzwzdzrrv.html

C#:   public string Greet() => Name;
来源：http://dali.guannengcc.top/Article/details/gthveovhob.html

[G05] 继承
来源：http://dali.dianchejie.cn/Article/details/gtooxqewdy.html

Py:   class Admin(User): pass
来源：http://dali.nanxinkj.top/Article/details/gtwlfflgea.html

PHP:  class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gthaekdzig.html

JS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtvdhpdzqq.html

TS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtsaozrwoh.html

Java: class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtbxefggne.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gotoacloud.top/Article/details/gthrssiodf.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gtqvdtmfxa.html

C#:   class Admin : User {}
来源：http://dali.zhixingplan.top/Article/details/gtzmjvixnm.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gtamkaudqs.html

Py:   def greet(self): return "admin"
来源：http://dali.zhongyouzk.top/Article/details/gtqjdjtwrs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtpqmionkq.html

JS:   greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtstqiuqhl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtmtecwjuj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtbpmloiav.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gthhwzioso.html

Ruby: def greet; "admin"; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudgcdfgy.html

C#:   public override string Greet() => "admin";
来源：http://dali.fengsongda.top/Article/details/gtqjbrzvqd.html

[G07] 调用父类方法
来源：http://dali.hammf.cn/Article/details/gtowlfmtwd.html

Py:   super().greet()
来源：http://dali.shangyingyoupin.top/Article/details/gtejfwjavb.html

PHP:  parent::greet();
来源：http://dali.sxryk.cn/Article/details/gtxhmnaajy.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtjhnnybxw.html

TS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtfukssphl.html

Java: super.greet();
来源：http://dali.iojbl.cn/Article/details/gtdtqziqec.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dianchejie.cn/Article/details/gtglnwuzqt.html

Ruby: super
来源：http://dali.mhx1999.top/Article/details/gtneuinzyc.html

C#:   base.Greet();
来源：http://dali.jqgufenzy.top/Article/details/gtyzpjfdmn.html

[G08] 静态方法与属性
来源：http://dali.yueranfly.top/Article/details/gtrerobhmj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gtumoivjds.html

PHP:  public static function f() {}
来源：http://dali.sxryk.cn/Article/details/gtshgejwty.html

JS:   static f() {}
来源：http://dali.zdqjudy.top/Article/details/gttrwyavby.html

TS:   static f(): void {}
来源：http://dali.jianghu66.top/Article/details/gtmbikijtk.html

Java: static void f() {}
来源：http://dali.xziqi.cn/Article/details/gtvuaceqyj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj202588.top/Article/details/gtliducfiw.html

Ruby: def self.f; end
来源：http://dali.gogol.net.cn/Article/details/gtjvrkbkxz.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gtzlpvpnah.html

[G09] 接口 / 抽象类
来源：http://dali.chenjidiqi.icu/Article/details/gtluesslkj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yvedp.cn/Article/details/gtbbjgdevk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspbuugyd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnqzz.top/Article/details/gtyefnwjue.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gtjypxvtiy.html

Java: interface Shape { double area(); }
来源：http://dali.tian-w.cn/Article/details/gtbgwsrhrn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yongpay.top/Article/details/gtmcuddifu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gtpzorvefv.html

C#:   interface IShape { double Area(); }
来源：http://dali.cashguo.top/Article/details/gtalhxhbzy.html

[G10] 访问控制
来源：http://dali.tianlin.xyz/Article/details/gtjdkkywxx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dianchejie.cn/Article/details/gttjawqqnb.html

PHP:  public / protected / private
来源：http://dali.hammf.cn/Article/details/gtzciqzifz.html

JS:   #private 字段；其余公开
来源：http://dali.nanxinkj.top/Article/details/gtjuzefbxe.html

TS:   public / protected / private
来源：http://dali.tanke756.top/Article/details/gtqsudlxyy.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gtukbyhtlk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.c1oappe.top/Article/details/gtvzknzrxq.html

Ruby: public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtqbkywbva.html

C#:   public / protected / private / internal
来源：http://dali.zhongyouzk.top/Article/details/gtorvkewpk.html

[G11] getter / setter
来源：http://dali.hnqzz.top/Article/details/gtvsbeoynl.html

Py:   @property 与 @x.setter
来源：http://dali.jlsjyb.cn/Article/details/gtugajctrj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtrwstyiew.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtmiqaqrul.html

TS:   get name(): string { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwjiwlbf.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtbqvykugo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtkgvgbmfy.html

Ruby: attr_accessor :name
来源：http://dali.daxiang520.top/Article/details/gtoouniwqz.html

C#:   public string Name { get; set; }
来源：http://dali.yuxming.cn/Article/details/gtaemrqbrq.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gtzxwlbuso.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtfaiiwfnr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtpkwfxfaa.html

JS:   toString() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtrtwhiyku.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbnktwsm.html

Java: @Override public String toString() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gthffnfpcq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtzefjpaxp.html

Ruby: def to_s; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtvforouec.html

C#:   public override string ToString() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtahjhxmsq.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gttrfqkuyh.html

Py:   isinstance(u, User)
来源：http://dali.aibaodan.cn/Article/details/gtreurtpgu.html

PHP:  $u instanceof User
来源：http://dali.havefunace.top/Article/details/gtkdbtyqgn.html

JS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtwncplopi.html

TS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtzkcjdavi.html

Java: u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtewoxcwko.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yonumen.top/Article/details/gtuxkybgxj.html

Ruby: u.is_a?(User)
来源：http://dali.guowangkeji.top/Article/details/gtzaraylgu.html

C#:   u is User
来源：http://dali.zdqjudy.top/Article/details/gtgwcltpmy.html

[G14] 数据类 / record
来源：http://dali.tianlin.xyz/Article/details/gtlcuruale.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yonumen.top/Article/details/gtxxnaoeka.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hongshengwenyu.top/Article/details/gtfqsdgovn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.redwolf501.top/Article/details/gtqjrnrcrn.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gtrsftbwim.html

Java: record User(String name, int age) {}
来源：http://dali.aibaodan.cn/Article/details/gtvyrvymcr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhongyouzk.top/Article/details/gtoojkdxwg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gotoacloud.top/Article/details/gtzcnolkrr.html

C#:   record User(string Name, int Age);
来源：http://dali.ydzc1.top/Article/details/gtzshxqiya.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gtgrkdpluf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gtyollakvs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hysaishi.cn/Article/details/gtsbxrudau.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gtxkhouzng.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gtapkuxnta.html

Java: enum Color { RED, GREEN }
来源：http://dali.fengsongda.top/Article/details/gtdiwgwiyo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangdashe.top/Article/details/gtgzkwujmm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gtilmdegje.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gturaydmus.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gtefsxggxf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgbxenwm.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gtrbkkvnxj.html

JS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gtmccvgogs.html

TS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gtsoyjnuyj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ehwqpu.com/Article/details/gtynfxniki.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aizwys.cn/Article/details/gtailhjkem.html

Ruby: obj.instance_variables
来源：http://dali.shzxlz.cn/Article/details/gtdfassell.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.316326.xyz/Article/details/gtfrxhpmai.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtnqgkzzcs.html

H. 异常与错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwjjoiab.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtmhjivwzl.html

[H01] try / catch 基础
来源：http://dali.mhx1999.top/Article/details/gtdohdqspn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.snrcjt.cn/Article/details/gtvsopyjrh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cheryme.top/Article/details/gtneqzjjmn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtlvbjzftc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtiogidtqs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hongshengwenyu.top/Article/details/gtoibjynfs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnxiangtu.top/Article/details/gtfhvyoqro.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gzhubu.top/Article/details/gtalagklzr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenzaomai.com/Article/details/gtrrntrazc.html

[H02] finally / ensure 收尾
来源：http://dali.sweek.top/Article/details/gtvpzzfocw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guowangkeji.top/Article/details/gtbgyltuwa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtbufgcsbd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtpucyugpy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtszzvtcty.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtkbndyesg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dianchejie.cn/Article/details/gtidyzrvuw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.mhx1999.top/Article/details/gtvnvxbewn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtwkdxgeld.html

[H03] 主动抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gtkcwlwusj.html

Py:   raise ValueError("错误信息")
来源：http://dali.ppjwa.cn/Article/details/gtptrhuiyw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtuzmodytq.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtbudhcyco.html

TS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtkqeaottv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtwjzbdmoq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.andypj.xyz/Article/details/gtcspuopsk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgufenzy.top/Article/details/gtupvkgjle.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtnhyffkyd.html

[H04] 自定义异常类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuldudxd.html

Py:   class MyError(Exception): pass
来源：http://dali.dashuyun.cn/Article/details/gtoklxlljb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gtrrcvdaat.html

JS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtmlpbrlve.html

TS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gtaqfwwugl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gttkaxsigf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigufen.top/Article/details/gtahvozxst.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gtohrxkdpf.html

C#:   class MyException : Exception {}
来源：http://dali.ydzc1.top/Article/details/gtpdlveyat.html

[H05] 捕获特定类型
来源：http://dali.pycfn.com/Article/details/gtyzzvshue.html

Py:   except ValueError as e:
来源：http://dali.wangdashe.top/Article/details/gtsnfqjatl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yvedp.cn/Article/details/gtannbagxo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtpyhwmifv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gticeblnkb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dashuyun.cn/Article/details/gtrfpklrmo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gtvcwzllua.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gtywwsrwip.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gtnesbezio.html

[H06] 可选值 / 空值安全访问
来源：http://dali.andypj.xyz/Article/details/gtksgahlwh.html

Py:   value = d.get("k") or default
来源：http://dali.aibaodan.cn/Article/details/gthzgybwoc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gtbaqrxpok.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gtzjkqiygh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtwqpgjxzy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgufenzy.top/Article/details/gtkhtgqpqq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gtbsiqkhve.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tian-w.cn/Article/details/gtlvjpgixm.html

C#:   obj?.A?.B ?? default
来源：http://dali.shuidangran.top/Article/details/gtkhxqcwea.html

[H07] 断言
来源：http://dali.shangyingyoupin.top/Article/details/gtpbnyhapo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.c1oappe.top/Article/details/gtmkhbixpw.html

PHP:  assert($x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtgiegnngy.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtgduuovdm.html

TS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtjmthbuki.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthecfykdu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigufen.top/Article/details/gthpmopgva.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.vqdsnc.cn/Article/details/gtrfnkdwiq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtxhsyjich.html

[H08] 获取错误信息与堆栈
来源：http://dali.cqqwz.cn/Article/details/gtzfwxgzir.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hfpthk.cn/Article/details/gtrfsksoxv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gtphdbtpci.html

JS:   e.message;  e.stack
来源：http://dali.fengsongda.top/Article/details/gtbppxfqbp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuanzx.com/Article/details/gthkfnjlhe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gtuigukdzl.html

Go:   err.Error()
来源：http://dali.xinyue.icu/Article/details/gtchhldfhh.html

Ruby: e.message;  e.backtrace
来源：http://dali.gaohongyu789.top/Article/details/gtfgrhpint.html

C#:   e.Message;  e.StackTrace
来源：http://dali.chenjidiqi.icu/Article/details/gtmjasnozm.html

[H09] 带错误码的异常
来源：http://dali.zhongyouzk.top/Article/details/gtiwyjwafw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenjidiqi.icu/Article/details/gtrtubkmyu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ivvv.top/Article/details/gtkfmlixby.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangdashe.top/Article/details/gtxiiaeurd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hysaishi.cn/Article/details/gtbcvcidft.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ppjwa.cn/Article/details/gtjmapgwlx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tanke756.top/Article/details/gtwnhpwjfo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkziybmi.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.redwolf501.top/Article/details/gtfqtcmtfn.html

[H10] 资源自动释放
来源：http://dali.yanxiufei.cn/Article/details/gtqgmvgxmc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tian-w.cn/Article/details/gtbfzwpcfu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gtfvivucej.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtzyhsxxms.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gtxpvfpehg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxuanxn.top/Article/details/gtdohlvjso.html

Go:   defer f.Close()
来源：http://dali.hysaishi.cn/Article/details/gtavlfkzkf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sxryk.cn/Article/details/gtbmrixsso.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sweek.top/Article/details/gttrgfpzcx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmbebudw.html

I. 正则表达式
来源：http://dali.dashuyun.cn/Article/details/gtsuwqyjrd.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgpqhmwo.html

[I01] 判断是否匹配
来源：http://dali.dianchejie.cn/Article/details/gtaxeijqbh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gtexfwwigq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtahgaofwg.html

JS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gttionhchm.html

TS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gthyjdmxyr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yangfankeji.com/Article/details/gtzaxqxkoz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fengsongda.top/Article/details/gtiixzzxli.html

Ruby: s.match?(/\d+/)
来源：http://dali.pycfn.com/Article/details/gtsxnvtnjj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.sufxvd.cn/Article/details/gtitfoigis.html

[I02] 提取所有匹配
来源：http://dali.zhengqikj.top/Article/details/gtjfpbucqy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtzwbctalm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigufen.top/Article/details/gtelxqhxko.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenzaomai.com/Article/details/gtwccjwdkp.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigfzy.top/Article/details/gtashafiuz.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hfpthk.cn/Article/details/gtseniybcr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.fzhhl.top/Article/details/gtdfnrqerb.html

Ruby: s.scan(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gtrapofylf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtcedxlwyz.html

[I03] 提取捕获分组
来源：http://dali.quarkkingdee.top/Article/details/gtsydhbevh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ehwqpu.com/Article/details/gtewrvugfe.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.kuanghao11.cn/Article/details/gtsnpeliev.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yonumen.top/Article/details/gtflrvpfxx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhijiandao.cn/Article/details/gtqzismgfe.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xuetiantiany.cn/Article/details/gtwlngbfic.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj20258888.top/Article/details/gtecsnzxpu.html


<!-- 参考信息 -->