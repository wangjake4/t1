代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zycfv.cn/Article/details/gtkrndxfdh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuanzhike.top/Article/details/gtlegxkbpg.html

[F03] 写入文件（覆盖）
来源：http://dali.yonumen.top/Article/details/gtrjpaokmo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhongyouzk.top/Article/details/gtjemrrlcj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtlgcidybq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gtacunfkfd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gtacnhkyjl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gtsbhttysb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gtqykqcvaa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtztpmizcu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtlywvgjir.html

[F04] 追加写入文件
来源：http://dali.hywenlv.cn/Article/details/gthccsppjs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258.top/Article/details/gtzuugwoef.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daria6918.cn/Article/details/gtrgpgguzw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtdoyckoxg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtageaoyyo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ppjwa.cn/Article/details/gtpstybpyl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ivvv.top/Article/details/gtfsdqllko.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.vqdsnc.cn/Article/details/gtjlxaejah.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hammf.cn/Article/details/gtdspcczrv.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtqglbqaaw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjinpsqjl.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtppyckawd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtxpvafaxa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtllcfegcz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtldbmpgrr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcarprjqa.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtmwyyhemy.html

C#:   File.Exists("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtykzficwb.html

[F06] 删除文件
来源：http://dali.cashguo.top/Article/details/gtrwnjtuph.html

Py:   os.remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtmhdvfvhl.html

PHP:  unlink("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtvlljxwzv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gticukxznz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtsjxnoxma.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtczlflfhh.html

Go:   os.Remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtbxieigxr.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtkupejsav.html

C#:   File.Delete("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtkkvzknis.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gtrvjlyzjg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gtjnfshzzs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jianghu66.top/Article/details/gtsvwehnbn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gtntnkxfbp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gtedkmbapn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jyoumei.cn/Article/details/gtdhixcenl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dianchejie.cn/Article/details/gtlhvbylxj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinghuilouyu.cn/Article/details/gtagyvahcj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxuanxn.top/Article/details/gthxklooma.html

[F08] 遍历目录
来源：http://dali.haohaochexian.top/Article/details/gtlcbhdbnr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gtiulwdfue.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ydzc1.top/Article/details/gtjncvbzvu.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtwbttdxsy.html

TS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gtxyrbgold.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gtywkrawrm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ivvv.top/Article/details/gtrdnvagkf.html

Ruby: Dir.children("dir")
来源：http://dali.cdnleiting.top/Article/details/gtxwgoaodj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ivvv.top/Article/details/gtfmtqssjv.html

[F09] 获取文件大小
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpuzydnu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtvssdmopo.html

PHP:  filesize("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gttjzlyaig.html

JS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtwksglgbq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gtjbrkdgug.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtzisvtqcr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuxming.cn/Article/details/gtcwhszrps.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtdzwqvllm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gtmmfgcgfn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gtftshpfaq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtqkjxjirf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.redwolf501.top/Article/details/gtkizprqwh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtwakmxtig.html

TS:   path.extname("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtkyhmbkey.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yangfankeji.com/Article/details/gtbidhakic.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtsomoljil.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtmoodarjv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtagnaoqvt.html

[F11] 复制与移动文件
来源：http://dali.kuanghao11.cn/Article/details/gtefisfslt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtvrtehpat.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.c1oappe.top/Article/details/gtpudwhlsw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtlxiqamrn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlfscqek.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.haohaochexian.top/Article/details/gteichywpn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gtvjqlglmy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtuooiyfzu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pengpengdd.cyou/Article/details/gtxdszrfpb.html

[F12] CSV 读写
来源：http://dali.nanxinkj.top/Article/details/gtgrtmokpo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnqzz.top/Article/details/gthiijnrza.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gotoacloud.top/Article/details/gtdnpyokgk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hysaishi.cn/Article/details/gtcomesqer.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gtrhhfueyt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gtueumanpj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgfzy.top/Article/details/gttqahrqiy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.vqdsnc.cn/Article/details/gtkvcgnzkb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zdqjudy.top/Article/details/gtmdccofuo.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtzonexrdl.html

G. 面向对象
来源：http://dali.xziqi.cn/Article/details/gtuomstjad.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgrdayvpk.html

[G01] 定义类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwlhezqq.html

Py:   class User: pass
来源：http://dali.yongpay.top/Article/details/gtfevcyztt.html

PHP:  class User {}
来源：http://dali.xinyue.icu/Article/details/gtdfytwdvo.html

JS:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtqhcsjxht.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gtscymjwkb.html

Java: class User {}
来源：http://dali.yangfankeji.com/Article/details/gtvuisktkk.html

Go:   type User struct { Name string }
来源：http://dali.chenzaomai.com/Article/details/gtygjqvinl.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gttvzeomxe.html

C#:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtylkhniuq.html

[G02] 构造函数
来源：http://dali.cheryme.top/Article/details/gtvgpjteow.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gtaramkuen.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jyoumei.cn/Article/details/gtzplinqjz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtklakcnum.html

TS:   constructor(public name: string) {}
来源：http://dali.cucudq.cn/Article/details/gtdsbdywke.html

Java: User(String name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gtupcjyhqi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sysykeji.top/Article/details/gtfvnsirpl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj202588.top/Article/details/gtwvnkypsm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtmjiehlgq.html

[G03] 实例属性
来源：http://dali.nwbrower.top/Article/details/gtwlzacxyr.html

Py:   self.name = "x"
来源：http://dali.haohaochexian.top/Article/details/gtblmrfgyz.html

PHP:  public string $name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtswtrdgac.html

JS:   this.name = "x";
来源：http://dali.ivvv.top/Article/details/gtlbdsqsob.html

TS:   name: string = "x";
来源：http://dali.sysykeji.top/Article/details/gtrqnhokrj.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gtawizdcaz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gtcrivirlk.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gtnvsvechm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ppjwa.cn/Article/details/gtvhvkpwbj.html

[G04] 定义方法
来源：http://dali.sufxvd.cn/Article/details/gtqmgsgwqf.html

Py:   def greet(self): return self.name
来源：http://dali.yueranfly.top/Article/details/gtnzqxcbyc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtooqnkbyc.html

JS:   greet() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtvdurlbre.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtvgnjgsuk.html

Java: String greet() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzjvaofez.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtghlbupjw.html

Ruby: def greet; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtxpfrppqc.html

C#:   public string Greet() => Name;
来源：http://dali.guowangkeji.top/Article/details/gttfktmbtk.html

[G05] 继承
来源：http://dali.yueranfly.top/Article/details/gtbhnolznb.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gtgvgkixvd.html

PHP:  class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtlqfsgyqo.html

JS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtfskpiiop.html

TS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtmwifbfoc.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtpomlzvmd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsavpfugv.html

Ruby: class Admin < User; end
来源：http://dali.zdqjudy.top/Article/details/gttcsegsdz.html

C#:   class Admin : User {}
来源：http://dali.nwbrower.top/Article/details/gtcbipkmjn.html

[G06] 重写方法
来源：http://dali.ybcxt.top/Article/details/gtkjuffjzi.html

Py:   def greet(self): return "admin"
来源：http://dali.zhoulong.xyz/Article/details/gtndcasxnt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtsoevgbra.html

JS:   greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gthmwcurfm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtinwetrku.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gttoosttdz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuetiantiany.cn/Article/details/gtyvqjwsqx.html

Ruby: def greet; "admin"; end
来源：http://dali.xziqi.cn/Article/details/gtqzihegex.html

C#:   public override string Greet() => "admin";
来源：http://dali.xylfe.cn/Article/details/gtdexfzpje.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskxxzpok.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gtgrwaybkq.html

PHP:  parent::greet();
来源：http://dali.tianlin.xyz/Article/details/gtcoqjhxci.html

JS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtfjoxjljw.html

TS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gtmvewflqn.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtpzklmnlv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cucudq.cn/Article/details/gtvvcswohi.html

Ruby: super
来源：http://dali.ybcxt.top/Article/details/gtonjjugpt.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gtejxmocwe.html

[G08] 静态方法与属性
来源：http://dali.jinqigufen.top/Article/details/gtifvmcfkw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gtfghuokdi.html

PHP:  public static function f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtlvhlftst.html

JS:   static f() {}
来源：http://dali.mhx1999.top/Article/details/gtozuzgcwr.html

TS:   static f(): void {}
来源：http://dali.c1oappe.top/Article/details/gtdxmmqoir.html

Java: static void f() {}
来源：http://dali.zdqjudy.top/Article/details/gtisdzclcl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenzaomai.com/Article/details/gtugzgbcan.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gtyijrpzbq.html

C#:   public static void F() {}
来源：http://dali.bjfxy.top/Article/details/gttdcwnizz.html

[G09] 接口 / 抽象类
来源：http://dali.nanxuanxn.top/Article/details/gtswrhixal.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gzhubu.top/Article/details/gtmcgyjqxl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yanxiufei.cn/Article/details/gtbxwceyuv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuanzx.com/Article/details/gtsrtqroda.html

TS:   interface Shape { area(): number; }
来源：http://dali.tanke756.top/Article/details/gtdwxtvckg.html

Java: interface Shape { double area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtkrjxeeir.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigfzy.top/Article/details/gtsrkexctj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gthtqnasnh.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gtmdtzrptu.html

[G10] 访问控制
来源：http://dali.ppjwa.cn/Article/details/gtweqynfjk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tianlin.xyz/Article/details/gtifjbsabr.html

PHP:  public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gthmgsnpdb.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gtucygiupi.html

TS:   public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtxvoijdpv.html

Java: public / protected / private / 默认包级
来源：http://dali.guowangkeji.top/Article/details/gtfyzbroun.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hywenlv.cn/Article/details/gtczgcclsk.html

Ruby: public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonjrkmog.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gtqbxikoyc.html

[G11] getter / setter
来源：http://dali.sufxvd.cn/Article/details/gtubefxexf.html

Py:   @property 与 @x.setter
来源：http://dali.xylfe.cn/Article/details/gtpqcwjcsg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtmjnujeov.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjhryexzl.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtczrlcnhj.html

Java: public String getName() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtkehtpvwo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtwovrmaba.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbtvouos.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gtfpobxmyh.html

[G12] 对象转字符串
来源：http://dali.yonumen.top/Article/details/gtrlgskdyy.html

Py:   def __str__(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gtjkpqizwi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtybgcerxc.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtogupypxz.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtugifhrgz.html

Java: @Override public String toString() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtxpkwrppw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtsjrvofld.html

Ruby: def to_s; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuourztij.html

C#:   public override string ToString() => Name;
来源：http://dali.iojbl.cn/Article/details/gtkakzanzg.html

[G13] 判断对象类型
来源：http://dali.xylfe.cn/Article/details/gtqgciqeye.html

Py:   isinstance(u, User)
来源：http://dali.pengpengdd.cyou/Article/details/gtgeppraqc.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gthkfbcfwv.html

JS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdsntaix.html

TS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtjghbxrqi.html

Java: u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtqdredxeq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.mhx1999.top/Article/details/gtjoikqpvk.html

Ruby: u.is_a?(User)
来源：http://dali.xinyue.icu/Article/details/gtkpdhomnl.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqvkinlt.html

[G14] 数据类 / record
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwwcvxky.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gtomwqqymp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj202588.top/Article/details/gtabcnuiqk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nanxinkj.top/Article/details/gtcfixjhrk.html

TS:   type User = { name: string; age: number };
来源：http://dali.dashuyun.cn/Article/details/gtkxmdmkkf.html

Java: record User(String name, int age) {}
来源：http://dali.daria6918.cn/Article/details/gtmvpgleol.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gtgjztrjet.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgufenzy.top/Article/details/gtbudkerbe.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gtolvkwufz.html

[G15] 枚举
来源：http://dali.daxiang520.top/Article/details/gtuvsgktmu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.iojbl.cn/Article/details/gtqwtpkcrv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangdashe.top/Article/details/gtefimkhdr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnxiangtu.top/Article/details/gtpgosqhdq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyhphopc.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenzaomai.com/Article/details/gtvnsvigve.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.0kj1m.cn/Article/details/gtdtkgyoqf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jianghu66.top/Article/details/gtiwrtwwrj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtufbzuetp.html

[G16] 对象转数组 / 字典
来源：http://dali.xinyue.icu/Article/details/gtfnlsrykj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhijiandao.cn/Article/details/gtlvqqpuwf.html

PHP:  get_object_vars($obj);
来源：http://dali.cashguo.top/Article/details/gttdgnmzwq.html

JS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gtcxalxzrf.html

TS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gtepvftwec.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gtldskvfdc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cucudq.cn/Article/details/gtdubltdnm.html

Ruby: obj.instance_variables
来源：http://dali.9152youxi.cn/Article/details/gtpytctabo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbvzbjok.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gteorolirx.html

H. 异常与错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjcqposx.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtmkvrkdvh.html

[H01] try / catch 基础
来源：http://dali.guannengcc.top/Article/details/gtvkrjlxbc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.svipenyu.cn/Article/details/gttxryyyka.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hywenlv.cn/Article/details/gttppgkzai.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtovlaahsk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtudssyaqw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.andypj.xyz/Article/details/gtaqehiibf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daxiang520.top/Article/details/gtatohyvyj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cdnleiting.top/Article/details/gtoaemgbpx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.9152youxi.cn/Article/details/gtptrlvrfq.html

[H02] finally / ensure 收尾
来源：http://dali.tanke756.top/Article/details/gtogowjjzi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ehwqpu.com/Article/details/gtuwbtkkwv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtktfuqpaj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtjumyruxg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtvmrarplh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtjrroyqwb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgfzy.top/Article/details/gtzprgfhmw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tian-w.cn/Article/details/gtdsoqlnpw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtuxtfawzk.html

[H03] 主动抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gtnoinzoyr.html

Py:   raise ValueError("错误信息")
来源：http://dali.pengpengdd.cyou/Article/details/gtoxcbzyqq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtatcdwjyy.html

JS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtrtuzdcyi.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtbeopifth.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtuiqqcgjp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jlsjyb.cn/Article/details/gtornhezev.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepzlxmsm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtahatzmrp.html

[H04] 自定义异常类型
来源：http://dali.yj202588.top/Article/details/gtqdguslwg.html

Py:   class MyError(Exception): pass
来源：http://dali.meibo888.top/Article/details/gtevftsvou.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtpttcwlho.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjlytpbub.html

TS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gttxetwwvy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gtnbuqwscj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yonumen.top/Article/details/gtunahjump.html

Ruby: class MyError < StandardError; end
来源：http://dali.hfpthk.cn/Article/details/gtytyaxggt.html

C#:   class MyException : Exception {}
来源：http://dali.nwbrower.top/Article/details/gtsugntmyl.html

[H05] 捕获特定类型
来源：http://dali.guannengcc.top/Article/details/gtxdduroqn.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gtmvzukbxp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pycfn.com/Article/details/gtajdavsvj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gtfeqvhxtv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gtwzwegrtc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhengqikj.top/Article/details/gtkxyhfdem.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.feifeiyinyue.top/Article/details/gtdwmulfzs.html

Ruby: rescue ArgumentError => e
来源：http://dali.hongshengwenyu.top/Article/details/gtitxmvlbx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhuydqxl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigufen.top/Article/details/gtlgbtrghs.html

Py:   value = d.get("k") or default
来源：http://dali.gzhubu.top/Article/details/gtqqcixmtx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nanxuanxn.top/Article/details/gtgtscesce.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtodgvfddc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gtaxuhwhtq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sxryk.cn/Article/details/gtsumhgbnv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuanzx.com/Article/details/gtnlegrvab.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ydzc1.top/Article/details/gtpmytygsl.html

C#:   obj?.A?.B ?? default
来源：http://dali.tian-w.cn/Article/details/gtpaplbrnc.html

[H07] 断言
来源：http://dali.0kj1m.cn/Article/details/gthxndmapy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqacymsd.html

PHP:  assert($x > 0);
来源：http://dali.redwolf501.top/Article/details/gtasczzxvj.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtgeunqyee.html


<!-- 参考信息 -->