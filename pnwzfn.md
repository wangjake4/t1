代发 wailian999

[F09] 获取文件大小
来源：http://dali.fengsongda.top/Article/details/gtuzqrepla.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtnswujytb.html

PHP:  filesize("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtclzfboan.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gtatwoegzh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtppkppxrh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtpcbcpdcv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258.top/Article/details/gtkhmeirfx.html

Ruby: File.size("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtutxebtja.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigfzy.top/Article/details/gtuviieyty.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hammf.cn/Article/details/gtzyykvdkt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtkoqpsulf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ybcxt.top/Article/details/gtnreguhkg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtfywkdfdv.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtcqeyyrvd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gtakdaurgn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtznofokoc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtcdbutcgc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtisdrompk.html

[F11] 复制与移动文件
来源：http://dali.shuidangran.top/Article/details/gtmpcssyvn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtohlcdunb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gtbfshqbkm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtpbymuxgn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtyrzqrssi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gthjnkhznz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.smart0.xyz/Article/details/gtsicmyufj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtlkhmfwjo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yanxiufei.cn/Article/details/gtanhuwakz.html

[F12] CSV 读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymjnpwgg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cqqwz.cn/Article/details/gtipckhwjb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ppjwa.cn/Article/details/gtphpotnwe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangshuangyany.cn/Article/details/gtthczqjpy.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gtptlzpbtl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenjidiqi.icu/Article/details/gtplyhcere.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zdqjudy.top/Article/details/gtylfiyvaf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hammf.cn/Article/details/gtgpbwtfxb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gotoacloud.top/Article/details/gtsuwpjblr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnnyveenz.html

G. 面向对象
来源：http://dali.pengpengdd.cyou/Article/details/gthogugkxz.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlqbmnxzu.html

[G01] 定义类
来源：http://dali.zhengqikj.top/Article/details/gtythpyrsi.html

Py:   class User: pass
来源：http://dali.cashguo.top/Article/details/gtkbjeuelo.html

PHP:  class User {}
来源：http://dali.yongpay.top/Article/details/gthjslccdx.html

JS:   class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtghewvtjx.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gtgdqahppb.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gtqvcivkxh.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gtmmdiohau.html

Ruby: class User; end
来源：http://dali.wangshuangyany.cn/Article/details/gtitufgutq.html

C#:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvltvjdcv.html

[G02] 构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtwschocwt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gtgwozjzzr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tanke756.top/Article/details/gtwnuoedpz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtgozikzct.html

TS:   constructor(public name: string) {}
来源：http://dali.ppjwa.cn/Article/details/gtwqwvefak.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtlmiosdey.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cqqwz.cn/Article/details/gttokkzhoy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zdqjudy.top/Article/details/gtjslwjvpy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gogol.net.cn/Article/details/gtbdtppmdw.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gtfgrjmuop.html

Py:   self.name = "x"
来源：http://dali.hammf.cn/Article/details/gtbzqgveyw.html

PHP:  public string $name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcwmkajz.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinkjcmbo.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gtnxywnaex.html

Java: private String name;
来源：http://dali.zhixingplan.top/Article/details/gthgouzonb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gtcvbsthes.html

Ruby: @name = "x"
来源：http://dali.ehwqpu.com/Article/details/gtekorpebv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtynomzlri.html

[G04] 定义方法
来源：http://dali.pycfn.com/Article/details/gtnqvfzgal.html

Py:   def greet(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtnkcjushq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtxyigvovn.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtyobwpalt.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gttlovomdg.html

Java: String greet() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtapthdvza.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtukyahyex.html

Ruby: def greet; @name; end
来源：http://dali.yj202588.top/Article/details/gtawabbjbt.html

C#:   public string Greet() => Name;
来源：http://dali.nanxinkj.top/Article/details/gtgldzimgl.html

[G05] 继承
来源：http://dali.daria6918.cn/Article/details/gtcqvrbyzp.html

Py:   class Admin(User): pass
来源：http://dali.jiagoushi.top/Article/details/gtggblsfwc.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gttqhjqxdo.html

JS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtjdcicyze.html

TS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gthdqszeog.html

Java: class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtljpklgkm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj202588.top/Article/details/gtudspwpbe.html

Ruby: class Admin < User; end
来源：http://dali.yuanzhike.top/Article/details/gtslhdkoet.html

C#:   class Admin : User {}
来源：http://dali.jinqigufen.top/Article/details/gtbtwmanua.html

[G06] 重写方法
来源：http://dali.yvedp.cn/Article/details/gtcitjmfjy.html

Py:   def greet(self): return "admin"
来源：http://dali.snrcjt.cn/Article/details/gtjpiitdde.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtsmxovhuv.html

JS:   greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtfzlsuayy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtccwhhrig.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtqnepvmnd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nwbrower.top/Article/details/gtaekpbuvc.html

Ruby: def greet; "admin"; end
来源：http://dali.vqdsnc.cn/Article/details/gtkknsxqza.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gtjaahgaow.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gtihbfufya.html

Py:   super().greet()
来源：http://dali.smart0.xyz/Article/details/gtcglxjbaa.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gtifokpdsw.html

JS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtxdrzeksk.html

TS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtrvadlwvh.html

Java: super.greet();
来源：http://dali.wangdashe.top/Article/details/gtwwzekoqp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cdnleiting.top/Article/details/gtsomaopfw.html

Ruby: super
来源：http://dali.fzhhl.top/Article/details/gtugplnimr.html

C#:   base.Greet();
来源：http://dali.yangfankeji.com/Article/details/gtdfagxznh.html

[G08] 静态方法与属性
来源：http://dali.snrcjt.cn/Article/details/gtpmhtzkjv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tanke756.top/Article/details/gtiguicsis.html

PHP:  public static function f() {}
来源：http://dali.wangdashe.top/Article/details/gtcbovvvqn.html

JS:   static f() {}
来源：http://dali.yuanzhike.top/Article/details/gtegongvjj.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gtjwelahei.html

Java: static void f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtvtrdqdke.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.quarkkingdee.top/Article/details/gtuzdxnnpl.html

Ruby: def self.f; end
来源：http://dali.0kj1m.cn/Article/details/gtwocdgvnf.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqryqtftu.html

[G09] 接口 / 抽象类
来源：http://dali.c1oappe.top/Article/details/gtbneylbvy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gtszimuiva.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.svipenyu.cn/Article/details/gtjsosooht.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgufenzy.top/Article/details/gtgcnfuhpe.html

TS:   interface Shape { area(): number; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkeufouez.html

Java: interface Shape { double area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtkvmitxwp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtbavkiu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ehwqpu.com/Article/details/gtrpguihno.html

C#:   interface IShape { double Area(); }
来源：http://dali.guowangkeji.top/Article/details/gtvsiicrxe.html

[G10] 访问控制
来源：http://dali.fengsongda.top/Article/details/gthdnsxzds.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuxming.cn/Article/details/gtyghzqqzz.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtisdnntgs.html

JS:   #private 字段；其余公开
来源：http://dali.redwolf501.top/Article/details/gtdidlpnzh.html

TS:   public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtdvbwacyz.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gtujlzksyh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyfxwzqc.html

Ruby: public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtdvpoffvv.html

C#:   public / protected / private / internal
来源：http://dali.snrcjt.cn/Article/details/gtceenuqao.html

[G11] getter / setter
来源：http://dali.wangdashe.top/Article/details/gtyqvbubqc.html

Py:   @property 与 @x.setter
来源：http://dali.gzhubu.top/Article/details/gtpfnqomfv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtplapcied.html

JS:   get name() { return this._name; }
来源：http://dali.yj202588.top/Article/details/gtodemrtna.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258.top/Article/details/gtyzoxvwzm.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtukjerdxe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtromjunon.html

Ruby: attr_accessor :name
来源：http://dali.pycfn.com/Article/details/gtcigptyoo.html

C#:   public string Name { get; set; }
来源：http://dali.chenzaomai.com/Article/details/gtamgquazj.html

[G12] 对象转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkfmtvli.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtzdrdhdqp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtrlwmvqhp.html

JS:   toString() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbiratbmp.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtvihqljxl.html

Java: @Override public String toString() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtgtvlxiie.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtcbgjyrkr.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtmsoscbda.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtalmxgeww.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gtpxsmqffx.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gtbovoztpp.html

PHP:  $u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtltliebbt.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtifjnbwvb.html

TS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtdtbtszhl.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtgjvwcytx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xziqi.cn/Article/details/gtuvhmsnbv.html

Ruby: u.is_a?(User)
来源：http://dali.iojbl.cn/Article/details/gtcyyaqdiz.html

C#:   u is User
来源：http://dali.vqdsnc.cn/Article/details/gthbjcbohj.html

[G14] 数据类 / record
来源：http://dali.sysykeji.top/Article/details/gtvrtkorih.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gtkfognini.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gtsvvirwla.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gtpeatlzbe.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenzaomai.com/Article/details/gtzodteurp.html

Java: record User(String name, int age) {}
来源：http://dali.pycfn.com/Article/details/gtobbuoqgu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxinkj.top/Article/details/gtpjdalbyd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigufen.top/Article/details/gtlpgwxsmz.html

C#:   record User(string Name, int Age);
来源：http://dali.jlsjyb.cn/Article/details/gtcjnmfxti.html

[G15] 枚举
来源：http://dali.daria6918.cn/Article/details/gtersmthae.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yongpay.top/Article/details/gtszjezkib.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gtahbhzoea.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gtmfmwlpsb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gtznfqttln.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258888.top/Article/details/gtpaxrxbfv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhongyouzk.top/Article/details/gtkddaqzre.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtcaujhaxl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtsiowazlv.html

[G16] 对象转数组 / 字典
来源：http://dali.jlsjyb.cn/Article/details/gtkopmdawb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xinyue.icu/Article/details/gtuzucscph.html

PHP:  get_object_vars($obj);
来源：http://dali.tianlin.xyz/Article/details/gthkoijltr.html

JS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtfjvagggn.html

TS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gtvwjamhlj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhongyouzk.top/Article/details/gteecjqwgq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dianchejie.cn/Article/details/gtvcmmbpni.html

Ruby: obj.instance_variables
来源：http://dali.yj202588.top/Article/details/gtmmmxvljn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gtbyoyelxd.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gteosgvvsh.html

H. 异常与错误处理
来源：http://dali.daxiang520.top/Article/details/gtmyghmpar.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvloktoug.html

[H01] try / catch 基础
来源：http://dali.yj20258.top/Article/details/gtaagwushf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yvedp.cn/Article/details/gtlvghjbzr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.vqdsnc.cn/Article/details/gtuotlmjmq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtahyhdecr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gtjwdpgvpa.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxtybdgiw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gtsvsnjnqm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gtdqoyodrf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cucudq.cn/Article/details/gtiqlhiody.html

[H02] finally / ensure 收尾
来源：http://dali.hongshengwenyu.top/Article/details/gttwtsbazm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gtwrkolhqc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtqfialayp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtcyxutkvx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtttwqaspu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtpeujrxcz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258888.top/Article/details/gtiathdekd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ybcxt.top/Article/details/gtfhtjfnsj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.havefunace.top/Article/details/gthpsgwgms.html

[H03] 主动抛出异常
来源：http://dali.cdnleiting.top/Article/details/gtzobrkmrj.html

Py:   raise ValueError("错误信息")
来源：http://dali.hammf.cn/Article/details/gtcjsnyqpr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtgdpfkual.html

JS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtbkwyxhks.html

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtpscwjnnr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtiedzgxhm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sweek.top/Article/details/gtxngpnotn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.meibo888.top/Article/details/gtuepddkni.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtahdxbybw.html

[H04] 自定义异常类型
来源：http://dali.dashuyun.cn/Article/details/gtcrkglidx.html

Py:   class MyError(Exception): pass
来源：http://dali.cqqwz.cn/Article/details/gtqlhdfdhi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtxvqqdgkm.html

JS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gtljwiaydf.html

TS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gtahydefdy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gttnurgeik.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gtukfxuvma.html

Ruby: class MyError < StandardError; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhenndzo.html

C#:   class MyException : Exception {}
来源：http://dali.c1oappe.top/Article/details/gtqjooilwy.html

[H05] 捕获特定类型
来源：http://dali.gaohongyu789.top/Article/details/gtwfhozdhv.html

Py:   except ValueError as e:
来源：http://dali.yj20258888.top/Article/details/gtdkxkrzzv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gzhubu.top/Article/details/gtgrbnmjfz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtzymcrwly.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtxsrzlxep.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.haohaochexian.top/Article/details/gtgbpppofu.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenjidiqi.icu/Article/details/gtckagrlfp.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gtqskcnvea.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hammf.cn/Article/details/gtzuriuwrj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenzaomai.com/Article/details/gtqydocpzi.html

Py:   value = d.get("k") or default
来源：http://dali.nanxinkj.top/Article/details/gtxkxlireg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ivvv.top/Article/details/gtcsykmagx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gtduavmpog.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gtslgxxmvq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shangyingyoupin.top/Article/details/gtyfcibyop.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.c1oappe.top/Article/details/gtdbqubdke.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhengqikj.top/Article/details/gtajqkymub.html

C#:   obj?.A?.B ?? default
来源：http://dali.dashuyun.cn/Article/details/gteioweitm.html

[H07] 断言
来源：http://dali.ybcxt.top/Article/details/gtadbbhvrg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnqzz.top/Article/details/gtlphrvenk.html

PHP:  assert($x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtnrjvihhm.html

JS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtdgooszpi.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtfxbpktbg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gtyorgzohq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.feifeiyinyue.top/Article/details/gtwnvkbgdw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.svipenyu.cn/Article/details/gtedyuxird.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtkhulawsx.html

[H08] 获取错误信息与堆栈
来源：http://dali.smart0.xyz/Article/details/gtyxygdqav.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.dianchejie.cn/Article/details/gtztiljryl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.iojbl.cn/Article/details/gtvdccqynd.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gtmvbvgwsj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.andypj.xyz/Article/details/gtmusxtqoh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gtmobvlkvg.html

Go:   err.Error()
来源：http://dali.yueranfly.top/Article/details/gtxdpczioq.html

Ruby: e.message;  e.backtrace
来源：http://dali.jlsjyb.cn/Article/details/gtjqqnoqzo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigufen.top/Article/details/gtwfncaqvi.html

[H09] 带错误码的异常
来源：http://dali.zhongyouzk.top/Article/details/gttcaznnqf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hfpthk.cn/Article/details/gtywbpojzk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgfzy.top/Article/details/gtffqtujuy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tianlin.xyz/Article/details/gttkhlisyp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yanxiufei.cn/Article/details/gtojbfgdfy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.havefunace.top/Article/details/gtdhxpxaek.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daria6918.cn/Article/details/gtodevqbux.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gtewdbgzlo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shangyingyoupin.top/Article/details/gtcnwqjkne.html

[H10] 资源自动释放
来源：http://dali.chenlongwang.top/Article/details/gtomqllbun.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gteoowawfq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gtnocxcqfl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gtjqfyqsqt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtidvdlqed.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hysaishi.cn/Article/details/gtvsmqphwi.html

Go:   defer f.Close()
来源：http://dali.tanke756.top/Article/details/gtvvkmcskb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shangyingyoupin.top/Article/details/gtebpukcts.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.bjfxy.top/Article/details/gthwftagxc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtbeeitphz.html

I. 正则表达式
来源：http://dali.ybcxt.top/Article/details/gtvsslcghx.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtuvowhmdn.html

[I01] 判断是否匹配
来源：http://dali.yj202588.top/Article/details/gttvjjdwae.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvvmbsbh.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtijxcnjqa.html

JS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gtlofngwxe.html

TS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gthnmqhaub.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guowangkeji.top/Article/details/gtcevzhvko.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.snrcjt.cn/Article/details/gtkxvtuojc.html

Ruby: s.match?(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gtdxbbztqe.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ivvv.top/Article/details/gtlyxokbfh.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gtvjyvdaqv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevartdpx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.havefunace.top/Article/details/gtbdymdnby.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xylfe.cn/Article/details/gtdzacpnzq.html

TS:   s.match(/\d+/g)
来源：http://dali.gogol.net.cn/Article/details/gtsilrpeux.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dashuyun.cn/Article/details/gtxpxvxwuz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtlkbqvjbm.html

Ruby: s.scan(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gtoieohgzh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtepjuxnrc.html

[I03] 提取捕获分组
来源：http://dali.wangshuangyany.cn/Article/details/gtnohphgaf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuxming.cn/Article/details/gtdicexzzx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tianlin.xyz/Article/details/gtpscqcgfb.html


<!-- 参考信息 -->