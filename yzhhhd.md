代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2uzxksrpy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cucudq.cn/Article/details/gt2posdouuk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2tveakies.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2gvhyinhg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.mhx1999.top/Article/details/gt2yovhjlrf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gt2zzfkxrfe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gotoacloud.top/Article/details/gt2rmgssduq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tian-w.cn/Article/details/gt2xmmiqwbq.html

[F05] 判断文件或目录是否存在
来源：http://dali.jyoumei.cn/Article/details/gt2xsgdskas.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jlsjyb.cn/Article/details/gt2uyqzrmxj.html

PHP:  file_exists("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2aepnnkba.html

JS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2tojzgqaw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2hesrkuso.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2iqzzmyqr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cdnleiting.top/Article/details/gt2xuhisazo.html

Ruby: File.exist?("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jusemneg.html

C#:   File.Exists("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2seoaxmeg.html

[F06] 删除文件
来源：http://dali.yongpay.top/Article/details/gt2ttztiego.html

Py:   os.remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2rzbisgac.html

PHP:  unlink("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2ixhhqatm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2hjgamrtu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jzplmwuw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2vtbpokry.html

Go:   os.Remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vfwmeojj.html

Ruby: File.delete("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2wcmziakt.html

C#:   File.Delete("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2hlwulvlb.html

[F07] 创建目录（含多级）
来源：http://dali.hammf.cn/Article/details/gt2dfecvqjf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gt2exahetjb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tian-w.cn/Article/details/gt2ldhtbwxo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gt2jzdofohg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gt2yiuwdpuj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ylkywyma.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ddvamtjj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hywenlv.cn/Article/details/gt2iywlrwws.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxqkwieq.html

[F08] 遍历目录
来源：http://dali.ppjwa.cn/Article/details/gt2wxkihjof.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gt2ahrcpsbi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangdashe.top/Article/details/gt2hxhfbgwm.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2xphwgqas.html

TS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gt2fyadmbof.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gt2bhppvfrk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2tueyrnyd.html

Ruby: Dir.children("dir")
来源：http://dali.redwolf501.top/Article/details/gt2ouvjmhzp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ybcxt.top/Article/details/gt2ekpoivsc.html

[F09] 获取文件大小
来源：http://dali.wangshuangyany.cn/Article/details/gt2trytkpql.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2ahnpltdw.html

PHP:  filesize("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jqvboaax.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gt2dexpmgan.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gt2bdqbijha.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rnedsjxp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cqqwz.cn/Article/details/gt2uwoqsgxs.html

Ruby: File.size("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2tcgwybrb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ppjwa.cn/Article/details/gt2xsmttmcd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.birdmap.top/Article/details/gt2plegofic.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vdcwxxjj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2xvctzcdm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2tsbiiyjd.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2avjpaylr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gt2cledpnlw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2xvifipsl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2khgxzaqd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2tvknrmip.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gt2jkavjpzp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2zbkkjefn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2nqeivzxm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gt2xfrdcdju.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gevyaqad.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ptmtuqht.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aizwys.cn/Article/details/gt2tpnglell.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gt2feraggma.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ydzc1.top/Article/details/gt2gabrspst.html

[F12] CSV 读写
来源：http://dali.zhoulong.xyz/Article/details/gt2greqpqvd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gt2liladovl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gt2lhkrlrvb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cqqwz.cn/Article/details/gt2axsknyrj.html

TS:   // 同上
来源：http://dali.yanxiufei.cn/Article/details/gt2rrgobthi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dianchejie.cn/Article/details/gt2aeyafxrk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ehwqpu.com/Article/details/gt2qnwbykhd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shuidangran.top/Article/details/gt2srkghsso.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhongyouzk.top/Article/details/gt2fyktlich.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2mkiuawwb.html

G. 面向对象
来源：http://dali.hysaishi.cn/Article/details/gt2jaamwbay.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2yxxncmrn.html

[G01] 定义类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nidrzgvp.html

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gt2zrqzikyo.html

PHP:  class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2puhxkuoh.html

JS:   class User {}
来源：http://dali.guannengcc.top/Article/details/gt2rzbaonbx.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gt2hmfhjkqx.html

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2jztvgjgo.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gt2rvbjtqqi.html

Ruby: class User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iksdvbwm.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2nsmodoak.html

[G02] 构造函数
来源：http://dali.guowangkeji.top/Article/details/gt2ccxoltej.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cheryme.top/Article/details/gt2czlskmtc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2svuzrqni.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dxslnoet.html

TS:   constructor(public name: string) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2buspsjqb.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dcjumacb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuanzx.com/Article/details/gt2rrhlsmkp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.redwolf501.top/Article/details/gt2saagafyw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gt2zbgnkarf.html

[G03] 实例属性
来源：http://dali.zhixingplan.top/Article/details/gt2xwsuzcns.html

Py:   self.name = "x"
来源：http://dali.iojbl.cn/Article/details/gt2tnqjpeke.html

PHP:  public string $name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2nndezekx.html

JS:   this.name = "x";
来源：http://dali.jianghu66.top/Article/details/gt2dbmepgjw.html

TS:   name: string = "x";
来源：http://dali.zycfv.cn/Article/details/gt2nyogpuxm.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gt2feagfvaq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yongpay.top/Article/details/gt2ptfifjdg.html

Ruby: @name = "x"
来源：http://dali.hfpthk.cn/Article/details/gt2gdddzjwo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cashguo.top/Article/details/gt2yxzqtyrg.html

[G04] 定义方法
来源：http://dali.yonumen.top/Article/details/gt2sizwejhu.html

Py:   def greet(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gt2euihropz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2nenutoow.html

JS:   greet() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2edguekvt.html

TS:   greet(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2fqxfbvup.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2kfgmleke.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2rommfpmm.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gt2phfqrprz.html

C#:   public string Greet() => Name;
来源：http://dali.cashguo.top/Article/details/gt2dfesdwyn.html

[G05] 继承
来源：http://dali.wangdashe.top/Article/details/gt2tlgrvitp.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gt2ulncwjjj.html

PHP:  class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2vzeoexyw.html

JS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2tabffsjk.html

TS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gt2clzekgau.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2juardwpz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gt2vgolvmkl.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gt2opsdkpfu.html

C#:   class Admin : User {}
来源：http://dali.zhixingplan.top/Article/details/gt2nuplavqy.html

[G06] 重写方法
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ykzrlkdy.html

Py:   def greet(self): return "admin"
来源：http://dali.jlsjyb.cn/Article/details/gt2ggpfaqsf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2ubcruwiz.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2aypexnok.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2sgccthlt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2ncyvxevd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zdqjudy.top/Article/details/gt2tcubdsqr.html

Ruby: def greet; "admin"; end
来源：http://dali.quarkkingdee.top/Article/details/gt2mpvqmhyw.html

C#:   public override string Greet() => "admin";
来源：http://dali.c1oappe.top/Article/details/gt2vlmfmmnr.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gt2tjbscskd.html

Py:   super().greet()
来源：http://dali.yanxiufei.cn/Article/details/gt2xzexryek.html

PHP:  parent::greet();
来源：http://dali.hfpthk.cn/Article/details/gt2giwndvjk.html

JS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gt2whxwarsc.html

TS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynkltcrb.html

Java: super.greet();
来源：http://dali.zhixingplan.top/Article/details/gt2lzbpsolx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hammf.cn/Article/details/gt2qmkjlsok.html

Ruby: super
来源：http://dali.zdqjudy.top/Article/details/gt2otvgcoyy.html

C#:   base.Greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2isiudagm.html

[G08] 静态方法与属性
来源：http://dali.yuanzhike.top/Article/details/gt2fgiwnpmr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gt2rnsnajlc.html

PHP:  public static function f() {}
来源：http://dali.daria6918.cn/Article/details/gt2othgyfsu.html

JS:   static f() {}
来源：http://dali.316326.xyz/Article/details/gt2ffifmjli.html

TS:   static f(): void {}
来源：http://dali.dianchejie.cn/Article/details/gt2itcbekue.html

Java: static void f() {}
来源：http://dali.sxryk.cn/Article/details/gt2swksfkah.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cheryme.top/Article/details/gt2sestnogs.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gt2jgnymaym.html

C#:   public static void F() {}
来源：http://dali.ppjwa.cn/Article/details/gt2bhwpbqin.html

[G09] 接口 / 抽象类
来源：http://dali.gogol.net.cn/Article/details/gt2iwwajnvv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gt2brzvxzmf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gaohongyu789.top/Article/details/gt2tpnbgapl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shzxlz.cn/Article/details/gt2zzxvmyiq.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gt2tdvbmkxz.html

Java: interface Shape { double area(); }
来源：http://dali.chenlongwang.top/Article/details/gt2fxnjfdcj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dashuyun.cn/Article/details/gt2tzurgtsv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxuanxn.top/Article/details/gt2zyalcqss.html

C#:   interface IShape { double Area(); }
来源：http://dali.yonumen.top/Article/details/gt2wyxopblj.html

[G10] 访问控制
来源：http://dali.pycfn.com/Article/details/gt2djpmrgod.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gt2vxacxefu.html

PHP:  public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2jiykqjuc.html

JS:   #private 字段；其余公开
来源：http://dali.andypj.xyz/Article/details/gt2smjgokvx.html

TS:   public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2akmuuizj.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gt2lfokavsm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258888.top/Article/details/gt2ittyledj.html

Ruby: public / protected / private
来源：http://dali.wangdashe.top/Article/details/gt2veiwztiv.html

C#:   public / protected / private / internal
来源：http://dali.jyoumei.cn/Article/details/gt2llibjbbj.html

[G11] getter / setter
来源：http://dali.guowangkeji.top/Article/details/gt2aowfpuyx.html

Py:   @property 与 @x.setter
来源：http://dali.jqgufenzy.top/Article/details/gt2ffvbcecu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2gmzmtjyg.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gt2vxhepdht.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gt2kpjhsufi.html

Java: public String getName() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gt2htojgyvp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2jpkphgcm.html

Ruby: attr_accessor :name
来源：http://dali.yvedp.cn/Article/details/gt2lwaxtkwt.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gt2utzvbysn.html

[G12] 对象转字符串
来源：http://dali.daxiang520.top/Article/details/gt2prwktuft.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gt2jqepjage.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ebbpnpwa.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bhdqfxrd.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2pepraszh.html

Java: @Override public String toString() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tqgqxuuh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gt2rnvcaisa.html

Ruby: def to_s; @name; end
来源：http://dali.xylfe.cn/Article/details/gt2wsrhtxbx.html

C#:   public override string ToString() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2wkajcput.html

[G13] 判断对象类型
来源：http://dali.yj20258888.top/Article/details/gt2hvawvbbt.html

Py:   isinstance(u, User)
来源：http://dali.yvedp.cn/Article/details/gt2dtxftljq.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evtcacue.html

JS:   u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2bfohinat.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2eumwbjdx.html

Java: u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2jgkvrtlh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhongyouzk.top/Article/details/gt2cxcdahpt.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gt2gykjeccf.html

C#:   u is User
来源：http://dali.havefunace.top/Article/details/gt2avgvmytf.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gt2gjtcscsc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lherfhpv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shuidangran.top/Article/details/gt2tunqpaap.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258888.top/Article/details/gt2jagsdrgd.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxinkj.top/Article/details/gt2imrittmt.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gt2vvvovzqs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yonumen.top/Article/details/gt2idarttvz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zdqjudy.top/Article/details/gt2lwokptlq.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgfzy.top/Article/details/gt2uavhjbds.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2tyjhynfn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.vqdsnc.cn/Article/details/gt2rdvaeava.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.redwolf501.top/Article/details/gt2hlrizlzy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.quarkkingdee.top/Article/details/gt2kwoidsrn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gt2oofpfhgc.html

Java: enum Color { RED, GREEN }
来源：http://dali.iojbl.cn/Article/details/gt2ykdlbafj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjsbdsw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigufen.top/Article/details/gt2tgjgkhgu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gt2mpwrfiua.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gt2usupzsim.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tianlin.xyz/Article/details/gt2ketopcec.html

PHP:  get_object_vars($obj);
来源：http://dali.xylfe.cn/Article/details/gt2usuctlbg.html

JS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gt2qazggkkc.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2hihjywpa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.c1oappe.top/Article/details/gt2snxdqbbx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gt2omxtglye.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gt2migegfdd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gt2umagwqmv.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2npbikhvm.html

H. 异常与错误处理
来源：http://dali.jinqigufen.top/Article/details/gt2plshqaca.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2frvzjboy.html

[H01] try / catch 基础
来源：http://dali.cashguo.top/Article/details/gt2ktoiykfn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wgttovmq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.haohaochexian.top/Article/details/gt2xzcfgolt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gt2nwubncwr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gt2ytpafamz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.snrcjt.cn/Article/details/gt2feuvzkdr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shuidangran.top/Article/details/gt2wnhigiai.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sweek.top/Article/details/gt2qvowzktb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gt2ycrndtzm.html

[H02] finally / ensure 收尾
来源：http://dali.redwolf501.top/Article/details/gt2xvnfsmqt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daxiang520.top/Article/details/gt2mhpvriya.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2xrakqrkj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2varujujv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2jedmpdmt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mijbfdgq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hywenlv.cn/Article/details/gt2kbixsonu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fengsongda.top/Article/details/gt2onciugpg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ifzjovqr.html

[H03] 主动抛出异常
来源：http://dali.0kj1m.cn/Article/details/gt2mqnrmknd.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjbggiek.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2mwwerhkm.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2dslduelo.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2qknwjonb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2rzfsgzdw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gt2gpdsatuo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gt2kjthngjn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gt2pemwdgdi.html

[H04] 自定义异常类型
来源：http://dali.9152youxi.cn/Article/details/gt2nciqjocc.html

Py:   class MyError(Exception): pass
来源：http://dali.jyoumei.cn/Article/details/gt2wbbekovw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wexbmpcd.html

JS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gt2woizhzyl.html

TS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gt2qwoiitje.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gt2roexonxc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gaohongyu789.top/Article/details/gt2sgzvjqzw.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gt2dtqxlrqe.html

C#:   class MyException : Exception {}
来源：http://dali.0kj1m.cn/Article/details/gt2hwhpbdem.html

[H05] 捕获特定类型
来源：http://dali.wangdashe.top/Article/details/gt2uasjhkpi.html

Py:   except ValueError as e:
来源：http://dali.hysaishi.cn/Article/details/gt2jnspkrpd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sxryk.cn/Article/details/gt2uvwkypsi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2jcsrlexp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gt2sfhfzxzl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuanzhike.top/Article/details/gt2ayeqqumz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xylfe.cn/Article/details/gt2shshswco.html

Ruby: rescue ArgumentError => e
来源：http://dali.dianchejie.cn/Article/details/gt2kybvwvxq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.c1oappe.top/Article/details/gt2jordeepz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxuanxn.top/Article/details/gt2esfwohzk.html

Py:   value = d.get("k") or default
来源：http://dali.zycfv.cn/Article/details/gt2srddgdua.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gt2nfpxlryl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gt2ufsgmrbi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gt2eyodglni.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yueranfly.top/Article/details/gt2ttdcnpiy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yangfankeji.com/Article/details/gt2qpebnwns.html

Ruby: d&.dig(:a, :b)
来源：http://dali.c1oappe.top/Article/details/gt2huymepus.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gt2xglasvqp.html

[H07] 断言
来源：http://dali.nanxuanxn.top/Article/details/gt2bocgwgcz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjvlklmf.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gt2tdjuelhe.html

JS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2rxsousuk.html

TS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2oeebiukj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuanzhike.top/Article/details/gt2fdmnfycx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zycfv.cn/Article/details/gt2jamjuulb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuetiantiany.cn/Article/details/gt2mutulevp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2oljaheni.html

[H08] 获取错误信息与堆栈
来源：http://dali.yvedp.cn/Article/details/gt2gaequsnw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj202588.top/Article/details/gt2dmafgbem.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cqqwz.cn/Article/details/gt2lexpkcqa.html

JS:   e.message;  e.stack
来源：http://dali.smart0.xyz/Article/details/gt2ftsxmvqe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shzxlz.cn/Article/details/gt2xyukhkjf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gt2ikintjkx.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gt2rmnceens.html


<!-- 参考信息 -->