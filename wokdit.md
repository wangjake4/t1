代发 wailian999

[F09] 获取文件大小
来源：http://dali.tanke756.top/Article/details/gtloaghhhp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtpdxljljo.html

PHP:  filesize("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtverrhuvv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtsfmlkleo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtsfrvtvjc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gttxbhuabr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258.top/Article/details/gtiwfijqpo.html

Ruby: File.size("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtvlfaadrr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.bjfxy.top/Article/details/gtvmchaafy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhoulong.xyz/Article/details/gtdgepjaqh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtbfcdulwi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtlvnvikbh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtgwatckww.html

TS:   path.extname("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtdqcfechp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gtrxbzmqqh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtvtmhujea.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtcbmkxurp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtllykdofw.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gtdpesjuvx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtjoghuweb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jyoumei.cn/Article/details/gtuecznvjv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtdlnqjmvc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtfdbzpblh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.bjfxy.top/Article/details/gttynvyrry.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zycfv.cn/Article/details/gtlypdkfos.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtojjjnrgn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cdnleiting.top/Article/details/gtlahpfldp.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gtrmhhcncl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gtttpqlwss.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhengqikj.top/Article/details/gtnvduqsxk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jiagoushi.top/Article/details/gtxvkvzwbo.html

TS:   // 同上
来源：http://dali.zhengqikj.top/Article/details/gtyuhasqks.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tian-w.cn/Article/details/gttqhcespq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yueranfly.top/Article/details/gttjquufod.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxuanxn.top/Article/details/gtjzzkjlpa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangdashe.top/Article/details/gtissoykll.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpuxoyuay.html

G. 面向对象
来源：http://dali.316326.xyz/Article/details/gtmpjyqiwm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtouukfrkk.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gtmzafranp.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gtjilvjkaj.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtaenrxxnd.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gticchoqag.html

TS:   class User { name: string = ""; }
来源：http://dali.guowangkeji.top/Article/details/gtvbtcylhu.html

Java: class User {}
来源：http://dali.cdnleiting.top/Article/details/gtqszioyxw.html

Go:   type User struct { Name string }
来源：http://dali.hywenlv.cn/Article/details/gthmyngiyb.html

Ruby: class User; end
来源：http://dali.andypj.xyz/Article/details/gtiekbnicf.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtincqhxyi.html

[G02] 构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtydjejplp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdgostoe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cashguo.top/Article/details/gtifexufab.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gtazqtambj.html

TS:   constructor(public name: string) {}
来源：http://dali.hnxiangtu.top/Article/details/gteagfbcpm.html

Java: User(String name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtskwltgmo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangdashe.top/Article/details/gtfpvposah.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gtacahzkmn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtawbmzgcg.html

[G03] 实例属性
来源：http://dali.9152youxi.cn/Article/details/gtancevevh.html

Py:   self.name = "x"
来源：http://dali.wangdashe.top/Article/details/gtiuprbqdu.html

PHP:  public string $name = "x";
来源：http://dali.cheryme.top/Article/details/gtlmizlive.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gtvhuqzmju.html

TS:   name: string = "x";
来源：http://dali.hnqzz.top/Article/details/gtzvyznonh.html

Java: private String name;
来源：http://dali.zhoulong.xyz/Article/details/gtuxfqmugu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gtfmijnqxe.html

Ruby: @name = "x"
来源：http://dali.ybcxt.top/Article/details/gtxpcjrytg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.mhx1999.top/Article/details/gtgcpnjqxe.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gtrauewwap.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gthgkiakeo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtgcfkehjy.html

JS:   greet() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtxsxzlckf.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtnanmcenz.html

Java: String greet() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggheuslc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtasdncirm.html

Ruby: def greet; @name; end
来源：http://dali.sxryk.cn/Article/details/gtzllonipc.html

C#:   public string Greet() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gtudfydydp.html

[G05] 继承
来源：http://dali.fengsongda.top/Article/details/gtrtyabsxu.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gtxxhhkjza.html

PHP:  class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtohkckrzo.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtoqauuixo.html

TS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtgwvwbdep.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtqhjizbze.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hysaishi.cn/Article/details/gtjkpmaamc.html

Ruby: class Admin < User; end
来源：http://dali.aizwys.cn/Article/details/gtnxtjfavu.html

C#:   class Admin : User {}
来源：http://dali.sweek.top/Article/details/gtvflwkhvo.html

[G06] 重写方法
来源：http://dali.316326.xyz/Article/details/gtsdynaklo.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gtvidrqidx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtqivoivud.html

JS:   greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtloxlhssh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtetcflmol.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtiqxuxzrx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gtrcrpfzer.html

Ruby: def greet; "admin"; end
来源：http://dali.hywenlv.cn/Article/details/gtitxxmjru.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gthtggeccz.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gtisnjvxlw.html

Py:   super().greet()
来源：http://dali.yongpay.top/Article/details/gtwuqjtoth.html

PHP:  parent::greet();
来源：http://dali.0kj1m.cn/Article/details/gtdohgulig.html

JS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtvtndpeps.html

TS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtxebxkebj.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtyxkwtthk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtyslbdr.html

Ruby: super
来源：http://dali.dianchejie.cn/Article/details/gtpfttuava.html

C#:   base.Greet();
来源：http://dali.cucudq.cn/Article/details/gttfswbnmi.html

[G08] 静态方法与属性
来源：http://dali.yj202588.top/Article/details/gtccfttuae.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gtuoatbknl.html

PHP:  public static function f() {}
来源：http://dali.shuidangran.top/Article/details/gtayyllvre.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gtdteibqym.html

TS:   static f(): void {}
来源：http://dali.ydzc1.top/Article/details/gtguvwpqfg.html

Java: static void f() {}
来源：http://dali.ivvv.top/Article/details/gtivylsxex.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gtjknfvxob.html

Ruby: def self.f; end
来源：http://dali.ehwqpu.com/Article/details/gtxwrmocmt.html

C#:   public static void F() {}
来源：http://dali.yj20258888.top/Article/details/gtgtlxihip.html

[G09] 接口 / 抽象类
来源：http://dali.cashguo.top/Article/details/gtgtkgtunh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gtrgliwegp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gtprboxidz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.quarkkingdee.top/Article/details/gtckxjycbg.html

TS:   interface Shape { area(): number; }
来源：http://dali.guowangkeji.top/Article/details/gtamvinfju.html

Java: interface Shape { double area(); }
来源：http://dali.wangdashe.top/Article/details/gtlovbfjld.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenlongwang.top/Article/details/gtayrhglsz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gtdmvjylhk.html

C#:   interface IShape { double Area(); }
来源：http://dali.tianlin.xyz/Article/details/gtmkkqxqwb.html

[G10] 访问控制
来源：http://dali.iojbl.cn/Article/details/gtceupkoqt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cucudq.cn/Article/details/gtduiejrug.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtfohqkosk.html

JS:   #private 字段；其余公开
来源：http://dali.pycfn.com/Article/details/gtevysbddx.html

TS:   public / protected / private
来源：http://dali.yj202588.top/Article/details/gthezfzjng.html

Java: public / protected / private / 默认包级
来源：http://dali.9152youxi.cn/Article/details/gtratyrcsl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tianlin.xyz/Article/details/gteykzbbyr.html

Ruby: public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtrtqzcaws.html

C#:   public / protected / private / internal
来源：http://dali.jianghu66.top/Article/details/gtxjiygqvz.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gtzwmyvnkr.html

Py:   @property 与 @x.setter
来源：http://dali.feifeiyinyue.top/Article/details/gtqvtdviwm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtttwertqj.html

JS:   get name() { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtherecsdo.html

TS:   get name(): string { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gtilbftmzq.html

Java: public String getName() { return name; }
来源：http://dali.gzhubu.top/Article/details/gturahnyku.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtbebncvwv.html

Ruby: attr_accessor :name
来源：http://dali.bjfxy.top/Article/details/gtfwybfgda.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gtubqacmmi.html

[G12] 对象转字符串
来源：http://dali.sxryk.cn/Article/details/gtquqjvnod.html

Py:   def __str__(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gtqvydvbvb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtxfrxrhmy.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtrvttcdkx.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtmzinitmw.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtdgwobpex.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gttkpzfisb.html

Ruby: def to_s; @name; end
来源：http://dali.316326.xyz/Article/details/gtlmgwvncw.html

C#:   public override string ToString() => Name;
来源：http://dali.daxiang520.top/Article/details/gtyrzlgdjj.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gtqhrtwhjh.html

Py:   isinstance(u, User)
来源：http://dali.shuidangran.top/Article/details/gtnnjgrjne.html

PHP:  $u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtjpodyzrw.html

JS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtxrkgdzbz.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtnxcbopou.html

Java: u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtkogmgdjw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gtwczndepo.html

Ruby: u.is_a?(User)
来源：http://dali.jiagoushi.top/Article/details/gtdmceocou.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gtlqxgfraf.html

[G14] 数据类 / record
来源：http://dali.yonumen.top/Article/details/gtlwivwiog.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cdnleiting.top/Article/details/gtegvwclvp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuetiantiany.cn/Article/details/gthvcdnvqc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zdqjudy.top/Article/details/gtdzrsgtzz.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258.top/Article/details/gtgtgezvfx.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigufen.top/Article/details/gtevmxrazc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhixingplan.top/Article/details/gtjehporln.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258888.top/Article/details/gtnsbaigqd.html

C#:   record User(string Name, int Age);
来源：http://dali.pengpengdd.cyou/Article/details/gtnqxrfawq.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtcjaefzou.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aibaodan.cn/Article/details/gtpexwkvfa.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangdashe.top/Article/details/gtzmnpihoh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guannengcc.top/Article/details/gtjkiisdeh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtxdyycszf.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gtfvvseguc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sweek.top/Article/details/gtnmqhmdxw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gtspdymwpa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gtgjyinjlm.html

[G16] 对象转数组 / 字典
来源：http://dali.shzxlz.cn/Article/details/gtgzgxfdnc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guannengcc.top/Article/details/gtsyjjkafu.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gtxfjnbohs.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopikwibd.html

TS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gthhkqxuva.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gogol.net.cn/Article/details/gtncnndext.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tianlin.xyz/Article/details/gtbtqdjege.html

Ruby: obj.instance_variables
来源：http://dali.cqqwz.cn/Article/details/gtuyeyczvd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtsoxhywxr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtmjgwixzv.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gtihsoxzyb.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtjvbzaoda.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gtabqeafpk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jyoumei.cn/Article/details/gtjrdxzbud.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenlongwang.top/Article/details/gtvghgpnfj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtopztlxzx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtpuzrpxfc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhixingplan.top/Article/details/gtjqklpuwu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gtdfwmxfto.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daria6918.cn/Article/details/gtbtrzgdjy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cdnleiting.top/Article/details/gtkjzwjelo.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimoizqdj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jianghu66.top/Article/details/gtghusbzgr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtqbyxtqmo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwomqjdph.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gthjducwyo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtiuonpbxg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fengsongda.top/Article/details/gtttvhmwna.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gtbhlxpahd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtjveykvjm.html

[H03] 主动抛出异常
来源：http://dali.gogol.net.cn/Article/details/gtvbnhhimw.html

Py:   raise ValueError("错误信息")
来源：http://dali.pycfn.com/Article/details/gtkuqugvgo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtxeypbqvq.html

JS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gtpfwezceo.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtnbjxanyz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtozvfglra.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.0kj1m.cn/Article/details/gtsqbeufqa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenzaomai.com/Article/details/gtyaygyskv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtfxbvxsaz.html

[H04] 自定义异常类型
来源：http://dali.ppjwa.cn/Article/details/gtozaqnxrj.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigfzy.top/Article/details/gteonteduw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtiqzrikrn.html

JS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gttculwlal.html

TS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gtdwipyvsd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtkxitshoa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jlsjyb.cn/Article/details/gtncrvzqtp.html

Ruby: class MyError < StandardError; end
来源：http://dali.yongpay.top/Article/details/gtarqiipiy.html

C#:   class MyException : Exception {}
来源：http://dali.zhengqikj.top/Article/details/gtlsqaswlc.html

[H05] 捕获特定类型
来源：http://dali.tianlin.xyz/Article/details/gtnfrsclpp.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gtsbdvkhmk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gtcytpssjn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gtdwninzbz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gtvbstfrhi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.andypj.xyz/Article/details/gtntrgwbcf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jiagoushi.top/Article/details/gthqrdrtfs.html

Ruby: rescue ArgumentError => e
来源：http://dali.daxiang520.top/Article/details/gtrsmuztzd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ydzc1.top/Article/details/gtvleuerkp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tianlin.xyz/Article/details/gtpaytykfx.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gtdeucrhqi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gthhptykap.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtcbgdbljw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gtwmxrjosk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangtech.top/Article/details/gtonoqlodb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shzxlz.cn/Article/details/gtgmblywsz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hywenlv.cn/Article/details/gtnecnuymn.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxinkj.top/Article/details/gtlmhsvtyg.html

[H07] 断言
来源：http://dali.shangyingyoupin.top/Article/details/gthsnolvic.html

Py:   assert x > 0, "必须为正"
来源：http://dali.vqdsnc.cn/Article/details/gthwvzdlee.html

PHP:  assert($x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtsbzvfwwg.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtgmsxhyqz.html

TS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtvaxnpnbr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pycfn.com/Article/details/gtesgxtkvd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhongyouzk.top/Article/details/gtefalgjhn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jyoumei.cn/Article/details/gtbqtqugfw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gthnexkftm.html

[H08] 获取错误信息与堆栈
来源：http://dali.9152youxi.cn/Article/details/gtwimdxdrx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yangfankeji.com/Article/details/gtljcoycwi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangshuangyany.cn/Article/details/gtzzvgvfht.html

JS:   e.message;  e.stack
来源：http://dali.xylfe.cn/Article/details/gtsigepqln.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgufenzy.top/Article/details/gtyxwltizq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gtdhekfvij.html

Go:   err.Error()
来源：http://dali.gogol.net.cn/Article/details/gtyenpfxkw.html

Ruby: e.message;  e.backtrace
来源：http://dali.haohaochexian.top/Article/details/gtrrsjwqip.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gtwjufzjpl.html

[H09] 带错误码的异常
来源：http://dali.jinqigfzy.top/Article/details/gtmgqqddzb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cdnleiting.top/Article/details/gtzkmpxupf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ivvv.top/Article/details/gthaiervju.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gzhubu.top/Article/details/gtlmdwkfdi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.feifeiyinyue.top/Article/details/gtvukubfdo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorvdtaan.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ivvv.top/Article/details/gtpennkdhk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aibaodan.cn/Article/details/gtqulceymw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jianghu66.top/Article/details/gtdrkkvxcc.html

[H10] 资源自动释放
来源：http://dali.daxiang520.top/Article/details/gtuxbzexdc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sufxvd.cn/Article/details/gtfiisrnuw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgufenzy.top/Article/details/gtymwbqocr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gtwdfohzco.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gtoteqjdlz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daxiang520.top/Article/details/gtdqdsnuad.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gtpbigiolv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.fzhhl.top/Article/details/gtkwzkvpjp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtvjsjwipv.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtbifwtgsd.html

I. 正则表达式
来源：http://dali.iojbl.cn/Article/details/gtwfhbtbym.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtwktxhljv.html

[I01] 判断是否匹配
来源：http://dali.jqgfzy.top/Article/details/gtqyutvnev.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daria6918.cn/Article/details/gtanvgskay.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtgmmbxweo.html

JS:   /\d+/.test(s)
来源：http://dali.nwbrower.top/Article/details/gtlafuztei.html

TS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtgnqkkory.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gtgibsicsz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guannengcc.top/Article/details/gtybsnlrqa.html

Ruby: s.match?(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtbaiiaowx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.svipenyu.cn/Article/details/gtfddyqihs.html

[I02] 提取所有匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtovehoytt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gtltrrszsk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.9152youxi.cn/Article/details/gtsrdnzafw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tian-w.cn/Article/details/gtwkytjpmr.html

TS:   s.match(/\d+/g)
来源：http://dali.snrcjt.cn/Article/details/gtvcbchsfd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gtsuxdltra.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gtronwuymi.html

Ruby: s.scan(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gtbuxqdlhc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtguksawyj.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gtlvrzvkkd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xziqi.cn/Article/details/gtamtieiuf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.nanxinkj.top/Article/details/gtgaaerryx.html


<!-- 参考信息 -->