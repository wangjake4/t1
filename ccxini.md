代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtmbsxitsq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtljzdcgap.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtovtawwlp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gtycdiilfm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cdnleiting.top/Article/details/gtqypfjiqx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.c1oappe.top/Article/details/gtzreskoij.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtmmfplgog.html

[F04] 追加写入文件
来源：http://dali.aibaodan.cn/Article/details/gtxwjvsulu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gtkayyyojl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gtsdnzfqje.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtwufqftuc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtzzsfmnuy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gtvrcckfce.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuanzhike.top/Article/details/gtlckchggi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xziqi.cn/Article/details/gtwdczbinn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xinyue.icu/Article/details/gtvntqvsjk.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxvvujxl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fengsongda.top/Article/details/gtsetfminl.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtobhhkphf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtucgntrit.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtdrvzvdgm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtcddligce.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuanzhike.top/Article/details/gtqokwxbkg.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtesfvtmtk.html

C#:   File.Exists("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtntptqqdp.html

[F06] 删除文件
来源：http://dali.yuxming.cn/Article/details/gtuxosocza.html

Py:   os.remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtxmibygnh.html

PHP:  unlink("a.txt");
来源：http://dali.havefunace.top/Article/details/gtdmtrldfk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnysytyy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtsotbonwh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpxlhikv.html

Go:   os.Remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtoadetohd.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtcclpcjvb.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtrudvzrsb.html

[F07] 创建目录（含多级）
来源：http://dali.aibaodan.cn/Article/details/gtkuprvukz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtwmfufejg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ydzc1.top/Article/details/gthynwfboe.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gthvzzrvfz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtxexmyjgm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dianchejie.cn/Article/details/gtexndjubd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjnrphkg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pycfn.com/Article/details/gtbonefkud.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhoulong.xyz/Article/details/gtjyndvhlb.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gthmoiegog.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhoulong.xyz/Article/details/gtkhakabtp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gtkimjwzus.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gtwxhaagiv.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtudfouaay.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gticppcvgh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ybcxt.top/Article/details/gthezwdtxe.html

Ruby: Dir.children("dir")
来源：http://dali.aibaodan.cn/Article/details/gtqzsjtlfb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddfgxcpq.html

[F09] 获取文件大小
来源：http://dali.yangfankeji.com/Article/details/gtdfxsskcm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcjevwds.html

PHP:  filesize("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gthwgevnda.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gthzyeaocl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gttxftkvln.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtrwqqpsqg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.quarkkingdee.top/Article/details/gtsoxguptl.html

Ruby: File.size("a.txt")
来源：http://dali.sxryk.cn/Article/details/gthmisnofr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xinyue.icu/Article/details/gtgqqhipal.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gtccuwupsr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtyagjikar.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtmyizslff.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtbzucleqw.html

TS:   path.extname("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gthavywlid.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxinkj.top/Article/details/gtcvqlwwfb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtekkfuzyt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtevsstwnx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqcgmelg.html

[F11] 复制与移动文件
来源：http://dali.xinyue.icu/Article/details/gtbscyzllf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtusomrmdd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtqrmccyzl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtctoqatrn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtjxxvqjen.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrdwantu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.bjfxy.top/Article/details/gtntirnuri.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtnsyzqkye.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.kuanghao11.cn/Article/details/gtjuorcztg.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gtlhnfhsbb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuanzx.com/Article/details/gtbbvhsraw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aizwys.cn/Article/details/gtbmjqsihj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tian-w.cn/Article/details/gtfbmgfvtf.html

TS:   // 同上
来源：http://dali.ybcxt.top/Article/details/gtjchqnqxt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sxryk.cn/Article/details/gtbvtelkmy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gtvkeqncji.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cdnleiting.top/Article/details/gtbrbehady.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hysaishi.cn/Article/details/gtyhqlyign.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtmnansbxp.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gtimjebmst.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtwdnxsxpp.html

[G01] 定义类
来源：http://dali.0kj1m.cn/Article/details/gttzsgture.html

Py:   class User: pass
来源：http://dali.chenzaomai.com/Article/details/gteecxbchp.html

PHP:  class User {}
来源：http://dali.guowangkeji.top/Article/details/gtltusdqhh.html

JS:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtcwvyfnsx.html

TS:   class User { name: string = ""; }
来源：http://dali.quarkkingdee.top/Article/details/gtopoockrh.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gtzvalxxsf.html

Go:   type User struct { Name string }
来源：http://dali.zhijiandao.cn/Article/details/gtltwygmaq.html

Ruby: class User; end
来源：http://dali.haohaochexian.top/Article/details/gtrxkgrvdd.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtkvmyscev.html

[G02] 构造函数
来源：http://dali.tanke756.top/Article/details/gtfslfeafz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gtgxkuydlb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cqqwz.cn/Article/details/gtfrsozcgm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gtmaqwfgpc.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtqsdrizmy.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtbhgmmcri.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ppjwa.cn/Article/details/gtsjvfnbth.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gtqkxugtdi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdvpbdowt.html

[G03] 实例属性
来源：http://dali.dianchejie.cn/Article/details/gtfmmhbotf.html

Py:   self.name = "x"
来源：http://dali.meibo888.top/Article/details/gtyakmtevh.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gtwxagzujz.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gtrcfaougd.html

TS:   name: string = "x";
来源：http://dali.jqgfzy.top/Article/details/gtmmgndzvl.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gtrdepwvwa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnxiangtu.top/Article/details/gtveqqupku.html

Ruby: @name = "x"
来源：http://dali.yj20258.top/Article/details/gtkzgtvkrb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj202588.top/Article/details/gtfmalqrlr.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gtxdvxpdmd.html

Py:   def greet(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuilrzxsh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtlbgwfuvg.html

JS:   greet() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtvuahvtrl.html

TS:   greet(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtwrqhkuxf.html

Java: String greet() { return name; }
来源：http://dali.cucudq.cn/Article/details/gtpldnwzmz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtjhukkwsr.html

Ruby: def greet; @name; end
来源：http://dali.cheryme.top/Article/details/gttiafxezq.html

C#:   public string Greet() => Name;
来源：http://dali.jiagoushi.top/Article/details/gteshbnegi.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gtexluobpz.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gteookimzv.html

PHP:  class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtnxxfnbto.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtiyhgffgd.html

TS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtkrxirgon.html

Java: class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gthjkomugw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gogol.net.cn/Article/details/gtvluyxhcz.html

Ruby: class Admin < User; end
来源：http://dali.jianghu66.top/Article/details/gtjivbumja.html

C#:   class Admin : User {}
来源：http://dali.yj20258.top/Article/details/gtfgwkmlot.html

[G06] 重写方法
来源：http://dali.nwbrower.top/Article/details/gtbylztxbh.html

Py:   def greet(self): return "admin"
来源：http://dali.havefunace.top/Article/details/gtjcbdtgun.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmlipjhud.html

JS:   greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtsykzuoau.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtonxczrch.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtbkmdbuvr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj202588.top/Article/details/gtyhioepru.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpmkcaoc.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgufenzy.top/Article/details/gtjldwfahj.html

[G07] 调用父类方法
来源：http://dali.tian-w.cn/Article/details/gtbzulqcfe.html

Py:   super().greet()
来源：http://dali.cucudq.cn/Article/details/gtncncszrl.html

PHP:  parent::greet();
来源：http://dali.mhx1999.top/Article/details/gtuyynkvwb.html

JS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gtlmctjklk.html

TS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gthiyzcceb.html

Java: super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtjjxefhvm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nwbrower.top/Article/details/gtriuasezx.html

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gtghmocsxv.html

C#:   base.Greet();
来源：http://dali.cheryme.top/Article/details/gtczhadocj.html

[G08] 静态方法与属性
来源：http://dali.jyoumei.cn/Article/details/gtfbzogldc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gtredbwmxa.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtxucqpimg.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtmknoaxmg.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gtjeimpwws.html

Java: static void f() {}
来源：http://dali.yj20258888.top/Article/details/gtpnjfmhaj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zdqjudy.top/Article/details/gttanwuwjp.html

Ruby: def self.f; end
来源：http://dali.sxryk.cn/Article/details/gtqqujwsfs.html

C#:   public static void F() {}
来源：http://dali.dianchejie.cn/Article/details/gtqjnrpasj.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gtpyxyblij.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.bjfxy.top/Article/details/gtovejfphx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zdqjudy.top/Article/details/gtjftwqrlt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gtzmistcah.html

TS:   interface Shape { area(): number; }
来源：http://dali.gotoacloud.top/Article/details/gtfcweuydv.html

Java: interface Shape { double area(); }
来源：http://dali.meibo888.top/Article/details/gteatdxtsr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gtmvqmhtlk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gtupzztbej.html

C#:   interface IShape { double Area(); }
来源：http://dali.sysykeji.top/Article/details/gtsphqfviy.html

[G10] 访问控制
来源：http://dali.yueranfly.top/Article/details/gtcwemwuid.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenzaomai.com/Article/details/gtbrixmdhi.html

PHP:  public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtijahcbmt.html

JS:   #private 字段；其余公开
来源：http://dali.gotoacloud.top/Article/details/gtslmsgjyc.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtzbtzqwdl.html

Java: public / protected / private / 默认包级
来源：http://dali.yanxiufei.cn/Article/details/gtxseqfrnh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cashguo.top/Article/details/gtnijemhoh.html

Ruby: public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtatpkzevv.html

C#:   public / protected / private / internal
来源：http://dali.zhiwuduotai.top/Article/details/gtothqsmdp.html

[G11] getter / setter
来源：http://dali.yj20258.top/Article/details/gtrxfbicrz.html

Py:   @property 与 @x.setter
来源：http://dali.hywenlv.cn/Article/details/gtkbivlzzh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtwxknvmqo.html

JS:   get name() { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtlqndntwm.html

TS:   get name(): string { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtvtbldckv.html

Java: public String getName() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvipfjncb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gttrvqahvf.html

Ruby: attr_accessor :name
来源：http://dali.zhongyouzk.top/Article/details/gtotqknrgh.html

C#:   public string Name { get; set; }
来源：http://dali.jqgfzy.top/Article/details/gtfqnplfjc.html

[G12] 对象转字符串
来源：http://dali.zhixingplan.top/Article/details/gtraixaule.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gtydezoxuj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqhpaajje.html

JS:   toString() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtvavoshmo.html

TS:   toString(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtpzvpifux.html

Java: @Override public String toString() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtkiopmjwe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtbbowxulg.html

Ruby: def to_s; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtcyqdfbcq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtwcyttddh.html

[G13] 判断对象类型
来源：http://dali.fzhhl.top/Article/details/gtemehqkay.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gtgbarojur.html

PHP:  $u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtvbualpjp.html

JS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtbqoknmga.html

TS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gtcljoekui.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtpvzvnsov.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlutdmce.html

Ruby: u.is_a?(User)
来源：http://dali.zhengqikj.top/Article/details/gtgpbzqmvt.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gtgvfxcsbv.html

[G14] 数据类 / record
来源：http://dali.meibo888.top/Article/details/gtjedqhxes.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamiafphz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuxming.cn/Article/details/gtsxceutgo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gtvjpcrdrj.html

TS:   type User = { name: string; age: number };
来源：http://dali.daria6918.cn/Article/details/gtyksspshp.html

Java: record User(String name, int age) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtgdicadcp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ehwqpu.com/Article/details/gtgmndltck.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gogol.net.cn/Article/details/gtbpoiawfd.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258888.top/Article/details/gtwsjjxasr.html

[G15] 枚举
来源：http://dali.birdmap.top/Article/details/gtrloclkyi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.havefunace.top/Article/details/gtbntdvrrn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gtlhcpulca.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgufenzy.top/Article/details/gtxztgkbgw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gtkjaingjh.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gtyhuxvgjq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.kuanghao11.cn/Article/details/gtnazdomew.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aizwys.cn/Article/details/gtdogquxsf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xylfe.cn/Article/details/gtfppgvvsi.html

[G16] 对象转数组 / 字典
来源：http://dali.cqqwz.cn/Article/details/gtyenumszj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gthiexxrmi.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gtsaenmybs.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvdqqmtb.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtfqnoqmag.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gtcjinagfh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gtjxdrtlgs.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gtqikvbecn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtvveqkepd.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqulnsmie.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtnfukmmnd.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtockfysyr.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gtapmftnuk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.haohaochexian.top/Article/details/gtmamwlfru.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gtphglpkmo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gtqpvwjkgd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gthdcypzks.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaskkohqk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nwbrower.top/Article/details/gtzosegawv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxinkj.top/Article/details/gtfwyaozjr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yonumen.top/Article/details/gtcgqeopun.html

[H02] finally / ensure 收尾
来源：http://dali.cheryme.top/Article/details/gtohbulnko.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jyoumei.cn/Article/details/gtzartokvi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtcflgibpd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtdzhnlczw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtxcrwewho.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtijmdpeyh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangshuangyany.cn/Article/details/gtjgsyqxkt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gtathwjewn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauaehzmw.html

[H03] 主动抛出异常
来源：http://dali.cheryme.top/Article/details/gtsfvprpbf.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhongyouzk.top/Article/details/gtvwljfmrk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gthpvevsyg.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtfjzsxrks.html

TS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtumhnqjjy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtqqkgbqgv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangdashe.top/Article/details/gttypxanzb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sweek.top/Article/details/gtmbcupafe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtgppisasz.html

[H04] 自定义异常类型
来源：http://dali.smart0.xyz/Article/details/gtuiklkwif.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gttpqwkyqh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gtgycpicko.html

JS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gtnghzzyig.html

TS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtegjmxpgf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gtloprizuo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvpssqvj.html

Ruby: class MyError < StandardError; end
来源：http://dali.gogol.net.cn/Article/details/gtsfhzwbmk.html

C#:   class MyException : Exception {}
来源：http://dali.jiagoushi.top/Article/details/gtihkjqcvi.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gtnmjcixwt.html

Py:   except ValueError as e:
来源：http://dali.0kj1m.cn/Article/details/gtacaqncrm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cheryme.top/Article/details/gtozaysvwa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gtynmipudc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtnvjlifmt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gtfpsvfvhq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hysaishi.cn/Article/details/gthzyucrmr.html

Ruby: rescue ArgumentError => e
来源：http://dali.cdnleiting.top/Article/details/gtjeqlcfqg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.havefunace.top/Article/details/gtlwulyptu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jyoumei.cn/Article/details/gtxrcthwms.html

Py:   value = d.get("k") or default
来源：http://dali.fengsongda.top/Article/details/gtlkproizi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtgqxqnmqq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtuhykiicf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gtzdssdukf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaioyxyuj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.haohaochexian.top/Article/details/gticyxjluy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gtamncjjkh.html

C#:   obj?.A?.B ?? default
来源：http://dali.yueranfly.top/Article/details/gthqevgfle.html

[H07] 断言
来源：http://dali.aizwys.cn/Article/details/gtriuxzdxp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.haohaochexian.top/Article/details/gtwmiblocx.html

PHP:  assert($x > 0);
来源：http://dali.cucudq.cn/Article/details/gtcrssoech.html

JS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtzzvfyzxv.html

TS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtfhjfivnd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.bjfxy.top/Article/details/gttdhredel.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gtospyfqgo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.meibo888.top/Article/details/gttstergbi.html


<!-- 参考信息 -->