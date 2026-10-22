代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.c1oappe.top/Article/details/gt2ggbsjhci.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenjidiqi.icu/Article/details/gt2jrugjqcq.html

PHP:  file_exists("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2evwjpiks.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2hsqwifdf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2ktnghtmp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2zxgapsyx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nwbrower.top/Article/details/gt2viucciiz.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2cdxjvzug.html

C#:   File.Exists("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2mmxqqxid.html

[F06] 删除文件
来源：http://dali.yonumen.top/Article/details/gt2wflmtljo.html

Py:   os.remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2lxeqlbbk.html

PHP:  unlink("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2okfhncxy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2oklhityl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2yepujlru.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gt2etpvcpcl.html

Go:   os.Remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2kccwkelp.html

Ruby: File.delete("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fkeowqpd.html

C#:   File.Delete("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2xlclqett.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258888.top/Article/details/gt2hkfvbnjm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gt2cvjsstpt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yvedp.cn/Article/details/gt2sbzjckqm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gt2xpbqpgzp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gt2ygurtjfj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nwbrower.top/Article/details/gt2dppxyvuv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ybcxt.top/Article/details/gt2hmsefhmn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.bjfxy.top/Article/details/gt2lclmtkzw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shuidangran.top/Article/details/gt2nmhrelpa.html

[F08] 遍历目录
来源：http://dali.quarkkingdee.top/Article/details/gt2vrukrwsq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.havefunace.top/Article/details/gt2wfgvusgd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gt2oesyfeqg.html

JS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2laooaahb.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gt2xtfvdfqt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gt2ovbetsir.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2robjbpye.html

Ruby: Dir.children("dir")
来源：http://dali.daxiang520.top/Article/details/gt2howlvwsr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zycfv.cn/Article/details/gt2ycojpfws.html

[F09] 获取文件大小
来源：http://dali.jlsjyb.cn/Article/details/gt2bcmootve.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2rieolqdu.html

PHP:  filesize("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2vcfilnti.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gt2hvmxwelv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gt2iqtczlls.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2mxsgcpxt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sxryk.cn/Article/details/gt2szcxrusc.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2yiuvezyy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pycfn.com/Article/details/gt2vaitettx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cashguo.top/Article/details/gt2wrihyjav.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2swtqifco.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2cgwemmwz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2smpzgxin.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2hhonpvxd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yongpay.top/Article/details/gt2vvnkpuig.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yzhhllja.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2qyxdnfyi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2khomgixj.html

[F11] 复制与移动文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ctyxaasz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2gtlncevs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ivwkifoz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gt2jryxsdob.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gt2xuvhbqju.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gt2uvnlmzqs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.snrcjt.cn/Article/details/gt2dpagmykz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gt2kaeluecc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gotoacloud.top/Article/details/gt2pjyhcsoy.html

[F12] CSV 读写
来源：http://dali.havefunace.top/Article/details/gt2jjrlvhfq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bsqgsodz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sweek.top/Article/details/gt2xhihiwvx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.c1oappe.top/Article/details/gt2uwomatto.html

TS:   // 同上
来源：http://dali.jqgufenzy.top/Article/details/gt2ztaojlyu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ehwqpu.com/Article/details/gt2hyurciww.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjfpasdu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuanzx.com/Article/details/gt2yuhgjbii.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fengsongda.top/Article/details/gt2eamzxatu.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2xpiugiwj.html

G. 面向对象
来源：http://dali.wangdashe.top/Article/details/gt2ypnixxcv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ropdnvej.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gt2iuzwrqmw.html

Py:   class User: pass
来源：http://dali.wangshuangyany.cn/Article/details/gt2sisberei.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2kkfrmgvt.html

JS:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gt2ciovsjwk.html

TS:   class User { name: string = ""; }
来源：http://dali.sweek.top/Article/details/gt2xtngllzj.html

Java: class User {}
来源：http://dali.aibaodan.cn/Article/details/gt2ujbtuhmt.html

Go:   type User struct { Name string }
来源：http://dali.jinqigfzy.top/Article/details/gt2okcajfsl.html

Ruby: class User; end
来源：http://dali.yj20258888.top/Article/details/gt2kjnmsali.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gt2uwrxtccf.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tggepouk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gt2wozkuxli.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xylfe.cn/Article/details/gt2qmbvevzl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gt2anbvwqhv.html

TS:   constructor(public name: string) {}
来源：http://dali.sysykeji.top/Article/details/gt2mokzlgtp.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gt2rcbsimzr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenzaomai.com/Article/details/gt2rlrkephf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gt2efrqsgcw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gt2rlnyxsrz.html

[G03] 实例属性
来源：http://dali.snrcjt.cn/Article/details/gt2zoievnfl.html

Py:   self.name = "x"
来源：http://dali.hnqzz.top/Article/details/gt2drrlzxwh.html

PHP:  public string $name = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2nwoagmkx.html

JS:   this.name = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2catlagko.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gt2dzgqxbag.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gt2zdlkqczn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gt2hfuznfzm.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwimqsi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.meibo888.top/Article/details/gt2vfvucdao.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gt2xfhwlefu.html

Py:   def greet(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gt2rqnckdzq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2gjomioxk.html

JS:   greet() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2ulszgakm.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2eqgggzdz.html

Java: String greet() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2nkqtzxbk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gt2btpmmgpv.html

Ruby: def greet; @name; end
来源：http://dali.zhixingplan.top/Article/details/gt2juxjneaz.html

C#:   public string Greet() => Name;
来源：http://dali.sweek.top/Article/details/gt2mtuellat.html

[G05] 继承
来源：http://dali.gotoacloud.top/Article/details/gt2ifcbawbe.html

Py:   class Admin(User): pass
来源：http://dali.snrcjt.cn/Article/details/gt2blclmiry.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2qvtkkcfg.html

JS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2eeqaxuve.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2rtphmusv.html

Java: class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2ltrjexej.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gt2vzcyddlx.html

Ruby: class Admin < User; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2rvmajicg.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2uihytvko.html

[G06] 重写方法
来源：http://dali.tianlin.xyz/Article/details/gt2otkktogj.html

Py:   def greet(self): return "admin"
来源：http://dali.fzhhl.top/Article/details/gt2txadxido.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2xtlcfgmt.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gt2kfmvjnho.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2hgsjxnoe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2jelrdzfm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.316326.xyz/Article/details/gt2dhezyrrg.html

Ruby: def greet; "admin"; end
来源：http://dali.zycfv.cn/Article/details/gt2axkckojk.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gt2seqdjwjb.html

[G07] 调用父类方法
来源：http://dali.yj20258.top/Article/details/gt2fqeujjmz.html

Py:   super().greet()
来源：http://dali.gzhubu.top/Article/details/gt2uutgjobv.html

PHP:  parent::greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2kujjqadi.html

JS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vjenhmap.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2ehsokswv.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gt2gzyvbsgk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2jrhwafnz.html

Ruby: super
来源：http://dali.yj20258888.top/Article/details/gt2ppwzpvjn.html

C#:   base.Greet();
来源：http://dali.yueranfly.top/Article/details/gt2snwzhstn.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cyncafve.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxinkj.top/Article/details/gt2xihydzdh.html

PHP:  public static function f() {}
来源：http://dali.sxryk.cn/Article/details/gt2tffutkjy.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gt2ljqvcvmu.html

TS:   static f(): void {}
来源：http://dali.ivvv.top/Article/details/gt2duluyapk.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gt2hwfaxpeh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dianchejie.cn/Article/details/gt2utrpeheh.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rdeczula.html

C#:   public static void F() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2gnfcqfjq.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gt2ocyrcqxq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gt2bprzihcj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hkdgvdsf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sxryk.cn/Article/details/gt2vtfkjnkv.html

TS:   interface Shape { area(): number; }
来源：http://dali.ybcxt.top/Article/details/gt2ygdkvnha.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gt2dhvxjmic.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fzhhl.top/Article/details/gt2fvwdvafv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gaohongyu789.top/Article/details/gt2yxicptsx.html

C#:   interface IShape { double Area(); }
来源：http://dali.tianlin.xyz/Article/details/gt2jaqbbdvw.html

[G10] 访问控制
来源：http://dali.mhx1999.top/Article/details/gt2fraxryvx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ushqdvvg.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2lhgqhnsv.html

JS:   #private 字段；其余公开
来源：http://dali.jiagoushi.top/Article/details/gt2tcmscxil.html

TS:   public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2fobtiwmk.html

Java: public / protected / private / 默认包级
来源：http://dali.yonumen.top/Article/details/gt2ungawaix.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yvedp.cn/Article/details/gt2qnedrexq.html

Ruby: public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gt2vdvtmfuv.html

C#:   public / protected / private / internal
来源：http://dali.cdnleiting.top/Article/details/gt2rludfkys.html

[G11] getter / setter
来源：http://dali.daxiang520.top/Article/details/gt2kiectluk.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gt2iqwxrkey.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gt2devysjfd.html

JS:   get name() { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gt2txkpokkd.html

TS:   get name(): string { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2thgefvyn.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2uyfxmcny.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gt2zuxkiepi.html

Ruby: attr_accessor :name
来源：http://dali.redwolf501.top/Article/details/gt2xlmsodql.html

C#:   public string Name { get; set; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tygfecnh.html

[G12] 对象转字符串
来源：http://dali.ydzc1.top/Article/details/gt2yzhlhrje.html

Py:   def __str__(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gt2mpjsioud.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gt2vtlvdybj.html

JS:   toString() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2dmmljajr.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2psantntk.html

Java: @Override public String toString() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2icffqazn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gt2inznnqdu.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gt2ceaujidh.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gt2hjyzwsjq.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gt2iapxhyyd.html

Py:   isinstance(u, User)
来源：http://dali.yj20258.top/Article/details/gt2oufsbnhg.html

PHP:  $u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2okzxnuvv.html

JS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gt2szypqshg.html

TS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2geurjtif.html

Java: u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2elrzbgdc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gt2spsvbftr.html

Ruby: u.is_a?(User)
来源：http://dali.jlsjyb.cn/Article/details/gt2tcvxivio.html

C#:   u is User
来源：http://dali.gotoacloud.top/Article/details/gt2mbszgfww.html

[G14] 数据类 / record
来源：http://dali.sysykeji.top/Article/details/gt2wgrmjrye.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnxiangtu.top/Article/details/gt2ssnucblq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gt2zuixeegr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gt2qecxafqh.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gt2euymdgoi.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gt2rejopmif.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yongpay.top/Article/details/gt2vzrhmrfm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daria6918.cn/Article/details/gt2akkusdws.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gt2owamukfi.html

[G15] 枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ltsbdgaj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fengsongda.top/Article/details/gt2vagezwii.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yuanzhike.top/Article/details/gt2qwztvdho.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gt2fvlpkuht.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2qwqevwyy.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgfzy.top/Article/details/gt2xykulgqo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxuanxn.top/Article/details/gt2mrbyjkaz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gzhubu.top/Article/details/gt2omvvjwwu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gt2cdbhvgta.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gt2inlprqvp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenzaomai.com/Article/details/gt2wxiuvvsy.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gt2rhmynfgh.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gt2xuswhofc.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gt2twwezggb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yongpay.top/Article/details/gt2dxapuxgo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.svipenyu.cn/Article/details/gt2xidivawi.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gt2onrsbbqt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gt2mpwqtwor.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2odmpweem.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gt2melsmynl.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2oczybiia.html

[H01] try / catch 基础
来源：http://dali.iojbl.cn/Article/details/gt2hbupkmca.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fgckbnyb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gt2puipjiku.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gt2sihdjmfj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gt2yovcngmq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cheryme.top/Article/details/gt2ujvrtxot.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zycfv.cn/Article/details/gt2wamqomdl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dxafnimq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gt2tjcpzjup.html

[H02] finally / ensure 收尾
来源：http://dali.quarkkingdee.top/Article/details/gt2rizioczn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guowangkeji.top/Article/details/gt2jxzjeccm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2fhtpzvyu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gkbrikez.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2cwgjauwz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2yovdnbah.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hysaishi.cn/Article/details/gt2mmbtaorq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258.top/Article/details/gt2uwxzhrhu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2dsnpkenv.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gt2gssxrmig.html

Py:   raise ValueError("错误信息")
来源：http://dali.kuanghao11.cn/Article/details/gt2oqnuhikk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2yqcmtifb.html

JS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2gbihsmsp.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iyjwtqat.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2uunehrnm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guowangkeji.top/Article/details/gt2dbyimgrl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.snrcjt.cn/Article/details/gt2bayulsgt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2mnmjckbh.html

[H04] 自定义异常类型
来源：http://dali.yj20258.top/Article/details/gt2dileaqjh.html

Py:   class MyError(Exception): pass
来源：http://dali.nwbrower.top/Article/details/gt2pxlglvgr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gt2lqoekjcu.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gt2vlkrxgqw.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gt2kbsupsgw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gt2unhwzubg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ubpqooga.html

Ruby: class MyError < StandardError; end
来源：http://dali.ppjwa.cn/Article/details/gt2rcacsluw.html

C#:   class MyException : Exception {}
来源：http://dali.jianghu66.top/Article/details/gt2skdxeodu.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gt2hbjmgxfw.html

Py:   except ValueError as e:
来源：http://dali.hywenlv.cn/Article/details/gt2icprwzam.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.smart0.xyz/Article/details/gt2wwkdaxri.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2lgfvnwgn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gt2lrfwrgfc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.iojbl.cn/Article/details/gt2ahixzvkn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenzaomai.com/Article/details/gt2hthbxbod.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gt2hndlqxsj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gt2poenavpl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xylfe.cn/Article/details/gt2riuddxpa.html

Py:   value = d.get("k") or default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwsdxtbv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gt2wdkcckue.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gt2hvsmbfkh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gt2fmsrbczp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj202588.top/Article/details/gt2lzhvhqhg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj202588.top/Article/details/gt2xxdmzjoq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daxiang520.top/Article/details/gt2ifehgxox.html

C#:   obj?.A?.B ?? default
来源：http://dali.cqqwz.cn/Article/details/gt2piynexfl.html

[H07] 断言
来源：http://dali.yongpay.top/Article/details/gt2mhwfohqo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yonumen.top/Article/details/gt2wcdnnfxf.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2ahbamvgr.html

JS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2wjcpupeq.html

TS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gt2qrmppsqv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.svipenyu.cn/Article/details/gt2kyqjdsep.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jlsjyb.cn/Article/details/gt2qhnvzhzu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuetiantiany.cn/Article/details/gt2gemeohuk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2fohrpeym.html

[H08] 获取错误信息与堆栈
来源：http://dali.snrcjt.cn/Article/details/gt2jyzotwoq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hysaishi.cn/Article/details/gt2xfxekptj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cashguo.top/Article/details/gt2pblexxkf.html

JS:   e.message;  e.stack
来源：http://dali.redwolf501.top/Article/details/gt2lpxcryvw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zdqjudy.top/Article/details/gt2jfctiauo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.vqdsnc.cn/Article/details/gt2zvzxwavu.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gt2ghpdivmm.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhiwuduotai.top/Article/details/gt2jqzfmklm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxinkj.top/Article/details/gt2kybmcisa.html

[H09] 带错误码的异常
来源：http://dali.c1oappe.top/Article/details/gt2tudqxapz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hammf.cn/Article/details/gt2bdalvinf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258888.top/Article/details/gt2qyztfudz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yanxiufei.cn/Article/details/gt2nqyzxotr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhongyouzk.top/Article/details/gt2sdpnlvil.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xuanzx.com/Article/details/gt2kjdxtnep.html


<!-- 参考信息 -->