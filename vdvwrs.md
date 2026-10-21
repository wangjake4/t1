代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtxtwwsptn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.svipenyu.cn/Article/details/gteuzysxzc.html

PHP:  file_exists("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtnmgybtac.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtrbmnzuez.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtweekubuw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtseqlucju.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guowangkeji.top/Article/details/gtgxqkjqph.html

Ruby: File.exist?("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtpowwnzyg.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gthwfazenl.html

[F06] 删除文件
来源：http://dali.jlsjyb.cn/Article/details/gtwlbnmtwg.html

Py:   os.remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtwacleuuw.html

PHP:  unlink("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtyzpjwzrq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtkslbwwuk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtprkfaray.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtpdhypflv.html

Go:   os.Remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtoqpkupov.html

Ruby: File.delete("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtszsnlfar.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtvsyrjdtj.html

[F07] 创建目录（含多级）
来源：http://dali.yueranfly.top/Article/details/gtwohqljue.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.kuanghao11.cn/Article/details/gtyomactvb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtqlfawyca.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gttjyidegf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtphiddhqe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daxiang520.top/Article/details/gtplorblis.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoocumxre.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gtkovodlil.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guannengcc.top/Article/details/gtrzywqgce.html

[F08] 遍历目录
来源：http://dali.dianchejie.cn/Article/details/gtzdlkljul.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nwbrower.top/Article/details/gtzvmijrcj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenzaomai.com/Article/details/gtsdnnuzfy.html

JS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gtvafethmw.html

TS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtgxrujizf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gtoepqbgnd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aibaodan.cn/Article/details/gtoidlabfn.html

Ruby: Dir.children("dir")
来源：http://dali.zhixingplan.top/Article/details/gtaagohlik.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenzaomai.com/Article/details/gtijoqtfjj.html

[F09] 获取文件大小
来源：http://dali.bjfxy.top/Article/details/gttxezhizc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ivvv.top/Article/details/gtwfabtjem.html

PHP:  filesize("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtezptspkd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gtkmcgyqtu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtzatuhsyq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gttqzpbgza.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtavzofsjn.html

Ruby: File.size("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtgaukixji.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cqqwz.cn/Article/details/gtrebuhpsn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangshuangyany.cn/Article/details/gtugxnhlxn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtkhgdvvgf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ybcxt.top/Article/details/gtedixedjm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtelpqurdt.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtwivswxaw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tian-w.cn/Article/details/gtyoxqkswc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtjerxbigw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtmyviuozh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gthnftjome.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gtsecbtmtw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtwwnvahfy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gtsrkzmbln.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtqsavnadj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtjgiewido.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gticayfdyv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gttsqteezg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtepntyrzf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yvedp.cn/Article/details/gtlqcsfaoq.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gtrxkiphkm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gtkbnflvgi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.0kj1m.cn/Article/details/gtpbyghelc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gtpgucmphk.html

TS:   // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehwjdnvr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.havefunace.top/Article/details/gtfhzeqhhg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gtoidibrll.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yonumen.top/Article/details/gtckdunrhn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.9152youxi.cn/Article/details/gtlkqgbchf.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtmspggwic.html

G. 面向对象
来源：http://dali.kuanghao11.cn/Article/details/gtaczwlbsq.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtnqymhfgn.html

[G01] 定义类
来源：http://dali.zhengqikj.top/Article/details/gtfviwimkh.html

Py:   class User: pass
来源：http://dali.zycfv.cn/Article/details/gttyojwfbk.html

PHP:  class User {}
来源：http://dali.haohaochexian.top/Article/details/gtydhznobr.html

JS:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtmywwpokx.html

TS:   class User { name: string = ""; }
来源：http://dali.jyoumei.cn/Article/details/gtbgnmjzpc.html

Java: class User {}
来源：http://dali.havefunace.top/Article/details/gtxpvduwol.html

Go:   type User struct { Name string }
来源：http://dali.yuanzhike.top/Article/details/gtualhwjhy.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gtwrpjotve.html

C#:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gtdbojcdsd.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gtuvoeuhmc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ydzc1.top/Article/details/gtmsgzynjg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gtxrdmftay.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtnllmpvcz.html

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gtgagwdhcm.html

Java: User(String name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtgwxygywt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.havefunace.top/Article/details/gtfkcbropo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.feifeiyinyue.top/Article/details/gttrigiquw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj202588.top/Article/details/gtpovmtpxx.html

[G03] 实例属性
来源：http://dali.ydzc1.top/Article/details/gtdxepijpg.html

Py:   self.name = "x"
来源：http://dali.gzhubu.top/Article/details/gtofirgcxp.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gtiglmrzjv.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivyzsskh.html

TS:   name: string = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtacdqdddz.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gtyoafxwtv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqccufip.html

Ruby: @name = "x"
来源：http://dali.pycfn.com/Article/details/gtnpesaumy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jiagoushi.top/Article/details/gtowbwanuz.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gtllgkofvc.html

Py:   def greet(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqhkcydf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gtdzywcgxu.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtucusmqhw.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsmvzmir.html

Java: String greet() { return name; }
来源：http://dali.yonumen.top/Article/details/gtuqvfleys.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtpxrhtonp.html

Ruby: def greet; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdoqbktg.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gtxnwqoakr.html

[G05] 继承
来源：http://dali.cqqwz.cn/Article/details/gtxvbwmfve.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gtjdkbkuam.html

PHP:  class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtlhsxdyvt.html

JS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtoohbffbb.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtmseemvag.html

Java: class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtmhkyfzwz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nwbrower.top/Article/details/gtxeqfcneg.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gtoghjbiqp.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gtgetqqrxo.html

[G06] 重写方法
来源：http://dali.kuanghao11.cn/Article/details/gtjrolbnqd.html

Py:   def greet(self): return "admin"
来源：http://dali.haohaochexian.top/Article/details/gtedxphhnb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtnwmewrjv.html

JS:   greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtumgrskgb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtvwmzuujl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtarxettgu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangshuangyany.cn/Article/details/gtfzomrchi.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxuanxn.top/Article/details/gtwrpfhwby.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuanzhike.top/Article/details/gtauwiuoof.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gtovuqugbb.html

Py:   super().greet()
来源：http://dali.vqdsnc.cn/Article/details/gtbokncjgs.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gtjocinqcc.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtmwuhhhuk.html

TS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gttqbtnhhk.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gttbuxsdup.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ppjwa.cn/Article/details/gtdebznqer.html

Ruby: super
来源：http://dali.fengsongda.top/Article/details/gtmyvxpnrg.html

C#:   base.Greet();
来源：http://dali.wangdashe.top/Article/details/gthiuvxfjp.html

[G08] 静态方法与属性
来源：http://dali.shuidangran.top/Article/details/gtvorvxpqy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tianlin.xyz/Article/details/gtayimypsh.html

PHP:  public static function f() {}
来源：http://dali.hysaishi.cn/Article/details/gtlterhwjf.html

JS:   static f() {}
来源：http://dali.316326.xyz/Article/details/gtyxjdagnk.html

TS:   static f(): void {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkdawcvd.html

Java: static void f() {}
来源：http://dali.andypj.xyz/Article/details/gtwgkmnmfh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gtzlsksbbb.html

Ruby: def self.f; end
来源：http://dali.zhixingplan.top/Article/details/gtvdrqeesv.html

C#:   public static void F() {}
来源：http://dali.cheryme.top/Article/details/gtegwbenhh.html

[G09] 接口 / 抽象类
来源：http://dali.shuidangran.top/Article/details/gtbiykzmhr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yvedp.cn/Article/details/gtrflmrdyu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdncmmirh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigfzy.top/Article/details/gtafzjwikg.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj202588.top/Article/details/gtmccjalhp.html

Java: interface Shape { double area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtpjcxztbo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktnlalcg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shangyingyoupin.top/Article/details/gtekhcrbrt.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhoulong.xyz/Article/details/gtjhfxwmmv.html

[G10] 访问控制
来源：http://dali.hysaishi.cn/Article/details/gtyrjywowi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gtpzcqptyg.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzhyjbmc.html

JS:   #private 字段；其余公开
来源：http://dali.zhixingplan.top/Article/details/gtpfzkjyos.html

TS:   public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtgtknpqvx.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gtqpfyfltx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenlongwang.top/Article/details/gtvjhtydwy.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtwefksxlq.html

C#:   public / protected / private / internal
来源：http://dali.nwbrower.top/Article/details/gtleiurwas.html

[G11] getter / setter
来源：http://dali.quarkkingdee.top/Article/details/gtqbkoccvz.html

Py:   @property 与 @x.setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrktebdmk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtdqjwnpeh.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gttyqaagym.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtfyllzsrr.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtslphxwzs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtxdcqlxbj.html

Ruby: attr_accessor :name
来源：http://dali.iojbl.cn/Article/details/gtjjzazkcn.html

C#:   public string Name { get; set; }
来源：http://dali.zhengqikj.top/Article/details/gtehzpjlge.html

[G12] 对象转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtnmiglwbj.html

Py:   def __str__(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtpuvtiezd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtihurocum.html

JS:   toString() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtktmfxkgp.html

TS:   toString(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtwrwspaxh.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtaojgaceq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtwhyvoqqh.html

Ruby: def to_s; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtsuxdmpcw.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gttcqubdav.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwiqlxzt.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gtwslybovo.html

PHP:  $u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtolzjlisi.html

JS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtiqydclyu.html

TS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gtlaryvdsc.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtzhodymru.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangshuangyany.cn/Article/details/gteqnhnyuj.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gtphmuatho.html

C#:   u is User
来源：http://dali.zhixingplan.top/Article/details/gtqhpbztsl.html

[G14] 数据类 / record
来源：http://dali.smart0.xyz/Article/details/gtkdgjtgmz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258.top/Article/details/gtevcbiylf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hfpthk.cn/Article/details/gtbvwoplgf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gaohongyu789.top/Article/details/gthmnwflxv.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gtggbdrngh.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gtpcemniog.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ydzc1.top/Article/details/gtwkvquaiy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gtujxviblv.html

C#:   record User(string Name, int Age);
来源：http://dali.hnqzz.top/Article/details/gtvtzogang.html

[G15] 枚举
来源：http://dali.yueranfly.top/Article/details/gtqckzloka.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daxiang520.top/Article/details/gtqcyhjfns.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xinyue.icu/Article/details/gtxovblmyb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tanke756.top/Article/details/gtcrfymhmd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtwlnadqcf.html

Java: enum Color { RED, GREEN }
来源：http://dali.quarkkingdee.top/Article/details/gtyioaswfp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yvedp.cn/Article/details/gtidnnzdep.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fengsongda.top/Article/details/gtkxsokwzs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gtpzxdjyaq.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gtiiprmgho.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gtumvvxtuz.html

PHP:  get_object_vars($obj);
来源：http://dali.dianchejie.cn/Article/details/gtjilgfplq.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gteefyzwfv.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtulbbvcot.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.quarkkingdee.top/Article/details/gtenrwrfvn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.mhx1999.top/Article/details/gtiuxgldtk.html

Ruby: obj.instance_variables
来源：http://dali.chenzaomai.com/Article/details/gtecrhbkvz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gtsfrlfwwo.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtyunrzxps.html

H. 异常与错误处理
来源：http://dali.jinqigufen.top/Article/details/gtfqlpnnuv.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtjjxakmpg.html

[H01] try / catch 基础
来源：http://dali.hysaishi.cn/Article/details/gtlclulcyk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gtjyjgrzya.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pycfn.com/Article/details/gtqpsvrclb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gtjlnbhuej.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtfkebyxrk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuetiantiany.cn/Article/details/gteatlawbg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gogol.net.cn/Article/details/gtmpixjreo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jyoumei.cn/Article/details/gtvswyahhk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gtubdffijp.html

[H02] finally / ensure 收尾
来源：http://dali.zhoulong.xyz/Article/details/gtdwvuczrl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shuidangran.top/Article/details/gtrycmorru.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtkrvtayzt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtagkwndce.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtdyhanygw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnleqpjc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cucudq.cn/Article/details/gtasbadjfo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hysaishi.cn/Article/details/gtobglgams.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtaigjkezf.html

[H03] 主动抛出异常
来源：http://dali.ppjwa.cn/Article/details/gtmalfnklv.html

Py:   raise ValueError("错误信息")
来源：http://dali.feifeiyinyue.top/Article/details/gtzgkyouhm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtwvtgupya.html

JS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtndmjpcwk.html

TS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtijstfjxq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtqhypegpa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gtmdtygwss.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gtzeqmsdce.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtosbhiity.html

[H04] 自定义异常类型
来源：http://dali.tian-w.cn/Article/details/gtjsaforns.html

Py:   class MyError(Exception): pass
来源：http://dali.jianghu66.top/Article/details/gthoqccaiq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gtkyqirypj.html

JS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gthxncugxu.html

TS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gtkkfjtnoh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gtcoovnlgn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gtmvegvroq.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gtxxlbdwoz.html

C#:   class MyException : Exception {}
来源：http://dali.quarkkingdee.top/Article/details/gtkkvwpmqx.html

[H05] 捕获特定类型
来源：http://dali.wangshuangyany.cn/Article/details/gtcbtcjwkl.html

Py:   except ValueError as e:
来源：http://dali.feifeiyinyue.top/Article/details/gtgvoimkfa.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gzhubu.top/Article/details/gtepjfmuur.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gtcpiaittd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gthtacxbki.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlqkxykr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhixingplan.top/Article/details/gtzdduakmr.html

Ruby: rescue ArgumentError => e
来源：http://dali.svipenyu.cn/Article/details/gtjticxyus.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yanxiufei.cn/Article/details/gtponlpeoy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xinyue.icu/Article/details/gtamakbltr.html

Py:   value = d.get("k") or default
来源：http://dali.xziqi.cn/Article/details/gtstbwgbrd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gthpzxunkc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjiqehvx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtklgatxsi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorqodlpz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hywenlv.cn/Article/details/gtfwbpdmlz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gtubdkfsbp.html

C#:   obj?.A?.B ?? default
来源：http://dali.hfpthk.cn/Article/details/gtgxwkwieo.html

[H07] 断言
来源：http://dali.sxryk.cn/Article/details/gtfahfkqgq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guannengcc.top/Article/details/gtshheylau.html

PHP:  assert($x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtthcqnlzy.html

JS:   console.assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtxtediphp.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtqajkfkvb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.feifeiyinyue.top/Article/details/gtiyjdwdra.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbtipjgf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.iojbl.cn/Article/details/gtdcafdisf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtyrphtcdr.html

[H08] 获取错误信息与堆栈
来源：http://dali.tanke756.top/Article/details/gtougxnclm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sufxvd.cn/Article/details/gtqxtvzqut.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.bjfxy.top/Article/details/gtiwwghjlh.html

JS:   e.message;  e.stack
来源：http://dali.guannengcc.top/Article/details/gtgaorbqkw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpfnjmma.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.havefunace.top/Article/details/gtdvtinpdk.html

Go:   err.Error()
来源：http://dali.jlsjyb.cn/Article/details/gtvugpmpgo.html

Ruby: e.message;  e.backtrace
来源：http://dali.yonumen.top/Article/details/gtwcbcanov.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gtmzqfxjuh.html

[H09] 带错误码的异常
来源：http://dali.yonumen.top/Article/details/gtqyiarauj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daxiang520.top/Article/details/gthrqtgwpf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jianghu66.top/Article/details/gtrgkotrwu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gtuljukfov.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pengpengdd.cyou/Article/details/gtdrtotdjs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.havefunace.top/Article/details/gtxifrcyui.html


<!-- 参考信息 -->