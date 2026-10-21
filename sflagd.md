代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.bjfxy.top/Article/details/gtbhcektqt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gtwrnqktfw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gteixlicfn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuxming.cn/Article/details/gtavkdfktz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtctglrbvw.html

TS:   path.extname("a.txt")
来源：http://dali.hammf.cn/Article/details/gtrlpvvior.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.redwolf501.top/Article/details/gtxiohdaab.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtchxwlhxi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtiyvjaepr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtlpnvnuqg.html

[F11] 复制与移动文件
来源：http://dali.fengsongda.top/Article/details/gteqjbqcfx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gthitvbgpl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqkskedv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtcpuruijo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtodxjlbrx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtaprrxlte.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daria6918.cn/Article/details/gtohlwivrq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkvckoql.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjxqkksc.html

[F12] CSV 读写
来源：http://dali.sysykeji.top/Article/details/gtmtinhcqe.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nwbrower.top/Article/details/gtaulsoriy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yangfankeji.com/Article/details/gtldtnpols.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xinyue.icu/Article/details/gtalkmylzn.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gtubupnwdp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jianghu66.top/Article/details/gtyvnmcxpn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuanzhike.top/Article/details/gtzdxkihso.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nwbrower.top/Article/details/gtlmspadcm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtumctofii.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlgbwdbqx.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gtehwolaeq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtdqoeaqoo.html

[G01] 定义类
来源：http://dali.fzhhl.top/Article/details/gtoibbmvte.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gtgzhqytbn.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtxhxfazxd.html

JS:   class User {}
来源：http://dali.xinyue.icu/Article/details/gthpldcvfl.html

TS:   class User { name: string = ""; }
来源：http://dali.sysykeji.top/Article/details/gthqebqqcf.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gtauhrjgco.html

Go:   type User struct { Name string }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygxgomqu.html

Ruby: class User; end
来源：http://dali.zhoulong.xyz/Article/details/gtmgcdjxsb.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyowaajb.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gtcngsmhne.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gtsmxhvfxt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gtiesejukc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtablnkire.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258.top/Article/details/gtjrkitfrt.html

Java: User(String name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gtjfrgkqha.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuxming.cn/Article/details/gtqvxmtbfn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtknrzsfpu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gteaiqdvih.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gtoradhwdh.html

Py:   self.name = "x"
来源：http://dali.xinyue.icu/Article/details/gtpaordoyp.html

PHP:  public string $name = "x";
来源：http://dali.daria6918.cn/Article/details/gtgdmtdfxi.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gtmlqjnexz.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gtasvssguz.html

Java: private String name;
来源：http://dali.redwolf501.top/Article/details/gtbkijstrg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gtxyynvupn.html

Ruby: @name = "x"
来源：http://dali.gzhubu.top/Article/details/gtqscjgahu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.redwolf501.top/Article/details/gtbmwqktnp.html

[G04] 定义方法
来源：http://dali.pycfn.com/Article/details/gtvxtuhdpj.html

Py:   def greet(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gtoipzavgl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtptyskrfn.html

JS:   greet() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtpgpjrhrc.html

TS:   greet(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvyuykspy.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpcprhxe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtqetfqajm.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtgeexwvtz.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gtahxiaxru.html

[G05] 继承
来源：http://dali.zycfv.cn/Article/details/gttwvunkmh.html

Py:   class Admin(User): pass
来源：http://dali.yj20258.top/Article/details/gtwwhqfrlg.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbtypwxtg.html

JS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtahvauhcg.html

TS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtxkjuccti.html

Java: class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtgjgedyae.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenzaomai.com/Article/details/gtqjasjenr.html

Ruby: class Admin < User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtpulmnetc.html

C#:   class Admin : User {}
来源：http://dali.vqdsnc.cn/Article/details/gtasfyhpir.html

[G06] 重写方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmgehvbk.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gtcmpjetzp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtxbfdeukk.html

JS:   greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtlpgfbzle.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gteciycuco.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtkswcxmhb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cashguo.top/Article/details/gtemwtcxwj.html

Ruby: def greet; "admin"; end
来源：http://dali.snrcjt.cn/Article/details/gtppyfsuex.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gtbbdhxjiz.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gtprqewkhq.html

Py:   super().greet()
来源：http://dali.havefunace.top/Article/details/gtubpzemse.html

PHP:  parent::greet();
来源：http://dali.bjfxy.top/Article/details/gtzxrithou.html

JS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtughakmgx.html

TS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtiwegrrgc.html

Java: super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtmuuufuzp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gtddexppwt.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gtkewljdlu.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gtxxsfgpmo.html

[G08] 静态方法与属性
来源：http://dali.iojbl.cn/Article/details/gtcqykavdz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gtqardchxh.html

PHP:  public static function f() {}
来源：http://dali.daxiang520.top/Article/details/gtzbtngddv.html

JS:   static f() {}
来源：http://dali.jiagoushi.top/Article/details/gtptplotzn.html

TS:   static f(): void {}
来源：http://dali.nanxuanxn.top/Article/details/gtyffnsbys.html

Java: static void f() {}
来源：http://dali.guannengcc.top/Article/details/gtmltizyoz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgufenzy.top/Article/details/gthynhjtqf.html

Ruby: def self.f; end
来源：http://dali.gzhubu.top/Article/details/gtcppnpuqi.html

C#:   public static void F() {}
来源：http://dali.xziqi.cn/Article/details/gtdioyquuh.html

[G09] 接口 / 抽象类
来源：http://dali.jlsjyb.cn/Article/details/gtekpspyuo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nwbrower.top/Article/details/gtwktfubjp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenlongwang.top/Article/details/gtnjrcmlvn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gttkqpzefh.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnxiangtu.top/Article/details/gtudruosjj.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtaeiavhzy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxuanxn.top/Article/details/gthldogqda.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.vqdsnc.cn/Article/details/gtbtbjkjwl.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gtfgeafhwr.html

[G10] 访问控制
来源：http://dali.tanke756.top/Article/details/gtzcowilwj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jianghu66.top/Article/details/gtccifyefh.html

PHP:  public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtqkvafjgc.html

JS:   #private 字段；其余公开
来源：http://dali.guannengcc.top/Article/details/gtmqotehyi.html

TS:   public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtiggalysy.html

Java: public / protected / private / 默认包级
来源：http://dali.tanke756.top/Article/details/gtycbflhcn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenjidiqi.icu/Article/details/gtsulyyvll.html

Ruby: public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtketgdcoe.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gtwrxqnfpy.html

[G11] getter / setter
来源：http://dali.chenjidiqi.icu/Article/details/gtffnxumhh.html

Py:   @property 与 @x.setter
来源：http://dali.nwbrower.top/Article/details/gtmqfjzzca.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtvscvfpne.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtwierkpjs.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtttrratyq.html

Java: public String getName() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtgfsdighs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtwcpfpqqk.html

Ruby: attr_accessor :name
来源：http://dali.iojbl.cn/Article/details/gtalpumowb.html

C#:   public string Name { get; set; }
来源：http://dali.yueranfly.top/Article/details/gtojhrorwz.html

[G12] 对象转字符串
来源：http://dali.ybcxt.top/Article/details/gtmlymtesx.html

Py:   def __str__(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtkgbedtch.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtiagtwtqj.html

JS:   toString() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtzxbtwcdl.html

TS:   toString(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkyyrtftv.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtpongizbe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtkwojtowj.html

Ruby: def to_s; @name; end
来源：http://dali.yj202588.top/Article/details/gtpvusfzlu.html

C#:   public override string ToString() => Name;
来源：http://dali.cucudq.cn/Article/details/gthftrxwvc.html

[G13] 判断对象类型
来源：http://dali.316326.xyz/Article/details/gtaimimlkt.html

Py:   isinstance(u, User)
来源：http://dali.daria6918.cn/Article/details/gtamwgteer.html

PHP:  $u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtwflhpybs.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtlhujckkb.html

TS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtyzvkqhcg.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtmyyirtxc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yonumen.top/Article/details/gtyapyqzob.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpzzjqao.html

C#:   u is User
来源：http://dali.xziqi.cn/Article/details/gtdilugdjt.html

[G14] 数据类 / record
来源：http://dali.ybcxt.top/Article/details/gtjovhrkvi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhiwuduotai.top/Article/details/gtgesvlfzm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gtnufqioau.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangshuangyany.cn/Article/details/gtlpoppidw.html

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gtuemnqffq.html

Java: record User(String name, int age) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtffxkengz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuanzhike.top/Article/details/gtljjdlmvx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuanzx.com/Article/details/gtajpujseg.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxinkj.top/Article/details/gtdjinawaw.html

[G15] 枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyoenyzb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jiagoushi.top/Article/details/gtekfluiom.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gtnptuywee.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gtdawkceni.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtapgramve.html

Java: enum Color { RED, GREEN }
来源：http://dali.sufxvd.cn/Article/details/gtozeynasm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pycfn.com/Article/details/gtfuderkjn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hfpthk.cn/Article/details/gtwvjkclyh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogpzkyzk.html

[G16] 对象转数组 / 字典
来源：http://dali.jlsjyb.cn/Article/details/gtkeolgamy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.haohaochexian.top/Article/details/gtwxqimbwf.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gtfahmziun.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtmvprhjxy.html

TS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gtlmscvpjb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shuidangran.top/Article/details/gtqaoyvtcn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cdnleiting.top/Article/details/gtjwbqldca.html

Ruby: obj.instance_variables
来源：http://dali.hysaishi.cn/Article/details/gtldctwrkn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtaooicaqz.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtygnlflls.html

H. 异常与错误处理
来源：http://dali.zycfv.cn/Article/details/gtndysmsug.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtjnfnbbfm.html

[H01] try / catch 基础
来源：http://dali.shzxlz.cn/Article/details/gtchpolube.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gogol.net.cn/Article/details/gtazqwbypu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.9152youxi.cn/Article/details/gttcgurcyd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtwylbvsss.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtqkjmetxg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.316326.xyz/Article/details/gtfzicywxw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zycfv.cn/Article/details/gtogwqvdee.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ppjwa.cn/Article/details/gtupuuklie.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gtqhiawpcf.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gtvozmpxhb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gtpufmksqz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtejjzrhbg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtsmzjsieq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtnlulcsmu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtayljhzjp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhengqikj.top/Article/details/gttkukdbnj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gtlxppbltu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtzjcdntbp.html

[H03] 主动抛出异常
来源：http://dali.yangfankeji.com/Article/details/gtyxvdksid.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenzaomai.com/Article/details/gtnlxvkptc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtvehhenxv.html

JS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtbeqqkbcl.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtswomqjfd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtktgnfyhg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuxming.cn/Article/details/gtdhczjefl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtphhwwpdf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtolfmlnur.html

[H04] 自定义异常类型
来源：http://dali.jianghu66.top/Article/details/gtbismqclw.html

Py:   class MyError(Exception): pass
来源：http://dali.hywenlv.cn/Article/details/gttmnlbsvl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtaiyvfsau.html

JS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtcxqlswnw.html

TS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gtenyiwuow.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gtlamuimsb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guowangkeji.top/Article/details/gtwxwelwit.html

Ruby: class MyError < StandardError; end
来源：http://dali.c1oappe.top/Article/details/gtazdcixcy.html

C#:   class MyException : Exception {}
来源：http://dali.xziqi.cn/Article/details/gtysjddxmv.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gtzzlbldhp.html

Py:   except ValueError as e:
来源：http://dali.daria6918.cn/Article/details/gtlvoupneu.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daxiang520.top/Article/details/gtkezbdchk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkcqlkds.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtctshdgmx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gthfbowcns.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhongyouzk.top/Article/details/gtwdgfnqbp.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gtesjhpqvx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jianghu66.top/Article/details/gtzujmmcdf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gtzdfggqqx.html

Py:   value = d.get("k") or default
来源：http://dali.cheryme.top/Article/details/gtcvguylnu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.meibo888.top/Article/details/gthbprzfpn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtpsizygzd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtczqswgig.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pycfn.com/Article/details/gtszqcupdb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj202588.top/Article/details/gthfcyburi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangdashe.top/Article/details/gtgulieyoo.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangdashe.top/Article/details/gtkggoajuz.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gtbiurlhou.html

Py:   assert x > 0, "必须为正"
来源：http://dali.iojbl.cn/Article/details/gtjyywscdr.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gthqilfzhz.html

JS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gteslbbdvt.html

TS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtzmiltfos.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ehwqpu.com/Article/details/gtbhcvnnac.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigufen.top/Article/details/gtnmevvgtv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ydzc1.top/Article/details/gtukcixjel.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtuwyqiwep.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmrfqqng.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yueranfly.top/Article/details/gtfepghwwp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yonumen.top/Article/details/gtcimfbrzl.html

JS:   e.message;  e.stack
来源：http://dali.guowangkeji.top/Article/details/gthehglrev.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nwbrower.top/Article/details/gtekhkerro.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxinkj.top/Article/details/gtdroisrxh.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gtiqsiypwq.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigfzy.top/Article/details/gtxdadstih.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gteyxmvlzx.html

[H09] 带错误码的异常
来源：http://dali.gogol.net.cn/Article/details/gtsmghgcbk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.316326.xyz/Article/details/gtjfzmjopz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gttaafhpwg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.mhx1999.top/Article/details/gtqkrgtlug.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.mhx1999.top/Article/details/gtlkpebuim.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tanke756.top/Article/details/gtxcdfcqgv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gogol.net.cn/Article/details/gtimibdhbx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gtlwgbpuhw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jlsjyb.cn/Article/details/gtrwvtgxya.html

[H10] 资源自动释放
来源：http://dali.yangfankeji.com/Article/details/gthbapmizb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenzaomai.com/Article/details/gtdmsqgsnw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.316326.xyz/Article/details/gtacholfia.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gtexxedooi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258.top/Article/details/gtkztzlmrl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hysaishi.cn/Article/details/gtwbyzfwnv.html

Go:   defer f.Close()
来源：http://dali.dianchejie.cn/Article/details/gthvxtzyay.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yangfankeji.com/Article/details/gtiamxbnkq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtnjzeqxyq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwpyamhjt.html

I. 正则表达式
来源：http://dali.aibaodan.cn/Article/details/gtbcnrrbpx.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtyxunzlbc.html

[I01] 判断是否匹配
来源：http://dali.kuanghao11.cn/Article/details/gtzbykltzv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsjmrypq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtxlhsemic.html

JS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gtyhigtssz.html

TS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtojjhnctm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.nanxuanxn.top/Article/details/gtbzkappxm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jianghu66.top/Article/details/gtjmdgrjok.html

Ruby: s.match?(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtpwxcbbmv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hysaishi.cn/Article/details/gtflalhkkl.html

[I02] 提取所有匹配
来源：http://dali.dianchejie.cn/Article/details/gtkuommqmq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gtusyczyzm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cqqwz.cn/Article/details/gtaojiwady.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhiwuduotai.top/Article/details/gtnlgwuzwn.html

TS:   s.match(/\d+/g)
来源：http://dali.svipenyu.cn/Article/details/gtztugdfij.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xziqi.cn/Article/details/gtdafhmgaz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtjreppzwh.html

Ruby: s.scan(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtfzyantle.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tanke756.top/Article/details/gtrgksyded.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gtttbsafnv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hammf.cn/Article/details/gtzhrtpqua.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ehwqpu.com/Article/details/gtdsjqivvy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gtzjmxfqrp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprpedtyh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgfzy.top/Article/details/gtrpjvsqrg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gtcptxuvtu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ehwqpu.com/Article/details/gthaoxkiju.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yongpay.top/Article/details/gtkozfvrdn.html

[I04] 正则替换
来源：http://dali.mhx1999.top/Article/details/gtjrnzulap.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxuanxn.top/Article/details/gtituhfmog.html


<!-- 参考信息 -->