代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gt2vefkfacw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gt2yadijaph.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gt2ewwicegw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.316326.xyz/Article/details/gt2twcilqbh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.0kj1m.cn/Article/details/gt2xpqtibin.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jianghu66.top/Article/details/gt2inekqftr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gt2dhbzfuxg.html

[F04] 追加写入文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxlboqot.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.havefunace.top/Article/details/gt2vveaiqqh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zdqjudy.top/Article/details/gt2idsviciq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2okrkxtjg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gt2judyhzhc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.svipenyu.cn/Article/details/gt2znimnfrv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2ohebswls.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhengqikj.top/Article/details/gt2iwthmmtu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gt2acqxlual.html

[F05] 判断文件或目录是否存在
来源：http://dali.gzhubu.top/Article/details/gt2bgcgcups.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2loxzozbw.html

PHP:  file_exists("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2jajtknad.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2vfmyphhx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2nhyoqdfa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2tmwlhxqh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigufen.top/Article/details/gt2lbikewvh.html

Ruby: File.exist?("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2xjugjfty.html

C#:   File.Exists("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2wmxpueva.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2suheqifl.html

Py:   os.remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jatkwevq.html

PHP:  unlink("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2shstklqs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2tjmqprvr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uvvxnpgt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2dklursto.html

Go:   os.Remove("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2txasvsug.html

Ruby: File.delete("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2scvhgsxx.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xgbiqysy.html

[F07] 创建目录（含多级）
来源：http://dali.chenjidiqi.icu/Article/details/gt2oqoyxadd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gt2wgbpsjwh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenzaomai.com/Article/details/gt2pvjqudwo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gt2obfpmjeu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gt2tcjauhtw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guowangkeji.top/Article/details/gt2txjaqoav.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hammf.cn/Article/details/gt2yvimbuez.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangdashe.top/Article/details/gt2fojjqdbm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gotoacloud.top/Article/details/gt2wtntelyh.html

[F08] 遍历目录
来源：http://dali.daxiang520.top/Article/details/gt2owdmkhgh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nwbrower.top/Article/details/gt2ubhavhfx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnxiangtu.top/Article/details/gt2hrlwwqgb.html

JS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gt2shtlwcxb.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2mcrsyltu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gt2shiqdsgm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fzhhl.top/Article/details/gt2jzxnzbru.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bgjmnehp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuxming.cn/Article/details/gt2ziztvcvt.html

[F09] 获取文件大小
来源：http://dali.gogol.net.cn/Article/details/gt2zpqgzlyo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2clilclln.html

PHP:  filesize("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hpdaaafz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gt2bpmvbfiw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gt2ienwzqif.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gt2nrkhbqnt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.birdmap.top/Article/details/gt2pfgdyqdg.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2mqnffbrb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qiukavlg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ybcxt.top/Article/details/gt2ctqvjboa.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2vcahiepl.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2fbhaadrg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2uioqokcv.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2rahqaxvd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhixingplan.top/Article/details/gt2xhcmdosy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zcfhsiov.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gopayqrz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2zjpehsot.html

[F11] 复制与移动文件
来源：http://dali.hfpthk.cn/Article/details/gt2dchfsxju.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ibwephpo.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2gqssnqnl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2upnzdcks.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gt2jzkamipi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2hjnolznn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgufenzy.top/Article/details/gt2qzwdbuzq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2dapbjhsx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.svipenyu.cn/Article/details/gt2warzvxdb.html

[F12] CSV 读写
来源：http://dali.jyoumei.cn/Article/details/gt2aauxpocr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.meibo888.top/Article/details/gt2bnwcqprb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gt2yzmakxns.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gt2orljkkny.html

TS:   // 同上
来源：http://dali.iojbl.cn/Article/details/gt2vhryroyv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.fengsongda.top/Article/details/gt2trbocqwv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangshuangyany.cn/Article/details/gt2ubnqwkem.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shuidangran.top/Article/details/gt2grvtgmtt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ivvv.top/Article/details/gt2hiqqtchl.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2cdmqjftf.html

G. 面向对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2bdlthmgh.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2akybkhxl.html

[G01] 定义类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mwwexlkh.html

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gt2kdrbkzym.html

PHP:  class User {}
来源：http://dali.gotoacloud.top/Article/details/gt2bezdhykg.html

JS:   class User {}
来源：http://dali.mhx1999.top/Article/details/gt2eqwvbapb.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gt2mnjytqxp.html

Java: class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2jgqipsze.html

Go:   type User struct { Name string }
来源：http://dali.gaohongyu789.top/Article/details/gt2pchyipfh.html

Ruby: class User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kopqdunj.html

C#:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ydyequhz.html

[G02] 构造函数
来源：http://dali.pycfn.com/Article/details/gt2cqepwcob.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangshuangyany.cn/Article/details/gt2epvyrnox.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tianlin.xyz/Article/details/gt2mrwlafzh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjrcpay.html

TS:   constructor(public name: string) {}
来源：http://dali.cdnleiting.top/Article/details/gt2obtyayfu.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2zhjumvon.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.redwolf501.top/Article/details/gt2hcbcigbg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gt2elpxvwjr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yvedp.cn/Article/details/gt2lhhfhsnr.html

[G03] 实例属性
来源：http://dali.ydzc1.top/Article/details/gt2lbjxuwid.html

Py:   self.name = "x"
来源：http://dali.yj202588.top/Article/details/gt2xegzklfw.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2iiopqvma.html

JS:   this.name = "x";
来源：http://dali.ybcxt.top/Article/details/gt2bpbozbao.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2pltbugew.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gt2vhcvdues.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hammf.cn/Article/details/gt2qautxijv.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gt2jziulbxe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2oobchjrb.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gt2njhlbpys.html

Py:   def greet(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gt2sgvmtcxn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gt2skbabrjp.html

JS:   greet() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fubfyjzi.html

TS:   greet(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ooydsnfp.html

Java: String greet() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ugkpthdt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iegvnhju.html

Ruby: def greet; @name; end
来源：http://dali.pycfn.com/Article/details/gt2mudryfam.html

C#:   public string Greet() => Name;
来源：http://dali.ppjwa.cn/Article/details/gt2neffznec.html

[G05] 继承
来源：http://dali.yangfankeji.com/Article/details/gt2mlwuiypk.html

Py:   class Admin(User): pass
来源：http://dali.chenjidiqi.icu/Article/details/gt2gegxrhse.html

PHP:  class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2hgzcqxqy.html

JS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2wsqlxwiv.html

TS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gt2ffwtroek.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2thlomwik.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sufxvd.cn/Article/details/gt2ezqajblm.html

Ruby: class Admin < User; end
来源：http://dali.chenlongwang.top/Article/details/gt2idxsfzcg.html

C#:   class Admin : User {}
来源：http://dali.yangfankeji.com/Article/details/gt2ogqccbem.html

[G06] 重写方法
来源：http://dali.chenzaomai.com/Article/details/gt2gykkbfol.html

Py:   def greet(self): return "admin"
来源：http://dali.cdnleiting.top/Article/details/gt2fhavkadm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2hhkemkye.html

JS:   greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gt2xcemfrsb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2fxsvkavv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2wfkconlz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhhuilhf.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gt2jvvalyrs.html

C#:   public override string Greet() => "admin";
来源：http://dali.gaohongyu789.top/Article/details/gt2idfrucgi.html

[G07] 调用父类方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2jcrzdphk.html

Py:   super().greet()
来源：http://dali.hnqzz.top/Article/details/gt2quigvems.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gt2egocqitk.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2wocaontb.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gt2ounttnmp.html

Java: super.greet();
来源：http://dali.cucudq.cn/Article/details/gt2rcotkvvf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gt2atixyidk.html

Ruby: super
来源：http://dali.jinqigufen.top/Article/details/gt2pcfhzfum.html

C#:   base.Greet();
来源：http://dali.sufxvd.cn/Article/details/gt2icpouzfl.html

[G08] 静态方法与属性
来源：http://dali.sxryk.cn/Article/details/gt2emrndvyj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hywenlv.cn/Article/details/gt2ltbonwjb.html

PHP:  public static function f() {}
来源：http://dali.zhixingplan.top/Article/details/gt2ltlxiwvt.html

JS:   static f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2ycvbgdux.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gt2xwycirep.html

Java: static void f() {}
来源：http://dali.sxryk.cn/Article/details/gt2ubypnkmc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shzxlz.cn/Article/details/gt2tdyyioml.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gt2avhmsjjo.html

C#:   public static void F() {}
来源：http://dali.shuidangran.top/Article/details/gt2onvozyxo.html

[G09] 接口 / 抽象类
来源：http://dali.yj202588.top/Article/details/gt2ecbylmsh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gt2lfmqzyrb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zoevrkit.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aizwys.cn/Article/details/gt2nnhuvbgd.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gt2uqvmpwwy.html

Java: interface Shape { double area(); }
来源：http://dali.jianghu66.top/Article/details/gt2lpmhcelb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hammf.cn/Article/details/gt2fvztksae.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigufen.top/Article/details/gt2jpgsmrom.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenzaomai.com/Article/details/gt2capocbdl.html

[G10] 访问控制
来源：http://dali.zhixingplan.top/Article/details/gt2guhegrpr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yueranfly.top/Article/details/gt2ftykihaa.html

PHP:  public / protected / private
来源：http://dali.birdmap.top/Article/details/gt2vyxnnywm.html

JS:   #private 字段；其余公开
来源：http://dali.sysykeji.top/Article/details/gt2puhykkta.html

TS:   public / protected / private
来源：http://dali.ivvv.top/Article/details/gt2adzufyfx.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gt2ixvtafke.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnxiangtu.top/Article/details/gt2ktuyeouc.html

Ruby: public / protected / private
来源：http://dali.xylfe.cn/Article/details/gt2gbxudnll.html

C#:   public / protected / private / internal
来源：http://dali.birdmap.top/Article/details/gt2yzbaalef.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gt2rbpiibha.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gt2zjnbmrne.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gt2bapzoghr.html

JS:   get name() { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gt2mcwgvrdx.html

TS:   get name(): string { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gt2cukprntj.html

Java: public String getName() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2xlvpbiod.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gt2ogufykne.html

Ruby: attr_accessor :name
来源：http://dali.iojbl.cn/Article/details/gt2rgicdzzs.html

C#:   public string Name { get; set; }
来源：http://dali.ydzc1.top/Article/details/gt2joltpsds.html

[G12] 对象转字符串
来源：http://dali.cheryme.top/Article/details/gt2phhdfako.html

Py:   def __str__(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gt2mxkseejb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2hhbxtrik.html

JS:   toString() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kojjvjmy.html

TS:   toString(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gt2iytnvjtp.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjlnmwsl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2siaiboyr.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2prbdmlmo.html

C#:   public override string ToString() => Name;
来源：http://dali.havefunace.top/Article/details/gt2bapbmmoy.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gt2cdbbsfiv.html

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gt2zbaxedth.html

PHP:  $u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2pkyltnqy.html

JS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2lvwmpvmk.html

TS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2eymtlosy.html

Java: u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2eqbwmxya.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sweek.top/Article/details/gt2ipsdopst.html

Ruby: u.is_a?(User)
来源：http://dali.snrcjt.cn/Article/details/gt2kmdwarcx.html

C#:   u is User
来源：http://dali.jinqigfzy.top/Article/details/gt2hmuyhhkn.html

[G14] 数据类 / record
来源：http://dali.vqdsnc.cn/Article/details/gt2ukmdpocb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuanzx.com/Article/details/gt2mvpvpjbp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gt2oelmwzra.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.haohaochexian.top/Article/details/gt2cqsfdacs.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnxiangtu.top/Article/details/gt2wpanxyfa.html

Java: record User(String name, int age) {}
来源：http://dali.hfpthk.cn/Article/details/gt2qkszuhui.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jyoumei.cn/Article/details/gt2ialconbm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xziqi.cn/Article/details/gt2vghinext.html

C#:   record User(string Name, int Age);
来源：http://dali.zhongyouzk.top/Article/details/gt2xkuiwjyk.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gt2gntwtpwv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhongyouzk.top/Article/details/gt2xajzejbh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhixingplan.top/Article/details/gt2quryypew.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxuanxn.top/Article/details/gt2wixubcov.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2vqeldwsq.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigufen.top/Article/details/gt2pmjxjbrw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.vqdsnc.cn/Article/details/gt2oqmcmeld.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2egerjjob.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2bmqmzkis.html

[G16] 对象转数组 / 字典
来源：http://dali.jianghu66.top/Article/details/gt2wvqqcwqv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hongshengwenyu.top/Article/details/gt2bmsgiivz.html

PHP:  get_object_vars($obj);
来源：http://dali.fzhhl.top/Article/details/gt2vtdpfach.html

JS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gt2afbdldlu.html

TS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gt2ewvimqdx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxinkj.top/Article/details/gt2icunpmqo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tianlin.xyz/Article/details/gt2sbmydbtg.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gt2ldayaobq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gt2klickcea.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2rsuezlqc.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gt2idqkwako.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2kkuchaxo.html

[H01] try / catch 基础
来源：http://dali.iojbl.cn/Article/details/gt2gskjqbhi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.kuanghao11.cn/Article/details/gt2brroteov.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gt2bnvcnzcv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gt2kbdjagce.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gt2tpfciqah.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gt2rgqnychp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guannengcc.top/Article/details/gt2wlpmrjaq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yonumen.top/Article/details/gt2kgsgbgmw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.redwolf501.top/Article/details/gt2lhzirvws.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigufen.top/Article/details/gt2fzdbcwjt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hammf.cn/Article/details/gt2nbwzvaue.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2hnmwaceb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2ulxodzxa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2prgapfsj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2qbltuhju.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gt2lwvfbnxn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cucudq.cn/Article/details/gt2xokaffgt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2wqoncxwt.html

[H03] 主动抛出异常
来源：http://dali.zdqjudy.top/Article/details/gt2xwkhvhmv.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuanzhike.top/Article/details/gt2dkxigwgq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2njxhfdfx.html

JS:   throw new Error("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2prenvxvi.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2wfuivaxk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2gziephmf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.kuanghao11.cn/Article/details/gt2emmauewi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhoulong.xyz/Article/details/gt2lmcsrlal.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2dickuflm.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gt2beshlpxt.html

Py:   class MyError(Exception): pass
来源：http://dali.havefunace.top/Article/details/gt2ucoohbha.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gt2yywwttlq.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gt2sionwuta.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjwtxrmq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gt2rimxflld.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xylfe.cn/Article/details/gt2jayhdbke.html

Ruby: class MyError < StandardError; end
来源：http://dali.aibaodan.cn/Article/details/gt2gjvvrxkj.html

C#:   class MyException : Exception {}
来源：http://dali.dianchejie.cn/Article/details/gt2mcxgapfe.html

[H05] 捕获特定类型
来源：http://dali.yuanzhike.top/Article/details/gt2tvnovwsu.html

Py:   except ValueError as e:
来源：http://dali.snrcjt.cn/Article/details/gt2tupufvpy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gt2wuyhdasy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gt2dkqedrpt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gt2yvqejyod.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2wfghcgta.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cdnleiting.top/Article/details/gt2pvgruvyx.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gt2lfqnrypb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gzhubu.top/Article/details/gt2jcjgwfma.html

[H06] 可选值 / 空值安全访问
来源：http://dali.redwolf501.top/Article/details/gt2cmrgcdrm.html

Py:   value = d.get("k") or default
来源：http://dali.aibaodan.cn/Article/details/gt2aavfrwuw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gt2jilfqvkm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gt2osszdvam.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gt2xsuelots.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gt2jpzzzvwg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj202588.top/Article/details/gt2rgvyivqq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkareqs.html

C#:   obj?.A?.B ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gt2fgfiqenh.html

[H07] 断言
来源：http://dali.hywenlv.cn/Article/details/gt2xnmhwkiu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.vqdsnc.cn/Article/details/gt2dwlecndp.html

PHP:  assert($x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2ytuhnied.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2wrnunowe.html

TS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gyplaspq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhoulong.xyz/Article/details/gt2lygjtfat.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnxiangtu.top/Article/details/gt2eoufkoiq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxinkj.top/Article/details/gt2dqkxftyu.html


<!-- 参考信息 -->