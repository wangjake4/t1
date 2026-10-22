代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gt2iiyqnflh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gt2eupkudhs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2lypwsdjx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2vqnsfelf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2beixewcl.html

TS:   path.extname("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2gudwjgog.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenjidiqi.icu/Article/details/gt2reipjdoo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2twlcnjgj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nppfcnae.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2rdrdlbkr.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gt2sozphahv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gt2ikhobwda.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.smart0.xyz/Article/details/gt2gtfpsrop.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2tubhprrl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gt2qmnkskgz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cdnleiting.top/Article/details/gt2xohnuhxh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daria6918.cn/Article/details/gt2jertfqeu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gvutdekz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gzhubu.top/Article/details/gt2jqhoiama.html

[F12] CSV 读写
来源：http://dali.pycfn.com/Article/details/gt2gcrfyigh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhiwuduotai.top/Article/details/gt2turzqokl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxuanxn.top/Article/details/gt2ivszxaby.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.meibo888.top/Article/details/gt2mgcetlua.html

TS:   // 同上
来源：http://dali.316326.xyz/Article/details/gt2kbwotmoa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gt2ukerhynn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gt2fhasnkpz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hongshengwenyu.top/Article/details/gt2wxlytolw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gt2fwwmdhlx.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vycxckai.html

G. 面向对象
来源：http://dali.hammf.cn/Article/details/gt2udpgbyce.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfhnzop.html

[G01] 定义类
来源：http://dali.cqqwz.cn/Article/details/gt2bqcrsjgd.html

Py:   class User: pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2srcrrncy.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ahdmywkq.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2mqabvmki.html

TS:   class User { name: string = ""; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xfopvnrj.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gt2mthxvowk.html

Go:   type User struct { Name string }
来源：http://dali.smart0.xyz/Article/details/gt2aphohqeg.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gt2azgdsbfi.html

C#:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2rfeztpvd.html

[G02] 构造函数
来源：http://dali.quarkkingdee.top/Article/details/gt2ovluxzwr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gt2bhyjmwaz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258888.top/Article/details/gt2esqozvvs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gt2zvinpmyr.html

TS:   constructor(public name: string) {}
来源：http://dali.316326.xyz/Article/details/gt2wkcrlbmw.html

Java: User(String name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gt2qomnfzus.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.redwolf501.top/Article/details/gt2jepsydcs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gt2namdnnpa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dianchejie.cn/Article/details/gt2cqhsudiw.html

[G03] 实例属性
来源：http://dali.cqqwz.cn/Article/details/gt2cecqicib.html

Py:   self.name = "x"
来源：http://dali.9152youxi.cn/Article/details/gt2qdqawbxi.html

PHP:  public string $name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2zwoiaban.html

JS:   this.name = "x";
来源：http://dali.redwolf501.top/Article/details/gt2xlioegwq.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2qzilkfoq.html

Java: private String name;
来源：http://dali.jinqigufen.top/Article/details/gt2hfgidkbq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hyexflje.html

Ruby: @name = "x"
来源：http://dali.nanxinkj.top/Article/details/gt2oqtglzyp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sxryk.cn/Article/details/gt2mpanpwxs.html

[G04] 定义方法
来源：http://dali.daxiang520.top/Article/details/gt2moxskvup.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gt2yathwlfk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gt2dkrmltip.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2noxphlck.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gt2unjwiadc.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2ycsfckxg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gt2kpdhljvm.html

Ruby: def greet; @name; end
来源：http://dali.sufxvd.cn/Article/details/gt2bfwjfhip.html

C#:   public string Greet() => Name;
来源：http://dali.jyoumei.cn/Article/details/gt2ypqnznxk.html

[G05] 继承
来源：http://dali.daria6918.cn/Article/details/gt2lxvveqxz.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gt2swrcroez.html

PHP:  class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gt2povcyovq.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2kujbgxhf.html

TS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2thwjkpof.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2tnhqhbys.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pycfn.com/Article/details/gt2xxpvnfle.html

Ruby: class Admin < User; end
来源：http://dali.svipenyu.cn/Article/details/gt2vsnmdeok.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zwcakhpe.html

[G06] 重写方法
来源：http://dali.hammf.cn/Article/details/gt2oicnlpdg.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gt2klpwvjno.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2raqbxhff.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ptqvabvt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gt2lnedjcgh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2mnvxdhak.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gt2nektgdle.html

Ruby: def greet; "admin"; end
来源：http://dali.iojbl.cn/Article/details/gt2upqywzaq.html

C#:   public override string Greet() => "admin";
来源：http://dali.cashguo.top/Article/details/gt2ncafruqh.html

[G07] 调用父类方法
来源：http://dali.meibo888.top/Article/details/gt2wdgqdctc.html

Py:   super().greet()
来源：http://dali.zhiwuduotai.top/Article/details/gt2dnbxpddr.html

PHP:  parent::greet();
来源：http://dali.hysaishi.cn/Article/details/gt2zhdanvjc.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2btxrpljp.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gt2qqzfazcm.html

Java: super.greet();
来源：http://dali.birdmap.top/Article/details/gt2cvutxkot.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oqtrnisn.html

Ruby: super
来源：http://dali.feifeiyinyue.top/Article/details/gt2qreelqkf.html

C#:   base.Greet();
来源：http://dali.0kj1m.cn/Article/details/gt2gojxfald.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zqdiwyec.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sweek.top/Article/details/gt2xdpturnp.html

PHP:  public static function f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2sumfclqx.html

JS:   static f() {}
来源：http://dali.gotoacloud.top/Article/details/gt2odrptous.html

TS:   static f(): void {}
来源：http://dali.jiagoushi.top/Article/details/gt2rhoowvja.html

Java: static void f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2zmmhqipq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gt2rdexokyv.html

Ruby: def self.f; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2anqkacal.html

C#:   public static void F() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2uwlynkrm.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gt2uhghgchq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vimsndnd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.iojbl.cn/Article/details/gt2ydxyxymp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuanzhike.top/Article/details/gt2aevyrbps.html

TS:   interface Shape { area(): number; }
来源：http://dali.vqdsnc.cn/Article/details/gt2cdkphqvl.html

Java: interface Shape { double area(); }
来源：http://dali.shzxlz.cn/Article/details/gt2vhdrgumw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.iojbl.cn/Article/details/gt2znmiexgw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2mksyuems.html

C#:   interface IShape { double Area(); }
来源：http://dali.ydzc1.top/Article/details/gt2rvkgsrfm.html

[G10] 访问控制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2apbpxqae.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.snrcjt.cn/Article/details/gt2cocdesbx.html

PHP:  public / protected / private
来源：http://dali.smart0.xyz/Article/details/gt2mvifmrqn.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imyzrgwk.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2urujcqht.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gt2nkdxlgvx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2yszzqunp.html

Ruby: public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uzjfnigp.html

C#:   public / protected / private / internal
来源：http://dali.yj20258.top/Article/details/gt2gtyauptf.html

[G11] getter / setter
来源：http://dali.iojbl.cn/Article/details/gt2dcwrhmll.html

Py:   @property 与 @x.setter
来源：http://dali.ydzc1.top/Article/details/gt2ofbhpybl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gt2xdukzlhg.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gt2avytvxdy.html

TS:   get name(): string { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gt2vrdsbqay.html

Java: public String getName() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2jhadonne.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pyjjyyou.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gt2cahavgas.html

C#:   public string Name { get; set; }
来源：http://dali.yueranfly.top/Article/details/gt2grrxkyby.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ljvvohek.html

Py:   def __str__(self): return self.name
来源：http://dali.sweek.top/Article/details/gt2psebtils.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gt2vsuovoxm.html

JS:   toString() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ejbawiub.html

TS:   toString(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2vkoszccp.html

Java: @Override public String toString() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ezrgfkqp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gt2kljttonm.html

Ruby: def to_s; @name; end
来源：http://dali.jiagoushi.top/Article/details/gt2dumnnaam.html

C#:   public override string ToString() => Name;
来源：http://dali.yvedp.cn/Article/details/gt2yfiglvra.html

[G13] 判断对象类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zfycllry.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gt2htlkyyym.html

PHP:  $u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gt2vzgkxsyc.html

JS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2onapizsj.html

TS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gt2gymkudvc.html

Java: u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2musrprdi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.meibo888.top/Article/details/gt2lfpujbhh.html

Ruby: u.is_a?(User)
来源：http://dali.jlsjyb.cn/Article/details/gt2jhijugxq.html

C#:   u is User
来源：http://dali.xylfe.cn/Article/details/gt2cxmbtegn.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gt2axczyehd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aibaodan.cn/Article/details/gt2qfchmwfq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.havefunace.top/Article/details/gt2ymczmhdy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gt2dxyvxrel.html

TS:   type User = { name: string; age: number };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2enpuhxik.html

Java: record User(String name, int age) {}
来源：http://dali.jyoumei.cn/Article/details/gt2uczrewue.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sysykeji.top/Article/details/gt2rxlfuehb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daria6918.cn/Article/details/gt2tykylikp.html

C#:   record User(string Name, int Age);
来源：http://dali.zdqjudy.top/Article/details/gt2tmrxtvos.html

[G15] 枚举
来源：http://dali.dashuyun.cn/Article/details/gt2fwcpjgrt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gt2ttmzdabi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gt2oxlneujd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2azgvqdzu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ameoqrbr.html

Java: enum Color { RED, GREEN }
来源：http://dali.yonumen.top/Article/details/gt2cuqychsq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sufxvd.cn/Article/details/gt2zyzcjojk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gt2oeuprdaj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gt2btvvbfjs.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gt2izvepqyp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gt2gysrhalh.html

PHP:  get_object_vars($obj);
来源：http://dali.fzhhl.top/Article/details/gt2cvcdndmb.html

JS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2ymltocwd.html

TS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2cbucuypm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigfzy.top/Article/details/gt2qkfrqvhv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.meibo888.top/Article/details/gt2cpbojkle.html

Ruby: obj.instance_variables
来源：http://dali.yongpay.top/Article/details/gt2ruvswwuw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2alegcrae.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2paemvpyb.html

H. 异常与错误处理
来源：http://dali.iojbl.cn/Article/details/gt2ppmxsabj.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2mnghfwgn.html

[H01] try / catch 基础
来源：http://dali.fengsongda.top/Article/details/gt2qtqfabgd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gogol.net.cn/Article/details/gt2qypkpfsg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xziqi.cn/Article/details/gt2xaxqxmvx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gt2rqhjbjdh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gt2bxizwygb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hnqzz.top/Article/details/gt2eliqiazb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pycfn.com/Article/details/gt2iogknigi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yvedp.cn/Article/details/gt2ameniqug.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cucudq.cn/Article/details/gt2slcqagzd.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxkptzbp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gt2ispualgd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2pxkqbdzo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2otirealw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2yzgszzso.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2rqdvdafv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xskdexvz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gt2deyajkvf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2calqouny.html

[H03] 主动抛出异常
来源：http://dali.sxryk.cn/Article/details/gt2cnswhoxa.html

Py:   raise ValueError("错误信息")
来源：http://dali.xziqi.cn/Article/details/gt2eqaifmhn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2abwejuai.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2gwsjring.html

TS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2ylblnolb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2mukrxjcn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2layjksgm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.snrcjt.cn/Article/details/gt2opxvzixm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wijkcevw.html

[H04] 自定义异常类型
来源：http://dali.9152youxi.cn/Article/details/gt2rbzcacxe.html

Py:   class MyError(Exception): pass
来源：http://dali.316326.xyz/Article/details/gt2mdvytqvt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wvonbspa.html

JS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gt2raibyxde.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2euxufixr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gt2ilvpdhuq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yanxiufei.cn/Article/details/gt2jzgxkqok.html

Ruby: class MyError < StandardError; end
来源：http://dali.dianchejie.cn/Article/details/gt2ixewxznz.html

C#:   class MyException : Exception {}
来源：http://dali.vqdsnc.cn/Article/details/gt2memdmbfr.html

[H05] 捕获特定类型
来源：http://dali.hfpthk.cn/Article/details/gt2tggfjitk.html

Py:   except ValueError as e:
来源：http://dali.daxiang520.top/Article/details/gt2lefbihfd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.bjfxy.top/Article/details/gt2rftkqwxf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldilshew.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gt2rodgqkbd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2sevugdyw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pycfn.com/Article/details/gt2rwagkkyz.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258888.top/Article/details/gt2arrzwmgf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gt2xkkksqeq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dianchejie.cn/Article/details/gt2tfmqlhmp.html

Py:   value = d.get("k") or default
来源：http://dali.xinyue.icu/Article/details/gt2vdbxfbcc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gt2leqhxgcy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gt2rfdaawnk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gt2sxqfdkae.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gzhubu.top/Article/details/gt2qpdzdkmt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tanke756.top/Article/details/gt2qwucfxty.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guowangkeji.top/Article/details/gt2ljijehqu.html

C#:   obj?.A?.B ?? default
来源：http://dali.cheryme.top/Article/details/gt2itaaywse.html

[H07] 断言
来源：http://dali.xylfe.cn/Article/details/gt2ebfmlpmc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sufxvd.cn/Article/details/gt2wcnptctx.html

PHP:  assert($x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2eonferff.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gt2fxgwsose.html

TS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gt2zugqrqpx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sysykeji.top/Article/details/gt2zqdslqqh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dianchejie.cn/Article/details/gt2zkkhmpjc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuanzx.com/Article/details/gt2dwkuzscm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2onoihafo.html

[H08] 获取错误信息与堆栈
来源：http://dali.sxryk.cn/Article/details/gt2fgykjugm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guowangkeji.top/Article/details/gt2mimozaed.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yueranfly.top/Article/details/gt2yrzvjsuv.html

JS:   e.message;  e.stack
来源：http://dali.sweek.top/Article/details/gt2ojpzhfzr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywelggml.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj202588.top/Article/details/gt2jpqteaog.html

Go:   err.Error()
来源：http://dali.zhengqikj.top/Article/details/gt2hgfvqlzl.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gt2iuylctjd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yvedp.cn/Article/details/gt2jugshkok.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gt2mrqctenj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tian-w.cn/Article/details/gt2fhjctmib.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tianlin.xyz/Article/details/gt2vtyuprmk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gt2nvytnjds.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shuidangran.top/Article/details/gt2avurmmop.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cgnosstw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cashguo.top/Article/details/gt2fulxdkjy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.c1oappe.top/Article/details/gt2kaapujim.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.0kj1m.cn/Article/details/gt2pghcnoos.html

[H10] 资源自动释放
来源：http://dali.dashuyun.cn/Article/details/gt2zrpgbwlq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.iojbl.cn/Article/details/gt2vfcpcweb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.0kj1m.cn/Article/details/gt2jtdqqcwj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jzbqpgnk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gt2bgvqckql.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.daria6918.cn/Article/details/gt2snlqhyjs.html

Go:   defer f.Close()
来源：http://dali.zhixingplan.top/Article/details/gt2ejxtzcuo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.quarkkingdee.top/Article/details/gt2qemjgsox.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2biptfbsd.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2tqgebxta.html

I. 正则表达式
来源：http://dali.yanxiufei.cn/Article/details/gt2atssszhz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2fquklwdk.html

[I01] 判断是否匹配
来源：http://dali.jinqigfzy.top/Article/details/gt2kuvrgxon.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwjvabaz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2pkzsvxjd.html

JS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2qcxeucnx.html

TS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gt2pcuyqrni.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj202588.top/Article/details/gt2hgvphnhz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhixingplan.top/Article/details/gt2ttsiknlm.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gt2tqcofbvb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pycfn.com/Article/details/gt2auycjeqb.html

[I02] 提取所有匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2mnjperhy.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vrodhukx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gt2bfvvynzc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2joykrdxu.html

TS:   s.match(/\d+/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vlezawza.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cucudq.cn/Article/details/gt2xbeeebcg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zutovqfw.html

Ruby: s.scan(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gt2hyyuplwa.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2fwdbanqj.html

[I03] 提取捕获分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hmnyycaf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.snrcjt.cn/Article/details/gt2hedwikzj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jianghu66.top/Article/details/gt2hayzpiag.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hnqzz.top/Article/details/gt2cbvrgowf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.svipenyu.cn/Article/details/gt2sizjomxe.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhengqikj.top/Article/details/gt2bqgfxdno.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhoulong.xyz/Article/details/gt2lvdawcil.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hongshengwenyu.top/Article/details/gt2xyimfwqf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.birdmap.top/Article/details/gt2qqqjwpnq.html

[I04] 正则替换
来源：http://dali.havefunace.top/Article/details/gt2bdturymp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gotoacloud.top/Article/details/gt2wyiptiex.html


<!-- 参考信息 -->