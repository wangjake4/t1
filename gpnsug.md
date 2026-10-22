代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.cashguo.top/Article/details/gtotqvlmdg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258888.top/Article/details/gtydirvsmp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtrofnavhb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xziqi.cn/Article/details/gtxizoduqh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtfqilqgcf.html

TS:   path.extname("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtdvwdzhjp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gotoacloud.top/Article/details/gtyqhcvfrg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtgjjyllit.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtnljhycml.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtkepxdzhh.html

[F11] 复制与移动文件
来源：http://dali.wangshuangyany.cn/Article/details/gthszofxmr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtujcxnsqv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ydzc1.top/Article/details/gthtgdoocc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtjohptkrn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtgxnfavgy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nwbrower.top/Article/details/gtpyshwbhn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnxiangtu.top/Article/details/gtcpfmhmpb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtcsoppvid.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gtbgxfizzu.html

[F12] CSV 读写
来源：http://dali.gotoacloud.top/Article/details/gtyekvkvhg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigufen.top/Article/details/gttvigorle.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuanzhike.top/Article/details/gtfqwqzsur.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cheryme.top/Article/details/gtmviwtksn.html

TS:   // 同上
来源：http://dali.nwbrower.top/Article/details/gtlqpbltxk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.andypj.xyz/Article/details/gtqllrxrsd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.svipenyu.cn/Article/details/gtrcmodbki.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.kuanghao11.cn/Article/details/gtzofvefpu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.c1oappe.top/Article/details/gtkospkphp.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtvzwpgwkr.html

G. 面向对象
来源：http://dali.bjfxy.top/Article/details/gthbsgctlz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtydehmipg.html

[G01] 定义类
来源：http://dali.cdnleiting.top/Article/details/gtgnnpigsn.html

Py:   class User: pass
来源：http://dali.cashguo.top/Article/details/gtqkqcnpjk.html

PHP:  class User {}
来源：http://dali.aizwys.cn/Article/details/gtosivlnbt.html

JS:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtsobcoewk.html

TS:   class User { name: string = ""; }
来源：http://dali.zhongyouzk.top/Article/details/gtesyfnpsd.html

Java: class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfnqpuze.html

Go:   type User struct { Name string }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqqmbhlb.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gtyxkgwqbd.html

C#:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtemxujldh.html

[G02] 构造函数
来源：http://dali.aizwys.cn/Article/details/gtsbwevaai.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yangfankeji.com/Article/details/gtgjsawije.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvlevbmu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtbvcvhoyj.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxinkj.top/Article/details/gtmavxklfi.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtjzeofzuc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenlongwang.top/Article/details/gtubxinscf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.c1oappe.top/Article/details/gtlzckrcxr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtaylifjbt.html

[G03] 实例属性
来源：http://dali.sweek.top/Article/details/gtsxfqllce.html

Py:   self.name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtdixgtdhs.html

PHP:  public string $name = "x";
来源：http://dali.hywenlv.cn/Article/details/gtmuupmobz.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytbcvptl.html

TS:   name: string = "x";
来源：http://dali.jinqigufen.top/Article/details/gtpeiqxdwy.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gtoohqsqap.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.0kj1m.cn/Article/details/gttojyksrv.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtwtnunqok.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gtsjnneysg.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gtjiiucgzu.html

Py:   def greet(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gthsodkeej.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gtquyilway.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtubtxtkwf.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gteksvimqf.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gtavfoglqc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtzqrfvfjb.html

Ruby: def greet; @name; end
来源：http://dali.316326.xyz/Article/details/gtljlfzavx.html

C#:   public string Greet() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gthljncuvr.html

[G05] 继承
来源：http://dali.yuxming.cn/Article/details/gtbhdbdkey.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gtowivxjot.html

PHP:  class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtpntmziwq.html

JS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtdlizhgho.html

TS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtntcranvm.html

Java: class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtuacycaxn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gtoeitcylu.html

Ruby: class Admin < User; end
来源：http://dali.yuanzhike.top/Article/details/gtemflpxtn.html

C#:   class Admin : User {}
来源：http://dali.ybcxt.top/Article/details/gtrajqukaz.html

[G06] 重写方法
来源：http://dali.guannengcc.top/Article/details/gtdkdqfnsy.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbagdxoq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtilyeluci.html

JS:   greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtqtvnjzmc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtynxgrsll.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtcyungxyh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gtsdysocik.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gtyrkbkati.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenjidiqi.icu/Article/details/gtippzbgxo.html

[G07] 调用父类方法
来源：http://dali.316326.xyz/Article/details/gtffkaqzxv.html

Py:   super().greet()
来源：http://dali.svipenyu.cn/Article/details/gtkpacrilt.html

PHP:  parent::greet();
来源：http://dali.xuanzx.com/Article/details/gtkvuprzdd.html

JS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtwomwsxfi.html

TS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gttzieskwr.html

Java: super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtwrjptkcj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.svipenyu.cn/Article/details/gtrgtzfhjo.html

Ruby: super
来源：http://dali.yanxiufei.cn/Article/details/gtmjgxvrnw.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gttfepzcsg.html

[G08] 静态方法与属性
来源：http://dali.cqqwz.cn/Article/details/gtfheazcew.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.kuanghao11.cn/Article/details/gtfmieoyun.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gtaagtcsfr.html

JS:   static f() {}
来源：http://dali.c1oappe.top/Article/details/gtyxdmkzoh.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gtferujrtl.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gtbeimmzkj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gtvjkuazqk.html

Ruby: def self.f; end
来源：http://dali.aizwys.cn/Article/details/gtqnaohveu.html

C#:   public static void F() {}
来源：http://dali.yvedp.cn/Article/details/gtddpmkllw.html

[G09] 接口 / 抽象类
来源：http://dali.xuetiantiany.cn/Article/details/gtwbgfosjw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hfpthk.cn/Article/details/gtoolmvlki.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwhipzio.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fengsongda.top/Article/details/gtxloozpmz.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhoulong.xyz/Article/details/gtyzkfjwto.html

Java: interface Shape { double area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbqouaii.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtawugfsyi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.9152youxi.cn/Article/details/gthxjedwvb.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcalumlqu.html

[G10] 访问控制
来源：http://dali.tianlin.xyz/Article/details/gtflmafloi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gtkcjglgms.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtqnqzbvxp.html

JS:   #private 字段；其余公开
来源：http://dali.aibaodan.cn/Article/details/gtejffmqhx.html

TS:   public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtikedmplh.html

Java: public / protected / private / 默认包级
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbnbywzp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gtjxscdith.html

Ruby: public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtzjonsxgy.html

C#:   public / protected / private / internal
来源：http://dali.hongshengwenyu.top/Article/details/gtjjylrmqt.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gtilcbqeus.html

Py:   @property 与 @x.setter
来源：http://dali.hammf.cn/Article/details/gtbehphhwo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtleflbdhs.html

JS:   get name() { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gtkjfrwxzw.html

TS:   get name(): string { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtlnsdtrzc.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtrehfarlk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtlqwnzimh.html

Ruby: attr_accessor :name
来源：http://dali.zdqjudy.top/Article/details/gtkuhvnodf.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gtygkuguhj.html

[G12] 对象转字符串
来源：http://dali.jianghu66.top/Article/details/gtzxxxvans.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtsfypcetu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtupokxzxt.html

JS:   toString() { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gttgvnurnj.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbrpoitpv.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbffdciqp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtuiqystqa.html

Ruby: def to_s; @name; end
来源：http://dali.xuanzx.com/Article/details/gtbrynmebx.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxinkj.top/Article/details/gtmscnpowk.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gtujtjykpe.html

Py:   isinstance(u, User)
来源：http://dali.yj20258888.top/Article/details/gtbdstogrv.html

PHP:  $u instanceof User
来源：http://dali.cashguo.top/Article/details/gtxwluyzzv.html

JS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtpynczeqd.html

TS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtuatknvak.html

Java: u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtgimgqeek.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jianghu66.top/Article/details/gtbgfivnpa.html

Ruby: u.is_a?(User)
来源：http://dali.yuanzhike.top/Article/details/gtohzrscel.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gtsstfddfh.html

[G14] 数据类 / record
来源：http://dali.gotoacloud.top/Article/details/gtfhlttdsl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258888.top/Article/details/gtdqgfzkbz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daxiang520.top/Article/details/gtxidkoljq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gtchswciol.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gtbyfselsl.html

Java: record User(String name, int age) {}
来源：http://dali.mhx1999.top/Article/details/gtfxzvufjq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gtuhcphqow.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tanke756.top/Article/details/gtuhfsjtpy.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigfzy.top/Article/details/gtbumogdoy.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gtfsrwcbuj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gtxeotbtpo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenzaomai.com/Article/details/gtljjejaji.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.feifeiyinyue.top/Article/details/gtvkikvdmw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtztogazya.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gtqouheozr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnxiangtu.top/Article/details/gtcodxkoft.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gtgsptlnyz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gtnnkfuflq.html

[G16] 对象转数组 / 字典
来源：http://dali.pycfn.com/Article/details/gtzcshsnvu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhixingplan.top/Article/details/gtcosxsuky.html

PHP:  get_object_vars($obj);
来源：http://dali.jyoumei.cn/Article/details/gtvzukftwg.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjxkofho.html

TS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gtixxrbtrp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aizwys.cn/Article/details/gtwdzulrwe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gtxezocjkn.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gtkolqxbve.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtbidtcdoz.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtthehioma.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtbmgppesl.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtbnrrfcwy.html

[H01] try / catch 基础
来源：http://dali.hnqzz.top/Article/details/gtgsnzfbws.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sxryk.cn/Article/details/gtywxkuaui.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dianchejie.cn/Article/details/gtvgdlbwsw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtfvlqzvfc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtgfayrloz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gotoacloud.top/Article/details/gtagjjmcgb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sysykeji.top/Article/details/gtqduevsby.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuetiantiany.cn/Article/details/gtlegsywid.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.haohaochexian.top/Article/details/gtudyzctke.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258888.top/Article/details/gtpslqyqyd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sweek.top/Article/details/gtkqndnmwh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtrrnzasqe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtrznbqekm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gthjrndglh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwppatue.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.iojbl.cn/Article/details/gtltggahhr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gtcdofztuo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtzvjpsxqm.html

[H03] 主动抛出异常
来源：http://dali.sweek.top/Article/details/gtzyzdbfqq.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgufenzy.top/Article/details/gtdweignfa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtudalbgbr.html

JS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtbammkogy.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhkkgaap.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtwpplniak.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gtipkjnors.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gtnwyfyzoc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtrvmmbgrv.html

[H04] 自定义异常类型
来源：http://dali.quarkkingdee.top/Article/details/gtqadzwyhf.html

Py:   class MyError(Exception): pass
来源：http://dali.jiagoushi.top/Article/details/gtsklfgebo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtpjnbvhgr.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gtavnhhccj.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gtktxmdxbi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtkabnszce.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aibaodan.cn/Article/details/gtyxrnmgrv.html

Ruby: class MyError < StandardError; end
来源：http://dali.ybcxt.top/Article/details/gtsjyuluqk.html

C#:   class MyException : Exception {}
来源：http://dali.yueranfly.top/Article/details/gtktiakfas.html

[H05] 捕获特定类型
来源：http://dali.yueranfly.top/Article/details/gtlfsleumx.html

Py:   except ValueError as e:
来源：http://dali.kuanghao11.cn/Article/details/gtoilusyyf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhiwuduotai.top/Article/details/gtwufclsbn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrxovefo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmmgubcz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258.top/Article/details/gthwllmmsq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sweek.top/Article/details/gthhwzhmmi.html

Ruby: rescue ArgumentError => e
来源：http://dali.ppjwa.cn/Article/details/gtikkdlrka.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pycfn.com/Article/details/gtcwtecvpx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxuanxn.top/Article/details/gtfzsaneon.html

Py:   value = d.get("k") or default
来源：http://dali.chenzaomai.com/Article/details/gtcklkrrpt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gtuvjgpkgw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtiexlbhul.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gtvysumlsq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gtjfezypng.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ppjwa.cn/Article/details/gtbhwkanfz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.iojbl.cn/Article/details/gtcseorxbh.html

C#:   obj?.A?.B ?? default
来源：http://dali.dashuyun.cn/Article/details/gtrhgwvgqf.html

[H07] 断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvseutlgg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yonumen.top/Article/details/gtakdsakgx.html

PHP:  assert($x > 0);
来源：http://dali.yonumen.top/Article/details/gtgzqqgmfq.html

JS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwaeojga.html

TS:   console.assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtwrpofgrk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nwbrower.top/Article/details/gtzwnisdai.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sufxvd.cn/Article/details/gtmnokyceu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.svipenyu.cn/Article/details/gtisgzatzx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtbymbohol.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gtwbaxkglg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigfzy.top/Article/details/gtuuasgqcn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dashuyun.cn/Article/details/gtaidclvtk.html

JS:   e.message;  e.stack
来源：http://dali.zhiwuduotai.top/Article/details/gtqitdpylo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cashguo.top/Article/details/gtpswzkgdt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.bjfxy.top/Article/details/gtdragznoi.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gtmwjvuscz.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gtbzonwkqs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvpavtqr.html

[H09] 带错误码的异常
来源：http://dali.hammf.cn/Article/details/gtwowaooaa.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuxming.cn/Article/details/gtmqmtebyj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gtavfuevme.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sxryk.cn/Article/details/gtugcgnidv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.bjfxy.top/Article/details/gtyzadebfc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shuidangran.top/Article/details/gthzgxkeop.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgufenzy.top/Article/details/gthjjzyhfw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hongshengwenyu.top/Article/details/gtfloygler.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hammf.cn/Article/details/gtljiwuejw.html

[H10] 资源自动释放
来源：http://dali.redwolf501.top/Article/details/gtmplvigvg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yangfankeji.com/Article/details/gtorzvyljn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gtvciignls.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtsijhvxud.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gtnqmgaida.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fengsongda.top/Article/details/gtwyffhkri.html

Go:   defer f.Close()
来源：http://dali.gzhubu.top/Article/details/gtjqtakcaz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuxming.cn/Article/details/gteqlqhfcc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gtrrpseobj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtlzuhtitv.html

I. 正则表达式
来源：http://dali.hammf.cn/Article/details/gttgbmtsux.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtnrybovzc.html

[I01] 判断是否匹配
来源：http://dali.cucudq.cn/Article/details/gtnlmaijyj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gtxwavdubn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.iojbl.cn/Article/details/gthlwexnkf.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtmcpizkxs.html

TS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gtlgnzovuu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenlongwang.top/Article/details/gthzhmmxep.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gogol.net.cn/Article/details/gtrnktqnir.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gtzcisdgkf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gtuwanfudk.html

[I02] 提取所有匹配
来源：http://dali.zdqjudy.top/Article/details/gtsdwafrkc.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtxwlazgtn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgfzy.top/Article/details/gtcvwjvmvv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hammf.cn/Article/details/gtbylwocku.html

TS:   s.match(/\d+/g)
来源：http://dali.hywenlv.cn/Article/details/gtqufwvwso.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepwswgqg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.guannengcc.top/Article/details/gtbycwhrcd.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtdplasnsl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.316326.xyz/Article/details/gtbncumlpm.html

[I03] 提取捕获分组
来源：http://dali.fzhhl.top/Article/details/gtpzewfoip.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gtgtfxaafk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gtoqtqqojd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtwopvrfzo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ehwqpu.com/Article/details/gtyocgbsup.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinqigfzy.top/Article/details/gtqfmkbcpx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cqqwz.cn/Article/details/gtgqzoxacp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.vqdsnc.cn/Article/details/gtmarasdur.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shzxlz.cn/Article/details/gtjlxhtgqd.html

[I04] 正则替换
来源：http://dali.hysaishi.cn/Article/details/gtimespcfb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gthwonnnat.html


<!-- 参考信息 -->