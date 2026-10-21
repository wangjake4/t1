代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gtartrauas.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtcxidgijc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtijqwozge.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jyoumei.cn/Article/details/gtnypaqipi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fzhhl.top/Article/details/gtrimkrqrh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkxnatug.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtacclgltz.html

[F04] 追加写入文件
来源：http://dali.guowangkeji.top/Article/details/gtpmyaeuzb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtmcbyqkes.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hfpthk.cn/Article/details/gtmiccolky.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtssmwmsqm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtjredydhp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yvedp.cn/Article/details/gtynecvmqs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtepvkluzj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tianlin.xyz/Article/details/gthqdgjhsh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daria6918.cn/Article/details/gtvbowqovn.html

[F05] 判断文件或目录是否存在
来源：http://dali.yonumen.top/Article/details/gtvbalgsmw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hfpthk.cn/Article/details/gtcanxlswg.html

PHP:  file_exists("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtnfgxqezv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtpcdglplo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtqktuccps.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtazamekte.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daria6918.cn/Article/details/gtezpowsaz.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtfgmpitxu.html

C#:   File.Exists("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtsemkixvi.html

[F06] 删除文件
来源：http://dali.wangshuangyany.cn/Article/details/gtywhipxti.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtsglafkvg.html

PHP:  unlink("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtkkjwzgok.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtggrrilzy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtdyojyuux.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtpbesdykl.html

Go:   os.Remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gttcvqhybv.html

Ruby: File.delete("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtabotpybr.html

C#:   File.Delete("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtsehwtust.html

[F07] 创建目录（含多级）
来源：http://dali.dianchejie.cn/Article/details/gtjvrcxbsz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gtvnldxdpo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aibaodan.cn/Article/details/gtvkesdaep.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtgyndmcgl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtauglrztz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ydzc1.top/Article/details/gtgarcsxgj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenzaomai.com/Article/details/gtaenfkjiz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhoulong.xyz/Article/details/gtapjdfeua.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigfzy.top/Article/details/gtpxmwsfon.html

[F08] 遍历目录
来源：http://dali.shuidangran.top/Article/details/gtfzdxsuya.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.haohaochexian.top/Article/details/gtwpxfrstm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj202588.top/Article/details/gtayoefusl.html

JS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtozftygog.html

TS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtrdeaqldb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gthzycgasm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.havefunace.top/Article/details/gteptegahp.html

Ruby: Dir.children("dir")
来源：http://dali.daria6918.cn/Article/details/gtxvxevsau.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yvedp.cn/Article/details/gttobmwver.html

[F09] 获取文件大小
来源：http://dali.zhiwuduotai.top/Article/details/gtbkakqrhy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtddhrlwge.html

PHP:  filesize("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtnpivdusl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gthxoniago.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtvfdbvsjx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtlqushvao.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jyoumei.cn/Article/details/gtboemgojg.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtnxqmwcdx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.redwolf501.top/Article/details/gtuaczuyst.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shzxlz.cn/Article/details/gthvbmpvhm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtdoqzybik.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jyoumei.cn/Article/details/gthnbqtrrl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtaszmezfx.html

TS:   path.extname("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtzchndaoe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.c1oappe.top/Article/details/gtlbzojufj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtdwdmukky.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtnanzxxua.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfkiefja.html

[F11] 复制与移动文件
来源：http://dali.hfpthk.cn/Article/details/gtkxyrjtar.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtbliljfcm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gtokmjjatr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtljagkvan.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gteppjffjr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tian-w.cn/Article/details/gtxymuxywn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sufxvd.cn/Article/details/gtvnlfeqav.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtcglktztc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenlongwang.top/Article/details/gtwtziiqht.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gtqcqrkzkf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xylfe.cn/Article/details/gtharnkrum.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tianlin.xyz/Article/details/gtgrhqnpkt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yueranfly.top/Article/details/gtszctokxa.html

TS:   // 同上
来源：http://dali.svipenyu.cn/Article/details/gtmopnwkgc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hammf.cn/Article/details/gtnboingjm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhixingplan.top/Article/details/gtyrgyavyl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.316326.xyz/Article/details/gtjchixqeo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yvedp.cn/Article/details/gthlotdexp.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtioxpfirf.html

G. 面向对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsrdaanx.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtehufisxm.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gtzhtbytcb.html

Py:   class User: pass
来源：http://dali.9152youxi.cn/Article/details/gtsooftjps.html

PHP:  class User {}
来源：http://dali.guowangkeji.top/Article/details/gttaeioznm.html

JS:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtpeymdaak.html

TS:   class User { name: string = ""; }
来源：http://dali.havefunace.top/Article/details/gtdtynajrj.html

Java: class User {}
来源：http://dali.birdmap.top/Article/details/gtebyyipwx.html

Go:   type User struct { Name string }
来源：http://dali.fengsongda.top/Article/details/gtehfjmjis.html

Ruby: class User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gthyuuejbq.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtoxglqqpo.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gtmaylbviu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxinkj.top/Article/details/gtlcrgqgmc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.iojbl.cn/Article/details/gtzgqftkys.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtsdmuxblm.html

TS:   constructor(public name: string) {}
来源：http://dali.316326.xyz/Article/details/gtaoxcdhoe.html

Java: User(String name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfkguxxyl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhqyjgof.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jiagoushi.top/Article/details/gtfmgqfuor.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daxiang520.top/Article/details/gtqwzpmdfi.html

[G03] 实例属性
来源：http://dali.jlsjyb.cn/Article/details/gtctffpcao.html

Py:   self.name = "x"
来源：http://dali.redwolf501.top/Article/details/gtcbsgvrfn.html

PHP:  public string $name = "x";
来源：http://dali.yuanzhike.top/Article/details/gtzoheinhg.html

JS:   this.name = "x";
来源：http://dali.shuidangran.top/Article/details/gtosrqwpwk.html

TS:   name: string = "x";
来源：http://dali.snrcjt.cn/Article/details/gtcpdvxzad.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gtttjzxkcw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gtzubbjntp.html

Ruby: @name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtylhbvqif.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gthtfkddzk.html

[G04] 定义方法
来源：http://dali.ppjwa.cn/Article/details/gtsrefofsl.html

Py:   def greet(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtexuufezt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtkstpwjwh.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtnmkhttzw.html

TS:   greet(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtgcrswvps.html

Java: String greet() { return name; }
来源：http://dali.tanke756.top/Article/details/gtmwuhxjrg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtrbzjyknz.html

Ruby: def greet; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gtmrbwetks.html

C#:   public string Greet() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtuvvjdbds.html

[G05] 继承
来源：http://dali.jlsjyb.cn/Article/details/gtlynnydsh.html

Py:   class Admin(User): pass
来源：http://dali.ybcxt.top/Article/details/gtueuclotu.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtdakgadji.html

JS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtatzmcezi.html

TS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtaehdgcll.html

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gttvrduvmj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnxiangtu.top/Article/details/gtjsgqyijt.html

Ruby: class Admin < User; end
来源：http://dali.cucudq.cn/Article/details/gtkyovwarj.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtpsmqzufe.html

[G06] 重写方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtdglbzzro.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gtryidwasi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtpgyghlxw.html

JS:   greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtnpjppcce.html

TS:   greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gttxwtbrvx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gthogsapbx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.svipenyu.cn/Article/details/gtssidrujn.html

Ruby: def greet; "admin"; end
来源：http://dali.ehwqpu.com/Article/details/gtwrrdqbfy.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijknoyzo.html

[G07] 调用父类方法
来源：http://dali.hongshengwenyu.top/Article/details/gtxzmsxmpo.html

Py:   super().greet()
来源：http://dali.c1oappe.top/Article/details/gtdkuyqbhy.html

PHP:  parent::greet();
来源：http://dali.cucudq.cn/Article/details/gtvxndbxmf.html

JS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtyoxzgnsn.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gttzssttgz.html

Java: super.greet();
来源：http://dali.316326.xyz/Article/details/gtahkpndjl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guowangkeji.top/Article/details/gtdmkdmvsb.html

Ruby: super
来源：http://dali.jinqigufen.top/Article/details/gtuxqkxptf.html

C#:   base.Greet();
来源：http://dali.dianchejie.cn/Article/details/gtyahigwbn.html

[G08] 静态方法与属性
来源：http://dali.sysykeji.top/Article/details/gtelpsvpca.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jianghu66.top/Article/details/gtkawcwhwt.html

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gttqevonha.html

JS:   static f() {}
来源：http://dali.aibaodan.cn/Article/details/gtltwcwmla.html

TS:   static f(): void {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcljdbte.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gtqjlrefkl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj202588.top/Article/details/gtqvtjfyyz.html

Ruby: def self.f; end
来源：http://dali.vqdsnc.cn/Article/details/gtphysiqzp.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gtomyezgky.html

[G09] 接口 / 抽象类
来源：http://dali.guannengcc.top/Article/details/gtpyauphej.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhiwuduotai.top/Article/details/gtanmhyesw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhijiandao.cn/Article/details/gtwhcidhak.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aibaodan.cn/Article/details/gtlzfjkdxj.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gtdnkpajqw.html

Java: interface Shape { double area(); }
来源：http://dali.nwbrower.top/Article/details/gtckbujkiy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258.top/Article/details/gticennlax.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cqqwz.cn/Article/details/gtsppgmxfr.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gtimygsvth.html

[G10] 访问控制
来源：http://dali.jlsjyb.cn/Article/details/gtfniuoypc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shzxlz.cn/Article/details/gtmrnkhmms.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtsfjdjkvg.html

JS:   #private 字段；其余公开
来源：http://dali.haohaochexian.top/Article/details/gtkpmntgai.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtxbsbcwgd.html

Java: public / protected / private / 默认包级
来源：http://dali.zycfv.cn/Article/details/gtsvdpwygm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xziqi.cn/Article/details/gtwqquhqkv.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gtvlkywqni.html

C#:   public / protected / private / internal
来源：http://dali.jiagoushi.top/Article/details/gthinuxmbg.html

[G11] getter / setter
来源：http://dali.sysykeji.top/Article/details/gtdpbpmxeo.html

Py:   @property 与 @x.setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumpqclmu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtaieccrme.html

JS:   get name() { return this._name; }
来源：http://dali.daria6918.cn/Article/details/gtzhjurrno.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtiqdvxunb.html

Java: public String getName() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtwfcfygkk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtmvtrooee.html

Ruby: attr_accessor :name
来源：http://dali.guowangkeji.top/Article/details/gtomkjlvcx.html

C#:   public string Name { get; set; }
来源：http://dali.hysaishi.cn/Article/details/gtxuqmoksk.html

[G12] 对象转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwaniohyq.html

Py:   def __str__(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtamygvtmj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtxzqdgqkj.html

JS:   toString() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwvrutfkp.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtlbmnfebp.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtkbxnrrqq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtqebgayat.html

Ruby: def to_s; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtiiuxwxcf.html

C#:   public override string ToString() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtwhmfkpyz.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gtvdtxdgax.html

Py:   isinstance(u, User)
来源：http://dali.cdnleiting.top/Article/details/gtrcfhvwgw.html

PHP:  $u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtbksywhas.html

JS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtfumtpbci.html

TS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gtoxilzfca.html

Java: u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gthdpgbdoe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zdqjudy.top/Article/details/gtfvkbfofv.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gtorynvgko.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gtsqvyflrd.html

[G14] 数据类 / record
来源：http://dali.cashguo.top/Article/details/gtwocdhaxh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuxming.cn/Article/details/gtwtzvnfmq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigufen.top/Article/details/gtyxjzyelz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pengpengdd.cyou/Article/details/gtxsxflxhi.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gtjzhoehxo.html

Java: record User(String name, int age) {}
来源：http://dali.birdmap.top/Article/details/gtsylsorxs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cqqwz.cn/Article/details/gtpwmffsmo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gtjsheosdq.html

C#:   record User(string Name, int Age);
来源：http://dali.gogol.net.cn/Article/details/gtmnmaarop.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gtjvphdxau.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gtldrufllr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gtbwzvgsqd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pengpengdd.cyou/Article/details/gtxknncgfl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtlmiocpua.html

Java: enum Color { RED, GREEN }
来源：http://dali.dianchejie.cn/Article/details/gtyjwfuvyz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhoulong.xyz/Article/details/gtlygncuzc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhijiandao.cn/Article/details/gttrppmslk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtragptvhc.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gtbzdalgeh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigfzy.top/Article/details/gtgxhsygyo.html

PHP:  get_object_vars($obj);
来源：http://dali.cashguo.top/Article/details/gtzihmuhrp.html

JS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gthgcwglqw.html

TS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gtibfivcev.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gtoyiiwjls.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tian-w.cn/Article/details/gtgwbsiycb.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gtsmtvssan.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gtsehnfuvt.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtaciiwhks.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gtxjumpyml.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtptspbhmh.html

[H01] try / catch 基础
来源：http://dali.nanxuanxn.top/Article/details/gtjwwfoemr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuxming.cn/Article/details/gtwejkvscm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.kuanghao11.cn/Article/details/gtutxlhfin.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtwrosafhw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtrabvryty.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shzxlz.cn/Article/details/gtimjkmdpy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guowangkeji.top/Article/details/gtjigcxnnz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxinkj.top/Article/details/gtdumrahxl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhengqikj.top/Article/details/gtklbnnfia.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gtguhqpzor.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gtefdkocmj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtfuyujadr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtjjbeiole.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttolomuam.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtqqvjgnol.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gthkuqbndl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gtehdzsnjp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtsqgzkxux.html

[H03] 主动抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gtlunvazhz.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gtcyijyvhn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtkypdzkox.html

JS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtocewkxxy.html

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtxbedfbnf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtayfuubbg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cdnleiting.top/Article/details/gtfckwzuog.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuxming.cn/Article/details/gtjfasoyad.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtryxnyzkz.html

[H04] 自定义异常类型
来源：http://dali.hnxiangtu.top/Article/details/gtgjwntzxd.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtkutnppfh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtdoutplgt.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gtitszsrym.html

TS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gthfwrvexf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtwuizlgab.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yueranfly.top/Article/details/gtvopsibxi.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gtdjcjbsrk.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gtcetnkoqu.html

[H05] 捕获特定类型
来源：http://dali.yonumen.top/Article/details/gtxndtxhnq.html

Py:   except ValueError as e:
来源：http://dali.ppjwa.cn/Article/details/gtckxnmzwe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuetiantiany.cn/Article/details/gtutazeexk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtffprcffi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gtqjlwuffx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gtkvmghovl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gogol.net.cn/Article/details/gtbwnjlvne.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlbniguh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzltmgtd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gtmffacqey.html

Py:   value = d.get("k") or default
来源：http://dali.wangdashe.top/Article/details/gtpvovddeg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cdnleiting.top/Article/details/gtdlfzvqgt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtsqishrit.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtnbxhuhnt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenlongwang.top/Article/details/gtbqssgjlg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gotoacloud.top/Article/details/gtyllsjnae.html

Ruby: d&.dig(:a, :b)
来源：http://dali.meibo888.top/Article/details/gtcjlqtdrg.html

C#:   obj?.A?.B ?? default
来源：http://dali.yonumen.top/Article/details/gtxjdvrtyx.html

[H07] 断言
来源：http://dali.yj20258888.top/Article/details/gtjbambwek.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdimjlxi.html

PHP:  assert($x > 0);
来源：http://dali.shuidangran.top/Article/details/gttqqloemn.html

JS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtlnrubxkn.html

TS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtklpashkx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cdnleiting.top/Article/details/gteoarkzbe.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shzxlz.cn/Article/details/gtywexklfv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gtiszgaqvh.html


<!-- 参考信息 -->