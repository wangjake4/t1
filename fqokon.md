代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hywenlv.cn/Article/details/gttvqpsajg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtyhtbzdoo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daxiang520.top/Article/details/gtcmwwmpru.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tian-w.cn/Article/details/gtcesibuea.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gtkuncqmza.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.birdmap.top/Article/details/gtdjigfetj.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtvzizjorx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gttftzskwe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtmfoamqrb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtsdvfqznk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shangyingyoupin.top/Article/details/gtqqjhjmar.html

Ruby: File.exist?("a.txt")
来源：http://dali.fzhhl.top/Article/details/gttybpmxda.html

C#:   File.Exists("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtqbcnucvz.html

[F06] 删除文件
来源：http://dali.chenzaomai.com/Article/details/gtxiqjhrep.html

Py:   os.remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtehpwurhl.html

PHP:  unlink("a.txt");
来源：http://dali.hnqzz.top/Article/details/gthgadhlew.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtjuasosfu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtwiudwfjh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtkzcneoyz.html

Go:   os.Remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtczhzymxd.html

Ruby: File.delete("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gthemcanlf.html

C#:   File.Delete("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtldjsuviz.html

[F07] 创建目录（含多级）
来源：http://dali.gotoacloud.top/Article/details/gttwjrxdqi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gtuijyksyg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.9152youxi.cn/Article/details/gtwuqlxcgu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtqtpomobh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gtrxnwqtzv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gogol.net.cn/Article/details/gtcwblvzix.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fzhhl.top/Article/details/gtkmuacpms.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.c1oappe.top/Article/details/gteyvrejdx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gtxpbfykmw.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gtukfbthhr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwyogrcqj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gtnddpxiey.html

JS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtjigvizvd.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gttwzohdvb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtnoudfjwt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtknhjugsh.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gtlrpeeyzc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtixiilert.html

[F09] 获取文件大小
来源：http://dali.cdnleiting.top/Article/details/gtvapdclxo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtvnkjqcqr.html

PHP:  filesize("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gthkghonsm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gtidujkgtv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gtfrygwtfj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtomwvwxwl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aibaodan.cn/Article/details/gtovggmnrh.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtbhmvufay.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhiwuduotai.top/Article/details/gtxprwgljw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.0kj1m.cn/Article/details/gtyllaswvq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtkotwlwwv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtuqtwdwzv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtwdepmfgn.html

TS:   path.extname("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtqdnlnfup.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenjidiqi.icu/Article/details/gtvgqnwojz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtdtgrfaoi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtgljymhlp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gteaixcbek.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gtpepntqbx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gttehupzub.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cucudq.cn/Article/details/gttqoquwuz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtmgripviy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtbymkpmxn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtarddhkae.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuanzhike.top/Article/details/gtjtwlhysk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljtknyxc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cheryme.top/Article/details/gtyouhhjxe.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gthveuwnxv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tian-w.cn/Article/details/gtcjfyapvi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gaohongyu789.top/Article/details/gtqdehdzqy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ivvv.top/Article/details/gtbapiwjqf.html

TS:   // 同上
来源：http://dali.cheryme.top/Article/details/gtpegnuusp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zdqjudy.top/Article/details/gtdwdefcip.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tanke756.top/Article/details/gtxgbhopki.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sufxvd.cn/Article/details/gtrqmihxpr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ybcxt.top/Article/details/gtnvzwbctk.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtlufiosel.html

G. 面向对象
来源：http://dali.xuanzx.com/Article/details/gtecqtjyxw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtvjmmrfsl.html

[G01] 定义类
来源：http://dali.chenjidiqi.icu/Article/details/gtneeadtzq.html

Py:   class User: pass
来源：http://dali.pycfn.com/Article/details/gtkmkfuppc.html

PHP:  class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtvzfdrmej.html

JS:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuuntrpq.html

TS:   class User { name: string = ""; }
来源：http://dali.zhiwuduotai.top/Article/details/gttqdretuv.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gtaoxbcwox.html

Go:   type User struct { Name string }
来源：http://dali.zhiwuduotai.top/Article/details/gtxoegmqkp.html

Ruby: class User; end
来源：http://dali.shzxlz.cn/Article/details/gtwqkmowgw.html

C#:   class User {}
来源：http://dali.xylfe.cn/Article/details/gtcuekwgbx.html

[G02] 构造函数
来源：http://dali.tianlin.xyz/Article/details/gtdvmcccqz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aizwys.cn/Article/details/gtwzzrhbfb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aibaodan.cn/Article/details/gtnjaejxcb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtdsfosddx.html

TS:   constructor(public name: string) {}
来源：http://dali.kuanghao11.cn/Article/details/gtwwmgwwjx.html

Java: User(String name) { this.name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgghtteyu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sweek.top/Article/details/gtjjqaiwxl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gtswirygcn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yueranfly.top/Article/details/gtjwwctmrp.html

[G03] 实例属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfvbbjbi.html

Py:   self.name = "x"
来源：http://dali.yongpay.top/Article/details/gthngpjipu.html

PHP:  public string $name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtxbztlaum.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gtwlleoevl.html

TS:   name: string = "x";
来源：http://dali.ppjwa.cn/Article/details/gtrqfxgszy.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gtsrfjdgyi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtxdphsvnc.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtdxptstsz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ehwqpu.com/Article/details/gtgessgspd.html

[G04] 定义方法
来源：http://dali.hnxiangtu.top/Article/details/gtswclhzod.html

Py:   def greet(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtecwvypzp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtibpdluiq.html

JS:   greet() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkswvmdz.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtenrgjqqs.html

Java: String greet() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdhqqcco.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtrwrplvgz.html

Ruby: def greet; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtnjryfsvs.html

C#:   public string Greet() => Name;
来源：http://dali.yvedp.cn/Article/details/gtbuothbwx.html

[G05] 继承
来源：http://dali.yanxiufei.cn/Article/details/gteljkbctg.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gtqwucrazu.html

PHP:  class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtifxhqman.html

JS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtrjxfhxmr.html

TS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtltsgekrw.html

Java: class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtpbuucggm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.kuanghao11.cn/Article/details/gtfvqcoxzo.html

Ruby: class Admin < User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkydzdfh.html

C#:   class Admin : User {}
来源：http://dali.hnxiangtu.top/Article/details/gtkjbqwqai.html

[G06] 重写方法
来源：http://dali.jinqigufen.top/Article/details/gtktivfrnu.html

Py:   def greet(self): return "admin"
来源：http://dali.gzhubu.top/Article/details/gtmuomqpjd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtusnkhnby.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtlnvteytk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtrfxegmjt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gtfurqqcne.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258888.top/Article/details/gtzoocfxdl.html

Ruby: def greet; "admin"; end
来源：http://dali.shzxlz.cn/Article/details/gtxcupdmif.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gtkcfgnwzt.html

[G07] 调用父类方法
来源：http://dali.yvedp.cn/Article/details/gtdwdexybe.html

Py:   super().greet()
来源：http://dali.pengpengdd.cyou/Article/details/gtbrmpbphx.html

PHP:  parent::greet();
来源：http://dali.andypj.xyz/Article/details/gtddnvfzmd.html

JS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtaiulgbsk.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtdksgduhe.html

Java: super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtxlttwnsl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fzhhl.top/Article/details/gtefghyrta.html

Ruby: super
来源：http://dali.fengsongda.top/Article/details/gtdsvunwrk.html

C#:   base.Greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtaxihbhkj.html

[G08] 静态方法与属性
来源：http://dali.andypj.xyz/Article/details/gtjplxswbk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gtuaaddxdr.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gtsewcsyew.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtaoeuwkni.html

TS:   static f(): void {}
来源：http://dali.ehwqpu.com/Article/details/gtvfpyoewh.html

Java: static void f() {}
来源：http://dali.zdqjudy.top/Article/details/gtnrcgdacb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shzxlz.cn/Article/details/gtppgbcajp.html

Ruby: def self.f; end
来源：http://dali.xziqi.cn/Article/details/gtxgusjaot.html

C#:   public static void F() {}
来源：http://dali.yueranfly.top/Article/details/gtwyjllfyn.html

[G09] 接口 / 抽象类
来源：http://dali.nanxuanxn.top/Article/details/gtfdwwjnpl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxuanxn.top/Article/details/gtywocdgjz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnxiangtu.top/Article/details/gtzzorbcox.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gtppvvrqgb.html

TS:   interface Shape { area(): number; }
来源：http://dali.zycfv.cn/Article/details/gtmsumthgp.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gtvswworkv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj202588.top/Article/details/gtfzjlqhmq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gtontacpmd.html

C#:   interface IShape { double Area(); }
来源：http://dali.ivvv.top/Article/details/gttgjjlgxr.html

[G10] 访问控制
来源：http://dali.quarkkingdee.top/Article/details/gtbrtvgkic.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dashuyun.cn/Article/details/gtogzlgsmc.html

PHP:  public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtjffcclae.html

JS:   #private 字段；其余公开
来源：http://dali.sxryk.cn/Article/details/gttypimaww.html

TS:   public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtofyivjfz.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gtyvasibxc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.haohaochexian.top/Article/details/gtcmfisrft.html

Ruby: public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtyorxjxej.html

C#:   public / protected / private / internal
来源：http://dali.hfpthk.cn/Article/details/gtnpkxfjhv.html

[G11] getter / setter
来源：http://dali.shangyingyoupin.top/Article/details/gtatbrsmvi.html

Py:   @property 与 @x.setter
来源：http://dali.kuanghao11.cn/Article/details/gtvsgoecnd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtigkozguw.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtifoptzqm.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gteqgsqmyv.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtdifkgiay.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtcmydjyaj.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gtzzohosbk.html

C#:   public string Name { get; set; }
来源：http://dali.yuanzhike.top/Article/details/gtjjxepsca.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gthrgkaequ.html

Py:   def __str__(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtearylyqj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtbkegpfss.html

JS:   toString() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtvrafctyu.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtwfvnurvl.html

Java: @Override public String toString() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtozwzbton.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtqpkftmle.html

Ruby: def to_s; @name; end
来源：http://dali.tian-w.cn/Article/details/gtivdyjcvl.html

C#:   public override string ToString() => Name;
来源：http://dali.xziqi.cn/Article/details/gtjfbuwook.html

[G13] 判断对象类型
来源：http://dali.hnxiangtu.top/Article/details/gthvndfdll.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gtrfotdpmy.html

PHP:  $u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtjecuxizu.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gthjkwjxdi.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtyuxhvjxu.html

Java: u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gtbrbzsfja.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ivvv.top/Article/details/gtnipmpusd.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gtrakoqjpi.html

C#:   u is User
来源：http://dali.yuxming.cn/Article/details/gtuixfzyef.html

[G14] 数据类 / record
来源：http://dali.yj202588.top/Article/details/gtgztsgwps.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pycfn.com/Article/details/gtlbqdndyd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gtqfyiuglt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gtanyotmzq.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gticbwoidh.html

Java: record User(String name, int age) {}
来源：http://dali.9152youxi.cn/Article/details/gtnbzqrysi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gtvdddwzde.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yanxiufei.cn/Article/details/gthwawjglt.html

C#:   record User(string Name, int Age);
来源：http://dali.kuanghao11.cn/Article/details/gttkivfsrt.html

[G15] 枚举
来源：http://dali.yanxiufei.cn/Article/details/gtysiduhnf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmzeqatk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgfzy.top/Article/details/gttnuakagd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sxryk.cn/Article/details/gtrtmpwrkk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtopfmipcu.html

Java: enum Color { RED, GREEN }
来源：http://dali.gzhubu.top/Article/details/gtmcqrlkbe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gotoacloud.top/Article/details/gticsxclol.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gtlyslmlvf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtwvttnuru.html

[G16] 对象转数组 / 字典
来源：http://dali.yuxming.cn/Article/details/gtiyclqdnh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhongyouzk.top/Article/details/gteokgdpup.html

PHP:  get_object_vars($obj);
来源：http://dali.feifeiyinyue.top/Article/details/gtqpyrtexu.html

JS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtuqrmrrik.html

TS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gtgeiezyrg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gtsykbqfpe.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gtljiqvoql.html

Ruby: obj.instance_variables
来源：http://dali.xylfe.cn/Article/details/gtndgxlqug.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtzndzjtiu.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtclhkufqh.html

H. 异常与错误处理
来源：http://dali.daria6918.cn/Article/details/gttksjvqwt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtrcjivlkg.html

[H01] try / catch 基础
来源：http://dali.yonumen.top/Article/details/gtwisqdiyi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xinyue.icu/Article/details/gtxwwjmpmv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gtnteqdmse.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtgnfrpdfe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtomqcolip.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cheryme.top/Article/details/gtcylzzrxq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.birdmap.top/Article/details/gtdebzbgpu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtheyibheb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.c1oappe.top/Article/details/gtndjytfwb.html

[H02] finally / ensure 收尾
来源：http://dali.mhx1999.top/Article/details/gtgmutlpcx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxtqvpik.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabehdwiq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gthssvbmbu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtxnjkodyc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtjxiehifc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gttzvkoyat.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.svipenyu.cn/Article/details/gtjzlaefaq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtmurmnxhg.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gtozonkhjn.html

Py:   raise ValueError("错误信息")
来源：http://dali.haohaochexian.top/Article/details/gttrpudgrn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtvjxinwuu.html

JS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gthkmhkiai.html

TS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtqhgsfmny.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtlrycfczv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.haohaochexian.top/Article/details/gtaspvoyco.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gtouqkesvo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtedgjddoz.html

[H04] 自定义异常类型
来源：http://dali.cdnleiting.top/Article/details/gtpxqcuazh.html

Py:   class MyError(Exception): pass
来源：http://dali.birdmap.top/Article/details/gtowkrjydk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtyldvhjsu.html

JS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfpryfbu.html

TS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gthatdwwvf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtomwneyjp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cheryme.top/Article/details/gtcdxbtqal.html

Ruby: class MyError < StandardError; end
来源：http://dali.shzxlz.cn/Article/details/gtxitmgtrj.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfjhllyo.html

[H05] 捕获特定类型
来源：http://dali.sufxvd.cn/Article/details/gteyvkuvqm.html

Py:   except ValueError as e:
来源：http://dali.iojbl.cn/Article/details/gtngdzwuxf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yvedp.cn/Article/details/gtarjpgbli.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtcjfeyoqn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gtrttrslty.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jyoumei.cn/Article/details/gtadenrtwe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gtppcgpjoi.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gtorgkgcea.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shuidangran.top/Article/details/gtklxdbnqo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cheryme.top/Article/details/gtdpwufizk.html

Py:   value = d.get("k") or default
来源：http://dali.dianchejie.cn/Article/details/gtdhkzclmo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtjpdbbqdr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gtziwsbbpy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gtysymyppd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dianchejie.cn/Article/details/gtdglfclnk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fzhhl.top/Article/details/gtugfdpqde.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cashguo.top/Article/details/gtsskezksj.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gteagwfcoz.html

[H07] 断言
来源：http://dali.zhixingplan.top/Article/details/gtesmragnk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.mhx1999.top/Article/details/gtugkaggxj.html

PHP:  assert($x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtozjghiur.html

JS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtclcyqxbi.html

TS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtiydcvcxh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pengpengdd.cyou/Article/details/gttzdexpgo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gtqwgwoegi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gtkxiagyni.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtjiujukiu.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigfzy.top/Article/details/gtjbnshcah.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gtpuyxmdcn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangdashe.top/Article/details/gtspqleldh.html

JS:   e.message;  e.stack
来源：http://dali.gaohongyu789.top/Article/details/gthecdtiqr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gtthttncck.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.vqdsnc.cn/Article/details/gtpcaxitjq.html

Go:   err.Error()
来源：http://dali.316326.xyz/Article/details/gtzcngmvad.html

Ruby: e.message;  e.backtrace
来源：http://dali.pengpengdd.cyou/Article/details/gtplvxtbts.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aibaodan.cn/Article/details/gtxbqcsyzw.html

[H09] 带错误码的异常
来源：http://dali.pengpengdd.cyou/Article/details/gtkhorzonw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.quarkkingdee.top/Article/details/gtozlmxtcq.html


<!-- 参考信息 -->