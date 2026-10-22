代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ogesiavd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gt2umxdwtss.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2xgqurvye.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2kvykqzls.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2ujhjboqo.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2mkstfjuh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jlsjyb.cn/Article/details/gt2vliwguva.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2enkwjtau.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2orrshpzj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2einxnigl.html

[F11] 复制与移动文件
来源：http://dali.pycfn.com/Article/details/gt2vulqyvxt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gt2wbkkzitd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cheryme.top/Article/details/gt2zojzpxto.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2wyfkqxzk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2mhgaetde.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gt2lsdnyjvn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daria6918.cn/Article/details/gt2gdsrnxwh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2cxsnmhrg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2btlrkewm.html

[F12] CSV 读写
来源：http://dali.zhiwuduotai.top/Article/details/gt2jvhchkoh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.svipenyu.cn/Article/details/gt2qubblssj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xtvllqnf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258888.top/Article/details/gt2mpufvjde.html

TS:   // 同上
来源：http://dali.yuanzhike.top/Article/details/gt2ubstojyg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangshuangyany.cn/Article/details/gt2hoigeydz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gt2ckopbtgy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shuidangran.top/Article/details/gt2oqkzstuu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tianlin.xyz/Article/details/gt2tzprfnkd.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2ksfbbwri.html

G. 面向对象
来源：http://dali.vqdsnc.cn/Article/details/gt2dlfljpag.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2efjsnavm.html

[G01] 定义类
来源：http://dali.jinqigfzy.top/Article/details/gt2xwtcvwwj.html

Py:   class User: pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zrzeearx.html

PHP:  class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2qwecpvak.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gt2vaasihzl.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gt2cbishdfj.html

Java: class User {}
来源：http://dali.tanke756.top/Article/details/gt2kxkmqusn.html

Go:   type User struct { Name string }
来源：http://dali.snrcjt.cn/Article/details/gt2azmismpy.html

Ruby: class User; end
来源：http://dali.aizwys.cn/Article/details/gt2dtiphazl.html

C#:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2dytqzpfc.html

[G02] 构造函数
来源：http://dali.tian-w.cn/Article/details/gt2vesezcyc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vxgrmumn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2mshqcahr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gt2xzxkhnny.html

TS:   constructor(public name: string) {}
来源：http://dali.cashguo.top/Article/details/gt2egtyaerh.html

Java: User(String name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gt2xkgoxvud.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tian-w.cn/Article/details/gt2znlygmgv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.haohaochexian.top/Article/details/gt2swphjtxx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gotoacloud.top/Article/details/gt2gkyprefi.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gt2tuozlvim.html

Py:   self.name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gt2rojiudtt.html

PHP:  public string $name = "x";
来源：http://dali.ivvv.top/Article/details/gt2bmiajflh.html

JS:   this.name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2keluavia.html

TS:   name: string = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2xwvxfiax.html

Java: private String name;
来源：http://dali.cqqwz.cn/Article/details/gt2mqoogljq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jiagoushi.top/Article/details/gt2vwhckpcg.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gt2sdlfecgo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.meibo888.top/Article/details/gt2jopsbgxk.html

[G04] 定义方法
来源：http://dali.yueranfly.top/Article/details/gt2szrgpblm.html

Py:   def greet(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gt2wtrzbfwd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2qeapxwsr.html

JS:   greet() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2msbdemgd.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2kcaenggw.html

Java: String greet() { return name; }
来源：http://dali.birdmap.top/Article/details/gt2lchvtvyd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2wvsviitj.html

Ruby: def greet; @name; end
来源：http://dali.havefunace.top/Article/details/gt2dmicrznw.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gt2dohzyvsi.html

[G05] 继承
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zchrxlce.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2buhdixjl.html

PHP:  class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2qtkumtcd.html

JS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gt2dgcxxnly.html

TS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gt2cubzpbby.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2piflcjzz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gt2bgdzldfo.html

Ruby: class Admin < User; end
来源：http://dali.0kj1m.cn/Article/details/gt2zgoaflcq.html

C#:   class Admin : User {}
来源：http://dali.316326.xyz/Article/details/gt2kgnvcagp.html

[G06] 重写方法
来源：http://dali.guowangkeji.top/Article/details/gt2ckqxjxhq.html

Py:   def greet(self): return "admin"
来源：http://dali.sxryk.cn/Article/details/gt2ohzgoqaa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2ggatpojp.html

JS:   greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2wbrepopk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gt2sqkjglxf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lgbypcnj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gt2rntbshyx.html

Ruby: def greet; "admin"; end
来源：http://dali.iojbl.cn/Article/details/gt2qqszrkto.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxuanxn.top/Article/details/gt2bhtjjnqe.html

[G07] 调用父类方法
来源：http://dali.quarkkingdee.top/Article/details/gt2odlwucyh.html

Py:   super().greet()
来源：http://dali.jqgufenzy.top/Article/details/gt2dmautuqa.html

PHP:  parent::greet();
来源：http://dali.andypj.xyz/Article/details/gt2dsdyopul.html

JS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2pbnlhrpx.html

TS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2jipeyygn.html

Java: super.greet();
来源：http://dali.9152youxi.cn/Article/details/gt2gtnjczlh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.c1oappe.top/Article/details/gt2vsbtboev.html

Ruby: super
来源：http://dali.svipenyu.cn/Article/details/gt2blikwexa.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gt2yrrashly.html

[G08] 静态方法与属性
来源：http://dali.yj20258888.top/Article/details/gt2dhutytnp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daxiang520.top/Article/details/gt2wkuadjdt.html

PHP:  public static function f() {}
来源：http://dali.chenzaomai.com/Article/details/gt2ugoyhqfk.html

JS:   static f() {}
来源：http://dali.fzhhl.top/Article/details/gt2cosspueq.html

TS:   static f(): void {}
来源：http://dali.zhongyouzk.top/Article/details/gt2dqjydtiy.html

Java: static void f() {}
来源：http://dali.zycfv.cn/Article/details/gt2swzobnoq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xziqi.cn/Article/details/gt2obegwdsu.html

Ruby: def self.f; end
来源：http://dali.zhongyouzk.top/Article/details/gt2wmqldidl.html

C#:   public static void F() {}
来源：http://dali.yongpay.top/Article/details/gt2mfljdxaw.html

[G09] 接口 / 抽象类
来源：http://dali.shuidangran.top/Article/details/gt2qzhqpwiw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.snrcjt.cn/Article/details/gt2nsjpuftf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tianlin.xyz/Article/details/gt2zlaxlirc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.iojbl.cn/Article/details/gt2tcdwjuxm.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gt2gakpxpfo.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigufen.top/Article/details/gt2qwrbxziw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jrqxgojj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gt2evhffnul.html

C#:   interface IShape { double Area(); }
来源：http://dali.snrcjt.cn/Article/details/gt2gllhinsq.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gt2fdkqbrro.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnqzz.top/Article/details/gt2inwwpnzf.html

PHP:  public / protected / private
来源：http://dali.yj20258.top/Article/details/gt2waphrwrn.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gt2hqtmiyyt.html

TS:   public / protected / private
来源：http://dali.wangdashe.top/Article/details/gt2ylhuyzjy.html

Java: public / protected / private / 默认包级
来源：http://dali.kuanghao11.cn/Article/details/gt2iwcuwume.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ydzc1.top/Article/details/gt2xguolcbq.html

Ruby: public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2cpndqbfb.html

C#:   public / protected / private / internal
来源：http://dali.fzhhl.top/Article/details/gt2kxkmuyvu.html

[G11] getter / setter
来源：http://dali.fzhhl.top/Article/details/gt2amvsjbux.html

Py:   @property 与 @x.setter
来源：http://dali.sufxvd.cn/Article/details/gt2jsptpggl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gt2miyvvlen.html

JS:   get name() { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gt2buocdxxh.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2qjqunddd.html

Java: public String getName() { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2pazfescu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gt2xgttbjez.html

Ruby: attr_accessor :name
来源：http://dali.sysykeji.top/Article/details/gt2xqnwpqan.html

C#:   public string Name { get; set; }
来源：http://dali.smart0.xyz/Article/details/gt2egckdncy.html

[G12] 对象转字符串
来源：http://dali.pycfn.com/Article/details/gt2vsofzmzr.html

Py:   def __str__(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gt2rvviqluc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gt2nyofivcn.html

JS:   toString() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2ovyyynmd.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2egcbvlsx.html

Java: @Override public String toString() { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2fpthratr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gt2amtvbrlo.html

Ruby: def to_s; @name; end
来源：http://dali.zdqjudy.top/Article/details/gt2wyrxgelc.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gt2mbhrhtok.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gt2kdrhnues.html

Py:   isinstance(u, User)
来源：http://dali.yanxiufei.cn/Article/details/gt2pvldrblc.html

PHP:  $u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gt2hojuxyly.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qhyklzbx.html

TS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2lfhtvekx.html

Java: u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2picbgupi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.c1oappe.top/Article/details/gt2stzyejqh.html

Ruby: u.is_a?(User)
来源：http://dali.sufxvd.cn/Article/details/gt2qewpggij.html

C#:   u is User
来源：http://dali.sweek.top/Article/details/gt2fvgebfuz.html

[G14] 数据类 / record
来源：http://dali.sxryk.cn/Article/details/gt2xvhezcvt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xinyue.icu/Article/details/gt2bpzzzhjr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tqbpfkgw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenjidiqi.icu/Article/details/gt2jxmyjeos.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gt2gyzdxosl.html

Java: record User(String name, int age) {}
来源：http://dali.sweek.top/Article/details/gt2qunvplch.html

Go:   type User struct { Name string; Age int }
来源：http://dali.birdmap.top/Article/details/gt2ajnetxpj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gt2wxbwbhah.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gt2eowcibqj.html

[G15] 枚举
来源：http://dali.yuanzhike.top/Article/details/gt2jsqynmwg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgfzy.top/Article/details/gt2ggxzhtxf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gt2endmvfvd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.mhx1999.top/Article/details/gt2eefyrpal.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gt2yxbrzdhs.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhongyouzk.top/Article/details/gt2siuprxux.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cucudq.cn/Article/details/gt2yblogcmh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gt2qgingrws.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2tbslvmav.html

[G16] 对象转数组 / 字典
来源：http://dali.0kj1m.cn/Article/details/gt2qtmbzvrp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.havefunace.top/Article/details/gt2ltlbvrsc.html

PHP:  get_object_vars($obj);
来源：http://dali.hywenlv.cn/Article/details/gt2pigcengj.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2uzcwbyhv.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wvokqkuh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenlongwang.top/Article/details/gt2wlutmxdw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fengsongda.top/Article/details/gt2bhnzlquk.html

Ruby: obj.instance_variables
来源：http://dali.ivvv.top/Article/details/gt2klvqgvpn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gt2izokzbbi.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2ogvgezfk.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gt2svikrmer.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2awfebglr.html

[H01] try / catch 基础
来源：http://dali.snrcjt.cn/Article/details/gt2fqbmjebu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gt2dfkfzavv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2audltaaj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gt2vlhhgkcm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fulnzhja.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258.top/Article/details/gt2tdbkgjqn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jiagoushi.top/Article/details/gt2kzugojry.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gt2itbtnvdv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sxryk.cn/Article/details/gt2qbytstgy.html

[H02] finally / ensure 收尾
来源：http://dali.chenjidiqi.icu/Article/details/gt2psbptpgu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cashguo.top/Article/details/gt2ciunqnak.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imumxfze.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2zoziceea.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2hbalzknx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2cpumpkeq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gt2brqmbqrj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2govbhuax.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2wnyvusjz.html

[H03] 主动抛出异常
来源：http://dali.aizwys.cn/Article/details/gt2lzlywhgu.html

Py:   raise ValueError("错误信息")
来源：http://dali.9152youxi.cn/Article/details/gt2oylayukl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vcqimhnr.html

JS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2rvnvojlz.html

TS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2qjbziosx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2lxhwbqtt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sysykeji.top/Article/details/gt2tjiszhhk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aibaodan.cn/Article/details/gt2txflpjbr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2inqkmjqt.html

[H04] 自定义异常类型
来源：http://dali.mhx1999.top/Article/details/gt2efmwfgqw.html

Py:   class MyError(Exception): pass
来源：http://dali.gotoacloud.top/Article/details/gt2wtuauvjt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gt2itudnpqz.html

JS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gt2pxllibtl.html

TS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gt2yvwccomk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wlpqbelt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fzhhl.top/Article/details/gt2orrfqdcp.html

Ruby: class MyError < StandardError; end
来源：http://dali.iojbl.cn/Article/details/gt2ztjmruls.html

C#:   class MyException : Exception {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2gcnebvvz.html

[H05] 捕获特定类型
来源：http://dali.xylfe.cn/Article/details/gt2ikprnfso.html

Py:   except ValueError as e:
来源：http://dali.andypj.xyz/Article/details/gt2suzmmnyq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhixingplan.top/Article/details/gt2btpcnptc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2zuxfeimr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gt2uitecnfp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guannengcc.top/Article/details/gt2ipxcfvzj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ivvv.top/Article/details/gt2bskurmvk.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258.top/Article/details/gt2wjsvjeaq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hfpthk.cn/Article/details/gt2ggceiayd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gt2olybanae.html

Py:   value = d.get("k") or default
来源：http://dali.gaohongyu789.top/Article/details/gt2ugnxfdub.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yueranfly.top/Article/details/gt2vcltdodz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gt2fakooxxs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2blfjhbpy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgfzy.top/Article/details/gt2qnklznet.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgfzy.top/Article/details/gt2gnyiyjoe.html

Ruby: d&.dig(:a, :b)
来源：http://dali.havefunace.top/Article/details/gt2xylufhef.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxinkj.top/Article/details/gt2gphdsxcp.html

[H07] 断言
来源：http://dali.ivvv.top/Article/details/gt2djzrwvzj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gaohongyu789.top/Article/details/gt2lspfuhdg.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2hskuqmpo.html

JS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxjefmtq.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2xbejjhzo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fengsongda.top/Article/details/gt2qdqjuxht.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.haohaochexian.top/Article/details/gt2kcjhcmai.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhoulong.xyz/Article/details/gt2ymzhbttk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2bzlyywru.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2vujipszb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.smart0.xyz/Article/details/gt2hsxnsraa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258888.top/Article/details/gt2yvmfczxq.html

JS:   e.message;  e.stack
来源：http://dali.yuanzhike.top/Article/details/gt2klttrbmj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yueranfly.top/Article/details/gt2xdeolhmi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shzxlz.cn/Article/details/gt2kbqctzfx.html

Go:   err.Error()
来源：http://dali.feifeiyinyue.top/Article/details/gt2rrdjjvrf.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxinkj.top/Article/details/gt2uymqixed.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigfzy.top/Article/details/gt2vseudzuu.html

[H09] 带错误码的异常
来源：http://dali.nanxuanxn.top/Article/details/gt2gcjqfvsr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qglowcxt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtaizmvt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gaohongyu789.top/Article/details/gt2bxamigmc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxinkj.top/Article/details/gt2ttsbyxvp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.kuanghao11.cn/Article/details/gt2rzjteonb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.snrcjt.cn/Article/details/gt2oglffrto.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hfpthk.cn/Article/details/gt2beqrrbhg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenjidiqi.icu/Article/details/gt2kcnvfhwd.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gt2ordmsbkt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ivvv.top/Article/details/gt2mzacwlal.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ivvv.top/Article/details/gt2jhtzbbfl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gt2dsbhlkpv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gt2kibkyrxz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hongshengwenyu.top/Article/details/gt2zoqtghrs.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gt2frfbjsoq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tianlin.xyz/Article/details/gt2cmfdgnsx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kcsjhkmy.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2izssqprf.html

I. 正则表达式
来源：http://dali.iojbl.cn/Article/details/gt2eotjednf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2ieijeesc.html

[I01] 判断是否匹配
来源：http://dali.shuidangran.top/Article/details/gt2mrohugbc.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gt2rpedcske.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2zphtdvmr.html

JS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gt2bhluzgkr.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gt2zyuzvqnb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenlongwang.top/Article/details/gt2kfqxjwlw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hammf.cn/Article/details/gt2ahtynoim.html

Ruby: s.match?(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gt2dxkjizko.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhiwuduotai.top/Article/details/gt2yyydopgv.html

[I02] 提取所有匹配
来源：http://dali.zhixingplan.top/Article/details/gt2dwevpudg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gt2zptrlqnf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sufxvd.cn/Article/details/gt2vrcdlvvf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hfpthk.cn/Article/details/gt2ckojlasx.html

TS:   s.match(/\d+/g)
来源：http://dali.yangfankeji.com/Article/details/gt2qbynigyy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zycfv.cn/Article/details/gt2wqbfytid.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gt2gsbdppgu.html

Ruby: s.scan(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gt2rtvwvctz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2vjyfuhnn.html

[I03] 提取捕获分组
来源：http://dali.hfpthk.cn/Article/details/gt2rvxuunex.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.9152youxi.cn/Article/details/gt2mmfjxcns.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuanzhike.top/Article/details/gt2bnopkhzh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.snrcjt.cn/Article/details/gt2rrvxsiot.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zdqjudy.top/Article/details/gt2yqrrgkre.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yvedp.cn/Article/details/gt2nfvyhoqw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.0kj1m.cn/Article/details/gt2nddeaucx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daxiang520.top/Article/details/gt2sonmnpsv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigufen.top/Article/details/gt2zidjnmjk.html

[I04] 正则替换
来源：http://dali.gotoacloud.top/Article/details/gt2olrslhmv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnqzz.top/Article/details/gt2ifelirbt.html


<!-- 参考信息 -->