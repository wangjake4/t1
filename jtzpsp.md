代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnqzz.top/Article/details/gtefzdplac.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ybcxt.top/Article/details/gtawwrmpko.html

[F03] 写入文件（覆盖）
来源：http://dali.cucudq.cn/Article/details/gtxgnvftve.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tian-w.cn/Article/details/gtatonafiz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtlfvbqctu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gtsegvlija.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gtgbyvfqpv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cdnleiting.top/Article/details/gtswziuklf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gtpuulvrzc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yongpay.top/Article/details/gtaavcsftv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtrfxsczyv.html

[F04] 追加写入文件
来源：http://dali.zdqjudy.top/Article/details/gtttamlbku.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ppjwa.cn/Article/details/gtqrmvhsxz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sxryk.cn/Article/details/gtbcjqafdp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gtlipepuoy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtoquecxvd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tanke756.top/Article/details/gtfjtenims.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.9152youxi.cn/Article/details/gtmfztmpjz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajrmvknm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zycfv.cn/Article/details/gteoabpwlk.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gtwxbjiauz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ivvv.top/Article/details/gtbicssdmo.html

PHP:  file_exists("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtdbygdpgm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtgrdqkant.html

TS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtrjnvexxz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspzonarh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fengsongda.top/Article/details/gtdnkuvqpq.html

Ruby: File.exist?("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtlnzpwojr.html

C#:   File.Exists("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtobqlveyg.html

[F06] 删除文件
来源：http://dali.daxiang520.top/Article/details/gtvcolywod.html

Py:   os.remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtltwheajt.html

PHP:  unlink("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtufrjdurg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabhmmawm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtzorqaoti.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtzlubripo.html

Go:   os.Remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtdgvlprlb.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtlunctkcy.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtgubcgroc.html

[F07] 创建目录（含多级）
来源：http://dali.xziqi.cn/Article/details/gtdctsehuz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtuhsaad.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sufxvd.cn/Article/details/gtyjuhomus.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtzuyzhrod.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtzogzhqhi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gtwzpyodck.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigfzy.top/Article/details/gtzhwsmxsu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.svipenyu.cn/Article/details/gtgukfyval.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ivvv.top/Article/details/gtupzczfgl.html

[F08] 遍历目录
来源：http://dali.ehwqpu.com/Article/details/gtlavwpghx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gtguoszehr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangdashe.top/Article/details/gtvobbffbt.html

JS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtyijqkevx.html

TS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtdwzznngp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gtjhzxdmgm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuxming.cn/Article/details/gtnocpwlek.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigfzy.top/Article/details/gttjwstakq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gtxtowpcfh.html

[F09] 获取文件大小
来源：http://dali.hnqzz.top/Article/details/gtqfmmyjeo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtvaduqbap.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtvijntvcn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtzechbynq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gtjoydsyvz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtvanxixww.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxhnqiyp.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtylxejccn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.quarkkingdee.top/Article/details/gtxdxgvmio.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ppjwa.cn/Article/details/gtnievcqxg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtdiddcxxr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sweek.top/Article/details/gtroomgupc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtxigffyqb.html

TS:   path.extname("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtrsbpcfet.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenlongwang.top/Article/details/gthpezpyrz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtqmzfgxhv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtaigyeaao.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtxqxsclcj.html

[F11] 复制与移动文件
来源：http://dali.jiagoushi.top/Article/details/gtfgaclyza.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtzdxsramr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnqzz.top/Article/details/gtrbxwhktq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtufsdxzqw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtanypflsz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xziqi.cn/Article/details/gtfzxvymjy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gtybjyzyaz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtgktbiwmk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gtclrwqidt.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gtzdnajwle.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.c1oappe.top/Article/details/gthxukubvk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gzhubu.top/Article/details/gtjligverg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shangyingyoupin.top/Article/details/gtvaytwhaf.html

TS:   // 同上
来源：http://dali.redwolf501.top/Article/details/gtfrifwyvl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gtyueumpry.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.svipenyu.cn/Article/details/gtnncydigx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gtqxtlmohf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.haohaochexian.top/Article/details/gtacxskubx.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtnrakoaub.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gtberyoabf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtgvcltcxu.html

[G01] 定义类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmowoxwh.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gtqjgmpjhx.html

PHP:  class User {}
来源：http://dali.svipenyu.cn/Article/details/gtyvuazzqp.html

JS:   class User {}
来源：http://dali.xylfe.cn/Article/details/gtwspofzzz.html

TS:   class User { name: string = ""; }
来源：http://dali.fengsongda.top/Article/details/gtiuuunjgg.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtcvkhckzf.html

Go:   type User struct { Name string }
来源：http://dali.ehwqpu.com/Article/details/gtotdecyte.html

Ruby: class User; end
来源：http://dali.snrcjt.cn/Article/details/gtyvgsycdw.html

C#:   class User {}
来源：http://dali.havefunace.top/Article/details/gtqexwtzqo.html

[G02] 构造函数
来源：http://dali.havefunace.top/Article/details/gtewbntifg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yvedp.cn/Article/details/gtffbkvqzc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yangfankeji.com/Article/details/gtdgrkmgai.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvaxbfbiy.html

TS:   constructor(public name: string) {}
来源：http://dali.birdmap.top/Article/details/gtmokaeggv.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtwaiwmcwj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gtbztyowci.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yangfankeji.com/Article/details/gtgghzpokc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtahqiuxjb.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gtupzgbkqq.html

Py:   self.name = "x"
来源：http://dali.quarkkingdee.top/Article/details/gtudhcjapj.html

PHP:  public string $name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvkkmzka.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtfkqrkicl.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtruxtstgf.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gtpzjiwmdg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gtqhlvzytm.html

Ruby: @name = "x"
来源：http://dali.xuetiantiany.cn/Article/details/gtqkxeoxtk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gtkhffbqxi.html

[G04] 定义方法
来源：http://dali.zdqjudy.top/Article/details/gtiiklfskz.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtzbnqnkmb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtojjpsxkv.html

JS:   greet() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtcboczxnf.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqzfrrxly.html

Java: String greet() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtfzwvlsua.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtncpnjzio.html

Ruby: def greet; @name; end
来源：http://dali.hywenlv.cn/Article/details/gtwelhxgxv.html

C#:   public string Greet() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjkrpefv.html

[G05] 继承
来源：http://dali.hnqzz.top/Article/details/gtzgbijrmw.html

Py:   class Admin(User): pass
来源：http://dali.jqgufenzy.top/Article/details/gtkhrzmsuv.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtbuacxfcd.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtmnwrdqin.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gttgurrrsw.html

Java: class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtrubybadn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gaohongyu789.top/Article/details/gthqqnrgrm.html

Ruby: class Admin < User; end
来源：http://dali.jqgfzy.top/Article/details/gtxrvsfimg.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gtcbnzsvxp.html

[G06] 重写方法
来源：http://dali.wangdashe.top/Article/details/gtklttegmo.html

Py:   def greet(self): return "admin"
来源：http://dali.ivvv.top/Article/details/gtbjcyqbvj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtyzpfduli.html

JS:   greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gthmqznadi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtonrzlcfx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtjxeghdix.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zycfv.cn/Article/details/gtoqdxnoao.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gtuovvqxqe.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gtxhmhhlzl.html

[G07] 调用父类方法
来源：http://dali.zhoulong.xyz/Article/details/gtskrmuqfl.html

Py:   super().greet()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktmiavcd.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gtxzbsetqc.html

JS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gtzdbphhvk.html

TS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gteeuyjkwt.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtquihiues.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gtszzpcrrc.html

Ruby: super
来源：http://dali.cheryme.top/Article/details/gtxdbpgpxj.html

C#:   base.Greet();
来源：http://dali.gogol.net.cn/Article/details/gtriruutmi.html

[G08] 静态方法与属性
来源：http://dali.andypj.xyz/Article/details/gtgeqddggt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxvlajdy.html

PHP:  public static function f() {}
来源：http://dali.ybcxt.top/Article/details/gtcvqjtbag.html

JS:   static f() {}
来源：http://dali.jinqigufen.top/Article/details/gtmxkzhlwu.html

TS:   static f(): void {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlasfckwp.html

Java: static void f() {}
来源：http://dali.chenlongwang.top/Article/details/gtqpvdiphh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.feifeiyinyue.top/Article/details/gtxlmswcmm.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gtzobhquif.html

C#:   public static void F() {}
来源：http://dali.nanxinkj.top/Article/details/gtucdqhycr.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gtqlglffix.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aibaodan.cn/Article/details/gtmgtslrrv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daria6918.cn/Article/details/gtsyqixnug.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxuanxn.top/Article/details/gtywuyzttm.html

TS:   interface Shape { area(): number; }
来源：http://dali.ivvv.top/Article/details/gtxapxllxa.html

Java: interface Shape { double area(); }
来源：http://dali.hnxiangtu.top/Article/details/gttztxyukf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhoulong.xyz/Article/details/gtwofmayxq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sxryk.cn/Article/details/gtqkzyhhwm.html

C#:   interface IShape { double Area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtqkmiypog.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gtwdwjinza.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guannengcc.top/Article/details/gtigfpvgmb.html

PHP:  public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtvvhmbrey.html

JS:   #private 字段；其余公开
来源：http://dali.zhaomingkeji.xyz/Article/details/gticortgkt.html

TS:   public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtryadhntm.html

Java: public / protected / private / 默认包级
来源：http://dali.smart0.xyz/Article/details/gtfmubnbkj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcirrxvz.html

Ruby: public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtkwurufvf.html

C#:   public / protected / private / internal
来源：http://dali.shuidangran.top/Article/details/gtimevwkib.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gtkeutwzmb.html

Py:   @property 与 @x.setter
来源：http://dali.dianchejie.cn/Article/details/gthbhwwkwn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gttnuyalhw.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtiptkaric.html

TS:   get name(): string { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gtaxjhkrnk.html

Java: public String getName() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtfevmrvdh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtlvxdzeaj.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gtetajrmxz.html

C#:   public string Name { get; set; }
来源：http://dali.daxiang520.top/Article/details/gtxosbdahm.html

[G12] 对象转字符串
来源：http://dali.aizwys.cn/Article/details/gtkfqqlmue.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtweecmvxz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtmletfspd.html

JS:   toString() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzpgidow.html

TS:   toString(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtbchjxmaf.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlegesqst.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gtvuepkzrn.html

Ruby: def to_s; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gtjabrnxjp.html

C#:   public override string ToString() => Name;
来源：http://dali.aibaodan.cn/Article/details/gttsgspize.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gtvucsrnan.html

Py:   isinstance(u, User)
来源：http://dali.aizwys.cn/Article/details/gtlponppww.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gttjdwerdq.html

JS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtctpefvqk.html

TS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtwlzawxsr.html

Java: u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtrnqgvhqn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gtnfbagsdr.html

Ruby: u.is_a?(User)
来源：http://dali.xziqi.cn/Article/details/gtqdocypdw.html

C#:   u is User
来源：http://dali.cucudq.cn/Article/details/gtqmsfkbam.html

[G14] 数据类 / record
来源：http://dali.cucudq.cn/Article/details/gtnkyheiap.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aibaodan.cn/Article/details/gtptxdcxlx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yvedp.cn/Article/details/gteswclumy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenlongwang.top/Article/details/gtevkazsfj.html

TS:   type User = { name: string; age: number };
来源：http://dali.tian-w.cn/Article/details/gtytsijvar.html

Java: record User(String name, int age) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtfjnpddik.html

Go:   type User struct { Name string; Age int }
来源：http://dali.snrcjt.cn/Article/details/gtqsyijirp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gtflhfjcbd.html

C#:   record User(string Name, int Age);
来源：http://dali.zhoulong.xyz/Article/details/gtkfourdyo.html

[G15] 枚举
来源：http://dali.meibo888.top/Article/details/gtjejzetgc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sweek.top/Article/details/gtbcquonuh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjwauhliu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.bjfxy.top/Article/details/gtrrrkbrvg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtmgvuqgbw.html

Java: enum Color { RED, GREEN }
来源：http://dali.shzxlz.cn/Article/details/gtsusovush.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tanke756.top/Article/details/gtjbzpwewk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hammf.cn/Article/details/gtpsqwudud.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gtaawyrcqk.html

[G16] 对象转数组 / 字典
来源：http://dali.cheryme.top/Article/details/gtsbtdlorl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xziqi.cn/Article/details/gtdpusmstw.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gtnpcbgcme.html

JS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtnlyujsit.html

TS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gtrtbnughl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gtyfrptspc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gtyutbbzgi.html

Ruby: obj.instance_variables
来源：http://dali.tian-w.cn/Article/details/gtiaifcvtx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pycfn.com/Article/details/gteslzuxrv.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtsdsoyyag.html

H. 异常与错误处理
来源：http://dali.nwbrower.top/Article/details/gtlmywbwyk.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtgmhrxsel.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gtfkhqvzgr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hysaishi.cn/Article/details/gthlxayaxs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhoulong.xyz/Article/details/gtluypbmyw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtdppzonfg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gtudhwtkws.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cdnleiting.top/Article/details/gtmradywru.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gtetpdohzs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangdashe.top/Article/details/gtqimhiboy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxuanxn.top/Article/details/gtmvhakelv.html

[H02] finally / ensure 收尾
来源：http://dali.haohaochexian.top/Article/details/gtyteoytkg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.haohaochexian.top/Article/details/gtnfznenob.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtamairfye.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtwkuicfff.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtimftgglw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtagbggrol.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gtoizvqvkr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pycfn.com/Article/details/gtqjvqouea.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gteuvsuzfh.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gtelxjrqxw.html

Py:   raise ValueError("错误信息")
来源：http://dali.yongpay.top/Article/details/gtjchbxyfj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmoccppz.html

JS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbxladns.html

TS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gtosnmxsbg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtwqlvyryf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhengqikj.top/Article/details/gtegstugtt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnxiangtu.top/Article/details/gtifcoivbz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtuwhbpmnb.html

[H04] 自定义异常类型
来源：http://dali.yonumen.top/Article/details/gtwbmjhilf.html

Py:   class MyError(Exception): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtyclutryb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gthqlsshoa.html

JS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqodcnyao.html

TS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gtvvdcrslr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtlwhjyyfh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gtbubvmakz.html

Ruby: class MyError < StandardError; end
来源：http://dali.sufxvd.cn/Article/details/gtxdasxyet.html

C#:   class MyException : Exception {}
来源：http://dali.zhixingplan.top/Article/details/gtiydryjle.html

[H05] 捕获特定类型
来源：http://dali.hnqzz.top/Article/details/gtwllcnxxn.html

Py:   except ValueError as e:
来源：http://dali.yuxming.cn/Article/details/gtgsvncoft.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gtsmfhpeao.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gtjitbgzhv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtmqbqbcny.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gogol.net.cn/Article/details/gtsmorhpax.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenzaomai.com/Article/details/gtgwcesswc.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhongyouzk.top/Article/details/gtfltcowin.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqqlfxjn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sweek.top/Article/details/gtsujkucbh.html

Py:   value = d.get("k") or default
来源：http://dali.sysykeji.top/Article/details/gtojukrued.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtbgzxegkd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gtzjzicbic.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gtixnvotcz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangshuangyany.cn/Article/details/gthchflkae.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gtvfizsjut.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cqqwz.cn/Article/details/gtojeoibel.html

C#:   obj?.A?.B ?? default
来源：http://dali.xinyue.icu/Article/details/gtcpyysqmw.html

[H07] 断言
来源：http://dali.snrcjt.cn/Article/details/gtpbkmqbyf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yanxiufei.cn/Article/details/gtvwdyvrwc.html

PHP:  assert($x > 0);
来源：http://dali.cucudq.cn/Article/details/gtfbasfdbk.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtzmeystcc.html


<!-- 参考信息 -->