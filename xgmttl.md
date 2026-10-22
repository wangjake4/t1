代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.dashuyun.cn/Article/details/gt2lwegcsvc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.andypj.xyz/Article/details/gt2rrvbpvop.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2jhyzvnqn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2acrffwnt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2lbfmnkut.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2vkotsbsu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tnheupkq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2mlsydifk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2vhmdffwm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2ukxdyhpw.html

[F11] 复制与移动文件
来源：http://dali.hysaishi.cn/Article/details/gt2mcdilkle.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2rhmiwyhw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gt2hpgjfgae.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2liqnhxkn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2gjelwtdk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gt2idqqkiba.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2caudrnjm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gt2tnvmscog.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.0kj1m.cn/Article/details/gt2hkrzdpvv.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gt2eunohtnu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gt2wnzcqqop.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tanke756.top/Article/details/gt2gufnspzt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tanke756.top/Article/details/gt2wbdzekcp.html

TS:   // 同上
来源：http://dali.iojbl.cn/Article/details/gt2cnsgllgy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258888.top/Article/details/gt2larbjdoi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nwbrower.top/Article/details/gt2wdrtefkd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gotoacloud.top/Article/details/gt2apozgmlq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hongshengwenyu.top/Article/details/gt2blgbhpnc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2eiscianc.html

G. 面向对象
来源：http://dali.yj20258888.top/Article/details/gt2xsizkviv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2ndcgrwqd.html

[G01] 定义类
来源：http://dali.meibo888.top/Article/details/gt2sqrbquvd.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gt2odhclpks.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gt2wgexipis.html

JS:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gt2heyjjjfr.html

TS:   class User { name: string = ""; }
来源：http://dali.xuanzx.com/Article/details/gt2ixrkntgh.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2jqmytenj.html

Go:   type User struct { Name string }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uopgzmyf.html

Ruby: class User; end
来源：http://dali.chenlongwang.top/Article/details/gt2yayygisl.html

C#:   class User {}
来源：http://dali.ybcxt.top/Article/details/gt2hfbbpqaa.html

[G02] 构造函数
来源：http://dali.svipenyu.cn/Article/details/gt2krmfpssy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yangfankeji.com/Article/details/gt2xgurokar.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gzhubu.top/Article/details/gt2eobpipwu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gt2okzrpgyd.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gt2mwhevkzg.html

Java: User(String name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gt2aurjvjbk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aibaodan.cn/Article/details/gt2ngjigveq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.316326.xyz/Article/details/gt2vqtfyres.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnqzz.top/Article/details/gt2xcuqaxxn.html

[G03] 实例属性
来源：http://dali.daxiang520.top/Article/details/gt2mekiwjnx.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gt2eogbfcqj.html

PHP:  public string $name = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2rahycwfc.html

JS:   this.name = "x";
来源：http://dali.ybcxt.top/Article/details/gt2hnxiuifu.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ufgejrkt.html

Java: private String name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2hwfklmqr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gt2txkwiidd.html

Ruby: @name = "x"
来源：http://dali.gzhubu.top/Article/details/gt2dagamayu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2xrhkqbma.html

[G04] 定义方法
来源：http://dali.jiagoushi.top/Article/details/gt2sykiyldh.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gt2oedzgyln.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gt2siduwypz.html

JS:   greet() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2iaynjjyo.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2vomdiezw.html

Java: String greet() { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2wazbdiaz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gt2dalfebbw.html

Ruby: def greet; @name; end
来源：http://dali.yuxming.cn/Article/details/gt2kdgaljyt.html

C#:   public string Greet() => Name;
来源：http://dali.tian-w.cn/Article/details/gt2yzxbmrha.html

[G05] 继承
来源：http://dali.tianlin.xyz/Article/details/gt2tafvknmo.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gt2ffylferu.html

PHP:  class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2icetgdto.html

JS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gt2peidstuq.html

TS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gt2hrvkvmdy.html

Java: class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2pvgqqepz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.0kj1m.cn/Article/details/gt2yxdxcfvy.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gt2pkmqgwoa.html

C#:   class Admin : User {}
来源：http://dali.guannengcc.top/Article/details/gt2lraqndnd.html

[G06] 重写方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qerhxcrg.html

Py:   def greet(self): return "admin"
来源：http://dali.iojbl.cn/Article/details/gt2jdhfejek.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2cadywekg.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2ypyqklap.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qcodatml.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gt2llqteyft.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gt2huinucel.html

Ruby: def greet; "admin"; end
来源：http://dali.chenzaomai.com/Article/details/gt2zzcyshof.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenjidiqi.icu/Article/details/gt2gpbhgnfg.html

[G07] 调用父类方法
来源：http://dali.cqqwz.cn/Article/details/gt2suxkrxzq.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gt2ddisnsyi.html

PHP:  parent::greet();
来源：http://dali.wangdashe.top/Article/details/gt2zqpxinbg.html

JS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2qtbopxcp.html

TS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2anntqoxa.html

Java: super.greet();
来源：http://dali.hammf.cn/Article/details/gt2wosbtjus.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gzhubu.top/Article/details/gt2ntuudqml.html

Ruby: super
来源：http://dali.xinyue.icu/Article/details/gt2jwhcxccu.html

C#:   base.Greet();
来源：http://dali.cashguo.top/Article/details/gt2cptvuvon.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gt2bzaikudp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangshuangyany.cn/Article/details/gt2ripxbcss.html

PHP:  public static function f() {}
来源：http://dali.0kj1m.cn/Article/details/gt2xijbjyps.html

JS:   static f() {}
来源：http://dali.yj20258888.top/Article/details/gt2qorldkeu.html

TS:   static f(): void {}
来源：http://dali.haohaochexian.top/Article/details/gt2numpxrmb.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gt2vhgvgfex.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gt2pewhnuha.html

Ruby: def self.f; end
来源：http://dali.0kj1m.cn/Article/details/gt2xgkolpxr.html

C#:   public static void F() {}
来源：http://dali.sxryk.cn/Article/details/gt2qavdbpvi.html

[G09] 接口 / 抽象类
来源：http://dali.fengsongda.top/Article/details/gt2fxktzeqy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.bjfxy.top/Article/details/gt2dabhkxha.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gt2cyutfvwy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gt2xkfncbva.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuanzx.com/Article/details/gt2fpesteyt.html

Java: interface Shape { double area(); }
来源：http://dali.jqgfzy.top/Article/details/gt2qniiyrjo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.vqdsnc.cn/Article/details/gt2atknafnl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nwbrower.top/Article/details/gt2cecuwfmy.html

C#:   interface IShape { double Area(); }
来源：http://dali.aizwys.cn/Article/details/gt2esswmuqr.html

[G10] 访问控制
来源：http://dali.redwolf501.top/Article/details/gt2mzmfhqwv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nwbrower.top/Article/details/gt2auxiuuax.html

PHP:  public / protected / private
来源：http://dali.daxiang520.top/Article/details/gt2vscmuxhj.html

JS:   #private 字段；其余公开
来源：http://dali.yuxming.cn/Article/details/gt2dyyrpbhz.html

TS:   public / protected / private
来源：http://dali.xziqi.cn/Article/details/gt2huxmgeav.html

Java: public / protected / private / 默认包级
来源：http://dali.sufxvd.cn/Article/details/gt2nrcbqvuk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ppjwa.cn/Article/details/gt2sjtkoraz.html

Ruby: public / protected / private
来源：http://dali.cashguo.top/Article/details/gt2lkxzgwpz.html

C#:   public / protected / private / internal
来源：http://dali.jlsjyb.cn/Article/details/gt2rfracwsf.html

[G11] getter / setter
来源：http://dali.ivvv.top/Article/details/gt2hciczobw.html

Py:   @property 与 @x.setter
来源：http://dali.zhiwuduotai.top/Article/details/gt2gattlyth.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2fhdkzbgm.html

JS:   get name() { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gt2dwpslauw.html

TS:   get name(): string { return this._name; }
来源：http://dali.tanke756.top/Article/details/gt2doeitdpo.html

Java: public String getName() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2xbkaiupm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gt2vmsxbufv.html

Ruby: attr_accessor :name
来源：http://dali.guowangkeji.top/Article/details/gt2mfngrgch.html

C#:   public string Name { get; set; }
来源：http://dali.cheryme.top/Article/details/gt2pgyzohqp.html

[G12] 对象转字符串
来源：http://dali.zhengqikj.top/Article/details/gt2uznihqxh.html

Py:   def __str__(self): return self.name
来源：http://dali.hammf.cn/Article/details/gt2nufsnixf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2kusgawsy.html

JS:   toString() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gt2ksrlbnpg.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zynbjtwy.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gt2gwdknrej.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2jwkuejlm.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gt2tlzfyyxx.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gt2njjaanzr.html

[G13] 判断对象类型
来源：http://dali.meibo888.top/Article/details/gt2ovwrsfif.html

Py:   isinstance(u, User)
来源：http://dali.0kj1m.cn/Article/details/gt2mkrsdxcw.html

PHP:  $u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gt2jsnhgjlb.html

JS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gt2pccxdgbs.html

TS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2nuhlysnb.html

Java: u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2mbsostno.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.guowangkeji.top/Article/details/gt2mjfmqqfk.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gt2pwzsgomx.html

C#:   u is User
来源：http://dali.quarkkingdee.top/Article/details/gt2sevoowwt.html

[G14] 数据类 / record
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wcgeumrp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shzxlz.cn/Article/details/gt2amwvldjt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.iojbl.cn/Article/details/gt2qzsapbao.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.316326.xyz/Article/details/gt2wgkrxyjc.html

TS:   type User = { name: string; age: number };
来源：http://dali.sweek.top/Article/details/gt2esegqgql.html

Java: record User(String name, int age) {}
来源：http://dali.fengsongda.top/Article/details/gt2dmnagitn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yanxiufei.cn/Article/details/gt2bfdximkp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgfzy.top/Article/details/gt2yfgfoahy.html

C#:   record User(string Name, int Age);
来源：http://dali.316326.xyz/Article/details/gt2fbftnbps.html

[G15] 枚举
来源：http://dali.ppjwa.cn/Article/details/gt2kgxexjmo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2twhdffiu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hfpthk.cn/Article/details/gt2zrwpznxa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.svipenyu.cn/Article/details/gt2denerzza.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gt2xrzyxkqw.html

Java: enum Color { RED, GREEN }
来源：http://dali.yanxiufei.cn/Article/details/gt2ykzyduvl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj202588.top/Article/details/gt2ujqdiwpe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shangyingyoupin.top/Article/details/gt2beuqxsgk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gt2xxdzqegk.html

[G16] 对象转数组 / 字典
来源：http://dali.wangdashe.top/Article/details/gt2dqniianh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxuanxn.top/Article/details/gt2srdubyjh.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gt2hyfspzde.html

JS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gt2pddyrgvf.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bngxenvb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hammf.cn/Article/details/gt2naiiydbl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shuidangran.top/Article/details/gt2bvbdsfuw.html

Ruby: obj.instance_variables
来源：http://dali.dianchejie.cn/Article/details/gt2hywyaqlb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mmewnewu.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2mvjotcwo.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gt2canpxnby.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2xcyqetnp.html

[H01] try / catch 基础
来源：http://dali.shangyingyoupin.top/Article/details/gt2xetqqazj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenzaomai.com/Article/details/gt2gigwyqpm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daria6918.cn/Article/details/gt2ybkxzrwd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gt2lqlpufzs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gt2iuxxwdil.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.andypj.xyz/Article/details/gt2auvptawd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gzhubu.top/Article/details/gt2yyrojdww.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dianchejie.cn/Article/details/gt2qgsefcuu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258888.top/Article/details/gt2obotnvom.html

[H02] finally / ensure 收尾
来源：http://dali.nwbrower.top/Article/details/gt2bxezzuyn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.svipenyu.cn/Article/details/gt2dsabsevi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2lupfxdxi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2ogqqlswi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2otlpkvxj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2svffrhfm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2scuxoaem.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hammf.cn/Article/details/gt2xmflasfr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gt2pitfpfjr.html

[H03] 主动抛出异常
来源：http://dali.ybcxt.top/Article/details/gt2mdpstbrn.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jyhiyhgb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2oacvlqtm.html

JS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2bonnejgr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2qijvxbnf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2fsegahlv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xpdyllfv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgfzy.top/Article/details/gt2ptftfxwg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2csexohcv.html

[H04] 自定义异常类型
来源：http://dali.c1oappe.top/Article/details/gt2bglnkhnk.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gt2rfeyduba.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2hvqqojzr.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gt2flxlnqoh.html

TS:   class MyError extends Error {}
来源：http://dali.yanxiufei.cn/Article/details/gt2wrglfgcc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2plzrpdlm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gt2wbykqsxe.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gt2lipasysn.html

C#:   class MyException : Exception {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2jpouofeb.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gt2ukckpwgh.html

Py:   except ValueError as e:
来源：http://dali.kuanghao11.cn/Article/details/gt2pwreikbi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gt2stvzeqbp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gt2yfzwmwxg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gt2kxoosrmt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2twysskco.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cqqwz.cn/Article/details/gt2oofjjzga.html

Ruby: rescue ArgumentError => e
来源：http://dali.hammf.cn/Article/details/gt2nfjqggty.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ybcxt.top/Article/details/gt2pnihlpby.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuetiantiany.cn/Article/details/gt2nbkmmsns.html

Py:   value = d.get("k") or default
来源：http://dali.yongpay.top/Article/details/gt2wtsfvquj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gt2ylyzagiy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gt2tuyccfjr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gt2rrxvgeas.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxuanxn.top/Article/details/gt2mkdesdxh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.redwolf501.top/Article/details/gt2lyszexri.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gt2yyajcybb.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gt2jfdyqhfr.html

[H07] 断言
来源：http://dali.ppjwa.cn/Article/details/gt2gruejsjj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.0kj1m.cn/Article/details/gt2aurrvxac.html

PHP:  assert($x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2ionaqgcq.html

JS:   console.assert(x > 0);
来源：http://dali.zdqjudy.top/Article/details/gt2iimbiuso.html

TS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2vvgnvung.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gt2fskvtmew.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangshuangyany.cn/Article/details/gt2ewnioznt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.birdmap.top/Article/details/gt2asjagipt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2gcemkzvt.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cmskclsr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhongyouzk.top/Article/details/gt2lrwhlbdn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hammf.cn/Article/details/gt2rhtohpzz.html

JS:   e.message;  e.stack
来源：http://dali.meibo888.top/Article/details/gt2uimxfsom.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.c1oappe.top/Article/details/gt2oblmtomi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.316326.xyz/Article/details/gt2cqenvadj.html

Go:   err.Error()
来源：http://dali.meibo888.top/Article/details/gt2eqdgmygd.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangshuangyany.cn/Article/details/gt2syotcaul.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ehwqpu.com/Article/details/gt2nsoxfbsc.html

[H09] 带错误码的异常
来源：http://dali.yj20258888.top/Article/details/gt2cucrhhai.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aizwys.cn/Article/details/gt2xbwlrmed.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenlongwang.top/Article/details/gt2hnxklddt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zdqjudy.top/Article/details/gt2bjedxhdz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.bjfxy.top/Article/details/gt2byjuxrpr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.aizwys.cn/Article/details/gt2lgkukgsv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gt2lqfyefhb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gaohongyu789.top/Article/details/gt2uizocptb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwidspll.html

[H10] 资源自动释放
来源：http://dali.hammf.cn/Article/details/gt2gdelxfnp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sweek.top/Article/details/gt2egqdccti.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tianlin.xyz/Article/details/gt2kddkjxsl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxonqyuo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gt2bqxiolpw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ehwqpu.com/Article/details/gt2qrmbzczf.html

Go:   defer f.Close()
来源：http://dali.hnqzz.top/Article/details/gt2unexihms.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dianchejie.cn/Article/details/gt2zkdqpznz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2zaamzjlo.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2eqysbcxo.html

I. 正则表达式
来源：http://dali.ivvv.top/Article/details/gt2ycwibwjd.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2dqfsmppk.html

[I01] 判断是否匹配
来源：http://dali.9152youxi.cn/Article/details/gt2kaclovqt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dlqedawu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cucudq.cn/Article/details/gt2fjzxguqs.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gt2zrekkgit.html

TS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gt2owtaesqn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cqqwz.cn/Article/details/gt2lhwyoonh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2htccdupk.html

Ruby: s.match?(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gt2mwizkrdy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yangfankeji.com/Article/details/gt2emgkzvag.html

[I02] 提取所有匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2xzdinmak.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xuchqqfx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuanzx.com/Article/details/gt2cxpnvchf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gt2ospahips.html

TS:   s.match(/\d+/g)
来源：http://dali.gaohongyu789.top/Article/details/gt2lslwtbxs.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2hijkahmf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj20258.top/Article/details/gt2fpgrgezy.html

Ruby: s.scan(/\d+/)
来源：http://dali.sxryk.cn/Article/details/gt2yxwdvlim.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2pwdoanrh.html

[I03] 提取捕获分组
来源：http://dali.zhongyouzk.top/Article/details/gt2xzaqbjvq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fzhhl.top/Article/details/gt2lvqpxnof.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hnxiangtu.top/Article/details/gt2pcfvrcmm.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgfzy.top/Article/details/gt2phvctcbk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gt2fqpqtekk.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gt2qdbrqbzt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sufxvd.cn/Article/details/gt2cepncsca.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tian-w.cn/Article/details/gt2hrwhfngk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.meibo888.top/Article/details/gt2xjzoxjrl.html

[I04] 正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2fcopdgln.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.9152youxi.cn/Article/details/gt2iileuarh.html


<!-- 参考信息 -->