代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2cmjdawsf.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2ompijmva.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yueranfly.top/Article/details/gt2rnkfjdgp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2qirxnhtx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2dcjrzfso.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2qiiawzci.html

[F11] 复制与移动文件
来源：http://dali.jyoumei.cn/Article/details/gt2guzpiiif.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2ogehfgbl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gt2fyyqfgbk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2rnzijlpb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2xpqkniym.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daria6918.cn/Article/details/gt2wcfooszx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gogol.net.cn/Article/details/gt2afkjjzaj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2qjbageed.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xzptwqbw.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gt2cmsqajjv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ydzc1.top/Article/details/gt2nenlvaum.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sysykeji.top/Article/details/gt2maljspxu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gaohongyu789.top/Article/details/gt2mnnylqnc.html

TS:   // 同上
来源：http://dali.jinqigufen.top/Article/details/gt2siivjgjk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258.top/Article/details/gt2hmsplnze.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cdnleiting.top/Article/details/gt2bahowtjz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tian-w.cn/Article/details/gt2pazetbsv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gt2dupxnvdi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2vnlwwanl.html

G. 面向对象
来源：http://dali.shuidangran.top/Article/details/gt2ljezyhzg.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2jhahguxg.html

[G01] 定义类
来源：http://dali.svipenyu.cn/Article/details/gt2ghgcetou.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gt2zopplwrd.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gt2hoabmhei.html

JS:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gt2olnifajp.html

TS:   class User { name: string = ""; }
来源：http://dali.hywenlv.cn/Article/details/gt2slwrikfo.html

Java: class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2jgeyfkwn.html

Go:   type User struct { Name string }
来源：http://dali.hnqzz.top/Article/details/gt2nutvzsiy.html

Ruby: class User; end
来源：http://dali.bjfxy.top/Article/details/gt2ttzlzeqt.html

C#:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ftpfiack.html

[G02] 构造函数
来源：http://dali.yj202588.top/Article/details/gt2vjqikngd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258.top/Article/details/gt2qdonxwad.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2fugyforg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gt2bsotvvgt.html

TS:   constructor(public name: string) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2dfwzcnes.html

Java: User(String name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gt2yslanydw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gt2eukldflo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cdnleiting.top/Article/details/gt2lcllmdrk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gotoacloud.top/Article/details/gt2uxpkkgvl.html

[G03] 实例属性
来源：http://dali.zhoulong.xyz/Article/details/gt2kfhikkcd.html

Py:   self.name = "x"
来源：http://dali.jyoumei.cn/Article/details/gt2tqrdknso.html

PHP:  public string $name = "x";
来源：http://dali.tian-w.cn/Article/details/gt2vgwfluql.html

JS:   this.name = "x";
来源：http://dali.haohaochexian.top/Article/details/gt2lodymidk.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2ugnxuenq.html

Java: private String name;
来源：http://dali.vqdsnc.cn/Article/details/gt2gtgkctey.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.bjfxy.top/Article/details/gt2nxojbagx.html

Ruby: @name = "x"
来源：http://dali.jianghu66.top/Article/details/gt2lbrrjxgh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cashguo.top/Article/details/gt2pznjflty.html

[G04] 定义方法
来源：http://dali.fzhhl.top/Article/details/gt2yzuqsadr.html

Py:   def greet(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gt2uortkatv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2prqkbjwi.html

JS:   greet() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2mfqlxama.html

TS:   greet(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2ifarjwer.html

Java: String greet() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rdvkkdms.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2zucwnnog.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ppaoggth.html

C#:   public string Greet() => Name;
来源：http://dali.shuidangran.top/Article/details/gt2miwzxadp.html

[G05] 继承
来源：http://dali.tianlin.xyz/Article/details/gt2xsanhmnf.html

Py:   class Admin(User): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pcmcyuta.html

PHP:  class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2pzgbzksh.html

JS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2lmgxokrf.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2hsolggco.html

Java: class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2nxvfbkvc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yvedp.cn/Article/details/gt2ofbkmuea.html

Ruby: class Admin < User; end
来源：http://dali.gaohongyu789.top/Article/details/gt2jlmrucoy.html

C#:   class Admin : User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2yhmednra.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gt2znhwwvmw.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258.top/Article/details/gt2lbhycsdg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2iudxvmnw.html

JS:   greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2mmsbyklm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2vrxuiuqs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2pctcvaqi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gaohongyu789.top/Article/details/gt2jexbizve.html

Ruby: def greet; "admin"; end
来源：http://dali.yangfankeji.com/Article/details/gt2vyrvtsja.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxinkj.top/Article/details/gt2ypyjpfqj.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gt2tmhgxyfa.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gt2wpspitfy.html

PHP:  parent::greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbsuwzin.html

JS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2zpfchzkv.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2delqbxcn.html

Java: super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2cokkwzum.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gt2qydihmou.html

Ruby: super
来源：http://dali.sysykeji.top/Article/details/gt2fvsflijb.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ziobngkh.html

[G08] 静态方法与属性
来源：http://dali.yvedp.cn/Article/details/gt2vlxmmbrm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gt2rgicokfy.html

PHP:  public static function f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2msudkhim.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gt2slgzduag.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2fibmifun.html

Java: static void f() {}
来源：http://dali.bjfxy.top/Article/details/gt2donnydny.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenzaomai.com/Article/details/gt2oxockffv.html

Ruby: def self.f; end
来源：http://dali.cqqwz.cn/Article/details/gt2avapbkmh.html

C#:   public static void F() {}
来源：http://dali.yueranfly.top/Article/details/gt2zqcnxxwi.html

[G09] 接口 / 抽象类
来源：http://dali.fengsongda.top/Article/details/gt2wikvkqhd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gt2wcymcale.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenlongwang.top/Article/details/gt2utgoycof.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuxming.cn/Article/details/gt2yywypudn.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gt2dmxkoiet.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gt2lbmjlpxn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nertdihx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sxryk.cn/Article/details/gt2gzvtzfzs.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangdashe.top/Article/details/gt2qlfrwdvb.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gt2ujgfqkrr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zycfv.cn/Article/details/gt2vpwgmpqv.html

PHP:  public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2byjjdxtf.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gt2rcyqvvuv.html

TS:   public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gt2atgfesth.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gt2erdofden.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gt2oqllyszm.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqbvnqpe.html

C#:   public / protected / private / internal
来源：http://dali.xylfe.cn/Article/details/gt2ufwhzhlm.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gt2csxkojkf.html

Py:   @property 与 @x.setter
来源：http://dali.sxryk.cn/Article/details/gt2xkqwflnk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2wsndmqwt.html

JS:   get name() { return this._name; }
来源：http://dali.meibo888.top/Article/details/gt2uubxcgrm.html

TS:   get name(): string { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gt2xyrlwpfu.html

Java: public String getName() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2svqsyolr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gt2hzncarqy.html

Ruby: attr_accessor :name
来源：http://dali.cashguo.top/Article/details/gt2uuoeqfyi.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2elrepitw.html

[G12] 对象转字符串
来源：http://dali.wangdashe.top/Article/details/gt2iziumzoo.html

Py:   def __str__(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gt2algnryne.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2wqfipyjm.html

JS:   toString() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2pwsudhvf.html

TS:   toString(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2uvytvwpk.html

Java: @Override public String toString() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2ermffofn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gt2kyuxkcpj.html

Ruby: def to_s; @name; end
来源：http://dali.aizwys.cn/Article/details/gt2qbzgpycq.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uuusmncy.html

[G13] 判断对象类型
来源：http://dali.yangfankeji.com/Article/details/gt2msuvzydt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2kobrzskp.html

PHP:  $u instanceof User
来源：http://dali.tian-w.cn/Article/details/gt2vvngfvcs.html

JS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2zvtqvlnp.html

TS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2tbyltgah.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2deevmowo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.0kj1m.cn/Article/details/gt2hpytmfbv.html

Ruby: u.is_a?(User)
来源：http://dali.gotoacloud.top/Article/details/gt2yyzypazt.html

C#:   u is User
来源：http://dali.andypj.xyz/Article/details/gt2cuwbqnzh.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gt2ahjgmzuo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gt2sjtpebwu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigfzy.top/Article/details/gt2jzeijcyv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sxryk.cn/Article/details/gt2ycciosfc.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wwwgidib.html

Java: record User(String name, int age) {}
来源：http://dali.havefunace.top/Article/details/gt2cpwnxsle.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gt2udgsmiak.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gt2nirxeuad.html

C#:   record User(string Name, int Age);
来源：http://dali.shuidangran.top/Article/details/gt2canruwpa.html

[G15] 枚举
来源：http://dali.ydzc1.top/Article/details/gt2qbynfxzh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gt2aaqbnlxu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gt2jfhwzixt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yongpay.top/Article/details/gt2sxdgxaim.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gt2womvqzyk.html

Java: enum Color { RED, GREEN }
来源：http://dali.gaohongyu789.top/Article/details/gt2ppujmbdk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vfqstqjb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gogol.net.cn/Article/details/gt2wommveuu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bgsmakqq.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxuanxn.top/Article/details/gt2mnvqalxb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gotoacloud.top/Article/details/gt2ttwubmzv.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gt2aatyafia.html

JS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2poxcfhqn.html

TS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gt2fwgvygwg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.c1oappe.top/Article/details/gt2mpnymcww.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gt2krskketi.html

Ruby: obj.instance_variables
来源：http://dali.chenlongwang.top/Article/details/gt2eiljiciw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gt2ggkqarxq.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2qviuzoji.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gt2vuyfcvbs.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2wusvinwy.html

[H01] try / catch 基础
来源：http://dali.sufxvd.cn/Article/details/gt2hedjzqmu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gt2lncpkqni.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2tyzyoeaw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxjdtmti.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gt2rqtraxqs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xinyue.icu/Article/details/gt2jrotuleq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ybcxt.top/Article/details/gt2emtifplw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangdashe.top/Article/details/gt2oaokmvri.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vfxlpwxm.html

[H02] finally / ensure 收尾
来源：http://dali.jqgufenzy.top/Article/details/gt2ifwivrme.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gt2uqlsdbve.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2kgbgecnv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2whsxzwfz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2lropseuw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2nwktkami.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.redwolf501.top/Article/details/gt2owowudkp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2equisbwx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2ghkxbopd.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uqhzmnyx.html

Py:   raise ValueError("错误信息")
来源：http://dali.tian-w.cn/Article/details/gt2zsyoyxjd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2jiynlopk.html

JS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2juheurcw.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2ulkrjujy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2kcfuplpw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.kuanghao11.cn/Article/details/gt2pdkexeml.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2edcujepy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fueyrfgx.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gt2dvoqnppd.html

Py:   class MyError(Exception): pass
来源：http://dali.jiagoushi.top/Article/details/gt2qftnvcyz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gt2okfdvvjh.html

JS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2oyjsscwj.html

TS:   class MyError extends Error {}
来源：http://dali.jiagoushi.top/Article/details/gt2nuuzwvuv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ifkvatqw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuanzhike.top/Article/details/gt2viqnnolq.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxinkj.top/Article/details/gt2vvvzvouj.html

C#:   class MyException : Exception {}
来源：http://dali.chenzaomai.com/Article/details/gt2kvdfosiv.html

[H05] 捕获特定类型
来源：http://dali.gzhubu.top/Article/details/gt2urpfubcj.html

Py:   except ValueError as e:
来源：http://dali.xuetiantiany.cn/Article/details/gt2gwooyjny.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sxryk.cn/Article/details/gt2ovlpraaj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2xgsvmfna.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gt2jzdowrmg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gzhubu.top/Article/details/gt2mdxaualb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ydzc1.top/Article/details/gt2qesfcduo.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhoulong.xyz/Article/details/gt2otyctrof.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cucudq.cn/Article/details/gt2utliuces.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jvmzmqvt.html

Py:   value = d.get("k") or default
来源：http://dali.zhengqikj.top/Article/details/gt2ntctsssc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gt2jkdnuhlr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gt2fzywfkxi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gt2fydmoxkw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sweek.top/Article/details/gt2kmrwqapf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj202588.top/Article/details/gt2jhuukmfm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gt2wzpzcwtv.html

C#:   obj?.A?.B ?? default
来源：http://dali.yongpay.top/Article/details/gt2hyvsjngh.html

[H07] 断言
来源：http://dali.birdmap.top/Article/details/gt2hzeabuua.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gt2uycbfuec.html

PHP:  assert($x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2pbfldpsa.html

JS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2ppwchaoo.html

TS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2fenqdncn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2neoopcdr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2impzfnpk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gt2arxjgpix.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gt2ctgscdls.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhengqikj.top/Article/details/gt2nckmhgdd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.aizwys.cn/Article/details/gt2uqyjkuxv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gogol.net.cn/Article/details/gt2dcsyrzfq.html

JS:   e.message;  e.stack
来源：http://dali.sysykeji.top/Article/details/gt2yxtrtfoe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.svipenyu.cn/Article/details/gt2ylthngyg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhixingplan.top/Article/details/gt2ybzkzkpz.html

Go:   err.Error()
来源：http://dali.quarkkingdee.top/Article/details/gt2jeufewem.html

Ruby: e.message;  e.backtrace
来源：http://dali.zycfv.cn/Article/details/gt2nsmvvmil.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2finexmva.html

[H09] 带错误码的异常
来源：http://dali.smart0.xyz/Article/details/gt2jwihhoyo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.fengsongda.top/Article/details/gt2ltyrwunf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ivvv.top/Article/details/gt2ewnlkblk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gt2cejufvyu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2prxpcief.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.quarkkingdee.top/Article/details/gt2vivahqzg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gt2hpefhbww.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ytciqkhg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gt2mtmxvtrp.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gt2rqhapxqm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.quarkkingdee.top/Article/details/gt2ngejvfdr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gt2btrpnwfz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gt2wpcwhirk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gt2kmkijzhu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhiwuduotai.top/Article/details/gt2xcjltxof.html

Go:   defer f.Close()
来源：http://dali.smart0.xyz/Article/details/gt2omclvsuu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tian-w.cn/Article/details/gt2erzieqll.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2rvnoofay.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2avcjlpfh.html

I. 正则表达式
来源：http://dali.ehwqpu.com/Article/details/gt2jksqeztm.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2xonutprl.html

[I01] 判断是否匹配
来源：http://dali.ehwqpu.com/Article/details/gt2cmmtwrph.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xsqqslwq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qifihbjd.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gt2vnoyzzsk.html

TS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2aytbvogk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cashguo.top/Article/details/gt2ubsbznom.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rfpsxlnk.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gt2ggbekeii.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuanzx.com/Article/details/gt2zjtkxryc.html

[I02] 提取所有匹配
来源：http://dali.sufxvd.cn/Article/details/gt2xnocwote.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigufen.top/Article/details/gt2ukatpssv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sufxvd.cn/Article/details/gt2bzyfashp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ybcxt.top/Article/details/gt2zfxydwum.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hcrfriyl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aizwys.cn/Article/details/gt2uoepacuk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nzpqrbvq.html

Ruby: s.scan(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gt2ufwojymm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj202588.top/Article/details/gt2zbittneq.html

[I03] 提取捕获分组
来源：http://dali.daxiang520.top/Article/details/gt2dybxnlia.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yvedp.cn/Article/details/gt2pwvohybp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj202588.top/Article/details/gt2xpuyolfl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shzxlz.cn/Article/details/gt2vvudyjxx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.c1oappe.top/Article/details/gt2zgotflld.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dashuyun.cn/Article/details/gt2nptbxicl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jlsjyb.cn/Article/details/gt2dqazzkox.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2rsiyknnf.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daxiang520.top/Article/details/gt2hqnkzrnd.html

[I04] 正则替换
来源：http://dali.xziqi.cn/Article/details/gt2znhinawn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gt2oqxvuptj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gt2kogfdlil.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.chenlongwang.top/Article/details/gt2axzlwvnn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gt2txmrpygp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gt2vluwuizk.html


<!-- 参考信息 -->