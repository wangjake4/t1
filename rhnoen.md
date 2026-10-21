代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtvgavfnkc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gttsbwpeot.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtcepztypc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cashguo.top/Article/details/gtsxvinjso.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoeqegmjv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnqzz.top/Article/details/gtfcjyrrnd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtjfcwslwz.html

[F04] 追加写入文件
来源：http://dali.xziqi.cn/Article/details/gtifkbarqr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zycfv.cn/Article/details/gtibecqgxm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dianchejie.cn/Article/details/gtzpfdydjk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtsmwqdzez.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gtplpahpcm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gtcmllpkle.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guannengcc.top/Article/details/gtswpmylim.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gtaclxgvvw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sufxvd.cn/Article/details/gthiviwseu.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258.top/Article/details/gtyowplktj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jyoumei.cn/Article/details/gtqpmnhxup.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtlwffiemt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtsdmdcfnh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtyprjsalj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtvzykmgwg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuetiantiany.cn/Article/details/gtgycqnuyr.html

Ruby: File.exist?("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtgdiaaxlp.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gtddrdqpmv.html

[F06] 删除文件
来源：http://dali.andypj.xyz/Article/details/gtzdqvictx.html

Py:   os.remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtxbjedqjm.html

PHP:  unlink("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtjgxcmkrj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtfwaomcdx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtnhjbypsz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfpwutqu.html

Go:   os.Remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtjjarmtip.html

Ruby: File.delete("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtickrwrtv.html

C#:   File.Delete("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjaeshiao.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gtzihyfqot.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gtznbtngqz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yvedp.cn/Article/details/gtgjuvjcyg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gtxhoovouq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gteobnyqko.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xylfe.cn/Article/details/gtdbxkmyig.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gtnyxsxqpi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pycfn.com/Article/details/gtxnpcklcu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gthriknyxs.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gtiiiauutg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ppjwa.cn/Article/details/gtvcttfnrg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258888.top/Article/details/gtzcwzuicm.html

JS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtgxsvjykd.html

TS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gthgtwzahe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxeejyuce.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nwbrower.top/Article/details/gtpzufdsjb.html

Ruby: Dir.children("dir")
来源：http://dali.hfpthk.cn/Article/details/gtwhqgxxtn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yueranfly.top/Article/details/gtkpiubdwm.html

[F09] 获取文件大小
来源：http://dali.hywenlv.cn/Article/details/gttiimuzsv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtloalbkxm.html

PHP:  filesize("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtdbslbzmo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtqtgiadji.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gtgxbhfmlv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtqoyloyov.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.smart0.xyz/Article/details/gtqdnivcdo.html

Ruby: File.size("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtjcbeysfj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yongpay.top/Article/details/gtzmyvspai.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tanke756.top/Article/details/gtenxkqpjo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gttnertntg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtkfifaiew.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtxgejtzjr.html

TS:   path.extname("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtwchidseb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fengsongda.top/Article/details/gtillwuror.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtnajsczxr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemhfbgnn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gteouyqeev.html

[F11] 复制与移动文件
来源：http://dali.snrcjt.cn/Article/details/gtdfjrzevt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtceskcmqp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhixingplan.top/Article/details/gtihzaxawh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtpmrbsssf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtjyrircqy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sysykeji.top/Article/details/gtfmikebbr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cheryme.top/Article/details/gtqomcdtvf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtrtrhuiyu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jyoumei.cn/Article/details/gtzyqkvnrz.html

[F12] CSV 读写
来源：http://dali.zhoulong.xyz/Article/details/gteyyvtvee.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gtglxrdaws.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gogol.net.cn/Article/details/gtephhtqup.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxgkffmo.html

TS:   // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtqnkhpoap.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.c1oappe.top/Article/details/gtrrunyszx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gtnbfolvex.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydzrjzol.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jianghu66.top/Article/details/gtspczhdfw.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtcdajlqqs.html

G. 面向对象
来源：http://dali.cucudq.cn/Article/details/gtqaoqacjb.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtlksgpihe.html

[G01] 定义类
来源：http://dali.cucudq.cn/Article/details/gtzuszatqy.html

Py:   class User: pass
来源：http://dali.hysaishi.cn/Article/details/gtzasreyyw.html

PHP:  class User {}
来源：http://dali.hfpthk.cn/Article/details/gtgknatwfm.html

JS:   class User {}
来源：http://dali.ydzc1.top/Article/details/gtfrqyywlu.html

TS:   class User { name: string = ""; }
来源：http://dali.redwolf501.top/Article/details/gtvwwqepqx.html

Java: class User {}
来源：http://dali.birdmap.top/Article/details/gtiqkxfcmn.html

Go:   type User struct { Name string }
来源：http://dali.yueranfly.top/Article/details/gtpddzglps.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gtrcjkjojj.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtervdmcsq.html

[G02] 构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtwogvqdhf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gtgqqjmjym.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.svipenyu.cn/Article/details/gtphkmygwo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrmoxtccf.html

TS:   constructor(public name: string) {}
来源：http://dali.nwbrower.top/Article/details/gtzvhbcrig.html

Java: User(String name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtrexkxqdu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hammf.cn/Article/details/gtvdavaeos.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gtzngzzhkz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gtnyrqgzhk.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gttlzukysi.html

Py:   self.name = "x"
来源：http://dali.havefunace.top/Article/details/gtfvanzucw.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gtcxmrtryn.html

JS:   this.name = "x";
来源：http://dali.xylfe.cn/Article/details/gtbanukwwq.html

TS:   name: string = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtaeinuqxe.html

Java: private String name;
来源：http://dali.quarkkingdee.top/Article/details/gtglmllole.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhiwuduotai.top/Article/details/gtlpqrouam.html

Ruby: @name = "x"
来源：http://dali.fzhhl.top/Article/details/gtoxdazkpi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgquwegce.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gtllgmqzjs.html

Py:   def greet(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gttrggflww.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtoqentfpy.html

JS:   greet() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtspybdoma.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtdjsllrdh.html

Java: String greet() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtpuntunfx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtajqhyeqj.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gtmsshmhew.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gtadpcgnzy.html

[G05] 继承
来源：http://dali.yj20258.top/Article/details/gtrdizqmez.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gtvedxndbo.html

PHP:  class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtfpbgwqin.html

JS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtqrmavwhb.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gttfionzsg.html

Java: class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtwaxearmm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cashguo.top/Article/details/gtlumwjpvg.html

Ruby: class Admin < User; end
来源：http://dali.yj20258888.top/Article/details/gtexegjcag.html

C#:   class Admin : User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtoirwkxqw.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gtttxyuqjc.html

Py:   def greet(self): return "admin"
来源：http://dali.gzhubu.top/Article/details/gtpxdeagna.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtwngacufg.html

JS:   greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtsvtioasv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtilotmffc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtfknfbfwl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.redwolf501.top/Article/details/gtgxwkooxl.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gtnuayizrz.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gtyyykuege.html

[G07] 调用父类方法
来源：http://dali.wangdashe.top/Article/details/gtpbgghuof.html

Py:   super().greet()
来源：http://dali.yangfankeji.com/Article/details/gtapitqsmm.html

PHP:  parent::greet();
来源：http://dali.gogol.net.cn/Article/details/gtqddaeuak.html

JS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gtvwomkdsm.html

TS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gthzsefbub.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtlthikmdm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.redwolf501.top/Article/details/gtjswdwcrq.html

Ruby: super
来源：http://dali.nanxinkj.top/Article/details/gtvwhnnikf.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gtygcgujpd.html

[G08] 静态方法与属性
来源：http://dali.birdmap.top/Article/details/gtdcgcgage.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdiobcvp.html

PHP:  public static function f() {}
来源：http://dali.jyoumei.cn/Article/details/gtapzwvmhu.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtejubzcxu.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gtsegapxfz.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gtauamirmq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenzaomai.com/Article/details/gtvafnmiuk.html

Ruby: def self.f; end
来源：http://dali.shzxlz.cn/Article/details/gtneylcakd.html

C#:   public static void F() {}
来源：http://dali.yj20258888.top/Article/details/gtigkxjrvd.html

[G09] 接口 / 抽象类
来源：http://dali.haohaochexian.top/Article/details/gtuopzpuwa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cdnleiting.top/Article/details/gtzvbsbqui.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.haohaochexian.top/Article/details/gtdzrbffez.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.quarkkingdee.top/Article/details/gtipydztjr.html

TS:   interface Shape { area(): number; }
来源：http://dali.pycfn.com/Article/details/gtmgvuchng.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gtdsrazltq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gtlgbhmcng.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gthtrtnrzi.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqqkkwew.html

[G10] 访问控制
来源：http://dali.snrcjt.cn/Article/details/gtgdhkldxl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yvedp.cn/Article/details/gtanwawvfo.html

PHP:  public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtevikhjwc.html

JS:   #private 字段；其余公开
来源：http://dali.316326.xyz/Article/details/gtviymkvuv.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtgqtiguwf.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gtsvhobbsh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.vqdsnc.cn/Article/details/gtbqlycgfc.html

Ruby: public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtfxufygog.html

C#:   public / protected / private / internal
来源：http://dali.zhengqikj.top/Article/details/gtoamsymbm.html

[G11] getter / setter
来源：http://dali.dianchejie.cn/Article/details/gtmvlacukn.html

Py:   @property 与 @x.setter
来源：http://dali.shuidangran.top/Article/details/gtevsnwhii.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gteparnqiu.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvnmlvvrj.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gtddkaclne.html

Java: public String getName() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtlthqnqxs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteiyeaizq.html

Ruby: attr_accessor :name
来源：http://dali.sweek.top/Article/details/gtdsjgaxau.html

C#:   public string Name { get; set; }
来源：http://dali.zhongyouzk.top/Article/details/gtcnhbdcvz.html

[G12] 对象转字符串
来源：http://dali.pycfn.com/Article/details/gtqedgevdx.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtjvyltgha.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtxtryrbax.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtcwzqntsf.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtztanoxky.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtkfevprhm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtkpsmpjxk.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gtzasgeiem.html

C#:   public override string ToString() => Name;
来源：http://dali.havefunace.top/Article/details/gtfjmqostz.html

[G13] 判断对象类型
来源：http://dali.gzhubu.top/Article/details/gtlldsvplb.html

Py:   isinstance(u, User)
来源：http://dali.shanyushiyangtech.top/Article/details/gthmpbtjya.html

PHP:  $u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtpdzrbocf.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtocgxpesx.html

TS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gttquyqjsu.html

Java: u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtbvbexray.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gtmziqxyza.html

Ruby: u.is_a?(User)
来源：http://dali.ybcxt.top/Article/details/gtutrwrgff.html

C#:   u is User
来源：http://dali.xinyue.icu/Article/details/gtrxfsyfaq.html

[G14] 数据类 / record
来源：http://dali.pengpengdd.cyou/Article/details/gtkahdrprd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ppjwa.cn/Article/details/gterobatlf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dianchejie.cn/Article/details/gtghgspbkf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gtyrxedfgj.html

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gtgrwfxgwp.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gtaerzvcfz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gtalehkbfo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgufenzy.top/Article/details/gtaprbiqpv.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigufen.top/Article/details/gticugtarf.html

[G15] 枚举
来源：http://dali.dashuyun.cn/Article/details/gtuscznkuq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nwbrower.top/Article/details/gtpmykwrww.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sysykeji.top/Article/details/gtwkqyijkz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gzhubu.top/Article/details/gtmmjyntxx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtsomjqmmu.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gtorufentu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shangyingyoupin.top/Article/details/gtfpyxxqgj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shzxlz.cn/Article/details/gtwfbucdde.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtftnzzkrq.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gtxulhlsme.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdelxmew.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gtdaynkbri.html

JS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gtvcusgyld.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtxegqrbrc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.svipenyu.cn/Article/details/gtuancgnig.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyoatgdpy.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gtikogfrco.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtwqwiqhzc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtaqislssf.html

H. 异常与错误处理
来源：http://dali.xinyue.icu/Article/details/gtwhmgsmjh.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtceegfqnl.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gtjlchxgru.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gtsdljftte.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenlongwang.top/Article/details/gtlbztagfp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtfwtrnzzx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtloojyamr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hysaishi.cn/Article/details/gtjeimrmmj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gtrffosluc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.snrcjt.cn/Article/details/gtavtqzlvw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258.top/Article/details/gtyulzidbg.html

[H02] finally / ensure 收尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhflnmjr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.andypj.xyz/Article/details/gtaxoqhuhx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtlemcnmsw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtodxfsgcs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtwbrxdnge.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtcmmzaptn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daria6918.cn/Article/details/gtonobdepu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangdashe.top/Article/details/gtddssdjby.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtiznscfdk.html

[H03] 主动抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gtjdjnpodc.html

Py:   raise ValueError("错误信息")
来源：http://dali.xziqi.cn/Article/details/gtxqdijmks.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gthbkkbhuw.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtqhhcxlgb.html

TS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtranabrog.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtdzdqlrvu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xziqi.cn/Article/details/gtfeqaxreb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gzhubu.top/Article/details/gtybtnmean.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtaocjkzpx.html

[H04] 自定义异常类型
来源：http://dali.cheryme.top/Article/details/gtlndvfust.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gtxzlcqifp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtlnqnxxwo.html

JS:   class MyError extends Error {}
来源：http://dali.xinyue.icu/Article/details/gtalptvwsa.html

TS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtooleskax.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gtfuhcjtkn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangdashe.top/Article/details/gtzxriciah.html

Ruby: class MyError < StandardError; end
来源：http://dali.feifeiyinyue.top/Article/details/gtthnwrtvt.html

C#:   class MyException : Exception {}
来源：http://dali.dianchejie.cn/Article/details/gtczronhij.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gtxlhrxbtz.html

Py:   except ValueError as e:
来源：http://dali.smart0.xyz/Article/details/gtfagrayva.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.vqdsnc.cn/Article/details/gtzrilaign.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gteriuzkmz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gtjtfvdzna.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cucudq.cn/Article/details/gtnvytpoqj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnxnhtcd.html

Ruby: rescue ArgumentError => e
来源：http://dali.tanke756.top/Article/details/gtjfgcyfac.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hammf.cn/Article/details/gtaclzncmn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgfzy.top/Article/details/gtaohpzhtc.html

Py:   value = d.get("k") or default
来源：http://dali.shuidangran.top/Article/details/gtrqpiknco.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gtuzmsbwge.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtwanfgpvr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtcaccnjcm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fengsongda.top/Article/details/gtpfaardgv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenjidiqi.icu/Article/details/gtwxelxydq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkyybbliq.html

C#:   obj?.A?.B ?? default
来源：http://dali.tianlin.xyz/Article/details/gtqnpclyic.html

[H07] 断言
来源：http://dali.xylfe.cn/Article/details/gtybmeqeyu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.0kj1m.cn/Article/details/gtvxzgsqji.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtboxdqscd.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtscvrylzz.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtnmlhvoan.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gtplyvvdlh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.meibo888.top/Article/details/gtnehkadvq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gtndvzkijc.html


<!-- 参考信息 -->