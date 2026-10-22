代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.kuanghao11.cn/Article/details/gtcthiyiju.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tian-w.cn/Article/details/gthrfenniv.html

PHP:  file_exists("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtehkxxlmf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtmzrpxvge.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtahqbeatk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtlpmowfqt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jlsjyb.cn/Article/details/gtpgwinabj.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtagwhelzx.html

C#:   File.Exists("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtwsajoyxr.html

[F06] 删除文件
来源：http://dali.yangfankeji.com/Article/details/gtikxafmrb.html

Py:   os.remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtwcfmewah.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtddxtijlc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtljhkipvw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtmgzlrkia.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtoszryldi.html

Go:   os.Remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtapqeiusf.html

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtsidjotzs.html

C#:   File.Delete("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtfwposfuk.html

[F07] 创建目录（含多级）
来源：http://dali.ppjwa.cn/Article/details/gtrxmravho.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cashguo.top/Article/details/gtgzdoizpc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenlongwang.top/Article/details/gtmkmqswgp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gtvafzpvbx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtekvibvge.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtijoadj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gtmniekcyu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tianlin.xyz/Article/details/gttqjubxss.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yongpay.top/Article/details/gtdtuiowcj.html

[F08] 遍历目录
来源：http://dali.jqgfzy.top/Article/details/gtaulsrdcq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sxryk.cn/Article/details/gtdqlppylo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gtbxcefmyw.html

JS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbocllfp.html

TS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gtlvlpdysk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gtmsqrwsbh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gthuhpyigy.html

Ruby: Dir.children("dir")
来源：http://dali.mhx1999.top/Article/details/gtiwnugqpx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtqavsygwt.html

[F09] 获取文件大小
来源：http://dali.wangdashe.top/Article/details/gtotwrhwle.html

Py:   os.path.getsize("a.txt")
来源：http://dali.meibo888.top/Article/details/gtjvcggfqb.html

PHP:  filesize("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtgbdqyiim.html

JS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gtqyspwxic.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gtvvxaydzm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtgojorskj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yangfankeji.com/Article/details/gtqmoixnqf.html

Ruby: File.size("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gttxpnahla.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cucudq.cn/Article/details/gtkywvuekr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gtviyqtawv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtwmidmbrl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xziqi.cn/Article/details/gtfiixeeat.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtndfvzcqx.html

TS:   path.extname("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gthwjjxeeh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcomcfonb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtsusevejs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtelkhnjzf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtcttouvfr.html

[F11] 复制与移动文件
来源：http://dali.xinyue.icu/Article/details/gtwtndwpfh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtpicucjqh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hywenlv.cn/Article/details/gtymzvkukx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtqazmhesh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtpkwgvdrj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtlovydiss.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.redwolf501.top/Article/details/gtyslmdkbz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtjfdkulci.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuetiantiany.cn/Article/details/gthbodeias.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gtfqwzkvry.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guannengcc.top/Article/details/gtfotvncyz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gtbwibczgv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yongpay.top/Article/details/gtzctlnpsu.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtxgcclkkt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gotoacloud.top/Article/details/gttluckmpt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dashuyun.cn/Article/details/gthxhrgvui.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangtech.top/Article/details/gtavftbnby.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gtbjqrmsso.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtezqtprkq.html

G. 面向对象
来源：http://dali.cheryme.top/Article/details/gtpxgwcpjr.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtzenmgntc.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gtaruimfwc.html

Py:   class User: pass
来源：http://dali.gotoacloud.top/Article/details/gtodrwctlz.html

PHP:  class User {}
来源：http://dali.yongpay.top/Article/details/gtikyjaijy.html

JS:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiisbldee.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gtburjqyew.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtgekkimpf.html

Go:   type User struct { Name string }
来源：http://dali.zhoulong.xyz/Article/details/gtanoezxaz.html

Ruby: class User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhvtwnam.html

C#:   class User {}
来源：http://dali.tanke756.top/Article/details/gthhprrbwl.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gtgbycfuqu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.meibo888.top/Article/details/gtbsuonnyy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.c1oappe.top/Article/details/gtyiukrqkh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtnzecekyc.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gtxodnudpt.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtigzorxyo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhugwfif.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gtwwdoipjz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xziqi.cn/Article/details/gtazxhzlck.html

[G03] 实例属性
来源：http://dali.hnqzz.top/Article/details/gtruktwvdb.html

Py:   self.name = "x"
来源：http://dali.mhx1999.top/Article/details/gtnljjpaic.html

PHP:  public string $name = "x";
来源：http://dali.nwbrower.top/Article/details/gtxylvxaug.html

JS:   this.name = "x";
来源：http://dali.wangdashe.top/Article/details/gtrsthttjq.html

TS:   name: string = "x";
来源：http://dali.jianghu66.top/Article/details/gtsqbnbsbn.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gtfdpxyutn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.vqdsnc.cn/Article/details/gtsrobpitc.html

Ruby: @name = "x"
来源：http://dali.gzhubu.top/Article/details/gtmdbqsohe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.fzhhl.top/Article/details/gtchjbeibg.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyztuxeww.html

Py:   def greet(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gtuhgafoab.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtsyiphfzb.html

JS:   greet() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtmciydwvh.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtmofguoop.html

Java: String greet() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtuwjqrnye.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtngojzcdp.html

Ruby: def greet; @name; end
来源：http://dali.sufxvd.cn/Article/details/gtgrkrdauf.html

C#:   public string Greet() => Name;
来源：http://dali.yvedp.cn/Article/details/gtgumddqet.html

[G05] 继承
来源：http://dali.wangdashe.top/Article/details/gtlpufkijv.html

Py:   class Admin(User): pass
来源：http://dali.tanke756.top/Article/details/gtkkeutqhr.html

PHP:  class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsgftcdu.html

JS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoccgkljt.html

TS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtmwucaybr.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtpzclovul.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gtddzzqqol.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtqazkotse.html

C#:   class Admin : User {}
来源：http://dali.yvedp.cn/Article/details/gtgdxczjzc.html

[G06] 重写方法
来源：http://dali.haohaochexian.top/Article/details/gtooqlydoo.html

Py:   def greet(self): return "admin"
来源：http://dali.andypj.xyz/Article/details/gtimshaezx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtroudzshq.html

JS:   greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtfhpzlflm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtjrrohzhv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtjcycgiud.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aibaodan.cn/Article/details/gtjyrkskmh.html

Ruby: def greet; "admin"; end
来源：http://dali.feifeiyinyue.top/Article/details/gtntykghqc.html

C#:   public override string Greet() => "admin";
来源：http://dali.mhx1999.top/Article/details/gtnixxguho.html

[G07] 调用父类方法
来源：http://dali.haohaochexian.top/Article/details/gtsjkcwkxw.html

Py:   super().greet()
来源：http://dali.svipenyu.cn/Article/details/gteypawgyv.html

PHP:  parent::greet();
来源：http://dali.nanxinkj.top/Article/details/gtordlqyye.html

JS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtustmygdz.html

TS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgycdeto.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtxqmjiwod.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuetiantiany.cn/Article/details/gtfxnfzath.html

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gtocknefxq.html

C#:   base.Greet();
来源：http://dali.vqdsnc.cn/Article/details/gtoyewenrr.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gtdiwpfawo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigfzy.top/Article/details/gthrnlzmbp.html

PHP:  public static function f() {}
来源：http://dali.jqgfzy.top/Article/details/gtrxuykgfp.html

JS:   static f() {}
来源：http://dali.snrcjt.cn/Article/details/gtooaeygil.html

TS:   static f(): void {}
来源：http://dali.shuidangran.top/Article/details/gtewfnvvra.html

Java: static void f() {}
来源：http://dali.hammf.cn/Article/details/gtgozmgulu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gtbkvuwxms.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gtlqtrgxjk.html

C#:   public static void F() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtyquxejmk.html

[G09] 接口 / 抽象类
来源：http://dali.316326.xyz/Article/details/gtelqmwivm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guowangkeji.top/Article/details/gtuhcsykze.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxuanxn.top/Article/details/gtmcgaebip.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cucudq.cn/Article/details/gtjalwcjyn.html

TS:   interface Shape { area(): number; }
来源：http://dali.jlsjyb.cn/Article/details/gtiyxnrmhr.html

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gtxcaahzjj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gtmwuumyhc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.c1oappe.top/Article/details/gtypwouewh.html

C#:   interface IShape { double Area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqtfxzxw.html

[G10] 访问控制
来源：http://dali.sufxvd.cn/Article/details/gtcgqjjfpe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ybcxt.top/Article/details/gtmshlphxy.html

PHP:  public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtznohxkwr.html

JS:   #private 字段；其余公开
来源：http://dali.9152youxi.cn/Article/details/gtylzzpqfs.html

TS:   public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtiuuyhhon.html

Java: public / protected / private / 默认包级
来源：http://dali.yangfankeji.com/Article/details/gtkitbdtnt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhoulong.xyz/Article/details/gtslpgaxia.html

Ruby: public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtqsdlngnh.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gtfmpydakl.html

[G11] getter / setter
来源：http://dali.jinqigufen.top/Article/details/gtqmofouoh.html

Py:   @property 与 @x.setter
来源：http://dali.fengsongda.top/Article/details/gtdbgvfqgz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnmhkffc.html

JS:   get name() { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gtyjbxdeoj.html

TS:   get name(): string { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gtahxgmtls.html

Java: public String getName() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxieiaqa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtzyzdovbe.html

Ruby: attr_accessor :name
来源：http://dali.gogol.net.cn/Article/details/gtzhmhazbq.html

C#:   public string Name { get; set; }
来源：http://dali.meibo888.top/Article/details/gtzgcowwcy.html

[G12] 对象转字符串
来源：http://dali.sysykeji.top/Article/details/gtmymkkqmr.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtsngubvqi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtnbtphoty.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtzrzifgvi.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtengokufy.html

Java: @Override public String toString() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtzbvflves.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtnlexlpmz.html

Ruby: def to_s; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtrjnjtpao.html

C#:   public override string ToString() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtpgnjavir.html

[G13] 判断对象类型
来源：http://dali.fengsongda.top/Article/details/gtdpbywtih.html

Py:   isinstance(u, User)
来源：http://dali.vqdsnc.cn/Article/details/gtxdajpxeo.html

PHP:  $u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtfpzfyhuc.html

JS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehzhimkz.html

TS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtvwqncbxi.html

Java: u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gttfaqjbja.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymbsnzls.html

Ruby: u.is_a?(User)
来源：http://dali.sysykeji.top/Article/details/gtkvfwplye.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gthhnqfddm.html

[G14] 数据类 / record
来源：http://dali.hongshengwenyu.top/Article/details/gttxszupug.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolesoyse.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daxiang520.top/Article/details/gtnziyryxa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xylfe.cn/Article/details/gthfffpgww.html

TS:   type User = { name: string; age: number };
来源：http://dali.sufxvd.cn/Article/details/gtzkarneec.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gtqqirrxaq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuanzhike.top/Article/details/gtoqlexmtw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuanzhike.top/Article/details/gtmvfevbqn.html

C#:   record User(string Name, int Age);
来源：http://dali.fzhhl.top/Article/details/gtwtnaaelx.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtiaiycypa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigufen.top/Article/details/gtmetxfwwe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhongyouzk.top/Article/details/gtmrnlqkyz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gtaaazwqwv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gtnhdqdezi.html

Java: enum Color { RED, GREEN }
来源：http://dali.bjfxy.top/Article/details/gtggyhgtxa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gtjahwxhky.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigufen.top/Article/details/gtcnspdqga.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtpffrvmho.html

[G16] 对象转数组 / 字典
来源：http://dali.cucudq.cn/Article/details/gtdbpzbivz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhixingplan.top/Article/details/gtqakqybbo.html

PHP:  get_object_vars($obj);
来源：http://dali.cdnleiting.top/Article/details/gtmjevhjme.html

JS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gtpiurvnrk.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtnirqolif.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhoulong.xyz/Article/details/gtfuqhiioc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hfpthk.cn/Article/details/gtwyiglocz.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gtpxkkqhvt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtzymxinzy.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtzwvegaol.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gtxdsnzbpn.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtnxcanazu.html

[H01] try / catch 基础
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetskajdp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ybcxt.top/Article/details/gtfckcusql.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yongpay.top/Article/details/gtzuesgwnu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtoezbircn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtgchtaevy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hammf.cn/Article/details/gtbbiojfdz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xinyue.icu/Article/details/gtkebbcrcu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hywenlv.cn/Article/details/gtonytlfrg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gtlvgcqgsz.html

[H02] finally / ensure 收尾
来源：http://dali.mhx1999.top/Article/details/gtynlfuuaw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gtjrvnwjjb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtdzeukxyc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtbtfjxwmh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtcoriozhk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtbrwnbtdz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.birdmap.top/Article/details/gtsderowdy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhengqikj.top/Article/details/gtjcqdfxkw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtiqouhouy.html

[H03] 主动抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gtfssjwcbj.html

Py:   raise ValueError("错误信息")
来源：http://dali.gogol.net.cn/Article/details/gtszwjpolf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtriklazjd.html

JS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgysbnsw.html

TS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvruayjg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtolqhvuyx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gtnrmdgjhf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibcyapze.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtmtgerpom.html

[H04] 自定义异常类型
来源：http://dali.feifeiyinyue.top/Article/details/gtpxbjutqx.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gtpwesggte.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gtabpnlryi.html

JS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtbylouxfv.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gtnnszzwkg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtnndboffj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhixingplan.top/Article/details/gtfzvamsqq.html

Ruby: class MyError < StandardError; end
来源：http://dali.0kj1m.cn/Article/details/gtlyenbdyp.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptghnmdg.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqujtspdu.html

Py:   except ValueError as e:
来源：http://dali.xziqi.cn/Article/details/gtyfyaaddt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangdashe.top/Article/details/gtqfzevedi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtdgmzzgzj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtoivajavl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gtwgqqbjig.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yanxiufei.cn/Article/details/gtfjkjifsq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zycfv.cn/Article/details/gtedxaduxt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjqajvxmm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258888.top/Article/details/gtfsyvqoay.html

Py:   value = d.get("k") or default
来源：http://dali.yangfankeji.com/Article/details/gtqpecqgsu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtcfdosblw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gttetpdhzh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gticpnfcjc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.andypj.xyz/Article/details/gtdfrosqlw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guowangkeji.top/Article/details/gtaxlygrcr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hammf.cn/Article/details/gtuuxweryv.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxinkj.top/Article/details/gtgdgmcjhc.html

[H07] 断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcflvzuj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nwbrower.top/Article/details/gtaesaxbnk.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gtuendtxrc.html

JS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtcqjdjyzw.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrhotpez.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gtbemzngud.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guowangkeji.top/Article/details/gtoryrwvoa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhoulong.xyz/Article/details/gtimrxheib.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gthjkwbsga.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gttumyokjz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.smart0.xyz/Article/details/gtkcgftqnv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.sufxvd.cn/Article/details/gtumbrpltu.html

JS:   e.message;  e.stack
来源：http://dali.zhixingplan.top/Article/details/gtrqjgeelx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ybcxt.top/Article/details/gtozmrnhko.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.mhx1999.top/Article/details/gtixtkuats.html

Go:   err.Error()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmflhgaz.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhixingplan.top/Article/details/gtbbwsqedq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gthghkyfwq.html

[H09] 带错误码的异常
来源：http://dali.jyoumei.cn/Article/details/gtkevetdwx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shuidangran.top/Article/details/gtbcojyryr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hammf.cn/Article/details/gtytkfjrfh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.kuanghao11.cn/Article/details/gtulhxecqv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aizwys.cn/Article/details/gtxxlxsfbk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxuanxn.top/Article/details/gttlnqptkf.html


<!-- 参考信息 -->