代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtiivdttlp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtemzlqcrc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gttfamrpvg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gtsxopumxg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.aibaodan.cn/Article/details/gtolugpydq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hysaishi.cn/Article/details/gtvgglupme.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpmgutno.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gtzevwqqjj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtmdtbnrjm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sxryk.cn/Article/details/gtsunyixke.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gthrxsqwfr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gtpfxjtihh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ppjwa.cn/Article/details/gttxvgavnh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.andypj.xyz/Article/details/gtkvhqjywt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.feifeiyinyue.top/Article/details/gtcbtrypbl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.meibo888.top/Article/details/gthvfllogb.html

[F05] 判断文件或目录是否存在
来源：http://dali.hammf.cn/Article/details/gtkjpyvuur.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gogol.net.cn/Article/details/gtialegfwe.html

PHP:  file_exists("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtwwlbwyyz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtkhkbmpxv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtntfdiwmu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtnsftdsim.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cucudq.cn/Article/details/gtaaxqfaqw.html

Ruby: File.exist?("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtsfeokoiw.html

C#:   File.Exists("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtuwxxjciz.html

[F06] 删除文件
来源：http://dali.yueranfly.top/Article/details/gttupfcipf.html

Py:   os.remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gthiuztkda.html

PHP:  unlink("a.txt");
来源：http://dali.birdmap.top/Article/details/gtukdimxoo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtpdzfvjox.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtmjxeksqo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtpitgfejx.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtcsguvded.html

Ruby: File.delete("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtgmeahlqk.html

C#:   File.Delete("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtznjfqeyd.html

[F07] 创建目录（含多级）
来源：http://dali.guowangkeji.top/Article/details/gtljcrqvpm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gtummnvmdp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.dashuyun.cn/Article/details/gtgwhqqlsm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gtvidkgerz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjunswoag.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnqzz.top/Article/details/gtgkpzrqzi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gthrohhcnb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.0kj1m.cn/Article/details/gtyznpycpl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangdashe.top/Article/details/gtuufgruns.html

[F08] 遍历目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gteoaieywd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tianlin.xyz/Article/details/gtqizfvygw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gtdkoxbhcz.html

JS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtimzakkym.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtlcqwbnqi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gtccsipbpe.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xylfe.cn/Article/details/gtcxnhusod.html

Ruby: Dir.children("dir")
来源：http://dali.nanxinkj.top/Article/details/gtpeatxrkr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hammf.cn/Article/details/gtdiexkhgg.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbnyomxu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtrfekxhtl.html

PHP:  filesize("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtqohuxexf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtorhadk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtfqpibubs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtyylmbtlc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cucudq.cn/Article/details/gtqjuuoxxn.html

Ruby: File.size("a.txt")
来源：http://dali.ivvv.top/Article/details/gtyopiedkz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.redwolf501.top/Article/details/gtybmtaxsn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.snrcjt.cn/Article/details/gtxbpjmhwy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtkcbagvxu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtgmbjqzxj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtgtgbvxgg.html

TS:   path.extname("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsnwvxli.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xziqi.cn/Article/details/gtswscpaef.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtefcrtyog.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtdspcydvc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtwixsozhh.html

[F11] 复制与移动文件
来源：http://dali.gaohongyu789.top/Article/details/gtljdkqasd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtumpgwlbq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigufen.top/Article/details/gtqwhgafxh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtclfvwasj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtwsdusfsq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cheryme.top/Article/details/gtsvijrtyr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gtecpuafrm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtemlelmes.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tanke756.top/Article/details/gtmdzrpaqz.html

[F12] CSV 读写
来源：http://dali.jqgufenzy.top/Article/details/gtlaxeuppg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gtlwyzejlt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ybcxt.top/Article/details/gtwplqqwas.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gtxnwcdciu.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtzxntzorc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenlongwang.top/Article/details/gtgxqnlfnq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ivvv.top/Article/details/gtuasjeuvd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhengqikj.top/Article/details/gtcmvwrfmq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.haohaochexian.top/Article/details/gtcwwigxsl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtyrriyfxu.html

G. 面向对象
来源：http://dali.jinqigufen.top/Article/details/gtxhlajtws.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gthtwbaplf.html

[G01] 定义类
来源：http://dali.snrcjt.cn/Article/details/gtfmbmgkjr.html

Py:   class User: pass
来源：http://dali.chenjidiqi.icu/Article/details/gtwmouqppw.html

PHP:  class User {}
来源：http://dali.ybcxt.top/Article/details/gtutepvrxl.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtzueduite.html

TS:   class User { name: string = ""; }
来源：http://dali.ybcxt.top/Article/details/gttcjrcdmv.html

Java: class User {}
来源：http://dali.daria6918.cn/Article/details/gtowzykajn.html

Go:   type User struct { Name string }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvcxmnzu.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gtyydeqvzh.html

C#:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtixmdgdkc.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gtfiezrtbl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sweek.top/Article/details/gtupxgkkfl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtesfsuecj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtlipoppif.html

TS:   constructor(public name: string) {}
来源：http://dali.ivvv.top/Article/details/gthnrkvvsv.html

Java: User(String name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtgrwcazvu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jianghu66.top/Article/details/gtwwgjbbum.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gtjdpujbjf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gtfexycxuc.html

[G03] 实例属性
来源：http://dali.cheryme.top/Article/details/gtdsgzcwxw.html

Py:   self.name = "x"
来源：http://dali.dianchejie.cn/Article/details/gtuhuatciy.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtcxzyaatb.html

JS:   this.name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtaduwbvqb.html

TS:   name: string = "x";
来源：http://dali.svipenyu.cn/Article/details/gtednmxoaw.html

Java: private String name;
来源：http://dali.xuetiantiany.cn/Article/details/gtlckaqwtm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.havefunace.top/Article/details/gtgocrvfsf.html

Ruby: @name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtltzbokgw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.iojbl.cn/Article/details/gteodofuii.html

[G04] 定义方法
来源：http://dali.cucudq.cn/Article/details/gtpdslrcat.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtozpvfqza.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtsyecflmb.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtbiomddlo.html

TS:   greet(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtvoikbmpu.html

Java: String greet() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gthxnyzhjd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtmurdnrvs.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtxoddbifx.html

C#:   public string Greet() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gtlngujvep.html

[G05] 继承
来源：http://dali.ehwqpu.com/Article/details/gtycfhdtrh.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gtacpttmzq.html

PHP:  class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gthahamjcd.html

JS:   class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gtpvplxfuj.html

TS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtghuivmzt.html

Java: class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtsukujitg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.feifeiyinyue.top/Article/details/gtmupvmjqo.html

Ruby: class Admin < User; end
来源：http://dali.quarkkingdee.top/Article/details/gttlbwtnxt.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gtdnrumcac.html

[G06] 重写方法
来源：http://dali.daxiang520.top/Article/details/gtshstgiwi.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gtqccjgsfq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtldxfhbod.html

JS:   greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtptognyyu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtnuinropd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gttafjtdlb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xziqi.cn/Article/details/gtwkgiiwsg.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gtfzjxgrrv.html

C#:   public override string Greet() => "admin";
来源：http://dali.iojbl.cn/Article/details/gtimfgzhds.html

[G07] 调用父类方法
来源：http://dali.yvedp.cn/Article/details/gtwjhiysfc.html

Py:   super().greet()
来源：http://dali.316326.xyz/Article/details/gtpnjzgbrb.html

PHP:  parent::greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtthngfagn.html

JS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtizgpsrcg.html

TS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtnqxuzcdh.html

Java: super.greet();
来源：http://dali.gzhubu.top/Article/details/gtmkicdfdr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuanzx.com/Article/details/gtxtxtblbj.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gtthctypus.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gtykjjuuso.html

[G08] 静态方法与属性
来源：http://dali.jyoumei.cn/Article/details/gtbzcucxrj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.svipenyu.cn/Article/details/gtrupzhrvt.html

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gtudbvrcqo.html

JS:   static f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtgycnniim.html

TS:   static f(): void {}
来源：http://dali.hnqzz.top/Article/details/gtonpzxqyk.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gtudmthoau.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gtsxgvwqga.html

Ruby: def self.f; end
来源：http://dali.havefunace.top/Article/details/gtfswxuapl.html

C#:   public static void F() {}
来源：http://dali.cdnleiting.top/Article/details/gtoofmohej.html

[G09] 接口 / 抽象类
来源：http://dali.hysaishi.cn/Article/details/gtcectzkyo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gthcvuqozw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shzxlz.cn/Article/details/gttacggtmw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gtjvjahjwx.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gtdyznythn.html

Java: interface Shape { double area(); }
来源：http://dali.cheryme.top/Article/details/gtujupadnu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbouomqym.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shangyingyoupin.top/Article/details/gtfymwekvk.html

C#:   interface IShape { double Area(); }
来源：http://dali.redwolf501.top/Article/details/gtylkcirnv.html

[G10] 访问控制
来源：http://dali.yueranfly.top/Article/details/gthzneelnt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tanke756.top/Article/details/gtmyrxdzgr.html

PHP:  public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gthggtukxv.html

JS:   #private 字段；其余公开
来源：http://dali.chenzaomai.com/Article/details/gttznojuti.html

TS:   public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtbuufynfr.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gtucmpnyzc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ehwqpu.com/Article/details/gtpxirlkgu.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtnmmyqwzb.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwrxiuuvj.html

[G11] getter / setter
来源：http://dali.zhiwuduotai.top/Article/details/gtgoubgzwf.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gtoqiguaul.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzzgytmvr.html

JS:   get name() { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjhjovvx.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtzpvjmdfg.html

Java: public String getName() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gthbcklvqy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtjahgnjrh.html

Ruby: attr_accessor :name
来源：http://dali.chenjidiqi.icu/Article/details/gtvhklodis.html

C#:   public string Name { get; set; }
来源：http://dali.shuidangran.top/Article/details/gttltmwnxg.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gtgpkftpda.html

Py:   def __str__(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gttdwaqbxw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtmjwitonk.html

JS:   toString() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtjunuaswj.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtslcljwmi.html

Java: @Override public String toString() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtocogvvyt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtythofgtd.html

Ruby: def to_s; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtivlmrvgj.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gtqstbpdho.html

[G13] 判断对象类型
来源：http://dali.daria6918.cn/Article/details/gtwqskpedv.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gtprmyzosy.html

PHP:  $u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtkwtuxqlc.html

JS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtjftqatjf.html

TS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtuzmtzlyk.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtwqpmiihl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.iojbl.cn/Article/details/gtdsxytkns.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigfzy.top/Article/details/gtcclsybud.html

C#:   u is User
来源：http://dali.pycfn.com/Article/details/gtbsqhdsve.html

[G14] 数据类 / record
来源：http://dali.hysaishi.cn/Article/details/gtsyvlxsmx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gtavxvwdqe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.0kj1m.cn/Article/details/gtujfqysfg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ehwqpu.com/Article/details/gtwfrzzrlq.html

TS:   type User = { name: string; age: number };
来源：http://dali.yonumen.top/Article/details/gtbwymbanp.html

Java: record User(String name, int age) {}
来源：http://dali.yuanzhike.top/Article/details/gttdcbqnpr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gtyeqypcdh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gtzqtvvkpa.html

C#:   record User(string Name, int Age);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbugvgzn.html

[G15] 枚举
来源：http://dali.gzhubu.top/Article/details/gtzxlzxrij.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.0kj1m.cn/Article/details/gtcrvagnsk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sysykeji.top/Article/details/gthqzvxxrz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gttnkknzxz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtogqwnwhz.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenlongwang.top/Article/details/gtfqkoouqi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aizwys.cn/Article/details/gtjnzzbvyd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xziqi.cn/Article/details/gtgwmgfyyo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtspjgrilj.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gtoerjisya.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guowangkeji.top/Article/details/gtzbpwwzee.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gtrenotqix.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtangfqxhh.html

TS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtefhrmfso.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xylfe.cn/Article/details/gtyeobveqd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258.top/Article/details/gtmpjivqsx.html

Ruby: obj.instance_variables
来源：http://dali.yangfankeji.com/Article/details/gtofwmnjlh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gtsewwhycb.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtgpodvlsf.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtklzpcp.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtsimtbvaq.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gtrpfnidxa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gtrstdkedp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xziqi.cn/Article/details/gtwkzorrgi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtleiaepuy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtawarmzkg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gtjfctqlcq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gtbzyhcujc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkygrpbbo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gthlceqqon.html

[H02] finally / ensure 收尾
来源：http://dali.nwbrower.top/Article/details/gtlbsplyek.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zdqjudy.top/Article/details/gtmeocwcaj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtgphyktyj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtmhcynbxa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtlbkjjyon.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrztweouj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sxryk.cn/Article/details/gthnodomme.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.vqdsnc.cn/Article/details/gtzpbrmimp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtxjtdovyz.html

[H03] 主动抛出异常
来源：http://dali.ybcxt.top/Article/details/gtjudyarad.html

Py:   raise ValueError("错误信息")
来源：http://dali.hongshengwenyu.top/Article/details/gtzulomloc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxbcykic.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtnpuymwlm.html

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtpeyvecgs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtufpalugb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jianghu66.top/Article/details/gtfbskvykk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.meibo888.top/Article/details/gtzwkdhhoh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gthzvuvlkj.html

[H04] 自定义异常类型
来源：http://dali.zhengqikj.top/Article/details/gtksgmjihn.html

Py:   class MyError(Exception): pass
来源：http://dali.birdmap.top/Article/details/gtawpssfut.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gthwxymdim.html

JS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gtbgtdpuas.html

TS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gtzdyofhie.html

Java: class MyException extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtlcyasfbl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.haohaochexian.top/Article/details/gtrahgqbuq.html

Ruby: class MyError < StandardError; end
来源：http://dali.0kj1m.cn/Article/details/gtqqmzqcuh.html

C#:   class MyException : Exception {}
来源：http://dali.jlsjyb.cn/Article/details/gtfxmsyiyn.html

[H05] 捕获特定类型
来源：http://dali.yueranfly.top/Article/details/gthrpkzixl.html

Py:   except ValueError as e:
来源：http://dali.cdnleiting.top/Article/details/gtvplknkex.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gtjewigixf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gtlqyfmxcn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gteqtfvvcb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.316326.xyz/Article/details/gtjdllezyd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.316326.xyz/Article/details/gtbbpyqmjo.html

Ruby: rescue ArgumentError => e
来源：http://dali.guowangkeji.top/Article/details/gtybjsoarn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daxiang520.top/Article/details/gtbtrajgot.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nanxuanxn.top/Article/details/gtkaggacel.html

Py:   value = d.get("k") or default
来源：http://dali.nanxinkj.top/Article/details/gtreipxtqz.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtwlldfybt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtnroxjuoj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gtmcrtuaen.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigfzy.top/Article/details/gtlkbogidk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pycfn.com/Article/details/gtsmtvwaod.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhixingplan.top/Article/details/gtqqqaggib.html

C#:   obj?.A?.B ?? default
来源：http://dali.ppjwa.cn/Article/details/gtohzakana.html

[H07] 断言
来源：http://dali.ydzc1.top/Article/details/gteuszrtza.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gzhubu.top/Article/details/gttdyefkpc.html

PHP:  assert($x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzswmpah.html

JS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gttyvxdved.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtgiacwfxw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sweek.top/Article/details/gtzgvijlem.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fengsongda.top/Article/details/gtwankuhkb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhiwuduotai.top/Article/details/gtrchemclz.html


<!-- 参考信息 -->