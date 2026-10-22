代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gtpxtnzeqv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnkfcxqy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gthlrijutn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xziqi.cn/Article/details/gtwccwhect.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jyoumei.cn/Article/details/gtaqeasztm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtlncimktv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtsdojyvue.html

[F04] 追加写入文件
来源：http://dali.mhx1999.top/Article/details/gtxausmvcl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sufxvd.cn/Article/details/gthgaiwbba.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.kuanghao11.cn/Article/details/gtzirbmcfy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtvpqzxonf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtlcjwkxlq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gzhubu.top/Article/details/gtybigktyw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtfvtfzeuq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gtdzgjloon.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwxrlwjd.html

[F05] 判断文件或目录是否存在
来源：http://dali.hammf.cn/Article/details/gtiprfzlaa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hywenlv.cn/Article/details/gthzrrufqq.html

PHP:  file_exists("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtotpbmazm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtcmqascue.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gttntpyyyn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtziyppgyq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nwbrower.top/Article/details/gtmlglybat.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtjqghxcgt.html

C#:   File.Exists("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtyfhtutmz.html

[F06] 删除文件
来源：http://dali.cqqwz.cn/Article/details/gtzbwhwlzc.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtuphvlubs.html

PHP:  unlink("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtiismnaac.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtkpwxpzfo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtqpitcfpl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtagnagebe.html

Go:   os.Remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtpnmoyraa.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtimettalq.html

C#:   File.Delete("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtczhguomx.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigfzy.top/Article/details/gtcdfeauca.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtdetmvugb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxuanxn.top/Article/details/gtksfytuzo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtjmkfkqua.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gtwikfffqj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigufen.top/Article/details/gtgyqkuxls.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gtystryzct.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guowangkeji.top/Article/details/gtayutuips.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hfpthk.cn/Article/details/gtjjxvevmx.html

[F08] 遍历目录
来源：http://dali.ehwqpu.com/Article/details/gtcseqwxen.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shangyingyoupin.top/Article/details/gtvhjdiexk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkzyfbhvu.html

JS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gthdpqnjlt.html

TS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gtkhcpsfuk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtkaegsttn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ydzc1.top/Article/details/gtybyrakql.html

Ruby: Dir.children("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrzxbodu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigufen.top/Article/details/gtfrzqfkpy.html

[F09] 获取文件大小
来源：http://dali.hongshengwenyu.top/Article/details/gtpcnrhter.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtnwhsmbpv.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtihtuvesg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtozjajoqm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gtpwfbagma.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtozwnnspr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gtakwivxia.html

Ruby: File.size("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtttgpxevf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gtxejixhgl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dianchejie.cn/Article/details/gtswuwgfcr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtwspjohwv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jianghu66.top/Article/details/gtcmjklpju.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gttllhusgi.html

TS:   path.extname("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtidfwsyhb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gtjyojlivb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtbewiwgux.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtmnkxdjyt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtnkgcnxfv.html

[F11] 复制与移动文件
来源：http://dali.fzhhl.top/Article/details/gtdzxoyzmw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtctsprupe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.meibo888.top/Article/details/gtozsvwnay.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtqnrtupvp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtzblkkmde.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daria6918.cn/Article/details/gtiespklve.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gtzjhtjwvv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtdoiolnxz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gtvrbhzjhy.html

[F12] CSV 读写
来源：http://dali.hfpthk.cn/Article/details/gtgmuuybwx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jlsjyb.cn/Article/details/gtedskmyih.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.0kj1m.cn/Article/details/gtswmiztji.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gtnutjwyuf.html

TS:   // 同上
来源：http://dali.xuanzx.com/Article/details/gtmneuzwhg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.haohaochexian.top/Article/details/gtfakcqsiw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guannengcc.top/Article/details/gttlffqsml.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnxiangtu.top/Article/details/gttqdxazgi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gtfqlrlmka.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtpnhmivcr.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gtgbmjerbc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtwrtsfzjd.html

[G01] 定义类
来源：http://dali.jlsjyb.cn/Article/details/gtmrxxglid.html

Py:   class User: pass
来源：http://dali.shzxlz.cn/Article/details/gteqhidmcy.html

PHP:  class User {}
来源：http://dali.yuxming.cn/Article/details/gthyzflayn.html

JS:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtsfadciub.html

TS:   class User { name: string = ""; }
来源：http://dali.kuanghao11.cn/Article/details/gtbaycphud.html

Java: class User {}
来源：http://dali.fzhhl.top/Article/details/gtzegybbdk.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gtnajsikud.html

Ruby: class User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtrfeodthn.html

C#:   class User {}
来源：http://dali.yonumen.top/Article/details/gtcsqjunlf.html

[G02] 构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtprofiajd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppgwaneh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gtqcpaapsi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gticpuerbp.html

TS:   constructor(public name: string) {}
来源：http://dali.ivvv.top/Article/details/gtawckrueb.html

Java: User(String name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gtyztnuhqw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.0kj1m.cn/Article/details/gthastsjob.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtzqoovfnr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtjgkayykw.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gtfpmhodhd.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtepcjdmey.html

PHP:  public string $name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtfjpszkxy.html

JS:   this.name = "x";
来源：http://dali.dashuyun.cn/Article/details/gtxqqdduon.html

TS:   name: string = "x";
来源：http://dali.jyoumei.cn/Article/details/gtkhiclozp.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gtgmhdrdci.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gtfmqztxoc.html

Ruby: @name = "x"
来源：http://dali.nwbrower.top/Article/details/gtxujgxvej.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ivvv.top/Article/details/gtnbifsrzb.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gtffqlwbvn.html

Py:   def greet(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtkridozna.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtpvvdicpb.html

JS:   greet() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gthbsqsnhk.html

TS:   greet(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtbzxvhlfb.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtpxtidqri.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gtwqxrvwcf.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gtjsxihfjs.html

C#:   public string Greet() => Name;
来源：http://dali.hammf.cn/Article/details/gtzybhfkjl.html

[G05] 继承
来源：http://dali.jyoumei.cn/Article/details/gtnyhwvdac.html

Py:   class Admin(User): pass
来源：http://dali.gogol.net.cn/Article/details/gtisicjjyr.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gttxgrmmrz.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtwuoljjtd.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtbwfigzdm.html

Java: class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtfvzhgarx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.kuanghao11.cn/Article/details/gtkgsmhzmu.html

Ruby: class Admin < User; end
来源：http://dali.yj202588.top/Article/details/gtqquwkxew.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtrbzmyovq.html

[G06] 重写方法
来源：http://dali.zhiwuduotai.top/Article/details/gtkgmsyxcv.html

Py:   def greet(self): return "admin"
来源：http://dali.cashguo.top/Article/details/gtrnaoerfi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtzpbrtqnq.html

JS:   greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtzcpwlpgq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtdimaayoo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtulyknhxh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangshuangyany.cn/Article/details/gtycfavyma.html

Ruby: def greet; "admin"; end
来源：http://dali.fengsongda.top/Article/details/gtbmmfdluu.html

C#:   public override string Greet() => "admin";
来源：http://dali.hfpthk.cn/Article/details/gtsjwzlvql.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gtqwyacose.html

Py:   super().greet()
来源：http://dali.jinqigufen.top/Article/details/gtugffqsed.html

PHP:  parent::greet();
来源：http://dali.0kj1m.cn/Article/details/gtkwqnbipl.html

JS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtcsssdbbu.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gttaarpiya.html

Java: super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtxmzqmtbk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhixingplan.top/Article/details/gtxlksahls.html

Ruby: super
来源：http://dali.yj20258.top/Article/details/gthkinzxok.html

C#:   base.Greet();
来源：http://dali.iojbl.cn/Article/details/gtixefgtwe.html

[G08] 静态方法与属性
来源：http://dali.birdmap.top/Article/details/gtozakyvha.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gtxvzvmwgg.html

PHP:  public static function f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtmybvijet.html

JS:   static f() {}
来源：http://dali.haohaochexian.top/Article/details/gtltzqbdlx.html

TS:   static f(): void {}
来源：http://dali.aizwys.cn/Article/details/gtggegymlc.html

Java: static void f() {}
来源：http://dali.andypj.xyz/Article/details/gtpyqoqklc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daxiang520.top/Article/details/gtgrbrztzh.html

Ruby: def self.f; end
来源：http://dali.tianlin.xyz/Article/details/gtsmovlsou.html

C#:   public static void F() {}
来源：http://dali.yvedp.cn/Article/details/gtjdbqpnke.html

[G09] 接口 / 抽象类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsigtuuxd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gtfbcldwoz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hfpthk.cn/Article/details/gtscevucqr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hfpthk.cn/Article/details/gttvuxulhs.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gtbpzqjier.html

Java: interface Shape { double area(); }
来源：http://dali.yuanzhike.top/Article/details/gtkwjuwifm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xylfe.cn/Article/details/gtdewzbmyi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sxryk.cn/Article/details/gtsvqlojfr.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwasgamxm.html

[G10] 访问控制
来源：http://dali.xuetiantiany.cn/Article/details/gtofzghjzr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yueranfly.top/Article/details/gtcbqwoncc.html

PHP:  public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtnkfogkib.html

JS:   #private 字段；其余公开
来源：http://dali.yvedp.cn/Article/details/gtfsmsrkfx.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtbryzxlkb.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gtfigvwqog.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pycfn.com/Article/details/gththwvojg.html

Ruby: public / protected / private
来源：http://dali.pycfn.com/Article/details/gtrjqurrei.html

C#:   public / protected / private / internal
来源：http://dali.iojbl.cn/Article/details/gtluxnlcag.html

[G11] getter / setter
来源：http://dali.snrcjt.cn/Article/details/gtsoctxiqq.html

Py:   @property 与 @x.setter
来源：http://dali.hammf.cn/Article/details/gtfjqihkxt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtfzctiifb.html

JS:   get name() { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtdewwnqxp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gteusqjghj.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gtozkxweza.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtxuzedfkd.html

Ruby: attr_accessor :name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgttfubu.html

C#:   public string Name { get; set; }
来源：http://dali.sxryk.cn/Article/details/gtwvttudxd.html

[G12] 对象转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevgcqsbh.html

Py:   def __str__(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtiboogfpd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gttedarhac.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtvrnhubib.html

TS:   toString(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtrzwcazlb.html

Java: @Override public String toString() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtuljpqiml.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtskbjviim.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtlfxlqzoa.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsutjvix.html

[G13] 判断对象类型
来源：http://dali.tianlin.xyz/Article/details/gtmouwnaqc.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gtbhednmtc.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtkwbqbzic.html

JS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtpamnwcck.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtnntoygte.html

Java: u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtjmvtgqqv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenzaomai.com/Article/details/gtmbseujhx.html

Ruby: u.is_a?(User)
来源：http://dali.xuetiantiany.cn/Article/details/gtpxhmwlen.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gtehisetqy.html

[G14] 数据类 / record
来源：http://dali.shuidangran.top/Article/details/gtbvrxmosb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ppjwa.cn/Article/details/gtntsnjbgm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guowangkeji.top/Article/details/gtyaystnxu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gtgmrjfsmf.html

TS:   type User = { name: string; age: number };
来源：http://dali.zycfv.cn/Article/details/gtooekglyc.html

Java: record User(String name, int age) {}
来源：http://dali.nanxinkj.top/Article/details/gtoscmmbqk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gtqnyaslbf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tanke756.top/Article/details/gtiyckqhdk.html

C#:   record User(string Name, int Age);
来源：http://dali.xuanzx.com/Article/details/gtuovnfwor.html

[G15] 枚举
来源：http://dali.guowangkeji.top/Article/details/gtsuuxrguj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pycfn.com/Article/details/gtoohzxcoj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gtbplschaw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jyoumei.cn/Article/details/gtzgvnoihk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtrqpowukw.html

Java: enum Color { RED, GREEN }
来源：http://dali.0kj1m.cn/Article/details/gtvnjwfemd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.bjfxy.top/Article/details/gtvutnibso.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ybcxt.top/Article/details/gtyexfudrs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtbqksiolu.html

[G16] 对象转数组 / 字典
来源：http://dali.nwbrower.top/Article/details/gtsbelxghw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pengpengdd.cyou/Article/details/gtidslabkp.html

PHP:  get_object_vars($obj);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzeglnlmq.html

JS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtylzylmbx.html

TS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gtnzofqgno.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.birdmap.top/Article/details/gtoppinhxz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ehwqpu.com/Article/details/gtwekztxxz.html

Ruby: obj.instance_variables
来源：http://dali.0kj1m.cn/Article/details/gtoavgifiy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtudssergs.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtdczwgskv.html

H. 异常与错误处理
来源：http://dali.9152youxi.cn/Article/details/gtdjzzpwjr.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtikixuzut.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gtwvahgvio.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gttryvnbai.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gtpataevcg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtgikabvdx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtoqlshgvh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhiwuduotai.top/Article/details/gthwvjatwp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuanzx.com/Article/details/gtzzeehzqr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.0kj1m.cn/Article/details/gtvklvtwsc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gtzaxkjdlc.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gtnthtrwnl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yangfankeji.com/Article/details/gtdfacurub.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxpuztmy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtwcgsmxuf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtvhpzsfwu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtxocglhek.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.vqdsnc.cn/Article/details/gtymtsmeuv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.havefunace.top/Article/details/gtfzqeljhr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtsijwsxvz.html

[H03] 主动抛出异常
来源：http://dali.pycfn.com/Article/details/gtxlozzktf.html

Py:   raise ValueError("错误信息")
来源：http://dali.guowangkeji.top/Article/details/gttuftzkjw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtsqcsmjeq.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtfxoemmtw.html

TS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gttwoikxqj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gttnenakqu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgfzy.top/Article/details/gtcrntgdpq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gzhubu.top/Article/details/gtklneyrrr.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtqokkwuuo.html

[H04] 自定义异常类型
来源：http://dali.ydzc1.top/Article/details/gtgywuiggt.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gtqriuqxvz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtocopfvsx.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtmdpducmu.html

TS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gtlvcciybi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtobvinfcq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hfpthk.cn/Article/details/gtnwqziojt.html

Ruby: class MyError < StandardError; end
来源：http://dali.zdqjudy.top/Article/details/gtoawovgyz.html

C#:   class MyException : Exception {}
来源：http://dali.meibo888.top/Article/details/gtshvwkfdl.html

[H05] 捕获特定类型
来源：http://dali.dianchejie.cn/Article/details/gtskyawmhn.html

Py:   except ValueError as e:
来源：http://dali.andypj.xyz/Article/details/gtztffobsj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhoulong.xyz/Article/details/gtjeqcdfxc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gtqxyydpps.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtbahzlsvg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dianchejie.cn/Article/details/gtibtrnblt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj202588.top/Article/details/gtzjakdjzz.html

Ruby: rescue ArgumentError => e
来源：http://dali.vqdsnc.cn/Article/details/gtcfnedjsy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.c1oappe.top/Article/details/gtdekxjcdv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj202588.top/Article/details/gtmcumckuq.html

Py:   value = d.get("k") or default
来源：http://dali.nanxuanxn.top/Article/details/gtztfmgzod.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gtisvtswea.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtoypobprz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gticyreeao.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pycfn.com/Article/details/gtosersgxe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.mhx1999.top/Article/details/gtbemtvlji.html

Ruby: d&.dig(:a, :b)
来源：http://dali.iojbl.cn/Article/details/gttvlmulmd.html

C#:   obj?.A?.B ?? default
来源：http://dali.redwolf501.top/Article/details/gtpjlbxsae.html

[H07] 断言
来源：http://dali.havefunace.top/Article/details/gtkeztdyny.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258888.top/Article/details/gtywjsosbd.html

PHP:  assert($x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtdvqfkgfw.html

JS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtolxjbukp.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtpcayuohk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hywenlv.cn/Article/details/gtdznjrqzk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guowangkeji.top/Article/details/gtbiabppoy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenlongwang.top/Article/details/gtzrrzjwhp.html


<!-- 参考信息 -->