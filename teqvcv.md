代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gt2ikpnfesf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2xbjgzuyv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.birdmap.top/Article/details/gt2wasixxiw.html

Ruby: File.size("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2sagnzexe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cqqwz.cn/Article/details/gt2qrusgplx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cashguo.top/Article/details/gt2ibjaabyy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2jgxnovhx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2srjquzci.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2srkaicbe.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2krruiffn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xylfe.cn/Article/details/gt2owonobba.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2iwurkqto.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2gtdjhydv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2sfpjqwbb.html

[F11] 复制与移动文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jvmfemzf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2kuxpopdz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2mwrftnqp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2siozmpce.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2yiqeeuci.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmraatsi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xziqi.cn/Article/details/gt2nubiqtpt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2enbimitv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yanxiufei.cn/Article/details/gt2xvohrwmf.html

[F12] CSV 读写
来源：http://dali.meibo888.top/Article/details/gt2mxdtvcil.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnxiangtu.top/Article/details/gt2tpumrijm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gt2rqikuluv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ppjwa.cn/Article/details/gt2kkqfemqi.html

TS:   // 同上
来源：http://dali.xuanzx.com/Article/details/gt2vnbzojxu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.feifeiyinyue.top/Article/details/gt2vbkxplwv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhengqikj.top/Article/details/gt2trpudxch.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gt2mzixekfw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yongpay.top/Article/details/gt2skvdgsql.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2oaqerkuo.html

G. 面向对象
来源：http://dali.nanxuanxn.top/Article/details/gt2slptpxjp.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2xwndzrii.html

[G01] 定义类
来源：http://dali.zhoulong.xyz/Article/details/gt2mlrfvwkt.html

Py:   class User: pass
来源：http://dali.fengsongda.top/Article/details/gt2zpaleyxk.html

PHP:  class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2hxpecxwk.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gt2twfspoow.html

TS:   class User { name: string = ""; }
来源：http://dali.zhoulong.xyz/Article/details/gt2njfmaxdb.html

Java: class User {}
来源：http://dali.yuxming.cn/Article/details/gt2dapchuxr.html

Go:   type User struct { Name string }
来源：http://dali.guowangkeji.top/Article/details/gt2ogmtwgdj.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gt2spnmqyxo.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gt2pjsaarso.html

[G02] 构造函数
来源：http://dali.aibaodan.cn/Article/details/gt2snootqln.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hgiqmphv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2fvdmlpjg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gt2vnhmapop.html

TS:   constructor(public name: string) {}
来源：http://dali.chenlongwang.top/Article/details/gt2gedcgmkn.html

Java: User(String name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gt2nrnklngh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.0kj1m.cn/Article/details/gt2uagqmijl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gt2ohglbswp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2shmxcfnp.html

[G03] 实例属性
来源：http://dali.yonumen.top/Article/details/gt2eziyyogq.html

Py:   self.name = "x"
来源：http://dali.cdnleiting.top/Article/details/gt2chfvgleu.html

PHP:  public string $name = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2kpxbvqik.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qbylsxef.html

TS:   name: string = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjjrtrcf.html

Java: private String name;
来源：http://dali.yj20258.top/Article/details/gt2iwqalhxs.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.iojbl.cn/Article/details/gt2nrqnfouf.html

Ruby: @name = "x"
来源：http://dali.sysykeji.top/Article/details/gt2biepfhru.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2fxyvohhs.html

[G04] 定义方法
来源：http://dali.fengsongda.top/Article/details/gt2jzmfbztu.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gt2xzjqousc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2edposffa.html

JS:   greet() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2uqklznsm.html

TS:   greet(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hnmwfpau.html

Java: String greet() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2rmyjhyns.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gt2rsuwgiat.html

Ruby: def greet; @name; end
来源：http://dali.yongpay.top/Article/details/gt2mkjtjhja.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258888.top/Article/details/gt2ovqpfpdt.html

[G05] 继承
来源：http://dali.xinyue.icu/Article/details/gt2mfvfaptf.html

Py:   class Admin(User): pass
来源：http://dali.hammf.cn/Article/details/gt2bcugaven.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2bcbvsukf.html

JS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2tqqipnlf.html

TS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gt2qxksdric.html

Java: class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2zpgfegze.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.bjfxy.top/Article/details/gt2lfahelsl.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gt2outkwjwp.html

C#:   class Admin : User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2dcdpszrr.html

[G06] 重写方法
来源：http://dali.cucudq.cn/Article/details/gt2sszttqig.html

Py:   def greet(self): return "admin"
来源：http://dali.yonumen.top/Article/details/gt2herdoowi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gt2ewerbdrf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bewmbgfw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2brdhsquy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2cszibaqr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.quarkkingdee.top/Article/details/gt2lakluloi.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gt2acacjitq.html

C#:   public override string Greet() => "admin";
来源：http://dali.nwbrower.top/Article/details/gt2kwnweeex.html

[G07] 调用父类方法
来源：http://dali.xylfe.cn/Article/details/gt2vchsshnw.html

Py:   super().greet()
来源：http://dali.aizwys.cn/Article/details/gt2xoqchnnf.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gt2urqmuwcj.html

JS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gt2qynhdjcd.html

TS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gt2nvlzntck.html

Java: super.greet();
来源：http://dali.iojbl.cn/Article/details/gt2kgciiqdx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jlsjyb.cn/Article/details/gt2gqamkjae.html

Ruby: super
来源：http://dali.zhixingplan.top/Article/details/gt2nujvzpsc.html

C#:   base.Greet();
来源：http://dali.mhx1999.top/Article/details/gt2aihyoqpt.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gt2frpdnols.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daxiang520.top/Article/details/gt2btayuucp.html

PHP:  public static function f() {}
来源：http://dali.316326.xyz/Article/details/gt2ihiygmwi.html

JS:   static f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdhhmoap.html

TS:   static f(): void {}
来源：http://dali.hammf.cn/Article/details/gt2ehygxxxk.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2dfxptlbo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gt2raadrabw.html

Ruby: def self.f; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wykfdyya.html

C#:   public static void F() {}
来源：http://dali.cashguo.top/Article/details/gt2ashcwaaa.html

[G09] 接口 / 抽象类
来源：http://dali.shangyingyoupin.top/Article/details/gt2blkefgdi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gt2kjpfknvb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuanzhike.top/Article/details/gt2tifytrni.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gt2lymtxxxd.html

TS:   interface Shape { area(): number; }
来源：http://dali.shuidangran.top/Article/details/gt2hjpnauhg.html

Java: interface Shape { double area(); }
来源：http://dali.guannengcc.top/Article/details/gt2tiuaaxix.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gt2iutytrot.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgfzy.top/Article/details/gt2pstdtwgm.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhixingplan.top/Article/details/gt2nbkccbuw.html

[G10] 访问控制
来源：http://dali.nwbrower.top/Article/details/gt2tftxwecw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gaohongyu789.top/Article/details/gt2zxacoyxt.html

PHP:  public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gt2ahnmyvmr.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gt2sywqbisl.html

TS:   public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2vrtkylod.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gt2zadxzhqg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gzhubu.top/Article/details/gt2rmjnkyjy.html

Ruby: public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gt2oxhrnisz.html

C#:   public / protected / private / internal
来源：http://dali.ybcxt.top/Article/details/gt2cnzctslp.html

[G11] getter / setter
来源：http://dali.quarkkingdee.top/Article/details/gt2gdztciuf.html

Py:   @property 与 @x.setter
来源：http://dali.dianchejie.cn/Article/details/gt2mairrzjf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2wljxkrlw.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gt2yyhsjfcm.html

TS:   get name(): string { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zetduhan.html

Java: public String getName() { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2jbeeckbr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gt2hlvxxovn.html

Ruby: attr_accessor :name
来源：http://dali.kuanghao11.cn/Article/details/gt2fbwnidqz.html

C#:   public string Name { get; set; }
来源：http://dali.ydzc1.top/Article/details/gt2cvtjkgjs.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gt2zwdeuinq.html

Py:   def __str__(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gt2auyknugw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2opjkzism.html

JS:   toString() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkgmrtqz.html

TS:   toString(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wgkumitl.html

Java: @Override public String toString() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2hpcmcskb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gt2wwormwlj.html

Ruby: def to_s; @name; end
来源：http://dali.dashuyun.cn/Article/details/gt2wakqshvj.html

C#:   public override string ToString() => Name;
来源：http://dali.guannengcc.top/Article/details/gt2nkkqpvpp.html

[G13] 判断对象类型
来源：http://dali.gaohongyu789.top/Article/details/gt2xjmhlpuz.html

Py:   isinstance(u, User)
来源：http://dali.vqdsnc.cn/Article/details/gt2honhpnhk.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2psxvtgzi.html

JS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2nhjiwfci.html

TS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2wyeefesd.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2ocuzxlre.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gt2liqftavw.html

Ruby: u.is_a?(User)
来源：http://dali.sysykeji.top/Article/details/gt2ubdcxghb.html

C#:   u is User
来源：http://dali.aibaodan.cn/Article/details/gt2uasoonjw.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gt2nursttoa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2plpbhhkg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.mhx1999.top/Article/details/gt2pjltdetl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.quarkkingdee.top/Article/details/gt2jaxtjvvu.html

TS:   type User = { name: string; age: number };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zjuxvtjb.html

Java: record User(String name, int age) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2dhecedwa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.kuanghao11.cn/Article/details/gt2qdonzuvh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.vqdsnc.cn/Article/details/gt2rhwaiusz.html

C#:   record User(string Name, int Age);
来源：http://dali.zdqjudy.top/Article/details/gt2swuiqhpz.html

[G15] 枚举
来源：http://dali.fengsongda.top/Article/details/gt2zfyeaslz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.bjfxy.top/Article/details/gt2bmbycadc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fengsongda.top/Article/details/gt2drbqklvj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gzhubu.top/Article/details/gt2bmagroyh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2wzquunbd.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gt2dqgpsxne.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.0kj1m.cn/Article/details/gt2jvejzwfk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gt2cicawhrd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gt2gwjzsrbu.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mysdnlwb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tanke756.top/Article/details/gt2witdazzg.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gt2jkboblwd.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2hmdsxljl.html

TS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gt2nwpzpdsm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnllmiod.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.haohaochexian.top/Article/details/gt2femndqbw.html

Ruby: obj.instance_variables
来源：http://dali.zhiwuduotai.top/Article/details/gt2mrstfqtc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ivvv.top/Article/details/gt2wfnqszlm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2jcglhzpx.html

H. 异常与错误处理
来源：http://dali.iojbl.cn/Article/details/gt2nhqoshrg.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2qgcealol.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gt2dnywbvpq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aibaodan.cn/Article/details/gt2dpfipzdk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shzxlz.cn/Article/details/gt2wmcqvish.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gt2wygfhyhj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.redwolf501.top/Article/details/gt2dqeerdnx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zycfv.cn/Article/details/gt2goulwzis.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrxglgvy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gt2wcduzjtd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.316326.xyz/Article/details/gt2mmmakcuu.html

[H02] finally / ensure 收尾
来源：http://dali.gzhubu.top/Article/details/gt2jjizfvsp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gt2ojqpfnyy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2ihsohgaw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2nrupzdyk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2xafitnjq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2oyqjzxyv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhengqikj.top/Article/details/gt2uxskpdxp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2jjvqjrct.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2abhwndou.html

[H03] 主动抛出异常
来源：http://dali.9152youxi.cn/Article/details/gt2mbgchnpi.html

Py:   raise ValueError("错误信息")
来源：http://dali.hfpthk.cn/Article/details/gt2zvwvlduf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2ptstjvoo.html

JS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2wbmdrlyb.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2krgccfiw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2jvenbpqu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangdashe.top/Article/details/gt2jsekizvb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yongpay.top/Article/details/gt2wvogkdsp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2orupgpsm.html

[H04] 自定义异常类型
来源：http://dali.fzhhl.top/Article/details/gt2uslahdkp.html

Py:   class MyError(Exception): pass
来源：http://dali.quarkkingdee.top/Article/details/gt2cmsntzal.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gt2halrqywz.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gt2kmacxjzy.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gt2ivywznxi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gt2ebywuvyz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenlongwang.top/Article/details/gt2ovlprfqy.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ztzwaybc.html

C#:   class MyException : Exception {}
来源：http://dali.nanxinkj.top/Article/details/gt2hjvezsqj.html

[H05] 捕获特定类型
来源：http://dali.haohaochexian.top/Article/details/gt2mjetvqfr.html

Py:   except ValueError as e:
来源：http://dali.nanxinkj.top/Article/details/gt2arbkefei.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekwsfmqx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gt2mmxcnweq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gt2ssfxmhhw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2dahccrwo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sweek.top/Article/details/gt2duevqqtr.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuanzhike.top/Article/details/gt2ybbwethw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigufen.top/Article/details/gt2aoxnqxir.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gt2elrlmwbk.html

Py:   value = d.get("k") or default
来源：http://dali.shzxlz.cn/Article/details/gt2npoqledi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gt2gwrrminh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gt2twiguowa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gt2ekekbnmu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ppjwa.cn/Article/details/gt2ujnzqgko.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sweek.top/Article/details/gt2zasufgld.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zycfv.cn/Article/details/gt2cawsbujb.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenlongwang.top/Article/details/gt2apcgcdyb.html

[H07] 断言
来源：http://dali.yanxiufei.cn/Article/details/gt2sywumxbq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daxiang520.top/Article/details/gt2elqpgadb.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2oadsnrqo.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2djekxexn.html

TS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gt2zcwqflvh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuetiantiany.cn/Article/details/gt2iigbohsi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.smart0.xyz/Article/details/gt2zayjwaxg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jianghu66.top/Article/details/gt2lpwcvipo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2mmwjuwvq.html

[H08] 获取错误信息与堆栈
来源：http://dali.gotoacloud.top/Article/details/gt2cqtmxxap.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shzxlz.cn/Article/details/gt2thqdcsvc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenjidiqi.icu/Article/details/gt2ovqtpjtr.html

JS:   e.message;  e.stack
来源：http://dali.9152youxi.cn/Article/details/gt2dsmttkex.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangdashe.top/Article/details/gt2xmqkferh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gogol.net.cn/Article/details/gt2cxgeeatc.html

Go:   err.Error()
来源：http://dali.guannengcc.top/Article/details/gt2pgfiydlu.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhoulong.xyz/Article/details/gt2kkhdtdei.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangdashe.top/Article/details/gt2zbhojbbl.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gt2hfmjrleo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sysykeji.top/Article/details/gt2ccnncpzk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.cashguo.top/Article/details/gt2zbegphfq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ystoyzwq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gt2yyjbyppu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yanxiufei.cn/Article/details/gt2cffhfsjy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yanxiufei.cn/Article/details/gt2xvjgfmyc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hysaishi.cn/Article/details/gt2iltsarqb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.andypj.xyz/Article/details/gt2ahmndwzx.html

[H10] 资源自动释放
来源：http://dali.tianlin.xyz/Article/details/gt2qbavrjvq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.snrcjt.cn/Article/details/gt2prdaxcwc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hammf.cn/Article/details/gt2odudbzqx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gt2fmkmdmtm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hysaishi.cn/Article/details/gt2hqeqkbmm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bscwitub.html

Go:   defer f.Close()
来源：http://dali.ybcxt.top/Article/details/gt2pcltttpm.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.svipenyu.cn/Article/details/gt2ltjxihqm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2bnzzejbd.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2deleyfkb.html

I. 正则表达式
来源：http://dali.redwolf501.top/Article/details/gt2cuqnbxia.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2ibtrdpoz.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kcfcgukp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2szcpieaq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ydzc1.top/Article/details/gt2hkifrnrm.html

JS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2xvqnxrsd.html

TS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gt2fuumhuqu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.316326.xyz/Article/details/gt2ezmmucht.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.andypj.xyz/Article/details/gt2esyeculb.html

Ruby: s.match?(/\d+/)
来源：http://dali.haohaochexian.top/Article/details/gt2ubtybikk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.snrcjt.cn/Article/details/gt2gckkdunq.html

[I02] 提取所有匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2lkwdubqb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gt2zjrvwmlh.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gt2qdlwzgbw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.sxryk.cn/Article/details/gt2evbmrqcs.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rvxxkbpl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.bjfxy.top/Article/details/gt2oedshyam.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gzhubu.top/Article/details/gt2sqbdqayc.html

Ruby: s.scan(/\d+/)
来源：http://dali.zycfv.cn/Article/details/gt2ezyoqcji.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2ayvqlcfh.html

[I03] 提取捕获分组
来源：http://dali.hywenlv.cn/Article/details/gt2dzusatck.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.andypj.xyz/Article/details/gt2whpfghtn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tdihjagp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jinqigufen.top/Article/details/gt2bgurvcoe.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj202588.top/Article/details/gt2buoevaiu.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.kuanghao11.cn/Article/details/gt2fyduzkne.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenzaomai.com/Article/details/gt2eiptlofu.html


<!-- 参考信息 -->