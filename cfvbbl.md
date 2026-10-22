代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.birdmap.top/Article/details/gt2furkikji.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258888.top/Article/details/gt2uhyuedfa.html

[F03] 写入文件（覆盖）
来源：http://dali.ivvv.top/Article/details/gt2pvjhobbe.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.vqdsnc.cn/Article/details/gt2sxsmqxxp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gt2vfreaeow.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qxxqvkyg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gt2avnjindu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258888.top/Article/details/gt2qqayhzkc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fzhhl.top/Article/details/gt2wultrkvt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.birdmap.top/Article/details/gt2xxxspjez.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gt2ztxheoma.html

[F04] 追加写入文件
来源：http://dali.jqgfzy.top/Article/details/gt2ldhugiet.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yueranfly.top/Article/details/gt2xdynyxae.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ktcapaif.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gt2gfnbetyv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2cgfrcrpt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yongpay.top/Article/details/gt2qixhqrid.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.birdmap.top/Article/details/gt2owlmfyrh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cheryme.top/Article/details/gt2izujfvzk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jyoumei.cn/Article/details/gt2ffvxscug.html

[F05] 判断文件或目录是否存在
来源：http://dali.hywenlv.cn/Article/details/gt2xojhynrb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxuanxn.top/Article/details/gt2frvuzhsc.html

PHP:  file_exists("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2pztkwcgo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2cndcnrxh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2xsualxub.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2jzyfokcf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhixingplan.top/Article/details/gt2gihfhlme.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2icsugbkz.html

C#:   File.Exists("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qnknhkkl.html

[F06] 删除文件
来源：http://dali.aizwys.cn/Article/details/gt2sudifina.html

Py:   os.remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2iuguazhc.html

PHP:  unlink("a.txt");
来源：http://dali.meibo888.top/Article/details/gt2lvjzbfky.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sfbgdsjz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2wesjppgr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2goaiklud.html

Go:   os.Remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pxcqemyz.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2wmyyceki.html

C#:   File.Delete("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2irnqsetq.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gt2icizpwag.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gt2vewppcln.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xziqi.cn/Article/details/gt2kjgxrksk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gt2iovdkfkg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gt2iinshxsq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.316326.xyz/Article/details/gt2weyttylg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gt2tkcndwzo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.iojbl.cn/Article/details/gt2ejfjohcv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.birdmap.top/Article/details/gt2xusfvawf.html

[F08] 遍历目录
来源：http://dali.sufxvd.cn/Article/details/gt2txujxtkk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gt2lgkfcwlo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hammf.cn/Article/details/gt2yhpfsuwb.html

JS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gt2vlpvgivk.html

TS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gt2ailjucxe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gt2motyasiu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cashguo.top/Article/details/gt2hfrvifwo.html

Ruby: Dir.children("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2sxmtsghl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gzhubu.top/Article/details/gt2cpsvzuzu.html

[F09] 获取文件大小
来源：http://dali.jqgfzy.top/Article/details/gt2tkuyoczo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvueafww.html

PHP:  filesize("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2bzpquexz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gt2oabquqox.html

TS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gt2yasrkgru.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2pcqdtxtk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aidngksi.html

Ruby: File.size("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vgmxnrdm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gt2zfnwsnja.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fmefczdo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2wnoztdvd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2qsxvlmxp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2pvfzouqn.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2naiazsbv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hfpthk.cn/Article/details/gt2bgihhglc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2komrslru.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2ukbcgglx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2qmlobveb.html

[F11] 复制与移动文件
来源：http://dali.jinqigfzy.top/Article/details/gt2pblxwhcf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2tttolbgb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aizwys.cn/Article/details/gt2wefquzmf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2hjzbavei.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2cfrfbkxk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gt2vafswirv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.bjfxy.top/Article/details/gt2scmowtcl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2wuozevjz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fzhshfdf.html

[F12] CSV 读写
来源：http://dali.feifeiyinyue.top/Article/details/gt2oosnvpvv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gt2ebcxtyya.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cdnleiting.top/Article/details/gt2eyzzykdd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgfzy.top/Article/details/gt2wfbpoeqk.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gt2oqmqtqwp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shzxlz.cn/Article/details/gt2hjqjttrr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenlongwang.top/Article/details/gt2bwovxaxe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhongyouzk.top/Article/details/gt2flxxbsmr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shuidangran.top/Article/details/gt2oregnhtg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2tbdfnlta.html

G. 面向对象
来源：http://dali.tianlin.xyz/Article/details/gt2dotxljko.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qffkoriz.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gt2xkcwiqsv.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gt2rfrcjqun.html

PHP:  class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ahmsfjgw.html

JS:   class User {}
来源：http://dali.guannengcc.top/Article/details/gt2otuzgjbk.html

TS:   class User { name: string = ""; }
来源：http://dali.yongpay.top/Article/details/gt2ydftpydh.html

Java: class User {}
来源：http://dali.ivvv.top/Article/details/gt2kqruduje.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gt2npibmvlp.html

Ruby: class User; end
来源：http://dali.kuanghao11.cn/Article/details/gt2wkilmqll.html

C#:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2jroinmbx.html

[G02] 构造函数
来源：http://dali.yvedp.cn/Article/details/gt2rymulqui.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cdnleiting.top/Article/details/gt2mbisfmzo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yvedp.cn/Article/details/gt2adqqeysd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2qqhcgzyf.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gt2nexfoupi.html

Java: User(String name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gt2qwigaylv.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jyoumei.cn/Article/details/gt2vrshbsqr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangdashe.top/Article/details/gt2overxooo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qkttauyl.html

[G03] 实例属性
来源：http://dali.yonumen.top/Article/details/gt2zximmblm.html

Py:   self.name = "x"
来源：http://dali.svipenyu.cn/Article/details/gt2ndnwbcag.html

PHP:  public string $name = "x";
来源：http://dali.sweek.top/Article/details/gt2ymqahcvm.html

JS:   this.name = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2myklnegh.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2jflcndil.html

Java: private String name;
来源：http://dali.sxryk.cn/Article/details/gt2bdiojwrf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgufenzy.top/Article/details/gt2ayjnqqyt.html

Ruby: @name = "x"
来源：http://dali.zycfv.cn/Article/details/gt2ldczaadk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nwbrower.top/Article/details/gt2vzjfdsuz.html

[G04] 定义方法
来源：http://dali.vqdsnc.cn/Article/details/gt2ymkdywin.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gt2upxxdden.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2lgbvrmdt.html

JS:   greet() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2javcnqve.html

TS:   greet(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2orxikbyk.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gt2seetnktr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ozuaywir.html

Ruby: def greet; @name; end
来源：http://dali.jianghu66.top/Article/details/gt2clonwxrv.html

C#:   public string Greet() => Name;
来源：http://dali.svipenyu.cn/Article/details/gt2wafzamnb.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gt2lmbnmoor.html

Py:   class Admin(User): pass
来源：http://dali.ybcxt.top/Article/details/gt2jqjdmqyj.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gt2zbagnmas.html

JS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2kttfgawg.html

TS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2gdcdjeix.html

Java: class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2tgblwafa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cheryme.top/Article/details/gt2cjgrifnz.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gt2sutvyaqh.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2legntkah.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gt2hykofflm.html

Py:   def greet(self): return "admin"
来源：http://dali.cheryme.top/Article/details/gt2diufhgyi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2htnkhkby.html

JS:   greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qojnjlmt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gt2pgufkxso.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2vqkngbco.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gt2dolycfal.html

Ruby: def greet; "admin"; end
来源：http://dali.jlsjyb.cn/Article/details/gt2ubgnabtr.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258888.top/Article/details/gt2twzsheoy.html

[G07] 调用父类方法
来源：http://dali.yvedp.cn/Article/details/gt2ksgzlzjp.html

Py:   super().greet()
来源：http://dali.quarkkingdee.top/Article/details/gt2osqhewyo.html

PHP:  parent::greet();
来源：http://dali.jiagoushi.top/Article/details/gt2wukhpdnw.html

JS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2usmajxdw.html

TS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gt2yezymmlv.html

Java: super.greet();
来源：http://dali.aizwys.cn/Article/details/gt2fapcddqw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fengsongda.top/Article/details/gt2zcsinovf.html

Ruby: super
来源：http://dali.daria6918.cn/Article/details/gt2qegnxzij.html

C#:   base.Greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2zulrvnhr.html

[G08] 静态方法与属性
来源：http://dali.ivvv.top/Article/details/gt2ngwmwerv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.0kj1m.cn/Article/details/gt2vaitxmyw.html

PHP:  public static function f() {}
来源：http://dali.tianlin.xyz/Article/details/gt2axoiduih.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2lxwgjums.html

TS:   static f(): void {}
来源：http://dali.dianchejie.cn/Article/details/gt2fbiubqdl.html

Java: static void f() {}
来源：http://dali.gzhubu.top/Article/details/gt2rzvpjboj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gt2vxmgacfc.html

Ruby: def self.f; end
来源：http://dali.nanxinkj.top/Article/details/gt2dlmetzno.html

C#:   public static void F() {}
来源：http://dali.sysykeji.top/Article/details/gt2biwollym.html

[G09] 接口 / 抽象类
来源：http://dali.yvedp.cn/Article/details/gt2jilgnwil.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.svipenyu.cn/Article/details/gt2xjdyvvdd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hfpthk.cn/Article/details/gt2iimaxect.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgfzy.top/Article/details/gt2rgesnihy.html

TS:   interface Shape { area(): number; }
来源：http://dali.xinyue.icu/Article/details/gt2umoaaxzj.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gt2kcniixdj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yvedp.cn/Article/details/gt2lsakyvnv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jianghu66.top/Article/details/gt2qqoujanj.html

C#:   interface IShape { double Area(); }
来源：http://dali.zdqjudy.top/Article/details/gt2ouofafbr.html

[G10] 访问控制
来源：http://dali.guannengcc.top/Article/details/gt2ujpztwqv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.0kj1m.cn/Article/details/gt2pffmntxh.html

PHP:  public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gt2voniurld.html

JS:   #private 字段；其余公开
来源：http://dali.ivvv.top/Article/details/gt2ubcgfcnn.html

TS:   public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gt2povprgod.html

Java: public / protected / private / 默认包级
来源：http://dali.zycfv.cn/Article/details/gt2ryyqoaco.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nwbrower.top/Article/details/gt2zkkzuxrp.html

Ruby: public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2wcnlaofs.html

C#:   public / protected / private / internal
来源：http://dali.xinyue.icu/Article/details/gt2ojoqvmhf.html

[G11] getter / setter
来源：http://dali.jinqigfzy.top/Article/details/gt2rpoofydu.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gt2khrmyvtu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gt2tjyhiith.html

JS:   get name() { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gt2dcrjdrfh.html

TS:   get name(): string { return this._name; }
来源：http://dali.yongpay.top/Article/details/gt2fifogfun.html

Java: public String getName() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2snivjrkk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2uemqping.html

Ruby: attr_accessor :name
来源：http://dali.iojbl.cn/Article/details/gt2bjegrbko.html

C#:   public string Name { get; set; }
来源：http://dali.yonumen.top/Article/details/gt2harrlmvc.html

[G12] 对象转字符串
来源：http://dali.birdmap.top/Article/details/gt2vqddgkwk.html

Py:   def __str__(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gt2akefcimx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gt2hhrxaqjj.html

JS:   toString() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2uceunhvx.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gt2gkmymyya.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2ycteewtp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gt2omkadjuq.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gt2puvcjsbz.html

C#:   public override string ToString() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2wchwsejk.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gt2polvxpuy.html

Py:   isinstance(u, User)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrafxnbo.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sceurysc.html

JS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2tfuxwwpq.html

TS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2igkwebis.html

Java: u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2ckiyyegc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgufenzy.top/Article/details/gt2zexeljrg.html

Ruby: u.is_a?(User)
来源：http://dali.xziqi.cn/Article/details/gt2alasrgxx.html

C#:   u is User
来源：http://dali.chenzaomai.com/Article/details/gt2widubhtb.html

[G14] 数据类 / record
来源：http://dali.snrcjt.cn/Article/details/gt2edsqnpsu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gt2ffgigdkv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gt2eqqfqfku.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daria6918.cn/Article/details/gt2nxpybiir.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zarmadms.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258888.top/Article/details/gt2dapmyppn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.smart0.xyz/Article/details/gt2hrlhklki.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxtldsck.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gt2hlwtnyjq.html

[G15] 枚举
来源：http://dali.yuanzhike.top/Article/details/gt2ykyposrh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gt2gozwoart.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.haohaochexian.top/Article/details/gt2kiyuyuoy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj202588.top/Article/details/gt2rsukgnmr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2yojmmnyc.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gt2crvlemyb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hysaishi.cn/Article/details/gt2wcvabhar.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gt2nwagjnjl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2zwkvpqwo.html

[G16] 对象转数组 / 字典
来源：http://dali.yj202588.top/Article/details/gt2vcqxhdfc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hysaishi.cn/Article/details/gt2icpetvjq.html

PHP:  get_object_vars($obj);
来源：http://dali.tianlin.xyz/Article/details/gt2alpqkslh.html

JS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gt2ozqfkdzv.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2nydyjqlp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kbhydduh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.andypj.xyz/Article/details/gt2qxymmhal.html

Ruby: obj.instance_variables
来源：http://dali.daxiang520.top/Article/details/gt2nbnssmto.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gt2xaahknbg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2algpbqdh.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gt2eyqbnxvh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ffmsjlow.html

[H01] try / catch 基础
来源：http://dali.pycfn.com/Article/details/gt2fuintrcj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cqqwz.cn/Article/details/gt2dqmlloyl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.316326.xyz/Article/details/gt2uileeioc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gt2jtmjgplf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gt2twjtbrxh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.vqdsnc.cn/Article/details/gt2cnnxqmrz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gt2rqonuequ.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gt2agjpjgxz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dianchejie.cn/Article/details/gt2nizfzijv.html

[H02] finally / ensure 收尾
来源：http://dali.0kj1m.cn/Article/details/gt2zsjdiklz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangdashe.top/Article/details/gt2bqljzkys.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2lmozhfjx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2cxzqeutl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2dkgkzyge.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2izhmkgzw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cheryme.top/Article/details/gt2wzicuvfz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aexyelks.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2yutlejxr.html

[H03] 主动抛出异常
来源：http://dali.ybcxt.top/Article/details/gt2hgrqobtr.html

Py:   raise ValueError("错误信息")
来源：http://dali.hywenlv.cn/Article/details/gt2yuwlabum.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2zirknysr.html

JS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2dsezuimj.html

TS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gt2tqrkwjst.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2ghlrvjre.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gt2xmklcqdu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.bjfxy.top/Article/details/gt2isxhrvgb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2naatxuel.html

[H04] 自定义异常类型
来源：http://dali.sweek.top/Article/details/gt2qqbagfjs.html

Py:   class MyError(Exception): pass
来源：http://dali.tianlin.xyz/Article/details/gt2zjogmjzm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gt2viahutoi.html

JS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gt2zsxbqrwm.html

TS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hltzrkvc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2qsabsbzm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.0kj1m.cn/Article/details/gt2xlpxwboc.html

Ruby: class MyError < StandardError; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yvzoeazt.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258.top/Article/details/gt2wubkbbtu.html

[H05] 捕获特定类型
来源：http://dali.birdmap.top/Article/details/gt2mxwjqpxe.html

Py:   except ValueError as e:
来源：http://dali.daria6918.cn/Article/details/gt2qxhbfllm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sysykeji.top/Article/details/gt2hantcywj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.bjfxy.top/Article/details/gt2ntkyqtxq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gt2qsanoveq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gt2ddejcmvm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgufenzy.top/Article/details/gt2faoyyjms.html

Ruby: rescue ArgumentError => e
来源：http://dali.pengpengdd.cyou/Article/details/gt2elvglgox.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daxiang520.top/Article/details/gt2qcjcepal.html

[H06] 可选值 / 空值安全访问
来源：http://dali.snrcjt.cn/Article/details/gt2fviazwyt.html

Py:   value = d.get("k") or default
来源：http://dali.chenlongwang.top/Article/details/gt2fvrxisce.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gt2cvdeqvjx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gt2fxubmmjw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gt2jynnxaoa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgfzy.top/Article/details/gt2ktpgnfqp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gt2onlubbzn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aibaodan.cn/Article/details/gt2rbaqgcce.html

C#:   obj?.A?.B ?? default
来源：http://dali.sufxvd.cn/Article/details/gt2yfrsxavn.html

[H07] 断言
来源：http://dali.c1oappe.top/Article/details/gt2iqthbgvc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jianghu66.top/Article/details/gt2coztsftq.html

PHP:  assert($x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2tgzstuis.html

JS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2lmarkzru.html


<!-- 参考信息 -->