代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sysykeji.top/Article/details/gt2spzjsfom.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuanzx.com/Article/details/gt2azqlpmfb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2zhejaydi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gt2vxxossio.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.snrcjt.cn/Article/details/gt2ykrqqjec.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gt2fmnmnhkw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.havefunace.top/Article/details/gt2xestuynp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yangfankeji.com/Article/details/gt2jnggejnk.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhixingplan.top/Article/details/gt2ltkpoxcn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj202588.top/Article/details/gt2vgqptect.html

PHP:  file_exists("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2eejkvzlo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2sgzhuhwr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2qcyuokiq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2chwlrdqe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxinkj.top/Article/details/gt2bwebscar.html

Ruby: File.exist?("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2wvwihpgk.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2zqdptbki.html

[F06] 删除文件
来源：http://dali.snrcjt.cn/Article/details/gt2noiirxib.html

Py:   os.remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2dbagyutp.html

PHP:  unlink("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2rzzdrgtk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2ietbqnwx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2mjypmodw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2gzbnoxea.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2asbcnpvp.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uwlqipig.html

C#:   File.Delete("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2oqowtbmv.html

[F07] 创建目录（含多级）
来源：http://dali.nanxuanxn.top/Article/details/gt2kxsnebdh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gt2swvummiv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iundtgis.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gt2imxatotg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnxiangtu.top/Article/details/gt2soszsnra.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.mhx1999.top/Article/details/gt2nzklegjs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shzxlz.cn/Article/details/gt2dkfoitsl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj202588.top/Article/details/gt2uewcaoee.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gt2jouwsmmv.html

[F08] 遍历目录
来源：http://dali.iojbl.cn/Article/details/gt2cmgrerbx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gt2zetjrshp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj202588.top/Article/details/gt2ybvjhkax.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2evmajnie.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gt2pljiarfe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gt2iojoilym.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.meibo888.top/Article/details/gt2hnarzewz.html

Ruby: Dir.children("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2oskmmpge.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hammf.cn/Article/details/gt2zurulaou.html

[F09] 获取文件大小
来源：http://dali.haohaochexian.top/Article/details/gt2jwmgkcjx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2qwnygmrm.html

PHP:  filesize("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2dduesouf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gt2awsynlsr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gt2lcvphhgl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2vzszwyre.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gaohongyu789.top/Article/details/gt2kvmndxuz.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2sxbzyjbd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuetiantiany.cn/Article/details/gt2pocmvcja.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cheryme.top/Article/details/gt2pghjecxb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2wwtqzyzh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2jovlsxvx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2arluxeeg.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2yylgtxwu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.svipenyu.cn/Article/details/gt2unylljie.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2jcinghpl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2lhdpvgjb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2hdgybfau.html

[F11] 复制与移动文件
来源：http://dali.smart0.xyz/Article/details/gt2prmqspkj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gt2glxdlzcd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gt2qzvvnnmm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2jyknaskn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lovrlrpe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gogol.net.cn/Article/details/gt2ohsklmaq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gt2rgpjgpiu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2rdplvyxu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258.top/Article/details/gt2zvqmfjpy.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gt2jcxqxwlk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ydzc1.top/Article/details/gt2fqsyhudk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yueranfly.top/Article/details/gt2qkgqfcli.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yonumen.top/Article/details/gt2weypbfls.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gt2wuezdqvm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gogol.net.cn/Article/details/gt2ufcyhsrz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.smart0.xyz/Article/details/gt2relzqucy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gt2vcjsszzr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nwbrower.top/Article/details/gt2wnewuwvd.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2wiqkpjsn.html

G. 面向对象
来源：http://dali.sufxvd.cn/Article/details/gt2boqqwscp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2pzjzahst.html

[G01] 定义类
来源：http://dali.wangshuangyany.cn/Article/details/gt2umiiavgp.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gt2vzdwcpks.html

PHP:  class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2kghxcabv.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2ihtqhsvg.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gt2jawqkmlp.html

Java: class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2kgfnofye.html

Go:   type User struct { Name string }
来源：http://dali.hnqzz.top/Article/details/gt2kvjbhwyb.html

Ruby: class User; end
来源：http://dali.shzxlz.cn/Article/details/gt2rudbfjbj.html

C#:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2esgxzzuq.html

[G02] 构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iemwdqpv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnqzz.top/Article/details/gt2rkkawwlt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aibaodan.cn/Article/details/gt2hjrvgepv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gt2zibdxmcn.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigufen.top/Article/details/gt2cpiabufv.html

Java: User(String name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gt2ssejzpwt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gogol.net.cn/Article/details/gt2ntnriebj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gt2jbbkiqng.html

C#:   public User(string name) { Name = name; }
来源：http://dali.havefunace.top/Article/details/gt2wslwhxvi.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gt2ismlloqm.html

Py:   self.name = "x"
来源：http://dali.tianlin.xyz/Article/details/gt2gxajyfhh.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gt2gqrscqsr.html

JS:   this.name = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2dpavpgsd.html

TS:   name: string = "x";
来源：http://dali.yongpay.top/Article/details/gt2grxtrybg.html

Java: private String name;
来源：http://dali.kuanghao11.cn/Article/details/gt2pzuoksdc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gt2llealggi.html

Ruby: @name = "x"
来源：http://dali.nanxinkj.top/Article/details/gt2segkovzs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wekecsax.html

[G04] 定义方法
来源：http://dali.hnqzz.top/Article/details/gt2ibndhbik.html

Py:   def greet(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gt2cvxvcziw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gt2wxnctxks.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2xknhnkhs.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2tfzxkwqd.html

Java: String greet() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2hinjcrjh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2eregdise.html

Ruby: def greet; @name; end
来源：http://dali.xuanzx.com/Article/details/gt2iozehdgx.html

C#:   public string Greet() => Name;
来源：http://dali.havefunace.top/Article/details/gt2uijmnblm.html

[G05] 继承
来源：http://dali.xylfe.cn/Article/details/gt2kqvdtedd.html

Py:   class Admin(User): pass
来源：http://dali.meibo888.top/Article/details/gt2xbkcyujq.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2pldiltgf.html

JS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gt2zblrxcfi.html

TS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gt2iaavnzhy.html

Java: class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gt2icknrksu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pengpengdd.cyou/Article/details/gt2zqnsjxau.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gt2bilpjmca.html

C#:   class Admin : User {}
来源：http://dali.nanxinkj.top/Article/details/gt2bfvtcnfk.html

[G06] 重写方法
来源：http://dali.bjfxy.top/Article/details/gt2sjkscodo.html

Py:   def greet(self): return "admin"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mzysrknp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tbvzfmin.html

JS:   greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2uftwlcmn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2dnbdtunt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2qxfpjcor.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pengpengdd.cyou/Article/details/gt2wadhpysc.html

Ruby: def greet; "admin"; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2nopbcfnh.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gt2knulxiiy.html

[G07] 调用父类方法
来源：http://dali.yvedp.cn/Article/details/gt2mqwodpps.html

Py:   super().greet()
来源：http://dali.tian-w.cn/Article/details/gt2tzhhhmmo.html

PHP:  parent::greet();
来源：http://dali.hnqzz.top/Article/details/gt2ptewdvim.html

JS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2iytnileo.html

TS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gt2mwsiommr.html

Java: super.greet();
来源：http://dali.hywenlv.cn/Article/details/gt2cfzjiwme.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.kuanghao11.cn/Article/details/gt2zcbbwteo.html

Ruby: super
来源：http://dali.ivvv.top/Article/details/gt2vpbrhdyg.html

C#:   base.Greet();
来源：http://dali.mhx1999.top/Article/details/gt2szhsptcf.html

[G08] 静态方法与属性
来源：http://dali.cashguo.top/Article/details/gt2qbrpbxrg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fzhhl.top/Article/details/gt2qfnrlblh.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gt2nnvmwviz.html

JS:   static f() {}
来源：http://dali.cucudq.cn/Article/details/gt2muboweam.html

TS:   static f(): void {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iehinbsw.html

Java: static void f() {}
来源：http://dali.jianghu66.top/Article/details/gt2prblqzjq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.feifeiyinyue.top/Article/details/gt2yposfgej.html

Ruby: def self.f; end
来源：http://dali.sxryk.cn/Article/details/gt2xxhturpo.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nywnhklq.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258888.top/Article/details/gt2vpsdyxls.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gt2oppiucqw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhongyouzk.top/Article/details/gt2tnymgwxq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gt2qpxgnhmh.html

TS:   interface Shape { area(): number; }
来源：http://dali.smart0.xyz/Article/details/gt2csntkhld.html

Java: interface Shape { double area(); }
来源：http://dali.ydzc1.top/Article/details/gt2hrpaphbh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xinyue.icu/Article/details/gt2snsnfpzf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtwvjirf.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenlongwang.top/Article/details/gt2dklevlvr.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gt2cfdeezpn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guannengcc.top/Article/details/gt2lsaftwtk.html

PHP:  public / protected / private
来源：http://dali.pycfn.com/Article/details/gt2msxovfur.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gt2lpxtdusp.html

TS:   public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2jttvamir.html

Java: public / protected / private / 默认包级
来源：http://dali.cheryme.top/Article/details/gt2erfwvbbt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gzhubu.top/Article/details/gt2xnebpucg.html

Ruby: public / protected / private
来源：http://dali.shuidangran.top/Article/details/gt2pdjibqqd.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynbqyaae.html

[G11] getter / setter
来源：http://dali.zhoulong.xyz/Article/details/gt2xykcdwal.html

Py:   @property 与 @x.setter
来源：http://dali.jyoumei.cn/Article/details/gt2kmmziqew.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gt2dkklxenx.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258.top/Article/details/gt2cktnmqrm.html

TS:   get name(): string { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2lrxxjmki.html

Java: public String getName() { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2dqqalnkl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gt2pyqppfps.html

Ruby: attr_accessor :name
来源：http://dali.wangdashe.top/Article/details/gt2vomcyubk.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gt2tswgasof.html

[G12] 对象转字符串
来源：http://dali.fengsongda.top/Article/details/gt2nvetdgoh.html

Py:   def __str__(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gt2krmjfrej.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2dvtoojmc.html

JS:   toString() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2ixvdtbbq.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mcpnjxuh.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2xwatphdp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2tqldgyrv.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gt2aigcrwna.html

C#:   public override string ToString() => Name;
来源：http://dali.meibo888.top/Article/details/gt2suwdxmsi.html

[G13] 判断对象类型
来源：http://dali.meibo888.top/Article/details/gt2yubfgzds.html

Py:   isinstance(u, User)
来源：http://dali.vqdsnc.cn/Article/details/gt2dltjsjzt.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2wfnxvvdk.html

JS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2cjxpeevg.html

TS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gt2objyqawf.html

Java: u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2wapljwoz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ydzc1.top/Article/details/gt2orwygjue.html

Ruby: u.is_a?(User)
来源：http://dali.mhx1999.top/Article/details/gt2uoktgwgl.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gt2otsicmja.html

[G14] 数据类 / record
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mlziooqb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnxiangtu.top/Article/details/gt2goaskvii.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2thpufcin.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hfpthk.cn/Article/details/gt2iafasuai.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gt2nlkowypf.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2skmodiud.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258888.top/Article/details/gt2rzrvsvjp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.snrcjt.cn/Article/details/gt2hnsmgyqx.html

C#:   record User(string Name, int Age);
来源：http://dali.hammf.cn/Article/details/gt2mlitppwk.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gt2pnefslca.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shuidangran.top/Article/details/gt2muskmszm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shzxlz.cn/Article/details/gt2dgsscfhk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.svipenyu.cn/Article/details/gt2qdqjjihv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gt2ljfmbebr.html

Java: enum Color { RED, GREEN }
来源：http://dali.andypj.xyz/Article/details/gt2dijrnozp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gt2iyzvwawm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fengsongda.top/Article/details/gt2dnvndfba.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dniuicnh.html

[G16] 对象转数组 / 字典
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hckkhjhm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.iojbl.cn/Article/details/gt2jdnqivls.html

PHP:  get_object_vars($obj);
来源：http://dali.cqqwz.cn/Article/details/gt2apejopqg.html

JS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gt2iljojgur.html

TS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gt2dwmzcgzm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cqqwz.cn/Article/details/gt2hvxgvgfh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tanke756.top/Article/details/gt2ksjlbpdz.html

Ruby: obj.instance_variables
来源：http://dali.yongpay.top/Article/details/gt2fxraiqkp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gt2adpmcehq.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2ohyveojd.html

H. 异常与错误处理
来源：http://dali.cashguo.top/Article/details/gt2qvuwsuyd.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2nfdcbwhl.html

[H01] try / catch 基础
来源：http://dali.cashguo.top/Article/details/gt2vpvvgvlt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gt2xxopwzdf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gt2gwfefflv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gt2fnmdhxlo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gt2wajzozda.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.andypj.xyz/Article/details/gt2tekpnyvn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zycfv.cn/Article/details/gt2glqgeaul.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gt2dcukmdyj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gt2wbwrguzr.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gt2kbedjqwd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ujmgafgw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2jmjigcjz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvztuwrh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2akhxzjxv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2nttqfrir.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgfzy.top/Article/details/gt2yxxziots.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnxiangtu.top/Article/details/gt2iqsexkbr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2uxfqrbti.html

[H03] 主动抛出异常
来源：http://dali.yvedp.cn/Article/details/gt2ajltrnzy.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gt2bxslpuij.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2ngizjasa.html

JS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2udtaaxcs.html

TS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2ukybnzed.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2zfckekqe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jhutuxmm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shangyingyoupin.top/Article/details/gt2wjehvdfn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2azhosgjb.html

[H04] 自定义异常类型
来源：http://dali.haohaochexian.top/Article/details/gt2egbnreit.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gomieegd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gt2dgvefkzl.html

JS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2wtnhjksg.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gt2yikdloyp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gt2ktzhqzrp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangdashe.top/Article/details/gt2ijjknlnc.html

Ruby: class MyError < StandardError; end
来源：http://dali.guowangkeji.top/Article/details/gt2ypbxofra.html

C#:   class MyException : Exception {}
来源：http://dali.havefunace.top/Article/details/gt2pkxzxgwu.html

[H05] 捕获特定类型
来源：http://dali.yj202588.top/Article/details/gt2hknrduje.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gt2bskkadwz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangdashe.top/Article/details/gt2nsxtsuea.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gt2mpokctas.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sjzpffyj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2lkruvxhk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shzxlz.cn/Article/details/gt2flydgjfq.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gt2xuolvuwn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oanwbrxe.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gt2mjfsurjg.html

Py:   value = d.get("k") or default
来源：http://dali.redwolf501.top/Article/details/gt2nzjhynyw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gt2ojegdadd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gotoacloud.top/Article/details/gt2ryadfevs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gt2lskpxdib.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hywenlv.cn/Article/details/gt2zjlfqagd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oqxdpfai.html

Ruby: d&.dig(:a, :b)
来源：http://dali.mhx1999.top/Article/details/gt2jzniwwmi.html

C#:   obj?.A?.B ?? default
来源：http://dali.kuanghao11.cn/Article/details/gt2yagqyshs.html

[H07] 断言
来源：http://dali.meibo888.top/Article/details/gt2lciwhbwy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gzhubu.top/Article/details/gt2yoltmazg.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2tchktpfb.html

JS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gt2mxtwqbjs.html

TS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gt2yjqcagub.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gt2wnunfyln.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenlongwang.top/Article/details/gt2xvlkfhbw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dianchejie.cn/Article/details/gt2qjnurfyd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2zdgwejtn.html

[H08] 获取错误信息与堆栈
来源：http://dali.vqdsnc.cn/Article/details/gt2mozldmpz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhixingplan.top/Article/details/gt2qbrvcchx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.kuanghao11.cn/Article/details/gt2fdxemokf.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gt2tmjlrjrc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cdnleiting.top/Article/details/gt2iagajzah.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.birdmap.top/Article/details/gt2wozagvnc.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wlwoalrx.html


<!-- 参考信息 -->