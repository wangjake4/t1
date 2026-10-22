代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtlsilqlfx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ybcxt.top/Article/details/gtitgbobvo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtczaymlvk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gtyqolltuc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gzhubu.top/Article/details/gtmrchlout.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuxming.cn/Article/details/gtbffoxpfp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypipwweh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gtwvayxhqq.html

[F05] 判断文件或目录是否存在
来源：http://dali.gogol.net.cn/Article/details/gtvkkxxhaj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jiagoushi.top/Article/details/gtdgoahcbr.html

PHP:  file_exists("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtvihwkubn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtzafqrhes.html

TS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtvystkvft.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtxwbwzszs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.snrcjt.cn/Article/details/gtqvbzchbr.html

Ruby: File.exist?("a.txt")
来源：http://dali.birdmap.top/Article/details/gtdvsirwuk.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258.top/Article/details/gtottugllj.html

[F06] 删除文件
来源：http://dali.nanxinkj.top/Article/details/gtckdwyfov.html

Py:   os.remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtmzmqihyv.html

PHP:  unlink("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtztfuurqv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtkvjdjowv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtexmschoe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtksckawnj.html

Go:   os.Remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtypdkgilw.html

Ruby: File.delete("a.txt")
来源：http://dali.ybcxt.top/Article/details/gttkzzismg.html

C#:   File.Delete("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtsiogirmv.html

[F07] 创建目录（含多级）
来源：http://dali.daxiang520.top/Article/details/gtuqkamrwd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptvswwwd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gotoacloud.top/Article/details/gtduhtwbeo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gtsczydybm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gtrrcinqyn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.c1oappe.top/Article/details/gtprvjnvkp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ehwqpu.com/Article/details/gtelqgwrea.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xinyue.icu/Article/details/gtihysykft.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aizwys.cn/Article/details/gtzufmbvec.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gtpwkcyslw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nwbrower.top/Article/details/gthwizhjll.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xinyue.icu/Article/details/gtxghtpexu.html

JS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gtpacozpov.html

TS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtewziunju.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gteqokxaws.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.snrcjt.cn/Article/details/gtocvtievw.html

Ruby: Dir.children("dir")
来源：http://dali.daria6918.cn/Article/details/gtnagkqeqz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guowangkeji.top/Article/details/gtwhnrorpo.html

[F09] 获取文件大小
来源：http://dali.yangfankeji.com/Article/details/gtmbddwfun.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtgeoutpve.html

PHP:  filesize("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtblczxkof.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gtuhepvebp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtgmakeodx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtgvmvtfuu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gtvdqkmmws.html

Ruby: File.size("a.txt")
来源：http://dali.hammf.cn/Article/details/gtzzvllavi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuxming.cn/Article/details/gtiqzxmytl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gtiblnyqjm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtkbmrbsbi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xinyue.icu/Article/details/gtolvqnjtr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtpuwxzcqv.html

TS:   path.extname("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtjfcfvjdd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxuanxn.top/Article/details/gtgbrsuhty.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtblfxjwzt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtvcsbfext.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtqsmbjhva.html

[F11] 复制与移动文件
来源：http://dali.smart0.xyz/Article/details/gtlfhsokhe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtlwggrpns.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ivvv.top/Article/details/gtbaqarron.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtnmxqwmqe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtbhdvmtnw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gtgsvbxkmb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258.top/Article/details/gtlhtdywws.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtctxaqggq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zdqjudy.top/Article/details/gtttapveja.html

[F12] CSV 读写
来源：http://dali.vqdsnc.cn/Article/details/gtggoshgvm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xinyue.icu/Article/details/gtugivihmy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.redwolf501.top/Article/details/gtrimpwxpt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuanzx.com/Article/details/gthfuogppo.html

TS:   // 同上
来源：http://dali.xuetiantiany.cn/Article/details/gtixvtgwga.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yangfankeji.com/Article/details/gtccquujuk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.0kj1m.cn/Article/details/gtkzbasmgm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmkhxyza.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gtxlpwkoxc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtwnyhfckf.html

G. 面向对象
来源：http://dali.jinqigfzy.top/Article/details/gtwqzkjbsb.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvxwnkzz.html

[G01] 定义类
来源：http://dali.hywenlv.cn/Article/details/gtukhwhsnv.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gtoquxuvbw.html

PHP:  class User {}
来源：http://dali.svipenyu.cn/Article/details/gtflztbrvl.html

JS:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtlisyyeak.html

TS:   class User { name: string = ""; }
来源：http://dali.shangyingyoupin.top/Article/details/gtopiunmcb.html

Java: class User {}
来源：http://dali.redwolf501.top/Article/details/gtehagfxqa.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gtfcqvofgr.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gtemkneowj.html

C#:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtcxamwgrb.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gtgwjuckxi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xziqi.cn/Article/details/gtvgifmado.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.meibo888.top/Article/details/gtegmwzimg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtlqxqeigx.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gtxqacxbme.html

Java: User(String name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtuuhpqqcd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yangfankeji.com/Article/details/gtyirrmtqm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gtxoffwqxf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcvebynrt.html

[G03] 实例属性
来源：http://dali.daria6918.cn/Article/details/gtwaqbjhun.html

Py:   self.name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gtmsvomnlr.html

PHP:  public string $name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtaljlsznt.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gtszdiqwtt.html

TS:   name: string = "x";
来源：http://dali.jiagoushi.top/Article/details/gtshbnyfjv.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gtkfunmrwk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jyoumei.cn/Article/details/gtyqkzfxmw.html

Ruby: @name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gtbzgcsyps.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nwbrower.top/Article/details/gtzrwbspwp.html

[G04] 定义方法
来源：http://dali.jiagoushi.top/Article/details/gtmwryhlsx.html

Py:   def greet(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtylwbqqza.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtogsbqlpn.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtrodaguqu.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmacgmsbp.html

Java: String greet() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtsvzbvdwt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtzkotzezc.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtkrbmcytc.html

C#:   public string Greet() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtljonpcon.html

[G05] 继承
来源：http://dali.zdqjudy.top/Article/details/gtmusiuljp.html

Py:   class Admin(User): pass
来源：http://dali.quarkkingdee.top/Article/details/gtucfjgybo.html

PHP:  class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtsapiwcof.html

JS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtwhrcacif.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlblpbylc.html

Java: class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtovwwqxhx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigufen.top/Article/details/gttejqukaf.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gtzguwqfda.html

C#:   class Admin : User {}
来源：http://dali.jqgufenzy.top/Article/details/gtkgxsnrzz.html

[G06] 重写方法
来源：http://dali.yuanzhike.top/Article/details/gtqafoulxa.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gtloylwotb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlflkggo.html

JS:   greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtiebyntfn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwdmzola.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtrboqclwq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gtlyxioavs.html

Ruby: def greet; "admin"; end
来源：http://dali.tanke756.top/Article/details/gtuslgcytd.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gtnlmilvkt.html

[G07] 调用父类方法
来源：http://dali.daria6918.cn/Article/details/gtusszpixt.html

Py:   super().greet()
来源：http://dali.zhiwuduotai.top/Article/details/gtwaaeeusd.html

PHP:  parent::greet();
来源：http://dali.fzhhl.top/Article/details/gthgavyzbe.html

JS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gtcqoqhmlb.html

TS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtiyuodcwc.html

Java: super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gthytvormy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gtcjsromny.html

Ruby: super
来源：http://dali.c1oappe.top/Article/details/gtlzwhmyhg.html

C#:   base.Greet();
来源：http://dali.yuanzhike.top/Article/details/gtumxbawsr.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gtmloisxkm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gtejshpflq.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdzkvoxk.html

JS:   static f() {}
来源：http://dali.dianchejie.cn/Article/details/gtzdaobuiv.html

TS:   static f(): void {}
来源：http://dali.hongshengwenyu.top/Article/details/gtfxlqpqja.html

Java: static void f() {}
来源：http://dali.tanke756.top/Article/details/gtyqdarvwt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shzxlz.cn/Article/details/gtmqqbzwfx.html

Ruby: def self.f; end
来源：http://dali.yuanzhike.top/Article/details/gtqslqcgml.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtdsshwtxz.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gtgxnyqkmp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gtbmevdjlv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gtnwicphpg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.haohaochexian.top/Article/details/gtmckozpat.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gtnnyuntyx.html

Java: interface Shape { double area(); }
来源：http://dali.quarkkingdee.top/Article/details/gtmhnzvbjk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gtzksmosfb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtgffiebpk.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtmbrxogxy.html

[G10] 访问控制
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtmjbqdd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenzaomai.com/Article/details/gtmvqgmngo.html

PHP:  public / protected / private
来源：http://dali.havefunace.top/Article/details/gtsglwfzbd.html

JS:   #private 字段；其余公开
来源：http://dali.xinyue.icu/Article/details/gtbgvhhdjk.html

TS:   public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkmvourq.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gtfzvgybku.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cqqwz.cn/Article/details/gtdiqjoxxi.html

Ruby: public / protected / private
来源：http://dali.meibo888.top/Article/details/gtgcthsbam.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gtsscbmmde.html

[G11] getter / setter
来源：http://dali.ydzc1.top/Article/details/gttoxycqlw.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gtyeqbqomp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtcgaadjpa.html

JS:   get name() { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtigjualid.html

TS:   get name(): string { return this._name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrigxhsci.html

Java: public String getName() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtwluhahkl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtcloqipfj.html

Ruby: attr_accessor :name
来源：http://dali.yj202588.top/Article/details/gtlipczptz.html

C#:   public string Name { get; set; }
来源：http://dali.guannengcc.top/Article/details/gtlcqdaktg.html

[G12] 对象转字符串
来源：http://dali.chenzaomai.com/Article/details/gtptlxzruf.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtzrxedqye.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtmuwaztfw.html

JS:   toString() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtmgtvhgib.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtcofqhlbo.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtwytndogv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtwunvwodc.html

Ruby: def to_s; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtahjxllia.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgfzy.top/Article/details/gtblurfelh.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gtjlnpfuft.html

Py:   isinstance(u, User)
来源：http://dali.ehwqpu.com/Article/details/gtdvpdamfy.html

PHP:  $u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtcrwxlqkc.html

JS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtwwbgfeet.html

TS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtedeehlnt.html

Java: u instanceof User
来源：http://dali.havefunace.top/Article/details/gthkdehgvh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljlfwkva.html

Ruby: u.is_a?(User)
来源：http://dali.shzxlz.cn/Article/details/gtmaigzylw.html

C#:   u is User
来源：http://dali.cucudq.cn/Article/details/gthjygirkn.html

[G14] 数据类 / record
来源：http://dali.daria6918.cn/Article/details/gtqcrmxmlr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.meibo888.top/Article/details/gtqotsxjqt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hysaishi.cn/Article/details/gtmtkrskrs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gtsumwxunt.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenlongwang.top/Article/details/gtbsmofojw.html

Java: record User(String name, int age) {}
来源：http://dali.haohaochexian.top/Article/details/gtpzwjjfnj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jianghu66.top/Article/details/gtiywstloz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tianlin.xyz/Article/details/gtwtntsedk.html

C#:   record User(string Name, int Age);
来源：http://dali.yuanzhike.top/Article/details/gtucudwjbk.html

[G15] 枚举
来源：http://dali.birdmap.top/Article/details/gtffqgnsbo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zycfv.cn/Article/details/gtvpyotket.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gtmliqlwmr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sufxvd.cn/Article/details/gtrcyuifkq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gthzwomcsw.html

Java: enum Color { RED, GREEN }
来源：http://dali.havefunace.top/Article/details/gtlidqftrv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.smart0.xyz/Article/details/gtsgarugly.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yvedp.cn/Article/details/gtwzcjqgsm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtvcbxnzzb.html

[G16] 对象转数组 / 字典
来源：http://dali.ybcxt.top/Article/details/gtlhvsvltl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.smart0.xyz/Article/details/gtnucupzwn.html

PHP:  get_object_vars($obj);
来源：http://dali.mhx1999.top/Article/details/gtgfrjuyas.html

JS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gtutczeitt.html

TS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtzocucjfa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.kuanghao11.cn/Article/details/gttbuvvrxa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gtpmxyrrjw.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsklswpjf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtmsvwkofr.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtnqbiygfz.html

H. 异常与错误处理
来源：http://dali.nanxinkj.top/Article/details/gtxlwtjgvm.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtgmxjvqck.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gtpfbapqht.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gtzpblzeyn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jianghu66.top/Article/details/gtjctbifar.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtquukmfzj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gtaqqdiixk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aizwys.cn/Article/details/gtzqhomgdd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjdiijxd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.c1oappe.top/Article/details/gtkzyohtia.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.kuanghao11.cn/Article/details/gtdwgjylwp.html

[H02] finally / ensure 收尾
来源：http://dali.hfpthk.cn/Article/details/gtuallcosm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aibaodan.cn/Article/details/gtrhyabvjl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtfehipghh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gteqidphsg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtspakizoa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtsdjnzvgf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gtarxrlfog.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ehwqpu.com/Article/details/gtpcrqjwsp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtnyxijrtt.html

[H03] 主动抛出异常
来源：http://dali.sysykeji.top/Article/details/gtbxtzudtb.html

Py:   raise ValueError("错误信息")
来源：http://dali.sufxvd.cn/Article/details/gtzjsbttsk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtqqyfkwio.html

JS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtsabqxphz.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtdmhumfta.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtqqfdxdls.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gtahmjwhkp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gtidatkrhm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtvrbyyevp.html

[H04] 自定义异常类型
来源：http://dali.feifeiyinyue.top/Article/details/gtxugpgzrh.html

Py:   class MyError(Exception): pass
来源：http://dali.0kj1m.cn/Article/details/gtwgfksfud.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtiaeuifec.html

JS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtcqeotewh.html

TS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtyxudgxhn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gtvfinsvff.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jianghu66.top/Article/details/gtjuhgrras.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gtibubuejn.html

C#:   class MyException : Exception {}
来源：http://dali.yvedp.cn/Article/details/gtrkixgczl.html

[H05] 捕获特定类型
来源：http://dali.chenlongwang.top/Article/details/gtuoznuwjc.html

Py:   except ValueError as e:
来源：http://dali.dianchejie.cn/Article/details/gtcwajokyj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sxryk.cn/Article/details/gtaprksoil.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtejakjbld.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cheryme.top/Article/details/gtxdyjthei.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gtykyaiknz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhengqikj.top/Article/details/gthlqueedw.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenlongwang.top/Article/details/gtgfqnjazc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yongpay.top/Article/details/gtbrzzqhri.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenjidiqi.icu/Article/details/gtwyvbcsom.html

Py:   value = d.get("k") or default
来源：http://dali.meibo888.top/Article/details/gthmtjxpal.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gthyygpsuj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtoaftgkpl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtguqhvrjs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gtddenvnrb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenzaomai.com/Article/details/gtdfllgrqd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.smart0.xyz/Article/details/gthcbcvzds.html

C#:   obj?.A?.B ?? default
来源：http://dali.gogol.net.cn/Article/details/gtqaecijxc.html

[H07] 断言
来源：http://dali.zhongyouzk.top/Article/details/gtvabxzdbz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daxiang520.top/Article/details/gtgxczmqeg.html

PHP:  assert($x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtrbqfyjgo.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtgdxmcwhm.html

TS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtkuogetyj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuanzx.com/Article/details/gtmbiglaaj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gtfsqpjfkd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hywenlv.cn/Article/details/gtxhidvidk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtooghabne.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gtileiwlrm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shzxlz.cn/Article/details/gtzudkwdbo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjtcstcy.html

JS:   e.message;  e.stack
来源：http://dali.yuxming.cn/Article/details/gtzuvpaqty.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuanzhike.top/Article/details/gtjxpjfjoj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tian-w.cn/Article/details/gtctveesfm.html

Go:   err.Error()
来源：http://dali.zhixingplan.top/Article/details/gteskdotpy.html


<!-- 参考信息 -->