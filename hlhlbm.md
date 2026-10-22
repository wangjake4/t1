代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zqbsapdf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gt2vddyepbx.html

[F03] 写入文件（覆盖）
来源：http://dali.tian-w.cn/Article/details/gt2nclsyyex.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhongyouzk.top/Article/details/gt2smgvsiqo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gt2qcnmvksk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gt2zeawonzg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdpzlvkj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigufen.top/Article/details/gt2buovqhrx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tanke756.top/Article/details/gt2ocrkrudy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.smart0.xyz/Article/details/gt2saibbzsx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gt2nlqtcusu.html

[F04] 追加写入文件
来源：http://dali.svipenyu.cn/Article/details/gt2sdtvslkf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewxsismz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.iojbl.cn/Article/details/gt2ujzrvcus.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gt2uskfudmn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gt2chwfrqwr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.havefunace.top/Article/details/gt2qznnccdi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.mhx1999.top/Article/details/gt2sgwczxfb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aibaodan.cn/Article/details/gt2qwkizplh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hfpthk.cn/Article/details/gt2qlminolg.html

[F05] 判断文件或目录是否存在
来源：http://dali.shuidangran.top/Article/details/gt2dpsylxvs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yanxiufei.cn/Article/details/gt2pwbijpmx.html

PHP:  file_exists("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2gkegvmrf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2zccoddzq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yrotzycp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2corgehbg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jlsjyb.cn/Article/details/gt2mcedtlkb.html

Ruby: File.exist?("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2kdjydfxb.html

C#:   File.Exists("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2ivufuqqg.html

[F06] 删除文件
来源：http://dali.0kj1m.cn/Article/details/gt2kmmbcxyi.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tinellbs.html

PHP:  unlink("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2ekcrwxbb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2iobsypxm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2zmuouzcd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2cjxgogxn.html

Go:   os.Remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2xkrqllba.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2kvtsvunj.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2erqhkyef.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vdjkfzcm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gt2ceuffnrm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zycfv.cn/Article/details/gt2yaqaylrq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gt2jkutuzxi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gt2ekoeoisr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xziqi.cn/Article/details/gt2xexmxjev.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgufenzy.top/Article/details/gt2zkrsnium.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dkpmabbq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aibaodan.cn/Article/details/gt2dxksrqxk.html

[F08] 遍历目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lgkgdocr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgfzy.top/Article/details/gt2ptxcgsst.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cqqwz.cn/Article/details/gt2wfehdhot.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqdjglkb.html

TS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2qppcoiqx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gt2olhzixcc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sysykeji.top/Article/details/gt2nuatrnjh.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2qnkaefty.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guannengcc.top/Article/details/gt2isqmnodu.html

[F09] 获取文件大小
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tfcsionn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2vvtcdeqn.html

PHP:  filesize("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2pxgognbq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gt2rloxgdkg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gt2wvrhlwaq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2hfqafvzw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gt2wnuwenwu.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2cefrpubj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.vqdsnc.cn/Article/details/gt2qhehojpk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zybbrflp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2rxmdytcu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2vuyhxrmf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2adfbdmrn.html

TS:   path.extname("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2gwtvonnq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cashguo.top/Article/details/gt2nhdrpgbl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2vzddsmnh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2ptrewvos.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxwgasha.html

[F11] 复制与移动文件
来源：http://dali.jiagoushi.top/Article/details/gt2tbbrrhtc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gt2qxvmngdz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gt2tscvoaqa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2uduydrtw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2amgyndts.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gyewfyqi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sufxvd.cn/Article/details/gt2pbxdwmqr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sjrzeclv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sysykeji.top/Article/details/gt2gsoukcrj.html

[F12] CSV 读写
来源：http://dali.daxiang520.top/Article/details/gt2kmmlvhcs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gt2uorayzme.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ivvv.top/Article/details/gt2bxajmyhd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxuanxn.top/Article/details/gt2mayzjmma.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gt2jvhxorih.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mamkpmah.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gzhubu.top/Article/details/gt2gdyzrahr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yonumen.top/Article/details/gt2fixpqaex.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sufxvd.cn/Article/details/gt2cqfybxxs.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2vxknmbct.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gt2mkaczhzm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2cppllfgh.html

[G01] 定义类
来源：http://dali.tian-w.cn/Article/details/gt2tvnqdhei.html

Py:   class User: pass
来源：http://dali.tianlin.xyz/Article/details/gt2ysptmtko.html

PHP:  class User {}
来源：http://dali.aizwys.cn/Article/details/gt2mlixgccj.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2cpaxzoex.html

TS:   class User { name: string = ""; }
来源：http://dali.redwolf501.top/Article/details/gt2nmwgxosu.html

Java: class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2caaonshv.html

Go:   type User struct { Name string }
来源：http://dali.snrcjt.cn/Article/details/gt2gismjnhd.html

Ruby: class User; end
来源：http://dali.quarkkingdee.top/Article/details/gt2qvkmwffy.html

C#:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkryjibx.html

[G02] 构造函数
来源：http://dali.nwbrower.top/Article/details/gt2vmzmlfzs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pengpengdd.cyou/Article/details/gt2bguxapjz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2otwhfwhp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gt2yhpiiuxu.html

TS:   constructor(public name: string) {}
来源：http://dali.ppjwa.cn/Article/details/gt2fcqvchco.html

Java: User(String name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2ybeddxbe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jlsjyb.cn/Article/details/gt2awqfjlwx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gt2ijnmybir.html

C#:   public User(string name) { Name = name; }
来源：http://dali.bjfxy.top/Article/details/gt2ghxopeom.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gt2zzlqvazm.html

Py:   self.name = "x"
来源：http://dali.cucudq.cn/Article/details/gt2iqyhzuyn.html

PHP:  public string $name = "x";
来源：http://dali.sxryk.cn/Article/details/gt2nezntgkw.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2qwvgsthh.html

TS:   name: string = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2ennouvyw.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gt2lhbzarqa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gzhubu.top/Article/details/gt2ppgafypm.html

Ruby: @name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gt2ayfaganm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2dvtgqybm.html

[G04] 定义方法
来源：http://dali.tanke756.top/Article/details/gt2kvqxjaun.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gt2koufrpzq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gt2zpytipgi.html

JS:   greet() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2mrwwhzpx.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2snynemhp.html

Java: String greet() { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2wmplnbzq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gt2ogjkqlns.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gt2qkhkrzyc.html

C#:   public string Greet() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2xdbuqfae.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gt2uojssqkr.html

Py:   class Admin(User): pass
来源：http://dali.yj202588.top/Article/details/gt2qnyuptop.html

PHP:  class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2xtdqpgzi.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2tfjfjvoq.html

TS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2nvteylpy.html

Java: class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2hrwdmely.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.c1oappe.top/Article/details/gt2calgcaaz.html

Ruby: class Admin < User; end
来源：http://dali.hysaishi.cn/Article/details/gt2lecvepye.html

C#:   class Admin : User {}
来源：http://dali.hywenlv.cn/Article/details/gt2lwnsxxfr.html

[G06] 重写方法
来源：http://dali.aibaodan.cn/Article/details/gt2rfvejtby.html

Py:   def greet(self): return "admin"
来源：http://dali.c1oappe.top/Article/details/gt2zyxhlikf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zupunjfe.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gt2nzdzpcya.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wqwvmpzz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2skwahbbb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zdqjudy.top/Article/details/gt2cquyauhc.html

Ruby: def greet; "admin"; end
来源：http://dali.jyoumei.cn/Article/details/gt2vbvspahl.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gt2ehvqzcwn.html

[G07] 调用父类方法
来源：http://dali.tianlin.xyz/Article/details/gt2ukkfnfsi.html

Py:   super().greet()
来源：http://dali.hammf.cn/Article/details/gt2fbmqrdva.html

PHP:  parent::greet();
来源：http://dali.yonumen.top/Article/details/gt2sibbmcwi.html

JS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gt2qezostrr.html

TS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gt2gqihdfxk.html

Java: super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gt2qhdeprfh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xuyefxno.html

Ruby: super
来源：http://dali.jlsjyb.cn/Article/details/gt2escimpaw.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gt2owtgnyct.html

[G08] 静态方法与属性
来源：http://dali.gzhubu.top/Article/details/gt2lmwomjxe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gt2audfcytw.html

PHP:  public static function f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2mzkkfbwj.html

JS:   static f() {}
来源：http://dali.cucudq.cn/Article/details/gt2vfphwnqw.html

TS:   static f(): void {}
来源：http://dali.snrcjt.cn/Article/details/gt2mboatmir.html

Java: static void f() {}
来源：http://dali.yj20258888.top/Article/details/gt2pbiizlxt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daria6918.cn/Article/details/gt2xfxrmgpb.html

Ruby: def self.f; end
来源：http://dali.jqgufenzy.top/Article/details/gt2igrurupt.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gt2lcbjlbno.html

[G09] 接口 / 抽象类
来源：http://dali.xuetiantiany.cn/Article/details/gt2dljakpbn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gt2zeqzdgwu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gt2sfrxnfip.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sxryk.cn/Article/details/gt2zqohvoyf.html

TS:   interface Shape { area(): number; }
来源：http://dali.pycfn.com/Article/details/gt2neybtcpf.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gt2njjwchif.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2shbfwhih.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yanxiufei.cn/Article/details/gt2fnxexcng.html

C#:   interface IShape { double Area(); }
来源：http://dali.zdqjudy.top/Article/details/gt2sujcwamt.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gt2wqjrfjij.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gt2xcyjeknb.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2aehkwrod.html

JS:   #private 字段；其余公开
来源：http://dali.zycfv.cn/Article/details/gt2oyepquzf.html

TS:   public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2fccaqogk.html

Java: public / protected / private / 默认包级
来源：http://dali.yj202588.top/Article/details/gt2yiaucuxr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxinkj.top/Article/details/gt2ppsbtyda.html

Ruby: public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gt2lhecgspj.html

C#:   public / protected / private / internal
来源：http://dali.9152youxi.cn/Article/details/gt2gxvlrpjc.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gt2bwhboyhc.html

Py:   @property 与 @x.setter
来源：http://dali.daxiang520.top/Article/details/gt2cgwucqhs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hlbkfway.html

JS:   get name() { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gt2etshnvko.html

TS:   get name(): string { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gt2ekkuedjd.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2bsdfcpsy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gt2kttaqlyg.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gt2uuykbsiv.html

C#:   public string Name { get; set; }
来源：http://dali.yanxiufei.cn/Article/details/gt2tsutvoow.html

[G12] 对象转字符串
来源：http://dali.yueranfly.top/Article/details/gt2pgqmyvgl.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gt2cpbjtfio.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gt2glsxdylx.html

JS:   toString() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2tzeuzkjj.html

TS:   toString(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lmdujkda.html

Java: @Override public String toString() { return name; }
来源：http://dali.316326.xyz/Article/details/gt2xxtxjbzs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2jsdkggzg.html

Ruby: def to_s; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2odldjzzl.html

C#:   public override string ToString() => Name;
来源：http://dali.yongpay.top/Article/details/gt2asybtuvv.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yjsoxuga.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gt2spgstqiy.html

PHP:  $u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2lwiboldn.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2uvwyacbh.html

TS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gt2loltjxdz.html

Java: u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2fiaijxuj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daria6918.cn/Article/details/gt2pvnjnzvs.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gt2tljfvhbq.html

C#:   u is User
来源：http://dali.xinyue.icu/Article/details/gt2uciohyzy.html

[G14] 数据类 / record
来源：http://dali.sufxvd.cn/Article/details/gt2ijpllfry.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258888.top/Article/details/gt2ypzfpiuy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yvedp.cn/Article/details/gt2lellhycp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jlsjyb.cn/Article/details/gt2dpzkabqe.html

TS:   type User = { name: string; age: number };
来源：http://dali.316326.xyz/Article/details/gt2mebwjewd.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigufen.top/Article/details/gt2wtmniqgl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hysaishi.cn/Article/details/gt2upnmulmc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gaohongyu789.top/Article/details/gt2xvibkdoo.html

C#:   record User(string Name, int Age);
来源：http://dali.wangdashe.top/Article/details/gt2wyjakqtk.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gt2aymtygqm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gt2qrehdlmk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gt2vxjszxbh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yonumen.top/Article/details/gt2nnmzhcwy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gt2evzwvkia.html

Java: enum Color { RED, GREEN }
来源：http://dali.shzxlz.cn/Article/details/gt2kbtiglkv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.0kj1m.cn/Article/details/gt2ejgtmyxr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jianghu66.top/Article/details/gt2smfpcbap.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2vsdjprkz.html

[G16] 对象转数组 / 字典
来源：http://dali.shzxlz.cn/Article/details/gt2awgmqxdt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hongshengwenyu.top/Article/details/gt2oewflmrp.html

PHP:  get_object_vars($obj);
来源：http://dali.mhx1999.top/Article/details/gt2nblxqmau.html

JS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gt2dixtxjxf.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gt2mcidoyma.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ekdoxpme.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuanzhike.top/Article/details/gt2ssciilst.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gt2ykhkclph.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gt2ficejtti.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2kmiikbsz.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gt2zhvaxphb.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2racswrjf.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gt2aaxlfivy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxuanxn.top/Article/details/gt2capheayo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pofzfbov.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gt2exmbicde.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gt2lhscarby.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gzhubu.top/Article/details/gt2frnhtqab.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.snrcjt.cn/Article/details/gt2kwertvwm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2qeffqfac.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gt2gqobakte.html

[H02] finally / ensure 收尾
来源：http://dali.hysaishi.cn/Article/details/gt2aredfcgy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigufen.top/Article/details/gt2zexirdzr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2uxhokcdi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2nxblhdhp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2okoanavd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2cwrtnigb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pnhmsmqi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2qdyvwzmk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2eszjwlph.html

[H03] 主动抛出异常
来源：http://dali.jyoumei.cn/Article/details/gt2gpyqcclc.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gt2rjozacax.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2cidhnvic.html

JS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ywhpqtao.html

TS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2aoankani.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2zountmqz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2liaypsme.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xziqi.cn/Article/details/gt2adshkxmi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2nzszluif.html

[H04] 自定义异常类型
来源：http://dali.daxiang520.top/Article/details/gt2kulwxqqq.html

Py:   class MyError(Exception): pass
来源：http://dali.zycfv.cn/Article/details/gt2lfydxdry.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gt2kjvtpfye.html

JS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gt2dwjhxjqk.html

TS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gt2eeegcszh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gt2wmbrsrbt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenzaomai.com/Article/details/gt2nxiapdmp.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gt2dwfgowsg.html

C#:   class MyException : Exception {}
来源：http://dali.yueranfly.top/Article/details/gt2wpiujgww.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gt2hthlthiz.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gt2hstrmfzi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gzhubu.top/Article/details/gt2ehfrfgsy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjsdzwf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2vuwdkvaa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jianghu66.top/Article/details/gt2gqqhoras.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuanzhike.top/Article/details/gt2prrmpdxi.html

Ruby: rescue ArgumentError => e
来源：http://dali.shuidangran.top/Article/details/gt2dwutfmle.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.bjfxy.top/Article/details/gt2eikkycjk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sysykeji.top/Article/details/gt2afqqkswz.html

Py:   value = d.get("k") or default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cdhrwhto.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gt2qmhbkscg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.daria6918.cn/Article/details/gt2vzfijmcy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gt2grcoyjfc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jqgfzy.top/Article/details/gt2bppiwnzt.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgyomoat.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ikenzxca.html

C#:   obj?.A?.B ?? default
来源：http://dali.yongpay.top/Article/details/gt2yfnedwaa.html

[H07] 断言
来源：http://dali.haohaochexian.top/Article/details/gt2kbtvzpmk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenzaomai.com/Article/details/gt2ulkghbor.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2hviwaczz.html

JS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2tbcrovdh.html


<!-- 参考信息 -->