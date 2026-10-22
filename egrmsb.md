代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtkqvoofpe.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtsekopmds.html

[F11] 复制与移动文件
来源：http://dali.jqgfzy.top/Article/details/gtzxrutfmt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzycnkezk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtstczjviu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtabdvlrll.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtmludlwii.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.smart0.xyz/Article/details/gtvxjrtnwi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gttizjdxcq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtrwbcgdcb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcclebipw.html

[F12] CSV 读写
来源：http://dali.hnxiangtu.top/Article/details/gthlrwjdul.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhppbwkh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenjidiqi.icu/Article/details/gtvzysjrhl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sysykeji.top/Article/details/gtqcsrrylg.html

TS:   // 同上
来源：http://dali.0kj1m.cn/Article/details/gtljdiyynp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gtsfkacmyu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xylfe.cn/Article/details/gtihhqcazr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aibaodan.cn/Article/details/gtyqtdezei.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhengqikj.top/Article/details/gtnwqifzlt.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtsuhizgku.html

G. 面向对象
来源：http://dali.9152youxi.cn/Article/details/gttrwzxmjq.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtsqfbwabg.html

[G01] 定义类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcnspywu.html

Py:   class User: pass
来源：http://dali.pengpengdd.cyou/Article/details/gtvhukobgh.html

PHP:  class User {}
来源：http://dali.mhx1999.top/Article/details/gtaydsldlf.html

JS:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gtjynafkdw.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gtnkkdzger.html

Java: class User {}
来源：http://dali.tian-w.cn/Article/details/gtioihvhgq.html

Go:   type User struct { Name string }
来源：http://dali.chenlongwang.top/Article/details/gtehqwyioi.html

Ruby: class User; end
来源：http://dali.yuanzhike.top/Article/details/gtmvrtkxip.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtbkwmwbgy.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhfcqczu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gtwyfdxcub.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sufxvd.cn/Article/details/gtgkfrusmg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtzcqoydsi.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gtdguwdfaz.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtzegkslxq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenjidiqi.icu/Article/details/gtftpnhgqy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gogol.net.cn/Article/details/gtbgyegyxy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yongpay.top/Article/details/gtbinbfjum.html

[G03] 实例属性
来源：http://dali.yangfankeji.com/Article/details/gtyhzcbosh.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqmuhnke.html

PHP:  public string $name = "x";
来源：http://dali.sysykeji.top/Article/details/gtgoppnvfm.html

JS:   this.name = "x";
来源：http://dali.nwbrower.top/Article/details/gtkvmbivsn.html

TS:   name: string = "x";
来源：http://dali.hnqzz.top/Article/details/gtlelngdyr.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gttmqgnwcx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuanzhike.top/Article/details/gtbjzpcwdp.html

Ruby: @name = "x"
来源：http://dali.fengsongda.top/Article/details/gtwjxqvzkj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gtsmhkyzbd.html

[G04] 定义方法
来源：http://dali.sufxvd.cn/Article/details/gtmmojrgxx.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtjmfqqedg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtocirvtmh.html

JS:   greet() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtfvrumdwx.html

TS:   greet(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtpkykjkxo.html

Java: String greet() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtxmqoeyho.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtbqokjbnh.html

Ruby: def greet; @name; end
来源：http://dali.sysykeji.top/Article/details/gtdjpahkex.html

C#:   public string Greet() => Name;
来源：http://dali.ivvv.top/Article/details/gtufaltfpk.html

[G05] 继承
来源：http://dali.zhongyouzk.top/Article/details/gtjgemnefg.html

Py:   class Admin(User): pass
来源：http://dali.xylfe.cn/Article/details/gtprpfbeio.html

PHP:  class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gtvaeklort.html

JS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtfjrhuebs.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gttakxzbza.html

Java: class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtirmmnskg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gtrkjxgxkv.html

Ruby: class Admin < User; end
来源：http://dali.haohaochexian.top/Article/details/gtyfnmqehb.html

C#:   class Admin : User {}
来源：http://dali.jinqigufen.top/Article/details/gtohzyuxoh.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gtsyjuphud.html

Py:   def greet(self): return "admin"
来源：http://dali.gzhubu.top/Article/details/gtzfvoduhe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtssbfhtse.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtupsumiuh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtfrqqzbll.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtbozrrjcx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenzaomai.com/Article/details/gtwzxvcbri.html

Ruby: def greet; "admin"; end
来源：http://dali.yanxiufei.cn/Article/details/gthwswycik.html

C#:   public override string Greet() => "admin";
来源：http://dali.shuidangran.top/Article/details/gtfyzuhrcf.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gtuofijzbc.html

Py:   super().greet()
来源：http://dali.cashguo.top/Article/details/gtnjwdxsby.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gtskevhfiq.html

JS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtqslotnhr.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gthibirkyz.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gtxvhghqiq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258888.top/Article/details/gtfalztonl.html

Ruby: super
来源：http://dali.yongpay.top/Article/details/gtqhgdsnnf.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssawoxzg.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gtoiwyfymm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gtrkujaoxf.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gtzlggzwgv.html

JS:   static f() {}
来源：http://dali.ehwqpu.com/Article/details/gtaxrdghwd.html

TS:   static f(): void {}
来源：http://dali.yj202588.top/Article/details/gtvlxengdx.html

Java: static void f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtfkssfgft.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.birdmap.top/Article/details/gtzrtofoud.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gtjglvjtfp.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gtciwnhhgt.html

[G09] 接口 / 抽象类
来源：http://dali.ybcxt.top/Article/details/gtjqavipeu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cucudq.cn/Article/details/gtdtdbophi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigfzy.top/Article/details/gtxzhqrwhu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gtgnxesmkq.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gtrfnnwanc.html

Java: interface Shape { double area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtuthgxmoi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhongyouzk.top/Article/details/gtxirtfphl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhiwuduotai.top/Article/details/gthofqpmte.html

C#:   interface IShape { double Area(); }
来源：http://dali.meibo888.top/Article/details/gtzrdsclaw.html

[G10] 访问控制
来源：http://dali.nanxinkj.top/Article/details/gtzxpperxr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zdqjudy.top/Article/details/gtbygjbwsw.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtjxnzdezd.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gtdnjosoln.html

TS:   public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtgxbkdwvm.html

Java: public / protected / private / 默认包级
来源：http://dali.shzxlz.cn/Article/details/gtxtudqdzb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hfpthk.cn/Article/details/gtichtgzvk.html

Ruby: public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtvsnyjmox.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gtlxkgpkeu.html

[G11] getter / setter
来源：http://dali.yj20258888.top/Article/details/gtrqvxtpjr.html

Py:   @property 与 @x.setter
来源：http://dali.yueranfly.top/Article/details/gtcqvbyeom.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtwpyiukps.html

JS:   get name() { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlfzuqaik.html

TS:   get name(): string { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtarhcrjkh.html

Java: public String getName() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtbwdivxkz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtnkwwqwne.html

Ruby: attr_accessor :name
来源：http://dali.bjfxy.top/Article/details/gtxmdfudqe.html

C#:   public string Name { get; set; }
来源：http://dali.havefunace.top/Article/details/gtnlagovlm.html

[G12] 对象转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtjfukvdwv.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtabtsghsi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtxaswwjky.html

JS:   toString() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtpevdazxr.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtgjaqfoct.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtnysrzccp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtpgqknmap.html

Ruby: def to_s; @name; end
来源：http://dali.havefunace.top/Article/details/gtxvdaggeu.html

C#:   public override string ToString() => Name;
来源：http://dali.hammf.cn/Article/details/gtikseiezx.html

[G13] 判断对象类型
来源：http://dali.daria6918.cn/Article/details/gtijtkxrpr.html

Py:   isinstance(u, User)
来源：http://dali.guannengcc.top/Article/details/gtdoclyzql.html

PHP:  $u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtwrfopiyo.html

JS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtpgbavtbs.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtcyrtpxhy.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtpweoxbsq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yvedp.cn/Article/details/gtrjnktsip.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gtpkaqrbmh.html

C#:   u is User
来源：http://dali.iojbl.cn/Article/details/gtgvpawnja.html

[G14] 数据类 / record
来源：http://dali.xylfe.cn/Article/details/gtenswirxm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gtgaccclvy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shzxlz.cn/Article/details/gtydrqehka.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gtuxfooijd.html

TS:   type User = { name: string; age: number };
来源：http://dali.birdmap.top/Article/details/gtocjcjltn.html

Java: record User(String name, int age) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gturakpebj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gtpxtlwwpn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmedccebn.html

C#:   record User(string Name, int Age);
来源：http://dali.chenzaomai.com/Article/details/gtlpcnuufu.html

[G15] 枚举
来源：http://dali.cqqwz.cn/Article/details/gtyrcehqtx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gtchobrbks.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nwbrower.top/Article/details/gtvvkhgdot.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ppjwa.cn/Article/details/gtwincrapg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtqhzkebnk.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangdashe.top/Article/details/gtlxfpbheg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.0kj1m.cn/Article/details/gtvmrufmlb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hammf.cn/Article/details/gtpmnkevfp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gtfonzgxxt.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgfzy.top/Article/details/gtglhnpcqw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfujxoly.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gtxtkajphe.html

JS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtdpvbxori.html

TS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gtmlnotokx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gttsjupgas.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenlongwang.top/Article/details/gtyagfpbef.html

Ruby: obj.instance_variables
来源：http://dali.xuanzx.com/Article/details/gtsqesabpr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanhzeweg.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtwikswdxs.html

H. 异常与错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gtvyswpngs.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gttzorktax.html

[H01] try / catch 基础
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpekunsy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhengqikj.top/Article/details/gtfjpjhyem.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gtpozcgyff.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtsqmdfuts.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtnahhblec.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuanzhike.top/Article/details/gtiepbjbsq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ybcxt.top/Article/details/gtbohotjqe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuanzx.com/Article/details/gtjodoocuw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tianlin.xyz/Article/details/gtadabghuy.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gtcrlcitfm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxmevgyc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtoxwqqjur.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtbwceexsm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gttxacrkcu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtzqyjkgmm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gzhubu.top/Article/details/gtgaftssuq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xinyue.icu/Article/details/gtpvfrcbfq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtqivkegol.html

[H03] 主动抛出异常
来源：http://dali.guowangkeji.top/Article/details/gtpxyeltsi.html

Py:   raise ValueError("错误信息")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqlbngcw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtgcnbyklr.html

JS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtksywuhvm.html

TS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtfpbxscsp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtdnqatgxd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gtwqjblonk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.birdmap.top/Article/details/gtlhtaftpc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gthzlovcsg.html

[H04] 自定义异常类型
来源：http://dali.sufxvd.cn/Article/details/gtyxyhyirz.html

Py:   class MyError(Exception): pass
来源：http://dali.quarkkingdee.top/Article/details/gtfypdlkek.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtrrupjgmd.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtiiwuvnbo.html

TS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gtbtpvbfer.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gtxlunklov.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guowangkeji.top/Article/details/gttraeaola.html

Ruby: class MyError < StandardError; end
来源：http://dali.dianchejie.cn/Article/details/gtuutiwbqc.html

C#:   class MyException : Exception {}
来源：http://dali.jiagoushi.top/Article/details/gthyyitgzq.html

[H05] 捕获特定类型
来源：http://dali.sysykeji.top/Article/details/gtdbfuwori.html

Py:   except ValueError as e:
来源：http://dali.gotoacloud.top/Article/details/gtgplamytt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gthargbbke.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtlshxvzpw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtvridblwk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenzaomai.com/Article/details/gtwpmfgfto.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gttoefxogh.html

Ruby: rescue ArgumentError => e
来源：http://dali.kuanghao11.cn/Article/details/gtlpveglkv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gtcfkuxqua.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dianchejie.cn/Article/details/gtuvfmybjh.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gtccujuavv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tanke756.top/Article/details/gtzqcodatj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtujpgdmkx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtjzihukxd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabuipxuy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfxyabjx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sweek.top/Article/details/gtmxuftimd.html

C#:   obj?.A?.B ?? default
来源：http://dali.tianlin.xyz/Article/details/gtjuipinxm.html

[H07] 断言
来源：http://dali.zhiwuduotai.top/Article/details/gtbhvgnqfn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gtjqvmtkuh.html

PHP:  assert($x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtzgsborst.html

JS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtbaxbmsfx.html

TS:   console.assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtpzmisdnz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hongshengwenyu.top/Article/details/gthcwtnoxl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hfpthk.cn/Article/details/gtjqgxmqhq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.iojbl.cn/Article/details/gtwrelmnvx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtbpbwmuav.html

[H08] 获取错误信息与堆栈
来源：http://dali.hysaishi.cn/Article/details/gtczvudcvn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jiagoushi.top/Article/details/gtlbhwcceq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gtbscbfymx.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gtzxqfmtpa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ppjwa.cn/Article/details/gtvdfylxxb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigufen.top/Article/details/gtmhuuygtq.html

Go:   err.Error()
来源：http://dali.jyoumei.cn/Article/details/gtskjwfoao.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuxming.cn/Article/details/gtsqkjzncb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jiagoushi.top/Article/details/gtoiljsgtl.html

[H09] 带错误码的异常
来源：http://dali.daria6918.cn/Article/details/gtbcgmuoiy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.tianlin.xyz/Article/details/gtzccpziqv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuetiantiany.cn/Article/details/gtepotqity.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.bjfxy.top/Article/details/gtwvuhbeda.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.316326.xyz/Article/details/gtimyechqn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.snrcjt.cn/Article/details/gthmkisbbw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gtxbrxjdhg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daria6918.cn/Article/details/gtnxjbtxsp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuxming.cn/Article/details/gtkcjtlnfg.html

[H10] 资源自动释放
来源：http://dali.ydzc1.top/Article/details/gtjujyxdmm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ybcxt.top/Article/details/gtergycqof.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gtqpxculrz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtxwjkmbph.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gtwsmpfsfl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gtfwqilhwe.html

Go:   defer f.Close()
来源：http://dali.jqgfzy.top/Article/details/gtiqqpqqxa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhongyouzk.top/Article/details/gtarmygdnd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtocwefate.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtnsxiytru.html

I. 正则表达式
来源：http://dali.yonumen.top/Article/details/gtltegjqnt.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtavlhxitn.html

[I01] 判断是否匹配
来源：http://dali.jyoumei.cn/Article/details/gtcdgquzzi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtimjkpkin.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtykpwxjgq.html

JS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gtvmijoejn.html

TS:   /\d+/.test(s)
来源：http://dali.iojbl.cn/Article/details/gtvybigndh.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cucudq.cn/Article/details/gtfzvilxju.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkilfgfvm.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtnkghadbn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nwbrower.top/Article/details/gtutrwbccr.html

[I02] 提取所有匹配
来源：http://dali.sweek.top/Article/details/gtpyhianex.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gthdmpstvv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.vqdsnc.cn/Article/details/gtazgedttr.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cqqwz.cn/Article/details/gtxqrovawy.html

TS:   s.match(/\d+/g)
来源：http://dali.gotoacloud.top/Article/details/gtwdktdlvj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.meibo888.top/Article/details/gtjmuqjioq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtuetbmkum.html

Ruby: s.scan(/\d+/)
来源：http://dali.cdnleiting.top/Article/details/gtpddqaboc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtwczqezec.html

[I03] 提取捕获分组
来源：http://dali.vqdsnc.cn/Article/details/gtolqxadgh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.andypj.xyz/Article/details/gttcqswaew.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hammf.cn/Article/details/gtbmpbkhds.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daria6918.cn/Article/details/gtqevstmxk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnqzz.top/Article/details/gtffwfmrpb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.aibaodan.cn/Article/details/gtbxngbqgb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xziqi.cn/Article/details/gtkcztzbhv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fzhhl.top/Article/details/gtwmxapelw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.sxryk.cn/Article/details/gtsvxhwzuj.html

[I04] 正则替换
来源：http://dali.jqgfzy.top/Article/details/gtsueexwnp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guowangkeji.top/Article/details/gtsydrumvd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hfpthk.cn/Article/details/gtbzkjsoeq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hammf.cn/Article/details/gtxnfnciha.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.wangdashe.top/Article/details/gtnmxmziiv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gtkbjzioxq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zdqjudy.top/Article/details/gtksbhzaid.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtlutwcbpd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gthedzqwhl.html

[I05] 按正则拆分
来源：http://dali.tanke756.top/Article/details/gtwbqfohte.html


<!-- 参考信息 -->