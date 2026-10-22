代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2zszmezfq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2tsjmyzyd.html

[F11] 复制与移动文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yijcigrz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2pjjikfqe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.smart0.xyz/Article/details/gt2iflmiagg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2guhmrxgu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2rpycfyqn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hammf.cn/Article/details/gt2yrpgcwvo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gt2zbgwmnsv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2olurckfx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gt2nknfkfoc.html

[F12] CSV 读写
来源：http://dali.cqqwz.cn/Article/details/gt2wbcbhlvu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.andypj.xyz/Article/details/gt2ffzvxyex.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gt2ghrtutix.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gt2qajcdoeo.html

TS:   // 同上
来源：http://dali.yuanzhike.top/Article/details/gt2oaeszimz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigufen.top/Article/details/gt2jrtvypea.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.smart0.xyz/Article/details/gt2pesefvrm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gt2czyyxxup.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangshuangyany.cn/Article/details/gt2oaxhaskm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwvvqzq.html

G. 面向对象
来源：http://dali.nanxinkj.top/Article/details/gt2goxpppbg.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2vdlqovvc.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gt2doicdayb.html

Py:   class User: pass
来源：http://dali.gotoacloud.top/Article/details/gt2ztojwuzo.html

PHP:  class User {}
来源：http://dali.hfpthk.cn/Article/details/gt2lrdvnimh.html

JS:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2kslutknb.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vwbxhkiu.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgxrflq.html

Go:   type User struct { Name string }
来源：http://dali.gogol.net.cn/Article/details/gt2maktfifk.html

Ruby: class User; end
来源：http://dali.zycfv.cn/Article/details/gt2oxyjvqrb.html

C#:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2xllnevjn.html

[G02] 构造函数
来源：http://dali.ivvv.top/Article/details/gt2otchdplg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.quarkkingdee.top/Article/details/gt2hwxyghbi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuanzhike.top/Article/details/gt2cctqvxeg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ondqlcpi.html

TS:   constructor(public name: string) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2sojwjxzi.html

Java: User(String name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gt2ltuxwyjr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gzhubu.top/Article/details/gt2atjzuhhb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2loybvwry.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gt2gybxbcrc.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gt2ymdqavnc.html

Py:   self.name = "x"
来源：http://dali.smart0.xyz/Article/details/gt2zagbwfpo.html

PHP:  public string $name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2ujfezfgm.html

JS:   this.name = "x";
来源：http://dali.smart0.xyz/Article/details/gt2nizzicfi.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2ecutiehj.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gt2qoasumlu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ndxzaboc.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtogensz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ydzc1.top/Article/details/gt2ujvawubl.html

[G04] 定义方法
来源：http://dali.wangshuangyany.cn/Article/details/gt2oaldetgt.html

Py:   def greet(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gt2mbnzuooj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gt2uhpyvude.html

JS:   greet() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2dwcnvsbv.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2lqpezigu.html

Java: String greet() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2bwueqrka.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gt2ymjjnlzv.html

Ruby: def greet; @name; end
来源：http://dali.nwbrower.top/Article/details/gt2xmvploet.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gt2budjttgo.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gt2mdmohibp.html

Py:   class Admin(User): pass
来源：http://dali.nanxinkj.top/Article/details/gt2ffuzoowl.html

PHP:  class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2wtsqudns.html

JS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2upbjeiav.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2trwxmsux.html

Java: class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gt2kqdwyqsk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gt2kfpvqrmh.html

Ruby: class Admin < User; end
来源：http://dali.cashguo.top/Article/details/gt2mpzcmgda.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2bprrilsq.html

[G06] 重写方法
来源：http://dali.sufxvd.cn/Article/details/gt2piupoyuu.html

Py:   def greet(self): return "admin"
来源：http://dali.sufxvd.cn/Article/details/gt2wqjimjwr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vdvhtajt.html

JS:   greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2lgwgmjoh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2tpbtsdyu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gt2jvociwpe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijsriaqj.html

Ruby: def greet; "admin"; end
来源：http://dali.yvedp.cn/Article/details/gt2rxavqlxy.html

C#:   public override string Greet() => "admin";
来源：http://dali.ybcxt.top/Article/details/gt2rgsoflvp.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gt2vvoyfbor.html

Py:   super().greet()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hlaqfadm.html

PHP:  parent::greet();
来源：http://dali.dianchejie.cn/Article/details/gt2bvuopnau.html

JS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nkdezhvz.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gt2vagdtnhz.html

Java: super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2aybinjig.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhiwuduotai.top/Article/details/gt2hccxrigd.html

Ruby: super
来源：http://dali.hfpthk.cn/Article/details/gt2ztaedhew.html

C#:   base.Greet();
来源：http://dali.birdmap.top/Article/details/gt2ktnjmbis.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gt2alvitklr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jianghu66.top/Article/details/gt2tdsjinha.html

PHP:  public static function f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2sdvtusoz.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2yumxfzfi.html

TS:   static f(): void {}
来源：http://dali.xylfe.cn/Article/details/gt2dgptronh.html

Java: static void f() {}
来源：http://dali.hammf.cn/Article/details/gt2utunojcj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sweek.top/Article/details/gt2snzdyfph.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gt2bajjobzc.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gt2jfgkqqji.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gt2xaqnzaon.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gt2bpjmhwjt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gt2tyfpjwlm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258.top/Article/details/gt2fncsucin.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gt2flatpkek.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gt2cajpvdgc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gt2eibfkoss.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gt2psvbzjfs.html

C#:   interface IShape { double Area(); }
来源：http://dali.daxiang520.top/Article/details/gt2sygwaxmn.html

[G10] 访问控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hptnpusf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2gioxhixv.html

PHP:  public / protected / private
来源：http://dali.c1oappe.top/Article/details/gt2xkcezhhr.html

JS:   #private 字段；其余公开
来源：http://dali.tanke756.top/Article/details/gt2kojnstdl.html

TS:   public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gt2myhchtlp.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxuanxn.top/Article/details/gt2fkcqmqag.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.c1oappe.top/Article/details/gt2psyrprlx.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gt2wjdlnouf.html

C#:   public / protected / private / internal
来源：http://dali.fzhhl.top/Article/details/gt2hnegouzm.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gt2lpxnfelp.html

Py:   @property 与 @x.setter
来源：http://dali.jlsjyb.cn/Article/details/gt2iydfgohs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gt2aanazsrb.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gt2rufpldzm.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gt2lwmdcjtw.html

Java: public String getName() { return name; }
来源：http://dali.cashguo.top/Article/details/gt2cqfmluoi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2xpsptupy.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gt2xbblnrqn.html

C#:   public string Name { get; set; }
来源：http://dali.kuanghao11.cn/Article/details/gt2yzygcixr.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gt2xqhgqgou.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gt2pcvwnjwc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ktnxepzh.html

JS:   toString() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2pczodvdi.html

TS:   toString(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gt2aqykrohr.html

Java: @Override public String toString() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2jzwxakdq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2slrhtyec.html

Ruby: def to_s; @name; end
来源：http://dali.ehwqpu.com/Article/details/gt2cyrvzkkq.html

C#:   public override string ToString() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2srfzvkub.html

[G13] 判断对象类型
来源：http://dali.aibaodan.cn/Article/details/gt2mhhpchje.html

Py:   isinstance(u, User)
来源：http://dali.jlsjyb.cn/Article/details/gt2kfsqkujk.html

PHP:  $u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gt2edhfpjad.html

JS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2vmcoaevy.html

TS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2spsoqfqg.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2osvdioop.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fengsongda.top/Article/details/gt2xatlllzh.html

Ruby: u.is_a?(User)
来源：http://dali.haohaochexian.top/Article/details/gt2pvbpdzfo.html

C#:   u is User
来源：http://dali.zhengqikj.top/Article/details/gt2bnefbhzr.html

[G14] 数据类 / record
来源：http://dali.andypj.xyz/Article/details/gt2ghlybuvl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xylfe.cn/Article/details/gt2qtktpcqf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tanke756.top/Article/details/gt2vjnquvfm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dashuyun.cn/Article/details/gt2nomoypsk.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgufenzy.top/Article/details/gt2khtxsinj.html

Java: record User(String name, int age) {}
来源：http://dali.nanxinkj.top/Article/details/gt2wukpnfmp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhnsnyzz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hywenlv.cn/Article/details/gt2sglmguwo.html

C#:   record User(string Name, int Age);
来源：http://dali.wangdashe.top/Article/details/gt2yiwpryxt.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gt2ydvsbplr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gt2zjucayni.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewjksmxu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hysaishi.cn/Article/details/gt2pdmhexky.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gt2nztmlpuy.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gt2qavelwtv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gt2jrxnemrk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.quarkkingdee.top/Article/details/gt2irpkczgy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2bqzjkpml.html

[G16] 对象转数组 / 字典
来源：http://dali.pycfn.com/Article/details/gt2yexdcdsv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gt2xdzhmznj.html

PHP:  get_object_vars($obj);
来源：http://dali.svipenyu.cn/Article/details/gt2zgmqhqcw.html

JS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gt2uahpcroh.html

TS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2rqszhryx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenlongwang.top/Article/details/gt2gcbseroh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.kuanghao11.cn/Article/details/gt2xxhfokmq.html

Ruby: obj.instance_variables
来源：http://dali.ehwqpu.com/Article/details/gt2spnkkzwv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gt2galkzocp.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2hkipozzh.html

H. 异常与错误处理
来源：http://dali.yj20258.top/Article/details/gt2sjafmird.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2xdsrbfwd.html

[H01] try / catch 基础
来源：http://dali.smart0.xyz/Article/details/gt2heqjphkf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gt2wpcdwrqm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gt2kfwuyffe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lgvatnya.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gt2oowamzil.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pycfn.com/Article/details/gt2sqqgxgoq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.quarkkingdee.top/Article/details/gt2mgdoaqzv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.svipenyu.cn/Article/details/gt2rncgtfxn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.haohaochexian.top/Article/details/gt2cwzzyzyt.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gt2wylivlno.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gt2eoyzclaf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2wqitrroy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2lxdbnrbl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2pcyswoza.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2aqpyejqc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258.top/Article/details/gt2vhjmhcil.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gt2codcnpyh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2jskvqacx.html

[H03] 主动抛出异常
来源：http://dali.pycfn.com/Article/details/gt2cveyitlj.html

Py:   raise ValueError("错误信息")
来源：http://dali.fengsongda.top/Article/details/gt2djnxoeny.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2gunzemkw.html

JS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2yokvfvrt.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hjaqhsct.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2xxyctimh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.snrcjt.cn/Article/details/gt2nkpxrsfq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hflwqxhz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2amaqufkd.html

[H04] 自定义异常类型
来源：http://dali.iojbl.cn/Article/details/gt2cxqmqkjt.html

Py:   class MyError(Exception): pass
来源：http://dali.aibaodan.cn/Article/details/gt2ckyrndfh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gt2bjmwqyrn.html

JS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2vzbobgfm.html

TS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gt2rqjfoxsm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tcwldxhz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gt2wsxvqaja.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2chxcdntj.html

C#:   class MyException : Exception {}
来源：http://dali.zhengqikj.top/Article/details/gt2rjqpkcik.html

[H05] 捕获特定类型
来源：http://dali.sysykeji.top/Article/details/gt2dazbvvgs.html

Py:   except ValueError as e:
来源：http://dali.iojbl.cn/Article/details/gt2pyspfdxx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gt2tzcogxos.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gt2rassudhl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gt2fgzolygq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gt2xdjwxfng.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gt2mxohvctz.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gt2mpagskll.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2qstarzpg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ybcxt.top/Article/details/gt2rxmdiyre.html

Py:   value = d.get("k") or default
来源：http://dali.chenlongwang.top/Article/details/gt2krexdgrr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.meibo888.top/Article/details/gt2klizlovd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2tjadayjw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gt2tbncpuno.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenjidiqi.icu/Article/details/gt2trmxccas.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ybcxt.top/Article/details/gt2rercwjos.html

Ruby: d&.dig(:a, :b)
来源：http://dali.quarkkingdee.top/Article/details/gt2xidvcitg.html

C#:   obj?.A?.B ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2tnwtczbv.html

[H07] 断言
来源：http://dali.jqgufenzy.top/Article/details/gt2bgxtdlid.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tianlin.xyz/Article/details/gt2svdpiwqc.html

PHP:  assert($x > 0);
来源：http://dali.yonumen.top/Article/details/gt2lpijdysd.html

JS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2rrtrjvfq.html

TS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gt2njhmcyhc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.9152youxi.cn/Article/details/gt2rftqdcga.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tanke756.top/Article/details/gt2ecijtlsq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sufxvd.cn/Article/details/gt2krdpeovu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2ntutyfhf.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2fcwsdjxu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zdqjudy.top/Article/details/gt2ekfnsdtl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hysaishi.cn/Article/details/gt2qwbwkcvp.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gt2fkrfdhfe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnqzz.top/Article/details/gt2ppwxpbsu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aibaodan.cn/Article/details/gt2cfrgznvn.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gt2fusctgng.html

Ruby: e.message;  e.backtrace
来源：http://dali.kuanghao11.cn/Article/details/gt2bjsvdzmu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ltocxyfq.html

[H09] 带错误码的异常
来源：http://dali.zhoulong.xyz/Article/details/gt2txqpekvr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ivvv.top/Article/details/gt2erxgrhyi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xtdgbtly.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sysykeji.top/Article/details/gt2ienwfdvl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jianghu66.top/Article/details/gt2aigoxjvw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xziqi.cn/Article/details/gt2vzmmwtjf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daria6918.cn/Article/details/gt2hulrdwoq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yonumen.top/Article/details/gt2smlcxned.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gt2iismgxbu.html

[H10] 资源自动释放
来源：http://dali.pycfn.com/Article/details/gt2mjtoxegh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj202588.top/Article/details/gt2vnzqotwi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cheryme.top/Article/details/gt2rmyefbvo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gt2vimpcepr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2bsforydx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fzhhl.top/Article/details/gt2vgmmzagw.html

Go:   defer f.Close()
来源：http://dali.yanxiufei.cn/Article/details/gt2hqdfwfkq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gt2uzlnkfnc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urqmulfs.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2hkcwusny.html

I. 正则表达式
来源：http://dali.bjfxy.top/Article/details/gt2tdrssvar.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ugbndpet.html

[I01] 判断是否匹配
来源：http://dali.shuidangran.top/Article/details/gt2wbolffnp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.redwolf501.top/Article/details/gt2ditwigkp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwiztyhy.html

JS:   /\d+/.test(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xdlimysr.html

TS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2erayditp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gt2bnxqdmes.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hnqzz.top/Article/details/gt2ovfrqacl.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cemtugbd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.redwolf501.top/Article/details/gt2koqmvmtd.html

[I02] 提取所有匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vjvohaig.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj202588.top/Article/details/gt2ejfeozsc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhoulong.xyz/Article/details/gt2edpxqsmh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxuanxn.top/Article/details/gt2cqclezom.html

TS:   s.match(/\d+/g)
来源：http://dali.quarkkingdee.top/Article/details/gt2cxutwqld.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ksphehed.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tkklvprd.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hclerldf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2lsgdpqnu.html

[I03] 提取捕获分组
来源：http://dali.bjfxy.top/Article/details/gt2kzdfcwlw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258888.top/Article/details/gt2ufruture.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.mhx1999.top/Article/details/gt2xupzoqzd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sysykeji.top/Article/details/gt2lobxwhko.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhongyouzk.top/Article/details/gt2cgxpqacm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2easdnnfc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zycfv.cn/Article/details/gt2hbbndppx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ybcxt.top/Article/details/gt2osdaeqsu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhoulong.xyz/Article/details/gt2ngerhuky.html

[I04] 正则替换
来源：http://dali.shuidangran.top/Article/details/gt2hnzkrbmi.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cucudq.cn/Article/details/gt2oxwjxpai.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gt2sgjjafij.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.c1oappe.top/Article/details/gt2hiesbnsv.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gt2ldrktsbv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gt2haeaeyrw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgfzy.top/Article/details/gt2ekdgyxyj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.nanxinkj.top/Article/details/gt2gtdovlrt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fstkefti.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gt2mefjwbkg.html


<!-- 参考信息 -->