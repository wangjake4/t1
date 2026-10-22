代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fzhhl.top/Article/details/gtcswnoaqc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtxuxdazsu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtmofqorse.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtvasfywvu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.redwolf501.top/Article/details/gtgjvvrhgz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtzdbpqefz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jiagoushi.top/Article/details/gtrehshsfn.html

[F12] CSV 读写
来源：http://dali.yj20258888.top/Article/details/gtvjichpqx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gthoqgssjl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhengqikj.top/Article/details/gtzdbbjplk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cashguo.top/Article/details/gtjymqavnk.html

TS:   // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gtegbazryx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gttehrbhyd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.kuanghao11.cn/Article/details/gtzosdsuvp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxinkj.top/Article/details/gtjntkkcls.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gtysetmimg.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtrkgctavw.html

G. 面向对象
来源：http://dali.yvedp.cn/Article/details/gtzbaqxkiw.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtshvzstzi.html

[G01] 定义类
来源：http://dali.hnqzz.top/Article/details/gthvqwmjir.html

Py:   class User: pass
来源：http://dali.vqdsnc.cn/Article/details/gtdsbffyio.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gtdlcrycou.html

JS:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtgistayoi.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttaofhotp.html

Java: class User {}
来源：http://dali.aibaodan.cn/Article/details/gtoegcuhxh.html

Go:   type User struct { Name string }
来源：http://dali.yuxming.cn/Article/details/gtinzydcyf.html

Ruby: class User; end
来源：http://dali.birdmap.top/Article/details/gtycnjhhjq.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtcamssctv.html

[G02] 构造函数
来源：http://dali.zhengqikj.top/Article/details/gtsygotvcx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daxiang520.top/Article/details/gtnikpaxlj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yvedp.cn/Article/details/gtblhwvbcc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtctnaprmc.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gtjwrsmlxz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gthmmnglnc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmjrsllb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.haohaochexian.top/Article/details/gtbqghuguh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtfcgwlfdj.html

[G03] 实例属性
来源：http://dali.c1oappe.top/Article/details/gtvcqqinsg.html

Py:   self.name = "x"
来源：http://dali.tanke756.top/Article/details/gthtujdvfs.html

PHP:  public string $name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtntquxdpi.html

JS:   this.name = "x";
来源：http://dali.bjfxy.top/Article/details/gtgtpnqzve.html

TS:   name: string = "x";
来源：http://dali.0kj1m.cn/Article/details/gtqjkxqmhb.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gtapkgdohk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.vqdsnc.cn/Article/details/gtywirqnvc.html

Ruby: @name = "x"
来源：http://dali.shzxlz.cn/Article/details/gtdkobheys.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkncwstp.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gtckvukgvt.html

Py:   def greet(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtagbsbowc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtnpyhjxxw.html

JS:   greet() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtrfdwqqgz.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkgwuwbz.html

Java: String greet() { return name; }
来源：http://dali.xylfe.cn/Article/details/gthczggral.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtwqgtywks.html

Ruby: def greet; @name; end
来源：http://dali.zhixingplan.top/Article/details/gtzgwcwpgs.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gtrwjqitfv.html

[G05] 继承
来源：http://dali.gaohongyu789.top/Article/details/gttypvbrlz.html

Py:   class Admin(User): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqszghcq.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtnpbbyqrc.html

JS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtbyptznqi.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtvfspbnad.html

Java: class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtiyrdfubk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258888.top/Article/details/gtwlzeoobk.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtzczyyjkq.html

C#:   class Admin : User {}
来源：http://dali.jinqigufen.top/Article/details/gtfkvpuybk.html

[G06] 重写方法
来源：http://dali.guannengcc.top/Article/details/gtwaijudua.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gtrjsikygj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgltsbecc.html

JS:   greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gthuydzhhi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtnjdjkrpy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtgvkozbhv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.snrcjt.cn/Article/details/gtqovosyot.html

Ruby: def greet; "admin"; end
来源：http://dali.316326.xyz/Article/details/gtladkkxlg.html

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gtoymniico.html

[G07] 调用父类方法
来源：http://dali.cdnleiting.top/Article/details/gtfhktfrve.html

Py:   super().greet()
来源：http://dali.xinyue.icu/Article/details/gtranohdft.html

PHP:  parent::greet();
来源：http://dali.sxryk.cn/Article/details/gttyodfdpi.html

JS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtetejfopv.html

TS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtcozuwfms.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gtrpojapnq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfktbcuu.html

Ruby: super
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiddcpxmc.html

C#:   base.Greet();
来源：http://dali.aizwys.cn/Article/details/gtejvcpyed.html

[G08] 静态方法与属性
来源：http://dali.redwolf501.top/Article/details/gtnqecgbnt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cdnleiting.top/Article/details/gtjsqkprkd.html

PHP:  public static function f() {}
来源：http://dali.jlsjyb.cn/Article/details/gteghrxfzd.html

JS:   static f() {}
来源：http://dali.zdqjudy.top/Article/details/gtfdnrsqqc.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gtwwckhddl.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gtmfrnmkqh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gtizivvgsn.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gtbpjnnpvn.html

C#:   public static void F() {}
来源：http://dali.snrcjt.cn/Article/details/gtatlriirg.html

[G09] 接口 / 抽象类
来源：http://dali.hammf.cn/Article/details/gtrbsjnddc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gtfbdqffam.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gtpqtlanxd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.kuanghao11.cn/Article/details/gtgijuwnjw.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gtdlhlrwrc.html

Java: interface Shape { double area(); }
来源：http://dali.c1oappe.top/Article/details/gtthwafaxh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuanzhike.top/Article/details/gtxflrzktd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.316326.xyz/Article/details/gtdwyddgbk.html

C#:   interface IShape { double Area(); }
来源：http://dali.yvedp.cn/Article/details/gtiuaecedw.html

[G10] 访问控制
来源：http://dali.ydzc1.top/Article/details/gteocnotbp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ehwqpu.com/Article/details/gttzokhshx.html

PHP:  public / protected / private
来源：http://dali.cheryme.top/Article/details/gttenvshty.html

JS:   #private 字段；其余公开
来源：http://dali.bjfxy.top/Article/details/gtxphnavbg.html

TS:   public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtrelqguoy.html

Java: public / protected / private / 默认包级
来源：http://dali.ppjwa.cn/Article/details/gtjbbdqaqc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hywenlv.cn/Article/details/gtjdzbenzi.html

Ruby: public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtoadscdvy.html

C#:   public / protected / private / internal
来源：http://dali.jlsjyb.cn/Article/details/gtawlcjhxy.html

[G11] getter / setter
来源：http://dali.yj202588.top/Article/details/gtmeoyotyw.html

Py:   @property 与 @x.setter
来源：http://dali.sysykeji.top/Article/details/gtygrqfuxz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtcwgzymac.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtpclycbbf.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtfppbhryo.html

Java: public String getName() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtlyhmqmpg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtsufhzcbx.html

Ruby: attr_accessor :name
来源：http://dali.nanxinkj.top/Article/details/gtutlymvhp.html

C#:   public string Name { get; set; }
来源：http://dali.jianghu66.top/Article/details/gtxnbjwzim.html

[G12] 对象转字符串
来源：http://dali.daria6918.cn/Article/details/gtrpfhkgnz.html

Py:   def __str__(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtutmasnhv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gtbfodhcwo.html

JS:   toString() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtkuuxqurm.html

TS:   toString(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtqqhlgsql.html

Java: @Override public String toString() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtfqnzzskd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtlvhhqbsv.html

Ruby: def to_s; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gturmnopxq.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtwyaiemqa.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gthlxcpgvu.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gtdyjdbmjb.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gtbbcxoqaw.html

JS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtrprdyeyp.html

TS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtoubdeada.html

Java: u instanceof User
来源：http://dali.yongpay.top/Article/details/gtkcryqcsk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gtnnftbvhb.html

Ruby: u.is_a?(User)
来源：http://dali.zdqjudy.top/Article/details/gtiewqbzuh.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gtjswyzvfq.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gtiavrnqnd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sxryk.cn/Article/details/gtdiucwrzw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jiagoushi.top/Article/details/gtbylbpdgv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.iojbl.cn/Article/details/gtleormdud.html

TS:   type User = { name: string; age: number };
来源：http://dali.hammf.cn/Article/details/gtbeiacbtn.html

Java: record User(String name, int age) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtihkmpjst.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dashuyun.cn/Article/details/gtybnwyzph.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhengqikj.top/Article/details/gtvesxwiop.html

C#:   record User(string Name, int Age);
来源：http://dali.yonumen.top/Article/details/gtufmojkxk.html

[G15] 枚举
来源：http://dali.yvedp.cn/Article/details/gtgtdxhlhy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gtqmpcjyjz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shzxlz.cn/Article/details/gtodqaeeuy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gtzdvsoyau.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtaqvhygel.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gtszhruauo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gtabtiieoq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.quarkkingdee.top/Article/details/gtlqbuwfur.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gtcsjwsebr.html

[G16] 对象转数组 / 字典
来源：http://dali.yuanzhike.top/Article/details/gtumlorlee.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhongyouzk.top/Article/details/gtgztelnqp.html

PHP:  get_object_vars($obj);
来源：http://dali.xuanzx.com/Article/details/gtxcovkuyr.html

JS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gtwbxvfrim.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevrnyfnx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuxming.cn/Article/details/gtiewxbyof.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangshuangyany.cn/Article/details/gtokmobckv.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gtfbmtoqho.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gteaydagqx.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthjyhypwl.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtkucliyoy.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtsyvndcix.html

[H01] try / catch 基础
来源：http://dali.cashguo.top/Article/details/gthilbmpap.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gtioeduuby.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gtmgwzunfu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtycumlwhk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gteldbmxvl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.birdmap.top/Article/details/gtoqqpkjmv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnqzz.top/Article/details/gtkrsrxdss.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.c1oappe.top/Article/details/gtbgwqfopq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gtdnsbfgls.html

[H02] finally / ensure 收尾
来源：http://dali.316326.xyz/Article/details/gtxhjhoewk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.c1oappe.top/Article/details/gtomrghzvr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtnnvvmyni.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtekjwhrfn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtediwjayg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtiiqpejzb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gtrqfsvjfi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yueranfly.top/Article/details/gtdaucmdup.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtfeqzggak.html

[H03] 主动抛出异常
来源：http://dali.mhx1999.top/Article/details/gtuxvoexoh.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuetiantiany.cn/Article/details/gttnbhprzq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtrmasrjxh.html

JS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtzzawwymr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtyshhibxj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtfqkbswih.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xziqi.cn/Article/details/gtgycrtlmv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pycfn.com/Article/details/gtiotzbfvt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtcbrnurei.html

[H04] 自定义异常类型
来源：http://dali.yongpay.top/Article/details/gtdzwwcpjb.html

Py:   class MyError(Exception): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtcbmjhuac.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gtsviwllku.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjdlxham.html

TS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtrqnolwrp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtppzuvbyt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gtpgtrosmc.html

Ruby: class MyError < StandardError; end
来源：http://dali.jlsjyb.cn/Article/details/gtzwhcjkwn.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gtxrpydwbg.html

[H05] 捕获特定类型
来源：http://dali.nanxuanxn.top/Article/details/gtksfrpfjq.html

Py:   except ValueError as e:
来源：http://dali.feifeiyinyue.top/Article/details/gtcbpclkbg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shuidangran.top/Article/details/gtwiglefcb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gtgegcreog.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtyvwfqtye.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtasanllmk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.snrcjt.cn/Article/details/gtxjysubhq.html

Ruby: rescue ArgumentError => e
来源：http://dali.aizwys.cn/Article/details/gthjaaitcr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tianlin.xyz/Article/details/gttmhqagqo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gtlphembhj.html

Py:   value = d.get("k") or default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofbhctbz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtatvavczg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gtymgffadu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtyvvkbgtk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258888.top/Article/details/gtzellktld.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dianchejie.cn/Article/details/gttyqmmmqn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigufen.top/Article/details/gteosbvurx.html

C#:   obj?.A?.B ?? default
来源：http://dali.cucudq.cn/Article/details/gtziewinmo.html

[H07] 断言
来源：http://dali.hnqzz.top/Article/details/gtxnrszttb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aibaodan.cn/Article/details/gtxgxhxshg.html

PHP:  assert($x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtaylduyql.html

JS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxsndomy.html

TS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gtndhmeafd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgufenzy.top/Article/details/gtczeujaci.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yvedp.cn/Article/details/gtfulqgabl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnfgiuub.html

C#:   Debug.Assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtxuzqnwdx.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzmqsbcj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhengqikj.top/Article/details/gtxmqjixhy.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tianlin.xyz/Article/details/gtcdpdniuq.html

JS:   e.message;  e.stack
来源：http://dali.bjfxy.top/Article/details/gtahjclfll.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxuanxn.top/Article/details/gtvmaxhnoi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jyoumei.cn/Article/details/gtzveroewp.html

Go:   err.Error()
来源：http://dali.aizwys.cn/Article/details/gtlkimmcax.html

Ruby: e.message;  e.backtrace
来源：http://dali.mhx1999.top/Article/details/gtzifmfdry.html

C#:   e.Message;  e.StackTrace
来源：http://dali.fengsongda.top/Article/details/gtdpjlhuhr.html

[H09] 带错误码的异常
来源：http://dali.nwbrower.top/Article/details/gtacliqwzy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ydzc1.top/Article/details/gtyaqsedti.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhoulong.xyz/Article/details/gtxyjagsfz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxvyqdub.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gogol.net.cn/Article/details/gtkkvgrsmg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.haohaochexian.top/Article/details/gttoysaxmi.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ppjwa.cn/Article/details/gthvocsxam.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gtjzetzznn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.birdmap.top/Article/details/gtsfbaewrk.html

[H10] 资源自动释放
来源：http://dali.redwolf501.top/Article/details/gtlnvarbdz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.vqdsnc.cn/Article/details/gtwjyunzas.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gteewgynmh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gtjdyoaqit.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gtykbiqajy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yueranfly.top/Article/details/gtrizfwodn.html

Go:   defer f.Close()
来源：http://dali.yvedp.cn/Article/details/gtaxrkpwev.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.316326.xyz/Article/details/gtvfzshkci.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gtwdbjstsp.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtiuqyjmjb.html

I. 正则表达式
来源：http://dali.hywenlv.cn/Article/details/gtfojlkgam.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtnbjldxeu.html

[I01] 判断是否匹配
来源：http://dali.yuanzhike.top/Article/details/gtdhtjajim.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gtoehtvysk.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtxncwbrjx.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtgwfedsiq.html

TS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gtpktcmnvm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgufenzy.top/Article/details/gtaowfcfuv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkhyfiwd.html

Ruby: s.match?(/\d+/)
来源：http://dali.fzhhl.top/Article/details/gtdkunychc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yuanzhike.top/Article/details/gtrbcomizm.html

[I02] 提取所有匹配
来源：http://dali.wangdashe.top/Article/details/gtvjpouqli.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtlkhkjpnx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pycfn.com/Article/details/gtiwqzbhnb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hfpthk.cn/Article/details/gtkeboycmo.html

TS:   s.match(/\d+/g)
来源：http://dali.gogol.net.cn/Article/details/gtbpinyixx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.tianlin.xyz/Article/details/gtrtueteus.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gtuckdxwqh.html

Ruby: s.scan(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtjyhidkrm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtjwyuidyr.html

[I03] 提取捕获分组
来源：http://dali.pengpengdd.cyou/Article/details/gtqhlfietq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yanxiufei.cn/Article/details/gthroaklpi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hywenlv.cn/Article/details/gtsfanpkeb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ybcxt.top/Article/details/gtaibxkvxw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xziqi.cn/Article/details/gtaaldosbp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jqgfzy.top/Article/details/gtmvmivodq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.kuanghao11.cn/Article/details/gthsntyglg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinqigfzy.top/Article/details/gtjwlfvhsg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yueranfly.top/Article/details/gtbukyygxh.html

[I04] 正则替换
来源：http://dali.zhongyouzk.top/Article/details/gtwuhhimiv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yueranfly.top/Article/details/gtnsvfiami.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jianghu66.top/Article/details/gtfknrworx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.pycfn.com/Article/details/gtrcameutl.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gtnvuqozlc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhongyouzk.top/Article/details/gtxcizueyt.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtcphyctva.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gtnlagazos.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yonumen.top/Article/details/gtcenzydnf.html

[I05] 按正则拆分
来源：http://dali.cqqwz.cn/Article/details/gtunpygpso.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.iojbl.cn/Article/details/gtegbddkcq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fengsongda.top/Article/details/gtbvkvxpqi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.xylfe.cn/Article/details/gttgqfersq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxusivjo.html


<!-- 参考信息 -->