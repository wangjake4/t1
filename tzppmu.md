代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2jcslicdg.html

TS:   path.extname("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2jodgacui.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gotoacloud.top/Article/details/gt2qjlbjgeu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2fsdmfegd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2rcicolli.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2wljwkqnq.html

[F11] 复制与移动文件
来源：http://dali.aibaodan.cn/Article/details/gt2hmsbudmk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2vkvmhhcb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2zpggrlzb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2hgyagfwk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2hpzilfvl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jiagoushi.top/Article/details/gt2oviimdlb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuanzhike.top/Article/details/gt2qbuvcong.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2udbnqpvt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ehwqpu.com/Article/details/gt2rjfxbsaa.html

[F12] CSV 读写
来源：http://dali.shzxlz.cn/Article/details/gt2yxshvvme.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxinkj.top/Article/details/gt2ciajkqii.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daria6918.cn/Article/details/gt2ykvxkkyo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cqqwz.cn/Article/details/gt2krunltby.html

TS:   // 同上
来源：http://dali.cucudq.cn/Article/details/gt2wsdstyiv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yonumen.top/Article/details/gt2vyebaifo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnqzz.top/Article/details/gt2bbiobasa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.c1oappe.top/Article/details/gt2wxuhxefm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigufen.top/Article/details/gt2egfpkyys.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2kssnbaav.html

G. 面向对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ivznlbnh.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2zkfobjmx.html

[G01] 定义类
来源：http://dali.jlsjyb.cn/Article/details/gt2cmxhguuv.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gt2sjxkjilq.html

PHP:  class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2lsizgzim.html

JS:   class User {}
来源：http://dali.sysykeji.top/Article/details/gt2elcephex.html

TS:   class User { name: string = ""; }
来源：http://dali.snrcjt.cn/Article/details/gt2rasizsry.html

Java: class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cuntjdfz.html

Go:   type User struct { Name string }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zwklxidd.html

Ruby: class User; end
来源：http://dali.yuxming.cn/Article/details/gt2cxguojrp.html

C#:   class User {}
来源：http://dali.jianghu66.top/Article/details/gt2mludhyln.html

[G02] 构造函数
来源：http://dali.fengsongda.top/Article/details/gt2vmititci.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jqgfzy.top/Article/details/gt2pbrdgpcr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2xorueyho.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2fjiguuxb.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtdjgge.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gt2kwwrzxgj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxuanxn.top/Article/details/gt2wvjwtyeb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gt2evquahpa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gt2waaqwpub.html

[G03] 实例属性
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wlapnhoh.html

Py:   self.name = "x"
来源：http://dali.sysykeji.top/Article/details/gt2owhkuopw.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gt2eskjblrk.html

JS:   this.name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2ujririfl.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gzzgchcq.html

Java: private String name;
来源：http://dali.gogol.net.cn/Article/details/gt2bfpmqrwk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhiwuduotai.top/Article/details/gt2gzgnpbpo.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2udnydmta.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2dkbztusr.html

[G04] 定义方法
来源：http://dali.0kj1m.cn/Article/details/gt2snczzpyx.html

Py:   def greet(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gt2zclsogzf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2ycdtoyds.html

JS:   greet() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2limkwfvz.html

TS:   greet(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2oxxyyftc.html

Java: String greet() { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2xsgyviqv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gt2hzuxwgrp.html

Ruby: def greet; @name; end
来源：http://dali.mhx1999.top/Article/details/gt2isedbqts.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258888.top/Article/details/gt2vobhyfki.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gt2bpeuladn.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fmhyupag.html

PHP:  class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2nefwmbpj.html

JS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2tnsrvaaq.html

TS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2rmiaamog.html

Java: class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fzwkxsdx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nwbrower.top/Article/details/gt2jqrqzifo.html

Ruby: class Admin < User; end
来源：http://dali.yonumen.top/Article/details/gt2cfiessoa.html

C#:   class Admin : User {}
来源：http://dali.smart0.xyz/Article/details/gt2esofrega.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gt2gjxmmuzb.html

Py:   def greet(self): return "admin"
来源：http://dali.hysaishi.cn/Article/details/gt2arqdwaom.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfjbptn.html

JS:   greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gt2bfquresp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2xszuanxm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2iwpquego.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zycfv.cn/Article/details/gt2iblnpbeb.html

Ruby: def greet; "admin"; end
来源：http://dali.zhengqikj.top/Article/details/gt2xgzqwmtp.html

C#:   public override string Greet() => "admin";
来源：http://dali.cucudq.cn/Article/details/gt2qvdywpfa.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gt2cvkuilhz.html

Py:   super().greet()
来源：http://dali.zhengqikj.top/Article/details/gt2lqrnsbwl.html

PHP:  parent::greet();
来源：http://dali.haohaochexian.top/Article/details/gt2lnelalyd.html

JS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2phjbagai.html

TS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gt2tfomtedo.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gt2hugfgsgh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gt2wdhojjar.html

Ruby: super
来源：http://dali.hammf.cn/Article/details/gt2orexlwjr.html

C#:   base.Greet();
来源：http://dali.bjfxy.top/Article/details/gt2acdlwffc.html

[G08] 静态方法与属性
来源：http://dali.tianlin.xyz/Article/details/gt2wdvqgdra.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gt2qapfqkzl.html

PHP:  public static function f() {}
来源：http://dali.iojbl.cn/Article/details/gt2qbckfahf.html

JS:   static f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2vhupugoh.html

TS:   static f(): void {}
来源：http://dali.ybcxt.top/Article/details/gt2wwovxidd.html

Java: static void f() {}
来源：http://dali.tanke756.top/Article/details/gt2xseyvoen.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gt2qeesxniv.html

Ruby: def self.f; end
来源：http://dali.kuanghao11.cn/Article/details/gt2ikirwcyv.html

C#:   public static void F() {}
来源：http://dali.tianlin.xyz/Article/details/gt2kjtlwusn.html

[G09] 接口 / 抽象类
来源：http://dali.tanke756.top/Article/details/gt2ycjdmetc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gt2ekthmkux.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2roursawv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gt2wqegtdnh.html

TS:   interface Shape { area(): number; }
来源：http://dali.gotoacloud.top/Article/details/gt2lszokbaa.html

Java: interface Shape { double area(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2hnncbuep.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hvwwmwoh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bppbouxn.html

C#:   interface IShape { double Area(); }
来源：http://dali.bjfxy.top/Article/details/gt2iphmoutp.html

[G10] 访问控制
来源：http://dali.pycfn.com/Article/details/gt2segbknoi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gt2otwmtrwk.html

PHP:  public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gt2hgasozpm.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gt2mbzxfjll.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2adaovrcp.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gt2yvlzuavd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.c1oappe.top/Article/details/gt2etbokkok.html

Ruby: public / protected / private
来源：http://dali.yj20258.top/Article/details/gt2osymjnrl.html

C#:   public / protected / private / internal
来源：http://dali.ybcxt.top/Article/details/gt2ohrqhnxm.html

[G11] getter / setter
来源：http://dali.ivvv.top/Article/details/gt2qwbgxpoh.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigfzy.top/Article/details/gt2kcgvxrjo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gt2uwcfeycu.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gt2itlhhexu.html

TS:   get name(): string { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gt2ahvhxgrx.html

Java: public String getName() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2diqatzvd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2xvpffnyp.html

Ruby: attr_accessor :name
来源：http://dali.pycfn.com/Article/details/gt2fskoymlw.html

C#:   public string Name { get; set; }
来源：http://dali.yuanzhike.top/Article/details/gt2pudxogsh.html

[G12] 对象转字符串
来源：http://dali.9152youxi.cn/Article/details/gt2qsxdeafb.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gt2vagxdjze.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2ulnhmyjq.html

JS:   toString() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2vadoplod.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2fxowukry.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2ilcinuly.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gt2lmaundft.html

Ruby: def to_s; @name; end
来源：http://dali.haohaochexian.top/Article/details/gt2pgzmfrfa.html

C#:   public override string ToString() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ruswwuhz.html

[G13] 判断对象类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2qkduujko.html

Py:   isinstance(u, User)
来源：http://dali.jlsjyb.cn/Article/details/gt2uuzipzqv.html

PHP:  $u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2qmlkrmwc.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2tdyrzjhd.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2uhpuwjzy.html

Java: u instanceof User
来源：http://dali.daxiang520.top/Article/details/gt2tgubpwlt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhongyouzk.top/Article/details/gt2ctvfahmf.html

Ruby: u.is_a?(User)
来源：http://dali.shzxlz.cn/Article/details/gt2kmhndppk.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gt2noaeagwr.html

[G14] 数据类 / record
来源：http://dali.xylfe.cn/Article/details/gt2fnlvikey.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gt2jesfzvvv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cheryme.top/Article/details/gt2zhgjjkym.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gt2jylqdzqc.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2widmjeya.html

Java: record User(String name, int age) {}
来源：http://dali.redwolf501.top/Article/details/gt2qvlvxxfb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gt2ciqvlixw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shangyingyoupin.top/Article/details/gt2ozqygmqv.html

C#:   record User(string Name, int Age);
来源：http://dali.hfpthk.cn/Article/details/gt2hipejpkh.html

[G15] 枚举
来源：http://dali.iojbl.cn/Article/details/gt2ulmwilkp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aibaodan.cn/Article/details/gt2ademhbut.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuanzx.com/Article/details/gt2jwlwbwsn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yongpay.top/Article/details/gt2rvgiqjyw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2jpxetkjo.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gt2hhzikbjr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yonumen.top/Article/details/gt2pcrbqhll.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuxming.cn/Article/details/gt2vgxfddht.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2bzpxphcd.html

[G16] 对象转数组 / 字典
来源：http://dali.0kj1m.cn/Article/details/gt2ctvdyyjg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hammf.cn/Article/details/gt2mlpiktbv.html

PHP:  get_object_vars($obj);
来源：http://dali.hywenlv.cn/Article/details/gt2rvhibhsv.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2ulrjumlq.html

TS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2gtsldhvb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuanzhike.top/Article/details/gt2ootnmoin.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guowangkeji.top/Article/details/gt2aqrwtoxp.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gt2lnhsitir.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gt2wlufjpwn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nycpeefx.html

H. 异常与错误处理
来源：http://dali.iojbl.cn/Article/details/gt2hrxpqefy.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2mmiaxvev.html

[H01] try / catch 基础
来源：http://dali.tian-w.cn/Article/details/gt2negjjxrk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yongpay.top/Article/details/gt2bocvzlxh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jianghu66.top/Article/details/gt2chbaxdar.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gt2jcqorxsf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gt2ajifkcre.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dianchejie.cn/Article/details/gt2aaxotthe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.haohaochexian.top/Article/details/gt2lrkuxzjq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cashguo.top/Article/details/gt2gocxgzbp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sufxvd.cn/Article/details/gt2uduqkdzc.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gt2spqknste.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.vqdsnc.cn/Article/details/gt2tbnxzoeq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2ycueogdz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2eecqrtro.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2kjbmymqo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2uzzfqbbf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.mhx1999.top/Article/details/gt2ymnqupba.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hammf.cn/Article/details/gt2oihcjtap.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tlerrnlq.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2fyalwuve.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gt2gqvlasqx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2crsnmwiy.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2zvjotggr.html

TS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2xocyjkeg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2sgvxzqkr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxinkj.top/Article/details/gt2yyxsgllk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuanzx.com/Article/details/gt2hbivkhto.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oyokffqe.html

[H04] 自定义异常类型
来源：http://dali.ydzc1.top/Article/details/gt2nvcjhvvt.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gt2ayqxfgob.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gt2nzypvrrj.html

JS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gt2ygwpfcba.html

TS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gt2xrbrkyar.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gt2rvgzgenl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ivvv.top/Article/details/gt2brtvmjnn.html

Ruby: class MyError < StandardError; end
来源：http://dali.ehwqpu.com/Article/details/gt2qsjdmsqa.html

C#:   class MyException : Exception {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2myqzslne.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gt2hrzxfhzw.html

Py:   except ValueError as e:
来源：http://dali.wangshuangyany.cn/Article/details/gt2qogyboka.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gt2yoniwkdw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lgiebnzr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gt2famvgjkk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oxlqktyn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sxryk.cn/Article/details/gt2bxwrfqwb.html

Ruby: rescue ArgumentError => e
来源：http://dali.yanxiufei.cn/Article/details/gt2qywnwiqq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daria6918.cn/Article/details/gt2fjcnxbhd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gt2aiifropp.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gt2axcctsww.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gt2hwhokwlx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvespera.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gt2mpratpcn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigufen.top/Article/details/gt2wtucswhb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gt2ygeyxdiw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tianlin.xyz/Article/details/gt2oyvsnodl.html

C#:   obj?.A?.B ?? default
来源：http://dali.fzhhl.top/Article/details/gt2qjontvll.html

[H07] 断言
来源：http://dali.hywenlv.cn/Article/details/gt2lhvogbfn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj202588.top/Article/details/gt2bkuoqeja.html

PHP:  assert($x > 0);
来源：http://dali.yuxming.cn/Article/details/gt2zlibzzpu.html

JS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2iddeswoc.html

TS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gt2lrlxsssp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hysaishi.cn/Article/details/gt2pwqpjjnz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.iojbl.cn/Article/details/gt2gyqoflue.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gt2berijzrq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2cbigkfyy.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangdashe.top/Article/details/gt2btmwiefo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2glgcihiu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gotoacloud.top/Article/details/gt2kzuixqhe.html

JS:   e.message;  e.stack
来源：http://dali.mhx1999.top/Article/details/gt2qtejqqgs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gt2mnluoqin.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pycfn.com/Article/details/gt2dcayxjxv.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gt2kswcehgo.html

Ruby: e.message;  e.backtrace
来源：http://dali.snrcjt.cn/Article/details/gt2kfdvrshc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuxming.cn/Article/details/gt2ebgvlube.html

[H09] 带错误码的异常
来源：http://dali.yangfankeji.com/Article/details/gt2ujsxwoii.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yongpay.top/Article/details/gt2jqqnmsay.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.haohaochexian.top/Article/details/gt2fapbavam.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gaohongyu789.top/Article/details/gt2updsxcgp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tanke756.top/Article/details/gt2bbscabog.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhongyouzk.top/Article/details/gt2nvipcgyv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuanzhike.top/Article/details/gt2isqavmij.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.quarkkingdee.top/Article/details/gt2crtoxnfj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj20258.top/Article/details/gt2eoofyikh.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gt2bfolwbya.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgufenzy.top/Article/details/gt2xqwposjg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sweek.top/Article/details/gt2xodhmahk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gt2xaorghad.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenjidiqi.icu/Article/details/gt2wehehmsx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnxiangtu.top/Article/details/gt2tcjpjogk.html

Go:   defer f.Close()
来源：http://dali.yj202588.top/Article/details/gt2gfyxrysq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258888.top/Article/details/gt2dzkxgahz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2nndwapap.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xijdwpfa.html

I. 正则表达式
来源：http://dali.ppjwa.cn/Article/details/gt2dvutibcv.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2vjfhaier.html

[I01] 判断是否匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2lafquggw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgufenzy.top/Article/details/gt2kgoiyzfy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2wukapwag.html

JS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2bnzdafrr.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2smwsltez.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gt2bxyzgvek.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sxryk.cn/Article/details/gt2ivhgozbh.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cejsjlmg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuanzx.com/Article/details/gt2uckosdpp.html

[I02] 提取所有匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2wdsjasuh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gt2sfwuckzf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhoulong.xyz/Article/details/gt2ecixkeod.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yonumen.top/Article/details/gt2rjfighcf.html

TS:   s.match(/\d+/g)
来源：http://dali.wangshuangyany.cn/Article/details/gt2buoutpdm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ppjwa.cn/Article/details/gt2yztnjytk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2molsclos.html

Ruby: s.scan(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gt2cxcnzbfd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gzhubu.top/Article/details/gt2owdnvxsr.html

[I03] 提取捕获分组
来源：http://dali.hysaishi.cn/Article/details/gt2hbnmiatt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gt2tohndmqa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hongshengwenyu.top/Article/details/gt2hmwpylyd.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.dianchejie.cn/Article/details/gt2zbxgawdb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cdnleiting.top/Article/details/gt2lxawzvep.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jianghu66.top/Article/details/gt2fdbjwvyx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjiedjvf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgfzy.top/Article/details/gt2lbgjacax.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ppjwa.cn/Article/details/gt2fpqtvcgb.html

[I04] 正则替换
来源：http://dali.sysykeji.top/Article/details/gt2cqqbvqwv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnqzz.top/Article/details/gt2vsclpmld.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxgrvzgl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tian-w.cn/Article/details/gt2plvmhtyx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gt2asoujluw.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.aibaodan.cn/Article/details/gt2aihgejoh.html


<!-- 参考信息 -->