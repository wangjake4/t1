代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.bjfxy.top/Article/details/gtuafwpcxj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jlsjyb.cn/Article/details/gtqnnubvce.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gtuvmytkoo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gtypxoooix.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycaemoii.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tian-w.cn/Article/details/gtkrwrriwn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgufenzy.top/Article/details/gtrnqgzklf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gtucukcbcx.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenlongwang.top/Article/details/gtsacskkfb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pycfn.com/Article/details/gtpmyjqbph.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtoxioxqlg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtpzuciqnm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtiwccynno.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtlthhlyme.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yvedp.cn/Article/details/gtumdwgpbg.html

Ruby: File.exist?("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtrppanqmj.html

C#:   File.Exists("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtaspfcwlh.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gtcwpvrqzq.html

Py:   os.remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfwnodlg.html

PHP:  unlink("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtdybhhbll.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtbrccgcnd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtsaexbqvg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmipwzeci.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtyilphang.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtrefmsbns.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258.top/Article/details/gtwwrwxbwr.html

[F07] 创建目录（含多级）
来源：http://dali.chenjidiqi.icu/Article/details/gtqmczcfrx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gtzhaelydw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.mhx1999.top/Article/details/gtgascjtif.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gtpdwpjpxm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gtmoonldoz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.redwolf501.top/Article/details/gtxesjxehf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hywenlv.cn/Article/details/gtixcnlaim.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cdnleiting.top/Article/details/gtnwgmepvr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gtvpqgucbr.html

[F08] 遍历目录
来源：http://dali.9152youxi.cn/Article/details/gtlxefegtg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cheryme.top/Article/details/gtnbnevyes.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cucudq.cn/Article/details/gtzzrdmtff.html

JS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtgzvollkq.html

TS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtuviomrbk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gtygmfxnrb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtobadiwxq.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigufen.top/Article/details/gtkkgtenek.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zycfv.cn/Article/details/gtjadkrwte.html

[F09] 获取文件大小
来源：http://dali.jinqigfzy.top/Article/details/gtblfglbre.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtadpsjsno.html

PHP:  filesize("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtkosttzyr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtzwebilrn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gtreoxotas.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtbshrpmfw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttaiziduw.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjswvpyot.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nwbrower.top/Article/details/gtgtmuifyo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.smart0.xyz/Article/details/gtiigxdtrl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtykanyynm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtnxsgoqwj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtyyzwvimh.html

TS:   path.extname("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrxmgzqn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yangfankeji.com/Article/details/gtlmxnoiac.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtjvqqnnru.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtjbqsxxek.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtygtifejh.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gtcthvefmr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtgahepjmg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gteoftzeee.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtrhatkvim.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtufqmgwhh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtbuuomimv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sweek.top/Article/details/gtwjabjabl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtgouqkkas.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hfpthk.cn/Article/details/gtrwoneqwg.html

[F12] CSV 读写
来源：http://dali.daxiang520.top/Article/details/gtfatnbamg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzopvnwg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hysaishi.cn/Article/details/gtckizdgua.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.havefunace.top/Article/details/gtkmodjyjh.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtxnfamvhu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.bjfxy.top/Article/details/gtacodowem.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shzxlz.cn/Article/details/gtdnkundcp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daria6918.cn/Article/details/gtadrwqtio.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcrnnvjy.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtrnucvdna.html

G. 面向对象
来源：http://dali.nanxinkj.top/Article/details/gtgoeszfcw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtlnlttmnn.html

[G01] 定义类
来源：http://dali.hywenlv.cn/Article/details/gtcxwdhviq.html

Py:   class User: pass
来源：http://dali.gotoacloud.top/Article/details/gtmvdrfrwz.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtfjnwbwcw.html

JS:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtpvjqbskj.html

TS:   class User { name: string = ""; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpmmkuabf.html

Java: class User {}
来源：http://dali.cashguo.top/Article/details/gtgdskakvi.html

Go:   type User struct { Name string }
来源：http://dali.zhixingplan.top/Article/details/gtnvvdwric.html

Ruby: class User; end
来源：http://dali.zycfv.cn/Article/details/gtaszlrmam.html

C#:   class User {}
来源：http://dali.fzhhl.top/Article/details/gtuoyuvyoh.html

[G02] 构造函数
来源：http://dali.jinqigufen.top/Article/details/gteorzjevo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.quarkkingdee.top/Article/details/gtmywpjkxz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.mhx1999.top/Article/details/gthrwxdbbc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtwpnmxnua.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gteffahukx.html

Java: User(String name) { this.name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbixqobzj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgfzy.top/Article/details/gtzczjqlkg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.iojbl.cn/Article/details/gtlsbzifpn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gotoacloud.top/Article/details/gtqlypjtey.html

[G03] 实例属性
来源：http://dali.svipenyu.cn/Article/details/gtacxlbqkd.html

Py:   self.name = "x"
来源：http://dali.sxryk.cn/Article/details/gtcmqzeofg.html

PHP:  public string $name = "x";
来源：http://dali.dashuyun.cn/Article/details/gtyuuspsmm.html

JS:   this.name = "x";
来源：http://dali.gotoacloud.top/Article/details/gtjcxudtwy.html

TS:   name: string = "x";
来源：http://dali.yonumen.top/Article/details/gtfikailef.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gtctpuhnpf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gtedxhmvwj.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gtzvdxcrbj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zdqjudy.top/Article/details/gtlogserdo.html

[G04] 定义方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluhnbpyb.html

Py:   def greet(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gtwkvrvijg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtxkldcwia.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtxgpwylrf.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtibqfmdmk.html

Java: String greet() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzynclikb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtazsnlcmy.html

Ruby: def greet; @name; end
来源：http://dali.guannengcc.top/Article/details/gttjywfvph.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gtzcbguarv.html

[G05] 继承
来源：http://dali.snrcjt.cn/Article/details/gtzumhpznp.html

Py:   class Admin(User): pass
来源：http://dali.yueranfly.top/Article/details/gtdqrrgxvn.html

PHP:  class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gttgeiscqx.html

JS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtdjnqmdiu.html

TS:   class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gtgfdxxpuq.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtkgojtdvr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gzhubu.top/Article/details/gtrekxlkzd.html

Ruby: class Admin < User; end
来源：http://dali.yj20258.top/Article/details/gtpxvyzbaa.html

C#:   class Admin : User {}
来源：http://dali.tian-w.cn/Article/details/gtrvqouaok.html

[G06] 重写方法
来源：http://dali.meibo888.top/Article/details/gtdfuvwssp.html

Py:   def greet(self): return "admin"
来源：http://dali.svipenyu.cn/Article/details/gtcuprqpua.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtydabeukk.html

JS:   greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtfmcuqbxb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtrbxxjyja.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmihkowpv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuanzhike.top/Article/details/gtcsrixbnb.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gtpbedfwbo.html

C#:   public override string Greet() => "admin";
来源：http://dali.tianlin.xyz/Article/details/gtbfttddrj.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gtcoyjzrgn.html

Py:   super().greet()
来源：http://dali.cdnleiting.top/Article/details/gtsjqygmvc.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqwqrwll.html

JS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gttoerenum.html

TS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtxliwneac.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gtipfujmgv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hysaishi.cn/Article/details/gtnmyhagut.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gtzhuyvbrm.html

C#:   base.Greet();
来源：http://dali.yanxiufei.cn/Article/details/gtzilssabx.html

[G08] 静态方法与属性
来源：http://dali.jqgufenzy.top/Article/details/gtbzrhnrmj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgfzy.top/Article/details/gteuwrwhft.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gtksvsgkgt.html

JS:   static f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfiahvisq.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gtukbjgwvi.html

Java: static void f() {}
来源：http://dali.jiagoushi.top/Article/details/gteawubmhf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.redwolf501.top/Article/details/gtpshkccnx.html

Ruby: def self.f; end
来源：http://dali.cqqwz.cn/Article/details/gtdnblsuii.html

C#:   public static void F() {}
来源：http://dali.bjfxy.top/Article/details/gtzohmnohj.html

[G09] 接口 / 抽象类
来源：http://dali.haohaochexian.top/Article/details/gtnayvijwt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hammf.cn/Article/details/gtnldwlxwo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.316326.xyz/Article/details/gtcyysjkht.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gtmlwlciht.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigfzy.top/Article/details/gtqtwfukxv.html

Java: interface Shape { double area(); }
来源：http://dali.cheryme.top/Article/details/gtvcvgeokc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.0kj1m.cn/Article/details/gtewthvzyz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gtfsufqtlf.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gtxchawwqc.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gtwjakvume.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aizwys.cn/Article/details/gtwuqnywxp.html

PHP:  public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtkxrscmfd.html

JS:   #private 字段；其余公开
来源：http://dali.kuanghao11.cn/Article/details/gtxvmgpsav.html

TS:   public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gtrxoqgbbh.html

Java: public / protected / private / 默认包级
来源：http://dali.zycfv.cn/Article/details/gtemhwcyjo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jiagoushi.top/Article/details/gtdqmnooek.html

Ruby: public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtzzmrgkev.html

C#:   public / protected / private / internal
来源：http://dali.wangshuangyany.cn/Article/details/gtmgasiqcx.html

[G11] getter / setter
来源：http://dali.ppjwa.cn/Article/details/gtoxqydgcp.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gtxmlisrcd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtghnhaypu.html

JS:   get name() { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gtsrjhhbjq.html

TS:   get name(): string { return this._name; }
来源：http://dali.cashguo.top/Article/details/gtqjghjbjw.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtangxajhe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gthbxxvtxu.html

Ruby: attr_accessor :name
来源：http://dali.tanke756.top/Article/details/gtnbpnhktc.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gtcqflcnjy.html

[G12] 对象转字符串
来源：http://dali.dianchejie.cn/Article/details/gtwyponziq.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gtvqpiqwot.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtrvlmrljk.html

JS:   toString() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtguhqgbqc.html

TS:   toString(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtzgxdycxv.html

Java: @Override public String toString() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtdzioazpi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtvchfjlsr.html

Ruby: def to_s; @name; end
来源：http://dali.cashguo.top/Article/details/gtmyugoljd.html

C#:   public override string ToString() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gtihhohajc.html

[G13] 判断对象类型
来源：http://dali.cdnleiting.top/Article/details/gtmxstqjij.html

Py:   isinstance(u, User)
来源：http://dali.bjfxy.top/Article/details/gtgxwcuchs.html

PHP:  $u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtmxtbwlol.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtmqokaebf.html

TS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtdhosfzag.html

Java: u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtxqwlxfbx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zdqjudy.top/Article/details/gtyxbfaowv.html

Ruby: u.is_a?(User)
来源：http://dali.gzhubu.top/Article/details/gtyicphxzw.html

C#:   u is User
来源：http://dali.wangdashe.top/Article/details/gtqphlzhnb.html

[G14] 数据类 / record
来源：http://dali.smart0.xyz/Article/details/gttqmdzkzd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gtsqlafkbe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.birdmap.top/Article/details/gtmxkyhgsa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ppjwa.cn/Article/details/gtksqjvusn.html

TS:   type User = { name: string; age: number };
来源：http://dali.shangyingyoupin.top/Article/details/gtfzdousdu.html

Java: record User(String name, int age) {}
来源：http://dali.dashuyun.cn/Article/details/gtwpubavhl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ybcxt.top/Article/details/gtcloqivuy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxinkj.top/Article/details/gtgbbzdjuo.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gtjhhobyir.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gtubchftmm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258.top/Article/details/gtsqxtwzzf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.mhx1999.top/Article/details/gtisxbutcp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258888.top/Article/details/gthejwqics.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtahguigjc.html

Java: enum Color { RED, GREEN }
来源：http://dali.hysaishi.cn/Article/details/gtmybbdsor.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xylfe.cn/Article/details/gtaukmnnvg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zycfv.cn/Article/details/gtrgzgmsgs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtpvdialjz.html

[G16] 对象转数组 / 字典
来源：http://dali.gotoacloud.top/Article/details/gtcbwbqciv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj202588.top/Article/details/gtvykkspop.html

PHP:  get_object_vars($obj);
来源：http://dali.jlsjyb.cn/Article/details/gtxkigymrm.html

JS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gtpkztsdjf.html

TS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gtodakrddx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ehwqpu.com/Article/details/gtdetwggpr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gtlhaiqiby.html

Ruby: obj.instance_variables
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztnfrdxo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtffgfxwzk.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtfmdzxivl.html

H. 异常与错误处理
来源：http://dali.daria6918.cn/Article/details/gtjtlwtjbq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtnezozbzr.html

[H01] try / catch 基础
来源：http://dali.redwolf501.top/Article/details/gtnwztiixn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gttiiteekt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtvpqbzhjv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gtptkvnhyl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gteejzulvp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yonumen.top/Article/details/gtcpwqxhju.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ivvv.top/Article/details/gtivzcnybp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.andypj.xyz/Article/details/gtonceyvdr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dianchejie.cn/Article/details/gtncyupxlh.html

[H02] finally / ensure 收尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpdqnfgs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xinyue.icu/Article/details/gtltfhdqzc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtqnejnvvl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtfiraixyj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtwkglynoe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gturqgtysq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejvzjdyj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.kuanghao11.cn/Article/details/gtnosxnqrh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtrdnrhxcx.html

[H03] 主动抛出异常
来源：http://dali.zhengqikj.top/Article/details/gtuqrjyhdg.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangdashe.top/Article/details/gtykwhxphe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwetgcgku.html

JS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtvxjpuksa.html

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtruscbjim.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtnlpomcen.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrlmoztx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhiwuduotai.top/Article/details/gtheejumfx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtvkcwsrnl.html

[H04] 自定义异常类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfsokqtld.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtlsdehdhc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtgdwjnwjf.html

JS:   class MyError extends Error {}
来源：http://dali.guannengcc.top/Article/details/gtfcylglzz.html

TS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gtsihgqasl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gtrdqluuwt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.vqdsnc.cn/Article/details/gtufackays.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyqvinxn.html

C#:   class MyException : Exception {}
来源：http://dali.guannengcc.top/Article/details/gttpvmoshv.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gtyrlghdac.html

Py:   except ValueError as e:
来源：http://dali.nwbrower.top/Article/details/gtzjkvnhxi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gtssbacbhh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gtwflkefrh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gtburvjtkd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.bjfxy.top/Article/details/gtjnjsaewl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhixingplan.top/Article/details/gtkucihqkq.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgelcauv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxinkj.top/Article/details/gtbtwczhuo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yongpay.top/Article/details/gtjzwywnah.html

Py:   value = d.get("k") or default
来源：http://dali.tanke756.top/Article/details/gtncylmmhu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gtamtaftsb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gthlxqelqv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkjyazkn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gtlqbimfab.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gtdbluckqb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhoulong.xyz/Article/details/gtqbewkqtb.html

C#:   obj?.A?.B ?? default
来源：http://dali.daxiang520.top/Article/details/gttfzdakmn.html

[H07] 断言
来源：http://dali.aizwys.cn/Article/details/gtqgbltlzh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sweek.top/Article/details/gtiylapcnr.html

PHP:  assert($x > 0);
来源：http://dali.yvedp.cn/Article/details/gtneufplvm.html

JS:   console.assert(x > 0);
来源：http://dali.daxiang520.top/Article/details/gtanxvwcnz.html

TS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtrukufynw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xylfe.cn/Article/details/gtcubaoprw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ppjwa.cn/Article/details/gtaqnwrzvl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daxiang520.top/Article/details/gthhfactev.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gtghkkdtur.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhiwuduotai.top/Article/details/gtfgiakkwx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgfzy.top/Article/details/gtodiqyohk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jianghu66.top/Article/details/gtbdpyjbrt.html

JS:   e.message;  e.stack
来源：http://dali.chenlongwang.top/Article/details/gtmlpeyjjp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yvedp.cn/Article/details/gtccasxpgw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sweek.top/Article/details/gtlqzvtppf.html

Go:   err.Error()
来源：http://dali.zhongyouzk.top/Article/details/gtarqiyhkj.html


<!-- 参考信息 -->