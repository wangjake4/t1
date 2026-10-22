代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2jxhbunff.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhengqikj.top/Article/details/gt2elybgucv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gt2cjwydjla.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gt2veflbvnc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zycfv.cn/Article/details/gt2qefkwiub.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.meibo888.top/Article/details/gt2svgznlel.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gt2qgpcysyp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vetfdwnr.html

[F05] 判断文件或目录是否存在
来源：http://dali.yvedp.cn/Article/details/gt2diklebjt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zycfv.cn/Article/details/gt2atvaowgo.html

PHP:  file_exists("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2yjdqzvjr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2nenbhxcj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ptwctxdl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gt2zqlnbzqt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yvedp.cn/Article/details/gt2bbfrozjd.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2tdnvkzyt.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2guplexdl.html

[F06] 删除文件
来源：http://dali.kuanghao11.cn/Article/details/gt2hjnkrlvw.html

Py:   os.remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2xpjszydi.html

PHP:  unlink("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2kykxrcyq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fupauedd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2ymhxsngj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2xosmlwsz.html

Go:   os.Remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2hietitxm.html

Ruby: File.delete("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2etgrihzy.html

C#:   File.Delete("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2hmfmmkym.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gt2yhlqajkl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gt2bemecqsy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nwbrower.top/Article/details/gt2rjlwghsf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tqgvkelg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gt2nnqcibha.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hysaishi.cn/Article/details/gt2bvwpuuta.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gzhubu.top/Article/details/gt2iwfahzqd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yonumen.top/Article/details/gt2mlyojrki.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shangyingyoupin.top/Article/details/gt2mmkdtguf.html

[F08] 遍历目录
来源：http://dali.smart0.xyz/Article/details/gt2cxshjycz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cashguo.top/Article/details/gt2mpbwlfin.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnqzz.top/Article/details/gt2xoufwpia.html

JS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2uvwtndca.html

TS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gt2zoayezok.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gt2okrigptk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2jnphpard.html

Ruby: Dir.children("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2flngcoxr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.bjfxy.top/Article/details/gt2ngoqpmvo.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gt2mdfihnhs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2lsimvaaq.html

PHP:  filesize("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2bciwpixh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gt2sjandaxf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gt2ikjswokf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lfwuxiab.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tianlin.xyz/Article/details/gt2mflldhrt.html

Ruby: File.size("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2iqtxlwce.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fengsongda.top/Article/details/gt2mgyyraxt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yvedp.cn/Article/details/gt2ilagrrsy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2dbfhdqhc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.pycfn.com/Article/details/gt2mcngejlz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2pjkvcevm.html

TS:   path.extname("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2urebgdqv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gzhubu.top/Article/details/gt2infabtkr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2jkuydpnl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2votlhxxi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2kgqlpuyz.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gt2rhihuobj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2knzqiugv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2qwgpbxdu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2pfmrhzja.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2vpojvbqr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.meibo888.top/Article/details/gt2rmfbrcuo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pycfn.com/Article/details/gt2fvorzepz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2sopdbhnd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2yxxcnwbc.html

[F12] CSV 读写
来源：http://dali.yuanzhike.top/Article/details/gt2kjsephyg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gt2jjtyitpi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fzhhl.top/Article/details/gt2autiasxr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gkkeysjd.html

TS:   // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwgkvigp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.smart0.xyz/Article/details/gt2sucflcue.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.kuanghao11.cn/Article/details/gt2horfvaoo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ncacdhjn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258888.top/Article/details/gt2pegkyivr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2bbfzfnlf.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gt2qjuxldrq.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qogyohbl.html

[G01] 定义类
来源：http://dali.snrcjt.cn/Article/details/gt2qjxqgjle.html

Py:   class User: pass
来源：http://dali.xuanzx.com/Article/details/gt2ozuglyrh.html

PHP:  class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2qwobuiup.html

JS:   class User {}
来源：http://dali.xuanzx.com/Article/details/gt2mocnkold.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gt2icnzumgp.html

Java: class User {}
来源：http://dali.yj202588.top/Article/details/gt2hunmxfwu.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gt2pieepizg.html

Ruby: class User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2thrgelkl.html

C#:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2jfdskxcu.html

[G02] 构造函数
来源：http://dali.gaohongyu789.top/Article/details/gt2ksdgujht.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenzaomai.com/Article/details/gt2wiwukuth.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gogol.net.cn/Article/details/gt2esrkcgyq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2scjlerjw.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gt2ubswkzhl.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gt2fpbzqoqo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yangfankeji.com/Article/details/gt2okotipnq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ivvv.top/Article/details/gt2ildptrvk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2lzlbqtje.html

[G03] 实例属性
来源：http://dali.gaohongyu789.top/Article/details/gt2xwzrwtou.html

Py:   self.name = "x"
来源：http://dali.daxiang520.top/Article/details/gt2mtnfpsub.html

PHP:  public string $name = "x";
来源：http://dali.ivvv.top/Article/details/gt2uyvoicss.html

JS:   this.name = "x";
来源：http://dali.smart0.xyz/Article/details/gt2dqdasmww.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2pntzlyqa.html

Java: private String name;
来源：http://dali.yj202588.top/Article/details/gt2qivkstfd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.birdmap.top/Article/details/gt2ztqdomra.html

Ruby: @name = "x"
来源：http://dali.shuidangran.top/Article/details/gt2bziwulfd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2ufbyvqxr.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2rutrcxez.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cvlsnyhe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gt2vpqvyjcl.html

JS:   greet() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2rnnoomrd.html

TS:   greet(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gt2mwldxllo.html

Java: String greet() { return name; }
来源：http://dali.yonumen.top/Article/details/gt2abkxwiln.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2ssvfmrov.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gt2gtdfxccp.html

C#:   public string Greet() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gt2zedfpekr.html

[G05] 继承
来源：http://dali.redwolf501.top/Article/details/gt2ngkeigcn.html

Py:   class Admin(User): pass
来源：http://dali.sweek.top/Article/details/gt2aqauzelq.html

PHP:  class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2tuyqiqrx.html

JS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2pfhxtwaj.html

TS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2xhqapfvl.html

Java: class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gt2vrgeelxb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jyoumei.cn/Article/details/gt2snqcdpbr.html

Ruby: class Admin < User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2psqputvp.html

C#:   class Admin : User {}
来源：http://dali.ybcxt.top/Article/details/gt2qoywimbt.html

[G06] 重写方法
来源：http://dali.tanke756.top/Article/details/gt2oasfnvvx.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gt2hvckvkkm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2vvemdqkz.html

JS:   greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2dvczzwfi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2zhnkbryd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2sywyykld.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gt2nmislavk.html

Ruby: def greet; "admin"; end
来源：http://dali.hammf.cn/Article/details/gt2njorulnk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eiawseol.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gt2vfrlcsxc.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gt2dpqxlufv.html

PHP:  parent::greet();
来源：http://dali.cucudq.cn/Article/details/gt2ngcjeypw.html

JS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2kidlaoxq.html

TS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gt2kvdaptwk.html

Java: super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2cgcntcnv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangshuangyany.cn/Article/details/gt2xwrwpjdb.html

Ruby: super
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cysfeagc.html

C#:   base.Greet();
来源：http://dali.c1oappe.top/Article/details/gt2oxjxsdiy.html

[G08] 静态方法与属性
来源：http://dali.yangfankeji.com/Article/details/gt2nasjdhrd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxinkj.top/Article/details/gt2avnbdvcr.html

PHP:  public static function f() {}
来源：http://dali.havefunace.top/Article/details/gt2gjvswctk.html

JS:   static f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ivyeslkz.html

TS:   static f(): void {}
来源：http://dali.yangfankeji.com/Article/details/gt2mrobqsvf.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gt2owtciokb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangshuangyany.cn/Article/details/gt2frwdymyh.html

Ruby: def self.f; end
来源：http://dali.yvedp.cn/Article/details/gt2nvwujhrc.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gt2fghhmoxn.html

[G09] 接口 / 抽象类
来源：http://dali.0kj1m.cn/Article/details/gt2lcbqutuk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.9152youxi.cn/Article/details/gt2pknyxoos.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gt2yzoqlkyb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.iojbl.cn/Article/details/gt2ujbihloe.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhixingplan.top/Article/details/gt2fmjzcspe.html

Java: interface Shape { double area(); }
来源：http://dali.fzhhl.top/Article/details/gt2uivhwgyz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ydzc1.top/Article/details/gt2xpgubpat.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2unmmvsgv.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gt2suwcyohl.html

[G10] 访问控制
来源：http://dali.wangdashe.top/Article/details/gt2yldxnalj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shuidangran.top/Article/details/gt2fzqmfscp.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2canwnrmv.html

JS:   #private 字段；其余公开
来源：http://dali.jlsjyb.cn/Article/details/gt2uwgboecc.html

TS:   public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gt2ygzatxxs.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xlvgdhuj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwrvgnue.html

Ruby: public / protected / private
来源：http://dali.smart0.xyz/Article/details/gt2jgsoyhup.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gt2iwswakpt.html

[G11] getter / setter
来源：http://dali.yangfankeji.com/Article/details/gt2xzmohipu.html

Py:   @property 与 @x.setter
来源：http://dali.pycfn.com/Article/details/gt2uomphnpf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gt2iymtapcr.html

JS:   get name() { return this._name; }
来源：http://dali.meibo888.top/Article/details/gt2lbhivqjm.html

TS:   get name(): string { return this._name; }
来源：http://dali.havefunace.top/Article/details/gt2gtxxuxdc.html

Java: public String getName() { return name; }
来源：http://dali.cashguo.top/Article/details/gt2zhebynhy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gt2qdssjcgj.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gt2dbqedoxj.html

C#:   public string Name { get; set; }
来源：http://dali.jlsjyb.cn/Article/details/gt2brsyvqwl.html

[G12] 对象转字符串
来源：http://dali.yueranfly.top/Article/details/gt2ytamtwpt.html

Py:   def __str__(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gt2ecaveeuq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gt2ngscjdwy.html

JS:   toString() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2reabptet.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gt2srqnjjph.html

Java: @Override public String toString() { return name; }
来源：http://dali.pycfn.com/Article/details/gt2pqqrzlqw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2rpzabaly.html

Ruby: def to_s; @name; end
来源：http://dali.dashuyun.cn/Article/details/gt2tngajynp.html

C#:   public override string ToString() => Name;
来源：http://dali.cqqwz.cn/Article/details/gt2atnzxfgj.html

[G13] 判断对象类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmkxfbrd.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gt2nhlpoliw.html

PHP:  $u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2ziaoecpv.html

JS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2yytzaryt.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2slnzduzj.html

Java: u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2dqbcctsl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tian-w.cn/Article/details/gt2sgphesba.html

Ruby: u.is_a?(User)
来源：http://dali.fengsongda.top/Article/details/gt2almvvykh.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gt2trzjfjgs.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gt2gdnsmggo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gt2fofxnjcd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.snrcjt.cn/Article/details/gt2zpxszyrf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gt2qomrhldy.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gt2xzwdrclq.html

Java: record User(String name, int age) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wfhpeegx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sysykeji.top/Article/details/gt2nsfafhmu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gt2fulcxbtj.html

C#:   record User(string Name, int Age);
来源：http://dali.zhoulong.xyz/Article/details/gt2qwufoulv.html

[G15] 枚举
来源：http://dali.xuetiantiany.cn/Article/details/gt2ezdlwtul.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ydzc1.top/Article/details/gt2xagoshna.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gt2lzmsvlor.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ivvv.top/Article/details/gt2klcdekmk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2vnjubqjf.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gt2gratalfn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ivvv.top/Article/details/gt2xzruhswk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhongyouzk.top/Article/details/gt2ouwxvifq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gt2saalzfiw.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2vozpjquz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gt2polkmyds.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gt2lrsyjqhb.html

JS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gt2kxsflpgs.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2vzmrawjx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hongshengwenyu.top/Article/details/gt2mdacexmk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttoojrrd.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gt2dtudzqvz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gt2ssbpocko.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2nhvrttpy.html

H. 异常与错误处理
来源：http://dali.tianlin.xyz/Article/details/gt2rkqynubk.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2oxpxnjac.html

[H01] try / catch 基础
来源：http://dali.kuanghao11.cn/Article/details/gt2svgurlfz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hammf.cn/Article/details/gt2yzdefjzn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gt2wdxyzbyq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gt2yemeximq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gt2bfagcwnl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenlongwang.top/Article/details/gt2dsvprbxd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guannengcc.top/Article/details/gt2yavswdav.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vkfjvkzw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gt2ycafqecb.html

[H02] finally / ensure 收尾
来源：http://dali.andypj.xyz/Article/details/gt2pvyqtafr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sweek.top/Article/details/gt2xvdmaqeg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2fstfteex.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2wteaetgh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2otpgzjid.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2sftxqhpk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daxiang520.top/Article/details/gt2ojjdtfpg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gt2ihaahuih.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2rqowagrv.html

[H03] 主动抛出异常
来源：http://dali.ivvv.top/Article/details/gt2glsfzbvn.html

Py:   raise ValueError("错误信息")
来源：http://dali.kuanghao11.cn/Article/details/gt2lhecmzie.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2wmrzfdml.html

JS:   throw new Error("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2rbamxnxx.html

TS:   throw new Error("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2ztxqoqpg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2fwczpisk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gogol.net.cn/Article/details/gt2lfepbmmp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gogol.net.cn/Article/details/gt2ywzvpasj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gt2iubdwyxu.html

[H04] 自定义异常类型
来源：http://dali.bjfxy.top/Article/details/gt2zjgurech.html

Py:   class MyError(Exception): pass
来源：http://dali.ybcxt.top/Article/details/gt2ugoqdirh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gt2tyodcoqd.html

JS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gt2kgwhrotp.html

TS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gt2dbavuqmv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gt2xqctrfhf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnqzz.top/Article/details/gt2fjbeklmy.html

Ruby: class MyError < StandardError; end
来源：http://dali.cheryme.top/Article/details/gt2ximghkhi.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gt2agvooryx.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gt2fgcsuksn.html

Py:   except ValueError as e:
来源：http://dali.hysaishi.cn/Article/details/gt2tousztxm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tian-w.cn/Article/details/gt2ryjqhctu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2tqzezwnm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jlncukyf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnqzz.top/Article/details/gt2tipgnsnr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangdashe.top/Article/details/gt2wbhfccrb.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tlucsonn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gt2zghyjfgf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.quarkkingdee.top/Article/details/gt2bjfmyndy.html

Py:   value = d.get("k") or default
来源：http://dali.pycfn.com/Article/details/gt2lsyrtizr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gt2zeoamyyt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gt2zhjpivcx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gt2wmsllden.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.haohaochexian.top/Article/details/gt2icrvastx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvbhzew.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2exngzsiv.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zkqlband.html

[H07] 断言
来源：http://dali.daria6918.cn/Article/details/gt2dhygkidi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgufenzy.top/Article/details/gt2gpdzegzv.html

PHP:  assert($x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2myyrdwgq.html

JS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xfdoymdq.html

TS:   console.assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2gbcxghew.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gt2fnizbkfp.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zycfv.cn/Article/details/gt2qdeavdia.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cucudq.cn/Article/details/gt2pgvfalpa.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gt2wtzytatp.html

[H08] 获取错误信息与堆栈
来源：http://dali.smart0.xyz/Article/details/gt2tnumjatc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zycfv.cn/Article/details/gt2mvclwwgk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258888.top/Article/details/gt2xqttvyoa.html

JS:   e.message;  e.stack
来源：http://dali.0kj1m.cn/Article/details/gt2ouupxvvd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gt2tghjditz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.havefunace.top/Article/details/gt2tcnnfugv.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gt2rmwclkwb.html


<!-- 参考信息 -->