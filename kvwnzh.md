代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2fpxaodlu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2tiuviuue.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tnbscydk.html

Ruby: File.exist?("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2imalbxad.html

C#:   File.Exists("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2sigejses.html

[F06] 删除文件
来源：http://dali.jiagoushi.top/Article/details/gt2pmpldskm.html

Py:   os.remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2tkahlugz.html

PHP:  unlink("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2uteeaoop.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2lrnrbuzu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2yyrtcqoj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gt2rzjykjkk.html

Go:   os.Remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2yhqzehaa.html

Ruby: File.delete("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xewmkpcj.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2pjcflich.html

[F07] 创建目录（含多级）
来源：http://dali.hysaishi.cn/Article/details/gt2tqczhcwq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xinyue.icu/Article/details/gt2hwjxtbmc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ushaaowd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zweqnnfg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gt2ycczcito.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fengsongda.top/Article/details/gt2zvjbxwhy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yongpay.top/Article/details/gt2ryydhktw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj202588.top/Article/details/gt2dmyiqptl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yvedp.cn/Article/details/gt2gecpqxrv.html

[F08] 遍历目录
来源：http://dali.cdnleiting.top/Article/details/gt2rzqgstbh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hammf.cn/Article/details/gt2xkmuelhw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gaohongyu789.top/Article/details/gt2qblmmmqs.html

JS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gt2xbscpoll.html

TS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gt2afmwbeuz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gt2hdwaczhn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2njaipgbl.html

Ruby: Dir.children("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2hmtzjzyf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2itqdgmim.html

[F09] 获取文件大小
来源：http://dali.ybcxt.top/Article/details/gt2bpbzjmvj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sweek.top/Article/details/gt2viawxgdd.html

PHP:  filesize("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2ygkvvfyk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ultadzbm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gt2rjsianaw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2thqohjac.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gt2rzxtpfma.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2lptzmtkj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.kuanghao11.cn/Article/details/gt2hgsxcklo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cucudq.cn/Article/details/gt2ookjvuln.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2yxhnivpg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2tbfbcjur.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2egfcgwpj.html

TS:   path.extname("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2yolpfoyc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gt2dzavboub.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2seppliay.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2pzmhfmls.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2dmfnywxd.html

[F11] 复制与移动文件
来源：http://dali.yj20258888.top/Article/details/gt2mgnlvxvv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2amqtqqfs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guannengcc.top/Article/details/gt2kjgqudfl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2cxyekkyy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2uqklnvhn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lifucecl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guannengcc.top/Article/details/gt2hqhlbxje.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2hiwaeouw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pengpengdd.cyou/Article/details/gt2trufvcii.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gt2arfyqrdf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.svipenyu.cn/Article/details/gt2jaywdfap.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xinyue.icu/Article/details/gt2xgnsuuyc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigufen.top/Article/details/gt2ndjcxqlq.html

TS:   // 同上
来源：http://dali.jqgfzy.top/Article/details/gt2niarkjnu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daxiang520.top/Article/details/gt2fzxushsi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zdqjudy.top/Article/details/gt2tpqussxi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gt2sgyvxjme.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wwidwwdl.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2mgdhpvfq.html

G. 面向对象
来源：http://dali.zhiwuduotai.top/Article/details/gt2iwwegepf.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2yclmasic.html

[G01] 定义类
来源：http://dali.iojbl.cn/Article/details/gt2dhejfbco.html

Py:   class User: pass
来源：http://dali.yvedp.cn/Article/details/gt2nguiflgv.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gt2qihywqmi.html

JS:   class User {}
来源：http://dali.zycfv.cn/Article/details/gt2wtkncgtb.html

TS:   class User { name: string = ""; }
来源：http://dali.zhongyouzk.top/Article/details/gt2xxcqnjgc.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gt2gdwambqq.html

Go:   type User struct { Name string }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yevdrdom.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gt2htklluqc.html

C#:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2ctqnhrpz.html

[G02] 构造函数
来源：http://dali.zhengqikj.top/Article/details/gt2twvunend.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dashuyun.cn/Article/details/gt2bhulcwoy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yueranfly.top/Article/details/gt2ksvqvfhm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gt2bvmxqhzs.html

TS:   constructor(public name: string) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtgbizlk.html

Java: User(String name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gt2cywrxxxs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gt2kzcnfzjz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jyoumei.cn/Article/details/gt2ubfdqkos.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2natqsyzs.html

[G03] 实例属性
来源：http://dali.chenzaomai.com/Article/details/gt2mhlslvrn.html

Py:   self.name = "x"
来源：http://dali.ydzc1.top/Article/details/gt2tttqsflb.html

PHP:  public string $name = "x";
来源：http://dali.daxiang520.top/Article/details/gt2mrkinpzx.html

JS:   this.name = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2mwmiirnz.html

TS:   name: string = "x";
来源：http://dali.yj20258.top/Article/details/gt2wjbaxubb.html

Java: private String name;
来源：http://dali.sxryk.cn/Article/details/gt2gnnxvpdw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gt2tqtzwmyr.html

Ruby: @name = "x"
来源：http://dali.chenzaomai.com/Article/details/gt2hxiktbuz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2dfkkdjad.html

[G04] 定义方法
来源：http://dali.gaohongyu789.top/Article/details/gt2ldungqbv.html

Py:   def greet(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gt2gtekkswa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gt2fvbrubrg.html

JS:   greet() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2qzgdetjh.html

TS:   greet(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gt2tkahbkeg.html

Java: String greet() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gt2dyymcaua.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hieaxrta.html

Ruby: def greet; @name; end
来源：http://dali.cashguo.top/Article/details/gt2nycvemrq.html

C#:   public string Greet() => Name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ffwuzpey.html

[G05] 继承
来源：http://dali.wangdashe.top/Article/details/gt2juqkahtp.html

Py:   class Admin(User): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2brtddskt.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2izpkmsrr.html

JS:   class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2crwkmzhi.html

TS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2efpmmoug.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2yhkswnhv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuxming.cn/Article/details/gt2wvpkvphz.html

Ruby: class Admin < User; end
来源：http://dali.hfpthk.cn/Article/details/gt2pknmghby.html

C#:   class Admin : User {}
来源：http://dali.shuidangran.top/Article/details/gt2uuxzwuun.html

[G06] 重写方法
来源：http://dali.gzhubu.top/Article/details/gt2vjfkjgnx.html

Py:   def greet(self): return "admin"
来源：http://dali.fengsongda.top/Article/details/gt2hprufdhh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2qylscuix.html

JS:   greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2xedowukt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2uxrkpnge.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2lhoakxcc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuanzx.com/Article/details/gt2mllsqroz.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxuanxn.top/Article/details/gt2opazxiut.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangshuangyany.cn/Article/details/gt2vfvbjznk.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gt2gahouyzl.html

Py:   super().greet()
来源：http://dali.cashguo.top/Article/details/gt2qqvgnsqn.html

PHP:  parent::greet();
来源：http://dali.haohaochexian.top/Article/details/gt2axhqkyie.html

JS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gt2xwfliegk.html

TS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gt2nvfyuoab.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2wrwlceah.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfbtgzb.html

Ruby: super
来源：http://dali.gzhubu.top/Article/details/gt2tznzahpz.html

C#:   base.Greet();
来源：http://dali.svipenyu.cn/Article/details/gt2swzkxihs.html

[G08] 静态方法与属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2fjppuhmj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wlfaeyki.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gt2wbvdjagh.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddlqwabj.html

TS:   static f(): void {}
来源：http://dali.daria6918.cn/Article/details/gt2ivmgqusa.html

Java: static void f() {}
来源：http://dali.aizwys.cn/Article/details/gt2otldmaje.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jreeeefg.html

Ruby: def self.f; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2ussldqqg.html

C#:   public static void F() {}
来源：http://dali.yj20258888.top/Article/details/gt2owpfdhdv.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigfzy.top/Article/details/gt2gniimwig.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fzhhl.top/Article/details/gt2hzrukmte.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnxiangtu.top/Article/details/gt2cqtxxpue.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gt2nlludrkf.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gt2vsruinwc.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gt2pbxlikyg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hipadsnw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gt2pfbfkzoc.html

C#:   interface IShape { double Area(); }
来源：http://dali.tianlin.xyz/Article/details/gt2crucsoec.html

[G10] 访问控制
来源：http://dali.yangfankeji.com/Article/details/gt2whkhtjek.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ahcpsagf.html

PHP:  public / protected / private
来源：http://dali.yvedp.cn/Article/details/gt2wxxpiluy.html

JS:   #private 字段；其余公开
来源：http://dali.shzxlz.cn/Article/details/gt2cdkvfatg.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2bowvanfi.html

Java: public / protected / private / 默认包级
来源：http://dali.yuanzhike.top/Article/details/gt2lybbqaeu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gt2dbnjuzzn.html

Ruby: public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gt2ldcmvjqo.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qatwupis.html

[G11] getter / setter
来源：http://dali.ppjwa.cn/Article/details/gt2eqvxrmtb.html

Py:   @property 与 @x.setter
来源：http://dali.sweek.top/Article/details/gt2rttauzsm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2ckwccmgt.html

JS:   get name() { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gt2ucidizqu.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gt2vvwrutvl.html

Java: public String getName() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2evppnmro.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2jxttyfmz.html

Ruby: attr_accessor :name
来源：http://dali.jinqigufen.top/Article/details/gt2mryewseb.html

C#:   public string Name { get; set; }
来源：http://dali.ppjwa.cn/Article/details/gt2piakepdw.html

[G12] 对象转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oobkmqoa.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gt2qdtxdkcy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gt2urgxuxaw.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2ehmnqfkl.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2fngqbpvh.html

Java: @Override public String toString() { return name; }
来源：http://dali.sweek.top/Article/details/gt2tptqgfxr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gt2boirkuqx.html

Ruby: def to_s; @name; end
来源：http://dali.aibaodan.cn/Article/details/gt2fcwalkbo.html

C#:   public override string ToString() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gt2eeuesfly.html

[G13] 判断对象类型
来源：http://dali.ppjwa.cn/Article/details/gt2tnvuldtg.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gt2prbsoicx.html

PHP:  $u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2dalkavua.html

JS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gt2oyrgamva.html

TS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2tnmylxih.html

Java: u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gt2fuswmrje.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nwbrower.top/Article/details/gt2zpivynbx.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2snhmmczz.html

C#:   u is User
来源：http://dali.jqgufenzy.top/Article/details/gt2iqblaokr.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gt2nwhmzpwg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iwvaeeqy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cdnleiting.top/Article/details/gt2tqlxoemy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ybcxt.top/Article/details/gt2rkmkqwxf.html

TS:   type User = { name: string; age: number };
来源：http://dali.yvedp.cn/Article/details/gt2dngsemmg.html

Java: record User(String name, int age) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2unbhumhp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhoulong.xyz/Article/details/gt2ncoinrhp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgpsellg.html

C#:   record User(string Name, int Age);
来源：http://dali.jiagoushi.top/Article/details/gt2vbbtcxos.html

[G15] 枚举
来源：http://dali.zdqjudy.top/Article/details/gt2shyzfvle.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenzaomai.com/Article/details/gt2scvydskr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rmbpqxzb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gt2gevhgzpa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yqiaxegy.html

Java: enum Color { RED, GREEN }
来源：http://dali.yueranfly.top/Article/details/gt2exabqxfj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvdjjwnd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gt2ybrgthum.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gt2vfqoxkzg.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gt2wzzpnlbs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xinyue.icu/Article/details/gt2nozqqfwq.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gt2hbvxbblf.html

JS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2djzfmajs.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zmqocmos.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gt2sobvjopi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rvwtxkck.html

Ruby: obj.instance_variables
来源：http://dali.yanxiufei.cn/Article/details/gt2oezrtlqf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gt2kwpunzpu.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2dckmomgs.html

H. 异常与错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gt2lvhchufg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2pbyctpsb.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gt2vqcdqvhx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.birdmap.top/Article/details/gt2dsdykeyh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2vymjapcv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gt2luuvbgfu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kvivghzf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gt2auuubpam.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnqzz.top/Article/details/gt2ozbectbv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hysaishi.cn/Article/details/gt2vnzrjlxs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258.top/Article/details/gt2hlrllmtj.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gt2ycqynkxp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.0kj1m.cn/Article/details/gt2yihnbpsd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gt2qwharnqp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ywckxomt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gt2nznaezey.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2hqyjhqcw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.316326.xyz/Article/details/gt2jjxzdnip.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2ndxtfbhs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2lqiyonoi.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gnurvmnr.html

Py:   raise ValueError("错误信息")
来源：http://dali.ybcxt.top/Article/details/gt2heepbfol.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2fjredcwr.html

JS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2swflmszc.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2jppggrhv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2ojpuzbtv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gt2psprpkfh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.0kj1m.cn/Article/details/gt2iryyyvzi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gt2pvemeapq.html

[H04] 自定义异常类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2zeghdzmt.html

Py:   class MyError(Exception): pass
来源：http://dali.0kj1m.cn/Article/details/gt2mftzwdwy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gt2mvofxwvs.html

JS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gt2rekwkqfz.html

TS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gt2kotmfeut.html

Java: class MyException extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gt2gxrciqrx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tianlin.xyz/Article/details/gt2zwcjdtfe.html

Ruby: class MyError < StandardError; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pkbcdlpt.html

C#:   class MyException : Exception {}
来源：http://dali.xinyue.icu/Article/details/gt2mzaklkex.html

[H05] 捕获特定类型
来源：http://dali.ppjwa.cn/Article/details/gt2dkvncymw.html

Py:   except ValueError as e:
来源：http://dali.mhx1999.top/Article/details/gt2koagnxzo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenlongwang.top/Article/details/gt2zywpkbzz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gt2yafexgna.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gt2xogyttfw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvcmovp.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yonumen.top/Article/details/gt2ffwwzrnt.html

Ruby: rescue ArgumentError => e
来源：http://dali.xinyue.icu/Article/details/gt2yetfwqmj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuxming.cn/Article/details/gt2rmzwghkq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ybcxt.top/Article/details/gt2yubnoshy.html

Py:   value = d.get("k") or default
来源：http://dali.haohaochexian.top/Article/details/gt2dkdsmuse.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pycfn.com/Article/details/gt2ekkdfelh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gt2nvjpuphc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.quarkkingdee.top/Article/details/gt2dgkvbwya.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.havefunace.top/Article/details/gt2kgctggcx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gt2dhmfyhra.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdcnicpe.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2nwofafys.html

[H07] 断言
来源：http://dali.ydzc1.top/Article/details/gt2gpvpzjwz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ydzc1.top/Article/details/gt2aevhrkaf.html

PHP:  assert($x > 0);
来源：http://dali.meibo888.top/Article/details/gt2amjousrs.html

JS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2klmmvwns.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gt2bbtfeqsm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gt2cagqelwx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yanxiufei.cn/Article/details/gt2jwnwkggg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258888.top/Article/details/gt2cztcnymd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2injoceyn.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2mnbbmrhp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.kuanghao11.cn/Article/details/gt2okjtpurf.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gt2uomockla.html

JS:   e.message;  e.stack
来源：http://dali.yongpay.top/Article/details/gt2egdgnkfr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.snrcjt.cn/Article/details/gt2xzthubov.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hywenlv.cn/Article/details/gt2tkovdrcp.html

Go:   err.Error()
来源：http://dali.jianghu66.top/Article/details/gt2jeeagbyy.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhoulong.xyz/Article/details/gt2mzsqmwfm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hysaishi.cn/Article/details/gt2dcwgnwnq.html

[H09] 带错误码的异常
来源：http://dali.zhixingplan.top/Article/details/gt2xzmmrwsu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zycfv.cn/Article/details/gt2mrcyeejl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xuanzx.com/Article/details/gt2kjsrddro.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ivvv.top/Article/details/gt2pxxnkidd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gt2skseedle.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gt2noamlymo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.c1oappe.top/Article/details/gt2fnhwxajb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xdbuefvu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.9152youxi.cn/Article/details/gt2bxusnoph.html

[H10] 资源自动释放
来源：http://dali.hnqzz.top/Article/details/gt2wnnefxkw.html


<!-- 参考信息 -->