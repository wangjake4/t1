代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jianghu66.top/Article/details/gt2dyltahby.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2fzwtujlo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxinkj.top/Article/details/gt2nqnqknaq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xylfe.cn/Article/details/gt2enwctidt.html

[F05] 判断文件或目录是否存在
来源：http://dali.hfpthk.cn/Article/details/gt2ltzaxfml.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guowangkeji.top/Article/details/gt2beazqynu.html

PHP:  file_exists("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2jcgkvkun.html

JS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2sdngspca.html

TS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2iibnbcik.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gt2gbastwut.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.iojbl.cn/Article/details/gt2psxgtoej.html

Ruby: File.exist?("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qyyduxyb.html

C#:   File.Exists("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2hxixdrsd.html

[F06] 删除文件
来源：http://dali.gzhubu.top/Article/details/gt2feptbnjp.html

Py:   os.remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2ujdvcdpa.html

PHP:  unlink("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2rdhvmqlt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2gxauyljh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2odgrivpt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2riiujbyr.html

Go:   os.Remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2oegdeblq.html

Ruby: File.delete("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2ttanxfcs.html

C#:   File.Delete("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2ukafcuke.html

[F07] 创建目录（含多级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dapqttci.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gt2hinlggbv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigfzy.top/Article/details/gt2jlzjyoic.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gt2jkdbnybz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jianghu66.top/Article/details/gt2zuznouna.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gogol.net.cn/Article/details/gt2wwjgtavm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ehwqpu.com/Article/details/gt2kcmhtnlq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tianlin.xyz/Article/details/gt2tgjurmlv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dashuyun.cn/Article/details/gt2nwacsije.html

[F08] 遍历目录
来源：http://dali.wangshuangyany.cn/Article/details/gt2txqzqpsf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnxiangtu.top/Article/details/gt2rtwkpanl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258.top/Article/details/gt2rxfoczbn.html

JS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gt2lxfmrdxv.html

TS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gt2higemduj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gt2onsnnztd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daxiang520.top/Article/details/gt2tbsktsst.html

Ruby: Dir.children("dir")
来源：http://dali.bjfxy.top/Article/details/gt2ggzhinve.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2cqtmkosq.html

[F09] 获取文件大小
来源：http://dali.daria6918.cn/Article/details/gt2katsmcap.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2ugvvutkm.html

PHP:  filesize("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmhdqovh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gt2byxbgekx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gt2rvqtrmbi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gt2lvqjrsuf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cashguo.top/Article/details/gt2womekzrl.html

Ruby: File.size("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2reuoyvtk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gt2vycwgozp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fzhhl.top/Article/details/gt2xctsdipd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2zfseszxg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpptafly.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2dsnphtzs.html

TS:   path.extname("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2rwzxkjec.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2exedgrqw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkwobkgb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2ameknqoi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2phfaaoov.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gt2gthoimux.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2rimzsikl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rvkoxqbw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2ufpxdjac.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2hdtnijip.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gogol.net.cn/Article/details/gt2fjmfxaxm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.smart0.xyz/Article/details/gt2egnsiqau.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2chnxrhjz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ydzc1.top/Article/details/gt2njmcilws.html

[F12] CSV 读写
来源：http://dali.hfpthk.cn/Article/details/gt2uuklfbtu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.bjfxy.top/Article/details/gt2cdkflwvk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fengsongda.top/Article/details/gt2xadefcct.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gotoacloud.top/Article/details/gt2bgjoehcq.html

TS:   // 同上
来源：http://dali.ivvv.top/Article/details/gt2prspxlfk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gt2ycempqfu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aibaodan.cn/Article/details/gt2fyqjvhwy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gt2qtbzvcok.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xylfe.cn/Article/details/gt2lknivuwp.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ncufhxhf.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gt2onwllwga.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2jfgmqast.html

[G01] 定义类
来源：http://dali.yuxming.cn/Article/details/gt2ejyfktjp.html

Py:   class User: pass
来源：http://dali.zdqjudy.top/Article/details/gt2urafrssa.html

PHP:  class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gotbiqfl.html

JS:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2rayselkk.html

TS:   class User { name: string = ""; }
来源：http://dali.gogol.net.cn/Article/details/gt2pwfsqvai.html

Java: class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2vdfmiizr.html

Go:   type User struct { Name string }
来源：http://dali.0kj1m.cn/Article/details/gt2xyedchar.html

Ruby: class User; end
来源：http://dali.yj20258.top/Article/details/gt2qbvhbogi.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gt2brvvnmde.html

[G02] 构造函数
来源：http://dali.gogol.net.cn/Article/details/gt2crysygdu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gt2gltdovbs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tianlin.xyz/Article/details/gt2fjidtkfn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gt2cvckfnty.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2sghpfsbi.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gt2vxgvknzk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dugxnkgw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ydzc1.top/Article/details/gt2flrmkpkn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2nucenvtg.html

[G03] 实例属性
来源：http://dali.jqgfzy.top/Article/details/gt2gnnnehjn.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gt2czkbjlen.html

PHP:  public string $name = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2lbkrpsyz.html

JS:   this.name = "x";
来源：http://dali.yj20258888.top/Article/details/gt2qzdnjibt.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gt2ocktttdk.html

Java: private String name;
来源：http://dali.tanke756.top/Article/details/gt2lzrwzyub.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gt2oridaghf.html

Ruby: @name = "x"
来源：http://dali.cqqwz.cn/Article/details/gt2eqrxlzuh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pycfn.com/Article/details/gt2kaqyllbq.html

[G04] 定义方法
来源：http://dali.zhixingplan.top/Article/details/gt2ldyvkwgi.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258.top/Article/details/gt2jxserpxt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2quqdsdif.html

JS:   greet() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2eewbdnet.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2zhkukwwm.html

Java: String greet() { return name; }
来源：http://dali.cashguo.top/Article/details/gt2tcufdoze.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gt2rbjjkuhu.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gt2nccxpvhr.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gt2gvdvytmh.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gt2ozuzorwm.html

Py:   class Admin(User): pass
来源：http://dali.kuanghao11.cn/Article/details/gt2jqqcduso.html

PHP:  class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2zjqictxl.html

JS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2vxdfcozq.html

TS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2kbpoxxjy.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2vuwswuft.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gt2bzpitevu.html

Ruby: class Admin < User; end
来源：http://dali.xylfe.cn/Article/details/gt2fjczjsqv.html

C#:   class Admin : User {}
来源：http://dali.cqqwz.cn/Article/details/gt2awhgvzvz.html

[G06] 重写方法
来源：http://dali.hnxiangtu.top/Article/details/gt2qddqorrw.html

Py:   def greet(self): return "admin"
来源：http://dali.hfpthk.cn/Article/details/gt2lelmwxrf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2xnqcfcdo.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gt2wipjvmci.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2euwnoelp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2plsbrrlj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cucudq.cn/Article/details/gt2zqiojafj.html

Ruby: def greet; "admin"; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zcmquisj.html

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gt2auxyqzid.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gt2kfpnsreq.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gt2nglzhbag.html

PHP:  parent::greet();
来源：http://dali.fengsongda.top/Article/details/gt2duzdbbsc.html

JS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2dtpzgaqh.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gt2dfmhogon.html

Java: super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2qflutdrg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shuidangran.top/Article/details/gt2gugdudkj.html

Ruby: super
来源：http://dali.hongshengwenyu.top/Article/details/gt2ljzwcgqw.html

C#:   base.Greet();
来源：http://dali.wangdashe.top/Article/details/gt2wkswkgyi.html

[G08] 静态方法与属性
来源：http://dali.hywenlv.cn/Article/details/gt2trvlbkpw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gt2uuqdiyvu.html

PHP:  public static function f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2bwdcofff.html

JS:   static f() {}
来源：http://dali.bjfxy.top/Article/details/gt2ehtpbrhm.html

TS:   static f(): void {}
来源：http://dali.sufxvd.cn/Article/details/gt2nkpfgfbq.html

Java: static void f() {}
来源：http://dali.bjfxy.top/Article/details/gt2khiaskus.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdlyhzsp.html

Ruby: def self.f; end
来源：http://dali.dianchejie.cn/Article/details/gt2buhhzbml.html

C#:   public static void F() {}
来源：http://dali.guowangkeji.top/Article/details/gt2iqdrcpap.html

[G09] 接口 / 抽象类
来源：http://dali.gaohongyu789.top/Article/details/gt2nbfhppug.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gt2iabkojkh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.haohaochexian.top/Article/details/gt2mpxbfqax.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gt2hfuhoonz.html

TS:   interface Shape { area(): number; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fajfbjcf.html

Java: interface Shape { double area(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2ueqpurtx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gt2dkpbhcga.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.kuanghao11.cn/Article/details/gt2dpyupwrq.html

C#:   interface IShape { double Area(); }
来源：http://dali.sxryk.cn/Article/details/gt2trbbqeka.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gt2srjwbdzo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2crpxhpiw.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2steyffni.html

JS:   #private 字段；其余公开
来源：http://dali.nwbrower.top/Article/details/gt2bqdkpkjh.html

TS:   public / protected / private
来源：http://dali.tanke756.top/Article/details/gt2gjvteczh.html

Java: public / protected / private / 默认包级
来源：http://dali.yuxming.cn/Article/details/gt2lddwpcim.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.feifeiyinyue.top/Article/details/gt2zvycdfxi.html

Ruby: public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2hzjnoaiu.html

C#:   public / protected / private / internal
来源：http://dali.ehwqpu.com/Article/details/gt2pjjyzwzf.html

[G11] getter / setter
来源：http://dali.jiagoushi.top/Article/details/gt2unjdobme.html

Py:   @property 与 @x.setter
来源：http://dali.zhixingplan.top/Article/details/gt2wotlujkh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gt2jgcheglx.html

JS:   get name() { return this._name; }
来源：http://dali.sweek.top/Article/details/gt2xcaodblh.html

TS:   get name(): string { return this._name; }
来源：http://dali.tanke756.top/Article/details/gt2jijvejiy.html

Java: public String getName() { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2hfqxrwdw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gt2kavvgjal.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gt2kevnlrim.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ruayegqt.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gt2vyjiwygx.html

Py:   def __str__(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gt2ziykavun.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yueranfly.top/Article/details/gt2twmizuxs.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2kkuoyann.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2juvwqglw.html

Java: @Override public String toString() { return name; }
来源：http://dali.sweek.top/Article/details/gt2jlhqrqtk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gt2tgcvnczr.html

Ruby: def to_s; @name; end
来源：http://dali.haohaochexian.top/Article/details/gt2qnzghvlj.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gt2afsafvuc.html

[G13] 判断对象类型
来源：http://dali.haohaochexian.top/Article/details/gt2ojtmprbz.html

Py:   isinstance(u, User)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xyyhvzjd.html

PHP:  $u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2zbfswlms.html

JS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2gdpueltq.html

TS:   u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2zwctmkxc.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2tnnxubta.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gt2xksdplvi.html

Ruby: u.is_a?(User)
来源：http://dali.cqqwz.cn/Article/details/gt2tlkrzgmt.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gt2wxylfmqf.html

[G14] 数据类 / record
来源：http://dali.ppjwa.cn/Article/details/gt2ososvicu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rfapdutg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvinodqm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.quarkkingdee.top/Article/details/gt2amxeacgj.html

TS:   type User = { name: string; age: number };
来源：http://dali.cqqwz.cn/Article/details/gt2xktumoec.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gt2jtorwfgm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tanke756.top/Article/details/gt2qzoxkurf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jlsjyb.cn/Article/details/gt2cugeureq.html

C#:   record User(string Name, int Age);
来源：http://dali.guowangkeji.top/Article/details/gt2kkifjdud.html

[G15] 枚举
来源：http://dali.svipenyu.cn/Article/details/gt2uhtqdrcg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gt2yiloajve.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pycfn.com/Article/details/gt2zvvacmom.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hfpthk.cn/Article/details/gt2wsqidmgm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gt2fpofletp.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gt2rvhmrihu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.mhx1999.top/Article/details/gt2vaaokbar.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigufen.top/Article/details/gt2jrzefumj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2bzxazpig.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2mqquzezt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gt2srgbtnna.html

PHP:  get_object_vars($obj);
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdbfcloq.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2rscamhoh.html

TS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2pprlvqfd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gt2ehjtlynd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.316326.xyz/Article/details/gt2gylutzaz.html

Ruby: obj.instance_variables
来源：http://dali.iojbl.cn/Article/details/gt2hhevsgpx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gt2hmqdpvbr.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2dkommnjz.html

H. 异常与错误处理
来源：http://dali.hywenlv.cn/Article/details/gt2ykmtjcwq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ulnhdaix.html

[H01] try / catch 基础
来源：http://dali.daxiang520.top/Article/details/gt2tvmsyalo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cqqwz.cn/Article/details/gt2vodfhgaq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pycfn.com/Article/details/gt2dizcmepf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gt2hksltchn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gt2qncgsdeh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sxryk.cn/Article/details/gt2vdcvxahp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2pkglszvo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gjbwapju.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gt2tbuutzzp.html

[H02] finally / ensure 收尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awvjuazp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxinkj.top/Article/details/gt2kmiqebox.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2loqlpvjm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gt2tmjmpgig.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2tywzrjwh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2mgkbiiff.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sweek.top/Article/details/gt2sicykgan.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jlsjyb.cn/Article/details/gt2hqjzdwsn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2vepzlksh.html

[H03] 主动抛出异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ivmodnes.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gt2nueomlrs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2dtdlzrjj.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2vwcvcxxe.html

TS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2dqiislbo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2vespakdb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daxiang520.top/Article/details/gt2ulaqifyh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gt2qpijskag.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2rcyffrew.html

[H04] 自定义异常类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2ncnozyrd.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gt2xlinyein.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wrbbvrew.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gt2zcbnihco.html

TS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gt2aziurfmz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gt2yryedijy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhixingplan.top/Article/details/gt2uqebcgkm.html

Ruby: class MyError < StandardError; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2pyobdtov.html

C#:   class MyException : Exception {}
来源：http://dali.sufxvd.cn/Article/details/gt2emchitun.html

[H05] 捕获特定类型
来源：http://dali.ydzc1.top/Article/details/gt2yrfyqkrs.html

Py:   except ValueError as e:
来源：http://dali.guowangkeji.top/Article/details/gt2hmivvgfs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.bjfxy.top/Article/details/gt2wedurkqx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hfpthk.cn/Article/details/gt2xsmmagff.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gt2ssnpylfi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2betbdjuk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zycfv.cn/Article/details/gt2kdheealh.html

Ruby: rescue ArgumentError => e
来源：http://dali.sysykeji.top/Article/details/gt2tfrfjwlv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2npnpnejp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ivvv.top/Article/details/gt2gvgcxkgz.html

Py:   value = d.get("k") or default
来源：http://dali.gogol.net.cn/Article/details/gt2mwvzqsvf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gt2kasyggzi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gt2fmlllmvs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gt2poeuyxqa.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vjphrhmq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhoulong.xyz/Article/details/gt2nvnyhwuk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gt2cyhctrqf.html

C#:   obj?.A?.B ?? default
来源：http://dali.daxiang520.top/Article/details/gt2txdqvoim.html

[H07] 断言
来源：http://dali.sxryk.cn/Article/details/gt2nozklsay.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ppjwa.cn/Article/details/gt2ofayfjfb.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2iqusoirx.html

JS:   console.assert(x > 0);
来源：http://dali.cqqwz.cn/Article/details/gt2twkbmuit.html

TS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2sziokpbd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fengsongda.top/Article/details/gt2plwphlwv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhoulong.xyz/Article/details/gt2dvnvtsoj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gt2iyqwmlzv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dwrnbvhm.html

[H08] 获取错误信息与堆栈
来源：http://dali.feifeiyinyue.top/Article/details/gt2tndmppjf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fzhhl.top/Article/details/gt2oaxtnegg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tanke756.top/Article/details/gt2kjuzwfus.html

JS:   e.message;  e.stack
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vnywpicm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuxming.cn/Article/details/gt2tekuycjs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zycfv.cn/Article/details/gt2mkwtkrtk.html

Go:   err.Error()
来源：http://dali.cdnleiting.top/Article/details/gt2olsilkjr.html

Ruby: e.message;  e.backtrace
来源：http://dali.sxryk.cn/Article/details/gt2gxirjhgk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shangyingyoupin.top/Article/details/gt2fpjrjakz.html

[H09] 带错误码的异常
来源：http://dali.jlsjyb.cn/Article/details/gt2kzepijlc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gt2gxxvcxqe.html


<!-- 参考信息 -->