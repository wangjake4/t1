代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtcquqgaev.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtegvaiyqu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jyoumei.cn/Article/details/gttbwwcocj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtwvwwavpw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtnmijjniu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtteavjkyu.html

[F11] 复制与移动文件
来源：http://dali.guannengcc.top/Article/details/gtrcrmolvi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtfvvvirqx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zycfv.cn/Article/details/gteyzripcr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtsipkvbzr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtpitwlbea.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gtexvedqzy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.meibo888.top/Article/details/gtxdpcofyg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtsxemoxed.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xziqi.cn/Article/details/gtthbqmaad.html

[F12] CSV 读写
来源：http://dali.yuxming.cn/Article/details/gtyuwuewmf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangtech.top/Article/details/gttfcjufvf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.snrcjt.cn/Article/details/gtvngjjwco.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.iojbl.cn/Article/details/gtjlrtyqoh.html

TS:   // 同上
来源：http://dali.shzxlz.cn/Article/details/gtzxhwnunr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gtvqadbqot.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cqqwz.cn/Article/details/gtipfpdmqr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gttyjabpie.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hywenlv.cn/Article/details/gtyukqfuvm.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtqwqyzsim.html

G. 面向对象
来源：http://dali.yj202588.top/Article/details/gtifvcsxzs.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtcogkldlc.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gtplrkasbt.html

Py:   class User: pass
来源：http://dali.ehwqpu.com/Article/details/gtljfeifxy.html

PHP:  class User {}
来源：http://dali.gogol.net.cn/Article/details/gtqtoxksps.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtsnlgebkg.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqvhuxrh.html

Java: class User {}
来源：http://dali.sxryk.cn/Article/details/gtuopavjlh.html

Go:   type User struct { Name string }
来源：http://dali.jqgufenzy.top/Article/details/gtkqlaujcm.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gtldzekuma.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtmhrgqhkj.html

[G02] 构造函数
来源：http://dali.meibo888.top/Article/details/gtpfyyzduh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jianghu66.top/Article/details/gtntpashdn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgfzy.top/Article/details/gteilekeaz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtxjtkjpvk.html

TS:   constructor(public name: string) {}
来源：http://dali.vqdsnc.cn/Article/details/gtxcwuvkto.html

Java: User(String name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gthlozroye.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jianghu66.top/Article/details/gtgbeyrmth.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daria6918.cn/Article/details/gttfevibfk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ivvv.top/Article/details/gtwipspkjs.html

[G03] 实例属性
来源：http://dali.smart0.xyz/Article/details/gtmcqocjrd.html

Py:   self.name = "x"
来源：http://dali.sysykeji.top/Article/details/gtvzunlutz.html

PHP:  public string $name = "x";
来源：http://dali.smart0.xyz/Article/details/gtuchuezge.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtvmsbjswv.html

TS:   name: string = "x";
来源：http://dali.dashuyun.cn/Article/details/gtohdcoocz.html

Java: private String name;
来源：http://dali.zycfv.cn/Article/details/gtmmlqddah.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.svipenyu.cn/Article/details/gtsnwrguuz.html

Ruby: @name = "x"
来源：http://dali.daxiang520.top/Article/details/gtqslmozdp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gotoacloud.top/Article/details/gtnixdblvu.html

[G04] 定义方法
来源：http://dali.aibaodan.cn/Article/details/gtxorarvjk.html

Py:   def greet(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtuoswqhzm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqitzrsw.html

JS:   greet() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtjleuwewb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtxdsuamup.html

Java: String greet() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtbcuewnxe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtamftlfbi.html

Ruby: def greet; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtmaaalpse.html

C#:   public string Greet() => Name;
来源：http://dali.gotoacloud.top/Article/details/gtxglhoxab.html

[G05] 继承
来源：http://dali.mhx1999.top/Article/details/gtszarysph.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gtdzslpbri.html

PHP:  class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtqbgzaejb.html

JS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtbqjapsbl.html

TS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtueaudlkh.html

Java: class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtychkxobd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuekmqhwn.html

Ruby: class Admin < User; end
来源：http://dali.zhongyouzk.top/Article/details/gttovcvvtt.html

C#:   class Admin : User {}
来源：http://dali.birdmap.top/Article/details/gtxioraqbb.html

[G06] 重写方法
来源：http://dali.tian-w.cn/Article/details/gtqqrgkqwm.html

Py:   def greet(self): return "admin"
来源：http://dali.pengpengdd.cyou/Article/details/gttafxrmgt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfsvhjfm.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtpgxuvhvl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtcprwfyqy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtdjxvssgo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gtkraxtgaq.html

Ruby: def greet; "admin"; end
来源：http://dali.gogol.net.cn/Article/details/gtebzvmatj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zycfv.cn/Article/details/gtjyorynxn.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtucncsgdt.html

Py:   super().greet()
来源：http://dali.sysykeji.top/Article/details/gtksuvswgm.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gtzsqhvblj.html

JS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmrpipvz.html

TS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gteiedbkst.html

Java: super.greet();
来源：http://dali.ybcxt.top/Article/details/gtrhqfebcp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hammf.cn/Article/details/gtfgjodfak.html

Ruby: super
来源：http://dali.daxiang520.top/Article/details/gtxymoosjr.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gtterrnoby.html

[G08] 静态方法与属性
来源：http://dali.hywenlv.cn/Article/details/gtiifpshgi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gotoacloud.top/Article/details/gtwkcoaqdg.html

PHP:  public static function f() {}
来源：http://dali.sweek.top/Article/details/gtamotocxd.html

JS:   static f() {}
来源：http://dali.tanke756.top/Article/details/gtdkerhjuy.html

TS:   static f(): void {}
来源：http://dali.kuanghao11.cn/Article/details/gtuuhkvryv.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gtitgtvxjw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yvedp.cn/Article/details/gtfkaldxcb.html

Ruby: def self.f; end
来源：http://dali.ivvv.top/Article/details/gtbxbaepwt.html

C#:   public static void F() {}
来源：http://dali.aizwys.cn/Article/details/gtqlnysqou.html

[G09] 接口 / 抽象类
来源：http://dali.cucudq.cn/Article/details/gtyomxyxnl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gtyefmngwd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbiihbumw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenlongwang.top/Article/details/gtaveafsov.html

TS:   interface Shape { area(): number; }
来源：http://dali.cucudq.cn/Article/details/gtplummwwz.html

Java: interface Shape { double area(); }
来源：http://dali.svipenyu.cn/Article/details/gttldmugnn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cheryme.top/Article/details/gtmlrqvfvm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gaohongyu789.top/Article/details/gttutfecmi.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgfzy.top/Article/details/gtirnlbasz.html

[G10] 访问控制
来源：http://dali.wangshuangyany.cn/Article/details/gtywosgrcv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenzaomai.com/Article/details/gtvjnvumbl.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtxhtsfhfc.html

JS:   #private 字段；其余公开
来源：http://dali.guannengcc.top/Article/details/gtudqjqoen.html

TS:   public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtmqsmqqyg.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gtdodzzoxt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aibaodan.cn/Article/details/gtculjysdb.html

Ruby: public / protected / private
来源：http://dali.havefunace.top/Article/details/gthwnqhxpz.html

C#:   public / protected / private / internal
来源：http://dali.ybcxt.top/Article/details/gtmxpomump.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gttvjkjxuj.html

Py:   @property 与 @x.setter
来源：http://dali.yvedp.cn/Article/details/gtkpdssjbh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtytgpfqjs.html

JS:   get name() { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmqlmzayb.html

TS:   get name(): string { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gttrlfzxbi.html

Java: public String getName() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtqztsrcaq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtqautnrzf.html

Ruby: attr_accessor :name
来源：http://dali.meibo888.top/Article/details/gtbuzezsqr.html

C#:   public string Name { get; set; }
来源：http://dali.hammf.cn/Article/details/gtaqijdzbe.html

[G12] 对象转字符串
来源：http://dali.birdmap.top/Article/details/gtraxxrlao.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtifoliuml.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtagodpflb.html

JS:   toString() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtogopmeir.html

TS:   toString(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtiizveilm.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gteyqenmmo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtieutndky.html

Ruby: def to_s; @name; end
来源：http://dali.ehwqpu.com/Article/details/gtstglockf.html

C#:   public override string ToString() => Name;
来源：http://dali.bjfxy.top/Article/details/gtfvuaecpw.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gtebolyfni.html

Py:   isinstance(u, User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysxvmiic.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtqmgtckss.html

JS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtsxvtgwgr.html

TS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtfkefbotx.html

Java: u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtznsdhvje.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtyaavqzyt.html

Ruby: u.is_a?(User)
来源：http://dali.jqgufenzy.top/Article/details/gtwphddxrl.html

C#:   u is User
来源：http://dali.hnqzz.top/Article/details/gtzfoacfeg.html

[G14] 数据类 / record
来源：http://dali.svipenyu.cn/Article/details/gtbrjjajhy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhoulong.xyz/Article/details/gtgayyiyzz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.andypj.xyz/Article/details/gtchipuevf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gogol.net.cn/Article/details/gthxoxcxlc.html

TS:   type User = { name: string; age: number };
来源：http://dali.andypj.xyz/Article/details/gtldtqczoe.html

Java: record User(String name, int age) {}
来源：http://dali.c1oappe.top/Article/details/gtqwfwkqoi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gtyomrfbvf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gtincynnxq.html

C#:   record User(string Name, int Age);
来源：http://dali.ybcxt.top/Article/details/gtaxehgybq.html

[G15] 枚举
来源：http://dali.xinyue.icu/Article/details/gtffjxsjct.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pycfn.com/Article/details/gtqochosap.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xylfe.cn/Article/details/gtzgnjpzin.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gtvvkgkwzu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtjfvnknfa.html

Java: enum Color { RED, GREEN }
来源：http://dali.0kj1m.cn/Article/details/gtepuczmbg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfuxbsglt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.havefunace.top/Article/details/gtnxyxdsxl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gtukkxejel.html

[G16] 对象转数组 / 字典
来源：http://dali.pengpengdd.cyou/Article/details/gtrtlpszfc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hfpthk.cn/Article/details/gtlnmhcjdf.html

PHP:  get_object_vars($obj);
来源：http://dali.kuanghao11.cn/Article/details/gteincieln.html

JS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtgmitzmvf.html

TS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtzarjhmvs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhoulong.xyz/Article/details/gtujjwtrki.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gtcyatvoth.html

Ruby: obj.instance_variables
来源：http://dali.yueranfly.top/Article/details/gtyrxaurwn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtenxisfid.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gttecegjaq.html

H. 异常与错误处理
来源：http://dali.jiagoushi.top/Article/details/gtlopcqhrh.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtifdokwav.html

[H01] try / catch 基础
来源：http://dali.yueranfly.top/Article/details/gtozmzhmfu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cdnleiting.top/Article/details/gtyowzpzee.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gtwyvwdisj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtxvenkbwm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtzpevkwoq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgfzy.top/Article/details/gtnffejnhy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.quarkkingdee.top/Article/details/gtqhtojoil.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gtvvdabwor.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aizwys.cn/Article/details/gtbcuabacj.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gtcjpjdxwy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aibaodan.cn/Article/details/gtpmnsrupj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtofsmncuy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtmvcygseb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtovhrdmgc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtbugapzrj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuanzhike.top/Article/details/gtgsqaxbkk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.mhx1999.top/Article/details/gtcmfilqcb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtpqluchyb.html

[H03] 主动抛出异常
来源：http://dali.haohaochexian.top/Article/details/gtfldpbgjr.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gtaitysprx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtdsafhxhm.html

JS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtxfvgdbgf.html

TS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtyngotwwt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtekgcxbvs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gtnymndfnw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.svipenyu.cn/Article/details/gtktuczszj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtfmeqxksi.html

[H04] 自定义异常类型
来源：http://dali.haohaochexian.top/Article/details/gtazvsstnm.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258888.top/Article/details/gtvrzamzpx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gtojokrvba.html

JS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gtsgzgnnip.html

TS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gtikoaimda.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtyptidlmo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aizwys.cn/Article/details/gtybhqjrll.html

Ruby: class MyError < StandardError; end
来源：http://dali.birdmap.top/Article/details/gtaswkpzsl.html

C#:   class MyException : Exception {}
来源：http://dali.hywenlv.cn/Article/details/gtamlfjwrh.html

[H05] 捕获特定类型
来源：http://dali.mhx1999.top/Article/details/gtavrevxvl.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gtmhfzhntv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuxming.cn/Article/details/gtuakqhehs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtuifmkzte.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gtxnftelzz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tanke756.top/Article/details/gtbtdkbmwh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ppjwa.cn/Article/details/gtloelpsyq.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gtcxaugren.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigufen.top/Article/details/gtzkskhjvl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.andypj.xyz/Article/details/gtqxxiyvfl.html

Py:   value = d.get("k") or default
来源：http://dali.gaohongyu789.top/Article/details/gtmxpsxzfk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gthddllsin.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtgzlfejsw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gtifapgldg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.smart0.xyz/Article/details/gtwxdgzyeg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gthcjmkprb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxuanxn.top/Article/details/gtwsdkkgks.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtnpokuggt.html

[H07] 断言
来源：http://dali.cdnleiting.top/Article/details/gtkmklplwx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvqnysub.html

PHP:  assert($x > 0);
来源：http://dali.yonumen.top/Article/details/gtgluacppz.html

JS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtgxicmuen.html

TS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtlladtpbx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenjidiqi.icu/Article/details/gtjtmkdour.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.snrcjt.cn/Article/details/gtuieohmwa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gtmdalyeir.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqrxrbji.html

[H08] 获取错误信息与堆栈
来源：http://dali.zdqjudy.top/Article/details/gtdlcmkjfz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigfzy.top/Article/details/gtgwflxszu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.pycfn.com/Article/details/gtjdguetzd.html

JS:   e.message;  e.stack
来源：http://dali.jqgfzy.top/Article/details/gtbedkpllm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmtnzoon.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gtfkztcrvy.html

Go:   err.Error()
来源：http://dali.c1oappe.top/Article/details/gttznzplnf.html

Ruby: e.message;  e.backtrace
来源：http://dali.tanke756.top/Article/details/gtzdmaobfc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.snrcjt.cn/Article/details/gtrsplvixu.html

[H09] 带错误码的异常
来源：http://dali.cucudq.cn/Article/details/gtugrjoiik.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hfpthk.cn/Article/details/gtpsxbgyfj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ydzc1.top/Article/details/gtjqkorual.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgfzy.top/Article/details/gtbflacric.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.svipenyu.cn/Article/details/gtbqwcjtos.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yanxiufei.cn/Article/details/gtchrlfovi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guowangkeji.top/Article/details/gtqxkcvqxp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yongpay.top/Article/details/gtbednlmqj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hnqzz.top/Article/details/gtkfmbkrrw.html

[H10] 资源自动释放
来源：http://dali.chenlongwang.top/Article/details/gtzuzsqnsv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sysykeji.top/Article/details/gtqqogusuw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.aizwys.cn/Article/details/gtuitwawrv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gtjncbxncv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gtlcdxfktp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztzsnfal.html

Go:   defer f.Close()
来源：http://dali.feifeiyinyue.top/Article/details/gtlxtxncgd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.birdmap.top/Article/details/gtfwqpyujr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gteckqvmwx.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gttbnpubfj.html

I. 正则表达式
来源：http://dali.chenlongwang.top/Article/details/gtvhclrsmd.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtxmgtjfch.html

[I01] 判断是否匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtnbwuevdp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtkribqgau.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258888.top/Article/details/gthfoteoqt.html

JS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtzudifymg.html

TS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtqkhgaemn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgfzy.top/Article/details/gtlozxdprt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.haohaochexian.top/Article/details/gtbociwzuu.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtadhlfbxz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yueranfly.top/Article/details/gtbqtlyanb.html

[I02] 提取所有匹配
来源：http://dali.cucudq.cn/Article/details/gtfszirzzh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gtzjtkzupe.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.feifeiyinyue.top/Article/details/gtsynbwmrp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gzhubu.top/Article/details/gtrljnxmcx.html

TS:   s.match(/\d+/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtipnkarny.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sufxvd.cn/Article/details/gtgfsnegnb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gtdhvcxmvn.html

Ruby: s.scan(/\d+/)
来源：http://dali.xuetiantiany.cn/Article/details/gtommudltb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.mhx1999.top/Article/details/gtkqwyifwp.html

[I03] 提取捕获分组
来源：http://dali.xinyue.icu/Article/details/gtcjuqsdzs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.smart0.xyz/Article/details/gtwtgklued.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daria6918.cn/Article/details/gtfapxfpre.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.pengpengdd.cyou/Article/details/gtqhsatkzi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yanxiufei.cn/Article/details/gtndtaolvy.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gogol.net.cn/Article/details/gtxnrpuhnt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sysykeji.top/Article/details/gtroivybmq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtkzegwaxo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sysykeji.top/Article/details/gtfhhyztng.html

[I04] 正则替换
来源：http://dali.ivvv.top/Article/details/gtaqtvmdcb.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fengsongda.top/Article/details/gtssjbwxfg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.pycfn.com/Article/details/gtogschspt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jiagoushi.top/Article/details/gtudvqcopi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohpjuxyv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.smart0.xyz/Article/details/gtszsonvbe.html


<!-- 参考信息 -->