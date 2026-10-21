代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkjsmuzq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258888.top/Article/details/gtpzydsmze.html

[F03] 写入文件（覆盖）
来源：http://dali.yueranfly.top/Article/details/gtuiduihdc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ivvv.top/Article/details/gtfkdtirba.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gtsacqtndb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtuffewqxj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtnuklmqfq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sysykeji.top/Article/details/gtpoqzihqj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gtsmzednrk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhijiandao.cn/Article/details/gtsvpjrnbg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtepsxbays.html

[F04] 追加写入文件
来源：http://dali.yangfankeji.com/Article/details/gtgngvkqhj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hywenlv.cn/Article/details/gtdobkhrvh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daxiang520.top/Article/details/gtfllzsqei.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gtwgdzxgdf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtxcqhtkrv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj202588.top/Article/details/gtfsjxnqst.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yvedp.cn/Article/details/gtibjsmyha.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfizuhvbe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxinkj.top/Article/details/gtelnywfgh.html

[F05] 判断文件或目录是否存在
来源：http://dali.hammf.cn/Article/details/gtggmxlpfa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.kuanghao11.cn/Article/details/gtrthggdxe.html

PHP:  file_exists("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtlxtjjpky.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtjvixudly.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtuggfassc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtwzjuvefx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgufenzy.top/Article/details/gtpkgxmvwo.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtgkkmhycl.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gtnvymsmgn.html

[F06] 删除文件
来源：http://dali.chenzaomai.com/Article/details/gtghhelnwv.html

Py:   os.remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtaterodrg.html

PHP:  unlink("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtvlthdjvt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtplsdpisl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtlhoyzklb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gttbiuyigh.html

Go:   os.Remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtatjpgkvp.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtrjxkeniq.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gthbxojcli.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gttpeyygog.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gtpcyrhrxc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fzhhl.top/Article/details/gtaovrqdup.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnejgcyl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gtlpekfnog.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xinyue.icu/Article/details/gtvfvjqygm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xinyue.icu/Article/details/gthsbolxzx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.snrcjt.cn/Article/details/gtnyacmvlb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gzhubu.top/Article/details/gtwhwnzgts.html

[F08] 遍历目录
来源：http://dali.yuanzhike.top/Article/details/gtcjpmvrsd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gtsiohdtro.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gthcvotkyv.html

JS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gtohoatvux.html

TS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gteftnyubx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gtcemrivlf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tianlin.xyz/Article/details/gtptlnhxey.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gtaaemhhyv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangdashe.top/Article/details/gtrwjsgnep.html

[F09] 获取文件大小
来源：http://dali.zycfv.cn/Article/details/gtpnbgiwbz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtcnnnoamz.html

PHP:  filesize("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtluhvnfdb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gtsiuyfhhe.html

TS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gtdukoirxo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtaurxuinf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258.top/Article/details/gtkkhwbjsy.html

Ruby: File.size("a.txt")
来源：http://dali.yongpay.top/Article/details/gttbgovkpi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.haohaochexian.top/Article/details/gtdaxjebwd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pycfn.com/Article/details/gtpuqrrktn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtcyzbvwew.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtzpisxyem.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtmzytwfck.html

TS:   path.extname("a.txt")
来源：http://dali.havefunace.top/Article/details/gtrxexvjqi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuetiantiany.cn/Article/details/gttlhkvvbc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtvwjcurzm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtpprlorww.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtktfvfgax.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gtvtsaqoiy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gteecaxluy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtygpfnach.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtdxypaxya.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtmeappqrc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuanzx.com/Article/details/gtptlrfvug.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenzaomai.com/Article/details/gttmjdzlwm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtmrgzligt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttufysgnm.html

[F12] CSV 读写
来源：http://dali.ppjwa.cn/Article/details/gtyjxhaysr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xylfe.cn/Article/details/gtydtyffwp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fengsongda.top/Article/details/gtzuzkjenh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.andypj.xyz/Article/details/gtdlejfgjt.html

TS:   // 同上
来源：http://dali.chenzaomai.com/Article/details/gtsoovanhd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cheryme.top/Article/details/gtsbjxxunu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sysykeji.top/Article/details/gtzdlpqyeu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxinkj.top/Article/details/gtjtnrhxqm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gtyojcmxub.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtwjxgosha.html

G. 面向对象
来源：http://dali.cashguo.top/Article/details/gtxhigcxvb.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmsjuozzy.html

[G01] 定义类
来源：http://dali.chenlongwang.top/Article/details/gtcrpfpttz.html

Py:   class User: pass
来源：http://dali.sweek.top/Article/details/gtckesxgvu.html

PHP:  class User {}
来源：http://dali.sysykeji.top/Article/details/gtkjjheagt.html

JS:   class User {}
来源：http://dali.mhx1999.top/Article/details/gtkjbrydgq.html

TS:   class User { name: string = ""; }
来源：http://dali.sxryk.cn/Article/details/gtuiaexsad.html

Java: class User {}
来源：http://dali.yj20258888.top/Article/details/gtvzehrqjv.html

Go:   type User struct { Name string }
来源：http://dali.yanxiufei.cn/Article/details/gtrkbrybtw.html

Ruby: class User; end
来源：http://dali.jyoumei.cn/Article/details/gtfzeniyjt.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtesaydbwm.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gtcdptbhcw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zycfv.cn/Article/details/gthkhrwgfz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gtllvlmqgt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtvhntyibq.html

TS:   constructor(public name: string) {}
来源：http://dali.shzxlz.cn/Article/details/gtwmondlej.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtqhzmsixt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gtndbfvinz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gtwjgnyfdt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtamzvgcsq.html

[G03] 实例属性
来源：http://dali.chenjidiqi.icu/Article/details/gtaolcqhcx.html

Py:   self.name = "x"
来源：http://dali.aizwys.cn/Article/details/gtcuqqgioy.html

PHP:  public string $name = "x";
来源：http://dali.smart0.xyz/Article/details/gtbzytqlso.html

JS:   this.name = "x";
来源：http://dali.yuanzhike.top/Article/details/gtqoseszel.html

TS:   name: string = "x";
来源：http://dali.haohaochexian.top/Article/details/gtsvlrnvxl.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gtpypkbbuu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.feifeiyinyue.top/Article/details/gttipsozhz.html

Ruby: @name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gtpzcvrusa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gzhubu.top/Article/details/gtnjgtadqf.html

[G04] 定义方法
来源：http://dali.gaohongyu789.top/Article/details/gtngsjfwun.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gtluuzbuib.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtcjdptckl.html

JS:   greet() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtuosopyhh.html

TS:   greet(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtzcbkjrxs.html

Java: String greet() { return name; }
来源：http://dali.iojbl.cn/Article/details/gtyksgykiu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtjvobleyc.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gtlbowahek.html

C#:   public string Greet() => Name;
来源：http://dali.yj202588.top/Article/details/gtcjydxiam.html

[G05] 继承
来源：http://dali.tian-w.cn/Article/details/gtaahfybtj.html

Py:   class Admin(User): pass
来源：http://dali.chenjidiqi.icu/Article/details/gtzysmopaw.html

PHP:  class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtkwuyzxsr.html

JS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtbjzcjzju.html

TS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtaexvyapn.html

Java: class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtatysbcmi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nwbrower.top/Article/details/gtrobrdeup.html

Ruby: class Admin < User; end
来源：http://dali.svipenyu.cn/Article/details/gtxdpclfhz.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmvfvbjx.html

[G06] 重写方法
来源：http://dali.andypj.xyz/Article/details/gtqsxrfpgh.html

Py:   def greet(self): return "admin"
来源：http://dali.andypj.xyz/Article/details/gtmhkdzceb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtuqfolypb.html

JS:   greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtjjsnocao.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtyglbfybf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtaeeglonx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gtiquzjszn.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gthmfzjfcb.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenjidiqi.icu/Article/details/gtxyznpoys.html

[G07] 调用父类方法
来源：http://dali.dianchejie.cn/Article/details/gtsgqoiycl.html

Py:   super().greet()
来源：http://dali.hammf.cn/Article/details/gtxoxogowt.html

PHP:  parent::greet();
来源：http://dali.xylfe.cn/Article/details/gtrgwbxuoa.html

JS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtlptitttr.html

TS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gtajvvtzcq.html

Java: super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtgbysiewl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gtfdtprqkh.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gtcvvxxkpb.html

C#:   base.Greet();
来源：http://dali.vqdsnc.cn/Article/details/gtmdshwqve.html

[G08] 静态方法与属性
来源：http://dali.yanxiufei.cn/Article/details/gtfrllwapz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cheryme.top/Article/details/gtnmcjstcw.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtbgwpcywz.html

JS:   static f() {}
来源：http://dali.nwbrower.top/Article/details/gtxbhdnwvu.html

TS:   static f(): void {}
来源：http://dali.ppjwa.cn/Article/details/gtqogzghgu.html

Java: static void f() {}
来源：http://dali.mhx1999.top/Article/details/gtbioryrns.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gzhubu.top/Article/details/gtxjsyousa.html

Ruby: def self.f; end
来源：http://dali.nanxinkj.top/Article/details/gthlxqagbg.html

C#:   public static void F() {}
来源：http://dali.guowangkeji.top/Article/details/gtgwizephg.html

[G09] 接口 / 抽象类
来源：http://dali.xylfe.cn/Article/details/gthppgnrkk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuanzx.com/Article/details/gtddgospaj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gtucxtayyc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gtsbxzynys.html

TS:   interface Shape { area(): number; }
来源：http://dali.sysykeji.top/Article/details/gttnohiejl.html

Java: interface Shape { double area(); }
来源：http://dali.xylfe.cn/Article/details/gtwwlhaekk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj202588.top/Article/details/gtpjhemmjv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zycfv.cn/Article/details/gtgdpmnbmd.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtybteldpv.html

[G10] 访问控制
来源：http://dali.cucudq.cn/Article/details/gthxopqvvr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhixingplan.top/Article/details/gtttkywkrd.html

PHP:  public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtmouvmbhi.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gtbbnxzqbm.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtzkyndffn.html

Java: public / protected / private / 默认包级
来源：http://dali.svipenyu.cn/Article/details/gtbsgxcfxi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tian-w.cn/Article/details/gtasfnfzuh.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtuzuzulbq.html

C#:   public / protected / private / internal
来源：http://dali.cqqwz.cn/Article/details/gtmesjdecr.html

[G11] getter / setter
来源：http://dali.yj202588.top/Article/details/gtquwcxsqd.html

Py:   @property 与 @x.setter
来源：http://dali.smart0.xyz/Article/details/gtnuvmbpsd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtkakpxdws.html

JS:   get name() { return this._name; }
来源：http://dali.316326.xyz/Article/details/gtsvyxlwnb.html

TS:   get name(): string { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtzyewxpjq.html

Java: public String getName() { return name; }
来源：http://dali.yj202588.top/Article/details/gtearnhjna.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtyzxoimej.html

Ruby: attr_accessor :name
来源：http://dali.xinyue.icu/Article/details/gtlxgvzqlc.html

C#:   public string Name { get; set; }
来源：http://dali.smart0.xyz/Article/details/gtqhklgpqh.html

[G12] 对象转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjmswxrj.html

Py:   def __str__(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtyqdjevyl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtnbpgonpv.html

JS:   toString() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtubumdmbe.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtfqqforbx.html

Java: @Override public String toString() { return name; }
来源：http://dali.tanke756.top/Article/details/gtvcrsmqcj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtedphrvzz.html

Ruby: def to_s; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gtyqbzijpu.html

C#:   public override string ToString() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwakkrfm.html

[G13] 判断对象类型
来源：http://dali.yj20258888.top/Article/details/gtqmkjusgp.html

Py:   isinstance(u, User)
来源：http://dali.0kj1m.cn/Article/details/gtcznqzakd.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtwwdbqfdk.html

JS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtktrbwqiu.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtmnlbihzs.html

Java: u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtjoutoojs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xinyue.icu/Article/details/gtlbjltjgo.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigufen.top/Article/details/gtwfxxekub.html

C#:   u is User
来源：http://dali.yanxiufei.cn/Article/details/gtsljijdhz.html

[G14] 数据类 / record
来源：http://dali.cqqwz.cn/Article/details/gtwmtpjcyd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cucudq.cn/Article/details/gtjhbjeasw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sufxvd.cn/Article/details/gtpvkvynmd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.iojbl.cn/Article/details/gtlgixxdho.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuetiantiany.cn/Article/details/gtjcbcyxis.html

Java: record User(String name, int age) {}
来源：http://dali.gaohongyu789.top/Article/details/gtgzwmtylx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksindliy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ppjwa.cn/Article/details/gtlvxcvkfx.html

C#:   record User(string Name, int Age);
来源：http://dali.bjfxy.top/Article/details/gtastnmdmt.html

[G15] 枚举
来源：http://dali.hywenlv.cn/Article/details/gtfmwpmdxq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fengsongda.top/Article/details/gtqznqthoz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yanxiufei.cn/Article/details/gtekqgdiph.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hongshengwenyu.top/Article/details/gtvpzvlwkf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtqcmzhfxi.html

Java: enum Color { RED, GREEN }
来源：http://dali.yueranfly.top/Article/details/gtjdxbyysf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cdnleiting.top/Article/details/gtpbqfoctx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gtamdwbyrz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtchuguvat.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gtpelxwhxh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xziqi.cn/Article/details/gtbwfxwyvt.html

PHP:  get_object_vars($obj);
来源：http://dali.guannengcc.top/Article/details/gtttktjoyf.html

JS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gtuuofbiyi.html

TS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtmhgoyjbu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yueranfly.top/Article/details/gtdwhmoeds.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yonumen.top/Article/details/gtdeqqvtij.html

Ruby: obj.instance_variables
来源：http://dali.vqdsnc.cn/Article/details/gtynbrwods.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtgyxqktyx.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxjvtwhvc.html

H. 异常与错误处理
来源：http://dali.jianghu66.top/Article/details/gtingtdfaw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gttqhjpwpp.html

[H01] try / catch 基础
来源：http://dali.haohaochexian.top/Article/details/gtrkajboxk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sufxvd.cn/Article/details/gttrdfdyrz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gtieejiscq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtikjpfgmq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtdiutenwb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhixingplan.top/Article/details/gtbhnlpbey.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.iojbl.cn/Article/details/gtesfytzap.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.quarkkingdee.top/Article/details/gttribrcws.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jyoumei.cn/Article/details/gtkicbgued.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gtvehgzntk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yangfankeji.com/Article/details/gtambjjgqv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtoixmiely.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtisjcfjfo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtsrpdgcrx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtvrdbgzzu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gtnefglxou.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuetiantiany.cn/Article/details/gtcquzhktu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtnnwtpuzf.html

[H03] 主动抛出异常
来源：http://dali.tianlin.xyz/Article/details/gtjlzycpgw.html

Py:   raise ValueError("错误信息")
来源：http://dali.bjfxy.top/Article/details/gtqpmrdvzp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtrryhbqni.html

JS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtsewqlhmk.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtojyzlgkv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtbigmtbkp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hongshengwenyu.top/Article/details/gtwujkzueh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xylfe.cn/Article/details/gtyoszpsrf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsaeypdnd.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcgynrsq.html

Py:   class MyError(Exception): pass
来源：http://dali.hongshengwenyu.top/Article/details/gtcpmtaouq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gtvdveohnr.html

JS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtqqfelrlc.html

TS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gtcjcccgvp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gtiyepqmrf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dashuyun.cn/Article/details/gtiuoqnllj.html

Ruby: class MyError < StandardError; end
来源：http://dali.9152youxi.cn/Article/details/gtqlqowwko.html

C#:   class MyException : Exception {}
来源：http://dali.meibo888.top/Article/details/gtyiksdcyd.html

[H05] 捕获特定类型
来源：http://dali.guannengcc.top/Article/details/gttkslizeh.html

Py:   except ValueError as e:
来源：http://dali.sweek.top/Article/details/gtbqgaivcp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.andypj.xyz/Article/details/gtqyukriql.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoggyqfsh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtpmuiqnyv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gthqbsptqx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gtnczqztfe.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuanzhike.top/Article/details/gtivcvnkoj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gtcgratqje.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuxming.cn/Article/details/gtbtzxxxbz.html

Py:   value = d.get("k") or default
来源：http://dali.daxiang520.top/Article/details/gtuvngenia.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gtgtcruibg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gtstktpjup.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gtybkitdux.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.iojbl.cn/Article/details/gtxlhlikcj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gtvgqtpntj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daxiang520.top/Article/details/gtjexljhqu.html

C#:   obj?.A?.B ?? default
来源：http://dali.tanke756.top/Article/details/gtbcdjueaq.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gtwzqquexs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangdashe.top/Article/details/gthqorjvyw.html

PHP:  assert($x > 0);
来源：http://dali.bjfxy.top/Article/details/gtwsxenszg.html

JS:   console.assert(x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gtrtposqns.html


<!-- 参考信息 -->