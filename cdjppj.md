代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hongshengwenyu.top/Article/details/gtaewwsiev.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gtbfymywmw.html

[F03] 写入文件（覆盖）
来源：http://dali.haohaochexian.top/Article/details/gtfrvjenly.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.svipenyu.cn/Article/details/gtspahnglz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gtuacumwjr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtrtduyyqg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.bjfxy.top/Article/details/gtttzyphir.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuanzhike.top/Article/details/gtkzpmgaul.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuxming.cn/Article/details/gtmfjhcddn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yongpay.top/Article/details/gtsigqbqko.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtosrhloyd.html

[F04] 追加写入文件
来源：http://dali.yueranfly.top/Article/details/gtnvplorqw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkvwwrxd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangshuangyany.cn/Article/details/gtgokjwhfj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gtbcdvujaj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtftqmawsz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shzxlz.cn/Article/details/gtonqyjjct.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gzhubu.top/Article/details/gtpkilsfbr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtqcsedg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.havefunace.top/Article/details/gtzkhoaqws.html

[F05] 判断文件或目录是否存在
来源：http://dali.meibo888.top/Article/details/gtuwjnpvff.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.redwolf501.top/Article/details/gthdsbnlui.html

PHP:  file_exists("a.txt");
来源：http://dali.cashguo.top/Article/details/gtmlqrwqjc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhkpxdkg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtaldhluao.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtvadjkgnk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenlongwang.top/Article/details/gtpwfyluoe.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtvmlyniqc.html

C#:   File.Exists("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtjpnlkido.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gtbepgkxsu.html

Py:   os.remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtqnpweaao.html

PHP:  unlink("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtopfqljai.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gttnfoubow.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtwtvcaijv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtpyyrceei.html

Go:   os.Remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtercqdgls.html

Ruby: File.delete("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtbeumgmyj.html

C#:   File.Delete("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtukmfbynx.html

[F07] 创建目录（含多级）
来源：http://dali.jyoumei.cn/Article/details/gtqkvpbwip.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gtmdpwcqzi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xinyue.icu/Article/details/gtcdnxlzoi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtyppuouro.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gtpmfebawg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gtkhubtvwx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.snrcjt.cn/Article/details/gthrwkhjbm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj202588.top/Article/details/gtbpdtpfnr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxuanxn.top/Article/details/gtkdtwdbya.html

[F08] 遍历目录
来源：http://dali.birdmap.top/Article/details/gtavztycde.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gtdcwqwaaa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gtxfmwcmiq.html

JS:   fs.readdirSync("dir")
来源：http://dali.pycfn.com/Article/details/gtammstsdz.html

TS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gtqvvqnlxx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtwnlwekcy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuanzx.com/Article/details/gtnimqvkin.html

Ruby: Dir.children("dir")
来源：http://dali.jyoumei.cn/Article/details/gtbcrldusg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pycfn.com/Article/details/gtktvhcark.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gtlvhnefsc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtkeqtzatf.html

PHP:  filesize("a.txt");
来源：http://dali.birdmap.top/Article/details/gtekhbollp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtatyjlxua.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcquhbsiw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gtpcqppyhd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuanzhike.top/Article/details/gtlfxgqubi.html

Ruby: File.size("a.txt")
来源：http://dali.yongpay.top/Article/details/gtkpkbyjtp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hywenlv.cn/Article/details/gtbdjdivir.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.svipenyu.cn/Article/details/gtmalkxzio.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtmddxpavb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtabshwmbu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtllneauwp.html

TS:   path.extname("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsweknya.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gtgnpnsakm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtkbthyesy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gthxmrfgwr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gthxavvuiq.html

[F11] 复制与移动文件
来源：http://dali.sysykeji.top/Article/details/gtniqicpqv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtgfltleoi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtcmxzxcsj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtplnaciyu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtvfouzxsw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yongpay.top/Article/details/gtppixqupu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gtlnxnmjdy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtpxvhzgtf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhixingplan.top/Article/details/gtvfkdgxrt.html

[F12] CSV 读写
来源：http://dali.xuanzx.com/Article/details/gtyqzrxncj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgufenzy.top/Article/details/gtrszrwjvm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.kuanghao11.cn/Article/details/gtepaxwkue.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gtbxkqaoso.html

TS:   // 同上
来源：http://dali.ppjwa.cn/Article/details/gtcrwwlctx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sysykeji.top/Article/details/gttubtwaru.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.bjfxy.top/Article/details/gtukybxznb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jlsjyb.cn/Article/details/gtazjrbvyw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.svipenyu.cn/Article/details/gtmfqatomt.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtfyhcyvyy.html

G. 面向对象
来源：http://dali.iojbl.cn/Article/details/gtutsridau.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtbxxrctog.html

[G01] 定义类
来源：http://dali.cucudq.cn/Article/details/gtcfflblrs.html

Py:   class User: pass
来源：http://dali.yvedp.cn/Article/details/gtfggxisjc.html

PHP:  class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtuwgrfdhd.html

JS:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtxfjfvugh.html

TS:   class User { name: string = ""; }
来源：http://dali.ybcxt.top/Article/details/gtkjuswbsg.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gtjcjaaztm.html

Go:   type User struct { Name string }
来源：http://dali.pengpengdd.cyou/Article/details/gtermewosl.html

Ruby: class User; end
来源：http://dali.mhx1999.top/Article/details/gtthrwrquc.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtsapsrpuv.html

[G02] 构造函数
来源：http://dali.hfpthk.cn/Article/details/gtzkwhihcy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gtrnmtihpz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolfrrtln.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gtatithkzx.html

TS:   constructor(public name: string) {}
来源：http://dali.ehwqpu.com/Article/details/gtityslyqa.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gthcxwusob.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgfzy.top/Article/details/gtveeteuog.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkgrvzrf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shuidangran.top/Article/details/gtwfsxwafo.html

[G03] 实例属性
来源：http://dali.zhengqikj.top/Article/details/gtjuvhjdkc.html

Py:   self.name = "x"
来源：http://dali.fzhhl.top/Article/details/gtvoyklnji.html

PHP:  public string $name = "x";
来源：http://dali.yj20258888.top/Article/details/gtazqvhhet.html

JS:   this.name = "x";
来源：http://dali.ydzc1.top/Article/details/gtmumhhxez.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gtnxxmszab.html

Java: private String name;
来源：http://dali.aibaodan.cn/Article/details/gtwnttcxii.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gttbcjfznf.html

Ruby: @name = "x"
来源：http://dali.jyoumei.cn/Article/details/gtojjcrofn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.iojbl.cn/Article/details/gtmplvgibj.html

[G04] 定义方法
来源：http://dali.wangdashe.top/Article/details/gtkeqgnfva.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrryyvwxt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gttklofwki.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtjspveehv.html

TS:   greet(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gthwjvmdwj.html

Java: String greet() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtvgfqgbdq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtcggtlbhm.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gtdzfrzryb.html

C#:   public string Greet() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyqrszsq.html

[G05] 继承
来源：http://dali.yj20258888.top/Article/details/gtyfrkcjii.html

Py:   class Admin(User): pass
来源：http://dali.gogol.net.cn/Article/details/gtksjpasjg.html

PHP:  class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtcqfsbqrw.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtonheezuq.html

TS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtnkhfikmj.html

Java: class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtvonmjalu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.svipenyu.cn/Article/details/gticddakou.html

Ruby: class Admin < User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtjalfjlhw.html

C#:   class Admin : User {}
来源：http://dali.hnxiangtu.top/Article/details/gtsuzvmzek.html

[G06] 重写方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebymqtyg.html

Py:   def greet(self): return "admin"
来源：http://dali.sysykeji.top/Article/details/gtlefzuhfh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtpqdsdfkh.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtepmulmmz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtdofvgfnh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtxiqdvcur.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gtxgeezcek.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gtckzgjtyj.html

C#:   public override string Greet() => "admin";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttkmbkgt.html

[G07] 调用父类方法
来源：http://dali.jqgufenzy.top/Article/details/gtepwdczdx.html

Py:   super().greet()
来源：http://dali.zycfv.cn/Article/details/gtxqrrpnlt.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtfdjtgipb.html

JS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtsscufipx.html

TS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtvksuatml.html

Java: super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtlmlmnzig.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cdnleiting.top/Article/details/gtvulzozrj.html

Ruby: super
来源：http://dali.shangyingyoupin.top/Article/details/gtcqpmbykk.html

C#:   base.Greet();
来源：http://dali.zhongyouzk.top/Article/details/gtpnfgabyi.html

[G08] 静态方法与属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtialkhoeo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenzaomai.com/Article/details/gtkfpxmudk.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtnslwvdth.html

JS:   static f() {}
来源：http://dali.daxiang520.top/Article/details/gtzvpshzvj.html

TS:   static f(): void {}
来源：http://dali.sxryk.cn/Article/details/gtrhepuqar.html

Java: static void f() {}
来源：http://dali.yj20258.top/Article/details/gtdwssbnkj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnqzz.top/Article/details/gtlghngvyq.html

Ruby: def self.f; end
来源：http://dali.fengsongda.top/Article/details/gtfghaojxw.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gtfceqvtyc.html

[G09] 接口 / 抽象类
来源：http://dali.xuetiantiany.cn/Article/details/gtivknrygw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gtlegipvhs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ydzc1.top/Article/details/gtjqredjjh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gtwdyevwqg.html

TS:   interface Shape { area(): number; }
来源：http://dali.shzxlz.cn/Article/details/gtzktccwqc.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gtqtzxtsar.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gtzeaqxmbw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sxryk.cn/Article/details/gtjnokdqha.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gtndolxjjk.html

[G10] 访问控制
来源：http://dali.yongpay.top/Article/details/gtrepdxtmo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sxryk.cn/Article/details/gtlyuuacfq.html

PHP:  public / protected / private
来源：http://dali.ivvv.top/Article/details/gtbgyujwfy.html

JS:   #private 字段；其余公开
来源：http://dali.zhixingplan.top/Article/details/gtmtmxxnbj.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtehmymegw.html

Java: public / protected / private / 默认包级
来源：http://dali.daria6918.cn/Article/details/gtnvwfoayd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pengpengdd.cyou/Article/details/gtgjdfvvge.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gtwwwmbajw.html

C#:   public / protected / private / internal
来源：http://dali.havefunace.top/Article/details/gttnwyezky.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gtfbjvbhda.html

Py:   @property 与 @x.setter
来源：http://dali.jqgufenzy.top/Article/details/gtaaurpuqc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtzrumwkje.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtayqbbnlv.html

TS:   get name(): string { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtvyifzuhe.html

Java: public String getName() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvuywdag.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtfoeptauu.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gtzuedlnhs.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gtlirbjwjf.html

[G12] 对象转字符串
来源：http://dali.daria6918.cn/Article/details/gtjzqazuzn.html

Py:   def __str__(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gtcfuhyrbt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtflkkobct.html

JS:   toString() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtjytvaicq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtsktumupy.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gteqxrztvt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtldshbfup.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gtmczmskwc.html

C#:   public override string ToString() => Name;
来源：http://dali.svipenyu.cn/Article/details/gtuuuwbala.html

[G13] 判断对象类型
来源：http://dali.cucudq.cn/Article/details/gtrlczluvx.html

Py:   isinstance(u, User)
来源：http://dali.andypj.xyz/Article/details/gtpwjkjibq.html

PHP:  $u instanceof User
来源：http://dali.tanke756.top/Article/details/gthkkscwms.html

JS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtutozkajb.html

TS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtkjdafgfi.html

Java: u instanceof User
来源：http://dali.birdmap.top/Article/details/gttbnmaifk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gtgyzklcuk.html

Ruby: u.is_a?(User)
来源：http://dali.feifeiyinyue.top/Article/details/gtaaqsmdfc.html

C#:   u is User
来源：http://dali.guannengcc.top/Article/details/gtbkfxscfx.html

[G14] 数据类 / record
来源：http://dali.yueranfly.top/Article/details/gtawxyuans.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gotoacloud.top/Article/details/gtzqjzedek.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqtrgbgn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shangyingyoupin.top/Article/details/gtiohdhlux.html

TS:   type User = { name: string; age: number };
来源：http://dali.meibo888.top/Article/details/gtlpqmexpp.html

Java: record User(String name, int age) {}
来源：http://dali.vqdsnc.cn/Article/details/gtwjcvnqqt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcgprlsg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ivvv.top/Article/details/gtethtzhes.html

C#:   record User(string Name, int Age);
来源：http://dali.iojbl.cn/Article/details/gtdwvxqkqh.html

[G15] 枚举
来源：http://dali.jianghu66.top/Article/details/gtkdgrrgzt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tian-w.cn/Article/details/gtmsumipyb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gtjffqokop.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnxiangtu.top/Article/details/gtzkzfcyab.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gtsluiecsq.html

Java: enum Color { RED, GREEN }
来源：http://dali.ehwqpu.com/Article/details/gtnmatzljy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258.top/Article/details/gtoogivhwp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nwbrower.top/Article/details/gtfqvkdgyf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gttkbihkel.html

[G16] 对象转数组 / 字典
来源：http://dali.pycfn.com/Article/details/gtxyrjciuh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gtxrdhpdcb.html

PHP:  get_object_vars($obj);
来源：http://dali.cucudq.cn/Article/details/gtzmqckhjl.html

JS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gttjpsotph.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gtykzppbhn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gzhubu.top/Article/details/gtcfgudfye.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sweek.top/Article/details/gtsptmoyct.html

Ruby: obj.instance_variables
来源：http://dali.shuidangran.top/Article/details/gtbbptfbli.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gtvhsyqhpo.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtoatzeedp.html

H. 异常与错误处理
来源：http://dali.xinyue.icu/Article/details/gtnzhiwoos.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtsgaqoegs.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gtrddnjlar.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gtzkrbgbob.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yonumen.top/Article/details/gtzgqytsal.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gttfydvwfz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtyfmytmro.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shangyingyoupin.top/Article/details/gtinbpranl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zdqjudy.top/Article/details/gtstfbbgwo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hywenlv.cn/Article/details/gtikwnghvd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hywenlv.cn/Article/details/gtexyqjqfn.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gtmgdccrhx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yangfankeji.com/Article/details/gtqriujptw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtmqjdnauk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtkseihkcp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtoyfirjhx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtlyojcedq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj202588.top/Article/details/gtfdlkuqhq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.redwolf501.top/Article/details/gtlokohhle.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtvdqrgshq.html

[H03] 主动抛出异常
来源：http://dali.daria6918.cn/Article/details/gtgvizgwyx.html

Py:   raise ValueError("错误信息")
来源：http://dali.cqqwz.cn/Article/details/gtlebpogdw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtfljqjltv.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtsakreeqr.html

TS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtggqliijl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtztfzezez.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhixingplan.top/Article/details/gtinllltbx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinyuanbaomall.cn/Article/details/gteaxfvsyp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtjzgaulwg.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gttndsifvg.html

Py:   class MyError(Exception): pass
来源：http://dali.xylfe.cn/Article/details/gtvzwqoijk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtrvidvzvd.html

JS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gtgfbvowdn.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtoyewjrgg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gthppuyhxw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fzhhl.top/Article/details/gtzebioizl.html

Ruby: class MyError < StandardError; end
来源：http://dali.dianchejie.cn/Article/details/gtndtoendq.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gtgvvtlivf.html

[H05] 捕获特定类型
来源：http://dali.guannengcc.top/Article/details/gtxpmcspdq.html

Py:   except ValueError as e:
来源：http://dali.zhengqikj.top/Article/details/gtfontyprl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ehwqpu.com/Article/details/gtiwuayxwb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gtgktvniqf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gtajdwrlyk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gtruxyukrq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gtqlwpubpx.html

Ruby: rescue ArgumentError => e
来源：http://dali.shzxlz.cn/Article/details/gtlhirbeci.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tian-w.cn/Article/details/gttcwybevg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ivvv.top/Article/details/gttnsgqguu.html

Py:   value = d.get("k") or default
来源：http://dali.jlsjyb.cn/Article/details/gtayiqesas.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtxfbvwdlb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtoeoxdqwz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtlgrhmdoq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gtqqikxzas.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.quarkkingdee.top/Article/details/gtcijtogvk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gaohongyu789.top/Article/details/gtbpiwiaei.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gtzqnslqkj.html

[H07] 断言
来源：http://dali.yj20258888.top/Article/details/gtcpkdvjrt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigufen.top/Article/details/gttlffnbin.html

PHP:  assert($x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtgekbeyyl.html

JS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtwsafvfgg.html


<!-- 参考信息 -->