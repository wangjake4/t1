代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.redwolf501.top/Article/details/gt2pvgywmwp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258888.top/Article/details/gt2sezflugj.html

PHP:  file_exists("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2cushgfql.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2imvcyacl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2fsllufzx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2indhirep.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gotoacloud.top/Article/details/gt2qvoeufgz.html

Ruby: File.exist?("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2ixalebwb.html

C#:   File.Exists("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2fqyntbpu.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gt2szofucej.html

Py:   os.remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2bztdrcic.html

PHP:  unlink("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2vtvhnzjz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2pnztxggd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2yzwjmhdi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2wpdpzryw.html

Go:   os.Remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2otpwqhae.html

Ruby: File.delete("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2nampouzb.html

C#:   File.Delete("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2cwbikupx.html

[F07] 创建目录（含多级）
来源：http://dali.tian-w.cn/Article/details/gt2wphldrpu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gt2rglrowtt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gt2ggqiurcb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gt2mzjxrvpi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gt2innxrbzk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sxryk.cn/Article/details/gt2mhcwhfdw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258.top/Article/details/gt2dnxdppph.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gzhubu.top/Article/details/gt2wrmpnboq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigufen.top/Article/details/gt2xlbxditk.html

[F08] 遍历目录
来源：http://dali.fzhhl.top/Article/details/gt2xegwxjbp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zycfv.cn/Article/details/gt2ralyqzao.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daxiang520.top/Article/details/gt2nktzwgsf.html

JS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gt2qnmjyrkl.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gt2sfycyjrn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gt2xcttmagd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hjzistpk.html

Ruby: Dir.children("dir")
来源：http://dali.xziqi.cn/Article/details/gt2xxnsixzm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.havefunace.top/Article/details/gt2wuxgctsv.html

[F09] 获取文件大小
来源：http://dali.tianlin.xyz/Article/details/gt2abpmleik.html

Py:   os.path.getsize("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2uhgpuzgc.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2xirhhyvr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gt2dkuzygpy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gt2xmecvlgy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gt2ojxmkcao.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gt2bapfpthz.html

Ruby: File.size("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bgbqowlz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gt2wqjnopnq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jianghu66.top/Article/details/gt2ssbrfldy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2zrpqyyoi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2zckabwtw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2mctvewns.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2xifbbmqk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gt2vtvbjjus.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2kfqwmcqv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2gvikrrdh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2aofrgion.html

[F11] 复制与移动文件
来源：http://dali.zycfv.cn/Article/details/gt2ltcaesal.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsfqlwx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ydzc1.top/Article/details/gt2lmkconmq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gt2qhjiaxut.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2tslykycr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lzmpbvwu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gzhubu.top/Article/details/gt2okljmwhh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2deumjiiy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sweek.top/Article/details/gt2lwingagj.html

[F12] CSV 读写
来源：http://dali.ppjwa.cn/Article/details/gt2tsnhgdtr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yrjhkcvo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenlongwang.top/Article/details/gt2gqfukmaz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fzhhl.top/Article/details/gt2bjprcxps.html

TS:   // 同上
来源：http://dali.hnqzz.top/Article/details/gt2rhaujmfn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gt2qakisxpm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhiwuduotai.top/Article/details/gt2ndewftvj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tianlin.xyz/Article/details/gt2cwtqffda.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gt2haerpnjm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2lcxplipp.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gt2qvxakrtu.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2mvxhvauk.html

[G01] 定义类
来源：http://dali.fzhhl.top/Article/details/gt2stbqtkjc.html

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gt2biarpple.html

PHP:  class User {}
来源：http://dali.hnqzz.top/Article/details/gt2etydsojq.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2dvachxrn.html

TS:   class User { name: string = ""; }
来源：http://dali.cashguo.top/Article/details/gt2weenmylc.html

Java: class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2bwanxwxq.html

Go:   type User struct { Name string }
来源：http://dali.iojbl.cn/Article/details/gt2lerturvv.html

Ruby: class User; end
来源：http://dali.cqqwz.cn/Article/details/gt2jxbftqgl.html

C#:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ybvwgfut.html

[G02] 构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fgzhzhse.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sysykeji.top/Article/details/gt2hjhwdmot.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cucudq.cn/Article/details/gt2dqtfvxbd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gt2fiswdbpe.html

TS:   constructor(public name: string) {}
来源：http://dali.yonumen.top/Article/details/gt2hsvkdxox.html

Java: User(String name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gt2kjjjizec.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cheryme.top/Article/details/gt2ljszcyod.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shuidangran.top/Article/details/gt2bbxrtzah.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pzywnmvb.html

[G03] 实例属性
来源：http://dali.guowangkeji.top/Article/details/gt2ypxvtihu.html

Py:   self.name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gt2liqyawym.html

PHP:  public string $name = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2nytmdnzc.html

JS:   this.name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gt2crzyxhdj.html

TS:   name: string = "x";
来源：http://dali.haohaochexian.top/Article/details/gt2kajdugrj.html

Java: private String name;
来源：http://dali.fengsongda.top/Article/details/gt2ylkqlcws.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gt2citrvror.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gt2hmqgrfeb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2hhnslimr.html

[G04] 定义方法
来源：http://dali.zhixingplan.top/Article/details/gt2iqvduoaj.html

Py:   def greet(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gt2azmsbrpy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gt2vxaxmsqm.html

JS:   greet() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rvxoapxs.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2zsteadca.html

Java: String greet() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2vtseqwuu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gt2cidcqctz.html

Ruby: def greet; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfdlrzjt.html

C#:   public string Greet() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gt2jzhbkfgm.html

[G05] 继承
来源：http://dali.hnqzz.top/Article/details/gt2famxbzia.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gt2fbupsxhv.html

PHP:  class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2lnjuyage.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2jmssmegb.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2yycnaguw.html

Java: class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gt2inqbltyq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.vqdsnc.cn/Article/details/gt2kptjpwqj.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gt2efpkcren.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gt2hkyjzgth.html

[G06] 重写方法
来源：http://dali.yueranfly.top/Article/details/gt2fnpvnnpa.html

Py:   def greet(self): return "admin"
来源：http://dali.daxiang520.top/Article/details/gt2rzuylerm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gt2ypeusibi.html

JS:   greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qvhronsx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gt2otxcdmwq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2wpvcvxho.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gzhubu.top/Article/details/gt2srcnjbcy.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gt2flmatnlz.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangdashe.top/Article/details/gt2unvauszw.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gt2czsvhwkt.html

Py:   super().greet()
来源：http://dali.haohaochexian.top/Article/details/gt2nxhbgttk.html

PHP:  parent::greet();
来源：http://dali.cucudq.cn/Article/details/gt2ijxcbxxc.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2hrsuxqaj.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2khmnslrx.html

Java: super.greet();
来源：http://dali.ydzc1.top/Article/details/gt2jxdsdbfx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gt2gvydexof.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gt2jxisyoec.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gt2ibttrhkj.html

[G08] 静态方法与属性
来源：http://dali.yueranfly.top/Article/details/gt2ajfdoazg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yanxiufei.cn/Article/details/gt2ekymfmap.html

PHP:  public static function f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2neddklbw.html

JS:   static f() {}
来源：http://dali.mhx1999.top/Article/details/gt2pewwodqz.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gt2tenjmzqn.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2hoekfjfx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhengqikj.top/Article/details/gt2mhoferuv.html

Ruby: def self.f; end
来源：http://dali.jinqigfzy.top/Article/details/gt2gmlmvtka.html

C#:   public static void F() {}
来源：http://dali.cucudq.cn/Article/details/gt2yxmzyjky.html

[G09] 接口 / 抽象类
来源：http://dali.bjfxy.top/Article/details/gt2ftekgfby.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gt2zydwoiqr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ccystkqt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuanzhike.top/Article/details/gt2yaakycao.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gt2dxizlhfn.html

Java: interface Shape { double area(); }
来源：http://dali.iojbl.cn/Article/details/gt2zizbkbzz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shzxlz.cn/Article/details/gt2djantkxl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hfpthk.cn/Article/details/gt2nqsxcomg.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gt2kbwkjbsj.html

[G10] 访问控制
来源：http://dali.gogol.net.cn/Article/details/gt2mcfndclx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pengpengdd.cyou/Article/details/gt2omaldwhi.html

PHP:  public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gt2lwfqjjmz.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gt2nougcqbc.html

TS:   public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gt2mltgvzjz.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gt2ofmsizby.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhixingplan.top/Article/details/gt2tcdieuxv.html

Ruby: public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2xbipgbif.html

C#:   public / protected / private / internal
来源：http://dali.andypj.xyz/Article/details/gt2fbvxfsov.html

[G11] getter / setter
来源：http://dali.hywenlv.cn/Article/details/gt2zpjlkuqh.html

Py:   @property 与 @x.setter
来源：http://dali.vqdsnc.cn/Article/details/gt2hsdwaoaf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gt2wrkybugv.html

JS:   get name() { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gt2adlrqzky.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2pjcdllib.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2fvmlnifl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2rjauysuk.html

Ruby: attr_accessor :name
来源：http://dali.aizwys.cn/Article/details/gt2lkcgjigg.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rnfxldyj.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gt2qualjsyx.html

Py:   def __str__(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gt2dqhvzdae.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gt2tzucnxot.html

JS:   toString() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kvyncslc.html

TS:   toString(): string { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2bdrobvsi.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2ktzusxaf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2zdnhsptf.html

Ruby: def to_s; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2twvulltd.html

C#:   public override string ToString() => Name;
来源：http://dali.shzxlz.cn/Article/details/gt2nrjopxwy.html

[G13] 判断对象类型
来源：http://dali.xinyue.icu/Article/details/gt2aovbkxcg.html

Py:   isinstance(u, User)
来源：http://dali.yj20258.top/Article/details/gt2vckwkkte.html

PHP:  $u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2girhtzsp.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gt2rgyqfssw.html

TS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2iobkoowc.html

Java: u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gt2jgdcsxyc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gt2iaiiiear.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigfzy.top/Article/details/gt2tubmchet.html

C#:   u is User
来源：http://dali.yuxming.cn/Article/details/gt2paosnddh.html

[G14] 数据类 / record
来源：http://dali.cheryme.top/Article/details/gt2scazmapo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gt2ctnlnmub.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.svipenyu.cn/Article/details/gt2uvqnevqz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pengpengdd.cyou/Article/details/gt2ykydxwtg.html

TS:   type User = { name: string; age: number };
来源：http://dali.c1oappe.top/Article/details/gt2ckgcckqh.html

Java: record User(String name, int age) {}
来源：http://dali.9152youxi.cn/Article/details/gt2xcpibvbj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vxpvoyus.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnxiangtu.top/Article/details/gt2sdrruuvo.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gt2gcllefhn.html

[G15] 枚举
来源：http://dali.yj202588.top/Article/details/gt2megpxxkk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ydzc1.top/Article/details/gt2amcxfihk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hysaishi.cn/Article/details/gt2lmfkigez.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhiwuduotai.top/Article/details/gt2aaerweyx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2sdzmkkrg.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qijxduhr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dashuyun.cn/Article/details/gt2vnilpkqc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigfzy.top/Article/details/gt2blutmuzp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gt2thotujus.html

[G16] 对象转数组 / 字典
来源：http://dali.xuanzx.com/Article/details/gt2uqlqkktn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tianlin.xyz/Article/details/gt2xdgnwmam.html

PHP:  get_object_vars($obj);
来源：http://dali.c1oappe.top/Article/details/gt2nzsqqmfq.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2dxaabalx.html

TS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gt2nvsfjytk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ydzc1.top/Article/details/gt2cbeiovuc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guowangkeji.top/Article/details/gt2jpzruahb.html

Ruby: obj.instance_variables
来源：http://dali.mhx1999.top/Article/details/gt2oxjwakwy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yongpay.top/Article/details/gt2hgdcgbac.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2ragmfjfc.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gt2epzewway.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2ykjaalqf.html

[H01] try / catch 基础
来源：http://dali.tanke756.top/Article/details/gt2zguicwxa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.havefunace.top/Article/details/gt2ulclhpck.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhengqikj.top/Article/details/gt2ssvbhhbg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gt2moekeneq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gt2todelkzb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pbaphwve.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yonumen.top/Article/details/gt2mqxajhmj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ivvv.top/Article/details/gt2qbumharv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kctwlcsn.html

[H02] finally / ensure 收尾
来源：http://dali.jyoumei.cn/Article/details/gt2uuouqtzc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aibaodan.cn/Article/details/gt2rokkwgrl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2kcfwqmjb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2wodpjcun.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2wluvgmdi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gt2xjgpafos.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gt2qfqpgdtx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nwbrower.top/Article/details/gt2hcgyrdcf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ckyuymup.html

[H03] 主动抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gt2vwjymhbf.html

Py:   raise ValueError("错误信息")
来源：http://dali.xziqi.cn/Article/details/gt2ecornmzm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2kxbnhxjf.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2immaipbs.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2suwdbjwr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2umgcqdjh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangdashe.top/Article/details/gt2hbghqicy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gt2cehwxrke.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2cdhrdsip.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gt2qenidzbt.html

Py:   class MyError(Exception): pass
来源：http://dali.fzhhl.top/Article/details/gt2ppbmqoji.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gt2mncyfsff.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gt2upyfmjyr.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gt2gwesjxyn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gt2vthfnnlv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guannengcc.top/Article/details/gt2jvyqfsne.html

Ruby: class MyError < StandardError; end
来源：http://dali.zycfv.cn/Article/details/gt2cnqrejgt.html

C#:   class MyException : Exception {}
来源：http://dali.hywenlv.cn/Article/details/gt2agblncxd.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gt2arjrblve.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nhyyppum.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hfpthk.cn/Article/details/gt2szluciop.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2uetsedsw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gt2lvfxmrrj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xuwqwvcj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cucudq.cn/Article/details/gt2looswjqq.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rgldchlr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2xesdfxfc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2zylztujo.html

Py:   value = d.get("k") or default
来源：http://dali.birdmap.top/Article/details/gt2dozmocfy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gt2qzsenhwq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2utdethqf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gt2rfphtxki.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj202588.top/Article/details/gt2utgzwqqd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wgyjbikt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cucudq.cn/Article/details/gt2tmjlyceh.html

C#:   obj?.A?.B ?? default
来源：http://dali.redwolf501.top/Article/details/gt2itrjfknx.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2izrixudm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sysykeji.top/Article/details/gt2hcbrnvfr.html

PHP:  assert($x > 0);
来源：http://dali.yuxming.cn/Article/details/gt2adrtolgc.html

JS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gt2lcpxrzwp.html

TS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gt2nxlzfepz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenzaomai.com/Article/details/gt2gsmruvbq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2splnjfxz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenzaomai.com/Article/details/gt2bxxqqahj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gt2rerblnjw.html

[H08] 获取错误信息与堆栈
来源：http://dali.aibaodan.cn/Article/details/gt2rbtvfcra.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jlsjyb.cn/Article/details/gt2bvxklxbj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.mhx1999.top/Article/details/gt2pnovkjki.html

JS:   e.message;  e.stack
来源：http://dali.ydzc1.top/Article/details/gt2pwhmivdm.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenlongwang.top/Article/details/gt2iwnpnpej.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tianlin.xyz/Article/details/gt2kppvbmgz.html

Go:   err.Error()
来源：http://dali.xuetiantiany.cn/Article/details/gt2klyttijl.html

Ruby: e.message;  e.backtrace
来源：http://dali.ivvv.top/Article/details/gt2twfqqvgo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gt2jkvepxdq.html

[H09] 带错误码的异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tagjhemw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yueranfly.top/Article/details/gt2tubmekvr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hfpthk.cn/Article/details/gt2tusoxapc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nanxuanxn.top/Article/details/gt2awkqsqkv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daxiang520.top/Article/details/gt2vpatkwvv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxuanxn.top/Article/details/gt2rqrngjmj.html


<!-- 参考信息 -->