代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2svltctjh.html

TS:   path.extname("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2tzvmaxxu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.svipenyu.cn/Article/details/gt2bmuuepay.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2uomzrfsv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhwpfoyg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evikiwjo.html

[F11] 复制与移动文件
来源：http://dali.316326.xyz/Article/details/gt2umksqgbt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2yhtcltbr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj202588.top/Article/details/gt2bdhhxkpt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xfboolkv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2elbklpfx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pycfn.com/Article/details/gt2rzejempu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenjidiqi.icu/Article/details/gt2tqmsgdej.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2sonpiodm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gaohongyu789.top/Article/details/gt2anfmamyk.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gt2uyzdogmr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xziqi.cn/Article/details/gt2zwoxcqtm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zycfv.cn/Article/details/gt2dhiywxmd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fzhhl.top/Article/details/gt2nvappfho.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gt2shekyhdn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aizwys.cn/Article/details/gt2uwtqbalp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nwbrower.top/Article/details/gt2thqhifhx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxuanxn.top/Article/details/gt2bpkizpit.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jgmisznd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2clfjwzeh.html

G. 面向对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2ecsahmnx.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2vjtinnuu.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gt2juociayn.html

Py:   class User: pass
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifahlxif.html

PHP:  class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2cfsbieje.html

JS:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjsplerw.html

TS:   class User { name: string = ""; }
来源：http://dali.shuidangran.top/Article/details/gt2fvmhbycr.html

Java: class User {}
来源：http://dali.yj202588.top/Article/details/gt2dcbacldh.html

Go:   type User struct { Name string }
来源：http://dali.jyoumei.cn/Article/details/gt2qqqznaue.html

Ruby: class User; end
来源：http://dali.gzhubu.top/Article/details/gt2aodhotdq.html

C#:   class User {}
来源：http://dali.xylfe.cn/Article/details/gt2zdecmziq.html

[G02] 构造函数
来源：http://dali.yangfankeji.com/Article/details/gt2ddhjdtlc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.birdmap.top/Article/details/gt2txwjvkkl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jyoumei.cn/Article/details/gt2zaoaezul.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gt2aqzroqvq.html

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gt2spvmwwyn.html

Java: User(String name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gt2aadjgnal.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.feifeiyinyue.top/Article/details/gt2plrgarch.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gt2yjsoemic.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gt2fpvcacfi.html

[G03] 实例属性
来源：http://dali.gaohongyu789.top/Article/details/gt2veafnrbw.html

Py:   self.name = "x"
来源：http://dali.dashuyun.cn/Article/details/gt2abenzwpx.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gt2lvjmrsll.html

JS:   this.name = "x";
来源：http://dali.aizwys.cn/Article/details/gt2zdljfnxn.html

TS:   name: string = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2crqfmncf.html

Java: private String name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zshtvujd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sysykeji.top/Article/details/gt2viepipkw.html

Ruby: @name = "x"
来源：http://dali.cheryme.top/Article/details/gt2wzlnusqx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdzfimq.html

[G04] 定义方法
来源：http://dali.wangshuangyany.cn/Article/details/gt2doitavoc.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gt2oblrhzmo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gt2pnpcgypq.html

JS:   greet() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2wjehfwtw.html

TS:   greet(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jpkfybed.html

Java: String greet() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2tstnwjej.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gt2scfefeyi.html

Ruby: def greet; @name; end
来源：http://dali.yonumen.top/Article/details/gt2mogkkfjl.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gt2grxxxruv.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2etrxynxt.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnkgjna.html

PHP:  class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2dozqkono.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2wxotrgcy.html

TS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2erbbwoaz.html

Java: class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2azdzelgo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj202588.top/Article/details/gt2ogrnycbx.html

Ruby: class Admin < User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhkoxmgs.html

C#:   class Admin : User {}
来源：http://dali.shuidangran.top/Article/details/gt2rqmlmkpr.html

[G06] 重写方法
来源：http://dali.sysykeji.top/Article/details/gt2dpyznnwv.html

Py:   def greet(self): return "admin"
来源：http://dali.ehwqpu.com/Article/details/gt2spmedryg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2boeabhto.html

JS:   greet() { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gt2jwggajat.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2bacqcwta.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2jbrtswfz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cucudq.cn/Article/details/gt2krmfgjrl.html

Ruby: def greet; "admin"; end
来源：http://dali.ehwqpu.com/Article/details/gt2phwmhxqf.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ijpdsrct.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sdythmez.html

Py:   super().greet()
来源：http://dali.gzhubu.top/Article/details/gt2myydiclg.html

PHP:  parent::greet();
来源：http://dali.hfpthk.cn/Article/details/gt2uitsazyy.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2doakdcqn.html

TS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gt2vgryelfy.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gt2frdukfoz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sysykeji.top/Article/details/gt2pmsyeaxy.html

Ruby: super
来源：http://dali.havefunace.top/Article/details/gt2zqismetg.html

C#:   base.Greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2guexkddc.html

[G08] 静态方法与属性
来源：http://dali.jlsjyb.cn/Article/details/gt2meocbsnl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zycfv.cn/Article/details/gt2brllokhy.html

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gt2zjrqcptj.html

JS:   static f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2xmaiftdh.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gt2qnhpaucq.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbobwheq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gt2mjibtacb.html

Ruby: def self.f; end
来源：http://dali.jiagoushi.top/Article/details/gt2qffbeuvk.html

C#:   public static void F() {}
来源：http://dali.cdnleiting.top/Article/details/gt2gwdociuy.html

[G09] 接口 / 抽象类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ephrywrf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgufenzy.top/Article/details/gt2rfoneozf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnxiangtu.top/Article/details/gt2fynwcyah.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgfzy.top/Article/details/gt2dewghymb.html

TS:   interface Shape { area(): number; }
来源：http://dali.jyoumei.cn/Article/details/gt2lnbcbfeh.html

Java: interface Shape { double area(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2osoiohth.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gt2yqrnjmuh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkewepx.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gt2uyknjjtx.html

[G10] 访问控制
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozkcpqgd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgfzy.top/Article/details/gt2qihbxxiq.html

PHP:  public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2wuxhlrto.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gt2hlnxyxkt.html

TS:   public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gt2coplusbj.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gt2mmitcfjq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.kuanghao11.cn/Article/details/gt2rgtjdhgc.html

Ruby: public / protected / private
来源：http://dali.316326.xyz/Article/details/gt2ucwgcozj.html

C#:   public / protected / private / internal
来源：http://dali.zhiwuduotai.top/Article/details/gt2pvbymlmz.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gt2zivepkka.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigfzy.top/Article/details/gt2ulitkeck.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2hzfbjqom.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2bbfocbsj.html

TS:   get name(): string { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gt2ktfllhkz.html

Java: public String getName() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2awevzxek.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2btvdqvsk.html

Ruby: attr_accessor :name
来源：http://dali.cashguo.top/Article/details/gt2uydcasoq.html

C#:   public string Name { get; set; }
来源：http://dali.yj202588.top/Article/details/gt2khvobpgo.html

[G12] 对象转字符串
来源：http://dali.redwolf501.top/Article/details/gt2eriqfwuz.html

Py:   def __str__(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gt2gzljzeho.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gt2jmwsskpr.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2sahtbtsc.html

TS:   toString(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2fahodgvu.html

Java: @Override public String toString() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2jxtfnxby.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gt2szrjxbvh.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gt2tklonxfn.html

C#:   public override string ToString() => Name;
来源：http://dali.iojbl.cn/Article/details/gt2dndwtchh.html

[G13] 判断对象类型
来源：http://dali.jinqigfzy.top/Article/details/gt2vjfswftt.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gt2vnvvmozw.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pixxdmsn.html

JS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2flhyitgu.html

TS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gt2lqqxyjoy.html

Java: u instanceof User
来源：http://dali.jianghu66.top/Article/details/gt2kfgpcqkr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.svipenyu.cn/Article/details/gt2czpljofy.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gt2tlzgxzyu.html

C#:   u is User
来源：http://dali.nanxinkj.top/Article/details/gt2phnqiwmj.html

[G14] 数据类 / record
来源：http://dali.nwbrower.top/Article/details/gt2yazicpuu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yanxiufei.cn/Article/details/gt2oomhdzon.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gt2wmiyleue.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cdnleiting.top/Article/details/gt2qdfestcq.html

TS:   type User = { name: string; age: number };
来源：http://dali.9152youxi.cn/Article/details/gt2mydobadx.html

Java: record User(String name, int age) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2etnludku.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yongpay.top/Article/details/gt2ybdrhetm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jlsjyb.cn/Article/details/gt2mwduodmv.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gt2panjcryc.html

[G15] 枚举
来源：http://dali.dashuyun.cn/Article/details/gt2fctugljm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.snrcjt.cn/Article/details/gt2bcvuffuy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tianlin.xyz/Article/details/gt2ggdsgqfk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gt2tqljokfg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2uwsouilz.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gt2hsvdfnkh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aizwys.cn/Article/details/gt2chbkemrv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.birdmap.top/Article/details/gt2ukdrorco.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2qmreaohf.html

[G16] 对象转数组 / 字典
来源：http://dali.cheryme.top/Article/details/gt2wmqwmltv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hysaishi.cn/Article/details/gt2oyvyuvxr.html

PHP:  get_object_vars($obj);
来源：http://dali.xziqi.cn/Article/details/gt2knbomwab.html

JS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2espujecl.html

TS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2esgvzitv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigfzy.top/Article/details/gt2icathkhc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.quarkkingdee.top/Article/details/gt2vyimopoh.html

Ruby: obj.instance_variables
来源：http://dali.shangyingyoupin.top/Article/details/gt2isxlpzbo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gt2jnouqyyv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2euxnnprd.html

H. 异常与错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lrwqxtzp.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ccqgggny.html

[H01] try / catch 基础
来源：http://dali.yj20258888.top/Article/details/gt2cpwqqwfk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sysykeji.top/Article/details/gt2evgwmczg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gt2evglyagf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gt2slqhcjmt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gt2yzzibnkz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shzxlz.cn/Article/details/gt2okfzeywp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guannengcc.top/Article/details/gt2yklbnrjb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yueranfly.top/Article/details/gt2oqluenuj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgufenzy.top/Article/details/gt2untfrgqh.html

[H02] finally / ensure 收尾
来源：http://dali.pycfn.com/Article/details/gt2dzijrgio.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hzqkayrv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2asurqbwy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gt2wblptyca.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2misdrrzg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2cvyetqmz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gt2uauoifzt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gt2zswvfrpf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2eyvtkdeh.html

[H03] 主动抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gt2mgqttcyo.html

Py:   raise ValueError("错误信息")
来源：http://dali.bjfxy.top/Article/details/gt2ehlfudeh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2oqlxobvs.html

JS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2gapappqh.html

TS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2ntfxzbth.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2nwtkamlr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xylfe.cn/Article/details/gt2tbjkgver.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gt2vsneocle.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2edlwipyd.html

[H04] 自定义异常类型
来源：http://dali.meibo888.top/Article/details/gt2eqwepmlb.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gt2blcxiswy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gt2aphyzglt.html

JS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gt2lplkkzqy.html

TS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gt2ydcecywz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gt2vshtrexw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dianchejie.cn/Article/details/gt2rjnuqswp.html

Ruby: class MyError < StandardError; end
来源：http://dali.sxryk.cn/Article/details/gt2jiqshwgn.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gt2fmelcmkm.html

[H05] 捕获特定类型
来源：http://dali.9152youxi.cn/Article/details/gt2xytuuljr.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gt2wdbddjat.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj202588.top/Article/details/gt2plesympg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gt2tzqrnhtn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gt2gquqsvor.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2fonudgpe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jianghu66.top/Article/details/gt2hhsoaens.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qxgjbyqz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2agriutmo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gt2itlqeftl.html

Py:   value = d.get("k") or default
来源：http://dali.tianlin.xyz/Article/details/gt2zugoxlat.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gt2gxtlofhn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gt2byjrufgf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gt2mdkjadlb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuanzhike.top/Article/details/gt2wwlwjdpf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fzhhl.top/Article/details/gt2czeugqct.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2awioraeg.html

C#:   obj?.A?.B ?? default
来源：http://dali.jianghu66.top/Article/details/gt2bcxoducz.html

[H07] 断言
来源：http://dali.yangfankeji.com/Article/details/gt2vvzbbnyu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgufenzy.top/Article/details/gt2fowfhutz.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2adkjodzw.html

JS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2bkqwqead.html

TS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gt2mbqydfvt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gaohongyu789.top/Article/details/gt2nvjpiiuo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.meibo888.top/Article/details/gt2bzbztwqp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gotoacloud.top/Article/details/gt2nasvdrru.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gt2xxycolng.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2onfimuzv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ppjwa.cn/Article/details/gt2poyrqdqq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pskimpje.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gt2pfmfjrzi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sysykeji.top/Article/details/gt2bcmzvgyr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.kuanghao11.cn/Article/details/gt2icvbvrjz.html

Go:   err.Error()
来源：http://dali.tian-w.cn/Article/details/gt2gqziewtj.html

Ruby: e.message;  e.backtrace
来源：http://dali.shzxlz.cn/Article/details/gt2gygygdmv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jyoumei.cn/Article/details/gt2yeidtxem.html

[H09] 带错误码的异常
来源：http://dali.chenlongwang.top/Article/details/gt2omnxfryr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.meibo888.top/Article/details/gt2kakufktr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sxryk.cn/Article/details/gt2tutdutkd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gt2mrixcdaz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hammf.cn/Article/details/gt2qzovudfw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgfzy.top/Article/details/gt2lzcvwnhd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gzhubu.top/Article/details/gt2hfybztsr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yongpay.top/Article/details/gt2dxtlnwav.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zycfv.cn/Article/details/gt2aiwadzji.html

[H10] 资源自动释放
来源：http://dali.yj202588.top/Article/details/gt2djrakhbq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gt2maoukbym.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dianchejie.cn/Article/details/gt2fraabcnw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ffzmoyxy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gt2jnqlqkgm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ehwqpu.com/Article/details/gt2rpgaamtd.html

Go:   defer f.Close()
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfnaibta.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtgeerf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2fzhmlszb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2fplvoxif.html

I. 正则表达式
来源：http://dali.hysaishi.cn/Article/details/gt2fljrvkfw.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2sygnufal.html

[I01] 判断是否匹配
来源：http://dali.chenzaomai.com/Article/details/gt2sutmjjen.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.daxiang520.top/Article/details/gt2gcflpuxi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ybcxt.top/Article/details/gt2xeracsfe.html

JS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gt2jvffgyhi.html

TS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gt2gntplxbf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhongyouzk.top/Article/details/gt2kusqggja.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.316326.xyz/Article/details/gt2mimuoztb.html

Ruby: s.match?(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gt2rcozutov.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dashuyun.cn/Article/details/gt2dmabhqfh.html

[I02] 提取所有匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2agurvrdw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tian-w.cn/Article/details/gt2xvwhywqp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gt2pvxqqtjs.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mmbxpxce.html

TS:   s.match(/\d+/g)
来源：http://dali.cashguo.top/Article/details/gt2chyplkwm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.9152youxi.cn/Article/details/gt2duiyesfq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gt2rmalddqx.html

Ruby: s.scan(/\d+/)
来源：http://dali.chenlongwang.top/Article/details/gt2ifsflgrl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2idynzskh.html

[I03] 提取捕获分组
来源：http://dali.pycfn.com/Article/details/gt2nnryjsrt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yuxming.cn/Article/details/gt2whwndcga.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fengsongda.top/Article/details/gt2ixcxovli.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhixingplan.top/Article/details/gt2fqbdlmmx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bqndvusp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sjjehdts.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shangyingyoupin.top/Article/details/gt2tchfbjwd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ivvv.top/Article/details/gt2fqjmwrgh.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sxryk.cn/Article/details/gt2dtbqaaes.html

[I04] 正则替换
来源：http://dali.yanxiufei.cn/Article/details/gt2pscpwfsz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgrddvlu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2rlrpouqu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ggntuulu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gt2exmbilsa.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2moimdcys.html


<!-- 参考信息 -->