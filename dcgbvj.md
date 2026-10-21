代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtzxpbgzmq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtqchinycv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ybcxt.top/Article/details/gtejxuhfdc.html

Ruby: File.exist?("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtyjjozdrl.html

C#:   File.Exists("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtozdoiinz.html

[F06] 删除文件
来源：http://dali.jiagoushi.top/Article/details/gticptlwgm.html

Py:   os.remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gtglsrzelk.html

PHP:  unlink("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtqjdgnyzx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtizbtygem.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtdtvbvpjr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtdbhsvcug.html

Go:   os.Remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtcbimfmwx.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtpsqutnfn.html

C#:   File.Delete("a.txt");
来源：http://dali.yj202588.top/Article/details/gtgjtumqkz.html

[F07] 创建目录（含多级）
来源：http://dali.jianghu66.top/Article/details/gtedbdsyau.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gtiyodzzwt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aibaodan.cn/Article/details/gtmnzngqkx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gtlyehcmcy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtuoiduirl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jianghu66.top/Article/details/gthzhpkgqr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yangfankeji.com/Article/details/gtwxglvjqf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.feifeiyinyue.top/Article/details/gtbicsqlaa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazgqdixd.html

[F08] 遍历目录
来源：http://dali.sufxvd.cn/Article/details/gttnbeeshi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhixingplan.top/Article/details/gtsyjxvzod.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gtpvqycfbq.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtnxbnpxsl.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gtodtofsrc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtmqcnmlzs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gtsgpzdpsx.html

Ruby: Dir.children("dir")
来源：http://dali.shzxlz.cn/Article/details/gtxwvdfvkj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sweek.top/Article/details/gtzwaxjopf.html

[F09] 获取文件大小
来源：http://dali.daxiang520.top/Article/details/gtzgtchdah.html

Py:   os.path.getsize("a.txt")
来源：http://dali.havefunace.top/Article/details/gtrgjsnkia.html

PHP:  filesize("a.txt");
来源：http://dali.pycfn.com/Article/details/gtmbtsdclk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gtedgjwyfj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.kuanghao11.cn/Article/details/gtoqsekrlk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtkyazmurq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yonumen.top/Article/details/gtllinqhpy.html

Ruby: File.size("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtabqjxezc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yangfankeji.com/Article/details/gtxajbbaiy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shuidangran.top/Article/details/gtjgrqladw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtzlilizos.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuxming.cn/Article/details/gtvxxypmsr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkyqdvdti.html

TS:   path.extname("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gteglcveco.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrjshwhi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtolifufgs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtrcrpauaa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtuwbffrgd.html

[F11] 复制与移动文件
来源：http://dali.feifeiyinyue.top/Article/details/gtxpfoyxqe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtzeoflpfu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ppjwa.cn/Article/details/gtfumeknpe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtagshlpcu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtjtwvsxks.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtktduwzxc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aizwys.cn/Article/details/gtsurcvqkg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtzcquggvj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aibaodan.cn/Article/details/gtlfmllscu.html

[F12] CSV 读写
来源：http://dali.ehwqpu.com/Article/details/gthujplule.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guannengcc.top/Article/details/gtlpyxbtlo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cqqwz.cn/Article/details/gtvzvedday.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhiwuduotai.top/Article/details/gtocjwokbr.html

TS:   // 同上
来源：http://dali.hnqzz.top/Article/details/gtggqbtcmz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dianchejie.cn/Article/details/gtxxpesamm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.haohaochexian.top/Article/details/gthxkgcmsg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fengsongda.top/Article/details/gtujdgwnxn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenzaomai.com/Article/details/gtcpequcmk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtcqrfycpx.html

G. 面向对象
来源：http://dali.hywenlv.cn/Article/details/gtlzbbbxez.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtvmpzqcxd.html

[G01] 定义类
来源：http://dali.gotoacloud.top/Article/details/gtpjwpzwkc.html

Py:   class User: pass
来源：http://dali.feifeiyinyue.top/Article/details/gtxmcvzedw.html

PHP:  class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtqtkidlfg.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gtytelannr.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpjtupbd.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gthrwejqkv.html

Go:   type User struct { Name string }
来源：http://dali.316326.xyz/Article/details/gtafsgevio.html

Ruby: class User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvjnddkp.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtibngwkkr.html

[G02] 构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtcowfhjlw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yvedp.cn/Article/details/gtvbefwnuo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gthpmiexyf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gttmankwwq.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtqeymruzj.html

Java: User(String name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtifkyumov.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nwbrower.top/Article/details/gtyhycnpmu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtpqxqxzcw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtqkgwjdox.html

[G03] 实例属性
来源：http://dali.xylfe.cn/Article/details/gttffeeypc.html

Py:   self.name = "x"
来源：http://dali.zycfv.cn/Article/details/gtmtfftmwu.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gtvkbrhiwh.html

JS:   this.name = "x";
来源：http://dali.yvedp.cn/Article/details/gthdckitsm.html

TS:   name: string = "x";
来源：http://dali.316326.xyz/Article/details/gtjvkpmhlt.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gtdygxxglb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gtxyekivfc.html

Ruby: @name = "x"
来源：http://dali.sysykeji.top/Article/details/gtzmwdewtv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzwferlz.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gtuvtulrrc.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtmlvasboi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gthhgtcype.html

JS:   greet() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtyyzjrzdx.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtaiolfwvb.html

Java: String greet() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtrunrxgnz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtcgogkogd.html

Ruby: def greet; @name; end
来源：http://dali.0kj1m.cn/Article/details/gtorzafjez.html

C#:   public string Greet() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtfggvbitj.html

[G05] 继承
来源：http://dali.yj20258.top/Article/details/gtfmfrbaes.html

Py:   class Admin(User): pass
来源：http://dali.xinyue.icu/Article/details/gteaxleoqs.html

PHP:  class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtmtmmczdx.html

JS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtespvmwdn.html

TS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtlofyhlge.html

Java: class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtltyyhtuh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yongpay.top/Article/details/gtncygiohb.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gtiiiclioe.html

C#:   class Admin : User {}
来源：http://dali.ivvv.top/Article/details/gtfmuwqrrc.html

[G06] 重写方法
来源：http://dali.yuxming.cn/Article/details/gtmemiynzs.html

Py:   def greet(self): return "admin"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjciqgmtx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtaojxrnzb.html

JS:   greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtqwitocat.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtgtylhaqh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtzgancdcf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gtiqiazbwe.html

Ruby: def greet; "admin"; end
来源：http://dali.yuxming.cn/Article/details/gtamhmbdtf.html

C#:   public override string Greet() => "admin";
来源：http://dali.daria6918.cn/Article/details/gtfsscfrkc.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gthhqsyodr.html

Py:   super().greet()
来源：http://dali.wangdashe.top/Article/details/gtydyjurwl.html

PHP:  parent::greet();
来源：http://dali.316326.xyz/Article/details/gttpmnyuhm.html

JS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtdwhnktnl.html

TS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtcvabtquu.html

Java: super.greet();
来源：http://dali.hammf.cn/Article/details/gtowcfvzzy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhixingplan.top/Article/details/gtxjinqnrb.html

Ruby: super
来源：http://dali.snrcjt.cn/Article/details/gtfxgeygiw.html

C#:   base.Greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgrcviqp.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gtrpzaqucu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhgfydte.html

PHP:  public static function f() {}
来源：http://dali.jinqigufen.top/Article/details/gtmtzbueuk.html

JS:   static f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtqrvcrlue.html

TS:   static f(): void {}
来源：http://dali.cashguo.top/Article/details/gtfctnmqam.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtskvasvzy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhengqikj.top/Article/details/gtakrqidby.html

Ruby: def self.f; end
来源：http://dali.cashguo.top/Article/details/gtyfluvbzl.html

C#:   public static void F() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtaylkloip.html

[G09] 接口 / 抽象类
来源：http://dali.ehwqpu.com/Article/details/gteoeyofdo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nanxinkj.top/Article/details/gtsxderngy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gtosdzstbd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnxiangtu.top/Article/details/gtmssemdcv.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gtjgvakytd.html

Java: interface Shape { double area(); }
来源：http://dali.meibo888.top/Article/details/gtedwmbjny.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangshuangyany.cn/Article/details/gtlgivpqnc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gtoapgjoia.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnqzz.top/Article/details/gtzgzgnbdl.html

[G10] 访问控制
来源：http://dali.zdqjudy.top/Article/details/gtzmffafhw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gtxgwhrgmp.html

PHP:  public / protected / private
来源：http://dali.sweek.top/Article/details/gthlkfwuem.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gtwsnqlxtw.html

TS:   public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtnxsbsolm.html

Java: public / protected / private / 默认包级
来源：http://dali.zycfv.cn/Article/details/gtvanlvwde.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhiwuduotai.top/Article/details/gtzzgmyxuo.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtfjukrrpo.html

C#:   public / protected / private / internal
来源：http://dali.zhengqikj.top/Article/details/gtcsrpyoby.html

[G11] getter / setter
来源：http://dali.guowangkeji.top/Article/details/gtaqlgslmh.html

Py:   @property 与 @x.setter
来源：http://dali.hnxiangtu.top/Article/details/gtvkfedpcv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzzbtzsev.html

JS:   get name() { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gtsnwkufaz.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtkkgdeppg.html

Java: public String getName() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtiubqbxbk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtmnxorqvy.html

Ruby: attr_accessor :name
来源：http://dali.sweek.top/Article/details/gtuqmvzezt.html

C#:   public string Name { get; set; }
来源：http://dali.xylfe.cn/Article/details/gttmttfxwo.html

[G12] 对象转字符串
来源：http://dali.ybcxt.top/Article/details/gtliucemvq.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtcwrtqhiz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtyfgqlkyj.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gthsdbgjpz.html

TS:   toString(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtejtlybtx.html

Java: @Override public String toString() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtixqwxpya.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtxsitzixu.html

Ruby: def to_s; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtccisrdlo.html

C#:   public override string ToString() => Name;
来源：http://dali.redwolf501.top/Article/details/gtkxwnsubg.html

[G13] 判断对象类型
来源：http://dali.feifeiyinyue.top/Article/details/gtjnhsuyja.html

Py:   isinstance(u, User)
来源：http://dali.ppjwa.cn/Article/details/gtzmaegahz.html

PHP:  $u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtnfcbdrqg.html

JS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtymlhoaka.html

TS:   u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gthufrkubf.html

Java: u instanceof User
来源：http://dali.316326.xyz/Article/details/gtymhooonp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sweek.top/Article/details/gtaljuwhbv.html

Ruby: u.is_a?(User)
来源：http://dali.guowangkeji.top/Article/details/gtgdrainlr.html

C#:   u is User
来源：http://dali.0kj1m.cn/Article/details/gtlafwhsed.html

[G14] 数据类 / record
来源：http://dali.ehwqpu.com/Article/details/gtimhzmtal.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gttbmxbvrf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.bjfxy.top/Article/details/gtvlsrxbyb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.andypj.xyz/Article/details/gtqiyouead.html

TS:   type User = { name: string; age: number };
来源：http://dali.fzhhl.top/Article/details/gttjsgbkvo.html

Java: record User(String name, int age) {}
来源：http://dali.havefunace.top/Article/details/gtagbqyyyk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tian-w.cn/Article/details/gtnvbulhke.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gtapitmxbg.html

C#:   record User(string Name, int Age);
来源：http://dali.havefunace.top/Article/details/gtrjpvoigu.html

[G15] 枚举
来源：http://dali.gotoacloud.top/Article/details/gttqtephqc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.smart0.xyz/Article/details/gtfpthksve.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pycfn.com/Article/details/gtwvdzajga.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnquhtwar.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtjuihzmrj.html

Java: enum Color { RED, GREEN }
来源：http://dali.hnxiangtu.top/Article/details/gtydijfllh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqimqfjt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.meibo888.top/Article/details/gtwjrqwxcs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtirvtwmhb.html

[G16] 对象转数组 / 字典
来源：http://dali.sufxvd.cn/Article/details/gtajgazdtx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.fzhhl.top/Article/details/gttermrgnq.html

PHP:  get_object_vars($obj);
来源：http://dali.zdqjudy.top/Article/details/gtdtknjydo.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gtoszecfob.html

TS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtyruvkhnh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgufenzy.top/Article/details/gtrzoyzrvw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbxkegku.html

Ruby: obj.instance_variables
来源：http://dali.zycfv.cn/Article/details/gthhpfcodq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.wangshuangyany.cn/Article/details/gtntauaiab.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtrmvhmlbr.html

H. 异常与错误处理
来源：http://dali.ehwqpu.com/Article/details/gtvunvswws.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtxrecpqlg.html

[H01] try / catch 基础
来源：http://dali.jqgfzy.top/Article/details/gthzldirud.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgufenzy.top/Article/details/gtirpwrlqi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shzxlz.cn/Article/details/gtvzjbgnuo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtfoskwips.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtyljslpgm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gtcdpbfzan.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sysykeji.top/Article/details/gtckgmxhmb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangdashe.top/Article/details/gtafjxzeis.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtforwfzxz.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gtdhjjtktf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhongyouzk.top/Article/details/gtmkhtdrzf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtprwvjyvl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtwadshbch.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtuoqxlvam.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtgtbyxdxl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gtyhduccxn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.haohaochexian.top/Article/details/gtopnzwhmj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtmvclwbsj.html

[H03] 主动抛出异常
来源：http://dali.jiagoushi.top/Article/details/gteskkvdjg.html

Py:   raise ValueError("错误信息")
来源：http://dali.jyoumei.cn/Article/details/gtxenqffvf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtahdirgta.html

JS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtymlczwen.html

TS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gtqxueaqbm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtamweltjq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gttpcukdzx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.andypj.xyz/Article/details/gtjlivzcjg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtcaqzzwyr.html

[H04] 自定义异常类型
来源：http://dali.shanyushiyangtech.top/Article/details/gteazgahnp.html

Py:   class MyError(Exception): pass
来源：http://dali.aizwys.cn/Article/details/gtdvnepyhe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gtigacccxa.html

JS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrrpjjde.html

TS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtyskxmnfr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gtemgjlknc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gtkakqaunu.html

Ruby: class MyError < StandardError; end
来源：http://dali.cashguo.top/Article/details/gtwzraazic.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gtkgbvrwnc.html

[H05] 捕获特定类型
来源：http://dali.xuanzx.com/Article/details/gtluybsrbv.html

Py:   except ValueError as e:
来源：http://dali.gotoacloud.top/Article/details/gtevjohdta.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gaohongyu789.top/Article/details/gtpejnnimm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtaqzzbthm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtvjeyputv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.316326.xyz/Article/details/gtbjtergyz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ydzc1.top/Article/details/gtydeluofo.html

Ruby: rescue ArgumentError => e
来源：http://dali.sxryk.cn/Article/details/gtudkjzykp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hammf.cn/Article/details/gttkbnyidq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jianghu66.top/Article/details/gtvqvjemqo.html

Py:   value = d.get("k") or default
来源：http://dali.dianchejie.cn/Article/details/gtlnjlsuqh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gtpwirjrgb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtboezbfjk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gthownlhqn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pengpengdd.cyou/Article/details/gtoglvpowk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmeaqvfrg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgufenzy.top/Article/details/gtvwxqcvvv.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gttvdwwxad.html

[H07] 断言
来源：http://dali.dianchejie.cn/Article/details/gtywioxsbx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgufenzy.top/Article/details/gtlubpqdod.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtzsdcdqyy.html

JS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtezmixmct.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtoyfkhywu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zdqjudy.top/Article/details/gtsxvjqgdq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.quarkkingdee.top/Article/details/gtricvqdtb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hongshengwenyu.top/Article/details/gtxnijcjjr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtcyjpntwo.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gtahxzunlr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jyoumei.cn/Article/details/gtxjxrepyv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gtnjwzpgrq.html

JS:   e.message;  e.stack
来源：http://dali.c1oappe.top/Article/details/gtuofczklq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cdnleiting.top/Article/details/gtkuzyisfi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ydzc1.top/Article/details/gtrkjufurm.html

Go:   err.Error()
来源：http://dali.sxryk.cn/Article/details/gtbcmrmvbj.html

Ruby: e.message;  e.backtrace
来源：http://dali.jyoumei.cn/Article/details/gtyiusvois.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gtgesiidve.html

[H09] 带错误码的异常
来源：http://dali.mhx1999.top/Article/details/gtqpolosil.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gtfusqdgvb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gzhubu.top/Article/details/gtbjxkwecj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gtybltllhx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daxiang520.top/Article/details/gtyanncxue.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzwmczilc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gtfejxdori.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yvedp.cn/Article/details/gtxpbnkcgw.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cucudq.cn/Article/details/gtcvgnnzrt.html

[H10] 资源自动释放
来源：http://dali.hnxiangtu.top/Article/details/gtpurakrib.html


<!-- 参考信息 -->