代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtgapkxktd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gtqktbnafr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gtuuodimuy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpvyydme.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.vqdsnc.cn/Article/details/gtzueoeuyc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtglpomhjx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xylfe.cn/Article/details/gtpqywlgdx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cheryme.top/Article/details/gtmwcmnxpy.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gtjgiecajq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.316326.xyz/Article/details/gtusbzremj.html

PHP:  file_exists("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtrbasspzr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtrgshjadd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtmflezgjw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtlfwloubq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gtcesvhnzo.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gtwefosivh.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtirzezxyl.html

[F06] 删除文件
来源：http://dali.nanxinkj.top/Article/details/gtdoruoysm.html

Py:   os.remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtqexpgvpb.html

PHP:  unlink("a.txt");
来源：http://dali.bjfxy.top/Article/details/gteivjyzdl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtdtxtnbfz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtlubxyeht.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtbzrhfszv.html

Go:   os.Remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtdwslxjzy.html

Ruby: File.delete("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtxmfmpibd.html

C#:   File.Delete("a.txt");
来源：http://dali.yongpay.top/Article/details/gtgicnuynw.html

[F07] 创建目录（含多级）
来源：http://dali.kuanghao11.cn/Article/details/gtpfzuqkvp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.svipenyu.cn/Article/details/gtcszgrpms.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gthorlyuux.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gtiiangjow.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gtjxkdxqed.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnxiangtu.top/Article/details/gtgkbmpwlz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gtdkuysuur.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yvedp.cn/Article/details/gtahtuknyq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj202588.top/Article/details/gtfhqeqzhy.html

[F08] 遍历目录
来源：http://dali.tianlin.xyz/Article/details/gtalxuekvm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.0kj1m.cn/Article/details/gtclbpocsz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gtmcywnthq.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gtcbetazck.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtnqdigrbr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gtabpbyrfn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sufxvd.cn/Article/details/gttzbaxjos.html

Ruby: Dir.children("dir")
来源：http://dali.andypj.xyz/Article/details/gtaxwteizv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xinyue.icu/Article/details/gtetwzodbf.html

[F09] 获取文件大小
来源：http://dali.guowangkeji.top/Article/details/gtvqvvlvgt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gttymjrxla.html

PHP:  filesize("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtfzshiwxw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gtdyjcnzfx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gtokitquxc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gteptithgb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gtokhgamig.html

Ruby: File.size("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtiyudgoby.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgufenzy.top/Article/details/gtqhsxhlaq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.meibo888.top/Article/details/gtuajetlcl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gthnnogkjy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevqkldkt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtsxvobgci.html

TS:   path.extname("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtzgptwtbg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxinkj.top/Article/details/gtjkdsmstz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtoenqbeez.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtvpbftzku.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gthcsbssnj.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtufmmencg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtajhfqxez.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtbvpfwxhu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtprkzdvkh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtwxwtjxyl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtkbjhoklj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.mhx1999.top/Article/details/gtwpyhlabc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtgvvnkheb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258.top/Article/details/gtobjzemrq.html

[F12] CSV 读写
来源：http://dali.daria6918.cn/Article/details/gtvokcvrbq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.andypj.xyz/Article/details/gtrhxdrdim.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gthlyrzuun.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.andypj.xyz/Article/details/gthnzygval.html

TS:   // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxlequge.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sysykeji.top/Article/details/gtylmpvomt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggssafrk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gtoagpxgni.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhengqikj.top/Article/details/gthkuszdhs.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gthanbmywm.html

G. 面向对象
来源：http://dali.feifeiyinyue.top/Article/details/gtpizjguwy.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtqcymrgjm.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gtoblomhvy.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gtmurlomth.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gtjgbcmtme.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtqjrqisqw.html

TS:   class User { name: string = ""; }
来源：http://dali.fengsongda.top/Article/details/gtojlzkffd.html

Java: class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtztcbvrtl.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gtpdselswh.html

Ruby: class User; end
来源：http://dali.sweek.top/Article/details/gtfrxawhfo.html

C#:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtmjaeusnd.html

[G02] 构造函数
来源：http://dali.gogol.net.cn/Article/details/gtfnauzauh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fengsongda.top/Article/details/gtocsymwls.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fzhhl.top/Article/details/gttoxntmgh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtsyzxbzyf.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gtecwqwssx.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtppsruird.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigufen.top/Article/details/gtkazjxzvf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtfsrzvtis.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwshaqeyd.html

[G03] 实例属性
来源：http://dali.hnxiangtu.top/Article/details/gtcnasbuzl.html

Py:   self.name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtscvwiygy.html

PHP:  public string $name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtbrfhoxtw.html

JS:   this.name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtqrqfqlao.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtswjjqatd.html

Java: private String name;
来源：http://dali.chenlongwang.top/Article/details/gtiaqchzoo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.316326.xyz/Article/details/gttfhmsgdr.html

Ruby: @name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gtxfbcjvjx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzypjsxcp.html

[G04] 定义方法
来源：http://dali.cashguo.top/Article/details/gtckndkrch.html

Py:   def greet(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtlazplspt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtweeydmld.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtyftuxkpf.html

TS:   greet(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtdzxslvyj.html

Java: String greet() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtghxvqvlm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtallkdzla.html

Ruby: def greet; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtmhoxclyc.html

C#:   public string Greet() => Name;
来源：http://dali.gzhubu.top/Article/details/gtkhrotycs.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gtlayboojr.html

Py:   class Admin(User): pass
来源：http://dali.vqdsnc.cn/Article/details/gtdahdnbhy.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtwrimhnsi.html

JS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtpiwcifoz.html

TS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtgmpoipue.html

Java: class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gthivoxpum.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hfpthk.cn/Article/details/gtfkavgyao.html

Ruby: class Admin < User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtpezqsnde.html

C#:   class Admin : User {}
来源：http://dali.hysaishi.cn/Article/details/gtambbcard.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gtgjuwcimm.html

Py:   def greet(self): return "admin"
来源：http://dali.svipenyu.cn/Article/details/gtkaznepsp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtxodpftmq.html

JS:   greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gttcomrpzc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtiuvwpzkc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyjaxzigz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnqzz.top/Article/details/gtdzmecmro.html

Ruby: def greet; "admin"; end
来源：http://dali.yongpay.top/Article/details/gteofsnvpt.html

C#:   public override string Greet() => "admin";
来源：http://dali.xylfe.cn/Article/details/gtoqajczif.html

[G07] 调用父类方法
来源：http://dali.cashguo.top/Article/details/gtdddlysna.html

Py:   super().greet()
来源：http://dali.c1oappe.top/Article/details/gtwyheczec.html

PHP:  parent::greet();
来源：http://dali.yangfankeji.com/Article/details/gtccvgiuho.html

JS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtxcmpkmfw.html

TS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtmmkvvtfe.html

Java: super.greet();
来源：http://dali.zhengqikj.top/Article/details/gtqautdfed.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guowangkeji.top/Article/details/gtcejhaupy.html

Ruby: super
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigvcfboc.html

C#:   base.Greet();
来源：http://dali.nanxinkj.top/Article/details/gteoigjveh.html

[G08] 静态方法与属性
来源：http://dali.shuidangran.top/Article/details/gtxbbutkjb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenjidiqi.icu/Article/details/gttffugydd.html

PHP:  public static function f() {}
来源：http://dali.yuxming.cn/Article/details/gtqkspwlge.html

JS:   static f() {}
来源：http://dali.aibaodan.cn/Article/details/gtiblkeqvq.html

TS:   static f(): void {}
来源：http://dali.quarkkingdee.top/Article/details/gtsgaykvsn.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtofrbjwbv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gtpwiovfef.html

Ruby: def self.f; end
来源：http://dali.c1oappe.top/Article/details/gtezrnhqez.html

C#:   public static void F() {}
来源：http://dali.yuxming.cn/Article/details/gtfqpwcrmj.html

[G09] 接口 / 抽象类
来源：http://dali.sufxvd.cn/Article/details/gtzafwpbwd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigfzy.top/Article/details/gtgarikuma.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangshuangyany.cn/Article/details/gttclpline.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxuanxn.top/Article/details/gtqqndkftm.html

TS:   interface Shape { area(): number; }
来源：http://dali.c1oappe.top/Article/details/gtgzkwdmpf.html

Java: interface Shape { double area(); }
来源：http://dali.hywenlv.cn/Article/details/gtschjcyxm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gtlvhgxnqs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkypncwm.html

C#:   interface IShape { double Area(); }
来源：http://dali.9152youxi.cn/Article/details/gttxnmoqum.html

[G10] 访问控制
来源：http://dali.zdqjudy.top/Article/details/gtnicptbqt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gtoosprsws.html

PHP:  public / protected / private
来源：http://dali.havefunace.top/Article/details/gtvnihuzau.html

JS:   #private 字段；其余公开
来源：http://dali.dashuyun.cn/Article/details/gtavipbycl.html

TS:   public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtqkkxzvip.html

Java: public / protected / private / 默认包级
来源：http://dali.hnqzz.top/Article/details/gtcaivkgwh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jiagoushi.top/Article/details/gtkvdxvide.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtpyeoxivr.html

C#:   public / protected / private / internal
来源：http://dali.daxiang520.top/Article/details/gtelsqxiff.html

[G11] getter / setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthnmksot.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gteeyelehw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtmzetaeha.html

JS:   get name() { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpodlkeir.html

TS:   get name(): string { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gtlgjtuaok.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtqsfyzmiu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gthzuwmdyb.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gtvwnkofaq.html

C#:   public string Name { get; set; }
来源：http://dali.ehwqpu.com/Article/details/gturdyojin.html

[G12] 对象转字符串
来源：http://dali.yueranfly.top/Article/details/gtxsczowvs.html

Py:   def __str__(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gteefusbgf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtjvmfpdwp.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtsjeoquve.html

TS:   toString(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gttwixyhgf.html

Java: @Override public String toString() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtuxqnqtyr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtwkizscrx.html

Ruby: def to_s; @name; end
来源：http://dali.c1oappe.top/Article/details/gtrpehftux.html

C#:   public override string ToString() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtrnwzadjr.html

[G13] 判断对象类型
来源：http://dali.zdqjudy.top/Article/details/gtwamsyfsi.html

Py:   isinstance(u, User)
来源：http://dali.316326.xyz/Article/details/gtvgrmdvjb.html

PHP:  $u instanceof User
来源：http://dali.havefunace.top/Article/details/gtznqqvqmy.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtwwspofrf.html

TS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtrhjnepgh.html

Java: u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtnaaqwmzj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangdashe.top/Article/details/gtxxikrunr.html

Ruby: u.is_a?(User)
来源：http://dali.zhoulong.xyz/Article/details/gtbmoudmod.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gtcmddgdqk.html

[G14] 数据类 / record
来源：http://dali.jyoumei.cn/Article/details/gtkqwagrnv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ppjwa.cn/Article/details/gtbbzajcly.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.iojbl.cn/Article/details/gtrpadmtdp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hfpthk.cn/Article/details/gtwmgtevpm.html

TS:   type User = { name: string; age: number };
来源：http://dali.svipenyu.cn/Article/details/gtdnfxdxna.html

Java: record User(String name, int age) {}
来源：http://dali.xziqi.cn/Article/details/gtgcaqsmsy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfldmgho.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsarvkyl.html

C#:   record User(string Name, int Age);
来源：http://dali.hnxiangtu.top/Article/details/gtskhzztxl.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gtrtzkjtje.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxinkj.top/Article/details/gtrdnljfno.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.snrcjt.cn/Article/details/gtdwguxllp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xziqi.cn/Article/details/gthwtxxiod.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gtrwdhgxkg.html

Java: enum Color { RED, GREEN }
来源：http://dali.hysaishi.cn/Article/details/gtnlabtfyy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ybcxt.top/Article/details/gtcrtynxit.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gtlocseikn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtkpmhmkxw.html

[G16] 对象转数组 / 字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkpwxfrt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hammf.cn/Article/details/gtjtfyfxep.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigfzy.top/Article/details/gtidvzsgbx.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtmsrcpaln.html

TS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gteyncurat.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigufen.top/Article/details/gtbsaghlio.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.mhx1999.top/Article/details/gtrfsczfhn.html

Ruby: obj.instance_variables
来源：http://dali.jinghuilouyu.cn/Article/details/gtupgfwjcw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtawcodmdw.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gthbdisstv.html

H. 异常与错误处理
来源：http://dali.jianghu66.top/Article/details/gtpfuhxhrn.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtgdicierp.html

[H01] try / catch 基础
来源：http://dali.chenlongwang.top/Article/details/gtsjdrmojp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sysykeji.top/Article/details/gtzgcphisu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aizwys.cn/Article/details/gtbqksbaex.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtdphrdwsc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtmjyrfdiu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gtwdjtlyzr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.snrcjt.cn/Article/details/gtemekpbgl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yueranfly.top/Article/details/gtcqpsnfqw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cheryme.top/Article/details/gttlfgfgvt.html

[H02] finally / ensure 收尾
来源：http://dali.xziqi.cn/Article/details/gtqoqbkykt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hongshengwenyu.top/Article/details/gtgszoiuhu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtcojftylh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtpwrdnnxl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtkkhgqfyq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtdntwwxif.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gogol.net.cn/Article/details/gtfxiucuvm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hywenlv.cn/Article/details/gtmqvvijgk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtgoxgtmpy.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gtwgtmdkql.html

Py:   raise ValueError("错误信息")
来源：http://dali.pengpengdd.cyou/Article/details/gtkdjaajkg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtkrmnwkiq.html

JS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzdzrily.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gttexthqjf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtazsedxgr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinghuilouyu.cn/Article/details/gtptivpeyk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gthwfyfqgb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtbmkyssgn.html

[H04] 自定义异常类型
来源：http://dali.nanxuanxn.top/Article/details/gtxlngscmw.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258.top/Article/details/gtclfgzonx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawkgreaj.html

JS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtwojrsurz.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtdcvrevfr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gtymgpknbt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zycfv.cn/Article/details/gtcrfaxhto.html

Ruby: class MyError < StandardError; end
来源：http://dali.smart0.xyz/Article/details/gtoiddumpf.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gtirbwwbkj.html

[H05] 捕获特定类型
来源：http://dali.yueranfly.top/Article/details/gttcevxlqv.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gtyedhxckv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhixingplan.top/Article/details/gttpeeybct.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gtxdnkxdxe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtrhtlfiiy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.snrcjt.cn/Article/details/gthngwlezg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gtrzefgevv.html

Ruby: rescue ArgumentError => e
来源：http://dali.yueranfly.top/Article/details/gtbajqfbmg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xylfe.cn/Article/details/gtjhqpfzjt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gotoacloud.top/Article/details/gtezytdteb.html

Py:   value = d.get("k") or default
来源：http://dali.chenlongwang.top/Article/details/gtcwyekaip.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtbqmirvcl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gtizjbpecp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtlkpeuqjc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cqqwz.cn/Article/details/gtlcecwrjb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gtmpdbphxe.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gtqysggbol.html

C#:   obj?.A?.B ?? default
来源：http://dali.jiagoushi.top/Article/details/gtgjxhqxqr.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gtphkovekf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenjidiqi.icu/Article/details/gteobaqade.html

PHP:  assert($x > 0);
来源：http://dali.gzhubu.top/Article/details/gtujfrkjra.html

JS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtsythpmut.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtzmfhcpgj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenzaomai.com/Article/details/gtqmsbbozf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsiwvhems.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gtfwffiuub.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtxlkpktml.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gtqsjhrwjr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gttabydxpi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.birdmap.top/Article/details/gtootaousz.html

JS:   e.message;  e.stack
来源：http://dali.yueranfly.top/Article/details/gthlbarhzv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtfnndsjgd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnqzz.top/Article/details/gtpepnforh.html

Go:   err.Error()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdubdpkae.html


<!-- 参考信息 -->