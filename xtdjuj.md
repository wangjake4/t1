代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtjfmegqzf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gzhubu.top/Article/details/gtuahotcqh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtgxhhdwep.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gtekdaxnfj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ivvv.top/Article/details/gtaaeteahr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.mhx1999.top/Article/details/gtidcfhowm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258888.top/Article/details/gtijkuwgsp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yanxiufei.cn/Article/details/gtftotyjqq.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gtofzlnetj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gtfdbhiauf.html

PHP:  file_exists("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtvjsybgoi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtkvtbhznj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtuuafhqir.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtfnxvsjku.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gtrpmratwp.html

Ruby: File.exist?("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtudtrrphy.html

C#:   File.Exists("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtbuganbve.html

[F06] 删除文件
来源：http://dali.fzhhl.top/Article/details/gtuuswrfea.html

Py:   os.remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtfengyoxm.html

PHP:  unlink("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtvdkrxlee.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnxvtiit.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtwabpwabi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtfuzgrpqw.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gtfnhinrcm.html

Ruby: File.delete("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtpgfxtypu.html

C#:   File.Delete("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtgkjkleeg.html

[F07] 创建目录（含多级）
来源：http://dali.jqgfzy.top/Article/details/gtpotquyvp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gtbioarfle.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.bjfxy.top/Article/details/gtzagwfkmo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzulznybw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gtouiddfzu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangshuangyany.cn/Article/details/gtwgonalrh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gtwfbikrvo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aibaodan.cn/Article/details/gtlsygtpdd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigufen.top/Article/details/gtvuhkwdrs.html

[F08] 遍历目录
来源：http://dali.nanxinkj.top/Article/details/gtbmzhvcxu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nwbrower.top/Article/details/gtavzmqduq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tianlin.xyz/Article/details/gtwmyseekh.html

JS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gtnxmdvviw.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtmfnzpbbx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gtxnfyvhca.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtxprokaid.html

Ruby: Dir.children("dir")
来源：http://dali.ivvv.top/Article/details/gtepuyzfcw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cheryme.top/Article/details/gtxtcyingc.html

[F09] 获取文件大小
来源：http://dali.yj202588.top/Article/details/gtyflcjvua.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtusrfxuaq.html

PHP:  filesize("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtkaowdmkq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtnqrddjjm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gtbhkuntpu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtoesmzvzq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.feifeiyinyue.top/Article/details/gtprwgxtph.html

Ruby: File.size("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtlmevgcyp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.birdmap.top/Article/details/gtgyxyrlpt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.andypj.xyz/Article/details/gtweigobky.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtfybmawcm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gtdnrxxobk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtawoyloej.html

TS:   path.extname("a.txt")
来源：http://dali.cashguo.top/Article/details/gtcesvkwak.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gogol.net.cn/Article/details/gtmtvaueiq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtkhchvwom.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtfienaxbk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtymyoouqz.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gtrtkrrysf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtibpzdenc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.mhx1999.top/Article/details/gtisveefdo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtgwsprxjv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtxgbfokuk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yonumen.top/Article/details/gtcnsrvofd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pycfn.com/Article/details/gtnxkmtilt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtyyzgqrxc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yongpay.top/Article/details/gtydptpgna.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gtsabeiadt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqckhloek.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yvedp.cn/Article/details/gtvsdpaaie.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zycfv.cn/Article/details/gtuvugcpzy.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gtxrtqpzzn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgprbrewu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hammf.cn/Article/details/gtmphcursc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gotoacloud.top/Article/details/gtckomvzui.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuanzx.com/Article/details/gtckffffet.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtcmctyqap.html

G. 面向对象
来源：http://dali.wangdashe.top/Article/details/gtrlcftobp.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gthrmxxvsx.html

[G01] 定义类
来源：http://dali.shanyushiyangtech.top/Article/details/gtyyochtej.html

Py:   class User: pass
来源：http://dali.yj20258888.top/Article/details/gttdsuywqv.html

PHP:  class User {}
来源：http://dali.daxiang520.top/Article/details/gtatwglpjt.html

JS:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtumnhzkul.html

TS:   class User { name: string = ""; }
来源：http://dali.tianlin.xyz/Article/details/gtzcsqnmtr.html

Java: class User {}
来源：http://dali.sweek.top/Article/details/gtudmqshfz.html

Go:   type User struct { Name string }
来源：http://dali.hywenlv.cn/Article/details/gtsnwzljbc.html

Ruby: class User; end
来源：http://dali.pycfn.com/Article/details/gtbsvaesas.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtoplsxtpr.html

[G02] 构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtszqcabtn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yueranfly.top/Article/details/gtguxrzdcd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhoulong.xyz/Article/details/gtwphyfvom.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtyerxfips.html

TS:   constructor(public name: string) {}
来源：http://dali.hnxiangtu.top/Article/details/gtgmhaegvn.html

Java: User(String name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gtlxzagazt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jlsjyb.cn/Article/details/gthdcuwgmv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.quarkkingdee.top/Article/details/gtmpvvjfyq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hywenlv.cn/Article/details/gthzcqqjoy.html

[G03] 实例属性
来源：http://dali.tian-w.cn/Article/details/gtsyljdwwj.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gthnuvdzuz.html

PHP:  public string $name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtqrvdiyxp.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtwezmarxc.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gthuudlcca.html

Java: private String name;
来源：http://dali.yj20258.top/Article/details/gtmfagkhyx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.316326.xyz/Article/details/gtitejesmf.html

Ruby: @name = "x"
来源：http://dali.jinqigufen.top/Article/details/gtpndlhfcb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pycfn.com/Article/details/gtpjncuvxw.html

[G04] 定义方法
来源：http://dali.zhiwuduotai.top/Article/details/gthzndrrjj.html

Py:   def greet(self): return self.name
来源：http://dali.sweek.top/Article/details/gtcxicxdep.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gthzvlufbc.html

JS:   greet() { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtuxmyomui.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtrhnydihw.html

Java: String greet() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtzhmownyd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtvokdjmmf.html

Ruby: def greet; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gtoxrqmnwm.html

C#:   public string Greet() => Name;
来源：http://dali.meibo888.top/Article/details/gthdgggmjm.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gttyivppfm.html

Py:   class Admin(User): pass
来源：http://dali.yj20258.top/Article/details/gtfmmuzjdf.html

PHP:  class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtgjghvyxx.html

JS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtgodhsdrh.html

TS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtvlunjlyb.html

Java: class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtnbupgvrq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258888.top/Article/details/gtkicnwvwc.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gtwqhprhvn.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gtvpqjkrbq.html

[G06] 重写方法
来源：http://dali.haohaochexian.top/Article/details/gtflifjdhq.html

Py:   def greet(self): return "admin"
来源：http://dali.xuanzx.com/Article/details/gttsleakbm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtdbifbfxk.html

JS:   greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzuglvtgk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtsawwhwzk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtolwxbjtx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.quarkkingdee.top/Article/details/gtmtvmnjxb.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gtywikazkn.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgfzy.top/Article/details/gtcdsghzwn.html

[G07] 调用父类方法
来源：http://dali.xinyue.icu/Article/details/gtvenqobll.html

Py:   super().greet()
来源：http://dali.hongshengwenyu.top/Article/details/gtblqmjytw.html

PHP:  parent::greet();
来源：http://dali.nanxinkj.top/Article/details/gtzchvwqmn.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtbdgjgtie.html

TS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtaenmmrtw.html

Java: super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtrnxrjgxp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sxryk.cn/Article/details/gtsdpmjgkp.html

Ruby: super
来源：http://dali.hywenlv.cn/Article/details/gtrdwzkyrn.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gtbmltnsaj.html

[G08] 静态方法与属性
来源：http://dali.xuetiantiany.cn/Article/details/gtkfnzryuu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daxiang520.top/Article/details/gtdawhwmte.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gttibitinv.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gteifolgul.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gtcbrqmbsb.html

Java: static void f() {}
来源：http://dali.hnqzz.top/Article/details/gtqjkzawco.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dianchejie.cn/Article/details/gtoimsugas.html

Ruby: def self.f; end
来源：http://dali.dashuyun.cn/Article/details/gtulsfyqqj.html

C#:   public static void F() {}
来源：http://dali.hammf.cn/Article/details/gtqwqviuyl.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gtlwtbmjro.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgfzy.top/Article/details/gtyhvrnmpa.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.316326.xyz/Article/details/gtuiiibpjy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxuanxn.top/Article/details/gtuieyjcka.html

TS:   interface Shape { area(): number; }
来源：http://dali.daria6918.cn/Article/details/gtnrccmuic.html

Java: interface Shape { double area(); }
来源：http://dali.fzhhl.top/Article/details/gtvghexmzq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyynqfzsu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sxryk.cn/Article/details/gtvbxrtazk.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuanzx.com/Article/details/gtqslhtlxv.html

[G10] 访问控制
来源：http://dali.gzhubu.top/Article/details/gtwaejynwt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxuanxn.top/Article/details/gtphydwgul.html

PHP:  public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtnhimowwn.html

JS:   #private 字段；其余公开
来源：http://dali.birdmap.top/Article/details/gtkalgmtbt.html

TS:   public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhjylily.html

Java: public / protected / private / 默认包级
来源：http://dali.hnqzz.top/Article/details/gtzesfjlnz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzjwzbky.html

Ruby: public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtfgdrnrdb.html

C#:   public / protected / private / internal
来源：http://dali.316326.xyz/Article/details/gtubojmpeq.html

[G11] getter / setter
来源：http://dali.ppjwa.cn/Article/details/gtdlebhpfq.html

Py:   @property 与 @x.setter
来源：http://dali.chenzaomai.com/Article/details/gtyndhvubr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtmrozrkvi.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtpunarbny.html

TS:   get name(): string { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gtfwantaqg.html

Java: public String getName() { return name; }
来源：http://dali.meibo888.top/Article/details/gtxuryidlq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtfbnmkiyi.html

Ruby: attr_accessor :name
来源：http://dali.daxiang520.top/Article/details/gtnypikoed.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gtpfqoqwhs.html

[G12] 对象转字符串
来源：http://dali.dianchejie.cn/Article/details/gtilaszgba.html

Py:   def __str__(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtrxialupb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtpaupdskz.html

JS:   toString() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgsmgrvba.html

TS:   toString(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtdpadgonh.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtcmudbcll.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtvmxwezul.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtxogqmpgm.html

C#:   public override string ToString() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gthwtcless.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gtqbespqkl.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gthwrczdfq.html

PHP:  $u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtjtokxuiy.html

JS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtytxrplal.html

TS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtamdbvldg.html

Java: u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtcrqokdxl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hongshengwenyu.top/Article/details/gtnbcwdsxw.html

Ruby: u.is_a?(User)
来源：http://dali.fengsongda.top/Article/details/gtewjnhpou.html

C#:   u is User
来源：http://dali.ydzc1.top/Article/details/gtmvollxho.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gtnjmvyqeg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gtvtgafaoq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtvvvpwbbd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jiagoushi.top/Article/details/gtirehegkp.html

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gtjuqbylsx.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gtfvbwpwbg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gtypvfiowo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jiagoushi.top/Article/details/gtfstqkwvj.html

C#:   record User(string Name, int Age);
来源：http://dali.yuxming.cn/Article/details/gtxnsffcpf.html

[G15] 枚举
来源：http://dali.xylfe.cn/Article/details/gtxpnisclt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shuidangran.top/Article/details/gtrardwjrx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gthrzzojse.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gtnjhordzg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtbobgdbin.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigufen.top/Article/details/gtlyhtmqzq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jyoumei.cn/Article/details/gtdceavhco.html

Ruby: Color = %i[red green].freeze
来源：http://dali.haohaochexian.top/Article/details/gtwqxznrfl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtrubifrat.html

[G16] 对象转数组 / 字典
来源：http://dali.xuanzx.com/Article/details/gtahxktdmi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgufenzy.top/Article/details/gtckjlwhye.html

PHP:  get_object_vars($obj);
来源：http://dali.hnxiangtu.top/Article/details/gtbujyaeyb.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gtjdsxmthv.html

TS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gtuwptqecc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gtysgvkirh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gotoacloud.top/Article/details/gtybcjybkc.html

Ruby: obj.instance_variables
来源：http://dali.hammf.cn/Article/details/gthnryixvw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gtlicxhtds.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtouzigand.html

H. 异常与错误处理
来源：http://dali.havefunace.top/Article/details/gtrixxkfas.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtyzruzccu.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gtrrspftvt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hfpthk.cn/Article/details/gtrjpavqzn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.meibo888.top/Article/details/gtljukaajy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtsmzmwtyn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gthjkambfe.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shzxlz.cn/Article/details/gtipgnnzei.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gtlabmhdde.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fzhhl.top/Article/details/gtuueoivhb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqsvudqym.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gtgopamqzp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guannengcc.top/Article/details/gtaosmgzvk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtqalmranw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtodsaneop.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtbydhmsab.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtdbfizbqa.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gtrgiwaikz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gthfeyhylw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtsqxffmsc.html

[H03] 主动抛出异常
来源：http://dali.xziqi.cn/Article/details/gthfwiqeom.html

Py:   raise ValueError("错误信息")
来源：http://dali.cashguo.top/Article/details/gtxkdujunh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtdxlstgjm.html

JS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtxcpvfulq.html

TS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtvwvqftda.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtohkrrxoj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fzhhl.top/Article/details/gtawnllzkz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hfpthk.cn/Article/details/gtewyqapma.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtbmtdisqz.html

[H04] 自定义异常类型
来源：http://dali.yj202588.top/Article/details/gtidmvxeek.html

Py:   class MyError(Exception): pass
来源：http://dali.chenzaomai.com/Article/details/gttarguujz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gtzwnbstan.html

JS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gtaujqycaw.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gtyqsvlbii.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gtbtrioguv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sysykeji.top/Article/details/gtjkexqyyh.html

Ruby: class MyError < StandardError; end
来源：http://dali.hysaishi.cn/Article/details/gtldkrjwom.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzdgrtqx.html

[H05] 捕获特定类型
来源：http://dali.yonumen.top/Article/details/gtupqgbjrs.html

Py:   except ValueError as e:
来源：http://dali.xylfe.cn/Article/details/gtskadufon.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cucudq.cn/Article/details/gtoivxfltm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cheryme.top/Article/details/gtlrcjapdc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtjqyymyhj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gtnkpntgnk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ydzc1.top/Article/details/gtvinehang.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gtraharrnu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhengqikj.top/Article/details/gtfdiogadj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuxming.cn/Article/details/gtczsxmahf.html

Py:   value = d.get("k") or default
来源：http://dali.hnxiangtu.top/Article/details/gtrxncwohl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtijfiquml.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gtdoowetiw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gtgklgcuha.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gttcgnktxq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258.top/Article/details/gtgfgrdhvw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.birdmap.top/Article/details/gtojgvqchr.html

C#:   obj?.A?.B ?? default
来源：http://dali.xinyue.icu/Article/details/gtgaelxdbr.html

[H07] 断言
来源：http://dali.jqgfzy.top/Article/details/gtkadzabeh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgufenzy.top/Article/details/gtiwtfrfml.html

PHP:  assert($x > 0);
来源：http://dali.yj202588.top/Article/details/gtjeupmkfk.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gttzzuxqho.html

TS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtaqqjbopo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tianlin.xyz/Article/details/gtedgpuaii.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigufen.top/Article/details/gtoyfltpif.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xuanzx.com/Article/details/gtufmesskx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtuqcjcaeo.html

[H08] 获取错误信息与堆栈
来源：http://dali.tanke756.top/Article/details/gtgeeuerfq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daxiang520.top/Article/details/gtprkktnzv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.dashuyun.cn/Article/details/gtpxkbtcsd.html

JS:   e.message;  e.stack
来源：http://dali.jqgfzy.top/Article/details/gtqluyithe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gtaumorkgl.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jianghu66.top/Article/details/gttnneocty.html

Go:   err.Error()
来源：http://dali.nanxinkj.top/Article/details/gtnkpkuglp.html


<!-- 参考信息 -->