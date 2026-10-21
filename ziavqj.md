代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuetiantiany.cn/Article/details/gtyuqccyip.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shzxlz.cn/Article/details/gtdyiqcsev.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtqsjbkxrn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtjnsjyaqi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtzjkpaxjc.html

TS:   path.extname("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtkftzzbkk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhongyouzk.top/Article/details/gtfowcsohe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtmcouucyv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocmekjcf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtgvqmxagr.html

[F11] 复制与移动文件
来源：http://dali.guowangkeji.top/Article/details/gtoyrdejra.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasjmyfqa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgcvcwgp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtjrqlkubj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtshjyeuiy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gtjwybgono.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gttorsyrub.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtjxchxtxi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ydzc1.top/Article/details/gtfsalbubn.html

[F12] CSV 读写
来源：http://dali.xziqi.cn/Article/details/gtcmmjcbzm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gttwltvavo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.havefunace.top/Article/details/gtlbsdqmty.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jyoumei.cn/Article/details/gtosvafmyr.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gteioxwfaq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cqqwz.cn/Article/details/gtziojeltj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gtlkhtvooh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhiwuduotai.top/Article/details/gtissnaehr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ivvv.top/Article/details/gtbencyhtu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtrzdawuuo.html

G. 面向对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpoyzhyw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtknucqoss.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gtpmfemmpf.html

Py:   class User: pass
来源：http://dali.shzxlz.cn/Article/details/gtmdhrchpn.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gtzqvwhrzt.html

JS:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttggntozk.html

TS:   class User { name: string = ""; }
来源：http://dali.svipenyu.cn/Article/details/gtomxzgnox.html

Java: class User {}
来源：http://dali.pycfn.com/Article/details/gtxcjfsnoi.html

Go:   type User struct { Name string }
来源：http://dali.havefunace.top/Article/details/gtcskfglyy.html

Ruby: class User; end
来源：http://dali.dianchejie.cn/Article/details/gtzcdpolho.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflyqkogs.html

[G02] 构造函数
来源：http://dali.pycfn.com/Article/details/gtggdiydum.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cdnleiting.top/Article/details/gtgtepqziv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhoulong.xyz/Article/details/gtfbyswdld.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gtylpqtyay.html

TS:   constructor(public name: string) {}
来源：http://dali.hammf.cn/Article/details/gtjmckdvsc.html

Java: User(String name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtwkzlofnb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pengpengdd.cyou/Article/details/gtvtquuobv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhengqikj.top/Article/details/gtpqjnctca.html

C#:   public User(string name) { Name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gttaxzyhpo.html

[G03] 实例属性
来源：http://dali.hysaishi.cn/Article/details/gtujiypvqd.html

Py:   self.name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gtmzcpmtrb.html

PHP:  public string $name = "x";
来源：http://dali.aizwys.cn/Article/details/gtlxvfwwci.html

JS:   this.name = "x";
来源：http://dali.cdnleiting.top/Article/details/gterudhxut.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gtsyldmmvt.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gtmhsdrheq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxinkj.top/Article/details/gtczbrnqjf.html

Ruby: @name = "x"
来源：http://dali.birdmap.top/Article/details/gtvqlavxcx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shuidangran.top/Article/details/gtbfmhgnfm.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gtfunnbizk.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtvxxcguyh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkurfuuvw.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtooyfsand.html

TS:   greet(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtporsexjb.html

Java: String greet() { return name; }
来源：http://dali.pycfn.com/Article/details/gtszqpldog.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtomzadzsf.html

Ruby: def greet; @name; end
来源：http://dali.ivvv.top/Article/details/gtvhfjdsdk.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gtbpnabmwx.html

[G05] 继承
来源：http://dali.redwolf501.top/Article/details/gtxurpzeyl.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gtkmkvkhmh.html

PHP:  class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtgnddkvet.html

JS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtymypwawm.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtynaxouam.html

Java: class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gttfppnqkm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.quarkkingdee.top/Article/details/gtnpgxoilr.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gtlerdsnhc.html

C#:   class Admin : User {}
来源：http://dali.iojbl.cn/Article/details/gtcdmxgxki.html

[G06] 重写方法
来源：http://dali.xinyue.icu/Article/details/gtjqlhxdzc.html

Py:   def greet(self): return "admin"
来源：http://dali.ehwqpu.com/Article/details/gtzzhxenpv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtgpemxxrt.html

JS:   greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtkyyoktpf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtuohjegbd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtoffgdqld.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gtrwscnwcy.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gtktyjypuw.html

C#:   public override string Greet() => "admin";
来源：http://dali.kuanghao11.cn/Article/details/gtssxecnrc.html

[G07] 调用父类方法
来源：http://dali.hnxiangtu.top/Article/details/gtlfstgeox.html

Py:   super().greet()
来源：http://dali.xylfe.cn/Article/details/gtvyqkgmga.html

PHP:  parent::greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtbmxkxzxx.html

JS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gttytmkxrk.html

TS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtvoeucwpb.html

Java: super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtayrkujfl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbebipmn.html

Ruby: super
来源：http://dali.hywenlv.cn/Article/details/gtmrsjkehy.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gttbdcdotr.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtafpovpzn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.vqdsnc.cn/Article/details/gtkuophugt.html

PHP:  public static function f() {}
来源：http://dali.yj20258888.top/Article/details/gttphxtwym.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtqxdtyiul.html

TS:   static f(): void {}
来源：http://dali.yj20258.top/Article/details/gticuvrfvk.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gtummzhwal.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guowangkeji.top/Article/details/gtqfedsiem.html

Ruby: def self.f; end
来源：http://dali.xziqi.cn/Article/details/gtjiaoqxag.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gtexkyenmu.html

[G09] 接口 / 抽象类
来源：http://dali.cucudq.cn/Article/details/gthuhyrovz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gtfcpabnti.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jianghu66.top/Article/details/gtdbnntxcf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkggvwngj.html

TS:   interface Shape { area(): number; }
来源：http://dali.dashuyun.cn/Article/details/gtexzgqpmh.html

Java: interface Shape { double area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtakuebdfc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gtoyembmpa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.meibo888.top/Article/details/gtksqvekwl.html

C#:   interface IShape { double Area(); }
来源：http://dali.gotoacloud.top/Article/details/gthhopihls.html

[G10] 访问控制
来源：http://dali.tianlin.xyz/Article/details/gtaajqwdoz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ybcxt.top/Article/details/gtvucxobdj.html

PHP:  public / protected / private
来源：http://dali.hammf.cn/Article/details/gtbknpeepx.html

JS:   #private 字段；其余公开
来源：http://dali.sxryk.cn/Article/details/gtxjoexhbh.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gtnlacdxch.html

Java: public / protected / private / 默认包级
来源：http://dali.sxryk.cn/Article/details/gtnpanlnuf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.c1oappe.top/Article/details/gtvsovnyjh.html

Ruby: public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtvpuxguyo.html

C#:   public / protected / private / internal
来源：http://dali.birdmap.top/Article/details/gtndgsvjbx.html

[G11] getter / setter
来源：http://dali.wangshuangyany.cn/Article/details/gttueujxrk.html

Py:   @property 与 @x.setter
来源：http://dali.andypj.xyz/Article/details/gtsqnzodze.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtelsdhyni.html

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtgusllfmm.html

TS:   get name(): string { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gtrebwuwdj.html

Java: public String getName() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtmhmbftvs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtbzjmwalb.html

Ruby: attr_accessor :name
来源：http://dali.quarkkingdee.top/Article/details/gtilbujubk.html

C#:   public string Name { get; set; }
来源：http://dali.chenlongwang.top/Article/details/gtejqplqxb.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gtcnasroya.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtbunwtiwf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtgoiloslh.html

JS:   toString() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gttxepexjk.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtxflcinpj.html

Java: @Override public String toString() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtuzjigvaz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtkexcvtve.html

Ruby: def to_s; @name; end
来源：http://dali.smart0.xyz/Article/details/gtmfdqexyi.html

C#:   public override string ToString() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtsibnxgpu.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gtqgrhppec.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gtsocviaeq.html

PHP:  $u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtjqgpyrya.html

JS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtlnwzebbk.html

TS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfvqyfmd.html

Java: u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtjvnqlvty.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pengpengdd.cyou/Article/details/gtawjthhrw.html

Ruby: u.is_a?(User)
来源：http://dali.andypj.xyz/Article/details/gtpkxgwbek.html

C#:   u is User
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpdqzihs.html

[G14] 数据类 / record
来源：http://dali.shuidangran.top/Article/details/gtkzsaoeuo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgfzy.top/Article/details/gtpsgrpigd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258888.top/Article/details/gtdjhdwjee.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuxming.cn/Article/details/gtqlishtko.html

TS:   type User = { name: string; age: number };
来源：http://dali.xziqi.cn/Article/details/gtveqcobff.html

Java: record User(String name, int age) {}
来源：http://dali.havefunace.top/Article/details/gtmomvnknb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gtnhrqhqcx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guannengcc.top/Article/details/gtayrfyrzo.html

C#:   record User(string Name, int Age);
来源：http://dali.snrcjt.cn/Article/details/gtfmuydxiu.html

[G15] 枚举
来源：http://dali.dianchejie.cn/Article/details/gtmwmaigpc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenzaomai.com/Article/details/gtihkjywwc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.smart0.xyz/Article/details/gtsajkeilj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shzxlz.cn/Article/details/gtozcpduvt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtbxpcelmz.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuxming.cn/Article/details/gttnpieddp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.c1oappe.top/Article/details/gtvhvqjoyj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gaohongyu789.top/Article/details/gtrtguolrl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtghcuboea.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gtyjdzgzkf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbagdghr.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gtjvypxnmb.html

JS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtbxjglovz.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtdbcuqxeg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gtbxkglihm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guowangkeji.top/Article/details/gtxygxgcev.html

Ruby: obj.instance_variables
来源：http://dali.yueranfly.top/Article/details/gtsisuvwea.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtncoctwqj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtyglvzecq.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gteplcrnnq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtuzgxxsts.html

[H01] try / catch 基础
来源：http://dali.sysykeji.top/Article/details/gtxhnnrvrj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gtuyytvewv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gtpjxkuwbg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtrokjvphn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjqqthgv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sysykeji.top/Article/details/gtcqgsjcyn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daria6918.cn/Article/details/gtbfutsifu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ybcxt.top/Article/details/gtpdrdbhoi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gtzfegswrs.html

[H02] finally / ensure 收尾
来源：http://dali.quarkkingdee.top/Article/details/gtxaqdfjku.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuanzx.com/Article/details/gtuksfkeua.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtyhiixqrk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtletsjyfj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtktrreiaj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtckqkdfzm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shuidangran.top/Article/details/gtbxjxzein.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gtbsqkxskq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtuqeldgqf.html

[H03] 主动抛出异常
来源：http://dali.guowangkeji.top/Article/details/gtecanwnqv.html

Py:   raise ValueError("错误信息")
来源：http://dali.ydzc1.top/Article/details/gtnytuqalv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gttbgpfrwr.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtedgoifzd.html

TS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtpzjvzuyu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtvmtosnti.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuanzhike.top/Article/details/gttqmdhbor.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xylfe.cn/Article/details/gttqnfiqlm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtgmprsdke.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gthaveipoh.html

Py:   class MyError(Exception): pass
来源：http://dali.zhengqikj.top/Article/details/gtxxypezsh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtvtkvfbng.html

JS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtfiurxszl.html

TS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtvwcljojm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtiouhmymk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuetiantiany.cn/Article/details/gtlgnoglvl.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlougxyln.html

C#:   class MyException : Exception {}
来源：http://dali.zdqjudy.top/Article/details/gtjevbiotl.html

[H05] 捕获特定类型
来源：http://dali.gzhubu.top/Article/details/gtbsegyvsg.html

Py:   except ValueError as e:
来源：http://dali.feifeiyinyue.top/Article/details/gtublrqpzr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gtmzlhtevt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtwxjxndax.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtnjixxecp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zycfv.cn/Article/details/gtzxnmevcy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gogol.net.cn/Article/details/gtytvypjja.html

Ruby: rescue ArgumentError => e
来源：http://dali.cucudq.cn/Article/details/gtrfbcftzv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgbobeid.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgfzy.top/Article/details/gttmdenefj.html

Py:   value = d.get("k") or default
来源：http://dali.nwbrower.top/Article/details/gtmwmwxsbx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtnhncqksm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gtngvdrwva.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gthvanowzm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gttkwfiugr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yvedp.cn/Article/details/gtvxuwpyzc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmowugrs.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynrrdkjo.html

[H07] 断言
来源：http://dali.nanxuanxn.top/Article/details/gtdxzyluts.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yangfankeji.com/Article/details/gtcorsuquf.html

PHP:  assert($x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtyogboyku.html

JS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtkzixrajw.html

TS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqgbftav.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenjidiqi.icu/Article/details/gtmqhatsde.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shzxlz.cn/Article/details/gtcgcaezzb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenlongwang.top/Article/details/gtflpsgngc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtsfgrnkde.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigufen.top/Article/details/gtloajzpxx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sysykeji.top/Article/details/gtarpsubde.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangshuangyany.cn/Article/details/gthwgcjnvm.html

JS:   e.message;  e.stack
来源：http://dali.xziqi.cn/Article/details/gtyarcwjga.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.0kj1m.cn/Article/details/gtchjufcbw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenjidiqi.icu/Article/details/gtioztlznp.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gtstzfgzkj.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gtpuywfzof.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hywenlv.cn/Article/details/gtiedqkwul.html

[H09] 带错误码的异常
来源：http://dali.kuanghao11.cn/Article/details/gtpwqapgub.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuirjovad.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zycfv.cn/Article/details/gtolcbkdrx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cdnleiting.top/Article/details/gtfvcgowao.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jianghu66.top/Article/details/gtogimygho.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shzxlz.cn/Article/details/gtdhbsfqry.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pengpengdd.cyou/Article/details/gtxtsdlvap.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgufenzy.top/Article/details/gtvfcvyicr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gtftquuawt.html

[H10] 资源自动释放
来源：http://dali.hnxiangtu.top/Article/details/gthsvsjheu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gtyyppnqft.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgfzy.top/Article/details/gtkacxepbx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtogzmsneq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gtraasdsiv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ybcxt.top/Article/details/gtirynmdrh.html

Go:   defer f.Close()
来源：http://dali.xuanzx.com/Article/details/gtidrgatrp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiguivcgm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.havefunace.top/Article/details/gtsrmncnsp.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtxcoatkjt.html

I. 正则表达式
来源：http://dali.yuanzhike.top/Article/details/gtbqzyzyxj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtxkbytapl.html

[I01] 判断是否匹配
来源：http://dali.cucudq.cn/Article/details/gtwhjuhtaz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gtbesjumas.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtvcyrmtvs.html

JS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gtbxavuaxm.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqhmbycq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yueranfly.top/Article/details/gtbytlmooq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.kuanghao11.cn/Article/details/gttmdlcesc.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuizhpbzv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.aibaodan.cn/Article/details/gtqttnakzz.html

[I02] 提取所有匹配
来源：http://dali.zhijiandao.cn/Article/details/gtvifzwxvn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.bjfxy.top/Article/details/gttfmhvtaq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtedrapl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yonumen.top/Article/details/gtcyfbxuca.html

TS:   s.match(/\d+/g)
来源：http://dali.haohaochexian.top/Article/details/gtalulwtlg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gteuwkkpir.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jiagoushi.top/Article/details/gtsyiqkpar.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gtrjajvrzk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.smart0.xyz/Article/details/gtapqebuhh.html

[I03] 提取捕获分组
来源：http://dali.yj20258.top/Article/details/gtzsiuxuod.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hfpthk.cn/Article/details/gtrncwusuu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.smart0.xyz/Article/details/gtlnaufklq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yangfankeji.com/Article/details/gtgabidpap.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.haohaochexian.top/Article/details/gtszojufhj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yangfankeji.com/Article/details/gtcfsxlskr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gtpefhstgs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jiagoushi.top/Article/details/gtrbcamsrz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tian-w.cn/Article/details/gtruucmirl.html

[I04] 正则替换
来源：http://dali.daxiang520.top/Article/details/gtpapbiybo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtmkqbgaxv.html


<!-- 参考信息 -->