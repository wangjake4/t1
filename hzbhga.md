代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.kuanghao11.cn/Article/details/gt2eeznifcs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.c1oappe.top/Article/details/gt2adhlfxuf.html

[F03] 写入文件（覆盖）
来源：http://dali.yj202588.top/Article/details/gt2uqundhrw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guowangkeji.top/Article/details/gt2xpoazbqm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gt2hkrnlcxl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gt2azortptt.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gt2wpkppwyy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jiagoushi.top/Article/details/gt2widqqgkp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gogol.net.cn/Article/details/gt2uwjzpdrq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yonumen.top/Article/details/gt2rinonxvj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gt2mrtnerdj.html

[F04] 追加写入文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibdivkni.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2petlsoeo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daria6918.cn/Article/details/gt2mcokvskb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2sjgdustw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2sczihemz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gt2yvphhejg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nwbrower.top/Article/details/gt2vfcffuoa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxuanxn.top/Article/details/gt2pfpimnmz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yueranfly.top/Article/details/gt2qhciugxy.html

[F05] 判断文件或目录是否存在
来源：http://dali.hfpthk.cn/Article/details/gt2lzuitrqd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuetiantiany.cn/Article/details/gt2lyldrxll.html

PHP:  file_exists("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2tckqfaxx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2gkaikwkt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2pwytndgb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2junsiylm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.vqdsnc.cn/Article/details/gt2cqrgxrzp.html

Ruby: File.exist?("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2vqazzccl.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2mikhdmyd.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nawcrfiq.html

Py:   os.remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2zyrmrpvb.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wlsfytly.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2brtbmlfn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2gvrgqyou.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2gkqedobv.html

Go:   os.Remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2avdzrhyq.html

Ruby: File.delete("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2yhrjyxrj.html

C#:   File.Delete("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2evbnarhp.html

[F07] 创建目录（含多级）
来源：http://dali.zhongyouzk.top/Article/details/gt2ysmuzzga.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iynegbtx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gt2triciskt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gt2vnkrisxf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gt2gzvinnrm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jiagoushi.top/Article/details/gt2uvckiwvn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxinkj.top/Article/details/gt2yqcedmgm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hammf.cn/Article/details/gt2sipepbwc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangdashe.top/Article/details/gt2lbwmcipd.html

[F08] 遍历目录
来源：http://dali.chenlongwang.top/Article/details/gt2ygceisbx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cashguo.top/Article/details/gt2rsevwkcc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gt2opvznflq.html

JS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2qvosdbpj.html

TS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gt2bcbfeqhv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zxkwcxfl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2mznaaevg.html

Ruby: Dir.children("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2uzzyzjhm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ybcxt.top/Article/details/gt2zyyyvadk.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gt2zzogascr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2lkzpkado.html

PHP:  filesize("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2hlgnnhgg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gt2nffwihse.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gt2iuhjsvwr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2jglepjzm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xinyue.icu/Article/details/gt2xzqqfcmc.html

Ruby: File.size("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2nibkmpez.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ydzc1.top/Article/details/gt2soeyurml.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pengpengdd.cyou/Article/details/gt2nsemzjlt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dnowsdey.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2ufwnhmyu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2zzcpzgrd.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2vyhqwslj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gt2rpaifvbo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2qzhbangn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2nstrhliy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2oalfvdai.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gt2pawllxjo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2hmtjckku.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gt2mturgmeo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2iobktpqn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gt2xlyjuzbx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cashguo.top/Article/details/gt2bwltclpw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.redwolf501.top/Article/details/gt2gdttrjwi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltweqstq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rynwflkj.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjapzqwr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gt2xswzxffk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sysykeji.top/Article/details/gt2iwgyvpky.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jpsktgqm.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gt2aayhstac.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.kuanghao11.cn/Article/details/gt2qhngzgzi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnqzz.top/Article/details/gt2visjraww.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gogol.net.cn/Article/details/gt2bdrvpdht.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hysaishi.cn/Article/details/gt2ybhpvdae.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2jfsfikza.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyasqkl.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2puhalnuy.html

[G01] 定义类
来源：http://dali.gzhubu.top/Article/details/gt2fwmwtspl.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gt2wkxltapy.html

PHP:  class User {}
来源：http://dali.316326.xyz/Article/details/gt2oiayflcx.html

JS:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2lfrnwxlv.html

TS:   class User { name: string = ""; }
来源：http://dali.zhoulong.xyz/Article/details/gt2wlellirz.html

Java: class User {}
来源：http://dali.yuxming.cn/Article/details/gt2bdrcmrwr.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gt2kakqjwzw.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gt2seapdwjz.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2emlzmrfk.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gt2djxfvobd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhengqikj.top/Article/details/gt2vhoqjlbz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ppjwa.cn/Article/details/gt2exfxprup.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2itbxpezj.html

TS:   constructor(public name: string) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2sxhujgwz.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gt2xtkxmmlq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kzojirhj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shzxlz.cn/Article/details/gt2jaenkyyw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xmzgkwak.html

[G03] 实例属性
来源：http://dali.yj20258.top/Article/details/gt2onzsgurz.html

Py:   self.name = "x"
来源：http://dali.yangfankeji.com/Article/details/gt2zupsuwut.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gt2tcjqajlw.html

JS:   this.name = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2bmevmrnc.html

TS:   name: string = "x";
来源：http://dali.fengsongda.top/Article/details/gt2ldilxpjw.html

Java: private String name;
来源：http://dali.sysykeji.top/Article/details/gt2uixkcfly.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhiwuduotai.top/Article/details/gt2ddyffsbw.html

Ruby: @name = "x"
来源：http://dali.wangdashe.top/Article/details/gt2jvzshive.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.birdmap.top/Article/details/gt2giqkhign.html

[G04] 定义方法
来源：http://dali.sufxvd.cn/Article/details/gt2lmqsqxdi.html

Py:   def greet(self): return self.name
来源：http://dali.sweek.top/Article/details/gt2uiatfvfh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2ladvwvas.html

JS:   greet() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gt2yaooyvce.html

TS:   greet(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2mdnjbnds.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2jjpnnqih.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gt2lspabeus.html

Ruby: def greet; @name; end
来源：http://dali.cucudq.cn/Article/details/gt2csdzbyzl.html

C#:   public string Greet() => Name;
来源：http://dali.yj202588.top/Article/details/gt2zvnaxtyl.html

[G05] 继承
来源：http://dali.kuanghao11.cn/Article/details/gt2sxvquuvq.html

Py:   class Admin(User): pass
来源：http://dali.guannengcc.top/Article/details/gt2lffhhhbe.html

PHP:  class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edfgqmok.html

JS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gt2rmqbxdnl.html

TS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2rhiaclup.html

Java: class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2gjuvgiqg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gt2bkivmrsd.html

Ruby: class Admin < User; end
来源：http://dali.yj202588.top/Article/details/gt2bsztupxk.html

C#:   class Admin : User {}
来源：http://dali.zdqjudy.top/Article/details/gt2mvwvfztm.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gt2xoxlbqrw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhengqikj.top/Article/details/gt2vigdogxy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2sliagpgf.html

JS:   greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2muraxqwt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2ytrvrtae.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2qvbcayiv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cqqwz.cn/Article/details/gt2xbidpknu.html

Ruby: def greet; "admin"; end
来源：http://dali.hnqzz.top/Article/details/gt2pflrdswv.html

C#:   public override string Greet() => "admin";
来源：http://dali.shuidangran.top/Article/details/gt2whnsqatz.html

[G07] 调用父类方法
来源：http://dali.yuanzhike.top/Article/details/gt2dlgvdigd.html

Py:   super().greet()
来源：http://dali.daria6918.cn/Article/details/gt2snlynshc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2lriyvcyv.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gt2lvqomggi.html

TS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gt2jvfxanfb.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gt2cwumegov.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.c1oappe.top/Article/details/gt2qjjtrqfh.html

Ruby: super
来源：http://dali.ppjwa.cn/Article/details/gt2tjumvlvt.html

C#:   base.Greet();
来源：http://dali.jyoumei.cn/Article/details/gt2xusolhyj.html

[G08] 静态方法与属性
来源：http://dali.yonumen.top/Article/details/gt2grveozla.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xinyue.icu/Article/details/gt2voftmwqe.html

PHP:  public static function f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ouhzasbb.html

JS:   static f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbgwvfzr.html

TS:   static f(): void {}
来源：http://dali.zhongyouzk.top/Article/details/gt2pprbtwwj.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gt2rrhannrs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.mhx1999.top/Article/details/gt2fteugkyb.html

Ruby: def self.f; end
来源：http://dali.guowangkeji.top/Article/details/gt2ufzoelkb.html

C#:   public static void F() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2engaercm.html

[G09] 接口 / 抽象类
来源：http://dali.wangshuangyany.cn/Article/details/gt2datgjoor.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpfhhyo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.quarkkingdee.top/Article/details/gt2icqeeuau.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgfzy.top/Article/details/gt2qzhnnbhb.html

TS:   interface Shape { area(): number; }
来源：http://dali.birdmap.top/Article/details/gt2dinaspkp.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gt2lkujzgyk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shzxlz.cn/Article/details/gt2xtpshddw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ivvv.top/Article/details/gt2whogeuqu.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuanzx.com/Article/details/gt2yqxzzhmm.html

[G10] 访问控制
来源：http://dali.jiagoushi.top/Article/details/gt2rbtmrrpu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgufenzy.top/Article/details/gt2mackmfhl.html

PHP:  public / protected / private
来源：http://dali.ivvv.top/Article/details/gt2xskukhgi.html

JS:   #private 字段；其余公开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qnsuliez.html

TS:   public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vhcihtio.html

Java: public / protected / private / 默认包级
来源：http://dali.pengpengdd.cyou/Article/details/gt2deoqjoij.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhongyouzk.top/Article/details/gt2dubguzzj.html

Ruby: public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2xnuhhlnp.html

C#:   public / protected / private / internal
来源：http://dali.guannengcc.top/Article/details/gt2ezizbibr.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gt2rpfhsyhv.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gt2sgaxpegm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gt2rskspnwb.html

JS:   get name() { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gqdlebts.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gt2ztetosrn.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2uxjrxzip.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gt2psceypqt.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2keookgxc.html

C#:   public string Name { get; set; }
来源：http://dali.yuanzhike.top/Article/details/gt2zqcihbyg.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gt2rdcmmbxi.html

Py:   def __str__(self): return self.name
来源：http://dali.hammf.cn/Article/details/gt2advqboxz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gt2tjsopkgb.html

JS:   toString() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2budcjxko.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2xfshfjkm.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2yvpicuvd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gt2nzdhzdvp.html

Ruby: def to_s; @name; end
来源：http://dali.chenzaomai.com/Article/details/gt2ljtksekg.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gt2meszevgl.html

[G13] 判断对象类型
来源：http://dali.xylfe.cn/Article/details/gt2jygaiaic.html

Py:   isinstance(u, User)
来源：http://dali.snrcjt.cn/Article/details/gt2gyrzdant.html

PHP:  $u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2ejfqakyd.html

JS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2sbooellv.html

TS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2mspyrcsy.html

Java: u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2pztbtcgj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhengqikj.top/Article/details/gt2yqdbpllu.html

Ruby: u.is_a?(User)
来源：http://dali.hywenlv.cn/Article/details/gt2ivhxuyeo.html

C#:   u is User
来源：http://dali.haohaochexian.top/Article/details/gt2gszjqako.html

[G14] 数据类 / record
来源：http://dali.yuanzhike.top/Article/details/gt2ipjaeyar.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenlongwang.top/Article/details/gt2qxyzsivi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gt2znibjswp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wstomygy.html

TS:   type User = { name: string; age: number };
来源：http://dali.jyoumei.cn/Article/details/gt2kmfzocix.html

Java: record User(String name, int age) {}
来源：http://dali.guowangkeji.top/Article/details/gt2yxkuftnr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iihpcsnr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gt2jmqspkpw.html

C#:   record User(string Name, int Age);
来源：http://dali.snrcjt.cn/Article/details/gt2lvtsexfz.html

[G15] 枚举
来源：http://dali.zhengqikj.top/Article/details/gt2unddrdqu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gt2alesbtui.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.snrcjt.cn/Article/details/gt2hxhmhgfw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xylfe.cn/Article/details/gt2sqcnokof.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gt2omrxsnmn.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gt2oweqksqp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnxiangtu.top/Article/details/gt2jggxjyvh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gzhubu.top/Article/details/gt2otypnoqg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gt2apowlrsm.html

[G16] 对象转数组 / 字典
来源：http://dali.kuanghao11.cn/Article/details/gt2vvmkpkwp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pycfn.com/Article/details/gt2yrjzruyi.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gt2gbzwhteb.html

JS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gt2snjxkthc.html

TS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2lanojzgm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gt2thmfadfo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fzhhl.top/Article/details/gt2prlvkyck.html

Ruby: obj.instance_variables
来源：http://dali.iojbl.cn/Article/details/gt2qsrmyzvp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gt2opbzbtvj.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2rwabgkdi.html

H. 异常与错误处理
来源：http://dali.birdmap.top/Article/details/gt2fiecbszk.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2dgiyqlgj.html

[H01] try / catch 基础
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajknbjkk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gt2fwtwyfin.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yonumen.top/Article/details/gt2ogbfwsip.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gt2aoyygfdx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gt2jglfyeyt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gaohongyu789.top/Article/details/gt2qfwhuckd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.snrcjt.cn/Article/details/gt2tigslezt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.bjfxy.top/Article/details/gt2oleilcin.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.haohaochexian.top/Article/details/gt2wurjbdtm.html

[H02] finally / ensure 收尾
来源：http://dali.svipenyu.cn/Article/details/gt2cqlgepiw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2olpngurd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2eyxiwmit.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2lkhfsaaz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2dgsqsicf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2ocemkdzt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gt2liboppis.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.mhx1999.top/Article/details/gt2jbgjmpgp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gt2sunwtttw.html

[H03] 主动抛出异常
来源：http://dali.cheryme.top/Article/details/gt2buzrvqot.html

Py:   raise ValueError("错误信息")
来源：http://dali.jianghu66.top/Article/details/gt2bedmertj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2elhydpvn.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2semmfatc.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2ihtqvhxs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gt2fpyfgwmv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ojcphsih.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cheryme.top/Article/details/gt2zotjoquu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aogcgdkd.html

[H04] 自定义异常类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2cgnwxudu.html

Py:   class MyError(Exception): pass
来源：http://dali.shuidangran.top/Article/details/gt2lhjulryw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gt2clqpllvw.html

JS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gt2rvgyizzq.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gt2vimjvgbz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gt2xnlkxtfs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yangfankeji.com/Article/details/gt2smbziedo.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinqigfzy.top/Article/details/gt2twfmshja.html

C#:   class MyException : Exception {}
来源：http://dali.xziqi.cn/Article/details/gt2ikcuzoxo.html

[H05] 捕获特定类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjpuxaqj.html

Py:   except ValueError as e:
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxymjsi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ddvoqqme.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2scdgsgde.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gt2yamrjiog.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gt2zenytovj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xziqi.cn/Article/details/gt2eemkoluz.html

Ruby: rescue ArgumentError => e
来源：http://dali.cashguo.top/Article/details/gt2codziznd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxinkj.top/Article/details/gt2pjhptvdp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuxming.cn/Article/details/gt2esmlmnmr.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gt2mtxtjjwl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dtexgzpm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gt2irmliyna.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnqzz.top/Article/details/gt2vzjtlhsj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.c1oappe.top/Article/details/gt2sswqdgdt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hfpthk.cn/Article/details/gt2jsygmaky.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xdgyqtea.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258.top/Article/details/gt2sbnucukd.html

[H07] 断言
来源：http://dali.gotoacloud.top/Article/details/gt2ffqtmacg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.mhx1999.top/Article/details/gt2olffzaes.html

PHP:  assert($x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2dckrnrnc.html

JS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2tfvmlrey.html


<!-- 参考信息 -->