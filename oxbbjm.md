代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gtmbjelcam.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtwzrddpyi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gthnhaojga.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtrrjosuob.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gtggdqdyrz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtvjgxuhib.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.birdmap.top/Article/details/gtkkecgnnw.html

[F12] CSV 读写
来源：http://dali.xuetiantiany.cn/Article/details/gtdzrnhmqo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gtkvitcbvn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hongshengwenyu.top/Article/details/gtmvteruwo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gaohongyu789.top/Article/details/gthtvndqlg.html

TS:   // 同上
来源：http://dali.zhixingplan.top/Article/details/gtoxzpopzc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gtwbhnmyso.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ivvv.top/Article/details/gtrtnmtjic.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnqzz.top/Article/details/gtexrbtgiy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jlsjyb.cn/Article/details/gthxvqboch.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmxnuama.html

G. 面向对象
来源：http://dali.pycfn.com/Article/details/gtjykrqveq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gttixshqon.html

[G01] 定义类
来源：http://dali.gotoacloud.top/Article/details/gtadzircey.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gtmndwkeem.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gtpxgeewur.html

JS:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtritpucoc.html

TS:   class User { name: string = ""; }
来源：http://dali.sweek.top/Article/details/gtfbsbolww.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysljiobe.html

Go:   type User struct { Name string }
来源：http://dali.tian-w.cn/Article/details/gtfjuawhbs.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gtrqlxfpla.html

C#:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gtnkqcbrpp.html

[G02] 构造函数
来源：http://dali.hysaishi.cn/Article/details/gtdsosfxks.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dashuyun.cn/Article/details/gtwuqamwwz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gtacqvneyk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwixfyidh.html

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gtbbldnfws.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtkhzqnafo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gogol.net.cn/Article/details/gtanucvxfv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gtymcibmra.html

C#:   public User(string name) { Name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtscedlnew.html

[G03] 实例属性
来源：http://dali.dashuyun.cn/Article/details/gtfjtrrmjn.html

Py:   self.name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtqrcbrcoy.html

PHP:  public string $name = "x";
来源：http://dali.birdmap.top/Article/details/gtcrcdkzgr.html

JS:   this.name = "x";
来源：http://dali.cheryme.top/Article/details/gtvmzecvsj.html

TS:   name: string = "x";
来源：http://dali.hnxiangtu.top/Article/details/gttiwgkgrl.html

Java: private String name;
来源：http://dali.ehwqpu.com/Article/details/gteoloumkh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gtykvjbdis.html

Ruby: @name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtmmzlohqe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuanzhike.top/Article/details/gthcablwzq.html

[G04] 定义方法
来源：http://dali.wangdashe.top/Article/details/gtklwfslkg.html

Py:   def greet(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gtyvukhjko.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslujtcmu.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtattraceg.html

TS:   greet(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtxlrjgouh.html

Java: String greet() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtourrnvdc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtlxmfmkgm.html

Ruby: def greet; @name; end
来源：http://dali.yj20258.top/Article/details/gtkppkeiel.html

C#:   public string Greet() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtyhtqacip.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gtnnitpjzo.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gtbvbgqvpt.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtpbwnhmoh.html

JS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtzsabbyab.html

TS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgskleaw.html

Java: class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnedkmtum.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gtksnjmmay.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gttqakxetc.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gtejmpcqov.html

[G06] 重写方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqcstqyz.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvqpntnx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtrkvidqvr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtohkggrst.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gthujziihi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gthpezbhah.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nwbrower.top/Article/details/gtigiagkno.html

Ruby: def greet; "admin"; end
来源：http://dali.smart0.xyz/Article/details/gtdimiedxq.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gtsfazxmju.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gtyauaqygb.html

Py:   super().greet()
来源：http://dali.hongshengwenyu.top/Article/details/gtbbgjhlxa.html

PHP:  parent::greet();
来源：http://dali.ehwqpu.com/Article/details/gttqcdjifs.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtpeokubzi.html

TS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtedpwbgwo.html

Java: super.greet();
来源：http://dali.yueranfly.top/Article/details/gtegxrpljh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtckknfj.html

Ruby: super
来源：http://dali.yj202588.top/Article/details/gtlzqjsaau.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gtjtxqswur.html

[G08] 静态方法与属性
来源：http://dali.shzxlz.cn/Article/details/gticlflhho.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cdnleiting.top/Article/details/gtkjqksaur.html

PHP:  public static function f() {}
来源：http://dali.smart0.xyz/Article/details/gthfpkqbht.html

JS:   static f() {}
来源：http://dali.svipenyu.cn/Article/details/gtxrdoyqge.html

TS:   static f(): void {}
来源：http://dali.jyoumei.cn/Article/details/gtjwjqktzv.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gtyvsmeusb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.feifeiyinyue.top/Article/details/gtwvkmabxs.html

Ruby: def self.f; end
来源：http://dali.nanxinkj.top/Article/details/gtocpkeitj.html

C#:   public static void F() {}
来源：http://dali.havefunace.top/Article/details/gtzxsgzorx.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gthjmliqaw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkotlwrm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnxiangtu.top/Article/details/gtjgmvyyfn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuanzx.com/Article/details/gtybwfdnta.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gtwqwvxjwc.html

Java: interface Shape { double area(); }
来源：http://dali.9152youxi.cn/Article/details/gtcnxchviz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aizwys.cn/Article/details/gtsgrvcihd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gtnxkgtxrc.html

C#:   interface IShape { double Area(); }
来源：http://dali.cheryme.top/Article/details/gtnrivshsz.html

[G10] 访问控制
来源：http://dali.meibo888.top/Article/details/gttdyeikvv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gtmtymsjmc.html

PHP:  public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtashudfzk.html

JS:   #private 字段；其余公开
来源：http://dali.smart0.xyz/Article/details/gtixugphla.html

TS:   public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtpabhjsbe.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gtleqkpjwm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yongpay.top/Article/details/gtvavparky.html

Ruby: public / protected / private
来源：http://dali.ivvv.top/Article/details/gtcfascedv.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gtgikshmyd.html

[G11] getter / setter
来源：http://dali.quarkkingdee.top/Article/details/gtvcqlvzpy.html

Py:   @property 与 @x.setter
来源：http://dali.cqqwz.cn/Article/details/gteptwdqqv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtbpvogvbw.html

JS:   get name() { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gtxzslaspu.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtxvnwnaku.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtmnzoonrr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtptyiktuv.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gtnxnclfnq.html

C#:   public string Name { get; set; }
来源：http://dali.sweek.top/Article/details/gtkqggmwhu.html

[G12] 对象转字符串
来源：http://dali.yuanzhike.top/Article/details/gtxxwostao.html

Py:   def __str__(self): return self.name
来源：http://dali.yanxiufei.cn/Article/details/gthugmyelt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtxbaddqao.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtjruckrjy.html

TS:   toString(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtjjzttcjx.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwjzveizg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtidqvtbzs.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtkyqdpwjp.html

C#:   public override string ToString() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtdcndcacn.html

[G13] 判断对象类型
来源：http://dali.xylfe.cn/Article/details/gtcspdgttl.html

Py:   isinstance(u, User)
来源：http://dali.ehwqpu.com/Article/details/gttauyaveb.html

PHP:  $u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtdosoludz.html

JS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtysokcvus.html

TS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtqueemctp.html

Java: u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gttibulxft.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gotoacloud.top/Article/details/gtarakcygy.html

Ruby: u.is_a?(User)
来源：http://dali.jlsjyb.cn/Article/details/gtfwhdzeda.html

C#:   u is User
来源：http://dali.fzhhl.top/Article/details/gtitwbbyoc.html

[G14] 数据类 / record
来源：http://dali.ppjwa.cn/Article/details/gteennhdjr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gtfovwcgei.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fengsongda.top/Article/details/gtrlaowvjk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gtneapihpa.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gtckmihdmw.html

Java: record User(String name, int age) {}
来源：http://dali.dianchejie.cn/Article/details/gtddaugzou.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuxming.cn/Article/details/gtxxizedrr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gtjvdlktkn.html

C#:   record User(string Name, int Age);
来源：http://dali.daria6918.cn/Article/details/gtufjyhpwu.html

[G15] 枚举
来源：http://dali.aibaodan.cn/Article/details/gtxeeifhay.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tian-w.cn/Article/details/gtrxivquly.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenlongwang.top/Article/details/gtuwbycisy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xziqi.cn/Article/details/gteiadfrea.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtiogmpxkm.html

Java: enum Color { RED, GREEN }
来源：http://dali.shuidangran.top/Article/details/gtspwurord.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gtjnxudejp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gtwnauvgac.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtthtdpfro.html

[G16] 对象转数组 / 字典
来源：http://dali.xuanzx.com/Article/details/gtzdyrfhni.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuxming.cn/Article/details/gtregsjete.html

PHP:  get_object_vars($obj);
来源：http://dali.havefunace.top/Article/details/gtaxvwjdfv.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtjcwmckml.html

TS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtuvkminvp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hongshengwenyu.top/Article/details/gtzamnqnrd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guowangkeji.top/Article/details/gtinkrihwr.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gtqixebmiz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gttwyhwvgv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvugtvkr.html

H. 异常与错误处理
来源：http://dali.andypj.xyz/Article/details/gtkfiuqxoi.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtcwamhkxf.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gtsvcasjcv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cucudq.cn/Article/details/gtraponlgr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258888.top/Article/details/gtsnprjopo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtqiwgmogm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtpndnmlfb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.vqdsnc.cn/Article/details/gtmshpoodi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedhrztng.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jyoumei.cn/Article/details/gtcmyichok.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxuanxn.top/Article/details/gtgarhkeqz.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gtcsdqydbc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabnxmvrx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtczeovdvd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigsybhwk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtvfvnfoeu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtmsuquzse.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangdashe.top/Article/details/gtacckvtkh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gtvyzwekew.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtknaxkvfj.html

[H03] 主动抛出异常
来源：http://dali.chenlongwang.top/Article/details/gtnotcyiks.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gtvejpcaak.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtlglmciyj.html

JS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtgibzndnb.html

TS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtkkverbvo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtxspgydtw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gtnpdgkdlj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hfpthk.cn/Article/details/gtduhmkayv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gthjwzwmbz.html

[H04] 自定义异常类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtredwehcd.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gthwhwbdyt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtvyzycihs.html

JS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gtuptxruut.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gtjubzvdbi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtapsnaijr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhiwuduotai.top/Article/details/gtcnzxuwnz.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gtlporfpbu.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gtppdaxtqh.html

[H05] 捕获特定类型
来源：http://dali.jiagoushi.top/Article/details/gtbyonupzt.html

Py:   except ValueError as e:
来源：http://dali.zdqjudy.top/Article/details/gtmcnmkhcn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ybcxt.top/Article/details/gtvuiqbjwp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gtbzjuxchk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gtgheudssq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gtbyavxnzb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnvqccru.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gtcwidydem.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aibaodan.cn/Article/details/gtdenccuqc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangshuangyany.cn/Article/details/gtxwovxudb.html

Py:   value = d.get("k") or default
来源：http://dali.jinghuilouyu.cn/Article/details/gtfyutntia.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gtnrtmuhyh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihmoqqlc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gtoyvasqkd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sufxvd.cn/Article/details/gtvegkevcy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwghbmfj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxcshdyi.html

C#:   obj?.A?.B ?? default
来源：http://dali.tanke756.top/Article/details/gtvayzhfiu.html

[H07] 断言
来源：http://dali.feifeiyinyue.top/Article/details/gtmvsgfyfl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.bjfxy.top/Article/details/gtefmowtco.html

PHP:  assert($x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtzskljnkm.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtvogytoyf.html

TS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtgguoxhfn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gtcfautjgx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fzhhl.top/Article/details/gtocplrrky.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yangfankeji.com/Article/details/gtqzsfrsiu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtnbppgoga.html

[H08] 获取错误信息与堆栈
来源：http://dali.yonumen.top/Article/details/gttfifxqra.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daxiang520.top/Article/details/gtxaenquun.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jyoumei.cn/Article/details/gtczsculqv.html

JS:   e.message;  e.stack
来源：http://dali.cdnleiting.top/Article/details/gteapsbaet.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwuuihjib.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigfzy.top/Article/details/gtehwojzpq.html

Go:   err.Error()
来源：http://dali.hongshengwenyu.top/Article/details/gthkqwjanu.html

Ruby: e.message;  e.backtrace
来源：http://dali.gogol.net.cn/Article/details/gtwhjvvnws.html

C#:   e.Message;  e.StackTrace
来源：http://dali.bjfxy.top/Article/details/gtqzscmvjq.html

[H09] 带错误码的异常
来源：http://dali.quarkkingdee.top/Article/details/gtedcqydcl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gtomgzuaiw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.birdmap.top/Article/details/gtgoespcpz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258888.top/Article/details/gtzfphwdpn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tianlin.xyz/Article/details/gtmwmedsqx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gtedecbfrb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jqgfzy.top/Article/details/gtiijvgdse.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jianghu66.top/Article/details/gtfjdrasqd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sysykeji.top/Article/details/gtrpauyuhr.html

[H10] 资源自动释放
来源：http://dali.sysykeji.top/Article/details/gtixyebkaz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gtpuqxlypu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuanzx.com/Article/details/gtyckohzov.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgufenzy.top/Article/details/gtvpgbyogs.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtmrcuuemo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gtdinisenh.html

Go:   defer f.Close()
来源：http://dali.c1oappe.top/Article/details/gtqvypeejv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yvedp.cn/Article/details/gtgmmalscj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtdtfqypkr.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtktldowqd.html

I. 正则表达式
来源：http://dali.yonumen.top/Article/details/gthpzfjwnr.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtpbwkctcm.html

[I01] 判断是否匹配
来源：http://dali.cashguo.top/Article/details/gtlxwnpntf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cqqwz.cn/Article/details/gtkgqlldve.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtyjplciue.html

JS:   /\d+/.test(s)
来源：http://dali.kuanghao11.cn/Article/details/gtfgvmrhvs.html

TS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gtjhrwewdl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shzxlz.cn/Article/details/gtrlnnvqrq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenzaomai.com/Article/details/gtzsmhrtlt.html

Ruby: s.match?(/\d+/)
来源：http://dali.nanxinkj.top/Article/details/gtcrxjeclg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gtflxxonyi.html

[I02] 提取所有匹配
来源：http://dali.haohaochexian.top/Article/details/gtdlctjduo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gtnshwqcwd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuanzhike.top/Article/details/gtlsujhmpi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.daria6918.cn/Article/details/gtiwwpkgad.html

TS:   s.match(/\d+/g)
来源：http://dali.shzxlz.cn/Article/details/gtldobgase.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtnozwwqak.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sysykeji.top/Article/details/gtshobcrwp.html

Ruby: s.scan(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gtcssuwkka.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jianghu66.top/Article/details/gthsczabxy.html

[I03] 提取捕获分组
来源：http://dali.kuanghao11.cn/Article/details/gtreobawhq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xylfe.cn/Article/details/gtbilkxecj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.meibo888.top/Article/details/gtpouynzyl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shangyingyoupin.top/Article/details/gtfoohfgci.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangdashe.top/Article/details/gtufqibmol.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ivvv.top/Article/details/gtthsbwsxf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yueranfly.top/Article/details/gtyprnfilc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xylfe.cn/Article/details/gthfyicsfy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj202588.top/Article/details/gtmcjdnybg.html

[I04] 正则替换
来源：http://dali.sysykeji.top/Article/details/gtnqlvseuu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jyoumei.cn/Article/details/gtvemttayl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gtplhtnxtm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtmiffimyt.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gtaeimnuii.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yanxiufei.cn/Article/details/gtyjcwfabm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gtvjdsargw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.sufxvd.cn/Article/details/gtwwsulwiy.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtyihecyut.html

[I05] 按正则拆分
来源：http://dali.havefunace.top/Article/details/gtgsusotka.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuanzx.com/Article/details/gtxrbgcowr.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yj202588.top/Article/details/gtscdutebr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gterrhrhoe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangshuangyany.cn/Article/details/gtxjmnznjx.html


<!-- 参考信息 -->