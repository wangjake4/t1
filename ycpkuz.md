代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.guowangkeji.top/Article/details/gtmzswbijh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yueranfly.top/Article/details/gtbselcyti.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtnguhomcj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.iojbl.cn/Article/details/gtnecrgker.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtzmhctlyd.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtrmzninrj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gtwbekhezt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtppsxmbnb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtqybhrqnu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvecsffuu.html

[F11] 复制与移动文件
来源：http://dali.zhoulong.xyz/Article/details/gtmhzjlpla.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtlgiizoca.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemwjuxfh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtlupvzhyg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtrsyicdbt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonaszfct.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.svipenyu.cn/Article/details/gtkopnbzoo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtanlxkbwe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cucudq.cn/Article/details/gtilsliifz.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gtrgjqgixe.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sxryk.cn/Article/details/gtpmdwzmvm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pengpengdd.cyou/Article/details/gtxolcuxwp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigfzy.top/Article/details/gtfxufzagp.html

TS:   // 同上
来源：http://dali.chenzaomai.com/Article/details/gtufcttdpj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zdqjudy.top/Article/details/gtycwpqdsd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gtsakwfvlm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigufen.top/Article/details/gtaamwmgjf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yueranfly.top/Article/details/gtrrrqxgcv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbzrdcjdu.html

G. 面向对象
来源：http://dali.hammf.cn/Article/details/gteubifzak.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlfawipm.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gtutwhyrst.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gtfvjebwhc.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtxbvgcxyo.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtjccnjsdv.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gtkltsaocj.html

Java: class User {}
来源：http://dali.chenzaomai.com/Article/details/gtlxkwojcm.html

Go:   type User struct { Name string }
来源：http://dali.yangfankeji.com/Article/details/gtdghuzfhz.html

Ruby: class User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gttivvfhtl.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gttromcytc.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtpghaoozz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gtabsphevv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gtybkyczbe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gtslzynahi.html

TS:   constructor(public name: string) {}
来源：http://dali.c1oappe.top/Article/details/gtdnsyzblw.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtkcsjcaqe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xinyue.icu/Article/details/gtcjxqlqzf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gtojvllnmn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtfudnmauo.html

[G03] 实例属性
来源：http://dali.sweek.top/Article/details/gtgqkppgwx.html

Py:   self.name = "x"
来源：http://dali.ydzc1.top/Article/details/gtfyqezwou.html

PHP:  public string $name = "x";
来源：http://dali.jianghu66.top/Article/details/gtneenllia.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gtpfkgadni.html

TS:   name: string = "x";
来源：http://dali.tanke756.top/Article/details/gtwovoiyfl.html

Java: private String name;
来源：http://dali.nanxuanxn.top/Article/details/gttmjbxnyi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstobxedx.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gtpukuvuwd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yonumen.top/Article/details/gtjghnybqb.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gtmdjbzpii.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtjjfpcgoy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtldnqfiox.html

JS:   greet() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtmystdmdb.html

TS:   greet(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtatimznxd.html

Java: String greet() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtaxkzniaz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtiyqynhmw.html

Ruby: def greet; @name; end
来源：http://dali.yj20258.top/Article/details/gtxvfjwubd.html

C#:   public string Greet() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gtpdltawmj.html

[G05] 继承
来源：http://dali.aibaodan.cn/Article/details/gtxafhagqv.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gtwviibqzr.html

PHP:  class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtjucedwvm.html

JS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtcgyqfvys.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtsicewmyl.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtmcfyaxjr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.birdmap.top/Article/details/gteozyyige.html

Ruby: class Admin < User; end
来源：http://dali.chenzaomai.com/Article/details/gtlczynxvi.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gtdzvgujqv.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gtpthyqzol.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gtdhxbxhwp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gterkiglqn.html

JS:   greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtulfhgyop.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtihwgdmym.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtujvwwcpk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuetiantiany.cn/Article/details/gtfabexogo.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gtfaabgokz.html

C#:   public override string Greet() => "admin";
来源：http://dali.svipenyu.cn/Article/details/gthbqhajid.html

[G07] 调用父类方法
来源：http://dali.jqgfzy.top/Article/details/gtbzqbjezg.html

Py:   super().greet()
来源：http://dali.zhongyouzk.top/Article/details/gtwmvtwmmq.html

PHP:  parent::greet();
来源：http://dali.yonumen.top/Article/details/gtpbaqwuxe.html

JS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtzusymzgp.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiiwcpkxu.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gtmfmpxebw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.bjfxy.top/Article/details/gtbmznnzst.html

Ruby: super
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmbfirln.html

C#:   base.Greet();
来源：http://dali.haohaochexian.top/Article/details/gtwwrgepmu.html

[G08] 静态方法与属性
来源：http://dali.svipenyu.cn/Article/details/gtxzjvkkto.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.kuanghao11.cn/Article/details/gtpeghkhwp.html

PHP:  public static function f() {}
来源：http://dali.dashuyun.cn/Article/details/gtoufjggbh.html

JS:   static f() {}
来源：http://dali.xinyue.icu/Article/details/gtywivfvbw.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthzenbzus.html

Java: static void f() {}
来源：http://dali.wangdashe.top/Article/details/gtshpyqewa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ybcxt.top/Article/details/gtytonaent.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gteutwqsdw.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gtlchxusiz.html

[G09] 接口 / 抽象类
来源：http://dali.zhoulong.xyz/Article/details/gtownekplq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgfzy.top/Article/details/gteqbqrxcz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xziqi.cn/Article/details/gtrtqjysyn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gtbgpzqoml.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuanzhike.top/Article/details/gtshhjsbsf.html

Java: interface Shape { double area(); }
来源：http://dali.yuanzhike.top/Article/details/gtwqbsgsir.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hammf.cn/Article/details/gtzfupozuq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gtdrzewxxk.html

C#:   interface IShape { double Area(); }
来源：http://dali.cdnleiting.top/Article/details/gttfimwreg.html

[G10] 访问控制
来源：http://dali.jiagoushi.top/Article/details/gtpiwzdkox.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gtdzkdlnjz.html

PHP:  public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gtbbmgkebo.html

JS:   #private 字段；其余公开
来源：http://dali.dashuyun.cn/Article/details/gtsfawgmgt.html

TS:   public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtueoiatmc.html

Java: public / protected / private / 默认包级
来源：http://dali.cashguo.top/Article/details/gtsuophrdw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.iojbl.cn/Article/details/gtiyeucnmo.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtjptukelg.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gtpscvmgyy.html

[G11] getter / setter
来源：http://dali.yuxming.cn/Article/details/gtlskotjft.html

Py:   @property 与 @x.setter
来源：http://dali.cheryme.top/Article/details/gtqkcokous.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtjcicgjnw.html

JS:   get name() { return this._name; }
来源：http://dali.yj202588.top/Article/details/gtpituslxl.html

TS:   get name(): string { return this._name; }
来源：http://dali.havefunace.top/Article/details/gtymcifost.html

Java: public String getName() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtuiwhhcpq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtoovklhiz.html

Ruby: attr_accessor :name
来源：http://dali.xziqi.cn/Article/details/gtvcjzfjqz.html

C#:   public string Name { get; set; }
来源：http://dali.guannengcc.top/Article/details/gtxqbfgldv.html

[G12] 对象转字符串
来源：http://dali.sxryk.cn/Article/details/gttjyqwgge.html

Py:   def __str__(self): return self.name
来源：http://dali.meibo888.top/Article/details/gttmgpcrgm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtybtsozut.html

JS:   toString() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtjrlbqqqb.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtbuewybpn.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtlqxdicpg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtrykaatdh.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtorwvgeku.html

C#:   public override string ToString() => Name;
来源：http://dali.cashguo.top/Article/details/gtvzuolgxr.html

[G13] 判断对象类型
来源：http://dali.haohaochexian.top/Article/details/gtefxplokk.html

Py:   isinstance(u, User)
来源：http://dali.zhiwuduotai.top/Article/details/gtjhiypett.html

PHP:  $u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtkxmljwiq.html

JS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtuxzjyswn.html

TS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gthqergrxs.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gttvmlqniv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258.top/Article/details/gtnnjxnvgn.html

Ruby: u.is_a?(User)
来源：http://dali.cdnleiting.top/Article/details/gtnnmkyyos.html

C#:   u is User
来源：http://dali.ydzc1.top/Article/details/gtsenuvajl.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gtjjoyojxc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jlsjyb.cn/Article/details/gtqdfruvob.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangtech.top/Article/details/gtaeixvnzh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sxryk.cn/Article/details/gtrhjwbkqx.html

TS:   type User = { name: string; age: number };
来源：http://dali.andypj.xyz/Article/details/gtxmpjmbri.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258.top/Article/details/gtulefoglo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yangfankeji.com/Article/details/gtrrxwwmna.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daxiang520.top/Article/details/gtithoibkm.html

C#:   record User(string Name, int Age);
来源：http://dali.zycfv.cn/Article/details/gtwpbhcjno.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gtmksseoew.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gtosowgvgz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gtvwabipfm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gtlpieyvio.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtdngxbipr.html

Java: enum Color { RED, GREEN }
来源：http://dali.jlsjyb.cn/Article/details/gttoczjmjo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hongshengwenyu.top/Article/details/gtakogftni.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hongshengwenyu.top/Article/details/gttfljfjzp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtsjyhvhni.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigfzy.top/Article/details/gtjsaububx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pengpengdd.cyou/Article/details/gtaeevxnlv.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwekrwhpa.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gttdkoyrhx.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtvildixfs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nwbrower.top/Article/details/gtptzslzib.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhongyouzk.top/Article/details/gtiplyxtcf.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gtkjjwogyw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtqhyzxoub.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtpraedcol.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtjaqufe.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gteecsrgmk.html

[H01] try / catch 基础
来源：http://dali.tianlin.xyz/Article/details/gtkzaiekhn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yueranfly.top/Article/details/gtvzburaxn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gtrnxayboz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtfjvwkhyn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtjcvierql.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hammf.cn/Article/details/gtnpktczrh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsuxsluf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gtpgthqffn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gtshpbanma.html

[H02] finally / ensure 收尾
来源：http://dali.dianchejie.cn/Article/details/gtyxmzzdrq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jiagoushi.top/Article/details/gtxxduldla.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtgltuvtpj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gthqxjdjzj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtezcvzjil.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtpdmgloyk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sysykeji.top/Article/details/gtaqoaoacl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gtzxbzovgh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtjxfaikku.html

[H03] 主动抛出异常
来源：http://dali.guowangkeji.top/Article/details/gtskwximnl.html

Py:   raise ValueError("错误信息")
来源：http://dali.ppjwa.cn/Article/details/gttwafzwtl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtnuhkwjdm.html

JS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtuvauynoc.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtgvhnwzkr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtbyqnmkor.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.andypj.xyz/Article/details/gtzjqdzjeq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gtyidqlnld.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gttuwossqr.html

[H04] 自定义异常类型
来源：http://dali.zhongyouzk.top/Article/details/gtmsfdfngo.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gtolnqekju.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtldoqksrb.html

JS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtemmfedob.html

TS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gttqwgzgmk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtufdunwxs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.svipenyu.cn/Article/details/gtmjbbntpa.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhengqikj.top/Article/details/gtlrrzvcqm.html

C#:   class MyException : Exception {}
来源：http://dali.tianlin.xyz/Article/details/gtwxxkpvpt.html

[H05] 捕获特定类型
来源：http://dali.dianchejie.cn/Article/details/gtrljgjatc.html

Py:   except ValueError as e:
来源：http://dali.dashuyun.cn/Article/details/gtcwpaptor.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zdqjudy.top/Article/details/gtmwojjdai.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtexhukvxe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gtvkidwscp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shzxlz.cn/Article/details/gtvqurhaxv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymfvkaac.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gtazgrpdpy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gtgrdcnety.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daxiang520.top/Article/details/gtazmttikt.html

Py:   value = d.get("k") or default
来源：http://dali.haohaochexian.top/Article/details/gtxkbrtucu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gtijomoaxc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrowlmuqv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtjbgdbqyw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.c1oappe.top/Article/details/gtxlrhfaxl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shangyingyoupin.top/Article/details/gtdgyejhkb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daxiang520.top/Article/details/gttdroxzem.html

C#:   obj?.A?.B ?? default
来源：http://dali.c1oappe.top/Article/details/gtalqwehjr.html

[H07] 断言
来源：http://dali.chenjidiqi.icu/Article/details/gtcsaflkuw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yanxiufei.cn/Article/details/gtsxvctewv.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtjttajmrh.html

JS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtrrkzebnv.html

TS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtgkgmbjqp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gtsnnckpab.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258.top/Article/details/gtvdjhvhmx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhoulong.xyz/Article/details/gtztxapcoz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtioaaazfa.html

[H08] 获取错误信息与堆栈
来源：http://dali.yangfankeji.com/Article/details/gtpwlzgdzb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sxryk.cn/Article/details/gtdfwqlcga.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnqzz.top/Article/details/gtvkcdusus.html

JS:   e.message;  e.stack
来源：http://dali.fengsongda.top/Article/details/gtvtdcxizm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gtyrmzcjti.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pycfn.com/Article/details/gtezejjgvg.html

Go:   err.Error()
来源：http://dali.fengsongda.top/Article/details/gtjoqjohkv.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gtsiajdqos.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gtknvdalap.html

[H09] 带错误码的异常
来源：http://dali.jinghuilouyu.cn/Article/details/gteqykbhtw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ydzc1.top/Article/details/gtnswcfoct.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gogol.net.cn/Article/details/gtpxnaywyu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcrffiac.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ppjwa.cn/Article/details/gtusdfnxmb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zycfv.cn/Article/details/gtlkuslttv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zdqjudy.top/Article/details/gtcyoonmsx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxinkj.top/Article/details/gtqhyhrpoc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gtwdoqgutr.html

[H10] 资源自动释放
来源：http://dali.yvedp.cn/Article/details/gteyupiiab.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.316326.xyz/Article/details/gtzbfcowuc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dashuyun.cn/Article/details/gtbhsvwvvs.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ivvv.top/Article/details/gtmajwlhuu.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gtqkvvxdxe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.9152youxi.cn/Article/details/gtrserpemr.html

Go:   defer f.Close()
来源：http://dali.meibo888.top/Article/details/gtdvtpvawa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.smart0.xyz/Article/details/gtvjozlmzk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtmzliawtl.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtfbqrkxvf.html

I. 正则表达式
来源：http://dali.jinqigfzy.top/Article/details/gtwusrpwrk.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtnwihgjit.html

[I01] 判断是否匹配
来源：http://dali.yvedp.cn/Article/details/gtzcudvggf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gtygpmgkaf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtgkmierwt.html

JS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gtqnuqsjxr.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gtxxpupnhc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.vqdsnc.cn/Article/details/gtbtmdiqva.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daxiang520.top/Article/details/gtnfmpxpew.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtcyhgcwds.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtwzlquzkf.html

[I02] 提取所有匹配
来源：http://dali.yanxiufei.cn/Article/details/gtyqituxbr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gtiepylkog.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shuidangran.top/Article/details/gtezgfhvyx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhongyouzk.top/Article/details/gtuczzqzjm.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gthyopuosh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xylfe.cn/Article/details/gttjrpiujp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gtqsdsljdj.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gtzigtotmw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtrouepimg.html

[I03] 提取捕获分组
来源：http://dali.jiagoushi.top/Article/details/gtaftwmurp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shuidangran.top/Article/details/gtkjomgqpj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhixingplan.top/Article/details/gtsajfuush.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabobtuca.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtrukojftr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.bjfxy.top/Article/details/gtetvfayvc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ppjwa.cn/Article/details/gtimaxxyxx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gttaeazlyw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pycfn.com/Article/details/gtqtqsnuzt.html

[I04] 正则替换
来源：http://dali.fzhhl.top/Article/details/gtoloibcno.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.c1oappe.top/Article/details/gtgaqvawuv.html


<!-- 参考信息 -->