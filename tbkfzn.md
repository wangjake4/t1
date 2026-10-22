代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gt2mclfcnns.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gt2qtwxcbmv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gt2tgrkgxmz.html

[F04] 追加写入文件
来源：http://dali.ybcxt.top/Article/details/gt2kpfnqchs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cashguo.top/Article/details/gt2ssgvsfkx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ybcxt.top/Article/details/gt2fiqxnzrx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gt2dylhnnzi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2edzsdrop.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gt2ojjyzcxv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2awfkggbp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenzaomai.com/Article/details/gt2attgfsfr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hywenlv.cn/Article/details/gt2mvpqhnnj.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gt2yplvuamt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.havefunace.top/Article/details/gt2skxlsoqg.html

PHP:  file_exists("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2ozssjtej.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2acgxdoix.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2zfipyghv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2zuziusns.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.iojbl.cn/Article/details/gt2zwucavcq.html

Ruby: File.exist?("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2ehildvdk.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2uqimtfyn.html

[F06] 删除文件
来源：http://dali.chenlongwang.top/Article/details/gt2xktsdbjl.html

Py:   os.remove("a.txt")
来源：http://dali.sweek.top/Article/details/gt2kpqzfymn.html

PHP:  unlink("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2eijucfse.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2mhlrhmxf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2tacflxek.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gt2zktfwufg.html

Go:   os.Remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2sihvcbji.html

Ruby: File.delete("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2cmhzfzpe.html

C#:   File.Delete("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2bzhmiokt.html

[F07] 创建目录（含多级）
来源：http://dali.feifeiyinyue.top/Article/details/gt2azciopwf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gt2anckwffc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gt2ahtixkax.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ocadhifb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gt2qmhzgkjg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cqqwz.cn/Article/details/gt2bwpcjqae.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenlongwang.top/Article/details/gt2ymbwejlo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.snrcjt.cn/Article/details/gt2mrtvymnq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gt2rsamueoj.html

[F08] 遍历目录
来源：http://dali.hammf.cn/Article/details/gt2xmhwinns.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.andypj.xyz/Article/details/gt2folikkbf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sysykeji.top/Article/details/gt2hwbaytjz.html

JS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gt2yrtnuknz.html

TS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gt2ryauxhtl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gt2xbepfrio.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2ifjuotsm.html

Ruby: Dir.children("dir")
来源：http://dali.hnqzz.top/Article/details/gt2wkntmtih.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2srozkwua.html

[F09] 获取文件大小
来源：http://dali.daria6918.cn/Article/details/gt2wctojvyv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2mtwfbnkm.html

PHP:  filesize("a.txt");
来源：http://dali.sweek.top/Article/details/gt2zptvskzd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gt2qvwdzgwp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gt2lggezhrm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gt2xstiscsd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigufen.top/Article/details/gt2fbtwrwia.html

Ruby: File.size("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2fkjzthkh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxinkj.top/Article/details/gt2enneojtq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigfzy.top/Article/details/gt2pevbusdr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2ajvbbxvk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2paskjwxt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2lwhhkocz.html

TS:   path.extname("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2vugqdsvm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtphubsb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2vsvvwfqr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2jzmrjajs.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2lydfahve.html

[F11] 复制与移动文件
来源：http://dali.ybcxt.top/Article/details/gt2yiwzmsvu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2pjsnquha.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2monmhxwp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2thrstvlw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2fmkkngus.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258888.top/Article/details/gt2yyrfsymn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cldazcbi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2hvzaajjf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ivvv.top/Article/details/gt2rlqmukkc.html

[F12] CSV 读写
来源：http://dali.9152youxi.cn/Article/details/gt2emncombn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvyetrh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhixingplan.top/Article/details/gt2ihsugkho.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangdashe.top/Article/details/gt2addagqoh.html

TS:   // 同上
来源：http://dali.yanxiufei.cn/Article/details/gt2ijbyufbu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.bjfxy.top/Article/details/gt2mqdiuzqv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guowangkeji.top/Article/details/gt2aksmhajg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guowangkeji.top/Article/details/gt2enrmpuvc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gt2kirhhsuo.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kceasmhp.html

G. 面向对象
来源：http://dali.cucudq.cn/Article/details/gt2tbbbybsz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2igavbluv.html

[G01] 定义类
来源：http://dali.yj202588.top/Article/details/gt2arnhsjtp.html

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gt2fllogshf.html

PHP:  class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwxasilm.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2aodoxjwj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wytgslqp.html

Java: class User {}
来源：http://dali.yueranfly.top/Article/details/gt2mfzawblr.html

Go:   type User struct { Name string }
来源：http://dali.cheryme.top/Article/details/gt2nbdeyzql.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gt2prfufryh.html

C#:   class User {}
来源：http://dali.havefunace.top/Article/details/gt2qtbssfrx.html

[G02] 构造函数
来源：http://dali.yj202588.top/Article/details/gt2hyudxtet.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhongyouzk.top/Article/details/gt2nepvyqcj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gt2vihktete.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gt2aulviuqb.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gt2yehkeboa.html

Java: User(String name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gt2czvjmvdi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yanxiufei.cn/Article/details/gt2pyuaopba.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gt2pmxxbgmz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.andypj.xyz/Article/details/gt2yonilcav.html

[G03] 实例属性
来源：http://dali.gogol.net.cn/Article/details/gt2ulixrrgu.html

Py:   self.name = "x"
来源：http://dali.mhx1999.top/Article/details/gt2bfnixmvi.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gt2paaheyqo.html

JS:   this.name = "x";
来源：http://dali.tian-w.cn/Article/details/gt2jaawwawi.html

TS:   name: string = "x";
来源：http://dali.yongpay.top/Article/details/gt2gxmnrlqy.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gt2chngueku.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxinkj.top/Article/details/gt2vbakmowo.html

Ruby: @name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gt2lnikojco.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2eytcjvom.html

[G04] 定义方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2ebpmbvzu.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gt2hfjscjhj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gt2yhwjzbfn.html

JS:   greet() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2yzviioms.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2zrayzbtb.html

Java: String greet() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2fcpiisdl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mqakurqi.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gt2ohsiyfql.html

C#:   public string Greet() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gt2ebcrpwrw.html

[G05] 继承
来源：http://dali.yanxiufei.cn/Article/details/gt2jzhfodot.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gt2perjzcnu.html

PHP:  class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2awqrqlii.html

JS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2zotvhrcb.html

TS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2ugumiyfu.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2iesluznw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.haohaochexian.top/Article/details/gt2rqbhdszd.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gt2uzkrclps.html

C#:   class Admin : User {}
来源：http://dali.c1oappe.top/Article/details/gt2enxgiwme.html

[G06] 重写方法
来源：http://dali.yj20258.top/Article/details/gt2fphatzzf.html

Py:   def greet(self): return "admin"
来源：http://dali.tianlin.xyz/Article/details/gt2mgcaqyrk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ptkhlvuu.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2njxasbrr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhejsfsp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2ccpwxkdb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daria6918.cn/Article/details/gt2wjppopim.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2icsmxlfi.html

C#:   public override string Greet() => "admin";
来源：http://dali.nwbrower.top/Article/details/gt2swmxcreg.html

[G07] 调用父类方法
来源：http://dali.ppjwa.cn/Article/details/gt2esraoiks.html

Py:   super().greet()
来源：http://dali.sxryk.cn/Article/details/gt2ghglektr.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2rdgimwsb.html

JS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2duirqeku.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gt2gvpohbzb.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2acphumeq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.quarkkingdee.top/Article/details/gt2cwxylmbf.html

Ruby: super
来源：http://dali.xziqi.cn/Article/details/gt2qjcnhefz.html

C#:   base.Greet();
来源：http://dali.yangfankeji.com/Article/details/gt2aydxeazz.html

[G08] 静态方法与属性
来源：http://dali.cdnleiting.top/Article/details/gt2vadoktfm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sufxvd.cn/Article/details/gt2ljhvlrgz.html

PHP:  public static function f() {}
来源：http://dali.jyoumei.cn/Article/details/gt2qfezbhyc.html

JS:   static f() {}
来源：http://dali.cucudq.cn/Article/details/gt2gzmifruq.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gt2waplhnll.html

Java: static void f() {}
来源：http://dali.hnxiangtu.top/Article/details/gt2dqofruyu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhiwuduotai.top/Article/details/gt2mwzxhcxo.html

Ruby: def self.f; end
来源：http://dali.kuanghao11.cn/Article/details/gt2wxqysvye.html

C#:   public static void F() {}
来源：http://dali.guannengcc.top/Article/details/gt2lrrfqegn.html

[G09] 接口 / 抽象类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ypziwsmy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jytdhqyc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gt2fzdsabql.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fengsongda.top/Article/details/gt2yxzmtola.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gt2pprexjtg.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gt2exzfeabw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gt2afaifldt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gt2mxcxhdjm.html

C#:   interface IShape { double Area(); }
来源：http://dali.guannengcc.top/Article/details/gt2giuxnqvq.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gt2azgybojn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fevntqzb.html

PHP:  public / protected / private
来源：http://dali.wangdashe.top/Article/details/gt2kskmczkd.html

JS:   #private 字段；其余公开
来源：http://dali.yuxming.cn/Article/details/gt2fptmnahf.html

TS:   public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2kelulsgo.html

Java: public / protected / private / 默认包级
来源：http://dali.vqdsnc.cn/Article/details/gt2kmrnexhv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.haohaochexian.top/Article/details/gt2chbfwxjs.html

Ruby: public / protected / private
来源：http://dali.pycfn.com/Article/details/gt2mgedywuv.html

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gt2nfnvlwli.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gt2bunanyob.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gt2mmnstmhd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gt2obhkpjbj.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gt2znucaltl.html

TS:   get name(): string { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gt2nkfgtwsl.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2qcyzfrkc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2ioahgihv.html

Ruby: attr_accessor :name
来源：http://dali.jqgufenzy.top/Article/details/gt2ztajhfjw.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gt2shmtdexh.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gt2qindnfsd.html

Py:   def __str__(self): return self.name
来源：http://dali.cucudq.cn/Article/details/gt2rmhnkmsp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gt2auszfqgs.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2gnmjxdow.html

TS:   toString(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2kzekxmis.html

Java: @Override public String toString() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2uruxbryw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gt2znlwjexp.html

Ruby: def to_s; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gt2ciryyalj.html

C#:   public override string ToString() => Name;
来源：http://dali.yonumen.top/Article/details/gt2ztwufcae.html

[G13] 判断对象类型
来源：http://dali.shuidangran.top/Article/details/gt2mlzrcsmm.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gt2svgyfipv.html

PHP:  $u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2hpqlgtdf.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vxtogpys.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2nfjfthnz.html

Java: u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gt2vhjsnjhx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xuetiantiany.cn/Article/details/gt2piiijmyq.html

Ruby: u.is_a?(User)
来源：http://dali.gogol.net.cn/Article/details/gt2knigheps.html

C#:   u is User
来源：http://dali.0kj1m.cn/Article/details/gt2mqgeuopq.html

[G14] 数据类 / record
来源：http://dali.cucudq.cn/Article/details/gt2ghgpngsk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhoulong.xyz/Article/details/gt2nzkxzjgc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gt2sitgtjym.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zycfv.cn/Article/details/gt2hughmlcc.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhoulong.xyz/Article/details/gt2rxfgrbuk.html

Java: record User(String name, int age) {}
来源：http://dali.dianchejie.cn/Article/details/gt2rppzcrfq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhoulong.xyz/Article/details/gt2ldxcvhxc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yongpay.top/Article/details/gt2wwhgkybn.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgfzy.top/Article/details/gt2phxggcut.html

[G15] 枚举
来源：http://dali.xinyue.icu/Article/details/gt2ajuwdjfk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjilzsw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsgyicng.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258888.top/Article/details/gt2hgaamskw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2jaeoyzsz.html

Java: enum Color { RED, GREEN }
来源：http://dali.tanke756.top/Article/details/gt2indfgjuw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gt2kexbltus.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangshuangyany.cn/Article/details/gt2gabycppc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2euickmxv.html

[G16] 对象转数组 / 字典
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uynkeqxy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.snrcjt.cn/Article/details/gt2guvfrnvz.html

PHP:  get_object_vars($obj);
来源：http://dali.yuanzhike.top/Article/details/gt2deuybkhr.html

JS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gt2xayslhsq.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2apomiyvw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gt2kxyqljux.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.bjfxy.top/Article/details/gt2yhxalalk.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gt2xgbmopzr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gt2fjrwtsqw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2zadcyfmp.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gt2dnpkslfx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2upkjizqf.html

[H01] try / catch 基础
来源：http://dali.hammf.cn/Article/details/gt2gdmvqanf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gt2woybrjxw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gt2edcbdgvb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gt2ysrhawtc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gt2kwgtmpeq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nanxinkj.top/Article/details/gt2bkiwcsjb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tian-w.cn/Article/details/gt2zpqqvttp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xziqi.cn/Article/details/gt2jwwamxlf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gogol.net.cn/Article/details/gt2obriczcu.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gt2xbpdqimd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.0kj1m.cn/Article/details/gt2kybngegq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2aqpopddb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2xajqsdmn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2lbclzsyh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2hxkkptgu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnxiangtu.top/Article/details/gt2vofloqmp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigfzy.top/Article/details/gt2ehwpravo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2bljmetnz.html

[H03] 主动抛出异常
来源：http://dali.shuidangran.top/Article/details/gt2qpfguxbq.html

Py:   raise ValueError("错误信息")
来源：http://dali.ybcxt.top/Article/details/gt2wbfuybew.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2tfxcaipu.html

JS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2jyptzona.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2cwfohhlh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2ixcyqvgj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tqmhjgda.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnqzz.top/Article/details/gt2ccmobbrs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2denpengi.html

[H04] 自定义异常类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xbtxlfnd.html

Py:   class MyError(Exception): pass
来源：http://dali.hammf.cn/Article/details/gt2ccktfnhn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gt2wdjhemls.html

JS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2mbnqibbl.html

TS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gt2qrlionqr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gt2itosehon.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxinkj.top/Article/details/gt2fszyjfim.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gt2jciictzu.html

C#:   class MyException : Exception {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oafzmrtp.html

[H05] 捕获特定类型
来源：http://dali.guannengcc.top/Article/details/gt2kjinoalq.html

Py:   except ValueError as e:
来源：http://dali.yangfankeji.com/Article/details/gt2tfpzrnna.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangdashe.top/Article/details/gt2hyxpfsdl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gt2zyzqlohm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gt2vuhxvsug.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cashguo.top/Article/details/gt2qycgetbo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.haohaochexian.top/Article/details/gt2gtvzohhv.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258.top/Article/details/gt2xrcyhcxm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.havefunace.top/Article/details/gt2rmwmhjcj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.feifeiyinyue.top/Article/details/gt2siiclogl.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dalrislb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gt2gchdclhw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gt2pjkcjjyk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gt2notvhxes.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.9152youxi.cn/Article/details/gt2pxtatiay.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gogol.net.cn/Article/details/gt2vegwlmxr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sweek.top/Article/details/gt2upmhiijn.html

C#:   obj?.A?.B ?? default
来源：http://dali.yonumen.top/Article/details/gt2vupcujog.html

[H07] 断言
来源：http://dali.cqqwz.cn/Article/details/gt2xpnyhwgq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gotoacloud.top/Article/details/gt2csupeqeg.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2axqulklc.html

JS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gt2ljzdthto.html

TS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gt2wuhsptoh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gt2iwezlxue.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhoulong.xyz/Article/details/gt2hewcszii.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.smart0.xyz/Article/details/gt2lphetqkw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhtffwdj.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2dpgnflch.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258.top/Article/details/gt2smtrujgk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gt2yhgbbort.html


<!-- 参考信息 -->