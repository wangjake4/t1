代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2ubflztaf.html

[F06] 删除文件
来源：http://dali.cashguo.top/Article/details/gt2atmbrckw.html

Py:   os.remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2pzsmrcdk.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2ssblhisw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2fdtnalrg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzeizkau.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gt2grlkfolr.html

Go:   os.Remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2jfxcnlka.html

Ruby: File.delete("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2ajmxdobu.html

C#:   File.Delete("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2iwfgfmzf.html

[F07] 创建目录（含多级）
来源：http://dali.zhongyouzk.top/Article/details/gt2vfvmgfec.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wlqtykhm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gt2vdfjxdxn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gt2tbqkxdod.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gt2oqlbjxoo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fzhhl.top/Article/details/gt2itlkylld.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxinkj.top/Article/details/gt2yoamovwg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnxiangtu.top/Article/details/gt2txwaqhrk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.0kj1m.cn/Article/details/gt2sevtbure.html

[F08] 遍历目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cojkohsj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shuidangran.top/Article/details/gt2etfvkcup.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vhbtfbuv.html

JS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2vdzdkfyq.html

TS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gt2femydmab.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gt2wvqzvpqk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2tiamympv.html

Ruby: Dir.children("dir")
来源：http://dali.xinyue.icu/Article/details/gt2kdkruyfg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gt2gwjumydv.html

[F09] 获取文件大小
来源：http://dali.jinqigufen.top/Article/details/gt2tfbcswjk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2flrvpyev.html

PHP:  filesize("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2ihubtucm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gt2pozwziin.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gt2ezbwegvn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2hkzzfpom.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.haohaochexian.top/Article/details/gt2utuoezdl.html

Ruby: File.size("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2jdnvrrho.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gt2ebjkfxkb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daxiang520.top/Article/details/gt2yokvgmhc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2mxwlhwad.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2dkdcpclh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rgmvqcln.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2afyghmpu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pycfn.com/Article/details/gt2jqzeyhlk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2unoijjsd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2pdftecdo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2wqmnzkha.html

[F11] 复制与移动文件
来源：http://dali.xuanzx.com/Article/details/gt2efytdrev.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gt2pejzkcka.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.havefunace.top/Article/details/gt2hargtmpr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2scvqyafl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2xjfbzubv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.andypj.xyz/Article/details/gt2pkshhorz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yanxiufei.cn/Article/details/gt2pcrhjaeu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2ulchgoun.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yvedp.cn/Article/details/gt2tzpmiblt.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxrlcpbx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnxiangtu.top/Article/details/gt2obvbelbf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ivvv.top/Article/details/gt2qiptqxqz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj202588.top/Article/details/gt2yrqsrtdz.html

TS:   // 同上
来源：http://dali.shuidangran.top/Article/details/gt2stiovolx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj20258.top/Article/details/gt2nevlyjql.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dianchejie.cn/Article/details/gt2wtgofwsr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gt2lwurjcwf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.c1oappe.top/Article/details/gt2dzdfezaf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2xmmvtaos.html

G. 面向对象
来源：http://dali.xziqi.cn/Article/details/gt2bnikgmas.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2abpdzmyz.html

[G01] 定义类
来源：http://dali.jiagoushi.top/Article/details/gt2nmkiwkwh.html

Py:   class User: pass
来源：http://dali.yuxming.cn/Article/details/gt2pnsglhiw.html

PHP:  class User {}
来源：http://dali.cashguo.top/Article/details/gt2esgyfuqu.html

JS:   class User {}
来源：http://dali.jianghu66.top/Article/details/gt2wndnopxu.html

TS:   class User { name: string = ""; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rkvhirjr.html

Java: class User {}
来源：http://dali.birdmap.top/Article/details/gt2zzxsjzhv.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gt2kkelracz.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gt2stxaoqns.html

C#:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2wtqhudyv.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gt2tirnziaz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aizwys.cn/Article/details/gt2xsckydww.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cdnleiting.top/Article/details/gt2wbgnokzm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2hkxlfoaf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qaagtiwk.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gt2twrsqcyq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gt2sfydtfpx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qbrfjguy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2aftfodfo.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gt2ixutjekx.html

Py:   self.name = "x"
来源：http://dali.9152youxi.cn/Article/details/gt2wujqeeop.html

PHP:  public string $name = "x";
来源：http://dali.ybcxt.top/Article/details/gt2kobvqsee.html

JS:   this.name = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2fpgnpqxa.html

TS:   name: string = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gt2mojugret.html

Java: private String name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xmqcivhn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenlongwang.top/Article/details/gt2xrdgekah.html

Ruby: @name = "x"
来源：http://dali.jinqigufen.top/Article/details/gt2rxwmbelx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sxryk.cn/Article/details/gt2yoxjkkbx.html

[G04] 定义方法
来源：http://dali.ydzc1.top/Article/details/gt2ibenawwj.html

Py:   def greet(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gt2ceabefbe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gt2ieafueyy.html

JS:   greet() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ilukqxgc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2rvygsdnr.html

Java: String greet() { return name; }
来源：http://dali.havefunace.top/Article/details/gt2cauqmbrs.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gt2gotqmrmb.html

Ruby: def greet; @name; end
来源：http://dali.ppjwa.cn/Article/details/gt2bavnfxly.html

C#:   public string Greet() => Name;
来源：http://dali.guannengcc.top/Article/details/gt2omiuprkl.html

[G05] 继承
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtjjsnnb.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gt2bvqzivgs.html

PHP:  class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2jlmiwidj.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftplrxto.html

TS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2lqhrqmdn.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2hchqclid.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pycfn.com/Article/details/gt2fakwuyft.html

Ruby: class Admin < User; end
来源：http://dali.aizwys.cn/Article/details/gt2ffwuuqir.html

C#:   class Admin : User {}
来源：http://dali.316326.xyz/Article/details/gt2xixcdege.html

[G06] 重写方法
来源：http://dali.yanxiufei.cn/Article/details/gt2ckxyxpwh.html

Py:   def greet(self): return "admin"
来源：http://dali.c1oappe.top/Article/details/gt2inerirzs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gt2nwinkana.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qrcognbg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2dzqttfqw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2sqswvpct.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.iojbl.cn/Article/details/gt2fiwzpjvh.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gt2kmtldqjk.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iyurkqzs.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2wodouocl.html

Py:   super().greet()
来源：http://dali.cheryme.top/Article/details/gt2ftiehspw.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gt2hdzazfbj.html

JS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gt2ndetrxta.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gt2tooasymm.html

Java: super.greet();
来源：http://dali.chenzaomai.com/Article/details/gt2khtrhksk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.andypj.xyz/Article/details/gt2brqhwysf.html

Ruby: super
来源：http://dali.yj20258888.top/Article/details/gt2inibeyda.html

C#:   base.Greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2oizbvbih.html

[G08] 静态方法与属性
来源：http://dali.xuetiantiany.cn/Article/details/gt2vfxnimry.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.havefunace.top/Article/details/gt2hsvelbyx.html

PHP:  public static function f() {}
来源：http://dali.xylfe.cn/Article/details/gt2dmoigwvs.html

JS:   static f() {}
来源：http://dali.tianlin.xyz/Article/details/gt2mcgwrryn.html

TS:   static f(): void {}
来源：http://dali.316326.xyz/Article/details/gt2xcrkiqkn.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2xlnehrxb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shuidangran.top/Article/details/gt2thbrayql.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gt2lajuatrf.html

C#:   public static void F() {}
来源：http://dali.nanxinkj.top/Article/details/gt2rtgpancu.html

[G09] 接口 / 抽象类
来源：http://dali.fengsongda.top/Article/details/gt2xdbcmofb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.feifeiyinyue.top/Article/details/gt2verbaxqa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fzhhl.top/Article/details/gt2nkwyipto.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zqaonbym.html

TS:   interface Shape { area(): number; }
来源：http://dali.0kj1m.cn/Article/details/gt2sjsegpaq.html

Java: interface Shape { double area(); }
来源：http://dali.cashguo.top/Article/details/gt2iwaovcdr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhongyouzk.top/Article/details/gt2rjptbaep.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gaohongyu789.top/Article/details/gt2nezpwmun.html

C#:   interface IShape { double Area(); }
来源：http://dali.tian-w.cn/Article/details/gt2ksjbfwst.html

[G10] 访问控制
来源：http://dali.ehwqpu.com/Article/details/gt2ivwpzalz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hongshengwenyu.top/Article/details/gt2oxajtvdn.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2qkdvxvui.html

JS:   #private 字段；其余公开
来源：http://dali.svipenyu.cn/Article/details/gt2piivwphb.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2rkuuhvoi.html

Java: public / protected / private / 默认包级
来源：http://dali.yvedp.cn/Article/details/gt2bpnbifem.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gt2ezzkxxrk.html

Ruby: public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2hynirqat.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfbivtxg.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gt2intaqeez.html

Py:   @property 与 @x.setter
来源：http://dali.zhoulong.xyz/Article/details/gt2vgpajome.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2upvsxxbd.html

JS:   get name() { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gt2ylshxhqw.html

TS:   get name(): string { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gt2gbpuhlwx.html

Java: public String getName() { return name; }
来源：http://dali.havefunace.top/Article/details/gt2zhtrdzrl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xawmhhkl.html

Ruby: attr_accessor :name
来源：http://dali.xuetiantiany.cn/Article/details/gt2ryuudpow.html

C#:   public string Name { get; set; }
来源：http://dali.yvedp.cn/Article/details/gt2vnoiuegb.html

[G12] 对象转字符串
来源：http://dali.xinyue.icu/Article/details/gt2umblpzrs.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2xehqdkzj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gt2rvzhrbnm.html

JS:   toString() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hmyaqtkj.html

TS:   toString(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2uotalyqi.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2psnnzpxs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gt2fnllbrzb.html

Ruby: def to_s; @name; end
来源：http://dali.smart0.xyz/Article/details/gt2oozpxwnt.html

C#:   public override string ToString() => Name;
来源：http://dali.zdqjudy.top/Article/details/gt2mdgrnjyl.html

[G13] 判断对象类型
来源：http://dali.sysykeji.top/Article/details/gt2odjcqkik.html

Py:   isinstance(u, User)
来源：http://dali.gotoacloud.top/Article/details/gt2evrakjof.html

PHP:  $u instanceof User
来源：http://dali.xziqi.cn/Article/details/gt2twnvcrak.html

JS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gt2swevphli.html

TS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gt2udzcbeqq.html

Java: u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2xcqfhxla.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258.top/Article/details/gt2gmayrxfw.html

Ruby: u.is_a?(User)
来源：http://dali.hnqzz.top/Article/details/gt2yhkojjww.html

C#:   u is User
来源：http://dali.sufxvd.cn/Article/details/gt2yqhpddiv.html

[G14] 数据类 / record
来源：http://dali.dianchejie.cn/Article/details/gt2lhndabzh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sysykeji.top/Article/details/gt2glktdlez.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinghuilouyu.cn/Article/details/gt2thouiuzl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gt2ptewiuao.html

TS:   type User = { name: string; age: number };
来源：http://dali.316326.xyz/Article/details/gt2wrjtfxdx.html

Java: record User(String name, int age) {}
来源：http://dali.bjfxy.top/Article/details/gt2mizisfma.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sufxvd.cn/Article/details/gt2cewxpdmn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gt2rbelbqny.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gt2eqhxpapm.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gt2ltigglpj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gt2yjyxzwit.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuwbywn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gt2ilfgldih.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gt2lljnvmmn.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hdmmeygn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fengsongda.top/Article/details/gt2amxoucad.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gt2ezsegymb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2rctqvnnn.html

[G16] 对象转数组 / 字典
来源：http://dali.haohaochexian.top/Article/details/gt2fizuckfk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.9152youxi.cn/Article/details/gt2osntjpfy.html

PHP:  get_object_vars($obj);
来源：http://dali.gzhubu.top/Article/details/gt2ojsmrajy.html

JS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gt2itrnrlad.html

TS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2bmgzyhyd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aibaodan.cn/Article/details/gt2tsixgswv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dianchejie.cn/Article/details/gt2efplcbjz.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gt2rpldlsqq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gt2bdjljlby.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2vdqipvth.html

H. 异常与错误处理
来源：http://dali.jyoumei.cn/Article/details/gt2xlugsfng.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2rtzvciub.html

[H01] try / catch 基础
来源：http://dali.nwbrower.top/Article/details/gt2kvokgkdx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gt2vrepafmy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gt2pwqrhoxg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gt2rfdfjpqy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2umdoihyu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gogol.net.cn/Article/details/gt2mgtwdlde.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.mhx1999.top/Article/details/gt2pnetzqaa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigfzy.top/Article/details/gt2yjzioeto.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xinyue.icu/Article/details/gt2kgjgjryu.html

[H02] finally / ensure 收尾
来源：http://dali.ivvv.top/Article/details/gt2ukmvhsul.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gaohongyu789.top/Article/details/gt2xlzptmff.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2zuosxuwq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2lewegxbv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2pnefmjez.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2hgvaojmb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gzhubu.top/Article/details/gt2oyoexxjj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gt2uaswkuwm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2biiovmwg.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gt2xxwpvbkw.html

Py:   raise ValueError("错误信息")
来源：http://dali.quarkkingdee.top/Article/details/gt2vopeujtv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2sptmftxl.html

JS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2udqdiywv.html

TS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2erghzcse.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2kiupgivv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sxryk.cn/Article/details/gt2rqxwgdhm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.iojbl.cn/Article/details/gt2ghnzbzaz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2koghunis.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gt2itolesgr.html

Py:   class MyError(Exception): pass
来源：http://dali.wangshuangyany.cn/Article/details/gt2skjmgqxu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gt2adnbaxoa.html

JS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gt2kliuiwvj.html

TS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gt2wvkqahml.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gt2tkthonjr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guannengcc.top/Article/details/gt2esakoaaq.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgufenzy.top/Article/details/gt2clzliayu.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gt2ctmragnq.html

[H05] 捕获特定类型
来源：http://dali.gzhubu.top/Article/details/gt2fbjwzilc.html

Py:   except ValueError as e:
来源：http://dali.yj20258.top/Article/details/gt2zllmudfv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gzhubu.top/Article/details/gt2nvqjklry.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2zlxlvykv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2bmypcvsq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgfzy.top/Article/details/gt2esayqrim.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jianghu66.top/Article/details/gt2hgpomjlk.html

Ruby: rescue ArgumentError => e
来源：http://dali.jianghu66.top/Article/details/gt2durcnuvy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigufen.top/Article/details/gt2vfitcjzq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gt2glqxtlms.html

Py:   value = d.get("k") or default
来源：http://dali.fzhhl.top/Article/details/gt2lvampyct.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.meibo888.top/Article/details/gt2bsutbukq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2mdsqjfag.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gt2jsdgokxo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jcprrlnu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangshuangyany.cn/Article/details/gt2svjwpmox.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shzxlz.cn/Article/details/gt2lhnordsk.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2itjoleif.html

[H07] 断言
来源：http://dali.cdnleiting.top/Article/details/gt2aafjjjzt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ppjwa.cn/Article/details/gt2ysudljlt.html

PHP:  assert($x > 0);
来源：http://dali.yuanzhike.top/Article/details/gt2ypupkmkr.html

JS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2yrxhnfmm.html

TS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2izjdgwqw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj202588.top/Article/details/gt2quzkbkqu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tianlin.xyz/Article/details/gt2wffnlwtf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cucudq.cn/Article/details/gt2iiarcqaa.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gt2mzerilji.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnxiangtu.top/Article/details/gt2veaqpyaa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.iojbl.cn/Article/details/gt2lgxzbxbd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lyujopcb.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gt2oosspfkz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjycvci.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.cqqwz.cn/Article/details/gt2qukqdkza.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gt2pdkvbpxi.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuxming.cn/Article/details/gt2icdiiilw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.9152youxi.cn/Article/details/gt2ddlkwbqc.html

[H09] 带错误码的异常
来源：http://dali.dashuyun.cn/Article/details/gt2vdtyabem.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gotoacloud.top/Article/details/gt2auuwwwls.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhixingplan.top/Article/details/gt2dawlwewd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaanpuen.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gt2lgtmnhuv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cqqwz.cn/Article/details/gt2dnuadtol.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gt2polemffo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.havefunace.top/Article/details/gt2pjphqnej.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.chenlongwang.top/Article/details/gt2tujranml.html

[H10] 资源自动释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vdobeyfs.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jqgfzy.top/Article/details/gt2lzddmgkn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gt2rxtrbtfz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gt2bnxzwnnd.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shuidangran.top/Article/details/gt2jcubrclq.html


<!-- 参考信息 -->