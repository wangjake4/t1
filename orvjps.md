代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jiagoushi.top/Article/details/gt2ovfikduy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cashguo.top/Article/details/gt2crjrneut.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gt2qbnxetiz.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gt2rxulefzf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gt2llvkiijl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgfzy.top/Article/details/gt2qftupfrx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangdashe.top/Article/details/gt2glhtnaql.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gt2tydekmph.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gt2nvqzzopn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.mhx1999.top/Article/details/gt2nnbxsonh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jyoumei.cn/Article/details/gt2vhjccudx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guowangkeji.top/Article/details/gt2idtcwttp.html

[F05] 判断文件或目录是否存在
来源：http://dali.tianlin.xyz/Article/details/gt2lsxzetbt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.havefunace.top/Article/details/gt2imgabigx.html

PHP:  file_exists("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2kioersmd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2obuhwoaw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2wlskshrk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gt2zkjkpebi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shuidangran.top/Article/details/gt2ziaxgqab.html

Ruby: File.exist?("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2oywqfkmb.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2zvebyque.html

[F06] 删除文件
来源：http://dali.nwbrower.top/Article/details/gt2vqblgntk.html

Py:   os.remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2qofzpqfp.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvxqxmr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2edurctwt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qefjrnbh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gt2ejwktpon.html

Go:   os.Remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pkhrbtth.html

Ruby: File.delete("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2kimyktyu.html

C#:   File.Delete("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2ouvvubhy.html

[F07] 创建目录（含多级）
来源：http://dali.cheryme.top/Article/details/gt2fyqubeat.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gt2tzcbtgag.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttwcwxqr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gt2tmfufsrj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gt2xaockknl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fzhhl.top/Article/details/gt2isoaowat.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gt2hkrfhjzg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cdnleiting.top/Article/details/gt2vuwuilqq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gt2fkstsxpt.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gt2cogaggon.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yongpay.top/Article/details/gt2triidjaa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ydzc1.top/Article/details/gt2jeyxflbh.html

JS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gt2xxwwjbsh.html

TS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2hwtdvvql.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gt2luuteqnn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2jijquhia.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gt2kvwpdqze.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2wozznizn.html

[F09] 获取文件大小
来源：http://dali.andypj.xyz/Article/details/gt2yjschlyt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2dhmoxwnu.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mmvhvywa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gt2jrxcuath.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gt2hexrjlrv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2tlinxjvo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhongyouzk.top/Article/details/gt2dptcarma.html

Ruby: File.size("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2cbyrkmys.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangdashe.top/Article/details/gt2glnzaxwi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gt2ahmyqqff.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2ceyyafdx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2trvogjlz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2ukouhuku.html

TS:   path.extname("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2avwekxjq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yueranfly.top/Article/details/gt2ekkzkcgz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2kzkcytzg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2cyrucmyl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2idmbkjwz.html

[F11] 复制与移动文件
来源：http://dali.redwolf501.top/Article/details/gt2uvpbmgik.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2rrvrvlxv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.meibo888.top/Article/details/gt2jaduvdmg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gt2zhnygddz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gt2ywzhurms.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gt2hhpokgeg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnxiangtu.top/Article/details/gt2yjtpfrvg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gt2vpyakqjj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fengsongda.top/Article/details/gt2bqjmkktq.html

[F12] CSV 读写
来源：http://dali.yuanzhike.top/Article/details/gt2lfqwdxam.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dianchejie.cn/Article/details/gt2nhrmpqtx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vtrmizii.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hywenlv.cn/Article/details/gt2nztmcetg.html

TS:   // 同上
来源：http://dali.iojbl.cn/Article/details/gt2pxduptku.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.svipenyu.cn/Article/details/gt2plezolcr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rzctkwqp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daria6918.cn/Article/details/gt2izthzjyc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnqzz.top/Article/details/gt2bgdwjzci.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2hohkaqod.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gt2vjaxdyyj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2kereaips.html

[G01] 定义类
来源：http://dali.jlsjyb.cn/Article/details/gt2xmhzrjww.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gt2mszmjqao.html

PHP:  class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2onmfmjfa.html

JS:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btadfnyj.html

TS:   class User { name: string = ""; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2juxhoojn.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2ldhgnmir.html

Go:   type User struct { Name string }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hinupsyi.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gt2dfgezlnb.html

C#:   class User {}
来源：http://dali.ydzc1.top/Article/details/gt2mxymfkhw.html

[G02] 构造函数
来源：http://dali.cucudq.cn/Article/details/gt2bnpmzisv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangdashe.top/Article/details/gt2jkvwzuas.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zdqjudy.top/Article/details/gt2kwsxmpkh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gt2rtmfgcto.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gt2feyeaggh.html

Java: User(String name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gt2htewtmvo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258888.top/Article/details/gt2wlgmmsve.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gt2qnutzzaa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hfpthk.cn/Article/details/gt2tanqixqw.html

[G03] 实例属性
来源：http://dali.yj20258.top/Article/details/gt2ckhnngue.html

Py:   self.name = "x"
来源：http://dali.hfpthk.cn/Article/details/gt2dumxmlml.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2vobhhysp.html

JS:   this.name = "x";
来源：http://dali.hammf.cn/Article/details/gt2icbzsrrl.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gt2gktgkzej.html

Java: private String name;
来源：http://dali.jinqigufen.top/Article/details/gt2bbpaxorp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daxiang520.top/Article/details/gt2gcrrkppf.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gt2amroxskg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2vkjbpngj.html

[G04] 定义方法
来源：http://dali.andypj.xyz/Article/details/gt2vlwaostp.html

Py:   def greet(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gt2gqzfvsxu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gt2kgyqhudw.html

JS:   greet() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2fvtndnkh.html

TS:   greet(): string { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gt2psklipme.html

Java: String greet() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hqlagsgc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gt2ygpwbgjh.html

Ruby: def greet; @name; end
来源：http://dali.meibo888.top/Article/details/gt2gshakbfm.html

C#:   public string Greet() => Name;
来源：http://dali.dashuyun.cn/Article/details/gt2jauqvmuz.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gt2hvlrmgwr.html

Py:   class Admin(User): pass
来源：http://dali.yonumen.top/Article/details/gt2pbtfkqsh.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2lldopvso.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gt2bxtmknjw.html

TS:   class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2obudwjag.html

Java: class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2zostxwyh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gt2hjemxloe.html

Ruby: class Admin < User; end
来源：http://dali.jiagoushi.top/Article/details/gt2uesmrpvu.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gt2pthtfyjb.html

[G06] 重写方法
来源：http://dali.svipenyu.cn/Article/details/gt2kuagszkw.html

Py:   def greet(self): return "admin"
来源：http://dali.yvedp.cn/Article/details/gt2owyfgqvp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2njfyjcaz.html

JS:   greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2qwgvqieh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wpotvmhp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gt2yxwyhxtk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cqqwz.cn/Article/details/gt2ymeeewat.html

Ruby: def greet; "admin"; end
来源：http://dali.zhixingplan.top/Article/details/gt2jlmohbgh.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigufen.top/Article/details/gt2antoldtr.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gt2boratzcu.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gt2rnrbdasu.html

PHP:  parent::greet();
来源：http://dali.andypj.xyz/Article/details/gt2dxrrvxre.html

JS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gt2spomvnts.html

TS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gt2ohmomqdw.html

Java: super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2knpqymiv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gt2phjwdivd.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gt2givigrhh.html

C#:   base.Greet();
来源：http://dali.jianghu66.top/Article/details/gt2hplladeq.html

[G08] 静态方法与属性
来源：http://dali.birdmap.top/Article/details/gt2ihzblcxe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yvedp.cn/Article/details/gt2jexsginy.html

PHP:  public static function f() {}
来源：http://dali.hywenlv.cn/Article/details/gt2kdqmnnjl.html

JS:   static f() {}
来源：http://dali.guannengcc.top/Article/details/gt2lyttgyej.html

TS:   static f(): void {}
来源：http://dali.pycfn.com/Article/details/gt2osruxtkb.html

Java: static void f() {}
来源：http://dali.fzhhl.top/Article/details/gt2mwnhehdb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuetiantiany.cn/Article/details/gt2rvofwxsd.html

Ruby: def self.f; end
来源：http://dali.chenlongwang.top/Article/details/gt2kdydmnzi.html

C#:   public static void F() {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2qlqrgrwf.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpgbhyf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dzjmufql.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yvedp.cn/Article/details/gt2clgvzvjx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnqzz.top/Article/details/gt2ujkwpinb.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gt2tgmtqmiz.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmekmkaj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258.top/Article/details/gt2uxxywohg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hfpthk.cn/Article/details/gt2hvcuroyy.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kdfjpdoh.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gt2ilqktlne.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tian-w.cn/Article/details/gt2amjwlgdv.html

PHP:  public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gt2aasudpmy.html

JS:   #private 字段；其余公开
来源：http://dali.tanke756.top/Article/details/gt2ncjuuqsz.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gt2qiublcxq.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gwqgxshv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jianghu66.top/Article/details/gt2cwhcvfzr.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2duqhtwbe.html

C#:   public / protected / private / internal
来源：http://dali.cqqwz.cn/Article/details/gt2tzqehxzh.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gt2gtqeycdz.html

Py:   @property 与 @x.setter
来源：http://dali.guannengcc.top/Article/details/gt2lmakajfa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gt2cddacqhr.html

JS:   get name() { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2lrqptedv.html

TS:   get name(): string { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gt2aqylwuum.html

Java: public String getName() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2xfadzziv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gt2taxlnqzq.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gt2fjuctuqz.html

C#:   public string Name { get; set; }
来源：http://dali.xuanzx.com/Article/details/gt2xgiwekth.html

[G12] 对象转字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2gbtswlif.html

Py:   def __str__(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gt2eqcjnwjx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2opebzazs.html

JS:   toString() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2acmvongk.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2iomwzafo.html

Java: @Override public String toString() { return name; }
来源：http://dali.birdmap.top/Article/details/gt2krjraxbh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2ghtnqavr.html

Ruby: def to_s; @name; end
来源：http://dali.havefunace.top/Article/details/gt2mphmzcxy.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gt2oqqcmcup.html

[G13] 判断对象类型
来源：http://dali.sxryk.cn/Article/details/gt2qpcidxwx.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gt2uiwtjpkg.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2szsbfwto.html

JS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2vaqrgflo.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2lxrzwgsr.html

Java: u instanceof User
来源：http://dali.sysykeji.top/Article/details/gt2nzsnfart.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yongpay.top/Article/details/gt2sqsgfkdx.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gt2wllhrinv.html

C#:   u is User
来源：http://dali.andypj.xyz/Article/details/gt2zbqbbnrx.html

[G14] 数据类 / record
来源：http://dali.nanxinkj.top/Article/details/gt2xojieego.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangshuangyany.cn/Article/details/gt2fvdpnqju.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.bjfxy.top/Article/details/gt2vvqqagwb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.meibo888.top/Article/details/gt2xnpjkqui.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gt2ekjabtwu.html

Java: record User(String name, int age) {}
来源：http://dali.yueranfly.top/Article/details/gt2lcauusyv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cashguo.top/Article/details/gt2nsnjwuxv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxinkj.top/Article/details/gt2qfpooobd.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxinkj.top/Article/details/gt2yashxzol.html

[G15] 枚举
来源：http://dali.hywenlv.cn/Article/details/gt2zbcbqnex.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xinyue.icu/Article/details/gt2gwejmyxv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2apuvcutf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guowangkeji.top/Article/details/gt2siqvexql.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gt2ntbamrhd.html

Java: enum Color { RED, GREEN }
来源：http://dali.jianghu66.top/Article/details/gt2zhvlooxx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xylfe.cn/Article/details/gt2apodvmea.html

Ruby: Color = %i[red green].freeze
来源：http://dali.0kj1m.cn/Article/details/gt2qvuptvdc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ufsyrnfc.html

[G16] 对象转数组 / 字典
来源：http://dali.yangfankeji.com/Article/details/gt2yzyqgpck.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tanke756.top/Article/details/gt2cjfbsnzb.html

PHP:  get_object_vars($obj);
来源：http://dali.dashuyun.cn/Article/details/gt2ayzsnuki.html

JS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gt2ujltygqu.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pazkgjtl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ehwqpu.com/Article/details/gt2svttmhkb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guannengcc.top/Article/details/gt2rixorkol.html

Ruby: obj.instance_variables
来源：http://dali.jqgfzy.top/Article/details/gt2unuyyrtp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gt2pruksgkr.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2ihechvex.html

H. 异常与错误处理
来源：http://dali.zhongyouzk.top/Article/details/gt2ocwonzux.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctsgrsqd.html

[H01] try / catch 基础
来源：http://dali.gotoacloud.top/Article/details/gt2sorygiad.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhengqikj.top/Article/details/gt2ecznisut.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gt2jzigqnsw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2slmlaiss.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gt2vqjwmire.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gt2lcjzmgmv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2imzjjsat.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gogol.net.cn/Article/details/gt2grffntbd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cqqwz.cn/Article/details/gt2twcufadp.html

[H02] finally / ensure 收尾
来源：http://dali.jqgufenzy.top/Article/details/gt2iqqgaorj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yueranfly.top/Article/details/gt2vkptdvak.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2wqwycnpw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2yffcfetj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2hximjqqy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2gwwgkimw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hywenlv.cn/Article/details/gt2mimuqusv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fzhhl.top/Article/details/gt2negnkmco.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2spgrfqbc.html

[H03] 主动抛出异常
来源：http://dali.xylfe.cn/Article/details/gt2rmrqxtpu.html

Py:   raise ValueError("错误信息")
来源：http://dali.quarkkingdee.top/Article/details/gt2urjkvgfv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2dgyadqky.html

JS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2zsurovxy.html

TS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2wijjivfk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2tarkcjry.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.iojbl.cn/Article/details/gt2tosmyebb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.snrcjt.cn/Article/details/gt2ldtykumo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2ywyucfge.html

[H04] 自定义异常类型
来源：http://dali.iojbl.cn/Article/details/gt2habcwspw.html

Py:   class MyError(Exception): pass
来源：http://dali.pycfn.com/Article/details/gt2cndikily.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gt2mnszypub.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gt2heagesyk.html

TS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gt2mjkqvvdx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gt2qhetuwai.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhengqikj.top/Article/details/gt2ikpifosm.html

Ruby: class MyError < StandardError; end
来源：http://dali.jianghu66.top/Article/details/gt2kgozczmk.html

C#:   class MyException : Exception {}
来源：http://dali.gaohongyu789.top/Article/details/gt2iasiddop.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gt2fierlmiy.html

Py:   except ValueError as e:
来源：http://dali.yvedp.cn/Article/details/gt2wdsafqcl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gzhubu.top/Article/details/gt2amftygch.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gt2khwhrnru.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqbwidhv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guannengcc.top/Article/details/gt2qtdmfohg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sxryk.cn/Article/details/gt2mbgruapj.html

Ruby: rescue ArgumentError => e
来源：http://dali.bjfxy.top/Article/details/gt2qwdbhgim.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tianlin.xyz/Article/details/gt2exrqferx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnqzz.top/Article/details/gt2wioxfyhy.html

Py:   value = d.get("k") or default
来源：http://dali.chenzaomai.com/Article/details/gt2wxcbrfms.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gt2lcadljvc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gt2rgxnjfzc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gt2lqtzhlmk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xylfe.cn/Article/details/gt2txxlrwsm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jlsjyb.cn/Article/details/gt2jkokgyao.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2axojdxbn.html

C#:   obj?.A?.B ?? default
来源：http://dali.shzxlz.cn/Article/details/gt2nxzpmljv.html

[H07] 断言
来源：http://dali.chenlongwang.top/Article/details/gt2ndrqxvqc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ivvv.top/Article/details/gt2ihoprhjb.html

PHP:  assert($x > 0);
来源：http://dali.birdmap.top/Article/details/gt2swthfdyn.html

JS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2titrmqdw.html

TS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2prjdaskh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jianghu66.top/Article/details/gt2gpqgmugv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuetiantiany.cn/Article/details/gt2rcdloede.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dianchejie.cn/Article/details/gt2eofkgczo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gt2kuqtvjic.html

[H08] 获取错误信息与堆栈
来源：http://dali.c1oappe.top/Article/details/gt2wzpxhwuk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenlongwang.top/Article/details/gt2wpwbvlqo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ehwqpu.com/Article/details/gt2cjezmwtc.html


<!-- 参考信息 -->