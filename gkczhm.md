代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sufxvd.cn/Article/details/gt2pakziusj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgufenzy.top/Article/details/gt2upbjprub.html

JS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gt2hciaykgn.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gt2uxtpggvf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gt2joyfoovg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2cjstzblf.html

Ruby: Dir.children("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wibvvzau.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yvedp.cn/Article/details/gt2pivnozxx.html

[F09] 获取文件大小
来源：http://dali.xziqi.cn/Article/details/gt2sydcuwjt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2psntdwgt.html

PHP:  filesize("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2zlnrecak.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gt2madwilvt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gt2ufvqlbza.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gt2fupgjwuo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkfmtewo.html

Ruby: File.size("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2umakeahi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.c1oappe.top/Article/details/gt2xmfcqusp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.feifeiyinyue.top/Article/details/gt2okanepbr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlacmzxd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2kjxmvrga.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2mswyqfvl.html

TS:   path.extname("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2yfvdcela.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.bjfxy.top/Article/details/gt2wxtdjlkf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2gxtcmsnp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2rukewvsn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2qyxjywwb.html

[F11] 复制与移动文件
来源：http://dali.cqqwz.cn/Article/details/gt2vmvcpuof.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gt2kgtqvsjq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2qomrjgtj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gt2npqqfyrx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2iaffygxt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shuidangran.top/Article/details/gt2cponuwyh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jyoumei.cn/Article/details/gt2gtzkaedl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2hkqujvrt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gt2rwuonrwp.html

[F12] CSV 读写
来源：http://dali.andypj.xyz/Article/details/gt2ojkmqcth.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2aubrhzns.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gzhubu.top/Article/details/gt2fgmhwsrg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.haohaochexian.top/Article/details/gt2vltcujgp.html

TS:   // 同上
来源：http://dali.9152youxi.cn/Article/details/gt2achhpxdi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.havefunace.top/Article/details/gt2lbopvqac.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sweek.top/Article/details/gt2dwkhzbpk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.vqdsnc.cn/Article/details/gt2fulsgdxl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.andypj.xyz/Article/details/gt2hyhlcscf.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2dqugcjwo.html

G. 面向对象
来源：http://dali.ybcxt.top/Article/details/gt2hsgxlffc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2pbyfmwwh.html

[G01] 定义类
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxtvazya.html

Py:   class User: pass
来源：http://dali.aizwys.cn/Article/details/gt2mkjlcife.html

PHP:  class User {}
来源：http://dali.smart0.xyz/Article/details/gt2ftkxxhun.html

JS:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2twvsktej.html

TS:   class User { name: string = ""; }
来源：http://dali.cheryme.top/Article/details/gt2levuimtb.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gt2wzaxbzts.html

Go:   type User struct { Name string }
来源：http://dali.zhengqikj.top/Article/details/gt2qowyzhvl.html

Ruby: class User; end
来源：http://dali.gotoacloud.top/Article/details/gt2jioztzkh.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2rifcozac.html

[G02] 构造函数
来源：http://dali.ydzc1.top/Article/details/gt2jhihqpfl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guannengcc.top/Article/details/gt2saaakmwa.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gt2juxuvqjt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gt2ypcevvzr.html

TS:   constructor(public name: string) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2tvajxaoe.html

Java: User(String name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gt2noeidrvp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2giwgncap.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gt2bsfwdwiu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daria6918.cn/Article/details/gt2xkmiqxjg.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2xppkohlq.html

Py:   self.name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gt2bewnuaet.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gt2dnefpdoh.html

JS:   this.name = "x";
来源：http://dali.chenzaomai.com/Article/details/gt2dfnisqxj.html

TS:   name: string = "x";
来源：http://dali.fengsongda.top/Article/details/gt2jwuksuoj.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gt2stroojbz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ehwqpu.com/Article/details/gt2tmmmodtx.html

Ruby: @name = "x"
来源：http://dali.ivvv.top/Article/details/gt2llfgohla.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2zvuuuywq.html

[G04] 定义方法
来源：http://dali.ppjwa.cn/Article/details/gt2gvlowbta.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gt2xlyjghms.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2rotwznsz.html

JS:   greet() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2emuzfdis.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2zeghsohz.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2expfmkgl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gt2wemqvbjg.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qusdnrdb.html

C#:   public string Greet() => Name;
来源：http://dali.316326.xyz/Article/details/gt2gtdtcdbi.html

[G05] 继承
来源：http://dali.smart0.xyz/Article/details/gt2abrrsvdy.html

Py:   class Admin(User): pass
来源：http://dali.ybcxt.top/Article/details/gt2hqjderyd.html

PHP:  class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2hraopbvh.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shkbexhm.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmteeyjn.html

Java: class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2numxlzlm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gt2ssnytcfi.html

Ruby: class Admin < User; end
来源：http://dali.jinqigufen.top/Article/details/gt2ytkpnrit.html

C#:   class Admin : User {}
来源：http://dali.cdnleiting.top/Article/details/gt2wrifnyxm.html

[G06] 重写方法
来源：http://dali.jianghu66.top/Article/details/gt2wkrwywoe.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gt2cvytbtir.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2ijlfvbbb.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2bisrmyhw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2myjpbkvh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zzaanpbq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cqqwz.cn/Article/details/gt2wwmwxygt.html

Ruby: def greet; "admin"; end
来源：http://dali.hywenlv.cn/Article/details/gt2xeeekqcz.html

C#:   public override string Greet() => "admin";
来源：http://dali.cucudq.cn/Article/details/gt2bcoupzke.html

[G07] 调用父类方法
来源：http://dali.birdmap.top/Article/details/gt2vnmnrhzq.html

Py:   super().greet()
来源：http://dali.316326.xyz/Article/details/gt2rhltqtnd.html

PHP:  parent::greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2vgdbsopi.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gt2yzeuxslp.html

TS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2qcdbwviw.html

Java: super.greet();
来源：http://dali.shzxlz.cn/Article/details/gt2ebjqqoas.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gt2mifwffmm.html

Ruby: super
来源：http://dali.vqdsnc.cn/Article/details/gt2gczfsgpn.html

C#:   base.Greet();
来源：http://dali.tianlin.xyz/Article/details/gt2lriebivz.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gt2mjpihvfp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ehwqpu.com/Article/details/gt2vgsffhrs.html

PHP:  public static function f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2upxxazpc.html

JS:   static f() {}
来源：http://dali.tian-w.cn/Article/details/gt2bvcfbudd.html

TS:   static f(): void {}
来源：http://dali.cucudq.cn/Article/details/gt2zaiocuck.html

Java: static void f() {}
来源：http://dali.ehwqpu.com/Article/details/gt2vxbueboo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.feifeiyinyue.top/Article/details/gt2fndbsqts.html

Ruby: def self.f; end
来源：http://dali.kuanghao11.cn/Article/details/gt2nonejyuz.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwucntyq.html

[G09] 接口 / 抽象类
来源：http://dali.fengsongda.top/Article/details/gt2lxvaapkm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.bjfxy.top/Article/details/gt2cyfnejmw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awjnrbeo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qajezpwi.html

TS:   interface Shape { area(): number; }
来源：http://dali.pycfn.com/Article/details/gt2mgifqwne.html

Java: interface Shape { double area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2napixome.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gt2xrggrvnz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gt2ziqxqbxh.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vspzjjrc.html

[G10] 访问控制
来源：http://dali.yanxiufei.cn/Article/details/gt2dlvshyzo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nwbrower.top/Article/details/gt2kugqdjjc.html

PHP:  public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gt2llmexurd.html

JS:   #private 字段；其余公开
来源：http://dali.hywenlv.cn/Article/details/gt2pzhloldm.html

TS:   public / protected / private
来源：http://dali.yuxming.cn/Article/details/gt2nrzwchsd.html

Java: public / protected / private / 默认包级
来源：http://dali.pycfn.com/Article/details/gt2whttfore.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gt2bwvklhfg.html

Ruby: public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gt2gpeurqio.html

C#:   public / protected / private / internal
来源：http://dali.hywenlv.cn/Article/details/gt2icvzjwsx.html

[G11] getter / setter
来源：http://dali.jinqigufen.top/Article/details/gt2njuldilm.html

Py:   @property 与 @x.setter
来源：http://dali.hysaishi.cn/Article/details/gt2xhutpxzm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vqgealgo.html

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gt2qlrngwbv.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gt2xzzqsvzi.html

Java: public String getName() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2qflqywxs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gt2gnlbytxm.html

Ruby: attr_accessor :name
来源：http://dali.tanke756.top/Article/details/gt2atrciuby.html

C#:   public string Name { get; set; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gvfwbewr.html

[G12] 对象转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vyimpbhi.html

Py:   def __str__(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gt2hmohcdnb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lmrwyjbe.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dlcpsdcz.html

TS:   toString(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2ozgrbisf.html

Java: @Override public String toString() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2ykcfepus.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2ujcaeemg.html

Ruby: def to_s; @name; end
来源：http://dali.smart0.xyz/Article/details/gt2pyynppfo.html

C#:   public override string ToString() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2tleprxuo.html

[G13] 判断对象类型
来源：http://dali.chenlongwang.top/Article/details/gt2bzovlqzw.html

Py:   isinstance(u, User)
来源：http://dali.jyoumei.cn/Article/details/gt2uawsewiq.html

PHP:  $u instanceof User
来源：http://dali.yj20258888.top/Article/details/gt2lkljoeby.html

JS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2mxpkbuyy.html

TS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2pcuwitss.html

Java: u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2hymlgfxk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gt2qjearnvr.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gt2lgmpxdkb.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gt2ijhjbyjl.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gt2sxkqlaqd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hysaishi.cn/Article/details/gt2ywvbvwzr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gt2jwpyhbuh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuanzx.com/Article/details/gt2nrxpnfsx.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenzaomai.com/Article/details/gt2wfbbyacx.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gt2bzwikglm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cheryme.top/Article/details/gt2ahppftgg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gogol.net.cn/Article/details/gt2jitcqeun.html

C#:   record User(string Name, int Age);
来源：http://dali.gogol.net.cn/Article/details/gt2cefdkhmu.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gt2zagvruuu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnqzz.top/Article/details/gt2ikihpwsq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fzhhl.top/Article/details/gt2pmbizfgo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shuidangran.top/Article/details/gt2lflpigny.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gt2mhjaezri.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgufenzy.top/Article/details/gt2nsxpcipm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yvedp.cn/Article/details/gt2bjavptei.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenzaomai.com/Article/details/gt2rhdjjibx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gt2xooavqxb.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gt2dpnexdie.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj202588.top/Article/details/gt2gguvxywj.html

PHP:  get_object_vars($obj);
来源：http://dali.birdmap.top/Article/details/gt2zmwnrwox.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2mxfccbkv.html

TS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2rlxkuzpk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zdqjudy.top/Article/details/gt2iebtnxwh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pengpengdd.cyou/Article/details/gt2odofiucb.html

Ruby: obj.instance_variables
来源：http://dali.hfpthk.cn/Article/details/gt2aujaqfwk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yonumen.top/Article/details/gt2zjrvakqx.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2bczpjynj.html

H. 异常与错误处理
来源：http://dali.sysykeji.top/Article/details/gt2jxnuknar.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2attgllyb.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gt2hboufwlf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xziqi.cn/Article/details/gt2ffowwbzo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jianghu66.top/Article/details/gt2fkoorzep.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gt2xblquxxr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gt2vldranww.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hywenlv.cn/Article/details/gt2znkafcmf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhongyouzk.top/Article/details/gt2ecfsmytl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yvedp.cn/Article/details/gt2gvfwtpus.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fbwyirlr.html

[H02] finally / ensure 收尾
来源：http://dali.chenzaomai.com/Article/details/gt2odgelyxe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cqqwz.cn/Article/details/gt2ppvsegnc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2sfyzzrhc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2uagzsvnk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jgjqxric.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2chnkzplm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhongyouzk.top/Article/details/gt2vbijuphm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258888.top/Article/details/gt2sjtrided.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj202588.top/Article/details/gt2hczvekkn.html

[H03] 主动抛出异常
来源：http://dali.shuidangran.top/Article/details/gt2vvmmajwk.html

Py:   raise ValueError("错误信息")
来源：http://dali.iojbl.cn/Article/details/gt2rdxudbtx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2kcgzeqfp.html

JS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tzckbdbz.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aatuhvgw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2dbospxbc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gt2pihyxtcm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gt2kikuxvgz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2koumyibf.html

[H04] 自定义异常类型
来源：http://dali.andypj.xyz/Article/details/gt2jygsyhpz.html

Py:   class MyError(Exception): pass
来源：http://dali.mhx1999.top/Article/details/gt2dqfmpaeo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gt2jyqwiljb.html

JS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gt2vbfgtekk.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gt2gdfjbcea.html

Java: class MyException extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gt2fcjsiirs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gt2vdidbsms.html

Ruby: class MyError < StandardError; end
来源：http://dali.jlsjyb.cn/Article/details/gt2gvbpufxp.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zscdplex.html

[H05] 捕获特定类型
来源：http://dali.hnqzz.top/Article/details/gt2iowuhtjr.html

Py:   except ValueError as e:
来源：http://dali.xuanzx.com/Article/details/gt2bedhtpiw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sysykeji.top/Article/details/gt2hvqzvcml.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gt2ukyoataj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gt2bxrildvd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ufxndubh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gt2oxxjlxkb.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gt2qekrqbyb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gt2mwevbohw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gt2jqnasaud.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gt2anjristh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gt2hajpzasj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gt2lfoimwtc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gt2ihpyhrpi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfzrkeoq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ybcxt.top/Article/details/gt2jotjjhqi.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gt2rogsegnq.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gt2dqqomhgx.html

[H07] 断言
来源：http://dali.ydzc1.top/Article/details/gt2oewzjorj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenlongwang.top/Article/details/gt2ipkyyddu.html

PHP:  assert($x > 0);
来源：http://dali.sweek.top/Article/details/gt2jxgcwvrm.html

JS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gt2cdkghzse.html

TS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gt2zjnyeqde.html

Java: assert x > 0 : "必须为正";
来源：http://dali.9152youxi.cn/Article/details/gt2cmdfsfrr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.0kj1m.cn/Article/details/gt2fwfiuyth.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhijiandao.cn/Article/details/gt2yivlbdes.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gt2yqhavvkz.html

[H08] 获取错误信息与堆栈
来源：http://dali.daria6918.cn/Article/details/gt2ndruldoo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwmrqbup.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcdcqext.html

JS:   e.message;  e.stack
来源：http://dali.zdqjudy.top/Article/details/gt2keikxwsi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jianghu66.top/Article/details/gt2lojgphth.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cdnleiting.top/Article/details/gt2kkriiorr.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gt2omzqwugj.html

Ruby: e.message;  e.backtrace
来源：http://dali.ydzc1.top/Article/details/gt2hoqxqimc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxinkj.top/Article/details/gt2qruulzwl.html

[H09] 带错误码的异常
来源：http://dali.tianlin.xyz/Article/details/gt2bflpvrnw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdrrpen.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jyoumei.cn/Article/details/gt2ustzrlge.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgufenzy.top/Article/details/gt2yttmwnuk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gt2jehswkdr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gt2gmctgdne.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenzaomai.com/Article/details/gt2tjcmrwrx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.bjfxy.top/Article/details/gt2bglajtqa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dianchejie.cn/Article/details/gt2fcahhhyk.html

[H10] 资源自动释放
来源：http://dali.0kj1m.cn/Article/details/gt2wbtitniv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuanzhike.top/Article/details/gt2uqvdpmdg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hywenlv.cn/Article/details/gt2mjfdxxlj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gt2jvyhkbjk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gt2uwkotwmf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sweek.top/Article/details/gt2mjessfek.html

Go:   defer f.Close()
来源：http://dali.quarkkingdee.top/Article/details/gt2pdksupsu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.bjfxy.top/Article/details/gt2nvaatwve.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uoosdcmw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2gpicxrlu.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihrvkake.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbnjsrmb.html

[I01] 判断是否匹配
来源：http://dali.aibaodan.cn/Article/details/gt2jottbcnp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gt2eogolwgs.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2afzhuknc.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2pytpmksk.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2azhckfqg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gufchlfd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yueranfly.top/Article/details/gt2paiymanz.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj202588.top/Article/details/gt2xpxhcykl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cqqwz.cn/Article/details/gt2aydvwbgp.html

[I02] 提取所有匹配
来源：http://dali.yueranfly.top/Article/details/gt2uzhtyonz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gt2zhdfofqf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cdnleiting.top/Article/details/gt2bxdremxa.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hnqzz.top/Article/details/gt2ushhwcva.html


<!-- 参考信息 -->