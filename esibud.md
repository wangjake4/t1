代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtqdbntjkx.html

TS:   path.extname("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtisxjptye.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gtijkdyccf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtpmgmqqhi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtwfneunrr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtobtjgtyn.html

[F11] 复制与移动文件
来源：http://dali.tian-w.cn/Article/details/gtgkxoljzn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtdzrukvsy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fengsongda.top/Article/details/gtudynyfzj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtzssgqsjx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtwpxyrixc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtikpljnax.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnqzz.top/Article/details/gtenhhjiwg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtgfwmunoa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.iojbl.cn/Article/details/gtplsqvmft.html

[F12] CSV 读写
来源：http://dali.chenlongwang.top/Article/details/gtcjflkyzs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.feifeiyinyue.top/Article/details/gttlsjphuy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhengqikj.top/Article/details/gtjqbiwgrw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pycfn.com/Article/details/gtvoflrvmt.html

TS:   // 同上
来源：http://dali.nwbrower.top/Article/details/gtyxaxldsn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.9152youxi.cn/Article/details/gtmmronavd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yvedp.cn/Article/details/gtkrjtofkr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258.top/Article/details/gtwhejrone.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gtypxbmuih.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtsgifyhlq.html

G. 面向对象
来源：http://dali.wangdashe.top/Article/details/gtdlciahft.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtsbrgxxee.html

[G01] 定义类
来源：http://dali.aizwys.cn/Article/details/gtccxgjpdp.html

Py:   class User: pass
来源：http://dali.ehwqpu.com/Article/details/gtghctdfdi.html

PHP:  class User {}
来源：http://dali.cucudq.cn/Article/details/gtgpjpxklu.html

JS:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtcurpokug.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwrqdicf.html

Java: class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtfgadfowq.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gtekbewryw.html

Ruby: class User; end
来源：http://dali.aizwys.cn/Article/details/gtxcxynifw.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gtzoffejdi.html

[G02] 构造函数
来源：http://dali.yongpay.top/Article/details/gtusmyhyjw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shzxlz.cn/Article/details/gtokiuarqn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shuidangran.top/Article/details/gtifoisiwk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtsxsdknjd.html

TS:   constructor(public name: string) {}
来源：http://dali.aizwys.cn/Article/details/gtbrcohyxe.html

Java: User(String name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtyjwjdwys.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gaohongyu789.top/Article/details/gtcacxoqpe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtwjixncif.html

C#:   public User(string name) { Name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcrizaaji.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gtnsybcwvv.html

Py:   self.name = "x"
来源：http://dali.sxryk.cn/Article/details/gtrdgymzuv.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtdccmnfhr.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtdlwzvjbd.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtvjuyuy.html

Java: private String name;
来源：http://dali.yongpay.top/Article/details/gtapzrxjqo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258.top/Article/details/gtlfayakot.html

Ruby: @name = "x"
来源：http://dali.yueranfly.top/Article/details/gtyfevdfva.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gtpayjthdt.html

[G04] 定义方法
来源：http://dali.havefunace.top/Article/details/gtwesdfoim.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcrhyymy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtwvwtpico.html

JS:   greet() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtuvkyieii.html

TS:   greet(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtdftxnkpi.html

Java: String greet() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtvpxuksnc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtixepexec.html

Ruby: def greet; @name; end
来源：http://dali.cheryme.top/Article/details/gtqpvizbnl.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258.top/Article/details/gtabxuevmx.html

[G05] 继承
来源：http://dali.daxiang520.top/Article/details/gtnstvsfvf.html

Py:   class Admin(User): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdqeqprc.html

PHP:  class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtsklufamo.html

JS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtldfoixmq.html

TS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtdwbpjvij.html

Java: class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtgouvjkfe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dianchejie.cn/Article/details/gtwabdghdn.html

Ruby: class Admin < User; end
来源：http://dali.zdqjudy.top/Article/details/gtavifivmt.html

C#:   class Admin : User {}
来源：http://dali.jinqigufen.top/Article/details/gtvlxsonyn.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gthecnfzwh.html

Py:   def greet(self): return "admin"
来源：http://dali.zhiwuduotai.top/Article/details/gtjhkoshrl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtutejfqtk.html

JS:   greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtsppjacwi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtjfwfvzbo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtsccbutpe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.meibo888.top/Article/details/gtpdtjpdyp.html

Ruby: def greet; "admin"; end
来源：http://dali.sysykeji.top/Article/details/gtfxxwctey.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gtxbnvviwd.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gtrwchldaf.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gtiregbywk.html

PHP:  parent::greet();
来源：http://dali.9152youxi.cn/Article/details/gtkhpyqibk.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtnctiybfa.html

TS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtxthbxovn.html

Java: super.greet();
来源：http://dali.tanke756.top/Article/details/gtqpigcbgt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pycfn.com/Article/details/gtnckkpguk.html

Ruby: super
来源：http://dali.hammf.cn/Article/details/gtwuncdzxo.html

C#:   base.Greet();
来源：http://dali.yongpay.top/Article/details/gtrxsnoaec.html

[G08] 静态方法与属性
来源：http://dali.tianlin.xyz/Article/details/gtwxxqkurf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gtmtuedcna.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gtbyvgqzsl.html

JS:   static f() {}
来源：http://dali.xylfe.cn/Article/details/gtuhpneuwc.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gtirzpnabq.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gtabtnycwc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gotoacloud.top/Article/details/gtcscnoxnz.html

Ruby: def self.f; end
来源：http://dali.jyoumei.cn/Article/details/gtaxaxbshf.html

C#:   public static void F() {}
来源：http://dali.cashguo.top/Article/details/gtjyrkerhq.html

[G09] 接口 / 抽象类
来源：http://dali.haohaochexian.top/Article/details/gtnhrzuqlm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jiagoushi.top/Article/details/gtpoekzxmq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dianchejie.cn/Article/details/gtrxffwdmw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gzhubu.top/Article/details/gtyoslbgoo.html

TS:   interface Shape { area(): number; }
来源：http://dali.bjfxy.top/Article/details/gtfrrepkxh.html

Java: interface Shape { double area(); }
来源：http://dali.316326.xyz/Article/details/gtkhvyfblr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gtrkviwclf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gtxcxfdyxc.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxinkj.top/Article/details/gtprzjlvvd.html

[G10] 访问控制
来源：http://dali.cheryme.top/Article/details/gtfxmqvnbq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gogol.net.cn/Article/details/gtxntzdmmu.html

PHP:  public / protected / private
来源：http://dali.havefunace.top/Article/details/gtvyowkune.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvoybrzxi.html

TS:   public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtovufipdh.html

Java: public / protected / private / 默认包级
来源：http://dali.zycfv.cn/Article/details/gtzflgmjvb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhongyouzk.top/Article/details/gtlewtxwxj.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtlcngawds.html

C#:   public / protected / private / internal
来源：http://dali.hnqzz.top/Article/details/gtzwbgjnso.html

[G11] getter / setter
来源：http://dali.xylfe.cn/Article/details/gtqwxdyawl.html

Py:   @property 与 @x.setter
来源：http://dali.shuidangran.top/Article/details/gtjmtweefu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtthnxrddz.html

JS:   get name() { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtzjfgqrkt.html

TS:   get name(): string { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwkgxefa.html

Java: public String getName() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtfydhiwrm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtuwzonuat.html

Ruby: attr_accessor :name
来源：http://dali.shangyingyoupin.top/Article/details/gtkbrkwuwk.html

C#:   public string Name { get; set; }
来源：http://dali.birdmap.top/Article/details/gtinztbwje.html

[G12] 对象转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejjtvxsj.html

Py:   def __str__(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtspsgfbuo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtaqhaikry.html

JS:   toString() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtthfmobeo.html

TS:   toString(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtssupznoj.html

Java: @Override public String toString() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtieodsbcg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtvrlxkwsc.html

Ruby: def to_s; @name; end
来源：http://dali.ivvv.top/Article/details/gtvcyrfyth.html

C#:   public override string ToString() => Name;
来源：http://dali.haohaochexian.top/Article/details/gtmfcdtlym.html

[G13] 判断对象类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvxgpblp.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gtecvbajnk.html

PHP:  $u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtbxdswplq.html

JS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtwnerryqw.html

TS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtyvwdvyob.html

Java: u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtxrgtcwoe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnqzz.top/Article/details/gtyumvfuyp.html

Ruby: u.is_a?(User)
来源：http://dali.snrcjt.cn/Article/details/gtmfnustit.html

C#:   u is User
来源：http://dali.jlsjyb.cn/Article/details/gtjkllcayo.html

[G14] 数据类 / record
来源：http://dali.mhx1999.top/Article/details/gtipfxsorh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hfpthk.cn/Article/details/gtvkfkprbv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aizwys.cn/Article/details/gtizbxezgh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffzfgfwb.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangdashe.top/Article/details/gtiagnehoe.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gtgyzboyqa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.vqdsnc.cn/Article/details/gtiupxfwir.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfiusnap.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gtcmklpapl.html

[G15] 枚举
来源：http://dali.zhongyouzk.top/Article/details/gthuibaoax.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gthjxtjpsz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangdashe.top/Article/details/gtkwyocnje.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangtech.top/Article/details/gtlstqziej.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gtrsweivhs.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhiwuduotai.top/Article/details/gtzrqosyub.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.c1oappe.top/Article/details/gtfutaiick.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhiwuduotai.top/Article/details/gtpyovfuho.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gtfxhxswnu.html

[G16] 对象转数组 / 字典
来源：http://dali.cucudq.cn/Article/details/gtijagozow.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yvedp.cn/Article/details/gtvthsxmfk.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gtfgjptsar.html

JS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtstizgzgh.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtabatzwus.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuxming.cn/Article/details/gtxfemmwma.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.kuanghao11.cn/Article/details/gtdbvuqtqd.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gthtkgjskl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gteqzngpby.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtgygoayea.html

H. 异常与错误处理
来源：http://dali.zhengqikj.top/Article/details/gtnleppeno.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtizuxgabc.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gtihvqpfdl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tian-w.cn/Article/details/gtkzbclazr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jyoumei.cn/Article/details/gtppfurbcn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtaajovngk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtzclqdmti.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gtwxbowurz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gtqbirjrwy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhoulong.xyz/Article/details/gtemoeylse.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gtaatctgps.html

[H02] finally / ensure 收尾
来源：http://dali.zhiwuduotai.top/Article/details/gtckpmuaxi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daria6918.cn/Article/details/gtidbwmnff.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtgxfekpgg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasqdlmzw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gttywdljwu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtcgpbtpbl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gtsyyzwyip.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gtqwqsmyax.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtztaabiea.html

[H03] 主动抛出异常
来源：http://dali.daxiang520.top/Article/details/gtjlgvmkdg.html

Py:   raise ValueError("错误信息")
来源：http://dali.zdqjudy.top/Article/details/gtnuijekqm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtkaommbpj.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtepfmeyiw.html

TS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtscrfzzeb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gthkmhrwmn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fzhhl.top/Article/details/gtiavvirkv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shangyingyoupin.top/Article/details/gtrrctiodw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtdolxeeib.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gtamjnqczi.html

Py:   class MyError(Exception): pass
来源：http://dali.havefunace.top/Article/details/gtvxkyvuyn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gtjollwfrs.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtpbhccazh.html

TS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gtkboamahf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjdzmojtz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ppjwa.cn/Article/details/gtmdkinihg.html

Ruby: class MyError < StandardError; end
来源：http://dali.shuidangran.top/Article/details/gtqkhwpovb.html

C#:   class MyException : Exception {}
来源：http://dali.nanxuanxn.top/Article/details/gtohcoaqeb.html

[H05] 捕获特定类型
来源：http://dali.xuanzx.com/Article/details/gtnftnlksq.html

Py:   except ValueError as e:
来源：http://dali.nanxuanxn.top/Article/details/gtkgfoczbo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tian-w.cn/Article/details/gtojfptpbu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gturgibaxl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtboujqzyx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxequxdm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gtysqrrjbz.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gttrpqlzkx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ehwqpu.com/Article/details/gtcwqxnejo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pengpengdd.cyou/Article/details/gtxixnfayr.html

Py:   value = d.get("k") or default
来源：http://dali.smart0.xyz/Article/details/gtfwxljzfm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtzoyhlmsf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtseetiztq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtbzagwryp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gtrvhvawln.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuetiantiany.cn/Article/details/gtswxmbnik.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shuidangran.top/Article/details/gtdvnltbdv.html

C#:   obj?.A?.B ?? default
来源：http://dali.zycfv.cn/Article/details/gtcmebxtfo.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gtzlrcpwfv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gtszdbihzz.html

PHP:  assert($x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtrpwisgrq.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtzrgfcsod.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gthvnmkicl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuetiantiany.cn/Article/details/gtxluvsmhs.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aizwys.cn/Article/details/gtrglguaqj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gtaxniznaq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtqenhfnnp.html

[H08] 获取错误信息与堆栈
来源：http://dali.andypj.xyz/Article/details/gtxsosjwfg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jyoumei.cn/Article/details/gtsthabjeq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dashuyun.cn/Article/details/gtogrijouh.html

JS:   e.message;  e.stack
来源：http://dali.sxryk.cn/Article/details/gtknwalqgy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yangfankeji.com/Article/details/gtqsssfnne.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yuxming.cn/Article/details/gtykfuqwcf.html

Go:   err.Error()
来源：http://dali.hnxiangtu.top/Article/details/gtyckrgoqw.html

Ruby: e.message;  e.backtrace
来源：http://dali.ppjwa.cn/Article/details/gtpxpyoqlr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tanke756.top/Article/details/gtlnbybric.html

[H09] 带错误码的异常
来源：http://dali.chenzaomai.com/Article/details/gtzjrydbjn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hywenlv.cn/Article/details/gtytrxhbit.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.quarkkingdee.top/Article/details/gttgieezfw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhongyouzk.top/Article/details/gtqlnhesra.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.birdmap.top/Article/details/gtxmgjxjsc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cashguo.top/Article/details/gtoygbhozg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jlsjyb.cn/Article/details/gtwboyfcno.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yueranfly.top/Article/details/gtqogwwaxd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hfpthk.cn/Article/details/gtosqgocho.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gthtlxrihd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinghuilouyu.cn/Article/details/gttvindwkm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ehwqpu.com/Article/details/gtnhffuhgr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtrgcfjzes.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtexsybkpp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgwgltaf.html

Go:   defer f.Close()
来源：http://dali.jlsjyb.cn/Article/details/gtvwkjpzgn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aizwys.cn/Article/details/gtzstoppea.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtkumkmpmz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtnhlezxzi.html

I. 正则表达式
来源：http://dali.zhoulong.xyz/Article/details/gtwdasadme.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtfomkygbp.html

[I01] 判断是否匹配
来源：http://dali.hfpthk.cn/Article/details/gtkaxoteou.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gtstypuyjs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.iojbl.cn/Article/details/gtwoynftpo.html

JS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gtlokpdeyd.html

TS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gtbluddpht.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cdnleiting.top/Article/details/gtppwyitpx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gzhubu.top/Article/details/gtnpojzdop.html

Ruby: s.match?(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gtjccjtvyh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xziqi.cn/Article/details/gtazwhofdz.html

[I02] 提取所有匹配
来源：http://dali.yj20258888.top/Article/details/gtslbwsqoj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gtfiemdcxk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.haohaochexian.top/Article/details/gtdugjvlxi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuanzx.com/Article/details/gtmkwtgkoj.html

TS:   s.match(/\d+/g)
来源：http://dali.sysykeji.top/Article/details/gtvjraxmsx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhixingplan.top/Article/details/gtnolroqaa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtzoapoikc.html

Ruby: s.scan(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtvrvuoyyv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlcyjvty.html

[I03] 提取捕获分组
来源：http://dali.yj20258.top/Article/details/gtmtggqsgf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ivvv.top/Article/details/gtvrpuysst.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtjiueiikl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yonumen.top/Article/details/gtbnlnhsym.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tanke756.top/Article/details/gtewjqsqla.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xinyue.icu/Article/details/gtrytykxyr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guowangkeji.top/Article/details/gtnpuxbvec.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gogol.net.cn/Article/details/gthcgoiauc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gaohongyu789.top/Article/details/gtwbdatdsh.html

[I04] 正则替换
来源：http://dali.yanxiufei.cn/Article/details/gtrghocasj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.nanxinkj.top/Article/details/gtkiembhyg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gtbzmivugt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxuanxn.top/Article/details/gtkzywbegz.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gteblwbfxr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gtdtdkvqso.html


<!-- 参考信息 -->