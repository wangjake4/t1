代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2idcrtxrk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2drioucwz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gt2snporebt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yueranfly.top/Article/details/gt2ozwkiulq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rodminku.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uqumnwbw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gt2xfvsstln.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gt2micgopfs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gt2ydwyzcvz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cdnleiting.top/Article/details/gt2zntsvrcp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigufen.top/Article/details/gt2uhtllzlt.html

TS:   // 同上
来源：http://dali.meibo888.top/Article/details/gt2kchipdcs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zycfv.cn/Article/details/gt2vgyrjhtx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cqqwz.cn/Article/details/gt2vzgxnexp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sysykeji.top/Article/details/gt2ulizwrta.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigufen.top/Article/details/gt2pimwakmw.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2xpfnqiit.html

G. 面向对象
来源：http://dali.zhengqikj.top/Article/details/gt2hprgrjwv.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2qoylxpzp.html

[G01] 定义类
来源：http://dali.jinqigfzy.top/Article/details/gt2fcwfjtre.html

Py:   class User: pass
来源：http://dali.bjfxy.top/Article/details/gt2eiwatylp.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qkcqnpll.html

JS:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2jslyckeg.html

TS:   class User { name: string = ""; }
来源：http://dali.ppjwa.cn/Article/details/gt2raodimyi.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vpgsnoto.html

Go:   type User struct { Name string }
来源：http://dali.ydzc1.top/Article/details/gt2gpdplekw.html

Ruby: class User; end
来源：http://dali.gzhubu.top/Article/details/gt2kvhljuwn.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gt2kojrtcmy.html

[G02] 构造函数
来源：http://dali.chenzaomai.com/Article/details/gt2ybltfcuu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jianghu66.top/Article/details/gt2ofkzrrzg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2bnbevrnz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gt2xuqocrpy.html

TS:   constructor(public name: string) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ntgpcput.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wfkliwlm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjehlovs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2npssqfph.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nagljhsb.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gt2usivugzb.html

Py:   self.name = "x"
来源：http://dali.sysykeji.top/Article/details/gt2wddtmkts.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gt2clpbduor.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2jxrqvexi.html

TS:   name: string = "x";
来源：http://dali.jqgfzy.top/Article/details/gt2wvpephns.html

Java: private String name;
来源：http://dali.vqdsnc.cn/Article/details/gt2ufegysbz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pycfn.com/Article/details/gt2ynntpdtz.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gt2zhzxgudq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ehwqpu.com/Article/details/gt2dxxgjydi.html

[G04] 定义方法
来源：http://dali.jianghu66.top/Article/details/gt2wfeufxyl.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gt2mscsnqyw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2zvvelmoc.html

JS:   greet() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2jlaavrof.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gt2xkqzhdvs.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2bjmllzli.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gt2vvqdazkc.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gt2gacetfqy.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2xjultnru.html

[G05] 继承
来源：http://dali.yvedp.cn/Article/details/gt2lxaobjnb.html

Py:   class Admin(User): pass
来源：http://dali.dianchejie.cn/Article/details/gt2ktnwmfvz.html

PHP:  class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ecpqnwxg.html

JS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2kkimlttp.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2uttxfngg.html

Java: class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqfbakjj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gqproujx.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2cgnruelq.html

C#:   class Admin : User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2tqqjqhjk.html

[G06] 重写方法
来源：http://dali.smart0.xyz/Article/details/gt2rblizlgs.html

Py:   def greet(self): return "admin"
来源：http://dali.dashuyun.cn/Article/details/gt2gkceaqqt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2civwaaad.html

JS:   greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2qwoyveks.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vtxloypo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2qkcepidm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258888.top/Article/details/gt2anikkrvl.html

Ruby: def greet; "admin"; end
来源：http://dali.hnxiangtu.top/Article/details/gt2dbfruxgj.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gt2gsrcefcu.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gt2uezilpvo.html

Py:   super().greet()
来源：http://dali.quarkkingdee.top/Article/details/gt2epuhpdtd.html

PHP:  parent::greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2eowqnjpt.html

JS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxvvbyxf.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2ydgfyfxy.html

Java: super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2zbwbmiru.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gt2hkktzrvl.html

Ruby: super
来源：http://dali.jqgfzy.top/Article/details/gt2cgvpphts.html

C#:   base.Greet();
来源：http://dali.cqqwz.cn/Article/details/gt2szhxktts.html

[G08] 静态方法与属性
来源：http://dali.zhongyouzk.top/Article/details/gt2gtngmuzi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2ftktzwee.html

PHP:  public static function f() {}
来源：http://dali.bjfxy.top/Article/details/gt2ilamxrhk.html

JS:   static f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ignrsszn.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gt2gamsdpow.html

Java: static void f() {}
来源：http://dali.yj20258.top/Article/details/gt2aeihsrwn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgfzy.top/Article/details/gt2fprwphzq.html

Ruby: def self.f; end
来源：http://dali.0kj1m.cn/Article/details/gt2lajfhztf.html

C#:   public static void F() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rbgobtgi.html

[G09] 接口 / 抽象类
来源：http://dali.chenlongwang.top/Article/details/gt2sirzkkxe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shzxlz.cn/Article/details/gt2oonqmnsy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daria6918.cn/Article/details/gt2ypwlsrms.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aibaodan.cn/Article/details/gt2pxxrlrni.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigfzy.top/Article/details/gt2fwvjbapv.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2rqqwswcb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ckjgdznh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shuidangran.top/Article/details/gt2anvkqcap.html

C#:   interface IShape { double Area(); }
来源：http://dali.316326.xyz/Article/details/gt2xhwdwmdp.html

[G10] 访问控制
来源：http://dali.cqqwz.cn/Article/details/gt2ibhgbzgi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hbmxabjm.html

PHP:  public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyzglgt.html

JS:   #private 字段；其余公开
来源：http://dali.0kj1m.cn/Article/details/gt2iwxrelzi.html

TS:   public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gt2jgorvyfg.html

Java: public / protected / private / 默认包级
来源：http://dali.sufxvd.cn/Article/details/gt2jgasuank.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sysykeji.top/Article/details/gt2fmtubylv.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gt2asewfjfo.html

C#:   public / protected / private / internal
来源：http://dali.yongpay.top/Article/details/gt2mkrnemyl.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gt2xponzjia.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gt2dgnvpspw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gt2nufkrtan.html

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gt2zdycsqlj.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gt2nutlwsbe.html

Java: public String getName() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2jstmledv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gt2ykhjuahz.html

Ruby: attr_accessor :name
来源：http://dali.sufxvd.cn/Article/details/gt2wmspdpid.html

C#:   public string Name { get; set; }
来源：http://dali.jyoumei.cn/Article/details/gt2stujtmxj.html

[G12] 对象转字符串
来源：http://dali.yongpay.top/Article/details/gt2qgllbdyc.html

Py:   def __str__(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gt2jthnyawg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2vqlrvyux.html

JS:   toString() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2vxcygejg.html

TS:   toString(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2xscksloi.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2etidjgwm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gt2hdpdnkav.html

Ruby: def to_s; @name; end
来源：http://dali.guannengcc.top/Article/details/gt2tjhxuitz.html

C#:   public override string ToString() => Name;
来源：http://dali.havefunace.top/Article/details/gt2nonftkda.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gt2zitcvwri.html

Py:   isinstance(u, User)
来源：http://dali.iojbl.cn/Article/details/gt2pncplzxw.html

PHP:  $u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gt2ypzrpqfu.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2vepyrdwf.html

TS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2vfvqwqgb.html

Java: u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2rggtvzav.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gt2dtusavho.html

Ruby: u.is_a?(User)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sicemyyv.html

C#:   u is User
来源：http://dali.mhx1999.top/Article/details/gt2mnvanbpp.html

[G14] 数据类 / record
来源：http://dali.dianchejie.cn/Article/details/gt2lxqbvtfd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fzhhl.top/Article/details/gt2wghohfyt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.feifeiyinyue.top/Article/details/gt2ofvipkml.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zdqjudy.top/Article/details/gt2rvxilvrm.html

TS:   type User = { name: string; age: number };
来源：http://dali.cqqwz.cn/Article/details/gt2cpiofitc.html

Java: record User(String name, int age) {}
来源：http://dali.fengsongda.top/Article/details/gt2mhnmkfoh.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qangeoru.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gt2qjcbcagh.html

C#:   record User(string Name, int Age);
来源：http://dali.jianghu66.top/Article/details/gt2wiyaznlp.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gt2djlfcjas.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daxiang520.top/Article/details/gt2gwskxsgl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxinkj.top/Article/details/gt2ouuqfche.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sxryk.cn/Article/details/gt2nbimkkkd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2dpkmtkii.html

Java: enum Color { RED, GREEN }
来源：http://dali.cashguo.top/Article/details/gt2pmagbyds.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhixingplan.top/Article/details/gt2goqfufrm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.havefunace.top/Article/details/gt2acajhuko.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2ceewxqur.html

[G16] 对象转数组 / 字典
来源：http://dali.wangdashe.top/Article/details/gt2lqvowmfx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hammf.cn/Article/details/gt2zyuewxkq.html

PHP:  get_object_vars($obj);
来源：http://dali.chenlongwang.top/Article/details/gt2tdzfevgm.html

JS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2rtrxfyww.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zchxexuk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.svipenyu.cn/Article/details/gt2tbzfrund.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gt2qohxyckt.html

Ruby: obj.instance_variables
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kejpqxpl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gt2yeenxwxj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2kluibgqg.html

H. 异常与错误处理
来源：http://dali.haohaochexian.top/Article/details/gt2yvjcuagl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2uxojfdtc.html

[H01] try / catch 基础
来源：http://dali.nanxuanxn.top/Article/details/gt2mcyixzlp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xziqi.cn/Article/details/gt2jrkpjxyr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangdashe.top/Article/details/gt2rizsaciq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gt2zxkuowga.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gt2hcnylqtx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gt2usjfbwub.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gt2qfmgfkpf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gzhubu.top/Article/details/gt2gfggdxgo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.vqdsnc.cn/Article/details/gt2veyhtxkv.html

[H02] finally / ensure 收尾
来源：http://dali.vqdsnc.cn/Article/details/gt2ogahkbdw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.c1oappe.top/Article/details/gt2tevaayvv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2uzeaapno.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2vclhfspc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2cfispmkk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2wemdsxrl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhiwuduotai.top/Article/details/gt2jyyalacl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gaohongyu789.top/Article/details/gt2lpgamatm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2lskdjxvh.html

[H03] 主动抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gt2byesucnc.html

Py:   raise ValueError("错误信息")
来源：http://dali.fengsongda.top/Article/details/gt2vedeevpz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2jrlunrwl.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2zqffnhum.html

TS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2bjbambwi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2rzxmymjv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gt2mpmeuqlw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ccqakvmy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2nnmleoyg.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gt2qkmagymd.html

Py:   class MyError(Exception): pass
来源：http://dali.andypj.xyz/Article/details/gt2vpxkscqp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2nburvodj.html

JS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gt2yutdnhcx.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gt2wmdhfseq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gt2vvwofnyi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ppjwa.cn/Article/details/gt2ccwwshua.html

Ruby: class MyError < StandardError; end
来源：http://dali.dashuyun.cn/Article/details/gt2kekvzfku.html

C#:   class MyException : Exception {}
来源：http://dali.quarkkingdee.top/Article/details/gt2sfpojryh.html

[H05] 捕获特定类型
来源：http://dali.hfpthk.cn/Article/details/gt2oendauzv.html

Py:   except ValueError as e:
来源：http://dali.zycfv.cn/Article/details/gt2wahpxpmr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.birdmap.top/Article/details/gt2vczdmqbl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gt2ukonlxxm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2xteqkjwg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2khybxalw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jianghu66.top/Article/details/gt2fmioshtb.html

Ruby: rescue ArgumentError => e
来源：http://dali.xziqi.cn/Article/details/gt2pzliujae.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.smart0.xyz/Article/details/gt2zqoaybdi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hfpthk.cn/Article/details/gt2vftvkppe.html

Py:   value = d.get("k") or default
来源：http://dali.yongpay.top/Article/details/gt2lzziwiuh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gt2zgyndxnn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gt2qzcrsqde.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dvpbaxkk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gogol.net.cn/Article/details/gt2ovotvjsk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuanzx.com/Article/details/gt2wwtlmoix.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ydzc1.top/Article/details/gt2iiphptvv.html

C#:   obj?.A?.B ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2yqqjevsn.html

[H07] 断言
来源：http://dali.snrcjt.cn/Article/details/gt2kaxwecep.html

Py:   assert x > 0, "必须为正"
来源：http://dali.bjfxy.top/Article/details/gt2tgtjryfp.html

PHP:  assert($x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2ecaarsof.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2ecinoley.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2qolgpgel.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gt2ndjhrzvf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pycfn.com/Article/details/gt2mlypcykv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuanzx.com/Article/details/gt2fltwbskk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2bewoekib.html

[H08] 获取错误信息与堆栈
来源：http://dali.andypj.xyz/Article/details/gt2jpbdockq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daria6918.cn/Article/details/gt2mqknrkry.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ybcxt.top/Article/details/gt2xulyhhrs.html

JS:   e.message;  e.stack
来源：http://dali.tianlin.xyz/Article/details/gt2dsdkzwda.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gaohongyu789.top/Article/details/gt2sxtnfeib.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ehwqpu.com/Article/details/gt2sumfziia.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gt2rejrggfa.html

Ruby: e.message;  e.backtrace
来源：http://dali.haohaochexian.top/Article/details/gt2sgauwtqa.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ybcxt.top/Article/details/gt2scdiccha.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gt2vfrqppjf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gt2gyzcnyzr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gt2odqequyn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.snrcjt.cn/Article/details/gt2nrzhfutg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yanxiufei.cn/Article/details/gt2svbcygzl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yanxiufei.cn/Article/details/gt2vqcywjne.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fengsongda.top/Article/details/gt2maporbmz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nrnxinik.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gt2cliosdyg.html

[H10] 资源自动释放
来源：http://dali.yueranfly.top/Article/details/gt2awlimvpy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gt2vdgkptlz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jqgufenzy.top/Article/details/gt2jdltlpoh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gt2lytwyjfj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gt2moqygltw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnxiangtu.top/Article/details/gt2xktvlana.html

Go:   defer f.Close()
来源：http://dali.yj20258.top/Article/details/gt2uyefcjvn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuanzhike.top/Article/details/gt2ftgmnfnv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2igiuzzqv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hjfrtmtc.html

I. 正则表达式
来源：http://dali.ehwqpu.com/Article/details/gt2alhzhdxx.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2dkvuzqmp.html

[I01] 判断是否匹配
来源：http://dali.xinyue.icu/Article/details/gt2wnvctxen.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cdnleiting.top/Article/details/gt2iwarykkt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2xzhifqxw.html

JS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gt2etsxziqp.html

TS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gt2xkhzhhoi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jianghu66.top/Article/details/gt2fegccddp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.smart0.xyz/Article/details/gt2idmyurbs.html

Ruby: s.match?(/\d+/)
来源：http://dali.hammf.cn/Article/details/gt2oviucucy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.guannengcc.top/Article/details/gt2xzrmaadt.html

[I02] 提取所有匹配
来源：http://dali.aizwys.cn/Article/details/gt2tmebnngb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gt2guubaczd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jianghu66.top/Article/details/gt2bvnxshho.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jinqigufen.top/Article/details/gt2jqjfwryz.html

TS:   s.match(/\d+/g)
来源：http://dali.yuanzhike.top/Article/details/gt2wojcblpy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.smart0.xyz/Article/details/gt2hdfhhygx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqrjywve.html

Ruby: s.scan(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gt2wyuudcid.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2thrhtvyf.html

[I03] 提取捕获分组
来源：http://dali.yvedp.cn/Article/details/gt2pqapmcdb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjxornry.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hysaishi.cn/Article/details/gt2tsvetvfr.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.andypj.xyz/Article/details/gt2umtekemi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.redwolf501.top/Article/details/gt2aatgnqim.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.cqqwz.cn/Article/details/gt2reannjql.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gogol.net.cn/Article/details/gt2sroiwgte.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.guowangkeji.top/Article/details/gt2tghwojeo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cprlvqvb.html

[I04] 正则替换
来源：http://dali.yj20258.top/Article/details/gt2fagpyrus.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yzatdgtq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2veszdziz.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yuanzhike.top/Article/details/gt2yigcprua.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gt2jghwutuu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.iojbl.cn/Article/details/gt2zxookldj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ybcxt.top/Article/details/gt2glywnelb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cdnleiting.top/Article/details/gt2jllfnoil.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gt2gaesvlwv.html

[I05] 按正则拆分
来源：http://dali.fzhhl.top/Article/details/gt2cyzfbtao.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ppjwa.cn/Article/details/gt2efrgoswi.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dsxotdpz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gt2dqdbnjcq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gt2wsipdnhy.html


<!-- 参考信息 -->