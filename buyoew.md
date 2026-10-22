代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.meibo888.top/Article/details/gt2bgzwoyfs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xylfe.cn/Article/details/gt2ibmnwobv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ddxbsosf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gt2jxlrisrs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guannengcc.top/Article/details/gt2tamfuzve.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ehwqpu.com/Article/details/gt2vbdmgjnt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zdqjudy.top/Article/details/gt2wrfbyosd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuxming.cn/Article/details/gt2dudqqsnq.html

[F05] 判断文件或目录是否存在
来源：http://dali.xinyue.icu/Article/details/gt2orvwjryb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258888.top/Article/details/gt2thhuzfyo.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2lvsofnkf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2vkcohrsw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2psgkdvye.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rhdhgqcv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cdnleiting.top/Article/details/gt2quetotqu.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2afdjzohd.html

C#:   File.Exists("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nnkgzclz.html

[F06] 删除文件
来源：http://dali.daxiang520.top/Article/details/gt2kpkjpuvm.html

Py:   os.remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ezedonrz.html

PHP:  unlink("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lbxenyzf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2yilgbtey.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2isasojrg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2villxdzi.html

Go:   os.Remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2tthjttnr.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2poeuyfxq.html

C#:   File.Delete("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2rjzehqqx.html

[F07] 创建目录（含多级）
来源：http://dali.cqqwz.cn/Article/details/gt2agcpjgzg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xinyue.icu/Article/details/gt2lbtmjwlm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xziqi.cn/Article/details/gt2fonxqlfz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gt2vmrqkaip.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gt2qesiymqr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sweek.top/Article/details/gt2xcbpimlq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258.top/Article/details/gt2ghjrtxit.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gt2wrkukcbs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yangfankeji.com/Article/details/gt2fqkpxtbi.html

[F08] 遍历目录
来源：http://dali.sweek.top/Article/details/gt2jegezwvf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.316326.xyz/Article/details/gt2fipuqqpu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhoulong.xyz/Article/details/gt2drovsnkj.html

JS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2vmvimboh.html

TS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2kdazmdzp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gt2hminzwag.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tanke756.top/Article/details/gt2kgfckyrc.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gt2twmgcpoh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sweek.top/Article/details/gt2muvzpfdt.html

[F09] 获取文件大小
来源：http://dali.jqgufenzy.top/Article/details/gt2ibyrhxfy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2qzqicjqf.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2oykxrovb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gt2tmxegjpq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gt2dcecsoti.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gt2rzysaibb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgfzy.top/Article/details/gt2xdgqebxx.html

Ruby: File.size("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2agpxcoqk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxuanxn.top/Article/details/gt2cnahrreq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gt2gtgrwjbu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2dxpoekot.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2ktfyjvrk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2hgbyqbmb.html

TS:   path.extname("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2qwxevckg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hysaishi.cn/Article/details/gt2rceyibhe.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2vitfxkni.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2zcnoanfb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2zpncxmgm.html

[F11] 复制与移动文件
来源：http://dali.zdqjudy.top/Article/details/gt2krsfikhs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2qqlqrcfa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fengsongda.top/Article/details/gt2uyjdgblw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2ooykakme.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2fxxptgrv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yangfankeji.com/Article/details/gt2czqqdqxp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dashuyun.cn/Article/details/gt2vivjqual.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2jqalhayc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.kuanghao11.cn/Article/details/gt2uqyljcoe.html

[F12] CSV 读写
来源：http://dali.gotoacloud.top/Article/details/gt2fkbzcbii.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gt2hrifczyu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gt2fipjtzzn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dashuyun.cn/Article/details/gt2lmunamcf.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gt2ywtfmdcy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.9152youxi.cn/Article/details/gt2jjporbdl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zdqjudy.top/Article/details/gt2vdnibdhr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jyoumei.cn/Article/details/gt2nuqwatoc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ybcxt.top/Article/details/gt2tozibuhw.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2ttwjordb.html

G. 面向对象
来源：http://dali.tianlin.xyz/Article/details/gt2buzgbwag.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2wzqhvxwo.html

[G01] 定义类
来源：http://dali.316326.xyz/Article/details/gt2oxpnzdzn.html

Py:   class User: pass
来源：http://dali.0kj1m.cn/Article/details/gt2quywwlud.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2jcnakvqr.html

JS:   class User {}
来源：http://dali.smart0.xyz/Article/details/gt2ensqzuhh.html

TS:   class User { name: string = ""; }
来源：http://dali.fzhhl.top/Article/details/gt2csumhowf.html

Java: class User {}
来源：http://dali.sweek.top/Article/details/gt2elvjzrjz.html

Go:   type User struct { Name string }
来源：http://dali.gzhubu.top/Article/details/gt2clabnrkb.html

Ruby: class User; end
来源：http://dali.redwolf501.top/Article/details/gt2ovsxtjeq.html

C#:   class User {}
来源：http://dali.tanke756.top/Article/details/gt2fjxagkwn.html

[G02] 构造函数
来源：http://dali.0kj1m.cn/Article/details/gt2lmesfsof.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpidowcd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2sxkemimx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gt2ueyqyyoo.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gt2sihzbzca.html

Java: User(String name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gt2tlshfjvp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aibaodan.cn/Article/details/gt2uacudaia.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenzaomai.com/Article/details/gt2xmuhnsjb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2xvfavcvh.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gt2zazswayt.html

Py:   self.name = "x"
来源：http://dali.nanxinkj.top/Article/details/gt2ivqecpqc.html

PHP:  public string $name = "x";
来源：http://dali.ehwqpu.com/Article/details/gt2nuocmqeh.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2dbuiujgv.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ieimmfzp.html

Java: private String name;
来源：http://dali.zycfv.cn/Article/details/gt2ttcmrjgx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gt2miwsvqnx.html

Ruby: @name = "x"
来源：http://dali.hfpthk.cn/Article/details/gt2icxvdbbx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gt2zwmzubun.html

[G04] 定义方法
来源：http://dali.0kj1m.cn/Article/details/gt2zlkqnfyy.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gt2sccfvpun.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2icxxkmrn.html

JS:   greet() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2brxzpoak.html

TS:   greet(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gt2txspwplw.html

Java: String greet() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2cgdlriys.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gt2ntxbiefb.html

Ruby: def greet; @name; end
来源：http://dali.guannengcc.top/Article/details/gt2mqsxjfcc.html

C#:   public string Greet() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2bvzxyxxs.html

[G05] 继承
来源：http://dali.chenlongwang.top/Article/details/gt2gkujcyml.html

Py:   class Admin(User): pass
来源：http://dali.fengsongda.top/Article/details/gt2jzrkksqr.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gt2ixwuzpae.html

JS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gt2imuhmekg.html

TS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gt2czdpiyez.html

Java: class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gt2atmxuhwm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj202588.top/Article/details/gt2juotpdrt.html

Ruby: class Admin < User; end
来源：http://dali.ivvv.top/Article/details/gt2vdhkcbfh.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gt2pjbmiboh.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2raazlcnv.html

Py:   def greet(self): return "admin"
来源：http://dali.sweek.top/Article/details/gt2qkwibdhj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2tttaorpf.html

JS:   greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2pzuxltzh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sbdwuiwm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ipdgkngn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nhdywfqh.html

Ruby: def greet; "admin"; end
来源：http://dali.tanke756.top/Article/details/gt2vgpurkht.html

C#:   public override string Greet() => "admin";
来源：http://dali.aibaodan.cn/Article/details/gt2yrvspjkn.html

[G07] 调用父类方法
来源：http://dali.daria6918.cn/Article/details/gt2kucxxruw.html

Py:   super().greet()
来源：http://dali.gotoacloud.top/Article/details/gt2gkdbrlwa.html

PHP:  parent::greet();
来源：http://dali.yuanzhike.top/Article/details/gt2nhddcxld.html

JS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2dlomrnya.html

TS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gt2mlequbdo.html

Java: super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynjktlwx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gt2quurghgr.html

Ruby: super
来源：http://dali.yanxiufei.cn/Article/details/gt2zcarzsht.html

C#:   base.Greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2htrpuqaq.html

[G08] 静态方法与属性
来源：http://dali.guannengcc.top/Article/details/gt2utmrloxi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.havefunace.top/Article/details/gt2hkxmttkq.html

PHP:  public static function f() {}
来源：http://dali.andypj.xyz/Article/details/gt2dfxkczad.html

JS:   static f() {}
来源：http://dali.jianghu66.top/Article/details/gt2okiactxj.html

TS:   static f(): void {}
来源：http://dali.dashuyun.cn/Article/details/gt2rgdtysdf.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gt2eyfptdwm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhixingplan.top/Article/details/gt2aeqziyfj.html

Ruby: def self.f; end
来源：http://dali.yj202588.top/Article/details/gt2kwwookek.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gt2plxzqkce.html

[G09] 接口 / 抽象类
来源：http://dali.zhoulong.xyz/Article/details/gt2mpstqtse.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.vqdsnc.cn/Article/details/gt2oawdrfeg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gt2grwtnbns.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigfzy.top/Article/details/gt2wtzoxkcs.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgfzy.top/Article/details/gt2crmsvneo.html

Java: interface Shape { double area(); }
来源：http://dali.svipenyu.cn/Article/details/gt2angjylxb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.redwolf501.top/Article/details/gt2veopbanj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhixingplan.top/Article/details/gt2nephjlmv.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2idufwouw.html

[G10] 访问控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rlxvyegs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gt2dsfifcca.html

PHP:  public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gt2cokjwuww.html

JS:   #private 字段；其余公开
来源：http://dali.shangyingyoupin.top/Article/details/gt2vttgrgpg.html

TS:   public / protected / private
来源：http://dali.xziqi.cn/Article/details/gt2hufldgjm.html

Java: public / protected / private / 默认包级
来源：http://dali.chenjidiqi.icu/Article/details/gt2xhwgpsxa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gt2brbkdbej.html

Ruby: public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gt2qkdexfht.html

C#:   public / protected / private / internal
来源：http://dali.yuxming.cn/Article/details/gt2ciwgcyou.html

[G11] getter / setter
来源：http://dali.wangshuangyany.cn/Article/details/gt2ogpvagpm.html

Py:   @property 与 @x.setter
来源：http://dali.zhongyouzk.top/Article/details/gt2ynkibhbd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gt2zwuifwzd.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gt2ajbhnysd.html

TS:   get name(): string { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gt2zjtxdtil.html

Java: public String getName() { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2jzlalqsd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gt2jvtewwxu.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gt2ytbycqal.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gt2lhwxiikj.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gt2egvwghke.html

Py:   def __str__(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gt2pjykvkmc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2jhfulxbb.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2kgtvwuuk.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2avxsvacg.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2vzzkxunb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gt2xwyicxyk.html

Ruby: def to_s; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ieugztpu.html

C#:   public override string ToString() => Name;
来源：http://dali.sweek.top/Article/details/gt2coenzhef.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gt2bqxwacly.html

Py:   isinstance(u, User)
来源：http://dali.cdnleiting.top/Article/details/gt2vghiknsr.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2tqoyjyts.html

JS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gt2jhwfawjt.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2pydbmuhs.html

Java: u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2zhdwmfyf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gt2weoemfvl.html

Ruby: u.is_a?(User)
来源：http://dali.guowangkeji.top/Article/details/gt2qlmibcwf.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gt2uekkqxqo.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gt2gwarhhju.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xylfe.cn/Article/details/gt2qvoewgjz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jqgfzy.top/Article/details/gt2bpvcdlto.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shangyingyoupin.top/Article/details/gt2isoglhiq.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gt2lngaswcv.html

Java: record User(String name, int age) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2nrfiyifl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hysaishi.cn/Article/details/gt2oenccxhc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daxiang520.top/Article/details/gt2stqlyzlg.html

C#:   record User(string Name, int Age);
来源：http://dali.cashguo.top/Article/details/gt2shrsrbrm.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ksfderoy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gaohongyu789.top/Article/details/gt2lluoqgyp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shzxlz.cn/Article/details/gt2eypqqnhj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnxiangtu.top/Article/details/gt2godnkzym.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gt2aewheirl.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gt2ltuoyqtd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvmpksqz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.havefunace.top/Article/details/gt2ekbqnahv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gt2fkixbvup.html

[G16] 对象转数组 / 字典
来源：http://dali.gaohongyu789.top/Article/details/gt2hyoshion.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnqzz.top/Article/details/gt2gclpkmqu.html

PHP:  get_object_vars($obj);
来源：http://dali.xylfe.cn/Article/details/gt2mjfgqobu.html

JS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gt2llcnxsmb.html

TS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2toorryrx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yueranfly.top/Article/details/gt2raukdajk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.vqdsnc.cn/Article/details/gt2bzuzxday.html

Ruby: obj.instance_variables
来源：http://dali.kuanghao11.cn/Article/details/gt2ajejocaf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gt2sxwlwzmf.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2ijwtlcaf.html

H. 异常与错误处理
来源：http://dali.daxiang520.top/Article/details/gt2fhucsgbm.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2sfrqpugi.html

[H01] try / catch 基础
来源：http://dali.hnqzz.top/Article/details/gt2uyixywzv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gt2cddstkzv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gogol.net.cn/Article/details/gt2ndijowzx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gt2hlfopslj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gt2ergwhlxd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuanzx.com/Article/details/gt2bagqnsnm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gt2cgjinzre.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sufxvd.cn/Article/details/gt2qljvvxld.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daxiang520.top/Article/details/gt2jtccyvbl.html

[H02] finally / ensure 收尾
来源：http://dali.yueranfly.top/Article/details/gt2aijxpfgh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhoulong.xyz/Article/details/gt2bgprpnjz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gt2dhugrxhb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2jgcvcjdl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2ejgaaefx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2hrrqiknv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gt2lyctckyg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.bjfxy.top/Article/details/gt2wusjizge.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2kqqvgeyn.html

[H03] 主动抛出异常
来源：http://dali.bjfxy.top/Article/details/gt2fbffargn.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gnihsllb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2pggqngad.html

JS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2rvcbbbmr.html

TS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2tscpwxbo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2xfdriccz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gt2aergqjxe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gotoacloud.top/Article/details/gt2hpqenqyb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2kvnujkum.html

[H04] 自定义异常类型
来源：http://dali.gzhubu.top/Article/details/gt2eogogoza.html

Py:   class MyError(Exception): pass
来源：http://dali.tian-w.cn/Article/details/gt2ggwduvyk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gt2xcknfvpg.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gt2lrgbrbkc.html

TS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gt2fjlxiidy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxztsiww.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gt2pcfrluvh.html

Ruby: class MyError < StandardError; end
来源：http://dali.bjfxy.top/Article/details/gt2jvtxhaes.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2dqbqttoe.html

[H05] 捕获特定类型
来源：http://dali.jinqigufen.top/Article/details/gt2mgeysimr.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gt2wvzykuoy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sufxvd.cn/Article/details/gt2slviylam.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gt2hfspiela.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.haohaochexian.top/Article/details/gt2ewovvfdp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yongpay.top/Article/details/gt2mxvsgpcr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxuanxn.top/Article/details/gt2hejpaosr.html

Ruby: rescue ArgumentError => e
来源：http://dali.jianghu66.top/Article/details/gt2novmaxlt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2mnfstxad.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daxiang520.top/Article/details/gt2owynioqw.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gt2gkjkgubu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tanke756.top/Article/details/gt2joekzqfd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2ovfdyenj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gt2jjqyqshy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gt2sjztnegb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuxming.cn/Article/details/gt2vpjspoek.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhengqikj.top/Article/details/gt2uvipxivq.html

C#:   obj?.A?.B ?? default
来源：http://dali.guannengcc.top/Article/details/gt2xjtmkzas.html

[H07] 断言
来源：http://dali.guowangkeji.top/Article/details/gt2mpdcxpuw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.birdmap.top/Article/details/gt2qbokjatk.html

PHP:  assert($x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2cfvwrhap.html

JS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2xriypfzf.html

TS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2ehgituse.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zycfv.cn/Article/details/gt2alimhwdk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.chenlongwang.top/Article/details/gt2hozuhomc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aibaodan.cn/Article/details/gt2ekmfexdk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gt2zadfksmc.html

[H08] 获取错误信息与堆栈
来源：http://dali.cqqwz.cn/Article/details/gt2ncuwvkpn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258.top/Article/details/gt2tivhiwdk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fengsongda.top/Article/details/gt2xwfbsotk.html

JS:   e.message;  e.stack
来源：http://dali.pycfn.com/Article/details/gt2homgzkzp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gt2yetaqbmf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xylfe.cn/Article/details/gt2btzzfbwm.html

Go:   err.Error()
来源：http://dali.yuanzhike.top/Article/details/gt2umtzgfff.html


<!-- 参考信息 -->