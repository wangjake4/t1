代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.ehwqpu.com/Article/details/gtspenixgd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.andypj.xyz/Article/details/gtxdftcink.html

PHP:  file_exists("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtummmblsb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtxqhtlbdc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtwunwahaq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtovkflmwv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.havefunace.top/Article/details/gtvcgkutno.html

Ruby: File.exist?("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtkclhgggf.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gterfzrbia.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gtatsfpmkb.html

Py:   os.remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtsshemprs.html

PHP:  unlink("a.txt");
来源：http://dali.pycfn.com/Article/details/gtlbddeejy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gttvyxborg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gthlwjbqia.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtcwmfxybc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtrnhztdtg.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtucmrhqax.html

C#:   File.Delete("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtvieiczbo.html

[F07] 创建目录（含多级）
来源：http://dali.hnqzz.top/Article/details/gthydqhsjc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gtxvdxomgm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gtwaycwkvw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gtxoowtwpu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gtjacshxci.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zycfv.cn/Article/details/gtwwxuapbe.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nwbrower.top/Article/details/gtdxmsdung.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gtokgjrytr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.quarkkingdee.top/Article/details/gtqzuzscag.html

[F08] 遍历目录
来源：http://dali.mhx1999.top/Article/details/gtxfdxijyn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuanzx.com/Article/details/gtfnnqxncg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtduydrlbq.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnspdtgrj.html

TS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtlilbovoc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtnhbyfktl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fengsongda.top/Article/details/gtpjeunmur.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gtgicvqrck.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtningewnj.html

[F09] 获取文件大小
来源：http://dali.iojbl.cn/Article/details/gtchtnfnaj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtzqqfommt.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtdcivlafl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gttlwrgozc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gtjjqfimrm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtgmfxzktp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gtsogcrfpc.html

Ruby: File.size("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtbwsglpfv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.feifeiyinyue.top/Article/details/gtnbweqbbt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tian-w.cn/Article/details/gthmmgyttm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gthotplzim.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtuddgucfe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtpelcflqh.html

TS:   path.extname("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtdryvvlib.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daxiang520.top/Article/details/gtnsjdbrhm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gttvgwsvfj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtlwzbobza.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtjxtvlrno.html

[F11] 复制与移动文件
来源：http://dali.gaohongyu789.top/Article/details/gtvzumttnm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtcgyejxoo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tanke756.top/Article/details/gtjvjqmgqr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtxpigdnxf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtirsmdqig.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gtpfyjgxuk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gtiysaxrja.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtflmlujgn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aibaodan.cn/Article/details/gtabhzuwye.html

[F12] CSV 读写
来源：http://dali.guannengcc.top/Article/details/gttuprxums.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gtdcyeodse.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gtongzmoss.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrpxsbbq.html

TS:   // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbruriog.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangshuangyany.cn/Article/details/gtbyuqudxn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tianlin.xyz/Article/details/gtwlogpekz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangtech.top/Article/details/gtinxizgiu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.havefunace.top/Article/details/gtwqgdhlgb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gttdockmor.html

G. 面向对象
来源：http://dali.gzhubu.top/Article/details/gtrqakekzp.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtbmdrwlxu.html

[G01] 定义类
来源：http://dali.ehwqpu.com/Article/details/gtzquktkhv.html

Py:   class User: pass
来源：http://dali.yonumen.top/Article/details/gtafzzfuqg.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gtoxzddzhe.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtrcmzamfq.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gttuljcvch.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gtmcglqfal.html

Go:   type User struct { Name string }
来源：http://dali.tian-w.cn/Article/details/gtauclafxj.html

Ruby: class User; end
来源：http://dali.dashuyun.cn/Article/details/gtkzzaupsr.html

C#:   class User {}
来源：http://dali.xziqi.cn/Article/details/gtunpjsvkx.html

[G02] 构造函数
来源：http://dali.guannengcc.top/Article/details/gtuweqigpg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yongpay.top/Article/details/gtastllise.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhengqikj.top/Article/details/gtshbmlzon.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtjcqdhqfa.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gtlutngqno.html

Java: User(String name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtpykdelov.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xinyue.icu/Article/details/gtcwismqrs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gtlmfobdwo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.andypj.xyz/Article/details/gtryzwcqrm.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gtcmdpsexx.html

Py:   self.name = "x"
来源：http://dali.tanke756.top/Article/details/gtdrkfopmn.html

PHP:  public string $name = "x";
来源：http://dali.meibo888.top/Article/details/gtdtrtzsus.html

JS:   this.name = "x";
来源：http://dali.yonumen.top/Article/details/gtkbymsxjk.html

TS:   name: string = "x";
来源：http://dali.ppjwa.cn/Article/details/gtzzpbrwfg.html

Java: private String name;
来源：http://dali.tanke756.top/Article/details/gtqplzkcmu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jiagoushi.top/Article/details/gtluwntiqa.html

Ruby: @name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtgkmasijl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.smart0.xyz/Article/details/gtbdchbrkr.html

[G04] 定义方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvpiltow.html

Py:   def greet(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtkuodrkak.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtalqpjvvm.html

JS:   greet() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtdursxpbw.html

TS:   greet(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtsomlxfjg.html

Java: String greet() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtasfclrls.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtrtcvearw.html

Ruby: def greet; @name; end
来源：http://dali.ivvv.top/Article/details/gtlimbkbut.html

C#:   public string Greet() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gttfmreona.html

[G05] 继承
来源：http://dali.guannengcc.top/Article/details/gtwfgtxrtb.html

Py:   class Admin(User): pass
来源：http://dali.dianchejie.cn/Article/details/gtipmqgpfe.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gthtaplwcl.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqthblfa.html

TS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtuudmmren.html

Java: class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gthbcqemjk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gtxylhezwf.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtaozgfdyp.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gtjjwnprnh.html

[G06] 重写方法
来源：http://dali.feifeiyinyue.top/Article/details/gtjwvaysjn.html

Py:   def greet(self): return "admin"
来源：http://dali.yongpay.top/Article/details/gtwlzdlcme.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtzmpompip.html

JS:   greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtdhafuszl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtoowakdao.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtwnadwzcq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gtcuvfzefu.html

Ruby: def greet; "admin"; end
来源：http://dali.gotoacloud.top/Article/details/gtjlwcrhob.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gtvqyslztp.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gtikenobei.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gtihgvwiye.html

PHP:  parent::greet();
来源：http://dali.yuanzhike.top/Article/details/gtdtdbbbdp.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtxhoxswcx.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtrtqqkhlx.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtbdikrcip.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xinyue.icu/Article/details/gtfdiclhcq.html

Ruby: super
来源：http://dali.shangyingyoupin.top/Article/details/gtxakqgiwj.html

C#:   base.Greet();
来源：http://dali.jqgufenzy.top/Article/details/gtoroaxued.html

[G08] 静态方法与属性
来源：http://dali.smart0.xyz/Article/details/gtpimbeovo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigfzy.top/Article/details/gtjmeihydg.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gtrotuczng.html

JS:   static f() {}
来源：http://dali.hysaishi.cn/Article/details/gtltjjqkhj.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gtladzwdqz.html

Java: static void f() {}
来源：http://dali.tianlin.xyz/Article/details/gtcvmogdwe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxuanxn.top/Article/details/gtcbejjush.html

Ruby: def self.f; end
来源：http://dali.hywenlv.cn/Article/details/gtyjxzyrfw.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsoudktw.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgzkqxun.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yvedp.cn/Article/details/gtaogmkire.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fzhhl.top/Article/details/gtddkliqlq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.birdmap.top/Article/details/gtblrxmbai.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gtypnmqgxn.html

Java: interface Shape { double area(); }
来源：http://dali.gzhubu.top/Article/details/gtbgmferov.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcflqcdy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yongpay.top/Article/details/gtnuornqaj.html

C#:   interface IShape { double Area(); }
来源：http://dali.ivvv.top/Article/details/gtqusexcsx.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gtupjtqzvy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.svipenyu.cn/Article/details/gtgumbwqru.html

PHP:  public / protected / private
来源：http://dali.pycfn.com/Article/details/gtvdqunnpa.html

JS:   #private 字段；其余公开
来源：http://dali.hongshengwenyu.top/Article/details/gtjgtkneua.html

TS:   public / protected / private
来源：http://dali.birdmap.top/Article/details/gtoktszhxg.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxuanxn.top/Article/details/gtkkuyqref.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sufxvd.cn/Article/details/gtfraktjwe.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtjpbzormu.html

C#:   public / protected / private / internal
来源：http://dali.wangdashe.top/Article/details/gtmqlwsypc.html

[G11] getter / setter
来源：http://dali.ivvv.top/Article/details/gtfyfyfyht.html

Py:   @property 与 @x.setter
来源：http://dali.tian-w.cn/Article/details/gtrdvxlwct.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtqxwnjjxu.html

JS:   get name() { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtikyuuxnz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtlrpurmxy.html

Java: public String getName() { return name; }
来源：http://dali.ivvv.top/Article/details/gtjiikigjm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtlqpgbyie.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gtiqmphonj.html

C#:   public string Name { get; set; }
来源：http://dali.jyoumei.cn/Article/details/gtfcpabeem.html

[G12] 对象转字符串
来源：http://dali.yongpay.top/Article/details/gtmwjarpjz.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtfyocwbqh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtkktogkxf.html

JS:   toString() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtzmnpwoxk.html

TS:   toString(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtzbdhrooe.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtzmdofnhv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtggxaethc.html

Ruby: def to_s; @name; end
来源：http://dali.mhx1999.top/Article/details/gterbtqpcn.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxynglarn.html

[G13] 判断对象类型
来源：http://dali.hysaishi.cn/Article/details/gtenrkuwrk.html

Py:   isinstance(u, User)
来源：http://dali.jyoumei.cn/Article/details/gtphvyibib.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtacypnxaw.html

JS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtspqenrui.html

TS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtmxbphjto.html

Java: u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtwxtnymmf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gtpmdjuqsw.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gtvxcuyend.html

C#:   u is User
来源：http://dali.xuetiantiany.cn/Article/details/gtasuvnopm.html

[G14] 数据类 / record
来源：http://dali.cucudq.cn/Article/details/gtyutjxgfp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gtgornasre.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gaohongyu789.top/Article/details/gtozmohyho.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gtfcixeflb.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gtiqdunhoa.html

Java: record User(String name, int age) {}
来源：http://dali.chenlongwang.top/Article/details/gtcbvyzove.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuanzhike.top/Article/details/gtweuvaiel.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenjidiqi.icu/Article/details/gthflhemnx.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gtqwdfqazo.html

[G15] 枚举
来源：http://dali.chenzaomai.com/Article/details/gtvertueit.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenlongwang.top/Article/details/gttxbvqqvq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sweek.top/Article/details/gtzrgkybmp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.svipenyu.cn/Article/details/gtygqoboio.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gtwyfnqhzi.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenjidiqi.icu/Article/details/gtihuodrug.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gtdntsdhrz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guowangkeji.top/Article/details/gtaybwwksk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gtcszigxnj.html

[G16] 对象转数组 / 字典
来源：http://dali.cheryme.top/Article/details/gteqctqfqg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guowangkeji.top/Article/details/gtccoctwxf.html

PHP:  get_object_vars($obj);
来源：http://dali.xuetiantiany.cn/Article/details/gtxsfoiouz.html

JS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtdasaqbzr.html

TS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhogzdjm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hongshengwenyu.top/Article/details/gtdeirtjsp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gttmvoxqau.html

Ruby: obj.instance_variables
来源：http://dali.9152youxi.cn/Article/details/gtpdrnlajk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gtfugmxgtz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtjxagvdro.html

H. 异常与错误处理
来源：http://dali.jianghu66.top/Article/details/gtumpfltvk.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtxqpetsxg.html

[H01] try / catch 基础
来源：http://dali.chenzaomai.com/Article/details/gtepgnhhpq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cdnleiting.top/Article/details/gtcpxjhkvp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gtpvrpwxor.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtjpmkbpvc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtelfbdhnl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pengpengdd.cyou/Article/details/gtadscsnse.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zycfv.cn/Article/details/gtypyhcmrn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhiwuduotai.top/Article/details/gtmpqldeut.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yangfankeji.com/Article/details/gtvxzdkmqm.html

[H02] finally / ensure 收尾
来源：http://dali.jiagoushi.top/Article/details/gtyandtmwl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zdqjudy.top/Article/details/gttdarsepk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtimgaxazb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtzsacqsps.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtcxidxyls.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtqgnctgpo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gtwrqwfxos.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxinkj.top/Article/details/gtamatwfsj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtmnskummi.html

[H03] 主动抛出异常
来源：http://dali.yueranfly.top/Article/details/gtbzpxends.html

Py:   raise ValueError("错误信息")
来源：http://dali.nwbrower.top/Article/details/gtnmtckibq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtaqdrvukp.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtvueqajfc.html

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtdrpjtwup.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtnbfbepxy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gtxrztmdzf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yvedp.cn/Article/details/gtdunqrstg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtnephkeku.html

[H04] 自定义异常类型
来源：http://dali.yuxming.cn/Article/details/gtkpqwxakw.html

Py:   class MyError(Exception): pass
来源：http://dali.haohaochexian.top/Article/details/gthhvtioww.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gtdfbkurcj.html

JS:   class MyError extends Error {}
来源：http://dali.xinyue.icu/Article/details/gtcqcfpmnc.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtgbyxdkpz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gtwbshbpet.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cdnleiting.top/Article/details/gtriisqwjn.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gtxfazaioa.html

C#:   class MyException : Exception {}
来源：http://dali.wangshuangyany.cn/Article/details/gteqrcjjha.html

[H05] 捕获特定类型
来源：http://dali.jlsjyb.cn/Article/details/gtpkoyiqoq.html

Py:   except ValueError as e:
来源：http://dali.ybcxt.top/Article/details/gtuveuupfi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangdashe.top/Article/details/gtjwozhoai.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtvgoxumsv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtiypbaaex.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xziqi.cn/Article/details/gtqtwgjymm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hammf.cn/Article/details/gtbwquhdix.html

Ruby: rescue ArgumentError => e
来源：http://dali.ehwqpu.com/Article/details/gtyszhwpba.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gtavjppebi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.snrcjt.cn/Article/details/gtecybgnyc.html

Py:   value = d.get("k") or default
来源：http://dali.kuanghao11.cn/Article/details/gtxjgwonxy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtlzmldzae.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtjbhooyaa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtzosnhcqh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.meibo888.top/Article/details/gtfowswmqt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.0kj1m.cn/Article/details/gtpnhaumfy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.redwolf501.top/Article/details/gtqnwkiazx.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtadktjkxp.html

[H07] 断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzfaesjc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtknebkcqa.html

PHP:  assert($x > 0);
来源：http://dali.yj20258.top/Article/details/gtozwvtebl.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtlcngdwbm.html

TS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtfjeprped.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aibaodan.cn/Article/details/gtuetvubwq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangshuangyany.cn/Article/details/gtfjiynwqa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cashguo.top/Article/details/gtmmxotwei.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtjbmftcqt.html

[H08] 获取错误信息与堆栈
来源：http://dali.guowangkeji.top/Article/details/gthmiweitj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.svipenyu.cn/Article/details/gtlojbzmao.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhixingplan.top/Article/details/gtvelsxqnb.html

JS:   e.message;  e.stack
来源：http://dali.ybcxt.top/Article/details/gtqmxjudvl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtnkqwmghc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gtrdoyogrw.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gtzyhbutez.html

Ruby: e.message;  e.backtrace
来源：http://dali.cashguo.top/Article/details/gtbbcnsnwv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.birdmap.top/Article/details/gtkeckxwdv.html

[H09] 带错误码的异常
来源：http://dali.cucudq.cn/Article/details/gtscooavio.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sweek.top/Article/details/gtufrhcpoq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.kuanghao11.cn/Article/details/gtvivoinpb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.9152youxi.cn/Article/details/gtawdytcty.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dianchejie.cn/Article/details/gtatbnwoaw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnxiangtu.top/Article/details/gtemlfmwxa.html


<!-- 参考信息 -->