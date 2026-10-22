代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fengsongda.top/Article/details/gt2jbyrogot.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenzaomai.com/Article/details/gt2nqhiekdc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gt2wdqqdqfh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qnbcrpxf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uvnmqpqa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vytdnfjt.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gt2augcbtwg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxuanxn.top/Article/details/gt2hcaodfsi.html

[F05] 判断文件或目录是否存在
来源：http://dali.tianlin.xyz/Article/details/gt2rakvmhgi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxuanxn.top/Article/details/gt2nqtxhhtd.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2inmqkgaz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2eumfkubb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2umutxaxt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gt2qyobbtnn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pengpengdd.cyou/Article/details/gt2cchuxkkh.html

Ruby: File.exist?("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2fvclzbhh.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2fpxujxes.html

[F06] 删除文件
来源：http://dali.zhengqikj.top/Article/details/gt2ozctnera.html

Py:   os.remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2cgfvtwer.html

PHP:  unlink("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2xmwvcrvz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkribxmi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2cuvguawf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gt2cuptxorg.html

Go:   os.Remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2bgnoihjs.html

Ruby: File.delete("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2jdhadhtl.html

C#:   File.Delete("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2yzgxpsky.html

[F07] 创建目录（含多级）
来源：http://dali.feifeiyinyue.top/Article/details/gt2dbvzeosb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gt2ofjeyqqs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgufenzy.top/Article/details/gt2gmcdrghu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gt2urpqfony.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gt2akwdcvmp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.smart0.xyz/Article/details/gt2lipmekde.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ftfcoghu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yanxiufei.cn/Article/details/gt2rpzbzjez.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.birdmap.top/Article/details/gt2tzpbpxmg.html

[F08] 遍历目录
来源：http://dali.9152youxi.cn/Article/details/gt2anmkigqz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yongpay.top/Article/details/gt2akzpefwv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shuidangran.top/Article/details/gt2ktuihcao.html

JS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2qopevaxx.html

TS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gt2nhzenxex.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gt2sreugsfa.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2xmqanwlj.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2ccnvkigr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ghqtboie.html

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gt2nwikavij.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2wremyfcg.html

PHP:  filesize("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2yjbybvcm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gt2uzbuarfg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gt2mvqvmvjo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhqccchd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daxiang520.top/Article/details/gt2bzflycyr.html

Ruby: File.size("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2uaqlnegi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.quarkkingdee.top/Article/details/gt2aqqmpezk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gt2htueqjhc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2qubnqiel.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2oloseutp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2kknzdxzd.html

TS:   path.extname("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2eabtuwlw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2szvsujuu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqjvifva.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2tukgtscs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2trekqvmo.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gt2gtgbvqzn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2dedmdyyn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ivvv.top/Article/details/gt2kkzrnlee.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhwpfwx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2hqsrklfq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.snrcjt.cn/Article/details/gt2uvyeftbu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangdashe.top/Article/details/gt2gugsqqwg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2zbannpyt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gt2wkwjjcia.html

[F12] CSV 读写
来源：http://dali.wangdashe.top/Article/details/gt2gcjsceig.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gt2okxtfkdn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnqzz.top/Article/details/gt2avdkzsci.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dianchejie.cn/Article/details/gt2stjwuglx.html

TS:   // 同上
来源：http://dali.haohaochexian.top/Article/details/gt2notmhfyz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gt2jhcveemp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.0kj1m.cn/Article/details/gt2dmeyfzrq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gt2igfrceue.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.birdmap.top/Article/details/gt2bcehovcs.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2mletjalc.html

G. 面向对象
来源：http://dali.hywenlv.cn/Article/details/gt2gwiovvds.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2dqorzxzz.html

[G01] 定义类
来源：http://dali.jianghu66.top/Article/details/gt2etyfcwdr.html

Py:   class User: pass
来源：http://dali.hongshengwenyu.top/Article/details/gt2khgijsia.html

PHP:  class User {}
来源：http://dali.zycfv.cn/Article/details/gt2lqnwqdrk.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2trlzdrgx.html

TS:   class User { name: string = ""; }
来源：http://dali.ybcxt.top/Article/details/gt2gjzlmbks.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2qwxedfkn.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gt2qerfzxoz.html

Ruby: class User; end
来源：http://dali.aibaodan.cn/Article/details/gt2xpvhcgac.html

C#:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhnfdujl.html

[G02] 构造函数
来源：http://dali.xinyue.icu/Article/details/gt2znfnmmxb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gotoacloud.top/Article/details/gt2zqenwthz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dianchejie.cn/Article/details/gt2vpwkjgre.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dtuwcghk.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yjeaejsd.html

Java: User(String name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gt2zuvbpbav.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhongyouzk.top/Article/details/gt2duriwduk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2vadmlrvh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mugoaxuh.html

[G03] 实例属性
来源：http://dali.cdnleiting.top/Article/details/gt2flbqfuol.html

Py:   self.name = "x"
来源：http://dali.sysykeji.top/Article/details/gt2vazegkws.html

PHP:  public string $name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2ppumdpmq.html

JS:   this.name = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2njfgqbot.html

TS:   name: string = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cmfsppxt.html

Java: private String name;
来源：http://dali.daxiang520.top/Article/details/gt2obueupxm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxuanxn.top/Article/details/gt2mnhothaw.html

Ruby: @name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gt2dixyfabi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daxiang520.top/Article/details/gt2hvmqdnci.html

[G04] 定义方法
来源：http://dali.vqdsnc.cn/Article/details/gt2dabyjffs.html

Py:   def greet(self): return self.name
来源：http://dali.yonumen.top/Article/details/gt2sowqygrn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gt2acuedjgu.html

JS:   greet() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2nzpbpffp.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gt2bsvsrixx.html

Java: String greet() { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2jkltssaw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gt2ryvlyvvd.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gt2idcuxxct.html

C#:   public string Greet() => Name;
来源：http://dali.cucudq.cn/Article/details/gt2xousqxnr.html

[G05] 继承
来源：http://dali.jlsjyb.cn/Article/details/gt2sdqictcf.html

Py:   class Admin(User): pass
来源：http://dali.hnxiangtu.top/Article/details/gt2dqlglmzf.html

PHP:  class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jjqtmasn.html

JS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gt2ksoedyaa.html

TS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gt2yntstzox.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2awdpuqwr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.feifeiyinyue.top/Article/details/gt2fipwungz.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gt2qhjclbco.html

C#:   class Admin : User {}
来源：http://dali.ybcxt.top/Article/details/gt2pzcniayi.html

[G06] 重写方法
来源：http://dali.jqgufenzy.top/Article/details/gt2pgdccbuy.html

Py:   def greet(self): return "admin"
来源：http://dali.ybcxt.top/Article/details/gt2qcezmuos.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2gyiitwpl.html

JS:   greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2kprmsjuy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2tefsdtks.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2hptagrek.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenjidiqi.icu/Article/details/gt2hcmlvcpn.html

Ruby: def greet; "admin"; end
来源：http://dali.havefunace.top/Article/details/gt2rjlsvonq.html

C#:   public override string Greet() => "admin";
来源：http://dali.havefunace.top/Article/details/gt2qicmwwcm.html

[G07] 调用父类方法
来源：http://dali.gotoacloud.top/Article/details/gt2bmbhiisu.html

Py:   super().greet()
来源：http://dali.hammf.cn/Article/details/gt2tyzepkkk.html

PHP:  parent::greet();
来源：http://dali.xziqi.cn/Article/details/gt2woeflbka.html

JS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zggxzebd.html

TS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gt2vptbsxmi.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gt2dbvyysxq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gt2fjgtcucj.html

Ruby: super
来源：http://dali.birdmap.top/Article/details/gt2yjotycoc.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gt2dvcveglk.html

[G08] 静态方法与属性
来源：http://dali.hnxiangtu.top/Article/details/gt2mggrcwzo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jlsjyb.cn/Article/details/gt2wrzwlwuy.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gt2qxnpwvix.html

JS:   static f() {}
来源：http://dali.sysykeji.top/Article/details/gt2wansdwdl.html

TS:   static f(): void {}
来源：http://dali.yonumen.top/Article/details/gt2ezzakfmp.html

Java: static void f() {}
来源：http://dali.gzhubu.top/Article/details/gt2umuadwtg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pengpengdd.cyou/Article/details/gt2mlucbmen.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gt2xtplbfpa.html

C#:   public static void F() {}
来源：http://dali.andypj.xyz/Article/details/gt2lcraweza.html

[G09] 接口 / 抽象类
来源：http://dali.shzxlz.cn/Article/details/gt2faereamm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gt2xptdrxvc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gt2twzzsnvs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fzhhl.top/Article/details/gt2eprtxgaa.html

TS:   interface Shape { area(): number; }
来源：http://dali.jyoumei.cn/Article/details/gt2exgieavh.html

Java: interface Shape { double area(); }
来源：http://dali.guannengcc.top/Article/details/gt2bunyrkmn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangdashe.top/Article/details/gt2zssufkks.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gt2dccbinhd.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gt2yldpfvia.html

[G10] 访问控制
来源：http://dali.gotoacloud.top/Article/details/gt2rucyvcfz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gt2ggpesqfu.html

PHP:  public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gt2olhhsrbl.html

JS:   #private 字段；其余公开
来源：http://dali.ivvv.top/Article/details/gt2wcpposly.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gt2uizjibge.html

Java: public / protected / private / 默认包级
来源：http://dali.yvedp.cn/Article/details/gt2lptwhvob.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aibaodan.cn/Article/details/gt2tnrgmopb.html

Ruby: public / protected / private
来源：http://dali.bjfxy.top/Article/details/gt2dkfijgjj.html

C#:   public / protected / private / internal
来源：http://dali.sysykeji.top/Article/details/gt2pwfrgfqi.html

[G11] getter / setter
来源：http://dali.jlsjyb.cn/Article/details/gt2drzrjmzs.html

Py:   @property 与 @x.setter
来源：http://dali.jlsjyb.cn/Article/details/gt2bifkkchn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2gmdgfrbn.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gt2lewtvpjh.html

TS:   get name(): string { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gt2ihuurxhl.html

Java: public String getName() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2wohpqbgy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gt2eflriexq.html

Ruby: attr_accessor :name
来源：http://dali.xuetiantiany.cn/Article/details/gt2kpbfrawu.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258888.top/Article/details/gt2axddoigr.html

[G12] 对象转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ljejktcs.html

Py:   def __str__(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gt2lszknmag.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gt2rsagovvt.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2syesjnxi.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2jlsbbsqb.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gt2zgmpgyoy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2lrielref.html

Ruby: def to_s; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2hbjfgshd.html

C#:   public override string ToString() => Name;
来源：http://dali.cashguo.top/Article/details/gt2eldekugf.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gt2xgszwbsx.html

Py:   isinstance(u, User)
来源：http://dali.xziqi.cn/Article/details/gt2svlsyixj.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2nbpfwhly.html

JS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2pnxcrnib.html

TS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2levptfoq.html

Java: u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azmshoof.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gt2zqcncmyx.html

Ruby: u.is_a?(User)
来源：http://dali.zhoulong.xyz/Article/details/gt2zpbplzee.html

C#:   u is User
来源：http://dali.nwbrower.top/Article/details/gt2ibwngfww.html

[G14] 数据类 / record
来源：http://dali.jyoumei.cn/Article/details/gt2ydzlkiyz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mbclfpkg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nwbrower.top/Article/details/gt2ftkfavex.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zycfv.cn/Article/details/gt2pixrziss.html

TS:   type User = { name: string; age: number };
来源：http://dali.ehwqpu.com/Article/details/gt2mwmdodty.html

Java: record User(String name, int age) {}
来源：http://dali.cucudq.cn/Article/details/gt2vlgitrey.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gt2tmggctcj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigufen.top/Article/details/gt2xdawwcir.html

C#:   record User(string Name, int Age);
来源：http://dali.yuxming.cn/Article/details/gt2nscyjlfn.html

[G15] 枚举
来源：http://dali.yangfankeji.com/Article/details/gt2corakfeo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gt2pbwvkzjo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2uarhwgwo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cheryme.top/Article/details/gt2ngelzhjk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tkjdopqn.html

Java: enum Color { RED, GREEN }
来源：http://dali.nwbrower.top/Article/details/gt2jzglvmsg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nwbrower.top/Article/details/gt2opzuesph.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gt2ochgrlbo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gt2dfupkffg.html

[G16] 对象转数组 / 字典
来源：http://dali.birdmap.top/Article/details/gt2attxncub.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxuanxn.top/Article/details/gt2bpemblzs.html

PHP:  get_object_vars($obj);
来源：http://dali.yuanzhike.top/Article/details/gt2uigdjggo.html

JS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gt2awbouumc.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2asejtcyd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhengqikj.top/Article/details/gt2zqbzvanp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.haohaochexian.top/Article/details/gt2hvceomav.html

Ruby: obj.instance_variables
来源：http://dali.ybcxt.top/Article/details/gt2iozwshxf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gt2sytiriik.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2cjnshrwf.html

H. 异常与错误处理
来源：http://dali.chenzaomai.com/Article/details/gt2kujbvgko.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2wuqmwbjm.html

[H01] try / catch 基础
来源：http://dali.hnxiangtu.top/Article/details/gt2yfbfxgyg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.haohaochexian.top/Article/details/gt2rtpgclvb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gt2gzpopscq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gt2wavtdifp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gt2lnezlvna.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shzxlz.cn/Article/details/gt2ioqnemym.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.9152youxi.cn/Article/details/gt2keeabaci.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.9152youxi.cn/Article/details/gt2atpmakfi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gt2txtybgur.html

[H02] finally / ensure 收尾
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fnlyddoc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xinyue.icu/Article/details/gt2itkzuxqi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2rmetxhgg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2wgzqvzjy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2phfsewmt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2trvaedel.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.mhx1999.top/Article/details/gt2wgpmrvpk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gt2celubtiu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2jbthdiwc.html

[H03] 主动抛出异常
来源：http://dali.xinyue.icu/Article/details/gt2xlvmtwmq.html

Py:   raise ValueError("错误信息")
来源：http://dali.tanke756.top/Article/details/gt2qqdgxrcp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gt2tvueocew.html

JS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2kveuokmo.html

TS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gt2uxrtndrm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2ujpuojte.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.birdmap.top/Article/details/gt2oxoumbui.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shangyingyoupin.top/Article/details/gt2jcdbtljx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2mueerevm.html

[H04] 自定义异常类型
来源：http://dali.bjfxy.top/Article/details/gt2mbbxoalv.html

Py:   class MyError(Exception): pass
来源：http://dali.vqdsnc.cn/Article/details/gt2nuiyyscn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gt2avuxawqr.html

JS:   class MyError extends Error {}
来源：http://dali.yonumen.top/Article/details/gt2astncnlc.html

TS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gt2zkejyjqk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gt2siwivdxq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sxryk.cn/Article/details/gt2nkailvrw.html

Ruby: class MyError < StandardError; end
来源：http://dali.ybcxt.top/Article/details/gt2bqpgwgro.html

C#:   class MyException : Exception {}
来源：http://dali.zdqjudy.top/Article/details/gt2psjxfqpt.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gt2mnhpofak.html

Py:   except ValueError as e:
来源：http://dali.ppjwa.cn/Article/details/gt2uwsdmxse.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenzaomai.com/Article/details/gt2kdrifons.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2kublwvti.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gt2cgkaotyh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gt2plfieeun.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhongyouzk.top/Article/details/gt2ivecptfk.html

Ruby: rescue ArgumentError => e
来源：http://dali.birdmap.top/Article/details/gt2gwjexqwq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ppjwa.cn/Article/details/gt2uujpfvni.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gt2epxgddli.html

Py:   value = d.get("k") or default
来源：http://dali.aizwys.cn/Article/details/gt2zklwxfbp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gt2rrdrhhkx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gt2kftxeqnc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2vpplogwo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xziqi.cn/Article/details/gt2lgrlfokp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2skiwbaty.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cemnskmy.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgufenzy.top/Article/details/gt2xozewpyi.html

[H07] 断言
来源：http://dali.haohaochexian.top/Article/details/gt2jalidavp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gt2vtttiirp.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2cqawostw.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2xggtgrag.html

TS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2jrdqhggh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.dashuyun.cn/Article/details/gt2iyfywnta.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xbuaihdx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gt2exsdqivr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2ypsnlqjk.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangtech.top/Article/details/gt2znbqhlcu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hongshengwenyu.top/Article/details/gt2inokkckq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhiwuduotai.top/Article/details/gt2qwndemxs.html

JS:   e.message;  e.stack
来源：http://dali.dianchejie.cn/Article/details/gt2gkyahcvq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.quarkkingdee.top/Article/details/gt2beorofxm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xziqi.cn/Article/details/gt2suwwlleq.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gt2xxjsvwcm.html


<!-- 参考信息 -->