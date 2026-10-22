代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2xueqdxtz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gt2ntofmoss.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2okuunuju.html

Ruby: File.exist?("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2xcwrmphe.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2frvviocs.html

[F06] 删除文件
来源：http://dali.pycfn.com/Article/details/gt2ftrzchdt.html

Py:   os.remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2eaphlfdv.html

PHP:  unlink("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2itdteqqo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2xsjhnijc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2zayoekvk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gt2tcscxjua.html

Go:   os.Remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2ucdnofqa.html

Ruby: File.delete("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2nbqwhuqt.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2bowokzcv.html

[F07] 创建目录（含多级）
来源：http://dali.ybcxt.top/Article/details/gt2vejebsdv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jxqtggpk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cashguo.top/Article/details/gt2zszgainu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hpldbjmi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gt2uxjkcuqd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hysaishi.cn/Article/details/gt2ioehxarw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zdqjudy.top/Article/details/gt2qzhnjgzc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nwbrower.top/Article/details/gt2ocznwtkz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258888.top/Article/details/gt2sqvarkmr.html

[F08] 遍历目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pmrnaumz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guannengcc.top/Article/details/gt2vftajalt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxuanxn.top/Article/details/gt2znnruehh.html

JS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gt2pztolyqz.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2qfqlapif.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hfpthk.cn/Article/details/gt2csdqtylm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2rztpdwdq.html

Ruby: Dir.children("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2rivbgghz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2quxtftkt.html

[F09] 获取文件大小
来源：http://dali.fengsongda.top/Article/details/gt2wmdggons.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2pcqzozrt.html

PHP:  filesize("a.txt");
来源：http://dali.sweek.top/Article/details/gt2zmowhjkh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gt2vlzegcqu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gt2cosyfwny.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zhmegbyp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rssknamg.html

Ruby: File.size("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2ycrdqptv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gt2kleidjtn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hammf.cn/Article/details/gt2cqwixwue.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2npvfwakv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2fyvdtbtn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2sesibdgc.html

TS:   path.extname("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2ecqzhpwc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhiwuduotai.top/Article/details/gt2cultrxkh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2immkesva.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2nffugdhh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2gvfwiayn.html

[F11] 复制与移动文件
来源：http://dali.pycfn.com/Article/details/gt2xenziphz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2gxoausvu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.meibo888.top/Article/details/gt2vjirqwwv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2hxvsvymh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2ljazuaxo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gt2vvtmjqqv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhengqikj.top/Article/details/gt2gihpyaeg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2sgfqtjwc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gt2tykepfle.html

[F12] CSV 读写
来源：http://dali.chenlongwang.top/Article/details/gt2bohcihxe.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.haohaochexian.top/Article/details/gt2skjalkzs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.vqdsnc.cn/Article/details/gt2qslbepiv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cucudq.cn/Article/details/gt2uhzqxlvw.html

TS:   // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzksrdgp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gt2ipwapilu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhiwuduotai.top/Article/details/gt2aglsxmdk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigufen.top/Article/details/gt2bxxoyplc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdmhzdzs.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2feiymzpl.html

G. 面向对象
来源：http://dali.jinqigfzy.top/Article/details/gt2xwnlltfm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2rysrlcwy.html

[G01] 定义类
来源：http://dali.ydzc1.top/Article/details/gt2xxwojpip.html

Py:   class User: pass
来源：http://dali.xziqi.cn/Article/details/gt2stdzngsj.html

PHP:  class User {}
来源：http://dali.cucudq.cn/Article/details/gt2tqpopqie.html

JS:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2bfbhdsas.html

TS:   class User { name: string = ""; }
来源：http://dali.meibo888.top/Article/details/gt2hzthyckn.html

Java: class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2evvsqzao.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gt2jtjipuxd.html

Ruby: class User; end
来源：http://dali.nwbrower.top/Article/details/gt2nodemwjf.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gt2ktlhywup.html

[G02] 构造函数
来源：http://dali.yj20258.top/Article/details/gt2jbqcwllr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yvdxfuix.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hywenlv.cn/Article/details/gt2wbnxcqke.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2fnneebcd.html

TS:   constructor(public name: string) {}
来源：http://dali.daria6918.cn/Article/details/gt2hyyanngf.html

Java: User(String name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gt2kuwqhfqc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fengsongda.top/Article/details/gt2qszgidny.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2hjyoanqt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2fqqfxtci.html

[G03] 实例属性
来源：http://dali.hammf.cn/Article/details/gt2ilbtnina.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gt2prbkklqh.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gt2ynkkbphw.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxurzag.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2qybcezmr.html

Java: private String name;
来源：http://dali.yueranfly.top/Article/details/gt2fhfyyftr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shangyingyoupin.top/Article/details/gt2ezczwrhw.html

Ruby: @name = "x"
来源：http://dali.cheryme.top/Article/details/gt2djzzfvym.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2kdizptye.html

[G04] 定义方法
来源：http://dali.cashguo.top/Article/details/gt2wsytwjqz.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gt2cpuqirkd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gt2upscrmzx.html

JS:   greet() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2ksgeauni.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gt2vlkesdwo.html

Java: String greet() { return name; }
来源：http://dali.tanke756.top/Article/details/gt2eoqmjxie.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gt2idvbcqey.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wtiyfyyc.html

C#:   public string Greet() => Name;
来源：http://dali.dashuyun.cn/Article/details/gt2zltddjuu.html

[G05] 继承
来源：http://dali.sysykeji.top/Article/details/gt2tyskxydq.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gt2maxxremx.html

PHP:  class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2muszeimy.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2jfgvyqfc.html

TS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gt2nlwnxgon.html

Java: class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2fvppkmqf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yamhcosg.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gt2gssanwgs.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gt2sqednbvz.html

[G06] 重写方法
来源：http://dali.zdqjudy.top/Article/details/gt2jnkuzuah.html

Py:   def greet(self): return "admin"
来源：http://dali.kuanghao11.cn/Article/details/gt2xfetkytf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2unjygacg.html

JS:   greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gt2oisdwajo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2qltihokb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2xdydehhh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gt2qlrgtekg.html

Ruby: def greet; "admin"; end
来源：http://dali.snrcjt.cn/Article/details/gt2opkfidlr.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gt2lyfzhwmt.html

[G07] 调用父类方法
来源：http://dali.cqqwz.cn/Article/details/gt2zawbgutm.html

Py:   super().greet()
来源：http://dali.sweek.top/Article/details/gt2dvhvzlqm.html

PHP:  parent::greet();
来源：http://dali.iojbl.cn/Article/details/gt2fdpwocrm.html

JS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2vovgvohu.html

TS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gt2lezcdzdr.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gt2rdrctave.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.quarkkingdee.top/Article/details/gt2cuxfvttq.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gt2budhonmr.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gt2xlkfspuc.html

[G08] 静态方法与属性
来源：http://dali.hnxiangtu.top/Article/details/gt2jbjpkfmd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhoulong.xyz/Article/details/gt2osbxidmm.html

PHP:  public static function f() {}
来源：http://dali.9152youxi.cn/Article/details/gt2udhovpqf.html

JS:   static f() {}
来源：http://dali.mhx1999.top/Article/details/gt2aghvmfju.html

TS:   static f(): void {}
来源：http://dali.shzxlz.cn/Article/details/gt2kkftbyfp.html

Java: static void f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2fnxygozh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jiagoushi.top/Article/details/gt2hgrafggc.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gt2bvvrjcbu.html

C#:   public static void F() {}
来源：http://dali.yvedp.cn/Article/details/gt2txtosvme.html

[G09] 接口 / 抽象类
来源：http://dali.0kj1m.cn/Article/details/gt2wveqylzq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tian-w.cn/Article/details/gt2agizwlbp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jqgufenzy.top/Article/details/gt2fhbxsvfv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guowangkeji.top/Article/details/gt2ssqmsuej.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gt2xsbmxviz.html

Java: interface Shape { double area(); }
来源：http://dali.zdqjudy.top/Article/details/gt2hjgywnlm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cqqwz.cn/Article/details/gt2aoqwcrif.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2scyqkyxq.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gt2rnphfnij.html

[G10] 访问控制
来源：http://dali.chenjidiqi.icu/Article/details/gt2mgoidfjk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gt2nabhkrao.html

PHP:  public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2ciwewkpb.html

JS:   #private 字段；其余公开
来源：http://dali.ivvv.top/Article/details/gt2lnaobjbn.html

TS:   public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gt2aougsahh.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gt2lltnfuan.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gt2hcydrvss.html

Ruby: public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2esxzywdu.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gt2bclpbpzr.html

[G11] getter / setter
来源：http://dali.ehwqpu.com/Article/details/gt2xjneyxnu.html

Py:   @property 与 @x.setter
来源：http://dali.chenlongwang.top/Article/details/gt2dyyysgxd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gt2gwletdfd.html

JS:   get name() { return this._name; }
来源：http://dali.ybcxt.top/Article/details/gt2dpapcfru.html

TS:   get name(): string { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gt2eimjbhyx.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mdksrblc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gt2rfrztfyw.html

Ruby: attr_accessor :name
来源：http://dali.ppjwa.cn/Article/details/gt2zgxqphuk.html

C#:   public string Name { get; set; }
来源：http://dali.havefunace.top/Article/details/gt2vsakksok.html

[G12] 对象转字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2mijvwimr.html

Py:   def __str__(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gt2hqysuota.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kdtocyyg.html

JS:   toString() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2ysbymldw.html

TS:   toString(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2zsqloqhs.html

Java: @Override public String toString() { return name; }
来源：http://dali.yueranfly.top/Article/details/gt2mkrgfopd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2tmqniqpk.html

Ruby: def to_s; @name; end
来源：http://dali.chenzaomai.com/Article/details/gt2dihxeyuw.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gt2shqzoeln.html

[G13] 判断对象类型
来源：http://dali.yangfankeji.com/Article/details/gt2lwkyypdk.html

Py:   isinstance(u, User)
来源：http://dali.haohaochexian.top/Article/details/gt2gasuosdd.html

PHP:  $u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2zhkdzcza.html

JS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2rohwrndy.html

TS:   u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gt2yiiblibb.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlmzeiv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2pqpusrfb.html

Ruby: u.is_a?(User)
来源：http://dali.shzxlz.cn/Article/details/gt2fazmmzjv.html

C#:   u is User
来源：http://dali.gzhubu.top/Article/details/gt2agzzzbri.html

[G14] 数据类 / record
来源：http://dali.yvedp.cn/Article/details/gt2ggttqxif.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuanzx.com/Article/details/gt2yqytkwcq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gzhubu.top/Article/details/gt2phmxqerc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gt2tgwmiqhv.html

TS:   type User = { name: string; age: number };
来源：http://dali.gotoacloud.top/Article/details/gt2mmagztno.html

Java: record User(String name, int age) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2pdhntact.html

Go:   type User struct { Name string; Age int }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzbpivor.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnxiangtu.top/Article/details/gt2gfhvrzdo.html

C#:   record User(string Name, int Age);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vcamtajo.html

[G15] 枚举
来源：http://dali.kuanghao11.cn/Article/details/gt2njqxccuf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xziqi.cn/Article/details/gt2pxxftfqm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aibaodan.cn/Article/details/gt2ujleiyfh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ppjwa.cn/Article/details/gt2xegzrnwj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.redwolf501.top/Article/details/gt2bivklaza.html

Java: enum Color { RED, GREEN }
来源：http://dali.0kj1m.cn/Article/details/gt2ulfyhayd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ybcxt.top/Article/details/gt2yojgnzqv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cqqwz.cn/Article/details/gt2njpppbhw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gt2oxxelkli.html

[G16] 对象转数组 / 字典
来源：http://dali.shzxlz.cn/Article/details/gt2bvoffydp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zdqjudy.top/Article/details/gt2hfobpvod.html

PHP:  get_object_vars($obj);
来源：http://dali.jlsjyb.cn/Article/details/gt2chyhnqxx.html

JS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2nywgsflg.html

TS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gt2rshkazda.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenzaomai.com/Article/details/gt2amdslgps.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj202588.top/Article/details/gt2aesbmsnp.html

Ruby: obj.instance_variables
来源：http://dali.meibo888.top/Article/details/gt2ldiwbsgz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gt2zzxqubmc.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2oakdhgev.html

H. 异常与错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2euklywxj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2axxulbxg.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gt2cwkrxvqv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nwbrower.top/Article/details/gt2fgfnszsq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yueranfly.top/Article/details/gt2wapfllez.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gt2xbgnuohq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wsdjjwph.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.vqdsnc.cn/Article/details/gt2oaspabvu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.redwolf501.top/Article/details/gt2vxihkbtk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fengsongda.top/Article/details/gt2hvavbjva.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gt2btpmvacj.html

[H02] finally / ensure 收尾
来源：http://dali.guowangkeji.top/Article/details/gt2wdarjeku.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gzhubu.top/Article/details/gt2efedbkav.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gt2checyztr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2hcpybkri.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2tymeqvul.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdxgpwxf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gt2gsjdrhxx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gt2axwbtezx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2ktjvcpom.html

[H03] 主动抛出异常
来源：http://dali.c1oappe.top/Article/details/gt2wytsgtlr.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgufenzy.top/Article/details/gt2lewhbrag.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2dgqjnkho.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2ipffjlbz.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2yrlrekbt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gt2hhbgpkiz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gt2yimsicip.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fzhhl.top/Article/details/gt2cfrmxqud.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2xxozzocl.html

[H04] 自定义异常类型
来源：http://dali.jianghu66.top/Article/details/gt2suesbbty.html

Py:   class MyError(Exception): pass
来源：http://dali.zdqjudy.top/Article/details/gt2twihaaqj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gt2xgnowklm.html

JS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gt2ezzqynde.html

TS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gt2pshyfyku.html

Java: class MyException extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gt2zwpnwckx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gt2xmwvyaim.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gt2nrrfbbes.html

C#:   class MyException : Exception {}
来源：http://dali.aizwys.cn/Article/details/gt2pikzshwl.html

[H05] 捕获特定类型
来源：http://dali.jianghu66.top/Article/details/gt2clhlhimz.html

Py:   except ValueError as e:
来源：http://dali.nanxuanxn.top/Article/details/gt2dglnmxhv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhixingplan.top/Article/details/gt2ctqxbgow.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2igcmvzcf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gt2egwehobk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnqzz.top/Article/details/gt2zwxhjxzg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.snrcjt.cn/Article/details/gt2xfjthdra.html

Ruby: rescue ArgumentError => e
来源：http://dali.zycfv.cn/Article/details/gt2ezltmqtv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fzhhl.top/Article/details/gt2jymacluo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sxryk.cn/Article/details/gt2thsfrumx.html

Py:   value = d.get("k") or default
来源：http://dali.gogol.net.cn/Article/details/gt2siapwjtu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.meibo888.top/Article/details/gt2pxnujens.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xziqi.cn/Article/details/gt2ilahwxau.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xinyue.icu/Article/details/gt2btyqcjjj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhixingplan.top/Article/details/gt2ewimbrki.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.havefunace.top/Article/details/gt2cnfcxeds.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gt2ntafxdup.html

C#:   obj?.A?.B ?? default
来源：http://dali.zdqjudy.top/Article/details/gt2wwqwlxrz.html

[H07] 断言
来源：http://dali.vqdsnc.cn/Article/details/gt2goibmfgi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shangyingyoupin.top/Article/details/gt2tpzzxlfz.html

PHP:  assert($x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2ildrlhtq.html

JS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2evlbjgmr.html

TS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2asakpebs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gt2jrntyuhv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ydzc1.top/Article/details/gt2ydatzwxx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnqzz.top/Article/details/gt2ouxbprmr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sweek.top/Article/details/gt2edfalekd.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2etkbtdfm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gt2zndztnko.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gaohongyu789.top/Article/details/gt2fxjvjgbt.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gt2jdsikkxn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sbqsczvt.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yanxiufei.cn/Article/details/gt2njscpsgl.html

Go:   err.Error()
来源：http://dali.ppjwa.cn/Article/details/gt2qdpttqiu.html

Ruby: e.message;  e.backtrace
来源：http://dali.vqdsnc.cn/Article/details/gt2elmjzlem.html

C#:   e.Message;  e.StackTrace
来源：http://dali.9152youxi.cn/Article/details/gt2xaboyebe.html

[H09] 带错误码的异常
来源：http://dali.vqdsnc.cn/Article/details/gt2rxydobyy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cqqwz.cn/Article/details/gt2uwmqfbzv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eaudrrcm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jlsjyb.cn/Article/details/gt2vzeijcpv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yanxiufei.cn/Article/details/gt2ouiqhljq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2akllpffo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigufen.top/Article/details/gt2lnpcayna.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigfzy.top/Article/details/gt2ntpexpbm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gt2djpmtdmd.html

[H10] 资源自动释放
来源：http://dali.9152youxi.cn/Article/details/gt2bsklzgiy.html


<!-- 参考信息 -->