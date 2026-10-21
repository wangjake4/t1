代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtgatxdhuj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gtrqqbwqcr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gtthyvwniv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.9152youxi.cn/Article/details/gtrlzdohrw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aizwys.cn/Article/details/gtjizkdlrj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zdqjudy.top/Article/details/gtazybddbn.html

[F03] 写入文件（覆盖）
来源：http://dali.0kj1m.cn/Article/details/gtzmulbvos.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuxming.cn/Article/details/gtqncmvdvn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shuidangran.top/Article/details/gtztbeoedk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtvjbmibyq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtbmlrdqky.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gtjabgsymt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yangfankeji.com/Article/details/gtemcfdfke.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gtaqyrroim.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gtyxyyftfg.html

[F04] 追加写入文件
来源：http://dali.feifeiyinyue.top/Article/details/gtfaqesazh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tanke756.top/Article/details/gtpiysgvuz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jyoumei.cn/Article/details/gthzyxpdpv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gtnxdljqty.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gtvjwpkpab.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cdnleiting.top/Article/details/gthdnwhmyb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnqzz.top/Article/details/gtleyldweh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jiagoushi.top/Article/details/gthynrzfcy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yanxiufei.cn/Article/details/gtnrufhzfh.html

[F05] 判断文件或目录是否存在
来源：http://dali.sysykeji.top/Article/details/gtdoiweair.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pycfn.com/Article/details/gtodfhapnu.html

PHP:  file_exists("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtxvpysjca.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtvzhmqtlm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gttmshizww.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtpspzlmsd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ivvv.top/Article/details/gtettymcrl.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbafktca.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtonpxqzus.html

[F06] 删除文件
来源：http://dali.ivvv.top/Article/details/gtcwgxrqjw.html

Py:   os.remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtzsxbqoym.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtvldnogbu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtkxwkjgtl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtcdiidqgf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtnypoeijy.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtyrkwrsjn.html

Ruby: File.delete("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtbsnophbr.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtqreqtwky.html

[F07] 创建目录（含多级）
来源：http://dali.hammf.cn/Article/details/gtqnnjucie.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gtyudicnzq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sxryk.cn/Article/details/gtlmolzsbr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gtdiplrulf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtuxuxkhyq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gogol.net.cn/Article/details/gtjfxntiyl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fzhhl.top/Article/details/gtzvfdfgyt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gtefulxinf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtypokiw.html

[F08] 遍历目录
来源：http://dali.zhiwuduotai.top/Article/details/gtgrwembec.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhongyouzk.top/Article/details/gtmvfkxqrj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nwbrower.top/Article/details/gtmgnpkwzr.html

JS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtfeuipvqt.html

TS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gttrcmydre.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtpjztpkrl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvdrdnts.html

Ruby: Dir.children("dir")
来源：http://dali.daxiang520.top/Article/details/gtuglefaij.html

C#:   Directory.GetFiles("dir")
来源：http://dali.bjfxy.top/Article/details/gtbieleqor.html

[F09] 获取文件大小
来源：http://dali.hywenlv.cn/Article/details/gtptuvpcer.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtjoqsbnfq.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gtqibbqplw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gtlcytkzgg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtebvxaeqk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtkbzaccgq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhiwuduotai.top/Article/details/gtxhgrvslw.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtjlzhzaps.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gtnzljfsga.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjsehcfu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtfhzotkrl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.bjfxy.top/Article/details/gtkgyavebt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtrelgiaaz.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtngdhmjkr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yonumen.top/Article/details/gtzwobfiye.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtullnimrr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtwgpwqnvv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtdfwowhsu.html

[F11] 复制与移动文件
来源：http://dali.guowangkeji.top/Article/details/gtqllydcso.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtcilkqfnh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ehwqpu.com/Article/details/gtlfttyait.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtlubudlyc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtthamjlol.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gtemgruioy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cucudq.cn/Article/details/gthdrjqtfp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtsfabhonr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gtpyksmgzt.html

[F12] CSV 读写
来源：http://dali.vqdsnc.cn/Article/details/gtnnwkkxvs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sufxvd.cn/Article/details/gtwfrunzyw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xinyue.icu/Article/details/gtjpmluqvj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdertxdj.html

TS:   // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtywxtelwq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ivvv.top/Article/details/gtvwbfewhy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhongyouzk.top/Article/details/gtywmrluzl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gotoacloud.top/Article/details/gtrtonurqn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fzhhl.top/Article/details/gtgitmdedy.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpgdeygiv.html

G. 面向对象
来源：http://dali.birdmap.top/Article/details/gtwuafpscd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtplxezubx.html

[G01] 定义类
来源：http://dali.daria6918.cn/Article/details/gtjxxkyiqe.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gtkbikavah.html

PHP:  class User {}
来源：http://dali.sweek.top/Article/details/gtmcfixrdd.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtwhlooijz.html

TS:   class User { name: string = ""; }
来源：http://dali.chenlongwang.top/Article/details/gtyboqjtkd.html

Java: class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtbozjukhw.html

Go:   type User struct { Name string }
来源：http://dali.ydzc1.top/Article/details/gtugwzyitp.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gtrhxmnefz.html

C#:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gtgyxwmmhl.html

[G02] 构造函数
来源：http://dali.c1oappe.top/Article/details/gtiruozeds.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guannengcc.top/Article/details/gtmtbvoeyd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gthxzykqys.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtnqenghvh.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigufen.top/Article/details/gtgbicbzcs.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvduivyi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gtlxwzhqdn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gtbiypmrey.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtvcifjmcv.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gteycjvaqh.html

Py:   self.name = "x"
来源：http://dali.jyoumei.cn/Article/details/gtbykeoujd.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gtekvcuuyp.html

JS:   this.name = "x";
来源：http://dali.dashuyun.cn/Article/details/gtcnixgarq.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gtzbormyoa.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gtkcugtvlo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hfpthk.cn/Article/details/gtdwqeeihd.html

Ruby: @name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtfxiqclqk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tanke756.top/Article/details/gtycqhxowa.html

[G04] 定义方法
来源：http://dali.xuanzx.com/Article/details/gtcgmizdgt.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtbnxlenil.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtkujbnyvw.html

JS:   greet() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtnnnsnfol.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtfrwqhiqo.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtnfowwqoq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtlgsnmwzu.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gtrknynnie.html

C#:   public string Greet() => Name;
来源：http://dali.nanxinkj.top/Article/details/gttyxypffn.html

[G05] 继承
来源：http://dali.ppjwa.cn/Article/details/gtgmheowns.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gtxzrcitsz.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtljutnnph.html

JS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtyzqgtpwt.html

TS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtanqqjxfo.html

Java: class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtzmnnhrvd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenlongwang.top/Article/details/gthhygwvjy.html

Ruby: class Admin < User; end
来源：http://dali.xziqi.cn/Article/details/gteuqkevzl.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gtniglufgo.html

[G06] 重写方法
来源：http://dali.haohaochexian.top/Article/details/gtxkuciewp.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gtemqwphjz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtfuudnfkm.html

JS:   greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtzjqmlmyo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtozhvgxdp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtxmpztadx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gtvhehymjb.html

Ruby: def greet; "admin"; end
来源：http://dali.pycfn.com/Article/details/gtipwgdmdw.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenzaomai.com/Article/details/gtsvqyhslc.html

[G07] 调用父类方法
来源：http://dali.wangshuangyany.cn/Article/details/gtmtwearwq.html

Py:   super().greet()
来源：http://dali.feifeiyinyue.top/Article/details/gtfosjktdj.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrqkvmza.html

JS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtnncersco.html

TS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gtiekoucvw.html

Java: super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtizmkhanc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jlsjyb.cn/Article/details/gtvhgzrbrs.html

Ruby: super
来源：http://dali.yuanzhike.top/Article/details/gtgjixznmh.html

C#:   base.Greet();
来源：http://dali.nwbrower.top/Article/details/gtvnokohvc.html

[G08] 静态方法与属性
来源：http://dali.xylfe.cn/Article/details/gtvbfmkinh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xziqi.cn/Article/details/gtvkxfgdzm.html

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtmyhgykqh.html

JS:   static f() {}
来源：http://dali.hfpthk.cn/Article/details/gtiohszsct.html

TS:   static f(): void {}
来源：http://dali.sxryk.cn/Article/details/gtamlfjryx.html

Java: static void f() {}
来源：http://dali.ehwqpu.com/Article/details/gtmjvqwlkd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xziqi.cn/Article/details/gtgbigmirr.html

Ruby: def self.f; end
来源：http://dali.iojbl.cn/Article/details/gtaeyrxrif.html

C#:   public static void F() {}
来源：http://dali.nanxinkj.top/Article/details/gtvpurhgjt.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gtbyjhmcag.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dashuyun.cn/Article/details/gtxkmfbpqu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sufxvd.cn/Article/details/gtgkycmqoi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenlongwang.top/Article/details/gtewfwbqmp.html

TS:   interface Shape { area(): number; }
来源：http://dali.meibo888.top/Article/details/gtyqvostwz.html

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gtrtwmvgsh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gzhubu.top/Article/details/gtymasajml.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirehxsqh.html

C#:   interface IShape { double Area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtdcnuaqch.html

[G10] 访问控制
来源：http://dali.redwolf501.top/Article/details/gtdnzofxzm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ydzc1.top/Article/details/gtawmtgcal.html

PHP:  public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtdpcvgzyq.html

JS:   #private 字段；其余公开
来源：http://dali.zhengqikj.top/Article/details/gtzvrwgsbm.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtastfimlk.html

Java: public / protected / private / 默认包级
来源：http://dali.xylfe.cn/Article/details/gtavpthvob.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.meibo888.top/Article/details/gtjgzkbvcy.html

Ruby: public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtdwsujhmi.html

C#:   public / protected / private / internal
来源：http://dali.daria6918.cn/Article/details/gtlmfvqjsn.html

[G11] getter / setter
来源：http://dali.mhx1999.top/Article/details/gtozdeefrp.html

Py:   @property 与 @x.setter
来源：http://dali.yuanzhike.top/Article/details/gtsfpnvtql.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gttmdanixb.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdpphqilk.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtyukexsoy.html

Java: public String getName() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtteqpblgi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtgrkowscu.html

Ruby: attr_accessor :name
来源：http://dali.haohaochexian.top/Article/details/gteinzjgsl.html

C#:   public string Name { get; set; }
来源：http://dali.yvedp.cn/Article/details/gtbpuiqsbx.html

[G12] 对象转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtptztyvpw.html

Py:   def __str__(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gtjcqzohgo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtqvrhvbjg.html

JS:   toString() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gttuvzsvxo.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gtlhvrdfwo.html

Java: @Override public String toString() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gttikonmol.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtpijuwqyh.html

Ruby: def to_s; @name; end
来源：http://dali.bjfxy.top/Article/details/gtyagsucet.html

C#:   public override string ToString() => Name;
来源：http://dali.yvedp.cn/Article/details/gtrxrsmhxc.html

[G13] 判断对象类型
来源：http://dali.aizwys.cn/Article/details/gttqpvvieq.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gtwzxpuvkb.html

PHP:  $u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gthdrxueuq.html

JS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtanjvwjlb.html

TS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtaufnkicr.html

Java: u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtybnscddq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.316326.xyz/Article/details/gtknfluttp.html

Ruby: u.is_a?(User)
来源：http://dali.ehwqpu.com/Article/details/gtxwvbuvek.html

C#:   u is User
来源：http://dali.hammf.cn/Article/details/gtlilntvuf.html

[G14] 数据类 / record
来源：http://dali.zhixingplan.top/Article/details/gtmsuharxx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhongyouzk.top/Article/details/gtkjynpwqt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.0kj1m.cn/Article/details/gtwpxyqljr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hnxiangtu.top/Article/details/gtnmknqdur.html

TS:   type User = { name: string; age: number };
来源：http://dali.iojbl.cn/Article/details/gtqltbjuno.html

Java: record User(String name, int age) {}
来源：http://dali.guannengcc.top/Article/details/gtqschomvp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guowangkeji.top/Article/details/gtnlxokwqc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daria6918.cn/Article/details/gtpycwxdnp.html

C#:   record User(string Name, int Age);
来源：http://dali.chenjidiqi.icu/Article/details/gtrzaiufmk.html

[G15] 枚举
来源：http://dali.yj20258.top/Article/details/gtkejqcoir.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gterwgleyp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhoulong.xyz/Article/details/gtvzabqizj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yueranfly.top/Article/details/gtnrxjjdaq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gtdhqymueu.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gtrylijmzt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daxiang520.top/Article/details/gtmjqxhdfu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.316326.xyz/Article/details/gtmkjztndz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gtaqsjbcew.html

[G16] 对象转数组 / 字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtehnokhrr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gtajuytfxn.html

PHP:  get_object_vars($obj);
来源：http://dali.cheryme.top/Article/details/gtmqvaulyc.html

JS:   Object.entries(obj)
来源：http://dali.yuanzhike.top/Article/details/gtilhzjzun.html

TS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gtmtbegvjm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sysykeji.top/Article/details/gtuqllvlve.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sweek.top/Article/details/gtathfikvg.html

Ruby: obj.instance_variables
来源：http://dali.cucudq.cn/Article/details/gtppenbaep.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gtclnkdkxj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtxizytncl.html

H. 异常与错误处理
来源：http://dali.0kj1m.cn/Article/details/gtcmjjukdv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtkdfzqifs.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gtghwvecaz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xziqi.cn/Article/details/gtvdgtwfgx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gtmhmtjzja.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtenpntmfm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtkkovilpp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gtvpgyhsji.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guowangkeji.top/Article/details/gtphxgqvak.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yonumen.top/Article/details/gtbsfancsy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhengqikj.top/Article/details/gtviinorxc.html

[H02] finally / ensure 收尾
来源：http://dali.cheryme.top/Article/details/gtenqovxog.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jianghu66.top/Article/details/gthqjrngxy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtfggpxmss.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtmdallxgk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtfusghfjj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtwygsod.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuetiantiany.cn/Article/details/gtxyyhrbqr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhoulong.xyz/Article/details/gtqowchewy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtuexleddi.html

[H03] 主动抛出异常
来源：http://dali.hysaishi.cn/Article/details/gtogkrbdkv.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258.top/Article/details/gtrunhtdhm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtvinjwagq.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtvtjnkhgy.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtdgqlcytc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtpjvfkyph.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gtgvixhpde.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guowangkeji.top/Article/details/gttuzmokvl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtmheovtjl.html

[H04] 自定义异常类型
来源：http://dali.fengsongda.top/Article/details/gtiyswnpro.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gtqawsybsi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtgtifvutd.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtumglmumx.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfttpuqee.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtmrpnikba.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fzhhl.top/Article/details/gtwbfrlnmz.html

Ruby: class MyError < StandardError; end
来源：http://dali.gogol.net.cn/Article/details/gtddlfrlmq.html

C#:   class MyException : Exception {}
来源：http://dali.iojbl.cn/Article/details/gtoqkpakna.html

[H05] 捕获特定类型
来源：http://dali.pycfn.com/Article/details/gtzahvbnxh.html

Py:   except ValueError as e:
来源：http://dali.fzhhl.top/Article/details/gtdbrlhakk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gotoacloud.top/Article/details/gtgufezizz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtkneujpse.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daria6918.cn/Article/details/gttzhyssnz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258.top/Article/details/gtqdkuonim.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fengsongda.top/Article/details/gtnhbcxyrb.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gtakbkrbiq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtozfdgjqs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yueranfly.top/Article/details/gtxjqlwsbd.html

Py:   value = d.get("k") or default
来源：http://dali.yuxming.cn/Article/details/gtuhjewqoj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gtgugvsygy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtudfrsljc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cdnleiting.top/Article/details/gtjxbgdutw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cashguo.top/Article/details/gtjncendfe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shuidangran.top/Article/details/gthncbojqf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fzhhl.top/Article/details/gtyfwazlqm.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenlongwang.top/Article/details/gtmqjbrrtk.html


<!-- 参考信息 -->