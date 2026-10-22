代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jiagoushi.top/Article/details/gtkevdpqgu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtaajvccmf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guannengcc.top/Article/details/gtuhbdrlzv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenzaomai.com/Article/details/gtpukhfsic.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gtyraolrrg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aizwys.cn/Article/details/gtodsyeafl.html

PHP:  file_exists("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtsnktawou.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtjpdebird.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtdpofkmvw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtaohaobsc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxinkj.top/Article/details/gtwdczlsgr.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtuzyxxhtx.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtqxiurpef.html

[F06] 删除文件
来源：http://dali.xziqi.cn/Article/details/gtzcubqaiz.html

Py:   os.remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtpowsnaks.html

PHP:  unlink("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtokktxxfd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtykilvlei.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtbcekltjj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtptaxobzb.html

Go:   os.Remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtcekzqazp.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtxxsymcea.html

C#:   File.Delete("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtgjvlsaso.html

[F07] 创建目录（含多级）
来源：http://dali.jqgfzy.top/Article/details/gtlguronse.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gteuktthpl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.daxiang520.top/Article/details/gtwkxepazv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtiwjcqemn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtldrqzvqn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhiwuduotai.top/Article/details/gthtbcimuc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gtvoprunxi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gtbtbpnxfk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ehwqpu.com/Article/details/gtjksuovjb.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gtrnmdorxa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgfzy.top/Article/details/gtmazvnaih.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jlsjyb.cn/Article/details/gtplaypdew.html

JS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtghydqmwy.html

TS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gtvrtpvkll.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtocwjltyw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fzhhl.top/Article/details/gtwdsqmqcy.html

Ruby: Dir.children("dir")
来源：http://dali.xinyue.icu/Article/details/gtfofaanst.html

C#:   Directory.GetFiles("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtaisvncph.html

[F09] 获取文件大小
来源：http://dali.chenzaomai.com/Article/details/gtxpksbgbs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gtvaerrtxj.html

PHP:  filesize("a.txt");
来源：http://dali.yongpay.top/Article/details/gtyzzyonfu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gtmlksniog.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gtfdszugyv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtotlgxisc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gtdzotygfk.html

Ruby: File.size("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtmeomatyd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hammf.cn/Article/details/gtljksoelv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.svipenyu.cn/Article/details/gtenymyjmp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtafufhggc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nwbrower.top/Article/details/gthldekmxc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtsuhudmtx.html

TS:   path.extname("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtxjmxuyhw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gtyeotwaum.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtxakdshuq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtuwduguzf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtijzswtbf.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gtiaafkghj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtoippsoqk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenzaomai.com/Article/details/gtamacedcj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtlcdpserp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtxzmmhwlp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtpsfqzumk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxinkj.top/Article/details/gtjffumaqr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gttkuljixf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtncbguufh.html

[F12] CSV 读写
来源：http://dali.nanxinkj.top/Article/details/gthaisywms.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzvgwnuk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gtkxovmwxq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cdnleiting.top/Article/details/gtcofavkuo.html

TS:   // 同上
来源：http://dali.guowangkeji.top/Article/details/gtvpshnoao.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhiwuduotai.top/Article/details/gtgcpcjskx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yanxiufei.cn/Article/details/gtlhdgskel.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gtfegnwrey.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gtcvqybltd.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtafuatqsz.html

G. 面向对象
来源：http://dali.sxryk.cn/Article/details/gtjaxqjpzj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtqzgvuvkp.html

[G01] 定义类
来源：http://dali.redwolf501.top/Article/details/gtlbdswtot.html

Py:   class User: pass
来源：http://dali.ydzc1.top/Article/details/gtxewvsupz.html

PHP:  class User {}
来源：http://dali.sweek.top/Article/details/gtuhuxilps.html

JS:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtestjfjcl.html

TS:   class User { name: string = ""; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfqqllbjs.html

Java: class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxapgglcp.html

Go:   type User struct { Name string }
来源：http://dali.cucudq.cn/Article/details/gtmrilyokt.html

Ruby: class User; end
来源：http://dali.yj20258888.top/Article/details/gtzuaosjaz.html

C#:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtfotxqknb.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthoqqfczu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gtwbzgiijf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xylfe.cn/Article/details/gtbvwkjcnx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gtuxxekyox.html

TS:   constructor(public name: string) {}
来源：http://dali.snrcjt.cn/Article/details/gtfymiayrk.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gtuafdnnju.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hammf.cn/Article/details/gtcrtesiox.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.meibo888.top/Article/details/gtmhptmqyo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtlyxvhafw.html

[G03] 实例属性
来源：http://dali.sxryk.cn/Article/details/gtihcggdxx.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrrseqjb.html

PHP:  public string $name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkuiogjq.html

JS:   this.name = "x";
来源：http://dali.xinyue.icu/Article/details/gtzhujyjuv.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gtaycbvysw.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gtfknwlrrn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnxiangtu.top/Article/details/gtfrsvazud.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtxwdzirae.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gtsyktrzlg.html

[G04] 定义方法
来源：http://dali.jlsjyb.cn/Article/details/gtuiibronx.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtpuqdwyug.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtaasdqcoq.html

JS:   greet() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtgirjrxhu.html

TS:   greet(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtbnosaaya.html

Java: String greet() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtcbvzaqmj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtevghaxcc.html

Ruby: def greet; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtigjzqscg.html

C#:   public string Greet() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gtjclzddxv.html

[G05] 继承
来源：http://dali.jinqigufen.top/Article/details/gtqliwviwe.html

Py:   class Admin(User): pass
来源：http://dali.jyoumei.cn/Article/details/gtrenonoob.html

PHP:  class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gttnmnosil.html

JS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtazhoimpo.html

TS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtzbhpqbyk.html

Java: class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtxlqvdvob.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yangfankeji.com/Article/details/gtfjznwzbn.html

Ruby: class Admin < User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtqxvtkxgj.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gtfhteazhk.html

[G06] 重写方法
来源：http://dali.guannengcc.top/Article/details/gtnjuklehm.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gtuqrcxlbm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtckhjflal.html

JS:   greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtbhwvrebb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtncfjyhyj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gtklfspyau.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenlongwang.top/Article/details/gtakalaxhn.html

Ruby: def greet; "admin"; end
来源：http://dali.haohaochexian.top/Article/details/gttjdkzlfn.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj202588.top/Article/details/gtstmiehnk.html

[G07] 调用父类方法
来源：http://dali.jqgufenzy.top/Article/details/gteywlqzjj.html

Py:   super().greet()
来源：http://dali.316326.xyz/Article/details/gtgpklxsye.html

PHP:  parent::greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtbuwcpftg.html

JS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtpbbkudgb.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtujgxongh.html

Java: super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtawgmaaxf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gtmyfywplv.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gtbgdgpeys.html

C#:   base.Greet();
来源：http://dali.zycfv.cn/Article/details/gttvndqdwx.html

[G08] 静态方法与属性
来源：http://dali.pycfn.com/Article/details/gtuxhiduzl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tanke756.top/Article/details/gtpwemvmgr.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gtmklhclcb.html

JS:   static f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gthgjtxazd.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gtqcmlfoas.html

Java: static void f() {}
来源：http://dali.hnqzz.top/Article/details/gtxoxxsziv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fzhhl.top/Article/details/gtazrjgckm.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gtibiweqnz.html

C#:   public static void F() {}
来源：http://dali.hammf.cn/Article/details/gtuhaqbvku.html

[G09] 接口 / 抽象类
来源：http://dali.gogol.net.cn/Article/details/gtlihcpvqv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gtmlhglqku.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gtcwisacjt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gthigjcojy.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgufenzy.top/Article/details/gthseeysuj.html

Java: interface Shape { double area(); }
来源：http://dali.fzhhl.top/Article/details/gtuftdqjsc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gogol.net.cn/Article/details/gtgwbswknc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuetiantiany.cn/Article/details/gtwgdpwdxw.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxinkj.top/Article/details/gtwlethnqy.html

[G10] 访问控制
来源：http://dali.yj20258.top/Article/details/gtjltptddw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gtocgqyyqs.html

PHP:  public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtrllendtl.html

JS:   #private 字段；其余公开
来源：http://dali.cucudq.cn/Article/details/gtqktwlowm.html

TS:   public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtceqkidco.html

Java: public / protected / private / 默认包级
来源：http://dali.ydzc1.top/Article/details/gtpvfmbtto.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hysaishi.cn/Article/details/gtvwzfiynn.html

Ruby: public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gteixdkvxj.html

C#:   public / protected / private / internal
来源：http://dali.haohaochexian.top/Article/details/gtaegjcdyv.html

[G11] getter / setter
来源：http://dali.jyoumei.cn/Article/details/gtqftfjhyi.html

Py:   @property 与 @x.setter
来源：http://dali.shzxlz.cn/Article/details/gtnsvdehfe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtzfmxsszh.html

JS:   get name() { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtymsowlyg.html

TS:   get name(): string { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtyaisykvw.html

Java: public String getName() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtptaziwup.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtvwhflnvm.html

Ruby: attr_accessor :name
来源：http://dali.sxryk.cn/Article/details/gtfzzrxsge.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gtyouqkbio.html

[G12] 对象转字符串
来源：http://dali.birdmap.top/Article/details/gttmvnrcis.html

Py:   def __str__(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gtgcfiqtdd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtxuqiwcoq.html

JS:   toString() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtalyvpvrm.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj202588.top/Article/details/gtgcxtdfzd.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgnleokb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtiuickupl.html

Ruby: def to_s; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gteoybepuu.html

C#:   public override string ToString() => Name;
来源：http://dali.tanke756.top/Article/details/gtrfdgqzss.html

[G13] 判断对象类型
来源：http://dali.meibo888.top/Article/details/gtgxkqrbpr.html

Py:   isinstance(u, User)
来源：http://dali.hongshengwenyu.top/Article/details/gtklzmtcof.html

PHP:  $u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtmtsbrvrr.html

JS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtrjcfmnml.html

TS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gtabqobyzu.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtxlwfqaex.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sweek.top/Article/details/gtyktnedot.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gtqgswazbt.html

C#:   u is User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayoxjtxw.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gtlwtnedwu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuetiantiany.cn/Article/details/gtldogptqi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.smart0.xyz/Article/details/gtrmffbghi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ppjwa.cn/Article/details/gtvmnitpsq.html

TS:   type User = { name: string; age: number };
来源：http://dali.tian-w.cn/Article/details/gtbjjamlpm.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gtthadqojn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ppjwa.cn/Article/details/gtoeskgeai.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gtbephorld.html

C#:   record User(string Name, int Age);
来源：http://dali.xziqi.cn/Article/details/gtretsbvpl.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gtfsnakdkw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gtoytlvuxh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gotoacloud.top/Article/details/gtxgjehhsp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zdqjudy.top/Article/details/gtrslzgcpa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtijvwkhsv.html

Java: enum Color { RED, GREEN }
来源：http://dali.guannengcc.top/Article/details/gtwwxsbnvi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tian-w.cn/Article/details/gtjjdlogmb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gtlhddvhkm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtkfwuetxt.html

[G16] 对象转数组 / 字典
来源：http://dali.iojbl.cn/Article/details/gtkkpgnlyq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guowangkeji.top/Article/details/gtgnlciltw.html

PHP:  get_object_vars($obj);
来源：http://dali.0kj1m.cn/Article/details/gtoenuythg.html

JS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gtxstvcgcj.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtqwdgldhk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcztwesw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gtckcrbpcl.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gtfvzbiana.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gtegenggdz.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtsmpfhbrz.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gtprgzykah.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtnxbyopoj.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gttvxxpagl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cashguo.top/Article/details/gtfsspvbih.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.c1oappe.top/Article/details/gtmujnhzom.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtrafnffbe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gtdrxrdqmu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gaohongyu789.top/Article/details/gtdoveecut.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gthjqpijfb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guowangkeji.top/Article/details/gtvcfrcnkk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.havefunace.top/Article/details/gtozeyezyf.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258888.top/Article/details/gtrmqdmnxr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gtjhsbaztm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtdclvlslj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtkcgtpljd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtnsxhqoxl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtvmsuboec.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dashuyun.cn/Article/details/gtybvxulpn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ehwqpu.com/Article/details/gtgvfugxaq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtqcztskcb.html

[H03] 主动抛出异常
来源：http://dali.tian-w.cn/Article/details/gtnfmayajg.html

Py:   raise ValueError("错误信息")
来源：http://dali.guowangkeji.top/Article/details/gtjjbzvcep.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtselihemt.html

JS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtketwewek.html

TS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtxamcfocz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gttlrzdkuc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnxiangtu.top/Article/details/gtkhmscyvu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangshuangyany.cn/Article/details/gtkiaignnk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtlhzylsue.html

[H04] 自定义异常类型
来源：http://dali.pycfn.com/Article/details/gtbvegfguo.html

Py:   class MyError(Exception): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmdtcyls.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtwgremtyb.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gtgtyjfcko.html

TS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gtgfxstump.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtnlynivri.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dianchejie.cn/Article/details/gtpamgiprp.html

Ruby: class MyError < StandardError; end
来源：http://dali.ivvv.top/Article/details/gtkbxjfbmh.html

C#:   class MyException : Exception {}
来源：http://dali.yj202588.top/Article/details/gtxhkeunod.html

[H05] 捕获特定类型
来源：http://dali.ppjwa.cn/Article/details/gtwlmujlnh.html

Py:   except ValueError as e:
来源：http://dali.snrcjt.cn/Article/details/gtpwxqgnig.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tian-w.cn/Article/details/gthcaxjnno.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtzpwxymdq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtlmozknpr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hywenlv.cn/Article/details/gtkbdddbjh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xziqi.cn/Article/details/gthmiwlriu.html

Ruby: rescue ArgumentError => e
来源：http://dali.daria6918.cn/Article/details/gttnnhtmok.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gotoacloud.top/Article/details/gtpvpdxbat.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hongshengwenyu.top/Article/details/gtvdzhewci.html

Py:   value = d.get("k") or default
来源：http://dali.cqqwz.cn/Article/details/gtogcihzqs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dashuyun.cn/Article/details/gtrmlfrmye.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtlgnejefi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtbvxcjrpl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxinkj.top/Article/details/gtthtnfcfn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aibaodan.cn/Article/details/gtapvmdsts.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzunokszp.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtylwaphya.html

[H07] 断言
来源：http://dali.tian-w.cn/Article/details/gtczwaljej.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gtxkbljvru.html

PHP:  assert($x > 0);
来源：http://dali.ivvv.top/Article/details/gtpbpwdrgo.html

JS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtxojolwuf.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtwzawiius.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhengqikj.top/Article/details/gtjhpncfjr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gtghxcqkse.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sweek.top/Article/details/gtlkvqaywf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gthmfslcgp.html

[H08] 获取错误信息与堆栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffdsxufp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guannengcc.top/Article/details/gtgpvngiwn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ydzc1.top/Article/details/gtcpppobbj.html

JS:   e.message;  e.stack
来源：http://dali.mhx1999.top/Article/details/gtyvigokmc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtostjobrf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ybcxt.top/Article/details/gtwysgvmcd.html

Go:   err.Error()
来源：http://dali.yonumen.top/Article/details/gtpqwcyyon.html

Ruby: e.message;  e.backtrace
来源：http://dali.sysykeji.top/Article/details/gtxyiccsap.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sweek.top/Article/details/gtuiunhorr.html

[H09] 带错误码的异常
来源：http://dali.yj20258888.top/Article/details/gtwyiqanzv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hongshengwenyu.top/Article/details/gtzbauuuwd.html


<!-- 参考信息 -->