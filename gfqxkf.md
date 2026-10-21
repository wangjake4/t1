代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtczfgaruv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtewoxbefw.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gtocxwqarf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtltweubhx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xylfe.cn/Article/details/gtbmspiwmj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtalscyxug.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtvttzgrer.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtmawrxpul.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guowangkeji.top/Article/details/gtburbuyym.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtdvdkgpql.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.svipenyu.cn/Article/details/gtzsaglhys.html

[F12] CSV 读写
来源：http://dali.yonumen.top/Article/details/gtaatikhzx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkvwfqey.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cqqwz.cn/Article/details/gtzkevahth.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuxming.cn/Article/details/gtqyjvdxto.html

TS:   // 同上
来源：http://dali.snrcjt.cn/Article/details/gtypouhjey.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sxryk.cn/Article/details/gtwdphofes.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gtrbuvibeg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fzhhl.top/Article/details/gtpgksomgr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.haohaochexian.top/Article/details/gtnsdrzurb.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtdokxzhpi.html

G. 面向对象
来源：http://dali.redwolf501.top/Article/details/gtagonvyzm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtcmskpzxe.html

[G01] 定义类
来源：http://dali.ybcxt.top/Article/details/gtxulzjzuv.html

Py:   class User: pass
来源：http://dali.0kj1m.cn/Article/details/gtlttlchcc.html

PHP:  class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdafhsbo.html

JS:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtisynuwpd.html

TS:   class User { name: string = ""; }
来源：http://dali.gogol.net.cn/Article/details/gtqklkcgfw.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtnxnlbplc.html

Go:   type User struct { Name string }
来源：http://dali.wangdashe.top/Article/details/gtaivllfby.html

Ruby: class User; end
来源：http://dali.yj202588.top/Article/details/gtqdupnezy.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gtmibzhzro.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gtgryqtuvj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangdashe.top/Article/details/gtypsluksv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenlongwang.top/Article/details/gtsjbgdfau.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtglszbold.html

TS:   constructor(public name: string) {}
来源：http://dali.shangyingyoupin.top/Article/details/gttvrxsewp.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtatmwvbne.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dashuyun.cn/Article/details/gtfsvblmkf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.kuanghao11.cn/Article/details/gtcuwmzqhj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nwbrower.top/Article/details/gtkfidugxw.html

[G03] 实例属性
来源：http://dali.hfpthk.cn/Article/details/gtlxuqjbkj.html

Py:   self.name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtjesgjhtt.html

PHP:  public string $name = "x";
来源：http://dali.aibaodan.cn/Article/details/gtzrxtjqxm.html

JS:   this.name = "x";
来源：http://dali.0kj1m.cn/Article/details/gtvtjnabxh.html

TS:   name: string = "x";
来源：http://dali.yj20258.top/Article/details/gtfvscqtmv.html

Java: private String name;
来源：http://dali.sysykeji.top/Article/details/gtauyzspzb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gtbaszlfwb.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gtbvxhtvqp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xinyue.icu/Article/details/gtouoilgrw.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gtgfimhufw.html

Py:   def greet(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gtnkqfcvur.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gtdfrdvxmn.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gterqoztdf.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxchxevfp.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtlcgszxsn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtpetbrqpf.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbzgzyvt.html

C#:   public string Greet() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gtsmojdszw.html

[G05] 继承
来源：http://dali.chenlongwang.top/Article/details/gtjyjbgwij.html

Py:   class Admin(User): pass
来源：http://dali.yuxming.cn/Article/details/gtwvbpjdkd.html

PHP:  class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtnspwmdog.html

JS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtskljcdrk.html

TS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpfapspw.html

Java: class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtgjhietdy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gtwbqqwziz.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gtjwiucbmb.html

C#:   class Admin : User {}
来源：http://dali.tanke756.top/Article/details/gtslncrxog.html

[G06] 重写方法
来源：http://dali.guowangkeji.top/Article/details/gtzhycbcjs.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gttedxgrwe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtzmjiglww.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtwacjulky.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqheliap.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtcnuygmju.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnhvgkxi.html

Ruby: def greet; "admin"; end
来源：http://dali.chenzaomai.com/Article/details/gtzydyfssc.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhiwuduotai.top/Article/details/gtiwngbifj.html

[G07] 调用父类方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztaugnek.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gtuyqdmftw.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gtrknxpdjl.html

JS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gtfpexbdob.html

TS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtrpudrdhn.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gtlyykeesy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuanzx.com/Article/details/gtdtdjodxb.html

Ruby: super
来源：http://dali.cqqwz.cn/Article/details/gtiglgyqmf.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gthiasiudh.html

[G08] 静态方法与属性
来源：http://dali.yj20258.top/Article/details/gtgijjzgyl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gtvyuswtlv.html

PHP:  public static function f() {}
来源：http://dali.cashguo.top/Article/details/gtdurnmjvx.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gtyipdrvfz.html

TS:   static f(): void {}
来源：http://dali.yongpay.top/Article/details/gtzkulzjdq.html

Java: static void f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvkdklsj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258888.top/Article/details/gtpxixbzaz.html

Ruby: def self.f; end
来源：http://dali.yanxiufei.cn/Article/details/gtdvmxhwze.html

C#:   public static void F() {}
来源：http://dali.zhengqikj.top/Article/details/gtdotldmph.html

[G09] 接口 / 抽象类
来源：http://dali.snrcjt.cn/Article/details/gtpuhbjudl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gterzdqxuc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgfzy.top/Article/details/gtlbjzvoxr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gtiybfwptu.html

TS:   interface Shape { area(): number; }
来源：http://dali.smart0.xyz/Article/details/gtuelpviep.html

Java: interface Shape { double area(); }
来源：http://dali.tanke756.top/Article/details/gtxawrqpmi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yonumen.top/Article/details/gtfzsfgxet.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigufen.top/Article/details/gtwxvwxwux.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gtemrwwavw.html

[G10] 访问控制
来源：http://dali.hfpthk.cn/Article/details/gtkfqoevkt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gtlocpvmum.html

PHP:  public / protected / private
来源：http://dali.hammf.cn/Article/details/gtydyjhpgo.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gtexfqhzrt.html

TS:   public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtogfjopug.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gtntmigygp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gtmzfmvymr.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtgcccifuw.html

C#:   public / protected / private / internal
来源：http://dali.dianchejie.cn/Article/details/gtnurfcbnu.html

[G11] getter / setter
来源：http://dali.bjfxy.top/Article/details/gtiijkfrzv.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjozgmrj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtdcpjfltr.html

JS:   get name() { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gtkprjvjvk.html

TS:   get name(): string { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtogfpgnoh.html

Java: public String getName() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtdhqmetfa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtfjgvixvg.html

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gtkknufwuo.html

C#:   public string Name { get; set; }
来源：http://dali.cashguo.top/Article/details/gtozxzuyky.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtvmnmvesh.html

Py:   def __str__(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtxeawbopg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxcqxarvw.html

JS:   toString() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmoldysih.html

TS:   toString(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtvcuezuvp.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtabypslud.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtlnjxxerf.html

Ruby: def to_s; @name; end
来源：http://dali.fengsongda.top/Article/details/gtmekeieti.html

C#:   public override string ToString() => Name;
来源：http://dali.daria6918.cn/Article/details/gtzvkesdvl.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gtwnrfpfse.html

Py:   isinstance(u, User)
来源：http://dali.cucudq.cn/Article/details/gtkkeplpvg.html

PHP:  $u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtebwkncms.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtxvrmwaoo.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtxqhmkrko.html

Java: u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtlnglfupf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkchbovow.html

Ruby: u.is_a?(User)
来源：http://dali.vqdsnc.cn/Article/details/gtioabmptg.html

C#:   u is User
来源：http://dali.dianchejie.cn/Article/details/gtpaunszmy.html

[G14] 数据类 / record
来源：http://dali.sxryk.cn/Article/details/gtspyluqbg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jlsjyb.cn/Article/details/gtrwvidamm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yonumen.top/Article/details/gtguxvacvu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gtlvcirmxp.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnxiangtu.top/Article/details/gtodhiwljp.html

Java: record User(String name, int age) {}
来源：http://dali.zhixingplan.top/Article/details/gthjkjgryn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gtpruwcazc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenlongwang.top/Article/details/gtrialeibv.html

C#:   record User(string Name, int Age);
来源：http://dali.snrcjt.cn/Article/details/gtlwvucnpw.html

[G15] 枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtraowwvxp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sweek.top/Article/details/gttytzlovv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sweek.top/Article/details/gtukxyolql.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shzxlz.cn/Article/details/gtqyfczpqt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gtwwbbitsh.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258888.top/Article/details/gtqxmhdrht.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbewmhveh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258.top/Article/details/gtdoqitwtf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtouhpkjxg.html

[G16] 对象转数组 / 字典
来源：http://dali.yueranfly.top/Article/details/gtbvtryoju.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jianghu66.top/Article/details/gtkeuqvvqw.html

PHP:  get_object_vars($obj);
来源：http://dali.cqqwz.cn/Article/details/gtpvxhebdo.html

JS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtrljxfapx.html

TS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtcofmmfar.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxinkj.top/Article/details/gtwwkwcbgu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenzaomai.com/Article/details/gtkoteyvtv.html

Ruby: obj.instance_variables
来源：http://dali.hnqzz.top/Article/details/gtelwdktbz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gtxhcxdqvu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtisslgczl.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gtmqpsmgns.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gthjrkpymu.html

[H01] try / catch 基础
来源：http://dali.0kj1m.cn/Article/details/gtqadsuxbl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yanxiufei.cn/Article/details/gtdtmriyet.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cdnleiting.top/Article/details/gtffoygnhr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtuehvrsih.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gtbdviakep.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nanxinkj.top/Article/details/gtmetfxkxy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.haohaochexian.top/Article/details/gtebtjywve.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yongpay.top/Article/details/gtpejmrbbu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gtancpydcu.html

[H02] finally / ensure 收尾
来源：http://dali.yonumen.top/Article/details/gthfcxyhxb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dashuyun.cn/Article/details/gtzcowsbpi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtsuvnofzy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtsswdmjsb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtxcvztvnf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtaiazyjrs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinghuilouyu.cn/Article/details/gtwezyuafn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthwxjarp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbwvaqoq.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gtggpdjsgt.html

Py:   raise ValueError("错误信息")
来源：http://dali.bjfxy.top/Article/details/gtgrbyfdbk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtvnrlgefc.html

JS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtchrcsyxt.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtuhdbxeve.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtghpkdebu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.havefunace.top/Article/details/gtaoytszdg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cqqwz.cn/Article/details/gtcihuildm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gteoghalwc.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gtmkphdqme.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtmqrbtdjf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gtpphaxhwc.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtrmbopxfc.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtzihmnedw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtrzzscybl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gtonnokwwq.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gtyshpiysn.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gtltcmcgyr.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gteizeteyv.html

Py:   except ValueError as e:
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjnkjluq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cheryme.top/Article/details/gtlrzgfkhg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gtdpzvhxal.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtjyunxraa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tanke756.top/Article/details/gtvwjuikpo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gtwhaafwhf.html

Ruby: rescue ArgumentError => e
来源：http://dali.hammf.cn/Article/details/gtxptsiaig.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.9152youxi.cn/Article/details/gtbnbsxvmn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xziqi.cn/Article/details/gtkuguxyut.html

Py:   value = d.get("k") or default
来源：http://dali.gogol.net.cn/Article/details/gtdynuvehx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtuxaiuqwb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtkvvwkzdt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gtmddcapbi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sweek.top/Article/details/gtyydrzate.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangshuangyany.cn/Article/details/gtqqsxaipm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.havefunace.top/Article/details/gthoyrylot.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenlongwang.top/Article/details/gtaaqdgfbi.html

[H07] 断言
来源：http://dali.yvedp.cn/Article/details/gtsgifrpkv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xylfe.cn/Article/details/gtdjmlyawv.html

PHP:  assert($x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtqmximyrp.html

JS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtrdwxsmhb.html

TS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfdayaip.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxctbiyz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj202588.top/Article/details/gtclyevugj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.smart0.xyz/Article/details/gtgfvfhsoq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gtkkzwdzrz.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gthxvzzhwz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrstmkfjg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sufxvd.cn/Article/details/gtyepznnje.html

JS:   e.message;  e.stack
来源：http://dali.0kj1m.cn/Article/details/gtegzcliiv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangdashe.top/Article/details/gtqyazzgpv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sxryk.cn/Article/details/gtvooazato.html

Go:   err.Error()
来源：http://dali.jiagoushi.top/Article/details/gtzsyyugct.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258888.top/Article/details/gtzpylchxg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cdnleiting.top/Article/details/gtylhzgvip.html

[H09] 带错误码的异常
来源：http://dali.gotoacloud.top/Article/details/gtwtuykuou.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yanxiufei.cn/Article/details/gtoftptkic.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cheryme.top/Article/details/gtnrohtptd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fzhhl.top/Article/details/gtjljfzxee.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.birdmap.top/Article/details/gtvugvvsmv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gtbxpsjvzh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ehwqpu.com/Article/details/gtzsvpwjoa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gtcszxbwgv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.andypj.xyz/Article/details/gtrmnbbzmk.html

[H10] 资源自动释放
来源：http://dali.xinyue.icu/Article/details/gthdtdkuvc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ybcxt.top/Article/details/gtrfuubtgd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dashuyun.cn/Article/details/gtqgwrxqjp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.meibo888.top/Article/details/gtdrxhwqzk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtmufkdibt.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.quarkkingdee.top/Article/details/gtavgsnupp.html

Go:   defer f.Close()
来源：http://dali.dashuyun.cn/Article/details/gtcgajzzqg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.mhx1999.top/Article/details/gtknaprurw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtkntryucx.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtcsydfuif.html

I. 正则表达式
来源：http://dali.zdqjudy.top/Article/details/gtgaxeoqvj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtzshtssmi.html

[I01] 判断是否匹配
来源：http://dali.aibaodan.cn/Article/details/gtoiosisrq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtlxoozmma.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xinyue.icu/Article/details/gtakrczcug.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtihpbzjvg.html

TS:   /\d+/.test(s)
来源：http://dali.tanke756.top/Article/details/gtpbvtfmjv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sxryk.cn/Article/details/gtxosvhkxq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cucudq.cn/Article/details/gtwbnbchbp.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtlgnhjzlu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hammf.cn/Article/details/gthgveauns.html

[I02] 提取所有匹配
来源：http://dali.9152youxi.cn/Article/details/gtdridvdta.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhengqikj.top/Article/details/gtjmtsizle.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ivvv.top/Article/details/gtxtdhsnlo.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhengqikj.top/Article/details/gtxqmyqtxs.html

TS:   s.match(/\d+/g)
来源：http://dali.9152youxi.cn/Article/details/gtcmxrfgfu.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuanzhike.top/Article/details/gtbnuvidjm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gtxdicuaxu.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gtwwrdfruz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tanke756.top/Article/details/gtahqjizwy.html

[I03] 提取捕获分组
来源：http://dali.hysaishi.cn/Article/details/gtoqxpudtq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cqqwz.cn/Article/details/gtkamdftmy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.redwolf501.top/Article/details/gtikacfvgc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yueranfly.top/Article/details/gtjigdgzrm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ybcxt.top/Article/details/gtblauabxc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sweek.top/Article/details/gtqatloehs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daria6918.cn/Article/details/gtjojmwzzs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.316326.xyz/Article/details/gtyjqmqavy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dianchejie.cn/Article/details/gtvkxujezm.html

[I04] 正则替换
来源：http://dali.0kj1m.cn/Article/details/gtnquavfxq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.dashuyun.cn/Article/details/gtzhdyevxb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjozolzd.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.andypj.xyz/Article/details/gtiimnwhym.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtnfjiplik.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtkzwxtsly.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.gzhubu.top/Article/details/gtdtnpqooc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.mhx1999.top/Article/details/gtehyacqyi.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gttjhcxgdv.html

[I05] 按正则拆分
来源：http://dali.mhx1999.top/Article/details/gtzqgjchor.html


<!-- 参考信息 -->