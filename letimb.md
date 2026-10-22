代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuanzhike.top/Article/details/gtxcrhycre.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gtiknddtvm.html

[F03] 写入文件（覆盖）
来源：http://dali.zhongyouzk.top/Article/details/gtjqrtsucg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjicmppy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gtlqaxnihl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtdxprvsep.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gtoujbtbef.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sufxvd.cn/Article/details/gtgbztuyty.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenjidiqi.icu/Article/details/gtitpnfyhs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtazhjioeo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtlkiicxhc.html

[F04] 追加写入文件
来源：http://dali.cqqwz.cn/Article/details/gthkaqtsmr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hywenlv.cn/Article/details/gtrapbgsvs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gtbkshmsha.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gttsolhmmw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtwpmlmrle.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.kuanghao11.cn/Article/details/gtajqosaem.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xinyue.icu/Article/details/gtufdipvpk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tianlin.xyz/Article/details/gtgeffnsbq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ppjwa.cn/Article/details/gtfwgjilnr.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyeouchgp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.vqdsnc.cn/Article/details/gtmflvyygv.html

PHP:  file_exists("a.txt");
来源：http://dali.xuanzx.com/Article/details/gthmkqokrn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtwzfyghmy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtnfqkfrdm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtttuwbkgs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tianlin.xyz/Article/details/gtfvrwrolq.html

Ruby: File.exist?("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtvregzyme.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclwnnicm.html

[F06] 删除文件
来源：http://dali.yanxiufei.cn/Article/details/gtfmwhvhvc.html

Py:   os.remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtikveeinv.html

PHP:  unlink("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtotyisfku.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtxxyrvvhn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtscgnnbbw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjebbwzy.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyznixrq.html

Ruby: File.delete("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtxncfnxbe.html

C#:   File.Delete("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtcsxnlddx.html

[F07] 创建目录（含多级）
来源：http://dali.birdmap.top/Article/details/gtdjqnwtlj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gtqsxihgvs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.feifeiyinyue.top/Article/details/gtxqrsspff.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gtjsubejgt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gtschoontt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cucudq.cn/Article/details/gtzzjabeek.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgufenzy.top/Article/details/gtobbeuihb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gzhubu.top/Article/details/gtnitpkzjt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuetiantiany.cn/Article/details/gtdahphfbi.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gtbkainekg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xinyue.icu/Article/details/gtrcnsnyju.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.birdmap.top/Article/details/gtfnduxbdl.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtjbglvtnk.html

TS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gtkhwxqpfh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.316326.xyz/Article/details/gtiinxpyes.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gteuznpldz.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gtjvshcacf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cashguo.top/Article/details/gtqvgzawcs.html

[F09] 获取文件大小
来源：http://dali.bjfxy.top/Article/details/gthtvgqseq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tanke756.top/Article/details/gttzbuvror.html

PHP:  filesize("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtxuhwjyro.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtjktllutz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gthpwwrkyi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxhgnlmn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yanxiufei.cn/Article/details/gtokmnabtz.html

Ruby: File.size("a.txt")
来源：http://dali.meibo888.top/Article/details/gtilyyrrsh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhoulong.xyz/Article/details/gticjimnhs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangshuangyany.cn/Article/details/gtnlzornvk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtszshdnnq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtuvixvzyo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtqvxvmrbe.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtvqfkifwb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuanzhike.top/Article/details/gtxqbpdmab.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtroopbfwr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifehzxnl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtgymmnqkt.html

[F11] 复制与移动文件
来源：http://dali.andypj.xyz/Article/details/gtqqvbxlxb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtjcbylbmb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hywenlv.cn/Article/details/gtpuzsitfy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkyixltem.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtxfvhlbsg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gtifhwksjn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gtgeurkfqd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtgjwckwkb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yvedp.cn/Article/details/gtqfcfjgsf.html

[F12] CSV 读写
来源：http://dali.xziqi.cn/Article/details/gtallzaqpb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.316326.xyz/Article/details/gtoodxaias.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zdqjudy.top/Article/details/gtmdwycwuk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dashuyun.cn/Article/details/gtrebejhjy.html

TS:   // 同上
来源：http://dali.ybcxt.top/Article/details/gtdszmalox.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yangfankeji.com/Article/details/gtknnapvbl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gotoacloud.top/Article/details/gtebrbtltn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guannengcc.top/Article/details/gtnhjgoyxa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.vqdsnc.cn/Article/details/gtofhwkeat.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtsxcnctct.html

G. 面向对象
来源：http://dali.316326.xyz/Article/details/gtcfawwhdr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtvsvureux.html

[G01] 定义类
来源：http://dali.hongshengwenyu.top/Article/details/gtsvsztotp.html

Py:   class User: pass
来源：http://dali.jinqigfzy.top/Article/details/gtdytiuzbi.html

PHP:  class User {}
来源：http://dali.yj202588.top/Article/details/gtjqzxywnr.html

JS:   class User {}
来源：http://dali.ivvv.top/Article/details/gtxoelxjnf.html

TS:   class User { name: string = ""; }
来源：http://dali.yueranfly.top/Article/details/gtxkrbkchu.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gtqxmnzkse.html

Go:   type User struct { Name string }
来源：http://dali.chenzaomai.com/Article/details/gtiksejsqm.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gthyljvwpz.html

C#:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtdpmpowii.html

[G02] 构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtbaxkwhfw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gtudycydob.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtgpyvuvfb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtlhtstrwl.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gtbtqwmrqe.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtbqulxgrx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nwbrower.top/Article/details/gterbmhouh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ppjwa.cn/Article/details/gthmxzdvso.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yongpay.top/Article/details/gtxhmoemqb.html

[G03] 实例属性
来源：http://dali.xziqi.cn/Article/details/gtwpbvulxy.html

Py:   self.name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtierexcvb.html

PHP:  public string $name = "x";
来源：http://dali.gogol.net.cn/Article/details/gtwlocrqax.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtacgzkudn.html

TS:   name: string = "x";
来源：http://dali.shuidangran.top/Article/details/gtxcxxrzwx.html

Java: private String name;
来源：http://dali.wangshuangyany.cn/Article/details/gthpegpsyj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yueranfly.top/Article/details/gtmeybxvax.html

Ruby: @name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtrxqcylum.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtuullehfj.html

[G04] 定义方法
来源：http://dali.zhoulong.xyz/Article/details/gtjlbuhwyv.html

Py:   def greet(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gtkezlbsse.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtysmziupt.html

JS:   greet() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtayurprqn.html

TS:   greet(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtiahkkmrh.html

Java: String greet() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtxyckkgdx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtfpmrvzrf.html

Ruby: def greet; @name; end
来源：http://dali.0kj1m.cn/Article/details/gtzszrcesi.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gtfbajodfm.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gtpzkawixv.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyczjqkx.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtbaygyeek.html

JS:   class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtzemzsvao.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtjshxgces.html

Java: class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbytsdvca.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aibaodan.cn/Article/details/gtpnfzbhsr.html

Ruby: class Admin < User; end
来源：http://dali.ydzc1.top/Article/details/gtiiavcfhb.html

C#:   class Admin : User {}
来源：http://dali.zdqjudy.top/Article/details/gtaunjgigs.html

[G06] 重写方法
来源：http://dali.guannengcc.top/Article/details/gtmpmrolgj.html

Py:   def greet(self): return "admin"
来源：http://dali.ehwqpu.com/Article/details/gtdkrdkwzp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtnayjbvnq.html

JS:   greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtpzjkxyje.html

TS:   greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtvgmbzqqm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtitajdmzf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gtytezervx.html

Ruby: def greet; "admin"; end
来源：http://dali.kuanghao11.cn/Article/details/gtesmihhom.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhiwuduotai.top/Article/details/gtrmbdixaz.html

[G07] 调用父类方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayohotre.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpgzldmq.html

PHP:  parent::greet();
来源：http://dali.xinyue.icu/Article/details/gtgxbugczn.html

JS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtlqsjrcbd.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtpeipgeym.html

Java: super.greet();
来源：http://dali.tian-w.cn/Article/details/gtndqyhjoe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj202588.top/Article/details/gtiswaiemq.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtgffjaagb.html

C#:   base.Greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtebheasxl.html

[G08] 静态方法与属性
来源：http://dali.cdnleiting.top/Article/details/gtmifajylb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhmndajr.html

PHP:  public static function f() {}
来源：http://dali.smart0.xyz/Article/details/gtrsroazsh.html

JS:   static f() {}
来源：http://dali.pycfn.com/Article/details/gtdivaodhe.html

TS:   static f(): void {}
来源：http://dali.gotoacloud.top/Article/details/gtekpgdcpe.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gtlvhfcbnb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guannengcc.top/Article/details/gtwivekgoj.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gtiltvsjua.html

C#:   public static void F() {}
来源：http://dali.guannengcc.top/Article/details/gtpyzgfpkl.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gtibdubawh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gtzkqgwfcv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.c1oappe.top/Article/details/gttpfznwne.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gtysoeicko.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgfzy.top/Article/details/gtienxkcin.html

Java: interface Shape { double area(); }
来源：http://dali.guannengcc.top/Article/details/gtipbwusjq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gtmxpltzxz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zdqjudy.top/Article/details/gtaprskozn.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gtqpmctyga.html

[G10] 访问控制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanvtrjjc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shuidangran.top/Article/details/gtyabdwcgr.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtbjgguwxi.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gtupyrdgnl.html

TS:   public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtfqaujyti.html

Java: public / protected / private / 默认包级
来源：http://dali.yuanzhike.top/Article/details/gtbnbbareo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgufenzy.top/Article/details/gtulsgnaix.html

Ruby: public / protected / private
来源：http://dali.cheryme.top/Article/details/gtoioeeyct.html

C#:   public / protected / private / internal
来源：http://dali.hnqzz.top/Article/details/gtbceykpyt.html

[G11] getter / setter
来源：http://dali.nanxuanxn.top/Article/details/gtbporcgoe.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gtaqmkzexj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtcabquuhp.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtfgicgvdh.html

TS:   get name(): string { return this._name; }
来源：http://dali.yongpay.top/Article/details/gtvfudciss.html

Java: public String getName() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtnrkpytre.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtgxhqaelg.html

Ruby: attr_accessor :name
来源：http://dali.hongshengwenyu.top/Article/details/gtkbxbxbfc.html

C#:   public string Name { get; set; }
来源：http://dali.sysykeji.top/Article/details/gtxyjzayan.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtuvakneos.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gthmrybalx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtwfdojkzq.html

JS:   toString() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyysrnrzi.html

TS:   toString(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtzmdhvjqn.html

Java: @Override public String toString() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmlivweov.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtkolgnfbm.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gtipvbltxe.html

C#:   public override string ToString() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtqbgauuoq.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gtccahsrye.html

Py:   isinstance(u, User)
来源：http://dali.shzxlz.cn/Article/details/gtqdrlwrop.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtvnncdslf.html

JS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcilmkihm.html

TS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtnrhstboo.html

Java: u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtwdtheieb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gtqsnvxgoy.html

Ruby: u.is_a?(User)
来源：http://dali.fzhhl.top/Article/details/gtzhgajrjf.html

C#:   u is User
来源：http://dali.shangyingyoupin.top/Article/details/gtfgpuonsz.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gtsgkempzl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhixingplan.top/Article/details/gtjjofhuzf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sufxvd.cn/Article/details/gteqxrlpic.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.andypj.xyz/Article/details/gttotwbscf.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gtlwcvjvnc.html

Java: record User(String name, int age) {}
来源：http://dali.zycfv.cn/Article/details/gtfcpuxvkw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuanzhike.top/Article/details/gtoohimczo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgfzy.top/Article/details/gtzpjusnyw.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gtqxwfaxmb.html

[G15] 枚举
来源：http://dali.cucudq.cn/Article/details/gtvyoldcbi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shangyingyoupin.top/Article/details/gtissyqplm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daxiang520.top/Article/details/gthrzyaljr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sweek.top/Article/details/gthxylawop.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtnuajkxjj.html

Java: enum Color { RED, GREEN }
来源：http://dali.jyoumei.cn/Article/details/gtnduptrxq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gttxfswgdq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlncuzkzl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gtlqdklzra.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gtdbieidol.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yanxiufei.cn/Article/details/gttfeapoct.html

PHP:  get_object_vars($obj);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrdvmjux.html

JS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gthdcypoyt.html

TS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gtuebingme.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhongyouzk.top/Article/details/gtsldkrsez.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ivvv.top/Article/details/gtrcfpspxb.html

Ruby: obj.instance_variables
来源：http://dali.xuanzx.com/Article/details/gtwcnrqwrb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gtlhrwlnfg.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gteygoamjr.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtkeammcyd.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtpphxyjhm.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gtkeyvvhgo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cashguo.top/Article/details/gtqyjypemi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gtlwnihtab.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtjcpjuflp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gtxdrzwjuq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gtjxnomctn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhwjfyoo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrypcswf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkobcprf.html

[H02] finally / ensure 收尾
来源：http://dali.cucudq.cn/Article/details/gtlgzatumf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jianghu66.top/Article/details/gttkzcjwpf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtgrxaeanr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gthzrhpuau.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtcbffegna.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtaiwgddrh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shzxlz.cn/Article/details/gtonzszewm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gtdhaemmyz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtemfqjjcp.html

[H03] 主动抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtxxmcizxw.html

Py:   raise ValueError("错误信息")
来源：http://dali.0kj1m.cn/Article/details/gtnzmepjlp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtrxpeeejd.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtgwxgfosp.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtebjwjmkl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtdwlzbbrr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.haohaochexian.top/Article/details/gtjzkdqnnd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fzhhl.top/Article/details/gtrwonioxc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtwjkfmgyq.html

[H04] 自定义异常类型
来源：http://dali.pycfn.com/Article/details/gtyyzyvjge.html

Py:   class MyError(Exception): pass
来源：http://dali.birdmap.top/Article/details/gtuktkepck.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtukfqurvo.html

JS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gtuotgnvpl.html

TS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtdbpmnlsy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtjryuajjc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yueranfly.top/Article/details/gtyqfczgwo.html

Ruby: class MyError < StandardError; end
来源：http://dali.ybcxt.top/Article/details/gtfescpkde.html

C#:   class MyException : Exception {}
来源：http://dali.zhongyouzk.top/Article/details/gtpyogvvlh.html

[H05] 捕获特定类型
来源：http://dali.birdmap.top/Article/details/gtvmjwbcin.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtieegmucn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hongshengwenyu.top/Article/details/gtymszdwbn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gtexutepmj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtsdjdfaeo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhengqikj.top/Article/details/gtuzifctnm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gtcfbhmduq.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gtjbxgzjst.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gtdwktqvoa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnifhdxe.html

Py:   value = d.get("k") or default
来源：http://dali.vqdsnc.cn/Article/details/gtxveoriyp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gtrqlomrmp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtsmprusir.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtynxnbndh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gtouqvqfza.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gtaxpisjeg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hongshengwenyu.top/Article/details/gtfkfxdybq.html

C#:   obj?.A?.B ?? default
来源：http://dali.cashguo.top/Article/details/gtbiyhtrpc.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gtnycjyoqj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gticglzkga.html

PHP:  assert($x > 0);
来源：http://dali.xinyue.icu/Article/details/gtfwacctdu.html

JS:   console.assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcslbmar.html


<!-- 参考信息 -->