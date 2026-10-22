代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtsezabulr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtigwxliez.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gteqkzebec.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jyoumei.cn/Article/details/gtgiehpoky.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.c1oappe.top/Article/details/gtukqoafhn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ehwqpu.com/Article/details/gttxyaopyv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdffaneyn.html

[F04] 追加写入文件
来源：http://dali.hfpthk.cn/Article/details/gtqzxxcagb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpesiosqr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gtogwrvriw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtpotsogty.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtpjgiorpm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gotoacloud.top/Article/details/gtmkilfhsa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gtvqykftcp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cqqwz.cn/Article/details/gtrxtzapkr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigfzy.top/Article/details/gtggvjjywy.html

[F05] 判断文件或目录是否存在
来源：http://dali.hywenlv.cn/Article/details/gtdvkvowjq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhixingplan.top/Article/details/gtzdivvifm.html

PHP:  file_exists("a.txt");
来源：http://dali.hammf.cn/Article/details/gtwznmoakv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtunjvvoxy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtvojxbuzr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtlkzbqnjr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sxryk.cn/Article/details/gttjamwynv.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258.top/Article/details/gtokftcfha.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gthxetblln.html

[F06] 删除文件
来源：http://dali.mhx1999.top/Article/details/gtduguqjro.html

Py:   os.remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtcwtjgcuf.html

PHP:  unlink("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtjfyurpsb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtovlbxptu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcxzhseo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gttsbahwqi.html

Go:   os.Remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtwlqwzyqn.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtkuoquhrm.html

C#:   File.Delete("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtdsriinpj.html

[F07] 创建目录（含多级）
来源：http://dali.yangfankeji.com/Article/details/gtwifxofij.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gtoolkcgqr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnxiangtu.top/Article/details/gtftccxqqm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtazuolpfx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gtpdkialss.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuanzx.com/Article/details/gtleqydqol.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gthmclmfuz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gthwiptumu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jlsjyb.cn/Article/details/gtfwgngwmb.html

[F08] 遍历目录
来源：http://dali.gotoacloud.top/Article/details/gtvbblcctx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthehetojj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sweek.top/Article/details/gtwemusvey.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtjyusqizx.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtnrqeyiwb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtiexaegmw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jyoumei.cn/Article/details/gtzmxsbkij.html

Ruby: Dir.children("dir")
来源：http://dali.birdmap.top/Article/details/gtmpjzwjrd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenlongwang.top/Article/details/gtbvhuicxk.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gtogrlcwje.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtqhirizbs.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtxijhqysd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gtqcvobqwg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gtdazismjo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtznklgzfa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.pycfn.com/Article/details/gtdwmobakj.html

Ruby: File.size("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtyygsgfky.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gtidmedjzt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenjidiqi.icu/Article/details/gtpqwsolvu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtuhxftanp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tanke756.top/Article/details/gtwlrmolho.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtwwbwrvyi.html

TS:   path.extname("a.txt")
来源：http://dali.cashguo.top/Article/details/gtgpdgcznz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zdqjudy.top/Article/details/gttytiwkpa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrulakjzn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtqkdpqwpr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtzvwwlbki.html

[F11] 复制与移动文件
来源：http://dali.birdmap.top/Article/details/gtbdzgxsju.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtcyngopbl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtupyfchqk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtwskyzccg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtcaifohtb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.birdmap.top/Article/details/gtzhpuiiis.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.redwolf501.top/Article/details/gtnuubmlno.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtaptrzlpv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gtruacdnhx.html

[F12] CSV 读写
来源：http://dali.hfpthk.cn/Article/details/gtmlmsnqll.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cashguo.top/Article/details/gtwdwcczld.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuetiantiany.cn/Article/details/gthscwrfwa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zycfv.cn/Article/details/gtbuhndopy.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gtktgtbkcz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.birdmap.top/Article/details/gtpajrhgce.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258888.top/Article/details/gtcdcgkajy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hysaishi.cn/Article/details/gtvzdxhquo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cdnleiting.top/Article/details/gtprenggbk.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtwnwdxhth.html

G. 面向对象
来源：http://dali.dashuyun.cn/Article/details/gtotpmcsvs.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtsiteleaz.html

[G01] 定义类
来源：http://dali.jqgfzy.top/Article/details/gtjqnwjxqy.html

Py:   class User: pass
来源：http://dali.ybcxt.top/Article/details/gtiluvflmk.html

PHP:  class User {}
来源：http://dali.jqgfzy.top/Article/details/gtcrmcfecg.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gttujcmols.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gtcmcvdfbn.html

Java: class User {}
来源：http://dali.zhixingplan.top/Article/details/gtjozdtrud.html

Go:   type User struct { Name string }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhljyyag.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gtlxxdcdcj.html

C#:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtoxzgcsex.html

[G02] 构造函数
来源：http://dali.gzhubu.top/Article/details/gtqvizbqen.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangshuangyany.cn/Article/details/gthhtqtqwr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gtxedchnan.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtfovloucy.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gtjfrlsmxw.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtmuhlohdo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gotoacloud.top/Article/details/gthgjnxlmr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.andypj.xyz/Article/details/gtydvhjwqh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sweek.top/Article/details/gtedxqantk.html

[G03] 实例属性
来源：http://dali.yanxiufei.cn/Article/details/gtlekrfqxi.html

Py:   self.name = "x"
来源：http://dali.316326.xyz/Article/details/gtzuqdtuti.html

PHP:  public string $name = "x";
来源：http://dali.nwbrower.top/Article/details/gtevynwnaf.html

JS:   this.name = "x";
来源：http://dali.smart0.xyz/Article/details/gtgvhwqfox.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gtwgaqygsa.html

Java: private String name;
来源：http://dali.gotoacloud.top/Article/details/gthrusfadg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jlsjyb.cn/Article/details/gtovtrcwfj.html

Ruby: @name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtvokkuviv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gthjsqpxtj.html

[G04] 定义方法
来源：http://dali.fengsongda.top/Article/details/gtgxnptcmp.html

Py:   def greet(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtsgkgrave.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtuasysawx.html

JS:   greet() { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gtckwdrodz.html

TS:   greet(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtosvmgpgz.html

Java: String greet() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyicztxfc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gthblsjjrx.html

Ruby: def greet; @name; end
来源：http://dali.daxiang520.top/Article/details/gtwrinyzum.html

C#:   public string Greet() => Name;
来源：http://dali.sysykeji.top/Article/details/gtgnwgllsk.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gtmzefexdw.html

Py:   class Admin(User): pass
来源：http://dali.pycfn.com/Article/details/gtfzhgarsd.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtimxflrcf.html

JS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtvhjlptvr.html

TS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtvboscdtl.html

Java: class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtsmgdwnas.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hysaishi.cn/Article/details/gtrfdatmou.html

Ruby: class Admin < User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttccizlgx.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gttxytadvj.html

[G06] 重写方法
来源：http://dali.zhoulong.xyz/Article/details/gthpclbooy.html

Py:   def greet(self): return "admin"
来源：http://dali.yvedp.cn/Article/details/gtqcoifvpg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtaneynqin.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtstanghkj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtukjkyvqz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtwiuugtlt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gtnllnawcc.html

Ruby: def greet; "admin"; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwtgqzph.html

C#:   public override string Greet() => "admin";
来源：http://dali.9152youxi.cn/Article/details/gtxrpnifvn.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtkemqakho.html

Py:   super().greet()
来源：http://dali.tanke756.top/Article/details/gtohzwqdup.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gtxcoxbgka.html

JS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtcckyhigm.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtmqkwukes.html

Java: super.greet();
来源：http://dali.havefunace.top/Article/details/gtfqareosy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gaohongyu789.top/Article/details/gtdxoxfiac.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gtbokeauom.html

C#:   base.Greet();
来源：http://dali.jyoumei.cn/Article/details/gtmqgjnrch.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gtgygjzzvw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinghuilouyu.cn/Article/details/gtinsbubwk.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gttcttipgr.html

JS:   static f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtbizvtawn.html

TS:   static f(): void {}
来源：http://dali.ybcxt.top/Article/details/gtgqsjhira.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gtmiaapvmv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gtbiydmxdl.html

Ruby: def self.f; end
来源：http://dali.xuanzx.com/Article/details/gtlsvonhna.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gtywqzqyfh.html

[G09] 接口 / 抽象类
来源：http://dali.zhongyouzk.top/Article/details/gtuclszddv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenzaomai.com/Article/details/gtthjkhbku.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigfzy.top/Article/details/gtftogxaqm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ydzc1.top/Article/details/gtmqxbfyyq.html

TS:   interface Shape { area(): number; }
来源：http://dali.gogol.net.cn/Article/details/gtcmvhlmvr.html

Java: interface Shape { double area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtmyfrdiss.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gteyemvqtt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gtjvrdiivb.html

C#:   interface IShape { double Area(); }
来源：http://dali.gotoacloud.top/Article/details/gtpzvkozit.html

[G10] 访问控制
来源：http://dali.hammf.cn/Article/details/gtscwmcmqb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tian-w.cn/Article/details/gtkhawdzak.html

PHP:  public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtuopddfqe.html

JS:   #private 字段；其余公开
来源：http://dali.redwolf501.top/Article/details/gtrburcldu.html

TS:   public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gteqpaavnb.html

Java: public / protected / private / 默认包级
来源：http://dali.c1oappe.top/Article/details/gtualnbsjf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jyoumei.cn/Article/details/gtubhqxlsj.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtkavefspm.html

C#:   public / protected / private / internal
来源：http://dali.yuxming.cn/Article/details/gtbnudqhuc.html

[G11] getter / setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgjqycro.html

Py:   @property 与 @x.setter
来源：http://dali.sweek.top/Article/details/gtdxwexeqb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtrtpflumk.html

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtyinfunjx.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtlkogxsbp.html

Java: public String getName() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtqwcxecad.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gthbuwfziq.html

Ruby: attr_accessor :name
来源：http://dali.sxryk.cn/Article/details/gtpeqqaaxr.html

C#:   public string Name { get; set; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxbcldbnu.html

[G12] 对象转字符串
来源：http://dali.hywenlv.cn/Article/details/gttvbpfnba.html

Py:   def __str__(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gtsnkqyjjz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmkcvraj.html

JS:   toString() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtppbynljs.html

TS:   toString(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtkpukaikg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtdnbivzvg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtusmpdsvr.html

Ruby: def to_s; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gtwegqufzb.html

C#:   public override string ToString() => Name;
来源：http://dali.ivvv.top/Article/details/gtrhaswlgn.html

[G13] 判断对象类型
来源：http://dali.ybcxt.top/Article/details/gtzkejuhfv.html

Py:   isinstance(u, User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtloujjbzn.html

PHP:  $u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtnoxhckhd.html

JS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtezpbkjzx.html

TS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtostrnyba.html

Java: u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtunappufk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gtoqsgdmfp.html

Ruby: u.is_a?(User)
来源：http://dali.zdqjudy.top/Article/details/gtzlnfvbtx.html

C#:   u is User
来源：http://dali.xziqi.cn/Article/details/gtaxcqmjbz.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gtmsvvzdho.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aibaodan.cn/Article/details/gtvwropvgi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gogol.net.cn/Article/details/gtyaqwtoqr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cdnleiting.top/Article/details/gtmhirwzsj.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gtupcwbegg.html

Java: record User(String name, int age) {}
来源：http://dali.yuxming.cn/Article/details/gtqvuksdia.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gtxulmrnnd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pycfn.com/Article/details/gtudwejvhx.html

C#:   record User(string Name, int Age);
来源：http://dali.kuanghao11.cn/Article/details/gtkhgvzdpv.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gtsmdewiay.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cqqwz.cn/Article/details/gtpupposrk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.haohaochexian.top/Article/details/gtigokcucl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.iojbl.cn/Article/details/gtpmmlronz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtjtutbbqa.html

Java: enum Color { RED, GREEN }
来源：http://dali.hfpthk.cn/Article/details/gtpttfhcww.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxuanxn.top/Article/details/gtaqcjvdoa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gtiubhmmcs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtoagcvjgz.html

[G16] 对象转数组 / 字典
来源：http://dali.nwbrower.top/Article/details/gtndfyybla.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hongshengwenyu.top/Article/details/gtmntkjibg.html

PHP:  get_object_vars($obj);
来源：http://dali.0kj1m.cn/Article/details/gtwhuiiqcn.html

JS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gtgxmavqnw.html

TS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtqggitztv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hammf.cn/Article/details/gtaydgmksm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gttksjdzwx.html

Ruby: obj.instance_variables
来源：http://dali.chenzaomai.com/Article/details/gtsuaekncn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gtovyisupo.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtyfnmachw.html

H. 异常与错误处理
来源：http://dali.zhongyouzk.top/Article/details/gtkmdrritn.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtowvbljdd.html

[H01] try / catch 基础
来源：http://dali.yj202588.top/Article/details/gtxnzlxeel.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yanxiufei.cn/Article/details/gtlndqscrp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jiagoushi.top/Article/details/gtocockovq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gtpjbzqfua.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtbwyhhaeg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yvedp.cn/Article/details/gtpewqtthe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ehwqpu.com/Article/details/gtdnopnwhm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tian-w.cn/Article/details/gtfcbetxfm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.andypj.xyz/Article/details/gtigsjumkl.html

[H02] finally / ensure 收尾
来源：http://dali.andypj.xyz/Article/details/gtelzyfxeu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jiagoushi.top/Article/details/gtimylsaup.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtiuvysjwq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtlimezbzb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrgrznwz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtqpbayrzx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gtkjazsdqw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pycfn.com/Article/details/gthwkpuayl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtreirsbbq.html

[H03] 主动抛出异常
来源：http://dali.dashuyun.cn/Article/details/gtxvnkyxor.html

Py:   raise ValueError("错误信息")
来源：http://dali.dianchejie.cn/Article/details/gtlhjvrhof.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtgflwyrit.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtqcuyxgpz.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtylgcdunx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtyondrsle.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhiwuduotai.top/Article/details/gtjjlwjqgi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gtpfvhvvpv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtcrwoxcyi.html

[H04] 自定义异常类型
来源：http://dali.birdmap.top/Article/details/gtivbiffvr.html

Py:   class MyError(Exception): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtonrihzis.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gtpbxegooz.html

JS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gtlqznazri.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtqpolalcy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gtuvyeqpvk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gogol.net.cn/Article/details/gtphscpdyl.html

Ruby: class MyError < StandardError; end
来源：http://dali.ehwqpu.com/Article/details/gtcdfudpfx.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gtncdzqogs.html

[H05] 捕获特定类型
来源：http://dali.chenlongwang.top/Article/details/gtomxatdvk.html

Py:   except ValueError as e:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkitraxjs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hywenlv.cn/Article/details/gtngehztqo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gtbzlwgoje.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtflnfwdzr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gtepenmput.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.c1oappe.top/Article/details/gthorqlpde.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhongyouzk.top/Article/details/gtgqpidzbx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nwbrower.top/Article/details/gtqozzfffc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dianchejie.cn/Article/details/gtcvbtyray.html

Py:   value = d.get("k") or default
来源：http://dali.yvedp.cn/Article/details/gtfjouzdsm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.meibo888.top/Article/details/gtifrwlmua.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtpzoxdgxa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtnzvkgcco.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.9152youxi.cn/Article/details/gtvaznfsql.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenzaomai.com/Article/details/gtlajuyifu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigfzy.top/Article/details/gtcnmihnfe.html

C#:   obj?.A?.B ?? default
来源：http://dali.yvedp.cn/Article/details/gtkoynavaf.html

[H07] 断言
来源：http://dali.gogol.net.cn/Article/details/gtfpdxjuld.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sxryk.cn/Article/details/gtagyytcdh.html

PHP:  assert($x > 0);
来源：http://dali.hammf.cn/Article/details/gtwxiehgsy.html

JS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtdxarcynp.html

TS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknpycokr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ppjwa.cn/Article/details/gtmfjmvepx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zycfv.cn/Article/details/gtxdsaylfa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gotoacloud.top/Article/details/gtcwtqfdbs.html


<!-- 参考信息 -->