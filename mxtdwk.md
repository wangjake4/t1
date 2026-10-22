代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shzxlz.cn/Article/details/gtoantjnio.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gtljjnlnmc.html

[F03] 写入文件（覆盖）
来源：http://dali.yonumen.top/Article/details/gthodjtzrb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jianghu66.top/Article/details/gtdjkkdaef.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtkthdylqe.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gtipnuipav.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gtncuonbdn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shzxlz.cn/Article/details/gtmxmewhkj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.bjfxy.top/Article/details/gtmijakxmy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tanke756.top/Article/details/gtqemhhtqd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbpuepyr.html

[F04] 追加写入文件
来源：http://dali.hongshengwenyu.top/Article/details/gtlwlcixax.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cashguo.top/Article/details/gtysztzyxv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gtfpxhqtos.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtjxylqltn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtoagpozkz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxuanxn.top/Article/details/gtoqhafllk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtmuysmzzt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.andypj.xyz/Article/details/gtdiunkhts.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gzhubu.top/Article/details/gtqsqctdqa.html

[F05] 判断文件或目录是否存在
来源：http://dali.fengsongda.top/Article/details/gtbzdxhmgv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.meibo888.top/Article/details/gtmceatdid.html

PHP:  file_exists("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtaznqvjzf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtdacceqpa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtyubrbowf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtgqlliosw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zycfv.cn/Article/details/gtpsykqeta.html

Ruby: File.exist?("a.txt")
来源：http://dali.daria6918.cn/Article/details/gthvrejcfx.html

C#:   File.Exists("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtuqprecnj.html

[F06] 删除文件
来源：http://dali.haohaochexian.top/Article/details/gtcccijttr.html

Py:   os.remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtcgwtsbxi.html

PHP:  unlink("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtahhjwnbm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gteydajfnd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtyehkjvgl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtbmoadfec.html

Go:   os.Remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gttvbrwdsk.html

Ruby: File.delete("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqxejtyw.html

C#:   File.Delete("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtxzpoiiqc.html

[F07] 创建目录（含多级）
来源：http://dali.quarkkingdee.top/Article/details/gttthnywac.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gttjeajole.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gternmwmfs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtgyykpdbe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gtygztmeyi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258888.top/Article/details/gtnnnwmmwe.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gtsfrbkhsp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gttyflfmui.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gttvqzfzga.html

[F08] 遍历目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfddtmjse.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tian-w.cn/Article/details/gtrursztye.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangdashe.top/Article/details/gtnjblphat.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjawtriki.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtrkbmkhez.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtjhdwsqwr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenlongwang.top/Article/details/gtrfnctvcw.html

Ruby: Dir.children("dir")
来源：http://dali.smart0.xyz/Article/details/gthktwglls.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yueranfly.top/Article/details/gtvifcrskw.html

[F09] 获取文件大小
来源：http://dali.hnqzz.top/Article/details/gtxaxeonkk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtacmqrgrj.html

PHP:  filesize("a.txt");
来源：http://dali.pycfn.com/Article/details/gtyvvaqfze.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtdlsqjree.html

TS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gtiitaizue.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtaptfgead.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gththvtkrp.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlszqmzdi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hywenlv.cn/Article/details/gtvccbdlpr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.mhx1999.top/Article/details/gtafdievkv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtpzmladqf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xylfe.cn/Article/details/gtwpczwvmy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtuvwzvhpo.html

TS:   path.extname("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtyxhgjlef.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gogol.net.cn/Article/details/gtzlvdwvdv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtqonijbsy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtjmlijcgm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtefvtbssh.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gtskojhfvw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtgzygyrem.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtwedredbn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtgerfxiys.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtcifhzxou.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtbamahrbp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuanzx.com/Article/details/gtonoqjcdx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtseeitnyn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenzaomai.com/Article/details/gtfgrjvqrs.html

[F12] CSV 读写
来源：http://dali.shzxlz.cn/Article/details/gtzahkielv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shuidangran.top/Article/details/gtabaylfmz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqewjixx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuanzhike.top/Article/details/gtdpblmvek.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gtmtlscfor.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pycfn.com/Article/details/gtibhmxqcu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ybcxt.top/Article/details/gtxciqfwya.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gttylmcrgx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zycfv.cn/Article/details/gtdwlkdffd.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtrdckgcsw.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gtuneuzjnv.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttwjaggol.html

[G01] 定义类
来源：http://dali.xuetiantiany.cn/Article/details/gttkcwnlul.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gtavhxpxqf.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gticqewxlp.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtmvopqdha.html

TS:   class User { name: string = ""; }
来源：http://dali.fengsongda.top/Article/details/gtzwxykhxz.html

Java: class User {}
来源：http://dali.jianghu66.top/Article/details/gthblsmpgx.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gtwoqpgbiu.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gtcbbdaxty.html

C#:   class User {}
来源：http://dali.yonumen.top/Article/details/gtduygotbl.html

[G02] 构造函数
来源：http://dali.shuidangran.top/Article/details/gtsthsnqpz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zycfv.cn/Article/details/gtxcuamenv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gogol.net.cn/Article/details/gtzszzkttg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtjtigjhrn.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gtvmltzjtg.html

Java: User(String name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtfcqsdmrd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gogol.net.cn/Article/details/gteokpdqph.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnxiangtu.top/Article/details/gtenuoclfu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjjbtbndh.html

[G03] 实例属性
来源：http://dali.316326.xyz/Article/details/gtpsamwygb.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyuilujw.html

PHP:  public string $name = "x";
来源：http://dali.hywenlv.cn/Article/details/gteelhsiqo.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtnzjlzmtk.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gtuxyvfxow.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gtbxzsvdis.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hfpthk.cn/Article/details/gtgngntnrt.html

Ruby: @name = "x"
来源：http://dali.ivvv.top/Article/details/gtwmthujge.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sweek.top/Article/details/gtzjdlsmmo.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gtxqnwxihq.html

Py:   def greet(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gtevratjei.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtkpavcwab.html

JS:   greet() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtqcxpbere.html

TS:   greet(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtwwrvacqj.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtbymzzdgp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmikuzjaa.html

Ruby: def greet; @name; end
来源：http://dali.ybcxt.top/Article/details/gthjnoownu.html

C#:   public string Greet() => Name;
来源：http://dali.dashuyun.cn/Article/details/gtnfpuxtnc.html

[G05] 继承
来源：http://dali.shzxlz.cn/Article/details/gtoxkyqhyd.html

Py:   class Admin(User): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtnqsptwsz.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtbyvdoktv.html

JS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtummrhoic.html

TS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtrxcuixhx.html

Java: class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtzegxuhql.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.meibo888.top/Article/details/gtyrctopnn.html

Ruby: class Admin < User; end
来源：http://dali.yuanzhike.top/Article/details/gtbhmxgvnh.html

C#:   class Admin : User {}
来源：http://dali.chenzaomai.com/Article/details/gtzmiveydb.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gtoiqtjfyf.html

Py:   def greet(self): return "admin"
来源：http://dali.zhengqikj.top/Article/details/gtlrjnqzdq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmmfruumr.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtcginfibw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtzfiymvzq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtxigaihtk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sweek.top/Article/details/gtkwkgageb.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gtibjixipt.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpngnjrvj.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrntymcvn.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gthpzquwme.html

PHP:  parent::greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpwcrpwr.html

JS:   super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtvvyuuocl.html

TS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gtsvueorio.html

Java: super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtwqmrqrrm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gtmsmmkcxc.html

Ruby: super
来源：http://dali.yj20258888.top/Article/details/gtecrtgegm.html

C#:   base.Greet();
来源：http://dali.yueranfly.top/Article/details/gtzjvejdbj.html

[G08] 静态方法与属性
来源：http://dali.birdmap.top/Article/details/gtnsbjlxtv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbubazhod.html

PHP:  public static function f() {}
来源：http://dali.nwbrower.top/Article/details/gtscvjlgtj.html

JS:   static f() {}
来源：http://dali.haohaochexian.top/Article/details/gtnijwnjzy.html

TS:   static f(): void {}
来源：http://dali.bjfxy.top/Article/details/gtmawlspzt.html

Java: static void f() {}
来源：http://dali.ehwqpu.com/Article/details/gtnvqmbnuc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cashguo.top/Article/details/gtlfohrepm.html

Ruby: def self.f; end
来源：http://dali.snrcjt.cn/Article/details/gtwxobsglv.html

C#:   public static void F() {}
来源：http://dali.c1oappe.top/Article/details/gtwbtvavaz.html

[G09] 接口 / 抽象类
来源：http://dali.c1oappe.top/Article/details/gtoqtjqzhd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gtxheotlyp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ehwqpu.com/Article/details/gtqszvbcfl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhengqikj.top/Article/details/gtcclwjkmg.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gtgitkdren.html

Java: interface Shape { double area(); }
来源：http://dali.yangfankeji.com/Article/details/gtozllyzlg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jyoumei.cn/Article/details/gtdesnspfx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxuanxn.top/Article/details/gtfbwhpvvw.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenlongwang.top/Article/details/gtdknpgtyx.html

[G10] 访问控制
来源：http://dali.gzhubu.top/Article/details/gtnowlhplr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gtehybocjq.html

PHP:  public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtsnvhqudv.html

JS:   #private 字段；其余公开
来源：http://dali.sxryk.cn/Article/details/gttzdzolea.html

TS:   public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtsjqjfwln.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gteoallmku.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenlongwang.top/Article/details/gtzbkwrvid.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtpbegeamm.html

C#:   public / protected / private / internal
来源：http://dali.yangfankeji.com/Article/details/gtrhfgccib.html

[G11] getter / setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkbpeeob.html

Py:   @property 与 @x.setter
来源：http://dali.haohaochexian.top/Article/details/gtfebucwtc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtoyapnpvr.html

JS:   get name() { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtuwllczab.html

TS:   get name(): string { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtlhfrmdcn.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gtzyghcuoa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtirpjpxkj.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gtzgerxyyy.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gtywvklomv.html

[G12] 对象转字符串
来源：http://dali.tanke756.top/Article/details/gtribuyukk.html

Py:   def __str__(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gtcxosuwbp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtlkaugdmx.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzodqfres.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtvxpqtmee.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtllhhkqmd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtafrdyggg.html

Ruby: def to_s; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtgalpqdjz.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtytkhvqep.html

[G13] 判断对象类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxptzczlf.html

Py:   isinstance(u, User)
来源：http://dali.jinqigufen.top/Article/details/gtqfwsqzjg.html

PHP:  $u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtoiuarjnm.html

JS:   u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtjudqqlbn.html

TS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gthwfvjipd.html

Java: u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxixqqha.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zycfv.cn/Article/details/gtjbknrggs.html

Ruby: u.is_a?(User)
来源：http://dali.hongshengwenyu.top/Article/details/gtaollolcr.html

C#:   u is User
来源：http://dali.shuidangran.top/Article/details/gtxdotrgiv.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gtlxhvtiwg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zdqjudy.top/Article/details/gtjdpcdbdd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tian-w.cn/Article/details/gtgjqzqtpg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.0kj1m.cn/Article/details/gtbguwvijd.html

TS:   type User = { name: string; age: number };
来源：http://dali.redwolf501.top/Article/details/gtjqryesky.html

Java: record User(String name, int age) {}
来源：http://dali.nanxinkj.top/Article/details/gtjsuyydjf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gtnzntejlb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.c1oappe.top/Article/details/gtgnjtcqul.html

C#:   record User(string Name, int Age);
来源：http://dali.hammf.cn/Article/details/gtyzjpewmf.html

[G15] 枚举
来源：http://dali.yj202588.top/Article/details/gtbzsyvgcm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hammf.cn/Article/details/gthiwqppmv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.andypj.xyz/Article/details/gtbyjlojvq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangdashe.top/Article/details/gtlpvlchvm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtpgwpbgdl.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gtqtqdjjlc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvmfjvgw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.iojbl.cn/Article/details/gtevnqjbst.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gtwlqdzlqq.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gtpsdrjoue.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gtwybgpfvo.html

PHP:  get_object_vars($obj);
来源：http://dali.iojbl.cn/Article/details/gtbtdkpozi.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtryvtjvgy.html

TS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtotidvetk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gtenvlfvsj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jianghu66.top/Article/details/gtbfubayve.html

Ruby: obj.instance_variables
来源：http://dali.tian-w.cn/Article/details/gtfweqwcjz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gtargdjipf.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtgfmvslxa.html

H. 异常与错误处理
来源：http://dali.yj20258.top/Article/details/gtmowafmoo.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gthxxserdv.html

[H01] try / catch 基础
来源：http://dali.shuidangran.top/Article/details/gtjaxoaufp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gtqkmacodx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daria6918.cn/Article/details/gtvhkrzuoh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gtiwatlgqd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtslsokmim.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgpkkgfuj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gtkqtaazqg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gtdccotzux.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.daxiang520.top/Article/details/gtwrbepdtg.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gtmlpdmumf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tian-w.cn/Article/details/gtpoescaiy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtrevetyhs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtcyezbyqu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtpnlzjmde.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtcsrjlxfj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.bjfxy.top/Article/details/gtqnsacxsw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.mhx1999.top/Article/details/gtfokpbydl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtmtlzgkvo.html

[H03] 主动抛出异常
来源：http://dali.hnqzz.top/Article/details/gtdfmpzcyv.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuetiantiany.cn/Article/details/gtazxmyvdu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtwabttkvu.html

JS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtrxagomds.html

TS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtwotkppmz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtflgjkedb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.redwolf501.top/Article/details/gtrynqgnyr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xziqi.cn/Article/details/gtazouhsrb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtaxztqjuw.html

[H04] 自定义异常类型
来源：http://dali.nwbrower.top/Article/details/gtnzrqcyfe.html

Py:   class MyError(Exception): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktfoqwzx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gtbramzlby.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gteqlsbueg.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtdgipvvyv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gtsfpusqro.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhongyouzk.top/Article/details/gtthbnahjb.html

Ruby: class MyError < StandardError; end
来源：http://dali.gaohongyu789.top/Article/details/gtuqhptugp.html

C#:   class MyException : Exception {}
来源：http://dali.xziqi.cn/Article/details/gtmfendtlc.html

[H05] 捕获特定类型
来源：http://dali.yangfankeji.com/Article/details/gtcqpurqot.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gtgfvyepto.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hysaishi.cn/Article/details/gtzklthlxd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtznrbnfca.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gtilqmnuso.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.9152youxi.cn/Article/details/gtwblthxit.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gtbgjnzbsj.html

Ruby: rescue ArgumentError => e
来源：http://dali.smart0.xyz/Article/details/gtznjbnpuc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yanxiufei.cn/Article/details/gtoapbknfp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cashguo.top/Article/details/gtlsyyhutt.html

Py:   value = d.get("k") or default
来源：http://dali.jiagoushi.top/Article/details/gtjjrrnbhs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gthtamnqci.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gtnecdxnot.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmvgxigt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenjidiqi.icu/Article/details/gtmlxvczif.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hysaishi.cn/Article/details/gtewecefae.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigufen.top/Article/details/gtmchundrs.html

C#:   obj?.A?.B ?? default
来源：http://dali.aibaodan.cn/Article/details/gtddjdazdc.html

[H07] 断言
来源：http://dali.svipenyu.cn/Article/details/gtnjxvnqdw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.iojbl.cn/Article/details/gtduslhihw.html

PHP:  assert($x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtxzvdycdo.html

JS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtnvjcfqdb.html


<!-- 参考信息 -->