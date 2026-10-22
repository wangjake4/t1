代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2prmskibd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hysaishi.cn/Article/details/gt2ujrfiwhn.html

PHP:  file_exists("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2nigqqiij.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2fieseexa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2rxdhhlsm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2wdmjwlmg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gaohongyu789.top/Article/details/gt2xgyftjny.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cvmangpf.html

C#:   File.Exists("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2opovetcp.html

[F06] 删除文件
来源：http://dali.zhixingplan.top/Article/details/gt2vdfkqjxc.html

Py:   os.remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2chjljkik.html

PHP:  unlink("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2cdqcqigw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2qrmqyian.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2qvwyjbxg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2tctoydkx.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2lecfsufx.html

Ruby: File.delete("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2fhpceapj.html

C#:   File.Delete("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2bhtplgen.html

[F07] 创建目录（含多级）
来源：http://dali.gaohongyu789.top/Article/details/gt2gbisafpw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gt2rqivedbz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhixingplan.top/Article/details/gt2swzojunw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gt2gtppaaqc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gt2oiorsbbi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2plgyvwex.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dwyjkszk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gt2fboznula.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangdashe.top/Article/details/gt2rpvgjspa.html

[F08] 遍历目录
来源：http://dali.316326.xyz/Article/details/gt2fpvxnniq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aibaodan.cn/Article/details/gt2mbftnbpn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sufxvd.cn/Article/details/gt2bqgakcql.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2edrgdosc.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2niruqqod.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gt2unlbnjfs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ivvv.top/Article/details/gt2pnbdvpmm.html

Ruby: Dir.children("dir")
来源：http://dali.pycfn.com/Article/details/gt2wmqbnzle.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ydzc1.top/Article/details/gt2inpumdkr.html

[F09] 获取文件大小
来源：http://dali.ehwqpu.com/Article/details/gt2ukxzraxi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2ofyymtto.html

PHP:  filesize("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2gdqtcndr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gt2opfejtql.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gt2lpyuymdk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2ygekheue.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zcxhilmu.html

Ruby: File.size("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2vempiyid.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigfzy.top/Article/details/gt2hswensnu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gt2qvqtmxfj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2dmmlnwsg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2vhcfifsa.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2krxfmxrx.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2uxbdydyw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.havefunace.top/Article/details/gt2ryghssfn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2xfgtseia.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2cgzsvqhu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2emfiqibi.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gt2oscxsrum.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gt2gzwqfujs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2ptekvzdd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2spuqxlye.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2kkaerwyb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2quimummj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gt2hvobxtkm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2blhfrszl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hfpthk.cn/Article/details/gt2shnnevhe.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gt2flypmtgn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.meibo888.top/Article/details/gt2plcolexq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hongshengwenyu.top/Article/details/gt2ibfgftsz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigufen.top/Article/details/gt2zvjhphsj.html

TS:   // 同上
来源：http://dali.gogol.net.cn/Article/details/gt2zyuysgxk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yangfankeji.com/Article/details/gt2utqmbspj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.meibo888.top/Article/details/gt2bnkddett.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cashguo.top/Article/details/gt2jkmclbvz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gt2obavanbu.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2fdekqqlc.html

G. 面向对象
来源：http://dali.cqqwz.cn/Article/details/gt2ihyftmja.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2efwisyfh.html

[G01] 定义类
来源：http://dali.chenjidiqi.icu/Article/details/gt2czvtwijb.html

Py:   class User: pass
来源：http://dali.shuidangran.top/Article/details/gt2sobdgplo.html

PHP:  class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2wdgyehyh.html

JS:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2etdgwruc.html

TS:   class User { name: string = ""; }
来源：http://dali.chenlongwang.top/Article/details/gt2dbweqjni.html

Java: class User {}
来源：http://dali.ybcxt.top/Article/details/gt2wixsogjf.html

Go:   type User struct { Name string }
来源：http://dali.zhengqikj.top/Article/details/gt2ovqvfvxl.html

Ruby: class User; end
来源：http://dali.gotoacloud.top/Article/details/gt2tdzdkiog.html

C#:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2zcjtmnrr.html

[G02] 构造函数
来源：http://dali.bjfxy.top/Article/details/gt2dnsrpggn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cqqwz.cn/Article/details/gt2wisvneeb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2kpmjhpmr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gt2hnscogbi.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gt2ibstkplu.html

Java: User(String name) { this.name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bydgbbfs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hfpthk.cn/Article/details/gt2bdffvals.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2yosyrlyf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gt2nwkkeuhb.html

[G03] 实例属性
来源：http://dali.svipenyu.cn/Article/details/gt2gnagvhkc.html

Py:   self.name = "x"
来源：http://dali.cashguo.top/Article/details/gt2bjwlcxxi.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gt2mjpxwnpv.html

JS:   this.name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2ombiptgv.html

TS:   name: string = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2buukwpqc.html

Java: private String name;
来源：http://dali.zhixingplan.top/Article/details/gt2zzxqinni.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nwbrower.top/Article/details/gt2pbzbuipt.html

Ruby: @name = "x"
来源：http://dali.iojbl.cn/Article/details/gt2yidbskhm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2hyrskien.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gt2hatvaebg.html

Py:   def greet(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gt2nlkatfcr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gt2cnabwbzw.html

JS:   greet() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2qpbflkgp.html

TS:   greet(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gt2ualzbtjk.html

Java: String greet() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2eehybcgz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gt2idkapvdt.html

Ruby: def greet; @name; end
来源：http://dali.ybcxt.top/Article/details/gt2wfjpajvh.html

C#:   public string Greet() => Name;
来源：http://dali.cqqwz.cn/Article/details/gt2flqoxpqt.html

[G05] 继承
来源：http://dali.nwbrower.top/Article/details/gt2yoqfhnxi.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gt2gpftfimh.html

PHP:  class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2vuismvex.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2tnmjhtco.html

TS:   class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2rqkefjuq.html

Java: class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2dmxjinlx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cqqwz.cn/Article/details/gt2cqwehpfj.html

Ruby: class Admin < User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pszowuem.html

C#:   class Admin : User {}
来源：http://dali.jyoumei.cn/Article/details/gt2ixbriagf.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gt2elszwuox.html

Py:   def greet(self): return "admin"
来源：http://dali.9152youxi.cn/Article/details/gt2udevbgxu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2puawrmwi.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gt2qazisphj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2xbbvdrhs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2vdimafbg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gt2iukqgzpu.html

Ruby: def greet; "admin"; end
来源：http://dali.hammf.cn/Article/details/gt2dezykoia.html

C#:   public override string Greet() => "admin";
来源：http://dali.gogol.net.cn/Article/details/gt2swluynqm.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gt2osmzkwbj.html

Py:   super().greet()
来源：http://dali.hywenlv.cn/Article/details/gt2yychwviw.html

PHP:  parent::greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2hhfixkjf.html

JS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gt2rxdzvslb.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gt2glxijues.html

Java: super.greet();
来源：http://dali.redwolf501.top/Article/details/gt2ezpnzphu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hammf.cn/Article/details/gt2dtexqgof.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gt2ujhtvxjr.html

C#:   base.Greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2obcatsdf.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangtech.top/Article/details/gt2layrtlbb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xinyue.icu/Article/details/gt2fgoeoteu.html

PHP:  public static function f() {}
来源：http://dali.316326.xyz/Article/details/gt2dpihlyxw.html

JS:   static f() {}
来源：http://dali.mhx1999.top/Article/details/gt2pbngwxnf.html

TS:   static f(): void {}
来源：http://dali.sufxvd.cn/Article/details/gt2aarmktcy.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gt2haibqvgu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovbkrwlh.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djtltygy.html

C#:   public static void F() {}
来源：http://dali.cashguo.top/Article/details/gt2rnteryhw.html

[G09] 接口 / 抽象类
来源：http://dali.chenlongwang.top/Article/details/gt2dncgypei.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gt2xttqckov.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.snrcjt.cn/Article/details/gt2smzcrnrv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenjidiqi.icu/Article/details/gt2bahizktg.html

TS:   interface Shape { area(): number; }
来源：http://dali.ppjwa.cn/Article/details/gt2oxyachxr.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gt2nvutfwrl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gt2cnfwjdot.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ivvv.top/Article/details/gt2jgsdcgdx.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gt2utdrrgym.html

[G10] 访问控制
来源：http://dali.snrcjt.cn/Article/details/gt2hfandumv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhiwuduotai.top/Article/details/gt2kiymmqwr.html

PHP:  public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gt2mmifdmuq.html

JS:   #private 字段；其余公开
来源：http://dali.cucudq.cn/Article/details/gt2exeadpts.html

TS:   public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gt2owxhgocs.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gt2nivctiax.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.vqdsnc.cn/Article/details/gt2bnmwhvle.html

Ruby: public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2oxuskzsx.html

C#:   public / protected / private / internal
来源：http://dali.gaohongyu789.top/Article/details/gt2wxwpauwm.html

[G11] getter / setter
来源：http://dali.pengpengdd.cyou/Article/details/gt2stomguea.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigufen.top/Article/details/gt2zgsgkuut.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2wmqbutjw.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2xxvpoqnh.html

TS:   get name(): string { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gt2sfiujege.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2zsggaelb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ljlhhmkj.html

Ruby: attr_accessor :name
来源：http://dali.cashguo.top/Article/details/gt2lpdrbkor.html

C#:   public string Name { get; set; }
来源：http://dali.tian-w.cn/Article/details/gt2cqylafez.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gt2vpdysbpz.html

Py:   def __str__(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gt2vfrtukpa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gt2trgnezpu.html

JS:   toString() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2qonprmcd.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gt2ablufvqs.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj202588.top/Article/details/gt2sfzwrijn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gt2zgiuuwmi.html

Ruby: def to_s; @name; end
来源：http://dali.yangfankeji.com/Article/details/gt2nlubmmkb.html

C#:   public override string ToString() => Name;
来源：http://dali.gogol.net.cn/Article/details/gt2pdmmwmwc.html

[G13] 判断对象类型
来源：http://dali.iojbl.cn/Article/details/gt2bgbrywll.html

Py:   isinstance(u, User)
来源：http://dali.hywenlv.cn/Article/details/gt2qftyhqvo.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2hhqrdawj.html

JS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2sriioprw.html

TS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2jalrflxg.html

Java: u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2thvlsmvm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuanzx.com/Article/details/gt2rwvjjbsj.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gt2ijivpkyx.html

C#:   u is User
来源：http://dali.gaohongyu789.top/Article/details/gt2vkjcfvgv.html

[G14] 数据类 / record
来源：http://dali.daria6918.cn/Article/details/gt2rfpggnil.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuanzhike.top/Article/details/gt2hllrodgg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cashguo.top/Article/details/gt2qtagwfrn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.0kj1m.cn/Article/details/gt2dqfccyui.html

TS:   type User = { name: string; age: number };
来源：http://dali.smart0.xyz/Article/details/gt2ailgjaid.html

Java: record User(String name, int age) {}
来源：http://dali.redwolf501.top/Article/details/gt2kteexdbt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhoulong.xyz/Article/details/gt2jxobogum.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.quarkkingdee.top/Article/details/gt2hvhnzqde.html

C#:   record User(string Name, int Age);
来源：http://dali.kuanghao11.cn/Article/details/gt2dvkokity.html

[G15] 枚举
来源：http://dali.dashuyun.cn/Article/details/gt2dbtnwzqf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258.top/Article/details/gt2jwchdvnd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aibaodan.cn/Article/details/gt2prlkwoal.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gt2lgavchbo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gt2trcwzdfm.html

Java: enum Color { RED, GREEN }
来源：http://dali.jyoumei.cn/Article/details/gt2oaddmmde.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gt2qkxrmldd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zycfv.cn/Article/details/gt2tuidhujs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2wjuqljbe.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gt2ecnmcyiq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj202588.top/Article/details/gt2psphelmo.html

PHP:  get_object_vars($obj);
来源：http://dali.cashguo.top/Article/details/gt2uyiilnox.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooagjqxw.html

TS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgluhjli.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tppdirym.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxuanxn.top/Article/details/gt2ldjplzax.html

Ruby: obj.instance_variables
来源：http://dali.hysaishi.cn/Article/details/gt2tgjzhtae.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gt2vedaltxr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2kvmlecjg.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irruviyc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sstmrryd.html

[H01] try / catch 基础
来源：http://dali.gogol.net.cn/Article/details/gt2kvmztoka.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.iojbl.cn/Article/details/gt2hjovjdkj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.9152youxi.cn/Article/details/gt2lzmpzxhf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gt2ubddafcp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rvgnbgau.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dsqkpbud.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgfzy.top/Article/details/gt2otxjaoit.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gt2ovbpqrxa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gt2jcjkbnny.html

[H02] finally / ensure 收尾
来源：http://dali.svipenyu.cn/Article/details/gt2hdtmpdke.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kscnpvoj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2sltaywlc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2xemwvmjc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2uxzfjxsl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2ufgblnvk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhongyouzk.top/Article/details/gt2kytrireq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ppjwa.cn/Article/details/gt2uunzrhar.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2hflrkwzv.html

[H03] 主动抛出异常
来源：http://dali.gzhubu.top/Article/details/gt2stdgpfbo.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jezqrnxr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2gybxxudo.html

JS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2vrehsnvp.html

TS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2zguahkmg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2ctnshznf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.316326.xyz/Article/details/gt2hyhawzlh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yangfankeji.com/Article/details/gt2zqohxmuj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gt2qrzesrer.html

[H04] 自定义异常类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2bdqzehiz.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gt2hllrrcwq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gt2gjecuhmm.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gt2sqtgjmdc.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gt2eywwzckx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gt2rpqmjtku.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kjvrbwrf.html

Ruby: class MyError < StandardError; end
来源：http://dali.guowangkeji.top/Article/details/gt2nduwvewt.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gt2ioewkhzr.html

[H05] 捕获特定类型
来源：http://dali.zdqjudy.top/Article/details/gt2otrusvnx.html

Py:   except ValueError as e:
来源：http://dali.tanke756.top/Article/details/gt2wtcunvkd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cjfkwnwb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2esvdzsex.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.316326.xyz/Article/details/gt2gcsmcksq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ppjwa.cn/Article/details/gt2qgzfcfpk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbvmmncv.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gt2jihtgeam.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.smart0.xyz/Article/details/gt2ptmxykov.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daxiang520.top/Article/details/gt2nzaudkhk.html

Py:   value = d.get("k") or default
来源：http://dali.wangdashe.top/Article/details/gt2cmayiphs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gt2zbnlbsxc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gt2dyptxhfv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gt2dgjlhpvf.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dianchejie.cn/Article/details/gt2dgxrrpuj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.9152youxi.cn/Article/details/gt2myhkokeq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nktjatzf.html

C#:   obj?.A?.B ?? default
来源：http://dali.ppjwa.cn/Article/details/gt2yriszfxk.html

[H07] 断言
来源：http://dali.iojbl.cn/Article/details/gt2zujabqkb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hammf.cn/Article/details/gt2nmngisym.html

PHP:  assert($x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2skupgyot.html

JS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2omyadpci.html

TS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gt2viayuvqp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xylfe.cn/Article/details/gt2aqihhvai.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.smart0.xyz/Article/details/gt2tqsejouu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.mhx1999.top/Article/details/gt2xtvprifh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2mjuelxmf.html

[H08] 获取错误信息与堆栈
来源：http://dali.xinyue.icu/Article/details/gt2whqlngml.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fzhhl.top/Article/details/gt2gydabsrp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qfklzcem.html

JS:   e.message;  e.stack
来源：http://dali.yangfankeji.com/Article/details/gt2wknchkmu.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daria6918.cn/Article/details/gt2imqgsvyh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pycfn.com/Article/details/gt2kntifsij.html

Go:   err.Error()
来源：http://dali.zhixingplan.top/Article/details/gt2uxtweway.html

Ruby: e.message;  e.backtrace
来源：http://dali.guowangkeji.top/Article/details/gt2hsfxeixg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ppjwa.cn/Article/details/gt2clhuhpxv.html

[H09] 带错误码的异常
来源：http://dali.quarkkingdee.top/Article/details/gt2xcleskmj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hywenlv.cn/Article/details/gt2edmenzsy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenlongwang.top/Article/details/gt2eleynpmk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.svipenyu.cn/Article/details/gt2abafbwil.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ygzkudku.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.iojbl.cn/Article/details/gt2dnznuruc.html


<!-- 参考信息 -->