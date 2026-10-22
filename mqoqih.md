代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2kzcdydcn.html

TS:   path.extname("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2fccsaedo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pycfn.com/Article/details/gt2urqypife.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2sagdqwmi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2ookwnlbn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2bfxxayzz.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yuvdtrpe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2hretsepy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2rqccbrss.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2ocxqnqpz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2jexihyhg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangdashe.top/Article/details/gt2byblbjwl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.vqdsnc.cn/Article/details/gt2ktbdcmdz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gt2qtjjwfup.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daxiang520.top/Article/details/gt2zclgvczj.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gt2uztbutqw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shuidangran.top/Article/details/gt2dgpathdx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.9152youxi.cn/Article/details/gt2lbpbdmrs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.snrcjt.cn/Article/details/gt2wwgrfvqx.html

TS:   // 同上
来源：http://dali.nanxinkj.top/Article/details/gt2tkfzsgcp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gogol.net.cn/Article/details/gt2yudzqyck.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gt2ficirwew.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yueranfly.top/Article/details/gt2wwtgjbca.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenzaomai.com/Article/details/gt2agkwtakr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2yozdjfvy.html

G. 面向对象
来源：http://dali.xinyue.icu/Article/details/gt2uyvqpziy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2qixqdhjw.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gt2nvlvlzmv.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gt2lxvckquy.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2stzwojus.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2mznboaet.html

TS:   class User { name: string = ""; }
来源：http://dali.gogol.net.cn/Article/details/gt2amnahqkv.html

Java: class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktrqoksv.html

Go:   type User struct { Name string }
来源：http://dali.tanke756.top/Article/details/gt2mtsbfsce.html

Ruby: class User; end
来源：http://dali.zhoulong.xyz/Article/details/gt2hovsngdf.html

C#:   class User {}
来源：http://dali.hnqzz.top/Article/details/gt2uqzetfpi.html

[G02] 构造函数
来源：http://dali.meibo888.top/Article/details/gt2wwjzblkx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gxplmbhu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gt2fchgafbc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gt2jqfnlwzy.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2itijwgpq.html

Java: User(String name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gt2gaphgqwz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hywenlv.cn/Article/details/gt2njbgchmc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gogol.net.cn/Article/details/gt2oxklljbo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ksqvwzuh.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gt2xktsessr.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gt2xjgflduk.html

PHP:  public string $name = "x";
来源：http://dali.mhx1999.top/Article/details/gt2dpmceway.html

JS:   this.name = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2rtbcmgib.html

TS:   name: string = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2swlucuoj.html

Java: private String name;
来源：http://dali.chenzaomai.com/Article/details/gt2rlnpludk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gt2xjjbgaxo.html

Ruby: @name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gt2cwygrgme.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2odnpycaq.html

[G04] 定义方法
来源：http://dali.ivvv.top/Article/details/gt2nhjmarbx.html

Py:   def greet(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gt2kdishmdh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gt2epjurvjq.html

JS:   greet() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gt2irhyfxex.html

TS:   greet(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2ildhconm.html

Java: String greet() { return name; }
来源：http://dali.ivvv.top/Article/details/gt2wgxkkunv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gt2xlvcflsa.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gt2ggmmlcpc.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ammecaop.html

[G05] 继承
来源：http://dali.fzhhl.top/Article/details/gt2wqisfrsc.html

Py:   class Admin(User): pass
来源：http://dali.tianlin.xyz/Article/details/gt2xncoftyg.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gt2rnvoazwv.html

JS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gt2dunzrdrq.html

TS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2qwuteqds.html

Java: class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2jnxbanql.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gt2fmpegimf.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gt2bbxaozcp.html

C#:   class Admin : User {}
来源：http://dali.hysaishi.cn/Article/details/gt2wluytfmk.html

[G06] 重写方法
来源：http://dali.ehwqpu.com/Article/details/gt2hovcikni.html

Py:   def greet(self): return "admin"
来源：http://dali.c1oappe.top/Article/details/gt2tqpzivrr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gt2lisgagdt.html

JS:   greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2lqkvxigg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ezountzl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gt2lxbdyzzc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gt2czicskpv.html

Ruby: def greet; "admin"; end
来源：http://dali.shuidangran.top/Article/details/gt2sqhhbjdw.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gt2ebmxlwbq.html

[G07] 调用父类方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hjqxujrk.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gt2hxmgatot.html

PHP:  parent::greet();
来源：http://dali.yangfankeji.com/Article/details/gt2fdaadntw.html

JS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gt2wxsbsxfx.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2atpmgowu.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gt2oxribsom.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sufxvd.cn/Article/details/gt2oxwlscqz.html

Ruby: super
来源：http://dali.xziqi.cn/Article/details/gt2avsqrhdx.html

C#:   base.Greet();
来源：http://dali.xuanzx.com/Article/details/gt2wqvxmgug.html

[G08] 静态方法与属性
来源：http://dali.guowangkeji.top/Article/details/gt2drbtxhot.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jiagoushi.top/Article/details/gt2vxdaxtwh.html

PHP:  public static function f() {}
来源：http://dali.ybcxt.top/Article/details/gt2umixskur.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2jurpmrtd.html

TS:   static f(): void {}
来源：http://dali.zhoulong.xyz/Article/details/gt2qxjiilqn.html

Java: static void f() {}
来源：http://dali.cheryme.top/Article/details/gt2puciktrs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cqqwz.cn/Article/details/gt2feiqmosg.html

Ruby: def self.f; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2boswdmjl.html

C#:   public static void F() {}
来源：http://dali.quarkkingdee.top/Article/details/gt2fepkivww.html

[G09] 接口 / 抽象类
来源：http://dali.hongshengwenyu.top/Article/details/gt2uxdhrikq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shangyingyoupin.top/Article/details/gt2nomlvmdx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.mhx1999.top/Article/details/gt2bvckjptk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mntiirue.html

TS:   interface Shape { area(): number; }
来源：http://dali.sysykeji.top/Article/details/gt2rnlpmopz.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gt2cmnutdkg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj202588.top/Article/details/gt2gxxnwulc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gt2qqwcmofd.html

C#:   interface IShape { double Area(); }
来源：http://dali.yongpay.top/Article/details/gt2jkcuwykn.html

[G10] 访问控制
来源：http://dali.chenzaomai.com/Article/details/gt2cnmbkdhm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.birdmap.top/Article/details/gt2ifxmfooi.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2hcnnidrf.html

JS:   #private 字段；其余公开
来源：http://dali.mhx1999.top/Article/details/gt2qdrxpdxn.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2gvedeueo.html

Java: public / protected / private / 默认包级
来源：http://dali.cucudq.cn/Article/details/gt2laicqtap.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgufenzy.top/Article/details/gt2nahccdbl.html

Ruby: public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gt2pfujxojl.html

C#:   public / protected / private / internal
来源：http://dali.chenzaomai.com/Article/details/gt2osutvrpt.html

[G11] getter / setter
来源：http://dali.yj202588.top/Article/details/gt2bnnayitg.html

Py:   @property 与 @x.setter
来源：http://dali.sysykeji.top/Article/details/gt2jgnlvslr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gt2ehkigwye.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2jnjxycsv.html

TS:   get name(): string { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gt2xnwugedm.html

Java: public String getName() { return name; }
来源：http://dali.aizwys.cn/Article/details/gt2iaxhdjju.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gt2hxantcag.html

Ruby: attr_accessor :name
来源：http://dali.birdmap.top/Article/details/gt2edvxtiae.html

C#:   public string Name { get; set; }
来源：http://dali.xziqi.cn/Article/details/gt2pptytfwy.html

[G12] 对象转字符串
来源：http://dali.gotoacloud.top/Article/details/gt2bgesagvh.html

Py:   def __str__(self): return self.name
来源：http://dali.yonumen.top/Article/details/gt2jgupkdqu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gt2optgtqsq.html

JS:   toString() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2ckgclrpf.html

TS:   toString(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ubuvvkqs.html

Java: @Override public String toString() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gt2sxkbatjf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gt2lyudtjpy.html

Ruby: def to_s; @name; end
来源：http://dali.daria6918.cn/Article/details/gt2eemdgyyo.html

C#:   public override string ToString() => Name;
来源：http://dali.sufxvd.cn/Article/details/gt2qvquywwh.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lnjsgdru.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gt2wyxnvife.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2qlivlnsx.html

JS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2tgoizphg.html

TS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gt2empfnbou.html

Java: u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gt2wtrtbzqm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenjidiqi.icu/Article/details/gt2vqulzprp.html

Ruby: u.is_a?(User)
来源：http://dali.havefunace.top/Article/details/gt2funcjtbm.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gt2rccamcfh.html

[G14] 数据类 / record
来源：http://dali.gogol.net.cn/Article/details/gt2uxolqjyq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.vqdsnc.cn/Article/details/gt2jhxihoen.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.c1oappe.top/Article/details/gt2ipyatkjd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yanxiufei.cn/Article/details/gt2xwnzemtt.html

TS:   type User = { name: string; age: number };
来源：http://dali.meibo888.top/Article/details/gt2qtsonzed.html

Java: record User(String name, int age) {}
来源：http://dali.wangdashe.top/Article/details/gt2nlfwcwvu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sweek.top/Article/details/gt2zxsvhhbd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.snrcjt.cn/Article/details/gt2rkrmzovg.html

C#:   record User(string Name, int Age);
来源：http://dali.cqqwz.cn/Article/details/gt2hagbgndn.html

[G15] 枚举
来源：http://dali.xinyue.icu/Article/details/gt2idbbmunl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hammf.cn/Article/details/gt2szxhgtqv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xylfe.cn/Article/details/gt2jsapplll.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangdashe.top/Article/details/gt2wodijhnx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2mzbwrnhi.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gt2ccoocovd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bxfrmcsz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xziqi.cn/Article/details/gt2nobasbjm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gt2xzezknbs.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrwxbfkd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigfzy.top/Article/details/gt2paynukxn.html

PHP:  get_object_vars($obj);
来源：http://dali.havefunace.top/Article/details/gt2qjlljqhg.html

JS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gt2iafckitb.html

TS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gt2ccunenia.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tian-w.cn/Article/details/gt2evnlfjdu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gt2jssczbht.html

Ruby: obj.instance_variables
来源：http://dali.guannengcc.top/Article/details/gt2biuojavw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzegmhkm.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2xwuwnmsc.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gt2ykgvbmra.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2slxhiyje.html

[H01] try / catch 基础
来源：http://dali.nanxuanxn.top/Article/details/gt2lsrxamsa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daxiang520.top/Article/details/gt2gzzxrtyu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yonumen.top/Article/details/gt2zafkqjon.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gt2zytwqhdn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oijicgpx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2fpyuovmh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdejlqw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.havefunace.top/Article/details/gt2niszzvdh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258.top/Article/details/gt2vvkfiarg.html

[H02] finally / ensure 收尾
来源：http://dali.cdnleiting.top/Article/details/gt2dgwvvbur.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gotoacloud.top/Article/details/gt2fftobytv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2kaaaraox.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2dxtghttu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2itpgwbsm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2kiajffpi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gt2jhhtjsrz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yangfankeji.com/Article/details/gt2bdvahyao.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2gljricsz.html

[H03] 主动抛出异常
来源：http://dali.zhixingplan.top/Article/details/gt2nhgneyeh.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gt2frymktow.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2bqtmnfme.html

JS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2vsnvehna.html

TS:   throw new Error("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2hafnuaol.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2mqrgpcvt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnxiangtu.top/Article/details/gt2hersdelw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2brnfxqow.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2xroqcgvd.html

[H04] 自定义异常类型
来源：http://dali.smart0.xyz/Article/details/gt2anarojef.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gt2dfymdbbm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gt2wvjadrfx.html

JS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gt2olxiyiwh.html

TS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gt2pqktpgnl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qhfixkuc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aizwys.cn/Article/details/gt2gahllavs.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gt2ddfhiivl.html

C#:   class MyException : Exception {}
来源：http://dali.yueranfly.top/Article/details/gt2ckwsctan.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gt2vaxhpvjm.html

Py:   except ValueError as e:
来源：http://dali.hnxiangtu.top/Article/details/gt2rxkqkcrx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daxiang520.top/Article/details/gt2zjotkxkg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gt2rmzvvjqp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gt2bxifkqcy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gt2uheqgppw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuanzx.com/Article/details/gt2yvkkrfjf.html

Ruby: rescue ArgumentError => e
来源：http://dali.daxiang520.top/Article/details/gt2ngtpfzjz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lruxzcik.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cashguo.top/Article/details/gt2dxqeqnja.html

Py:   value = d.get("k") or default
来源：http://dali.jyoumei.cn/Article/details/gt2ovvhndvz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gt2uayljjvi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gt2xqrumhfs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gt2cbictlbl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aizwys.cn/Article/details/gt2himzwfir.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wykmsxne.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shzxlz.cn/Article/details/gt2jgrxrfsa.html

C#:   obj?.A?.B ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2dznmtbdn.html

[H07] 断言
来源：http://dali.snrcjt.cn/Article/details/gt2hgxmnskc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sysykeji.top/Article/details/gt2znpqqjrl.html

PHP:  assert($x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2wnldhedx.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2whxwrnoc.html

TS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2hfskwbxw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gt2kiwcitjy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2soqdrmve.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gotoacloud.top/Article/details/gt2xfdxxmxp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gt2gnruwodh.html

[H08] 获取错误信息与堆栈
来源：http://dali.hysaishi.cn/Article/details/gt2nzmprvop.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daxiang520.top/Article/details/gt2abqqkitv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guowangkeji.top/Article/details/gt2lvszycqj.html

JS:   e.message;  e.stack
来源：http://dali.meibo888.top/Article/details/gt2hkmsosdw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gogol.net.cn/Article/details/gt2omgvdfzj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhixingplan.top/Article/details/gt2zkhlyzid.html

Go:   err.Error()
来源：http://dali.yuxming.cn/Article/details/gt2fjkevaaq.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258888.top/Article/details/gt2ypnogcdw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yueranfly.top/Article/details/gt2zqkiyglr.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gt2nvkhxulg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zdqjudy.top/Article/details/gt2eskviyos.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pycfn.com/Article/details/gt2mnvsluxk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gt2fsnvpsso.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.fengsongda.top/Article/details/gt2zyacayil.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ppjwa.cn/Article/details/gt2ifzobjdy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhengqikj.top/Article/details/gt2dftdxqcp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhongyouzk.top/Article/details/gt2ufvzhgil.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgfzy.top/Article/details/gt2fckwkyfp.html

[H10] 资源自动释放
来源：http://dali.chenzaomai.com/Article/details/gt2rilumgku.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.9152youxi.cn/Article/details/gt2fqnpcipk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sweek.top/Article/details/gt2dzoinhrb.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gt2zschxjmi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gt2efkzvpjs.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gaohongyu789.top/Article/details/gt2uohqispe.html

Go:   defer f.Close()
来源：http://dali.316326.xyz/Article/details/gt2atlmznjg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hywenlv.cn/Article/details/gt2tdgwrdni.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2ocptwprd.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2rybdaupe.html

I. 正则表达式
来源：http://dali.yuxming.cn/Article/details/gt2uzxbtmqh.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2qoxlqjjr.html

[I01] 判断是否匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2levqkjqv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gt2wvomzzrx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gt2dadebaqc.html

JS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gt2grlkhenb.html

TS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gt2lifxjiwn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ksxxhdww.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2irmygkex.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zvksypcd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yueranfly.top/Article/details/gt2kygpudep.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gt2jxrxfdep.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gt2brzevoee.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhengqikj.top/Article/details/gt2xgjqupnj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ybcxt.top/Article/details/gt2rirsugpc.html

TS:   s.match(/\d+/g)
来源：http://dali.tanke756.top/Article/details/gt2tpcpeuue.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cheryme.top/Article/details/gt2wyvrbiui.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gt2bbqscmvw.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhixingplan.top/Article/details/gt2hrdiqxha.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hleybtje.html

[I03] 提取捕获分组
来源：http://dali.0kj1m.cn/Article/details/gt2sbxqdvft.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.snrcjt.cn/Article/details/gt2nsacetcu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yongpay.top/Article/details/gt2mcugknun.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj202588.top/Article/details/gt2floqzsku.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.havefunace.top/Article/details/gt2hqqpdfel.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jyoumei.cn/Article/details/gt2omkvvzrq.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gogol.net.cn/Article/details/gt2tndeoqup.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.andypj.xyz/Article/details/gt2pvvfmswh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ivhgqqcq.html

[I04] 正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2myfhxezc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uyhiahuk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2icqwoiby.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ufowwvaq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jyoumei.cn/Article/details/gt2btolribz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sweek.top/Article/details/gt2sebtfgqj.html


<!-- 参考信息 -->