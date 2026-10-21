代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj202588.top/Article/details/gtrsjmirwo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gtcvkqtgjo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtmzrxokum.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fengsongda.top/Article/details/gtioykrrmb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtqqtlnsai.html

TS:   path.extname("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtbkcltiuv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dianchejie.cn/Article/details/gtpmaangxz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrttlfmu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtfbwrogep.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtonpzxtft.html

[F11] 复制与移动文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzjokwsg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtzvawqrrn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhixingplan.top/Article/details/gtfjsjbnpe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtumzvyltu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtzjdnfxnz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.bjfxy.top/Article/details/gtworgwvcr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sweek.top/Article/details/gtddhboojg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtchfntfid.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.smart0.xyz/Article/details/gtdwzbgpuf.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gtqixquxnl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hysaishi.cn/Article/details/gtxqcotdjj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuanzx.com/Article/details/gtygxgpahx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftbbjccx.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gtkypntbsf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aizwys.cn/Article/details/gtfrbkjwwu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.kuanghao11.cn/Article/details/gtqrshdwca.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tianlin.xyz/Article/details/gtyvoammwe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hysaishi.cn/Article/details/gtkabqdkns.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtgzswosnu.html

G. 面向对象
来源：http://dali.hywenlv.cn/Article/details/gtjmcgeqzd.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtsqwefhme.html

[G01] 定义类
来源：http://dali.sysykeji.top/Article/details/gtjabgisui.html

Py:   class User: pass
来源：http://dali.xylfe.cn/Article/details/gtfqdxjcdt.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gtjzbgaczn.html

JS:   class User {}
来源：http://dali.tanke756.top/Article/details/gthcmjqyyg.html

TS:   class User { name: string = ""; }
来源：http://dali.dianchejie.cn/Article/details/gtpwuoffop.html

Java: class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtznvedszu.html

Go:   type User struct { Name string }
来源：http://dali.sufxvd.cn/Article/details/gtkmslqpho.html

Ruby: class User; end
来源：http://dali.yj202588.top/Article/details/gtaikmlewz.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtoerjnolo.html

[G02] 构造函数
来源：http://dali.hnqzz.top/Article/details/gtdalaejqd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gzhubu.top/Article/details/gtrkqmgrmj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shzxlz.cn/Article/details/gtpmrjvwsf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gtmhrlaowu.html

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gtjgzettkp.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtwkzejjjr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gtwecailyd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.bjfxy.top/Article/details/gtxokwbywa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtfxpsjubv.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gtnbreyxoy.html

Py:   self.name = "x"
来源：http://dali.jianghu66.top/Article/details/gtsrfhjucp.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtuygiprxd.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtdrcygzvd.html

TS:   name: string = "x";
来源：http://dali.jianghu66.top/Article/details/gtgatxswrx.html

Java: private String name;
来源：http://dali.pengpengdd.cyou/Article/details/gtmauvwqat.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhongyouzk.top/Article/details/gtsmkedcwo.html

Ruby: @name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtksphlpee.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gthylwhdmf.html

[G04] 定义方法
来源：http://dali.zycfv.cn/Article/details/gtsawlhyta.html

Py:   def greet(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtupicmcxj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtrdztgomv.html

JS:   greet() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtwtkrmbot.html

TS:   greet(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtzkxloqcm.html

Java: String greet() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtqjkegfet.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtrzbremnj.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtelzkeamx.html

C#:   public string Greet() => Name;
来源：http://dali.gogol.net.cn/Article/details/gtjxigevlq.html

[G05] 继承
来源：http://dali.iojbl.cn/Article/details/gtzgsokanr.html

Py:   class Admin(User): pass
来源：http://dali.vqdsnc.cn/Article/details/gtrfhkukmv.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtxdtsgtpq.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjtplsol.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtawibbrax.html

Java: class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtsumgbbvz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gtzylztjok.html

Ruby: class Admin < User; end
来源：http://dali.quarkkingdee.top/Article/details/gtwqylqljc.html

C#:   class Admin : User {}
来源：http://dali.birdmap.top/Article/details/gtwfmxxkhp.html

[G06] 重写方法
来源：http://dali.kuanghao11.cn/Article/details/gtwdrcrpqm.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gtcecnkufu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtapshezip.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtcskfqqgq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtucyoryop.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtxqfugpix.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangtech.top/Article/details/gtltseiowf.html

Ruby: def greet; "admin"; end
来源：http://dali.zhengqikj.top/Article/details/gtjqfhyqkv.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gtkbzvjdfy.html

[G07] 调用父类方法
来源：http://dali.yuanzhike.top/Article/details/gtshmeifcd.html

Py:   super().greet()
来源：http://dali.vqdsnc.cn/Article/details/gtrrurwueu.html

PHP:  parent::greet();
来源：http://dali.yueranfly.top/Article/details/gttwvtpees.html

JS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gtqmkvztiq.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtfmqwmwwp.html

Java: super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtyrghhomu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ppjwa.cn/Article/details/gtsgtjhlsl.html

Ruby: super
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjyifqlg.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtwvhdzddk.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gtxtytczyr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gogol.net.cn/Article/details/gtiuzvdbly.html

PHP:  public static function f() {}
来源：http://dali.0kj1m.cn/Article/details/gtnnmqqtyg.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtfdobaoaf.html

TS:   static f(): void {}
来源：http://dali.shzxlz.cn/Article/details/gtfhgzlkvi.html

Java: static void f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtjsyskfvw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigfzy.top/Article/details/gtturjzzqd.html

Ruby: def self.f; end
来源：http://dali.yj20258888.top/Article/details/gtqznnrvpw.html

C#:   public static void F() {}
来源：http://dali.nanxinkj.top/Article/details/gtyldnmcsw.html

[G09] 接口 / 抽象类
来源：http://dali.zhongyouzk.top/Article/details/gtvzhuirzp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gtyfjyhkqi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkzitaczl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.feifeiyinyue.top/Article/details/gthhnumyqm.html

TS:   interface Shape { area(): number; }
来源：http://dali.yueranfly.top/Article/details/gtuogcjyvm.html

Java: interface Shape { double area(); }
来源：http://dali.snrcjt.cn/Article/details/gtvlmuoeku.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gtnesucmhx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gtdtsjxpos.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gtlodfhjsv.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gtekdcsfep.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sysykeji.top/Article/details/gtybmhayjd.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtiaqbcdop.html

JS:   #private 字段；其余公开
来源：http://dali.aizwys.cn/Article/details/gtjxbxckfh.html

TS:   public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gttcqvgdsr.html

Java: public / protected / private / 默认包级
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivzfkvtu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yongpay.top/Article/details/gteyfwwpno.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtcqpkznlg.html

C#:   public / protected / private / internal
来源：http://dali.sysykeji.top/Article/details/gtyesttxsu.html

[G11] getter / setter
来源：http://dali.jianghu66.top/Article/details/gtrflzjxwf.html

Py:   @property 与 @x.setter
来源：http://dali.hywenlv.cn/Article/details/gtjuqkkezk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtaemwccae.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtwnjmvjjh.html

TS:   get name(): string { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gtvkflhkvv.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcvutgent.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvrcqbfb.html

Ruby: attr_accessor :name
来源：http://dali.zdqjudy.top/Article/details/gtotoltbig.html

C#:   public string Name { get; set; }
来源：http://dali.sufxvd.cn/Article/details/gttgznbvtd.html

[G12] 对象转字符串
来源：http://dali.tianlin.xyz/Article/details/gtmqxbmikk.html

Py:   def __str__(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtaxljqasy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtihojkhij.html

JS:   toString() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzwmgeqqw.html

TS:   toString(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtudrpmuvp.html

Java: @Override public String toString() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtkiiiocyd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtrdhbcvna.html

Ruby: def to_s; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtpnkgpyur.html

C#:   public override string ToString() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gtslrmepsr.html

[G13] 判断对象类型
来源：http://dali.shuidangran.top/Article/details/gtxdrjdyte.html

Py:   isinstance(u, User)
来源：http://dali.meibo888.top/Article/details/gtilyjmwrc.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtdtzaazjb.html

JS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtqvdnutwd.html

TS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtbbgwtnzv.html

Java: u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtjlkrjcxs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgufenzy.top/Article/details/gtqjvotare.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gtqhikzpty.html

C#:   u is User
来源：http://dali.jinqigufen.top/Article/details/gtxpcdsxch.html

[G14] 数据类 / record
来源：http://dali.ehwqpu.com/Article/details/gtqohqpqmy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gtzpovlmda.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aibaodan.cn/Article/details/gtknnxsblo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258.top/Article/details/gtkapygvvn.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gtepcuvycx.html

Java: record User(String name, int age) {}
来源：http://dali.hnqzz.top/Article/details/gttxoitaai.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sweek.top/Article/details/gthgaexufo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gtqoljvjjm.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gtmprvyduz.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gtmldfpcoe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.meibo888.top/Article/details/gtgjgjgmjm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.havefunace.top/Article/details/gttbgbpkvh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gtpnvpiapw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gttvekbzhh.html

Java: enum Color { RED, GREEN }
来源：http://dali.yongpay.top/Article/details/gthwcgcoid.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenjidiqi.icu/Article/details/gtsvedzrlv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xylfe.cn/Article/details/gtfsgjbwvh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtaocuxjei.html

[G16] 对象转数组 / 字典
来源：http://dali.svipenyu.cn/Article/details/gtqrxhhxtq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gtanmugjsy.html

PHP:  get_object_vars($obj);
来源：http://dali.ybcxt.top/Article/details/gtbgebphlz.html

JS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gtnvaxcxdj.html

TS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gtpvlbuxre.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hfpthk.cn/Article/details/gtmfukopcl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fengsongda.top/Article/details/gtfpebylca.html

Ruby: obj.instance_variables
来源：http://dali.daxiang520.top/Article/details/gtvlepgtlf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gtriefousn.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtfrmyvprh.html

H. 异常与错误处理
来源：http://dali.gotoacloud.top/Article/details/gtccyzsbcc.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtugesxbed.html

[H01] try / catch 基础
来源：http://dali.gaohongyu789.top/Article/details/gtgyogjqsa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.svipenyu.cn/Article/details/gtxlygvtdf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtqvzumehg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtltfheysk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtkktoixim.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gtsfkyjahg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jianghu66.top/Article/details/gttqjzkgvl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.smart0.xyz/Article/details/gtgliiobcx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhongyouzk.top/Article/details/gtovxsbfea.html

[H02] finally / ensure 收尾
来源：http://dali.aizwys.cn/Article/details/gtoxclfpzt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnxiangtu.top/Article/details/gtgzovimbw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtzbjwfzsk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtgdteipkl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtkudomvyq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtnvdqqfut.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluufhbzb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fengsongda.top/Article/details/gtojkxrfsp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtgkbhfezu.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gttnmlsujl.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gtdvhsheap.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtftwpwnnq.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtrvbgpxbj.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtyiwrlokd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtwlasapgp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbppvsqy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xziqi.cn/Article/details/gtcutxmioq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtorswzmgf.html

[H04] 自定义异常类型
来源：http://dali.pengpengdd.cyou/Article/details/gtojhcdbdr.html

Py:   class MyError(Exception): pass
来源：http://dali.xuanzx.com/Article/details/gtbfkxempm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gtrwayrxva.html

JS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnuezvsre.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gtkjpilhzg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtpcutueoq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.meibo888.top/Article/details/gtiutmycsl.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gtcslsfmvp.html

C#:   class MyException : Exception {}
来源：http://dali.chenjidiqi.icu/Article/details/gtnmflhbqg.html

[H05] 捕获特定类型
来源：http://dali.yuanzhike.top/Article/details/gtvfbsqhnh.html

Py:   except ValueError as e:
来源：http://dali.xuanzx.com/Article/details/gtfmaonzlc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gtrstghsxx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtzoktedik.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtnxahcczu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jianghu66.top/Article/details/gtzjsmvcyj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tian-w.cn/Article/details/gtsfmbsiom.html

Ruby: rescue ArgumentError => e
来源：http://dali.gaohongyu789.top/Article/details/gtfcbqgple.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gtmytoxecn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangshuangyany.cn/Article/details/gtutvuqhxa.html

Py:   value = d.get("k") or default
来源：http://dali.nanxuanxn.top/Article/details/gturdskyxk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtnbznzvip.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gtmsdtfwny.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gteyararun.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258888.top/Article/details/gthgmmorzb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gthhwuduen.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gtgareszwp.html

C#:   obj?.A?.B ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtptvepcye.html

[H07] 断言
来源：http://dali.snrcjt.cn/Article/details/gtmijokzbq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guowangkeji.top/Article/details/gtpijoxuid.html

PHP:  assert($x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtflntijnv.html

JS:   console.assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtxcylowib.html

TS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtjdaqpiye.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guannengcc.top/Article/details/gtvftbrhbd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gthdbjyfne.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jqgufenzy.top/Article/details/gtfryqzvdf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtmfrwbeik.html

[H08] 获取错误信息与堆栈
来源：http://dali.hfpthk.cn/Article/details/gttqqoebae.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ppjwa.cn/Article/details/gtkumsehxh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ivvv.top/Article/details/gtaweqldbu.html

JS:   e.message;  e.stack
来源：http://dali.ppjwa.cn/Article/details/gtnuhfewam.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jlsjyb.cn/Article/details/gtdcmriufl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzrsvxqb.html

Go:   err.Error()
来源：http://dali.snrcjt.cn/Article/details/gtibfwowhu.html

Ruby: e.message;  e.backtrace
来源：http://dali.hywenlv.cn/Article/details/gtifbsktbp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gtwgttgcsl.html

[H09] 带错误码的异常
来源：http://dali.zhoulong.xyz/Article/details/gtxmwnccoc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gtjkkyccut.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jianghu66.top/Article/details/gtedcixgil.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyrpnszg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gtvvfpgkxn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.andypj.xyz/Article/details/gtqdwjiskw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxinkj.top/Article/details/gtxpohxtdt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gtnvbmoytu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuanzhike.top/Article/details/gtrbsgvzrd.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gtgzyoezbr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yangfankeji.com/Article/details/gtozelhrrs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigfzy.top/Article/details/gtumeyqyfq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtrlxfuoss.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gtzrkdzyil.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenzaomai.com/Article/details/gtycbervkv.html

Go:   defer f.Close()
来源：http://dali.tanke756.top/Article/details/gtzhxhfsfh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daria6918.cn/Article/details/gtrnoxzfug.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtbwmhexpu.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtxcbzcfaw.html

I. 正则表达式
来源：http://dali.cucudq.cn/Article/details/gtzncxhfcv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyivltgte.html

[I01] 判断是否匹配
来源：http://dali.vqdsnc.cn/Article/details/gtvwjkyexa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gtdvacwkva.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtzruhiqud.html

JS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gtkzqrulro.html

TS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gtxskqkysh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258.top/Article/details/gtaxohxqdo.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.bjfxy.top/Article/details/gtufylhtni.html

Ruby: s.match?(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gtjllvfwvg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.andypj.xyz/Article/details/gtodunvkew.html

[I02] 提取所有匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtazsdqgzn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gtxbjjpmas.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvqqnvsk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.pengpengdd.cyou/Article/details/gtjclcvqep.html

TS:   s.match(/\d+/g)
来源：http://dali.ehwqpu.com/Article/details/gttjlnayqw.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.316326.xyz/Article/details/gtcpbfkryo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gtilbqxmwx.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuanzx.com/Article/details/gtrsuyvncx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbjtiiwp.html

[I03] 提取捕获分组
来源：http://dali.yongpay.top/Article/details/gttomcmhsr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jianghu66.top/Article/details/gtxwkwbvjp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnqzz.top/Article/details/gtsswaowqz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.cucudq.cn/Article/details/gtldvhsghd.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.quarkkingdee.top/Article/details/gtbzachuvi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xziqi.cn/Article/details/gtbqpuslrp.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guannengcc.top/Article/details/gtldkzspfc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gaohongyu789.top/Article/details/gtydecjxno.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sysykeji.top/Article/details/gtaabfkans.html

[I04] 正则替换
来源：http://dali.tianlin.xyz/Article/details/gtwbjhblnr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ehwqpu.com/Article/details/gtxwpumgej.html


<!-- 参考信息 -->