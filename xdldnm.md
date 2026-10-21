代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gzhubu.top/Article/details/gtejjxomdy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangshuangyany.cn/Article/details/gtuxjrnpvx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gtztrholxm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gtyaphdylc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gtihibqpta.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.redwolf501.top/Article/details/gtdlzsvngl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangshuangyany.cn/Article/details/gtsffhchyr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuanzhike.top/Article/details/gtxhgginhr.html

[F05] 判断文件或目录是否存在
来源：http://dali.dashuyun.cn/Article/details/gtpiiaguvd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqssxhato.html

PHP:  file_exists("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gteuwizrwa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtbahfmukl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtxdrrqaai.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtkxlhruyz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hywenlv.cn/Article/details/gtouwcjccg.html

Ruby: File.exist?("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtqicbherd.html

C#:   File.Exists("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtdsyrnbbe.html

[F06] 删除文件
来源：http://dali.guowangkeji.top/Article/details/gtftdflezr.html

Py:   os.remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtfpzxqvau.html

PHP:  unlink("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxerabzi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtgvaksazj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtmdndjixy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtdbvfqmnu.html

Go:   os.Remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gthconwslq.html

Ruby: File.delete("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtdzupnolq.html

C#:   File.Delete("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtxxffzyms.html

[F07] 创建目录（含多级）
来源：http://dali.xylfe.cn/Article/details/gtsorkakva.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gtjsfcuzan.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shzxlz.cn/Article/details/gtfnlrbobr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gttztfdnib.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gtjoapygud.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nwbrower.top/Article/details/gtihsnvxuy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daxiang520.top/Article/details/gtpcnxqonm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zdqjudy.top/Article/details/gttrrehzvk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daria6918.cn/Article/details/gtzhfqvubh.html

[F08] 遍历目录
来源：http://dali.nanxinkj.top/Article/details/gtfkkhkeiq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shangyingyoupin.top/Article/details/gtymayuwlw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gtvptpwmjz.html

JS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtfehvbwkt.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtxzvhwtci.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtolltsnrc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tianlin.xyz/Article/details/gtzjlvfekg.html

Ruby: Dir.children("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtunpsxtfa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ydzc1.top/Article/details/gtlycwfbcz.html

[F09] 获取文件大小
来源：http://dali.haohaochexian.top/Article/details/gtmwlshsfg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtijwnaftg.html

PHP:  filesize("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtcemghmnp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gtqouinsvo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gtxtggbapr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtefekzboi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gtxwamwrvq.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtvlufakhn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgufenzy.top/Article/details/gtciaxsycl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.andypj.xyz/Article/details/gtcmkhskxh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtbxavflxu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aizwys.cn/Article/details/gtmdppdcqx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtiadxrbkc.html

TS:   path.extname("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtgbrfbtra.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jlsjyb.cn/Article/details/gtuobusbqt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtcrfcylox.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gthgnpjidu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtorujbryr.html

[F11] 复制与移动文件
来源：http://dali.chenjidiqi.icu/Article/details/gtiojngpue.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtihpmwepy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nwbrower.top/Article/details/gteazzjpyp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtqajmqnar.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtciupzynt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtdvvbsrnc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gtemxotzvq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtxphlpdmx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.redwolf501.top/Article/details/gtlkmnxlhd.html

[F12] CSV 读写
来源：http://dali.0kj1m.cn/Article/details/gtqeycriuz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gtjxyvrkuc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xziqi.cn/Article/details/gtfjhyyqth.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gtszrjqxqe.html

TS:   // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gtafcprykb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guannengcc.top/Article/details/gtionbouph.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgfzy.top/Article/details/gtxbtxlvtc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nwbrower.top/Article/details/gtopnkcbmw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gzhubu.top/Article/details/gtrdjnjtof.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtlhurpoma.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gtdszrqgbl.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gttnaipkea.html

[G01] 定义类
来源：http://dali.tianlin.xyz/Article/details/gtxyauzbff.html

Py:   class User: pass
来源：http://dali.wangdashe.top/Article/details/gtdiuddxpq.html

PHP:  class User {}
来源：http://dali.xinyue.icu/Article/details/gtjfcqyzej.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gttrjkbwqd.html

TS:   class User { name: string = ""; }
来源：http://dali.hywenlv.cn/Article/details/gtjfhxtgci.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtliurcrny.html

Go:   type User struct { Name string }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbwpjkxp.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gtliogyjwe.html

C#:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtelisgbhu.html

[G02] 构造函数
来源：http://dali.tian-w.cn/Article/details/gturkjkqbq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.havefunace.top/Article/details/gtvmhpqvds.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.havefunace.top/Article/details/gthrzossib.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gtdymggcii.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gttnkqfkao.html

Java: User(String name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gtsyysqxgs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gzhubu.top/Article/details/gtqwglmbhu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.bjfxy.top/Article/details/gtbgkfbyws.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yonumen.top/Article/details/gteoontxwq.html

[G03] 实例属性
来源：http://dali.gogol.net.cn/Article/details/gttfrcyraf.html

Py:   self.name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtdkkaecrc.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gtpinedxle.html

JS:   this.name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtjlghjrqh.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gtyilbfndj.html

Java: private String name;
来源：http://dali.chenjidiqi.icu/Article/details/gtdsqozcwy.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.meibo888.top/Article/details/gtgmbcvoyf.html

Ruby: @name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gtlxaueusf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnqzz.top/Article/details/gtnsftpjyy.html

[G04] 定义方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrqzewou.html

Py:   def greet(self): return self.name
来源：http://dali.chenlongwang.top/Article/details/gtwbljerjb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtoqcoohbt.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtflxcdkch.html

TS:   greet(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtcmssozdp.html

Java: String greet() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtowtvxduj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtsodiknbz.html

Ruby: def greet; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtmifulnqc.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtyichzkse.html

[G05] 继承
来源：http://dali.chenjidiqi.icu/Article/details/gtbufwpifk.html

Py:   class Admin(User): pass
来源：http://dali.cucudq.cn/Article/details/gtzavqejdo.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtfzeslvby.html

JS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtxylmmqgm.html

TS:   class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtyredqqmr.html

Java: class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqjmsbtd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenzaomai.com/Article/details/gtvjtvzaob.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gtgxnzrgwo.html

C#:   class Admin : User {}
来源：http://dali.cashguo.top/Article/details/gtknwkbthj.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gtxrubfuaf.html

Py:   def greet(self): return "admin"
来源：http://dali.yongpay.top/Article/details/gtefwgclst.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtewpllzox.html

JS:   greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmikicnbx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtdsjogkdx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtbiexnkdk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinyuanbaomall.cn/Article/details/gteiybghqb.html

Ruby: def greet; "admin"; end
来源：http://dali.yangfankeji.com/Article/details/gtwaopavkx.html

C#:   public override string Greet() => "admin";
来源：http://dali.smart0.xyz/Article/details/gtyknrwsbb.html

[G07] 调用父类方法
来源：http://dali.shzxlz.cn/Article/details/gthcshzzud.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gttdoyapji.html

PHP:  parent::greet();
来源：http://dali.pengpengdd.cyou/Article/details/gthmvtxfyq.html

JS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gttqvxnwoy.html

TS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtwfomfuin.html

Java: super.greet();
来源：http://dali.ybcxt.top/Article/details/gtdlbtjsks.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ydzc1.top/Article/details/gtpbizgsls.html

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gtzinfkvra.html

C#:   base.Greet();
来源：http://dali.zhengqikj.top/Article/details/gtyzdlpqby.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gtzoyverjx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcskhcoih.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gtrrykpjlh.html

JS:   static f() {}
来源：http://dali.sxryk.cn/Article/details/gtdivursqy.html

TS:   static f(): void {}
来源：http://dali.tian-w.cn/Article/details/gtpgbtfydx.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtxlaatmse.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgfzy.top/Article/details/gtsuiizmxx.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gtqebcbszm.html

C#:   public static void F() {}
来源：http://dali.fzhhl.top/Article/details/gthvbkumxr.html

[G09] 接口 / 抽象类
来源：http://dali.shuidangran.top/Article/details/gtfklhmpsk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yueranfly.top/Article/details/gtmlticvfo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.haohaochexian.top/Article/details/gttjjfhiay.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgufenzy.top/Article/details/gtvaeilcdq.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzocspajq.html

Java: interface Shape { double area(); }
来源：http://dali.shuidangran.top/Article/details/gtfmzlkuay.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gtasdjdkio.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlblxdaop.html

C#:   interface IShape { double Area(); }
来源：http://dali.xylfe.cn/Article/details/gtwafrxhjm.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gtdkzyfinl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.smart0.xyz/Article/details/gtlopzlywq.html

PHP:  public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtyhxdwwxq.html

JS:   #private 字段；其余公开
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsokjempg.html

TS:   public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtdidqdnse.html

Java: public / protected / private / 默认包级
来源：http://dali.ydzc1.top/Article/details/gtownjwmpf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dianchejie.cn/Article/details/gtcnlafchh.html

Ruby: public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtosiiszyc.html

C#:   public / protected / private / internal
来源：http://dali.sxryk.cn/Article/details/gtvsymjtng.html

[G11] getter / setter
来源：http://dali.gogol.net.cn/Article/details/gtrtsakonj.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gtmwptcboo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gthsmonokz.html

JS:   get name() { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtcdlcpnaq.html

TS:   get name(): string { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gtwjjazszb.html

Java: public String getName() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtgwnyceza.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtsuoxxebg.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gtxkcxbyfg.html

C#:   public string Name { get; set; }
来源：http://dali.pycfn.com/Article/details/gtpridaodj.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gtxwvunils.html

Py:   def __str__(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtrxdmygal.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtwuqwphdq.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtixefaxtq.html

TS:   toString(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtgqmjdijk.html

Java: @Override public String toString() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtuwtelaay.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtllmqavxu.html

Ruby: def to_s; @name; end
来源：http://dali.0kj1m.cn/Article/details/gtmqiaxmxk.html

C#:   public override string ToString() => Name;
来源：http://dali.nwbrower.top/Article/details/gtukipgxsd.html

[G13] 判断对象类型
来源：http://dali.zhiwuduotai.top/Article/details/gtnvbappvb.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gtyberaszh.html

PHP:  $u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtnvphoutk.html

JS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtdukruhgm.html

TS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtplttnlci.html

Java: u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtkxahlzjk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhengqikj.top/Article/details/gthenixvac.html

Ruby: u.is_a?(User)
来源：http://dali.hfpthk.cn/Article/details/gtvjyaddox.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gtwkebicmh.html

[G14] 数据类 / record
来源：http://dali.iojbl.cn/Article/details/gttdycpktz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gtgvodjsfe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yonumen.top/Article/details/gteytmweaa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gthunqumvn.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxuanxn.top/Article/details/gtsiwhdfuu.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gtqrxpaudu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtausvwphk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guannengcc.top/Article/details/gttfheartj.html

C#:   record User(string Name, int Age);
来源：http://dali.yueranfly.top/Article/details/gtrfxohert.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gtatercadn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hongshengwenyu.top/Article/details/gtpfxuxpdz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllrqagkj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.bjfxy.top/Article/details/gttdthsxep.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtjspawuyo.html

Java: enum Color { RED, GREEN }
来源：http://dali.cqqwz.cn/Article/details/gtbvhwyioz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sufxvd.cn/Article/details/gtatnkmjfr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hammf.cn/Article/details/gtllrokkko.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gtduttybsq.html

[G16] 对象转数组 / 字典
来源：http://dali.fzhhl.top/Article/details/gtllwpcmtx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gzhubu.top/Article/details/gtszeerjjy.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gtmjalcpli.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtjqhxwrff.html

TS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gtjemcjbox.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gtzmrnxbgc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hysaishi.cn/Article/details/gtpyvfixem.html

Ruby: obj.instance_variables
来源：http://dali.xuanzx.com/Article/details/gtkxfdrtys.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gtkotonsxi.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtxxhgoemb.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjbixoeb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtqdkyqmad.html

[H01] try / catch 基础
来源：http://dali.c1oappe.top/Article/details/gtlspjksll.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yanxiufei.cn/Article/details/gtgaxykiih.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gtifkdenia.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtkrqudlpm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtctvssxos.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gtlarfskxc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtlejimael.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xylfe.cn/Article/details/gtictodpen.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gtmrrkzoxj.html

[H02] finally / ensure 收尾
来源：http://dali.daria6918.cn/Article/details/gtkamgzqtp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gtkoedydpm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtxhojcfai.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gttmliefvr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtwwzyouuv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtiufduaeb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jiagoushi.top/Article/details/gtrqlmbqmo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybjjrhpd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtxqnmksmf.html

[H03] 主动抛出异常
来源：http://dali.kuanghao11.cn/Article/details/gtmtopplmu.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gtpaovryjv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtdackpiyh.html

JS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtkslodltw.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtrmtyfxnn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtokyxbbbm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daxiang520.top/Article/details/gttxuwllyl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gtlddhmgnp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtqblgwxqu.html

[H04] 自定义异常类型
来源：http://dali.redwolf501.top/Article/details/gtneodowut.html

Py:   class MyError(Exception): pass
来源：http://dali.cdnleiting.top/Article/details/gtqeqpvcyn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtxqwchejf.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtyupsxtyb.html

TS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gttwnpykwa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtvdnytsqf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gtsthwielt.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gtiaxzedjg.html

C#:   class MyException : Exception {}
来源：http://dali.zycfv.cn/Article/details/gtkcxrnids.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gtfmvmocrr.html

Py:   except ValueError as e:
来源：http://dali.cucudq.cn/Article/details/gtsulrnvdl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenjidiqi.icu/Article/details/gtasgpuxnd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gtiokjmacq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gtnigwuwpz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yonumen.top/Article/details/gtfkgefcop.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.mhx1999.top/Article/details/gtqlaimjsd.html

Ruby: rescue ArgumentError => e
来源：http://dali.zdqjudy.top/Article/details/gthzzejerc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtofvmpnxf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cashguo.top/Article/details/gtjofpjrht.html

Py:   value = d.get("k") or default
来源：http://dali.hysaishi.cn/Article/details/gtucyhdtcb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtknsykfaj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtcyiocjyk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtqonrqwob.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxinkj.top/Article/details/gtchxwqagr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhoulong.xyz/Article/details/gtgotweoof.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtxhdbiy.html

C#:   obj?.A?.B ?? default
来源：http://dali.meibo888.top/Article/details/gtzyjmuvst.html

[H07] 断言
来源：http://dali.tanke756.top/Article/details/gtlwifkkca.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhiwuduotai.top/Article/details/gtmoobczpp.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gtozdpvzbt.html

JS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtattvdnli.html

TS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorwlyzcd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hysaishi.cn/Article/details/gtsvheafxw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dianchejie.cn/Article/details/gtckhwpzqn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.meibo888.top/Article/details/gthruzlsgm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtqxqpyvre.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gtrxbgsfgd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yongpay.top/Article/details/gtetvqpayo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.316326.xyz/Article/details/gtlrdwevet.html

JS:   e.message;  e.stack
来源：http://dali.aizwys.cn/Article/details/gtdhuiybzv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigfzy.top/Article/details/gtcyjpowcc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yanxiufei.cn/Article/details/gthhiedxpm.html

Go:   err.Error()
来源：http://dali.svipenyu.cn/Article/details/gtufzscokw.html


<!-- 参考信息 -->