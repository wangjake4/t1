代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dianchejie.cn/Article/details/gt2zjvbhzmz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2tbpxbzsk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gzhubu.top/Article/details/gt2qpcxelqz.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gt2ntyabagp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxupjvjz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gt2tywdxcwc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ehwqpu.com/Article/details/gt2xspkozuq.html

TS:   // 同上
来源：http://dali.0kj1m.cn/Article/details/gt2crlqejsl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cashguo.top/Article/details/gt2oeaiomrj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hongshengwenyu.top/Article/details/gt2wdwdmqos.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenlongwang.top/Article/details/gt2ejzwyxmq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.feifeiyinyue.top/Article/details/gt2mfrkzitp.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kqahfkga.html

G. 面向对象
来源：http://dali.tanke756.top/Article/details/gt2ifiwoqva.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2hbmufxqi.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gt2uuzlaioy.html

Py:   class User: pass
来源：http://dali.yuanzhike.top/Article/details/gt2hkzjpgar.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gt2cjfmmgzd.html

JS:   class User {}
来源：http://dali.yueranfly.top/Article/details/gt2ndnbukhe.html

TS:   class User { name: string = ""; }
来源：http://dali.snrcjt.cn/Article/details/gt2ibcdmdro.html

Java: class User {}
来源：http://dali.yueranfly.top/Article/details/gt2qbuxjxyk.html

Go:   type User struct { Name string }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dmdbbdaf.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gt2bmfedbrn.html

C#:   class User {}
来源：http://dali.zycfv.cn/Article/details/gt2idewtlhb.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2glnztimh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daria6918.cn/Article/details/gt2xotuglky.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2zvtquiis.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pdweyoit.html

TS:   constructor(public name: string) {}
来源：http://dali.iojbl.cn/Article/details/gt2tilqzvqn.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gt2oqrmtdmq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tanke756.top/Article/details/gt2wewphwlq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xinyue.icu/Article/details/gt2ktidaela.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2tdrmpetz.html

[G03] 实例属性
来源：http://dali.yongpay.top/Article/details/gt2fidgjllk.html

Py:   self.name = "x"
来源：http://dali.hnqzz.top/Article/details/gt2ftkbwido.html

PHP:  public string $name = "x";
来源：http://dali.nwbrower.top/Article/details/gt2uikpceqi.html

JS:   this.name = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2chbcaeyt.html

TS:   name: string = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2rlmbeozu.html

Java: private String name;
来源：http://dali.jinqigufen.top/Article/details/gt2kyfdicjx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daria6918.cn/Article/details/gt2wgchogdc.html

Ruby: @name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gt2szyggexd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gt2pgcbrbxg.html

[G04] 定义方法
来源：http://dali.daxiang520.top/Article/details/gt2ymaqunuu.html

Py:   def greet(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gt2iislrrmq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gt2nszfsrmb.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2djmmbhbn.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2zjfjztzn.html

Java: String greet() { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2sosqbfto.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gt2lmjsxpxe.html

Ruby: def greet; @name; end
来源：http://dali.haohaochexian.top/Article/details/gt2gwsnhbni.html

C#:   public string Greet() => Name;
来源：http://dali.yuanzhike.top/Article/details/gt2bpgnziou.html

[G05] 继承
来源：http://dali.hnxiangtu.top/Article/details/gt2oycjjqak.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gt2grtqpuwq.html

PHP:  class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtfytqcj.html

JS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oglyngzx.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2xmattnza.html

Java: class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2xdtewbzw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gt2rljbdfek.html

Ruby: class Admin < User; end
来源：http://dali.xinyue.icu/Article/details/gt2phoibpjg.html

C#:   class Admin : User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2vxtlmwuq.html

[G06] 重写方法
来源：http://dali.nanxinkj.top/Article/details/gt2lxfajhxu.html

Py:   def greet(self): return "admin"
来源：http://dali.zhiwuduotai.top/Article/details/gt2jqalrqxn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2dqjwuhxh.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gt2qmefyyta.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2ritcoarz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2kzjhkwqg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj202588.top/Article/details/gt2macdaegv.html

Ruby: def greet; "admin"; end
来源：http://dali.c1oappe.top/Article/details/gt2hbimhnve.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gt2slnmdldx.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gt2krcxvtpc.html

Py:   super().greet()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ratydfyz.html

PHP:  parent::greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2ewfzalrn.html

JS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2flbjvcnq.html

TS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gt2oghgccwo.html

Java: super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2xahkswls.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daxiang520.top/Article/details/gt2qragwfcz.html

Ruby: super
来源：http://dali.fengsongda.top/Article/details/gt2zhhqoldr.html

C#:   base.Greet();
来源：http://dali.sxryk.cn/Article/details/gt2gbzafhnl.html

[G08] 静态方法与属性
来源：http://dali.xylfe.cn/Article/details/gt2gsukpqqq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenjidiqi.icu/Article/details/gt2hynmkmha.html

PHP:  public static function f() {}
来源：http://dali.shuidangran.top/Article/details/gt2ygajrpdi.html

JS:   static f() {}
来源：http://dali.zycfv.cn/Article/details/gt2geyvlqge.html

TS:   static f(): void {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2vsafnqup.html

Java: static void f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2arteniya.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cheryme.top/Article/details/gt2wpvhtmwp.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gt2wlewyhga.html

C#:   public static void F() {}
来源：http://dali.redwolf501.top/Article/details/gt2kusntcna.html

[G09] 接口 / 抽象类
来源：http://dali.svipenyu.cn/Article/details/gt2ilvjnzlo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.bjfxy.top/Article/details/gt2lxxstiiq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.quarkkingdee.top/Article/details/gt2iiievqpt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zycfv.cn/Article/details/gt2gekzygck.html

TS:   interface Shape { area(): number; }
来源：http://dali.hfpthk.cn/Article/details/gt2ujyrrvhp.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258888.top/Article/details/gt2axnvcqet.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gt2fjvrglzs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhengqikj.top/Article/details/gt2epuktwro.html

C#:   interface IShape { double Area(); }
来源：http://dali.yangfankeji.com/Article/details/gt2vaoxxrkj.html

[G10] 访问控制
来源：http://dali.gaohongyu789.top/Article/details/gt2szdobvaa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gt2avfglyec.html

PHP:  public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gt2xxmhwkwe.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gt2vdgexmgj.html

TS:   public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vzrvhagq.html

Java: public / protected / private / 默认包级
来源：http://dali.xylfe.cn/Article/details/gt2mwenyexu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.bjfxy.top/Article/details/gt2thelioup.html

Ruby: public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2qsolqsgv.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gt2osjqnkkg.html

[G11] getter / setter
来源：http://dali.sweek.top/Article/details/gt2vvynprft.html

Py:   @property 与 @x.setter
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdhqpbsi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gt2vrykomoq.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mogcixiq.html

TS:   get name(): string { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gt2ctwcpevg.html

Java: public String getName() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hpeomjaz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gt2uoeftunq.html

Ruby: attr_accessor :name
来源：http://dali.jqgufenzy.top/Article/details/gt2xfzkhojq.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gt2viaicnlp.html

[G12] 对象转字符串
来源：http://dali.cdnleiting.top/Article/details/gt2riktutkc.html

Py:   def __str__(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gt2txywardd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2rzcxrvfw.html

JS:   toString() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gt2qtjzawpg.html

TS:   toString(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gt2hknikyld.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2zlndohjv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gt2gnqrbztt.html

Ruby: def to_s; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2dfnisaxk.html

C#:   public override string ToString() => Name;
来源：http://dali.fzhhl.top/Article/details/gt2cuegdewm.html

[G13] 判断对象类型
来源：http://dali.ydzc1.top/Article/details/gt2bgllwjes.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gt2yieqorqt.html

PHP:  $u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2mipvirtg.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2zrvobcsl.html

TS:   u instanceof User
来源：http://dali.aizwys.cn/Article/details/gt2xoganzco.html

Java: u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oonprwro.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gt2sdgwlapx.html

Ruby: u.is_a?(User)
来源：http://dali.vqdsnc.cn/Article/details/gt2adcxpmeb.html

C#:   u is User
来源：http://dali.ydzc1.top/Article/details/gt2azjwscax.html

[G14] 数据类 / record
来源：http://dali.xylfe.cn/Article/details/gt2hqnwpibd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gt2zckahxqa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cheryme.top/Article/details/gt2rkojualh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cdnleiting.top/Article/details/gt2osnrqpdr.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tfygbloz.html

Java: record User(String name, int age) {}
来源：http://dali.zdqjudy.top/Article/details/gt2skysbclx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gogol.net.cn/Article/details/gt2zhdqfunp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dianchejie.cn/Article/details/gt2lwqkejvb.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigufen.top/Article/details/gt2jomxgjgm.html

[G15] 枚举
来源：http://dali.cucudq.cn/Article/details/gt2bbcrlamu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hammf.cn/Article/details/gt2rypyubyq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xziqi.cn/Article/details/gt2jdwqgiuk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgufenzy.top/Article/details/gt2undsnanl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gt2ynbjnwne.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangdashe.top/Article/details/gt2jlaywqbh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gt2zarjwxyh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258888.top/Article/details/gt2xwjsbwxh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2vfhjbzzx.html

[G16] 对象转数组 / 字典
来源：http://dali.ydzc1.top/Article/details/gt2muelplqk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hywenlv.cn/Article/details/gt2hhxnoxcd.html

PHP:  get_object_vars($obj);
来源：http://dali.zhixingplan.top/Article/details/gt2seqvrpvx.html

JS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2diomqwbt.html

TS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2lmqxpaov.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2agztkkeu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenzaomai.com/Article/details/gt2nlhyfrjg.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gt2ghdxblpf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gt2zvdsxzrs.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2dufaskjc.html

H. 异常与错误处理
来源：http://dali.xziqi.cn/Article/details/gt2izaivrrr.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2xqiqmsrr.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gt2tnpkcuhy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gzvjcyak.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gt2gicsirye.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gt2lmxudzus.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gt2wxkllgwj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gotoacloud.top/Article/details/gt2smnhgrzp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gt2ervizxpw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daxiang520.top/Article/details/gt2ynhawrlw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gt2rfojcbcw.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gt2mkpdheal.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gt2ullicqgs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2qageoerw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2lpsovzpp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2biqprxjk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2ilvtnhsn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.316326.xyz/Article/details/gt2mehpyrot.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.9152youxi.cn/Article/details/gt2hbxecuci.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2qtsepsyc.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oxhyasoi.html

Py:   raise ValueError("错误信息")
来源：http://dali.xziqi.cn/Article/details/gt2iskcjara.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2rphzkmzp.html

JS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdxvsrrn.html

TS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2mehuqolt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2vhrlzmao.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tian-w.cn/Article/details/gt2jmnrqmqq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.iojbl.cn/Article/details/gt2lwceelvf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2zxhkyxuv.html

[H04] 自定义异常类型
来源：http://dali.yj20258.top/Article/details/gt2dtisbiwe.html

Py:   class MyError(Exception): pass
来源：http://dali.chenlongwang.top/Article/details/gt2dkxasdgn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gt2nalmewpu.html

JS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gt2doynugdh.html

TS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gt2heddrxnn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gt2rjmmjhoi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gt2dsdsowlc.html

Ruby: class MyError < StandardError; end
来源：http://dali.xylfe.cn/Article/details/gt2kkgxduzl.html

C#:   class MyException : Exception {}
来源：http://dali.vqdsnc.cn/Article/details/gt2dlcbrmlp.html

[H05] 捕获特定类型
来源：http://dali.yongpay.top/Article/details/gt2auduenff.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gt2kgzewfjh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jiagoushi.top/Article/details/gt2cicfkhrc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gt2ahwbskbb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gt2kyimgxdl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gotoacloud.top/Article/details/gt2amffxmay.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gt2psmtauya.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gt2qxnyueyy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2mpxwkaca.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yueranfly.top/Article/details/gt2vvrbannm.html

Py:   value = d.get("k") or default
来源：http://dali.guannengcc.top/Article/details/gt2khffpolz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gt2nnhwawox.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gt2fsgzdkct.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gt2gcmxmfij.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258.top/Article/details/gt2eoxlvmuw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj202588.top/Article/details/gt2pifvakqc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2htdasobd.html

C#:   obj?.A?.B ?? default
来源：http://dali.mhx1999.top/Article/details/gt2cwrrvktq.html

[H07] 断言
来源：http://dali.ybcxt.top/Article/details/gt2zpzekdcr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yanxiufei.cn/Article/details/gt2qftshfve.html

PHP:  assert($x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2sawpriex.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2qsvzgxfd.html

TS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2ochipyzg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.9152youxi.cn/Article/details/gt2nydioptp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.0kj1m.cn/Article/details/gt2jlbujgfh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gzhubu.top/Article/details/gt2jpdhytaq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2rqlxufxq.html

[H08] 获取错误信息与堆栈
来源：http://dali.xylfe.cn/Article/details/gt2igqxezrj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigfzy.top/Article/details/gt2sdrlcgky.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hammf.cn/Article/details/gt2ndcvzzcc.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gt2uzwbfrvf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yangfankeji.com/Article/details/gt2njzsybjz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gt2rhsizqnw.html

Go:   err.Error()
来源：http://dali.zdqjudy.top/Article/details/gt2elqqvxke.html

Ruby: e.message;  e.backtrace
来源：http://dali.cashguo.top/Article/details/gt2jpyventb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhiwuduotai.top/Article/details/gt2oolhszfa.html

[H09] 带错误码的异常
来源：http://dali.yongpay.top/Article/details/gt2kviwhkiz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gotoacloud.top/Article/details/gt2smvhycte.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gt2puvmiogm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hfpthk.cn/Article/details/gt2txawmopg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xziqi.cn/Article/details/gt2xzfvqxff.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgufenzy.top/Article/details/gt2dlnnrhbr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yvedp.cn/Article/details/gt2juwizovb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wuihtuzr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.316326.xyz/Article/details/gt2zyoqvdzz.html

[H10] 资源自动释放
来源：http://dali.daxiang520.top/Article/details/gt2wzvgrxaw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cpengswo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daxiang520.top/Article/details/gt2xiocpjfk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gt2xernnzad.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gt2hnpljsmx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.svipenyu.cn/Article/details/gt2auqyvisk.html

Go:   defer f.Close()
来源：http://dali.316326.xyz/Article/details/gt2jyidufys.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ydzc1.top/Article/details/gt2sivwlyoh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2epzjystx.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2wozdqrnm.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gt2eozxqvmv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2txhczzvx.html

[I01] 判断是否匹配
来源：http://dali.daria6918.cn/Article/details/gt2oxaunqsj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ydzc1.top/Article/details/gt2afyuqafw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gt2drkhefns.html

JS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gt2euotuhfr.html

TS:   /\d+/.test(s)
来源：http://dali.yj202588.top/Article/details/gt2uzvxdrdv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gt2astchyra.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ehwqpu.com/Article/details/gt2fsxomwuu.html

Ruby: s.match?(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gt2dgwjmxfx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gogol.net.cn/Article/details/gt2fthukams.html

[I02] 提取所有匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2zebmgnrv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gt2fxpznegl.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2khazqvcq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yongpay.top/Article/details/gt2qwwumjet.html

TS:   s.match(/\d+/g)
来源：http://dali.gzhubu.top/Article/details/gt2aphzyssm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gt2pgaawupw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangdashe.top/Article/details/gt2nvjlvinm.html

Ruby: s.scan(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gt2kxhlndbn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangdashe.top/Article/details/gt2pcixalbq.html

[I03] 提取捕获分组
来源：http://dali.guannengcc.top/Article/details/gt2xwspdegx.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cheryme.top/Article/details/gt2fluqxqsx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cheryme.top/Article/details/gt2isnochfi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xziqi.cn/Article/details/gt2hokspkiu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.mhx1999.top/Article/details/gt2mxnvuyur.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nudrwrtd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhixingplan.top/Article/details/gt2nzeyecuo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gt2lwytpkzx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ehwqpu.com/Article/details/gt2cxptpowv.html

[I04] 正则替换
来源：http://dali.zhoulong.xyz/Article/details/gt2zrjpstdq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.tianlin.xyz/Article/details/gt2wmhqvrla.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.redwolf501.top/Article/details/gt2rashaqdm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gt2iukacfwx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hongshengwenyu.top/Article/details/gt2nydszask.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nfyoogof.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hywenlv.cn/Article/details/gt2ynsdwtfn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2begnraia.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gt2agmmwrqq.html

[I05] 按正则拆分
来源：http://dali.dianchejie.cn/Article/details/gt2kbfjbyny.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xszrqbaz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgfzy.top/Article/details/gt2khuhwnbi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gt2nvldimjj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gt2nrjujgux.html

Java: s.split("\\s*,\\s*")
来源：http://dali.havefunace.top/Article/details/gt2ciaptwrz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pgtvnceo.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zlahryjz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hywenlv.cn/Article/details/gt2vpuwaehm.html


<!-- 参考信息 -->