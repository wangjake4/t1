代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2ojrqnveu.html

TS:   path.extname("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2auipbxnp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.haohaochexian.top/Article/details/gt2fxmrxebj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlidzjjv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2kzxybsgs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zhglxbxx.html

[F11] 复制与移动文件
来源：http://dali.aizwys.cn/Article/details/gt2kgozcdiu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2mtnfvcgj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2pzwiweze.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gt2iazuunfp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2exzggcgc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qrfvaurd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigfzy.top/Article/details/gt2qfjavbof.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2uxomlpqk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daxiang520.top/Article/details/gt2deqkcbjs.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gt2znrvjnov.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gt2opdkkpqf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daria6918.cn/Article/details/gt2zmgwfjtn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxuanxn.top/Article/details/gt2zctrnssl.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gt2sxomnrxi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xylfe.cn/Article/details/gt2mkouhykg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gt2wqnkuyjj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hfpthk.cn/Article/details/gt2vfyddszv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yanxiufei.cn/Article/details/gt2zuvnufgg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2ffogoite.html

G. 面向对象
来源：http://dali.cheryme.top/Article/details/gt2kzpvdwng.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2tzpqavmq.html

[G01] 定义类
来源：http://dali.kuanghao11.cn/Article/details/gt2pxzuppbs.html

Py:   class User: pass
来源：http://dali.hywenlv.cn/Article/details/gt2bhqcbxwo.html

PHP:  class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2swfzojgd.html

JS:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gt2uwptuvsk.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigfzy.top/Article/details/gt2xnungvjl.html

Java: class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2gafjgahw.html

Go:   type User struct { Name string }
来源：http://dali.jqgfzy.top/Article/details/gt2kpzqemhj.html

Ruby: class User; end
来源：http://dali.jianghu66.top/Article/details/gt2jlwohiiu.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2wabwznoo.html

[G02] 构造函数
来源：http://dali.zhixingplan.top/Article/details/gt2hjcsbtht.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gzhubu.top/Article/details/gt2yqmzttfe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.daxiang520.top/Article/details/gt2pnoofzon.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gt2spzujyix.html

TS:   constructor(public name: string) {}
来源：http://dali.daxiang520.top/Article/details/gt2wlhuhumg.html

Java: User(String name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gt2kxihxwur.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ixiackzx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2frjrdjdl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhengqikj.top/Article/details/gt2lxqgllif.html

[G03] 实例属性
来源：http://dali.nwbrower.top/Article/details/gt2lfqxkjbs.html

Py:   self.name = "x"
来源：http://dali.9152youxi.cn/Article/details/gt2hvdyyfpz.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2sqaqljpm.html

JS:   this.name = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2fjxidvou.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2fagpquhy.html

Java: private String name;
来源：http://dali.gzhubu.top/Article/details/gt2plrznaiz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gt2guuhlfif.html

Ruby: @name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gt2sjeixnxd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sysykeji.top/Article/details/gt2gpkqmkqb.html

[G04] 定义方法
来源：http://dali.hfpthk.cn/Article/details/gt2ukprzhlh.html

Py:   def greet(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gt2oflmmuik.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gt2rmtyayxl.html

JS:   greet() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2pnovfvin.html

TS:   greet(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gt2nfodmrfe.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2vdducfkd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2fyzlarpw.html

Ruby: def greet; @name; end
来源：http://dali.fzhhl.top/Article/details/gt2bzdzdzjs.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gt2smtbbmar.html

[G05] 继承
来源：http://dali.hammf.cn/Article/details/gt2whfeixun.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ujlpenpf.html

PHP:  class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2yexbgfux.html

JS:   class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2rfhugavl.html

TS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gt2bgoajpxg.html

Java: class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2zyqrmyzp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gt2csjezrax.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gt2fhshyxqe.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gt2rdblqebu.html

[G06] 重写方法
来源：http://dali.cdnleiting.top/Article/details/gt2jfgvqicj.html

Py:   def greet(self): return "admin"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gehmyybu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vrppwtqg.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzuyqhht.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2euyyqmrl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2aewlzlhh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ruybnocr.html

Ruby: def greet; "admin"; end
来源：http://dali.daria6918.cn/Article/details/gt2agdfdtgi.html

C#:   public override string Greet() => "admin";
来源：http://dali.jiagoushi.top/Article/details/gt2vdbmgibg.html

[G07] 调用父类方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cjnljlna.html

Py:   super().greet()
来源：http://dali.redwolf501.top/Article/details/gt2rwhpgdwe.html

PHP:  parent::greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2uopmsfpx.html

JS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2obtnfwza.html

TS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2vboakwpi.html

Java: super.greet();
来源：http://dali.iojbl.cn/Article/details/gt2wivnduji.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgfzy.top/Article/details/gt2hqxtshhb.html

Ruby: super
来源：http://dali.chenjidiqi.icu/Article/details/gt2vibrklfr.html

C#:   base.Greet();
来源：http://dali.havefunace.top/Article/details/gt2jomilkbu.html

[G08] 静态方法与属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2ejzeqchi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shzxlz.cn/Article/details/gt2owkpqlcj.html

PHP:  public static function f() {}
来源：http://dali.guannengcc.top/Article/details/gt2knwmmlsi.html

JS:   static f() {}
来源：http://dali.yj20258.top/Article/details/gt2nfztweep.html

TS:   static f(): void {}
来源：http://dali.xziqi.cn/Article/details/gt2xpugwqln.html

Java: static void f() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2cnruoecd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gt2kqsqqjgj.html

Ruby: def self.f; end
来源：http://dali.ydzc1.top/Article/details/gt2mwtcogzh.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yiqfrlau.html

[G09] 接口 / 抽象类
来源：http://dali.chenzaomai.com/Article/details/gt2bqwaqqqp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ehwqpu.com/Article/details/gt2qrjqjsre.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cucudq.cn/Article/details/gt2tmvfisjj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gt2jmfnrvbp.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnxiangtu.top/Article/details/gt2aynoyndi.html

Java: interface Shape { double area(); }
来源：http://dali.yangfankeji.com/Article/details/gt2niookxau.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2aetsxfap.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gt2ehkpgwob.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2sgebsvma.html

[G10] 访问控制
来源：http://dali.bjfxy.top/Article/details/gt2tbsechxo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xtdpyzbg.html

PHP:  public / protected / private
来源：http://dali.aizwys.cn/Article/details/gt2tsdqgncw.html

JS:   #private 字段；其余公开
来源：http://dali.iojbl.cn/Article/details/gt2dknwsrhp.html

TS:   public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2zgnswdoy.html

Java: public / protected / private / 默认包级
来源：http://dali.shuidangran.top/Article/details/gt2rzdgjvcv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuanzx.com/Article/details/gt2jczhlvqe.html

Ruby: public / protected / private
来源：http://dali.sweek.top/Article/details/gt2rvqvwtxf.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vkfufazh.html

[G11] getter / setter
来源：http://dali.zhongyouzk.top/Article/details/gt2poupyxwg.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gt2cpholjbo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2gwxhwqea.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gt2hfbpvqtq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gt2fvsoqrqf.html

Java: public String getName() { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2amigjdyf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gt2kvwollwm.html

Ruby: attr_accessor :name
来源：http://dali.ydzc1.top/Article/details/gt2avpvghdg.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gt2mvzivytv.html

[G12] 对象转字符串
来源：http://dali.tian-w.cn/Article/details/gt2kcsuuesd.html

Py:   def __str__(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gt2mqzaojlp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2avimlhnr.html

JS:   toString() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gt2cowezbrv.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2uhotfgkm.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahvqefyk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gt2jswbonom.html

Ruby: def to_s; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gt2kzkubbof.html

C#:   public override string ToString() => Name;
来源：http://dali.9152youxi.cn/Article/details/gt2sxtkkmln.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fcgbxtoe.html

Py:   isinstance(u, User)
来源：http://dali.yj20258.top/Article/details/gt2zwilpmzc.html

PHP:  $u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2jtouyscz.html

JS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gt2bkmjkznv.html

TS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gt2grexgqle.html

Java: u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2skvjotet.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gt2mayfytzs.html

Ruby: u.is_a?(User)
来源：http://dali.hnxiangtu.top/Article/details/gt2ifmqdllv.html

C#:   u is User
来源：http://dali.tianlin.xyz/Article/details/gt2qqzznkml.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxdbzvbp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fengsongda.top/Article/details/gt2hesnluog.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.smart0.xyz/Article/details/gt2jdmmnbtg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnqzz.top/Article/details/gt2vzntbtce.html

TS:   type User = { name: string; age: number };
来源：http://dali.sufxvd.cn/Article/details/gt2knzcyntm.html

Java: record User(String name, int age) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2zbexhgvk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tanke756.top/Article/details/gt2eibwqdaf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuetiantiany.cn/Article/details/gt2durndpfy.html

C#:   record User(string Name, int Age);
来源：http://dali.dianchejie.cn/Article/details/gt2dimfxoiu.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gt2unjlhont.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.havefunace.top/Article/details/gt2ismtsney.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2oijffspg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gt2dqrrpuan.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gt2vnildskr.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnqzz.top/Article/details/gt2sqdjjfzn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.c1oappe.top/Article/details/gt2frqezgnc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hywenlv.cn/Article/details/gt2lenqnjcd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uaaaeyxo.html

[G16] 对象转数组 / 字典
来源：http://dali.gotoacloud.top/Article/details/gt2doxcbifs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yvedp.cn/Article/details/gt2umvhgnjm.html

PHP:  get_object_vars($obj);
来源：http://dali.havefunace.top/Article/details/gt2udilyvmm.html

JS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2ewvgjnsy.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2aksygqbz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yangfankeji.com/Article/details/gt2ernzdtzn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jiagoushi.top/Article/details/gt2nuscszep.html

Ruby: obj.instance_variables
来源：http://dali.bjfxy.top/Article/details/gt2uyjfthcm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gt2hzekxnzy.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2sygcppus.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vouvivfh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2mhutmxto.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqjwmues.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenzaomai.com/Article/details/gt2nhepqhtt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gt2oenlkndl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gt2uqasdqji.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gt2kpjrabtn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gt2nfjdqsfm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hcnotuyy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sweek.top/Article/details/gt2ytlyigab.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.iojbl.cn/Article/details/gt2qlfdzakm.html

[H02] finally / ensure 收尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kxwxjqli.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuanzx.com/Article/details/gt2bhwmnghs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gqkenutz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkilapxa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qpxcpdlh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2gvowloiz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daria6918.cn/Article/details/gt2ltlrmmas.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gt2fgsrevew.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2twofxwss.html

[H03] 主动抛出异常
来源：http://dali.yueranfly.top/Article/details/gt2zhcsdfvz.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhoulong.xyz/Article/details/gt2mjjkbbix.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wuhkuujg.html

JS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2tplnzlto.html

TS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2uxnqclks.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2iczzfnvx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jlsjyb.cn/Article/details/gt2vldsmzmn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.0kj1m.cn/Article/details/gt2tyahdgit.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2nhhyxymd.html

[H04] 自定义异常类型
来源：http://dali.daxiang520.top/Article/details/gt2jfiufpae.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xjjzxmwf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gt2sqaiojbh.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gt2divamrvn.html

TS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gt2cprkcwlh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gt2bnujlvxo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jyomwfny.html

Ruby: class MyError < StandardError; end
来源：http://dali.zdqjudy.top/Article/details/gt2rrsbmfhf.html

C#:   class MyException : Exception {}
来源：http://dali.jlsjyb.cn/Article/details/gt2avyfkeuy.html

[H05] 捕获特定类型
来源：http://dali.bjfxy.top/Article/details/gt2oubocwlq.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gt2ltslfsrl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.meibo888.top/Article/details/gt2hvbooclz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gt2ufnrbpji.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ybcxt.top/Article/details/gt2zqrkxcva.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigufen.top/Article/details/gt2kygqmlgv.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cdnleiting.top/Article/details/gt2hztvlgep.html

Ruby: rescue ArgumentError => e
来源：http://dali.pengpengdd.cyou/Article/details/gt2aymxzvbj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangdashe.top/Article/details/gt2qzoyaprq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dianchejie.cn/Article/details/gt2igsornld.html

Py:   value = d.get("k") or default
来源：http://dali.gogol.net.cn/Article/details/gt2uexjbopx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gt2kozjvjvw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gt2ufksskok.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gt2gtexjtbn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cheryme.top/Article/details/gt2gbozxkoe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aizwys.cn/Article/details/gt2aqykjmuh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gt2domhgfgx.html

C#:   obj?.A?.B ?? default
来源：http://dali.iojbl.cn/Article/details/gt2hcfvgfcz.html

[H07] 断言
来源：http://dali.shuidangran.top/Article/details/gt2lconiiwd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ksghwhef.html

PHP:  assert($x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmklmxvm.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gt2sqbkfscw.html

TS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gt2mogzjxzz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zycfv.cn/Article/details/gt2olrxcxyt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hfpthk.cn/Article/details/gt2cwcuwqbn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.guannengcc.top/Article/details/gt2mrlniksx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2jiygqqrk.html

[H08] 获取错误信息与堆栈
来源：http://dali.tanke756.top/Article/details/gt2zdsayzvx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhengqikj.top/Article/details/gt2natbtpkh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.9152youxi.cn/Article/details/gt2pdlxmurf.html

JS:   e.message;  e.stack
来源：http://dali.fzhhl.top/Article/details/gt2qubxgqyo.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dianchejie.cn/Article/details/gt2maffxqom.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tianlin.xyz/Article/details/gt2otoaqrre.html

Go:   err.Error()
来源：http://dali.hnqzz.top/Article/details/gt2alrrsqsr.html

Ruby: e.message;  e.backtrace
来源：http://dali.hysaishi.cn/Article/details/gt2ciyqwaum.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gt2iukdvfma.html

[H09] 带错误码的异常
来源：http://dali.guowangkeji.top/Article/details/gt2wgpfukny.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2pstlxwzm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qcnckkhd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gt2ounqphin.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.svipenyu.cn/Article/details/gt2sdtqfdod.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.316326.xyz/Article/details/gt2ohdxhpnp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gotoacloud.top/Article/details/gt2qvktymlz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jqgufenzy.top/Article/details/gt2emrfiacq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shzxlz.cn/Article/details/gt2kxzbtanx.html

[H10] 资源自动释放
来源：http://dali.hnqzz.top/Article/details/gt2sujqzgnj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gt2mktqrqxv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gt2yhsxfhkr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oewgkjfw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gt2cfwpafwx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gt2tpyzpajq.html

Go:   defer f.Close()
来源：http://dali.iojbl.cn/Article/details/gt2tagcjmsg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.meibo888.top/Article/details/gt2wxmpijfs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2wxphqrff.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2tdiberyc.html

I. 正则表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iogudcjv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2bhnxpkhh.html

[I01] 判断是否匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2bvvooodl.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djxawwea.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2jtcvpanv.html

JS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gt2lrvqjikf.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gt2hfyejthv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258.top/Article/details/gt2pmacvlhv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sxryk.cn/Article/details/gt2gxitxmhp.html

Ruby: s.match?(/\d+/)
来源：http://dali.cheryme.top/Article/details/gt2tonpwrws.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gt2xithsebt.html

[I02] 提取所有匹配
来源：http://dali.meibo888.top/Article/details/gt2vjqcqqqn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gt2jnpyawcg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yongpay.top/Article/details/gt2rxzbdneq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigufen.top/Article/details/gt2bwwtdbsb.html

TS:   s.match(/\d+/g)
来源：http://dali.316326.xyz/Article/details/gt2gmvycrad.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.dianchejie.cn/Article/details/gt2lanyjdfg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ldhhjjvk.html

Ruby: s.scan(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gt2mlbbeiel.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj202588.top/Article/details/gt2strfkydw.html

[I03] 提取捕获分组
来源：http://dali.shzxlz.cn/Article/details/gt2jcjnwhar.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2btvelbdw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.iojbl.cn/Article/details/gt2niqffprn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.meibo888.top/Article/details/gt2uwnumnwu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gogol.net.cn/Article/details/gt2ezjdnwwx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pycfn.com/Article/details/gt2mfkedbmo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.c1oappe.top/Article/details/gt2nrmarpeu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdjmvhjx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj202588.top/Article/details/gt2xpymgtdc.html

[I04] 正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2grommhgm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.fzhhl.top/Article/details/gt2ztqctjro.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cashguo.top/Article/details/gt2mymmqddl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2qademeid.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nanxinkj.top/Article/details/gt2vxfwrszy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wvbepqke.html


<!-- 参考信息 -->