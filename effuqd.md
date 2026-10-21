代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtsobdujsr.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtouzhmysm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gzhubu.top/Article/details/gtevalgnqv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtyufbsjro.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtplpzqvmh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gthleuyowb.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gtcwqeqtbc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtophbjxal.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cashguo.top/Article/details/gtylgjbenf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtbyxruoxb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtkqyrynsu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zycfv.cn/Article/details/gtmgxfbevo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.feifeiyinyue.top/Article/details/gtenyhwhui.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtrbbbmwdn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gtxaxeddrj.html

[F12] CSV 读写
来源：http://dali.cucudq.cn/Article/details/gtpduoymie.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangtech.top/Article/details/gtslyicwms.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gtgbnfuhpy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yonumen.top/Article/details/gtethqmwnd.html

TS:   // 同上
来源：http://dali.gogol.net.cn/Article/details/gtkxycsagp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cheryme.top/Article/details/gtlxqzxvlx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hammf.cn/Article/details/gtgnxvqyyi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gogol.net.cn/Article/details/gtnfeaaybk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gtysnwmblu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtjfdzuxyz.html

G. 面向对象
来源：http://dali.mhx1999.top/Article/details/gtuqsrthxp.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmflaglwr.html

[G01] 定义类
来源：http://dali.meibo888.top/Article/details/gtmsfjsruc.html

Py:   class User: pass
来源：http://dali.cdnleiting.top/Article/details/gtjooyczij.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtxkmyeeqj.html

JS:   class User {}
来源：http://dali.nwbrower.top/Article/details/gtyalpmmky.html

TS:   class User { name: string = ""; }
来源：http://dali.sxryk.cn/Article/details/gtgnvfjrbj.html

Java: class User {}
来源：http://dali.yongpay.top/Article/details/gtthgcnirm.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gttqpemfwx.html

Ruby: class User; end
来源：http://dali.ivvv.top/Article/details/gtlslfyqsz.html

C#:   class User {}
来源：http://dali.xziqi.cn/Article/details/gtryfcxxhn.html

[G02] 构造函数
来源：http://dali.chenlongwang.top/Article/details/gtbeandahd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ivvv.top/Article/details/gtfmidkgwt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gtrcxdmxca.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtrvuvhwkw.html

TS:   constructor(public name: string) {}
来源：http://dali.yonumen.top/Article/details/gtpesxblos.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtvgecodde.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ydzc1.top/Article/details/gteqnvckic.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhoulong.xyz/Article/details/gtirtvbayg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cashguo.top/Article/details/gttigceahc.html

[G03] 实例属性
来源：http://dali.cheryme.top/Article/details/gtcgqxanfs.html

Py:   self.name = "x"
来源：http://dali.yueranfly.top/Article/details/gteaiufttu.html

PHP:  public string $name = "x";
来源：http://dali.hammf.cn/Article/details/gtizspwvjo.html

JS:   this.name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwwffame.html

TS:   name: string = "x";
来源：http://dali.shzxlz.cn/Article/details/gtaukewmxm.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gtpesrcwon.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gtscdnypmh.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxdmwsib.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.birdmap.top/Article/details/gtecvkepqp.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gtpbbojxuj.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtoqtrghkt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtlptzqlcb.html

JS:   greet() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtdqwhsksi.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtxsytrjaz.html

Java: String greet() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtreexxmbl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gtcmqbfkuz.html

Ruby: def greet; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtzggeqxss.html

C#:   public string Greet() => Name;
来源：http://dali.ydzc1.top/Article/details/gtmpsncxik.html

[G05] 继承
来源：http://dali.cheryme.top/Article/details/gtmresvczw.html

Py:   class Admin(User): pass
来源：http://dali.fzhhl.top/Article/details/gtlidjooyn.html

PHP:  class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtriifjzie.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtdkndhvgu.html

TS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtoslwdgnz.html

Java: class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtfbsmimmn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cheryme.top/Article/details/gtersqagcx.html

Ruby: class Admin < User; end
来源：http://dali.zycfv.cn/Article/details/gtyygtzchd.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gtwyalaunr.html

[G06] 重写方法
来源：http://dali.redwolf501.top/Article/details/gtbxgwldfu.html

Py:   def greet(self): return "admin"
来源：http://dali.zhongyouzk.top/Article/details/gtgvjonlnf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gthstwewnt.html

JS:   greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtfmmgynne.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtwhqvxnqb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gthlynsrei.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cqqwz.cn/Article/details/gtbpszgguv.html

Ruby: def greet; "admin"; end
来源：http://dali.redwolf501.top/Article/details/gtpvpaospf.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gtahowvsqq.html

[G07] 调用父类方法
来源：http://dali.jinqigfzy.top/Article/details/gtaneknoth.html

Py:   super().greet()
来源：http://dali.xinyue.icu/Article/details/gtpeqoarph.html

PHP:  parent::greet();
来源：http://dali.guowangkeji.top/Article/details/gthwcrhmim.html

JS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gtqdedgbgk.html

TS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtfacdcyhh.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gtdwgrxdal.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fengsongda.top/Article/details/gthxuqtdaw.html

Ruby: super
来源：http://dali.ppjwa.cn/Article/details/gtabxazqju.html

C#:   base.Greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtkohnpyru.html

[G08] 静态方法与属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlutyxlcd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gtxmssowgn.html

PHP:  public static function f() {}
来源：http://dali.guannengcc.top/Article/details/gtvjdxwbog.html

JS:   static f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvvmuyzos.html

TS:   static f(): void {}
来源：http://dali.cashguo.top/Article/details/gtzbftqewz.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gtokqiieyr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gtyepzzttu.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gtkghstaui.html

C#:   public static void F() {}
来源：http://dali.ybcxt.top/Article/details/gtyexkrydq.html

[G09] 接口 / 抽象类
来源：http://dali.zycfv.cn/Article/details/gttfosioja.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cucudq.cn/Article/details/gtdtwhgjnn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuetiantiany.cn/Article/details/gtejbeqelu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shangyingyoupin.top/Article/details/gtcqowdofd.html

TS:   interface Shape { area(): number; }
来源：http://dali.dashuyun.cn/Article/details/gtguqiekci.html

Java: interface Shape { double area(); }
来源：http://dali.cucudq.cn/Article/details/gtmtllnyrv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigufen.top/Article/details/gtjkakkrjy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkexmeeqq.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtsqjmhovj.html

[G10] 访问控制
来源：http://dali.jinqigufen.top/Article/details/gtncsszbra.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gtmiixwhxn.html

PHP:  public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtfywzkujb.html

JS:   #private 字段；其余公开
来源：http://dali.xinyue.icu/Article/details/gtiunwhmck.html

TS:   public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gttwhcbaik.html

Java: public / protected / private / 默认包级
来源：http://dali.aibaodan.cn/Article/details/gtpnfmjmdi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gtfsjqbquz.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtxeaqsrfe.html

C#:   public / protected / private / internal
来源：http://dali.yuxming.cn/Article/details/gtzqawwtzv.html

[G11] getter / setter
来源：http://dali.jyoumei.cn/Article/details/gtnmzvxihd.html

Py:   @property 与 @x.setter
来源：http://dali.sufxvd.cn/Article/details/gtrhcoiuhq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtrqqyswvk.html

JS:   get name() { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gtsljhxbrq.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoauhapbo.html

Java: public String getName() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtzgbvtigr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtwnrupurh.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gtzcymqblp.html

C#:   public string Name { get; set; }
来源：http://dali.iojbl.cn/Article/details/gtpclkdvrs.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtthmlaeko.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtmgwpnttc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzclzsqqo.html

JS:   toString() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtzgbkfvhe.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtwpxfzaad.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmlnpupxs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtgikvlrjz.html

Ruby: def to_s; @name; end
来源：http://dali.meibo888.top/Article/details/gtxpnmxelx.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gtjsuntgur.html

[G13] 判断对象类型
来源：http://dali.andypj.xyz/Article/details/gtftcygsib.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gtuoxvczpt.html

PHP:  $u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtbsmccccb.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtqwedwtmy.html

TS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtbnivnxha.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gtfdbmhzzr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gttcxwdrxw.html

Ruby: u.is_a?(User)
来源：http://dali.cucudq.cn/Article/details/gtuosttjji.html

C#:   u is User
来源：http://dali.zhijiandao.cn/Article/details/gtxyzekyfo.html

[G14] 数据类 / record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtreqtwkbv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tian-w.cn/Article/details/gtjchykvii.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.svipenyu.cn/Article/details/gtcebrmpie.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gtimbqzvhu.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258.top/Article/details/gthhypgfhf.html

Java: record User(String name, int age) {}
来源：http://dali.zhoulong.xyz/Article/details/gtzqywpkix.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jianghu66.top/Article/details/gtwxskcmak.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gtwcnplbzq.html

C#:   record User(string Name, int Age);
来源：http://dali.sysykeji.top/Article/details/gtjmgmfktb.html

[G15] 枚举
来源：http://dali.cashguo.top/Article/details/gtqwguoozb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hywenlv.cn/Article/details/gtaaxfsuop.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.meibo888.top/Article/details/gtwyqkdmkt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj202588.top/Article/details/gtqzhgyhew.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gtsuqonslz.html

Java: enum Color { RED, GREEN }
来源：http://dali.yongpay.top/Article/details/gtzipdmztv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daxiang520.top/Article/details/gtvwbbhqok.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gtmwibvtag.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtyhsiqput.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gtrszuqlle.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hongshengwenyu.top/Article/details/gtumutqhhx.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtnqumixcq.html

JS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gttridxmgv.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gticuxrhag.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ehwqpu.com/Article/details/gtwynqjcug.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gaohongyu789.top/Article/details/gtrqiqcpgt.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gtoxxwvtgi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtziboilgv.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtokijname.html

H. 异常与错误处理
来源：http://dali.yj202588.top/Article/details/gtyjhdmpnu.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtiahrvsek.html

[H01] try / catch 基础
来源：http://dali.nanxuanxn.top/Article/details/gtqkxqigic.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xinyue.icu/Article/details/gtahnuqfhc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gtarzelcwj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtksrbbvic.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtnwbczmtj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangdashe.top/Article/details/gtlwtuguit.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.iojbl.cn/Article/details/gtombzoovn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgfzy.top/Article/details/gtdtcnyhwb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gtblujetxz.html

[H02] finally / ensure 收尾
来源：http://dali.ybcxt.top/Article/details/gtlrygjpcb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sufxvd.cn/Article/details/gtiaphonek.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gthdsvheow.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gturtibdvp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtzvhxbadp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gttfnrvgme.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhengqikj.top/Article/details/gtdljxpuay.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cqqwz.cn/Article/details/gtwfravzrd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gttzvdjwms.html

[H03] 主动抛出异常
来源：http://dali.zycfv.cn/Article/details/gtrdjkbawp.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuanzx.com/Article/details/gtkpsgxhmw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtazllgmgr.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtidkxhfyy.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtzejnpzdp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtfibpticj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhixingplan.top/Article/details/gtrvfgxyiy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sufxvd.cn/Article/details/gtdyzzmzuo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtmkeskvwf.html

[H04] 自定义异常类型
来源：http://dali.hnxiangtu.top/Article/details/gtqpefhxdl.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gtqfienygk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtehrpfpzl.html

JS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gtaonlihoy.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtjgwjrdxa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtawcuztzr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shuidangran.top/Article/details/gtgichmrpz.html

Ruby: class MyError < StandardError; end
来源：http://dali.jianghu66.top/Article/details/gtyaswoitk.html

C#:   class MyException : Exception {}
来源：http://dali.gaohongyu789.top/Article/details/gtlnwmtfzp.html

[H05] 捕获特定类型
来源：http://dali.zdqjudy.top/Article/details/gtviuyyrxf.html

Py:   except ValueError as e:
来源：http://dali.gzhubu.top/Article/details/gtazlpnsvx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangdashe.top/Article/details/gtfzzasscr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtsfcynyjt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gtundzzpcd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cashguo.top/Article/details/gtjrmcgscb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xylfe.cn/Article/details/gtqebwauio.html

Ruby: rescue ArgumentError => e
来源：http://dali.ppjwa.cn/Article/details/gtjhsxrjoh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.havefunace.top/Article/details/gtpciequrw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sufxvd.cn/Article/details/gtvvgvdzat.html

Py:   value = d.get("k") or default
来源：http://dali.smart0.xyz/Article/details/gtgktapyfa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gthrxbdhtr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtuquvedfu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gtcbwiikob.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jyoumei.cn/Article/details/gtfpsfmgqj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gtneakpbgp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.pycfn.com/Article/details/gtyqlorslw.html

C#:   obj?.A?.B ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtwgqqmmuc.html

[H07] 断言
来源：http://dali.shangyingyoupin.top/Article/details/gtiimliacs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nwbrower.top/Article/details/gtibpnyryq.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtfoffliaa.html

JS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtpthqthwi.html

TS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtqzeqproc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cashguo.top/Article/details/gtuldfeuis.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gtbxjccfbe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangshuangyany.cn/Article/details/gtznprqeah.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtxffqbbdj.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuxming.cn/Article/details/gtczwzacum.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.redwolf501.top/Article/details/gtzjyuzwwt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangshuangyany.cn/Article/details/gtvdxizgfg.html

JS:   e.message;  e.stack
来源：http://dali.sysykeji.top/Article/details/gtgfkkblaf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangdashe.top/Article/details/gtllvptgan.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.mhx1999.top/Article/details/gthyahxjwl.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gtrjeloope.html

Ruby: e.message;  e.backtrace
来源：http://dali.nanxinkj.top/Article/details/gtlxzyiqfi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pycfn.com/Article/details/gtsejujlwq.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gtdoxcadzv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hammf.cn/Article/details/gtkharpivx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xziqi.cn/Article/details/gtgobipqnl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.svipenyu.cn/Article/details/gtfhoihqbr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ybcxt.top/Article/details/gtboudfczl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdguadjsn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yangfankeji.com/Article/details/gtdvbbfnpb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guowangkeji.top/Article/details/gtpjoaokkf.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hywenlv.cn/Article/details/gtqlbboqaw.html

[H10] 资源自动释放
来源：http://dali.kuanghao11.cn/Article/details/gtrrmfzwko.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gtifzzmnkl.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ivvv.top/Article/details/gtutwhloka.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtafbgphnh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtwspqlnfg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gtisrsmuba.html

Go:   defer f.Close()
来源：http://dali.shuidangran.top/Article/details/gtdljsefuv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.chenzaomai.com/Article/details/gttrouqvvy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtsqljngzk.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtohowiwmd.html

I. 正则表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqxkdbqp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtemafdtou.html

[I01] 判断是否匹配
来源：http://dali.hfpthk.cn/Article/details/gtrpkjrstu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtlbbvtgnq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ybcxt.top/Article/details/gtykgiynyq.html

JS:   /\d+/.test(s)
来源：http://dali.zdqjudy.top/Article/details/gtpgqkgnqh.html

TS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtelbgndyg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.aibaodan.cn/Article/details/gtsligybgy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gtdqtgeucf.html

Ruby: s.match?(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gturnrokrj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yonumen.top/Article/details/gtdgxwexkm.html

[I02] 提取所有匹配
来源：http://dali.ydzc1.top/Article/details/gtzssoizvn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtnltmrgno.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xylfe.cn/Article/details/gtzictomjv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhongyouzk.top/Article/details/gtcoalcfze.html

TS:   s.match(/\d+/g)
来源：http://dali.daria6918.cn/Article/details/gtwlrfnkdd.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258.top/Article/details/gtrpvqqeqq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtduintldv.html

Ruby: s.scan(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtpvlldrpf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daria6918.cn/Article/details/gtessarbbq.html

[I03] 提取捕获分组
来源：http://dali.cashguo.top/Article/details/gtkpfjnsuf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhengqikj.top/Article/details/gtqxksvgrv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.wangshuangyany.cn/Article/details/gtfpnpkxjj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gtdewmoary.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hongshengwenyu.top/Article/details/gthdvfprtm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cdnleiting.top/Article/details/gtesusguvs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gtrscifebw.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jlsjyb.cn/Article/details/gtldvmdswa.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gtgyxyixcc.html

[I04] 正则替换
来源：http://dali.jinqigufen.top/Article/details/gtwptwamoz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yueranfly.top/Article/details/gthezjiogi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jianghu66.top/Article/details/gtfodhkwdc.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gtuhjdwtbp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtsqfwyykn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.redwolf501.top/Article/details/gtobhilnpn.html


<!-- 参考信息 -->