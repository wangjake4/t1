代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.cqqwz.cn/Article/details/gtbcnxwvqu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gaohongyu789.top/Article/details/gtgandgkti.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtilscantq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtrvqleiru.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtmlxgtome.html

TS:   path.extname("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtvmfjekgf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guannengcc.top/Article/details/gtdvqnjywk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtgemeuusb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gthnjbyvgs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtfkobqgxd.html

[F11] 复制与移动文件
来源：http://dali.chenzaomai.com/Article/details/gtkjfinczk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtcsbrboku.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fengsongda.top/Article/details/gtipygggmo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gttyeilsel.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gttwgersfj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylknzefe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.c1oappe.top/Article/details/gtdsugwckw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gttyinrohf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.svipenyu.cn/Article/details/gtclnhiimy.html

[F12] CSV 读写
来源：http://dali.aibaodan.cn/Article/details/gtywxmnlrf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpblspkc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hongshengwenyu.top/Article/details/gtpmhpxbtj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guannengcc.top/Article/details/gtdtqkpdvo.html

TS:   // 同上
来源：http://dali.xziqi.cn/Article/details/gtszqlahdo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.smart0.xyz/Article/details/gtpzfefsuu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dianchejie.cn/Article/details/gteshoebum.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xylfe.cn/Article/details/gtglemxixu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pycfn.com/Article/details/gtskvpwgbn.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtteyijreh.html

G. 面向对象
来源：http://dali.shangyingyoupin.top/Article/details/gtkmypokyn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdtehwnup.html

[G01] 定义类
来源：http://dali.shzxlz.cn/Article/details/gtshvtaegm.html

Py:   class User: pass
来源：http://dali.wangshuangyany.cn/Article/details/gtmvecyava.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtvrzgaxeg.html

JS:   class User {}
来源：http://dali.xuanzx.com/Article/details/gtabbbgcom.html

TS:   class User { name: string = ""; }
来源：http://dali.hongshengwenyu.top/Article/details/gtphhrqmyg.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtasrodosf.html

Go:   type User struct { Name string }
来源：http://dali.zhongyouzk.top/Article/details/gtwfudlmin.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gtjpmrfdlj.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtfiqyuaok.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtxjwvpvzm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gzhubu.top/Article/details/gtfrinfxdq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gtmlfubzek.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtmkdshdar.html

TS:   constructor(public name: string) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtvfzoidop.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtdcfqieht.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuanzx.com/Article/details/gtbvmghnxc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gtugcfhykt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtcoqpfbhm.html

[G03] 实例属性
来源：http://dali.smart0.xyz/Article/details/gtstfutspx.html

Py:   self.name = "x"
来源：http://dali.sweek.top/Article/details/gtmxmgcova.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gtnjwlijth.html

JS:   this.name = "x";
来源：http://dali.hywenlv.cn/Article/details/gtjxwlzeio.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwrsydqn.html

Java: private String name;
来源：http://dali.nanxinkj.top/Article/details/gtcwuthiyg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ivvv.top/Article/details/gtpedlhjya.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gtthraklwo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fzhhl.top/Article/details/gtvvmlvvck.html

[G04] 定义方法
来源：http://dali.jianghu66.top/Article/details/gthnomjwso.html

Py:   def greet(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gtpmljblav.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gteckpyxmn.html

JS:   greet() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtbgqmjmpg.html

TS:   greet(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtnvjkwazm.html

Java: String greet() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtvfrppmgp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtusxyxamc.html

Ruby: def greet; @name; end
来源：http://dali.nwbrower.top/Article/details/gtyrubskiu.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gtewviwepo.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gtzskhlzqw.html

Py:   class Admin(User): pass
来源：http://dali.bjfxy.top/Article/details/gtwomncpgv.html

PHP:  class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnalwdgbt.html

JS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtuyncotop.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtdcmwqojo.html

Java: class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtqpmdibug.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgufenzy.top/Article/details/gtcwtypjwx.html

Ruby: class Admin < User; end
来源：http://dali.cdnleiting.top/Article/details/gtmscgxoiq.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gtqjlnjkvv.html

[G06] 重写方法
来源：http://dali.gotoacloud.top/Article/details/gtsfpxpytn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhiwuduotai.top/Article/details/gtnobjcodv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbdneqsu.html

JS:   greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gttmamntza.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gthrwhhinp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtseyqukzr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guowangkeji.top/Article/details/gtzdmwgdrg.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gtknfegiaw.html

C#:   public override string Greet() => "admin";
来源：http://dali.jianghu66.top/Article/details/gtqmdnubsm.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gtdisjukff.html

Py:   super().greet()
来源：http://dali.feifeiyinyue.top/Article/details/gtgsqpqlac.html

PHP:  parent::greet();
来源：http://dali.yj202588.top/Article/details/gtphkzjyia.html

JS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtumllnkhd.html

TS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtrmztnejr.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gttflfhmte.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gtvqhgxajc.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gtttbywqmi.html

C#:   base.Greet();
来源：http://dali.ivvv.top/Article/details/gtkphkqjqb.html

[G08] 静态方法与属性
来源：http://dali.guannengcc.top/Article/details/gtrgronavd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gogol.net.cn/Article/details/gtxcakivyn.html

PHP:  public static function f() {}
来源：http://dali.cdnleiting.top/Article/details/gtycewapbx.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtqjjivzqc.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gtrjngeryi.html

Java: static void f() {}
来源：http://dali.wangdashe.top/Article/details/gteivgcsiz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.bjfxy.top/Article/details/gtcgibckhq.html

Ruby: def self.f; end
来源：http://dali.kuanghao11.cn/Article/details/gtukrbfhgb.html

C#:   public static void F() {}
来源：http://dali.hammf.cn/Article/details/gtflamrnsc.html

[G09] 接口 / 抽象类
来源：http://dali.tanke756.top/Article/details/gtapxzungo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nwbrower.top/Article/details/gtfeqfmmtb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuxming.cn/Article/details/gtvbqzpcqe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cqqwz.cn/Article/details/gtdnnbnikm.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtpictxrgp.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gtfmvezjxo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgufenzy.top/Article/details/gtnbqiudct.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenzaomai.com/Article/details/gtmfrmjnyt.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigfzy.top/Article/details/gtidfcahed.html

[G10] 访问控制
来源：http://dali.chenzaomai.com/Article/details/gtceukoloy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gtdsykebob.html

PHP:  public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtgvebrucd.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gtqkvvafeu.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtqbkueskr.html

Java: public / protected / private / 默认包级
来源：http://dali.ydzc1.top/Article/details/gtfeafimhu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangdashe.top/Article/details/gtralmezad.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtykwmiyto.html

C#:   public / protected / private / internal
来源：http://dali.shzxlz.cn/Article/details/gtsxnubhxj.html

[G11] getter / setter
来源：http://dali.xziqi.cn/Article/details/gtvcpfwxyx.html

Py:   @property 与 @x.setter
来源：http://dali.jyoumei.cn/Article/details/gtqagglmqo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbarcpaq.html

JS:   get name() { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gteicnpikk.html

TS:   get name(): string { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gtyndvzmbe.html

Java: public String getName() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtyarpubri.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtwfioqdnp.html

Ruby: attr_accessor :name
来源：http://dali.ehwqpu.com/Article/details/gtfrofwpri.html

C#:   public string Name { get; set; }
来源：http://dali.daxiang520.top/Article/details/gtwqfcixvu.html

[G12] 对象转字符串
来源：http://dali.yuxming.cn/Article/details/gttwjetdzi.html

Py:   def __str__(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtstxgfwus.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtepotsczs.html

JS:   toString() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtzukzgvyn.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtzhovfash.html

Java: @Override public String toString() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gttagqqmsz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtlucayxdx.html

Ruby: def to_s; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gtzcigcfjf.html

C#:   public override string ToString() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtzvarnkqb.html

[G13] 判断对象类型
来源：http://dali.yvedp.cn/Article/details/gtfgnygepm.html

Py:   isinstance(u, User)
来源：http://dali.jianghu66.top/Article/details/gturhedyjw.html

PHP:  $u instanceof User
来源：http://dali.cashguo.top/Article/details/gtblgojmbz.html

JS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtwjfthqdu.html

TS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtnumabnxp.html

Java: u instanceof User
来源：http://dali.zycfv.cn/Article/details/gthexbqgds.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sweek.top/Article/details/gtqdkhkczj.html

Ruby: u.is_a?(User)
来源：http://dali.pycfn.com/Article/details/gtnbrvatyr.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gtvivrhjgg.html

[G14] 数据类 / record
来源：http://dali.jqgfzy.top/Article/details/gtmjkgfsko.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tanke756.top/Article/details/gtapehpcri.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dianchejie.cn/Article/details/gtxbvdfuox.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gtravihppj.html

TS:   type User = { name: string; age: number };
来源：http://dali.ydzc1.top/Article/details/gtaawwkmwy.html

Java: record User(String name, int age) {}
来源：http://dali.havefunace.top/Article/details/gtbbvvdufz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yanxiufei.cn/Article/details/gtewgrcroo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdaipxdi.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gtkzydptce.html

[G15] 枚举
来源：http://dali.ybcxt.top/Article/details/gtskcywohx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jyoumei.cn/Article/details/gthwxujhyw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtguearfbw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.smart0.xyz/Article/details/gtqhjaciit.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gtymtagaxj.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuanzhike.top/Article/details/gtoqwgymqi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.wangshuangyany.cn/Article/details/gtpthzdoyq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhizpzhc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gtfrpioayu.html

[G16] 对象转数组 / 字典
来源：http://dali.tian-w.cn/Article/details/gtxhfhcppq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hongshengwenyu.top/Article/details/gtohlnekqp.html

PHP:  get_object_vars($obj);
来源：http://dali.cucudq.cn/Article/details/gtyezpuctp.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtikdeprku.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtqpdgkjrt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.c1oappe.top/Article/details/gtyjgngpyn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dianchejie.cn/Article/details/gtqzazxjyd.html

Ruby: obj.instance_variables
来源：http://dali.dianchejie.cn/Article/details/gtdftkumww.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cashguo.top/Article/details/gtsjwwcxar.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtcroclrdc.html

H. 异常与错误处理
来源：http://dali.jqgufenzy.top/Article/details/gtxaafhoho.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqiszaldm.html

[H01] try / catch 基础
来源：http://dali.iojbl.cn/Article/details/gtsfzbgbpr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gtlgwbsyge.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sysykeji.top/Article/details/gtedfumzvz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gtaoswfgmp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gtebdiutty.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangshuangyany.cn/Article/details/gtovigkgha.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgufenzy.top/Article/details/gtowqhltoe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.andypj.xyz/Article/details/gtpsdpmdpr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangshuangyany.cn/Article/details/gtchdmjlbw.html

[H02] finally / ensure 收尾
来源：http://dali.sysykeji.top/Article/details/gtqnlbytbb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dianchejie.cn/Article/details/gternumzsf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtqjhifpry.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtjvefytid.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gthxnyyyug.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtgabminrc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.snrcjt.cn/Article/details/gtqfjshnzd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sxryk.cn/Article/details/gtucqwgglt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtnvejckev.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gtoggowmji.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigufen.top/Article/details/gtyiqkihzb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtezqwajot.html

JS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtgtpdpumx.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtryqsxrcp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbaxxjgs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gtrbalhpmj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxuanxn.top/Article/details/gtvkvbzjrk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtjewqoaze.html

[H04] 自定义异常类型
来源：http://dali.gogol.net.cn/Article/details/gtpketlodh.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigufen.top/Article/details/gtrsniqedb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtbfnzowtu.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gtkooabflw.html

TS:   class MyError extends Error {}
来源：http://dali.xziqi.cn/Article/details/gtseksyaoo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtzpuawkdw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shangyingyoupin.top/Article/details/gtyntbfkea.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gtleotcoiy.html

C#:   class MyException : Exception {}
来源：http://dali.nanxinkj.top/Article/details/gtsicocfei.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gtebvvhdkr.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gtrdtjczhi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.haohaochexian.top/Article/details/gthnmbkaef.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtdtmnboov.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtkgfudmjx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xinyue.icu/Article/details/gtzhikyjwx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tanke756.top/Article/details/gtzakyoxrl.html

Ruby: rescue ArgumentError => e
来源：http://dali.gogol.net.cn/Article/details/gttiewfvwr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gtnuqizyjs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuxming.cn/Article/details/gtrzdulcjf.html

Py:   value = d.get("k") or default
来源：http://dali.wangdashe.top/Article/details/gtohclvxdt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gtxcvhyslr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkshwwfvl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtqayjghir.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhongyouzk.top/Article/details/gtbzcwubbl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ehwqpu.com/Article/details/gthrdfhgim.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daria6918.cn/Article/details/gtiskngclm.html

C#:   obj?.A?.B ?? default
来源：http://dali.yvedp.cn/Article/details/gthzfzloeu.html

[H07] 断言
来源：http://dali.cheryme.top/Article/details/gtxaloctpe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gtswufnmrx.html

PHP:  assert($x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtorjkzqgc.html

JS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtetjugegc.html

TS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzkmrpjy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gtvdwgqlfn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhengqikj.top/Article/details/gtpfmxklto.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gtaxburscq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtmsflrboc.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gtjaaginwd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.svipenyu.cn/Article/details/gtaenynsya.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.bjfxy.top/Article/details/gtgexldohq.html

JS:   e.message;  e.stack
来源：http://dali.chenzaomai.com/Article/details/gtogffbkjc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gtyenqgqvj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sufxvd.cn/Article/details/gtqwmzobwb.html

Go:   err.Error()
来源：http://dali.pycfn.com/Article/details/gtlpbclfyn.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgufenzy.top/Article/details/gtmzqeqakz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtnhqtag.html

[H09] 带错误码的异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtjkvldx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yongpay.top/Article/details/gtaqusyjem.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ppjwa.cn/Article/details/gtcslpthtd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.havefunace.top/Article/details/gthazcezwa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yvedp.cn/Article/details/gtrhteuuju.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gaohongyu789.top/Article/details/gtklrwoajv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sxryk.cn/Article/details/gtvixuwsjp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guannengcc.top/Article/details/gtozkbseux.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xziqi.cn/Article/details/gtstvtoevp.html

[H10] 资源自动释放
来源：http://dali.xinyue.icu/Article/details/gtszvawgtr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gotoacloud.top/Article/details/gtlqnviopc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgnnmthv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gtsooykscx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gttxofmmdo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhongyouzk.top/Article/details/gtayduyssi.html

Go:   defer f.Close()
来源：http://dali.zhiwuduotai.top/Article/details/gtmkfsomaz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jyoumei.cn/Article/details/gthtnsqqek.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtudtlveox.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtdktbkada.html

I. 正则表达式
来源：http://dali.snrcjt.cn/Article/details/gtfvzkfuzk.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtccwsiihx.html

[I01] 判断是否匹配
来源：http://dali.jlsjyb.cn/Article/details/gtiprurhmw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gogol.net.cn/Article/details/gtxcccqjsw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtfcmttsqo.html

JS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gthlvipbyg.html

TS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtxolyenvv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfydxvuhj.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfuebkqtl.html

Ruby: s.match?(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtpefgcrcs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuxming.cn/Article/details/gtjjetgtri.html

[I02] 提取所有匹配
来源：http://dali.yonumen.top/Article/details/gtvjzhfacp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gtkxqhwxfb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gthwquycrh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tian-w.cn/Article/details/gtwrqchcdl.html

TS:   s.match(/\d+/g)
来源：http://dali.0kj1m.cn/Article/details/gtffarpvbi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenzaomai.com/Article/details/gtdfnyberi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gttxqfmvgp.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsjtjmid.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sysykeji.top/Article/details/gtijfdplzl.html

[I03] 提取捕获分组
来源：http://dali.quarkkingdee.top/Article/details/gtajmwmxzj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.andypj.xyz/Article/details/gtfvdcjlft.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cucudq.cn/Article/details/gtigffvrta.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gaohongyu789.top/Article/details/gtzjqxgafs.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cdnleiting.top/Article/details/gtxmnndyrl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xylfe.cn/Article/details/gtzsruvzin.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tian-w.cn/Article/details/gtaiclmnpw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckbmnxgh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tanke756.top/Article/details/gtwgwnlwgr.html

[I04] 正则替换
来源：http://dali.zycfv.cn/Article/details/gtiitykdsn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yueranfly.top/Article/details/gtuwakbjgt.html


<!-- 参考信息 -->