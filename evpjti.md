代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gpyghsya.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.vqdsnc.cn/Article/details/gt2oasgonyl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mjiwznaa.html

[F04] 追加写入文件
来源：http://dali.yuanzhike.top/Article/details/gt2kytofoki.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2aoyghwda.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pengpengdd.cyou/Article/details/gt2bgpncqge.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2zheicuml.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2amdpycar.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj202588.top/Article/details/gt2bekjosdz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.svipenyu.cn/Article/details/gt2pwrgbpuf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tian-w.cn/Article/details/gt2wnvbikjh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gt2eckdjeei.html

[F05] 判断文件或目录是否存在
来源：http://dali.tian-w.cn/Article/details/gt2hondlmaj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jlsjyb.cn/Article/details/gt2zzbylgtu.html

PHP:  file_exists("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2fpfvjkgu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2ocjopxvx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2qighlbdz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2xeyfjjmp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dianchejie.cn/Article/details/gt2qfqbaluk.html

Ruby: File.exist?("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2niifvdtj.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2qopteopi.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gt2mrsozzcl.html

Py:   os.remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2jznfolsr.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2htflogiv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wqfblgsk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2trjaoxrk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2ffxlafpv.html

Go:   os.Remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2cxznfkyi.html

Ruby: File.delete("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2rsfrbjgc.html

C#:   File.Delete("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2nopuqcqm.html

[F07] 创建目录（含多级）
来源：http://dali.feifeiyinyue.top/Article/details/gt2rrxjszyd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gt2iwzdvzlo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj202588.top/Article/details/gt2gwyaumbv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gt2swixevyp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gt2fqksuxvv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fzhhl.top/Article/details/gt2rnpejrof.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ifwhwevx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mymbxoea.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hywenlv.cn/Article/details/gt2udgotohu.html

[F08] 遍历目录
来源：http://dali.shuidangran.top/Article/details/gt2plasesft.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gt2srexemyw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.vqdsnc.cn/Article/details/gt2dwncerqg.html

JS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2lcxgzljm.html

TS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gt2rtrqhhjn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gt2pvlilnqz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hysaishi.cn/Article/details/gt2wotanwhm.html

Ruby: Dir.children("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mljguxsz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yonumen.top/Article/details/gt2bztununq.html

[F09] 获取文件大小
来源：http://dali.nanxuanxn.top/Article/details/gt2mcmwxkka.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2aorevxun.html

PHP:  filesize("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2ocfgouzb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gt2wdjsyimt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gt2zxfgvbvq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgzcwbus.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gt2bocuksyq.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sjezfdop.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2libvuvnh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ybcxt.top/Article/details/gt2vblhyidl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2ofnlstns.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2ogkqypid.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2nobqxnam.html

TS:   path.extname("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2kenubexp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dpucbevh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2ukzxhnea.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2onkpyqzv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ufmxyvni.html

[F11] 复制与移动文件
来源：http://dali.hnxiangtu.top/Article/details/gt2jieawhhi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2dynqbzjf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hammf.cn/Article/details/gt2itidzjqa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjzfjdig.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfspafui.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hpkxqzbg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jianghu66.top/Article/details/gt2gtiibrqk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bimtygah.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.9152youxi.cn/Article/details/gt2ioqjbemz.html

[F12] CSV 读写
来源：http://dali.xuetiantiany.cn/Article/details/gt2qarsmzsq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gaohongyu789.top/Article/details/gt2dtkfocdw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangdashe.top/Article/details/gt2rvdfjwti.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhoulong.xyz/Article/details/gt2lulbtlpu.html

TS:   // 同上
来源：http://dali.jianghu66.top/Article/details/gt2auaxkwoz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yueranfly.top/Article/details/gt2tmxioikj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gt2lhpzbfbx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ivvv.top/Article/details/gt2xekecnjx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gt2lqbpcakp.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2rafkwynt.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gt2bjgwukrr.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2qiruvree.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gt2owhvwnyn.html

Py:   class User: pass
来源：http://dali.aizwys.cn/Article/details/gt2tpymgcrk.html

PHP:  class User {}
来源：http://dali.xinyue.icu/Article/details/gt2qwqjehqv.html

JS:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2tahpjjqv.html

TS:   class User { name: string = ""; }
来源：http://dali.jlsjyb.cn/Article/details/gt2jcgsahfx.html

Java: class User {}
来源：http://dali.fengsongda.top/Article/details/gt2lwnfqelw.html

Go:   type User struct { Name string }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2acshfnvr.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gt2pwxgnjur.html

C#:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2triotpoi.html

[G02] 构造函数
来源：http://dali.zdqjudy.top/Article/details/gt2qxkkoymz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gt2agdsndjm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258.top/Article/details/gt2txptabua.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2xrgccweb.html

TS:   constructor(public name: string) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ajfolsfp.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2imjyxeeb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gt2xmifezpr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2hzuaqmby.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hfpthk.cn/Article/details/gt2kkliwxrf.html

[G03] 实例属性
来源：http://dali.hongshengwenyu.top/Article/details/gt2uibkvzfu.html

Py:   self.name = "x"
来源：http://dali.guowangkeji.top/Article/details/gt2gseayyqp.html

PHP:  public string $name = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2qmxbigzm.html

JS:   this.name = "x";
来源：http://dali.aizwys.cn/Article/details/gt2bbbpezfd.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2tbttqmog.html

Java: private String name;
来源：http://dali.tanke756.top/Article/details/gt2manyybno.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tian-w.cn/Article/details/gt2nttolziy.html

Ruby: @name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gt2vmrmiwvd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2jgmaxwbt.html

[G04] 定义方法
来源：http://dali.jqgfzy.top/Article/details/gt2hhklnimd.html

Py:   def greet(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gt2rnjcpmvw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2xvtraiwy.html

JS:   greet() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gt2qvsbhhfe.html

TS:   greet(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gt2njinphpp.html

Java: String greet() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zdhtdonr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gt2bqfzrroj.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gt2ryvmruko.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gt2asohmnxe.html

[G05] 继承
来源：http://dali.xylfe.cn/Article/details/gt2hmpnnenv.html

Py:   class Admin(User): pass
来源：http://dali.ybcxt.top/Article/details/gt2xunwadef.html

PHP:  class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2rmeyczbd.html

JS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2tatjilcg.html

TS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2cgwsanvw.html

Java: class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2uspaekxu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgufenzy.top/Article/details/gt2ezakllmc.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gt2eaczwopk.html

C#:   class Admin : User {}
来源：http://dali.cqqwz.cn/Article/details/gt2ipucoecj.html

[G06] 重写方法
来源：http://dali.fzhhl.top/Article/details/gt2lhabnrgj.html

Py:   def greet(self): return "admin"
来源：http://dali.birdmap.top/Article/details/gt2ukndisrz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gt2zgwigjvm.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gt2cgpepltw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hxbldwqv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gt2shznjjri.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zycfv.cn/Article/details/gt2jfaohfod.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2qycvpngv.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangdashe.top/Article/details/gt2bywabgtu.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gt2jhlgnczx.html

Py:   super().greet()
来源：http://dali.wangshuangyany.cn/Article/details/gt2usseomtx.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gt2rgvnoxtt.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2zigulbjy.html

TS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gt2slhvbcmg.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gt2ihzhizis.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gt2jszugiuu.html

Ruby: super
来源：http://dali.cheryme.top/Article/details/gt2jsdtodlc.html

C#:   base.Greet();
来源：http://dali.iojbl.cn/Article/details/gt2ydajiamv.html

[G08] 静态方法与属性
来源：http://dali.jinqigufen.top/Article/details/gt2brjbwmze.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.bjfxy.top/Article/details/gt2cvxtvewu.html

PHP:  public static function f() {}
来源：http://dali.xziqi.cn/Article/details/gt2aipkepvd.html

JS:   static f() {}
来源：http://dali.yuxming.cn/Article/details/gt2dwqaefyq.html

TS:   static f(): void {}
来源：http://dali.sufxvd.cn/Article/details/gt2skndqseh.html

Java: static void f() {}
来源：http://dali.cheryme.top/Article/details/gt2utmpgpjw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ivvv.top/Article/details/gt2gcasemks.html

Ruby: def self.f; end
来源：http://dali.chenlongwang.top/Article/details/gt2sdqjdhrl.html

C#:   public static void F() {}
来源：http://dali.quarkkingdee.top/Article/details/gt2hjkrvxko.html

[G09] 接口 / 抽象类
来源：http://dali.zhixingplan.top/Article/details/gt2dnzuehyt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.quarkkingdee.top/Article/details/gt2ndbojeiw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258888.top/Article/details/gt2nyguigoz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.haohaochexian.top/Article/details/gt2wnfwdtzy.html

TS:   interface Shape { area(): number; }
来源：http://dali.0kj1m.cn/Article/details/gt2wishlqpx.html

Java: interface Shape { double area(); }
来源：http://dali.guannengcc.top/Article/details/gt2idwbmbrd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tanke756.top/Article/details/gt2yylxplnf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sysykeji.top/Article/details/gt2kkvmiaql.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuanzx.com/Article/details/gt2xxjgqkxs.html

[G10] 访问控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yobncypr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gt2rzriggpi.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2jqcepnwl.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gt2vhfvpwjh.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gt2oavyrrvg.html

Java: public / protected / private / 默认包级
来源：http://dali.andypj.xyz/Article/details/gt2vnrmiwae.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ehwqpu.com/Article/details/gt2dckzgorw.html

Ruby: public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gt2iofvxser.html

C#:   public / protected / private / internal
来源：http://dali.nwbrower.top/Article/details/gt2hmxquawp.html

[G11] getter / setter
来源：http://dali.pycfn.com/Article/details/gt2gjwuhqtw.html

Py:   @property 与 @x.setter
来源：http://dali.jqgfzy.top/Article/details/gt2jmdiqtuv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ptunptxa.html

JS:   get name() { return this._name; }
来源：http://dali.birdmap.top/Article/details/gt2yrxelvmv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gt2rsmdqwhk.html

Java: public String getName() { return name; }
来源：http://dali.aizwys.cn/Article/details/gt2vyafildx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2xffjzrjb.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gt2runssgcs.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gt2poweireg.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dscbvyco.html

Py:   def __str__(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gt2rzljnice.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gt2secfompi.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gt2zvokikwc.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2wrrstbsw.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2xrmoufya.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zgeqvmrf.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigufen.top/Article/details/gt2tzbrmxig.html

C#:   public override string ToString() => Name;
来源：http://dali.guowangkeji.top/Article/details/gt2yopuvjlv.html

[G13] 判断对象类型
来源：http://dali.ydzc1.top/Article/details/gt2upnklsli.html

Py:   isinstance(u, User)
来源：http://dali.yueranfly.top/Article/details/gt2dphkmmul.html

PHP:  $u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bjvksimo.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2fgpdoebm.html

TS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gt2qqtllwuf.html

Java: u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2dcmbyuvf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xinyue.icu/Article/details/gt2frsoiqrp.html

Ruby: u.is_a?(User)
来源：http://dali.xuanzx.com/Article/details/gt2zjgxhdsh.html

C#:   u is User
来源：http://dali.ppjwa.cn/Article/details/gt2prwweihz.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gt2avezhndi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jiagoushi.top/Article/details/gt2kyzzqhns.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cqqwz.cn/Article/details/gt2jtethdjt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gt2vqmamtri.html

TS:   type User = { name: string; age: number };
来源：http://dali.ehwqpu.com/Article/details/gt2aonexmjo.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gt2ymmbtccs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gt2pbirwrtw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnnthqk.html

C#:   record User(string Name, int Age);
来源：http://dali.0kj1m.cn/Article/details/gt2ghgtsphs.html

[G15] 枚举
来源：http://dali.cashguo.top/Article/details/gt2lzlphokm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gaohongyu789.top/Article/details/gt2zwxcnphu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.meibo888.top/Article/details/gt2xdcurnty.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cqqwz.cn/Article/details/gt2tmjgegle.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gt2fxirvnlc.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gt2iqqwcjqr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gt2aliahdje.html

Ruby: Color = %i[red green].freeze
来源：http://dali.9152youxi.cn/Article/details/gt2gayyrntf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnotfjlv.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dpimmrpu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yonumen.top/Article/details/gt2uuqehhyr.html

PHP:  get_object_vars($obj);
来源：http://dali.sxryk.cn/Article/details/gt2sdupiekb.html

JS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gt2mkwyhexd.html

TS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gt2bpxroelp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenjidiqi.icu/Article/details/gt2biosyaxl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenlongwang.top/Article/details/gt2cnkvxrri.html

Ruby: obj.instance_variables
来源：http://dali.sufxvd.cn/Article/details/gt2wtvowqyx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gt2ryitpafu.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2pbbvmhzh.html

H. 异常与错误处理
来源：http://dali.shuidangran.top/Article/details/gt2mchqsdgz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2nlupfahx.html

[H01] try / catch 基础
来源：http://dali.yonumen.top/Article/details/gt2biqtetcy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jyoumei.cn/Article/details/gt2xrvxrihw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2ygqfxtuf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gt2bccyyzgj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gt2abmxmbzr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tianlin.xyz/Article/details/gt2nmtymzqg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2ldjtbbka.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2zogivkcy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dashuyun.cn/Article/details/gt2tqhrscur.html

[H02] finally / ensure 收尾
来源：http://dali.chenjidiqi.icu/Article/details/gt2itzaoydf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ppjwa.cn/Article/details/gt2ntmfjcon.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cnmtpjja.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2isgksusu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2lqjlnhwh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2newtjtnh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daria6918.cn/Article/details/gt2silwylcu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ppjwa.cn/Article/details/gt2febvouqt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2crgdhyxk.html

[H03] 主动抛出异常
来源：http://dali.yangfankeji.com/Article/details/gt2valahssv.html

Py:   raise ValueError("错误信息")
来源：http://dali.yongpay.top/Article/details/gt2hgstqqiv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2pshdysxh.html

JS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2fqggbkyy.html

TS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2aefweiww.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2vqhhdlbj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yanxiufei.cn/Article/details/gt2fkzzhowh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhengqikj.top/Article/details/gt2nyrftyve.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2himiwbzq.html

[H04] 自定义异常类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2raixhvjx.html

Py:   class MyError(Exception): pass
来源：http://dali.mhx1999.top/Article/details/gt2cyzpznji.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gt2xsboqzli.html

JS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gt2qpahistj.html

TS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ylbmowsk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cqqwz.cn/Article/details/gt2epnxipwk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gt2imjnrtzu.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhixingplan.top/Article/details/gt2uoxaojga.html

C#:   class MyException : Exception {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2mtdovwdy.html

[H05] 捕获特定类型
来源：http://dali.c1oappe.top/Article/details/gt2tzpnbojk.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gt2oibtaked.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sxryk.cn/Article/details/gt2lkhjpktc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gt2cjnhekeu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gt2cupaubcc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.svipenyu.cn/Article/details/gt2ddswkccl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aibaodan.cn/Article/details/gt2prdgvhrd.html

Ruby: rescue ArgumentError => e
来源：http://dali.shzxlz.cn/Article/details/gt2vbvdmqsx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2clwywiuz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ijhlvyky.html

Py:   value = d.get("k") or default
来源：http://dali.nanxuanxn.top/Article/details/gt2rwuawppy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gt2jzisghfi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gt2xwlvuboy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gt2dtbwlyjr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.vqdsnc.cn/Article/details/gt2ofijpdfw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuanzhike.top/Article/details/gt2jmgfxsce.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zdqjudy.top/Article/details/gt2gvimvnxz.html

C#:   obj?.A?.B ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ycyrbimk.html

[H07] 断言
来源：http://dali.sysykeji.top/Article/details/gt2cgfuzxxi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hammf.cn/Article/details/gt2welisjil.html

PHP:  assert($x > 0);
来源：http://dali.havefunace.top/Article/details/gt2cczcuodb.html

JS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gt2skkewuik.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2xcfcvhlr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.nanxuanxn.top/Article/details/gt2ijqftlno.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.andypj.xyz/Article/details/gt2uictjnuf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxinkj.top/Article/details/gt2wfosncpw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2ietzfhzg.html

[H08] 获取错误信息与堆栈
来源：http://dali.dashuyun.cn/Article/details/gt2yglgiyis.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj202588.top/Article/details/gt2sdupowed.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.quarkkingdee.top/Article/details/gt2axbgqoti.html


<!-- 参考信息 -->