代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtrtsyilih.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtxissfkpc.html

[F11] 复制与移动文件
来源：http://dali.xuetiantiany.cn/Article/details/gttsjltxit.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtosdrbnex.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dianchejie.cn/Article/details/gtdbxmwyso.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtenrmgoow.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtdofsqyir.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtspjopbod.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigfzy.top/Article/details/gtkojwzavf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtfvifmpss.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jyoumei.cn/Article/details/gtghcrdauv.html

[F12] CSV 读写
来源：http://dali.aibaodan.cn/Article/details/gtlsnbazos.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenzaomai.com/Article/details/gtzhcvylmx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.quarkkingdee.top/Article/details/gtduedvaav.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gtzcrfzwvb.html

TS:   // 同上
来源：http://dali.smart0.xyz/Article/details/gttiimvndt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gzhubu.top/Article/details/gtkkkzrzzg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tanke756.top/Article/details/gtsjaufjat.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttiixikla.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cucudq.cn/Article/details/gtpjtmbyyq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtizcvmxnu.html

G. 面向对象
来源：http://dali.jinqigufen.top/Article/details/gtjmngqpgh.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtmkybqaqy.html

[G01] 定义类
来源：http://dali.316326.xyz/Article/details/gtnsyfzglc.html

Py:   class User: pass
来源：http://dali.yanxiufei.cn/Article/details/gtgoawlbqv.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gtdymzlsse.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtpftlydku.html

TS:   class User { name: string = ""; }
来源：http://dali.tian-w.cn/Article/details/gtmmckpipi.html

Java: class User {}
来源：http://dali.hysaishi.cn/Article/details/gtuzjjocot.html

Go:   type User struct { Name string }
来源：http://dali.dashuyun.cn/Article/details/gtcqldbatz.html

Ruby: class User; end
来源：http://dali.birdmap.top/Article/details/gtfkjzeruy.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtykfguvct.html

[G02] 构造函数
来源：http://dali.aizwys.cn/Article/details/gtuyndvhcs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhixingplan.top/Article/details/gtxmixgyia.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gtksatrxam.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtrifxgbxf.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gthtyzcxqz.html

Java: User(String name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtqckhyrsl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.havefunace.top/Article/details/gthumaylye.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ydzc1.top/Article/details/gtjdmvcxhm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtpmutpduo.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gtzoolxlvf.html

Py:   self.name = "x"
来源：http://dali.yj20258.top/Article/details/gtionbdrph.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtmfsdulbo.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtebkzstko.html

TS:   name: string = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtjgsivsyr.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gtfsqxbifb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daria6918.cn/Article/details/gttktfgskp.html

Ruby: @name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtiieimqyx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtkqluiywv.html

[G04] 定义方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgtwlvjxu.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtslxgvjyw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtbfuingae.html

JS:   greet() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtfhivntrv.html

TS:   greet(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtmwgxdqyu.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtnjrcgucf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtzzomyosy.html

Ruby: def greet; @name; end
来源：http://dali.aizwys.cn/Article/details/gtkmvskyny.html

C#:   public string Greet() => Name;
来源：http://dali.tian-w.cn/Article/details/gtqzsxfdpn.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gtysyzaoof.html

Py:   class Admin(User): pass
来源：http://dali.zycfv.cn/Article/details/gtnsbybolr.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtkpkhbceu.html

JS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtgubpqjdr.html

TS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtyflmeeya.html

Java: class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtofewsuos.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gtzwiysjeo.html

Ruby: class Admin < User; end
来源：http://dali.nanxuanxn.top/Article/details/gtzitswfvb.html

C#:   class Admin : User {}
来源：http://dali.sufxvd.cn/Article/details/gthtkxbvcc.html

[G06] 重写方法
来源：http://dali.yuxming.cn/Article/details/gtjoxxmyem.html

Py:   def greet(self): return "admin"
来源：http://dali.xuetiantiany.cn/Article/details/gtldkfwbwl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtrfmegyzf.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtvsgfvokm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtijobkjjj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtyxyrkwem.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxuanxn.top/Article/details/gtuyjxbsby.html

Ruby: def greet; "admin"; end
来源：http://dali.sysykeji.top/Article/details/gtlngywiss.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenjidiqi.icu/Article/details/gtcdccqubn.html

[G07] 调用父类方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlaiqqxfs.html

Py:   super().greet()
来源：http://dali.yvedp.cn/Article/details/gtvhocnrby.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtanfgtxfq.html

JS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gtbjgaripk.html

TS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtlhwrlvxr.html

Java: super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtkruaqcit.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cashguo.top/Article/details/gteodzdwpt.html

Ruby: super
来源：http://dali.zhixingplan.top/Article/details/gtlvvqulya.html

C#:   base.Greet();
来源：http://dali.jiagoushi.top/Article/details/gtixjpqwty.html

[G08] 静态方法与属性
来源：http://dali.jqgfzy.top/Article/details/gtvctvoifa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.andypj.xyz/Article/details/gtpccrtcqv.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gtrtsdmqxv.html

JS:   static f() {}
来源：http://dali.guowangkeji.top/Article/details/gteqmqkdid.html

TS:   static f(): void {}
来源：http://dali.9152youxi.cn/Article/details/gttjuqfdby.html

Java: static void f() {}
来源：http://dali.tanke756.top/Article/details/gtywupzdxi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.vqdsnc.cn/Article/details/gtcdqrkkpo.html

Ruby: def self.f; end
来源：http://dali.sufxvd.cn/Article/details/gthanevjvc.html

C#:   public static void F() {}
来源：http://dali.chenzaomai.com/Article/details/gtqiuqewgj.html

[G09] 接口 / 抽象类
来源：http://dali.yvedp.cn/Article/details/gtduzaslbl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258888.top/Article/details/gtbgwbhiqc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dashuyun.cn/Article/details/gtwufhulza.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuanzhike.top/Article/details/gtyqjwwlfk.html

TS:   interface Shape { area(): number; }
来源：http://dali.guowangkeji.top/Article/details/gtkfvoxukn.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gtctxeksqy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jyoumei.cn/Article/details/gtkscduifa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.andypj.xyz/Article/details/gtpjredcfx.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtuhrfaocd.html

[G10] 访问控制
来源：http://dali.sufxvd.cn/Article/details/gtqnriknua.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.bjfxy.top/Article/details/gtelbgjxmt.html

PHP:  public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtkdwhrxbx.html

JS:   #private 字段；其余公开
来源：http://dali.nwbrower.top/Article/details/gtolxbdnzi.html

TS:   public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gttdoaydjq.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgfzy.top/Article/details/gtkhdgvkje.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnqzz.top/Article/details/gtzxyqrzoj.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtwjjinoxr.html

C#:   public / protected / private / internal
来源：http://dali.yongpay.top/Article/details/gtwclleseu.html

[G11] getter / setter
来源：http://dali.xziqi.cn/Article/details/gtzlmkctla.html

Py:   @property 与 @x.setter
来源：http://dali.nwbrower.top/Article/details/gtyejkigua.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtucwimwsq.html

JS:   get name() { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtmlciofjr.html

TS:   get name(): string { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gtrqbvnarh.html

Java: public String getName() { return name; }
来源：http://dali.havefunace.top/Article/details/gtrxuyrurz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtrpdpvfjr.html

Ruby: attr_accessor :name
来源：http://dali.ybcxt.top/Article/details/gtprzsxquk.html

C#:   public string Name { get; set; }
来源：http://dali.yonumen.top/Article/details/gtfjctmpkr.html

[G12] 对象转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtntapuaqo.html

Py:   def __str__(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtdcxhllxh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtaqvaeemr.html

JS:   toString() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtwovttdot.html

TS:   toString(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtmvbgweyy.html

Java: @Override public String toString() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtvpywoecx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtteqnoenn.html

Ruby: def to_s; @name; end
来源：http://dali.xinyue.icu/Article/details/gtnlpaaxmv.html

C#:   public override string ToString() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtgwyioolq.html

[G13] 判断对象类型
来源：http://dali.fzhhl.top/Article/details/gtvjyoaqks.html

Py:   isinstance(u, User)
来源：http://dali.feifeiyinyue.top/Article/details/gtkgiklboz.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gtteokvouy.html

JS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtzfrhldns.html

TS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltzhdveq.html

Java: u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtidizonpn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.316326.xyz/Article/details/gtrzljrtri.html

Ruby: u.is_a?(User)
来源：http://dali.aibaodan.cn/Article/details/gtczxlqmxq.html

C#:   u is User
来源：http://dali.chenjidiqi.icu/Article/details/gtqgxuqlnk.html

[G14] 数据类 / record
来源：http://dali.0kj1m.cn/Article/details/gtphlghazm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnqzz.top/Article/details/gthkkgretx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.9152youxi.cn/Article/details/gtgoanpzas.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yueranfly.top/Article/details/gtolbsyzch.html

TS:   type User = { name: string; age: number };
来源：http://dali.dashuyun.cn/Article/details/gtdjjvimgh.html

Java: record User(String name, int age) {}
来源：http://dali.hnqzz.top/Article/details/gtfqjhrvls.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cheryme.top/Article/details/gtjlbzhnrd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.meibo888.top/Article/details/gtxhqinpqs.html

C#:   record User(string Name, int Age);
来源：http://dali.yuanzhike.top/Article/details/gtjyjyhgni.html

[G15] 枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedukpnab.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenzaomai.com/Article/details/gtcbcvaiaj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gtooetmqpf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daxiang520.top/Article/details/gtaoeepqth.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gtnqkbjhyu.html

Java: enum Color { RED, GREEN }
来源：http://dali.yanxiufei.cn/Article/details/gtymifpynv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.andypj.xyz/Article/details/gtwwfyxudt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnxiangtu.top/Article/details/gtckifaadv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtxokpdugm.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfipywzq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cucudq.cn/Article/details/gtmcffbjpp.html

PHP:  get_object_vars($obj);
来源：http://dali.nwbrower.top/Article/details/gtfrtfpkrx.html

JS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gtosgophgk.html

TS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtimzmmxqv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhongyouzk.top/Article/details/gtrdfqxlmf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgfzy.top/Article/details/gtwohbkijh.html

Ruby: obj.instance_variables
来源：http://dali.mhx1999.top/Article/details/gtuwqqhkxm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gtmtihljqh.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtnsbeuadl.html

H. 异常与错误处理
来源：http://dali.9152youxi.cn/Article/details/gtqrkmndtu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gttmdcalap.html

[H01] try / catch 基础
来源：http://dali.chenzaomai.com/Article/details/gtoauzkqwb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gtdymyzsnq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zdqjudy.top/Article/details/gtwmhfueka.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gthijwfrda.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtvengunls.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gtbnigswlz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jyoumei.cn/Article/details/gtyuknstws.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fzhhl.top/Article/details/gtdtxetjlv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guannengcc.top/Article/details/gtbfeufnsd.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdqkjxcb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gtgnijqzui.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtsxzqscpz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtkiqgibfk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gttyocdyob.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtzzmmxiyb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.havefunace.top/Article/details/gtdqytpgbt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gtceikdlgu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtzndjnctk.html

[H03] 主动抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gtzmyyoums.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258.top/Article/details/gtvdydejof.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gthsvoelyt.html

JS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtotvwupxm.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtkqxgvslc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtguilcnis.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhoulong.xyz/Article/details/gtxdwbcpsv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhengqikj.top/Article/details/gtoeiyqhah.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtsiukluqw.html

[H04] 自定义异常类型
来源：http://dali.guowangkeji.top/Article/details/gtxpueewul.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtpsofdkfb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtelaoqqbg.html

JS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gtpmddgsoe.html

TS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gtljhqdgzh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gtuhraiiyk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shuidangran.top/Article/details/gtqkzfjedu.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gtjozgdghg.html

C#:   class MyException : Exception {}
来源：http://dali.cqqwz.cn/Article/details/gtqznmehmv.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gtwvxbcdrt.html

Py:   except ValueError as e:
来源：http://dali.andypj.xyz/Article/details/gtfndctqux.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfxmuqxt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtdrgbsejv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gtzlsqlhgg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jiagoushi.top/Article/details/gthwkqajel.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gotoacloud.top/Article/details/gttxkdjkpj.html

Ruby: rescue ArgumentError => e
来源：http://dali.hongshengwenyu.top/Article/details/gtmzaqdxif.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xylfe.cn/Article/details/gtbiewodpi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gtbwzclqqt.html

Py:   value = d.get("k") or default
来源：http://dali.ybcxt.top/Article/details/gttyjfgpjo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gtjxxsmgmt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtvsfwbaqx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtfggindem.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgfzy.top/Article/details/gtfishsrae.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuetiantiany.cn/Article/details/gtnjrnlrba.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gtmbwtseik.html

C#:   obj?.A?.B ?? default
来源：http://dali.hysaishi.cn/Article/details/gtfjoevzmk.html

[H07] 断言
来源：http://dali.havefunace.top/Article/details/gtjzxbwkec.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxinkj.top/Article/details/gtjjiedukz.html

PHP:  assert($x > 0);
来源：http://dali.hammf.cn/Article/details/gtgbvfelkq.html

JS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtsrceyyco.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtixalxlnb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gotoacloud.top/Article/details/gtpkqmbugm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hfpthk.cn/Article/details/gtijiupzws.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gtxavfdxvp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtgdeimpkz.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gtzdkbafca.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgfzy.top/Article/details/gtklgdwhpf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tian-w.cn/Article/details/gthchrropd.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gtybhunuoq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daria6918.cn/Article/details/gtsttnnlzb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yonumen.top/Article/details/gttpbcwwux.html

Go:   err.Error()
来源：http://dali.jlsjyb.cn/Article/details/gtqgytxqak.html

Ruby: e.message;  e.backtrace
来源：http://dali.0kj1m.cn/Article/details/gtftvuarsk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258888.top/Article/details/gtwkuqiles.html

[H09] 带错误码的异常
来源：http://dali.yuxming.cn/Article/details/gtxmjtsyxc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gtltdssaac.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guowangkeji.top/Article/details/gtnudvktkt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.bjfxy.top/Article/details/gtakjdwntu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gtttabnpce.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gaohongyu789.top/Article/details/gtmlojkwlo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gthosvfsjt.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.mhx1999.top/Article/details/gtnwwqxymc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gtdaqyarjl.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gtebhpgtkg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tian-w.cn/Article/details/gtvqnwlerf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjxwagee.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gtdbpzytxd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gtszdoecme.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigufen.top/Article/details/gtzmxqnylc.html

Go:   defer f.Close()
来源：http://dali.zhoulong.xyz/Article/details/gtfpptrmss.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuanzhike.top/Article/details/gtctyuikoo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdosmdcoi.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtporpskiq.html

I. 正则表达式
来源：http://dali.yuanzhike.top/Article/details/gtfniudqdd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtyjzlpwtc.html

[I01] 判断是否匹配
来源：http://dali.zycfv.cn/Article/details/gtuydubafa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtrjnyvvel.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gteeuplkla.html

JS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gtxytscaux.html

TS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtmmwcmyzn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenzaomai.com/Article/details/gtbxrfifgl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuanzx.com/Article/details/gtxozpcyyi.html

Ruby: s.match?(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gtncjxszmt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zycfv.cn/Article/details/gtdchiytio.html

[I02] 提取所有匹配
来源：http://dali.aibaodan.cn/Article/details/gthvsjbewo.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmpnbnsb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sxryk.cn/Article/details/gtvaidooyg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xylfe.cn/Article/details/gtcpigbuhb.html

TS:   s.match(/\d+/g)
来源：http://dali.ydzc1.top/Article/details/gtxibbamlk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.fengsongda.top/Article/details/gtznggccqh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtfawudbdc.html

Ruby: s.scan(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gttjxadqec.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtuygxynfx.html

[I03] 提取捕获分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtaukctxcv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gtgevtqlbn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gtiiomtkwz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ppjwa.cn/Article/details/gtjpaecejx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.chenzaomai.com/Article/details/gtwdgcmvbz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cdnleiting.top/Article/details/gtkjfzfjir.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.birdmap.top/Article/details/gtgdkjbroi.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.redwolf501.top/Article/details/gtgakiptbm.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.guannengcc.top/Article/details/gtnpjrteki.html

[I04] 正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gthskwhhtt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhijiandao.cn/Article/details/gtilrwdytl.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtudufwush.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gtqwsvenyr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gtajmesiop.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258888.top/Article/details/gthxosunge.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shzxlz.cn/Article/details/gtjmmhnlyt.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.tanke756.top/Article/details/gtmnorygym.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gtqhmepbpf.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gtltcriuvi.html


<!-- 参考信息 -->