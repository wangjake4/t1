代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jyoumei.cn/Article/details/gt2dycsuyfp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yvedp.cn/Article/details/gt2vueskjrn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gt2ffmgdmnl.html

[F04] 追加写入文件
来源：http://dali.yuanzhike.top/Article/details/gt2vzxytieu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2ceqnavoy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yongpay.top/Article/details/gt2cpqujtgp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gt2szsvkpiq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gt2bvkgnztq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cheryme.top/Article/details/gt2uenvthim.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gt2slqgebwn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wxdzjprc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qcupfzzo.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenlongwang.top/Article/details/gt2yipbxbkh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dmwqxlem.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2oanpmduf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2whqlcwaz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2yibhupsn.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2icljslnj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ehwqpu.com/Article/details/gt2tzunoooy.html

Ruby: File.exist?("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2sweisedn.html

C#:   File.Exists("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2wddlwpkd.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gt2yjrgyird.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2iovcwnho.html

PHP:  unlink("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2dkfapcqm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kdjzefmq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2sklfcrxv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2umuzqfqt.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2chegzlkp.html

Ruby: File.delete("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqhpxawl.html

C#:   File.Delete("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2ebjprcfp.html

[F07] 创建目录（含多级）
来源：http://dali.chenlongwang.top/Article/details/gt2lzmyjpns.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gt2bnifarae.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cdnleiting.top/Article/details/gt2lxseuqjv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gt2xesphguk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gt2lkwnowxe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2zniesmmr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hzklbarw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yvedp.cn/Article/details/gt2tbjqmulz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tianlin.xyz/Article/details/gt2mjnzyrjt.html

[F08] 遍历目录
来源：http://dali.dianchejie.cn/Article/details/gt2uvqswixh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gt2beqllczu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yanxiufei.cn/Article/details/gt2pzoscqla.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gt2ltxlouso.html

TS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2lempsgth.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gt2yyxannhr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xinyue.icu/Article/details/gt2mynyeexq.html

Ruby: Dir.children("dir")
来源：http://dali.tian-w.cn/Article/details/gt2zdxvxknd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2tuygwepn.html

[F09] 获取文件大小
来源：http://dali.xylfe.cn/Article/details/gt2paphwfia.html

Py:   os.path.getsize("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2cetzbayh.html

PHP:  filesize("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2ukkyptbz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gt2mfobvgwt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gt2cxnrbuty.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2vfxseuim.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.bjfxy.top/Article/details/gt2csvfaqip.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2ugkayyif.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jyoumei.cn/Article/details/gt2kaqqjuky.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhengqikj.top/Article/details/gt2dgdqddpx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2mxaatjns.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2xikbmtvy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2piteyxzx.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2glrjlupp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj202588.top/Article/details/gt2xukpuzed.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2gfdexuzt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2vomxfysv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2snahokyv.html

[F11] 复制与移动文件
来源：http://dali.tian-w.cn/Article/details/gt2tpvftalm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2rdxjbjuj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangdashe.top/Article/details/gt2usqbbnzj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2vaetaroo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uzwiiiia.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xziqi.cn/Article/details/gt2lyfixbcb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zdqjudy.top/Article/details/gt2uhbrhfla.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2ospkygwb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenzaomai.com/Article/details/gt2dvhkxhuu.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gt2fahdbycq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ybcxt.top/Article/details/gt2jetbfxfd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuxming.cn/Article/details/gt2mlvrdgot.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sufxvd.cn/Article/details/gt2ckbhahnt.html

TS:   // 同上
来源：http://dali.shuidangran.top/Article/details/gt2zfpuzava.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ehwqpu.com/Article/details/gt2wmteubvy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gaohongyu789.top/Article/details/gt2pjtjkevp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cdnleiting.top/Article/details/gt2bfhfsben.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.316326.xyz/Article/details/gt2yztcujlz.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2cocxgnmb.html

G. 面向对象
来源：http://dali.quarkkingdee.top/Article/details/gt2gmnkjgsw.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2tuttqpub.html

[G01] 定义类
来源：http://dali.cheryme.top/Article/details/gt2tcdanjya.html

Py:   class User: pass
来源：http://dali.gogol.net.cn/Article/details/gt2ghyvbxby.html

PHP:  class User {}
来源：http://dali.cashguo.top/Article/details/gt2mclyabdr.html

JS:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2ygbkersi.html

TS:   class User { name: string = ""; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdmxzlop.html

Java: class User {}
来源：http://dali.iojbl.cn/Article/details/gt2ugpxgowb.html

Go:   type User struct { Name string }
来源：http://dali.yuanzhike.top/Article/details/gt2jqpzcyil.html

Ruby: class User; end
来源：http://dali.gotoacloud.top/Article/details/gt2tcrcrses.html

C#:   class User {}
来源：http://dali.smart0.xyz/Article/details/gt2rbnqreze.html

[G02] 构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2xkielrvg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gt2sygnadlx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cybzivxx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gt2pvhspnnu.html

TS:   constructor(public name: string) {}
来源：http://dali.hfpthk.cn/Article/details/gt2zmqqozdd.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gt2bzvqszhq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.mhx1999.top/Article/details/gt2wpcjgpuo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cheryme.top/Article/details/gt2ubhmykbg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2eahfxwdo.html

[G03] 实例属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txzwduli.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gt2iuvfegmh.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gt2hftqcpqm.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gt2nnmtdplx.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gt2ngghhmwo.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfdbyls.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhongyouzk.top/Article/details/gt2xegujpaq.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gt2yblyqyzr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nhfzfnnw.html

[G04] 定义方法
来源：http://dali.havefunace.top/Article/details/gt2tpymrodf.html

Py:   def greet(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cmhfysgc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gt2bjrdlslg.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2blvlcqab.html

TS:   greet(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gt2wsmhrpei.html

Java: String greet() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tkoyhcme.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gt2tkpayapz.html

Ruby: def greet; @name; end
来源：http://dali.ydzc1.top/Article/details/gt2gssgsxld.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kucqyrgr.html

[G05] 继承
来源：http://dali.svipenyu.cn/Article/details/gt2lwifiitd.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lazqpdfj.html

PHP:  class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2rkmdnmiu.html

JS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2dtirband.html

TS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2puipdhkw.html

Java: class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2couvtpbu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.andypj.xyz/Article/details/gt2thhxrkgg.html

Ruby: class Admin < User; end
来源：http://dali.nanxuanxn.top/Article/details/gt2ejuercvl.html

C#:   class Admin : User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qgjtdyea.html

[G06] 重写方法
来源：http://dali.yuxming.cn/Article/details/gt2aagolfpr.html

Py:   def greet(self): return "admin"
来源：http://dali.yanxiufei.cn/Article/details/gt2isbcqwnj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2ppxzghsa.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2fidxxrcj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2whszydqo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2fpynrtqc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gt2zkjvvfsd.html

Ruby: def greet; "admin"; end
来源：http://dali.tanke756.top/Article/details/gt2sekrihaq.html

C#:   public override string Greet() => "admin";
来源：http://dali.mhx1999.top/Article/details/gt2kpquohlo.html

[G07] 调用父类方法
来源：http://dali.nanxuanxn.top/Article/details/gt2sbgukqtp.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gt2bcujasbp.html

PHP:  parent::greet();
来源：http://dali.sxryk.cn/Article/details/gt2lfgmesja.html

JS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gt2wjaipfru.html

TS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gt2gkoljqrn.html

Java: super.greet();
来源：http://dali.andypj.xyz/Article/details/gt2yefglsfd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hfpthk.cn/Article/details/gt2sbtqjsbb.html

Ruby: super
来源：http://dali.zhiwuduotai.top/Article/details/gt2zpsnkzxc.html

C#:   base.Greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmdbssry.html

[G08] 静态方法与属性
来源：http://dali.havefunace.top/Article/details/gt2evfjexpl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tqhhudgf.html

PHP:  public static function f() {}
来源：http://dali.daria6918.cn/Article/details/gt2wggrrjam.html

JS:   static f() {}
来源：http://dali.redwolf501.top/Article/details/gt2agfemelu.html

TS:   static f(): void {}
来源：http://dali.yj202588.top/Article/details/gt2jszagnyh.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gt2hqskfvdq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cdnleiting.top/Article/details/gt2vosolplt.html

Ruby: def self.f; end
来源：http://dali.dashuyun.cn/Article/details/gt2jiaeuumx.html

C#:   public static void F() {}
来源：http://dali.fzhhl.top/Article/details/gt2hfddrckd.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gt2comeogcl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gt2zgrrhnmo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.havefunace.top/Article/details/gt2trjuqxdo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.0kj1m.cn/Article/details/gt2dqupfsey.html

TS:   interface Shape { area(): number; }
来源：http://dali.kuanghao11.cn/Article/details/gt2biaqpbgy.html

Java: interface Shape { double area(); }
来源：http://dali.nanxinkj.top/Article/details/gt2kzxygkje.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gt2iaonwbxt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2frwjauzv.html

C#:   interface IShape { double Area(); }
来源：http://dali.pycfn.com/Article/details/gt2nypwqbut.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gt2vxusckdp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangshuangyany.cn/Article/details/gt2jvwtcpmg.html

PHP:  public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gt2gbuochaj.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gt2gpvvctni.html

TS:   public / protected / private
来源：http://dali.cashguo.top/Article/details/gt2uznhluvv.html

Java: public / protected / private / 默认包级
来源：http://dali.gogol.net.cn/Article/details/gt2slfpvtfu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nanxinkj.top/Article/details/gt2qgwixjpo.html

Ruby: public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gt2kqmecoaz.html

C#:   public / protected / private / internal
来源：http://dali.zhoulong.xyz/Article/details/gt2dktohsvk.html

[G11] getter / setter
来源：http://dali.jlsjyb.cn/Article/details/gt2iwqankew.html

Py:   @property 与 @x.setter
来源：http://dali.feifeiyinyue.top/Article/details/gt2jyedauws.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2uskxgytp.html

JS:   get name() { return this._name; }
来源：http://dali.316326.xyz/Article/details/gt2whktdlsm.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2zcmbyifb.html

Java: public String getName() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2enadydvn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gt2ibrpjpeo.html

Ruby: attr_accessor :name
来源：http://dali.yj20258.top/Article/details/gt2nhhhdpcq.html

C#:   public string Name { get; set; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qgmmratw.html

[G12] 对象转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmbeqcrm.html

Py:   def __str__(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gt2qdsoaedm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2hvstuqyn.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2uxufhahm.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gt2gluinjzx.html

Java: @Override public String toString() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gt2kkjrqtsy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gt2snqdhxaz.html

Ruby: def to_s; @name; end
来源：http://dali.9152youxi.cn/Article/details/gt2yuryafni.html

C#:   public override string ToString() => Name;
来源：http://dali.yangfankeji.com/Article/details/gt2uzgokdua.html

[G13] 判断对象类型
来源：http://dali.jqgfzy.top/Article/details/gt2ltedvxky.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gt2rmipjipc.html

PHP:  $u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gt2leiaupnh.html

JS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2xntfgrkj.html

TS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gt2jbntbpvj.html

Java: u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2axvvqrko.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuanzhike.top/Article/details/gt2yutbejlz.html

Ruby: u.is_a?(User)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xphecdhc.html

C#:   u is User
来源：http://dali.yanxiufei.cn/Article/details/gt2cqszfgxa.html

[G14] 数据类 / record
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lykjgfuw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cqqwz.cn/Article/details/gt2qxubpans.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cqqwz.cn/Article/details/gt2ogqjfouq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.9152youxi.cn/Article/details/gt2ynmrhhqp.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hbakwvds.html

Java: record User(String name, int age) {}
来源：http://dali.sysykeji.top/Article/details/gt2ypeikgob.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xziqi.cn/Article/details/gt2hvlvjyjf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.316326.xyz/Article/details/gt2cdugqqvm.html

C#:   record User(string Name, int Age);
来源：http://dali.yuxming.cn/Article/details/gt2aucolyxq.html

[G15] 枚举
来源：http://dali.mhx1999.top/Article/details/gt2mdanbhzs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gt2tzdvszne.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.redwolf501.top/Article/details/gt2bvspwjbv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gt2untwpssw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gt2esnkzzwt.html

Java: enum Color { RED, GREEN }
来源：http://dali.hfpthk.cn/Article/details/gt2tbmngtbn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgufenzy.top/Article/details/gt2mneplqpx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gt2gkhuonqo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gt2zwbuojcp.html

[G16] 对象转数组 / 字典
来源：http://dali.cheryme.top/Article/details/gt2jpbmxyvl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gt2hkasevvl.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gt2dgmrkrub.html

JS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vyuvcecr.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gt2kdvunqwr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigfzy.top/Article/details/gt2qzjpyowr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gt2wszsyyhe.html

Ruby: obj.instance_variables
来源：http://dali.bjfxy.top/Article/details/gt2ujoyrhfd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gt2cnpmypdq.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2cfqcniaj.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gt2zyfxlace.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2jwhsnyic.html

[H01] try / catch 基础
来源：http://dali.hfpthk.cn/Article/details/gt2ghfgjruk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangdashe.top/Article/details/gt2qljhufpx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shuidangran.top/Article/details/gt2kbejnqon.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gt2koqdbasz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gt2ohpypwht.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuanzx.com/Article/details/gt2eglkgwql.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sxryk.cn/Article/details/gt2ramtxopv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guannengcc.top/Article/details/gt2gubbyckz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gotoacloud.top/Article/details/gt2itdyzumt.html

[H02] finally / ensure 收尾
来源：http://dali.zhiwuduotai.top/Article/details/gt2rbjwbtiu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.svipenyu.cn/Article/details/gt2jihavijs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2vzbevagn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2fjrdpcxc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2ejyjqlop.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2pecatxfr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guowangkeji.top/Article/details/gt2kzogjlvx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gzhubu.top/Article/details/gt2yjcmrrha.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2wevawyom.html

[H03] 主动抛出异常
来源：http://dali.nanxinkj.top/Article/details/gt2cakdabfq.html

Py:   raise ValueError("错误信息")
来源：http://dali.gzhubu.top/Article/details/gt2nhwjxyuz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2tlotkguz.html

JS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2fklzypnr.html

TS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2tqvcjvjm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2ywdhtkfg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cqqwz.cn/Article/details/gt2xcocumfl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnqzz.top/Article/details/gt2esexqsec.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2xtiehwbl.html

[H04] 自定义异常类型
来源：http://dali.sysykeji.top/Article/details/gt2mqqwihyn.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2svuntyte.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2klzlfedd.html

JS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gt2cmliikpe.html

TS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gt2baxmzbmc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gt2eexsjskz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxlqkxwt.html

Ruby: class MyError < StandardError; end
来源：http://dali.redwolf501.top/Article/details/gt2uqqzojnv.html

C#:   class MyException : Exception {}
来源：http://dali.sufxvd.cn/Article/details/gt2pjwpgigf.html

[H05] 捕获特定类型
来源：http://dali.sufxvd.cn/Article/details/gt2mxmykept.html

Py:   except ValueError as e:
来源：http://dali.zhixingplan.top/Article/details/gt2cksskfbv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuanzx.com/Article/details/gt2hwphqfnh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gt2mdgjugny.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2dmnwiyvv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigufen.top/Article/details/gt2ntsyvqvr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yongpay.top/Article/details/gt2hajqalge.html

Ruby: rescue ArgumentError => e
来源：http://dali.hysaishi.cn/Article/details/gt2munziqwe.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqdsixdx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aizwys.cn/Article/details/gt2chyypmbp.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mecwuuzf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gt2ohxhpelq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gt2paksnkfm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gt2uriasrms.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gt2fwmsfoup.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gt2jinhveqb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lunuhiow.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gt2nephhyco.html

[H07] 断言
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctmrptwx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ubpxiemg.html

PHP:  assert($x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2obvaaguj.html

JS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gt2uogevvyw.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2zrhpvfnc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shzxlz.cn/Article/details/gt2wrllpfqv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gt2ygynpfli.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sysykeji.top/Article/details/gt2xyvvcyzk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2hazvnglq.html

[H08] 获取错误信息与堆栈
来源：http://dali.haohaochexian.top/Article/details/gt2kucoepnh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gt2ennnjkmd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daxiang520.top/Article/details/gt2zavbxwqg.html


<!-- 参考信息 -->