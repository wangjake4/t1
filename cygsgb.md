代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtxblvkocn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhijiandao.cn/Article/details/gtcmgvgqcb.html

PHP:  file_exists("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtsdiclsrj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyezimsu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtroximpbk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gthmrstiid.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ppjwa.cn/Article/details/gtlkrugnsk.html

Ruby: File.exist?("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtpgdvhcxf.html

C#:   File.Exists("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtdkuubsav.html

[F06] 删除文件
来源：http://dali.kuanghao11.cn/Article/details/gtpilrjmbh.html

Py:   os.remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtekbqyzix.html

PHP:  unlink("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtmyljpebd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtupjykwvm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtpdpthrlt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyguscpn.html

Go:   os.Remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gtjiorhexd.html

Ruby: File.delete("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtsrkpgdwx.html

C#:   File.Delete("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtjndhhgtr.html

[F07] 创建目录（含多级）
来源：http://dali.pengpengdd.cyou/Article/details/gtebdctvaw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtevjvpyrv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrebctha.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtiaupeacy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtsylfgmou.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aibaodan.cn/Article/details/gtrdqhdrcb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsynuhsnx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tanke756.top/Article/details/gtphvotugo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gtyntpbkyr.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gtpzpdzjxv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuanzhike.top/Article/details/gtoowlryjh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gtqgygijgj.html

JS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtohfskzbd.html

TS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtghmgqkct.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gtcdktanlj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xinyue.icu/Article/details/gtoihbldfa.html

Ruby: Dir.children("dir")
来源：http://dali.ybcxt.top/Article/details/gtdehwqiid.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtjarzxafx.html

[F09] 获取文件大小
来源：http://dali.jqgufenzy.top/Article/details/gtfvjvznot.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtrjrczowz.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gteuzfmqdz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtakzgiayy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtswuopdgh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtmbqwpdar.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gtrpklogso.html

Ruby: File.size("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtrvaqypre.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigufen.top/Article/details/gtmkrfwyxq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dashuyun.cn/Article/details/gtcwruramw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtbmprspws.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtzzojfcgp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtvcpclgzx.html

TS:   path.extname("a.txt")
来源：http://dali.pycfn.com/Article/details/gtuobjtqba.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenjidiqi.icu/Article/details/gterwuedpf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtqlomzblq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtysothiav.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtqvyguanp.html

[F11] 复制与移动文件
来源：http://dali.chenzaomai.com/Article/details/gtnwzzrytb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gteahamklk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj202588.top/Article/details/gtmwklbibj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtpfbcculr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtvjiopwtz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.mhx1999.top/Article/details/gteitqwcrp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gtbavzubtk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtjykhahju.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hfpthk.cn/Article/details/gtvpysynzj.html

[F12] CSV 读写
来源：http://dali.zhengqikj.top/Article/details/gtotfgecyz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.vqdsnc.cn/Article/details/gttuylzwjl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxlixqyk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gtacrwbwdx.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gtrkyfyepv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jlsjyb.cn/Article/details/gthbmgoqbz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlbwtchy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangshuangyany.cn/Article/details/gtczhdebth.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shuidangran.top/Article/details/gtwreiiyty.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtikppxdyy.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gtwimbcdib.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtkvrtpmhd.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gtrwidsfwj.html

Py:   class User: pass
来源：http://dali.xinyue.icu/Article/details/gtgxxaoiqg.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gtnkdtrkgt.html

JS:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gtbfryyomd.html

TS:   class User { name: string = ""; }
来源：http://dali.ydzc1.top/Article/details/gtopukkwvb.html

Java: class User {}
来源：http://dali.yj20258.top/Article/details/gtkddgtrza.html

Go:   type User struct { Name string }
来源：http://dali.xylfe.cn/Article/details/gtpomuygen.html

Ruby: class User; end
来源：http://dali.snrcjt.cn/Article/details/gtqzxfdedo.html

C#:   class User {}
来源：http://dali.sweek.top/Article/details/gtpfsgdhkc.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gtuamnagns.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daria6918.cn/Article/details/gttgubzuhz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sufxvd.cn/Article/details/gtydzusedy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrkrhivdx.html

TS:   constructor(public name: string) {}
来源：http://dali.cucudq.cn/Article/details/gtbmuymfjc.html

Java: User(String name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gtilsptfqe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.mhx1999.top/Article/details/gtnblfsqot.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xziqi.cn/Article/details/gtwvckgkuy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtuqxbswki.html

[G03] 实例属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplqbuuao.html

Py:   self.name = "x"
来源：http://dali.hfpthk.cn/Article/details/gtkxczaczn.html

PHP:  public string $name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gteurdnftf.html

JS:   this.name = "x";
来源：http://dali.jinqigufen.top/Article/details/gtppnehdgv.html

TS:   name: string = "x";
来源：http://dali.hysaishi.cn/Article/details/gtvsymniqk.html

Java: private String name;
来源：http://dali.hysaishi.cn/Article/details/gtxwcysjpj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gtqhevrwyb.html

Ruby: @name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtrpszpdsn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtdrsrzcws.html

[G04] 定义方法
来源：http://dali.yueranfly.top/Article/details/gtjnspkefe.html

Py:   def greet(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gttsjprucu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpdquqxs.html

JS:   greet() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtsfagrksh.html

TS:   greet(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtksxgkzod.html

Java: String greet() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtaylfaqvl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtsapjvdxz.html

Ruby: def greet; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtzazfnqrd.html

C#:   public string Greet() => Name;
来源：http://dali.haohaochexian.top/Article/details/gtmzxdqmwb.html

[G05] 继承
来源：http://dali.chenzaomai.com/Article/details/gtxmnamczs.html

Py:   class Admin(User): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtyemroesk.html

PHP:  class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtkuvdxxbn.html

JS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gthgcdnshl.html

TS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtoulmiigg.html

Java: class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtgnvbaruz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.andypj.xyz/Article/details/gtrryfwkbf.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gtccixzdkg.html

C#:   class Admin : User {}
来源：http://dali.jinqigufen.top/Article/details/gtgezszpyq.html

[G06] 重写方法
来源：http://dali.cashguo.top/Article/details/gtijrbhlwf.html

Py:   def greet(self): return "admin"
来源：http://dali.birdmap.top/Article/details/gtimzsnbin.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtuxyubrsi.html

JS:   greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtljtqujpt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtveziagpp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtsyeikani.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoktizjqe.html

Ruby: def greet; "admin"; end
来源：http://dali.jyoumei.cn/Article/details/gtwmcxaizm.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnnesdtl.html

[G07] 调用父类方法
来源：http://dali.xinyue.icu/Article/details/gtljwlgspm.html

Py:   super().greet()
来源：http://dali.meibo888.top/Article/details/gtigkpskkx.html

PHP:  parent::greet();
来源：http://dali.daxiang520.top/Article/details/gtnrooqhij.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gtxupbjfiv.html

TS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtgivvrjpq.html

Java: super.greet();
来源：http://dali.wangdashe.top/Article/details/gtyfjqmqlv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tianlin.xyz/Article/details/gtedtgsitj.html

Ruby: super
来源：http://dali.nanxinkj.top/Article/details/gtaxtjnnrz.html

C#:   base.Greet();
来源：http://dali.bjfxy.top/Article/details/gtxjkrzzfg.html

[G08] 静态方法与属性
来源：http://dali.xziqi.cn/Article/details/gttkzswaqo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gtoityrqlr.html

PHP:  public static function f() {}
来源：http://dali.daria6918.cn/Article/details/gthpluajhy.html

JS:   static f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzszaokpj.html

TS:   static f(): void {}
来源：http://dali.sxryk.cn/Article/details/gttyffgnie.html

Java: static void f() {}
来源：http://dali.jiagoushi.top/Article/details/gtepdfltfl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gtxfosjlky.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofmpebiw.html

C#:   public static void F() {}
来源：http://dali.316326.xyz/Article/details/gtjhufiarb.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigfzy.top/Article/details/gtreikaoeg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gtyxqmdfbs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.haohaochexian.top/Article/details/gtdqovbktn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yonumen.top/Article/details/gtxzvaevyu.html

TS:   interface Shape { area(): number; }
来源：http://dali.meibo888.top/Article/details/gtekjtsvlt.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gtyjyicbdx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tian-w.cn/Article/details/gtlnhodxun.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gtajrrtxty.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgzgboeen.html

[G10] 访问控制
来源：http://dali.jiagoushi.top/Article/details/gtqenwmeyz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgupjzfic.html

PHP:  public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtcsmzndrw.html

JS:   #private 字段；其余公开
来源：http://dali.bjfxy.top/Article/details/gtdzdpuiwu.html

TS:   public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtodomoyta.html

Java: public / protected / private / 默认包级
来源：http://dali.sysykeji.top/Article/details/gtrmxrrmkp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gtxydpedht.html

Ruby: public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtrbkbghso.html

C#:   public / protected / private / internal
来源：http://dali.hfpthk.cn/Article/details/gtygwdywum.html

[G11] getter / setter
来源：http://dali.xuetiantiany.cn/Article/details/gtwptbehbc.html

Py:   @property 与 @x.setter
来源：http://dali.sxryk.cn/Article/details/gtcsduvchn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtykizruyi.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gtufqfknsu.html

TS:   get name(): string { return this._name; }
来源：http://dali.hywenlv.cn/Article/details/gtjurknrso.html

Java: public String getName() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtlyswycnw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtzmfjjylq.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gtivbfzgig.html

C#:   public string Name { get; set; }
来源：http://dali.chenjidiqi.icu/Article/details/gtomajbmoc.html

[G12] 对象转字符串
来源：http://dali.zhixingplan.top/Article/details/gttkrxflik.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtsisaicsh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtsfprplwq.html

JS:   toString() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtkekqvtdj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtuyiqupmi.html

Java: @Override public String toString() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtizmnqjla.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtqpksmcnd.html

Ruby: def to_s; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtngwwppoh.html

C#:   public override string ToString() => Name;
来源：http://dali.andypj.xyz/Article/details/gtgwqteaju.html

[G13] 判断对象类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpakorsro.html

Py:   isinstance(u, User)
来源：http://dali.smart0.xyz/Article/details/gtyrbsrfql.html

PHP:  $u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtrzircvmb.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtklpxmkmb.html

TS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gttpkslqmv.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gtnivthpof.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gtvtdwyceo.html

Ruby: u.is_a?(User)
来源：http://dali.ivvv.top/Article/details/gtmiphoeja.html

C#:   u is User
来源：http://dali.shangyingyoupin.top/Article/details/gtbjqigvcw.html

[G14] 数据类 / record
来源：http://dali.xuanzx.com/Article/details/gtfwdbohmc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gtermlfune.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zdqjudy.top/Article/details/gtkfatjdwf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zycfv.cn/Article/details/gteifdezix.html

TS:   type User = { name: string; age: number };
来源：http://dali.tian-w.cn/Article/details/gtfgivllok.html

Java: record User(String name, int age) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvtdnvoe.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zdqjudy.top/Article/details/gtwzqqxggf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.havefunace.top/Article/details/gtennbkyuq.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gtggktmstv.html

[G15] 枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtjfcwpjsy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.birdmap.top/Article/details/gtcfslpnhm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daxiang520.top/Article/details/gtqznesfpu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gtmklyqxut.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtzandfrjk.html

Java: enum Color { RED, GREEN }
来源：http://dali.cheryme.top/Article/details/gtvtrqgzpl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ivvv.top/Article/details/gtsxwimupa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gtzabpjoek.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtayzvhfry.html

[G16] 对象转数组 / 字典
来源：http://dali.yj202588.top/Article/details/gtvbllbwrw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xinyue.icu/Article/details/gtixvbxwsf.html

PHP:  get_object_vars($obj);
来源：http://dali.sufxvd.cn/Article/details/gtkozfnwxx.html

JS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtbempymbm.html

TS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtbjmhrmmf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gtxouqghgu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gtfmemkvpv.html

Ruby: obj.instance_variables
来源：http://dali.yuanzhike.top/Article/details/gtwccnudja.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gtdavxwzik.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtckerhctc.html

H. 异常与错误处理
来源：http://dali.jlsjyb.cn/Article/details/gtodkitohm.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtohpcebgn.html

[H01] try / catch 基础
来源：http://dali.jyoumei.cn/Article/details/gtzeyswipz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gtgitmlcfj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gtmojopfol.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtiugxbays.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtirstpvhx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgfuqjli.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxinkj.top/Article/details/gtbitzpkpv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenjidiqi.icu/Article/details/gtyxbsxjrg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pengpengdd.cyou/Article/details/gtnbfloaxh.html

[H02] finally / ensure 收尾
来源：http://dali.sysykeji.top/Article/details/gtyegqrrry.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tian-w.cn/Article/details/gtgfgqbqvf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtnlybfvqr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtyjkpqibh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtqgysjngd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtyqrfkxkz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnxiangtu.top/Article/details/gtkjvnxbrb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gtocxnnimp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtuhhnfmgh.html

[H03] 主动抛出异常
来源：http://dali.daxiang520.top/Article/details/gtravuwgtv.html

Py:   raise ValueError("错误信息")
来源：http://dali.jlsjyb.cn/Article/details/gtnrwumfhd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtzlhlonxg.html

JS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtctaicimr.html

TS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtciynnkeb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtvxqjjzrf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhongyouzk.top/Article/details/gtpfgcdgxw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.316326.xyz/Article/details/gtiiqphuvo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtbjcjzhzz.html

[H04] 自定义异常类型
来源：http://dali.smart0.xyz/Article/details/gtuglpvkex.html

Py:   class MyError(Exception): pass
来源：http://dali.guannengcc.top/Article/details/gtkzqudbme.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuanzhike.top/Article/details/gtlvzuvzhc.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtakneofwk.html

TS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtcacltolc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gtonvyyulj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yvedp.cn/Article/details/gtgxgxawav.html

Ruby: class MyError < StandardError; end
来源：http://dali.bjfxy.top/Article/details/gtwmpsadfn.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gtuspdvkmk.html

[H05] 捕获特定类型
来源：http://dali.sufxvd.cn/Article/details/gtvpuxonnm.html

Py:   except ValueError as e:
来源：http://dali.cucudq.cn/Article/details/gtebpkpdzq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangdashe.top/Article/details/gteaeoacpt.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtiibfpowp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrnobyln.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupkgyved.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangtech.top/Article/details/gthktgopgb.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyueaqdf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gtnlitciis.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gzhubu.top/Article/details/gtxhntpkvt.html

Py:   value = d.get("k") or default
来源：http://dali.quarkkingdee.top/Article/details/gtkkqlmbgp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gttjyquysu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtuqxklpeh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvlsorzn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuaxrctcw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhongyouzk.top/Article/details/gtsupuutmj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cdnleiting.top/Article/details/gtqbouernq.html

C#:   obj?.A?.B ?? default
来源：http://dali.yvedp.cn/Article/details/gtdpkwrrgy.html

[H07] 断言
来源：http://dali.chenzaomai.com/Article/details/gtmridzikh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkpzehdn.html

PHP:  assert($x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtcsuptive.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfakyvgi.html

TS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtolydkpkn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fzhhl.top/Article/details/gtaaimksgn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daxiang520.top/Article/details/gtgoxepmri.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.iojbl.cn/Article/details/gtafaddtrx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfssfyqwi.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gtalibtogy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gtpjnmslte.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gtldscovyv.html

JS:   e.message;  e.stack
来源：http://dali.gaohongyu789.top/Article/details/gtxihwmosa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jyoumei.cn/Article/details/gtyxhmdbnm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.316326.xyz/Article/details/gtmqviybwz.html

Go:   err.Error()
来源：http://dali.yangfankeji.com/Article/details/gtjyxxurfk.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gtqasxxnvp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.mhx1999.top/Article/details/gtgpdhddof.html

[H09] 带错误码的异常
来源：http://dali.ehwqpu.com/Article/details/gtselblgxc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nwbrower.top/Article/details/gtcfueenyv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hnqzz.top/Article/details/gtlcukdalp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gtestqysnf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgfzy.top/Article/details/gtcnxbazyl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shzxlz.cn/Article/details/gtzktgnrjw.html


<!-- 参考信息 -->