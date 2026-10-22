代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lqdyjsvt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2vmgjbnba.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gt2ogtrlirv.html

Ruby: File.exist?("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2ybmauptm.html

C#:   File.Exists("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2cfgjgnim.html

[F06] 删除文件
来源：http://dali.jinqigufen.top/Article/details/gt2aaprprxt.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2ktqxuoyu.html

PHP:  unlink("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2nukayete.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2swdpyloz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxvlunw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gt2ujjsratz.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2bdwmizty.html

Ruby: File.delete("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2xxcacief.html

C#:   File.Delete("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2ksiottoj.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gt2cdkabfgs.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ivvv.top/Article/details/gt2ysgvgpmk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cqqwz.cn/Article/details/gt2nvpiyesh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gt2fibzjhzs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gt2uvurzdvw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnqzz.top/Article/details/gt2qongydpz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fzhhl.top/Article/details/gt2jcwyfqpa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenlongwang.top/Article/details/gt2sexeastf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.birdmap.top/Article/details/gt2ggbephjs.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gt2mnwcdnhb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gt2cntdgesu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aizwys.cn/Article/details/gt2wupsujib.html

JS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2uejrscvi.html

TS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gt2ymlcimlp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gt2nazwzgrj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2uxbwgzyx.html

Ruby: Dir.children("dir")
来源：http://dali.zycfv.cn/Article/details/gt2ruuroojv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2nwfqglob.html

[F09] 获取文件大小
来源：http://dali.bjfxy.top/Article/details/gt2umrygojq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2osbvtcff.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2kudvnohg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gt2xuapfrbh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gt2opgddsha.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gt2iksbhmyc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xinyue.icu/Article/details/gt2azboovcd.html

Ruby: File.size("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqpdrvfn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xinyue.icu/Article/details/gt2zwtksphg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gt2dexepgcl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2mwfwhpdv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cheryme.top/Article/details/gt2ttobbkrh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2jmswfcel.html

TS:   path.extname("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2rnfxxrzx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuetiantiany.cn/Article/details/gt2atmxfmyf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ogxaaybn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2ggkxrpji.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2xpzawbth.html

[F11] 复制与移动文件
来源：http://dali.yongpay.top/Article/details/gt2iegroaoc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2bctokjpu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.c1oappe.top/Article/details/gt2cflvchpt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kmhdxptp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gt2jldmhkey.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xziqi.cn/Article/details/gt2zlwtzegm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gt2nefulysy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2uzhzuqua.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gt2ookgppmf.html

[F12] CSV 读写
来源：http://dali.fzhhl.top/Article/details/gt2uxssgbix.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gt2sywcfesh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gt2tmjzwrpa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cashguo.top/Article/details/gt2psrbnjvq.html

TS:   // 同上
来源：http://dali.xylfe.cn/Article/details/gt2supautxs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.meibo888.top/Article/details/gt2xzacddvf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gt2jktmrwuh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xyrzhfbo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhoulong.xyz/Article/details/gt2xvcienks.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2xlkzrldj.html

G. 面向对象
来源：http://dali.ppjwa.cn/Article/details/gt2exkcagbe.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2vepgnyhs.html

[G01] 定义类
来源：http://dali.gzhubu.top/Article/details/gt2bblxworb.html

Py:   class User: pass
来源：http://dali.yuxming.cn/Article/details/gt2wmozryyc.html

PHP:  class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2uzaxazqd.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2lmdiypyq.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qfeynhmj.html

Java: class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2vdsfjflv.html

Go:   type User struct { Name string }
来源：http://dali.yuxming.cn/Article/details/gt2nychnhee.html

Ruby: class User; end
来源：http://dali.quarkkingdee.top/Article/details/gt2nhczidog.html

C#:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2uzzgwgqu.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gt2wulyirkn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuanzx.com/Article/details/gt2ojhxkevz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cheryme.top/Article/details/gt2uvoskaao.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2emwqdjqp.html

TS:   constructor(public name: string) {}
来源：http://dali.sufxvd.cn/Article/details/gt2kymsjzmd.html

Java: User(String name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gt2xatgkxnr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gt2gbpzbfcl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dashuyun.cn/Article/details/gt2jgmrmygj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2rjnqezaz.html

[G03] 实例属性
来源：http://dali.ehwqpu.com/Article/details/gt2hgsvrrzu.html

Py:   self.name = "x"
来源：http://dali.redwolf501.top/Article/details/gt2nkuyyogx.html

PHP:  public string $name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2aeqynxxi.html

JS:   this.name = "x";
来源：http://dali.haohaochexian.top/Article/details/gt2jlqfifda.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gt2tyhynjyx.html

Java: private String name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntzttnkp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dianchejie.cn/Article/details/gt2boewzoei.html

Ruby: @name = "x"
来源：http://dali.fzhhl.top/Article/details/gt2ppkkldzf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.haohaochexian.top/Article/details/gt2embcftvo.html

[G04] 定义方法
来源：http://dali.yj20258.top/Article/details/gt2qxccphfr.html

Py:   def greet(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2erlcczbx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gt2cwvqzczb.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2dmqudaud.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2vzigcykp.html

Java: String greet() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2ubktskck.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gt2ildubyhu.html

Ruby: def greet; @name; end
来源：http://dali.dashuyun.cn/Article/details/gt2wugekucz.html

C#:   public string Greet() => Name;
来源：http://dali.guowangkeji.top/Article/details/gt2pvxzxliq.html

[G05] 继承
来源：http://dali.gaohongyu789.top/Article/details/gt2bgmyplgq.html

Py:   class Admin(User): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vjiwkyfc.html

PHP:  class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2myouoypm.html

JS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2ignnqwfu.html

TS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2fkysfiki.html

Java: class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2qedjtrmj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sysykeji.top/Article/details/gt2nrpaffzc.html

Ruby: class Admin < User; end
来源：http://dali.wangdashe.top/Article/details/gt2nplhtqfv.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2xkmnufyc.html

[G06] 重写方法
来源：http://dali.gotoacloud.top/Article/details/gt2oryxufth.html

Py:   def greet(self): return "admin"
来源：http://dali.jlsjyb.cn/Article/details/gt2ybtczetd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2hdixjrrp.html

JS:   greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2zlwwteiz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2teeypfca.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2hinigirs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhoulong.xyz/Article/details/gt2zrvunpbm.html

Ruby: def greet; "admin"; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2rzjtpext.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uipfstcx.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqynvjh.html

Py:   super().greet()
来源：http://dali.jiagoushi.top/Article/details/gt2tphaoutj.html

PHP:  parent::greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2uvzhnnqf.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gt2geacbwhc.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2brmsuklg.html

Java: super.greet();
来源：http://dali.tanke756.top/Article/details/gt2duhhbfqe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxinkj.top/Article/details/gt2uqdcxnns.html

Ruby: super
来源：http://dali.sufxvd.cn/Article/details/gt2iruksjxn.html

C#:   base.Greet();
来源：http://dali.cheryme.top/Article/details/gt2vqneccyf.html

[G08] 静态方法与属性
来源：http://dali.yangfankeji.com/Article/details/gt2lryzgwtu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shzxlz.cn/Article/details/gt2hpzjljoj.html

PHP:  public static function f() {}
来源：http://dali.iojbl.cn/Article/details/gt2pmnllklg.html

JS:   static f() {}
来源：http://dali.mhx1999.top/Article/details/gt2xvjlvjsu.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gt2tguqqell.html

Java: static void f() {}
来源：http://dali.tianlin.xyz/Article/details/gt2jjrlnwvj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yueranfly.top/Article/details/gt2lzwieuob.html

Ruby: def self.f; end
来源：http://dali.shzxlz.cn/Article/details/gt2dtuizkef.html

C#:   public static void F() {}
来源：http://dali.shzxlz.cn/Article/details/gt2xnojxyfm.html

[G09] 接口 / 抽象类
来源：http://dali.pengpengdd.cyou/Article/details/gt2tbkzjuws.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258.top/Article/details/gt2frsshykg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258.top/Article/details/gt2ovjpqrvz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dashuyun.cn/Article/details/gt2knzrherj.html

TS:   interface Shape { area(): number; }
来源：http://dali.shuidangran.top/Article/details/gt2yjopwxbl.html

Java: interface Shape { double area(); }
来源：http://dali.hfpthk.cn/Article/details/gt2rcretkvr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tanke756.top/Article/details/gt2trqkptlw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ybcxt.top/Article/details/gt2vmbcupdh.html

C#:   interface IShape { double Area(); }
来源：http://dali.zdqjudy.top/Article/details/gt2lsptfnai.html

[G10] 访问控制
来源：http://dali.cdnleiting.top/Article/details/gt2hosfbuqt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2souclfsm.html

PHP:  public / protected / private
来源：http://dali.gzhubu.top/Article/details/gt2zajjkibn.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gt2uwentbww.html

TS:   public / protected / private
来源：http://dali.yj20258.top/Article/details/gt2yagpantw.html

Java: public / protected / private / 默认包级
来源：http://dali.havefunace.top/Article/details/gt2treynngl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hywenlv.cn/Article/details/gt2xowiairw.html

Ruby: public / protected / private
来源：http://dali.cashguo.top/Article/details/gt2ryfqcefb.html

C#:   public / protected / private / internal
来源：http://dali.yanxiufei.cn/Article/details/gt2hjowhohi.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gt2ychonxgb.html

Py:   @property 与 @x.setter
来源：http://dali.smart0.xyz/Article/details/gt2poeneavt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2qlhvjyqb.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gt2rqyxrdmc.html

TS:   get name(): string { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gt2jgxnpoxs.html

Java: public String getName() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gt2hwmuqyca.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gt2rlgchfln.html

Ruby: attr_accessor :name
来源：http://dali.0kj1m.cn/Article/details/gt2xgsnbgpn.html

C#:   public string Name { get; set; }
来源：http://dali.redwolf501.top/Article/details/gt2xgfyjxcr.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gt2awwnqrsj.html

Py:   def __str__(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gt2dcnthgoe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2fnrybkep.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aussypgt.html

TS:   toString(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2wudkmfbh.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gt2qmotxuum.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gt2zdmxfzti.html

Ruby: def to_s; @name; end
来源：http://dali.nwbrower.top/Article/details/gt2cdfixovd.html

C#:   public override string ToString() => Name;
来源：http://dali.pycfn.com/Article/details/gt2bxoyelcx.html

[G13] 判断对象类型
来源：http://dali.meibo888.top/Article/details/gt2jcyztlvm.html

Py:   isinstance(u, User)
来源：http://dali.hnxiangtu.top/Article/details/gt2sojmuczt.html

PHP:  $u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gt2zqxhwpwy.html

JS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2jfwmexym.html

TS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xttkxeeu.html

Java: u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gt2uhvhrrcn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gt2eiebsuvz.html

Ruby: u.is_a?(User)
来源：http://dali.redwolf501.top/Article/details/gt2zoewhbgm.html

C#:   u is User
来源：http://dali.xuanzx.com/Article/details/gt2mufgaabv.html

[G14] 数据类 / record
来源：http://dali.ybcxt.top/Article/details/gt2nvwzoqig.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.mhx1999.top/Article/details/gt2opxibech.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.meibo888.top/Article/details/gt2oxvdpzdb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sysykeji.top/Article/details/gt2bpdaflno.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuetiantiany.cn/Article/details/gt2uppqzrlx.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gt2uvxhjtvg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gt2hgpyruin.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gt2kjddzinb.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gt2bqwdogwi.html

[G15] 枚举
来源：http://dali.tanke756.top/Article/details/gt2xqighoge.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yongpay.top/Article/details/gt2dhgseuaj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangdashe.top/Article/details/gt2czvhgeqz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gt2rtkbncot.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gt2wtoyyrhl.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gt2fjnwlkac.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gt2qkmkqull.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gt2pqvhibte.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2llceuspb.html

[G16] 对象转数组 / 字典
来源：http://dali.andypj.xyz/Article/details/gt2bjiypifa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.vqdsnc.cn/Article/details/gt2tacbjzcb.html

PHP:  get_object_vars($obj);
来源：http://dali.shuidangran.top/Article/details/gt2kdajooyz.html

JS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2youhqigj.html

TS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gt2ztwjapro.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cheryme.top/Article/details/gt2rqirxopy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daria6918.cn/Article/details/gt2nanusydf.html

Ruby: obj.instance_variables
来源：http://dali.smart0.xyz/Article/details/gt2qlvmydgy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gt2lgstdamy.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ncmakatk.html

H. 异常与错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gt2txxwphpu.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2qnssaljl.html

[H01] try / catch 基础
来源：http://dali.chenlongwang.top/Article/details/gt2ubiiteav.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ybcxt.top/Article/details/gt2onaaibqk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gt2nsvuzzoq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gt2mciwqcqf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gt2qvyprork.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tian-w.cn/Article/details/gt2uavrxxgh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2vjdfopcn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gt2bchskvtx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gt2umtyaxjy.html

[H02] finally / ensure 收尾
来源：http://dali.yueranfly.top/Article/details/gt2ftvkiugm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.iojbl.cn/Article/details/gt2rvvjeczp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gt2milecmyd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2rbhvmfmt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2mlddqpmq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hksblmes.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aibaodan.cn/Article/details/gt2cfnianot.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gt2zugdcjme.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2hqpciebb.html

[H03] 主动抛出异常
来源：http://dali.xylfe.cn/Article/details/gt2qzgvyebv.html

Py:   raise ValueError("错误信息")
来源：http://dali.xziqi.cn/Article/details/gt2fksertto.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2fncqybec.html

JS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2qbgdlsef.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2cduyfbdh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2yoqitynq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnqzz.top/Article/details/gt2petwrdzc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tpgdlgtx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2abpwymma.html

[H04] 自定义异常类型
来源：http://dali.jianghu66.top/Article/details/gt2gxfxnccm.html

Py:   class MyError(Exception): pass
来源：http://dali.daxiang520.top/Article/details/gt2zijlfcne.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gt2iwwvdwlz.html

JS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gt2wjwyqgsj.html

TS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gt2ifvgtffs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gt2ipqeautc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgfzy.top/Article/details/gt2xfrohwxm.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2luuxkzsk.html

C#:   class MyException : Exception {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2gzacgfea.html

[H05] 捕获特定类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2obbvpsct.html

Py:   except ValueError as e:
来源：http://dali.fzhhl.top/Article/details/gt2cggtfrjk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pycfn.com/Article/details/gt2fkjffbvr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gt2cppssehk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gt2thwqshdc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenlongwang.top/Article/details/gt2xezgrxnt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sxryk.cn/Article/details/gt2jghcuwsf.html

Ruby: rescue ArgumentError => e
来源：http://dali.iojbl.cn/Article/details/gt2naaogowm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuanzhike.top/Article/details/gt2ainysuls.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gt2qkmgzsre.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gt2yqagdgjh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gt2jlpbcgva.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gt2zuvsijgn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2khgfxjwm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangdashe.top/Article/details/gt2twfrzswb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yqjeeunb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ipafruil.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gt2lrpxzosq.html

[H07] 断言
来源：http://dali.ppjwa.cn/Article/details/gt2knvjlrqn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daria6918.cn/Article/details/gt2wthqstlc.html

PHP:  assert($x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2izmnwtdm.html

JS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2hlmtsflq.html

TS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2egtgnghr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gogol.net.cn/Article/details/gt2giegdulk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hongshengwenyu.top/Article/details/gt2cvwaoumo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daria6918.cn/Article/details/gt2wzztqjle.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2dgfgchef.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinghuilouyu.cn/Article/details/gt2knddfwgi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fzhhl.top/Article/details/gt2qcmtdmhr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dashuyun.cn/Article/details/gt2zwftmfjb.html

JS:   e.message;  e.stack
来源：http://dali.zhiwuduotai.top/Article/details/gt2jcxryuky.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tianlin.xyz/Article/details/gt2ulxmrpem.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zxiwhwgw.html

Go:   err.Error()
来源：http://dali.hnqzz.top/Article/details/gt2plafljli.html

Ruby: e.message;  e.backtrace
来源：http://dali.birdmap.top/Article/details/gt2wumelzyi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jlsjyb.cn/Article/details/gt2jwmxehkj.html

[H09] 带错误码的异常
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxdqskvb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ppjwa.cn/Article/details/gt2sjrrcvfp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhoulong.xyz/Article/details/gt2webhcgkx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pxbxbrsz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gotoacloud.top/Article/details/gt2tgbsidfz.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gt2cpcsrmbv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hfpthk.cn/Article/details/gt2vjdquzre.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhoulong.xyz/Article/details/gt2pqkaxcrj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gt2lgvvhhkg.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gt2vydbswol.html


<!-- 参考信息 -->