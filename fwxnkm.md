代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.zdqjudy.top/Article/details/gt2uzstuwab.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shangyingyoupin.top/Article/details/gt2oqlkytfe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2czbixvmi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2yvfizrkd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2fumgpkbb.html

TS:   path.extname("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2wkaomxlq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xylfe.cn/Article/details/gt2mqiymntp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2afvxlley.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2kiueplvt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2dochyizl.html

[F11] 复制与移动文件
来源：http://dali.havefunace.top/Article/details/gt2ltdsxuku.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2hmtgfpyj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2iaieysrs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wcspxauw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gt2uvfmarce.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2obezmcjr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daxiang520.top/Article/details/gt2dejnqora.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbtzmdjy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gogol.net.cn/Article/details/gt2xcigllme.html

[F12] CSV 读写
来源：http://dali.chenzaomai.com/Article/details/gt2mihwfhtk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lrijubwy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hammf.cn/Article/details/gt2iadmdqrd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yueranfly.top/Article/details/gt2tomefiur.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gt2pablipea.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.smart0.xyz/Article/details/gt2vpgjdgnu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guowangkeji.top/Article/details/gt2lekkfrap.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.iojbl.cn/Article/details/gt2eaiaxymy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.svipenyu.cn/Article/details/gt2zpojouen.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2pbzgvihl.html

G. 面向对象
来源：http://dali.xziqi.cn/Article/details/gt2vucrlpmg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2wjvoanam.html

[G01] 定义类
来源：http://dali.daxiang520.top/Article/details/gt2qpwikbdk.html

Py:   class User: pass
来源：http://dali.xuanzx.com/Article/details/gt2ypmwlipd.html

PHP:  class User {}
来源：http://dali.meibo888.top/Article/details/gt2psmtbgah.html

JS:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gt2jpebubvc.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gt2rxieyjoq.html

Java: class User {}
来源：http://dali.sysykeji.top/Article/details/gt2dyqubeuv.html

Go:   type User struct { Name string }
来源：http://dali.pycfn.com/Article/details/gt2bdjwnhxj.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gt2iuhyxjjv.html

C#:   class User {}
来源：http://dali.andypj.xyz/Article/details/gt2fhsznojw.html

[G02] 构造函数
来源：http://dali.xinyue.icu/Article/details/gt2wdzkydaa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cqqwz.cn/Article/details/gt2abdtwpyj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258888.top/Article/details/gt2usnlwphb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gt2xezzjhfy.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxeuwmhg.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gt2xnioeawl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kggchdvq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hysaishi.cn/Article/details/gt2jdvwukyl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wdnagmcz.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gt2yemayyrh.html

Py:   self.name = "x"
来源：http://dali.guowangkeji.top/Article/details/gt2mizmpbel.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gt2fmvlgnur.html

JS:   this.name = "x";
来源：http://dali.cucudq.cn/Article/details/gt2btipumdn.html

TS:   name: string = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2yikiseel.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gt2sqgrrsoz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gt2ttsmogrr.html

Ruby: @name = "x"
来源：http://dali.jqgfzy.top/Article/details/gt2phyavvqb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2jsgijuwj.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gt2kjfyqzeh.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gt2yzqmidej.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gt2txfhhrip.html

JS:   greet() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2bouufwhe.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gt2jockuxdg.html

Java: String greet() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2tfgodvxg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2aseruvjf.html

Ruby: def greet; @name; end
来源：http://dali.havefunace.top/Article/details/gt2zrnoncsh.html

C#:   public string Greet() => Name;
来源：http://dali.aibaodan.cn/Article/details/gt2xisddihn.html

[G05] 继承
来源：http://dali.jianghu66.top/Article/details/gt2pbnydkoe.html

Py:   class Admin(User): pass
来源：http://dali.c1oappe.top/Article/details/gt2jvrjgsko.html

PHP:  class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2manwmuve.html

JS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gt2dyfrknsu.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2esjnrxsi.html

Java: class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2hahragkx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yangfankeji.com/Article/details/gt2micmhudw.html

Ruby: class Admin < User; end
来源：http://dali.hysaishi.cn/Article/details/gt2fufziwcd.html

C#:   class Admin : User {}
来源：http://dali.hywenlv.cn/Article/details/gt2npvacico.html

[G06] 重写方法
来源：http://dali.jiagoushi.top/Article/details/gt2yqlvmiis.html

Py:   def greet(self): return "admin"
来源：http://dali.dashuyun.cn/Article/details/gt2hlzcwhfs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2agxksnjq.html

JS:   greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2yawyiuzw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2mygtzmis.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gt2skhoecfj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gt2bjedpebz.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwadgopa.html

C#:   public override string Greet() => "admin";
来源：http://dali.iojbl.cn/Article/details/gt2odfkvnsc.html

[G07] 调用父类方法
来源：http://dali.tanke756.top/Article/details/gt2knsvdftv.html

Py:   super().greet()
来源：http://dali.yj20258888.top/Article/details/gt2fnqvehov.html

PHP:  parent::greet();
来源：http://dali.dashuyun.cn/Article/details/gt2pzwoozaj.html

JS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uishrqle.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2wqbghwcd.html

Java: super.greet();
来源：http://dali.ppjwa.cn/Article/details/gt2sefyiddp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2hetzmktp.html

Ruby: super
来源：http://dali.gotoacloud.top/Article/details/gt2lerppfnk.html

C#:   base.Greet();
来源：http://dali.cheryme.top/Article/details/gt2gxuciknu.html

[G08] 静态方法与属性
来源：http://dali.ybcxt.top/Article/details/gt2pkupfaaa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sxryk.cn/Article/details/gt2knbzngly.html

PHP:  public static function f() {}
来源：http://dali.yuxming.cn/Article/details/gt2qijvlovq.html

JS:   static f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vgkhuurx.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gt2glshbfdh.html

Java: static void f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2nazrbrxy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gt2yggjqydg.html

Ruby: def self.f; end
来源：http://dali.zhixingplan.top/Article/details/gt2sqgqfwvk.html

C#:   public static void F() {}
来源：http://dali.xuanzx.com/Article/details/gt2lfayipou.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gt2uwrjyjhz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigfzy.top/Article/details/gt2bjtknjky.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258.top/Article/details/gt2ixyedfdn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yongpay.top/Article/details/gt2nysljciv.html

TS:   interface Shape { area(): number; }
来源：http://dali.dianchejie.cn/Article/details/gt2razbszry.html

Java: interface Shape { double area(); }
来源：http://dali.tian-w.cn/Article/details/gt2sgpmrfic.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gt2myesacof.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258.top/Article/details/gt2kwnpupjq.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2vtvofebh.html

[G10] 访问控制
来源：http://dali.hammf.cn/Article/details/gt2fukboumd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.birdmap.top/Article/details/gt2skfpkges.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2ulmuyyrm.html

JS:   #private 字段；其余公开
来源：http://dali.svipenyu.cn/Article/details/gt2pmnvzijc.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gt2cvpnjdnt.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gt2faajdfvh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wnzeyyhd.html

Ruby: public / protected / private
来源：http://dali.tanke756.top/Article/details/gt2oxdbijwa.html

C#:   public / protected / private / internal
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mkgqojby.html

[G11] getter / setter
来源：http://dali.zhixingplan.top/Article/details/gt2olbaslob.html

Py:   @property 与 @x.setter
来源：http://dali.hnqzz.top/Article/details/gt2ckdfoper.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gt2zjhgwrhu.html

JS:   get name() { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gt2gifhbzuc.html

TS:   get name(): string { return this._name; }
来源：http://dali.316326.xyz/Article/details/gt2pmnshrjz.html

Java: public String getName() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2sywdnjlk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2zjusppbn.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gt2fwpaksmj.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gt2byetimjc.html

[G12] 对象转字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2bsvouqvx.html

Py:   def __str__(self): return self.name
来源：http://dali.yongpay.top/Article/details/gt2cljegbtj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2iebpdqzs.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2zzojbliy.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2dipcglyg.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2pwgxjfyq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2ocpsrivm.html

Ruby: def to_s; @name; end
来源：http://dali.zdqjudy.top/Article/details/gt2yggjdwxf.html

C#:   public override string ToString() => Name;
来源：http://dali.zdqjudy.top/Article/details/gt2wthwanew.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gt2pgaoxpaw.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gt2hqilajho.html

PHP:  $u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2uyisjdsu.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gt2dnlvzzzg.html

TS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gt2pixmkhoi.html

Java: u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2swtfyadj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jianghu66.top/Article/details/gt2buqfamqq.html

Ruby: u.is_a?(User)
来源：http://dali.xinyue.icu/Article/details/gt2vhhsumbv.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gt2foooztud.html

[G14] 数据类 / record
来源：http://dali.wangdashe.top/Article/details/gt2gskcfwxt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sufxvd.cn/Article/details/gt2cxzbpngh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cheryme.top/Article/details/gt2xiendqvk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hammf.cn/Article/details/gt2ciugvrtc.html

TS:   type User = { name: string; age: number };
来源：http://dali.gotoacloud.top/Article/details/gt2nkpuiycs.html

Java: record User(String name, int age) {}
来源：http://dali.ydzc1.top/Article/details/gt2vkqkijit.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jyoumei.cn/Article/details/gt2wandqfzd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shzxlz.cn/Article/details/gt2wwljmlbt.html

C#:   record User(string Name, int Age);
来源：http://dali.ydzc1.top/Article/details/gt2moiipnov.html

[G15] 枚举
来源：http://dali.zhongyouzk.top/Article/details/gt2lbeuwjui.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xinyue.icu/Article/details/gt2nipkxrec.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cucudq.cn/Article/details/gt2qebgytkx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gt2ljodbuez.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gt2avcnfbte.html

Java: enum Color { RED, GREEN }
来源：http://dali.gotoacloud.top/Article/details/gt2scxtfbca.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gt2ggjyrcfb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxuanxn.top/Article/details/gt2gitmdlad.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aibaodan.cn/Article/details/gt2fbvufukc.html

[G16] 对象转数组 / 字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjrsqflx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangtech.top/Article/details/gt2alsopjvf.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqxhtil.html

JS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gt2vurjvhvh.html

TS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gt2nmznesng.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj202588.top/Article/details/gt2ofowhtra.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sxryk.cn/Article/details/gt2zmctahlc.html

Ruby: obj.instance_variables
来源：http://dali.feifeiyinyue.top/Article/details/gt2yhtinpwd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ivvv.top/Article/details/gt2lmefccab.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kfoocnyy.html

H. 异常与错误处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2oduvigwz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jrucjpwc.html

[H01] try / catch 基础
来源：http://dali.nanxuanxn.top/Article/details/gt2nsnztltd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gt2zhtbiswf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ujiktpii.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gt2ruxogdwg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gt2acosieuh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sweek.top/Article/details/gt2depvtnra.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.haohaochexian.top/Article/details/gt2dghgozhv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gt2emyuqwhd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gt2qveoxkgr.html

[H02] finally / ensure 收尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2doduljcb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhengqikj.top/Article/details/gt2zbttelki.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2mojkahdk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2mtjdgvms.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2jgyemyns.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2emncnzff.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guowangkeji.top/Article/details/gt2gzdgmzkb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xinyue.icu/Article/details/gt2rdesfrdh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2tjoahopp.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2pozelzvm.html

Py:   raise ValueError("错误信息")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dspfhdac.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2xxhnkucn.html

JS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2afcvhboc.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2unkgicww.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2zyowvsse.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvxlqkn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ehwqpu.com/Article/details/gt2utnebexs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ksbglers.html

[H04] 自定义异常类型
来源：http://dali.hnqzz.top/Article/details/gt2csiihivw.html

Py:   class MyError(Exception): pass
来源：http://dali.hammf.cn/Article/details/gt2lzhkihzg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gt2bvkdwxrp.html

JS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gt2riaqmeos.html

TS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gt2ihixorxo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2uddgjhis.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gt2oxykmrut.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gt2bdqlbxui.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2vworuehx.html

[H05] 捕获特定类型
来源：http://dali.shuidangran.top/Article/details/gt2cbpzvsdx.html

Py:   except ValueError as e:
来源：http://dali.ybcxt.top/Article/details/gt2hhmhpdfn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jianghu66.top/Article/details/gt2pboppmat.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dwgdorpg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gt2ekwkemcv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2gzlgzdcx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hdemevxm.html

Ruby: rescue ArgumentError => e
来源：http://dali.hysaishi.cn/Article/details/gt2fcqssovz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hjyrsmgt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gt2cvfluouc.html

Py:   value = d.get("k") or default
来源：http://dali.gaohongyu789.top/Article/details/gt2ttxfldxj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gt2eaaebijs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ovydyrhu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gt2tkdhblob.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tpzxsloy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daria6918.cn/Article/details/gt2fzizyagy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gaohongyu789.top/Article/details/gt2kzrsnhie.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gt2ukzymzos.html

[H07] 断言
来源：http://dali.hysaishi.cn/Article/details/gt2lpckbpog.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhongyouzk.top/Article/details/gt2gbuludia.html

PHP:  assert($x > 0);
来源：http://dali.daria6918.cn/Article/details/gt2jhnbqlhm.html

JS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2aywiwerk.html

TS:   console.assert(x > 0);
来源：http://dali.havefunace.top/Article/details/gt2xqlgvumx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gt2oenecvbf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinghuilouyu.cn/Article/details/gt2exealtwi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zdqjudy.top/Article/details/gt2utntpmds.html

C#:   Debug.Assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2lffixkpd.html

[H08] 获取错误信息与堆栈
来源：http://dali.tanke756.top/Article/details/gt2suprrtif.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ehwqpu.com/Article/details/gt2kpsevhbr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.andypj.xyz/Article/details/gt2apkjfdfg.html

JS:   e.message;  e.stack
来源：http://dali.316326.xyz/Article/details/gt2lscnwixm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shzxlz.cn/Article/details/gt2qbwurogm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gxguilac.html

Go:   err.Error()
来源：http://dali.zhiwuduotai.top/Article/details/gt2effbkgdr.html

Ruby: e.message;  e.backtrace
来源：http://dali.nwbrower.top/Article/details/gt2lxllspwm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.birdmap.top/Article/details/gt2cmwixvmy.html

[H09] 带错误码的异常
来源：http://dali.shuidangran.top/Article/details/gt2lshkhkjc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gt2ztygnbcu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tianlin.xyz/Article/details/gt2bdakwrcc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dianchejie.cn/Article/details/gt2ytdgmvpp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gt2odllvqix.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gt2xwxbjimp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cheryme.top/Article/details/gt2isrmyoxx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gt2vjouprjo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nwbrower.top/Article/details/gt2zudzqilx.html

[H10] 资源自动释放
来源：http://dali.jqgufenzy.top/Article/details/gt2ziomxznv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vewkwpmc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dianchejie.cn/Article/details/gt2rnwjmmgp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gt2xfidylln.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gt2cafsscfr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenjidiqi.icu/Article/details/gt2bnukesiy.html

Go:   defer f.Close()
来源：http://dali.nanxuanxn.top/Article/details/gt2nzrwuvnd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sxryk.cn/Article/details/gt2eqanpchm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhwqelsa.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2oxulmaei.html

I. 正则表达式
来源：http://dali.yanxiufei.cn/Article/details/gt2brelrulq.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2nmysxfmj.html

[I01] 判断是否匹配
来源：http://dali.ybcxt.top/Article/details/gt2njhgbfiw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jiagoushi.top/Article/details/gt2jbgytfiv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.316326.xyz/Article/details/gt2syoxxtji.html

JS:   /\d+/.test(s)
来源：http://dali.haohaochexian.top/Article/details/gt2tnutnmos.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gt2aocypujz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wdwwdtyc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvznujf.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gt2wnfupine.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhjwkges.html

[I02] 提取所有匹配
来源：http://dali.birdmap.top/Article/details/gt2egfzuswf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nssluaxr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ydzc1.top/Article/details/gt2ekxpujov.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xprikdar.html

TS:   s.match(/\d+/g)
来源：http://dali.aizwys.cn/Article/details/gt2exywllej.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cqqwz.cn/Article/details/gt2galqoygh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nwbrower.top/Article/details/gt2mjgxsopt.html

Ruby: s.scan(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gt2pgdfdpws.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2fiblvulo.html

[I03] 提取捕获分组
来源：http://dali.ybcxt.top/Article/details/gt2croxauwx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yonumen.top/Article/details/gt2ssgqcleb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2qkhfxxzm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.c1oappe.top/Article/details/gt2usewkwue.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ybcxt.top/Article/details/gt2uelvezvb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yangfankeji.com/Article/details/gt2mnrsxwhu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ehwqpu.com/Article/details/gt2uthtgnfg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2evyoxrhl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhiwuduotai.top/Article/details/gt2bgafigcz.html

[I04] 正则替换
来源：http://dali.hnqzz.top/Article/details/gt2kvgejyny.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.c1oappe.top/Article/details/gt2sdqjnmgr.html


<!-- 参考信息 -->