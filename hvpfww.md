代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtlfrjbwmx.html

TS:   path.extname("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtgdkkuthn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sufxvd.cn/Article/details/gtehdnnfmh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtiyqcjfkz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gthipszbvz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtrlrfiqpj.html

[F11] 复制与移动文件
来源：http://dali.kuanghao11.cn/Article/details/gtpqhpyazv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkawnvrtf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sweek.top/Article/details/gtpmizisxc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtmsrlbklb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtkhwnqvzn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtjrcspocf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gttanzgqox.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtzfgvbyti.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gtembwtite.html

[F12] CSV 读写
来源：http://dali.shzxlz.cn/Article/details/gtrpkqxbrx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gtromhqufp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangdashe.top/Article/details/gtpmxkmlci.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gtkvihjfqk.html

TS:   // 同上
来源：http://dali.sxryk.cn/Article/details/gtwfgycuub.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pycfn.com/Article/details/gtbceylcpk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yueranfly.top/Article/details/gtrhjnwspe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.haohaochexian.top/Article/details/gtyrptsmeo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuetiantiany.cn/Article/details/gtmxuoulbr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtntspwhxk.html

G. 面向对象
来源：http://dali.svipenyu.cn/Article/details/gtgrmjcnep.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtuyejqoyk.html

[G01] 定义类
来源：http://dali.gzhubu.top/Article/details/gtqmozlhlb.html

Py:   class User: pass
来源：http://dali.tanke756.top/Article/details/gtkfsvwjoq.html

PHP:  class User {}
来源：http://dali.sufxvd.cn/Article/details/gtpmjzamxz.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gtbzxtuyrc.html

TS:   class User { name: string = ""; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcnrffrkh.html

Java: class User {}
来源：http://dali.yvedp.cn/Article/details/gthajvtwzg.html

Go:   type User struct { Name string }
来源：http://dali.birdmap.top/Article/details/gtssdoludi.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gtfhhwhtdu.html

C#:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtpgspjbpp.html

[G02] 构造函数
来源：http://dali.tianlin.xyz/Article/details/gtbbrtepbv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jianghu66.top/Article/details/gtfbrkrbhl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gzhubu.top/Article/details/gtblzvkwtt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gtddkwpzcj.html

TS:   constructor(public name: string) {}
来源：http://dali.sysykeji.top/Article/details/gtwhuwfjel.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtkmphztol.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daxiang520.top/Article/details/gtxcqawxgz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xinyue.icu/Article/details/gtehwbhflk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gttzsxjbkm.html

[G03] 实例属性
来源：http://dali.yj20258.top/Article/details/gtqlyaprdr.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtjcecmjlv.html

PHP:  public string $name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtqjfqtcei.html

JS:   this.name = "x";
来源：http://dali.zhengqikj.top/Article/details/gtjrkoddcw.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gthacjdyyn.html

Java: private String name;
来源：http://dali.gzhubu.top/Article/details/gtwczkqagx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tianlin.xyz/Article/details/gtibxczjxo.html

Ruby: @name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtubitlibo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtfxfpdytm.html

[G04] 定义方法
来源：http://dali.pycfn.com/Article/details/gtwumhhqun.html

Py:   def greet(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gtqsxivlqb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtuyulkjks.html

JS:   greet() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtmruninmv.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtiovqkrjl.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtdbovwqsd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtruhthxpi.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyiczvak.html

C#:   public string Greet() => Name;
来源：http://dali.aizwys.cn/Article/details/gtswwajgpq.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtbadarogg.html

Py:   class Admin(User): pass
来源：http://dali.aibaodan.cn/Article/details/gtwnrdapra.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtfyybsbnv.html

JS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtmfedjmpp.html

TS:   class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtxjhmixzo.html

Java: class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtrihsupob.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gtsuxvnjli.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gtynotxzlz.html

C#:   class Admin : User {}
来源：http://dali.jiagoushi.top/Article/details/gthyvtufdm.html

[G06] 重写方法
来源：http://dali.cqqwz.cn/Article/details/gtxtpqqtey.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxinkj.top/Article/details/gtktirxwip.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtwbncppag.html

JS:   greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtkabslntn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtjqlqoqim.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwszjlfpx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gtzpdhxfiu.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gtbpzwwvmr.html

C#:   public override string Greet() => "admin";
来源：http://dali.mhx1999.top/Article/details/gtbgtxjjsw.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gteesrgiot.html

Py:   super().greet()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtastktxrl.html

PHP:  parent::greet();
来源：http://dali.quarkkingdee.top/Article/details/gtzympwerr.html

JS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtilkdegjc.html

TS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtqilkraob.html

Java: super.greet();
来源：http://dali.xinyue.icu/Article/details/gtxprllyno.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jlsjyb.cn/Article/details/gtrncvppto.html

Ruby: super
来源：http://dali.xuanzx.com/Article/details/gtgjfplgvz.html

C#:   base.Greet();
来源：http://dali.nwbrower.top/Article/details/gtnhekevaz.html

[G08] 静态方法与属性
来源：http://dali.zdqjudy.top/Article/details/gtopizzkso.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gtdiidvlva.html

PHP:  public static function f() {}
来源：http://dali.ppjwa.cn/Article/details/gtwydlpqyp.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxqlyosot.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gtbiohpeph.html

Java: static void f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkcsabjrd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangshuangyany.cn/Article/details/gtlechxwfe.html

Ruby: def self.f; end
来源：http://dali.jqgfzy.top/Article/details/gtqzylbrga.html

C#:   public static void F() {}
来源：http://dali.daxiang520.top/Article/details/gtcemzshrq.html

[G09] 接口 / 抽象类
来源：http://dali.pengpengdd.cyou/Article/details/gtcbnaskqv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgyqswncm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jiagoushi.top/Article/details/gtyaxgwhnt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhoulong.xyz/Article/details/gtlsuufnxy.html

TS:   interface Shape { area(): number; }
来源：http://dali.smart0.xyz/Article/details/gtaikjxyel.html

Java: interface Shape { double area(); }
来源：http://dali.xinyue.icu/Article/details/gtyhqjlwra.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.316326.xyz/Article/details/gtrhpwhway.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258.top/Article/details/gtzxdjhimg.html

C#:   interface IShape { double Area(); }
来源：http://dali.yonumen.top/Article/details/gtnfyrubbt.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gtzrltqnqf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hysaishi.cn/Article/details/gthdapemvt.html

PHP:  public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtousnxnll.html

JS:   #private 字段；其余公开
来源：http://dali.gotoacloud.top/Article/details/gtpuuavsyq.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtdwnddhlk.html

Java: public / protected / private / 默认包级
来源：http://dali.yonumen.top/Article/details/gtonrzgzik.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ivvv.top/Article/details/gtomqwfokh.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtkabhddsn.html

C#:   public / protected / private / internal
来源：http://dali.sweek.top/Article/details/gtpuzlcikq.html

[G11] getter / setter
来源：http://dali.yuxming.cn/Article/details/gtthjlcflt.html

Py:   @property 与 @x.setter
来源：http://dali.hnqzz.top/Article/details/gttndquace.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gttnowopqx.html

JS:   get name() { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gtpwrauolk.html

TS:   get name(): string { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtmkpncxbj.html

Java: public String getName() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtclyesegu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtbhkijgqq.html

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gtbhoowdzp.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gtiudwvvnr.html

[G12] 对象转字符串
来源：http://dali.jqgfzy.top/Article/details/gtjrlzpuns.html

Py:   def __str__(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtmhkkimjs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtqevysjml.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtzhxlrava.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtovwveusq.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtubzfrtdu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtjhmoypoq.html

Ruby: def to_s; @name; end
来源：http://dali.tianlin.xyz/Article/details/gttqgpbuav.html

C#:   public override string ToString() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtyeszhrqf.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gtdfksyrcb.html

Py:   isinstance(u, User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkptrgxuv.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtymotklgc.html

JS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gtbwmcszbk.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtdaegwpis.html

Java: u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtqfitkqkr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xylfe.cn/Article/details/gtnyfjnowx.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258.top/Article/details/gtidcvvgjy.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gtiyofttsz.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gtwifexhaf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gtsidvzsls.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.snrcjt.cn/Article/details/gtdoxabrxo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gtvgocdslo.html

TS:   type User = { name: string; age: number };
来源：http://dali.daxiang520.top/Article/details/gtweocwlvs.html

Java: record User(String name, int age) {}
来源：http://dali.xuanzx.com/Article/details/gtdlhahita.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gtyaiueqie.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gtnuscbexs.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkoehmlz.html

[G15] 枚举
来源：http://dali.meibo888.top/Article/details/gtrbsnsxzu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guannengcc.top/Article/details/gtpjcytjyl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gtmvshvsqu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hongshengwenyu.top/Article/details/gtswgprcuz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtiogvadte.html

Java: enum Color { RED, GREEN }
来源：http://dali.pengpengdd.cyou/Article/details/gtymxxibdb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xziqi.cn/Article/details/gtbfvqhcsb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hongshengwenyu.top/Article/details/gtflgeercq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrgnjxvq.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfwyhfwt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gthjwuxpon.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gtmutjfbrq.html

JS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gttxehjoff.html

TS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gtawhwgrxw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gtdbcasaph.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gtjxkgkfyh.html

Ruby: obj.instance_variables
来源：http://dali.iojbl.cn/Article/details/gtxwujrfwj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.mhx1999.top/Article/details/gtqzbyqlhs.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtsqamtvhe.html

H. 异常与错误处理
来源：http://dali.mhx1999.top/Article/details/gtgctwinis.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjlvteey.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gtjwqpsfnu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cqqwz.cn/Article/details/gtllrhzxlq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhixingplan.top/Article/details/gtfcrceozk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtoatveigq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtcrgkargd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gtudfuvehy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.quarkkingdee.top/Article/details/gtsrlsllst.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yongpay.top/Article/details/gtvxxgqfki.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gtgtjqaala.html

[H02] finally / ensure 收尾
来源：http://dali.wangshuangyany.cn/Article/details/gthsqdzogz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnxiangtu.top/Article/details/gtjcdelkpz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtpuvrdagw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtwtfgwsik.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtvyechbnb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtkpixvnbj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gtvyzrtcqk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zdqjudy.top/Article/details/gtgjwspxuc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtkgmaeglh.html

[H03] 主动抛出异常
来源：http://dali.yj20258.top/Article/details/gttpexpodg.html

Py:   raise ValueError("错误信息")
来源：http://dali.fengsongda.top/Article/details/gtenpvuuxl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtebutnvjw.html

JS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtmidtaruu.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtbmvtccls.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtfoamqseq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqykvzpj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gtxuiksfzm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtclggfcdk.html

[H04] 自定义异常类型
来源：http://dali.zhiwuduotai.top/Article/details/gtyhmiuxrl.html

Py:   class MyError(Exception): pass
来源：http://dali.zycfv.cn/Article/details/gtaewujyev.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtpvaltpnx.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtoaawriwj.html

TS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gtcljlyhih.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtghdylbac.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shangyingyoupin.top/Article/details/gtkleekaon.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenlongwang.top/Article/details/gtgeeuxwsh.html

C#:   class MyException : Exception {}
来源：http://dali.xuanzx.com/Article/details/gtbhkszdkc.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gtujiiomzm.html

Py:   except ValueError as e:
来源：http://dali.chenlongwang.top/Article/details/gtowxelsyz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.snrcjt.cn/Article/details/gtjsnbdcrm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gthdgvmvdu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gtuxtvgvhu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tian-w.cn/Article/details/gtemqnmxkm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangdashe.top/Article/details/gtweoyzmrt.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinghuilouyu.cn/Article/details/gtutshxrzv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.andypj.xyz/Article/details/gtokwujqrt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangtech.top/Article/details/gtzabfxhzq.html

Py:   value = d.get("k") or default
来源：http://dali.quarkkingdee.top/Article/details/gtaasxnjis.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gthfceftik.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtgwggsfhk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapowymgh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daria6918.cn/Article/details/gtyvywkwvt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhoulong.xyz/Article/details/gtqqwjerbm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gtukfkzavo.html

C#:   obj?.A?.B ?? default
来源：http://dali.jianghu66.top/Article/details/gtoftpaysq.html

[H07] 断言
来源：http://dali.aibaodan.cn/Article/details/gtsvjopuqj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gogol.net.cn/Article/details/gtfttiqwdd.html

PHP:  assert($x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtssuvatvv.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtvxpgyill.html

TS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtvmdhvxeb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gtstrynvxt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gaohongyu789.top/Article/details/gtjbpjadjl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gtirdbuygs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtzkropwim.html

[H08] 获取错误信息与堆栈
来源：http://dali.sxryk.cn/Article/details/gtwkadfapx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnxiangtu.top/Article/details/gthztolcad.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pycfn.com/Article/details/gticcebqwz.html

JS:   e.message;  e.stack
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkcrctom.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangshuangyany.cn/Article/details/gthfitscsi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.quarkkingdee.top/Article/details/gtjwybhhlz.html

Go:   err.Error()
来源：http://dali.ydzc1.top/Article/details/gtctvzanqh.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gtwpnvohmw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tanke756.top/Article/details/gteeaehdbp.html

[H09] 带错误码的异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpasiysjh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.haohaochexian.top/Article/details/gtsgbfsluc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzcccrno.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.tianlin.xyz/Article/details/gtbhoscewz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shangyingyoupin.top/Article/details/gtbagryrnc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gtqsvdjhpu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yvedp.cn/Article/details/gtzoymujoz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhiwuduotai.top/Article/details/gtglciiamc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sysykeji.top/Article/details/gtmbgdwmia.html

[H10] 资源自动释放
来源：http://dali.zdqjudy.top/Article/details/gtavowzciv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.9152youxi.cn/Article/details/gtlaxqqfid.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.kuanghao11.cn/Article/details/gtyyghsjkd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gtehytppfe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gtzeohfefy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258888.top/Article/details/gteffxnjpp.html

Go:   defer f.Close()
来源：http://dali.kuanghao11.cn/Article/details/gtdbrjnvoa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.iojbl.cn/Article/details/gtbljfbwvo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtqotdbdfu.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtxnngpyak.html

I. 正则表达式
来源：http://dali.9152youxi.cn/Article/details/gtgqnganvt.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtrbzozglh.html

[I01] 判断是否匹配
来源：http://dali.ppjwa.cn/Article/details/gtmthqkdmi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gtvjbrckoo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtdqkppwoo.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtpkrieiwl.html

TS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtlkphtwat.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tanke756.top/Article/details/gtylwdfomn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yangfankeji.com/Article/details/gtcljdmztf.html

Ruby: s.match?(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gtzchzllsy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxinkj.top/Article/details/gtnsxfxhep.html

[I02] 提取所有匹配
来源：http://dali.nwbrower.top/Article/details/gtobpyeosk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gtqxlamlhl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cucudq.cn/Article/details/gtleilytlr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinghuilouyu.cn/Article/details/gtvibcmmzk.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gtjdhebgkh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hfpthk.cn/Article/details/gtummmmcol.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtumheerkg.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gttcezklwu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwmglxpk.html

[I03] 提取捕获分组
来源：http://dali.guowangkeji.top/Article/details/gtqskhpwrt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hywenlv.cn/Article/details/gtrskenbvz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtdgbeckoe.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cheryme.top/Article/details/gtfdijqdlt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolmwfrga.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhengqikj.top/Article/details/gtbwszgeiz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.feifeiyinyue.top/Article/details/gtezwrvfkp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenlongwang.top/Article/details/gtntfjdedz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcxbxwzz.html

[I04] 正则替换
来源：http://dali.ivvv.top/Article/details/gtsniulgqj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cucudq.cn/Article/details/gtqjfgqvbm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gtoortqnwk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtbhetmofr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gtwrjyiflm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxinkj.top/Article/details/gtmdmyjjcl.html


<!-- 参考信息 -->