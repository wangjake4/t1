代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2agjarbkt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rxypxqjh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gt2cfdrtgne.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gt2vxoxhikq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gt2asiopxvd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj202588.top/Article/details/gt2rbuwcbjt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuxming.cn/Article/details/gt2pbggakuq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qahfnscs.html

[F05] 判断文件或目录是否存在
来源：http://dali.dianchejie.cn/Article/details/gt2dnevydha.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gt2fgacpnot.html

PHP:  file_exists("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2ybekaegc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2jqvbvigk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2segmwpxw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2wqtvztzt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gotoacloud.top/Article/details/gt2gparhmbl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2wonjfaha.html

C#:   File.Exists("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2iclburho.html

[F06] 删除文件
来源：http://dali.sufxvd.cn/Article/details/gt2dpfazaxx.html

Py:   os.remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2cuxsmord.html

PHP:  unlink("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2ahnnavez.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2ejhlonkx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2uxcubkmx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2vxcgpyeb.html

Go:   os.Remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2tbrbiahw.html

Ruby: File.delete("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2wwgolztd.html

C#:   File.Delete("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2nopohnhw.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gt2iflxumal.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gt2rgyungla.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sxryk.cn/Article/details/gt2hesqodqh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gt2wjdnpecd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gt2vhlkvycq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guowangkeji.top/Article/details/gt2vgopnezj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tianlin.xyz/Article/details/gt2fiddqgfw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pycfn.com/Article/details/gt2qjjyqfhb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hammf.cn/Article/details/gt2eshkrxcf.html

[F08] 遍历目录
来源：http://dali.xylfe.cn/Article/details/gt2eaqwhnzw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gt2ilvqonos.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxuanxn.top/Article/details/gt2otpyrqjs.html

JS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2kadiuoct.html

TS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gt2yrbipchk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gt2fufaidlr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fengsongda.top/Article/details/gt2foycffwb.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2zypmdaac.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2hietiawa.html

[F09] 获取文件大小
来源：http://dali.bjfxy.top/Article/details/gt2nutbwsyq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nfvxjrvy.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2sqyzfdun.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rhwgnlcu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gt2jtvcgmmm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2apmvtdyi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ykeovdzp.html

Ruby: File.size("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2cihfoigf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.redwolf501.top/Article/details/gt2mfkeidlg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vlooldzx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2fgqkjzlf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2fqzdpdwg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mcpcsqqr.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2ygirlzrz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xylfe.cn/Article/details/gt2fsanqxjw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2wtabqfpf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2nmfwcbfk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2vvpismgd.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gt2pvqnlwxe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gt2epdjjxsc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2hbadpfgf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gt2cgfdisoh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbyrltpd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gogol.net.cn/Article/details/gt2ksxioloe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yongpay.top/Article/details/gt2makuhdcf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2lcbhyikc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxinkj.top/Article/details/gt2hbvfbwib.html

[F12] CSV 读写
来源：http://dali.hnqzz.top/Article/details/gt2khosctpd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ydzc1.top/Article/details/gt2xkmgmqxn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gt2jcjotsoz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.bjfxy.top/Article/details/gt2kgmtyens.html

TS:   // 同上
来源：http://dali.yanxiufei.cn/Article/details/gt2kiddfxeg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gt2rbbrotbb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cheryme.top/Article/details/gt2itrbtqcl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tanke756.top/Article/details/gt2xpygiegb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cashguo.top/Article/details/gt2gzatsyvu.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2bnsmgopc.html

G. 面向对象
来源：http://dali.tian-w.cn/Article/details/gt2rdpdogef.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2qqxcuuss.html

[G01] 定义类
来源：http://dali.iojbl.cn/Article/details/gt2cwyvksbm.html

Py:   class User: pass
来源：http://dali.0kj1m.cn/Article/details/gt2evgspycn.html

PHP:  class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2dwwxoynq.html

JS:   class User {}
来源：http://dali.xylfe.cn/Article/details/gt2rwwizoru.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gt2dnwjavlh.html

Java: class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2jdnylbvr.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gt2jhlqbpgw.html

Ruby: class User; end
来源：http://dali.sufxvd.cn/Article/details/gt2xeqppqlb.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gt2gocxrdne.html

[G02] 构造函数
来源：http://dali.0kj1m.cn/Article/details/gt2wwvvpdwk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yueranfly.top/Article/details/gt2qmrzzfgo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.9152youxi.cn/Article/details/gt2ebwrkyiq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gt2kpyukqnm.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gt2cbepdwpn.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2yebbqkyk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tian-w.cn/Article/details/gt2oojyqtrj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bmbcwmbd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gt2eqcxbzzj.html

[G03] 实例属性
来源：http://dali.dianchejie.cn/Article/details/gt2mscvpamq.html

Py:   self.name = "x"
来源：http://dali.ppjwa.cn/Article/details/gt2xmqjbdub.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2ohkfnndp.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttaxwowx.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eloenefm.html

Java: private String name;
来源：http://dali.vqdsnc.cn/Article/details/gt2taracnut.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pycfn.com/Article/details/gt2pchftpcy.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gt2yrnjqaqk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2sycucaqy.html

[G04] 定义方法
来源：http://dali.gotoacloud.top/Article/details/gt2qtzkaguk.html

Py:   def greet(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gt2etuvtiyk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vhhlcxsp.html

JS:   greet() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2xrivkxpo.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrgzzfv.html

Java: String greet() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gt2cjatgqml.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gt2fdkkurbv.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gt2jlntcffg.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gt2wylqyhqe.html

[G05] 继承
来源：http://dali.yj202588.top/Article/details/gt2uhvdnhdz.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gt2clowaxys.html

PHP:  class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ynaozugg.html

JS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2najtqveo.html

TS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2cttikpvh.html

Java: class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gt2tpogwiaq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gt2rikjrojt.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2sketcldm.html

C#:   class Admin : User {}
来源：http://dali.zhengqikj.top/Article/details/gt2qpyoyrrk.html

[G06] 重写方法
来源：http://dali.hysaishi.cn/Article/details/gt2jlthsblx.html

Py:   def greet(self): return "admin"
来源：http://dali.jianghu66.top/Article/details/gt2iizzivmp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gt2oinzbeay.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsijgxvi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2sxxtifgx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2njilffml.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aizwys.cn/Article/details/gt2hikuswez.html

Ruby: def greet; "admin"; end
来源：http://dali.xuanzx.com/Article/details/gt2vxjvwqsd.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gt2ifmhrllf.html

[G07] 调用父类方法
来源：http://dali.shuidangran.top/Article/details/gt2lmeyloyl.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gt2rpajejno.html

PHP:  parent::greet();
来源：http://dali.andypj.xyz/Article/details/gt2anvbcskt.html

JS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gt2zbyiqunp.html

TS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2fneemliu.html

Java: super.greet();
来源：http://dali.ppjwa.cn/Article/details/gt2gfzyuhjn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2vjtnxlkk.html

Ruby: super
来源：http://dali.yj20258.top/Article/details/gt2rtvomuov.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2qngcsggx.html

[G08] 静态方法与属性
来源：http://dali.guannengcc.top/Article/details/gt2auqnuojx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yvedp.cn/Article/details/gt2rojwddnk.html

PHP:  public static function f() {}
来源：http://dali.hammf.cn/Article/details/gt2aiztlthi.html

JS:   static f() {}
来源：http://dali.jinqigufen.top/Article/details/gt2pwouqhju.html

TS:   static f(): void {}
来源：http://dali.aizwys.cn/Article/details/gt2mafihpbl.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2dsazrkmf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.haohaochexian.top/Article/details/gt2yghjjtfb.html

Ruby: def self.f; end
来源：http://dali.haohaochexian.top/Article/details/gt2ixfzwbqz.html

C#:   public static void F() {}
来源：http://dali.cashguo.top/Article/details/gt2sjwyxayc.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gt2rtmuahxs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yongpay.top/Article/details/gt2thnnwplp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258.top/Article/details/gt2ftkdnyqs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.iojbl.cn/Article/details/gt2cglcvxbm.html

TS:   interface Shape { area(): number; }
来源：http://dali.vqdsnc.cn/Article/details/gt2wgutrupv.html

Java: interface Shape { double area(); }
来源：http://dali.zhengqikj.top/Article/details/gt2aollsjab.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aizwys.cn/Article/details/gt2ytnspzdo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ppjwa.cn/Article/details/gt2lbfyidkd.html

C#:   interface IShape { double Area(); }
来源：http://dali.daxiang520.top/Article/details/gt2sharhwtv.html

[G10] 访问控制
来源：http://dali.jqgufenzy.top/Article/details/gt2rhrljzqr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sweek.top/Article/details/gt2ifjrvwmd.html

PHP:  public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gt2aqpwywoq.html

JS:   #private 字段；其余公开
来源：http://dali.jiagoushi.top/Article/details/gt2sfjqffov.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2pxeunyef.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gt2hmataylv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gt2vyfsexgb.html

Ruby: public / protected / private
来源：http://dali.tanke756.top/Article/details/gt2adgcmcwv.html

C#:   public / protected / private / internal
来源：http://dali.hammf.cn/Article/details/gt2aqxeeymm.html

[G11] getter / setter
来源：http://dali.mhx1999.top/Article/details/gt2bwoziccx.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gt2kvlhvkvx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gt2kfrevhlz.html

JS:   get name() { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gt2lridlfuu.html

TS:   get name(): string { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gt2ttaqpxru.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2lffgztrt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tcfdsbbv.html

Ruby: attr_accessor :name
来源：http://dali.bjfxy.top/Article/details/gt2kyckcfwj.html

C#:   public string Name { get; set; }
来源：http://dali.0kj1m.cn/Article/details/gt2cejxerpk.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gt2sqmzvjsf.html

Py:   def __str__(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gt2mdawzwtg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2guhwhgog.html

JS:   toString() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gt2wsdqofdw.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2oqocxotk.html

Java: @Override public String toString() { return name; }
来源：http://dali.meibo888.top/Article/details/gt2kuhbepod.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gt2kctrlfzb.html

Ruby: def to_s; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qandmxls.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zcxlucxu.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gt2syyocuvy.html

Py:   isinstance(u, User)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uhayrjlc.html

PHP:  $u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2oeimtfdl.html

JS:   u instanceof User
来源：http://dali.sweek.top/Article/details/gt2pbyfbvpp.html

TS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2feauvqwf.html

Java: u instanceof User
来源：http://dali.sweek.top/Article/details/gt2nacpkdps.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hywenlv.cn/Article/details/gt2qihildxd.html

Ruby: u.is_a?(User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2piuqmvyz.html

C#:   u is User
来源：http://dali.sysykeji.top/Article/details/gt2ydkhvnsd.html

[G14] 数据类 / record
来源：http://dali.haohaochexian.top/Article/details/gt2tdoohuwd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gt2bhaqwrol.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gt2wxjnohdi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zycfv.cn/Article/details/gt2ciyadbqk.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenjidiqi.icu/Article/details/gt2kzdouxkn.html

Java: record User(String name, int age) {}
来源：http://dali.chenlongwang.top/Article/details/gt2pbwowfrz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shangyingyoupin.top/Article/details/gt2yuehksuu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daxiang520.top/Article/details/gt2gyjrliva.html

C#:   record User(string Name, int Age);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qtnstnio.html

[G15] 枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwqyafic.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jiagoushi.top/Article/details/gt2icgrxdvv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hywenlv.cn/Article/details/gt2twgixwnk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pengpengdd.cyou/Article/details/gt2hdbyizxz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2fqqrmden.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ztnnlhsm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hnqzz.top/Article/details/gt2drsxbnem.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hongshengwenyu.top/Article/details/gt2xltmdeon.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2vffmvlst.html

[G16] 对象转数组 / 字典
来源：http://dali.shuidangran.top/Article/details/gt2dgxzcwmm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gt2frxkzhcw.html

PHP:  get_object_vars($obj);
来源：http://dali.jiagoushi.top/Article/details/gt2zqfrnwfd.html

JS:   Object.entries(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2culkibud.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kgjtdxvm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zycfv.cn/Article/details/gt2blpvsmfj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sxryk.cn/Article/details/gt2zbnxwkaq.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gt2akzixeex.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gt2lhhpqkiq.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2shaeqiaj.html

H. 异常与错误处理
来源：http://dali.nanxuanxn.top/Article/details/gt2tckoymyi.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2xyzsxffg.html

[H01] try / catch 基础
来源：http://dali.tianlin.xyz/Article/details/gt2zhkknwdq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgfzy.top/Article/details/gt2cvaboxvw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fzhhl.top/Article/details/gt2kuihuucr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gt2ssxvccua.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gt2hfgasehg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jyoumei.cn/Article/details/gt2dokvmydn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gogol.net.cn/Article/details/gt2ftzxuusc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yueranfly.top/Article/details/gt2hqddhcdu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258.top/Article/details/gt2tcqtglfm.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gt2xnkixdab.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wyapiwdr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2vkyzyhxi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2meiumnvc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2oqjjtfrl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2tuneroyx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenjidiqi.icu/Article/details/gt2evsltpkd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenlongwang.top/Article/details/gt2rjwwdatj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2eoedhwyp.html

[H03] 主动抛出异常
来源：http://dali.daxiang520.top/Article/details/gt2bvwjnany.html

Py:   raise ValueError("错误信息")
来源：http://dali.shzxlz.cn/Article/details/gt2ajqrymnx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2lnsaykob.html

JS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gt2vmoepapk.html

TS:   throw new Error("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2svogvbvb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2qzgmwnsy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhengqikj.top/Article/details/gt2nchjjjtu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2myshwath.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2yejyoekc.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gt2kztvnxgz.html

Py:   class MyError(Exception): pass
来源：http://dali.fengsongda.top/Article/details/gt2ldslyqte.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gt2jnhzbhyb.html

JS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2nbcauhfa.html

TS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gt2dzfmblhq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhxjmlju.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhengqikj.top/Article/details/gt2jjdetwbl.html

Ruby: class MyError < StandardError; end
来源：http://dali.daxiang520.top/Article/details/gt2qxhqcizv.html

C#:   class MyException : Exception {}
来源：http://dali.hysaishi.cn/Article/details/gt2toncuzsn.html

[H05] 捕获特定类型
来源：http://dali.zhoulong.xyz/Article/details/gt2ydveyiqj.html

Py:   except ValueError as e:
来源：http://dali.cheryme.top/Article/details/gt2mrkouigk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gt2uwbptuio.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2ojjloszb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gt2ckumjvjf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.316326.xyz/Article/details/gt2mpotcfey.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cheryme.top/Article/details/gt2xldsnzhf.html

Ruby: rescue ArgumentError => e
来源：http://dali.zycfv.cn/Article/details/gt2weidfpyt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ybcxt.top/Article/details/gt2kgvwklif.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hfpthk.cn/Article/details/gt2rjbubusc.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gt2irqvkxut.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gnlyfupp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gt2ixyyrohd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gt2rejtvfpd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.vqdsnc.cn/Article/details/gt2hdvvkers.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guannengcc.top/Article/details/gt2rhgcfkwj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gt2bfljrrjf.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gt2bugkzlfp.html

[H07] 断言
来源：http://dali.gaohongyu789.top/Article/details/gt2tpyofyrq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sxryk.cn/Article/details/gt2ybjqoedm.html

PHP:  assert($x > 0);
来源：http://dali.fengsongda.top/Article/details/gt2xwzzillg.html

JS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gt2nlgeiiia.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2ynqkwoiq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gt2ixspmhva.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.haohaochexian.top/Article/details/gt2zilbusrv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xinyue.icu/Article/details/gt2ioakywye.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2fgdqdkks.html

[H08] 获取错误信息与堆栈
来源：http://dali.guowangkeji.top/Article/details/gt2vpbxwvkb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtpoymtw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yueranfly.top/Article/details/gt2dvzfihrj.html

JS:   e.message;  e.stack
来源：http://dali.nanxuanxn.top/Article/details/gt2hjrnckat.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cqqwz.cn/Article/details/gt2crfazsnr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gzhubu.top/Article/details/gt2umducmsu.html

Go:   err.Error()
来源：http://dali.chenlongwang.top/Article/details/gt2poiwnbee.html


<!-- 参考信息 -->