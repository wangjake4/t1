代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gttqgfsxjz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtuypmzitc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jiagoushi.top/Article/details/gttlzokite.html

Ruby: File.size("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtmslshkbu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.haohaochexian.top/Article/details/gtvnpsukhd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.snrcjt.cn/Article/details/gtfbsdcmjf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtqnpwevsh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnxebjdi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtnjtsautz.html

TS:   path.extname("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtkvqnoefb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hywenlv.cn/Article/details/gtommoerml.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtnlwxmfmt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtkscdpytk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtimthivja.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gtonvmccwz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtipsdystd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hysaishi.cn/Article/details/gtbguxgkub.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtmiwzwfot.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gthsjmdrfo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtgeejebvu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cdnleiting.top/Article/details/gtwzxjskpi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtoegtbjdp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuanzhike.top/Article/details/gtftmisxas.html

[F12] CSV 读写
来源：http://dali.quarkkingdee.top/Article/details/gtpviqqsia.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenjidiqi.icu/Article/details/gtcdyzzvas.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aizwys.cn/Article/details/gtxknehhfa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gotoacloud.top/Article/details/gtvwqipvdq.html

TS:   // 同上
来源：http://dali.ybcxt.top/Article/details/gtdxpercws.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xinyue.icu/Article/details/gtemlyxrxs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fzhhl.top/Article/details/gtnknwrdpv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zycfv.cn/Article/details/gtyvujucuy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tian-w.cn/Article/details/gtopktswjq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtkctmgpbn.html

G. 面向对象
来源：http://dali.yangfankeji.com/Article/details/gtduqwkgag.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gteppgikrd.html

[G01] 定义类
来源：http://dali.zhongyouzk.top/Article/details/gtaosoutbf.html

Py:   class User: pass
来源：http://dali.c1oappe.top/Article/details/gtqtfuikmv.html

PHP:  class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexxbdlfe.html

JS:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gtfslguczb.html

TS:   class User { name: string = ""; }
来源：http://dali.shzxlz.cn/Article/details/gtdhbpcaxf.html

Java: class User {}
来源：http://dali.iojbl.cn/Article/details/gtdmivncyy.html

Go:   type User struct { Name string }
来源：http://dali.hfpthk.cn/Article/details/gtxzzuryqq.html

Ruby: class User; end
来源：http://dali.quarkkingdee.top/Article/details/gtqyrzacvl.html

C#:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtfszonece.html

[G02] 构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtgnurpyev.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.snrcjt.cn/Article/details/gtxgidfvdi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gtfmwbprgk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtayasykkd.html

TS:   constructor(public name: string) {}
来源：http://dali.cashguo.top/Article/details/gtgrbhxgsk.html

Java: User(String name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gtnslqxasl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yonumen.top/Article/details/gttkwgatoi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zdqjudy.top/Article/details/gtvynebtil.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtiqroucng.html

[G03] 实例属性
来源：http://dali.hnqzz.top/Article/details/gtyuohftal.html

Py:   self.name = "x"
来源：http://dali.sxryk.cn/Article/details/gtcqwkohqt.html

PHP:  public string $name = "x";
来源：http://dali.daria6918.cn/Article/details/gtajjmryma.html

JS:   this.name = "x";
来源：http://dali.0kj1m.cn/Article/details/gtqscvmbvy.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gthnlgachf.html

Java: private String name;
来源：http://dali.tanke756.top/Article/details/gtqatpueow.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhiwuduotai.top/Article/details/gtsepoitsp.html

Ruby: @name = "x"
来源：http://dali.aizwys.cn/Article/details/gtwhiglypa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtnowlbmcy.html

[G04] 定义方法
来源：http://dali.9152youxi.cn/Article/details/gthifgtmjk.html

Py:   def greet(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gthbifomer.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtityjqjbk.html

JS:   greet() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtqjmrvnte.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtkkxxclyw.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtihtyrvnm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtygtpexww.html

Ruby: def greet; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtprstngcl.html

C#:   public string Greet() => Name;
来源：http://dali.tian-w.cn/Article/details/gtjxgnzncx.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gtaqzdnogx.html

Py:   class Admin(User): pass
来源：http://dali.xylfe.cn/Article/details/gtyawpkybn.html

PHP:  class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtpjaydthg.html

JS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtsaofoafw.html

TS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtmctjfezh.html

Java: class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gtpbkbmyhd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gtaxmmlhbj.html

Ruby: class Admin < User; end
来源：http://dali.jianghu66.top/Article/details/gtxxmpxdnm.html

C#:   class Admin : User {}
来源：http://dali.tanke756.top/Article/details/gtfygjurjv.html

[G06] 重写方法
来源：http://dali.yj20258.top/Article/details/gtleghdsxu.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gtcffhzcpl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtabutpskd.html

JS:   greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtodahgfus.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtkoamlcmr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnwlfpawx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ivvv.top/Article/details/gtlfdaqdjf.html

Ruby: def greet; "admin"; end
来源：http://dali.dashuyun.cn/Article/details/gtzkljzfow.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gtvzkijeba.html

[G07] 调用父类方法
来源：http://dali.sufxvd.cn/Article/details/gthfsrdohg.html

Py:   super().greet()
来源：http://dali.316326.xyz/Article/details/gtkbigskfk.html

PHP:  parent::greet();
来源：http://dali.yangfankeji.com/Article/details/gtxqtjjubr.html

JS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gtxwammbfe.html

TS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtkwplnrjh.html

Java: super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtshzpbuhu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gtzgbdldif.html

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gtrhbzkhbf.html

C#:   base.Greet();
来源：http://dali.fengsongda.top/Article/details/gtanyddgqm.html

[G08] 静态方法与属性
来源：http://dali.yj20258888.top/Article/details/gtvfppafxm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinghuilouyu.cn/Article/details/gthfongsbn.html

PHP:  public static function f() {}
来源：http://dali.dianchejie.cn/Article/details/gtbmczclac.html

JS:   static f() {}
来源：http://dali.ivvv.top/Article/details/gtkodcgtxb.html

TS:   static f(): void {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtilurrput.html

Java: static void f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gttucpeaap.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gtpfdhzevb.html

Ruby: def self.f; end
来源：http://dali.jinqigufen.top/Article/details/gtsbypaxjv.html

C#:   public static void F() {}
来源：http://dali.sweek.top/Article/details/gtbzsvjfmx.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gtyhpctiel.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jlsjyb.cn/Article/details/gtgqwrzuwx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yvedp.cn/Article/details/gtiovujbrp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gtmimfsxxg.html

TS:   interface Shape { area(): number; }
来源：http://dali.guowangkeji.top/Article/details/gtavyxkdbr.html

Java: interface Shape { double area(); }
来源：http://dali.shuidangran.top/Article/details/gttuxijoco.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xinyue.icu/Article/details/gtfepelmrd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gtgzkiyedk.html

C#:   interface IShape { double Area(); }
来源：http://dali.dashuyun.cn/Article/details/gtsthnlkqe.html

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gtgfltgkog.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgijeknh.html

PHP:  public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtzjwtzscf.html

JS:   #private 字段；其余公开
来源：http://dali.guannengcc.top/Article/details/gtrdifrhss.html

TS:   public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtgppcqlor.html

Java: public / protected / private / 默认包级
来源：http://dali.cucudq.cn/Article/details/gtbdhfzuoy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhixingplan.top/Article/details/gtqpomxrgm.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtoigtuxzf.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gtzdndoqnb.html

[G11] getter / setter
来源：http://dali.xziqi.cn/Article/details/gtfumkiizp.html

Py:   @property 与 @x.setter
来源：http://dali.ybcxt.top/Article/details/gtadgnurrk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnmaytvm.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtkigxigkq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gtegatwwtm.html

Java: public String getName() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtmseajhbr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtnsgjrhmk.html

Ruby: attr_accessor :name
来源：http://dali.xuetiantiany.cn/Article/details/gtzjjwqvvj.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gtziwplypv.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtrcxdvuhu.html

Py:   def __str__(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gttirkmyux.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtaffmqmzh.html

JS:   toString() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtahqbmiii.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvqfgpjss.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtombkiwet.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtaxrhdnxs.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtpjrlhivc.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtzjhtanrn.html

[G13] 判断对象类型
来源：http://dali.birdmap.top/Article/details/gtpkrkhdae.html

Py:   isinstance(u, User)
来源：http://dali.sweek.top/Article/details/gtnooglnyi.html

PHP:  $u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtyqnqalfm.html

JS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxstwnub.html

TS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gticywzhkj.html

Java: u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtkocmtptn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hywenlv.cn/Article/details/gtzuytgnjj.html

Ruby: u.is_a?(User)
来源：http://dali.yuanzhike.top/Article/details/gtiodxybbv.html

C#:   u is User
来源：http://dali.shuidangran.top/Article/details/gtaqrjaydp.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gtizsyxpoc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fzhhl.top/Article/details/gtfgmqetpk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258.top/Article/details/gtrxnarvlb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtmythzk.html

TS:   type User = { name: string; age: number };
来源：http://dali.quarkkingdee.top/Article/details/gttgrlzjpj.html

Java: record User(String name, int age) {}
来源：http://dali.zhongyouzk.top/Article/details/gtkwvmqhvq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigufen.top/Article/details/gtbgpvdwur.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gotoacloud.top/Article/details/gtfhqcmfmh.html

C#:   record User(string Name, int Age);
来源：http://dali.cdnleiting.top/Article/details/gtngslnpab.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gtyekvugqq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aizwys.cn/Article/details/gteepfflfr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sysykeji.top/Article/details/gtkwovpzlt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guowangkeji.top/Article/details/gtnvvqlnqw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gtsycmanws.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gtznkjcjhh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.bjfxy.top/Article/details/gtoittdaja.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yueranfly.top/Article/details/gtioeqspow.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtuzseesax.html

[G16] 对象转数组 / 字典
来源：http://dali.hammf.cn/Article/details/gteyukahmq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jiagoushi.top/Article/details/gtvdovslui.html

PHP:  get_object_vars($obj);
来源：http://dali.zdqjudy.top/Article/details/gtaafiwpiw.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtyivnevik.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtatdehigm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.quarkkingdee.top/Article/details/gtbmbwzxit.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigufen.top/Article/details/gtmjjqqupe.html

Ruby: obj.instance_variables
来源：http://dali.nwbrower.top/Article/details/gtvnkfueho.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gtgysagrsr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtgkysuobv.html

H. 异常与错误处理
来源：http://dali.gzhubu.top/Article/details/gtvkzaxkfe.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtndohvqee.html

[H01] try / catch 基础
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydiwmclr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gtpeskjbyg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gthrzugkno.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtqrzwgewf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtmamqvmue.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hammf.cn/Article/details/gtbybwnfpl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.birdmap.top/Article/details/gthjqtfhxn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gzhubu.top/Article/details/gtcbhxcaph.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gtcertovwy.html

[H02] finally / ensure 收尾
来源：http://dali.jqgufenzy.top/Article/details/gtvjwvjycx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fengsongda.top/Article/details/gtcqgxntfr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtofmfuqed.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtgotubvvn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtfmyvusmg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtmiommhdq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtyjfmrc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cdnleiting.top/Article/details/gtgzspgwlp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtotgsqpjl.html

[H03] 主动抛出异常
来源：http://dali.havefunace.top/Article/details/gtxqhyfetz.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258.top/Article/details/gtctzvvoub.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtgbkgnylz.html

JS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtevmljcge.html

TS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtyxvhnrnx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtmtdatuzq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuanzhike.top/Article/details/gtswalbhrp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yonumen.top/Article/details/gtbzhmgeec.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gthxppmxwy.html

[H04] 自定义异常类型
来源：http://dali.zycfv.cn/Article/details/gtetdrcdko.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxinkj.top/Article/details/gtizydjpkg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gtnihyahjd.html

JS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gtknkaccyu.html

TS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gthkxlaraw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtoxwxjtil.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gtditgihnf.html

Ruby: class MyError < StandardError; end
来源：http://dali.zycfv.cn/Article/details/gtepqebxyh.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmeamdnhr.html

[H05] 捕获特定类型
来源：http://dali.chenlongwang.top/Article/details/gtskcergdu.html

Py:   except ValueError as e:
来源：http://dali.mhx1999.top/Article/details/gtqnjuxqhb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhoulong.xyz/Article/details/gtvbadoxnc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gtjtpgfzxc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtgrucrjpp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuetiantiany.cn/Article/details/gttojdegky.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.meibo888.top/Article/details/gtmyfpghml.html

Ruby: rescue ArgumentError => e
来源：http://dali.ybcxt.top/Article/details/gtcazvwslv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifhcxepc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cashguo.top/Article/details/gtnrlhlfsx.html

Py:   value = d.get("k") or default
来源：http://dali.sufxvd.cn/Article/details/gtbdwuxgxw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtwtpprxej.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gtdrrfakqf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtkgtgensm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sxryk.cn/Article/details/gtqhswwipk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gtyfendewc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.iojbl.cn/Article/details/gterovcpvl.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gtcdcxrnxd.html

[H07] 断言
来源：http://dali.zycfv.cn/Article/details/gtcopdeewz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.feifeiyinyue.top/Article/details/gtntjlgula.html

PHP:  assert($x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtpdpyictk.html

JS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtgkebkyri.html

TS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtmhgcjujb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gogol.net.cn/Article/details/gtachiopte.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yvedp.cn/Article/details/gtapokxrkh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aizwys.cn/Article/details/gtyanknjze.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtxsqgbtva.html

[H08] 获取错误信息与堆栈
来源：http://dali.quarkkingdee.top/Article/details/gtntjjngfg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhoulong.xyz/Article/details/gtsvopusja.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gtkjotrdhu.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gtkznlefow.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhoulong.xyz/Article/details/gtuavbzqwq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shuidangran.top/Article/details/gtjljohisp.html

Go:   err.Error()
来源：http://dali.wangshuangyany.cn/Article/details/gtzfsimzuo.html

Ruby: e.message;  e.backtrace
来源：http://dali.redwolf501.top/Article/details/gtauaxynyy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gtnsduneqe.html

[H09] 带错误码的异常
来源：http://dali.redwolf501.top/Article/details/gtamapmyzb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shangyingyoupin.top/Article/details/gtnogwbnyq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgfzy.top/Article/details/gtaszngkru.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sufxvd.cn/Article/details/gtxnvnrnnp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dianchejie.cn/Article/details/gtdwomwavt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ybcxt.top/Article/details/gtaxcuxnmy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gtzdagozha.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.birdmap.top/Article/details/gtmltnpncj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gtpveenqbs.html

[H10] 资源自动释放
来源：http://dali.zdqjudy.top/Article/details/gtvhsnszyq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gtvfpzndmn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.chenzaomai.com/Article/details/gtmzpgzegk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gtgbannyuv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gtwcfhcvoo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.guannengcc.top/Article/details/gtgkcggowp.html

Go:   defer f.Close()
来源：http://dali.sysykeji.top/Article/details/gtckstfrpr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gtciunouom.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtqepcblrc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtpgechhzn.html

I. 正则表达式
来源：http://dali.0kj1m.cn/Article/details/gteqizfwcb.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtclueyjph.html

[I01] 判断是否匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtvvqrjkxl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gaohongyu789.top/Article/details/gtlcoiikzv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sxryk.cn/Article/details/gtknyyrqfc.html

JS:   /\d+/.test(s)
来源：http://dali.wangdashe.top/Article/details/gtbepqyiuk.html

TS:   /\d+/.test(s)
来源：http://dali.aizwys.cn/Article/details/gtxjhemshj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jianghu66.top/Article/details/gtugpvvpzs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yvedp.cn/Article/details/gtoyoiuxqv.html

Ruby: s.match?(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gtggzosuvg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yanxiufei.cn/Article/details/gtwemojquw.html

[I02] 提取所有匹配
来源：http://dali.jinqigfzy.top/Article/details/gtchxkadoj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jyoumei.cn/Article/details/gtfxhofqka.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.dashuyun.cn/Article/details/gtjimjprca.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gtrzeedhpu.html

TS:   s.match(/\d+/g)
来源：http://dali.chenlongwang.top/Article/details/gtpezlmacu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.redwolf501.top/Article/details/gtcsgjjlrb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtmqxhebwu.html

Ruby: s.scan(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gtwawhokld.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yueranfly.top/Article/details/gtgtnhluty.html

[I03] 提取捕获分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwfzzwmg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.meibo888.top/Article/details/gtbkgocbou.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tianlin.xyz/Article/details/gtljgzdhtp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.bjfxy.top/Article/details/gtkyliltaz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gtnjkfqbbn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgfzy.top/Article/details/gtrflgjjtl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shangyingyoupin.top/Article/details/gtxoazuldd.html


<!-- 参考信息 -->