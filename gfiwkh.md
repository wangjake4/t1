代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2mpmbbkzb.html

TS:   path.extname("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2mlmggyyz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pycfn.com/Article/details/gt2kzlqbuwm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2pmjzjeek.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2uarerkzf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2aubmxfwb.html

[F11] 复制与移动文件
来源：http://dali.gaohongyu789.top/Article/details/gt2ngauxrvk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2gfzloiju.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2vcolscgs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2vndaogcs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2zxutdqez.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuanzhike.top/Article/details/gt2tjpwjxad.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yanxiufei.cn/Article/details/gt2gypdnkjd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gt2fvxnzbmh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.svipenyu.cn/Article/details/gt2dubrclnr.html

[F12] CSV 读写
来源：http://dali.nanxuanxn.top/Article/details/gt2objqbkff.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.svipenyu.cn/Article/details/gt2tyjeaksr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnqzz.top/Article/details/gt2mzeqshju.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gt2hwfvpfzo.html

TS:   // 同上
来源：http://dali.sufxvd.cn/Article/details/gt2myfahfci.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njnybuqa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shzxlz.cn/Article/details/gt2iczmvdxp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hywenlv.cn/Article/details/gt2jcvzldmz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.snrcjt.cn/Article/details/gt2jegvptre.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2pjvrfmxn.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwiotclx.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2dttuuepw.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gt2hgzdwhdr.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gt2anlfzjun.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eemmqslv.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2yzieixoz.html

TS:   class User { name: string = ""; }
来源：http://dali.xylfe.cn/Article/details/gt2sdypzexb.html

Java: class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2qleirjxq.html

Go:   type User struct { Name string }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vrncwmtl.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gt2yvybzxei.html

C#:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2tsxvrbkz.html

[G02] 构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2musograe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhengqikj.top/Article/details/gt2knhfpshv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gt2hgnpxgzb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wmmoxqpa.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2gpkaqjxu.html

Java: User(String name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gt2jghcpbcz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gt2bcqpjeji.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gt2tawsfihi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gogol.net.cn/Article/details/gt2sqzwylel.html

[G03] 实例属性
来源：http://dali.ppjwa.cn/Article/details/gt2qssnaisf.html

Py:   self.name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gt2kwcwpflo.html

PHP:  public string $name = "x";
来源：http://dali.aizwys.cn/Article/details/gt2wacgcdkz.html

JS:   this.name = "x";
来源：http://dali.hammf.cn/Article/details/gt2wyoxilue.html

TS:   name: string = "x";
来源：http://dali.daxiang520.top/Article/details/gt2twaowduu.html

Java: private String name;
来源：http://dali.gotoacloud.top/Article/details/gt2bvhjrnfa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.snrcjt.cn/Article/details/gt2toznzfgt.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mihoydqd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daria6918.cn/Article/details/gt2drvjgvdo.html

[G04] 定义方法
来源：http://dali.aibaodan.cn/Article/details/gt2rolnzkow.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gt2oqeaibsv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gt2hkdtzsrt.html

JS:   greet() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2upletgbu.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2izifdqlv.html

Java: String greet() { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2kiccywlt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gt2tkxektfy.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzsbqlc.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gt2vwxkjfmn.html

[G05] 继承
来源：http://dali.ehwqpu.com/Article/details/gt2jcoisziv.html

Py:   class Admin(User): pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2vqfcjqqw.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2zeswkaxb.html

JS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2tdogutte.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gt2pywoknam.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2hlgtjsxk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ehwqpu.com/Article/details/gt2eazocpsr.html

Ruby: class Admin < User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktcjaffm.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gt2vtzwdjgd.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2aerydyrj.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tbeuonot.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2prlqxgbu.html

JS:   greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2jykdahxk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2nudqshnk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gt2nhwbrclc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mdznxqbs.html

Ruby: def greet; "admin"; end
来源：http://dali.vqdsnc.cn/Article/details/gt2vpwjxouc.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gt2bmyzuzyx.html

[G07] 调用父类方法
来源：http://dali.gzhubu.top/Article/details/gt2qcjtarbj.html

Py:   super().greet()
来源：http://dali.aizwys.cn/Article/details/gt2kctssbzk.html

PHP:  parent::greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2qwkttten.html

JS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gt2mjqaezet.html

TS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wsecwgcy.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2przyynjv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gt2selhwvga.html

Ruby: super
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2purnfkif.html

C#:   base.Greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2rbqizgvb.html

[G08] 静态方法与属性
来源：http://dali.hywenlv.cn/Article/details/gt2kcfikcyl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.birdmap.top/Article/details/gt2lyozduvu.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2sckkbnwf.html

JS:   static f() {}
来源：http://dali.pycfn.com/Article/details/gt2uobfklfk.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gt2pyrhmyug.html

Java: static void f() {}
来源：http://dali.mhx1999.top/Article/details/gt2jvlabomb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zeljrfkr.html

Ruby: def self.f; end
来源：http://dali.jqgufenzy.top/Article/details/gt2tsrxppkw.html

C#:   public static void F() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2dpddjpjj.html

[G09] 接口 / 抽象类
来源：http://dali.hywenlv.cn/Article/details/gt2vjapsrhm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gaohongyu789.top/Article/details/gt2uclrcxuv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gt2tuzgfluu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.birdmap.top/Article/details/gt2ytowoufb.html

TS:   interface Shape { area(): number; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ndiqgrmw.html

Java: interface Shape { double area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lrvnbbvy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gt2mfvbqlsy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hghpjgzl.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2yuooobih.html

[G10] 访问控制
来源：http://dali.jinqigfzy.top/Article/details/gt2nolhrtlb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jqqfktui.html

PHP:  public / protected / private
来源：http://dali.wangdashe.top/Article/details/gt2npikbdgl.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gt2cdhuibdm.html

TS:   public / protected / private
来源：http://dali.shuidangran.top/Article/details/gt2rqmcpkzo.html

Java: public / protected / private / 默认包级
来源：http://dali.guannengcc.top/Article/details/gt2noimsxcy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xinyue.icu/Article/details/gt2alowsytx.html

Ruby: public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gt2qikkvqej.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gt2ruubugam.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gt2jrineblb.html

Py:   @property 与 @x.setter
来源：http://dali.aizwys.cn/Article/details/gt2omaizmbs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2oaqayrfr.html

JS:   get name() { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gt2bmzuytpd.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gt2klqzhght.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gt2xzmmosad.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gt2wakpbqvo.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gt2zkwynrcn.html

C#:   public string Name { get; set; }
来源：http://dali.guowangkeji.top/Article/details/gt2gazkllcf.html

[G12] 对象转字符串
来源：http://dali.dashuyun.cn/Article/details/gt2pthhxdis.html

Py:   def __str__(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gt2ocmjrdrp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gt2ywnapblq.html

JS:   toString() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gt2racmzwtn.html

TS:   toString(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2zakudsbw.html

Java: @Override public String toString() { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2hjdfbvqu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gt2iqskclsd.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigufen.top/Article/details/gt2kkdhvybh.html

C#:   public override string ToString() => Name;
来源：http://dali.smart0.xyz/Article/details/gt2xhboahiz.html

[G13] 判断对象类型
来源：http://dali.bjfxy.top/Article/details/gt2mctpjptl.html

Py:   isinstance(u, User)
来源：http://dali.jiagoushi.top/Article/details/gt2pnxochwc.html

PHP:  $u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2ujbpmwxs.html

JS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2qgmnjjmf.html

TS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2vvyartgm.html

Java: u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uzbzjxrb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hysaishi.cn/Article/details/gt2shewkame.html

Ruby: u.is_a?(User)
来源：http://dali.guannengcc.top/Article/details/gt2skfopjch.html

C#:   u is User
来源：http://dali.yuanzhike.top/Article/details/gt2rbyglmts.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gt2hjyjvwek.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gt2ughvdved.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gt2bkbcaxeo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2evzkypau.html

TS:   type User = { name: string; age: number };
来源：http://dali.pycfn.com/Article/details/gt2ilrlfpqw.html

Java: record User(String name, int age) {}
来源：http://dali.zycfv.cn/Article/details/gt2xxfrhxuf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daria6918.cn/Article/details/gt2qwknsnok.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yanxiufei.cn/Article/details/gt2brnnblcq.html

C#:   record User(string Name, int Age);
来源：http://dali.ppjwa.cn/Article/details/gt2qzmiklgf.html

[G15] 枚举
来源：http://dali.yongpay.top/Article/details/gt2jjxkdfqc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gt2fsafwsfu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jianghu66.top/Article/details/gt2uzvzuofe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jianghu66.top/Article/details/gt2asmrhdua.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kctdjbgm.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2prpdyxbc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pycfn.com/Article/details/gt2icczpzpi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adwedljc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2dgxaxdts.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gt2berqlxgr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenzaomai.com/Article/details/gt2kaeuikfa.html

PHP:  get_object_vars($obj);
来源：http://dali.xylfe.cn/Article/details/gt2yhvlkjux.html

JS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gt2xkajldlx.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fziplnwh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhengqikj.top/Article/details/gt2kerzqxgf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenjidiqi.icu/Article/details/gt2jpybaasj.html

Ruby: obj.instance_variables
来源：http://dali.zhiwuduotai.top/Article/details/gt2tyxfppdl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gt2ckebbrxj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2zaszbswu.html

H. 异常与错误处理
来源：http://dali.jqgfzy.top/Article/details/gt2cvundzqg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2zamoxmcj.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gt2jsxvmohd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhiwuduotai.top/Article/details/gt2blbaeqng.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hywenlv.cn/Article/details/gt2gbxmebvy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gt2slbeooeq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gt2fwxyxaex.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xinyue.icu/Article/details/gt2nrgtjakz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aizwys.cn/Article/details/gt2xdozgelp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.meibo888.top/Article/details/gt2zwglimoy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhixingplan.top/Article/details/gt2ndlkybqj.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gt2rgkfhjrn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gt2ehnxdclk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2uggepbza.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2xvmgwzyg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2bvsxtfjx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mcznhnmz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gt2uzeftdsp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ydzc1.top/Article/details/gt2lsohmczq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2vdaswxvc.html

[H03] 主动抛出异常
来源：http://dali.gotoacloud.top/Article/details/gt2kftjrfwi.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gt2tdtuuldu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2cpmrsbib.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2ridnjxue.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ivacyaye.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2ureoukky.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258888.top/Article/details/gt2oebjupil.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shangyingyoupin.top/Article/details/gt2daaprnio.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2bovjcabs.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wvfruwyc.html

Py:   class MyError(Exception): pass
来源：http://dali.yj202588.top/Article/details/gt2ltrqvcvk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gt2kjduqsfg.html

JS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gt2yuejdlud.html

TS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gt2xfahirea.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvgxpkuy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.9152youxi.cn/Article/details/gt2dwfvnosc.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2okkkbepp.html

C#:   class MyException : Exception {}
来源：http://dali.quarkkingdee.top/Article/details/gt2jsxghosc.html

[H05] 捕获特定类型
来源：http://dali.yj20258888.top/Article/details/gt2hmgrksnr.html

Py:   except ValueError as e:
来源：http://dali.zdqjudy.top/Article/details/gt2jyrbgark.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daxiang520.top/Article/details/gt2krdbbsld.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gt2bqihgcev.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gt2kdkpdqde.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2hhzasltt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnxiangtu.top/Article/details/gt2uqumfada.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj202588.top/Article/details/gt2ulzskjtl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gt2znpnemsc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vnzfgbia.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gt2elrolaei.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gt2hztlhcdm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fhcvflhb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gt2dmlqicyn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.redwolf501.top/Article/details/gt2bgedeblb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzozmrmy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nanxinkj.top/Article/details/gt2ofpqeitk.html

C#:   obj?.A?.B ?? default
来源：http://dali.tian-w.cn/Article/details/gt2xypcwtbi.html

[H07] 断言
来源：http://dali.yuxming.cn/Article/details/gt2vknawyoo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shangyingyoupin.top/Article/details/gt2meqguncp.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tnecmpem.html

JS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gt2rkdsbksk.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gt2pjkdhsko.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cdnleiting.top/Article/details/gt2mdikxgsi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hfpthk.cn/Article/details/gt2goaztcmy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigfzy.top/Article/details/gt2qcldxxyq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2yiptphxy.html

[H08] 获取错误信息与堆栈
来源：http://dali.316326.xyz/Article/details/gt2ckouwhhj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jiagoushi.top/Article/details/gt2fizsyfen.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jianghu66.top/Article/details/gt2qhylapct.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gt2enooindl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.c1oappe.top/Article/details/gt2akthuwjd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xylfe.cn/Article/details/gt2fvpprjyx.html

Go:   err.Error()
来源：http://dali.gotoacloud.top/Article/details/gt2emwunhwl.html

Ruby: e.message;  e.backtrace
来源：http://dali.snrcjt.cn/Article/details/gt2qrguzstw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hfpthk.cn/Article/details/gt2dmlnjzjw.html

[H09] 带错误码的异常
来源：http://dali.guannengcc.top/Article/details/gt2ciltyiql.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.haohaochexian.top/Article/details/gt2skevblfh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sxryk.cn/Article/details/gt2tgqrwqca.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zdqjudy.top/Article/details/gt2xzpewbaq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gzhubu.top/Article/details/gt2dswtgbcf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ppjwa.cn/Article/details/gt2schrcmfz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.quarkkingdee.top/Article/details/gt2yqfugykp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ehwqpu.com/Article/details/gt2ppvvxuon.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gt2xaqzpfrd.html

[H10] 资源自动释放
来源：http://dali.dashuyun.cn/Article/details/gt2myoipwmb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sysykeji.top/Article/details/gt2zxwknrhd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxuanxn.top/Article/details/gt2xzjqrbkg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gt2piwzyukx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gt2rmqvjhwp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.aibaodan.cn/Article/details/gt2qhplzwml.html

Go:   defer f.Close()
来源：http://dali.xinyue.icu/Article/details/gt2xqgaxvjl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dashuyun.cn/Article/details/gt2rmoeecel.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fvcxewch.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2xvftbwnu.html

I. 正则表达式
来源：http://dali.shzxlz.cn/Article/details/gt2xzxlbuql.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2zrkuonbz.html

[I01] 判断是否匹配
来源：http://dali.0kj1m.cn/Article/details/gt2lwhxtxdi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yueranfly.top/Article/details/gt2ojaeweub.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2ceblidiq.html

JS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gt2bxnauana.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gt2iuxqygcj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daria6918.cn/Article/details/gt2gfesrthh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.snrcjt.cn/Article/details/gt2qaoofcys.html

Ruby: s.match?(/\d+/)
来源：http://dali.sysykeji.top/Article/details/gt2arbikzbc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xziqi.cn/Article/details/gt2rusrnbgz.html

[I02] 提取所有匹配
来源：http://dali.ybcxt.top/Article/details/gt2gyizjufj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gt2ttrdilsx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ppjwa.cn/Article/details/gt2xinackof.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tian-w.cn/Article/details/gt2bqbtjyfj.html

TS:   s.match(/\d+/g)
来源：http://dali.smart0.xyz/Article/details/gt2evjifaem.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuzfjtv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gt2xzlubkoo.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinqigfzy.top/Article/details/gt2pkkjqpog.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2hgqowceu.html

[I03] 提取捕获分组
来源：http://dali.ehwqpu.com/Article/details/gt2qslkqriz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cucudq.cn/Article/details/gt2nolfehap.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigfzy.top/Article/details/gt2lsirwsxw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.aibaodan.cn/Article/details/gt2wmzsjyzw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hfpthk.cn/Article/details/gt2wsyqrkcs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.haohaochexian.top/Article/details/gt2nsnomnxc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuanzhike.top/Article/details/gt2zzsnjwnu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aizwys.cn/Article/details/gt2hcppyhzj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daxiang520.top/Article/details/gt2mijauufz.html

[I04] 正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2drteqizu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuanzx.com/Article/details/gt2hgvpbuby.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wrkigtrb.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdtrsuoc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.pengpengdd.cyou/Article/details/gt2juhxbmmf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gt2maeoripm.html


<!-- 参考信息 -->